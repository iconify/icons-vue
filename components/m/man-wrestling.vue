<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iY6FTDb)" transform="scale(-1 1)rotate(-40.802 8.67 22.575)" class="dm4voe-la"/><path fill="url(#ifys9gc)" class="zzjkwgj6o"/><g filter="url(#i4qKEid)"><path class="bd47k7a5l"/></g><g filter="url(#ibK2X5f)"><path class="czujv0sxy"/><path fill="url(#iUPgUSc)" class="v5o9libvx"/></g><path fill="url(#itNwi2b)" class="t57xntbrd"/><path fill="url(#iUe7fKb)" class="t57xntbrd"/><path fill="url(#iJQuHBK)" class="t57xntbrd"/><path fill="url(#ip7i9le)" class="avs6vzbgz"/><path fill="url(#ieHzg0d)" class="avs6vzbgz"/><path fill="url(#ilQJnzb)" class="avs6vzbgz"/><g filter="url(#iD4Pj7c)"><path class="ha76tmxnj"/></g><g filter="url(#iwHSPGe)"><path class="jn8cu6s_w"/></g><g filter="url(#ic4fbpe)"><path class="n_ivmfbzb"/><path fill="url(#i9V9pkE)" class="q7fjm26wi"/></g><path fill="url(#iJc4C3x)" class="tl4jonegg"/><path fill="url(#iXSZoGj)" class="tl4jonegg"/><g filter="url(#inM5yJb)"><path class="m1xx5kfqh"/><path fill="url(#iL3KCRb)" class="sn1rqklko"/><path fill="url(#i4XBy2c)" class="sn1rqklko"/><path fill="url(#iJzlOde)" class="sn1rqklko"/></g><g filter="url(#iqc5L9d)"><path class="whveigbld"/></g><g filter="url(#iAcUyDA)"><path class="fwfxfrotv"/><path fill="url(#imYfwQe)" class="hn_62y1ma"/><path fill="url(#iuFeuic)" class="hn_62y1ma"/><path fill="url(#ioTrI7b)" class="hn_62y1ma"/></g><g filter="url(#iQp0yyM)"><path fill="url(#iYIJNVc)" class="j3ug58blb"/></g><g filter="url(#iDLn2TO)"><rect stroke="url(#iQ74Fze)" transform="rotate(45 8.352 11.554)" class="r98xt8hnz"/></g><rect fill="url(#icxD7yc)" transform="rotate(45 8.352 11.554)" class="w20qtlznv"/><rect fill="url(#ihYP1pd)" transform="rotate(45 8.352 11.554)" class="w20qtlznv"/><g filter="url(#iTiexIb)"><path clip-rule="evenodd" class="ggeojxayc"/></g><path clip-rule="evenodd" class="e53sdbbza"/><path fill="url(#iXH3Osc)" clip-rule="evenodd" class="g83fgbbyy"/><path clip-rule="evenodd" class="kgwyv9bwy"/><path fill="url(#iBMYsHd)" clip-rule="evenodd" class="ni6dvehrg"/><path clip-rule="evenodd" class="w0ww-qb1v"/><path fill="url(#ihkMD0c)" clip-rule="evenodd" class="s-4wojr5g"/><path clip-rule="evenodd" class="pfz0j3bxp"/><path fill="url(#iwaJVIb)" clip-rule="evenodd" class="hptrd5b0d"/><path clip-rule="evenodd" class="ei0jw7bok"/><path fill="url(#iNnZTYd)" clip-rule="evenodd" class="ahv1csbpk"/><path fill="url(#iPJiZIb)" clip-rule="evenodd" class="p50qpvb-l"/><path fill="url(#ivOBaEc)" clip-rule="evenodd" class="p50qpvb-l"/><path fill="url(#iXDgeDv)" clip-rule="evenodd" class="p50qpvb-l"/><path fill="url(#ibXOHre)" clip-rule="evenodd" class="p50qpvb-l"/><g filter="url(#iC3lTYb)"><rect transform="rotate(-28.166 16.813 17.229)" class="g3g2_db3x"/></g><path fill="url(#i8ZICqS)" transform="rotate(-23.31 19.035 10.56)" class="iqlz2hawi"/><path fill="url(#iCc9ieb)" class="vgkwtybgv"/><path fill="url(#iA6jHoe)" class="vgkwtybgv"/><path fill="url(#iLlMvKd)" class="vgkwtybgv"/><path fill="url(#i13Klac)" class="mn215cb4x"/><path fill="url(#iDrqAtc)" class="mn215cb4x"/><path fill="url(#iMOdSCb)" class="mn215cb4x"/><g filter="url(#ib2od4b)"><path class="po83g90tv"/></g><g filter="url(#i4EPfld)"><path class="zlfnp5bxa"/></g><g filter="url(#iKm7yJc)"><path class="ixcfis0oi"/><path fill="url(#ilxVv0k)" class="v9jt40b6n"/></g><path fill="url(#iBvGaZb)" class="s3twa090i"/><path fill="url(#icTxbKd)" class="s3twa090i"/><g filter="url(#iA5Jaoc)"><path class="a-a659b1q"/><path fill="url(#iEkbWte)" class="r6at_9bif"/><path fill="url(#iiD2NGe)" class="r6at_9bif"/><path fill="url(#ixXfchc)" class="r6at_9bif"/></g><g filter="url(#ipTVUee)"><path class="r-govlg6m"/></g><g filter="url(#iUhChec)"><path class="l0hz2bwjg"/><path fill="url(#i3vLhpe)" class="comfxdbed"/><path fill="url(#iJyCNEc)" class="comfxdbed"/><path fill="url(#ikcfrVc)" class="comfxdbed"/></g><g filter="url(#iqGNMqb)"><path fill="url(#iqdbALb)" class="egzdhvbpq"/></g><g filter="url(#iclpEqb)"><rect stroke="url(#ixvNnqb)" transform="scale(-1 1)rotate(45 -25.472 -22.099)" class="gg2ehgbth"/></g><rect fill="url(#iD4h8Ac)" transform="scale(-1 1)rotate(45 -25.472 -22.099)" class="pxj138bcc"/><rect fill="url(#i4cwRAb)" transform="scale(-1 1)rotate(45 -25.472 -22.099)" class="pxj138bcc"/><path clip-rule="evenodd" class="igqqc-b6y"/><path fill="url(#iycdpJe)" clip-rule="evenodd" class="qtw47acth"/><path fill="url(#i3WnUge)" clip-rule="evenodd" class="qtw47acth"/><path fill="url(#irJO0Yd)" class="x-arwcb1i"/><path fill="url(#iMKiCyc)" class="x-arwcb1i"/><path class="mbn307bku"/><path fill="url(#iQ1KS4b)" class="ugk6lpbwj"/><path fill="url(#iMtVDIb)" class="ugk6lpbwj"/><path fill="url(#ia0MOjD)" class="zhnyavbli"/><path fill="url(#i3ybiac)" class="zhnyavbli"/><path class="uaz-z0b5y"/><path fill="url(#ipRqVUh)" class="wcp6pybct"/><g filter="url(#iDQudMd)"><path fill="url(#i7R5qub)" class="pwkppuz1r"/><path fill="url(#idLxkvc)" class="pwkppuz1r"/></g><g filter="url(#iQvWaze)"><path fill="url(#iPgHftc)" class="hjv1ly6lq"/></g><path fill="url(#iPENaDb)" class="hjv1ly6lq"/><path fill="url(#iIpElOb)" class="cfe6fmtoq"/><path class="iua_52v7a"/><path fill="url(#i8JH2Hb)" class="zt4dzgbzh"/><path fill="url(#iWpWyDb)" class="bes5zfizp"/><ellipse fill="url(#ikikhKc)" transform="scale(-1 1)rotate(24.61 -26.617 -27.116)" class="qi_39hbzn"/><path fill="url(#iXoBHTe)" clip-rule="evenodd" class="ucnu_4apo"/><path fill="url(#iNIOZBK)" clip-rule="evenodd" class="ucnu_4apo"/><path fill="url(#i18w8vv)" clip-rule="evenodd" class="ucnu_4apo"/><path fill="url(#inY1tGE)" clip-rule="evenodd" class="g3eobnbex"/><path fill="url(#ixAIarb)" clip-rule="evenodd" class="g3eobnbex"/><circle fill="url(#iCxY2nc)" class="f5es1ac2s"/><circle fill="url(#ixWo8nc)" class="f5es1ac2s"/><circle fill="url(#inoyoOd)" class="f5es1ac2s"/><g filter="url(#i763tGe)"><rect class="v1nkxhg1t"/></g><rect class="b5vaz6biu"/><path fill="url(#i9FhXVb)" class="kiki776xu"/><path fill="url(#iGJ3NXh)" class="yyudvh1wz"/><g filter="url(#ikdCG8e)"><path fill="url(#iBSEZzd)" class="o-bam90bc"/><path fill="url(#ibstNpP)" class="o-bam90bc"/><path fill="url(#idjQllb)" class="o-bam90bc"/></g><g filter="url(#ilPUqFd)"><path fill="url(#iJWwfRd)" class="x69_iy2_t"/></g><path fill="url(#iaLcvNc)" class="x69_iy2_t"/><path fill="url(#iWHGnHc)" class="gq4385_0g"/><path class="hc9rtyb3n"/><path fill="url(#iHDgSne)" class="jnmo26gja"/><path fill="url(#ifc6omd)" class="t_lqcx57b"/><ellipse fill="url(#inwNN5b)" transform="rotate(24.61 17.59 8.621)" class="j3dn9fs5p"/><path fill="url(#iCVYhce)" clip-rule="evenodd" class="r294_3bpq"/><path fill="url(#ieqwynb)" clip-rule="evenodd" class="r294_3bpq"/><path fill="url(#iPleFIc)" clip-rule="evenodd" class="r294_3bpq"/><path fill="url(#iiPPxFd)" clip-rule="evenodd" class="jnbv5jxhd"/><path fill="url(#i4dTTzQ)" clip-rule="evenodd" class="jnbv5jxhd"/><circle fill="url(#i0wCBJc)" transform="matrix(-1 0 0 1 20.584 9.172)" class="ms4f1oj7g"/><circle fill="url(#iXGn3Cd)" transform="matrix(-1 0 0 1 20.584 9.172)" class="ms4f1oj7g"/><circle fill="url(#iNSGxke)" transform="matrix(-1 0 0 1 20.584 9.172)" class="ms4f1oj7g"/><g filter="url(#iQ876Ip)"><rect transform="matrix(-1 0 0 1 18.63 7.922)" class="lzcvp_xbr"/></g><rect transform="matrix(-1 0 0 1 18.275 10.307)" class="b61r46b1w"/><defs><radialGradient id="iY6FTDb" cx="0" cy="0" r="1" gradientTransform="matrix(1.38633 1.36295 -2.28073 2.31985 -.033 1.45)" gradientUnits="userSpaceOnUse"><stop class="aie3sbybt"/><stop offset=".793" class="r29-u8u1s"/></radialGradient><radialGradient id="ifys9gc" cx="0" cy="0" r="1" gradientTransform="matrix(.49331 1.0236 -1.6646 .80223 10.672 8.613)" gradientUnits="userSpaceOnUse"><stop offset=".04" class="bervkqbmz"/><stop offset="1" class="c479w-bpn"/></radialGradient><radialGradient id="iUPgUSc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.71095 2.35327 -5.20382 -5.99476 18.618 12.29)" gradientUnits="userSpaceOnUse"><stop class="bbakdxbza"/><stop offset="1" class="so50u3yvk"/></radialGradient><radialGradient id="itNwi2b" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.96875 1.8125 0 11.376 26.906)" gradientUnits="userSpaceOnUse"><stop class="l4a0dtbst"/><stop offset="1" class="l2gyjvi4r"/></radialGradient><radialGradient id="iUe7fKb" cx="0" cy="0" r="1" gradientTransform="matrix(2.14185 1.875 -.94292 1.07712 7.11 21.875)" gradientUnits="userSpaceOnUse"><stop offset=".188" class="vgnymzutm"/><stop offset="1" class="cttd8qtou"/></radialGradient><radialGradient id="iJQuHBK" cx="0" cy="0" r="1" gradientTransform="rotate(144.26 1.876 11.73)scale(1.23051 3.4979)" gradientUnits="userSpaceOnUse"><stop offset=".278" class="ad7150bof"/><stop offset="1" class="touvs0bsg"/></radialGradient><radialGradient id="i9V9pkE" cx="0" cy="0" r="1" gradientTransform="rotate(-134.195 7.243 8.817)scale(2.212 .64075)" gradientUnits="userSpaceOnUse"><stop class="hwnq5ubzm"/><stop offset="1" class="y9oqcminv"/></radialGradient><radialGradient id="iJc4C3x" cx="0" cy="0" r="1" gradientTransform="rotate(128.536 .182 10.89)scale(4.51441 1.8822)" gradientUnits="userSpaceOnUse"><stop offset=".154" class="rlrqah7ok"/><stop offset="1" class="r-6du_zhr"/></radialGradient><radialGradient id="iXSZoGj" cx="0" cy="0" r="1" gradientTransform="matrix(6.96877 -7.18752 5.67939 5.50654 3.501 19.188)" gradientUnits="userSpaceOnUse"><stop offset=".93" class="i1avtge0l"/><stop offset="1" class="ifp1_xbmc"/></radialGradient><radialGradient id="i4XBy2c" cx="0" cy="0" r="1" gradientTransform="rotate(-144.397 8.258 13.852)scale(2.17397 2.91043)" gradientUnits="userSpaceOnUse"><stop class="ct6_m01bp"/><stop offset="1" class="hh9ibwbje"/></radialGradient><radialGradient id="iuFeuic" cx="0" cy="0" r="1" gradientTransform="matrix(-1.64636 -1.26563 1.72963 -2.24994 14.075 29.914)" gradientUnits="userSpaceOnUse"><stop class="ct6_m01bp"/><stop offset="1" class="hh9ibwbje"/></radialGradient><radialGradient id="iYIJNVc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.82813 .85156 0 10.923 27.734)" gradientUnits="userSpaceOnUse"><stop class="utx5lkfyi"/><stop offset="1" class="xn9ndqb6s"/></radialGradient><radialGradient id="icxD7yc" cx="0" cy="0" r="1" gradientTransform="matrix(.00794 2.83955 -1.96718 .0055 10.076 13.289)" gradientUnits="userSpaceOnUse"><stop offset=".545" class="rzbmz9bky"/><stop offset="1" class="km6_kbc8h"/></radialGradient><radialGradient id="ihYP1pd" cx="0" cy="0" r="1" gradientTransform="matrix(1.49 1.66988 -.81478 .72701 11.098 14.675)" gradientUnits="userSpaceOnUse"><stop offset=".176" class="gw8ri5cen"/><stop offset="1" class="yxjq9v5jp"/></radialGradient><radialGradient id="iXH3Osc" cx="0" cy="0" r="1" gradientTransform="rotate(137.121 2.61 10.854)scale(3.58218 11.0839)" gradientUnits="userSpaceOnUse"><stop offset=".56" class="xhhozw94f"/><stop offset=".963" class="op-7n-bkz"/></radialGradient><radialGradient id="iBMYsHd" cx="0" cy="0" r="1" gradientTransform="rotate(99.197 -1.48 15.98)scale(1.09458 3.26059)" gradientUnits="userSpaceOnUse"><stop offset=".466" class="spsau2bne"/><stop offset="1" class="hbq83-d0t"/></radialGradient><radialGradient id="ihkMD0c" cx="0" cy="0" r="1" gradientTransform="matrix(-.15645 1.10324 -2.89548 -.4106 14.19 20.531)" gradientUnits="userSpaceOnUse"><stop offset=".466" class="spsau2bne"/><stop offset="1" class="hbq83-d0t"/></radialGradient><radialGradient id="iwaJVIb" cx="0" cy="0" r="1" gradientTransform="matrix(-.28295 .92188 -2.48547 -.76287 13.971 20.906)" gradientUnits="userSpaceOnUse"><stop offset=".369" class="spsau2bne"/><stop offset="1" class="hbq83-d0t"/></radialGradient><radialGradient id="iPJiZIb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.37499 1.625 -1.79466 -1.51854 29.032 12)" gradientUnits="userSpaceOnUse"><stop class="o043sbvrw"/><stop offset="1" class="esuo4rbni"/></radialGradient><radialGradient id="ivOBaEc" cx="0" cy="0" r="1" gradientTransform="matrix(2.12183 -1.33219 1.13322 1.80492 26.113 14.207)" gradientUnits="userSpaceOnUse"><stop offset=".319" class="bpd58tbtp"/><stop offset="1" class="c62l-bbjc"/></radialGradient><radialGradient id="i8ZICqS" cx="0" cy="0" r="1" gradientTransform="matrix(1.21193 1.13469 -1.89875 2.02802 19.176 12.24)" gradientUnits="userSpaceOnUse"><stop class="l8hx5tsqw"/><stop offset=".919" class="u555vebcp"/></radialGradient><radialGradient id="iCc9ieb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.96875 1.8125 0 20.063 26.89)" gradientUnits="userSpaceOnUse"><stop class="l4a0dtbst"/><stop offset="1" class="l2gyjvi4r"/></radialGradient><radialGradient id="iA6jHoe" cx="0" cy="0" r="1" gradientTransform="matrix(-2.14186 1.87499 -.94291 -1.07712 24.329 21.86)" gradientUnits="userSpaceOnUse"><stop offset=".188" class="vgnymzutm"/><stop offset="1" class="cttd8qtou"/></radialGradient><radialGradient id="iLlMvKd" cx="0" cy="0" r="1" gradientTransform="matrix(.99878 .71875 -2.04315 2.83916 21.188 20.14)" gradientUnits="userSpaceOnUse"><stop offset=".278" class="ad7150bof"/><stop offset="1" class="touvs0bsg"/></radialGradient><radialGradient id="ilxVv0k" cx="0" cy="0" r="1" gradientTransform="matrix(1.542 -1.58594 .4594 .44667 25.47 20.14)" gradientUnits="userSpaceOnUse"><stop class="hwnq5ubzm"/><stop offset="1" class="y9oqcminv"/></radialGradient><radialGradient id="iBvGaZb" cx="0" cy="0" r="1" gradientTransform="rotate(51.464 -6.858 32.231)scale(4.51441 1.8822)" gradientUnits="userSpaceOnUse"><stop offset=".154" class="rlrqah7ok"/><stop offset="1" class="r-6du_zhr"/></radialGradient><radialGradient id="icTxbKd" cx="0" cy="0" r="1" gradientTransform="matrix(-6.9688 -7.18748 5.67936 -5.50657 27.938 19.172)" gradientUnits="userSpaceOnUse"><stop offset=".93" class="i1avtge0l"/><stop offset="1" class="ifp1_xbmc"/></radialGradient><radialGradient id="iiD2NGe" cx="0" cy="0" r="1" gradientTransform="matrix(1.76758 -1.26563 1.69437 2.36637 24.53 29.906)" gradientUnits="userSpaceOnUse"><stop class="ct6_m01bp"/><stop offset="1" class="hh9ibwbje"/></radialGradient><radialGradient id="iJyCNEc" cx="0" cy="0" r="1" gradientTransform="matrix(1.64636 -1.26562 1.72962 2.24995 17.364 29.898)" gradientUnits="userSpaceOnUse"><stop class="ct6_m01bp"/><stop offset="1" class="hh9ibwbje"/></radialGradient><radialGradient id="iqdbALb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.82813 .85156 0 20.516 27.719)" gradientUnits="userSpaceOnUse"><stop class="utx5lkfyi"/><stop offset="1" class="xn9ndqb6s"/></radialGradient><radialGradient id="iD4h8Ac" cx="0" cy="0" r="1" gradientTransform="rotate(18.094 -5.973 -4.332)scale(5.2482 3.63584)" gradientUnits="userSpaceOnUse"><stop offset=".492" class="bhv6r6bju"/><stop offset="1" class="zfu-fxb-u"/></radialGradient><radialGradient id="i4cwRAb" cx="0" cy="0" r="1" gradientTransform="rotate(132.455 .956 2.189)scale(1.40764 3.24456)" gradientUnits="userSpaceOnUse"><stop offset=".134" class="lui_krbte"/><stop offset="1" class="e1m0hbbbn"/></radialGradient><radialGradient id="iycdpJe" cx="0" cy="0" r="1" gradientTransform="matrix(1.49685 3.75 -10.37919 4.14298 18.97 15.813)" gradientUnits="userSpaceOnUse"><stop offset=".368" class="vkuvqbbwu"/><stop offset=".969" class="elr5y7baq"/></radialGradient><radialGradient id="i3WnUge" cx="0" cy="0" r="1" gradientTransform="matrix(-.96876 1.75 -2.0554 -1.13783 23.939 12.813)" gradientUnits="userSpaceOnUse"><stop class="r_8k9swvo"/><stop offset="1" class="q9ojxt_ur"/></radialGradient><radialGradient id="iMKiCyc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.00452 .04153 -.0243 -1.17307 17.046 18.325)" gradientUnits="userSpaceOnUse"><stop offset=".744" class="lid3ide5q"/><stop offset="1" class="r2t9jab3e"/></radialGradient><radialGradient id="iMtVDIb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .49784 -1.34351 0 16.36 19.205)" gradientUnits="userSpaceOnUse"><stop class="z_yn3vbua"/><stop offset="1" class="j6lbcibwa"/></radialGradient><radialGradient id="i3ybiac" cx="0" cy="0" r="1" gradientTransform="matrix(-1.9726 .04153 -.0247 -1.17306 17.055 18.952)" gradientUnits="userSpaceOnUse"><stop offset=".744" class="lid3ide5q"/><stop offset="1" class="r2t9jab3e"/></radialGradient><radialGradient id="ipRqVUh" cx="0" cy="0" r="1" gradientTransform="rotate(117.286 4.578 9.187)scale(.72019 .91721)" gradientUnits="userSpaceOnUse"><stop offset=".332" class="fvok_qxen"/><stop offset="1" class="suyap8bzv"/></radialGradient><radialGradient id="idLxkvc" cx="0" cy="0" r="1" gradientTransform="matrix(.89142 -.04952 .06038 1.08682 11.103 8.892)" gradientUnits="userSpaceOnUse"><stop offset=".156" class="d7kch3t0q"/><stop offset="1" class="admd7db0k"/></radialGradient><radialGradient id="iPgHftc" cx="0" cy="0" r="1" gradientTransform="rotate(42.274 -3.302 14.837)scale(4.90812 5.5655)" gradientUnits="userSpaceOnUse"><stop offset=".363" class="jve2rcqoj"/><stop offset="1" class="kpbiulbbs"/></radialGradient><radialGradient id="iPENaDb" cx="0" cy="0" r="1" gradientTransform="matrix(.1238 -1.3784 2.92276 .26252 9.79 10.512)" gradientUnits="userSpaceOnUse"><stop offset=".064" class="jfv70ccah"/><stop offset="1" class="b30rr0b3q"/></radialGradient><radialGradient id="iIpElOb" cx="0" cy="0" r="1" gradientTransform="matrix(.47873 .9946 -1.61617 .7779 10.781 8.702)" gradientUnits="userSpaceOnUse"><stop offset=".04" class="bervkqbmz"/><stop offset="1" class="c479w-bpn"/></radialGradient><radialGradient id="i8JH2Hb" cx="0" cy="0" r="1" gradientTransform="matrix(-.28889 0 0 -.56127 13.6 8.97)" gradientUnits="userSpaceOnUse"><stop offset=".895" class="l0aricxam"/><stop offset="1" class="n9r91ylyy"/></radialGradient><radialGradient id="iWpWyDb" cx="0" cy="0" r="1" gradientTransform="matrix(-.26364 0 0 -.57054 13.778 8.992)" gradientUnits="userSpaceOnUse"><stop class="gv3iwdbvq"/><stop offset=".813" class="ubyl24bdb"/></radialGradient><radialGradient id="iNIOZBK" cx="0" cy="0" r="1" gradientTransform="matrix(.23047 .0586 -.60662 2.38602 10.825 7.52)" gradientUnits="userSpaceOnUse"><stop class="a5dbyd6tf"/><stop offset="1" class="on8sxx3yx"/></radialGradient><radialGradient id="i18w8vv" cx="0" cy="0" r="1" gradientTransform="matrix(-.52148 1.82813 -.23787 -.06785 11.868 5.781)" gradientUnits="userSpaceOnUse"><stop class="ak32k0b7k"/><stop offset="1" class="rknzqr02l"/></radialGradient><radialGradient id="ixAIarb" cx="0" cy="0" r="1" gradientTransform="matrix(-.35156 .1875 -.70184 -1.31597 11.704 10.797)" gradientUnits="userSpaceOnUse"><stop class="kgukkhbth"/><stop offset="1" class="k8s01tfdv"/></radialGradient><radialGradient id="iCxY2nc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.03124 1.09376 -.96833 -1.7983 11.751 8.688)" gradientUnits="userSpaceOnUse"><stop class="k0iy46b0f"/><stop offset="1" class="cwawnsbpb"/></radialGradient><radialGradient id="ixWo8nc" cx="0" cy="0" r="1" gradientTransform="matrix(.76953 0 0 1.98438 9.435 9.172)" gradientUnits="userSpaceOnUse"><stop class="jdkxlmkke"/><stop offset="1" class="u8cibcbeo"/></radialGradient><radialGradient id="inoyoOd" cx="0" cy="0" r="1" gradientTransform="matrix(-.76563 -.64062 1.04002 -1.24297 11.782 10.063)" gradientUnits="userSpaceOnUse"><stop class="nuhsp4_no"/><stop offset="1" class="ye033cbdf"/></radialGradient><radialGradient id="i9FhXVb" cx="0" cy="0" r="1" gradientTransform="matrix(-.49331 1.0236 -1.6646 -.80223 20.627 8.614)" gradientUnits="userSpaceOnUse"><stop offset=".04" class="bervkqbmz"/><stop offset="1" class="c479w-bpn"/></radialGradient><radialGradient id="iGJ3NXh" cx="0" cy="0" r="1" gradientTransform="rotate(62.714 .573 18.169)scale(.72019 .91721)" gradientUnits="userSpaceOnUse"><stop offset=".332" class="pxzqtt8pl"/><stop offset="1" class="lwe9_nbqv"/></radialGradient><radialGradient id="ibstNpP" cx="0" cy="0" r="1" gradientTransform="matrix(-.89142 -.0496 .06048 -1.08682 20.195 8.893)" gradientUnits="userSpaceOnUse"><stop offset=".156" class="d7kch3t0q"/><stop offset="1" class="admd7db0k"/></radialGradient><radialGradient id="idjQllb" cx="0" cy="0" r="1" gradientTransform="rotate(130.227 8.154 9.436)scale(1.94875 1.89307)" gradientUnits="userSpaceOnUse"><stop offset=".437" class="qkiupezfq"/><stop offset="1" class="us4sdgeme"/></radialGradient><radialGradient id="iJWwfRd" cx="0" cy="0" r="1" gradientTransform="matrix(-3.6317 3.30158 -3.74378 -4.11812 22.177 6.08)" gradientUnits="userSpaceOnUse"><stop offset=".363" class="jve2rcqoj"/><stop offset="1" class="kpbiulbbs"/></radialGradient><radialGradient id="iaLcvNc" cx="0" cy="0" r="1" gradientTransform="rotate(-95.133 15.56 -4.576)scale(1.38395 2.93453)" gradientUnits="userSpaceOnUse"><stop offset=".064" class="jfv70ccah"/><stop offset="1" class="b30rr0b3q"/></radialGradient><radialGradient id="iWHGnHc" cx="0" cy="0" r="1" gradientTransform="rotate(115.703 7.524 10.799)scale(1.10381 1.79364)" gradientUnits="userSpaceOnUse"><stop offset=".04" class="bervkqbmz"/><stop offset="1" class="c479w-bpn"/></radialGradient><radialGradient id="iHDgSne" cx="0" cy="0" r="1" gradientTransform="matrix(.28889 0 0 .56127 17.699 8.97)" gradientUnits="userSpaceOnUse"><stop offset=".895" class="l0aricxam"/><stop offset="1" class="n9r91ylyy"/></radialGradient><radialGradient id="ifc6omd" cx="0" cy="0" r="1" gradientTransform="matrix(.26364 0 0 .57054 17.522 8.992)" gradientUnits="userSpaceOnUse"><stop class="gv3iwdbvq"/><stop offset=".813" class="ubyl24bdb"/></radialGradient><radialGradient id="ieqwynb" cx="0" cy="0" r="1" gradientTransform="rotate(165.735 9.767 5.04)scale(.2378 2.46193)" gradientUnits="userSpaceOnUse"><stop class="a5dbyd6tf"/><stop offset="1" class="on8sxx3yx"/></radialGradient><radialGradient id="iPleFIc" cx="0" cy="0" r="1" gradientTransform="matrix(.52148 1.82813 -.23787 .06785 19.432 5.781)" gradientUnits="userSpaceOnUse"><stop class="ak32k0b7k"/><stop offset="1" class="rknzqr02l"/></radialGradient><radialGradient id="i4dTTzQ" cx="0" cy="0" r="1" gradientTransform="matrix(.35156 .1875 -.70186 1.31595 19.596 10.797)" gradientUnits="userSpaceOnUse"><stop class="kgukkhbth"/><stop offset="1" class="k8s01tfdv"/></radialGradient><radialGradient id="i0wCBJc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.03124 1.09376 -.96833 -1.7983 2.316 .797)" gradientUnits="userSpaceOnUse"><stop class="k0iy46b0f"/><stop offset="1" class="cwawnsbpb"/></radialGradient><radialGradient id="iXGn3Cd" cx="0" cy="0" r="1" gradientTransform="matrix(.76953 0 0 1.98438 0 1.281)" gradientUnits="userSpaceOnUse"><stop class="jdkxlmkke"/><stop offset="1" class="u8cibcbeo"/></radialGradient><radialGradient id="iNSGxke" cx="0" cy="0" r="1" gradientTransform="matrix(-.76563 -.64062 1.04002 -1.24297 2.348 2.172)" gradientUnits="userSpaceOnUse"><stop class="nuhsp4_no"/><stop offset="1" class="ye033cbdf"/></radialGradient><linearGradient id="ip7i9le" x1="6.345" x2="8.126" y1="21.313" y2="19.625" gradientUnits="userSpaceOnUse"><stop class="omfadubst"/><stop offset="1" class="qka3_sxpa"/></linearGradient><linearGradient id="ieHzg0d" x1="8.048" x2="7.836" y1="20.703" y2="20.492" gradientUnits="userSpaceOnUse"><stop class="w7fy1faaf"/><stop offset="1" class="yik88x48u"/></linearGradient><linearGradient id="ilQJnzb" x1="5.282" x2="6.563" y1="20.75" y2="20.813" gradientUnits="userSpaceOnUse"><stop offset=".28" class="a8j9w7nsg"/><stop offset="1" class="nmxkbkb2v"/></linearGradient><linearGradient id="iL3KCRb" x1="1.97" x2="2.556" y1="29.563" y2="29.695" gradientUnits="userSpaceOnUse"><stop offset=".107" class="oybn7vbqt"/><stop offset="1" class="al_auo8nl"/></linearGradient><linearGradient id="iJzlOde" x1="5.345" x2="5.345" y1="29.922" y2="29.598" gradientUnits="userSpaceOnUse"><stop class="i_emxkhmq"/><stop offset="1" class="qihskpbeg"/></linearGradient><linearGradient id="imYfwQe" x1="9.475" x2="10.02" y1="29.688" y2="29.671" gradientUnits="userSpaceOnUse"><stop offset=".107" class="oybn7vbqt"/><stop offset="1" class="al_auo8nl"/></linearGradient><linearGradient id="ioTrI7b" x1="12.618" x2="12.618" y1="29.914" y2="29.59" gradientUnits="userSpaceOnUse"><stop class="i_emxkhmq"/><stop offset="1" class="qihskpbeg"/></linearGradient><linearGradient id="iQ74Fze" x1="10.084" x2="10.084" y1="11.554" y2="16.128" gradientUnits="userSpaceOnUse"><stop class="cdk0jybbv"/><stop offset="1" class="sqoomfbpf"/></linearGradient><linearGradient id="iNnZTYd" x1="13.126" x2="13.36" y1="22.078" y2="21.648" gradientUnits="userSpaceOnUse"><stop offset=".245" class="o5wphbctr"/><stop offset="1" class="bev6mnbks"/></linearGradient><linearGradient id="iXDgeDv" x1="26.113" x2="26.113" y1="11.288" y2="11.703" gradientUnits="userSpaceOnUse"><stop class="mbxf6yyls"/><stop offset="1" class="rixtyr4np"/></linearGradient><linearGradient id="ibXOHre" x1="28.923" x2="28.47" y1="14.953" y2="14.688" gradientUnits="userSpaceOnUse"><stop class="mbxf6yyls"/><stop offset="1" class="rixtyr4np"/></linearGradient><linearGradient id="i13Klac" x1="25.094" x2="23.313" y1="21.297" y2="19.609" gradientUnits="userSpaceOnUse"><stop class="omfadubst"/><stop offset="1" class="qka3_sxpa"/></linearGradient><linearGradient id="iDrqAtc" x1="23.391" x2="23.603" y1="20.688" y2="20.477" gradientUnits="userSpaceOnUse"><stop class="w7fy1faaf"/><stop offset="1" class="yik88x48u"/></linearGradient><linearGradient id="iMOdSCb" x1="26.157" x2="24.875" y1="20.734" y2="20.797" gradientUnits="userSpaceOnUse"><stop offset=".28" class="a8j9w7nsg"/><stop offset="1" class="nmxkbkb2v"/></linearGradient><linearGradient id="iEkbWte" x1="29.469" x2="28.883" y1="29.547" y2="29.68" gradientUnits="userSpaceOnUse"><stop offset=".107" class="oybn7vbqt"/><stop offset="1" class="al_auo8nl"/></linearGradient><linearGradient id="ixXfchc" x1="26.094" x2="26.094" y1="29.906" y2="29.582" gradientUnits="userSpaceOnUse"><stop class="i_emxkhmq"/><stop offset="1" class="qihskpbeg"/></linearGradient><linearGradient id="i3vLhpe" x1="21.964" x2="21.419" y1="29.672" y2="29.655" gradientUnits="userSpaceOnUse"><stop offset=".107" class="oybn7vbqt"/><stop offset="1" class="al_auo8nl"/></linearGradient><linearGradient id="ikcfrVc" x1="18.821" x2="18.821" y1="29.898" y2="29.574" gradientUnits="userSpaceOnUse"><stop class="i_emxkhmq"/><stop offset="1" class="qihskpbeg"/></linearGradient><linearGradient id="ixvNnqb" x1="1.732" x2="1.732" y1="0" y2="4.574" gradientUnits="userSpaceOnUse"><stop class="cdk0jybbv"/><stop offset="1" class="sqoomfbpf"/></linearGradient><linearGradient id="irJO0Yd" x1="16.009" x2="17.753" y1="18.388" y2="18.388" gradientUnits="userSpaceOnUse"><stop offset=".527" class="om8lrbchi"/><stop offset="1" class="hsvyf4b5t"/></linearGradient><linearGradient id="iQ1KS4b" x1="17.095" x2="17.095" y1="19.975" y2="19.5" gradientUnits="userSpaceOnUse"><stop class="ama23x97l"/><stop offset="1" class="naks3_bia"/></linearGradient><linearGradient id="ia0MOjD" x1="16.035" x2="17.751" y1="19.016" y2="19.016" gradientUnits="userSpaceOnUse"><stop offset=".527" class="om8lrbchi"/><stop offset="1" class="hsvyf4b5t"/></linearGradient><linearGradient id="i7R5qub" x1="11.434" x2="14.457" y1="9.676" y2="9.858" gradientUnits="userSpaceOnUse"><stop class="egm-dub4f"/><stop offset="1" class="zhwoohbuw"/></linearGradient><linearGradient id="ikikhKc" x1="-.007" x2=".189" y1=".052" y2=".116" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="stui2mbih"/></linearGradient><linearGradient id="iXoBHTe" x1="11.696" x2="10.622" y1="6.828" y2="7.734" gradientUnits="userSpaceOnUse"><stop class="nzvqyeb9k"/><stop offset="1" class="cnb6h8b8g"/></linearGradient><linearGradient id="inY1tGE" x1="11.126" x2="12.477" y1="10.437" y2="12.266" gradientUnits="userSpaceOnUse"><stop class="mfaot4byg"/><stop offset="1" class="fx9brcb0h"/></linearGradient><linearGradient id="iBSEZzd" x1="19.866" x2="16.842" y1="9.676" y2="9.858" gradientUnits="userSpaceOnUse"><stop offset=".607" class="x9w8qi-jn"/><stop offset="1" class="f8pl1cbjp"/></linearGradient><linearGradient id="inwNN5b" x1="17.515" x2="17.71" y1="8.581" y2="8.645" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="stui2mbih"/></linearGradient><linearGradient id="iCVYhce" x1="19.604" x2="20.678" y1="6.828" y2="7.734" gradientUnits="userSpaceOnUse"><stop class="nzvqyeb9k"/><stop offset="1" class="cnb6h8b8g"/></linearGradient><linearGradient id="iiPPxFd" x1="20.174" x2="18.822" y1="10.437" y2="12.266" gradientUnits="userSpaceOnUse"><stop class="mfaot4byg"/><stop offset="1" class="fx9brcb0h"/></linearGradient><filter id="i4qKEid" width="2.691" height="1.989" x="15.599" y="12.66" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.772549 0 0 0 0 0.478431 0 0 0 0 0.0941176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23626"/></filter><filter id="ibK2X5f" width="10.808" height="5.007" x="8.21" y="11.989" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.878431 0 0 0 0 0.541176 0 0 0 0 0.188235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23626"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.843137 0 0 0 0 0.478431 0 0 0 0 0.172549 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23626" result="effect2_innerShadow_3987_23626"/></filter><filter id="iD4Pj7c" width="4.146" height="5.805" x="2.507" y="21.5" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.819608 0 0 0 0 0.278431 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23626"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.921569 0 0 0 0 0.666667 0 0 0 0 0.152941 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23626" result="effect2_innerShadow_3987_23626"/></filter><filter id="iwHSPGe" width="9.426" height="8.574" x="2.437" y="11.299" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.290196 0 0 0 0 0.67451 0 0 0 0 0.956863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23626"/></filter><filter id="ic4fbpe" width="5.878" height="6.781" x="1.864" y="15.18" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.290196 0 0 0 0 0.67451 0 0 0 0 0.956863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23626"/></filter><filter id="inM5yJb" width="5.139" height="3.208" x="1.77" y="26.914" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.294118 0 0 0 0 0.466667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23626"/></filter><filter id="iqc5L9d" width="2.686" height="1.05" x="2.418" y="26.914" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.819608 0 0 0 0 0.776471 0 0 0 0 0.8 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23626"/></filter><filter id="iAcUyDA" width="4.9" height="3.308" x="9.175" y="26.906" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".3"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.294118 0 0 0 0 0.466667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23626"/></filter><filter id="iQp0yyM" width="2.288" height="1.065" x="9.475" y="26.906" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.752941 0 0 0 0 0.690196 0 0 0 0 0.74902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23626"/></filter><filter id="iDLn2TO" width="5.149" height="5.149" x="5.385" y="11.822" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23626" stdDeviation=".125"/></filter><filter id="iTiexIb" width="1.796" height="1.427" x="13.089" y="19.239" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.756863 0 0 0 0 0.470588 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23626"/></filter><filter id="iC3lTYb" width="1.065" height="1.475" x="16.948" y="16.853" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.898039 0 0 0 0 0.635294 0 0 0 0 0.180392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23626"/></filter><filter id="ib2od4b" width="4.146" height="5.805" x="24.785" y="21.484" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.819608 0 0 0 0 0.278431 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23626"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.921569 0 0 0 0 0.666667 0 0 0 0 0.152941 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23626" result="effect2_innerShadow_3987_23626"/></filter><filter id="i4EPfld" width="9.426" height="8.574" x="19.576" y="11.284" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.75"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.290196 0 0 0 0 0.67451 0 0 0 0 0.956863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23626"/></filter><filter id="iKm7yJc" width="5.878" height="6.781" x="23.697" y="15.164" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.75"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.290196 0 0 0 0 0.67451 0 0 0 0 0.956863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23626"/></filter><filter id="iA5Jaoc" width="5.139" height="3.208" x="24.33" y="26.898" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.294118 0 0 0 0 0.466667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23626"/></filter><filter id="ipTVUee" width="2.686" height="1.05" x="26.634" y="26.898" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.819608 0 0 0 0 0.776471 0 0 0 0 0.8 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23626"/></filter><filter id="iUhChec" width="4.9" height="3.308" x="17.064" y="26.891" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".3"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.294118 0 0 0 0 0.466667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23626"/></filter><filter id="iqGNMqb" width="2.288" height="1.065" x="19.876" y="26.891" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.752941 0 0 0 0 0.690196 0 0 0 0 0.74902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23626"/></filter><filter id="iclpEqb" width="5.149" height="5.149" x="20.905" y="11.806" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23626" stdDeviation=".125"/></filter><filter id="iDQudMd" width="4.883" height="5.535" x="9.975" y="6.581" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.94902 0 0 0 0 0.533333 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23626"/></filter><filter id="iQvWaze" width="6.724" height="5.754" x="8.285" y="4.849" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.835294 0 0 0 0 0.211765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23626"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.3"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.976471 0 0 0 0 0.592157 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23626" result="effect2_innerShadow_3987_23626"/></filter><filter id="i763tGe" width="1.258" height=".393" x="12.669" y="7.822" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.632517 0 0 0 0 0.207713 0 0 0 0 0.0745123 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23626"/></filter><filter id="ikdCG8e" width="4.883" height="5.535" x="16.442" y="6.581" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.894118 0 0 0 0 0.556863 0 0 0 0 0.0941176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23626"/></filter><filter id="ilPUqFd" width="6.724" height="5.754" x="16.19" y="4.849" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.835294 0 0 0 0 0.211765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23626"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.3"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.976471 0 0 0 0 0.592157 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23626" result="effect2_innerShadow_3987_23626"/></filter><filter id="iQ876Ip" width="1.258" height=".393" x="17.373" y="7.822" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.632517 0 0 0 0 0.207713 0 0 0 0 0.0745123 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23626"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-wrestling" /></template>
<style>
.a-a659b1q {
  fill: var(--svg-color--524d8c, #524D8C);
  d: path("m28.8 26.974l.661 2.621a.25.25 0 0 1-.242.311h-4.442c-.101 0-.196-.06-.22-.158c-.126-.504.197-.866.764-1.158a87 87 0 0 0 1.695-.9l-.376-.718a.05.05 0 0 1 .044-.074h2.02a.1.1 0 0 1 .097.076");
}

.a5dbyd6tf {
  stop-color: var(--svg-color--5e4d44, #5E4D44);
}

.a8j9w7nsg {
  stop-color: var(--svg-color--194ec0, #194EC0);
}

.ad7150bof {
  stop-color: var(--svg-color--e8a22e, #E8A22E);
}

.admd7db0k {
  stop-color: var(--svg-color--ffab1d, #FFAB1D);
  stop-opacity: 0;
}

.ahv1csbpk {
  fill-rule: evenodd;
  d: path("M12.745 21.139a.4.4 0 0 1 .559-.087l.746.547a.4.4 0 0 1-.473.645l-.746-.546a.4.4 0 0 1-.086-.56");
}

.aie3sbybt {
  stop-color: var(--svg-color--b06c27, #B06C27);
}

.ak32k0b7k {
  stop-color: var(--svg-color--695d73, #695D73);
}

.al_auo8nl {
  stop-color: var(--svg-color--6d6a94, #6D6A94);
  stop-opacity: 0;
}

.ama23x97l {
  stop-color: var(--svg-color--e19839, #E19839);
}

.avs6vzbgz {
  d: path("m6.864 21.811l-1.082-1.006l-1.148-1.024l3.133-1.906a78 78 0 0 0 1.399 1.66a.05.05 0 0 1-.003.068l-2.23 2.207a.05.05 0 0 1-.069.001");
}

.b30rr0b3q {
  stop-color: var(--svg-color--ef9926, #EF9926);
  stop-opacity: 0;
}

.b5vaz6biu {
  width: 0.855px;
  height: 0.248px;
  x: 13.024px;
  y: 10.307px;
  fill: var(--svg-color--87014d, #87014D);
  rx: 0.124px;
}

.b61r46b1w {
  width: 0.855px;
  height: 0.248px;
  fill: var(--svg-color--87014d, #87014D);
  rx: 0.124px;
}

.bbakdxbza {
  stop-color: var(--svg-color--e48527, #E48527);
}

.bd47k7a5l {
  fill: var(--svg-color--c16c25, #C16C25);
  d: path("m16.19 12.964l-.591.57l.297 1.115l1.425-.506l-.079-.116a.32.32 0 0 1-.024-.311l.03-.064a.2.2 0 0 1 .186-.118h.419a.437.437 0 1 0 0-.874h-.907c-.332 0-.643.203-.756.304");
}

.bervkqbmz {
  stop-color: var(--svg-color--ffd040, #FFD040);
}

.bes5zfizp {
  d: path("m13.46 8.992l-.004-.076c0-.196.083-.354.186-.354c.102 0 .185.159.185.354l-.004.076z");
}

.bev6mnbks {
  stop-color: var(--svg-color--f9bf3b, #F9BF3B);
  stop-opacity: 0;
}

.bhv6r6bju {
  stop-color: var(--svg-color--ffd83f, #FFD83F);
}

.bpd58tbtp {
  stop-color: var(--svg-color--ea760b, #EA760B);
}

.c479w-bpn {
  stop-color: var(--svg-color--fead30, #FEAD30);
}

.c62l-bbjc {
  stop-color: var(--svg-color--ffa31c, #FFA31C);
  stop-opacity: 0;
}

.cdk0jybbv {
  stop-color: var(--svg-color--35aaf7, #35AAF7);
}

.cfe6fmtoq {
  d: path("m11.5 9.69l-.21-1.52a.768.768 0 0 0 .21 1.52");
}

.cnb6h8b8g {
  stop-color: var(--svg-color--241e28, #241E28);
}

.comfxdbed {
  d: path("m21.875 27.836l.089-.89a.05.05 0 0 0-.05-.055h-1.989a.05.05 0 0 0-.05.05v.766c-.558.262-1.626.807-2.074 1.117c-.377.261-.44.563-.437.801c.002.156.142.273.297.273h3.964a.25.25 0 0 0 .25-.25z");
}

.ct6_m01bp {
  stop-color: var(--svg-color--5e5a92, #5E5A92);
}

.cttd8qtou {
  stop-color: var(--svg-color--d58b3f, #D58B3F);
  stop-opacity: 0;
}

.cwawnsbpb {
  stop-color: var(--svg-color--403547, #403547);
}

.czujv0sxy {
  fill: var(--svg-color--ffb330, #FFB330);
  d: path("m15.794 13.137l.535-.516c.124-.11.462-.332.824-.332h.989a.476.476 0 1 1 0 .953h-.866a.22.22 0 0 0-.203.129l-.032.07a.34.34 0 0 0-.002.287l.556-.038a.516.516 0 0 1 .071 1.029l-.67.046c-.738 1.026-1.884 2.055-3.901 2.229c-2.386.056-3.713-1.182-4.258-1.691a9 9 0 0 0-.212-.192a1.15 1.15 0 1 1 1.47-1.769c.023.02.077-.013.134-.046c.064-.038.131-.078.163-.05q.08.07.17.153c.497.455 1.236 1.132 2.533 1.132c.39 0 .884-.013 1.408-.336c.51-.314.937-.7 1.167-.95a.7.7 0 0 1 .124-.108");
}

.d7kch3t0q {
  stop-color: var(--svg-color--ffab1d, #FFAB1D);
}

.dm4voe-la {
  d: path("M0 0h2.371v3.351H0z");
}

.e1m0hbbbn {
  stop-color: var(--svg-color--e68f26, #E68F26);
  stop-opacity: 0;
}

.e53sdbbza {
  fill: var(--svg-color--ffd93e, #FFD93E);
  fill-rule: evenodd;
  d: path("M7.949 12.851a1.15 1.15 0 0 1 1.388.847c.33 1.361 1.57 4.161 4.242 5.911c.54.336.765 1.006.43 1.545a1.15 1.15 0 0 1-1.584.37c-3.291-1.75-4.815-4.977-5.323-7.284a1.15 1.15 0 0 1 .847-1.389");
}

.egm-dub4f {
  stop-color: var(--svg-color--ffc33e, #FFC33E);
}

.egzdhvbpq {
  d: path("M19.876 27.696v-.755a.05.05 0 0 1 .05-.05h1.988a.05.05 0 0 1 .05.055l-.088.89v.02z");
}

.ei0jw7bok {
  fill: var(--svg-color--fecf3d, #FECF3D);
  fill-rule: evenodd;
  d: path("M12.745 21.139a.4.4 0 0 1 .559-.087l.746.547a.4.4 0 0 1-.473.645l-.746-.546a.4.4 0 0 1-.086-.56");
}

.elr5y7baq {
  stop-color: var(--svg-color--d3843a, #D3843A);
}

.esuo4rbni {
  stop-color: var(--svg-color--ffc230, #FFC230);
}

.f5es1ac2s {
  cx: 10.716px;
  cy: 9.172px;
  r: 1.281px;
}

.f8pl1cbjp {
  stop-color: var(--svg-color--f3a028, #F3A028);
}

.ft5dv1b6b {
  fill: none;
}

.fvok_qxen {
  stop-color: var(--svg-color--ffbf42, #FFBF42);
}

.fwfxfrotv {
  fill: var(--svg-color--524d8c, #524D8C);
  d: path("m9.564 27.851l-.089-.89a.05.05 0 0 1 .05-.055h1.989a.05.05 0 0 1 .05.05v.767c.558.261 1.626.807 2.074 1.117c.377.261.44.563.437.801c-.002.155-.142.273-.297.273H9.814a.25.25 0 0 1-.25-.25z");
}

.fx9brcb0h {
  stop-color: var(--svg-color--704459, #704459);
}

.g3eobnbex {
  fill-rule: evenodd;
  d: path("M10.821 9.862a.25.25 0 0 1 .326.138c.1.247.284.645.51 1.038c.23.399.489.767.733.975a.25.25 0 0 1-.325.38c-.312-.266-.605-.697-.84-1.106a10 10 0 0 1-.541-1.1a.25.25 0 0 1 .137-.325");
}

.g3g2_db3x {
  width: 0.764px;
  height: 1.4px;
  x: 16.813px;
  y: 17.229px;
  fill: var(--svg-color--ffc427, #FFC427);
  rx: 0.382px;
}

.g83fgbbyy {
  fill-rule: evenodd;
  d: path("M7.949 12.851a1.15 1.15 0 0 1 1.388.847c.33 1.361 1.57 4.161 4.242 5.911c.54.336.765 1.006.43 1.545a1.15 1.15 0 0 1-1.584.37c-3.291-1.75-4.815-4.977-5.323-7.284a1.15 1.15 0 0 1 .847-1.389");
}

.gg2ehgbth {
  width: 3.464px;
  height: 4.574px;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  rx: 1.732px;
}

.ggeojxayc {
  fill: var(--svg-color--f4a72a, #F4A72A);
  fill-rule: evenodd;
  d: path("M14.846 19.616a.4.4 0 0 1-.188.534l-.996.476a.4.4 0 0 1-.345-.721l.996-.477a.4.4 0 0 1 .533.188");
}

.gq4385_0g {
  d: path("m19.799 9.69l.21-1.52a.768.768 0 0 1-.21 1.52");
}

.gv3iwdbvq {
  stop-color: var(--svg-color--666361, #666361);
}

.gw8ri5cen {
  stop-color: var(--svg-color--f49326, #F49326);
}

.ha76tmxnj {
  fill: var(--svg-color--fabd38, #FABD38);
  d: path("m3.61 23.617l-.57-1.726l2.875-.391l.203 1.43c.131.918-.125 1.664-.375 2.203l-1.219 2.172H2.657c.245-.771.844-2.77.93-3.032c.086-.261.086-.48.023-.656");
}

.hbq83-d0t {
  stop-color: var(--svg-color--f5a333, #F5A333);
}

.hc9rtyb3n {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.406 8.993h1.044c0-.414-.233-.749-.522-.749c-.288 0-.522.335-.522.75");
}

.hh9ibwbje {
  stop-color: var(--svg-color--5e5a92, #5E5A92);
  stop-opacity: 0;
}

.hjv1ly6lq {
  d: path("M13.753 7.359c.693 0 1.023-.392 1.056-.883c0-.694-.53-.84-.734-.863c-.232-.025-.322-.05-.644-.276a.95.95 0 0 0-.962-.103c-.157.074-.503.111-.751.037c-.413-.124-.735-.12-1.052.123c-.221.17-.384.17-.648.17c-.363 0-.672.162-.904.338c-.695.526-.615 2.332-.272 3.347c.327.971.82 1.085 1.233 1.048c.497-.044.624-.42.698-.734c.06-.251.212-.837.28-1.098c.144-.066.456-.3.562-.71c.105-.41.52-.456.8-.43c.171.017.644.034 1.338.034");
}

.hn_62y1ma {
  d: path("m9.564 27.851l-.089-.89a.05.05 0 0 1 .05-.055h1.989a.05.05 0 0 1 .05.05v.767c.558.261 1.626.807 2.074 1.117c.377.261.44.563.437.801c-.002.155-.142.273-.297.273H9.814a.25.25 0 0 1-.25-.25z");
}

.hptrd5b0d {
  fill-rule: evenodd;
  d: path("M13.112 20.623a.45.45 0 0 1 .625-.121l.973.656a.45.45 0 1 1-.504.746l-.973-.656a.45.45 0 0 1-.12-.625");
}

.hsvyf4b5t {
  stop-color: var(--svg-color--f5b436, #F5B436);
  stop-opacity: 0;
}

.hwnq5ubzm {
  stop-color: var(--svg-color--2670da, #2670DA);
}

.i_emxkhmq {
  stop-color: var(--svg-color--442f88, #442F88);
}

.i1avtge0l {
  stop-color: var(--svg-color--2f80be, #2F80BE);
  stop-opacity: 0;
}

.ifp1_xbmc {
  stop-color: var(--svg-color--2f80be, #2F80BE);
}

.igqqc-b6y {
  fill: var(--svg-color--ffca33, #FFCA33);
  fill-rule: evenodd;
  d: path("M23.565 12.67c.627.167 1 .81.832 1.438c-.25.937-.944 2.3-2.01 3.45c-1.076 1.157-2.671 2.248-4.616 2.413a1.175 1.175 0 0 1-1.27-1.071c-.055-.647.363-1.162 1.01-1.217c1.207-.141 2.262-.825 3.112-1.74c.86-.925 1.371-1.944 1.503-2.44c.168-.627.811-1 1.438-.833");
}

.iqlz2hawi {
  d: path("M19.035 10.561h2.371v3.351h-2.371z");
}

.iua_52v7a {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.893 8.993H12.85c0-.414.234-.749.522-.749s.522.335.522.75");
}

.ixcfis0oi {
  fill: var(--svg-color--2797f6, #2797F6);
  d: path("m28.791 15.828l-.664-.664l-3.68 3.953l1.211 1.016s-.193 1.043-.268 1.758a.05.05 0 0 0 .05.054h3.025a.05.05 0 0 0 .048-.034c.16-.506.565-1.792.937-3.24c.41-1.591-.286-2.517-.659-2.843");
}

.j3dn9fs5p {
  cx: 17.59px;
  cy: 8.621px;
  rx: 0.068px;
  ry: 0.092px;
}

.j3ug58blb {
  d: path("M11.563 27.712v-.756a.05.05 0 0 0-.05-.05H9.525a.05.05 0 0 0-.05.055l.088.89v.02z");
}

.j6lbcibwa {
  stop-color: var(--svg-color--ffcc3d, #FFCC3D);
  stop-opacity: 0;
}

.jdkxlmkke {
  stop-color: var(--svg-color--656262, #656262);
}

.jfv70ccah {
  stop-color: var(--svg-color--b28146, #B28146);
}

.jn8cu6s_w {
  fill: var(--svg-color--2797f6, #2797F6);
  d: path("M6.546 12.054a2.696 2.696 0 0 1 3.752 3.873l-3.262 3.178a2.71 2.71 0 1 1-3.77-3.892z");
}

.jnbv5jxhd {
  fill-rule: evenodd;
  d: path("M20.479 9.862a.25.25 0 0 0-.326.138a9 9 0 0 1-.51 1.038c-.23.399-.489.767-.733.975a.25.25 0 1 0 .325.38c.312-.266.605-.697.84-1.106c.24-.414.433-.833.541-1.1a.25.25 0 0 0-.137-.325");
}

.jnmo26gja {
  d: path("M18.045 8.993V8.99c0-.338-.145-.613-.324-.613c-.178 0-.323.275-.323.613v.004z");
}

.jve2rcqoj {
  stop-color: var(--svg-color--ffbc2b, #FFBC2B);
}

.k0iy46b0f {
  stop-color: var(--svg-color--625a6a, #625A6A);
}

.k8s01tfdv {
  stop-color: var(--svg-color--5e5663, #5E5663);
  stop-opacity: 0;
}

.kgukkhbth {
  stop-color: var(--svg-color--5e5663, #5E5663);
}

.kgwyv9bwy {
  fill: var(--svg-color--ffd93e, #FFD93E);
  fill-rule: evenodd;
  d: path("M13.093 19.785a.4.4 0 0 1 .549-.135c.405.245.86.47 1.376.647a.4.4 0 1 1-.26.757a8 8 0 0 1-1.53-.72a.4.4 0 0 1-.135-.549");
}

.kiki776xu {
  d: path("m19.886 9.632l.217-1.565a.79.79 0 0 1-.217 1.565");
}

.km6_kbc8h {
  stop-color: var(--svg-color--ffc437, #FFC437);
}

.kpbiulbbs {
  stop-color: var(--svg-color--ffa629, #FFA629);
}

.l0aricxam {
  stop-color: var(--svg-color--916a62, #916A62);
}

.l0hz2bwjg {
  fill: var(--svg-color--524d8c, #524D8C);
  d: path("m21.875 27.836l.089-.89a.05.05 0 0 0-.05-.055h-1.989a.05.05 0 0 0-.05.05v.766c-.558.262-1.626.807-2.074 1.117c-.377.261-.44.563-.437.801c.002.156.142.273.297.273h3.964a.25.25 0 0 0 .25-.25z");
}

.l2gyjvi4r {
  stop-color: var(--svg-color--da9628, #DA9628);
}

.l4a0dtbst {
  stop-color: var(--svg-color--f6b939, #F6B939);
}

.l8hx5tsqw {
  stop-color: var(--svg-color--ca6f1f, #CA6F1F);
}

.lid3ide5q {
  stop-color: var(--svg-color--f5a129, #F5A129);
  stop-opacity: 0;
}

.lui_krbte {
  stop-color: var(--svg-color--e68f26, #E68F26);
}

.lwe9_nbqv {
  stop-color: var(--svg-color--dd8332, #DD8332);
}

.lzcvp_xbr {
  width: 1.258px;
  height: 0.293px;
  fill: var(--svg-color--c76452, #C76452);
  rx: 0.146px;
}

.m1xx5kfqh {
  fill: var(--svg-color--524d8c, #524D8C);
  d: path("m2.638 26.99l-.66 2.62a.25.25 0 0 0 .242.312h4.442c.101 0 .195-.06.22-.159c.126-.503-.197-.866-.764-1.157a87 87 0 0 1-1.695-.9l.376-.719a.05.05 0 0 0-.045-.073H2.735a.1.1 0 0 0-.097.076");
}

.mbn307bku {
  fill: var(--svg-color--efaa37, #EFAA37);
  d: path("M15.566 19.59c0-.212.172-.385.385-.385h1.386l.307.77h-1.693a.385.385 0 0 1-.385-.385");
}

.mbxf6yyls {
  stop-color: var(--svg-color--e8bb3d, #E8BB3D);
}

.mfaot4byg {
  stop-color: var(--svg-color--3f3943, #3F3943);
}

.mn215cb4x {
  d: path("m24.575 21.796l1.082-1.007l1.148-1.023l-3.133-1.907a79 79 0 0 1-1.399 1.66a.05.05 0 0 0 .003.069l2.23 2.206a.05.05 0 0 0 .069.002");
}

.ms4f1oj7g {
  r: 1.281px;
}

.n_ivmfbzb {
  fill: var(--svg-color--2797f6, #2797F6);
  d: path("m2.648 15.844l.664-.664l3.68 3.953l-1.211 1.015s.193 1.044.268 1.758a.05.05 0 0 1-.05.055H2.974a.05.05 0 0 1-.048-.035a63 63 0 0 1-.937-3.238c-.41-1.592.286-2.519.659-2.844");
}

.n9r91ylyy {
  stop-color: var(--svg-color--824d44, #824D44);
}

.naks3_bia {
  stop-color: var(--svg-color--e19839, #E19839);
  stop-opacity: 0;
}

.ni6dvehrg {
  fill-rule: evenodd;
  d: path("M13.093 19.785a.4.4 0 0 1 .549-.135c.405.245.86.47 1.376.647a.4.4 0 1 1-.26.757a8 8 0 0 1-1.53-.72a.4.4 0 0 1-.135-.549");
}

.nmxkbkb2v {
  stop-color: var(--svg-color--115ecc, #115ECC);
  stop-opacity: 0;
}

.nuhsp4_no {
  stop-color: var(--svg-color--5c405f, #5C405F);
}

.nzvqyeb9k {
  stop-color: var(--svg-color--4f415a, #4F415A);
}

.o-bam90bc {
  d: path("M16.871 8.154c.04-.846.315-1.254.444-1.373h3.943l.066 3.342c-.915 2.242-3.71 2.338-4.127 1.527c-.417-.81-.373-2.516-.326-3.496");
}

.o043sbvrw {
  stop-color: var(--svg-color--fd4, #FD4);
}

.o5wphbctr {
  stop-color: var(--svg-color--f9bf3b, #F9BF3B);
}

.om8lrbchi {
  stop-color: var(--svg-color--fc3, #FC3);
}

.omfadubst {
  stop-color: var(--svg-color--205ac3, #205AC3);
}

.on8sxx3yx {
  stop-color: var(--svg-color--5e4d44, #5E4D44);
  stop-opacity: 0;
}

.op-7n-bkz {
  stop-color: var(--svg-color--ec9f38, #EC9F38);
}

.oybn7vbqt {
  stop-color: var(--svg-color--6d6a94, #6D6A94);
}

.p50qpvb-l {
  fill-rule: evenodd;
  d: path("M26.853 13.826a.1.1 0 0 0-.09-.14l-3.874-.058l.035-2.34l4.25.06c1.654.024 2.654 1.726 1.92 3.234l-1.187 2.545l-2.061-1.02z");
}

.pfz0j3bxp {
  fill: var(--svg-color--ffd93e, #FFD93E);
  fill-rule: evenodd;
  d: path("M13.112 20.623a.45.45 0 0 1 .625-.121l.973.656a.45.45 0 1 1-.504.746l-.973-.656a.45.45 0 0 1-.12-.625");
}

.po83g90tv {
  fill: var(--svg-color--fabd38, #FABD38);
  d: path("m27.829 23.602l.57-1.727l-2.875-.39l-.203 1.43c-.131.918.125 1.663.375 2.202l1.219 2.172h1.867c-.245-.77-.844-2.77-.93-3.031s-.086-.48-.023-.656");
}

.pwkppuz1r {
  d: path("M14.428 8.154c-.04-.846-.315-1.254-.444-1.373h-3.943l-.066 3.342c.915 2.242 3.71 2.338 4.127 1.527c.418-.81.373-2.516.326-3.496");
}

.pxj138bcc {
  width: 3.464px;
  height: 4.574px;
  rx: 1.732px;
}

.pxzqtt8pl {
  stop-color: var(--svg-color--ef9f1e, #EF9F1E);
}

.q7fjm26wi {
  d: path("m2.648 15.844l.664-.664l3.68 3.953l-1.211 1.015s.193 1.044.268 1.758a.05.05 0 0 1-.05.055H2.974a.05.05 0 0 1-.048-.035a63 63 0 0 1-.937-3.238c-.41-1.592.286-2.519.659-2.844");
}

.q9ojxt_ur {
  stop-color: var(--svg-color--ffda40, #FFDA40);
  stop-opacity: 0;
}

.qi_39hbzn {
  rx: 0.068px;
  ry: 0.092px;
}

.qihskpbeg {
  stop-color: var(--svg-color--524e8d, #524E8D);
  stop-opacity: 0;
}

.qka3_sxpa {
  stop-color: var(--svg-color--2b7ec4, #2B7EC4);
}

.qkiupezfq {
  stop-color: var(--svg-color--cf8219, #CF8219);
}

.qtw47acth {
  fill-rule: evenodd;
  d: path("M23.565 12.67c.627.167 1 .81.832 1.438c-.25.937-.944 2.3-2.01 3.45c-1.076 1.157-2.671 2.248-4.616 2.413a1.175 1.175 0 0 1-1.27-1.071c-.055-.647.363-1.162 1.01-1.217c1.207-.141 2.262-.825 3.112-1.74c.86-.925 1.371-1.944 1.503-2.44c.168-.627.811-1 1.438-.833");
}

.r_8k9swvo {
  stop-color: var(--svg-color--ffda40, #FFDA40);
}

.r-6du_zhr {
  stop-color: var(--svg-color--227be5, #227BE5);
  stop-opacity: 0;
}

.r-govlg6m {
  fill: var(--svg-color--baa4c5, #BAA4C5);
  d: path("m27.016 27.69l-.376-.718a.05.05 0 0 1 .045-.074h2.019a.1.1 0 0 1 .097.076l.22.874z");
}

.r29-u8u1s {
  stop-color: var(--svg-color--e99f28, #E99F28);
}

.r294_3bpq {
  fill-rule: evenodd;
  d: path("M19.402 5.106a.25.25 0 0 0-.162.314l.95 2.969a.25.25 0 0 0 .476-.153l-.95-2.968a.25.25 0 0 0-.314-.162");
}

.r2t9jab3e {
  stop-color: var(--svg-color--f5a129, #F5A129);
}

.r6at_9bif {
  d: path("m28.8 26.974l.661 2.621a.25.25 0 0 1-.242.311h-4.442c-.101 0-.196-.06-.22-.158c-.126-.504.197-.866.764-1.158a87 87 0 0 0 1.695-.9l-.376-.718a.05.05 0 0 1 .044-.074h2.02a.1.1 0 0 1 .097.076");
}

.r98xt8hnz {
  width: 3.464px;
  height: 4.574px;
  x: 8.352px;
  y: 11.554px;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  rx: 1.732px;
}

.rixtyr4np {
  stop-color: var(--svg-color--ffc532, #FFC532);
  stop-opacity: 0;
}

.rknzqr02l {
  stop-color: var(--svg-color--695d73, #695D73);
  stop-opacity: 0;
}

.rlrqah7ok {
  stop-color: var(--svg-color--225fc7, #225FC7);
}

.rzbmz9bky {
  stop-color: var(--svg-color--ffd53d, #FFD53D);
}

.s-4wojr5g {
  fill-rule: evenodd;
  d: path("M13.328 20.317a.4.4 0 0 1 .548-.142l1.215.715a.4.4 0 0 1-.406.69l-1.215-.716a.4.4 0 0 1-.142-.547");
}

.s3twa090i {
  d: path("M21.073 12.118a2.697 2.697 0 0 1 3.82-.08l3.234 3.126l.046.034q.1.096.188.2l.43.43c.373.326 1.069 1.252.66 2.844a63 63 0 0 1-.938 3.239a.05.05 0 0 1-.02.026l-.027.008H25.44a.05.05 0 0 1-.05-.054c.075-.715.268-1.758.268-1.758l-.876-.735a2.7 2.7 0 0 1-.379-.309l-3.262-3.177a2.696 2.696 0 0 1-.068-3.794");
}

.sn1rqklko {
  d: path("m2.638 26.99l-.66 2.62a.25.25 0 0 0 .242.312h4.442c.101 0 .195-.06.22-.159c.126-.503-.197-.866-.764-1.157a87 87 0 0 1-1.695-.9l.376-.719a.05.05 0 0 0-.045-.073H2.735a.1.1 0 0 0-.097.076");
}

.so50u3yvk {
  stop-color: var(--svg-color--e48527, #E48527);
  stop-opacity: 0;
}

.spsau2bne {
  stop-color: var(--svg-color--f5a333, #F5A333);
  stop-opacity: 0;
}

.sqoomfbpf {
  stop-color: var(--svg-color--39a2f4, #39A2F4);
}

.stui2mbih {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0;
}

.suyap8bzv {
  stop-color: var(--svg-color--eba544, #EBA544);
}

.t_lqcx57b {
  d: path("m17.84 8.992l.003-.076c0-.196-.083-.354-.185-.354s-.185.159-.185.354l.004.076z");
}

.t57xntbrd {
  d: path("m8.892 23.46l-2.04-1.804L9.01 19.47a68 68 0 0 0 1.902 2.277c.67.77.758 1.77.738 2.262l-.101 2.898H9.524c-.067-.734-.21-2.308-.242-2.726a.95.95 0 0 0-.39-.72");
}

.tl4jonegg {
  d: path("M10.366 12.133a2.697 2.697 0 0 0-3.82-.079L3.311 15.18l-.046.034q-.1.096-.187.2l-.431.43c-.373.325-1.069 1.252-.66 2.844c.373 1.447.778 2.733.938 3.238q.006.017.02.027a.05.05 0 0 0 .028.008h3.025a.05.05 0 0 0 .05-.055c-.075-.714-.268-1.758-.268-1.758l.876-.734q.2-.135.379-.309l3.262-3.178a2.696 2.696 0 0 0 .068-3.794");
}

.touvs0bsg {
  stop-color: var(--svg-color--e8a22e, #E8A22E);
  stop-opacity: 0;
}

.u555vebcp {
  stop-color: var(--svg-color--ffb837, #FFB837);
}

.u8cibcbeo {
  stop-color: var(--svg-color--656262, #656262);
  stop-opacity: 0;
}

.uaz-z0b5y {
  fill: var(--svg-color--ffc936, #FFC936);
  d: path("M15.806 16.939a.384.384 0 1 0 0 .768h.518a.065.065 0 0 1 0 .129h1.157v-.13h.254l-.309-.308a1.57 1.57 0 0 0-1.109-.46z");
}

.ubyl24bdb {
  stop-color: var(--svg-color--565352, #565352);
}

.ucnu_4apo {
  fill-rule: evenodd;
  d: path("M11.898 5.106a.25.25 0 0 1 .162.314l-.95 2.969a.25.25 0 0 1-.476-.153l.95-2.968a.25.25 0 0 1 .314-.162");
}

.ugk6lpbwj {
  d: path("M15.566 19.59c0-.212.172-.385.385-.385h1.386l.307.77h-1.693a.385.385 0 0 1-.385-.385");
}

.us4sdgeme {
  stop-color: var(--svg-color--cf8219, #CF8219);
  stop-opacity: 0;
}

.utx5lkfyi {
  stop-color: var(--svg-color--bcabc4, #BCABC4);
}

.v1nkxhg1t {
  width: 1.258px;
  height: 0.293px;
  x: 12.669px;
  y: 7.922px;
  fill: var(--svg-color--c76452, #C76452);
  rx: 0.146px;
}

.v5o9libvx {
  d: path("m15.794 13.137l.535-.516c.124-.11.462-.332.824-.332h.989a.476.476 0 1 1 0 .953h-.866a.22.22 0 0 0-.203.129l-.032.07a.34.34 0 0 0-.002.287l.556-.038a.516.516 0 0 1 .071 1.029l-.67.046c-.738 1.026-1.884 2.055-3.901 2.229c-2.386.056-3.713-1.182-4.258-1.691a9 9 0 0 0-.212-.192a1.15 1.15 0 1 1 1.47-1.769c.023.02.077-.013.134-.046c.064-.038.131-.078.163-.05q.08.07.17.153c.497.455 1.236 1.132 2.533 1.132c.39 0 .884-.013 1.408-.336c.51-.314.937-.7 1.167-.95a.7.7 0 0 1 .124-.108");
}

.v9jt40b6n {
  d: path("m28.791 15.828l-.664-.664l-3.68 3.953l1.211 1.016s-.193 1.043-.268 1.758a.05.05 0 0 0 .05.054h3.025a.05.05 0 0 0 .048-.034c.16-.506.565-1.792.937-3.24c.41-1.591-.286-2.517-.659-2.843");
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.vgkwtybgv {
  d: path("m22.547 23.445l2.04-1.804l-2.157-2.188a69 69 0 0 1-1.902 2.278c-.67.77-.758 1.769-.738 2.261l.101 2.899h2.024c.067-.735.21-2.308.242-2.727a.95.95 0 0 1 .39-.719");
}

.vgnymzutm {
  stop-color: var(--svg-color--d58b3f, #D58B3F);
}

.vkuvqbbwu {
  stop-color: var(--svg-color--feb036, #FEB036);
  stop-opacity: 0;
}

.w0ww-qb1v {
  fill: var(--svg-color--ffd93e, #FFD93E);
  fill-rule: evenodd;
  d: path("M13.328 20.317a.4.4 0 0 1 .548-.142l1.215.715a.4.4 0 0 1-.406.69l-1.215-.716a.4.4 0 0 1-.142-.547");
}

.w20qtlznv {
  width: 3.464px;
  height: 4.574px;
  x: 8.352px;
  y: 11.554px;
  rx: 1.732px;
}

.w7fy1faaf {
  stop-color: var(--svg-color--245dc6, #245DC6);
}

.wcp6pybct {
  d: path("M14.665 9.173a1.06 1.06 0 0 1-.273-.483h-.19v1.189c.227.144.552.121.648-.095c.083-.186.021-.417-.185-.611");
}

.whveigbld {
  fill: var(--svg-color--baa4c5, #BAA4C5);
  d: path("m4.423 27.705l.376-.718a.05.05 0 0 0-.045-.073H2.735a.1.1 0 0 0-.097.076l-.22.874z");
}

.x-arwcb1i {
  d: path("M15.184 18.226a.39.39 0 0 1 .39-.39h2.031v.78h-2.031a.39.39 0 0 1-.39-.39");
}

.x69_iy2_t {
  d: path("M17.547 7.359c-.694 0-1.024-.392-1.057-.883c0-.694.53-.84.735-.863c.23-.025.322-.05.644-.276a.95.95 0 0 1 .961-.103c.157.074.504.111.751.037c.413-.124.735-.12 1.053.123c.22.17.383.17.648.17c.363 0 .671.162.903.338c.695.526.615 2.332.273 3.347c-.328.971-.821 1.085-1.234 1.048c-.497-.044-.623-.42-.698-.734a67 67 0 0 0-.28-1.098a1.13 1.13 0 0 1-.561-.71c-.106-.41-.52-.456-.801-.43c-.17.017-.644.034-1.337.034");
}

.x9w8qi-jn {
  stop-color: var(--svg-color--ffad30, #FFAD30);
}

.xhhozw94f {
  stop-color: var(--svg-color--ffbf38, #FFBF38);
  stop-opacity: 0;
}

.xn9ndqb6s {
  stop-color: var(--svg-color--b09db6, #B09DB6);
}

.y9oqcminv {
  stop-color: var(--svg-color--2283f1, #2283F1);
  stop-opacity: 0;
}

.ye033cbdf {
  stop-color: var(--svg-color--5c405f, #5C405F);
  stop-opacity: 0;
}

.yik88x48u {
  stop-color: var(--svg-color--245dc6, #245DC6);
  stop-opacity: 0;
}

.yxjq9v5jp {
  stop-color: var(--svg-color--ffb032, #FFB032);
  stop-opacity: 0;
}

.yyudvh1wz {
  d: path("M16.635 9.173a1.06 1.06 0 0 0 .273-.483h.19v1.189c-.228.144-.552.121-.648-.095c-.083-.186-.021-.417.185-.611");
}

.z_yn3vbua {
  stop-color: var(--svg-color--ffcc3d, #FFCC3D);
}

.zfu-fxb-u {
  stop-color: var(--svg-color--ffba33, #FFBA33);
}

.zhnyavbli {
  d: path("M15.222 18.853c0-.215.172-.39.384-.39h2v.78h-2a.387.387 0 0 1-.384-.39");
}

.zhwoohbuw {
  stop-color: var(--svg-color--ffc247, #FFC247);
}

.zlfnp5bxa {
  fill: var(--svg-color--2797f6, #2797F6);
  d: path("M24.893 12.038a2.696 2.696 0 0 0-3.752 3.874l3.262 3.177a2.71 2.71 0 1 0 3.77-3.891z");
}

.zt4dzgbzh {
  d: path("M13.254 8.993V8.99c0-.338.145-.613.324-.613s.324.275.324.613v.004z");
}

.zzjkwgj6o {
  d: path("m11.414 9.632l-.218-1.565a.79.79 0 0 0 .218 1.565");
}

</style>
