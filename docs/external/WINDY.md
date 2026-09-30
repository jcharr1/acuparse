# Acuparse Windy Updater Guide

Acuparse uploads to Windy using the [Windy Stations API v2](https://stations.windy.com/api-reference).

## Registration

1. Go to [https://community.windy.com/register](https://community.windy.com/register) and fill out the form.
1. Agree to the data collection policy.
1. Visit [https://stations.windy.com/stations](https://stations.windy.com/stations) and add a new station.
1. Open your station and go to the **Connection** tab to find your `Station ID` and `Station Password`.

## Configuration

1. Change enabled to true.
1. Add your Windy `Station ID` and `Station Password` from the station's **Connection** tab.
1. Optionally, add your public Windy `ID`. It is only used for the Windy link in the navigation menu.

## Upgrading from Acuparse 3.9.4 or earlier

Windy's v1 API shuts down at the end of 2026. The v1 `API Key` and numeric station index are not used by v2, so the
upgrade clears them and disables Windy updates. Enter your `Station ID` and `Station Password`, then re-enable Windy.

## Webcam

1. Visit [https://www.windy.com/webcams/add](https://www.windy.com/webcams/add) and add a new camera.
    1. Page URL = `http(s)://<yourip/domain>/camera`
    1. Image URL = `http(s)://<yourip/domain>/img/cam/latest.jpg`
