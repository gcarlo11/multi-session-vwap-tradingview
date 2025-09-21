# Anchored VWAP for Market Sessions

This script implements an Anchored Volume Weighted Average Price (VWAP) indicator tailored for different market sessions, allowing traders to visualize volume-weighted pricing throughout the trading day.

## Features

- **Anchored VWAP Calculation**: Computes the VWAP for specified market sessions.
- **Session Colors**: Customizable colors for each market session.
- **Band Overlay**: Option to display upper and lower bands around the VWAP based on a specified multiplier.

## Supported Market Sessions

- Sydney
- Tokyo
- London
- New York
- Custom (User-defined session times)

## Installation

To use this script, follow these steps:

1. Open the TradingView platform.
2. Navigate to the Pine Editor.
3. Copy and paste the script into the Pine Editor.
4. Add the script to your chart.

## Configuration

The following inputs can be customized:

- **Source Price**: Select the price source (default is HLC3).
- **Session Offset**: Define the offset for the plotted values.
- **Enable Band Overlay**: Toggle the display of upper and lower VWAP bands.
- **Band Multiplier**: Set the multiplier for the VWAP bands.
- **Session Activation**: Toggle the activation of various market sessions (Sydney, Tokyo, London, New York, Custom).
- **Custom Session Time**: Define start and end times for a custom session.

## Color Customization

You can adjust the color settings for each session in the script using predefined color options. Each market session has its assigned color to enhance visibility.

## Example Usage

Once added to your chart, the Anchored VWAP indicator will visually represent the VWAP and its bands for the selected sessions, adapting dynamically to the market times. Use this information to make informed trading decisions based on historical volume-weighted averages.

## License

This script is licensed under the Mozilla Public License 2.0. For more information, see [Mozilla Public License 2.0](https://mozilla.org/MPL/2.0/).

## Disclaimer

Trading involves significant risk and is not suitable for every investor. The information contained in this script is for educational purposes only and should not be construed as financial advice.

---

Feel free to reach out for any questions or contributions regarding this script!
