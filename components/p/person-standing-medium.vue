<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="n2paa4yev"/><path fill="url(#iVctUTc)" class="dhem5bbqc"/><g filter="url(#izZgQvb)"><path class="tf4odqbmx"/><path fill="url(#iESMuFe)" class="a2zxjbcyy"/></g><path class="fwkvbob3q"/><path fill="url(#ivAFZgn)" class="u78464b_o"/><path fill="url(#iZNtoxe)" class="u78464b_o"/><path class="ta7i6wbki"/><path fill="url(#iSH97bP)" class="gh48jbbhn"/><path fill="url(#i0hUVic)" class="gh48jbbhn"/><path fill="url(#ivKrMAb)" class="gh48jbbhn"/><g filter="url(#ifpyWRc)"><path class="c25nbabot"/></g><path class="er818xpbc"/><path fill="url(#iXI2pNc)" class="bsrto12qr"/><path fill="url(#i7f2jHN)" class="bsrto12qr"/><g filter="url(#iUA9b7k)"><path class="ir-g6pm8n"/></g><path fill="url(#iKWj31d)" class="z9wedib1s"/><path fill="url(#i02Gsmn)" class="z9wedib1s"/><path fill="url(#ilCBvjH)" class="z9wedib1s"/><path fill="url(#iaPOC8b)" class="z9wedib1s"/><g filter="url(#iwFqmxd)"><path fill="url(#iEmngAd)" class="h5gec01yx"/><path fill="url(#iopGuPc)" class="h5gec01yx"/></g><path fill="url(#i7BkYhQ)" class="ja04_0anf"/><g filter="url(#iDCWfKb)"><path class="q7l7dqb4y"/></g><path fill="url(#iaDrApd)" class="kbtpxgecb"/><path fill="url(#ieH8Tse)" class="kbtpxgecb"/><g filter="url(#ip796ac)"><path class="sx-yjgb9f"/></g><path fill="url(#ijoBese)" class="poh_gwhje"/><path fill="url(#iLdLxpb)" class="drhu1ybzd"/><g filter="url(#iamgRKs)"><path fill="url(#iERG1kb)" class="yhl3rwbtd"/><path fill="url(#iPOmkqb)" class="yhl3rwbtd"/></g><path fill="url(#iPskTOb)" class="yhl3rwbtd"/><path fill="url(#igFU5ab)" class="yhl3rwbtd"/><path fill="url(#iJvpyde)" class="yhl3rwbtd"/><path fill="url(#icmiECd)" class="yhl3rwbtd"/><path fill="url(#iwJQRCe)" class="yhl3rwbtd"/><path fill="url(#i0PYvrb)" class="yhl3rwbtd"/><path fill="url(#iGuO30C)" class="yhl3rwbtd"/><path fill="url(#i9cLvPe)" class="yhl3rwbtd"/><g filter="url(#iwFBkip)"><path class="d-8mcelzu"/></g><g filter="url(#ivJQKMn)"><path class="znkgs0cxs"/><path fill="url(#iDDAf7d)" class="v1ass0bqn"/><path fill="url(#i3kbZWb)" class="v1ass0bqn"/><path fill="url(#idZIHLX)" class="v1ass0bqn"/><path fill="url(#ig0d8wO)" class="v1ass0bqn"/><path fill="url(#ienHm0c)" class="v1ass0bqn"/></g><g filter="url(#i6Qi44s)"><path stroke="url(#iw0ZM0d)" class="xc3ukgbty"/></g><path fill="url(#i8zyVhc)" class="as_wp7bxb"/><g filter="url(#idDSjdc)"><path fill="url(#iq1x4Gd)" class="cwum5ib6r"/></g><path fill="url(#iZLFOMe)" class="cwum5ib6r"/><path fill="url(#i8WzDhc)" class="cwum5ib6r"/><path fill="url(#iADKBle)" class="cwum5ib6r"/><g filter="url(#imoxxFe)"><path class="zk_ep7bop"/></g><g filter="url(#igHgeZb)"><path class="pdas9obvw"/></g><g filter="url(#irm4hFd)"><path class="hc31y0bhs"/><path fill="url(#isJl3Eb)" class="l4sfebcir"/><path fill="url(#ik6WMib)" class="l4sfebcir"/></g><g filter="url(#i7Y8nMf)"><path class="u0w6qu9xx"/><path fill="url(#iEyQ12d)" class="e3hv18bkn"/><path fill="url(#iIKhgQd)" class="e3hv18bkn"/><path fill="url(#iaD9Ldd)" class="e3hv18bkn"/></g><path class="i4lvugk7y"/><path fill="url(#iXq9w4S)" class="u__fffk1x"/><path class="s9e8mxbku"/><g filter="url(#iC2GOXc)"><path class="hozdj8wjb"/><path fill="url(#ib798Pe)" class="jykzbcbfn"/></g><g filter="url(#iWwlsDd)"><path fill="url(#idNkDye)" class="l5ljb8kaq"/></g><path class="tf9iwot5v"/><path fill="url(#iYgL78c)" class="wgp31zbmt"/><path class="cd-jzicse"/><g filter="url(#iBlhCpc)"><path fill="url(#imyaIkc)" class="cktzfgb9f"/></g><g filter="url(#iTk4dHe)"><ellipse transform="rotate(-27.914 14.93 5.455)" class="ozv9gm3ep"/><ellipse fill="url(#iHtZkLc)" transform="rotate(-27.914 14.93 5.455)" class="f6hrwsbeg"/></g><path fill="url(#ibZqhYd)" class="rufovacfb"/><path fill="url(#i8HgSKe)" class="rufovacfb"/><path fill="url(#iDxrzvd)" class="rufovacfb"/><path fill="url(#iMslYkc)" class="rufovacfb"/><path fill="url(#iDjrf8b)" class="d843-3b8b"/><path fill="url(#iTIcT5c)" class="d843-3b8b"/><g filter="url(#i60qFgc)"><path fill="url(#iCHqitb)" class="nybzm5bau"/></g><g filter="url(#iMwQOYc)"><path fill="url(#ix7TM1b)" class="xc5jbxb7v"/></g><g filter="url(#in7bfPe)"><path class="cfammzllu"/></g><g filter="url(#ifrFuhc)"><path class="c9ndjjb1a"/></g><g filter="url(#iN6vlAJ)"><path class="s4ofn26_c"/></g><defs><radialGradient id="iVctUTc" cx="0" cy="0" r="1" gradientTransform="matrix(.3711 -.3086 .27428 .32982 18.99 19.906)" gradientUnits="userSpaceOnUse"><stop class="q_4zm1-zb"/><stop offset="1" class="y8l9uwbpv"/></radialGradient><radialGradient id="iESMuFe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.84375 0 0 -12.369 13.326 16.63)" gradientUnits="userSpaceOnUse"><stop offset=".138" class="zay0pib-e"/><stop offset="1" class="f283vybwl"/></radialGradient><radialGradient id="ivAFZgn" cx="0" cy="0" r="1" gradientTransform="matrix(1.60938 0 0 15.4135 18.903 16.63)" gradientUnits="userSpaceOnUse"><stop offset=".101" class="nrk1uwb9l"/><stop offset="1" class="jewrngbdz"/></radialGradient><radialGradient id="iZNtoxe" cx="0" cy="0" r="1" gradientTransform="matrix(.1836 -.5625 .3991 .13026 19.35 19.025)" gradientUnits="userSpaceOnUse"><stop class="w48qw8bka"/><stop offset="1" class="q7l1h8mqg"/></radialGradient><radialGradient id="iSH97bP" cx="0" cy="0" r="1" gradientTransform="matrix(-1.98267 0 0 -3.09375 13.544 12.523)" gradientUnits="userSpaceOnUse"><stop offset=".638" class="cn77rwbmc"/><stop offset="1" class="y2mxoh-zc"/></radialGradient><radialGradient id="i0hUVic" cx="0" cy="0" r="1" gradientTransform="matrix(-1.51587 1.2383 -.95063 -1.16372 14.593 8.832)" gradientUnits="userSpaceOnUse"><stop class="y4_ytjb3b"/><stop offset="1" class="wysngjbll"/></radialGradient><radialGradient id="iXI2pNc" cx="0" cy="0" r="1" gradientTransform="matrix(.875 -.3125 1.2963 3.62963 18.825 11.976)" gradientUnits="userSpaceOnUse"><stop offset=".251" class="l7g1kibqg"/><stop offset="1" class="d_gvw4b_b"/></radialGradient><radialGradient id="i02Gsmn" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.35938 1.91919 0 16.031 18.101)" gradientUnits="userSpaceOnUse"><stop class="kcjik5o6k"/><stop offset="1" class="j6ndfp4vo"/></radialGradient><radialGradient id="ilCBvjH" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.26953 1.85938 0 18.107 28.465)" gradientUnits="userSpaceOnUse"><stop class="x7tdxqavt"/><stop offset="1" class="cssy6ccya"/></radialGradient><radialGradient id="iaPOC8b" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.32813 1.20581 0 14.825 28.554)" gradientUnits="userSpaceOnUse"><stop class="x7tdxqavt"/><stop offset="1" class="cssy6ccya"/></radialGradient><radialGradient id="iopGuPc" cx="0" cy="0" r="1" gradientTransform="rotate(140.013 7.442 8.232)scale(2.52874 3.92481)" gradientUnits="userSpaceOnUse"><stop class="mdbsecb0y"/><stop offset="1" class="y-nukfwnq"/></radialGradient><radialGradient id="i7BkYhQ" cx="0" cy="0" r="1" gradientTransform="matrix(1.42712 .66406 -.8419 1.8093 15.475 8.873)" gradientUnits="userSpaceOnUse"><stop offset=".526" class="sqipzm23w"/><stop offset="1" class="ewky_9bdi"/></radialGradient><radialGradient id="ieH8Tse" cx="0" cy="0" r="1" gradientTransform="matrix(-1.66284 -.84375 .32903 -.64844 19.598 29.414)" gradientUnits="userSpaceOnUse"><stop class="z3z2fqbpi"/><stop offset="1" class="qnuhplbln"/></radialGradient><radialGradient id="ijoBese" cx="0" cy="0" r="1" gradientTransform="rotate(69.657 4.532 16.22)scale(.96684 1.14853)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="hb-rh6b9c"/><stop offset="1" class="o5jc2cxps"/></radialGradient><radialGradient id="iLdLxpb" cx="0" cy="0" r="1" gradientTransform="matrix(.66276 .2083 -.6426 2.04466 13.312 6.552)" gradientUnits="userSpaceOnUse"><stop class="v_2gjcb5l"/><stop offset=".746" class="vzzhqfd0u"/></radialGradient><radialGradient id="iERG1kb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.11201 0 0 -3.73612 17.291 5.91)" gradientUnits="userSpaceOnUse"><stop class="hdsgirtov"/><stop offset="1" class="j213y8b_z"/></radialGradient><radialGradient id="iPOmkqb" cx="0" cy="0" r="1" gradientTransform="rotate(121.159 7.524 6.665)scale(1.51228 1.24851)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="v3vg2fbhx"/><stop offset="1" class="jon81gnkc"/></radialGradient><radialGradient id="igFU5ab" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.76786 -3.94836 0 16.282 4.171)" gradientUnits="userSpaceOnUse"><stop offset=".744" class="lgm4opl_d"/><stop offset="1" class="akctd8b8h"/></radialGradient><radialGradient id="iJvpyde" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.51548 .6379 0 17.13 5.32)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="kud2-ccnc"/><stop offset="1" class="qjdbe6bhy"/></radialGradient><radialGradient id="icmiECd" cx="0" cy="0" r="1" gradientTransform="matrix(.00176 -.4912 .53454 .00192 14.998 5.34)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="g101ufbyh"/><stop offset="1" class="ofu8odbdi"/></radialGradient><radialGradient id="iwJQRCe" cx="0" cy="0" r="1" gradientTransform="rotate(176.388 8.686 3.453)scale(3.82129 9.76149)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="c-0f6obbw"/><stop offset="1" class="q4oz8ebqu"/></radialGradient><radialGradient id="i0PYvrb" cx="0" cy="0" r="1" gradientTransform="rotate(-40.741 12.796 -15.14)scale(2.00593 .59252)" gradientUnits="userSpaceOnUse"><stop offset=".539" class="gl-yj8bin"/><stop offset="1" class="b1x_r2coy"/></radialGradient><radialGradient id="iGuO30C" cx="0" cy="0" r="1" gradientTransform="rotate(95.368 7.166 10.73)scale(1.12599 .45011)" gradientUnits="userSpaceOnUse"><stop offset=".245" class="y4noiz6ri"/><stop offset="1" class="n64jnw11q"/></radialGradient><radialGradient id="i9cLvPe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .39124 -.75107 0 15.036 5.687)" gradientUnits="userSpaceOnUse"><stop class="rlwq00h2l"/><stop offset="1" class="uhv9b32lc"/></radialGradient><radialGradient id="i3kbZWb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .10957 -.34437 0 16.24 6.52)" gradientUnits="userSpaceOnUse"><stop class="ifoj0vbnx"/><stop offset="1" class="fd01o6-ig"/></radialGradient><radialGradient id="ig0d8wO" cx="0" cy="0" r="1" gradientTransform="rotate(156.093 7.483 4.857)scale(.83082 1.33521)" gradientUnits="userSpaceOnUse"><stop offset=".702" class="xqbp6db-u"/><stop offset="1" class="l6ffphqdg"/><stop offset="1" class="bi0efq_rm"/></radialGradient><radialGradient id="i8zyVhc" cx="0" cy="0" r="1" gradientTransform="matrix(.97945 -.48153 1.93731 3.9406 15.81 7.536)" gradientUnits="userSpaceOnUse"><stop offset=".562" class="i_5kuqxuv"/><stop offset="1" class="iazz9lb4s"/></radialGradient><radialGradient id="iZLFOMe" cx="0" cy="0" r="1" gradientTransform="matrix(1.23024 -3.20931 4.554 1.7457 13.469 5.045)" gradientUnits="userSpaceOnUse"><stop class="gzjm9absi"/><stop offset="1" class="xys9jruze"/></radialGradient><radialGradient id="i8WzDhc" cx="0" cy="0" r="1" gradientTransform="matrix(-.682 -2.94187 4.17448 -.96775 18.577 5.072)" gradientUnits="userSpaceOnUse"><stop offset=".303" class="gzjm9absi"/><stop offset="1" class="xys9jruze"/></radialGradient><radialGradient id="iADKBle" cx="0" cy="0" r="1" gradientTransform="matrix(-.50815 -1.06977 1.26289 -.59988 17.48 3.147)" gradientUnits="userSpaceOnUse"><stop class="vm3i05jbz"/><stop offset="1" class="o0n2z3bef"/></radialGradient><radialGradient id="isJl3Eb" cx="0" cy="0" r="1" gradientTransform="matrix(-.98805 0 0 -.3667 16.145 2.681)" gradientUnits="userSpaceOnUse"><stop class="ur78mwbxs"/><stop offset="1" class="xxn4m8bxd"/></radialGradient><radialGradient id="ik6WMib" cx="0" cy="0" r="1" gradientTransform="matrix(1.44458 -2.28726 2.53405 1.60045 13.593 4.45)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="oxzu0y4el"/><stop offset=".311" class="h09cq_pwq"/><stop offset="1" class="fdnwjygjt"/></radialGradient><radialGradient id="iEyQ12d" cx="0" cy="0" r="1" gradientTransform="matrix(1.57792 -1.27036 1.96878 2.44543 16.892 3.829)" gradientUnits="userSpaceOnUse"><stop class="wv5n4khjs"/><stop offset=".445" class="oywlam1jg"/></radialGradient><radialGradient id="iIKhgQd" cx="0" cy="0" r="1" gradientTransform="matrix(1.32818 -1.18874 2.17628 2.43156 17.213 4.393)" gradientUnits="userSpaceOnUse"><stop offset=".857" class="ut-a4zo6y"/><stop offset="1" class="mw5vlrbvk"/></radialGradient><radialGradient id="iaD9Ldd" cx="0" cy="0" r="1" gradientTransform="matrix(1.44777 .32506 -.1361 .60615 16.826 3.576)" gradientUnits="userSpaceOnUse"><stop class="rxg51vbwm"/><stop offset="1" class="g9z9sr5ky"/></radialGradient><radialGradient id="iXq9w4S" cx="0" cy="0" r="1" gradientTransform="matrix(0 .36419 -.57928 0 17.01 5.498)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="ib798Pe" cx="0" cy="0" r="1" gradientTransform="rotate(-127.811 9.81 -1.373)scale(.16981 .23378)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iYgL78c" cx="0" cy="0" r="1" gradientTransform="matrix(0 .3642 -.57931 0 15.052 5.498)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="iHtZkLc" cx="0" cy="0" r="1" gradientTransform="matrix(-.00347 -.22179 .2666 -.00417 14.923 5.596)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i8HgSKe" cx="0" cy="0" r="1" gradientTransform="matrix(.28215 1.00697 -.96073 .26919 18.104 5.504)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="k-8l2bbtm"/><stop offset="1" class="j8b6y4byx"/></radialGradient><radialGradient id="iDxrzvd" cx="0" cy="0" r="1" gradientTransform="matrix(.35362 -.48529 .40677 .2964 18.265 5.75)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="gvb-xxmau"/><stop offset="1" class="wbdnw-owo"/></radialGradient><radialGradient id="iMslYkc" cx="0" cy="0" r="1" gradientTransform="matrix(.2635 -.69596 .9299 .35206 18.317 5.826)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="nx86noq5t"/><stop offset="1" class="mchm9tbqp"/></radialGradient><radialGradient id="iTIcT5c" cx="0" cy="0" r="1" gradientTransform="matrix(-.74436 0 0 -.83119 13.824 5.792)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="ok_b4wzpx"/><stop offset="1" class="mtikk0bwo"/></radialGradient><radialGradient id="iCHqitb" cx="0" cy="0" r="1" gradientTransform="matrix(-.4114 .07062 -.07241 -.4218 13.826 5.794)" gradientUnits="userSpaceOnUse"><stop class="qkgshibem"/><stop offset="1" class="b89ok8b-l"/></radialGradient><filter id="izZgQvb" width="2.311" height="8.028" x="11.372" y="12.617" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.666667 0 0 0 0 0.505882 0 0 0 0 0.447059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_176"/></filter><filter id="ifpyWRc" width="1.464" height="6.913" x="19.195" y="11.979" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_176" stdDeviation=".25"/></filter><filter id="iUA9b7k" width="6.169" height="12.453" x="13.047" y="16.011" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.486275 0 0 0 0 0.462745 0 0 0 0 0.505882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_176"/></filter><filter id="iwFqmxd" width="6.417" height="7.594" x="12.973" y="8.468" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.415686 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_176"/></filter><filter id="iDCWfKb" width="3.316" height="1.848" x="12.465" y="28.465" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.313726 0 0 0 0 0.235294 0 0 0 0 0.431373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_176"/></filter><filter id="ip796ac" width="6.594" height="13.766" x="12.872" y="15.382" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_176" stdDeviation=".5"/></filter><filter id="iamgRKs" width="5.588" height="5.64" x="13.758" y="3.139" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".7"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.584314 0 0 0 0 0.427451 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_176"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.419608 0 0 0 0 0.25098 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_176" result="effect2_innerShadow_4002_176"/></filter><filter id="iwFBkip" width="2.784" height="3.302" x="14.575" y="4.539" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_176" stdDeviation=".5"/></filter><filter id="ivJQKMn" width=".943" height="1.402" x="15.56" y="5.401" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_176" stdDeviation=".025"/></filter><filter id="i6Qi44s" width="1.745" height=".782" x="15.159" y="6.904" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_176" stdDeviation=".05"/></filter><filter id="idDSjdc" width="5.778" height="4.027" x="13.142" y="1.438" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.266667 0 0 0 0 0.152941 0 0 0 0 0.184314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_176"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.258824 0 0 0 0 0.133333 0 0 0 0 0.172549 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_176" result="effect2_innerShadow_4002_176"/></filter><filter id="imoxxFe" width="1.105" height=".645" x="16.744" y="4.146" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.243137 0 0 0 0 0.121569 0 0 0 0 0.2 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_176"/></filter><filter id="igHgeZb" width="1.105" height=".638" x="14.385" y="4.152" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.243137 0 0 0 0 0.121569 0 0 0 0 0.2 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_176"/></filter><filter id="irm4hFd" width="2.931" height="2.645" x="13.313" y="2.234" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.364706 0 0 0 0 0.286275 0 0 0 0 0.270588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_176"/><feGaussianBlur result="effect2_foregroundBlur_4002_176" stdDeviation=".05"/></filter><filter id="i7Y8nMf" width="3.658" height="2.912" x="16.045" y="2.043" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.282353 0 0 0 0 0.168627 0 0 0 0 0.188235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_176"/><feGaussianBlur result="effect2_foregroundBlur_4002_176" stdDeviation=".05"/></filter><filter id="iC2GOXc" width=".463" height=".423" x="16.626" y="5.245" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_176" stdDeviation=".05"/></filter><filter id="iWwlsDd" width=".62" height=".63" x="16.948" y="5.224" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_176" stdDeviation=".1"/></filter><filter id="iBlhCpc" width=".663" height=".687" x="14.953" y="5.196" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_176" stdDeviation=".1"/></filter><filter id="iTk4dHe" width=".52" height=".427" x="14.67" y="5.242" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_176" stdDeviation=".05"/></filter><filter id="i60qFgc" width=".872" height="1.344" x="13.164" y="5.121" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_176" stdDeviation=".125"/></filter><filter id="iMwQOYc" width="1.362" height="1.789" x="17.798" y="4.896" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_176" stdDeviation=".25"/></filter><filter id="in7bfPe" width="1.043" height=".484" x="14.367" y="4.314" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_176" stdDeviation=".05"/></filter><filter id="ifrFuhc" width="1.043" height=".484" x="16.753" y="4.289" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_176" stdDeviation=".05"/></filter><filter id="iN6vlAJ" width="2.536" height="1.494" x="16.424" y="2.544" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_176" stdDeviation=".2"/></filter><linearGradient id="ivKrMAb" x1="12.497" x2="12.497" y1="12.781" y2="12.304" gradientUnits="userSpaceOnUse"><stop class="mea8vgbzb"/><stop offset="1" class="x8_6e5b0q"/></linearGradient><linearGradient id="i7f2jHN" x1="19.778" x2="19.778" y1="12.867" y2="12.164" gradientUnits="userSpaceOnUse"><stop class="kidhsabwy"/><stop offset="1" class="i08i0qbub"/></linearGradient><linearGradient id="iKWj31d" x1="16.031" x2="16.031" y1="16.011" y2="16.445" gradientUnits="userSpaceOnUse"><stop class="sb3cb-bog"/><stop offset="1" class="hpe4_756h"/></linearGradient><linearGradient id="iEmngAd" x1="16.031" x2="16.031" y1="9.101" y2="16.062" gradientUnits="userSpaceOnUse"><stop class="hrtvttbtf"/><stop offset="1" class="nua72fb5w"/></linearGradient><linearGradient id="iaDrApd" x1="18.278" x2="16.531" y1="29.726" y2="29.523" gradientUnits="userSpaceOnUse"><stop class="c2i7i45cq"/><stop offset="1" class="wwbz7ibcz"/></linearGradient><linearGradient id="iPskTOb" x1="18.346" x2="17.211" y1="6.666" y2="6.666" gradientUnits="userSpaceOnUse"><stop class="cgoojyxdz"/><stop offset="1" class="zvhz6qbam"/></linearGradient><linearGradient id="iDDAf7d" x1="16.407" x2="16.031" y1="6.212" y2="6.228" gradientUnits="userSpaceOnUse"><stop offset=".36" class="gb7af0bvz"/><stop offset="1" class="gafrz43pc"/></linearGradient><linearGradient id="idZIHLX" x1="16.031" x2="16.031" y1="6.724" y2="6.515" gradientUnits="userSpaceOnUse"><stop class="q7066kb0m"/><stop offset="1" class="se5f_fbvx"/></linearGradient><linearGradient id="ienHm0c" x1="16.031" x2="16.031" y1="5.509" y2="5.755" gradientUnits="userSpaceOnUse"><stop class="bl4x47bvc"/><stop offset="1" class="nv0opqb4i"/></linearGradient><linearGradient id="iw0ZM0d" x1="15.492" x2="15.634" y1="7.429" y2="7.054" gradientUnits="userSpaceOnUse"><stop class="sjwz8ccmm"/><stop offset="1" class="itcx93bci"/></linearGradient><linearGradient id="iq1x4Gd" x1="19.107" x2="13.894" y1="3.367" y2="3.367" gradientUnits="userSpaceOnUse"><stop offset=".471" class="vj4yuc0qg"/><stop offset="1" class="yd6vs-kvu"/></linearGradient><linearGradient id="idNkDye" x1="17.36" x2="17.219" y1="5.522" y2="5.609" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="imyaIkc" x1="15.385" x2="15.245" y1="5.522" y2="5.609" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ibZqhYd" x1="18.92" x2="18.378" y1="5.534" y2="6.511" gradientUnits="userSpaceOnUse"><stop class="r-tgpdb_v"/><stop offset="1" class="o8077h_4a"/></linearGradient><linearGradient id="iDjrf8b" x1="13.405" x2="14.06" y1="5.85" y2="5.793" gradientUnits="userSpaceOnUse"><stop class="d7c3jfbwh"/><stop offset="1" class="zvm05wbin"/></linearGradient><linearGradient id="ix7TM1b" x1="18.479" x2="18.479" y1="5.396" y2="6.185" gradientUnits="userSpaceOnUse"><stop class="aj8ithlra"/><stop offset="1" class="a9_46dbsd"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-standing-medium" /></template>
<style>
.a2zxjbcyy {
  d: path("M12.08 20.44c-.937-1.981-.768-6.258-.486-7.823h1.672c-.072 2.425.039 5.243.177 6.511c.012.103.084.214 0 .276a.29.29 0 0 1-.438-.115l-.117-.262a.184.184 0 0 0-.226-.1a.176.176 0 0 0-.12.201c.062.3.172.678.265.973a.42.42 0 0 1-.239.513c-.186.076-.401.008-.487-.174");
}

