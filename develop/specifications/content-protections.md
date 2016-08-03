This is an informational reference for the DRM formats and the HDCP versions supporte dby the Roku OS

_<strong>note:</strong>_ To use Adobe DRM with HLS streams, a channel must include the _requires&lowbar;aaxs&lowbar;drm_ entry in the manifest file. See the <a href="https://sdkdocs.roku.com/display/sdkdoc/Manifest+File#ManifestFile-ManifestDRMAttributes"><b>Manifest File</b></a> page for details.

<h2>DRM</h2>
Although AES-128 Encryption is also supported for HLS, Roku recommends using Adobe DRM because there is no DRM when using AES-128 Encryption.
<table class="confluenceTable tablesorter tablesorter-default"><thead><tr class="tablesorter-headerRow"><th class="confluenceTh sortableHeader" data-column="0" tabindex="0" unselectable="on"><div class="tablesorter-header-inner">&nbsp;</div></th><th class="confluenceTh sortableHeader" data-column="1" tabindex="0" unselectable="on"><div class="tablesorter-header-inner">PlayReady</div></th><th class="confluenceTh sortableHeader" data-column="2" tabindex="0" unselectable="on"><div class="tablesorter-header-inner">Adobe DRM</div></th><th class="confluenceTh sortableHeader" data-column="3" tabindex="0" unselectable="on"><div class="tablesorter-header-inner">AES-128</div></th></tr></thead><tbody><tr><td class="confluenceTd"><strong>HLS</strong></td><td class="confluenceTd">&nbsp;</td><td style="text-align: center;" class="confluenceTd">X</td><td style="text-align: center;" class="confluenceTd">X</td></tr><tr><td class="confluenceTd"><strong>Smooth</strong></td><td style="text-align: center;" class="confluenceTd">X</td><td class="confluenceTd">&nbsp;</td><td class="confluenceTd">&nbsp;</td></tr><tr><td colspan="1" class="confluenceTd"><strong>DASH</strong></td><td colspan="1" style="text-align: center;" class="confluenceTd">X</td><td colspan="1" class="confluenceTd">&nbsp;</td><td colspan="1" class="confluenceTd">&nbsp;</td></tr></tbody></table>

<h2>Copy Protection</h2>
Roku's OS also supports HDCP for content copy protection between the Roku player's HDMI port and the connected display; however, the version of HDCP depends on the Roku Models in the table below.
<table class="confluenceTable tablesorter tablesorter-default"><thead><tr class="tablesorter-headerRow"><th class="confluenceTh sortableHeader" data-column="0" tabindex="0" unselectable="on"><div class="tablesorter-header-inner">&nbsp;</div></th><th class="confluenceTh sortableHeader" data-column="1" tabindex="0" unselectable="on"><div class="tablesorter-header-inner">HDCP 1.1</div></th><th class="confluenceTh sortableHeader" data-column="2" tabindex="0" unselectable="on"><div class="tablesorter-header-inner">HDCP 1.3</div></th><th class="confluenceTh sortableHeader" data-column="3" tabindex="0" unselectable="on"><div class="tablesorter-header-inner">HDCP 1.4</div></th><th colspan="1" class="confluenceTh sortableHeader" data-column="4" tabindex="0" unselectable="on"><div class="tablesorter-header-inner">HDCP 2.2</div></th></tr></thead><tbody><tr><td colspan="1" class="confluenceTd">Roku TV [4K] (6000X)</td><td colspan="1" class="confluenceTd">&nbsp;</td><td colspan="1" class="confluenceTd">&nbsp;</td><td colspan="1" style="text-align: center;" class="confluenceTd">&nbsp;</td><td colspan="1" style="text-align: center;" class="confluenceTd">X</td></tr><tr><td colspan="1" class="confluenceTd">Roku TV (5000X)</td><td colspan="1" class="confluenceTd">&nbsp;</td><td colspan="1" class="confluenceTd">&nbsp;</td><td colspan="1" style="text-align: center;" class="confluenceTd">X</td><td colspan="1" class="confluenceTd">&nbsp;</td></tr><tr><td colspan="1" class="confluenceTd">Roku 4 (4400X)</td><td colspan="1" class="confluenceTd">&nbsp;</td><td colspan="1" class="confluenceTd">&nbsp;</td><td colspan="1" class="confluenceTd">&nbsp;</td><td colspan="1" style="text-align: center;" class="confluenceTd">X</td></tr><tr><td colspan="1" class="confluenceTd">Roku 3 (4200X)</td><td colspan="1" class="confluenceTd">&nbsp;</td><td colspan="1" style="text-align: center;" class="confluenceTd">X</td><td colspan="1" class="confluenceTd">&nbsp;</td><td colspan="1" class="confluenceTd">&nbsp;</td></tr><tr><td colspan="1" class="confluenceTd">Roku 3 [US] (4230X)</td><td colspan="1" class="confluenceTd">&nbsp;</td><td colspan="1" style="text-align: center;" class="confluenceTd">X</td><td colspan="1" class="confluenceTd">&nbsp;</td><td colspan="1" class="confluenceTd">&nbsp;</td></tr><tr><td colspan="1" class="confluenceTd">Roku 2 [US] (4210X)</td><td colspan="1" class="confluenceTd">&nbsp;</td><td colspan="1" style="text-align: center;" class="confluenceTd">X</td><td colspan="1" class="confluenceTd">&nbsp;</td><td colspan="1" class="confluenceTd">&nbsp;</td></tr><tr><td colspan="1" class="confluenceTd">Roku Streaming Stick [2014] (3500X)</td><td colspan="1" style="text-align: center;" class="confluenceTd">X</td><td colspan="1" class="confluenceTd">&nbsp;</td><td colspan="1" class="confluenceTd">&nbsp;</td><td colspan="1" class="confluenceTd">&nbsp;</td></tr><tr><td colspan="1" class="confluenceTd">Roku Streaming Stick [2012] (3400X)</td><td colspan="1" style="text-align: center;" class="confluenceTd">X</td><td colspan="1" class="confluenceTd">&nbsp;</td><td colspan="1" class="confluenceTd">&nbsp;</td><td colspan="1" class="confluenceTd">&nbsp;</td></tr><tr><td class="confluenceTd">Roku LT (2700X)</td><td class="confluenceTd">&nbsp;</td><td class="confluenceTd">&nbsp;</td><td style="text-align: center;" class="confluenceTd">X</td><td colspan="1" class="confluenceTd">&nbsp;</td></tr><tr><td class="confluenceTd">Roku 1 (2710X)</td><td class="confluenceTd">&nbsp;</td><td class="confluenceTd">&nbsp;</td><td style="text-align: center;" class="confluenceTd">X</td><td colspan="1" class="confluenceTd">&nbsp;</td></tr><tr><td colspan="1" class="confluenceTd">Roku 2 (2720X)</td><td colspan="1" class="confluenceTd">&nbsp;</td><td colspan="1" class="confluenceTd">&nbsp;</td><td colspan="1" style="text-align: center;" class="confluenceTd">X</td><td colspan="1" class="confluenceTd">&nbsp;</td></tr></tbody></table>