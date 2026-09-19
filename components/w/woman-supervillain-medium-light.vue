<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iLa6YhI)"><path fill="url(#iHafeNc)" clip-rule="evenodd" class="jo4bwlwnx"/><path fill="url(#iErn67d)" clip-rule="evenodd" class="jo4bwlwnx"/><path fill="url(#iy2PN0d)" clip-rule="evenodd" class="jo4bwlwnx"/><path fill="url(#iZkAFsd)" clip-rule="evenodd" class="jo4bwlwnx"/><path fill="url(#izjKupd)" clip-rule="evenodd" class="jo4bwlwnx"/><path fill="url(#iF68pQd)" clip-rule="evenodd" class="jo4bwlwnx"/><path fill="url(#ifGpmEe)" clip-rule="evenodd" class="jo4bwlwnx"/><path fill="url(#iIsoAFe)" clip-rule="evenodd" class="jo4bwlwnx"/><path fill="url(#ikI7a9c)" clip-rule="evenodd" class="jo4bwlwnx"/><path fill="url(#i5ohH9b)" clip-rule="evenodd" class="jo4bwlwnx"/><path fill="url(#iHRQTpb)" clip-rule="evenodd" class="jo4bwlwnx"/><path fill="url(#i46PDCe)" clip-rule="evenodd" class="jo4bwlwnx"/></g><g filter="url(#in7TAne)"><path fill="url(#ipB4wze)" class="cde83gbyf"/><path fill="url(#iwaMCeb)" class="cde83gbyf"/></g><g filter="url(#ifcfEVb)"><path fill="url(#iBbCMac)" class="guy-l8i4u"/><path fill="url(#ihaEXGD)" class="guy-l8i4u"/></g><path fill="url(#im8y0ud)" class="ovtssoo9d"/><path fill="url(#i8jvHcc)" class="ovtssoo9d"/><path fill="url(#ik3Gv5d)" class="ovtssoo9d"/><path fill="url(#iLQm0wd)" class="ovtssoo9d"/><path fill="url(#iB7n71d)" class="ovtssoo9d"/><path fill="url(#ikLYGwe)" class="ovtssoo9d"/><path fill="url(#is2F7EB)" class="ovtssoo9d"/><path fill="url(#iy8SgCb)" class="ovtssoo9d"/><path fill="url(#iRXxLCQ)" class="nlr2b0b3e"/><path fill="url(#iN7FqDd)" class="nlr2b0b3e"/><path fill="url(#iNo8F4b)" class="nlr2b0b3e"/><path fill="url(#i023yre)" class="nlr2b0b3e"/><path fill="url(#igP8HXb)" class="ywq3rybse"/><path fill="url(#iGDWOKd)" class="ywq3rybse"/><path fill="url(#igU2lPc)" class="ywq3rybse"/><path fill="url(#iHM1Gxy)" class="ywq3rybse"/><path fill="url(#iGv0Hme)" class="fmxprb3kl"/><path fill="url(#iU37A6d)" class="v-zmzdb7a"/><path fill="url(#ixuFddc)" class="scbtoqb3l"/><g filter="url(#imh07qd)"><path fill="url(#iMvcWeb)" class="n9rl7eb9e"/><path fill="url(#iH6h84d)" class="n9rl7eb9e"/><path fill="url(#iU3qU3c)" class="n9rl7eb9e"/><path fill="url(#i5LaWOc)" class="n9rl7eb9e"/><path fill="url(#idHef0b)" class="n9rl7eb9e"/></g><path class="rif9xsaam"/><path fill="url(#iIsS1Ly)" class="t-9escbhg"/><path fill="url(#iZnGBIt)" class="t-9escbhg"/><path class="n7di9tbyj"/><path fill="url(#inNGekb)" class="ry7w-jzeh"/><g filter="url(#irvH8TI)"><path fill="url(#i8wzKEe)" class="webuc209o"/><path fill="url(#ibJ79iY)" class="webuc209o"/><path fill="url(#izC0zQd)" class="webuc209o"/><path fill="url(#iupYhEe)" class="webuc209o"/><path fill="url(#iwF9pPc)" class="webuc209o"/><path fill="url(#iR7pifb)" class="webuc209o"/></g><g filter="url(#ieXQsre)"><path fill="url(#iuemmYc)" class="smjh2tnga"/></g><path fill="url(#iODYiyc)" class="so1nkxb-p"/><path fill="url(#i59Bn0b)" class="so1nkxb-p"/><path fill="url(#iLO3Mze)" class="rhtry876r"/><path fill="url(#i3zzRrc)" class="fdbkpwb0i"/><path fill="url(#iHG9jBb)" class="fdbkpwb0i"/><path fill="url(#ilB2d8Q)" class="zfgt8xbqv"/><path fill="url(#inPSJAb)" class="zfgt8xbqv"/><g filter="url(#ijpFuvc)"><circle fill="url(#ibcNsZc)" class="k4qku8r4h"/><circle fill="url(#iRCxL2V)" class="k4qku8r4h"/></g><ellipse fill="url(#i2IXanx)" transform="rotate(-31.445 16.554 23.454)" class="zjaspid3j"/><path fill="url(#iXOVwle)" class="gret9hftq"/><path fill="url(#ilFuIwt)" class="zemj31c-h"/><g filter="url(#iiKL9dx)"><path fill="url(#ivjzx6y)" class="hucc6ubqq"/></g><g filter="url(#izE7jCK)"><path fill="url(#iGAnjff)" class="dkvs4abdd"/><path fill="url(#iHMILUc)" class="dkvs4abdd"/></g><g filter="url(#iB32Dmd)"><path class="t8-qegvol"/><path fill="url(#iI8WrBc)" class="grrpgcblm"/></g><g filter="url(#icA1HJe)"><path class="xsedbebld"/><path fill="url(#iRnY2xe)" class="qif7a-btz"/></g><g filter="url(#in4p97c)"><path fill="url(#iWTfyad)" class="jc85bsesr"/><path fill="url(#icALRlb)" class="jc85bsesr"/><path fill="url(#inu8uMc)" class="jc85bsesr"/><path fill="url(#ig0Es9L)" class="jc85bsesr"/><path fill="url(#iKNsMsc)" class="jc85bsesr"/><path fill="url(#iZLXhOp)" class="jc85bsesr"/><path fill="url(#ilmaElc)" class="jc85bsesr"/></g><path fill="url(#iJPV8xc)" class="m2alobbun"/><path fill="url(#i0qP7Wc)" class="m2alobbun"/><g filter="url(#iLMEXmd)"><path class="rhtaf6b5f"/></g><g filter="url(#ikoTIeb)"><path class="elws0m8-v"/><path fill="url(#iq2ommh)" class="acv4f8b4w"/><path fill="url(#iegyZ0b)" class="acv4f8b4w"/><path fill="url(#i3Q8cZd)" class="acv4f8b4w"/></g><g filter="url(#iB5s1Gd)"><path fill="url(#iXWm2Hc)" class="yp9d-gbxi"/><path fill="url(#iQcwLMe)" class="yp9d-gbxi"/></g><g filter="url(#icaQhwD)"><path fill="url(#icPJRPe)" class="zw2ilpbyt"/><path fill="url(#iykfbyb)" class="zw2ilpbyt"/><path fill="url(#ih2qbke)" class="zw2ilpbyt"/></g><g filter="url(#iMkdiAe)"><path stroke="url(#iMhTfvc)" class="wwaczdc2t"/></g><g filter="url(#i96T6oc)"><path class="dbmwgnbxz"/></g><g filter="url(#iPo5ZHb)"><path fill="url(#ilLk6Bc)" class="t2mctqsyv"/><path fill="url(#iDCQaXb)" class="t2mctqsyv"/><path fill="url(#iDPnDBU)" class="t2mctqsyv"/></g><path fill="url(#iuthEcd)" class="t2mctqsyv"/><g filter="url(#iRypnPb)"><path class="h71978_ps"/></g><g filter="url(#iSdqBdb)"><path class="xtelscc3f"/></g><g filter="url(#ivZrZ8b)"><path stroke="url(#iapqV4b)" class="kkpooduhu"/></g><path class="a-3s2tcqp"/><defs><radialGradient id="iErn67d" cx="0" cy="0" r="1" gradientTransform="matrix(1.74318 -3.62044 8.25485 3.97456 20.791 16.417)" gradientUnits="userSpaceOnUse"><stop class="rjxj417_v"/><stop offset="1" class="p1sg1mumi"/></radialGradient><radialGradient id="iy2PN0d" cx="0" cy="0" r="1" gradientTransform="rotate(109.074 3.312 11.675)scale(5.77873 5.40927)" gradientUnits="userSpaceOnUse"><stop offset=".62" class="ta36f8b7v"/><stop offset="1" class="hcuenbefp"/></radialGradient><radialGradient id="iZkAFsd" cx="0" cy="0" r="1" gradientTransform="rotate(142.167 4.2 8.907)scale(3.98975 4.91117)" gradientUnits="userSpaceOnUse"><stop offset=".205" class="hxuphr-8h"/><stop offset="1" class="v-9s4u7ch"/></radialGradient><radialGradient id="izjKupd" cx="0" cy="0" r="1" gradientTransform="rotate(125.038 2.814 8.336)scale(1.78101 1.61886)" gradientUnits="userSpaceOnUse"><stop offset=".334" class="ybvptdnhb"/><stop offset="1" class="ue-yx0baa"/></radialGradient><radialGradient id="iF68pQd" cx="0" cy="0" r="1" gradientTransform="rotate(-167.428 6.409 4.014)scale(2.38706 3.50899)" gradientUnits="userSpaceOnUse"><stop offset=".226" class="sqmgyf2vi"/><stop offset="1" class="mvuactshi"/></radialGradient><radialGradient id="ifGpmEe" cx="0" cy="0" r="1" gradientTransform="matrix(2.16229 3.16788 -5.52839 3.77349 12.26 3.024)" gradientUnits="userSpaceOnUse"><stop class="vrnylccvf"/><stop offset="1" class="b442o21cz"/></radialGradient><radialGradient id="iIsoAFe" cx="0" cy="0" r="1" gradientTransform="rotate(132.51 9.73 7.176)scale(1.63713 2.28786)" gradientUnits="userSpaceOnUse"><stop class="di6ktzbyk"/><stop offset="1" class="ejv935bph"/></radialGradient><radialGradient id="ikI7a9c" cx="0" cy="0" r="1" gradientTransform="matrix(-1.84366 .53637 -1.16706 -4.01156 23.607 9.745)" gradientUnits="userSpaceOnUse"><stop class="kdig6mnba"/><stop offset="1" class="him6rrbhz"/></radialGradient><radialGradient id="i5ohH9b" cx="0" cy="0" r="1" gradientTransform="matrix(-3.15113 1.34089 -2.13644 -5.02072 23.339 12.528)" gradientUnits="userSpaceOnUse"><stop class="c2fnpwywz"/><stop offset="1" class="c5g3vhi-m"/></radialGradient><radialGradient id="iHRQTpb" cx="0" cy="0" r="1" gradientTransform="matrix(6.75 -3.875 4.08266 7.11173 18.458 16.078)" gradientUnits="userSpaceOnUse"><stop offset=".234" class="g8jmegbpc"/><stop offset="1" class="cpuls8tfr"/></radialGradient><radialGradient id="i46PDCe" cx="0" cy="0" r="1" gradientTransform="matrix(-4.50001 -4.3125 5.29597 -5.52625 13.458 15.765)" gradientUnits="userSpaceOnUse"><stop offset=".256" class="bnk-4ablg"/><stop offset="1" class="l5fzepbio"/></radialGradient><radialGradient id="ipB4wze" cx="0" cy="0" r="1" gradientTransform="rotate(-77.425 20.294 12.622)scale(12.4871 3.86791)" gradientUnits="userSpaceOnUse"><stop class="fd6px-b3x"/><stop offset="1" class="zblf_actk"/></radialGradient><radialGradient id="iwaMCeb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.6437 5.87086 -1.1886 -.33278 5.881 24.588)" gradientUnits="userSpaceOnUse"><stop class="v_v98qact"/><stop offset="1" class="n7j357b5a"/></radialGradient><radialGradient id="iBbCMac" cx="0" cy="0" r="1" gradientTransform="rotate(-108.435 25.24 4.192)scale(14.6255 4.53031)" gradientUnits="userSpaceOnUse"><stop class="fd6px-b3x"/><stop offset="1" class="zblf_actk"/></radialGradient><radialGradient id="ihaEXGD" cx="0" cy="0" r="1" gradientTransform="matrix(1.6437 5.87086 -1.1886 .33278 26.118 24.589)" gradientUnits="userSpaceOnUse"><stop class="v_v98qact"/><stop offset="1" class="n7j357b5a"/></radialGradient><radialGradient id="im8y0ud" cx="0" cy="0" r="1" gradientTransform="matrix(-7.65624 8.81247 -8.58004 -7.4543 21.15 19.9)" gradientUnits="userSpaceOnUse"><stop class="m48igd19d"/><stop offset="1" class="m9hq76bya"/></radialGradient><radialGradient id="i8jvHcc" cx="0" cy="0" r="1" gradientTransform="rotate(123.254 3.415 15.196)scale(12.0566 23.4242)" gradientUnits="userSpaceOnUse"><stop offset=".612" class="zojxemb8i"/><stop offset="1" class="fypjwijgc"/></radialGradient><radialGradient id="ik3Gv5d" cx="0" cy="0" r="1" gradientTransform="matrix(-6.03124 1.09998 -3.62517 -19.87702 24.15 22.738)" gradientUnits="userSpaceOnUse"><stop class="uc4vypayb"/><stop offset="1" class="ib49rus2q"/></radialGradient><radialGradient id="iB7n71d" cx="0" cy="0" r="1" gradientTransform="matrix(.21874 4.4375 -3.52577 .1738 21.339 17.838)" gradientUnits="userSpaceOnUse"><stop offset=".787" class="yhvjw36xj"/><stop offset="1" class="qf-zh-bgi"/></radialGradient><radialGradient id="ikLYGwe" cx="0" cy="0" r="1" gradientTransform="matrix(.34375 5.52507 -4.70428 .29269 10.588 17.212)" gradientUnits="userSpaceOnUse"><stop offset=".648" class="kr4wgsbgo"/><stop offset=".991" class="vat9yt_ey"/></radialGradient><radialGradient id="is2F7EB" cx="0" cy="0" r="1" gradientTransform="matrix(0 9.34375 -.50337 0 8.838 20.587)" gradientUnits="userSpaceOnUse"><stop offset=".584" class="i3hug6b7s"/><stop offset="1" class="bkplcs5-b"/></radialGradient><radialGradient id="iRXxLCQ" cx="0" cy="0" r="1" gradientTransform="matrix(3.625 -.1875 .66954 12.9444 23.432 25.369)" gradientUnits="userSpaceOnUse"><stop offset=".247" class="cx3r1wb0p"/><stop offset="1" class="b5r8fe9sv"/></radialGradient><radialGradient id="iN7FqDd" cx="0" cy="0" r="1" gradientTransform="matrix(2.02342 3.79718 -2.02268 1.07783 23.252 20.213)" gradientUnits="userSpaceOnUse"><stop class="dkr4vta7s"/><stop offset="1" class="bfw_o9sgk"/></radialGradient><radialGradient id="iNo8F4b" cx="0" cy="0" r="1" gradientTransform="matrix(3.9375 -1.15625 3.32754 11.33163 23.588 25.65)" gradientUnits="userSpaceOnUse"><stop offset=".676" class="j0a0weg0v"/><stop offset="1" class="a--e2mwlv"/></radialGradient><radialGradient id="igP8HXb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.89844 -.93751 4.08965 -17.00586 8.861 27.056)" gradientUnits="userSpaceOnUse"><stop offset=".424" class="klsvjl5ds"/><stop offset=".808" class="n5x1trblw"/></radialGradient><radialGradient id="iGDWOKd" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.59375 -1.54958 0 9.213 20.119)" gradientUnits="userSpaceOnUse"><stop offset=".145" class="iek0mvbvg"/><stop offset="1" class="ksp1sznci"/></radialGradient><radialGradient id="igU2lPc" cx="0" cy="0" r="1" gradientTransform="matrix(-.46538 0 0 -10.5767 9.044 28.807)" gradientUnits="userSpaceOnUse"><stop offset=".473" class="a-lmuhb3j"/><stop offset="1" class="xrr4vbcci"/></radialGradient><radialGradient id="iHM1Gxy" cx="0" cy="0" r="1" gradientTransform="matrix(-5.4375 -.46874 1.19963 -13.91599 9.807 30.4)" gradientUnits="userSpaceOnUse"><stop offset=".919" class="e1q0bl71g"/><stop offset=".983" class="cvb6_wfpd"/></radialGradient><radialGradient id="iGv0Hme" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.75 3.76953 0 16.068 21.15)" gradientUnits="userSpaceOnUse"><stop offset=".625" class="f4t2p6bdy"/><stop offset=".921" class="n6ixpp1jb"/></radialGradient><radialGradient id="iU37A6d" cx="0" cy="0" r="1" gradientTransform="matrix(-.92969 0 0 -.7732 22.994 15.79)" gradientUnits="userSpaceOnUse"><stop class="e9rx7xb_x"/><stop offset="1" class="mxm28cb7d"/></radialGradient><radialGradient id="ixuFddc" cx="0" cy="0" r="1" gradientTransform="matrix(-.92969 0 0 -.7732 25.03 15.79)" gradientUnits="userSpaceOnUse"><stop class="e9rx7xb_x"/><stop offset="1" class="mxm28cb7d"/></radialGradient><radialGradient id="iH6h84d" cx="0" cy="0" r="1" gradientTransform="rotate(20.097 -35.744 58.912)scale(3.67385 7.23049)" gradientUnits="userSpaceOnUse"><stop class="ajmnmmbez"/><stop offset="1" class="ie12c-fkv"/></radialGradient><radialGradient id="iU3qU3c" cx="0" cy="0" r="1" gradientTransform="matrix(-2.25043 3.70058 -.73486 -.44689 26.744 16.547)" gradientUnits="userSpaceOnUse"><stop class="yog48s40z"/><stop offset="1" class="c50kycc4s"/></radialGradient><radialGradient id="i5LaWOc" cx="0" cy="0" r="1" gradientTransform="matrix(5.6875 0 0 .79688 20.12 15.869)" gradientUnits="userSpaceOnUse"><stop class="ungg6q-mb"/><stop offset="1" class="bozoj1btu"/></radialGradient><radialGradient id="idHef0b" cx="0" cy="0" r="1" gradientTransform="matrix(3.52963 0 0 2.27341 18.523 16.312)" gradientUnits="userSpaceOnUse"><stop class="ge69a97wz"/><stop offset="1" class="jd18rptxw"/></radialGradient><radialGradient id="iIsS1Ly" cx="0" cy="0" r="1" gradientTransform="matrix(.36719 .25757 -.32848 .46827 9.08 15.525)" gradientUnits="userSpaceOnUse"><stop class="f9nu08mzt"/><stop offset="1" class="y06th9bdt"/></radialGradient><radialGradient id="iZnGBIt" cx="0" cy="0" r="1" gradientTransform="matrix(.956 0 0 1.08294 9.174 15.783)" gradientUnits="userSpaceOnUse"><stop offset=".587" class="yr3p0jbaj"/><stop offset="1" class="n1_6kac4r"/></radialGradient><radialGradient id="inNGekb" cx="0" cy="0" r="1" gradientTransform="rotate(13.799 -61.21 36.106)scale(.68782 .87718)" gradientUnits="userSpaceOnUse"><stop class="kejp2n55e"/><stop offset="1" class="ecn2fkbpq"/></radialGradient><radialGradient id="izC0zQd" cx="0" cy="0" r="1" gradientTransform="matrix(2.72977 4.35939 -.30397 .19034 5.358 16.431)" gradientUnits="userSpaceOnUse"><stop class="do8d1irdg"/><stop offset="1" class="slx6fqref"/></radialGradient><radialGradient id="iupYhEe" cx="0" cy="0" r="1" gradientTransform="rotate(-125.167 12.001 7.394)scale(3.52673 3.449)" gradientUnits="userSpaceOnUse"><stop class="e33ikws-z"/><stop offset="1" class="ll-hxrboz"/></radialGradient><radialGradient id="iwF9pPc" cx="0" cy="0" r="1" gradientTransform="matrix(-7.31239 0 0 -2.83509 14.65 16.244)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="sb_6z1bpd"/><stop offset="1" class="cbuctgb-f"/></radialGradient><radialGradient id="iR7pifb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.66406 0 0 -.3962 12.572 15.863)" gradientUnits="userSpaceOnUse"><stop class="qsjdql87s"/><stop offset="1" class="u05m0u9vr"/></radialGradient><radialGradient id="iuemmYc" cx="0" cy="0" r="1" gradientTransform="rotate(163.78 7.323 9.537)scale(2.99183 5.25441)" gradientUnits="userSpaceOnUse"><stop class="sfxco_bym"/><stop offset="1" class="dhddxpm2q"/></radialGradient><radialGradient id="iODYiyc" cx="0" cy="0" r="1" gradientTransform="rotate(147.753 8.53 11.508)scale(.93297 1.08283)" gradientUnits="userSpaceOnUse"><stop offset=".125" class="fdilk9b4n"/><stop offset=".796" class="zhe9zhdzx"/></radialGradient><radialGradient id="i59Bn0b" cx="0" cy="0" r="1" gradientTransform="matrix(-.79688 -.1328 .1252 -.75127 21.775 16.916)" gradientUnits="userSpaceOnUse"><stop offset=".705" class="p63xbfaao"/><stop offset="1" class="qxsf0l9dp"/></radialGradient><radialGradient id="iLO3Mze" cx="0" cy="0" r="1" gradientTransform="matrix(-.78906 .46094 -.5319 -.91052 23.963 16.666)" gradientUnits="userSpaceOnUse"><stop offset=".125" class="fdilk9b4n"/><stop offset=".963" class="zhe9zhdzx"/></radialGradient><radialGradient id="i3zzRrc" cx="0" cy="0" r="1" gradientTransform="rotate(35.635 -21.796 20.914)scale(.89396 1.0943)" gradientUnits="userSpaceOnUse"><stop offset=".069" class="jipovxgfv"/><stop offset="1" class="ogttk6b6n"/></radialGradient><radialGradient id="iHG9jBb" cx="0" cy="0" r="1" gradientTransform="matrix(.86375 -.48466 .4507 .80322 8.182 17.049)" gradientUnits="userSpaceOnUse"><stop offset=".512" class="k1yq73b8m"/><stop offset="1" class="qaycvn_cp"/></radialGradient><radialGradient id="ilB2d8Q" cx="0" cy="0" r="1" gradientTransform="matrix(.72656 .5625 -.70389 .90919 10.182 16.634)" gradientUnits="userSpaceOnUse"><stop class="t55apucyo"/><stop offset="1" class="ogttk6b6n"/></radialGradient><radialGradient id="inPSJAb" cx="0" cy="0" r="1" gradientTransform="matrix(.86375 -.52344 .50555 .83423 10.26 17.103)" gradientUnits="userSpaceOnUse"><stop offset=".512" class="k1yq73b8m"/><stop offset="1" class="qaycvn_cp"/></radialGradient><radialGradient id="ibcNsZc" cx="0" cy="0" r="1" gradientTransform="rotate(114.286 1.102 16.938)scale(2.81128 2.59835)" gradientUnits="userSpaceOnUse"><stop class="av5bbdb4i"/><stop offset="1" class="l1led_brw"/></radialGradient><radialGradient id="iRCxL2V" cx="0" cy="0" r="1" gradientTransform="matrix(.70313 .8125 -1.6896 1.46215 14.713 22.431)" gradientUnits="userSpaceOnUse"><stop class="tyoz-v6go"/><stop offset="1" class="ptuohkesm"/></radialGradient><radialGradient id="iGAnjff" cx="0" cy="0" r="1" gradientTransform="matrix(2.48905 -1.13139 1.38138 3.03902 20.137 11.036)" gradientUnits="userSpaceOnUse"><stop offset=".572" class="qmmvvysmp"/><stop offset=".905" class="epx_cgb2c"/></radialGradient><radialGradient id="iHMILUc" cx="0" cy="0" r="1" gradientTransform="matrix(.9973 .28494 -.1498 .52432 21.16 8.815)" gradientUnits="userSpaceOnUse"><stop class="aso-vybjw"/><stop offset="1" class="krvd34mtu"/></radialGradient><radialGradient id="iI8WrBc" cx="0" cy="0" r="1" gradientTransform="rotate(-20.298 40.61 -52.376)scale(1.30459)" gradientUnits="userSpaceOnUse"><stop offset=".71" class="la61skb4q"/><stop offset="1" class="urs_pbb4x"/></radialGradient><radialGradient id="iRnY2xe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.21686 0 0 -1.164 11.431 10.597)" gradientUnits="userSpaceOnUse"><stop offset=".573" class="prydr8bcy"/><stop offset="1" class="ybx_6zbxd"/></radialGradient><radialGradient id="iWTfyad" cx="0" cy="0" r="1" gradientTransform="matrix(-6.50358 2.99902 -4.01413 -8.70492 18.957 10.06)" gradientUnits="userSpaceOnUse"><stop class="uy3z2gbbp"/><stop offset="1" class="gvh2bspmv"/></radialGradient><radialGradient id="icALRlb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.10973 1.11592 -.94678 -1.78996 17.998 10.757)" gradientUnits="userSpaceOnUse"><stop class="j8hkuac-d"/><stop offset="1" class="cre_5tbhq"/></radialGradient><radialGradient id="inu8uMc" cx="0" cy="0" r="1" gradientTransform="matrix(.8369 -4.04513 5.13253 1.06187 13.917 16.842)" gradientUnits="userSpaceOnUse"><stop class="t6jzi2-1t"/><stop offset="1" class="i3g5qu-9r"/></radialGradient><radialGradient id="ig0Es9L" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.99338 -9.47995 0 16.098 9.772)" gradientUnits="userSpaceOnUse"><stop offset=".638" class="af6x7obpr"/><stop offset="1" class="fol85thxe"/></radialGradient><radialGradient id="iKNsMsc" cx="0" cy="0" r="1" gradientTransform="rotate(172.34 7.953 6.757)scale(5.78399 9.95825)" gradientUnits="userSpaceOnUse"><stop offset=".813" class="zzstxpr9j"/><stop offset="1" class="irzp_cb7o"/></radialGradient><radialGradient id="iZLXhOp" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.15077 1.65436 0 18.4 9.64)" gradientUnits="userSpaceOnUse"><stop offset=".259" class="mt3h7fbpd"/><stop offset="1" class="wcr1klbjh"/></radialGradient><radialGradient id="ilmaElc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.36 1.55865 0 14.18 9.728)" gradientUnits="userSpaceOnUse"><stop class="r-jog4w_t"/><stop offset="1" class="xjkdvxqyn"/></radialGradient><radialGradient id="iJPV8xc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.34695 0 0 -4.43421 21.194 11.129)" gradientUnits="userSpaceOnUse"><stop class="yhs2bn2id"/><stop offset="1" class="g1fw3-bff"/></radialGradient><radialGradient id="i0qP7Wc" cx="0" cy="0" r="1" gradientTransform="matrix(1.15625 4.21875 -8.71783 2.38933 13.598 4.553)" gradientUnits="userSpaceOnUse"><stop class="mih5kfbap"/><stop offset="1" class="kqfxh5bnm"/></radialGradient><radialGradient id="iq2ommh" cx="0" cy="0" r="1" gradientTransform="matrix(-.69746 -2.44974 1.40177 -.3991 16.882 11.855)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="xjug-415a"/><stop offset="1" class="bd8jqdorr"/></radialGradient><radialGradient id="iXWm2Hc" cx="0" cy="0" r="1" gradientTransform="matrix(1.93486 2.6818 -5.32876 3.84458 10.14 4.348)" gradientUnits="userSpaceOnUse"><stop offset=".403" class="hi5yi9bqv"/><stop offset="1" class="d8y_5zbge"/></radialGradient><radialGradient id="iQcwLMe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.87735 2.48068 -1.9455 -1.47233 13.383 4.583)" gradientUnits="userSpaceOnUse"><stop class="g6mu4o3fz"/><stop offset="1" class="dx30lgbdy"/></radialGradient><radialGradient id="icPJRPe" cx="0" cy="0" r="1" gradientTransform="matrix(-2.11195 4.39145 -6.24446 -3.00311 18.009 2.672)" gradientUnits="userSpaceOnUse"><stop offset=".595" class="iz4jcxg0j"/><stop offset="1" class="qflnpfbur"/></radialGradient><radialGradient id="iykfbyb" cx="0" cy="0" r="1" gradientTransform="matrix(-.8568 3.20722 -5.72497 -1.5294 18.411 3.845)" gradientUnits="userSpaceOnUse"><stop class="mv8kv7beo"/><stop offset="1" class="g_ulzrbqz"/></radialGradient><radialGradient id="ih2qbke" cx="0" cy="0" r="1" gradientTransform="rotate(-119.068 11.433 -.46)scale(7.21046 6.45439)" gradientUnits="userSpaceOnUse"><stop offset=".891" class="w58maet4h"/><stop offset=".979" class="drxq29wnr"/></radialGradient><radialGradient id="ilLk6Bc" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.38819 -12.4445 0 16.032 6.498)" gradientUnits="userSpaceOnUse"><stop offset=".467" class="c7yfkfb_x"/><stop offset=".878" class="ly-mhyl9x"/></radialGradient><radialGradient id="iDCQaXb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.18748 -4.36884 3.96591 -1.07796 13.025 13.255)" gradientUnits="userSpaceOnUse"><stop class="cycj4pb5c"/><stop offset="1" class="xkd2ooi4v"/></radialGradient><radialGradient id="iDPnDBU" cx="0" cy="0" r="1" gradientTransform="matrix(-5.25001 4.51317 -4.6352 -5.39197 23.432 6.498)" gradientUnits="userSpaceOnUse"><stop class="mbbg-bcay"/><stop offset="1" class="psls5zbwz"/><stop offset="1" class="vyoyvyblw"/></radialGradient><radialGradient id="iapqV4b" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.57932 2.45245 0 16.245 14.23)" gradientUnits="userSpaceOnUse"><stop offset=".25" class="zxzg1ds7g"/><stop offset="1" class="ucq5r0blk"/></radialGradient><filter id="iLa6YhI" width="15.268" height="15.768" x="8.589" y="1.319" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.886275 0 0 0 0 0.698039 0 0 0 0 0.607843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1008"/></filter><filter id="in7TAne" width="7.981" height="13.148" x="1.991" y="16.783" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.392157 0 0 0 0 0.364706 0 0 0 0 0.423529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1008"/></filter><filter id="ifcfEVb" width="7.981" height="13.148" x="22.028" y="16.783" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.392157 0 0 0 0 0.364706 0 0 0 0 0.423529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1008"/></filter><filter id="imh07qd" width="9.078" height="5.683" x="17.916" y="15.619" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.803922 0 0 0 0 0.101961 0 0 0 0 0.32549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1008"/></filter><filter id="irvH8TI" width="8.928" height="5.533" x="5.258" y="15.763" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.823529 0 0 0 0 0.113725 0 0 0 0 0.337255 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1008"/></filter><filter id="ieXQsre" width="4.194" height="5.942" x="13.971" y="12.924" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.32549 0 0 0 0 0.227451 0 0 0 0 0.439216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1008"/></filter><filter id="ijpFuvc" width="3.465" height="3.465" x="14.33" y="22.209" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.819608 0 0 0 0 0.145098 0 0 0 0 0.364706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1008"/></filter><filter id="iiKL9dx" width="3.368" height="3.468" x="9.803" y="8.988" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.858824 0 0 0 0 0.635294 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1008"/></filter><filter id="izE7jCK" width="3.218" height="3.468" x="19.316" y="8.738" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.827451 0 0 0 0 0.568627 0 0 0 0 0.505882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1008"/></filter><filter id="iB32Dmd" width="3.148" height="3.148" x="19.351" y="9.023" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1008" stdDeviation=".25"/></filter><filter id="icA1HJe" width="2.948" height="2.948" x="9.957" y="9.123" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1008" stdDeviation=".2"/></filter><filter id="in4p97c" width="10.191" height="11.127" x="11.003" y="5.69" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.745098 0 0 0 0 0.486275 0 0 0 0 0.384314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1008"/></filter><filter id="iLMEXmd" width="2.877" height="3.682" x="14.497" y="9.592" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1008" stdDeviation=".25"/></filter><filter id="ikoTIeb" width="2.377" height="3.182" x="14.909" y="9.703" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1008" stdDeviation=".125"/></filter><filter id="iB5s1Gd" width="4.287" height="5.25" x="9.839" y="3.571" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1008" stdDeviation=".25"/></filter><filter id="icaQhwD" width="8.914" height="5.78" x="12.781" y="2.522" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1008" stdDeviation=".125"/></filter><filter id="iMkdiAe" width="1.145" height="2.31" x="12.907" y="3.755" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1008" stdDeviation=".1"/></filter><filter id="i96T6oc" width="13.891" height="7.06" x="9.087" y="7.182" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1008" stdDeviation=".375"/></filter><filter id="iPo5ZHb" width="15.159" height="7.107" x="8.403" y="6.298" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.188235 0 0 0 0 0.152941 0 0 0 0 0.223529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1008"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".25"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.364706 0 0 0 0 0.333333 0 0 0 0 0.4 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1008" result="effect2_innerShadow_4002_1008"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.270588 0 0 0 0 0.215686 0 0 0 0 0.317647 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_1008" result="effect3_innerShadow_4002_1008"/></filter><filter id="iRypnPb" width="2.192" height="1.627" x="17.223" y="8.923" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.360784 0 0 0 0 0.505882 0 0 0 0 0.301961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1008"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.596078 0 0 0 0 0.886275 0 0 0 0 0.380392 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1008" result="effect2_innerShadow_4002_1008"/></filter><filter id="iSdqBdb" width="2.192" height="1.627" x="12.726" y="8.923" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.360784 0 0 0 0 0.505882 0 0 0 0 0.301961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1008"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.596078 0 0 0 0 0.886275 0 0 0 0 0.380392 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1008" result="effect2_innerShadow_4002_1008"/></filter><filter id="ivZrZ8b" width="2.476" height="1.695" x="15.615" y="12.644" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1008" stdDeviation=".05"/></filter><linearGradient id="iHafeNc" x1="20.791" x2="13.986" y1="3.644" y2="16.249" gradientUnits="userSpaceOnUse"><stop class="p6otu2-6b"/><stop offset="1" class="q5mih6mme"/></linearGradient><linearGradient id="iLQm0wd" x1="23.236" x2="22.979" y1="29.931" y2="29.931" gradientUnits="userSpaceOnUse"><stop class="y-so25ixd"/><stop offset="1" class="zxe--8tbm"/></linearGradient><linearGradient id="iy8SgCb" x1="8.857" x2="8.994" y1="29.931" y2="29.931" gradientUnits="userSpaceOnUse"><stop class="cgymddbwl"/><stop offset="1" class="gn957lbyv"/></linearGradient><linearGradient id="i023yre" x1="23.252" x2="23.486" y1="29.931" y2="29.931" gradientUnits="userSpaceOnUse"><stop class="uq-m7pb0g"/><stop offset="1" class="d-jm4nrou"/></linearGradient><linearGradient id="iMvcWeb" x1="25.746" x2="20.292" y1="15.869" y2="20.081" gradientUnits="userSpaceOnUse"><stop class="lt42vtw3b"/><stop offset="1" class="xjh9cc18k"/></linearGradient><linearGradient id="i8wzKEe" x1="9.772" x2="9.772" y1="15.863" y2="20.65" gradientUnits="userSpaceOnUse"><stop class="ujur1qtze"/><stop offset="1" class="ctoai6naw"/></linearGradient><linearGradient id="ibJ79iY" x1="9.772" x2="9.772" y1="15.494" y2="17.462" gradientUnits="userSpaceOnUse"><stop offset=".071" class="g2wrz_okq"/><stop offset="1" class="uhjz0cbil"/></linearGradient><linearGradient id="i2IXanx" x1="16.985" x2="15.947" y1="23.068" y2="23.972" gradientUnits="userSpaceOnUse"><stop offset=".453" class="vc--wpv5i"/><stop offset=".905" class="stui2mbih"/></linearGradient><linearGradient id="iXOVwle" x1="8.913" x2="23.289" y1="15.517" y2="15.517" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="ilFuIwt" x1="8.913" x2="23.289" y1="15.486" y2="15.486" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="ivjzx6y" x1="9.803" x2="12.762" y1="10.684" y2="10.684" gradientUnits="userSpaceOnUse"><stop class="nka4--b6e"/><stop offset="1" class="aps1jhbfc"/></linearGradient><linearGradient id="iegyZ0b" x1="15.052" x2="15.906" y1="11.873" y2="11.977" gradientUnits="userSpaceOnUse"><stop class="urkjpbftr"/><stop offset="1" class="lwjatlajn"/></linearGradient><linearGradient id="i3Q8cZd" x1="16.098" x2="16.098" y1="12.727" y2="12.117" gradientUnits="userSpaceOnUse"><stop class="dvyniwihb"/><stop offset="1" class="e5pm1bciq"/></linearGradient><linearGradient id="iMhTfvc" x1="13.207" x2="13.752" y1="4.399" y2="5.672" gradientUnits="userSpaceOnUse"><stop class="gjbrx7i8b"/><stop offset="1" class="zcr9jykfw"/></linearGradient><linearGradient id="iuthEcd" x1="10.732" x2="10.979" y1="10.328" y2="10.168" gradientUnits="userSpaceOnUse"><stop offset=".102" class="a5a8_w8qp"/><stop offset=".478" class="ydi8a_bcj"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-supervillain-medium-light" /></template>
<style>
.a--e2mwlv {
  stop-color: var(--svg-color--614b90, #614B90);
}

.a-3s2tcqp {
  fill: var(--svg-color--88014e, #88014E);
  d: path("M17.75 12.861c-.614.807-1.368.893-1.872.925c-.085.005-.12.104-.051.154c.377.269.857.292 1.342.09c.51-.213.733-.703.747-1.123c.003-.092-.11-.119-.165-.046");
}

.a-lmuhb3j {
  stop-color: var(--svg-color--7560a8, #7560A8);
}

.a5a8_w8qp {
  stop-color: var(--svg-color--5e5158, #5E5158);
}

.acv4f8b4w {
  d: path("m15.716 10.236l-.532 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.53-1.7c-.115-.377-.646-.377-.765 0");
}

.af6x7obpr {
  stop-color: var(--svg-color--c48887, #C48887);
  stop-opacity: 0;
}

.ajmnmmbez {
  stop-color: var(--svg-color--ee205c, #EE205C);
}

.aps1jhbfc {
  stop-color: var(--svg-color--b47860, #B47860);
}

.aso-vybjw {
  stop-color: var(--svg-color--d59566, #D59566);
}

.av5bbdb4i {
  stop-color: var(--svg-color--ff499d, #FF499D);
}

.b442o21cz {
  stop-color: var(--svg-color--dcc893, #DCC893);
  stop-opacity: 0;
}

.b5r8fe9sv {
  stop-color: var(--svg-color--735ca8, #735CA8);
}

.bd8jqdorr {
  stop-color: var(--svg-color--fdc9a8, #FDC9A8);
  stop-opacity: 0;
}

.bfw_o9sgk {
  stop-color: var(--svg-color--8977bc, #8977BC);
  stop-opacity: 0;
}

.bkplcs5-b {
  stop-color: var(--svg-color--615181, #615181);
  stop-opacity: 0;
}

.bnk-4ablg {
  stop-color: var(--svg-color--a97a54, #A97A54);
}

.bozoj1btu {
  stop-color: var(--svg-color--e7547f, #E7547F);
  stop-opacity: 0;
}

.c2fnpwywz {
  stop-color: var(--svg-color--fff4bc, #FFF4BC);
}

.c50kycc4s {
  stop-color: var(--svg-color--ff5292, #FF5292);
  stop-opacity: 0;
}

.c5g3vhi-m {
  stop-color: var(--svg-color--fff4bc, #FFF4BC);
  stop-opacity: 0;
}

.c7yfkfb_x {
  stop-color: var(--svg-color--453753, #453753);
}

.cbuctgb-f {
  stop-color: var(--svg-color--dd225e, #DD225E);
  stop-opacity: 0;
}

.cde83gbyf {
  d: path("M1.99 29.931h3.532l4.25-8.75l-3.648-4.398C2.709 21.22 1.99 27.166 1.99 29.93");
}

.cgymddbwl {
  stop-color: var(--svg-color--3f2563, #3F2563);
}

.cpuls8tfr {
  stop-color: var(--svg-color--e19b78, #E19B78);
  stop-opacity: 0;
}

.cre_5tbhq {
  stop-color: var(--svg-color--ffc89e, #FFC89E);
  stop-opacity: 0;
}

.ctoai6naw {
  stop-color: var(--svg-color--f93362, #F93362);
}

.cvb6_wfpd {
  stop-color: var(--svg-color--443063, #443063);
}

.cx3r1wb0p {
  stop-color: var(--svg-color--8b74c8, #8B74C8);
}

.cycj4pb5c {
  stop-color: var(--svg-color--322f37, #322F37);
}

.d-jm4nrou {
  stop-color: var(--svg-color--7757b7, #7757B7);
  stop-opacity: 0;
}

.d8y_5zbge {
  stop-color: var(--svg-color--daa88f, #DAA88F);
}

.dbmwgnbxz {
  fill: var(--svg-color--ac7064, #AC7064);
  d: path("m9.897 8.415l3.235 4.806a.617.617 0 0 0 .975.06l1.45-1.655a.4.4 0 0 0 .085-.152c.08-.24.253-.577.388-.577c.154 0 .313.337.393.577a.4.4 0 0 0 .086.152l1.449 1.655a.617.617 0 0 0 .975-.06l3.235-4.806c.175-.258-.057-.559-.354-.466l-4.82 1.51a.5.5 0 0 0-.279.25c-.177.342-.275-.005-.485 0c-.21-.005-.703.342-.88 0a.5.5 0 0 0-.278-.25L10.25 7.95c-.297-.093-.528.208-.354.466");
}

.dhddxpm2q {
  stop-color: var(--svg-color--6a41a7, #6A41A7);
}

.di6ktzbyk {
  stop-color: var(--svg-color--ffffbf, #FFFFBF);
}

.dkr4vta7s {
  stop-color: var(--svg-color--8977bc, #8977BC);
}

.dkvs4abdd {
  d: path("M20.925 12.206a1.61 1.61 0 1 0 0-3.218a1.61 1.61 0 0 0 0 3.218");
}

.do8d1irdg {
  stop-color: var(--svg-color--e1658e, #E1658E);
}

.drxq29wnr {
  stop-color: var(--svg-color--dac493, #DAC493);
}

.dvyniwihb {
  stop-color: var(--svg-color--c57f82, #C57F82);
}

.dx30lgbdy {
  stop-color: var(--svg-color--fee2a9, #FEE2A9);
  stop-opacity: 0;
}

.e1q0bl71g {
  stop-color: var(--svg-color--5f4d85, #5F4D85);
  stop-opacity: 0;
}

.e33ikws-z {
  stop-color: var(--svg-color--ff4574, #FF4574);
}

.e5pm1bciq {
  stop-color: var(--svg-color--c57f82, #C57F82);
  stop-opacity: 0;
}

.e9rx7xb_x {
  stop-color: var(--svg-color--967bc2, #967BC2);
}

.ecn2fkbpq {
  stop-color: var(--svg-color--79659c, #79659C);
  stop-opacity: 0;
}

.ejv935bph {
  stop-color: var(--svg-color--ffffbf, #FFFFBF);
  stop-opacity: 0;
}

.elws0m8-v {
  fill: var(--svg-color--efb696, #EFB696);
  d: path("m15.716 10.236l-.532 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.53-1.7c-.115-.377-.646-.377-.765 0");
}

.epx_cgb2c {
  stop-color: var(--svg-color--f6c3a3, #F6C3A3);
}

.f4t2p6bdy {
  stop-color: var(--svg-color--a5ee69, #A5EE69);
}

.f9nu08mzt {
  stop-color: var(--svg-color--6b5b8d, #6B5B8D);
}

.fd6px-b3x {
  stop-color: var(--svg-color--593f75, #593F75);
}

.fdbkpwb0i {
  d: path("M7.987 16.896c0 .211.237.3.53.3c.291 0 .528-.112.528-.3a.53.53 0 0 0-1.058 0");
}

.fdilk9b4n {
  stop-color: var(--svg-color--977fd1, #977FD1);
}

.fmxprb3kl {
  d: path("m15.575 21.261l-2.98-4.595h6.946l-2.958 4.594a.6.6 0 0 1-1.008.001");
}

.fol85thxe {
  stop-color: var(--svg-color--ae7178, #AE7178);
}

.ft5dv1b6b {
  fill: none;
}

.fypjwijgc {
  stop-color: var(--svg-color--5b3e84, #5B3E84);
}

.g_ulzrbqz {
  stop-color: var(--svg-color--ffffc0, #FFFFC0);
  stop-opacity: 0;
}

.g1fw3-bff {
  stop-color: var(--svg-color--f4c099, #F4C099);
  stop-opacity: 0;
}

.g2wrz_okq {
  stop-color: var(--svg-color--bb4566, #BB4566);
}

.g6mu4o3fz {
  stop-color: var(--svg-color--fee2a9, #FEE2A9);
}

.g8jmegbpc {
  stop-color: var(--svg-color--b48860, #B48860);
}

.ge69a97wz {
  stop-color: var(--svg-color--961241, #961241);
}

.gjbrx7i8b {
  stop-color: var(--svg-color--ebce91, #EBCE91);
}

.gn957lbyv {
  stop-color: var(--svg-color--3f2563, #3F2563);
  stop-opacity: 0;
}

.gret9hftq {
  d: path("M16.453 15.487c.25.01.51.03.77.05c-.26-.02-.51-.04-.77-.05");
}

.grrpgcblm {
  d: path("M20.925 11.67a1.074 1.074 0 1 0 0-2.147a1.074 1.074 0 0 0 0 2.148");
}

.guy-l8i4u {
  d: path("M30.01 29.931h-3.532l-4.25-8.75l3.648-4.398c3.415 4.437 4.133 10.383 4.133 13.148");
}

.gvh2bspmv {
  stop-color: var(--svg-color--d39b88, #D39B88);
}

.h_j9u0wvt {
  stop-color: var(--svg-color--e6e6e6, #E6E6E6);
}

.h71978_ps {
  fill: var(--svg-color--92d55c, #92D55C);
  d: path("m19.064 8.992l-1.608.592c-.154.057-.235.23-.146.368c.22.342.656.692 1.344.489c.65-.192.792-.814.755-1.257c-.014-.167-.188-.25-.345-.192");
}

.hcuenbefp {
  stop-color: var(--svg-color--c7897d, #C7897D);
  stop-opacity: 0;
}

.hi5yi9bqv {
  stop-color: var(--svg-color--daa88f, #DAA88F);
  stop-opacity: 0;
}

.him6rrbhz {
  stop-color: var(--svg-color--fffabe, #FFFABE);
  stop-opacity: 0;
}

.hucc6ubqq {
  d: path("M11.412 12.206a1.61 1.61 0 1 0 0-3.218a1.61 1.61 0 0 0 0 3.218");
}

.hxuphr-8h {
  stop-color: var(--svg-color--cf987b, #CF987B);
}

.i3g5qu-9r {
  stop-color: var(--svg-color--b97783, #B97783);
  stop-opacity: 0;
}

.i3hug6b7s {
  stop-color: var(--svg-color--655586, #655586);
}

.ib49rus2q {
  stop-color: var(--svg-color--72599f, #72599F);
  stop-opacity: 0;
}

.ie12c-fkv {
  stop-color: var(--svg-color--ee205c, #EE205C);
  stop-opacity: 0;
}

.iek0mvbvg {
  stop-color: var(--svg-color--563680, #563680);
}

.irzp_cb7o {
  stop-color: var(--svg-color--e3ab91, #E3AB91);
}

.iz4jcxg0j {
  stop-color: var(--svg-color--f0c6a3, #F0C6A3);
  stop-opacity: 0;
}

.j0a0weg0v {
  stop-color: var(--svg-color--614b90, #614B90);
  stop-opacity: 0;
}

.j8hkuac-d {
  stop-color: var(--svg-color--ffc89e, #FFC89E);
}

.jc85bsesr {
  d: path("m11.013 9.069l-.01-.306c.02-.949.574-1.316.81-1.439l.051-.02l.051-.02a2.3 2.3 0 0 0 1.19-1.235l.082-.194a.264.264 0 0 1 .461-.051a3.86 3.86 0 0 0 3.19 1.673h3.22c.18 0 1.082.088 1.136 1.332l-.12 3.074c-.123 2.802-2.311 4.684-4.982 4.684s-4.86-1.882-4.984-4.684z");
}

.jd18rptxw {
  stop-color: var(--svg-color--d31c55, #D31C55);
  stop-opacity: 0;
}

.jipovxgfv {
  stop-color: var(--svg-color--7d64a6, #7D64A6);
}

.jo4bwlwnx {
  fill-rule: evenodd;
  d: path("M23.283 12.007a3.24 3.24 0 0 0 .324-1.427a3.3 3.3 0 0 0-.269-1.306h.006a3 3 0 0 0-.281-.513l-.002-.003a3.24 3.24 0 0 1-.527-1.77v-.011a3.3 3.3 0 0 0-3.299-3.3a.54.54 0 0 1-.455-.232a3.3 3.3 0 0 0-2.682-1.376a3.3 3.3 0 0 0-2.682 1.376a.56.56 0 0 1-.455.233h-.085a3.3 3.3 0 0 0-3.216 3.3v.01a3.24 3.24 0 0 1-.526 1.771l-.002.004a3.3 3.3 0 0 0-.22 3.245a.52.52 0 0 1 0 .455a3.213 3.213 0 0 0 2.894 4.625h8.582a3.213 3.213 0 0 0 3.218-3.218c0-.506-.121-.982-.324-1.407a.51.51 0 0 1 0-.455m-12.26-2.673h-.012l1.198 2.356c.124 2.802 1.217 0 3.889 0s3.836 3.12 3.96.317l1.135-3.198c-.053-1.244-.955-1.332-1.136-1.332h-3.22a3.86 3.86 0 0 1-3.189-1.673a.264.264 0 0 0-.461.051l-.082.194a2.3 2.3 0 0 1-1.292 1.275c-.236.123-.79.49-.81 1.439l.01.306z");
}

.k1yq73b8m {
  stop-color: var(--svg-color--67416e, #67416E);
  stop-opacity: 0;
}

.k4qku8r4h {
  cx: 16.063px;
  cy: 23.941px;
  r: 1.732px;
}

.kdig6mnba {
  stop-color: var(--svg-color--fffabe, #FFFABE);
}

.kejp2n55e {
  stop-color: var(--svg-color--79659c, #79659C);
}

.kkpooduhu {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M17.75 12.861c-.614.807-1.368.893-1.872.925c-.085.005-.12.104-.051.154c.377.269.857.292 1.342.09c.51-.213.733-.703.747-1.123c.003-.092-.11-.119-.165-.046Z");
}

.klsvjl5ds {
  stop-color: var(--svg-color--7056ae, #7056AE);
}

.kqfxh5bnm {
  stop-color: var(--svg-color--be7c5a, #BE7C5A);
  stop-opacity: 0;
}

.kr4wgsbgo {
  stop-color: var(--svg-color--533179, #533179);
}

.krvd34mtu {
  stop-color: var(--svg-color--d59566, #D59566);
  stop-opacity: 0;
}

.ksp1sznci {
  stop-color: var(--svg-color--6d55a5, #6D55A5);
  stop-opacity: 0;
}

.kt__1405u {
  stop-color: var(--svg-color--ccc, #CCC);
}

.l1led_brw {
  stop-color: var(--svg-color--df1d5a, #DF1D5A);
}

.l5fzepbio {
  stop-color: var(--svg-color--a97a54, #A97A54);
  stop-opacity: 0;
}

.la61skb4q {
  stop-color: var(--svg-color--e3a280, #E3A280);
  stop-opacity: 0;
}

.ll-hxrboz {
  stop-color: var(--svg-color--ff4574, #FF4574);
  stop-opacity: 0;
}

.lt42vtw3b {
  stop-color: var(--svg-color--ff3880, #FF3880);
}

.lwjatlajn {
  stop-color: var(--svg-color--d1987a, #D1987A);
  stop-opacity: 0;
}

.ly-mhyl9x {
  stop-color: var(--svg-color--4a474e, #4A474E);
}

.m2alobbun {
  d: path("M11.01 9.334h.013l-.01-.265l-.01-.306c.02-.949.574-1.316.81-1.439l.051-.02l.051-.02a2.3 2.3 0 0 0 1.19-1.235l.082-.194a.264.264 0 0 1 .461-.051a3.86 3.86 0 0 0 3.19 1.673h3.22c.18 0 1.082.088 1.136 1.332l-.12 3.074c-.123 2.802-2.311 4.684-4.982 4.684s-4.86-1.882-4.984-4.684z");
}

.m48igd19d {
  stop-color: var(--svg-color--735aa1, #735AA1);
}

.m9hq76bya {
  stop-color: var(--svg-color--64468e, #64468E);
}

.mbbg-bcay {
  stop-color: var(--svg-color--625570, #625570);
}

.mih5kfbap {
  stop-color: var(--svg-color--be7c5a, #BE7C5A);
}

.mt3h7fbpd {
  stop-color: var(--svg-color--e3a48e, #E3A48E);
}

.mv8kv7beo {
  stop-color: var(--svg-color--ffffc0, #FFFFC0);
}

.mvuactshi {
  stop-color: var(--svg-color--c49070, #C49070);
  stop-opacity: 0;
}

.mxm28cb7d {
  stop-color: var(--svg-color--735784, #735784);
}

.n1_6kac4r {
  stop-color: var(--svg-color--745b84, #745B84);
}

.n5x1trblw {
  stop-color: var(--svg-color--73629d, #73629D);
}

.n6ixpp1jb {
  stop-color: var(--svg-color--7da646, #7DA646);
}

.n7di9tbyj {
  fill: var(--svg-color--64417a, #64417A);
  d: path("M6.984 15.902c0 .222.249.316.556.316c.306 0 .555-.119.555-.316a.555.555 0 0 0-1.11 0");
}

.n7j357b5a {
  stop-color: var(--svg-color--230f39, #230F39);
  stop-opacity: 0;
}

.n9rl7eb9e {
  d: path("M24.635 19.865c-.75 1.082-1.856 1.976-4.008 1.05c-1.836-.788-2.711-3.268-2.711-5.046l8.203.023c.652 0 .752.442.492.856a424 424 0 0 1-1.976 3.117");
}

.nka4--b6e {
  stop-color: var(--svg-color--c48b78, #C48B78);
}

.nlr2b0b3e {
  d: path("M23.252 18.088v11.843h4.273c-.205-3.069-.605-5.613-1.406-7.563c-.772-1.881-1.77-3.268-2.867-4.28");
}

.ogttk6b6n {
  stop-color: var(--svg-color--774ca5, #774CA5);
}

.ovtssoo9d {
  d: path("M4.588 29.931h22.937c-.205-3.069-.605-5.613-1.406-7.563c-2.444-5.955-7.159-6.625-10.062-6.484c-2.904-.141-7.618.529-10.063 6.484c-.8 1.95-1.2 4.494-1.406 7.563");
}

.p1sg1mumi {
  stop-color: var(--svg-color--ffc3a8, #FFC3A8);
  stop-opacity: 0;
}

.p63xbfaao {
  stop-color: var(--svg-color--85527f, #85527F);
  stop-opacity: 0;
}

.p6otu2-6b {
  stop-color: var(--svg-color--ffffbe, #FFFFBE);
}

.prydr8bcy {
  stop-color: var(--svg-color--b0725a, #B0725A);
  stop-opacity: 0;
}

.psls5zbwz {
  stop-color: var(--svg-color--625570, #625570);
  stop-opacity: 0;
}

.ptuohkesm {
  stop-color: var(--svg-color--cd2172, #CD2172);
  stop-opacity: 0;
}

.q5mih6mme {
  stop-color: var(--svg-color--e5ae90, #E5AE90);
}

.qaycvn_cp {
  stop-color: var(--svg-color--67416e, #67416E);
}

.qf-zh-bgi {
  stop-color: var(--svg-color--755da2, #755DA2);
  stop-opacity: 0;
}

.qflnpfbur {
  stop-color: var(--svg-color--f0c6a3, #F0C6A3);
}

.qif7a-btz {
  d: path("M11.432 11.67a1.074 1.074 0 1 0 0-2.147a1.074 1.074 0 0 0 0 2.148");
}

.qmmvvysmp {
  stop-color: var(--svg-color--e1a792, #E1A792);
}

.qsjdql87s {
  stop-color: var(--svg-color--ae495e, #AE495E);
}

.qxsf0l9dp {
  stop-color: var(--svg-color--85527f, #85527F);
}

.r-jog4w_t {
  stop-color: var(--svg-color--c2847a, #C2847A);
}

.rhtaf6b5f {
  fill: var(--svg-color--c28178, #C28178);
  d: path("m15.706 10.374l-.684 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.531-1.7c-.114-.376-.493-.376-.613 0");
}

.rhtry876r {
  d: path("M24.115 16.904c0 .21-.237.3-.53.3c-.291 0-.528-.113-.528-.3a.53.53 0 0 1 1.058 0");
}

.rif9xsaam {
  fill: var(--svg-color--5c396f, #5C396F);
  d: path("M9.02 15.902c0 .222.248.316.555.316c.306 0 .555-.119.555-.316a.555.555 0 0 0-1.11 0");
}

.rjxj417_v {
  stop-color: var(--svg-color--f9bfa4, #F9BFA4);
}

.ry7w-jzeh {
  d: path("M6.984 15.902c0 .222.249.316.556.316c.306 0 .555-.119.555-.316a.555.555 0 0 0-1.11 0");
}

.sb_6z1bpd {
  stop-color: var(--svg-color--761032, #761032);
}

.scbtoqb3l {
  d: path("M25.118 15.91c0 .221-.249.316-.555.316s-.556-.12-.556-.316a.555.555 0 0 1 1.11 0");
}

.sfxco_bym {
  stop-color: var(--svg-color--8a63c7, #8A63C7);
}

.slx6fqref {
  stop-color: var(--svg-color--e1658e, #E1658E);
  stop-opacity: 0;
}

.smjh2tnga {
  d: path("M13.971 15.02a2.097 2.097 0 0 1 4.195 0v1.549c0 1.37-.94 2.097-2.098 2.097s-2.097-.696-2.097-2.097z");
}

.so1nkxb-p {
  d: path("M22.037 16.904c0 .292-.237.367-.53.367c-.292 0-.529-.075-.529-.367a.53.53 0 0 1 1.06 0");
}

.sqmgyf2vi {
  stop-color: var(--svg-color--c49070, #C49070);
}

.stui2mbih {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0;
}

.t-9escbhg {
  d: path("M9.02 15.902c0 .222.248.316.555.316c.306 0 .555-.119.555-.316a.555.555 0 0 0-1.11 0");
}

.t2mctqsyv {
  d: path("m8.576 7.085l3.932 5.84a.75.75 0 0 0 1.185.074l1.76-2.011a.5.5 0 0 0 .105-.186c.098-.291.307-.7.471-.7c.188 0 .38.409.478.7a.5.5 0 0 0 .104.186l1.761 2.011a.75.75 0 0 0 1.185-.073l3.932-5.84c.212-.314-.069-.68-.43-.567L17.2 8.355a.6.6 0 0 0-.338.304c-.216.414-.578.624-.833.63c-.254-.006-.61-.216-.826-.63a.6.6 0 0 0-.338-.304l-5.86-1.836c-.36-.113-.641.253-.429.566");
}

.t55apucyo {
  stop-color: var(--svg-color--725d9d, #725D9D);
}

.t6jzi2-1t {
  stop-color: var(--svg-color--b97783, #B97783);
}

.t8-qegvol {
  fill: var(--svg-color--e5aa8b, #E5AA8B);
  d: path("M20.925 11.67a1.074 1.074 0 1 0 0-2.147a1.074 1.074 0 0 0 0 2.148");
}

.ta36f8b7v {
  stop-color: var(--svg-color--c7897d, #C7897D);
}

.tyoz-v6go {
  stop-color: var(--svg-color--cd2172, #CD2172);
}

.u05m0u9vr {
  stop-color: var(--svg-color--ae495e, #AE495E);
  stop-opacity: 0;
}

.uc4vypayb {
  stop-color: var(--svg-color--8371ae, #8371AE);
}

.ucq5r0blk {
  stop-color: var(--svg-color--cd9790, #CD9790);
  stop-opacity: 0;
}

.ue-yx0baa {
  stop-color: var(--svg-color--c58e72, #C58E72);
  stop-opacity: 0;
}

.uhjz0cbil {
  stop-color: var(--svg-color--e62f68, #E62F68);
  stop-opacity: 0;
}

.ujur1qtze {
  stop-color: var(--svg-color--db2a69, #DB2A69);
}

.ungg6q-mb {
  stop-color: var(--svg-color--e7547f, #E7547F);
}

.uq-m7pb0g {
  stop-color: var(--svg-color--573a88, #573A88);
}

.urkjpbftr {
  stop-color: var(--svg-color--d1987a, #D1987A);
}

.urs_pbb4x {
  stop-color: var(--svg-color--e3a280, #E3A280);
}

.uy3z2gbbp {
  stop-color: var(--svg-color--ffc59d, #FFC59D);
}

.v_v98qact {
  stop-color: var(--svg-color--230f39, #230F39);
}

.v-9s4u7ch {
  stop-color: var(--svg-color--cf987b, #CF987B);
  stop-opacity: 0;
}

.v-zmzdb7a {
  d: path("M23.083 15.91c0 .221-.25.316-.556.316s-.555-.12-.555-.316a.555.555 0 1 1 1.11 0");
}

.vat9yt_ey {
  stop-color: var(--svg-color--614290, #614290);
  stop-opacity: 0;
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.vrnylccvf {
  stop-color: var(--svg-color--dcc893, #DCC893);
}

.vyoyvyblw {
  stop-color: var(--svg-color--6c587a, #6C587A);
  stop-opacity: 0;
}

.w58maet4h {
  stop-color: var(--svg-color--dac493, #DAC493);
  stop-opacity: 0;
}

.wcr1klbjh {
  stop-color: var(--svg-color--e3a48e, #E3A48E);
  stop-opacity: 0;
}

.webuc209o {
  d: path("M7.467 19.859c.75 1.082 1.856 1.976 4.008 1.051c1.836-.789 2.711-3.269 2.711-5.047l-8.203.024c-.652 0-.752.441-.492.855c.646 1.03 1.519 2.406 1.976 3.117");
}

.wwaczdc2t {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M13.207 4.055c.023.243.234 1.156.544 1.71");
}

.xjh9cc18k {
  stop-color: var(--svg-color--ff3669, #FF3669);
}

.xjkdvxqyn {
  stop-color: var(--svg-color--c2847a, #C2847A);
  stop-opacity: 0;
}

.xjug-415a {
  stop-color: var(--svg-color--fdc9a8, #FDC9A8);
}

.xkd2ooi4v {
  stop-color: var(--svg-color--322f37, #322F37);
  stop-opacity: 0;
}

.xrr4vbcci {
  stop-color: var(--svg-color--7560a8, #7560A8);
  stop-opacity: 0;
}

.xsedbebld {
  fill: var(--svg-color--b47a6c, #B47A6C);
  d: path("M11.432 11.67a1.074 1.074 0 1 0 0-2.147a1.074 1.074 0 0 0 0 2.148");
}

.xtelscc3f {
  fill: var(--svg-color--92d55c, #92D55C);
  d: path("m13.077 8.992l1.607.592c.155.057.236.23.147.368c-.22.342-.656.692-1.345.489c-.65-.192-.792-.814-.755-1.257c.014-.167.188-.25.346-.192");
}

.y-so25ixd {
  stop-color: var(--svg-color--50387f, #50387F);
}

.y06th9bdt {
  stop-color: var(--svg-color--6b5b8d, #6B5B8D);
  stop-opacity: 0;
}

.ybvptdnhb {
  stop-color: var(--svg-color--c58e72, #C58E72);
}

.ybx_6zbxd {
  stop-color: var(--svg-color--b0725a, #B0725A);
}

.ydi8a_bcj {
  stop-color: var(--svg-color--5e5158, #5E5158);
  stop-opacity: 0;
}

.yhs2bn2id {
  stop-color: var(--svg-color--f4c099, #F4C099);
}

.yhvjw36xj {
  stop-color: var(--svg-color--563079, #563079);
}

.yog48s40z {
  stop-color: var(--svg-color--ff5292, #FF5292);
}

.yp9d-gbxi {
  d: path("M11.204 4.583c.62-.553 1.517-.559 2.02-.47l.402 1.291c-.257-.039-.486.05-.68.235c-.452 1.676-2.161 1.425-2.497 2.682c-.15-1.492-.318-2.783.755-3.738");
}

.yr3p0jbaj {
  stop-color: var(--svg-color--5d3970, #5D3970);
  stop-opacity: 0;
}

.ywq3rybse {
  d: path("M8.861 18.088v11.843H4.588c.205-3.069.605-5.613 1.406-7.563c.772-1.881 1.77-3.268 2.867-4.28");
}

.zblf_actk {
  stop-color: var(--svg-color--372543, #372543);
}

.zcr9jykfw {
  stop-color: var(--svg-color--e6bd9f, #E6BD9F);
}

.zemj31c-h {
  d: path("M16.123 15.487h-.04c.1 0 .19 0 .29.01c-.08-.01-.17-.01-.25-.01");
}

.zfgt8xbqv {
  d: path("M10.065 16.896c0 .292.237.367.53.367c.292 0 .528-.075.528-.367a.53.53 0 1 0-1.058 0");
}

.zhe9zhdzx {
  stop-color: var(--svg-color--7a4c9c, #7A4C9C);
}

.zjaspid3j {
  cx: 16.554px;
  cy: 23.454px;
  rx: 0.552px;
  ry: 0.695px;
}

.zojxemb8i {
  stop-color: var(--svg-color--5b3e84, #5B3E84);
  stop-opacity: 0;
}

.zw2ilpbyt {
  d: path("M15.495 2.806c-1.133-.25-2.347.956-2.464 1.375c1.542 3.62 3.91 3.275 6.537 2.983c1.572-.175 1.743.542 1.877.889c-.436-4.057-3.37-4.677-5.95-5.247");
}

.zxe--8tbm {
  stop-color: var(--svg-color--50387f, #50387F);
  stop-opacity: 0;
}

.zxzg1ds7g {
  stop-color: var(--svg-color--cd9790, #CD9790);
}

.zzstxpr9j {
  stop-color: var(--svg-color--e3ab91, #E3AB91);
  stop-opacity: 0;
}

</style>
