# 🧩 Size Chart Popup for WooCommerce

If you're running a WooCommerce store and struggling to show size charts on your product pages — this plugin is for you!

This lightweight, customizable plugin allows you to easily display a **"View Size Chart"** button on single product pages. Clicking the button opens a popup showing the size chart you've set using the `WPC Product Size Chart for WooCommerce` plugin.


 ✨ Features

- Adds a **modern "View Size Chart"** button after the Add to Cart button
- Clean **popup modal** for better user experience
- Fully **compatible** with [WPC Product Size Chart for WooCommerce](https://wordpress.org/plugins/wpc-size-chart/)
- Easy to **customize** styling and layout
- Minimal code, no bloat


 🛠️ Installation

1. **Download** the latest version of the plugin ZIP from [Releases]().
2. In your WordPress dashboard, go to `Plugins → Add New → Upload Plugin`.
3. Upload the `size-chart-popup.zip` file and click **Install Now**.
4. After installation, click **Activate Plugin**.


 🚀 How to Use

1. Install and configure the [WPC Product Size Chart for WooCommerce](https://wordpress.org/plugins/wpc-size-chart/) plugin.
2. Create a new size chart inside it and copy the shortcode (e.g. `[wpcsc id='2925']`).
3. Open the plugin file (`size-chart-popup.php`) and update the following line:
   ```php
   define( 'WPC_SIZE_CHART_SHORTCODE', "[wpcsc id='2925']" );
