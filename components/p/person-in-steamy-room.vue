<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><circle fill="url(#iOokUYv)" class="r_bcr-ntk"/><circle fill="url(#ig6gRjd)" class="r_bcr-ntk"/><circle fill="url(#ifqCFkS)" class="iksuiqrgf"/><circle fill="url(#igczLIe)" transform="matrix(-1 0 0 1 21.326 16.165)" class="qnar36wle"/><circle fill="url(#iE9wJUA)" transform="matrix(-1 0 0 1 21.326 16.165)" class="qnar36wle"/><circle fill="url(#iiFjNse)" transform="matrix(-1 0 0 1 23.725 23.368)" class="n5l_opbqq"/><path fill="url(#i4UUWGe)" class="w8e9izb-y"/><path fill="url(#iFqMHgd)" class="w8e9izb-y"/><path fill="url(#iS6d3Rd)" class="w8e9izb-y"/><path fill="url(#i7GTaad)" class="rgs-6fbpw"/><path fill="url(#iU0xveW)" class="rgs-6fbpw"/><path class="lr6p412xr"/><path fill="url(#iJvbFZb)" class="gt-y46nru"/><path fill="url(#iMrfvye)" class="gt-y46nru"/><path fill="url(#ip742Bh)" class="gt-y46nru"/><path fill="url(#izyBClb)" class="gt-y46nru"/><path fill="url(#irX7roe)" class="gt-y46nru"/><path fill="url(#iB984Kc)" class="gt-y46nru"/><path class="dk0gm-byq"/><path fill="url(#i1Dor5L)" class="s6ufut5ul"/><path fill="url(#iv6Yn7W)" class="s6ufut5ul"/><path fill="url(#i4wIgAd)" class="s6ufut5ul"/><g filter="url(#iovtKcC)"><path class="sftxd4bwi"/><path fill="url(#il56jMe)" class="r_ngogb8h"/><path fill="url(#iRKJ5Zc)" class="r_ngogb8h"/></g><path class="wkmk90b2p"/><path fill="url(#i6lC7Ie)" class="dzzblgbkk"/><path fill="url(#igb4kne)" class="dzzblgbkk"/><path fill="url(#iib0wXd)" class="o6xvgfbag"/><path fill="url(#i2Hknqd)" class="o6xvgfbag"/><g filter="url(#i9vdf7H)"><path fill="url(#iBQDvre)" class="bcysn-2dp"/></g><path fill="url(#i6Zmsye)" class="bcysn-2dp"/><path fill="url(#ifK24Xb)" class="bcysn-2dp"/><path fill="url(#i0720Kc)" class="bcysn-2dp"/><path fill="url(#ijBouec)" class="bcysn-2dp"/><g filter="url(#iRpqtFb)"><path class="jndyf3b1j"/></g><g filter="url(#i76e0lc)"><path fill="url(#iODQEUb)" class="ncinfabic"/><path fill="url(#iH9U0pd)" class="ncinfabic"/><path fill="url(#iTIV5Vd)" class="ncinfabic"/><path fill="url(#iPStjWQ)" class="ncinfabic"/></g><g filter="url(#ibsuOHd)"><path stroke="url(#i5bbSbU)" class="c0n_1e4xo"/></g><path fill="url(#iEcKAae)" class="ixuhftnfj"/><g filter="url(#iohxfUd)"><path fill="url(#i2Cl93i)" class="rf4ocecah"/><path fill="url(#iSJ7tIc)" class="rf4ocecah"/><path fill="url(#i5QhaEb)" class="rf4ocecah"/><path fill="url(#ieCazMb)" class="rf4ocecah"/><path fill="url(#iDGdkic)" class="rf4ocecah"/></g><g filter="url(#iNtEiNd)"><path class="uxis8ac7p"/></g><g filter="url(#irnCRJb)"><path class="nh78fwb9x"/></g><g filter="url(#i2096Gb)"><path fill="url(#ix1CRIM)" class="yisb3abxj"/><path fill="url(#ihCDnbb)" class="yisb3abxj"/></g><g filter="url(#iK3Rnpd)"><path fill="url(#iCOpPvb)" class="tg3b212mk"/><path fill="url(#iU235Kc)" class="tg3b212mk"/><path fill="url(#iKZzfjO)" class="tg3b212mk"/><path fill="url(#iGjPFhb)" class="tg3b212mk"/><path fill="url(#i7Gyjfe)" class="tg3b212mk"/></g><path class="z5cogrbuu"/><path fill="url(#iDrDeeb)" class="h8yun6bzf"/><path class="yr9ecnbfu"/><g filter="url(#iLLRjMb)"><path class="qxm7upzvb"/><path fill="url(#i2gI1vq)" class="vymdidolh"/></g><g filter="url(#iKrC1Dc)"><path fill="url(#ioOOdeR)" class="jnsde6bol"/></g><path class="r7448c-_n"/><path fill="url(#ie8wKkd)" class="vhbqh4bkl"/><path class="lg0qaxtoc"/><g filter="url(#iwlQMkc)"><path fill="url(#iCB9ard)" class="mj5tuchat"/></g><g filter="url(#i27gPte)"><ellipse transform="rotate(-27.914 13.431 9.881)" class="bbc53ib4x"/><ellipse fill="url(#iuMRlDK)" transform="rotate(-27.914 13.431 9.881)" class="opgnw5bhs"/></g><path fill="url(#iBQrPeu)" class="oelmv7boz"/><path fill="url(#iMaa35c)" class="oelmv7boz"/><path fill="url(#itmGFGe)" class="oelmv7boz"/><path fill="url(#i6LIaVb)" class="r3829sbqp"/><path fill="url(#i5XA6ve)" class="r3829sbqp"/><g filter="url(#i3fzt9c)"><path class="wekziilbz"/></g><g filter="url(#ibabsmc)"><path class="b8scnnr9i"/></g><g filter="url(#iv0Bwjd)"><path class="hf5cwvb0n"/></g><g filter="url(#iirtdHe)"><path class="ogrm9vynh"/></g><defs><radialGradient id="iOokUYv" cx="0" cy="0" r="1" gradientTransform="matrix(3.59375 -2.4375 2.72822 4.02238 6.877 17.33)" gradientUnits="userSpaceOnUse"><stop class="dgu6o60tg"/><stop offset="1" class="n_p-4bbbu"/></radialGradient><radialGradient id="ig6gRjd" cx="0" cy="0" r="1" gradientTransform="matrix(-.01562 -1.76562 2.48224 -.02197 8.596 17.83)" gradientUnits="userSpaceOnUse"><stop offset=".384" class="v6wds2dtn"/><stop offset="1" class="nz8ufunsm"/></radialGradient><radialGradient id="ifqCFkS" cx="0" cy="0" r="1" gradientTransform="matrix(-5.47138 9.4622 -7.02133 -4.05998 10.46 19.268)" gradientUnits="userSpaceOnUse"><stop class="qc0o5_36v"/><stop offset="1" class="snymmbrnj"/></radialGradient><radialGradient id="igczLIe" cx="0" cy="0" r="1" gradientTransform="rotate(44.444 -1.585 1.225)scale(4.68833)" gradientUnits="userSpaceOnUse"><stop class="qc07hnbjk"/><stop offset=".836" class="b_5radckw"/></radialGradient><radialGradient id="iE9wJUA" cx="0" cy="0" r="1" gradientTransform="matrix(-.03125 -1.59375 5.11385 -.10027 2.316 5.313)" gradientUnits="userSpaceOnUse"><stop offset=".201" class="vze8wny8i"/><stop offset="1" class="o4sg_vbnc"/></radialGradient><radialGradient id="iiFjNse" cx="0" cy="0" r="1" gradientTransform="matrix(4.95236 7.33803 -10.65664 7.19205 1.352 1.24)" gradientUnits="userSpaceOnUse"><stop offset=".192" class="r8td-ob5s"/><stop offset=".819" class="eegxz98yy"/></radialGradient><radialGradient id="i4UUWGe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.35939 5.78125 -6.81223 -1.6018 23.096 22.58)" gradientUnits="userSpaceOnUse"><stop class="yf3t3eb5f"/><stop offset="1" class="a66gbwbzh"/></radialGradient><radialGradient id="i7GTaad" cx="0" cy="0" r="1" gradientTransform="matrix(6.87457 8.07189 -11.19707 9.5362 6.418 22.32)" gradientUnits="userSpaceOnUse"><stop class="pbkzvtx_w"/><stop offset="1" class="ykdcls_lk"/></radialGradient><radialGradient id="iJvbFZb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.18749 3.03127 -6.31539 -6.64086 13.752 16.392)" gradientUnits="userSpaceOnUse"><stop offset=".208" class="k3qin7bzy"/><stop offset="1" class="x3axlob0n"/></radialGradient><radialGradient id="ip742Bh" cx="0" cy="0" r="1" gradientTransform="matrix(-4.82764 -11.66358 1.58185 -.65474 15.958 28.962)" gradientUnits="userSpaceOnUse"><stop class="z2ddyab4m"/><stop offset="1" class="cqgvl433q"/></radialGradient><radialGradient id="irX7roe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.37282 -3.155 .92095 -.40073 16.346 27.58)" gradientUnits="userSpaceOnUse"><stop class="h3e5alaje"/><stop offset="1" class="u4bo2-o9a"/></radialGradient><radialGradient id="iB984Kc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.15863 -1.17796 1.62432 -1.59766 14.336 18.515)" gradientUnits="userSpaceOnUse"><stop offset=".328" class="gyulks50m"/><stop offset="1" class="atms-xm-n"/></radialGradient><radialGradient id="iv6Yn7W" cx="0" cy="0" r="1" gradientTransform="matrix(2.01563 -.67188 .83418 2.50254 17.502 18.33)" gradientUnits="userSpaceOnUse"><stop offset=".374" class="k-y64ibbx"/><stop offset="1" class="pjzr3aclu"/></radialGradient><radialGradient id="i4wIgAd" cx="0" cy="0" r="1" gradientTransform="rotate(110.875 2.49 18.294)scale(11.8396 2.00952)" gradientUnits="userSpaceOnUse"><stop class="bc2qs9bhj"/><stop offset="1" class="ktoycacxm"/></radialGradient><radialGradient id="il56jMe" cx="0" cy="0" r="1" gradientTransform="matrix(.28857 2.5 -5.28986 .6106 15.596 16.204)" gradientUnits="userSpaceOnUse"><stop offset=".377" class="jx0b83u0h"/><stop offset="1" class="yu9sk6b5g"/></radialGradient><radialGradient id="iRKJ5Zc" cx="0" cy="0" r="1" gradientTransform="matrix(1.8125 1.75 -2.19025 2.26847 13.158 17.204)" gradientUnits="userSpaceOnUse"><stop offset=".275" class="yhlucbb6c"/><stop offset="1" class="t79-6ab5u"/></radialGradient><radialGradient id="i6lC7Ie" cx="0" cy="0" r="1" gradientTransform="rotate(103.169 6.024 14.415)scale(3.82897 4.54852)" gradientUnits="userSpaceOnUse"><stop offset=".043" class="xitcw8bap"/><stop offset="1" class="by5wrxbms"/></radialGradient><radialGradient id="igb4kne" cx="0" cy="0" r="1" gradientTransform="rotate(53.902 -1.558 26.394)scale(.49786 .42293)" gradientUnits="userSpaceOnUse"><stop class="ke8n9wjsm"/><stop offset="1" class="iav904f4q"/></radialGradient><radialGradient id="iib0wXd" cx="0" cy="0" r="1" gradientTransform="matrix(1.33305 3.92345 -1.7834 .60594 10.336 11.952)" gradientUnits="userSpaceOnUse"><stop class="b9qaylb2c"/><stop offset="1" class="gz8haxb3i"/></radialGradient><radialGradient id="i2Hknqd" cx="0" cy="0" r="1" gradientTransform="rotate(72.29 -2.676 13.5)scale(1.04691 .91836)" gradientUnits="userSpaceOnUse"><stop offset=".263" class="n8euy9vjg"/><stop offset=".977" class="z8auuww1t"/></radialGradient><radialGradient id="iBQDvre" cx="0" cy="0" r="1" gradientTransform="matrix(-5.22785 0 0 -9.24801 18.692 10.893)" gradientUnits="userSpaceOnUse"><stop class="wbf-2ib5u"/><stop offset="1" class="r2t9jab3e"/></radialGradient><radialGradient id="i6Zmsye" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.75 18.478 0 15.69 17.61)" gradientUnits="userSpaceOnUse"><stop class="g1vv_3t4w"/><stop offset="1" class="yhtyhvpuw"/></radialGradient><radialGradient id="ifK24Xb" cx="0" cy="0" r="1" gradientTransform="matrix(-.40256 6.10192 -2.24332 -.148 21.042 10.661)" gradientUnits="userSpaceOnUse"><stop offset=".39" class="swgfs-c3o"/><stop offset="1" class="lppsh4wvc"/></radialGradient><radialGradient id="i0720Kc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.41386 1.70221 0 13.793 9.712)" gradientUnits="userSpaceOnUse"><stop offset=".276" class="u7o3559vd"/><stop offset="1" class="kbjuoc3rc"/></radialGradient><radialGradient id="ijBouec" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.53524 1.99125 0 18.373 9.3)" gradientUnits="userSpaceOnUse"><stop offset=".178" class="bija72usz"/><stop offset="1" class="wwr7m_5oe"/></radialGradient><radialGradient id="i5bbSbU" cx="0" cy="0" r="1" gradientTransform="rotate(-60.732 19.482 -5.503)scale(.7101 2.06639)" gradientUnits="userSpaceOnUse"><stop class="ninpi-65y"/><stop offset="1" class="bjbw-ir7e"/></radialGradient><radialGradient id="iEcKAae" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.72074 2.89971 0 15.884 14.432)" gradientUnits="userSpaceOnUse"><stop class="g3hjbil2k"/><stop offset="1" class="iazz9lb4s"/></radialGradient><radialGradient id="iSJ7tIc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.71897 10.1329 0 10.655 9.311)" gradientUnits="userSpaceOnUse"><stop offset=".315" class="ven54yrxx"/><stop offset="1" class="wrlksbcrj"/></radialGradient><radialGradient id="i5QhaEb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.63265 6.43634 0 20.745 9.311)" gradientUnits="userSpaceOnUse"><stop class="hlw3e_blf"/><stop offset="1" class="wxscdbbqi"/></radialGradient><radialGradient id="ieCazMb" cx="0" cy="0" r="1" gradientTransform="matrix(-4.10651 -1.44082 .76733 -2.187 19.99 3.035)" gradientUnits="userSpaceOnUse"><stop offset=".347" class="c6y_tcclg"/><stop offset="1" class="bn4a00sgu"/></radialGradient><radialGradient id="iDGdkic" cx="0" cy="0" r="1" gradientTransform="matrix(.90511 1.475 -3.4154 2.09581 14.98 1.442)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="iadv6taec"/><stop offset="1" class="m3om6jjzt"/></radialGradient><radialGradient id="ix1CRIM" cx="0" cy="0" r="1" gradientTransform="matrix(-3.80692 1.37358 -.3823 -1.05955 16.138 2.885)" gradientUnits="userSpaceOnUse"><stop class="ppo1r9bcz"/><stop offset="1" class="ijcelgbiw"/></radialGradient><radialGradient id="ihCDnbb" cx="0" cy="0" r="1" gradientTransform="rotate(-57.724 12.161 -5.661)scale(6.02662 6.67687)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="ltb-itmtt"/><stop offset=".233" class="pq3-kbbbz"/><stop offset="1" class="s-nb5j24l"/></radialGradient><radialGradient id="iCOpPvb" cx="0" cy="0" r="1" gradientTransform="rotate(13.307 -7.584 85.624)scale(3.4792 1.94581)" gradientUnits="userSpaceOnUse"><stop class="cnfyfo5ds"/><stop offset="1" class="ysruzhx-p"/></radialGradient><radialGradient id="iU235Kc" cx="0" cy="0" r="1" gradientTransform="rotate(-120.119 12.998 -1.727)scale(4.28181 2.38793)" gradientUnits="userSpaceOnUse"><stop class="cneetrb1a"/><stop offset="1" class="p82f5nbfd"/></radialGradient><radialGradient id="iKZzfjO" cx="0" cy="0" r="1" gradientTransform="rotate(-120.695 12.573 -1.63)scale(2.56111 1.83441)" gradientUnits="userSpaceOnUse"><stop offset=".394" class="zrke-tbre"/><stop offset="1" class="pgiiwpbet"/></radialGradient><radialGradient id="iGjPFhb" cx="0" cy="0" r="1" gradientTransform="matrix(-4.79843 1.1512 -1.2445 -5.18728 20.678 3.928)" gradientUnits="userSpaceOnUse"><stop offset=".735" class="o1l86cbis"/><stop offset="1" class="ygp8qdbik"/></radialGradient><radialGradient id="i7Gyjfe" cx="0" cy="0" r="1" gradientTransform="matrix(-.11733 .38373 -1.75436 -.53643 19.337 3.803)" gradientUnits="userSpaceOnUse"><stop offset=".461" class="o0qinnbwl"/><stop offset="1" class="ec7yarbjj"/></radialGradient><radialGradient id="iDrDeeb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.29049 0 18.066 9.977)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="i2gI1vq" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 11.383 .662)scale(.37829 .52081)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ie8wKkd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81136 -1.29056 0 13.702 9.977)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iuMRlDK" cx="0" cy="0" r="1" gradientTransform="matrix(-.00774 -.49408 .59392 -.0093 13.416 10.196)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iMaa35c" cx="0" cy="0" r="1" gradientTransform="matrix(.62855 2.24328 -2.14025 .59968 20.502 9.99)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="vr5749b_g"/><stop offset="1" class="r9kx25b9b"/></radialGradient><radialGradient id="itmGFGe" cx="0" cy="0" r="1" gradientTransform="matrix(.78778 -1.0811 .90618 .66032 20.862 10.535)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="a8tdckb6o"/><stop offset="1" class="mfa5gim3o"/></radialGradient><radialGradient id="i5XA6ve" cx="0" cy="0" r="1" gradientTransform="rotate(101.248 1.142 9.438)scale(2.11668 2.08089)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="bqhcerb-b"/><stop offset="1" class="g54wl109l"/></radialGradient><filter id="iovtKcC" width="6.879" height="10.938" x="12.32" y="16.517" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.917647 0 0 0 0 0.552941 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_776"/></filter><filter id="i9vdf7H" width="10.72" height="12.542" x="10.821" y="4.722" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.823529 0 0 0 0 0.623529 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_776"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.980392 0 0 0 0 0.54902 0 0 0 0 0.0941176 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_776" result="effect2_innerShadow_4002_776"/></filter><filter id="iRpqtFb" width="3.877" height="4.9" x="13.738" y="9.069" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_776" stdDeviation=".5"/></filter><filter id="i76e0lc" width="2.077" height="3.1" x="14.846" y="9.773" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_776" stdDeviation=".05"/></filter><filter id="ibsuOHd" width="3.718" height="1.573" x="14.025" y="13.193" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_776" stdDeviation=".05"/></filter><filter id="iohxfUd" width="12.873" height="8.357" x="9.448" y="1.546" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.945098 0 0 0 0 0.509804 0 0 0 0 0.0627451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_776"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.862745 0 0 0 0 0.486275 0 0 0 0 0.0470588 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_776" result="effect2_innerShadow_4002_776"/></filter><filter id="iNtEiNd" width="2.339" height="1.19" x="17.474" y="7.209" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.603922 0 0 0 0 0.243137 0 0 0 0 0.152941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_776"/></filter><filter id="irnCRJb" width="2.339" height="1.176" x="12.217" y="7.224" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.603922 0 0 0 0 0.243137 0 0 0 0 0.152941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_776"/></filter><filter id="i2096Gb" width="6.584" height="5.992" x="9.803" y="2.635" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_776" stdDeviation=".125"/></filter><filter id="iK3Rnpd" width="6.361" height="5.736" x="15.725" y="3.164" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_776" stdDeviation=".125"/></filter><filter id="iLLRjMb" width=".787" height=".696" x="17.332" y="9.537" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_776" stdDeviation=".05"/></filter><filter id="iKrC1Dc" width=".891" height=".913" x="18.172" y="9.612" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_776" stdDeviation=".1"/></filter><filter id="iwlQMkc" width=".986" height="1.04" x="13.729" y="9.549" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_776" stdDeviation=".1"/></filter><filter id="i27gPte" width=".913" height=".705" x="12.974" y="9.529" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_776" stdDeviation=".05"/></filter><filter id="i3fzt9c" width="1.329" height="2.379" x="9.852" y="9.445" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_776" stdDeviation=".125"/></filter><filter id="ibabsmc" width="1.447" height="2.403" x="20.596" y="9.429" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_776" stdDeviation=".125"/></filter><filter id="iv0Bwjd" width="2.405" height="1.16" x="12.136" y="7.299" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_776" stdDeviation=".125"/></filter><filter id="iirtdHe" width="2.405" height="1.16" x="17.415" y="7.252" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_776" stdDeviation=".125"/></filter><linearGradient id="iFqMHgd" x1="24.158" x2="24.189" y1="30.329" y2="26.673" gradientUnits="userSpaceOnUse"><stop offset=".078" class="npfrbd3jd"/><stop offset="1" class="w_5-rbc1a"/></linearGradient><linearGradient id="iS6d3Rd" x1="18.12" x2="19.472" y1="27.765" y2="28.151" gradientUnits="userSpaceOnUse"><stop class="p5jt_ib0l"/><stop offset="1" class="hw19_ybat"/></linearGradient><linearGradient id="iU0xveW" x1="13.658" x2="12.158" y1="28.736" y2="29.267" gradientUnits="userSpaceOnUse"><stop class="h65uoi6pi"/><stop offset="1" class="g04ogacjt"/></linearGradient><linearGradient id="iMrfvye" x1="12.315" x2="13.69" y1="27.392" y2="26.829" gradientUnits="userSpaceOnUse"><stop offset=".223" class="d05zivoho"/><stop offset="1" class="ue2ywxbfs"/></linearGradient><linearGradient id="izyBClb" x1="15.627" x2="14.221" y1="30.173" y2="29.486" gradientUnits="userSpaceOnUse"><stop offset=".208" class="cu8bl7b6w"/><stop offset="1" class="bkwavzmor"/></linearGradient><linearGradient id="i1Dor5L" x1="16.002" x2="18.033" y1="24.829" y2="25.736" gradientUnits="userSpaceOnUse"><stop class="ego3-fbwo"/><stop offset="1" class="up5p4s41k"/></linearGradient><linearGradient id="iODQEUb" x1="15.884" x2="16.739" y1="11.722" y2="11.722" gradientUnits="userSpaceOnUse"><stop class="kc3wm8i6w"/><stop offset="1" class="st3dxnbfu"/></linearGradient><linearGradient id="iH9U0pd" x1="14.812" x2="15.886" y1="11.566" y2="11.625" gradientUnits="userSpaceOnUse"><stop class="abomb1boi"/><stop offset="1" class="pvsu__x5y"/><stop offset="1" class="ig7uz4g5n"/></linearGradient><linearGradient id="iTIV5Vd" x1="15.884" x2="15.884" y1="12.12" y2="12.972" gradientUnits="userSpaceOnUse"><stop class="pvsu__x5y"/><stop offset=".845" class="ag8lyyc-n"/></linearGradient><linearGradient id="iPStjWQ" x1="15.884" x2="15.884" y1="9.873" y2="10.292" gradientUnits="userSpaceOnUse"><stop class="zav_leb7s"/><stop offset="1" class="l5m23db_l"/></linearGradient><linearGradient id="i2Cl93i" x1="21.248" x2="11.124" y1="5.23" y2="5.23" gradientUnits="userSpaceOnUse"><stop class="r37rgng3f"/><stop offset="1" class="gcsbsh2mh"/></linearGradient><linearGradient id="ioOOdeR" x1="18.844" x2="18.53" y1="10.03" y2="10.224" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iCB9ard" x1="14.446" x2="14.132" y1="10.031" y2="10.224" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iBQrPeu" x1="22.321" x2="21.114" y1="10.057" y2="12.234" gradientUnits="userSpaceOnUse"><stop class="dxsnshbck"/><stop offset="1" class="eihs-teph"/></linearGradient><linearGradient id="i6LIaVb" x1="10.035" x2="11.493" y1="10.761" y2="10.634" gradientUnits="userSpaceOnUse"><stop class="a9f7swmqb"/><stop offset="1" class="jr2wmk3hc"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-in-steamy-room" /></template>
<style>
.a66gbwbzh {
  stop-color: var(--svg-color--f65c3e, #F65C3E);
}

.a8tdckb6o {
  stop-color: var(--svg-color--ffbd22, #FFBD22);
}

.a9f7swmqb {
  stop-color: var(--svg-color--e39726, #E39726);
}

.abomb1boi {
  stop-color: var(--svg-color--f49f22, #F49F22);
}

.ag8lyyc-n {
  stop-color: var(--svg-color--e88830, #E88830);
}

.atms-xm-n {
  stop-color: var(--svg-color--9e2625, #9E2625);
  stop-opacity: 0;
}

.b_5radckw {
  stop-color: var(--svg-color--f2e8f1, #F2E8F1);
}

.b8scnnr9i {
  fill: var(--svg-color--ffc837, #FFC837);
  d: path("M20.846 11.583q.059-.952.11-1.904a.955.955 0 0 1-.11 1.904");
}

.b9qaylb2c {
  stop-color: var(--svg-color--d57a26, #D57A26);
}

.bbc53ib4x {
  cx: 13.431px;
  cy: 9.881px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.bc2qs9bhj {
  stop-color: var(--svg-color--ff7347, #FF7347);
}

.bcysn-2dp {
  d: path("M11.06 13.658a3.916 3.916 0 0 0 3.885 3.406h1.887a3.916 3.916 0 0 0 3.886-3.406c.117-1.884.236-3.76.324-5.643a1.45 1.45 0 0 0-1.38-1.432h-1.4a2.42 2.42 0 0 1-2.211-1.443a.66.66 0 0 0-.615-.418h-1.273c-1.846 0-3.342 1.512-3.342 3.379c0 1.86.117 3.691.239 5.557");
}

.bija72usz {
  stop-color: var(--svg-color--ffbe3a, #FFBE3A);
}

.bjbw-ir7e {
  stop-color: var(--svg-color--ffb534, #FFB534);
  stop-opacity: 0;
}

.bkwavzmor {
  stop-color: var(--svg-color--dd5022, #DD5022);
  stop-opacity: 0;
}

.bn4a00sgu {
  stop-color: var(--svg-color--ffe639, #FFE639);
  stop-opacity: 0;
}

.bqhcerb-b {
  stop-color: var(--svg-color--c77937, #C77937);
  stop-opacity: 0;
}

.by5wrxbms {
  stop-color: var(--svg-color--e26839, #E26839);
}

.c0n_1e4xo {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M14.534 13.395c.39.203.855.32 1.35.32c.501 0 .961-.117 1.351-.32a.23.23 0 0 1 .272.044a.214.214 0 0 1 .023.272m-2.996-.316l2.934.275m-2.934-.275h-.001a.23.23 0 0 0-.271.046a.21.21 0 0 0-.023.271m.295-.317l-.233.275m3.23.041l-.063-.04m.062.04l-.062-.04m.062.04c-.348.528-.955.88-1.646.88c-.69 0-1.297-.351-1.645-.879m3.229-.042a1.9 1.9 0 0 1-1.584.846a1.9 1.9 0 0 1-1.583-.846m-.062.042l.062-.042m-.062.042l.062-.042");
}

.c6y_tcclg {
  stop-color: var(--svg-color--ffe639, #FFE639);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cneetrb1a {
  stop-color: var(--svg-color--eb8f29, #EB8F29);
}

.cnfyfo5ds {
  stop-color: var(--svg-color--ffeb3b, #FFEB3B);
}

.cqgvl433q {
  stop-color: var(--svg-color--f47246, #F47246);
  stop-opacity: 0;
}

.cu8bl7b6w {
  stop-color: var(--svg-color--dd5022, #DD5022);
}

.d05zivoho {
  stop-color: var(--svg-color--e45c36, #E45C36);
}

.dgu6o60tg {
  stop-color: var(--svg-color--e1dae6, #E1DAE6);
}

.dk0gm-byq {
  fill: var(--svg-color--ec551b, #EC551B);
  d: path("M21.82 17.353c-.641-1.313-1.82-1.75-2.594-1.75h-2.61v2.875h2.47c.168.303.002.85-.102 1.086l-3.939 10.39h3.176c1.068-2.583 2.995-7.817 3.383-8.742c.42-1.004.81-2.476.216-3.86");
}

.dxsnshbck {
  stop-color: var(--svg-color--ffe343, #FFE343);
}

.dzzblgbkk {
  d: path("M20.746 12.143a1.64 1.64 0 0 0 .904-.309v.931c0 .893-.532 1.689-1.34 2.02c.17-.363.287-.759.345-1.18z");
}

.ec7yarbjj {
  stop-color: var(--svg-color--ffce3c, #FFCE3C);
  stop-opacity: 0;
}

.eegxz98yy {
  stop-color: var(--svg-color--dac9f0, #DAC9F0);
}

.ego3-fbwo {
  stop-color: var(--svg-color--ce3b1b, #CE3B1B);
}

.eihs-teph {
  stop-color: var(--svg-color--ffc136, #FFC136);
}

.ft5dv1b6b {
  fill: none;
}

.g04ogacjt {
  stop-color: var(--svg-color--d63c26, #D63C26);
  stop-opacity: 0;
}

.g1vv_3t4w {
  stop-color: var(--svg-color--ef8508, #EF8508);
}

.g3hjbil2k {
  stop-color: var(--svg-color--89014e, #89014E);
}

.g54wl109l {
  stop-color: var(--svg-color--c77937, #C77937);
}

.gcsbsh2mh {
  stop-color: var(--svg-color--d29935, #D29935);
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.gt-y46nru {
  d: path("M9.9 17.353c.641-1.313 1.82-1.75 2.594-1.75h2.61v2.875h-2.47c-.168.303-.002.85.102 1.086l4.317 10.39h-3.176c-1.068-2.583-3.292-7.817-3.68-8.742c-.42-1.004-.89-2.476-.297-3.86");
}

.gyulks50m {
  stop-color: var(--svg-color--9e2625, #9E2625);
}

.gz8haxb3i {
  stop-color: var(--svg-color--d06a3c, #D06A3C);
}

.h3e5alaje {
  stop-color: var(--svg-color--c03005, #C03005);
}

.h65uoi6pi {
  stop-color: var(--svg-color--d63c26, #D63C26);
}

.h8yun6bzf {
  d: path("M18.068 9.5a.892.892 0 0 1 .86 1.127h-1.724a.896.896 0 0 1 .864-1.128");
}

.hf5cwvb0n {
  stroke: var(--svg-color--c96953, #C96953);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M12.511 8.084c.257-.185.898-.509 1.655-.382");
}

.hlw3e_blf {
  stop-color: var(--svg-color--ffb52a, #FFB52A);
}

.hw19_ybat {
  stop-color: var(--svg-color--e04438, #E04438);
  stop-opacity: 0;
}

.iadv6taec {
  stop-color: var(--svg-color--f3c130, #F3C130);
}

.iav904f4q {
  stop-color: var(--svg-color--e18c2a, #E18C2A);
  stop-opacity: 0;
}

.iazz9lb4s {
  stop-color: var(--svg-color--87004d, #87004D);
}

.ig7uz4g5n {
  stop-color: var(--svg-color--f49f22, #F49F22);
  stop-opacity: 0;
}

.ijcelgbiw {
  stop-color: var(--svg-color--ffdc2b, #FFDC2B);
  stop-opacity: 0;
}

.iksuiqrgf {
  cx: 8.275px;
  cy: 23.368px;
  r: 6.305px;
}

.ixuhftnfj {
  d: path("M15.885 13.79c-.508 0-.985-.12-1.386-.329c-.137-.07-.284.085-.198.21c.335.507.919.845 1.583.845c.665 0 1.249-.338 1.584-.846c.086-.13-.061-.279-.198-.209a3 3 0 0 1-1.386.329");
}

.jndyf3b1j {
  fill: var(--svg-color--ee9020, #EE9020);
  d: path("m15.398 10.374l-.635 1.838c-.108.379.152.757.52.757h.787c.369 0 .63-.384.52-.757l-.53-1.838c-.115-.407-.543-.407-.662 0");
}

.jnsde6bol {
  d: path("M18.863 10.275a.84.84 0 0 0-.231-.463l-.26.285l.117.228z");
}

.jr2wmk3hc {
  stop-color: var(--svg-color--d9851d, #D9851D);
}

.jx0b83u0h {
  stop-color: var(--svg-color--f58d27, #F58D27);
}

.k-y64ibbx {
  stop-color: var(--svg-color--99201f, #99201F);
}

.k3qin7bzy {
  stop-color: var(--svg-color--b22307, #B22307);
}

.kbjuoc3rc {
  stop-color: var(--svg-color--f59632, #F59632);
  stop-opacity: 0;
}

.kc3wm8i6w {
  stop-color: var(--svg-color--ffc92f, #FFC92F);
}

.ke8n9wjsm {
  stop-color: var(--svg-color--e18c2a, #E18C2A);
}

.ktoycacxm {
  stop-color: var(--svg-color--f6682e, #F6682E);
  stop-opacity: 0;
}

.l5m23db_l {
  stop-color: var(--svg-color--fac137, #FAC137);
  stop-opacity: 0;
}

.lg0qaxtoc {
  fill: var(--svg-color--000, #000);
  d: path("M14.211 10.392a.51.51 0 0 0-.51-.511a.51.51 0 0 0-.455.746h.904a.5.5 0 0 0 .061-.235");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lppsh4wvc {
  stop-color: var(--svg-color--ffd930, #FFD930);
  stop-opacity: 0;
}

.lr6p412xr {
  fill: var(--svg-color--ed561d, #ED561D);
  d: path("M9.9 17.353c.641-1.313 1.82-1.75 2.594-1.75h2.61v2.875h-2.47c-.168.303-.002.85.102 1.086l4.317 10.39h-3.176c-1.068-2.583-3.292-7.817-3.68-8.742c-.42-1.004-.89-2.476-.297-3.86");
}

.ltb-itmtt {
  stop-color: var(--svg-color--d67227, #D67227);
}

.m3om6jjzt {
  stop-color: var(--svg-color--f3c130, #F3C130);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mfa5gim3o {
  stop-color: var(--svg-color--ffbd22, #FFBD22);
  stop-opacity: 0;
}

.mj5tuchat {
  d: path("M14.516 10.287c0-.288-.235-.48-.298-.538l-.289.278l.178.362z");
}

.n_p-4bbbu {
  stop-color: var(--svg-color--e6dee6, #E6DEE6);
}

.n5l_opbqq {
  r: 6.305px;
}

.n8euy9vjg {
  stop-color: var(--svg-color--be691e, #BE691E);
}

.ncinfabic {
  d: path("m15.502 10.178l-.531 1.839c-.109.378.152.756.52.756h.787c.368 0 .629-.384.52-.756l-.531-1.839c-.114-.407-.646-.407-.765 0");
}

.nh78fwb9x {
  fill: var(--svg-color--c05029, #C05029);
  d: path("M12.474 7.804a2.77 2.77 0 0 1 1.739-.36a.277.277 0 1 1-.068.551a2.22 2.22 0 0 0-1.387.285a1 1 0 0 0-.091.06l-.003.002a.277.277 0 0 1-.34-.438z");
}

.ninpi-65y {
  stop-color: var(--svg-color--ffb534, #FFB534);
}

.npfrbd3jd {
  stop-color: var(--svg-color--dd3537, #DD3537);
}

.nz8ufunsm {
  stop-color: var(--svg-color--dad4de, #DAD4DE);
  stop-opacity: 0;
}

.o0qinnbwl {
  stop-color: var(--svg-color--ffce3c, #FFCE3C);
}

.o1l86cbis {
  stop-color: var(--svg-color--f29415, #F29415);
  stop-opacity: 0;
}

.o4sg_vbnc {
  stop-color: var(--svg-color--e8dee9, #E8DEE9);
  stop-opacity: 0;
}

.o6xvgfbag {
  d: path("M11.023 12.143a1.64 1.64 0 0 1-.905-.309v.931c0 .893.532 1.689 1.341 2.02a4.1 4.1 0 0 1-.346-1.18z");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oelmv7boz {
  d: path("M20.806 12.234q.1-1.595.185-3.192a1.61 1.61 0 0 1-.185 3.192");
}

.ogrm9vynh {
  stroke: var(--svg-color--c96953, #C96953);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M19.445 8.038c-.257-.185-.897-.51-1.655-.382");
}

.opgnw5bhs {
  cx: 13.431px;
  cy: 9.881px;
  rx: 0.39px;
  ry: 0.197px;
}

.p5jt_ib0l {
  stop-color: var(--svg-color--e04438, #E04438);
}

.p82f5nbfd {
  stop-color: var(--svg-color--eb8f29, #EB8F29);
  stop-opacity: 0;
}

.pbkzvtx_w {
  stop-color: var(--svg-color--e06d3d, #E06D3D);
}

.pgiiwpbet {
  stop-color: var(--svg-color--e48421, #E48421);
  stop-opacity: 0;
}

.pjzr3aclu {
  stop-color: var(--svg-color--d03d1c, #D03D1C);
  stop-opacity: 0;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.ppo1r9bcz {
  stop-color: var(--svg-color--ffdd30, #FFDD30);
}

.pq3-kbbbz {
  stop-color: var(--svg-color--ef8a23, #EF8A23);
}

.pvsu__x5y {
  stop-color: var(--svg-color--e88830, #E88830);
  stop-opacity: 0;
}

.qc07hnbjk {
  stop-color: var(--svg-color--fbf7ff, #FBF7FF);
}

.qc0o5_36v {
  stop-color: var(--svg-color--e0d6e3, #E0D6E3);
}

.qnar36wle {
  r: 4.086px;
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qxm7upzvb {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.003 9.688c.063.085-.07.189-.22.302c-.152.113-.264.192-.328.107c-.063-.085.008-.245.159-.358s.325-.136.389-.05");
}

.r_bcr-ntk {
  cx: 10.674px;
  cy: 16.165px;
  r: 4.086px;
}

.r_ngogb8h {
  d: path("M14.01 16.517h4v.887c.01.175.045.374.152.53a.8.8 0 0 0 .446.333l.464.164c.076.068.22.478.04.984c-.181.505-2.043 5.51-3.094 8.02v.02l-.004-.01l-.005.01v-.02c-1.052-2.51-3.139-7.515-3.32-8.02c-.18-.506-.122-.87-.046-.937l.68-.192c.218-.062.373-.14.515-.347c.113-.166.158-.39.172-.572z");
}

.r2t9jab3e {
  stop-color: var(--svg-color--f5a129, #F5A129);
}

.r37rgng3f {
  stop-color: var(--svg-color--ffe235, #FFE235);
}

.r3829sbqp {
  d: path("M10.83 9.034a1.61 1.61 0 0 0 .139 3.2a78 78 0 0 1-.139-3.2");
}

.r7448c-_n {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.494 9.228c-.654 0-1.205.45-1.355 1.059a.273.273 0 0 0 .267.34h2.231a.23.23 0 0 0 .228-.271a1.4 1.4 0 0 0-1.372-1.128");
}

.r8td-ob5s {
  stop-color: var(--svg-color--f3ebfe, #F3EBFE);
}

.r9kx25b9b {
  stop-color: var(--svg-color--e08f2e, #E08F2E);
}

.rf4ocecah {
  d: path("M20.74 4.25c.514.177.975.536 1.267 1.051a2.37 2.37 0 0 1-.106 2.527a1.56 1.56 0 0 0-.27.874V9.89a1.7 1.7 0 0 0-.668-.268l.078-1.607a1.45 1.45 0 0 0-1.378-1.432h-1.4c-.955 0-1.82-.563-2.212-1.443a.66.66 0 0 0-.616-.418h-1.273c-1.845 0-3.34 1.513-3.34 3.38l.03 1.537c-.254.037-.52.122-.72.263v-1.2a1.56 1.56 0 0 0-.27-.874a2.39 2.39 0 0 1-.144-2.446a2.34 2.34 0 0 1 1.3-1.127a2.68 2.68 0 0 0 1.384-1.11a2.326 2.326 0 0 1 2.89-.912a1.5 1.5 0 0 0 1.194 0c.28-.118.588-.187.912-.187c.843 0 1.58.456 1.989 1.131c.307.51.79.88 1.352 1.073");
}

.rgs-6fbpw {
  d: path("M5.096 29.939c0-7.961 4.617-9.875 5.375-10.383l5.047 10.383z");
}

.s-nb5j24l {
  stop-color: var(--svg-color--ef8a23, #EF8A23);
  stop-opacity: 0;
}

.s6ufut5ul {
  d: path("M21.82 17.353c-.641-1.313-1.82-1.75-2.594-1.75h-2.61v2.875h2.47c.168.303.002.85-.102 1.086l-3.939 10.39h3.176c1.068-2.583 2.995-7.817 3.383-8.742c.42-1.004.81-2.476.216-3.86");
}

.sftxd4bwi {
  fill: var(--svg-color--ffce26, #FFCE26);
  d: path("M14.01 16.517h4v.887c.01.175.045.374.152.53a.8.8 0 0 0 .446.333l.464.164c.076.068.22.478.04.984c-.181.505-2.043 5.51-3.094 8.02v.02l-.004-.01l-.005.01v-.02c-1.052-2.51-3.139-7.515-3.32-8.02c-.18-.506-.122-.87-.046-.937l.68-.192c.218-.062.373-.14.515-.347c.113-.166.158-.39.172-.572z");
}

.snymmbrnj {
  stop-color: var(--svg-color--d5c4df, #D5C4DF);
}

.st3dxnbfu {
  stop-color: var(--svg-color--ffea47, #FFEA47);
}

.swgfs-c3o {
  stop-color: var(--svg-color--ffd930, #FFD930);
}

.t79-6ab5u {
  stop-color: var(--svg-color--ffa30b, #FFA30B);
  stop-opacity: 0;
}

.tg3b212mk {
  d: path("m21.097 8.65l-.03-.632c-.01-.763-.64-1.393-1.404-1.425h-1.4c-.89 0-1.7-.486-2.125-1.26c0 0-.058-.136-.12-.368c-.256-.97.671-1.712 1.656-1.521c.973.188 2.082.517 2.902 1.051c1.745 1.138 1.44 3.189.521 4.154");
}

.u4bo2-o9a {
  stop-color: var(--svg-color--d84f1a, #D84F1A);
  stop-opacity: 0;
}

.u7o3559vd {
  stop-color: var(--svg-color--f59632, #F59632);
}

.ue2ywxbfs {
  stop-color: var(--svg-color--e45c36, #E45C36);
  stop-opacity: 0;
}

.up5p4s41k {
  stop-color: var(--svg-color--e64812, #E64812);
  stop-opacity: 0;
}

.uxis8ac7p {
  fill: var(--svg-color--c05029, #C05029);
  d: path("M19.617 7.913a1.85 1.85 0 0 0-.687-.411c-.304-.096-.686-.122-1.213-.057a.277.277 0 1 0 .068.55c.48-.059.776-.028.978.036c.198.062.333.163.49.3a.277.277 0 0 0 .364-.418");
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.v6wds2dtn {
  stop-color: var(--svg-color--dad4de, #DAD4DE);
}

.ven54yrxx {
  stop-color: var(--svg-color--c98537, #C98537);
}

.vhbqh4bkl {
  d: path("M13.7 9.5a.893.893 0 0 0-.86 1.127h1.724a1 1 0 0 0 .033-.235a.9.9 0 0 0-.897-.892");
}

.vr5749b_g {
  stop-color: var(--svg-color--e1943d, #E1943D);
  stop-opacity: 0;
}

.vymdidolh {
  d: path("M18.003 9.688c.063.085-.07.189-.22.302c-.152.113-.264.192-.328.107c-.063-.085.008-.245.159-.358s.325-.136.389-.05");
}

.vze8wny8i {
  stop-color: var(--svg-color--e8dee9, #E8DEE9);
}

.w_5-rbc1a {
  stop-color: var(--svg-color--dd3537, #DD3537);
  stop-opacity: 0;
}

.w8e9izb-y {
  d: path("M26.947 29.939c0-7.961-4.617-9.875-5.375-10.383l-5.047 10.383z");
}

.wbf-2ib5u {
  stop-color: var(--svg-color--ffe846, #FFE846);
}

.wekziilbz {
  fill: var(--svg-color--dd8224, #DD8224);
  d: path("M10.847 9.695a.956.956 0 0 0 .084 1.88a78 78 0 0 1-.084-1.88");
}

.wkmk90b2p {
  fill: var(--svg-color--e8d6ff, #E8D6FF);
  d: path("M1.97 24.017h3.298a5.94 5.94 0 0 1 5.937 5.937H1.971zm28.06 0h-3.298a5.94 5.94 0 0 0-5.937 5.937h9.234z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.wrlksbcrj {
  stop-color: var(--svg-color--c98537, #C98537);
  stop-opacity: 0;
}

.wwr7m_5oe {
  stop-color: var(--svg-color--ffbe3a, #FFBE3A);
  stop-opacity: 0;
}

.wxscdbbqi {
  stop-color: var(--svg-color--ffb52a, #FFB52A);
  stop-opacity: 0;
}

.x3axlob0n {
  stop-color: var(--svg-color--e24c14, #E24C14);
  stop-opacity: 0;
}

.xitcw8bap {
  stop-color: var(--svg-color--ffc135, #FFC135);
}

.yf3t3eb5f {
  stop-color: var(--svg-color--ff8244, #FF8244);
}

.ygp8qdbik {
  stop-color: var(--svg-color--f29415, #F29415);
}

.yhlucbb6c {
  stop-color: var(--svg-color--d66e05, #D66E05);
}

.yhtyhvpuw {
  stop-color: var(--svg-color--ffa041, #FFA041);
  stop-opacity: 0;
}

.yisb3abxj {
  d: path("m16.117 5.277l-.066-.137a.66.66 0 0 0-.616-.418h-1.273c-1.845 0-3.34 1.513-3.34 3.38v.274c-.34-.258-.768-.804-.768-1.687c0-1.072.781-1.614 1.28-1.96c.14-.097.259-.18.33-.253q.046-.046.1-.105c.35-.37.973-1.031 2.06-1.32a5.5 5.5 0 0 1 1.508-.165c.473.012.806.42.806.893v1.485z");
}

.ykdcls_lk {
  stop-color: var(--svg-color--dd3d3d, #DD3D3D);
}

.yr9ecnbfu {
  fill: var(--svg-color--000, #000);
  d: path("M17.557 10.392c0-.284.227-.511.511-.511a.51.51 0 0 1 .455.746h-.905a.46.46 0 0 1-.06-.235");
}

.ysruzhx-p {
  stop-color: var(--svg-color--ffeb3b, #FFEB3B);
  stop-opacity: 0;
}

.yu9sk6b5g {
  stop-color: var(--svg-color--ffa929, #FFA929);
  stop-opacity: 0;
}

.z2ddyab4m {
  stop-color: var(--svg-color--f47246, #F47246);
}

.z5cogrbuu {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.275 9.228c.654 0 1.205.45 1.355 1.059a.274.274 0 0 1-.267.34H17.13a.23.23 0 0 1-.227-.272c.126-.64.69-1.127 1.371-1.127");
}

.z8auuww1t {
  stop-color: var(--svg-color--be691e, #BE691E);
  stop-opacity: 0;
}

.zav_leb7s {
  stop-color: var(--svg-color--fac137, #FAC137);
}

.zrke-tbre {
  stop-color: var(--svg-color--e48421, #E48421);
}

</style>
