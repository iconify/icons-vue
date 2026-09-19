<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iSVNyCc)" transform="matrix(-1 0 0 1 12.877 6.95)" class="hxu4b4bgy"/><path fill="url(#iRmug6d)" transform="matrix(-1 0 0 1 12.877 6.95)" class="hxu4b4bgy"/><path class="p74b59bbc"/><path fill="url(#iZVnChe)" class="hhs22o5wo"/><path fill="url(#i7qPWNb)" class="hhs22o5wo"/><path fill="url(#i80S3Wd)" class="hhs22o5wo"/><g filter="url(#idCvDxb)"><path fill="url(#it70R9b)" class="z2dz7rv_f"/><path fill="url(#ipHdoKe)" class="z2dz7rv_f"/><path fill="url(#iGJU6gd)" class="z2dz7rv_f"/><path fill="url(#iIRZOue)" class="z2dz7rv_f"/></g><path class="wkp12s_bh"/><path fill="url(#iouOzfA)" class="mnej9qroj"/><path fill="url(#iJoWh8c)" class="mnej9qroj"/><path fill="url(#i4TE3qe)" class="mnej9qroj"/><path fill="url(#iNzR8ye)" transform="matrix(-1 0 0 1 17.076 15.115)" class="nm4erqbgo"/><path fill="url(#i4SA5Ie)" transform="matrix(-1 0 0 1 7.813 26.306)" class="citbmybyr"/><path fill="url(#ivd6tJb)" transform="matrix(-1 0 0 1 19.464 26.306)" class="citbmybyr"/><g filter="url(#iyMcBdd)"><path clip-rule="evenodd" class="wyvd7ua1n"/><path fill="url(#iubs7te)" clip-rule="evenodd" class="bw_5kybsc"/></g><g filter="url(#iMnqkic)"><path stroke="url(#iBHhjse)" class="lzhai0baa"/></g><circle fill="url(#iLK7nid)" transform="matrix(-1 0 0 1 17.582 15.906)" class="e8l0r5bvp"/><circle fill="url(#iRx1pQM)" transform="matrix(-1 0 0 1 17.582 15.906)" class="e8l0r5bvp"/><circle fill="url(#iKNNrbe)" transform="matrix(-1 0 0 1 17.582 15.906)" class="e8l0r5bvp"/><circle transform="matrix(-1 0 0 1 17.305 14.287)" class="b4att628q"/><circle fill="url(#igYiLkb)" transform="matrix(-1 0 0 1 17.305 14.287)" class="qhupv-mle"/><circle fill="url(#ir3vfRc)" transform="matrix(-1 0 0 1 17.305 14.287)" class="qhupv-mle"/><g filter="url(#isMhCEd)"><path fill="url(#iaC9d0b)" class="mh6_ypbam"/><path fill="url(#ihjn0bd)" class="mh6_ypbam"/><path fill="url(#ir05cHd)" class="mh6_ypbam"/></g><g filter="url(#iXFTcMe)"><path class="llvcdob8n"/><path fill="url(#iCkau5Z)" class="n9843ccmv"/></g><path class="qj5co5rje"/><path fill="url(#iiSC1PO)" class="sbet6hhzy"/><path fill="url(#iembUNv)" class="sbet6hhzy"/><path fill="url(#ivbilGU)" class="sbet6hhzy"/><path fill="url(#iaXV8Fb)" class="sbet6hhzy"/><path fill="url(#ieWY2He)" class="sbet6hhzy"/><rect fill="url(#iwPJDld)" transform="scale(-1 1)rotate(9.205 -45.247 -48.785)" class="z-j5q9xut"/><rect fill="url(#itmobse)" transform="scale(-1 1)rotate(9.205 -45.247 -48.785)" class="z-j5q9xut"/><path fill="url(#iDuZkMe)" transform="matrix(-1 0 0 1 15.818 20.74)" class="lgp2azslk"/><path fill="url(#irXs2md)" transform="matrix(-1 0 0 1 15.818 20.74)" class="lgp2azslk"/><g filter="url(#iJLNrMb)"><path class="d2fye0bkn"/><path fill="url(#iANGQcb)" class="nuhmirbhy"/><path fill="url(#izsB74d)" class="nuhmirbhy"/></g><path fill="url(#i5BuEXm)" class="nuhmirbhy"/><g filter="url(#ikonTvW)"><rect transform="matrix(-1 0 0 1 19.271 18.089)" class="n26ducxcj"/><rect fill="url(#iqljcRc)" transform="matrix(-1 0 0 1 19.271 18.089)" class="gwis82dft"/><rect fill="url(#iw4jA1t)" transform="matrix(-1 0 0 1 19.271 18.089)" class="gwis82dft"/></g><rect fill="url(#iiahDEe)" transform="matrix(-1 0 0 1 19.271 18.089)" class="gwis82dft"/><g filter="url(#ieEEaQe)"><path fill="url(#iGWY1fq)" class="nlhf8jgze"/></g><path fill="url(#ikqBXHe)" class="nlhf8jgze"/><circle transform="matrix(-1 0 0 1 9.968 15.209)" class="m_-nxz25m"/><g filter="url(#i0bvYZc)"><circle transform="matrix(-1 0 0 1 20.725 27.013)" class="t84n9rbqs"/></g><circle fill="url(#i0VqqEr)" transform="matrix(-1 0 0 1 20.725 27.013)" class="pyf4h2zzf"/><circle fill="url(#iPRFEMc)" transform="matrix(-1 0 0 1 20.122 27.616)" class="bwibo9t2c"/><circle fill="url(#iPRFEMc)" transform="matrix(-1 0 0 1 8.466 27.616)" class="bwibo9t2c"/><g filter="url(#iCRn2qc)"><path clip-rule="evenodd" class="p6m2bvbro"/></g><path fill="url(#iCgsBrC)" clip-rule="evenodd" class="i_b2cj3we"/><g filter="url(#id9kE0d)"><circle transform="matrix(-1 0 0 1 19.605 28.133)" class="p2wklo0_t"/></g><g filter="url(#ilP3ijD)"><circle transform="matrix(-1 0 0 1 7.948 28.133)" class="p2wklo0_t"/></g><g filter="url(#ioutHYd)"><path fill="url(#iG9KDtC)" class="wj-_1oh1j"/></g><path fill="url(#ix5rcSb)" class="wj-_1oh1j"/><path fill="url(#imcQqKd)" class="wj-_1oh1j"/><circle fill="url(#iAfK1ib)" transform="matrix(-1 0 0 1 14.912 25.962)" class="o-elqripn"/><g filter="url(#ih9o4Yd)"><path clip-rule="evenodd" class="eutzrtbnw"/></g><g filter="url(#ixt7oPN)"><path stroke="url(#irD8uyz)" clip-rule="evenodd" class="i4u-5824r"/></g><g filter="url(#iV5a8sb)"><path stroke="url(#iOtxhzc)" clip-rule="evenodd" class="cb3my7ddm"/></g><g filter="url(#iaxk8IH)"><path class="cn0rvobaf"/></g><g filter="url(#i7TnMnd)"><path stroke="url(#iWsGP4b)" clip-rule="evenodd" class="xplz5bcrg"/></g><g filter="url(#iZgX7Vc)"><circle transform="matrix(-1 0 0 1 14.037 26.837)" class="e2kdnzhzw"/></g><g filter="url(#itAlPxV)"><path class="wxyfq_b9d"/></g><path fill="url(#iQjrHTc)" class="d51o8ek-s"/><g filter="url(#i1lBqiZ)"><path class="um0wv7bwm"/></g><g filter="url(#iG5WPJe)"><path class="ry2t0ob6u"/></g><path fill="url(#ijcgMle)" class="p13ql8bhx"/><g filter="url(#idM3yfc)"><path fill="url(#icWA75c)" class="eeeq85f7u"/><path fill="url(#irpWWBa)" class="eeeq85f7u"/></g><g filter="url(#iZbfwFt)"><path fill="url(#iK1Uyxc)" class="gs_3vbc-h"/></g><path fill="url(#iiPoz7c)" class="gs_3vbc-h"/><path fill="url(#iR1PSKd)" class="gs_3vbc-h"/><path fill="url(#ioVqF3c)" class="n_csnibjz"/><path clip-rule="evenodd" class="md_i0_blm"/><path class="f3ufgjgnw"/><path fill="url(#ixDAE0c)" class="sdzcd6bgx"/><path fill="url(#iBPpgwd)" class="aawlcz1lp"/><ellipse fill="url(#iicaIud)" transform="scale(-1 1)rotate(30.509 -16.05 -22.785)" class="iap3byr6y"/><g filter="url(#iqixjYc)"><path class="vhbvss0_z"/></g><path class="s_bd7ebgs"/><path fill="url(#iRWgNbc)" class="otvqpncsi"/><path fill="url(#i9ELlVd)" class="otvqpncsi"/><path fill="url(#igVHdmd)" class="otvqpncsi"/><path fill="url(#id2CJAb)" class="otvqpncsi"/><path fill="url(#iArwo1M)" class="otvqpncsi"/><g filter="url(#iy7cwCu)"><path fill="url(#iJGDNhe)" class="k8xj131jx"/></g><path class="y9tlk8oux"/><path fill="url(#iGSFPee)" class="cb_w9xm8y"/><path fill="url(#iEtQsqe)" class="cb_w9xm8y"/><path fill="url(#iB2Nswx)" class="cb_w9xm8y"/><defs><radialGradient id="iZVnChe" cx="0" cy="0" r="1" gradientTransform="matrix(-4.625 4.75001 -5.30938 -5.16964 15.915 9.474)" gradientUnits="userSpaceOnUse"><stop offset=".367" class="l-ch5ci-p"/><stop offset="1" class="z-2ie6sne"/></radialGradient><radialGradient id="i80S3Wd" cx="0" cy="0" r="1" gradientTransform="matrix(-.82524 -4.84513 7.08082 -1.20602 12.654 13.285)" gradientUnits="userSpaceOnUse"><stop offset=".918" class="zqylsrrgt"/><stop offset="1" class="j0xqyhb3r"/></radialGradient><radialGradient id="ipHdoKe" cx="0" cy="0" r="1" gradientTransform="matrix(2.125 -1 2.95173 6.27243 19.852 21.787)" gradientUnits="userSpaceOnUse"><stop class="jzl720bvd"/><stop offset="1" class="zdh48sb9s"/></radialGradient><radialGradient id="iGJU6gd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.40625 6.4375 0 13.352 18.068)" gradientUnits="userSpaceOnUse"><stop class="d9q4mwzxt"/><stop offset="1" class="kegmapbvr"/></radialGradient><radialGradient id="iIRZOue" cx="0" cy="0" r="1" gradientTransform="matrix(-1.53125 .31251 -1.31893 -6.46254 22.634 19.662)" gradientUnits="userSpaceOnUse"><stop class="d0phtb81o"/><stop class="d0phtb81o"/><stop offset="1" class="hwvatcc-y"/></radialGradient><radialGradient id="iouOzfA" cx="0" cy="0" r="1" gradientTransform="matrix(.11941 -1.8243 6.0381 .39524 23.634 24.787)" gradientUnits="userSpaceOnUse"><stop offset=".584" class="ie8_agh2b"/><stop offset="1" class="gzc_qccoq"/></radialGradient><radialGradient id="i4TE3qe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.64063 -.01563 .00576 -.60488 25.93 23.709)" gradientUnits="userSpaceOnUse"><stop class="u9mcm6llv"/><stop offset="1" class="b-3vnvcpj"/></radialGradient><radialGradient id="iubs7te" cx="0" cy="0" r="1" gradientTransform="rotate(179.119 13.13 12.073)scale(1.01575 2.26584)" gradientUnits="userSpaceOnUse"><stop class="ihz8r9bpq"/><stop offset="1" class="cabiwub4i"/></radialGradient><radialGradient id="iLK7nid" cx="0" cy="0" r="1" gradientTransform="matrix(-.80087 -.53995 .5353 -.79397 1.17 .793)" gradientUnits="userSpaceOnUse"><stop class="id6hb3b7i"/><stop offset="1" class="nbyzmw_ck"/></radialGradient><radialGradient id="iRx1pQM" cx="0" cy="0" r="1" gradientTransform="matrix(.27344 -.33594 .30415 .24757 1.076 .498)" gradientUnits="userSpaceOnUse"><stop offset=".133" class="z1-difb5b"/><stop offset="1" class="yxnjz7r7g"/></radialGradient><radialGradient id="iKNNrbe" cx="0" cy="0" r="1" gradientTransform="matrix(.18962 -.81468 .57531 .1339 0 .944)" gradientUnits="userSpaceOnUse"><stop class="mcd03_b4y"/><stop offset="1" class="e14bc-vgp"/></radialGradient><radialGradient id="igYiLkb" cx="0" cy="0" r="1" gradientTransform="rotate(65.376 -.034 .67)scale(.41251)" gradientUnits="userSpaceOnUse"><stop offset=".179" class="ipohnfkvg"/><stop offset="1" class="aur13kbnc"/></radialGradient><radialGradient id="ir3vfRc" cx="0" cy="0" r="1" gradientTransform="matrix(.41406 -.125 .14254 .47215 .05 .79)" gradientUnits="userSpaceOnUse"><stop class="clzavdftr"/><stop offset="1" class="w07b1tb5i"/></radialGradient><radialGradient id="ihjn0bd" cx="0" cy="0" r="1" gradientTransform="rotate(-158.199 13.009 10.947)scale(.75729 .97088)" gradientUnits="userSpaceOnUse"><stop class="b9iguid0k"/><stop offset="1" class="rfxr5lvvz"/></radialGradient><radialGradient id="itmobse" cx="0" cy="0" r="1" gradientTransform="rotate(-90.544 1.095 .493)scale(1.19329 .67738)" gradientUnits="userSpaceOnUse"><stop class="bcaxkqjfb"/><stop offset="1" class="kh4so6bgt"/></radialGradient><radialGradient id="iDuZkMe" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.16406 -2.98016 0 2.418 .11)" gradientUnits="userSpaceOnUse"><stop offset=".161" class="yu1mih4mu"/><stop offset="1" class="eu5aevb0y"/></radialGradient><radialGradient id="irXs2md" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.36328 -3.72499 0 2.418 .637)" gradientUnits="userSpaceOnUse"><stop offset=".358" class="cvn34-xwu"/><stop offset=".771" class="i8rkxoa5u"/></radialGradient><radialGradient id="izsB74d" cx="0" cy="0" r="1" gradientTransform="matrix(1.10465 .77326 -.66363 .94804 7.216 9.063)" gradientUnits="userSpaceOnUse"><stop class="t_w7gbbck"/><stop offset="1" class="pbwt4gb4m"/></radialGradient><radialGradient id="i5BuEXm" cx="0" cy="0" r="1" gradientTransform="matrix(.0138 .77326 -2.388 .04264 9.853 16.312)" gradientUnits="userSpaceOnUse"><stop offset=".208" class="seor_02fd"/><stop offset="1" class="cfhwg-9zy"/></radialGradient><radialGradient id="ikqBXHe" cx="0" cy="0" r="1" gradientTransform="rotate(-179.274 7.515 7.74)scale(.64849 1.33813)" gradientUnits="userSpaceOnUse"><stop offset=".032" class="etx6bbf-f"/><stop offset="1" class="xbtn5acgm"/></radialGradient><radialGradient id="i0VqqEr" cx="0" cy="0" r="1" gradientTransform="matrix(1.71874 -1.8125 1.7735 1.68175 .89 2.258)" gradientUnits="userSpaceOnUse"><stop offset=".556" class="bu0v-9rgl"/><stop offset="1" class="bzyp_ibbo"/></radialGradient><radialGradient id="iPRFEMc" cx="0" cy="0" r="1" gradientTransform="rotate(-49.87 1.676 -.079)scale(1.46152 1.87048)" gradientUnits="userSpaceOnUse"><stop offset=".233" class="b3dj2bied"/><stop offset="1" class="ma5b9zegf"/></radialGradient><radialGradient id="iCgsBrC" cx="0" cy="0" r="1" gradientTransform="rotate(-46.762 37.408 6.707)scale(2.87398 2.81213)" gradientUnits="userSpaceOnUse"><stop offset=".556" class="bu0v-9rgl"/><stop offset="1" class="bzyp_ibbo"/></radialGradient><radialGradient id="imcQqKd" cx="0" cy="0" r="1" gradientTransform="matrix(.625 3.92187 -.8118 .12937 9.256 22.818)" gradientUnits="userSpaceOnUse"><stop class="th1brvxrz"/><stop offset="1" class="ux0of3-jj"/></radialGradient><radialGradient id="iAfK1ib" cx="0" cy="0" r="1" gradientTransform="matrix(1.59375 -1.89062 2.41965 2.03971 1.11 2.121)" gradientUnits="userSpaceOnUse"><stop offset=".233" class="b3dj2bied"/><stop offset="1" class="ma5b9zegf"/></radialGradient><radialGradient id="ijcgMle" cx="0" cy="0" r="1" gradientTransform="rotate(111.387 5.437 7.818)scale(.62776 .79947)" gradientUnits="userSpaceOnUse"><stop offset=".332" class="fvok_qxen"/><stop offset="1" class="suyap8bzv"/></radialGradient><radialGradient id="irpWWBa" cx="0" cy="0" r="1" gradientTransform="matrix(1.1002 -.1957 .23859 1.34137 11.413 5.727)" gradientUnits="userSpaceOnUse"><stop offset=".156" class="d7kch3t0q"/><stop offset="1" class="admd7db0k"/></radialGradient><radialGradient id="iK1Uyxc" cx="0" cy="0" r="1" gradientTransform="matrix(3.44459 2.53722 -2.87705 3.90594 9.467 3.31)" gradientUnits="userSpaceOnUse"><stop offset=".363" class="jve2rcqoj"/><stop offset="1" class="kpbiulbbs"/></radialGradient><radialGradient id="iiPoz7c" cx="0" cy="0" r="1" gradientTransform="rotate(-90.766 8.722 -1.606)scale(1.20632 2.55788)" gradientUnits="userSpaceOnUse"><stop offset=".064" class="jfv70ccah"/><stop offset="1" class="b30rr0b3q"/></radialGradient><radialGradient id="iR1PSKd" cx="0" cy="0" r="1" gradientTransform="matrix(1.28125 -.23437 .49816 2.72328 9.016 5.019)" gradientUnits="userSpaceOnUse"><stop offset=".292" class="id4s2xn6z"/><stop offset="1" class="ubkfx58us"/></radialGradient><radialGradient id="ioVqF3c" cx="0" cy="0" r="1" gradientTransform="matrix(.50418 .81946 -1.33157 .81925 11.248 5.425)" gradientUnits="userSpaceOnUse"><stop offset=".04" class="bervkqbmz"/><stop offset="1" class="c479w-bpn"/></radialGradient><radialGradient id="ixDAE0c" cx="0" cy="0" r="1" gradientTransform="matrix(-.25047 .02588 -.05028 -.48664 13.716 5.405)" gradientUnits="userSpaceOnUse"><stop offset=".895" class="l0aricxam"/><stop offset="1" class="n9r91ylyy"/></radialGradient><radialGradient id="iBPpgwd" cx="0" cy="0" r="1" gradientTransform="rotate(174.111 6.797 3.062)scale(.23022 .49823)" gradientUnits="userSpaceOnUse"><stop class="gv3iwdbvq"/><stop offset=".813" class="ubyl24bdb"/></radialGradient><radialGradient id="iRWgNbc" cx="0" cy="0" r="1" gradientTransform="rotate(-100.964 7.166 -.924)scale(3.23851 1.02255)" gradientUnits="userSpaceOnUse"><stop class="fndizab4b"/><stop offset="1" class="hw8l16bxs"/></radialGradient><radialGradient id="id2CJAb" cx="0" cy="0" r="1" gradientTransform="matrix(1.15625 .875 -1.0205 1.3485 6.302 3.6)" gradientUnits="userSpaceOnUse"><stop class="v4yb5cu8i"/><stop offset="1" class="ewip82vxi"/></radialGradient><radialGradient id="iArwo1M" cx="0" cy="0" r="1" gradientTransform="rotate(97.765 2.893 4.939)scale(1.04079 3.79637)" gradientUnits="userSpaceOnUse"><stop offset=".167" class="i00c46bgu"/><stop offset="1" class="gb6cd3sju"/></radialGradient><radialGradient id="iGSFPee" cx="0" cy="0" r="1" gradientTransform="rotate(87.138 .34 10.484)scale(1.94294 1.12379)" gradientUnits="userSpaceOnUse"><stop class="axeyyr5nz"/><stop offset="1" class="wq290abaa"/></radialGradient><radialGradient id="iEtQsqe" cx="0" cy="0" r="1" gradientTransform="rotate(174.431 5.88 5.944)scale(1.99972 10.6844)" gradientUnits="userSpaceOnUse"><stop offset=".516" class="rnfgp6bsq"/><stop offset="1" class="sjqhriwca"/></radialGradient><linearGradient id="iSVNyCc" x1=".184" x2="1.501" y1="1.353" y2="1.236" gradientUnits="userSpaceOnUse"><stop class="uhndsibic"/><stop offset="1" class="mas-0fbya"/></linearGradient><linearGradient id="iRmug6d" x1="2.383" x2="1.227" y1="1.697" y2="1.759" gradientUnits="userSpaceOnUse"><stop class="gg7le5bub"/><stop offset="1" class="rtjr-xb4t"/></linearGradient><linearGradient id="i7qPWNb" x1="10.037" x2="14.446" y1="16.662" y2="12.1" gradientUnits="userSpaceOnUse"><stop class="hjg9lybhz"/><stop offset="1" class="arwl47bdv"/></linearGradient><linearGradient id="it70R9b" x1="14.04" x2="22.165" y1="16.818" y2="24.131" gradientUnits="userSpaceOnUse"><stop class="scqcqwblc"/><stop offset="1" class="j5-6p70xh"/></linearGradient><linearGradient id="iJoWh8c" x1="21.688" x2="22.868" y1="25.295" y2="24.678" gradientUnits="userSpaceOnUse"><stop class="wjw662jrg"/><stop offset="1" class="xkzs54_ul"/></linearGradient><linearGradient id="iNzR8ye" x1="-.102" x2=".498" y1=".507" y2=".507" gradientUnits="userSpaceOnUse"><stop class="p8hc-w2ji"/><stop offset=".573" class="c76owwbvh"/></linearGradient><linearGradient id="i4SA5Ie" x1=".471" x2="0" y1=".684" y2=".34" gradientUnits="userSpaceOnUse"><stop offset=".323" class="lzxtmdbfr"/><stop offset="1" class="ajt-21bdu"/></linearGradient><linearGradient id="ivd6tJb" x1=".052" x2=".513" y1=".676" y2=".426" gradientUnits="userSpaceOnUse"><stop offset=".385" class="lzxtmdbfr"/><stop offset="1" class="ajt-21bdu"/></linearGradient><linearGradient id="iBHhjse" x1="25.748" x2="20.396" y1="24.162" y2="26.435" gradientUnits="userSpaceOnUse"><stop class="bq9mpqbzy"/><stop offset="1" class="ka6kobc6f"/></linearGradient><linearGradient id="iaC9d0b" x1="20.506" x2="17.849" y1="26.568" y2="24.662" gradientUnits="userSpaceOnUse"><stop class="f6z4yi_ag"/><stop offset="1" class="cu9n-vbgf"/></linearGradient><linearGradient id="ir05cHd" x1="19.209" x2="19.037" y1="24.193" y2="24.662" gradientUnits="userSpaceOnUse"><stop class="ybejupycn"/><stop offset="1" class="o7v7nujms"/></linearGradient><linearGradient id="iCkau5Z" x1="7.224" x2="7.724" y1="24.162" y2="25.062" gradientUnits="userSpaceOnUse"><stop class="hlkhhwb3q"/><stop offset="1" class="b37qgpujw"/></linearGradient><linearGradient id="iiSC1PO" x1="16.781" x2="16.781" y1="16.77" y2="17.429" gradientUnits="userSpaceOnUse"><stop offset=".077" class="y05dlfbsr"/><stop offset="1" class="uevlegbhj"/></linearGradient><linearGradient id="iembUNv" x1="18.055" x2="16.976" y1="17.882" y2="17.882" gradientUnits="userSpaceOnUse"><stop offset=".326" class="mykl6fbtk"/><stop offset="1" class="uevlegbhj"/></linearGradient><linearGradient id="ivbilGU" x1="15.507" x2="16.325" y1="18.089" y2="18.089" gradientUnits="userSpaceOnUse"><stop class="jsdt5e8xl"/><stop offset="1" class="erpm-ebho"/></linearGradient><linearGradient id="iaXV8Fb" x1="15.507" x2="15.794" y1="18.089" y2="18.089" gradientUnits="userSpaceOnUse"><stop class="gxhbeh9zc"/><stop offset="1" class="t07ov5bcy"/></linearGradient><linearGradient id="ieWY2He" x1="18.055" x2="17.764" y1="17.831" y2="17.831" gradientUnits="userSpaceOnUse"><stop class="xs80ogben"/><stop offset="1" class="snka5sm3m"/></linearGradient><linearGradient id="iwPJDld" x1=".298" x2=".287" y1=".432" y2="1.637" gradientUnits="userSpaceOnUse"><stop class="ronnvab4v"/><stop offset="1" class="dt2-hrbth"/></linearGradient><linearGradient id="iANGQcb" x1="8.072" x2="9.784" y1="17.32" y2="17.155" gradientUnits="userSpaceOnUse"><stop offset=".357" class="ejmms-frd"/><stop offset="1" class="bd5h7cqqn"/></linearGradient><linearGradient id="iqljcRc" x1="5.922" x2="5.922" y1=".23" y2="1.23" gradientUnits="userSpaceOnUse"><stop offset=".219" class="jqu95-b8t"/><stop offset="1" class="vt606lu7d"/></linearGradient><linearGradient id="iw4jA1t" x1="11.844" x2="10.547" y1="1.42" y2="1.42" gradientUnits="userSpaceOnUse"><stop class="e9_lu_tkl"/><stop offset="1" class="ms0rob30e"/></linearGradient><linearGradient id="iiahDEe" x1="0" x2=".516" y1="1.55" y2="1.55" gradientUnits="userSpaceOnUse"><stop offset=".255" class="aafld1b5m"/><stop offset="1" class="t9qy5zbtq"/></linearGradient><linearGradient id="iGWY1fq" x1="11.435" x2="11.435" y1="15.008" y2="16.476" gradientUnits="userSpaceOnUse"><stop offset=".116" class="k8klmcqbt"/><stop offset="1" class="t8rqipb-o"/></linearGradient><linearGradient id="iG9KDtC" x1="13.412" x2="13.412" y1="21.896" y2="27.693" gradientUnits="userSpaceOnUse"><stop class="ebki_vbdj"/><stop offset=".752" class="w_fjow9gn"/></linearGradient><linearGradient id="ix5rcSb" x1="17.756" x2="16.756" y1="25.537" y2="25.443" gradientUnits="userSpaceOnUse"><stop class="golah4bmm"/><stop offset="1" class="nhtvs4bus"/></linearGradient><linearGradient id="irD8uyz" x1="11.795" x2="14.977" y1="25.702" y2="28.838" gradientUnits="userSpaceOnUse"><stop class="bqaby2bzq"/><stop offset=".37" class="hxfvufi0i"/><stop offset=".778" class="hxfvufi0i"/><stop offset="1" class="bqaby2bzq"/></linearGradient><linearGradient id="iOtxhzc" x1="6.649" x2="8.447" y1="27.512" y2="29.284" gradientUnits="userSpaceOnUse"><stop class="bqaby2bzq"/><stop offset=".37" class="hxfvufi0i"/><stop offset=".778" class="hxfvufi0i"/><stop offset="1" class="bqaby2bzq"/></linearGradient><linearGradient id="iWsGP4b" x1="20.499" x2="19.015" y1="28.896" y2="27.459" gradientUnits="userSpaceOnUse"><stop class="bqaby2bzq"/><stop offset="1" class="hxfvufi0i"/></linearGradient><linearGradient id="iQjrHTc" x1="17.446" x2="16.102" y1="13.683" y2="14.037" gradientUnits="userSpaceOnUse"><stop class="x37zrlbcp"/><stop offset="1" class="u2e3rxbtp"/></linearGradient><linearGradient id="icWA75c" x1="11.769" x2="14.407" y1="6.377" y2="6.264" gradientUnits="userSpaceOnUse"><stop class="sh1u5ab0i"/><stop offset="1" class="yru3_4bbx"/></linearGradient><linearGradient id="iicaIud" x1="-.006" x2=".164" y1=".045" y2=".101" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="stui2mbih"/></linearGradient><linearGradient id="i9ELlVd" x1="6.427" x2="7.63" y1="6.006" y2="5.771" gradientUnits="userSpaceOnUse"><stop class="sputfhdoz"/><stop offset="1" class="x91xhsboa"/></linearGradient><linearGradient id="igVHdmd" x1="8.193" x2="8.005" y1="7.093" y2="5.818" gradientUnits="userSpaceOnUse"><stop class="zeqefbvfd"/><stop offset="1" class="aetcf802l"/></linearGradient><linearGradient id="iJGDNhe" x1="21.977" x2="17.227" y1="23.037" y2="14.631" gradientUnits="userSpaceOnUse"><stop offset=".047" class="x9-imyafb"/><stop offset="1" class="uu4nvia_s"/></linearGradient><linearGradient id="iB2Nswx" x1="12.67" x2="12.037" y1="11.968" y2="11.968" gradientUnits="userSpaceOnUse"><stop class="o5h0oebxj"/><stop offset="1" class="ts_kmdhif"/></linearGradient><filter id="idCvDxb" width="15.582" height="10.819" x="10.455" y="14.788" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.309804 0 0 0 0 0.223529 0 0 0 0 0.32549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_4612"/></filter><filter id="iyMcBdd" width="6.441" height="2.956" x="20.051" y="23.488" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.203922 0 0 0 0 0.133333 0 0 0 0 0.286275 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_4612"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".15"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.14902 0 0 0 0 0.14902 0 0 0 0 0.196078 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_2_4612" result="effect2_innerShadow_2_4612"/></filter><filter id="iMnqkic" width="5.567" height="2.356" x="20.5" y="23.788" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_4612" stdDeviation=".075"/></filter><filter id="isMhCEd" width="4.441" height="3.418" x="16.701" y="23.277" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.74902 0 0 0 0 0.109804 0 0 0 0 0.27451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_4612"/></filter><filter id="iXFTcMe" width="4.535" height="3.468" x="5.658" y="23.227" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.764706 0 0 0 0 0.145098 0 0 0 0 0.301961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_4612"/></filter><filter id="iJLNrMb" width="4.718" height="10.273" x="7.076" y="8.115" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy=".3"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.145098 0 0 0 0 0.223529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_4612"/></filter><filter id="ikonTvW" width="11.844" height="3.289" x="7.427" y="17.839" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.294118 0 0 0 0 0.133333 0 0 0 0 0.356863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_4612"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.278431 0 0 0 0 0.184314 0 0 0 0 0.317647 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_2_4612" result="effect2_innerShadow_2_4612"/></filter><filter id="ieEEaQe" width="7.15" height="1.822" x="7.935" y="14.654" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.231373 0 0 0 0 0.137255 0 0 0 0 0.372549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_4612"/></filter><filter id="i0bvYZc" width="3.042" height="3.242" x="17.732" y="26.813" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.466667 0 0 0 0 0.337255 0 0 0 0 0.588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_4612"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.537255 0 0 0 0 0.494118 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_2_4612" result="effect2_innerShadow_2_4612"/></filter><filter id="iCRn2qc" width="3.042" height="3.242" x="6.076" y="26.813" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.466667 0 0 0 0 0.337255 0 0 0 0 0.588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_4612"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.537255 0 0 0 0 0.494118 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_2_4612" result="effect2_innerShadow_2_4612"/></filter><filter id="id9kE0d" width=".953" height=".953" x="18.752" y="28.033" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.239216 0 0 0 0 0.203922 0 0 0 0 0.294118 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_4612"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.258824 0 0 0 0 0.247059 0 0 0 0 0.298039 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_2_4612" result="effect2_innerShadow_2_4612"/></filter><filter id="ilP3ijD" width=".953" height=".953" x="7.095" y="28.033" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.239216 0 0 0 0 0.203922 0 0 0 0 0.294118 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_4612"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.258824 0 0 0 0 0.247059 0 0 0 0 0.298039 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_2_4612" result="effect2_innerShadow_2_4612"/></filter><filter id="ioutHYd" width="9.072" height="5.925" x="8.876" y="21.896" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".3"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.666667 0 0 0 0 0.0392157 0 0 0 0 0.180392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_4612"/></filter><filter id="ih9o4Yd" width="5.213" height="5.612" x="10.869" y="24.543" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.4"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.466667 0 0 0 0 0.337255 0 0 0 0 0.588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_4612"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".15"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.537255 0 0 0 0 0.494118 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_2_4612" result="effect2_innerShadow_2_4612"/></filter><filter id="ixt7oPN" width="4.858" height="4.858" x="10.871" y="24.945" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_4612" stdDeviation=".125"/></filter><filter id="iV5a8sb" width="2.743" height="2.742" x="6.129" y="27.086" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_4612" stdDeviation=".075"/></filter><filter id="iaxk8IH" width="4.351" height="5.782" x="9.525" y="8.216" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_4612" stdDeviation=".5"/></filter><filter id="i7TnMnd" width="2.743" height="2.742" x="17.857" y="27.086" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_4612" stdDeviation=".075"/></filter><filter id="iZgX7Vc" width="1.474" height="1.474" x="12.663" y="26.737" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.239216 0 0 0 0 0.203922 0 0 0 0 0.294118 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_4612"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.258824 0 0 0 0 0.247059 0 0 0 0 0.298039 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_2_4612" result="effect2_innerShadow_2_4612"/></filter><filter id="itAlPxV" width="7.234" height="2.726" x="10.589" y="12.22" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.67451 0 0 0 0 0.423529 0 0 0 0 0.0901961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_4612"/></filter><filter id="i1lBqiZ" width="1.984" height="1.537" x="16.401" y="13.488" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.898039 0 0 0 0 0.647059 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_4612"/></filter><filter id="iG5WPJe" width="1.948" height="1.321" x="15.95" y="13.919" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.788235 0 0 0 0 0.541176 0 0 0 0 0.133333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_4612"/></filter><filter id="idM3yfc" width="4.309" height="4.933" x="10.102" y="3.438" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.682353 0 0 0 0 0.509804 0 0 0 0 0.0862745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_4612"/></filter><filter id="iZbfwFt" width="5.82" height="5.34" x="8.814" y="1.865" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.835294 0 0 0 0 0.211765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_4612"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.3"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.976471 0 0 0 0 0.592157 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_2_4612" result="effect2_innerShadow_2_4612"/></filter><filter id="iqixjYc" width="1.051" height=".694" x="12.864" y="4.154" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.619608 0 0 0 0 0.2 0 0 0 0 0.0862745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_4612"/></filter><filter id="iy7cwCu" width="5.063" height="8.469" x="17.759" y="15.412" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_4612" stdDeviation=".25"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-in-motorized-wheelchair-facing-right" /></template>
<style>
.aafld1b5m {
  stop-color: var(--svg-color--64576e, #64576E);
}

.aawlcz1lp {
  d: path("m13.597 5.437l-.011-.065c-.018-.17.04-.316.13-.325c.088-.009.175.121.192.291l.003.067z");
}

.admd7db0k {
  stop-color: var(--svg-color--ffab1d, #FFAB1D);
  stop-opacity: 0;
}

.aetcf802l {
  stop-color: var(--svg-color--492f60, #492F60);
  stop-opacity: 0;
}

.ajt-21bdu {
  stop-color: var(--svg-color--3a183a, #3A183A);
}

.arwl47bdv {
  stop-color: var(--svg-color--142c6c, #142C6C);
  stop-opacity: 0;
}

.aur13kbnc {
  stop-color: var(--svg-color--5a4a71, #5A4A71);
  stop-opacity: 0;
}

.axeyyr5nz {
  stop-color: var(--svg-color--44a1e7, #44A1E7);
}

.b-3vnvcpj {
  stop-color: var(--svg-color--565476, #565476);
  stop-opacity: 0;
}

.b30rr0b3q {
  stop-color: var(--svg-color--ef9926, #EF9926);
  stop-opacity: 0;
}

.b37qgpujw {
  stop-color: var(--svg-color--f24147, #F24147);
  stop-opacity: 0;
}

.b3dj2bied {
  stop-color: var(--svg-color--c7b9d7, #C7B9D7);
}

.b4att628q {
  cx: 0.518px;
  cy: 0.518px;
  r: 0.518px;
  fill: var(--svg-color--4a2a60, #4A2A60);
}

.b9iguid0k {
  stop-color: var(--svg-color--cc3437, #CC3437);
}

.bcaxkqjfb {
  stop-color: var(--svg-color--404047, #404047);
}

.bd5h7cqqn {
  stop-color: var(--svg-color--5a4a6a, #5A4A6A);
  stop-opacity: 0;
}

.bervkqbmz {
  stop-color: var(--svg-color--ffd040, #FFD040);
}

.bq9mpqbzy {
  stop-color: var(--svg-color--474652, #474652);
}

.bqaby2bzq {
  stop-color: var(--svg-color--a09aa7, #A09AA7);
}

.bu0v-9rgl {
  stop-color: var(--svg-color--776287, #776287);
  stop-opacity: 0;
}

.bw_5kybsc {
  fill-rule: evenodd;
  d: path("M26.303 23.848a.375.375 0 0 0-.502-.17l-3.788 1.864l-.01.003h-1.427a.375.375 0 0 0 0 .75h1.426a.8.8 0 0 0 .343-.08l3.787-1.865a.375.375 0 0 0 .17-.502");
}

.bwibo9t2c {
  cx: 0.894px;
  cy: 0.894px;
  r: 0.894px;
}

.bzyp_ibbo {
  stop-color: var(--svg-color--71404f, #71404F);
}

.c479w-bpn {
  stop-color: var(--svg-color--fead30, #FEAD30);
}

.c76owwbvh {
  stop-color: var(--svg-color--393640, #393640);
}

.cabiwub4i {
  stop-color: var(--svg-color--535154, #535154);
  stop-opacity: 0;
}

.cb_w9xm8y {
  d: path("m12.407 10.106l.263 2.526c-.688 0-1.692.101-2.07.172c-.075-.523-.233-1.725-.274-2.356c-.052-.787.17-1.098.424-1.267c.154-.103.595-.3 1.083 0c.39.24.545.716.574.925");
}

.cb3my7ddm {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M7.5 29.603a1.146 1.146 0 1 1 0-2.292a1.146 1.146 0 0 1 0 2.292Z");
}

.cfhwg-9zy {
  stop-color: var(--svg-color--422d5a, #422D5A);
  stop-opacity: 0;
}

.citbmybyr {
  d: path("M0 0h.471v1.492H0z");
}

.clzavdftr {
  stop-color: var(--svg-color--5e4e70, #5E4E70);
}

.cn0rvobaf {
  fill: var(--svg-color--2c66a4, #2C66A4);
  d: path("m12.614 10.3l.263 2.526c-.688 0-1.692.102-2.07.172c-.075-.522-.233-1.725-.274-2.355c-.052-.788.17-1.098.424-1.268c.154-.103.595-.3 1.083 0c.39.24.546.717.574.925");
}

.cu9n-vbgf {
  stop-color: var(--svg-color--c7262d, #C7262D);
}

.cvn34-xwu {
  stop-color: var(--svg-color--832538, #832538);
  stop-opacity: 0;
}

.d0phtb81o {
  stop-color: var(--svg-color--9d969d, #9D969D);
}

.d2fye0bkn {
  fill: var(--svg-color--55416a, #55416A);
  d: path("M10.04 9.287a1.4 1.4 0 0 0-1.382-1.172h-.182a1.4 1.4 0 0 0-1.38 1.628l1.378 8.345h3.02z");
}

.d51o8ek-s {
  d: path("m12.534 12.928l-.062-.5a5.2 5.2 0 0 0-1.883.265c.01.164.05.597.125 1.016c.094.523.367 1.183 1.633 1.23c1.265.047 3.468-.152 3.726-.222c.206-.057.44-.065.532-.063l.968-.554c.195.07.375-.188.133-.391c-.325-.281-.98-.326-1.266-.313c-1.125-.387-3.073-.474-3.906-.468");
}

.d7kch3t0q {
  stop-color: var(--svg-color--ffab1d, #FFAB1D);
}

.d9q4mwzxt {
  stop-color: var(--svg-color--5c5166, #5C5166);
}

.dt2-hrbth {
  stop-color: var(--svg-color--2b2731, #2B2731);
}

.e14bc-vgp {
  stop-color: var(--svg-color--ab556a, #AB556A);
  stop-opacity: 0;
}

.e2kdnzhzw {
  cx: 0.637px;
  cy: 0.637px;
  r: 0.637px;
  fill: var(--svg-color--3e384b, #3E384B);
}

.e8l0r5bvp {
  cx: 0.794px;
  cy: 0.794px;
  r: 0.794px;
}

.e9_lu_tkl {
  stop-color: var(--svg-color--685977, #685977);
}

.ebki_vbdj {
  stop-color: var(--svg-color--e4355d, #E4355D);
}

.eeeq85f7u {
  d: path("M14.23 4.79c-.112-.73-.386-1.06-.509-1.152l-3.419.354l.242 2.903c.995 1.862 3.426 1.695 3.716.955c.289-.74.098-2.215-.03-3.06");
}

.ejmms-frd {
  stop-color: var(--svg-color--5a4a6a, #5A4A6A);
}

.erpm-ebho {
  stop-color: var(--svg-color--64597c, #64597C);
  stop-opacity: 0;
}

.etx6bbf-f {
  stop-color: var(--svg-color--6c5d7f, #6C5D7F);
}

.eu5aevb0y {
  stop-color: var(--svg-color--bb3143, #BB3143);
}

.eutzrtbnw {
  fill: var(--svg-color--857d8e, #857D8E);
  fill-rule: evenodd;
  d: path("M13.4 30.006a2.531 2.531 0 1 1 0-5.063a2.531 2.531 0 0 1 0 5.063m0-1.02a1.512 1.512 0 1 1 0-3.024a1.512 1.512 0 0 1 0 3.024");
}

.ewip82vxi {
  stop-color: var(--svg-color--56426b, #56426B);
  stop-opacity: 0;
}

.f3ufgjgnw {
  fill: var(--svg-color--fff, #fff);
  d: path("m13.972 5.399l-.905.093c-.037-.358.135-.67.385-.696s.483.244.52.603");
}

.f6z4yi_ag {
  stop-color: var(--svg-color--dd2f40, #DD2F40);
}

.fndizab4b {
  stop-color: var(--svg-color--5e4a5e, #5E4A5E);
}

.ft5dv1b6b {
  fill: none;
}

.fvok_qxen {
  stop-color: var(--svg-color--ffbf42, #FFBF42);
}

.gb6cd3sju {
  stop-color: var(--svg-color--4b3c57, #4B3C57);
  stop-opacity: 0;
}

.gg7le5bub {
  stop-color: var(--svg-color--976635, #976635);
}

.golah4bmm {
  stop-color: var(--svg-color--db4459, #DB4459);
}

.gs_3vbc-h {
  d: path("M13.597 4.005c.6-.062.852-.431.837-.86c-.062-.601-.535-.681-.715-.682c-.202 0-.283-.014-.583-.182a.83.83 0 0 0-.843-.004c-.129.079-.426.142-.647.1c-.37-.07-.648-.038-.902.202c-.176.166-.317.18-.546.204c-.315.033-.568.201-.754.375c-.555.518-.324 2.076.064 2.926c.371.813.81.868 1.164.798c.426-.083.502-.42.539-.699c.029-.223.108-.744.145-.977a.98.98 0 0 0 .423-.666c.055-.364.41-.442.655-.444c.15 0 .562-.029 1.163-.09");
}

.gv3iwdbvq {
  stop-color: var(--svg-color--666361, #666361);
}

.gwis82dft {
  width: 11.844px;
  height: 2.839px;
  rx: 0.5px;
}

.gxhbeh9zc {
  stop-color: var(--svg-color--483962, #483962);
}

.gzc_qccoq {
  stop-color: var(--svg-color--3e3e6c, #3E3E6C);
}

.hhs22o5wo {
  d: path("m15.27 15.013l-3.792 3.118l-1.44-8.172c.196-1.362 1.875-1.576 2.518-1.507c.642.068 1.37.436 1.875 1.978c.405 1.234.728 3.57.84 4.583");
}

.hjg9lybhz {
  stop-color: var(--svg-color--142c6c, #142C6C);
}

.hlkhhwb3q {
  stop-color: var(--svg-color--f24147, #F24147);
}

.hw8l16bxs {
  stop-color: var(--svg-color--5e4a5e, #5E4A5E);
  stop-opacity: 0;
}

.hwvatcc-y {
  stop-color: var(--svg-color--9d969d, #9D969D);
  stop-opacity: 0;
}

.hxfvufi0i {
  stop-color: var(--svg-color--a09aa7, #A09AA7);
  stop-opacity: 0;
}

.hxu4b4bgy {
  d: path("M0 0h1.914v2.752H0z");
}

.i_b2cj3we {
  fill-rule: evenodd;
  d: path("M7.572 30.006a1.496 1.496 0 1 1 0-2.993a1.496 1.496 0 0 1 0 2.993m0-.603a.894.894 0 1 1 0-1.787a.894.894 0 0 1 0 1.787");
}

.i00c46bgu {
  stop-color: var(--svg-color--4b3c57, #4B3C57);
}

.i4u-5824r {
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M13.3 29.403a2.03 2.03 0 1 1 0-4.058a2.03 2.03 0 0 1 0 4.058Z");
}

.i8rkxoa5u {
  stop-color: var(--svg-color--832538, #832538);
}

.iap3byr6y {
  cx: 0.059px;
  cy: 0.08px;
  rx: 0.059px;
  ry: 0.08px;
}

.id4s2xn6z {
  stop-color: var(--svg-color--824403, #824403);
}

.id6hb3b7i {
  stop-color: var(--svg-color--b11943, #B11943);
}

.ie8_agh2b {
  stop-color: var(--svg-color--3e3e6c, #3E3E6C);
  stop-opacity: 0;
}

.ihz8r9bpq {
  stop-color: var(--svg-color--535154, #535154);
}

.ipohnfkvg {
  stop-color: var(--svg-color--5a4a71, #5A4A71);
}

.j0xqyhb3r {
  stop-color: var(--svg-color--5382a1, #5382A1);
}

.j5-6p70xh {
  stop-color: var(--svg-color--908893, #908893);
}

.jfv70ccah {
  stop-color: var(--svg-color--b28146, #B28146);
}

.jqu95-b8t {
  stop-color: var(--svg-color--574568, #574568);
}

.jsdt5e8xl {
  stop-color: var(--svg-color--64597c, #64597C);
}

.jve2rcqoj {
  stop-color: var(--svg-color--ffbc2b, #FFBC2B);
}

.jzl720bvd {
  stop-color: var(--svg-color--816d8d, #816D8D);
}

.k8klmcqbt {
  stop-color: var(--svg-color--645381, #645381);
}

.k8xj131jx {
  d: path("m21.29 17.974l1.031 5.078l-.344.329l-1.718-5.875h-2v-1.594l1.281.156c1.125.125 1.636 1.323 1.75 1.906");
}

.ka6kobc6f {
  stop-color: var(--svg-color--474652, #474652);
  stop-opacity: 0;
}

.kegmapbvr {
  stop-color: var(--svg-color--5c5166, #5C5166);
  stop-opacity: 0;
}

.kh4so6bgt {
  stop-color: var(--svg-color--404047, #404047);
  stop-opacity: 0;
}

.kpbiulbbs {
  stop-color: var(--svg-color--ffa629, #FFA629);
}

.l-ch5ci-p {
  stop-color: var(--svg-color--2d64a3, #2D64A3);
  stop-opacity: 0;
}

.l0aricxam {
  stop-color: var(--svg-color--916a62, #916A62);
}

.lgp2azslk {
  d: path("M0 0h4.836v1.273H0z");
}

.llvcdob8n {
  fill: var(--svg-color--f0303e, #F0303E);
  d: path("m6.08 25.147l3.059-1.72l1.054 3.269H6.48a.827.827 0 0 1-.399-1.549");
}

.lzhai0baa {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("m25.842 24.013l-3.89 1.907h-1.227");
}

.lzxtmdbfr {
  stop-color: var(--svg-color--4a3a4c, #4A3A4C);
}

.m_-nxz25m {
  cx: 0.475px;
  cy: 0.475px;
  r: 0.475px;
  fill: var(--svg-color--3e3a4a, #3E3A4A);
}

.ma5b9zegf {
  stop-color: var(--svg-color--9c83b4, #9C83B4);
}

.mas-0fbya {
  stop-color: var(--svg-color--c5992b, #C5992B);
}

.mcd03_b4y {
  stop-color: var(--svg-color--ab556a, #AB556A);
}

.md_i0_blm {
  fill: var(--svg-color--87014d, #87014D);
  fill-rule: evenodd;
  d: path("M13.395 6.49a.115.115 0 0 0 .018.161c.24.191.561.214.662.214a.115.115 0 1 0 0-.23c-.086 0-.341-.023-.519-.164a.115.115 0 0 0-.161.018");
}

.mh6_ypbam {
  d: path("m20.72 25.147l-3.058-1.72l-.961 3.269h3.62a.827.827 0 0 0 .4-1.549");
}

.mnej9qroj {
  d: path("M21.47 24.262c.196.485.388.943.567 1.346c1.097-.411 4-1.833 4-1.833c-.02-.163-.217-.526-.848-.677c-.63-.15-2.033-.131-2.655-.103c0-.006-.48.55-1.065 1.267");
}

.ms0rob30e {
  stop-color: var(--svg-color--58426e, #58426E);
  stop-opacity: 0;
}

.mykl6fbtk {
  stop-color: var(--svg-color--564778, #564778);
}

.n_csnibjz {
  d: path("M11.877 6.232c.046-.005.074-.051.063-.096l-.275-1.12c-.013-.054-.068-.087-.12-.065a.67.67 0 0 0 .332 1.28");
}

.n26ducxcj {
  width: 11.844px;
  height: 2.839px;
  fill: var(--svg-color--58426f, #58426F);
  rx: 0.5px;
}

.n9843ccmv {
  d: path("m6.08 25.147l3.059-1.72l1.054 3.269H6.48a.827.827 0 0 1-.399-1.549");
}

.n9r91ylyy {
  stop-color: var(--svg-color--824d44, #824D44);
}

.nbyzmw_ck {
  stop-color: var(--svg-color--b52f5e, #B52F5E);
}

.nhtvs4bus {
  stop-color: var(--svg-color--db4459, #DB4459);
  stop-opacity: 0;
}

.nlhf8jgze {
  d: path("M14.935 15.504a.7.7 0 0 0-.7-.7h-6.3l.274 1.672h6.026a.7.7 0 0 0 .7-.7z");
}

.nm4erqbgo {
  d: path("M0 0h.578v1.285H0z");
}

.nuhmirbhy {
  d: path("M10.04 9.287a1.4 1.4 0 0 0-1.382-1.172h-.182a1.4 1.4 0 0 0-1.38 1.628l1.378 8.345h3.02z");
}

.o-elqripn {
  cx: 1.512px;
  cy: 1.512px;
  r: 1.512px;
}

.o5h0oebxj {
  stop-color: var(--svg-color--478ece, #478ECE);
}

.o7v7nujms {
  stop-color: var(--svg-color--b92c31, #B92C31);
  stop-opacity: 0;
}

.otvqpncsi {
  d: path("M9.117 3.888a1.2 1.2 0 0 0-1.39-.972l-.565.1a1.2 1.2 0 0 0-.973 1.39l.3 1.696a1.2 1.2 0 0 0 1.392.972l.564-.1a1.2 1.2 0 0 0 .973-1.39z");
}

.p13ql8bhx {
  d: path("M14.531 5.485a.9.9 0 0 1-.28-.394l-.164.017l.107 1.03c.21.105.489.056.553-.14c.055-.168-.02-.363-.216-.513");
}

.p2wklo0_t {
  cx: 0.377px;
  cy: 0.377px;
  r: 0.377px;
  fill: var(--svg-color--3e384b, #3E384B);
}

.p6m2bvbro {
  fill: var(--svg-color--857d8e, #857D8E);
  fill-rule: evenodd;
  d: path("M7.572 30.006a1.496 1.496 0 1 1 0-2.993a1.496 1.496 0 0 1 0 2.993m0-.603a.894.894 0 1 1 0-1.787a.894.894 0 0 1 0 1.787");
}

.p74b59bbc {
  fill: var(--svg-color--489ada, #489ADA);
  d: path("m15.27 15.013l-3.792 3.118l-1.44-8.172c.196-1.362 1.875-1.576 2.518-1.507c.642.068 1.37.436 1.875 1.978c.405 1.234.728 3.57.84 4.583");
}

.p8hc-w2ji {
  stop-color: var(--svg-color--746e6d, #746E6D);
}

.pbwt4gb4m {
  stop-color: var(--svg-color--675876, #675876);
  stop-opacity: 0;
}

.pyf4h2zzf {
  cx: 1.496px;
  cy: 1.496px;
  r: 1.496px;
}

.qhupv-mle {
  cx: 0.518px;
  cy: 0.518px;
  r: 0.518px;
}

.qj5co5rje {
  fill: var(--svg-color--5e4f7f, #5E4F7F);
  d: path("M18.055 17.27a.5.5 0 0 0-.5-.5h-1.548a.5.5 0 0 0-.5.5v.819h2.548z");
}

.rfxr5lvvz {
  stop-color: var(--svg-color--cc3437, #CC3437);
  stop-opacity: 0;
}

.rnfgp6bsq {
  stop-color: var(--svg-color--1e6db7, #1E6DB7);
  stop-opacity: 0;
}

.ronnvab4v {
  stop-color: var(--svg-color--211b2c, #211B2C);
}

.rtjr-xb4t {
  stop-color: var(--svg-color--c99223, #C99223);
  stop-opacity: 0;
}

.ry2t0ob6u {
  fill: var(--svg-color--fbbf3c, #FBBF3C);
  d: path("M17.836 14.767c-.417-.495-.92-.668-1.13-.707c-.222-.062-.651-.075-.726.121a.43.43 0 0 0 .062.419a1.94 1.94 0 0 1 1.32.55a.32.32 0 0 0 .443.004a.284.284 0 0 0 .03-.387");
}

.s_bd7ebgs {
  fill: var(--svg-color--55426a, #55426A);
  d: path("M9.117 3.888a1.2 1.2 0 0 0-1.39-.972l-.565.1a1.2 1.2 0 0 0-.973 1.39l.3 1.696a1.2 1.2 0 0 0 1.392.972l.564-.1a1.2 1.2 0 0 0 .973-1.39z");
}

.sbet6hhzy {
  d: path("M18.055 17.27a.5.5 0 0 0-.5-.5h-1.548a.5.5 0 0 0-.5.5v.819h2.548z");
}

.scqcqwblc {
  stop-color: var(--svg-color--7d7172, #7D7172);
}

.sdzcd6bgx {
  d: path("M13.417 5.456v-.004c-.03-.293.07-.544.226-.56c.155-.016.305.209.336.502v.004z");
}

.seor_02fd {
  stop-color: var(--svg-color--422d5a, #422D5A);
}

.sh1u5ab0i {
  stop-color: var(--svg-color--ffb535, #FFB535);
}

.sjqhriwca {
  stop-color: var(--svg-color--023981, #023981);
}

.snka5sm3m {
  stop-color: var(--svg-color--6b6080, #6B6080);
  stop-opacity: 0;
}

.sputfhdoz {
  stop-color: var(--svg-color--6a5c77, #6A5C77);
}

.stui2mbih {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0;
}

.suyap8bzv {
  stop-color: var(--svg-color--eba544, #EBA544);
}

.t_w7gbbck {
  stop-color: var(--svg-color--675876, #675876);
}

.t07ov5bcy {
  stop-color: var(--svg-color--483962, #483962);
  stop-opacity: 0;
}

.t84n9rbqs {
  cx: 1.496px;
  cy: 1.496px;
  r: 1.496px;
  fill: var(--svg-color--857d8e, #857D8E);
}

.t8rqipb-o {
  stop-color: var(--svg-color--523579, #523579);
}

.t9qy5zbtq {
  stop-color: var(--svg-color--64576e, #64576E);
  stop-opacity: 0;
}

.th1brvxrz {
  stop-color: var(--svg-color--ed516c, #ED516C);
}

.ts_kmdhif {
  stop-color: var(--svg-color--478ece, #478ECE);
  stop-opacity: 0;
}

.u2e3rxbtp {
  stop-color: var(--svg-color--f3bc3a, #F3BC3A);
  stop-opacity: 0;
}

.u9mcm6llv {
  stop-color: var(--svg-color--565476, #565476);
}

.ubkfx58us {
  stop-color: var(--svg-color--c37e14, #C37E14);
  stop-opacity: 0;
}

.ubyl24bdb {
  stop-color: var(--svg-color--565352, #565352);
}

.uevlegbhj {
  stop-color: var(--svg-color--5b4874, #5B4874);
  stop-opacity: 0;
}

.uhndsibic {
  stop-color: var(--svg-color--cca03a, #CCA03A);
}

.um0wv7bwm {
  fill: var(--svg-color--fbbf3c, #FBBF3C);
  d: path("M18.239 14.576c-.367-.533-.853-.754-1.057-.812c-.215-.083-.641-.137-.735.051a.43.43 0 0 0 .023.422c.643.083 1.02.403 1.261.675a.32.32 0 0 0 .44.047a.284.284 0 0 0 .068-.383");
}

.uu4nvia_s {
  stop-color: var(--svg-color--958d9a, #958D9A);
  stop-opacity: 0;
}

.ux0of3-jj {
  stop-color: var(--svg-color--e2305a, #E2305A);
  stop-opacity: 0;
}

.v4yb5cu8i {
  stop-color: var(--svg-color--695b77, #695B77);
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.vhbvss0_z {
  stroke: var(--svg-color--bc5f4e, #BC5F4E);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M13.615 4.354c-.118.012-.376.04-.551.195");
}

.vt606lu7d {
  stop-color: var(--svg-color--574568, #574568);
  stop-opacity: 0;
}

.w_fjow9gn {
  stop-color: var(--svg-color--d61f4c, #D61F4C);
}

.w07b1tb5i {
  stop-color: var(--svg-color--5e4e70, #5E4E70);
  stop-opacity: 0;
}

.wj-_1oh1j {
  d: path("m17.514 26.645l.425-3.4a1.2 1.2 0 0 0-1.191-1.349h-6.672a1.2 1.2 0 0 0-1.191 1.343l.406 3.4a1 1 0 0 0 .993.882h6.237a1 1 0 0 0 .992-.876");
}

.wjw662jrg {
  stop-color: var(--svg-color--321d4a, #321D4A);
}

.wkp12s_bh {
  fill: var(--svg-color--4c477e, #4C477E);
  d: path("M21.47 24.262c.196.485.388.943.567 1.346c1.097-.411 4-1.833 4-1.833c-.02-.163-.217-.526-.848-.677c-.63-.15-2.033-.131-2.655-.103c0-.006-.48.55-1.065 1.267");
}

.wq290abaa {
  stop-color: var(--svg-color--44a1e7, #44A1E7);
  stop-opacity: 0;
}

.wxyfq_b9d {
  fill: var(--svg-color--ffc136, #FFC136);
  d: path("m12.534 12.928l-.062-.5a5.2 5.2 0 0 0-1.883.265c.01.164.05.597.125 1.016c.094.523.367 1.183 1.633 1.23c1.265.047 3.468-.152 3.726-.222c.206-.057.44-.065.532-.063l.968-.554c.195.07.375-.188.133-.391c-.325-.281-.98-.326-1.266-.313c-1.125-.387-3.073-.474-3.906-.468");
}

.wyvd7ua1n {
  fill: var(--svg-color--3b3349, #3B3349);
  fill-rule: evenodd;
  d: path("M26.303 23.848a.375.375 0 0 0-.502-.17l-3.788 1.864l-.01.003h-1.427a.375.375 0 0 0 0 .75h1.426a.8.8 0 0 0 .343-.08l3.787-1.865a.375.375 0 0 0 .17-.502");
}

.x37zrlbcp {
  stop-color: var(--svg-color--f3bc3a, #F3BC3A);
}

.x9-imyafb {
  stop-color: var(--svg-color--958d9a, #958D9A);
}

.x91xhsboa {
  stop-color: var(--svg-color--55426a, #55426A);
  stop-opacity: 0;
}

.xbtn5acgm {
  stop-color: var(--svg-color--6c5d7f, #6C5D7F);
  stop-opacity: 0;
}

.xkzs54_ul {
  stop-color: var(--svg-color--4d487f, #4D487F);
  stop-opacity: 0;
}

.xplz5bcrg {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M19.229 29.603a1.146 1.146 0 1 1 0-2.292a1.146 1.146 0 0 1 0 2.292Z");
}

.xs80ogben {
  stop-color: var(--svg-color--6b6080, #6B6080);
}

.y05dlfbsr {
  stop-color: var(--svg-color--5b4874, #5B4874);
}

.y9tlk8oux {
  fill: var(--svg-color--328ce0, #328CE0);
  d: path("m12.407 10.106l.263 2.526c-.688 0-1.692.101-2.07.172c-.075-.523-.233-1.725-.274-2.356c-.052-.787.17-1.098.424-1.267c.154-.103.595-.3 1.083 0c.39.24.545.716.574.925");
}

.ybejupycn {
  stop-color: var(--svg-color--b92c31, #B92C31);
}

.yru3_4bbx {
  stop-color: var(--svg-color--fbb434, #FBB434);
}

.yu1mih4mu {
  stop-color: var(--svg-color--9c1a55, #9C1A55);
}

.yxnjz7r7g {
  stop-color: var(--svg-color--c54169, #C54169);
  stop-opacity: 0;
}

.z-2ie6sne {
  stop-color: var(--svg-color--2d64a3, #2D64A3);
}

.z-j5q9xut {
  width: 0.619px;
  height: 2.008px;
  rx: 0.31px;
}

.z1-difb5b {
  stop-color: var(--svg-color--c54169, #C54169);
}

.z2dz7rv_f {
  d: path("m19.15 15.518l-3.914-.48l-4.53 3.426h8.582s1.636 4.634 2.75 7.144c1.096-.411 4-1.833 4-1.833c-.02-.163-.218-.526-.849-.677c-.63-.15-2.033-.131-2.655-.103c-.117-.825-.439-2.956-.788-4.882s-1.876-2.532-2.595-2.595");
}

.zdh48sb9s {
  stop-color: var(--svg-color--816d8d, #816D8D);
  stop-opacity: 0;
}

.zeqefbvfd {
  stop-color: var(--svg-color--321c43, #321C43);
}

.zqylsrrgt {
  stop-color: var(--svg-color--5382a1, #5382A1);
  stop-opacity: 0;
}

</style>