.a9_46dbsd {
  stop-color: var(--svg-color--ad806f, #AD806F);
}

.aj8ithlra {
  stop-color: var(--svg-color--ac7f6f, #AC7F6F);
}

.akctd8b8h {
  stop-color: var(--svg-color--a35a70, #A35A70);
}

.as_wp7bxb {
  d: path("M16.031 7.21c-.228 0-.442-.054-.622-.148c-.061-.031-.128.038-.089.094a.85.85 0 0 0 .711.38a.85.85 0 0 0 .71-.38c.04-.058-.027-.125-.088-.094a1.34 1.34 0 0 1-.622.148");
}

.b1x_r2coy {
  stop-color: var(--svg-color--63413d, #63413D);
  stop-opacity: 0;
}

.b89ok8b-l {
  stop-color: var(--svg-color--784e52, #784E52);
}

.bbyb_mbsk {
  stop-color: var(--svg-color--664842, #664842);
}

.bi0efq_rm {
  stop-color: var(--svg-color--8a5f5c, #8A5F5C);
}

.bl4x47bvc {
  stop-color: var(--svg-color--a4786e, #A4786E);
}

.bsrto12qr {
  d: path("M20.499 12.66c-.487-2.253-1.629-3.333-3.03-3.828v3.949h2.932a.1.1 0 0 0 .098-.12");
}

.c-0f6obbw {
  stop-color: var(--svg-color--987064, #987064);
  stop-opacity: 0;
}

.c25nbabot {
  stroke: var(--svg-color--bd8a7d, #BD8A7D);
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M19.844 12.498c.125 1 .3 3.575 0 5.875");
}

.c2i7i45cq {
  stop-color: var(--svg-color--5a3f7c, #5A3F7C);
}

.c9ndjjb1a {
  stroke: var(--svg-color--553f3f, #553F3F);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M17.646 4.624a1.04 1.04 0 0 0-.743-.172");
}

.cd-jzicse {
  fill: var(--svg-color--000, #000);
  d: path("M15.28 5.685a.23.23 0 0 0-.23-.23a.228.228 0 0 0-.203.335h.406a.2.2 0 0 0 .027-.105");
}

.cfammzllu {
  stroke: var(--svg-color--553f3f, #553F3F);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.517 4.648a1.04 1.04 0 0 1 .743-.17");
}

.cgoojyxdz {
  stop-color: var(--svg-color--c2987e, #C2987E);
}

.cktzfgb9f {
  d: path("M15.417 5.637c0-.13-.106-.215-.134-.241l-.13.125l.08.162z");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cn77rwbmc {
  stop-color: var(--svg-color--f16440, #F16440);
  stop-opacity: 0;
}

.cssy6ccya {
  stop-color: var(--svg-color--aa9ba7, #AA9BA7);
  stop-opacity: 0;
}

.cwum5ib6r {
  d: path("M18.21 2.927a1.064 1.064 0 0 1 .521 1.606a.7.7 0 0 0-.12.393v.533a.8.8 0 0 0-.3-.12l.035-.721a.65.65 0 0 0-.62-.643h-.628c-.428 0-.816-.253-.992-.648a.3.3 0 0 0-.277-.188h-.571c-.828 0-1.5.68-1.5 1.517l.014.69a.8.8 0 0 0-.323.119v-.54a.7.7 0 0 0-.122-.392a1.07 1.07 0 0 1-.064-1.098c.13-.248.343-.42.583-.505a1.2 1.2 0 0 0 .622-.499a1.044 1.044 0 0 1 1.297-.409a.67.67 0 0 0 .536 0a1.044 1.044 0 0 1 1.302.424c.138.229.355.395.607.481");
}

.d_gvw4b_b {
  stop-color: var(--svg-color--ff391e, #FF391E);
  stop-opacity: 0;
}

.d-8mcelzu {
  fill: var(--svg-color--6f3f46, #6F3F46);
  d: path("m15.85 5.676l-.265.826c-.045.17.064.34.218.34h.328c.154 0 .263-.173.218-.34l-.222-.826c-.048-.182-.226-.182-.276 0");
}

.d7c3jfbwh {
  stop-color: var(--svg-color--855d5a, #855D5A);
}

.d843-3b8b {
  d: path("M13.767 5.073a.722.722 0 0 0 .058 1.439q-.046-.72-.058-1.44");
}

.dhem5bbqc {
  d: path("M19.364 19.16a.22.22 0 0 0 .043-.238h.437l-.32.996c-.262.078-.54.05-.59-.114a.32.32 0 0 1 .074-.3a9 9 0 0 0 .356-.344");
}

.drhu1ybzd {
  d: path("M13.849 6.47a.74.74 0 0 1-.406-.138v.418c0 .4.239.758.602.906a1.8 1.8 0 0 1-.156-.53z");
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e3hv18bkn {
  d: path("m18.37 4.855l-.012-.283a.66.66 0 0 0-.631-.64h-.628c-.4 0-.763-.218-.954-.566c0 0 .323-.933.86-.812c.392.088.811.227 1.132.436c.783.511.646 1.431.234 1.865");
}

.er818xpbc {
  fill: var(--svg-color--ff7a43, #FF7A43);
  d: path("M20.499 12.66c-.487-2.253-1.629-3.333-3.03-3.828v3.949h2.932a.1.1 0 0 0 .098-.12");
}

.ewky_9bdi {
  stop-color: var(--svg-color--b98070, #B98070);
}

.f283vybwl {
  stop-color: var(--svg-color--8d434a, #8D434A);
  stop-opacity: 0;
}

.f6hrwsbeg {
  cx: 14.93px;
  cy: 5.455px;
  rx: 0.175px;
  ry: 0.089px;
}

.fd01o6-ig {
  stop-color: var(--svg-color--c59a8a, #C59A8A);
  stop-opacity: 0;
}

.fdnwjygjt {
  stop-color: var(--svg-color--472438, #472438);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fwkvbob3q {
  fill: var(--svg-color--bb937c, #BB937C);
  d: path("M19.92 20.44c.937-1.981.768-6.258.486-7.823h-1.671c.071 2.425-.156 5.253-.294 6.522a.29.29 0 0 0 .554.15l.117-.262a.184.184 0 0 1 .226-.1a.176.176 0 0 1 .12.201c-.062.3-.172.678-.265.973a.42.42 0 0 0 .239.513c.186.076.401.008.487-.174");
}

.g101ufbyh {
  stop-color: var(--svg-color--8f5d66, #8F5D66);
}

.g9z9sr5ky {
  stop-color: var(--svg-color--4f2b3c, #4F2B3C);
  stop-opacity: 0;
}

.gafrz43pc {
  stop-color: var(--svg-color--cea58c, #CEA58C);
  stop-opacity: 0;
}

.gb7af0bvz {
  stop-color: var(--svg-color--cea58c, #CEA58C);
}

.gh48jbbhn {
  d: path("M11.564 12.66c.486-2.253 1.628-3.333 3.03-3.828v3.949H11.66a.1.1 0 0 1-.097-.12");
}

.gl-yj8bin {
  stop-color: var(--svg-color--63413d, #63413D);
}

.gvb-xxmau {
  stop-color: var(--svg-color--9e6a5c, #9E6A5C);
}

.gzjm9absi {
  stop-color: var(--svg-color--604946, #604946);
}

.h09cq_pwq {
  stop-color: var(--svg-color--472438, #472438);
}

.h5gec01yx {
  d: path("M12.973 11.527a3.059 3.059 0 1 1 6.117 0v4.441a.094.094 0 0 1-.094.094h-5.93a.094.094 0 0 1-.094-.094z");
}

.hb-rh6b9c {
  stop-color: var(--svg-color--493b3b, #493B3B);
}

.hc31y0bhs {
  fill: var(--svg-color--533634, #533634);
  d: path("m16.135 3.389l-.03-.062a.3.3 0 0 0-.276-.188h-.571c-.829 0-1.5.68-1.5 1.517v.124c-.153-.117-.344-.362-.344-.758c0-.481.35-.724.574-.88c.063-.043.117-.08.149-.113l.044-.047c.157-.167.437-.463.925-.593q.116-.03.231-.047c.468-.07.808.348.808.821v.22z");
}

.hdsgirtov {
  stop-color: var(--svg-color--c89980, #C89980);
}

.hozdj8wjb {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M16.982 5.369c.029.038-.031.084-.099.135c-.068.05-.118.086-.147.048s.004-.11.072-.16s.145-.062.174-.023");
}

.hpe4_756h {
  stop-color: var(--svg-color--856988, #856988);
  stop-opacity: 0;
}

.hrtvttbtf {
  stop-color: var(--svg-color--ff7325, #FF7325);
}

.i_5kuqxuv {
  stop-color: var(--svg-color--87014e, #87014E);
}

.i08i0qbub {
  stop-color: var(--svg-color--ff381e, #FF381E);
  stop-opacity: 0;
}

.i4lvugk7y {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.104 5.162c.294 0 .541.202.609.475a.123.123 0 0 1-.12.153H16.59a.103.103 0 0 1-.102-.122a.63.63 0 0 1 .615-.506");
}

.iazz9lb4s {
  stop-color: var(--svg-color--87004d, #87004D);
}

.ifoj0vbnx {
  stop-color: var(--svg-color--c59a8a, #C59A8A);
}

.ir-g6pm8n {
  fill: var(--svg-color--827a8a, #827A8A);
  d: path("m13.047 16.011l.484 12.454h2l.238-9.524c0-.328.029-.86.262-.86c.212 0 .263.555.262.86l.238 9.524h2l.485-12.454z");
}

.itcx93bci {
  stop-color: var(--svg-color--ab817b, #AB817B);
  stop-opacity: 0;
}

.j213y8b_z {
  stop-color: var(--svg-color--926763, #926763);
}

.j6ndfp4vo {
  stop-color: var(--svg-color--6a597b, #6A597B);
  stop-opacity: 0;
}

.j8b6y4byx {
  stop-color: var(--svg-color--9a676a, #9A676A);
}

.ja04_0anf {
  d: path("M15.16 7.375h1.742v1.351a.871.871 0 0 1-1.742 0z");
}

.jewrngbdz {
  stop-color: var(--svg-color--b06e67, #B06E67);
  stop-opacity: 0;
}

.jon81gnkc {
  stop-color: var(--svg-color--af887b, #AF887B);
  stop-opacity: 0;
}

.jykzbcbfn {
  d: path("M16.982 5.369c.029.038-.031.084-.099.135c-.068.05-.118.086-.147.048s.004-.11.072-.16s.145-.062.174-.023");
}

.k-8l2bbtm {
  stop-color: var(--svg-color--9a676a, #9A676A);
  stop-opacity: 0;
}

.kbtpxgecb {
  d: path("M19.598 29.82v.242H16.53v-1.598h1.992c.102.368.575.754.817.915c.186.123.258.3.258.44");
}

.kcjik5o6k {
  stop-color: var(--svg-color--6a597b, #6A597B);
}

.kidhsabwy {
  stop-color: var(--svg-color--ff381e, #FF381E);
}

.kud2-ccnc {
  stop-color: var(--svg-color--ab7872, #AB7872);
}

.l4sfebcir {
  d: path("m16.135 3.389l-.03-.062a.3.3 0 0 0-.276-.188h-.571c-.829 0-1.5.68-1.5 1.517v.124c-.153-.117-.344-.362-.344-.758c0-.481.35-.724.574-.88c.063-.043.117-.08.149-.113l.044-.047c.157-.167.437-.463.925-.593q.116-.03.231-.047c.468-.07.808.348.808.821v.22z");
}

.l5ljb8kaq {
  d: path("M17.368 5.632a.4.4 0 0 0-.103-.208l-.117.128l.053.103z");
}

.l6ffphqdg {
  stop-color: var(--svg-color--744a4a, #744A4A);
}

.l7g1kibqg {
  stop-color: var(--svg-color--ff391e, #FF391E);
}

.lgm4opl_d {
  stop-color: var(--svg-color--9b666f, #9B666F);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mchm9tbqp {
  stop-color: var(--svg-color--a47f62, #A47F62);
}

.mdbsecb0y {
  stop-color: var(--svg-color--ff863c, #FF863C);
}

.mea8vgbzb {
  stop-color: var(--svg-color--fb2d18, #FB2D18);
}

.mtikk0bwo {
  stop-color: var(--svg-color--9d7667, #9D7667);
}

.mw5vlrbvk {
  stop-color: var(--svg-color--685351, #685351);
}

.n2paa4yev {
  fill: var(--svg-color--7c4956, #7C4956);
  d: path("M12.699 19.16a.22.22 0 0 1-.043-.238h-.438l.32.996c.262.078.54.05.59-.114a.32.32 0 0 0-.074-.3a9 9 0 0 1-.355-.344");
}

.n64jnw11q {
  stop-color: var(--svg-color--bf9980, #BF9980);
  stop-opacity: 0;
}

.nrk1uwb9l {
  stop-color: var(--svg-color--8e4a4a, #8E4A4A);
}

.nua72fb5w {
  stop-color: var(--svg-color--ff4c2e, #FF4C2E);
}

.nv0opqb4i {
  stop-color: var(--svg-color--a4786e, #A4786E);
  stop-opacity: 0;
}

.nx86noq5t {
  stop-color: var(--svg-color--a47f62, #A47F62);
  stop-opacity: 0;
}

.nybzm5bau {
  d: path("M13.748 5.371a.429.429 0 0 0 .038.844a35 35 0 0 1-.038-.844");
}

.o0n2z3bef {
  stop-color: var(--svg-color--765a55, #765A55);
  stop-opacity: 0;
}

.o5jc2cxps {
  stop-color: var(--svg-color--311f2c, #311F2C);
}

.o8077h_4a {
  stop-color: var(--svg-color--b08175, #B08175);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ofu8odbdi {
  stop-color: var(--svg-color--8f5d66, #8F5D66);
  stop-opacity: 0;
}

.ok_b4wzpx {
  stop-color: var(--svg-color--9d7667, #9D7667);
  stop-opacity: 0;
}

.oxzu0y4el {
  stop-color: var(--svg-color--37192c, #37192C);
}

.oywlam1jg {
  stop-color: var(--svg-color--532c3f, #532C3F);
  stop-opacity: 0;
}

.ozv9gm3ep {
  cx: 14.93px;
  cy: 5.455px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.175px;
  ry: 0.089px;
}

.pdas9obvw {
  fill: var(--svg-color--462d2b, #462D2B);
  d: path("M14.5 4.523a1.25 1.25 0 0 1 .78-.161a.124.124 0 0 1-.03.247a1 1 0 0 0-.656.149l-.007.005l-.002.001a.125.125 0 0 1-.152-.197z");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.poh_gwhje {
  d: path("M18.213 6.47a.74.74 0 0 0 .406-.138v.418c0 .4-.239.758-.602.906q.116-.245.156-.53z");
}

.q_4zm1-zb {
  stop-color: var(--svg-color--90586c, #90586C);
}

.q4oz8ebqu {
  stop-color: var(--svg-color--987064, #987064);
}

.q7066kb0m {
  stop-color: var(--svg-color--9c6376, #9C6376);
}

.q7l1h8mqg {
  stop-color: var(--svg-color--9e6774, #9E6774);
  stop-opacity: 0;
}

.q7l7dqb4y {
  fill: var(--svg-color--5d4480, #5D4480);
  d: path("M12.465 29.82v.242h3.066v-1.598H13.54c-.102.368-.574.754-.816.915a.54.54 0 0 0-.258.44");
}

.qjdbe6bhy {
  stop-color: var(--svg-color--ab7872, #AB7872);
  stop-opacity: 0;
}

.qkgshibem {
  stop-color: var(--svg-color--714b4d, #714B4D);
}

.qnuhplbln {
  stop-color: var(--svg-color--635185, #635185);
  stop-opacity: 0;
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r-tgpdb_v {
  stop-color: var(--svg-color--c9a188, #C9A188);
}

.rlwq00h2l {
  stop-color: var(--svg-color--9e7765, #9E7765);
}

.rufovacfb {
  d: path("M18.24 6.511q.045-.717.083-1.432a.723.723 0 0 1-.083 1.432");
}

.rxg51vbwm {
  stop-color: var(--svg-color--4f2b3c, #4F2B3C);
}

.s4ofn26_c {
  fill: var(--svg-color--725050, #725050);
  d: path("M18.006 3.39h-.96a.222.222 0 1 1 .036-.443c.249.04.58.095.8.15c.501.124.64.367.678.541a.7.7 0 0 0-.554-.248");
}

.s9e8mxbku {
  fill: var(--svg-color--000, #000);
  d: path("M16.782 5.685c0-.128.102-.23.23-.23a.228.228 0 0 1 .203.335h-.406a.2.2 0 0 1-.027-.105");
}

.sb3cb-bog {
  stop-color: var(--svg-color--856988, #856988);
}

.se5f_fbvx {
  stop-color: var(--svg-color--9c6376, #9C6376);
  stop-opacity: 0;
}

.sjwz8ccmm {
  stop-color: var(--svg-color--ab817b, #AB817B);
}

.sqipzm23w {
  stop-color: var(--svg-color--a1646d, #A1646D);
}

.sx-yjgb9f {
  fill: var(--svg-color--9d98a2, #9D98A2);
  d: path("m13.872 16.382l.469 11.766h.812v-10.61h2.203v10.61h.672l.438-11.766z");
}

.ta7i6wbki {
  fill: var(--svg-color--ff4326, #FF4326);
  d: path("M11.564 12.66c.486-2.253 1.628-3.333 3.03-3.828v3.949H11.66a.1.1 0 0 1-.097-.12");
}

.tf4odqbmx {
  fill: var(--svg-color--996a67, #996A67);
  d: path("M12.08 20.44c-.937-1.981-.768-6.258-.486-7.823h1.672c-.072 2.425.039 5.243.177 6.511c.012.103.084.214 0 .276a.29.29 0 0 1-.438-.115l-.117-.262a.184.184 0 0 0-.226-.1a.176.176 0 0 0-.12.201c.062.3.172.678.265.973a.42.42 0 0 1-.239.513c-.186.076-.401.008-.487-.174");
}

.tf9iwot5v {
  fill: var(--svg-color--fff, #fff);
  d: path("M14.958 5.162a.63.63 0 0 0-.608.475c-.02.078.04.153.12.153h1.001a.103.103 0 0 0 .102-.122a.63.63 0 0 0-.615-.506");
}

.u__fffk1x {
  d: path("M17.011 5.284a.4.4 0 0 1 .387.506h-.774a.402.402 0 0 1 .388-.506");
}

.u0w6qu9xx {
  fill: var(--svg-color--563936, #563936);
  d: path("m18.37 4.855l-.012-.283a.66.66 0 0 0-.631-.64h-.628c-.4 0-.763-.218-.954-.566c0 0 .323-.933.86-.812c.392.088.811.227 1.132.436c.783.511.646 1.431.234 1.865");
}

.u78464b_o {
  d: path("M19.92 20.44c.937-1.981.768-6.258.486-7.823h-1.671c.071 2.425-.156 5.253-.294 6.522a.29.29 0 0 0 .554.15l.117-.262a.184.184 0 0 1 .226-.1a.176.176 0 0 1 .12.201c-.062.3-.172.678-.265.973a.42.42 0 0 0 .239.513c.186.076.401.008.487-.174");
}

.uhv9b32lc {
  stop-color: var(--svg-color--9e7765, #9E7765);
  stop-opacity: 0;
}

.ur78mwbxs {
  stop-color: var(--svg-color--654647, #654647);
}

.ut-a4zo6y {
  stop-color: var(--svg-color--685351, #685351);
  stop-opacity: 0;
}

.v_2gjcb5l {
  stop-color: var(--svg-color--4c3c39, #4C3C39);
}

.v1ass0bqn {
  d: path("m15.86 5.589l-.24.825c-.048.17.069.34.235.34h.353c.165 0 .282-.173.233-.34l-.238-.825c-.051-.183-.29-.183-.343 0");
}

.v3vg2fbhx {
  stop-color: var(--svg-color--af887b, #AF887B);
}

.vj4yuc0qg {
  stop-color: var(--svg-color--614440, #614440);
}

.vm3i05jbz {
  stop-color: var(--svg-color--765a55, #765A55);
}

.vzzhqfd0u {
  stop-color: var(--svg-color--2e1c2e, #2E1C2E);
}

.w48qw8bka {
  stop-color: var(--svg-color--8d5460, #8D5460);
}

.wbdnw-owo {
  stop-color: var(--svg-color--9e6a5c, #9E6A5C);
  stop-opacity: 0;
}

.wgp31zbmt {
  d: path("M15.05 5.284a.4.4 0 0 0-.385.506h.774a.403.403 0 0 0-.388-.506");
}

.wv5n4khjs {
  stop-color: var(--svg-color--532c3f, #532C3F);
}

.wwbz7ibcz {
  stop-color: var(--svg-color--462f5e, #462F5E);
}

.wysngjbll {
  stop-color: var(--svg-color--de5d25, #DE5D25);
  stop-opacity: 0;
}

.x7tdxqavt {
  stop-color: var(--svg-color--aa9ba7, #AA9BA7);
}

.x8_6e5b0q {
  stop-color: var(--svg-color--fb2d18, #FB2D18);
  stop-opacity: 0;
}

.xc3ukgbty {
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M16.031 7.21c-.228 0-.442-.054-.622-.148c-.061-.031-.128.038-.089.094a.85.85 0 0 0 .711.38a.85.85 0 0 0 .71-.38c.04-.058-.027-.125-.088-.094a1.34 1.34 0 0 1-.622.148Z");
}

.xc5jbxb7v {
  d: path("M18.298 6.185q.022-.394.042-.79c.18.025.32.192.32.394c0 .217-.162.394-.362.396");
}

.xqbp6db-u {
  stop-color: var(--svg-color--8a5f5c, #8A5F5C);
  stop-opacity: 0;
}

.xxn4m8bxd {
  stop-color: var(--svg-color--654647, #654647);
  stop-opacity: 0;
}

.xys9jruze {
  stop-color: var(--svg-color--604946, #604946);
  stop-opacity: 0;
}

.y-nukfwnq {
  stop-color: var(--svg-color--ff863c, #FF863C);
  stop-opacity: 0;
}

.y2mxoh-zc {
  stop-color: var(--svg-color--f16440, #F16440);
}

.y4_ytjb3b {
  stop-color: var(--svg-color--de5d25, #DE5D25);
}

.y4noiz6ri {
  stop-color: var(--svg-color--bf9980, #BF9980);
}

.y8l9uwbpv {
  stop-color: var(--svg-color--8a5c53, #8A5C53);
}

.yd6vs-kvu {
  stop-color: var(--svg-color--543f3c, #543F3C);
}

.yhl3rwbtd {
  d: path("M13.865 7.15a1.76 1.76 0 0 0 1.744 1.53h.847c.883 0 1.629-.653 1.744-1.53c.053-.845.107-1.687.146-2.532a.65.65 0 0 0-.62-.643h-.628c-.428 0-.816-.253-.992-.648a.3.3 0 0 0-.277-.188h-.57c-.83 0-1.5.68-1.5 1.517c0 .835.051 1.657.106 2.494");
}

.z3z2fqbpi {
  stop-color: var(--svg-color--635185, #635185);
}

.z9wedib1s {
  d: path("m13.047 16.011l.484 12.454h2l.238-9.524c0-.328.029-.86.262-.86c.212 0 .263.555.262.86l.238 9.524h2l.485-12.454z");
}

.zay0pib-e {
  stop-color: var(--svg-color--8d434a, #8D434A);
}

.zk_ep7bop {
  fill: var(--svg-color--462d2b, #462D2B);
  d: path("M17.707 4.572a.8.8 0 0 0-.31-.185c-.136-.043-.307-.054-.543-.025a.124.124 0 1 0 .03.247c.216-.027.348-.013.44.016a.6.6 0 0 1 .219.135a.124.124 0 1 0 .163-.188");
}

.znkgs0cxs {
  fill: var(--svg-color--a3776d, #A3776D);
  d: path("m15.86 5.589l-.24.825c-.048.17.069.34.235.34h.353c.165 0 .282-.173.233-.34l-.238-.825c-.051-.183-.29-.183-.343 0");
}

.zvhz6qbam {
  stop-color: var(--svg-color--c2987e, #C2987E);
  stop-opacity: 0;
}

.zvm05wbin {
  stop-color: var(--svg-color--7d4d5b, #7D4D5B);
}

</style>
