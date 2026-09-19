<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#i55neXb)" transform="rotate(-27.486 7.73 6.851)" class="m0j2adc3x"/><path fill="url(#iRPaY7d)" transform="rotate(-27.486 7.73 6.851)" class="m0j2adc3x"/><path fill="url(#ieAIo3c)" transform="rotate(-27.486 7.73 6.851)" class="m0j2adc3x"/><path fill="url(#iI6EPWb)" transform="rotate(-27.486 7.73 6.851)" class="m0j2adc3x"/><path fill="url(#i12Tiac)" transform="scale(-1 1)rotate(-27.486 1.85 53.136)" class="pnmas4b0d"/><path fill="url(#iedrh3b)" transform="scale(-1 1)rotate(-27.486 1.85 53.136)" class="pnmas4b0d"/><path fill="url(#iBORENc)" transform="scale(-1 1)rotate(-27.486 1.85 53.136)" class="pnmas4b0d"/><path fill="url(#idX16ke)" transform="scale(-1 1)rotate(-27.486 1.85 53.136)" class="pnmas4b0d"/><g filter="url(#iVMCz8F)"><path fill="url(#iVAnGZb)" class="q1wg51bmi"/><path fill="url(#i0AhJLc)" class="q1wg51bmi"/><path fill="url(#i8igjWE)" class="q1wg51bmi"/><path fill="url(#il5AC0d)" class="q1wg51bmi"/></g><g filter="url(#iH9o7Nd)"><rect fill="url(#iE3hHec)" class="uywq_y1iv"/><rect fill="url(#i1HNLPr)" class="uywq_y1iv"/></g><g filter="url(#i4YzNdj)"><path stroke="url(#ibRzype)" class="ijj045bhz"/></g><path fill="url(#i8au7wd)" class="g4offrb0h"/><path fill="url(#iHoWnVL)" class="g4offrb0h"/><path fill="url(#iCij2sz)" class="nm-q8ebbk"/><path fill="url(#iBlABrf)" class="nm-q8ebbk"/><path fill="url(#iF7g9qc)" class="z0ggixb3q"/><path fill="url(#iDp8kCc)" class="z0ggixb3q"/><path fill="url(#ifHDS2c)" class="tzfcre5-h"/><path fill="url(#ihsWgme)" class="tzfcre5-h"/><circle fill="url(#iyiTEAb)" class="gknucfb8h"/><circle fill="url(#iyEw6wd)" class="gknucfb8h"/><path fill="url(#iANYCKO)" class="y0nqeezxq"/><path fill="url(#ilM1Iye)" class="y0nqeezxq"/><path fill="url(#iGf76ye)" class="l2at7otgu"/><path fill="url(#i383xNc)" class="l2at7otgu"/><path fill="url(#i1NoS8b)" class="ufmuzl7ni"/><path fill="url(#ij9Wvnd)" class="ufmuzl7ni"/><path fill="url(#iCBlCAc)" class="rh3jx3c9i"/><path fill="url(#inej4re)" class="rh3jx3c9i"/><circle fill="url(#is0pJed)" transform="matrix(-1 0 0 1 21.398 7)" class="e4y-1lbum"/><circle fill="url(#isdBRue)" transform="matrix(-1 0 0 1 21.398 7)" class="e4y-1lbum"/><g filter="url(#i4c0Riu)"><path fill="url(#i7nMPid)" class="em3ofwhyw"/><path fill="url(#iuNDXud)" class="em3ofwhyw"/><path fill="url(#iFLqZSc)" class="em3ofwhyw"/></g><g filter="url(#iVQ9Kwc)"><path fill="url(#ii9TU6b)" class="qno0gyhtd"/><path fill="url(#iAW9NPa)" class="qno0gyhtd"/><path fill="url(#irsbW7b)" class="qno0gyhtd"/></g><g filter="url(#iO3DzZc)"><path fill="url(#iMd3cGY)" class="tphhgybtp"/><path fill="url(#iKoLy8d)" class="tphhgybtp"/></g><g filter="url(#iTAKpAb)"><path fill="url(#ipt2RNb)" class="x9t-2zb_r"/><path fill="url(#ijEmnZt)" class="x9t-2zb_r"/><path fill="url(#iqv6bwe)" class="x9t-2zb_r"/></g><g filter="url(#iNNk0be)"><path fill="url(#i1fW1XY)" class="g5fg-5cgy"/><path fill="url(#iL5td6D)" class="g5fg-5cgy"/></g><g filter="url(#ibKc14c)"><path fill="url(#ihiVjwC)" class="uv_bhvydh"/></g><g filter="url(#iYk7m5c)"><path fill="url(#imrVfMc)" class="u6_y93pge"/><path fill="url(#iID6PAd)" class="u6_y93pge"/></g><g filter="url(#iap92Rb)"><path fill="url(#iQ3Ldac)" class="qd4tofb7u"/></g><g filter="url(#imwKNkb)"><path fill="url(#it1w2ie)" class="nvirpp9bq"/></g><g filter="url(#iuHjAqc)"><path fill="url(#ixKrPfb)" class="kv3enpo0a"/><path fill="url(#iIOJZDd)" class="kv3enpo0a"/></g><g filter="url(#ikQ3IQb)"><path fill="url(#imGINwe)" class="fzjqedceo"/></g><path fill="url(#ijV2PSd)" class="n3mb1bkyt"/><path fill="url(#io2A8ed)" class="p4n-n-hjl"/><path fill="url(#iUqenfe)" class="p4n-n-hjl"/><path fill="url(#io2A8ed)" class="p4n-n-hjl"/><path fill="url(#iUqenfe)" class="p4n-n-hjl"/><g filter="url(#iOSNhlK)"><path fill="url(#ienxFNa)" class="g4x-n6byt"/></g><path fill="url(#ii6Z6se)" class="g4x-n6byt"/><path fill="url(#imkWOJd)" class="g4x-n6byt"/><path fill="url(#i8yivCb)" class="g4x-n6byt"/><path fill="url(#ijT5CIb)" class="g4x-n6byt"/><path fill="url(#iTEOQZc)" class="g4x-n6byt"/><path fill="url(#iL9sSUc)" class="g4x-n6byt"/><path fill="url(#ikz3PEc)" class="g4x-n6byt"/><path fill="url(#ivHW2zb)" class="g4x-n6byt"/><g filter="url(#iLNj94R)"><path class="d6_e8h1ot"/></g><g filter="url(#iRbMnBc)"><path fill="url(#iNVXGwn)" class="ica8k-btt"/><path fill="url(#izMuvMd)" class="ica8k-btt"/><path fill="url(#ikGMIpZ)" class="ica8k-btt"/><path fill="url(#il8AFub)" class="ica8k-btt"/></g><path fill="url(#iSkE1vI)" class="mx81u8b4x"/><g filter="url(#iSunpDb)"><path fill="url(#iRJhRmd)" class="pbjajzbux"/><path fill="url(#il9f5qF)" class="pbjajzbux"/><path fill="url(#iYrX67c)" class="pbjajzbux"/><path fill="url(#iZovgUc)" class="pbjajzbux"/><path fill="url(#iriJPGe)" class="pbjajzbux"/></g><g filter="url(#i2FAHJe)"><path fill="url(#iIgDFRd)" class="t-btxqb1c"/><path fill="url(#i2fpgMN)" class="t-btxqb1c"/></g><g filter="url(#iZIuOGh)"><path fill="url(#iOjh1he)" class="fvidxkbhs"/><path fill="url(#i1Wi94M)" class="fvidxkbhs"/><path fill="url(#i30hiFd)" class="fvidxkbhs"/><path fill="url(#iPP93Dc)" class="fvidxkbhs"/><path fill="url(#iXASTAc)" class="fvidxkbhs"/><path fill="url(#iprp0Lc)" class="fvidxkbhs"/></g><path class="gpakmqb6h"/><path fill="url(#iU39tRd)" class="rxzalgbac"/><path class="ubgz9cchc"/><g filter="url(#ieVh5Zb)"><path class="elsdh0pfv"/><path fill="url(#iZW6Ive)" class="l4vs1gb3i"/></g><g filter="url(#iEL76cc)"><path fill="url(#iyKd1LQ)" class="droqhhx7c"/></g><path class="g61jrsb0u"/><path fill="url(#i8jJXAb)" class="l1osmqbde"/><path class="ijdcyhc6v"/><g filter="url(#i0gCmxc)"><path fill="url(#iQKvEXy)" class="hu_tq9b4y"/></g><g filter="url(#iLkv7nb)"><ellipse transform="rotate(-27.914 14.79 12.939)" class="iq1bks3oo"/><ellipse fill="url(#ipA5Snc)" transform="rotate(-27.914 14.79 12.939)" class="dqlm0qbsn"/></g><path fill="url(#idhTwHd)" class="kkxorubtz"/><path fill="url(#i9VJs9d)" class="kkxorubtz"/><path fill="url(#ijMrP8d)" class="kkxorubtz"/><path fill="url(#iMp9rCd)" class="ms_n05bhl"/><path fill="url(#itQAjCO)" class="ms_n05bhl"/><g filter="url(#ibtsXfc)"><path class="m4la3rbxg"/></g><g filter="url(#iYFX78Y)"><path class="ds9lzfbic"/></g><g filter="url(#iYAqxHb)"><path class="yzurklbqv"/></g><g filter="url(#i1sPXve)"><path class="zeyra_kdw"/></g><g filter="url(#iWTeCSd)"><path class="jdwanbciu"/></g><g filter="url(#ihJauMe)"><path class="sgzwbsi2z"/></g><defs><radialGradient id="i55neXb" cx="0" cy="0" r="1" gradientTransform="rotate(90.019 -.557 10.368)scale(4.75464 1.72872)" gradientUnits="userSpaceOnUse"><stop class="g2y7heb1k"/><stop offset="1" class="xukae21xj"/></radialGradient><radialGradient id="ieAIo3c" cx="0" cy="0" r="1" gradientTransform="matrix(-.81736 1.73031 -3.31873 -1.5677 10.181 7.328)" gradientUnits="userSpaceOnUse"><stop offset=".356" class="zx13l8w6l"/><stop offset="1" class="t07n6xojw"/></radialGradient><radialGradient id="iI6EPWb" cx="0" cy="0" r="1" gradientTransform="rotate(-176.149 5.36 6.832)scale(1.28611 1.19239)" gradientUnits="userSpaceOnUse"><stop offset=".162" class="qf2r2ccba"/><stop offset="1" class="uo2e3-sou"/></radialGradient><radialGradient id="i12Tiac" cx="0" cy="0" r="1" gradientTransform="rotate(90.019 -.997 3.08)scale(4.75464 1.72872)" gradientUnits="userSpaceOnUse"><stop class="g2y7heb1k"/><stop offset="1" class="xukae21xj"/></radialGradient><radialGradient id="iBORENc" cx="0" cy="0" r="1" gradientTransform="matrix(-.81736 1.73031 -3.31873 -1.5677 2.452 .476)" gradientUnits="userSpaceOnUse"><stop offset=".356" class="zx13l8w6l"/><stop offset="1" class="t07n6xojw"/></radialGradient><radialGradient id="idX16ke" cx="0" cy="0" r="1" gradientTransform="rotate(-176.149 1.38 3.537)scale(1.28611 1.19239)" gradientUnits="userSpaceOnUse"><stop offset=".162" class="qf2r2ccba"/><stop offset="1" class="uo2e3-sou"/></radialGradient><radialGradient id="iVAnGZb" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.98437 -8.78125 0 17.375 21.945)" gradientUnits="userSpaceOnUse"><stop offset=".165" class="fmwe_9bnp"/><stop offset="1" class="rcnz-20vq"/></radialGradient><radialGradient id="il5AC0d" cx="0" cy="0" r="1" gradientTransform="matrix(0 .25 -6.76923 0 17.938 21.945)" gradientUnits="userSpaceOnUse"><stop offset=".269" class="vtfzq1zlw"/><stop offset="1" class="utuf8geyx"/></radialGradient><radialGradient id="iE3hHec" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.1875 -18 0 17.781 5.695)" gradientUnits="userSpaceOnUse"><stop offset=".443" class="id87reb_m"/><stop offset="1" class="htmlfhblq"/></radialGradient><radialGradient id="i1HNLPr" cx="0" cy="0" r="1" gradientTransform="matrix(.25781 .9375 -1.66543 .458 8.96 6.273)" gradientUnits="userSpaceOnUse"><stop offset=".405" class="c0s8udrlx"/><stop offset="1" class="q46dg-bku"/></radialGradient><radialGradient id="i8au7wd" cx="0" cy="0" r="1" gradientTransform="rotate(176.461 3.991 3.074)scale(.66582 1.05015)" gradientUnits="userSpaceOnUse"><stop offset=".242" class="szuswrb-r"/><stop offset="1" class="sbel2qb8e"/></radialGradient><radialGradient id="iHoWnVL" cx="0" cy="0" r="1" gradientTransform="matrix(-.2132 .05173 -.03984 -.16419 8.083 6.282)" gradientUnits="userSpaceOnUse"><stop class="alb2mybdx"/><stop offset="1" class="spunz4bdn"/></radialGradient><radialGradient id="iCij2sz" cx="0" cy="0" r="1" gradientTransform="matrix(-.70411 .04658 -.0787 -1.18967 8.863 5.875)" gradientUnits="userSpaceOnUse"><stop offset=".242" class="szuswrb-r"/><stop offset="1" class="sbel2qb8e"/></radialGradient><radialGradient id="iBlABrf" cx="0" cy="0" r="1" gradientTransform="matrix(-.2259 .05875 -.04809 -.18493 8.777 6.312)" gradientUnits="userSpaceOnUse"><stop class="alb2mybdx"/><stop offset="1" class="spunz4bdn"/></radialGradient><radialGradient id="iF7g9qc" cx="0" cy="0" r="1" gradientTransform="rotate(176.126 5.03 3.12)scale(.67032 1.15903)" gradientUnits="userSpaceOnUse"><stop offset=".242" class="szuswrb-r"/><stop offset="1" class="sbel2qb8e"/></radialGradient><radialGradient id="iDp8kCc" cx="0" cy="0" r="1" gradientTransform="matrix(-.21457 .05712 -.04771 -.17925 10.179 6.32)" gradientUnits="userSpaceOnUse"><stop class="alb2mybdx"/><stop offset="1" class="spunz4bdn"/></radialGradient><radialGradient id="ifHDS2c" cx="0" cy="0" r="1" gradientTransform="rotate(175.983 4.687 3.116)scale(.70792 1.26809)" gradientUnits="userSpaceOnUse"><stop offset=".242" class="szuswrb-r"/><stop offset="1" class="sbel2qb8e"/></radialGradient><radialGradient id="ihsWgme" cx="0" cy="0" r="1" gradientTransform="matrix(-.22656 .06252 -.05386 -.19519 9.496 6.362)" gradientUnits="userSpaceOnUse"><stop class="alb2mybdx"/><stop offset="1" class="spunz4bdn"/></radialGradient><radialGradient id="iyiTEAb" cx="0" cy="0" r="1" gradientTransform="rotate(134.624 3.957 5.724)scale(.6044)" gradientUnits="userSpaceOnUse"><stop offset=".16" class="svjjs0b3e"/><stop offset=".91" class="umuctbc3u"/></radialGradient><radialGradient id="iyEw6wd" cx="0" cy="0" r="1" gradientTransform="matrix(-.17969 .21094 -.20725 -.17654 10.827 6.85)" gradientUnits="userSpaceOnUse"><stop class="iqe9e2uud"/><stop offset="1" class="ks97e6bva"/></radialGradient><radialGradient id="iANYCKO" cx="0" cy="0" r="1" gradientTransform="matrix(-.66762 0 0 -1.09544 24.218 5.896)" gradientUnits="userSpaceOnUse"><stop offset=".213" class="qzfufsu3s"/><stop offset="1" class="zw2whl-je"/></radialGradient><radialGradient id="ilM1Iye" cx="0" cy="0" r="1" gradientTransform="rotate(117.929 10.237 10.362)scale(.21624 .19082)" gradientUnits="userSpaceOnUse"><stop class="swlqzkb4o"/><stop offset="1" class="qao3n1bvl"/></radialGradient><radialGradient id="iGf76ye" cx="0" cy="0" r="1" gradientTransform="matrix(-.70736 0 0 -1.24403 23.543 5.875)" gradientUnits="userSpaceOnUse"><stop offset=".213" class="qzfufsu3s"/><stop offset="1" class="zw2whl-je"/></radialGradient><radialGradient id="i383xNc" cx="0" cy="0" r="1" gradientTransform="rotate(116.317 9.834 10.393)scale(.24205 .20513)" gradientUnits="userSpaceOnUse"><stop class="swlqzkb4o"/><stop offset="1" class="qao3n1bvl"/></radialGradient><radialGradient id="i1NoS8b" cx="0" cy="0" r="1" gradientTransform="matrix(-.67188 0 0 -1.20947 22.124 5.895)" gradientUnits="userSpaceOnUse"><stop offset=".213" class="qzfufsu3s"/><stop offset="1" class="zw2whl-je"/></radialGradient><radialGradient id="ij9Wvnd" cx="0" cy="0" r="1" gradientTransform="matrix(-.10193 .21094 -.17622 -.08515 22.093 6.198)" gradientUnits="userSpaceOnUse"><stop class="swlqzkb4o"/><stop offset="1" class="qao3n1bvl"/></radialGradient><radialGradient id="iCBlCAc" cx="0" cy="0" r="1" gradientTransform="matrix(-.70944 0 0 -1.32351 22.826 5.896)" gradientUnits="userSpaceOnUse"><stop offset=".213" class="qzfufsu3s"/><stop offset="1" class="zw2whl-je"/></radialGradient><radialGradient id="inej4re" cx="0" cy="0" r="1" gradientTransform="matrix(-.10762 .23083 -.18853 -.0879 22.792 6.229)" gradientUnits="userSpaceOnUse"><stop class="swlqzkb4o"/><stop offset="1" class="qao3n1bvl"/></radialGradient><radialGradient id="is0pJed" cx="0" cy="0" r="1" gradientTransform="rotate(127.213 .238 .266)scale(.65236)" gradientUnits="userSpaceOnUse"><stop offset=".16" class="h27r7g9xr"/><stop offset=".91" class="shek1db6a"/></radialGradient><radialGradient id="isdBRue" cx="0" cy="0" r="1" gradientTransform="matrix(-.06323 .28125 -.28686 -.0645 .462 .182)" gradientUnits="userSpaceOnUse"><stop class="cftjypctq"/><stop offset="1" class="ns732vbyd"/></radialGradient><radialGradient id="i7nMPid" cx="0" cy="0" r="1" gradientTransform="matrix(-6.125 0 0 -11.7203 18.313 18.758)" gradientUnits="userSpaceOnUse"><stop class="vv2_9vbpq"/><stop offset="1" class="moznfwbra"/></radialGradient><radialGradient id="iuNDXud" cx="0" cy="0" r="1" gradientTransform="rotate(107.103 2.471 12.873)scale(2.4712 2.78644)" gradientUnits="userSpaceOnUse"><stop offset=".603" class="riglhacpo"/><stop offset="1" class="w_5lt8b6v"/></radialGradient><radialGradient id="iFLqZSc" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.88881 -1.74726 0 19.826 21.256)" gradientUnits="userSpaceOnUse"><stop offset=".191" class="wx7ikuwun"/><stop offset="1" class="qljsz814e"/></radialGradient><radialGradient id="ii9TU6b" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.55078 -.69088 0 6.5 6.488)" gradientUnits="userSpaceOnUse"><stop class="i9_a76-ul"/><stop offset="1" class="wpbhksb1v"/></radialGradient><radialGradient id="iMd3cGY" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.13872 -.62832 0 26.294 6.488)" gradientUnits="userSpaceOnUse"><stop class="i9_a76-ul"/><stop offset="1" class="wpbhksb1v"/></radialGradient><radialGradient id="ipt2RNb" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.26953 -1.27419 0 4.074 6.488)" gradientUnits="userSpaceOnUse"><stop class="i9_a76-ul"/><stop offset=".72" class="wpbhksb1v"/></radialGradient><radialGradient id="ijEmnZt" cx="0" cy="0" r="1" gradientTransform="matrix(2.48437 0 0 5.55129 2.773 6.883)" gradientUnits="userSpaceOnUse"><stop offset=".415" class="aufvjo_md"/><stop offset="1" class="d2-2pqbwj"/></radialGradient><radialGradient id="i1fW1XY" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.88672 -1.125 0 28.438 6.488)" gradientUnits="userSpaceOnUse"><stop class="i9_a76-ul"/><stop offset=".72" class="wpbhksb1v"/></radialGradient><radialGradient id="iL5td6D" cx="0" cy="0" r="1" gradientTransform="matrix(-2.48437 0 0 -5.55129 29.188 6.883)" gradientUnits="userSpaceOnUse"><stop offset=".415" class="aufvjo_md"/><stop offset="1" class="d2-2pqbwj"/></radialGradient><radialGradient id="iID6PAd" cx="0" cy="0" r="1" gradientTransform="rotate(138.833 2.145 12.111)scale(1.93493 1.5766)" gradientUnits="userSpaceOnUse"><stop class="tn93407hk"/><stop offset="1" class="t7wtrebxf"/></radialGradient><radialGradient id="iQ3Ldac" cx="0" cy="0" r="1" gradientTransform="matrix(-2.84376 2.48436 -2.68024 -3.06799 11.406 27.992)" gradientUnits="userSpaceOnUse"><stop class="hekob1wbk"/><stop offset=".787" class="q-vr2ac-v"/></radialGradient><radialGradient id="iIOJZDd" cx="0" cy="0" r="1" gradientTransform="rotate(129.405 6.729 15.316)scale(1.6175 1.31795)" gradientUnits="userSpaceOnUse"><stop class="tn93407hk"/><stop offset="1" class="t7wtrebxf"/></radialGradient><radialGradient id="imGINwe" cx="0" cy="0" r="1" gradientTransform="matrix(-2.84375 1.53126 -1.60652 -2.9835 23.719 28.54)" gradientUnits="userSpaceOnUse"><stop class="uhxzzsbrl"/><stop offset=".787" class="o6imu6bzx"/></radialGradient><radialGradient id="ijV2PSd" cx="0" cy="0" r="1" gradientTransform="matrix(-.2947 1.70935 -2.03058 -.35009 18.614 13.626)" gradientUnits="userSpaceOnUse"><stop offset=".28" class="uhnyo9buy"/><stop offset="1" class="e1m_j1-ji"/></radialGradient><radialGradient id="io2A8ed" cx="0" cy="0" r="1" gradientTransform="matrix(.61607 1.29699 -.58954 .28003 13.291 13.762)" gradientUnits="userSpaceOnUse"><stop class="dk-6ihb5y"/><stop offset="1" class="rp1-yvvbr"/></radialGradient><radialGradient id="iUqenfe" cx="0" cy="0" r="1" gradientTransform="rotate(81.457 -1.095 14.775)scale(.58374 .51207)" gradientUnits="userSpaceOnUse"><stop offset=".263" class="oscuplh_u"/><stop offset="1" class="q-uhenb9x"/></radialGradient><radialGradient id="ienxFNa" cx="0" cy="0" r="1" gradientTransform="matrix(-2.52832 0 0 -4.47257 17.332 13.25)" gradientUnits="userSpaceOnUse"><stop class="c8rk37lbz"/><stop offset="1" class="yl6fh-g8k"/></radialGradient><radialGradient id="imkWOJd" cx="0" cy="0" r="1" gradientTransform="rotate(95.039 3.612 12.86)scale(6.29355 5.21181)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="dqi7sbofo"/><stop offset="1" class="qz-t25gyz"/></radialGradient><radialGradient id="i8yivCb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.6485 .80251 0 17.158 12.708)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="aqc0pptzr"/><stop offset="1" class="z_smlmblg"/></radialGradient><radialGradient id="ijT5CIb" cx="0" cy="0" r="1" gradientTransform="rotate(-93.012 13.443 -.743)scale(.53437 .58152)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="kgvcakboi"/><stop offset="1" class="gubsnccaz"/></radialGradient><radialGradient id="iTEOQZc" cx="0" cy="0" r="1" gradientTransform="matrix(.58364 0 0 2.96654 13.614 13.436)" gradientUnits="userSpaceOnUse"><stop class="ijumd0ryg"/><stop offset="1" class="oa_7ckp0d"/></radialGradient><radialGradient id="iL9sSUc" cx="0" cy="0" r="1" gradientTransform="matrix(1.26455 -1.76715 .40027 .28642 13.144 11.799)" gradientUnits="userSpaceOnUse"><stop offset=".451" class="u_gcnab-s"/><stop offset="1" class="v09_-gbcb"/></radialGradient><radialGradient id="ikz3PEc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.16727 -4.95374 5.4567 -1.28579 15.9 15.22)" gradientUnits="userSpaceOnUse"><stop offset=".924" class="noikzrben"/><stop offset="1" class="xx6a4jo2h"/></radialGradient><radialGradient id="ivHW2zb" cx="0" cy="0" r="1" gradientTransform="matrix(.98895 .34856 -.2091 .59327 16.92 10.647)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="xx6a4jo2h"/><stop offset="1" class="noikzrben"/></radialGradient><radialGradient id="iSkE1vI" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.34857 1.40237 0 15.975 15)" gradientUnits="userSpaceOnUse"><stop class="hwx_eib-x"/><stop offset="1" class="iazz9lb4s"/></radialGradient><radialGradient id="il9f5qF" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.75684 3.11277 0 13.445 12.485)" gradientUnits="userSpaceOnUse"><stop class="ytx-8cb1b"/><stop offset="1" class="y3fq4efvh"/></radialGradient><radialGradient id="iYrX67c" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.75684 3.11277 0 18.325 12.485)" gradientUnits="userSpaceOnUse"><stop class="ugkkbdcpr"/><stop offset="1" class="lty0cjbuw"/></radialGradient><radialGradient id="iZovgUc" cx="0" cy="0" r="1" gradientTransform="rotate(-159.121 9.85 3.07)scale(1.68312 .89637)" gradientUnits="userSpaceOnUse"><stop class="ofjdtziny"/><stop offset="1" class="znwnmpxvd"/></radialGradient><radialGradient id="iriJPGe" cx="0" cy="0" r="1" gradientTransform="matrix(.43773 .71334 -1.65177 1.01358 15.537 8.68)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="mvigw0raw"/><stop offset="1" class="tmhk4ybst"/></radialGradient><radialGradient id="iIgDFRd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.84111 .6643 -.18489 -.51243 16.097 9.377)" gradientUnits="userSpaceOnUse"><stop class="f6hra4b6c"/><stop offset="1" class="gz-wtrqbh"/></radialGradient><radialGradient id="i2fpgMN" cx="0" cy="0" r="1" gradientTransform="rotate(-57.724 17.269 -6.27)scale(2.91462 3.2291)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="nd6y13bdf"/><stop offset=".233" class="z45w8t_um"/><stop offset="1" class="jm3h91bib"/></radialGradient><radialGradient id="iOjh1he" cx="0" cy="0" r="1" gradientTransform="matrix(1.63745 .3873 -.2166 .91577 17.725 9.938)" gradientUnits="userSpaceOnUse"><stop class="dzh_o9bpc"/><stop offset="1" class="d2ds5d49n"/></radialGradient><radialGradient id="i1Wi94M" cx="0" cy="0" r="1" gradientTransform="rotate(-120.119 12.73 .768)scale(2.07079 1.15486)" gradientUnits="userSpaceOnUse"><stop class="zmfxcpbii"/><stop offset="1" class="t1qc5-b8a"/></radialGradient><radialGradient id="i30hiFd" cx="0" cy="0" r="1" gradientTransform="matrix(-.63228 -1.06509 .76287 -.45287 18.155 12.02)" gradientUnits="userSpaceOnUse"><stop offset=".057" class="rk366-b7y"/><stop offset="1" class="m70pgaboa"/></radialGradient><radialGradient id="iPP93Dc" cx="0" cy="0" r="1" gradientTransform="rotate(166.509 8.562 6.023)scale(2.38649 2.57988)" gradientUnits="userSpaceOnUse"><stop offset=".652" class="gxl2qg7tq"/><stop offset="1" class="j1i4w4hfh"/></radialGradient><radialGradient id="iXASTAc" cx="0" cy="0" r="1" gradientTransform="matrix(-.05674 .18558 -.84846 -.25943 17.643 9.821)" gradientUnits="userSpaceOnUse"><stop offset=".461" class="howk4obit"/><stop offset="1" class="r0f0npb-q"/></radialGradient><radialGradient id="iprp0Lc" cx="0" cy="0" r="1" gradientTransform="rotate(117.979 5.989 10.014)scale(2.05611 5.30213)" gradientUnits="userSpaceOnUse"><stop offset=".651" class="h-4ltow4h"/><stop offset="1" class="rr64b4bjv"/></radialGradient><radialGradient id="iU39tRd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .39237 -.62411 0 17.031 12.985)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iZW6Ive" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 11.65 2.37)scale(.18295 .25188)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i8jJXAb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .3924 -.62415 0 14.92 12.985)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="ipA5Snc" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 13.835 -.73)scale(.23898 .28726)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i9VJs9d" cx="0" cy="0" r="1" gradientTransform="matrix(.30398 1.0849 -1.03508 .29002 18.208 12.814)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="mjrn6wykw"/><stop offset="1" class="l68saw0rr"/></radialGradient><radialGradient id="ijMrP8d" cx="0" cy="0" r="1" gradientTransform="matrix(.381 -.52285 .43825 .31934 18.381 13.078)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="wvh6w6olb"/><stop offset="1" class="hw3g0j7tn"/></radialGradient><radialGradient id="itQAjCO" cx="0" cy="0" r="1" gradientTransform="matrix(-.81008 -.1185 .1165 -.79638 13.597 13.125)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="qbxa2xbde"/><stop offset="1" class="g54wl109l"/><stop offset="1" class="umfyx2bzt"/></radialGradient><filter id="iVMCz8F" width="9.5" height="4.284" x="11.172" y="21.645" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.541176 0 0 0 0 0.419608 0 0 0 0 0.733333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23317"/></filter><filter id="iH9o7Nd" width="27.875" height="1.225" x="2.063" y="5.775" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.403922 0 0 0 0 0.341176 0 0 0 0 0.52549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23317"/></filter><filter id="i4YzNdj" width="27.781" height=".75" x="2.023" y="6.031" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23317" stdDeviation=".125"/></filter><filter id="i4c0Riu" width="10.708" height="10.353" x="10.803" y="11.742" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".15"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.862745 0 0 0 0 0.396078 0 0 0 0 0.305882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23317"/></filter><filter id="iVQ9Kwc" width="1.93" height="8.989" x="5.039" y="1.894" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.298039 0 0 0 0 0.215686 0 0 0 0 0.431373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23317"/></filter><filter id="iO3DzZc" width="1.93" height="8.989" x="24.992" y="1.894" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.298039 0 0 0 0 0.215686 0 0 0 0 0.431373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23317"/></filter><filter id="iTAKpAb" width="1.93" height="5.973" x="3.109" y="3.402" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.298039 0 0 0 0 0.215686 0 0 0 0 0.431373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23317"/></filter><filter id="iNNk0be" width="1.93" height="5.973" x="26.922" y="3.402" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.298039 0 0 0 0 0.215686 0 0 0 0 0.431373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23317"/></filter><filter id="ibKc14c" width="3.719" height="6.065" x="8.891" y="22.984" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".1"/><feGaussianBlur stdDeviation=".6"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.862745 0 0 0 0 0.627451 0 0 0 0 0.537255 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23317"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.839216 0 0 0 0 0.592157 0 0 0 0 0.490196 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23317" result="effect2_innerShadow_3987_23317"/></filter><filter id="iYk7m5c" width="4.477" height="4.023" x="8.516" y="19.078" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.247059 0 0 0 0 0.192157 0 0 0 0 0.329412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23317"/></filter><filter id="iap92Rb" width="4.833" height="2.114" x="7.039" y="27.992" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.309804 0 0 0 0 0.239216 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23317"/></filter><filter id="imwKNkb" width="3.719" height="5.564" x="19.922" y="22.984" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".1"/><feGaussianBlur stdDeviation=".6"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.862745 0 0 0 0 0.627451 0 0 0 0 0.537255 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23317"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.839216 0 0 0 0 0.592157 0 0 0 0 0.490196 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23317" result="effect2_innerShadow_3987_23317"/></filter><filter id="iuHjAqc" width="4.477" height="4.023" x="19.539" y="19.078" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.247059 0 0 0 0 0.192157 0 0 0 0 0.329412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23317"/></filter><filter id="ikQ3IQb" width="4.833" height="2.114" x="20.159" y="27.992" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.309804 0 0 0 0 0.239216 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23317"/></filter><filter id="iOSNhlK" width="5.693" height="6.169" x="13.526" y="10.266" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75"/><feGaussianBlur stdDeviation=".6"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.843137 0 0 0 0 0.611765 0 0 0 0 0.498039 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23317"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.776471 0 0 0 0 0.54902 0 0 0 0 0.423529 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23317" result="effect2_innerShadow_3987_23317"/></filter><filter id="iLNj94R" width="1.848" height="2.366" x="14.92" y="12.511" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23317" stdDeviation=".25"/></filter><filter id="iRbMnBc" width="1.108" height="1.603" x="15.42" y="12.779" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23317" stdDeviation=".05"/></filter><filter id="iSunpDb" width="6.226" height="4.3" x="12.862" y="8.471" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.913725 0 0 0 0 0.733333 0 0 0 0 0.592157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23317"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.87451 0 0 0 0 0.678431 0 0 0 0 0.556863 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23317" result="effect2_innerShadow_3987_23317"/></filter><filter id="i2FAHJe" width="3.443" height="3.14" x="12.904" y="9.143" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23317" stdDeviation=".125"/></filter><filter id="iZIuOGh" width="3.256" height="2.991" x="15.847" y="9.424" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23317" stdDeviation=".125"/></filter><filter id="ieVh5Zb" width=".484" height=".44" x="16.624" y="12.721" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23317" stdDeviation=".05"/></filter><filter id="iEL76cc" width=".638" height=".648" x="16.979" y="12.706" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23317" stdDeviation=".1"/></filter><filter id="i0gCmxc" width=".684" height=".71" x="14.831" y="12.675" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23317" stdDeviation=".1"/></filter><filter id="iLkv7nb" width=".545" height=".444" x="14.517" y="12.717" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23317" stdDeviation=".05"/></filter><filter id="ibtsXfc" width=".901" height="1.409" x="12.928" y="12.421" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23317" stdDeviation=".125"/></filter><filter id="iYFX78Y" width=".958" height="1.421" x="18.124" y="12.413" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23317" stdDeviation=".125"/></filter><filter id="iYAqxHb" width="1.177" height=".659" x="14.261" y="11.656" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.470588 0 0 0 0 0.270588 0 0 0 0 0.160784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23317"/></filter><filter id="i1sPXve" width="1.177" height=".659" x="16.73" y="11.656" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.470588 0 0 0 0 0.270588 0 0 0 0 0.160784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23317"/></filter><filter id="iWTeCSd" width="1.094" height=".495" x="14.259" y="11.827" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23317" stdDeviation=".05"/></filter><filter id="ihJauMe" width="1.094" height=".495" x="16.715" y="11.827" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23317" stdDeviation=".05"/></filter><linearGradient id="iRPaY7d" x1="7.383" x2="8.908" y1="7.933" y2="8.286" gradientUnits="userSpaceOnUse"><stop offset=".136" class="s84b2w06p"/><stop offset="1" class="gt36rlbyf"/></linearGradient><linearGradient id="iedrh3b" x1="-.347" x2="1.178" y1="1.081" y2="1.434" gradientUnits="userSpaceOnUse"><stop offset=".136" class="s84b2w06p"/><stop offset="1" class="gt36rlbyf"/></linearGradient><linearGradient id="i0AhJLc" x1="20.313" x2="17.781" y1="25.258" y2="24.82" gradientUnits="userSpaceOnUse"><stop offset=".124" class="x05mmvhgv"/><stop offset="1" class="bq07whb_v"/></linearGradient><linearGradient id="i8igjWE" x1="11.625" x2="14.438" y1="25.352" y2="24.258" gradientUnits="userSpaceOnUse"><stop class="jsyhh4bgt"/><stop offset="1" class="sc63ikbnc"/></linearGradient><linearGradient id="ibRzype" x1="2.398" x2="29.867" y1="7.406" y2="7.406" gradientUnits="userSpaceOnUse"><stop class="pty90zojz"/><stop offset=".498" class="lshdhbblk"/><stop offset=".759" class="ty2qe1a3m"/><stop offset="1" class="up_0b0b8w"/></linearGradient><linearGradient id="iAW9NPa" x1="5.039" x2="6.531" y1="7.477" y2="7.477" gradientUnits="userSpaceOnUse"><stop offset=".181" class="b4uz6upmi"/><stop offset="1" class="u-rrnxf4y"/></linearGradient><linearGradient id="irsbW7b" x1="5.039" x2="5.313" y1="7.348" y2="7.348" gradientUnits="userSpaceOnUse"><stop offset=".36" class="l097mcblv"/><stop offset="1" class="zdbzi7bsz"/></linearGradient><linearGradient id="iKoLy8d" x1="24.992" x2="26.188" y1="6.488" y2="6.488" gradientUnits="userSpaceOnUse"><stop offset=".181" class="b4uz6upmi"/><stop offset="1" class="u-rrnxf4y"/></linearGradient><linearGradient id="iqv6bwe" x1="2.958" x2="3.452" y1="6.488" y2="6.488" gradientUnits="userSpaceOnUse"><stop offset=".282" class="pg65l5bvs"/><stop offset="1" class="iywz772fi"/></linearGradient><linearGradient id="ihiVjwC" x1="12.28" x2="8.891" y1="24.627" y2="24.627" gradientUnits="userSpaceOnUse"><stop offset=".335" class="s7xwhlbed"/><stop offset="1" class="vr3repb8u"/></linearGradient><linearGradient id="imrVfMc" x1="12.492" x2="8.516" y1="21.774" y2="21.774" gradientUnits="userSpaceOnUse"><stop class="t2qgq-21l"/><stop offset=".912" class="c3kzq0biv"/></linearGradient><linearGradient id="it1w2ie" x1="23.686" x2="20.749" y1="25.206" y2="25.206" gradientUnits="userSpaceOnUse"><stop offset=".335" class="s7xwhlbed"/><stop offset="1" class="vr3repb8u"/></linearGradient><linearGradient id="ixKrPfb" x1="19.539" x2="23.516" y1="21.774" y2="21.774" gradientUnits="userSpaceOnUse"><stop class="t2qgq-21l"/><stop offset=".912" class="c3kzq0biv"/></linearGradient><linearGradient id="ii6Z6se" x1="18.468" x2="16.363" y1="14.065" y2="14.065" gradientUnits="userSpaceOnUse"><stop class="u0hok99ej"/><stop offset="1" class="tq4h8zb2j"/></linearGradient><linearGradient id="iNVXGwn" x1="15.974" x2="16.388" y1="13.773" y2="13.773" gradientUnits="userSpaceOnUse"><stop class="f6og14bdq"/><stop offset="1" class="hk633lr2o"/></linearGradient><linearGradient id="izMuvMd" x1="15.455" x2="15.975" y1="13.698" y2="13.726" gradientUnits="userSpaceOnUse"><stop class="z_vmdubsa"/><stop offset=".203" class="umam-bfga"/><stop offset="1" class="oanih0n0r"/></linearGradient><linearGradient id="ikGMIpZ" x1="15.974" x2="15.974" y1="13.966" y2="14.378" gradientUnits="userSpaceOnUse"><stop class="y-mxywbmo"/><stop offset=".845" class="ed0uty_4k"/></linearGradient><linearGradient id="il8AFub" x1="15.974" x2="15.974" y1="12.879" y2="13.082" gradientUnits="userSpaceOnUse"><stop class="f6ma3ccql"/><stop offset="1" class="donh02dkd"/></linearGradient><linearGradient id="iRJhRmd" x1="18.568" x2="13.672" y1="10.512" y2="10.512" gradientUnits="userSpaceOnUse"><stop class="wbaoi1vzd"/><stop offset="1" class="q37q-zblj"/></linearGradient><linearGradient id="iyKd1LQ" x1="17.407" x2="17.256" y1="13.011" y2="13.105" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iQKvEXy" x1="15.28" x2="15.129" y1="13.011" y2="13.105" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="idhTwHd" x1="19.087" x2="18.503" y1="12.846" y2="13.899" gradientUnits="userSpaceOnUse"><stop class="zlaemgbzs"/><stop offset="1" class="hye7ay5ht"/></linearGradient><linearGradient id="iMp9rCd" x1="13.145" x2="13.851" y1="13.187" y2="13.125" gradientUnits="userSpaceOnUse"><stop class="dp9jyhbkn"/><stop offset="1" class="a0uazvbjh"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-lifting-weights-medium-light" /></template>
<style>
.a0uazvbjh {
  stop-color: var(--svg-color--bd776c, #BD776C);
}

.alb2mybdx {
  stop-color: var(--svg-color--f4c5a9, #F4C5A9);
}

.aqc0pptzr {
  stop-color: var(--svg-color--e4a38d, #E4A38D);
}

.aufvjo_md {
  stop-color: var(--svg-color--483a56, #483A56);
  stop-opacity: 0;
}

.b4uz6upmi {
  stop-color: var(--svg-color--392f45, #392F45);
}

.bq07whb_v {
  stop-color: var(--svg-color--a99cbb, #A99CBB);
  stop-opacity: 0;
}

.c0s8udrlx {
  stop-color: var(--svg-color--6b5678, #6B5678);
}

.c3kzq0biv {
  stop-color: var(--svg-color--453060, #453060);
}

.c8rk37lbz {
  stop-color: var(--svg-color--ffc59f, #FFC59F);
}

.cftjypctq {
  stop-color: var(--svg-color--dcb09a, #DCB09A);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.d2-2pqbwj {
  stop-color: var(--svg-color--0e0716, #0E0716);
}

.d2ds5d49n {
  stop-color: var(--svg-color--ffffc7, #FFFFC7);
  stop-opacity: 0;
}

.d6_e8h1ot {
  fill: var(--svg-color--c48377, #C48377);
  d: path("m15.766 13.21l-.335.8c-.049.183.069.366.235.366h.356c.167 0 .284-.186.235-.366l-.24-.889c-.051-.197-.197-.108-.251.089");
}

.dk-6ihb5y {
  stop-color: var(--svg-color--f8bf95, #F8BF95);
}

.donh02dkd {
  stop-color: var(--svg-color--e0a78c, #E0A78C);
  stop-opacity: 0;
}

.dp9jyhbkn {
  stop-color: var(--svg-color--c48874, #C48874);
}

.dqi7sbofo {
  stop-color: var(--svg-color--c9937f, #C9937F);
  stop-opacity: 0;
}

.dqlm0qbsn {
  cx: 14.79px;
  cy: 12.939px;
  rx: 0.188px;
  ry: 0.095px;
}

.droqhhx7c {
  d: path("M17.417 13.13a.4.4 0 0 0-.112-.225l-.126.139l.057.11z");
}

.ds9lzfbic {
  fill: var(--svg-color--e6aa8b, #E6AA8B);
  d: path("m18.374 13.584l.053-.92a.462.462 0 0 1-.053.92");
}

.dzh_o9bpc {
  stop-color: var(--svg-color--ffffc7, #FFFFC7);
}

.e1m_j1-ji {
  stop-color: var(--svg-color--da8f78, #DA8F78);
}

.e4y-1lbum {
  r: 0.398px;
}

.ed0uty_4k {
  stop-color: var(--svg-color--cb8685, #CB8685);
}

.elsdh0pfv {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M17 12.846c.031.041-.033.091-.106.146s-.128.093-.158.052c-.031-.041.003-.12.076-.174s.157-.065.188-.024");
}

.em3ofwhyw {
  d: path("m10.948 13.026l2.396-1.12l2.578 3.399l2.469-3.563l2.729 1.318a.25.25 0 0 1 .113.34l-1.194 2.303a1 1 0 0 0-.112.482l.12 5.76h-7.985v-5.788a1 1 0 0 0-.098-.433l-1.136-2.363a.25.25 0 0 1 .12-.335");
}

.f6hra4b6c {
  stop-color: var(--svg-color--fffcbe, #FFFCBE);
}

.f6ma3ccql {
  stop-color: var(--svg-color--e0a78c, #E0A78C);
}

.f6og14bdq {
  stop-color: var(--svg-color--e1aa8c, #E1AA8C);
}

.fmwe_9bnp {
  stop-color: var(--svg-color--b9adcc, #B9ADCC);
}

.ft5dv1b6b {
  fill: none;
}

.fvidxkbhs {
  d: path("m18.495 12.165l-.014-.305a.71.71 0 0 0-.68-.69h-.677c-.43 0-.822-.234-1.027-.609c0 0 .348-1.005.926-.875c.422.095.875.245 1.22.47c.844.55.696 1.542.252 2.01");
}

.fzjqedceo {
  d: path("M24.992 29.53v.376H20.36v-1.914h2.352c.383.377 1.215.73 1.836.941c.398.169.445.442.445.597");
}

.g2y7heb1k {
  stop-color: var(--svg-color--edb495, #EDB495);
}

.g4offrb0h {
  d: path("M7.5 5.71a.399.399 0 1 1 .797-.034v.46a.38.38 0 0 1-.758.032z");
}

.g4x-n6byt {
  d: path("M13.64 14.587a1.894 1.894 0 0 0 1.88 1.648h.913c.95 0 1.754-.703 1.879-1.648c.057-.91.114-1.818.156-2.728a.7.7 0 0 0-.666-.693h-.678c-.461 0-.88-.272-1.07-.698a.32.32 0 0 0-.297-.202h-.615c-.893 0-1.616.731-1.616 1.634c0 .9.056 1.785.115 2.687");
}

.g54wl109l {
  stop-color: var(--svg-color--c77937, #C77937);
}

.g5fg-5cgy {
  d: path("M28.852 4.402a.8.8 0 0 0-.8-.8h-.33a.8.8 0 0 0-.8.8v4.173a.8.8 0 0 0 .8.8h.33a.8.8 0 0 0 .8-.8z");
}

.g61jrsb0u {
  fill: var(--svg-color--fff, #fff);
  d: path("M14.82 12.623a.676.676 0 0 0-.656.512a.133.133 0 0 0 .13.165h1.079a.11.11 0 0 0 .11-.132a.68.68 0 0 0-.664-.545");
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.gknucfb8h {
  cx: 10.586px;
  cy: 7px;
  r: 0.398px;
}

.gpakmqb6h {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.132 12.623c.316 0 .583.218.656.512a.133.133 0 0 1-.13.165H16.58a.11.11 0 0 1-.11-.132a.676.676 0 0 1 .663-.545");
}

.gt36rlbyf {
  stop-color: var(--svg-color--e0aa90, #E0AA90);
  stop-opacity: 0;
}

.gubsnccaz {
  stop-color: var(--svg-color--c2847c, #C2847C);
  stop-opacity: 0;
}

.gxl2qg7tq {
  stop-color: var(--svg-color--ebcd93, #EBCD93);
  stop-opacity: 0;
}

.gz-wtrqbh {
  stop-color: var(--svg-color--fffcbe, #FFFCBE);
  stop-opacity: 0;
}

.h-4ltow4h {
  stop-color: var(--svg-color--e1b395, #E1B395);
  stop-opacity: 0;
}

.h27r7g9xr {
  stop-color: var(--svg-color--c2937c, #C2937C);
}

.hekob1wbk {
  stop-color: var(--svg-color--695381, #695381);
}

.hk633lr2o {
  stop-color: var(--svg-color--fecaa8, #FECAA8);
}

.howk4obit {
  stop-color: var(--svg-color--ffed93, #FFED93);
}

.htmlfhblq {
  stop-color: var(--svg-color--615f65, #615F65);
}

.hu_tq9b4y {
  d: path("M15.314 13.135c0-.14-.113-.232-.144-.26l-.14.135l.086.174z");
}

.hw3g0j7tn {
  stop-color: var(--svg-color--e3a17b, #E3A17B);
  stop-opacity: 0;
}

.hwx_eib-x {
  stop-color: var(--svg-color--89024e, #89024E);
}

.hye7ay5ht {
  stop-color: var(--svg-color--e0a48c, #E0A48C);
}

.i9_a76-ul {
  stop-color: var(--svg-color--5e546b, #5E546B);
}

.iazz9lb4s {
  stop-color: var(--svg-color--87004d, #87004D);
}

.ica8k-btt {
  d: path("m15.79 13.026l-.258.89c-.052.182.074.365.252.365h.38c.179 0 .305-.186.252-.366l-.257-.889c-.055-.197-.312-.197-.37 0");
}

.id87reb_m {
  stop-color: var(--svg-color--918e92, #918E92);
}

.ijdcyhc6v {
  fill: var(--svg-color--000, #000);
  d: path("M15.167 13.186a.246.246 0 0 0-.247-.247a.246.246 0 0 0-.22.361h.438a.25.25 0 0 0 .029-.114");
}

.ijj045bhz {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M2.398 6.406H29.43");
}

.ijumd0ryg {
  stop-color: var(--svg-color--dba085, #DBA085);
}

.iq1bks3oo {
  cx: 14.79px;
  cy: 12.939px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.188px;
  ry: 0.095px;
}

.iqe9e2uud {
  stop-color: var(--svg-color--eec2a5, #EEC2A5);
}

.iywz772fi {
  stop-color: var(--svg-color--615e66, #615E66);
  stop-opacity: 0;
}

.j1i4w4hfh {
  stop-color: var(--svg-color--ebcd93, #EBCD93);
}

.jdwanbciu {
  stroke: var(--svg-color--b17847, #B17847);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.409 11.99c.15-.026.494-.032.794.182");
}

.jm3h91bib {
  stop-color: var(--svg-color--e4b99b, #E4B99B);
  stop-opacity: 0;
}

.jsyhh4bgt {
  stop-color: var(--svg-color--8d7b95, #8D7B95);
}

.kgvcakboi {
  stop-color: var(--svg-color--c2847c, #C2847C);
}

.kkxorubtz {
  d: path("M18.355 13.899q.048-.773.089-1.544a.779.779 0 0 1-.09 1.544");
}

.ks97e6bva {
  stop-color: var(--svg-color--eec2a5, #EEC2A5);
  stop-opacity: 0;
}

.kv3enpo0a {
  d: path("M23.516 21.066a1.988 1.988 0 0 0-3.977 0v1.686c0 .193.157.35.35.35h3.277a.35.35 0 0 0 .35-.35z");
}

.l097mcblv {
  stop-color: var(--svg-color--433f49, #433F49);
}

.l1osmqbde {
  d: path("M14.92 12.754a.432.432 0 0 0-.416.546h.834a.435.435 0 0 0-.418-.545");
}

.l2at7otgu {
  d: path("M23.823 5.627a.422.422 0 1 0-.843-.033v.584a.4.4 0 0 0 .798.031z");
}

.l4vs1gb3i {
  d: path("M17 12.846c.031.041-.033.091-.106.146s-.128.093-.158.052c-.031-.041.003-.12.076-.174s.157-.065.188-.024");
}

.l68saw0rr {
  stop-color: var(--svg-color--ce8d79, #CE8D79);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lshdhbblk {
  stop-color: var(--svg-color--9a969d, #9A969D);
}

.lty0cjbuw {
  stop-color: var(--svg-color--f6cb9c, #F6CB9C);
  stop-opacity: 0;
}

.m0j2adc3x {
  d: path("M7.73 6.851h2.46v7.269H7.73z");
}

.m4la3rbxg {
  fill: var(--svg-color--b57562, #B57562);
  d: path("M13.538 12.67a.462.462 0 0 0 .04.91q-.024-.454-.04-.91");
}

.m70pgaboa {
  stop-color: var(--svg-color--dfb086, #DFB086);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mjrn6wykw {
  stop-color: var(--svg-color--ce8d79, #CE8D79);
  stop-opacity: 0;
}

.moznfwbra {
  stop-color: var(--svg-color--ff6621, #FF6621);
}

.ms_n05bhl {
  d: path("M13.53 12.351a.778.778 0 0 0 .067 1.548a38 38 0 0 1-.067-1.548");
}

.mvigw0raw {
  stop-color: var(--svg-color--ddca94, #DDCA94);
}

.mx81u8b4x {
  d: path("M15.975 14.69c-.246 0-.477-.058-.67-.16c-.067-.033-.138.042-.096.102a.92.92 0 0 0 .766.409a.92.92 0 0 0 .765-.41c.042-.062-.03-.134-.095-.1a1.45 1.45 0 0 1-.67.159");
}

.n3mb1bkyt {
  d: path("M18.325 13.855a.8.8 0 0 0 .438-.15v.45c0 .433-.258.818-.649.977q.125-.263.168-.57z");
}

.nd6y13bdf {
  stop-color: var(--svg-color--d5a088, #D5A088);
}

.nm-q8ebbk {
  d: path("M8.16 5.627a.422.422 0 1 1 .844-.033v.584a.4.4 0 0 1-.798.031z");
}

.noikzrben {
  stop-color: var(--svg-color--c17f5f, #C17F5F);
  stop-opacity: 0;
}

.ns732vbyd {
  stop-color: var(--svg-color--dcb09a, #DCB09A);
  stop-opacity: 0;
}

.nvirpp9bq {
  d: path("m22.668 28.448l.473-5.464h-3.22l.479 5.464z");
}

.o6imu6bzx {
  stop-color: var(--svg-color--59417a, #59417A);
}

.oa_7ckp0d {
  stop-color: var(--svg-color--dba085, #DBA085);
  stop-opacity: 0;
}

.oanih0n0r {
  stop-color: var(--svg-color--d29879, #D29879);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ofjdtziny {
  stop-color: var(--svg-color--ffffc1, #FFFFC1);
}

.oscuplh_u {
  stop-color: var(--svg-color--d79b77, #D79B77);
}

.p4n-n-hjl {
  d: path("M13.623 13.855a.8.8 0 0 1-.437-.15v.45c0 .433.257.818.648.977a2 2 0 0 1-.167-.57z");
}

.pbjajzbux {
  d: path("M18.322 10.038a1.146 1.146 0 0 1 .562 1.73a.76.76 0 0 0-.13.423v.574a.85.85 0 0 0-.324-.13l.038-.777a.7.7 0 0 0-.666-.692h-.678c-.461 0-.88-.272-1.07-.698a.32.32 0 0 0-.297-.202h-.615c-.893 0-1.616.731-1.616 1.634l.014.743a.8.8 0 0 0-.348.128v-.58a.76.76 0 0 0-.13-.423a1.16 1.16 0 0 1-.07-1.183c.141-.267.37-.454.629-.545a1.3 1.3 0 0 0 .669-.537a1.125 1.125 0 0 1 1.398-.44a.72.72 0 0 0 .577 0a1.12 1.12 0 0 1 1.403.456c.149.246.382.425.654.519");
}

.pg65l5bvs {
  stop-color: var(--svg-color--615e66, #615E66);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pnmas4b0d {
  d: path("M0 0h2.46v7.269H0z");
}

.pty90zojz {
  stop-color: var(--svg-color--7b7784, #7B7784);
}

.q-uhenb9x {
  stop-color: var(--svg-color--d79b77, #D79B77);
  stop-opacity: 0;
}

.q-vr2ac-v {
  stop-color: var(--svg-color--5c447a, #5C447A);
}

.q1wg51bmi {
  d: path("M16 25.93c-2.363 0-4.203-.72-4.828-1.078v-2.907h9.5v3.016c-.573.323-2.31.969-4.672.969");
}

.q37q-zblj {
  stop-color: var(--svg-color--e7c991, #E7C991);
}

.q46dg-bku {
  stop-color: var(--svg-color--6b5678, #6B5678);
  stop-opacity: 0;
}

.qao3n1bvl {
  stop-color: var(--svg-color--e2b69c, #E2B69C);
  stop-opacity: 0;
}

.qbxa2xbde {
  stop-color: var(--svg-color--dca187, #DCA187);
  stop-opacity: 0;
}

.qd4tofb7u {
  d: path("M7.04 29.53v.376h4.632v-1.914H9.32c-.383.377-1.215.73-1.836.941c-.398.169-.445.442-.445.597");
}

.qf2r2ccba {
  stop-color: var(--svg-color--d9996f, #D9996F);
}

.qljsz814e {
  stop-color: var(--svg-color--ff8d41, #FF8D41);
  stop-opacity: 0;
}

.qno0gyhtd {
  d: path("M5.04 2.894a.8.8 0 0 1 .8-.8h.329a.8.8 0 0 1 .8.8v7.189a.8.8 0 0 1-.8.8h-.33a.8.8 0 0 1-.8-.8z");
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qz-t25gyz {
  stop-color: var(--svg-color--b36e91, #B36E91);
}

.qzfufsu3s {
  stop-color: var(--svg-color--d9af8d, #D9AF8D);
}

.r0f0npb-q {
  stop-color: var(--svg-color--ffed93, #FFED93);
  stop-opacity: 0;
}

.rcnz-20vq {
  stop-color: var(--svg-color--a090b1, #A090B1);
}

.rh3jx3c9i {
  d: path("M23.108 5.588a.424.424 0 1 0-.847-.016v.661a.411.411 0 0 0 .823.015z");
}

.riglhacpo {
  stop-color: var(--svg-color--bd3f19, #BD3F19);
}

.rk366-b7y {
  stop-color: var(--svg-color--dfb086, #DFB086);
}

.rp1-yvvbr {
  stop-color: var(--svg-color--dc998e, #DC998E);
}

.rr64b4bjv {
  stop-color: var(--svg-color--e1b395, #E1B395);
}

.rxzalgbac {
  d: path("M17.032 12.754a.432.432 0 0 1 .416.546h-.834a.433.433 0 0 1 .418-.545");
}

.s7xwhlbed {
  stop-color: var(--svg-color--f9bea4, #F9BEA4);
}

.s84b2w06p {
  stop-color: var(--svg-color--764549, #764549);
}

.sbel2qb8e {
  stop-color: var(--svg-color--c78b7b, #C78B7B);
}

.sc63ikbnc {
  stop-color: var(--svg-color--ac9ebe, #AC9EBE);
  stop-opacity: 0;
}

.sgzwbsi2z {
  stroke: var(--svg-color--b17847, #B17847);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M17.659 11.99a1.1 1.1 0 0 0-.794.182");
}

.shek1db6a {
  stop-color: var(--svg-color--c5897c, #C5897C);
}

.spunz4bdn {
  stop-color: var(--svg-color--f4c5a9, #F4C5A9);
  stop-opacity: 0;
}

.svjjs0b3e {
  stop-color: var(--svg-color--d3a080, #D3A080);
}

.swlqzkb4o {
  stop-color: var(--svg-color--e2b69c, #E2B69C);
}

.szuswrb-r {
  stop-color: var(--svg-color--f2c59f, #F2C59F);
}

.t-btxqb1c {
  d: path("m16.087 10.534l-.032-.066a.32.32 0 0 0-.298-.202h-.615c-.893 0-1.617.731-1.617 1.634v.133c-.164-.125-.37-.389-.37-.816c0-.519.377-.78.619-.948c.068-.047.125-.086.16-.122l.048-.05c.169-.18.47-.5.996-.64a2 2 0 0 1 .31-.059c.47-.058.809.358.809.83v.3z");
}

.t07n6xojw {
  stop-color: var(--svg-color--cc947b, #CC947B);
  stop-opacity: 0;
}

.t1qc5-b8a {
  stop-color: var(--svg-color--e4b78d, #E4B78D);
  stop-opacity: 0;
}

.t2qgq-21l {
  stop-color: var(--svg-color--574471, #574471);
}

.t7wtrebxf {
  stop-color: var(--svg-color--624d77, #624D77);
  stop-opacity: 0;
}

.tmhk4ybst {
  stop-color: var(--svg-color--ddca94, #DDCA94);
  stop-opacity: 0;
}

.tn93407hk {
  stop-color: var(--svg-color--624d77, #624D77);
}

.tphhgybtp {
  d: path("M26.922 2.894a.8.8 0 0 0-.8-.8h-.33a.8.8 0 0 0-.8.8v7.189a.8.8 0 0 0 .8.8h.33a.8.8 0 0 0 .8-.8z");
}

.tq4h8zb2j {
  stop-color: var(--svg-color--f7c29d, #F7C29D);
  stop-opacity: 0;
}

.ty2qe1a3m {
  stop-color: var(--svg-color--97959c, #97959C);
}

.tzfcre5-h {
  d: path("M8.876 5.588a.424.424 0 1 1 .847-.016v.661a.411.411 0 0 1-.823.015z");
}

.u_gcnab-s {
  stop-color: var(--svg-color--b67459, #B67459);
}

.u-rrnxf4y {
  stop-color: var(--svg-color--51435f, #51435F);
  stop-opacity: 0;
}

.u0hok99ej {
  stop-color: var(--svg-color--f7c29d, #F7C29D);
}

.u6_y93pge {
  d: path("M8.516 21.066a1.988 1.988 0 1 1 3.976 0v1.686a.35.35 0 0 1-.35.35H8.866a.35.35 0 0 1-.35-.35z");
}

.ubgz9cchc {
  fill: var(--svg-color--000, #000);
  d: path("M16.785 13.186c0-.137.11-.247.247-.247a.246.246 0 0 1 .22.36h-.438a.2.2 0 0 1-.03-.113");
}

.ufmuzl7ni {
  d: path("M22.392 5.626a.401.401 0 1 0-.803-.014v.575a.391.391 0 0 0 .783.013z");
}

.ugkkbdcpr {
  stop-color: var(--svg-color--f6cb9c, #F6CB9C);
}

.uhnyo9buy {
  stop-color: var(--svg-color--f7bf94, #F7BF94);
}

.uhxzzsbrl {
  stop-color: var(--svg-color--65507e, #65507E);
}

.umam-bfga {
  stop-color: var(--svg-color--d29879, #D29879);
}

.umfyx2bzt {
  stop-color: var(--svg-color--dca187, #DCA187);
}

.umuctbc3u {
  stop-color: var(--svg-color--c38478, #C38478);
}

.uo2e3-sou {
  stop-color: var(--svg-color--edae8a, #EDAE8A);
  stop-opacity: 0;
}

.up_0b0b8w {
  stop-color: var(--svg-color--8d8c90, #8D8C90);
}

.utuf8geyx {
  stop-color: var(--svg-color--cabed2, #CABED2);
  stop-opacity: 0;
}

.uv_bhvydh {
  d: path("m9.404 28.878l-.513-5.894h3.218l-.533 5.966z");
}

.uywq_y1iv {
  width: 27.875px;
  height: 1.025px;
  x: 2.063px;
  y: 5.975px;
  rx: 0.2px;
}

.v09_-gbcb {
  stop-color: var(--svg-color--b67459, #B67459);
  stop-opacity: 0;
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.vr3repb8u {
  stop-color: var(--svg-color--e3aa95, #E3AA95);
}

.vtfzq1zlw {
  stop-color: var(--svg-color--cabed2, #CABED2);
}

.vv2_9vbpq {
  stop-color: var(--svg-color--ff9347, #FF9347);
}

.w_5lt8b6v {
  stop-color: var(--svg-color--de4f22, #DE4F22);
  stop-opacity: 0;
}

.wbaoi1vzd {
  stop-color: var(--svg-color--fff6b9, #FFF6B9);
}

.wpbhksb1v {
  stop-color: var(--svg-color--50425e, #50425E);
}

.wvh6w6olb {
  stop-color: var(--svg-color--e3a17b, #E3A17B);
}

.wx7ikuwun {
  stop-color: var(--svg-color--c04203, #C04203);
}

.x05mmvhgv {
  stop-color: var(--svg-color--887497, #887497);
}

.x9t-2zb_r {
  d: path("M3.11 4.402a.8.8 0 0 1 .8-.8h.33a.8.8 0 0 1 .8.8v4.173a.8.8 0 0 1-.8.8h-.33a.8.8 0 0 1-.8-.8z");
}

.xukae21xj {
  stop-color: var(--svg-color--d8a38c, #D8A38C);
}

.xx6a4jo2h {
  stop-color: var(--svg-color--c17f5f, #C17F5F);
}

.y-mxywbmo {
  stop-color: var(--svg-color--cb8685, #CB8685);
  stop-opacity: 0;
}

.y0nqeezxq {
  d: path("M24.483 5.71a.399.399 0 1 0-.796-.034v.46a.38.38 0 0 0 .758.032z");
}

.y3fq4efvh {
  stop-color: var(--svg-color--e7b286, #E7B286);
  stop-opacity: 0;
}

.yl6fh-g8k {
  stop-color: var(--svg-color--c8917d, #C8917D);
}

.ytx-8cb1b {
  stop-color: var(--svg-color--e7b286, #E7B286);
}

.yzurklbqv {
  fill: var(--svg-color--a06937, #A06937);
  d: path("M14.452 11.86q.076-.007.204 0c.168.014.394.064.62.21a.133.133 0 0 1-.144.224a1.06 1.06 0 0 0-.7-.163l-.01.001h-.001a.133.133 0 0 1-.055-.26z");
}

.z_smlmblg {
  stop-color: var(--svg-color--e4a38d, #E4A38D);
  stop-opacity: 0;
}

.z_vmdubsa {
  stop-color: var(--svg-color--d29879, #D29879);
  stop-opacity: 0.915;
}

.z0ggixb3q {
  d: path("M9.592 5.626a.401.401 0 1 1 .803-.014v.575a.391.391 0 0 1-.783.013z");
}

.z45w8t_um {
  stop-color: var(--svg-color--e4b99b, #E4B99B);
}

.zdbzi7bsz {
  stop-color: var(--svg-color--433f49, #433F49);
  stop-opacity: 0;
}

.zeyra_kdw {
  fill: var(--svg-color--a06937, #A06937);
  d: path("M17.616 11.86a1.33 1.33 0 0 0-.825.21a.133.133 0 0 0 .144.224a1.06 1.06 0 0 1 .7-.163l.01.001h.002a.133.133 0 0 0 .054-.26z");
}

.zlaemgbzs {
  stop-color: var(--svg-color--f8c5a2, #F8C5A2);
}

.zmfxcpbii {
  stop-color: var(--svg-color--e3b593, #E3B593);
}

.znwnmpxvd {
  stop-color: var(--svg-color--ffffc1, #FFFFC1);
  stop-opacity: 0;
}

.zw2whl-je {
  stop-color: var(--svg-color--c48b7e, #C48B7E);
}

.zx13l8w6l {
  stop-color: var(--svg-color--a06353, #A06353);
}

</style>
