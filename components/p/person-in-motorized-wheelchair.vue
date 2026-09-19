<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#ixqmT6r)" class="afgvi4b_x"/><path fill="url(#iBZHtJb)" class="afgvi4b_x"/><path class="z4_9uopis"/><path fill="url(#iLvDlbc)" class="gfvzkzeir"/><path fill="url(#ij2EVRd)" class="gfvzkzeir"/><g filter="url(#iXztjAe)"><path fill="url(#iJUp0Jb)" class="xxg5o4foh"/><path fill="url(#iCxgseb)" class="xxg5o4foh"/><path fill="url(#iOtCVwd)" class="xxg5o4foh"/><path fill="url(#iM9K7qG)" class="xxg5o4foh"/></g><path class="uclk6dbhm"/><path fill="url(#irYS1Cc)" class="jid13cbfr"/><path fill="url(#ihqX1Gb)" class="jid13cbfr"/><path fill="url(#iGwjkFe)" class="jid13cbfr"/><path fill="url(#iI1tpDc)" class="oxa-zpnbc"/><path fill="url(#iMzf48b)" class="ijfe69bnq"/><path fill="url(#i51OYkb)" class="j3tnzsbnn"/><g filter="url(#iVEajnV)"><path clip-rule="evenodd" class="vj-cg71dv"/><path fill="url(#ieZHdVn)" clip-rule="evenodd" class="tnj2m0let"/></g><g filter="url(#iXH27rv)"><path stroke="url(#i8hukwc)" class="n0wdiubea"/></g><circle fill="url(#ioxDaxp)" class="auog_xb1g"/><circle fill="url(#iDFMV7c)" class="auog_xb1g"/><circle fill="url(#iQm5Vpd)" class="auog_xb1g"/><circle class="kikr0z55d"/><circle fill="url(#iTMEBRd)" class="ds-9iibtp"/><circle fill="url(#iupzpyb)" class="ds-9iibtp"/><g filter="url(#i1akbib)"><path fill="url(#idbAfre)" class="br13rubgx"/><path fill="url(#ix17Drc)" class="br13rubgx"/><path fill="url(#i4MQwgb)" class="br13rubgx"/></g><g filter="url(#igW0exb)"><path class="lw64igb3q"/><path fill="url(#i0nu64d)" class="pbwaenbxo"/></g><path class="ie8nvs_jh"/><path fill="url(#iQ8arBd)" class="mnv88fh6g"/><path fill="url(#iYZ49Bb)" class="mnv88fh6g"/><path fill="url(#inPpLde)" class="mnv88fh6g"/><path fill="url(#i8aI7de)" class="mnv88fh6g"/><path fill="url(#iruLXnd)" class="mnv88fh6g"/><rect fill="url(#i1iHwrd)" transform="rotate(9.205 23.613 6.619)" class="rzgv5-bix"/><rect fill="url(#iJtCvye)" transform="rotate(9.205 23.613 6.619)" class="rzgv5-bix"/><path fill="url(#ilkbDyc)" class="pae25fhsd"/><path fill="url(#i2me3Oi)" class="pae25fhsd"/><g filter="url(#igiwmpe)"><path class="jrtayobva"/><path fill="url(#irCv5re)" class="uxyvsjboq"/><path fill="url(#is0KsKe)" class="uxyvsjboq"/></g><path fill="url(#iQEBFhe)" class="uxyvsjboq"/><g filter="url(#i18aZ8c)"><rect class="trlm7mbbt"/><rect fill="url(#itMY40b)" class="zh7fl7z_h"/><rect fill="url(#ipVmsNm)" class="zh7fl7z_h"/></g><rect fill="url(#ilM5tfc)" class="zh7fl7z_h"/><g filter="url(#ip2cPFd)"><path fill="url(#i6JE2Wa)" class="rw_zanbli"/></g><path fill="url(#ihLFbta)" class="rw_zanbli"/><circle class="r-y-1acck"/><g filter="url(#ibRT17c)"><circle class="rbdcwebfp"/></g><circle fill="url(#iVLo4Kd)" class="sd26nmbri"/><circle fill="url(#ixyhycd)" class="lrd0xzbnc"/><circle fill="url(#itdFAxN)" class="ea3nq_bza"/><g filter="url(#idS3AIW)"><path clip-rule="evenodd" class="pngn0fmrc"/></g><path fill="url(#inFfYNq)" clip-rule="evenodd" class="imo1scbvv"/><g filter="url(#iACSlMk)"><circle class="afjbg56bb"/></g><g filter="url(#i8TNtvb)"><circle class="l056r-bgv"/></g><g filter="url(#iafDH8b)"><path fill="url(#iemLnZb)" class="l1p2lzbva"/></g><path fill="url(#imYmKGc)" class="l1p2lzbva"/><path fill="url(#icaXjhc)" class="l1p2lzbva"/><circle fill="url(#i2AXI8c)" class="g1l-ujbgf"/><g filter="url(#iIatJWd)"><path clip-rule="evenodd" class="ls7oj_z4s"/></g><g filter="url(#ibQvEQd)"><path stroke="url(#izPuBhe)" clip-rule="evenodd" class="nc_ezabaa"/></g><g filter="url(#iTfD0Tb)"><path stroke="url(#iKhOX5d)" clip-rule="evenodd" class="jejfpy4sc"/></g><g filter="url(#ikeQliR)"><path class="oqbmkuz2v"/></g><g filter="url(#i6k61ne)"><path stroke="url(#infXmad)" clip-rule="evenodd" class="cpg4-bb7y"/></g><g filter="url(#iugBmXc)"><circle class="itdceeb_q"/></g><g filter="url(#i67FoxQ)"><path class="m_reoz2pl"/></g><path fill="url(#ixarMEc)" class="zhngqmnyt"/><g filter="url(#iGjo8Gc)"><path class="wode0hb4p"/></g><g filter="url(#iyObIub)"><path class="pe6w2ixsr"/></g><path fill="url(#iE4Emyb)" class="tidy9bped"/><g filter="url(#iTr72ve)"><path fill="url(#i1X4Lnd)" class="pnj03optx"/><path fill="url(#ifgmvdc)" class="pnj03optx"/></g><g filter="url(#iUP7xmc)"><path class="txm_4ebvw"/><path fill="url(#i12dvYb)" class="jvia9sbhc"/><path fill="url(#i0YMSlc)" class="jvia9sbhc"/><path fill="url(#iJGAopd)" class="jvia9sbhc"/><path fill="url(#iBHpmrb)" class="jvia9sbhc"/><path fill="url(#ilRghRc)" class="jvia9sbhc"/></g><path fill="url(#iQ1Xkte)" class="jvia9sbhc"/><path fill="url(#iJkC0sc)" class="jvia9sbhc"/><path fill="url(#i5Hv8Zd)" class="xq7qudg4u"/><path clip-rule="evenodd" class="lnt0jpotc"/><g filter="url(#iiydiDe)"><path clip-rule="evenodd" class="oyu5u8bov"/></g><path class="oq29cacqb"/><path fill="url(#iHJDfzc)" class="vq556dbac"/><path fill="url(#iHW8Jge)" class="wy93f33rd"/><ellipse fill="url(#iyYKxQb)" transform="rotate(31.04 18.364 5.126)" class="p2cn_nwxs"/><path class="n2o4e_51w"/><path fill="url(#imHzYJK)" class="w3cjn9brj"/><path fill="url(#iCu7Tue)" class="w3cjn9brj"/><path fill="url(#iUHIUpb)" class="w3cjn9brj"/><path fill="url(#iupTs2d)" class="w3cjn9brj"/><path fill="url(#iK0A4Vd)" class="w3cjn9brj"/><g filter="url(#iMLnRQb)"><path fill="url(#ieEEZBA)" class="lnbhqzbme"/></g><path fill="url(#ijGOome)" class="aqa9dgbyv"/><path fill="url(#iFubDXd)" class="aqa9dgbyv"/><defs><radialGradient id="iLvDlbc" cx="0" cy="0" r="1" gradientTransform="matrix(4.625 4.75 -5.30937 5.16965 16.085 9.483)" gradientUnits="userSpaceOnUse"><stop offset=".367" class="at42zcbhv"/><stop offset="1" class="pwpzq7byn"/></radialGradient><radialGradient id="iCxgseb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.125 -1 2.95172 -6.27244 12.148 21.796)" gradientUnits="userSpaceOnUse"><stop class="jzl720bvd"/><stop offset="1" class="zdh48sb9s"/></radialGradient><radialGradient id="iOtCVwd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.40625 6.4375 0 18.648 18.077)" gradientUnits="userSpaceOnUse"><stop class="d9q4mwzxt"/><stop offset="1" class="kegmapbvr"/></radialGradient><radialGradient id="iM9K7qG" cx="0" cy="0" r="1" gradientTransform="matrix(1.53125 .3125 -1.31889 6.46255 9.366 19.67)" gradientUnits="userSpaceOnUse"><stop class="d0phtb81o"/><stop class="d0phtb81o"/><stop offset="1" class="hwvatcc-y"/></radialGradient><radialGradient id="irYS1Cc" cx="0" cy="0" r="1" gradientTransform="matrix(-.11941 -1.8243 6.0381 -.39524 8.366 24.796)" gradientUnits="userSpaceOnUse"><stop offset=".584" class="ie8_agh2b"/><stop offset="1" class="gzc_qccoq"/></radialGradient><radialGradient id="iGwjkFe" cx="0" cy="0" r="1" gradientTransform="matrix(1.64063 -.01563 .00576 .60488 6.07 23.718)" gradientUnits="userSpaceOnUse"><stop class="u9mcm6llv"/><stop offset="1" class="b-3vnvcpj"/></radialGradient><radialGradient id="ieZHdVn" cx="0" cy="0" r="1" gradientTransform="matrix(1.01563 .01563 -.03485 2.26557 5.557 23.952)" gradientUnits="userSpaceOnUse"><stop class="ihz8r9bpq"/><stop offset="1" class="cabiwub4i"/></radialGradient><radialGradient id="ioxDaxp" cx="0" cy="0" r="1" gradientTransform="matrix(-.80087 -.53995 .5353 -.79397 15.587 16.71)" gradientUnits="userSpaceOnUse"><stop class="id6hb3b7i"/><stop offset="1" class="nbyzmw_ck"/></radialGradient><radialGradient id="iDFMV7c" cx="0" cy="0" r="1" gradientTransform="matrix(.27344 -.33594 .30415 .24757 15.494 16.413)" gradientUnits="userSpaceOnUse"><stop offset=".133" class="z1-difb5b"/><stop offset="1" class="yxnjz7r7g"/></radialGradient><radialGradient id="iQm5Vpd" cx="0" cy="0" r="1" gradientTransform="matrix(.18962 -.81468 .57531 .1339 14.418 16.86)" gradientUnits="userSpaceOnUse"><stop class="mcd03_b4y"/><stop offset="1" class="e14bc-vgp"/></radialGradient><radialGradient id="iTMEBRd" cx="0" cy="0" r="1" gradientTransform="rotate(65.376 -3.826 19.267)scale(.41251)" gradientUnits="userSpaceOnUse"><stop offset=".179" class="ipohnfkvg"/><stop offset="1" class="aur13kbnc"/></radialGradient><radialGradient id="iupzpyb" cx="0" cy="0" r="1" gradientTransform="matrix(.41406 -.125 .14254 .47215 14.744 15.085)" gradientUnits="userSpaceOnUse"><stop class="clzavdftr"/><stop offset="1" class="w07b1tb5i"/></radialGradient><radialGradient id="ix17Drc" cx="0" cy="0" r="1" gradientTransform="matrix(.70312 -.28126 .36059 .90144 10.98 25.953)" gradientUnits="userSpaceOnUse"><stop class="b9iguid0k"/><stop offset="1" class="rfxr5lvvz"/></radialGradient><radialGradient id="iJtCvye" cx="0" cy="0" r="1" gradientTransform="rotate(-90.544 16.18 -7.893)scale(1.19329 .67738)" gradientUnits="userSpaceOnUse"><stop class="bcaxkqjfb"/><stop offset="1" class="kh4so6bgt"/></radialGradient><radialGradient id="ilkbDyc" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.16406 -2.98016 0 18.6 20.858)" gradientUnits="userSpaceOnUse"><stop offset=".161" class="yu1mih4mu"/><stop offset="1" class="eu5aevb0y"/></radialGradient><radialGradient id="i2me3Oi" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.36328 -3.72499 0 18.6 21.386)" gradientUnits="userSpaceOnUse"><stop offset=".358" class="cvn34-xwu"/><stop offset=".771" class="i8rkxoa5u"/></radialGradient><radialGradient id="is0KsKe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.10465 .77326 -.66363 -.94804 24.784 9.072)" gradientUnits="userSpaceOnUse"><stop class="t_w7gbbck"/><stop offset="1" class="pbwt4gb4m"/></radialGradient><radialGradient id="iQEBFhe" cx="0" cy="0" r="1" gradientTransform="matrix(-.0138 .77326 -2.388 -.04264 22.147 16.321)" gradientUnits="userSpaceOnUse"><stop offset=".208" class="seor_02fd"/><stop offset="1" class="cfhwg-9zy"/></radialGradient><radialGradient id="ihLFbta" cx="0" cy="0" r="1" gradientTransform="matrix(.64844 -.00781 .01612 1.33804 17.065 15.577)" gradientUnits="userSpaceOnUse"><stop offset=".032" class="etx6bbf-f"/><stop offset="1" class="xbtn5acgm"/></radialGradient><radialGradient id="iVLo4Kd" cx="0" cy="0" r="1" gradientTransform="matrix(1.71874 -1.8125 1.7735 1.68175 12.167 29.28)" gradientUnits="userSpaceOnUse"><stop offset=".556" class="bu0v-9rgl"/><stop offset="1" class="bzyp_ibbo"/></radialGradient><radialGradient id="ixyhycd" cx="0" cy="0" r="1" gradientTransform="rotate(-49.87 37.324 .96)scale(1.46152 1.87048)" gradientUnits="userSpaceOnUse"><stop offset=".233" class="b3dj2bied"/><stop offset="1" class="ma5b9zegf"/></radialGradient><radialGradient id="itdFAxN" cx="0" cy="0" r="1" gradientTransform="rotate(-49.87 43.152 -11.576)scale(1.46152 1.87048)" gradientUnits="userSpaceOnUse"><stop offset=".233" class="b3dj2bied"/><stop offset="1" class="ma5b9zegf"/></radialGradient><radialGradient id="inFfYNq" cx="0" cy="0" r="1" gradientTransform="rotate(-133.238 18.902 9.26)scale(2.87398 2.81213)" gradientUnits="userSpaceOnUse"><stop offset=".556" class="bu0v-9rgl"/><stop offset="1" class="bzyp_ibbo"/></radialGradient><radialGradient id="icaXjhc" cx="0" cy="0" r="1" gradientTransform="matrix(-.625 3.92187 -.8118 -.12937 22.744 22.827)" gradientUnits="userSpaceOnUse"><stop class="th1brvxrz"/><stop offset="1" class="ux0of3-jj"/></radialGradient><radialGradient id="i2AXI8c" cx="0" cy="0" r="1" gradientTransform="matrix(1.59375 -1.89062 2.41965 2.03971 18.197 28.093)" gradientUnits="userSpaceOnUse"><stop offset=".233" class="b3dj2bied"/><stop offset="1" class="ma5b9zegf"/></radialGradient><radialGradient id="iE4Emyb" cx="0" cy="0" r="1" gradientTransform="rotate(68.195 4.683 15.327)scale(.99409 1.26602)" gradientUnits="userSpaceOnUse"><stop offset=".332" class="fvok_qxen"/><stop offset="1" class="suyap8bzv"/></radialGradient><radialGradient id="ifgmvdc" cx="0" cy="0" r="1" gradientTransform="matrix(-.76203 -.12903 .1573 -.92907 20.58 5.612)" gradientUnits="userSpaceOnUse"><stop offset=".156" class="d7kch3t0q"/><stop offset="1" class="admd7db0k"/></radialGradient><radialGradient id="i12dvYb" cx="0" cy="0" r="1" gradientTransform="rotate(-39.068 20.252 -25.93)scale(2.48962 3.63832)" gradientUnits="userSpaceOnUse"><stop class="re8izvbqw"/><stop offset="1" class="kgio6d1ee"/></radialGradient><radialGradient id="i0YMSlc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.0225 .5918 -.8308 -2.8393 22.526 3.782)" gradientUnits="userSpaceOnUse"><stop class="u0-djrvhx"/><stop offset="1" class="fj67tibom"/></radialGradient><radialGradient id="iJGAopd" cx="0" cy="0" r="1" gradientTransform="matrix(-.71443 -.29622 .13774 -.33221 22.155 6.688)" gradientUnits="userSpaceOnUse"><stop class="jkk-xsb9b"/><stop offset="1" class="g6je8pe2z"/></radialGradient><radialGradient id="iBHpmrb" cx="0" cy="0" r="1" gradientTransform="rotate(176.08 10.55 1.552)scale(1.67059 .77134)" gradientUnits="userSpaceOnUse"><stop offset=".174" class="t5jak8x3h"/><stop offset="1" class="hze7fms1a"/></radialGradient><radialGradient id="ilRghRc" cx="0" cy="0" r="1" gradientTransform="matrix(.41272 .48513 -.70062 .59605 18.541 2.003)" gradientUnits="userSpaceOnUse"><stop offset=".117" class="an20q5kfx"/><stop offset="1" class="xh4g4qbuv"/></radialGradient><radialGradient id="iQ1Xkte" cx="0" cy="0" r="1" gradientTransform="matrix(-.75002 -4.1852 6.41043 -1.1488 22.46 7.42)" gradientUnits="userSpaceOnUse"><stop class="t4jg6lbel"/><stop offset="1" class="xd_rxccdu"/></radialGradient><radialGradient id="iJkC0sc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.0625 -.18748 .39764 -4.37436 23.007 5.702)" gradientUnits="userSpaceOnUse"><stop offset=".251" class="z6top7alb"/><stop offset="1" class="ebu-sjblb"/></radialGradient><radialGradient id="i5Hv8Zd" cx="0" cy="0" r="1" gradientTransform="rotate(122.132 8.883 8.482)scale(.95555 1.55272)" gradientUnits="userSpaceOnUse"><stop offset=".04" class="bervkqbmz"/><stop offset="1" class="c479w-bpn"/></radialGradient><radialGradient id="iHJDfzc" cx="0" cy="0" r="1" gradientTransform="matrix(.24818 .02796 -.05433 .48217 18.424 5.437)" gradientUnits="userSpaceOnUse"><stop offset=".895" class="l0aricxam"/><stop offset="1" class="n9r91ylyy"/></radialGradient><radialGradient id="iHW8Jge" cx="0" cy="0" r="1" gradientTransform="matrix(.2269 .02557 -.05533 .49103 18.27 5.44)" gradientUnits="userSpaceOnUse"><stop class="gv3iwdbvq"/><stop offset=".813" class="ubyl24bdb"/></radialGradient><radialGradient id="imHzYJK" cx="0" cy="0" r="1" gradientTransform="matrix(.61593 -3.1794 1.00389 .19448 22.564 5.944)" gradientUnits="userSpaceOnUse"><stop class="fndizab4b"/><stop offset="1" class="hw8l16bxs"/></radialGradient><radialGradient id="iupTs2d" cx="0" cy="0" r="1" gradientTransform="rotate(142.883 12.243 6.118)scale(1.45001 1.69112)" gradientUnits="userSpaceOnUse"><stop class="v4yb5cu8i"/><stop offset="1" class="ewip82vxi"/></radialGradient><radialGradient id="iK0A4Vd" cx="0" cy="0" r="1" gradientTransform="matrix(.14062 1.03125 -3.76156 .51293 23.823 2.748)" gradientUnits="userSpaceOnUse"><stop offset=".167" class="i00c46bgu"/><stop offset="1" class="gb6cd3sju"/></radialGradient><radialGradient id="iFubDXd" cx="0" cy="0" r="1" gradientTransform="rotate(96.882 6.207 14.362)scale(2.86868 .6355)" gradientUnits="userSpaceOnUse"><stop class="a-xw_r42a"/><stop offset="1" class="vahp-bcdd"/></radialGradient><linearGradient id="ixqmT6r" x1="19.308" x2="20.624" y1="8.312" y2="8.194" gradientUnits="userSpaceOnUse"><stop class="dqw_0wbtq"/><stop offset="1" class="pg0gw1osm"/></linearGradient><linearGradient id="iBZHtJb" x1="21.507" x2="20.351" y1="8.655" y2="8.718" gradientUnits="userSpaceOnUse"><stop class="gg7le5bub"/><stop offset="1" class="rtjr-xb4t"/></linearGradient><linearGradient id="ij2EVRd" x1="21.963" x2="17.554" y1="16.671" y2="12.108" gradientUnits="userSpaceOnUse"><stop class="t4k8t2b9t"/><stop offset="1" class="lhdv8ibog"/></linearGradient><linearGradient id="iJUp0Jb" x1="17.96" x2="9.835" y1="16.827" y2="24.14" gradientUnits="userSpaceOnUse"><stop class="scqcqwblc"/><stop offset="1" class="j5-6p70xh"/></linearGradient><linearGradient id="ihqX1Gb" x1="10.312" x2="9.132" y1="25.304" y2="24.687" gradientUnits="userSpaceOnUse"><stop class="wjw662jrg"/><stop offset="1" class="xkzs54_ul"/></linearGradient><linearGradient id="iI1tpDc" x1="14.822" x2="15.422" y1="15.631" y2="15.631" gradientUnits="userSpaceOnUse"><stop class="p8hc-w2ji"/><stop offset=".573" class="c76owwbvh"/></linearGradient><linearGradient id="iMzf48b" x1="24.658" x2="24.187" y1="26.999" y2="26.655" gradientUnits="userSpaceOnUse"><stop offset=".323" class="lzxtmdbfr"/><stop offset="1" class="ajt-21bdu"/></linearGradient><linearGradient id="i51OYkb" x1="12.588" x2="13.049" y1="26.991" y2="26.741" gradientUnits="userSpaceOnUse"><stop offset=".385" class="lzxtmdbfr"/><stop offset="1" class="ajt-21bdu"/></linearGradient><linearGradient id="i8hukwc" x1="6.252" x2="11.604" y1="24.171" y2="26.444" gradientUnits="userSpaceOnUse"><stop class="bq9mpqbzy"/><stop offset="1" class="ka6kobc6f"/></linearGradient><linearGradient id="idbAfre" x1="11.494" x2="14.151" y1="26.577" y2="24.671" gradientUnits="userSpaceOnUse"><stop class="f6z4yi_ag"/><stop offset="1" class="cu9n-vbgf"/></linearGradient><linearGradient id="i4MQwgb" x1="12.791" x2="12.963" y1="24.202" y2="24.671" gradientUnits="userSpaceOnUse"><stop class="ybejupycn"/><stop offset="1" class="o7v7nujms"/></linearGradient><linearGradient id="i0nu64d" x1="24.776" x2="24.276" y1="24.171" y2="25.071" gradientUnits="userSpaceOnUse"><stop class="hlkhhwb3q"/><stop offset="1" class="b37qgpujw"/></linearGradient><linearGradient id="iQ8arBd" x1="15.219" x2="15.219" y1="16.778" y2="17.438" gradientUnits="userSpaceOnUse"><stop offset=".077" class="y05dlfbsr"/><stop offset="1" class="uevlegbhj"/></linearGradient><linearGradient id="iYZ49Bb" x1="13.944" x2="15.024" y1="17.891" y2="17.891" gradientUnits="userSpaceOnUse"><stop offset=".326" class="mykl6fbtk"/><stop offset="1" class="uevlegbhj"/></linearGradient><linearGradient id="inPpLde" x1="16.493" x2="15.675" y1="18.098" y2="18.098" gradientUnits="userSpaceOnUse"><stop class="jsdt5e8xl"/><stop offset="1" class="erpm-ebho"/></linearGradient><linearGradient id="i8aI7de" x1="16.493" x2="16.206" y1="18.098" y2="18.098" gradientUnits="userSpaceOnUse"><stop class="gxhbeh9zc"/><stop offset="1" class="t07ov5bcy"/></linearGradient><linearGradient id="iruLXnd" x1="13.944" x2="14.236" y1="17.84" y2="17.84" gradientUnits="userSpaceOnUse"><stop class="xs80ogben"/><stop offset="1" class="snka5sm3m"/></linearGradient><linearGradient id="i1iHwrd" x1="23.911" x2="23.901" y1="7.051" y2="8.256" gradientUnits="userSpaceOnUse"><stop class="ronnvab4v"/><stop offset="1" class="dt2-hrbth"/></linearGradient><linearGradient id="irCv5re" x1="23.928" x2="22.216" y1="17.329" y2="17.164" gradientUnits="userSpaceOnUse"><stop offset=".357" class="ejmms-frd"/><stop offset="1" class="bd5h7cqqn"/></linearGradient><linearGradient id="itMY40b" x1="18.651" x2="18.651" y1="18.327" y2="19.327" gradientUnits="userSpaceOnUse"><stop offset=".219" class="jqu95-b8t"/><stop offset="1" class="vt606lu7d"/></linearGradient><linearGradient id="ipVmsNm" x1="24.573" x2="23.276" y1="19.517" y2="19.517" gradientUnits="userSpaceOnUse"><stop class="e9_lu_tkl"/><stop offset="1" class="ms0rob30e"/></linearGradient><linearGradient id="ilM5tfc" x1="12.729" x2="13.244" y1="19.648" y2="19.648" gradientUnits="userSpaceOnUse"><stop offset=".255" class="aafld1b5m"/><stop offset="1" class="t9qy5zbtq"/></linearGradient><linearGradient id="i6JE2Wa" x1="20.565" x2="20.565" y1="15.017" y2="16.485" gradientUnits="userSpaceOnUse"><stop offset=".116" class="k8klmcqbt"/><stop offset="1" class="t8rqipb-o"/></linearGradient><linearGradient id="iemLnZb" x1="18.588" x2="18.588" y1="21.905" y2="27.702" gradientUnits="userSpaceOnUse"><stop class="ebki_vbdj"/><stop offset=".752" class="w_fjow9gn"/></linearGradient><linearGradient id="imYmKGc" x1="14.244" x2="15.244" y1="25.546" y2="25.452" gradientUnits="userSpaceOnUse"><stop class="golah4bmm"/><stop offset="1" class="nhtvs4bus"/></linearGradient><linearGradient id="izPuBhe" x1="20.205" x2="17.023" y1="25.711" y2="28.847" gradientUnits="userSpaceOnUse"><stop class="bqaby2bzq"/><stop offset=".37" class="hxfvufi0i"/><stop offset=".778" class="hxfvufi0i"/><stop offset="1" class="bqaby2bzq"/></linearGradient><linearGradient id="iKhOX5d" x1="25.351" x2="23.553" y1="27.521" y2="29.293" gradientUnits="userSpaceOnUse"><stop class="bqaby2bzq"/><stop offset=".37" class="hxfvufi0i"/><stop offset=".778" class="hxfvufi0i"/><stop offset="1" class="bqaby2bzq"/></linearGradient><linearGradient id="infXmad" x1="11.501" x2="12.985" y1="28.905" y2="27.468" gradientUnits="userSpaceOnUse"><stop class="bqaby2bzq"/><stop offset="1" class="hxfvufi0i"/></linearGradient><linearGradient id="ixarMEc" x1="14.554" x2="15.898" y1="13.692" y2="14.046" gradientUnits="userSpaceOnUse"><stop class="x37zrlbcp"/><stop offset="1" class="u2e3rxbtp"/></linearGradient><linearGradient id="i1X4Lnd" x1="20.219" x2="17.6" y1="6.254" y2="6.118" gradientUnits="userSpaceOnUse"><stop class="egm-dub4f"/><stop offset="1" class="zhwoohbuw"/></linearGradient><linearGradient id="iyYKxQb" x1="18.299" x2="18.469" y1="5.092" y2="5.147" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="stui2mbih"/></linearGradient><linearGradient id="iCu7Tue" x1="25.572" x2="24.369" y1="6.015" y2="5.78" gradientUnits="userSpaceOnUse"><stop class="sputfhdoz"/><stop offset="1" class="x91xhsboa"/></linearGradient><linearGradient id="iUHIUpb" x1="23.807" x2="23.994" y1="7.102" y2="5.827" gradientUnits="userSpaceOnUse"><stop class="zeqefbvfd"/><stop offset="1" class="aetcf802l"/></linearGradient><linearGradient id="ieEEZBA" x1="10.023" x2="14.773" y1="23.046" y2="14.64" gradientUnits="userSpaceOnUse"><stop offset=".047" class="x9-imyafb"/><stop offset="1" class="uu4nvia_s"/></linearGradient><linearGradient id="ijGOome" x1="20.866" x2="20.366" y1="9.171" y2="12.452" gradientUnits="userSpaceOnUse"><stop class="hlxv8_5xa"/><stop offset="1" class="ulf1gwuyj"/></linearGradient><filter id="iXztjAe" width="15.582" height="10.819" x="5.713" y="14.797" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.309804 0 0 0 0 0.223529 0 0 0 0 0.32549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_386"/></filter><filter id="iVEajnV" width="6.441" height="2.956" x="5.508" y="23.497" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.203922 0 0 0 0 0.133333 0 0 0 0 0.286275 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_386"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".15"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.14902 0 0 0 0 0.14902 0 0 0 0 0.196078 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_386" result="effect2_innerShadow_4002_386"/></filter><filter id="iXH27rv" width="5.567" height="2.356" x="5.933" y="23.797" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_386" stdDeviation=".075"/></filter><filter id="i1akbib" width="4.441" height="3.418" x="10.858" y="23.287" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.74902 0 0 0 0 0.109804 0 0 0 0 0.27451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_386"/></filter><filter id="igW0exb" width="4.535" height="3.468" x="21.807" y="23.236" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.764706 0 0 0 0 0.145098 0 0 0 0 0.301961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_386"/></filter><filter id="igiwmpe" width="4.718" height="10.273" x="20.506" y="8.124" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy=".3"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.145098 0 0 0 0 0.223529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_386"/></filter><filter id="i18aZ8c" width="11.844" height="3.289" x="12.729" y="17.848" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.294118 0 0 0 0 0.133333 0 0 0 0 0.356863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_386"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.278431 0 0 0 0 0.184314 0 0 0 0 0.317647 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_386" result="effect2_innerShadow_4002_386"/></filter><filter id="ip2cPFd" width="7.15" height="1.822" x="17.065" y="14.664" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.231373 0 0 0 0 0.137255 0 0 0 0 0.372549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_386"/></filter><filter id="ibRT17c" width="3.042" height="3.242" x="11.275" y="26.823" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.466667 0 0 0 0 0.337255 0 0 0 0 0.588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_386"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.537255 0 0 0 0 0.494118 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_386" result="effect2_innerShadow_4002_386"/></filter><filter id="idS3AIW" width="3.042" height="3.242" x="22.932" y="26.823" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.466667 0 0 0 0 0.337255 0 0 0 0 0.588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_386"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.537255 0 0 0 0 0.494118 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_386" result="effect2_innerShadow_4002_386"/></filter><filter id="iACSlMk" width=".953" height=".953" x="12.295" y="28.042" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.239216 0 0 0 0 0.203922 0 0 0 0 0.294118 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_386"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.258824 0 0 0 0 0.247059 0 0 0 0 0.298039 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_386" result="effect2_innerShadow_4002_386"/></filter><filter id="i8TNtvb" width=".953" height=".953" x="23.951" y="28.042" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.239216 0 0 0 0 0.203922 0 0 0 0 0.294118 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_386"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.258824 0 0 0 0 0.247059 0 0 0 0 0.298039 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_386" result="effect2_innerShadow_4002_386"/></filter><filter id="iafDH8b" width="9.072" height="5.925" x="14.052" y="21.905" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".3"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.666667 0 0 0 0 0.0392157 0 0 0 0 0.180392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_386"/></filter><filter id="iIatJWd" width="5.213" height="5.612" x="16.068" y="24.552" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.4"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.466667 0 0 0 0 0.337255 0 0 0 0 0.588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_386"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".15"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.537255 0 0 0 0 0.494118 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_386" result="effect2_innerShadow_4002_386"/></filter><filter id="ibQvEQd" width="4.858" height="4.858" x="16.271" y="24.954" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_386" stdDeviation=".125"/></filter><filter id="iTfD0Tb" width="2.743" height="2.743" x="23.129" y="27.095" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_386" stdDeviation=".075"/></filter><filter id="ikeQliR" width="4.351" height="5.782" x="18.123" y="8.225" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_386" stdDeviation=".5"/></filter><filter id="i6k61ne" width="2.743" height="2.743" x="11.4" y="27.095" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_386" stdDeviation=".075"/></filter><filter id="iugBmXc" width="1.474" height="1.474" x="17.862" y="26.746" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.239216 0 0 0 0 0.203922 0 0 0 0 0.294118 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_386"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.258824 0 0 0 0 0.247059 0 0 0 0 0.298039 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_386" result="effect2_innerShadow_4002_386"/></filter><filter id="i67FoxQ" width="7.234" height="2.726" x="14.177" y="12.229" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.67451 0 0 0 0 0.423529 0 0 0 0 0.0901961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_386"/></filter><filter id="iGjo8Gc" width="1.984" height="1.537" x="13.714" y="13.497" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.898039 0 0 0 0 0.647059 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_386"/></filter><filter id="iyObIub" width="1.948" height="1.321" x="14.102" y="13.928" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.788235 0 0 0 0 0.541176 0 0 0 0 0.133333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_386"/></filter><filter id="iTr72ve" width="4.306" height="4.907" x="17.392" y="3.316" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.909804 0 0 0 0 0.52549 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_386"/></filter><filter id="iUP7xmc" width="4.99" height="5.384" x="17.934" y="1.945" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.607843 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_386"/></filter><filter id="iiydiDe" width=".915" height=".586" x="18.307" y="4.231" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.682353 0 0 0 0 0.219608 0 0 0 0 0.133333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_386"/></filter><filter id="iMLnRQb" width="5.063" height="8.469" x="9.179" y="15.421" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_386" stdDeviation=".25"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-in-motorized-wheelchair" /></template>
<style>
.a-xw_r42a {
  stop-color: var(--svg-color--e37f3a, #E37F3A);
}

.aafld1b5m {
  stop-color: var(--svg-color--64576e, #64576E);
}

.admd7db0k {
  stop-color: var(--svg-color--ffab1d, #FFAB1D);
  stop-opacity: 0;
}

.aetcf802l {
  stop-color: var(--svg-color--492f60, #492F60);
  stop-opacity: 0;
}

.afgvi4b_x {
  d: path("M19.123 6.959h1.914v2.752h-1.914z");
}

.afjbg56bb {
  cx: 12.771px;
  cy: 28.519px;
  r: 0.377px;
  fill: var(--svg-color--3e384b, #3E384B);
}

.ajt-21bdu {
  stop-color: var(--svg-color--3a183a, #3A183A);
}

.an20q5kfx {
  stop-color: var(--svg-color--e0a531, #E0A531);
}

.aqa9dgbyv {
  d: path("m19.666 10.07l-.263 2.527c.688 0 1.692.101 2.07.172c.075-.523.233-1.725.274-2.355c.052-.789-.17-1.099-.424-1.268a1 1 0 0 0-1.083 0c-.39.24-.545.716-.574.925");
}

.at42zcbhv {
  stop-color: var(--svg-color--e75c22, #E75C22);
  stop-opacity: 0;
}

.auog_xb1g {
  cx: 15.212px;
  cy: 16.709px;
  r: 0.794px;
}

.aur13kbnc {
  stop-color: var(--svg-color--5a4a71, #5A4A71);
  stop-opacity: 0;
}

.b-3vnvcpj {
  stop-color: var(--svg-color--565476, #565476);
  stop-opacity: 0;
}

.b37qgpujw {
  stop-color: var(--svg-color--f24147, #F24147);
  stop-opacity: 0;
}

.b3dj2bied {
  stop-color: var(--svg-color--c7b9d7, #C7B9D7);
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

.br13rubgx {
  d: path("m11.28 25.156l3.058-1.72l.961 3.269h-3.62a.827.827 0 0 1-.4-1.549");
}

.bu0v-9rgl {
  stop-color: var(--svg-color--776287, #776287);
  stop-opacity: 0;
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

.cfhwg-9zy {
  stop-color: var(--svg-color--422d5a, #422D5A);
  stop-opacity: 0;
}

.clzavdftr {
  stop-color: var(--svg-color--5e4e70, #5E4E70);
}

.cpg4-bb7y {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M12.772 29.612a1.146 1.146 0 1 0 0-2.292a1.146 1.146 0 0 0 0 2.292Z");
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

.d7kch3t0q {
  stop-color: var(--svg-color--ffab1d, #FFAB1D);
}

.d9q4mwzxt {
  stop-color: var(--svg-color--5c5166, #5C5166);
}

.dqw_0wbtq {
  stop-color: var(--svg-color--ec972b, #EC972B);
}

.ds-9iibtp {
  cx: 15.212px;
  cy: 14.813px;
  r: 0.518px;
}

.dt2-hrbth {
  stop-color: var(--svg-color--2b2731, #2B2731);
}

.e14bc-vgp {
  stop-color: var(--svg-color--ab556a, #AB556A);
  stop-opacity: 0;
}

.e9_lu_tkl {
  stop-color: var(--svg-color--685977, #685977);
}

.ea3nq_bza {
  cx: 24.428px;
  cy: 28.519px;
  r: 0.894px;
}

.ebki_vbdj {
  stop-color: var(--svg-color--e4355d, #E4355D);
}

.ebu-sjblb {
  stop-color: var(--svg-color--ea9c22, #EA9C22);
  stop-opacity: 0;
}

.egm-dub4f {
  stop-color: var(--svg-color--ffc33e, #FFC33E);
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

.ewip82vxi {
  stop-color: var(--svg-color--56426b, #56426B);
  stop-opacity: 0;
}

.f6z4yi_ag {
  stop-color: var(--svg-color--dd2f40, #DD2F40);
}

.fj67tibom {
  stop-color: var(--svg-color--ffd537, #FFD537);
  stop-opacity: 0;
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

.g1l-ujbgf {
  cx: 18.599px;
  cy: 27.483px;
  r: 1.512px;
}

.g6je8pe2z {
  stop-color: var(--svg-color--ffd237, #FFD237);
  stop-opacity: 0;
}

.gb6cd3sju {
  stop-color: var(--svg-color--4b3c57, #4B3C57);
  stop-opacity: 0;
}

.gfvzkzeir {
  d: path("m16.73 15.022l3.792 3.118l1.44-8.172c-.196-1.362-1.875-1.576-2.518-1.507c-.642.068-1.37.437-1.875 1.978c-.405 1.234-.728 3.57-.84 4.583");
}

.gg7le5bub {
  stop-color: var(--svg-color--976635, #976635);
}

.golah4bmm {
  stop-color: var(--svg-color--db4459, #DB4459);
}

.gv3iwdbvq {
  stop-color: var(--svg-color--666361, #666361);
}

.gxhbeh9zc {
  stop-color: var(--svg-color--483962, #483962);
}

.gzc_qccoq {
  stop-color: var(--svg-color--3e3e6c, #3E3E6C);
}

.hlkhhwb3q {
  stop-color: var(--svg-color--f24147, #F24147);
}

.hlxv8_5xa {
  stop-color: var(--svg-color--e08018, #E08018);
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

.hze7fms1a {
  stop-color: var(--svg-color--ffbf27, #FFBF27);
  stop-opacity: 0;
}

.i00c46bgu {
  stop-color: var(--svg-color--4b3c57, #4B3C57);
}

.i8rkxoa5u {
  stop-color: var(--svg-color--832538, #832538);
}

.id6hb3b7i {
  stop-color: var(--svg-color--b11943, #B11943);
}

.ie8_agh2b {
  stop-color: var(--svg-color--3e3e6c, #3E3E6C);
  stop-opacity: 0;
}

.ie8nvs_jh {
  fill: var(--svg-color--5e4f7f, #5E4F7F);
  d: path("M13.944 17.278a.5.5 0 0 1 .5-.5h1.549a.5.5 0 0 1 .5.5v.82h-2.549z");
}

.ihz8r9bpq {
  stop-color: var(--svg-color--535154, #535154);
}

.ijfe69bnq {
  d: path("M24.187 26.315h.471v1.492h-.471z");
}

.imo1scbvv {
  fill-rule: evenodd;
  d: path("M24.428 30.015a1.496 1.496 0 1 0 0-2.993a1.496 1.496 0 0 0 0 2.993m0-.603a.894.894 0 1 0 0-1.787a.894.894 0 0 0 0 1.787");
}

.ipohnfkvg {
  stop-color: var(--svg-color--5a4a71, #5A4A71);
}

.itdceeb_q {
  cx: 18.599px;
  cy: 27.483px;
  r: 0.637px;
  fill: var(--svg-color--3e384b, #3E384B);
}

.j3tnzsbnn {
  d: path("M12.536 26.315h.471v1.492h-.471z");
}

.j5-6p70xh {
  stop-color: var(--svg-color--908893, #908893);
}

.jejfpy4sc {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M24.5 29.612a1.146 1.146 0 1 0 0-2.292a1.146 1.146 0 0 0 0 2.292Z");
}

.jid13cbfr {
  d: path("M10.53 24.271c-.196.485-.388.943-.567 1.346c-1.097-.411-4-1.833-4-1.833c.02-.163.217-.526.848-.677c.63-.15 2.033-.131 2.655-.103c0-.006.48.55 1.065 1.267");
}

.jkk-xsb9b {
  stop-color: var(--svg-color--ffd237, #FFD237);
}

.jqu95-b8t {
  stop-color: var(--svg-color--574568, #574568);
}

.jrtayobva {
  fill: var(--svg-color--55416a, #55416A);
  d: path("M21.96 9.296a1.4 1.4 0 0 1 1.382-1.172h.182a1.4 1.4 0 0 1 1.38 1.628l-1.378 8.346h-3.02z");
}

.jsdt5e8xl {
  stop-color: var(--svg-color--64597c, #64597C);
}

.jvia9sbhc {
  d: path("M18.086 2.532c.266-.418.786-.467 1.037-.424c.776.13.852.412 1.575.346c.764-.07 1.127.016 1.43.197l.006.004c.299.178.917.548.767 1.881c-.138 1.228-.65 1.828-.887 2.036l.04.02c.201.099.263.333.163.535c-.085.172-.324.25-.605.172c-.322-.088-.557-.16-.741-.219a.23.23 0 0 1-.157-.242l.114-1.011a.9.9 0 0 0-.347-.805c.035-.442-.077-.66-.285-.79c-.345-.218-.468-.144-1.333-.295c-.917-.16-1.109-.881-.777-1.405");
}

.jzl720bvd {
  stop-color: var(--svg-color--816d8d, #816D8D);
}

.k8klmcqbt {
  stop-color: var(--svg-color--645381, #645381);
}

.ka6kobc6f {
  stop-color: var(--svg-color--474652, #474652);
  stop-opacity: 0;
}

.kegmapbvr {
  stop-color: var(--svg-color--5c5166, #5C5166);
  stop-opacity: 0;
}

.kgio6d1ee {
  stop-color: var(--svg-color--ffa526, #FFA526);
  stop-opacity: 0;
}

.kh4so6bgt {
  stop-color: var(--svg-color--404047, #404047);
  stop-opacity: 0;
}

.kikr0z55d {
  cx: 15.212px;
  cy: 14.813px;
  r: 0.518px;
  fill: var(--svg-color--4a2a60, #4A2A60);
}

.l056r-bgv {
  cx: 24.428px;
  cy: 28.519px;
  r: 0.377px;
  fill: var(--svg-color--3e384b, #3E384B);
}

.l0aricxam {
  stop-color: var(--svg-color--916a62, #916A62);
}

.l1p2lzbva {
  d: path("m14.487 26.654l-.426-3.4a1.2 1.2 0 0 1 1.191-1.349h6.672a1.2 1.2 0 0 1 1.191 1.343l-.406 3.4a1 1 0 0 1-.993.882H15.48a1 1 0 0 1-.992-.876");
}

.lhdv8ibog {
  stop-color: var(--svg-color--94161a, #94161A);
  stop-opacity: 0;
}

.lnbhqzbme {
  d: path("m10.71 17.983l-1.031 5.078l.344.329l1.718-5.875h2V15.92l-1.281.156c-1.125.125-1.636 1.323-1.75 1.906");
}

.lnt0jpotc {
  fill: var(--svg-color--87014d, #87014D);
  fill-rule: evenodd;
  d: path("M18.733 6.517c.04.05.03.121-.02.16c-.24.188-.559.207-.66.206a.114.114 0 0 1 .003-.228c.086 0 .34-.019.517-.158a.114.114 0 0 1 .16.02");
}

.lrd0xzbnc {
  cx: 12.771px;
  cy: 28.519px;
  r: 0.894px;
}

.ls7oj_z4s {
  fill: var(--svg-color--857d8e, #857D8E);
  fill-rule: evenodd;
  d: path("M18.6 30.015a2.531 2.531 0 1 0 0-5.063a2.531 2.531 0 0 0 0 5.063m0-1.02a1.512 1.512 0 1 0 0-3.023a1.512 1.512 0 0 0 0 3.023");
}

.lw64igb3q {
  fill: var(--svg-color--f0303e, #F0303E);
  d: path("m25.92 25.156l-3.059-1.72l-1.054 3.269h3.714a.827.827 0 0 0 .399-1.549");
}

.lzxtmdbfr {
  stop-color: var(--svg-color--4a3a4c, #4A3A4C);
}

.m_reoz2pl {
  fill: var(--svg-color--ffc136, #FFC136);
  d: path("m19.466 12.937l.062-.5a5.2 5.2 0 0 1 1.883.265c-.01.164-.05.597-.125 1.016c-.094.523-.367 1.183-1.633 1.23c-1.265.047-3.468-.152-3.726-.222a2 2 0 0 0-.531-.063l-.97-.555c-.194.07-.374-.187-.132-.39c.325-.281.98-.326 1.266-.313c1.125-.387 3.073-.474 3.906-.468");
}

.ma5b9zegf {
  stop-color: var(--svg-color--9c83b4, #9C83B4);
}

.mcd03_b4y {
  stop-color: var(--svg-color--ab556a, #AB556A);
}

.mnv88fh6g {
  d: path("M13.944 17.278a.5.5 0 0 1 .5-.5h1.549a.5.5 0 0 1 .5.5v.82h-2.549z");
}

.ms0rob30e {
  stop-color: var(--svg-color--58426e, #58426E);
  stop-opacity: 0;
}

.mykl6fbtk {
  stop-color: var(--svg-color--564778, #564778);
}

.n0wdiubea {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("m6.158 24.023l3.89 1.906h1.227");
}

.n2o4e_51w {
  fill: var(--svg-color--55426a, #55426A);
  d: path("M22.882 3.897a1.2 1.2 0 0 1 1.391-.972l.565.1a1.2 1.2 0 0 1 .972 1.39l-.3 1.696a1.2 1.2 0 0 1-1.39.972l-.566-.1a1.2 1.2 0 0 1-.972-1.39z");
}

.n9r91ylyy {
  stop-color: var(--svg-color--824d44, #824D44);
}

.nbyzmw_ck {
  stop-color: var(--svg-color--b52f5e, #B52F5E);
}

.nc_ezabaa {
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M18.7 29.412a2.029 2.029 0 1 0 0-4.058a2.029 2.029 0 0 0 0 4.058Z");
}

.nhtvs4bus {
  stop-color: var(--svg-color--db4459, #DB4459);
  stop-opacity: 0;
}

.o7v7nujms {
  stop-color: var(--svg-color--b92c31, #B92C31);
  stop-opacity: 0;
}

.oq29cacqb {
  fill: var(--svg-color--fff, #fff);
  d: path("m18.17 5.428l.898.102c.04-.356-.128-.667-.377-.695c-.247-.028-.481.238-.521.593");
}

.oqbmkuz2v {
  fill: var(--svg-color--e44d1f, #E44D1F);
  d: path("m19.386 10.31l-.262 2.525c.687 0 1.69.101 2.07.172c.074-.522.232-1.725.274-2.355c.05-.788-.17-1.099-.424-1.268a1 1 0 0 0-1.084 0c-.39.24-.545.717-.574.925");
}

.oxa-zpnbc {
  d: path("M14.924 15.124h.578v1.285h-.578z");
}

.oyu5u8bov {
  fill: var(--svg-color--af5247, #AF5247);
  fill-rule: evenodd;
  d: path("M18.742 4.542a.7.7 0 0 0-.196-.036a.137.137 0 0 1-.003-.275a1 1 0 0 1 .282.05a.94.94 0 0 1 .353.2a.137.137 0 1 1-.186.2a.7.7 0 0 0-.25-.139");
}

.p2cn_nwxs {
  cx: 18.364px;
  cy: 5.126px;
  rx: 0.059px;
  ry: 0.08px;
}

.p8hc-w2ji {
  stop-color: var(--svg-color--746e6d, #746E6D);
}

.pae25fhsd {
  d: path("M16.182 20.749h4.836v1.273h-4.836z");
}

.pbwaenbxo {
  d: path("m25.92 25.156l-3.059-1.72l-1.054 3.269h3.714a.827.827 0 0 0 .399-1.549");
}

.pbwt4gb4m {
  stop-color: var(--svg-color--675876, #675876);
  stop-opacity: 0;
}

.pe6w2ixsr {
  fill: var(--svg-color--fbbf3c, #FBBF3C);
  d: path("M14.164 14.776c.417-.495.921-.668 1.13-.707c.223-.062.651-.075.726.121a.43.43 0 0 1-.062.418a1.95 1.95 0 0 0-1.32.55a.32.32 0 0 1-.442.005a.284.284 0 0 1-.032-.387");
}

.pg0gw1osm {
  stop-color: var(--svg-color--e39c2d, #E39C2D);
}

.pngn0fmrc {
  fill: var(--svg-color--857d8e, #857D8E);
  fill-rule: evenodd;
  d: path("M24.428 30.015a1.496 1.496 0 1 0 0-2.993a1.496 1.496 0 0 0 0 2.993m0-.603a.894.894 0 1 0 0-1.787a.894.894 0 0 0 0 1.787");
}

.pnj03optx {
  d: path("M17.79 4.655c.118-.724.393-1.049.516-1.139l3.392.383l-.267 2.881c-1.005 1.84-3.418 1.652-3.699.914s-.077-2.2.059-3.039");
}

.pwpzq7byn {
  stop-color: var(--svg-color--e75c22, #E75C22);
}

.r-y-1acck {
  cx: 22.508px;
  cy: 15.693px;
  r: 0.475px;
  fill: var(--svg-color--3e3a4a, #3E3A4A);
}

.rbdcwebfp {
  cx: 12.771px;
  cy: 28.519px;
  r: 1.496px;
  fill: var(--svg-color--857d8e, #857D8E);
}

.re8izvbqw {
  stop-color: var(--svg-color--ffa526, #FFA526);
}

.rfxr5lvvz {
  stop-color: var(--svg-color--cc3437, #CC3437);
  stop-opacity: 0;
}

.ronnvab4v {
  stop-color: var(--svg-color--211b2c, #211B2C);
}

.rtjr-xb4t {
  stop-color: var(--svg-color--c99223, #C99223);
  stop-opacity: 0;
}

.rw_zanbli {
  d: path("M17.065 15.514a.7.7 0 0 1 .7-.7h6.3l-.274 1.671h-6.026a.7.7 0 0 1-.7-.7z");
}

.rzgv5-bix {
  width: 0.619px;
  height: 2.008px;
  x: 23.613px;
  y: 6.619px;
  rx: 0.31px;
}

.scqcqwblc {
  stop-color: var(--svg-color--7d7172, #7D7172);
}

.sd26nmbri {
  cx: 12.771px;
  cy: 28.519px;
  r: 1.496px;
}

.seor_02fd {
  stop-color: var(--svg-color--422d5a, #422D5A);
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

.t4jg6lbel {
  stop-color: var(--svg-color--ed9721, #ED9721);
}

.t4k8t2b9t {
  stop-color: var(--svg-color--94161a, #94161A);
}

.t5jak8x3h {
  stop-color: var(--svg-color--e4af34, #E4AF34);
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

.tidy9bped {
  d: path("M17.489 5.508a.9.9 0 0 0 .28-.389l.164.019l-.115 1.022c-.21.102-.486.051-.548-.144c-.053-.168.022-.361.219-.508");
}

.tnj2m0let {
  fill-rule: evenodd;
  d: path("M5.697 23.857a.375.375 0 0 1 .502-.17l3.788 1.864l.01.003h1.427a.375.375 0 0 1 0 .75H9.998a.8.8 0 0 1-.343-.08L5.868 24.36a.375.375 0 0 1-.17-.502");
}

.trlm7mbbt {
  width: 11.844px;
  height: 2.839px;
  x: 12.729px;
  y: 18.098px;
  fill: var(--svg-color--58426f, #58426F);
  rx: 0.5px;
}

.txm_4ebvw {
  fill: var(--svg-color--ffba23, #FFBA23);
  d: path("M18.086 2.532c.266-.418.786-.467 1.037-.424c.776.13.852.412 1.575.346c.764-.07 1.127.016 1.43.197l.006.004c.299.178.917.548.767 1.881c-.138 1.228-.65 1.828-.887 2.036l.04.02c.201.099.263.333.163.535c-.085.172-.324.25-.605.172c-.322-.088-.557-.16-.741-.219a.23.23 0 0 1-.157-.242l.114-1.011a.9.9 0 0 0-.347-.805c.035-.442-.077-.66-.285-.79c-.345-.218-.468-.144-1.333-.295c-.917-.16-1.109-.881-.777-1.405");
}

.u0-djrvhx {
  stop-color: var(--svg-color--ffd537, #FFD537);
}

.u2e3rxbtp {
  stop-color: var(--svg-color--f3bc3a, #F3BC3A);
  stop-opacity: 0;
}

.u9mcm6llv {
  stop-color: var(--svg-color--565476, #565476);
}

.ubyl24bdb {
  stop-color: var(--svg-color--565352, #565352);
}

.uclk6dbhm {
  fill: var(--svg-color--4c477e, #4C477E);
  d: path("M10.53 24.271c-.196.485-.388.943-.567 1.346c-1.097-.411-4-1.833-4-1.833c.02-.163.217-.526.848-.677c.63-.15 2.033-.131 2.655-.103c0-.006.48.55 1.065 1.267");
}

.uevlegbhj {
  stop-color: var(--svg-color--5b4874, #5B4874);
  stop-opacity: 0;
}

.ulf1gwuyj {
  stop-color: var(--svg-color--eb6425, #EB6425);
}

.uu4nvia_s {
  stop-color: var(--svg-color--958d9a, #958D9A);
  stop-opacity: 0;
}

.ux0of3-jj {
  stop-color: var(--svg-color--e2305a, #E2305A);
  stop-opacity: 0;
}

.uxyvsjboq {
  d: path("M21.96 9.296a1.4 1.4 0 0 1 1.382-1.172h.182a1.4 1.4 0 0 1 1.38 1.628l-1.378 8.346h-3.02z");
}

.v4yb5cu8i {
  stop-color: var(--svg-color--695b77, #695B77);
}

.vahp-bcdd {
  stop-color: var(--svg-color--e37f3a, #E37F3A);
  stop-opacity: 0;
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.vj-cg71dv {
  fill: var(--svg-color--3b3349, #3B3349);
  fill-rule: evenodd;
  d: path("M5.697 23.857a.375.375 0 0 1 .502-.17l3.788 1.864l.01.003h1.427a.375.375 0 0 1 0 .75H9.998a.8.8 0 0 1-.343-.08L5.868 24.36a.375.375 0 0 1-.17-.502");
}

.vq556dbac {
  d: path("M18.72 5.49v-.004c.033-.29-.066-.54-.22-.558c-.153-.017-.304.205-.337.495v.004z");
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

.w3cjn9brj {
  d: path("M22.882 3.897a1.2 1.2 0 0 1 1.391-.972l.565.1a1.2 1.2 0 0 1 .972 1.39l-.3 1.696a1.2 1.2 0 0 1-1.39.972l-.566-.1a1.2 1.2 0 0 1-.972-1.39z");
}

.wjw662jrg {
  stop-color: var(--svg-color--321d4a, #321D4A);
}

.wode0hb4p {
  fill: var(--svg-color--fbbf3c, #FBBF3C);
  d: path("M13.761 14.585c.367-.533.853-.754 1.057-.812c.215-.083.641-.137.735.051a.43.43 0 0 1-.023.422a1.95 1.95 0 0 0-1.261.675a.32.32 0 0 1-.44.047a.284.284 0 0 1-.068-.383");
}

.wy93f33rd {
  d: path("m18.542 5.47l.011-.065c.019-.169-.037-.313-.125-.323s-.175.118-.194.287l-.004.066z");
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

.xd_rxccdu {
  stop-color: var(--svg-color--ed9721, #ED9721);
  stop-opacity: 0;
}

.xh4g4qbuv {
  stop-color: var(--svg-color--e0a531, #E0A531);
  stop-opacity: 0;
}

.xkzs54_ul {
  stop-color: var(--svg-color--4d487f, #4D487F);
  stop-opacity: 0;
}

.xq7qudg4u {
  d: path("M20.158 6.265c-.046-.005-.073-.05-.061-.095l.283-1.109c.013-.054.069-.087.12-.064a.665.665 0 0 1-.342 1.268");
}

.xs80ogben {
  stop-color: var(--svg-color--6b6080, #6B6080);
}

.xxg5o4foh {
  d: path("m12.85 15.527l3.914-.48l4.53 3.426h-8.582s-1.636 4.634-2.75 7.144c-1.096-.411-4-1.833-4-1.833c.02-.163.218-.526.849-.677c.63-.15 2.033-.131 2.655-.103c.117-.825.439-2.956.788-4.882s1.876-2.532 2.595-2.595");
}

.y05dlfbsr {
  stop-color: var(--svg-color--5b4874, #5B4874);
}

.ybejupycn {
  stop-color: var(--svg-color--b92c31, #B92C31);
}

.yu1mih4mu {
  stop-color: var(--svg-color--9c1a55, #9C1A55);
}

.yxnjz7r7g {
  stop-color: var(--svg-color--c54169, #C54169);
  stop-opacity: 0;
}

.z1-difb5b {
  stop-color: var(--svg-color--c54169, #C54169);
}

.z4_9uopis {
  fill: var(--svg-color--ec7f2f, #EC7F2F);
  d: path("m16.73 15.022l3.792 3.118l1.44-8.172c-.196-1.362-1.875-1.576-2.518-1.507c-.642.068-1.37.437-1.875 1.978c-.405 1.234-.728 3.57-.84 4.583");
}

.z6top7alb {
  stop-color: var(--svg-color--411d01, #411D01);
}

.zdh48sb9s {
  stop-color: var(--svg-color--816d8d, #816D8D);
  stop-opacity: 0;
}

.zeqefbvfd {
  stop-color: var(--svg-color--321c43, #321C43);
}

.zh7fl7z_h {
  width: 11.844px;
  height: 2.839px;
  x: 12.729px;
  y: 18.098px;
  rx: 0.5px;
}

.zhngqmnyt {
  d: path("m19.466 12.937l.062-.5a5.2 5.2 0 0 1 1.883.265c-.01.164-.05.597-.125 1.016c-.094.523-.367 1.183-1.633 1.23c-1.265.047-3.468-.152-3.726-.222a2 2 0 0 0-.531-.063l-.97-.555c-.194.07-.374-.187-.132-.39c.325-.281.98-.326 1.266-.313c1.125-.387 3.073-.474 3.906-.468");
}

.zhwoohbuw {
  stop-color: var(--svg-color--ffc247, #FFC247);
}

</style>
