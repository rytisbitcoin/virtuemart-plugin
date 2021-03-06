# VirtueMart CoinGate Plugin

CoinGate bitcoin payment gateway VirtueMart plugin.


## Install

You can sign up for CoinGate account at https://coingate.com for production and https://sandbox.coingate.com for testing (sandbox) environment.

### via Extension Manager

1. Download [coingate-virtuemart-1.0.0.zip](https://github.com/coingate/virtuemart-plugin/releases/download/v1.0.0/coingate-virtuemart-1.0.0.zip)

2. In admin panel, go to *Extensions » Extension Manager » Install* in *Upload Package File* block choose **coingate-virtuemart.zip** from your computer, then click **Upload & Install**.

3. Enable CoinGate payment extension: In admin panel, go to *Extensions » Extension Manager » Manage*.
In search box type **CoinGate** and click **Search**. Either click on status indicator located in CoinGate extensions row, or check checkbox of CoinGate extension row and click **Enable** at the top of admin panel.

4. Setup CoinGate payment extension: In admin panel, go to *VirtueMart » Payment Methods » New*. Type in the information, selecting **VM Payment - CoinGate** as **Payment Method**. Be sure to select **Yes** in the publish section. Click **Save**. Click **Configuration**. Fill in *App ID*, *API Key*, *API Secret* from CoinGate and choose *CoinGate Environment* depending on where you created your API credentials(https://coingate.com - Live and https://sandbox.coingate.com - Sandbox). Select **Receive Currency**. Please note by selecting *EUR* or *USD* we will require you to verify your account (*BTC* does not require verification). **Be sure to set order statuses correctly**. Click **Save & Close**.
