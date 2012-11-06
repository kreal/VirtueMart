Copyright (C) 2012 by Kris

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

About
	Bitcoin payment via walletbit.com for VirtueMart.

Version 0.1
	
System Requirements:
	WalletBit.com account
	VirtueMart
	PHP 5+
	Curl PHP Extension
  
Configuration Instructions:
	1. Got to Extension Manager: Install
	2. Browse and select zip file, click Upload & Install.
	3. Go to Manage, and find the plugin, click on publish.
	4. Go to Components -> VirtueMart and click on Payment Methods.
	5. Go to your WalletBit account and set IPN URL to: https://YOUR_SITE/index.php?option=com_virtuemart&view=pluginresponse&task=pluginnotification&tmpl=component in Business Tools
	6. Click New. and type in the information, selecting VMPAYMENT_WALLETBIT as Payment Method.
	7. Click Configuration in the Tab menu, and input your details from WalletBit.com.