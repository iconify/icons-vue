<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iRWORoS)" class="b4oa6hbjp"/><path fill="url(#ioi0Kod)" class="cssihgbwg"/><path fill="url(#iAJIpsb)" class="cssihgbwg"/><path class="fxdv5lbkc"/><path fill="url(#i10pxld)" class="o60qitbpe"/><path fill="url(#iZexCld)" class="o60qitbpe"/><path fill="url(#iqLRTLc)" class="o60qitbpe"/><g filter="url(#iJkZ8Uz)"><path fill="url(#iLCRVOb)" class="usa015b5s"/></g><g filter="url(#iEfHrwb)"><path class="c318rfbui"/></g><g filter="url(#iGMjP2b)"><path fill="url(#ieGlbdd)" clip-rule="evenodd" class="g57dj_1-v"/></g><g filter="url(#iAQ5bIN)"><path fill="url(#ifMh0pe)" clip-rule="evenodd" class="dw6-41bxk"/></g><path class="xxfzimbqy"/><path fill="url(#iCXtP3X)" class="pymhrccao"/><path fill="url(#i6L8kee)" class="pymhrccao"/><path fill="url(#iVOZcQd)" class="pymhrccao"/><path fill="url(#i3TXVWb)" class="pymhrccao"/><path fill="url(#inf3Byd)" class="pymhrccao"/><path class="bwty5ybud"/><path fill="url(#iSwdehc)" class="xg19asgle"/><path fill="url(#i572bYb)" class="xg19asgle"/><path fill="url(#iiBzfye)" class="xg19asgle"/><path fill="url(#izrkykc)" class="xg19asgle"/><path fill="url(#i20wmqd)" class="xg19asgle"/><path fill="url(#ih0Rlub)" class="xg19asgle"/><rect transform="rotate(25.409 21.155 13.208)" class="lkwppxbql"/><rect fill="url(#ifCpDeb)" transform="rotate(25.409 21.155 13.208)" class="cspcopyxb"/><rect fill="url(#ioRKkPe)" transform="rotate(25.409 21.155 13.208)" class="cspcopyxb"/><path fill="url(#ijEjxFc)" class="ajk-yeb_a"/><path fill="url(#iQbm2Oc)" class="ajk-yeb_a"/><path fill="url(#iKupLdb)" class="ajk-yeb_a"/><path fill="url(#ibR0s5c)" class="c78259byf"/><path fill="url(#ixuhhxe)" class="c78259byf"/><path fill="url(#iQg0tND)" class="c78259byf"/><path fill="url(#idQHxvc)" class="qskg2u8et"/><path fill="url(#iMbCqAd)" class="qskg2u8et"/><g filter="url(#i0lx0hi)"><path clip-rule="evenodd" class="l38vou-0b"/></g><g filter="url(#imytV1c)"><path class="hg75w0bei"/></g><path fill="url(#iooWPDd)" class="usdmtuopw"/><path fill="url(#imN8Ece)" class="usdmtuopw"/><g filter="url(#iEoPnlS)"><path stroke="url(#it821mc)" class="f1re9tbmg"/></g><path fill="url(#iVDhENd)" class="ln_qsvbil"/><path fill="url(#i7u0hzb)" class="t7t36bb2z"/><path fill="url(#iefpZye)" class="t7t36bb2z"/><path fill="url(#iQIV1Ib)" class="t7t36bb2z"/><path fill="url(#iAc6BFc)" class="qhk1lkbyv"/><path fill="url(#isgnbDs)" class="qhk1lkbyv"/><path fill="url(#iOdV9ic)" class="qhk1lkbyv"/><path class="vd1hiwckb"/><path fill="url(#ipZmAHc)" class="zq5er1b8z"/><path class="cdupweb4v"/><g filter="url(#ilANucI)"><path fill="url(#iIwRIuc)" class="h-6fqb-jl"/></g><g filter="url(#iIPBnGc)"><path fill="url(#i24UOPc)" class="r9c671bap"/><path fill="url(#iewqA1d)" class="g2f02ucyq"/></g><g filter="url(#iofbFqd)"><path stroke="url(#iRNokae)" class="eaol6sc8a"/><path stroke="url(#iSpQGWc)" class="eaol6sc8a"/></g><g filter="url(#iIuYXnr)"><path class="fe01f8bxk"/></g><g filter="url(#itWixac)"><path class="wcc2bluii"/></g><defs><radialGradient id="iRWORoS" cx="0" cy="0" r="1" gradientTransform="matrix(-8.25 6.43749 -5.94882 -7.62374 28.627 21.5)" gradientUnits="userSpaceOnUse"><stop class="z9p88n4li"/><stop offset="1" class="qu-rxnact"/></radialGradient><radialGradient id="iAJIpsb" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.25 -2.01563 0 27.814 17.938)" gradientUnits="userSpaceOnUse"><stop class="tetb36znx"/><stop offset="1" class="mjae__bbd"/></radialGradient><radialGradient id="iZexCld" cx="0" cy="0" r="1" gradientTransform="rotate(157.751 10.847 3.69)scale(2.22841 4.74135)" gradientUnits="userSpaceOnUse"><stop offset=".481" class="b-mv_-jcb"/><stop offset="1" class="v59256asn"/></radialGradient><radialGradient id="iqLRTLc" cx="0" cy="0" r="1" gradientTransform="matrix(.32812 2.98438 -.50734 .05578 20.752 .86)" gradientUnits="userSpaceOnUse"><stop offset=".288" class="hxq43kbnk"/><stop offset="1" class="q4ehhl8ug"/></radialGradient><radialGradient id="iLCRVOb" cx="0" cy="0" r="1" gradientTransform="matrix(3.25 3.40625 -3.96363 3.78181 19.596 6.375)" gradientUnits="userSpaceOnUse"><stop class="c0hqs9jgc"/><stop offset="1" class="dwc664bvb"/></radialGradient><radialGradient id="ieGlbdd" cx="0" cy="0" r="1" gradientTransform="rotate(151.783 6.755 7.628)scale(2.18107 6.10648)" gradientUnits="userSpaceOnUse"><stop offset=".256" class="jby0r9b2o"/><stop offset="1" class="vixtmqora"/></radialGradient><radialGradient id="ifMh0pe" cx="0" cy="0" r="1" gradientTransform="rotate(150.678 5.367 7.964)scale(2.66165 7.63701)" gradientUnits="userSpaceOnUse"><stop offset=".256" class="jby0r9b2o"/><stop offset="1" class="vixtmqora"/></radialGradient><radialGradient id="i6L8kee" cx="0" cy="0" r="1" gradientTransform="matrix(0 -8.32499 31.8869 0 30.002 18.497)" gradientUnits="userSpaceOnUse"><stop offset=".08" class="n_majobgc"/><stop offset="1" class="i9da4mlgb"/></radialGradient><radialGradient id="iVOZcQd" cx="0" cy="0" r="1" gradientTransform="matrix(0 12.9922 -13.8743 0 29.502 5.562)" gradientUnits="userSpaceOnUse"><stop offset=".978" class="f5op-db1p"/><stop offset="1" class="p0my23bet"/></radialGradient><radialGradient id="i3TXVWb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.65625 3.40625 0 26.22 5.656)" gradientUnits="userSpaceOnUse"><stop offset=".21" class="isg8qrbyl"/><stop offset="1" class="mswmpi_ln"/></radialGradient><radialGradient id="inf3Byd" cx="0" cy="0" r="1" gradientTransform="matrix(2.1875 -3.71875 1.154 .67882 20.47 2.25)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="f92mc8b8d"/><stop offset="1" class="szo256bqp"/></radialGradient><radialGradient id="iSwdehc" cx="0" cy="0" r="1" gradientTransform="matrix(-.46875 3.1875 -3.36293 -.49455 18.127 21.406)" gradientUnits="userSpaceOnUse"><stop offset=".44" class="c935kubli"/><stop offset="1" class="tc-eqkbkl"/></radialGradient><radialGradient id="i572bYb" cx="0" cy="0" r="1" gradientTransform="rotate(155.042 9.68 12.714)scale(2.07371 2.38629)" gradientUnits="userSpaceOnUse"><stop offset=".102" class="jl-1u5bfr"/><stop offset="1" class="td79j7bjm"/></radialGradient><radialGradient id="iiBzfye" cx="0" cy="0" r="1" gradientTransform="matrix(4.28125 .52344 -.73073 5.9767 13.315 22.375)" gradientUnits="userSpaceOnUse"><stop offset=".021" class="x9w8qi-jn"/><stop offset="1" class="b4enoxk7f"/></radialGradient><radialGradient id="izrkykc" cx="0" cy="0" r="1" gradientTransform="matrix(1.4375 -3.71875 2.17154 .83942 21.283 25.625)" gradientUnits="userSpaceOnUse"><stop offset=".468" class="p3vjkybbp"/><stop offset="1" class="ljqluf2zv"/></radialGradient><radialGradient id="i20wmqd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.10937 2.25782 -1.47378 -.72413 16.377 20.64)" gradientUnits="userSpaceOnUse"><stop offset=".623" class="fsnpkqb3g"/><stop offset="1" class="hlv2pqbyv"/></radialGradient><radialGradient id="ih0Rlub" cx="0" cy="0" r="1" gradientTransform="matrix(-.56251 2.03125 -1.45908 -.40406 17.83 21.375)" gradientUnits="userSpaceOnUse"><stop offset=".431" class="qf3ch0b8m"/><stop offset="1" class="nj7d8jb1b"/></radialGradient><radialGradient id="ioRKkPe" cx="0" cy="0" r="1" gradientTransform="rotate(116.86 7.579 13.969)scale(2.06445 1.97258)" gradientUnits="userSpaceOnUse"><stop class="s05ajackq"/><stop offset="1" class="pp8v3-b-z"/></radialGradient><radialGradient id="ijEjxFc" cx="0" cy="0" r="1" gradientTransform="rotate(147.572 8.061 12.435)scale(2.29023 3.42612)" gradientUnits="userSpaceOnUse"><stop class="jirdmbbmq"/><stop offset=".928" class="o1jtj9b1y"/></radialGradient><radialGradient id="iQbm2Oc" cx="0" cy="0" r="1" gradientTransform="matrix(1.23147 -.56064 .71722 1.5754 19.957 22.5)" gradientUnits="userSpaceOnUse"><stop class="p69lpr5tx"/><stop offset="1" class="ntnqt37wf"/></radialGradient><radialGradient id="iKupLdb" cx="0" cy="0" r="1" gradientTransform="matrix(1.0098 4.1052 -2.79361 .68718 19.428 18.671)" gradientUnits="userSpaceOnUse"><stop offset=".867" class="xnhjstb2c"/><stop offset=".949" class="ltwe578dp"/></radialGradient><radialGradient id="ibR0s5c" cx="0" cy="0" r="1" gradientTransform="matrix(-2.0059 1.30528 -1.9722 -3.03078 20.216 18.646)" gradientUnits="userSpaceOnUse"><stop class="lj4kaubvr"/><stop offset="1" class="q3ysfbbce"/></radialGradient><radialGradient id="ixuhhxe" cx="0" cy="0" r="1" gradientTransform="rotate(135.546 5.974 13.514)scale(3.48863 6.50366)" gradientUnits="userSpaceOnUse"><stop offset=".618" class="ntnqt37wf"/><stop offset="1" class="znrqz3bnl"/></radialGradient><radialGradient id="iQg0tND" cx="0" cy="0" r="1" gradientTransform="matrix(1.7769 5.30926 -4.27366 1.4303 17.342 17.818)" gradientUnits="userSpaceOnUse"><stop offset=".887" class="injzqbc-i"/><stop offset=".97" class="gw3s7dbyz"/></radialGradient><radialGradient id="idQHxvc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.48813 1.5654 -2.19026 -3.48131 17.99 18.997)" gradientUnits="userSpaceOnUse"><stop class="lj4kaubvr"/><stop offset="1" class="y1en5cbdq"/></radialGradient><radialGradient id="iMbCqAd" cx="0" cy="0" r="1" gradientTransform="rotate(-86.517 20.051 2.68)scale(1.8002 3.61142)" gradientUnits="userSpaceOnUse"><stop offset=".095" class="xfq469bnl"/><stop offset="1" class="wtzd4lbuc"/></radialGradient><radialGradient id="imN8Ece" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.253 2.26733 0 30.08 11.347)" gradientUnits="userSpaceOnUse"><stop class="xsbe7ibsl"/><stop offset="1" class="bsq48580e"/></radialGradient><radialGradient id="iVDhENd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.08594 0 0 -2.32812 30.096 13.64)" gradientUnits="userSpaceOnUse"><stop class="w5du49byz"/><stop offset="1" class="cnkl7hbdv"/></radialGradient><radialGradient id="iefpZye" cx="0" cy="0" r="1" gradientTransform="rotate(113.199 -.095 18.44)scale(.47757 4.82093)" gradientUnits="userSpaceOnUse"><stop offset=".073" class="libsxlbtq"/><stop offset=".629" class="bzemojb9x"/></radialGradient><radialGradient id="iOdV9ic" cx="0" cy="0" r="1" gradientTransform="rotate(113.806 -.376 19.057)scale(1.16131 4.175)" gradientUnits="userSpaceOnUse"><stop offset=".207" class="l8_cxvb0x"/><stop offset="1" class="z9kltqbui"/></radialGradient><radialGradient id="ipZmAHc" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.36233 -2.16693 0 26.359 6.754)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="i24UOPc" cx="0" cy="0" r="1" gradientTransform="matrix(-.32813 -.53906 .98203 -.59777 26.115 7.004)" gradientUnits="userSpaceOnUse"><stop offset=".208" class="ezbem3b1x"/><stop offset=".79" class="kumz7j9en"/></radialGradient><radialGradient id="iewqA1d" cx="0" cy="0" r="1" gradientTransform="matrix(-.45084 -.82655 .77084 -.42045 26.192 7.197)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><linearGradient id="ioi0Kod" x1="30.314" x2="28.846" y1="19.156" y2="19.156" gradientUnits="userSpaceOnUse"><stop class="gyn7j9reu"/><stop offset="1" class="air8zsgnr"/></linearGradient><linearGradient id="i10pxld" x1="21.658" x2="21.658" y1="14.531" y2="9.781" gradientUnits="userSpaceOnUse"><stop class="nfkrwq-tu"/><stop offset="1" class="ie7cb3b5b"/></linearGradient><linearGradient id="iCXtP3X" x1="21.252" x2="23.408" y1="9.375" y2="9.281" gradientUnits="userSpaceOnUse"><stop class="wcmcdsdip"/><stop offset="1" class="i8wdd_rin"/></linearGradient><linearGradient id="ifCpDeb" x1="21.331" x2="22.083" y1="18.534" y2="15.973" gradientUnits="userSpaceOnUse"><stop offset=".159" class="jve2rcqoj"/><stop offset="1" class="b8gv4_dtn"/></linearGradient><linearGradient id="iooWPDd" x1="29.298" x2="29.298" y1="6.853" y2="11.347" gradientUnits="userSpaceOnUse"><stop class="jmna7zq9j"/><stop offset=".339" class="naer3jz1i"/></linearGradient><linearGradient id="it821mc" x1="27.689" x2="28.783" y1="13.906" y2="13.347" gradientUnits="userSpaceOnUse"><stop class="o-rmrib1p"/><stop offset="1" class="nl6v52b0i"/></linearGradient><linearGradient id="i7u0hzb" x1="12.552" x2="18.666" y1="25.289" y2="27.923" gradientUnits="userSpaceOnUse"><stop class="r4pf285wy"/><stop offset="1" class="x3msihbpq"/></linearGradient><linearGradient id="iQIV1Ib" x1="11.643" x2="13.101" y1="24.851" y2="25.556" gradientUnits="userSpaceOnUse"><stop offset=".399" class="biyzk_b9w"/><stop offset="1" class="zwamyqb1v"/></linearGradient><linearGradient id="iAc6BFc" x1="9.315" x2="17.502" y1="27.906" y2="31" gradientUnits="userSpaceOnUse"><stop class="lhw-mcbfc"/><stop offset="1" class="p92lizbmj"/></linearGradient><linearGradient id="isgnbDs" x1="15.19" x2="14.44" y1="26.031" y2="27.75" gradientUnits="userSpaceOnUse"><stop class="kkw49z3nn"/><stop offset="1" class="xuh6h4bdm"/></linearGradient><linearGradient id="iIwRIuc" x1="27.608" x2="27.081" y1="6.845" y2="7.169" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iRNokae" x1="26.942" x2="24.86" y1="2.745" y2="1.558" gradientUnits="userSpaceOnUse"><stop offset=".01" class="hneflfbzi"/><stop offset="1" class="h-62gkb0c"/></linearGradient><linearGradient id="iSpQGWc" x1="23.971" x2="24.546" y1="3.609" y2="3.728" gradientUnits="userSpaceOnUse"><stop offset=".01" class="hneflfbzi"/><stop offset="1" class="h-62gkb0c"/></linearGradient><filter id="iJkZ8Uz" width="5.5" height="5.75" x="19.002" y="4.597" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.878326 0 0 0 0 0.567095 0 0 0 0 0.319381 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3946"/></filter><filter id="iEfHrwb" width="4.5" height="4.5" x="19.502" y="5.347" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3946" stdDeviation=".25"/></filter><filter id="iGMjP2b" width="3.711" height="5.581" x="13.677" y="8.617" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.1"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.427451 0 0 0 0 0.380392 0 0 0 0 0.478431 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3946"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".05"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.678431 0 0 0 0 0.678431 0 0 0 0 0.694118 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3946" result="effect2_innerShadow_4002_3946"/></filter><filter id="iAQ5bIN" width="4.419" height="7.014" x="10.782" y="9.097" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.1"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.427451 0 0 0 0 0.380392 0 0 0 0 0.478431 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3946"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".05"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.678431 0 0 0 0 0.678431 0 0 0 0 0.694118 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3946" result="effect2_innerShadow_4002_3946"/></filter><filter id="i0lx0hi" width="3.88" height="1.932" x="23.502" y="2.097" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.670588 0 0 0 0 0.227451 0 0 0 0 0.258824 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3946"/></filter><filter id="imytV1c" width="2.707" height="4.677" x="27.685" y="7.347" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3946" stdDeviation=".25"/></filter><filter id="iEoPnlS" width="3.8" height="2.8" x="26.602" y="11.947" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3946" stdDeviation=".1"/></filter><filter id="ilANucI" width="1.385" height="1.475" x="26.54" y="6.171" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3946" stdDeviation=".1"/></filter><filter id="iIPBnGc" width="1.285" height="1.044" x="25.293" y="6.128" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3946" stdDeviation=".05"/></filter><filter id="iofbFqd" width="3.575" height="1.413" x="23.621" y="2.343" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3946" stdDeviation=".125"/></filter><filter id="iIuYXnr" width="3.936" height="6.647" x="11.252" y="9.138" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3946" stdDeviation=".25"/></filter><filter id="itWixac" width="3.133" height="5.109" x="14.119" y="8.737" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3946" stdDeviation=".25"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-deaf" /></template>
<style>
.air8zsgnr {
  stop-color: var(--svg-color--ee9c21, #EE9C21);
}

.ajk-yeb_a {
  d: path("M19.384 17.206a2.43 2.43 0 0 0-2.296.875l1.227 2.02c-.058.733.093 2.241 1.22 2.383c1.408.176 1.935-1.088 1.995-2.382c.06-1.285-.724-2.664-2.146-2.896");
}

.b-mv_-jcb {
  stop-color: var(--svg-color--e87b26, #E87B26);
}

.b4enoxk7f {
  stop-color: var(--svg-color--ffad30, #FFAD30);
  stop-opacity: 0;
}

.b4oa6hbjp {
  d: path("M30.002 16.687v13.16H12.619a18.07 18.07 0 0 1 17.383-13.16");
}

.b8gv4_dtn {
  stop-color: var(--svg-color--ffbc2b, #FFBC2B);
  stop-opacity: 0;
}

.biyzk_b9w {
  stop-color: var(--svg-color--ec7045, #EC7045);
}

.bsq48580e {
  stop-color: var(--svg-color--ea8d30, #EA8D30);
  stop-opacity: 0;
}

.bwty5ybud {
  fill: var(--svg-color--ffcc3b, #FFCC3B);
  d: path("m19.143 25.656l-.485.922l-6.656-2.5c.052-.255.222-.994.484-1.906c.263-.913.844-2.328 1.141-2.953l6.64 2.187l.737-1.37a1.498 1.498 0 0 1 2.22-.487c.66.496.794 1.43.289 2.083c-.361.466-.76.97-1.105 1.384c-.87 1.044-1.64 1.453-2.297 1.75a2.23 2.23 0 0 0-.968.89");
}

.bzemojb9x {
  stop-color: var(--svg-color--ff844d, #FF844D);
  stop-opacity: 0;
}

.c0hqs9jgc {
  stop-color: var(--svg-color--ffb734, #FFB734);
}

.c318rfbui {
  fill: var(--svg-color--f6941f, #F6941F);
  d: path("M21.752 9.347a1.75 1.75 0 1 0 0-3.5a1.75 1.75 0 0 0 0 3.5");
}

.c78259byf {
  d: path("M17.986 17.156c-1.23-.206-2.086.524-2.382.93l1.273 2.148c-.06.779.097 2.382 1.266 2.532c1.46.187 2.008-1.157 2.07-2.532c.062-1.365-.75-2.83-2.227-3.078");
}

.c935kubli {
  stop-color: var(--svg-color--ff9d3c, #FF9D3C);
}

.cdupweb4v {
  fill: var(--svg-color--000, #000);
  d: path("M27.214 7.452a.855.855 0 0 0-.858-.858a.855.855 0 0 0-.859.858c0 .143.034.279.096.395h1.519a.85.85 0 0 0 .102-.395");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cnkl7hbdv {
  stop-color: var(--svg-color--88004e, #88004E);
}

.cspcopyxb {
  width: 2.859px;
  height: 8.147px;
  x: 21.155px;
  y: 13.208px;
  rx: 1.429px;
}

.cssihgbwg {
  d: path("M30.002 11.847c-1.657 0-3 1.38-3 3.08v3.839c0 1.701 1.343 3.08 3 3.08z");
}

.dw6-41bxk {
  fill-rule: evenodd;
  d: path("M11.634 9.202a.85.85 0 0 1 .942.747c.207 1.788 1.009 3.299 2.22 4.708a.85.85 0 0 1-1.29 1.108c-1.367-1.59-2.362-3.408-2.618-5.62a.85.85 0 0 1 .746-.943");
}

.dwc664bvb {
  stop-color: var(--svg-color--f59624, #F59624);
}

.eaol6sc8a {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M23.97 3.406c.397-.291 1.526-.837 2.876-.687");
}

.ezbem3b1x {
  stop-color: var(--svg-color--c7a7a3, #C7A7A3);
  stop-opacity: 0.25;
}

.f1re9tbmg {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M30.102 12.87v1.558l-.092.008a3.17 3.17 0 0 1-1.853-.422a3.4 3.4 0 0 1-1.204-1.192l-.002-.003a.4.4 0 0 1-.047-.23a.4.4 0 0 1 .092-.217zm0 0l-.105.004m.105-.005l-.105.005m0 0a5 5 0 0 1-.244.005h-.002m.246-.005l-.246.005m0 0a4.74 4.74 0 0 1-2.323-.592m2.323.592l-2.323-.592m0 0l-.002-.001m.002.001l-.002-.001m0 0a.35.35 0 0 0-.23-.032m.23.032l-.23-.032m0 0a.36.36 0 0 0-.2.118z");
}

.f5op-db1p {
  stop-color: var(--svg-color--f27c64, #F27C64);
  stop-opacity: 0;
}

.f92mc8b8d {
  stop-color: var(--svg-color--de7606, #DE7606);
}

.fe01f8bxk {
  stroke: var(--svg-color--d4d2dd, #D4D2DD);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M12.002 9.888c.12 1.041.849 3.49 2.436 5.146");
}

.fsnpkqb3g {
  stop-color: var(--svg-color--f67b38, #F67B38);
}

.ft5dv1b6b {
  fill: none;
}

.fxdv5lbkc {
  fill: var(--svg-color--ffa93b, #FFA93B);
  d: path("M19.002 1.847a3.9 3.9 0 0 0 .642 1.56c.288.425.444.926.45 1.44v6.84a3.57 3.57 0 0 0 2.41 3.38l3.11 1.08V3.957l4.331.016V1.847z");
}

.g2f02ucyq {
  d: path("M26.44 6.386c.085.16.044.355-.32.389a.37.37 0 0 0-.26.161c-.155.22-.356.144-.438-.01c-.097-.184.052-.453.333-.602s.588-.121.685.062");
}

.g57dj_1-v {
  fill-rule: evenodd;
  d: path("M14.535 8.722a.85.85 0 0 1 .937.753a5.64 5.64 0 0 0 1.488 3.242a.85.85 0 0 1-1.243 1.161a7.34 7.34 0 0 1-1.935-4.219a.85.85 0 0 1 .753-.937");
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.gw3s7dbyz {
  stop-color: var(--svg-color--ec8759, #EC8759);
}

.gyn7j9reu {
  stop-color: var(--svg-color--f9b52d, #F9B52D);
}

.h-62gkb0c {
  stop-color: var(--svg-color--c26756, #C26756);
  stop-opacity: 0;
}

.h-6fqb-jl {
  d: path("M27.725 7.276c0-.484-.394-.807-.5-.905l-.485.468l.298.607z");
}

.hg75w0bei {
  fill: var(--svg-color--fea02a, #FEA02A);
  d: path("M29.777 7.847a.7.7 0 0 0-.31.123a.67.67 0 0 0-.247.34l-.995 2.065a.9.9 0 0 0 .143.808c.087.114.2.207.33.271c.362.18.849-.034 1.195-.142z");
}

.hlv2pqbyv {
  stop-color: var(--svg-color--f67b38, #F67B38);
  stop-opacity: 0;
}

.hneflfbzi {
  stop-color: var(--svg-color--c26756, #C26756);
}

.hxq43kbnk {
  stop-color: var(--svg-color--fd9610, #FD9610);
}

.i8wdd_rin {
  stop-color: var(--svg-color--ffbc45, #FFBC45);
  stop-opacity: 0;
}

.i9da4mlgb {
  stop-color: var(--svg-color--ffba2f, #FFBA2F);
  stop-opacity: 0;
}

.ie7cb3b5b {
  stop-color: var(--svg-color--f67e32, #F67E32);
  stop-opacity: 0;
}

.injzqbc-i {
  stop-color: var(--svg-color--ec8759, #EC8759);
  stop-opacity: 0;
}

.isg8qrbyl {
  stop-color: var(--svg-color--fea128, #FEA128);
}

.jby0r9b2o {
  stop-color: var(--svg-color--cfcbd9, #CFCBD9);
}

.jirdmbbmq {
  stop-color: var(--svg-color--ffea46, #FFEA46);
}

.jl-1u5bfr {
  stop-color: var(--svg-color--ffe645, #FFE645);
}

.jmna7zq9j {
  stop-color: var(--svg-color--ffbd2f, #FFBD2F);
  stop-opacity: 0;
}

.jve2rcqoj {
  stop-color: var(--svg-color--ffbc2b, #FFBC2B);
}

.kkw49z3nn {
  stop-color: var(--svg-color--ff8a25, #FF8A25);
}

.kumz7j9en {
  stop-color: var(--svg-color--c7a7a3, #C7A7A3);
}

.l38vou-0b {
  fill: var(--svg-color--b04f35, #B04F35);
  fill-rule: evenodd;
  d: path("M26.731 3.355a3.6 3.6 0 0 0-2.465.59a.49.49 0 0 1-.548-.812a4.58 4.58 0 0 1 3.135-.75a.49.49 0 0 1-.122.972");
}

.l8_cxvb0x {
  stop-color: var(--svg-color--ff914a, #FF914A);
}

.lhw-mcbfc {
  stop-color: var(--svg-color--e76025, #E76025);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.libsxlbtq {
  stop-color: var(--svg-color--ff844d, #FF844D);
}

.lj4kaubvr {
  stop-color: var(--svg-color--ffeb48, #FFEB48);
}

.ljqluf2zv {
  stop-color: var(--svg-color--ffb72c, #FFB72C);
  stop-opacity: 0;
}

.lkwppxbql {
  width: 2.859px;
  height: 8.147px;
  x: 21.155px;
  y: 13.208px;
  fill: var(--svg-color--ffc836, #FFC836);
  rx: 1.429px;
}

.ln_qsvbil {
  d: path("M30.002 12.974a5 5 0 0 1-.25.005a4.84 4.84 0 0 1-2.372-.604a.25.25 0 0 0-.164-.023a.26.26 0 0 0-.144.085a.3.3 0 0 0-.033.333a3.3 3.3 0 0 0 1.168 1.157a3.07 3.07 0 0 0 1.795.41z");
}

.ltwe578dp {
  stop-color: var(--svg-color--e98757, #E98757);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mjae__bbd {
  stop-color: var(--svg-color--e27e2f, #E27E2F);
  stop-opacity: 0;
}

.mswmpi_ln {
  stop-color: var(--svg-color--fea128, #FEA128);
  stop-opacity: 0;
}

.n_majobgc {
  stop-color: var(--svg-color--de8043, #DE8043);
}

.naer3jz1i {
  stop-color: var(--svg-color--ffc231, #FFC231);
}

.nfkrwq-tu {
  stop-color: var(--svg-color--f67e32, #F67E32);
}

.nj7d8jb1b {
  stop-color: var(--svg-color--de722b, #DE722B);
  stop-opacity: 0;
}

.nl6v52b0i {
  stop-color: var(--svg-color--ffb93a, #FFB93A);
  stop-opacity: 0;
}

.ntnqt37wf {
  stop-color: var(--svg-color--fdaa3c, #FDAA3C);
  stop-opacity: 0;
}

.o-rmrib1p {
  stop-color: var(--svg-color--ffb93a, #FFB93A);
}

.o1jtj9b1y {
  stop-color: var(--svg-color--ffc82d, #FFC82D);
}

.o60qitbpe {
  d: path("M19.002 1.847a3.9 3.9 0 0 0 .642 1.56c.288.425.444.926.45 1.44v6.84a3.57 3.57 0 0 0 2.41 3.38l3.11 1.08V3.957l4.331.016V1.847z");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.p0my23bet {
  stop-color: var(--svg-color--f27c64, #F27C64);
}

.p3vjkybbp {
  stop-color: var(--svg-color--ffb72c, #FFB72C);
}

.p69lpr5tx {
  stop-color: var(--svg-color--ee7e41, #EE7E41);
}

.p92lizbmj {
  stop-color: var(--svg-color--ff7732, #FF7732);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pp8v3-b-z {
  stop-color: var(--svg-color--ffe746, #FFE746);
  stop-opacity: 0;
}

.pymhrccao {
  d: path("M30.002 1.847h-8.555c-.445.5-.513 1.515-.445 2l.49 9a6.53 6.53 0 0 0 2.171 4.035c1.188 1.039 3.331 1.612 4.909 1.615h1.43z");
}

.q3ysfbbce {
  stop-color: var(--svg-color--ffc63a, #FFC63A);
}

.q4ehhl8ug {
  stop-color: var(--svg-color--fd9610, #FD9610);
  stop-opacity: 0;
}

.qf3ch0b8m {
  stop-color: var(--svg-color--de722b, #DE722B);
}

.qhk1lkbyv {
  d: path("M18.876 29.847H8.045l1.76-4.056a1.58 1.58 0 0 1 .869-.838a1.55 1.55 0 0 1 1.198.03l6.204 2.772c.377.175.671.492.82.885c.148.39.14.823-.02 1.207");
}

.qskg2u8et {
  d: path("M17.783 21.152c.598-1.607-.205-2.863-1.062-3.222c-1.038-.436-2.5-.086-3.149 1.414l.29 1.015l1.174-.512c.082-.035.167.048.137.132c-.64 1.79.251 2.099.642 2.287c.248.119 1.414.379 1.968-1.114");
}

.qu-rxnact {
  stop-color: var(--svg-color--ec5925, #EC5925);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r4pf285wy {
  stop-color: var(--svg-color--ed6432, #ED6432);
}

.r9c671bap {
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  d: path("M26.44 6.386c.085.16.044.355-.32.389a.37.37 0 0 0-.26.161c-.155.22-.356.144-.438-.01c-.097-.184.052-.453.333-.602s.588-.121.685.062");
}

.s05ajackq {
  stop-color: var(--svg-color--ffe746, #FFE746);
}

.szo256bqp {
  stop-color: var(--svg-color--de7606, #DE7606);
  stop-opacity: 0;
}

.t7t36bb2z {
  d: path("m18.65 26.188l-5.941-2.638a.5.5 0 0 0-.66.254l-.617 1.389a.5.5 0 0 0 .254.66l5.94 2.638a.5.5 0 0 0 .66-.254l.617-1.389a.5.5 0 0 0-.254-.66");
}

.tc-eqkbkl {
  stop-color: var(--svg-color--ff9d3c, #FF9D3C);
  stop-opacity: 0;
}

.td79j7bjm {
  stop-color: var(--svg-color--ffe645, #FFE645);
  stop-opacity: 0;
}

.tetb36znx {
  stop-color: var(--svg-color--e27e2f, #E27E2F);
}

.usa015b5s {
  d: path("M21.752 10.347a2.75 2.75 0 1 0 0-5.5a2.75 2.75 0 0 0 0 5.5");
}

.usdmtuopw {
  d: path("M30.002 6.853a.63.63 0 0 0-.29.124a.67.67 0 0 0-.234.34l-.847 2.852a.95.95 0 0 0 .135.808a.9.9 0 0 0 .31.272a.85.85 0 0 0 .393.098h.533z");
}

.v59256asn {
  stop-color: var(--svg-color--e87b26, #E87B26);
  stop-opacity: 0;
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.vd1hiwckb {
  fill: var(--svg-color--fff, #fff);
  d: path("M26.008 5.497a2.345 2.345 0 0 0-2.275 1.778a.46.46 0 0 0 .45.572h3.746c.239 0 .43-.218.382-.457a2.35 2.35 0 0 0-2.303-1.893");
}

.vixtmqora {
  stop-color: var(--svg-color--978ca5, #978CA5);
}

.w5du49byz {
  stop-color: var(--svg-color--910554, #910554);
}

.wcc2bluii {
  stroke: var(--svg-color--d4d2dd, #D4D2DD);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M14.87 9.487c.142.831.67 2.716 1.632 3.61");
}

.wcmcdsdip {
  stop-color: var(--svg-color--ffbc45, #FFBC45);
}

.wtzd4lbuc {
  stop-color: var(--svg-color--ffbd38, #FFBD38);
  stop-opacity: 0;
}

.x3msihbpq {
  stop-color: var(--svg-color--ff6d2e, #FF6D2E);
}

.x9w8qi-jn {
  stop-color: var(--svg-color--ffad30, #FFAD30);
}

.xfq469bnl {
  stop-color: var(--svg-color--f78039, #F78039);
}

.xg19asgle {
  d: path("m19.143 25.656l-.485.922l-6.656-2.5c.052-.255.222-.994.484-1.906c.263-.913.844-2.328 1.141-2.953l6.64 2.187l.737-1.37a1.498 1.498 0 0 1 2.22-.487c.66.496.794 1.43.289 2.083c-.361.466-.76.97-1.105 1.384c-.87 1.044-1.64 1.453-2.297 1.75a2.23 2.23 0 0 0-.968.89");
}

.xnhjstb2c {
  stop-color: var(--svg-color--e98757, #E98757);
  stop-opacity: 0;
}

.xsbe7ibsl {
  stop-color: var(--svg-color--ea8d30, #EA8D30);
}

.xuh6h4bdm {
  stop-color: var(--svg-color--ff8a25, #FF8A25);
  stop-opacity: 0;
}

.xxfzimbqy {
  fill: var(--svg-color--ffbc2f, #FFBC2F);
  d: path("M30.002 1.847h-8.555c-.445.5-.513 1.515-.445 2l.49 9a6.53 6.53 0 0 0 2.171 4.035c1.188 1.039 3.331 1.612 4.909 1.615h1.43z");
}

.y1en5cbdq {
  stop-color: var(--svg-color--ffbb36, #FFBB36);
}

.z9kltqbui {
  stop-color: var(--svg-color--ff914a, #FF914A);
  stop-opacity: 0;
}

.z9p88n4li {
  stop-color: var(--svg-color--ff791b, #FF791B);
}

.znrqz3bnl {
  stop-color: var(--svg-color--e76f17, #E76F17);
}

.zq5er1b8z {
  d: path("M26.356 5.953a1.5 1.5 0 0 0-1.445 1.894h2.895q.054-.193.055-.395a1.51 1.51 0 0 0-1.505-1.499");
}

.zwamyqb1v {
  stop-color: var(--svg-color--ec7045, #EC7045);
  stop-opacity: 0;
}

</style>
