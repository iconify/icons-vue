<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iIOckwd)"><rect fill="url(#iIk56Pc)" transform="rotate(-45 12.963 13.403)" class="etm0labvf"/></g><g filter="url(#ipGEO4b)"><rect fill="url(#i96BfVc)" transform="scale(-1 1)rotate(-45 -3.014 35.5)" class="ffese-y7m"/></g><rect fill="url(#iIRexfS)" transform="scale(-1 1)rotate(-45 -3.014 35.5)" class="ffese-y7m"/><g filter="url(#iZftjmc)"><path fill="url(#im3tg0d)" class="is89u6ban"/><path fill="url(#iX1BTZW)" class="is89u6ban"/></g><g filter="url(#iCoLqAA)"><rect fill="url(#i8mbSfd)" transform="scale(-1 1)rotate(-45 6.585 29.734)" class="z_5s59bdn"/></g><g filter="url(#ihA7opd)"><path class="g11vnob-s"/></g><g filter="url(#il9l0Ed)"><path class="ytl8wkbiv"/></g><g filter="url(#i3NISle)"><path class="s99p66ikg"/></g><g filter="url(#iu91LJd)"><path class="pv3dgeoha"/></g><g filter="url(#i4LDBWG)"><rect class="r9m8_svvg"/><rect fill="url(#iDG4Gmd)" class="nl4f7twra"/></g><g filter="url(#ia6enGc)"><path fill="url(#ioitlCc)" class="oa3f9ve3k"/></g><path fill="url(#i5Ao9Gd)" class="oa3f9ve3k"/><path fill="url(#i8KfH3d)" class="oa3f9ve3k"/><path fill="url(#iEdEbnd)" class="oa3f9ve3k"/><path class="a_g2v1e7w"/><path fill="url(#i5syKFD)" class="burjw8bvx"/><path fill="url(#ix4g9SG)" class="burjw8bvx"/><path fill="url(#i83V28c)" class="burjw8bvx"/><path fill="url(#iJXRjGd)" class="burjw8bvx"/><path fill="url(#iHjBAxX)" class="burjw8bvx"/><path class="e593k4bfv"/><path fill="url(#i7QnpSd)" class="xhtzkfsjn"/><path fill="url(#iJU4nte)" class="xhtzkfsjn"/><path fill="url(#ir07lqp)" class="m0kz_y80u"/><path fill="url(#is9Nicg)" class="m0kz_y80u"/><path fill="url(#iVXCTAc)" class="m0kz_y80u"/><path fill="url(#iZTxnje)" class="m0kz_y80u"/><path fill="url(#iR15onA)" class="eayua2tob"/><path fill="url(#iDv7Hjb)" class="eayua2tob"/><g filter="url(#iWinbce)"><path class="axzx4newn"/><path fill="url(#iC59Lpc)" class="b47wb-b1b"/><path fill="url(#iznQ8ib)" class="b47wb-b1b"/></g><path fill="url(#iFc3g8a)" class="z45oacyxz"/><path fill="url(#ihvNS4d)" class="z45oacyxz"/><circle fill="url(#iLjKZQG)" class="z30kudb-o"/><g filter="url(#iEGKK5b)"><path class="f6xfjgb1y"/><path fill="url(#iCc4k6d)" class="k-27-x9ja"/></g><g filter="url(#icnGpDe)"><path class="e9b9gabbg"/><path fill="url(#iXb4XGc)" class="xgq6w0b8s"/><path fill="url(#iQj6ttd)" class="xgq6w0b8s"/></g><g filter="url(#irLYtDc)"><path class="vt36tzbwu"/></g><path fill="url(#icTBtvb)" class="m9o60j3-s"/><path fill="url(#iU8dDfc)" class="m9o60j3-s"/><path fill="url(#iTOjr5j)" class="m9o60j3-s"/><path fill="url(#iTSrjze)" class="m9o60j3-s"/><path fill="url(#i0yjX3b)" class="m9o60j3-s"/><path fill="url(#ikWexdb)" class="jic9bm_zi"/><path fill="url(#ihyddKX)" class="jic9bm_zi"/><g filter="url(#iFe3YEb)"><path stroke="url(#iAyTcBl)" class="saunobcmg"/></g><g filter="url(#iIZgrgb)"><path stroke="url(#iVusaPe)" class="ikgkim2qs"/></g><g filter="url(#iyuD9ge)"><path stroke="url(#iSuyLse)" class="zh46g387g"/></g><path fill="url(#ilgydLb)" class="ui2im5sxy"/><path fill="url(#iKoyZsb)" class="rpk2cqb3k"/><g filter="url(#ir4yw8e)"><path fill="url(#ioTu69c)" class="l1fas3zcg"/><path fill="url(#ieH1J6c)" class="l1fas3zcg"/></g><path fill="url(#iKeySVc)" class="l1fas3zcg"/><path fill="url(#iCnkRMc)" class="l1fas3zcg"/><path fill="url(#iYFwRtd)" class="l1fas3zcg"/><path fill="url(#iMq3oVc)" class="l1fas3zcg"/><path fill="url(#ibyX2dc)" class="l1fas3zcg"/><path fill="url(#ilNzW3c)" class="l1fas3zcg"/><path fill="url(#icqB8hb)" class="l1fas3zcg"/><g filter="url(#isyZx3c)"><path class="vjbiphb3e"/></g><g filter="url(#im6K2pc)"><path class="odpjwqbbc"/><path fill="url(#ibvlNNE)" class="dnli9p0qf"/><path fill="url(#iyJFImd)" class="dnli9p0qf"/><path fill="url(#ijuGDAd)" class="dnli9p0qf"/><path fill="url(#iHIbaDc)" class="dnli9p0qf"/><path fill="url(#i8Kf1Rp)" class="dnli9p0qf"/></g><g filter="url(#isgHbtc)"><path stroke="url(#i7kOwnd)" class="nfvol29vo"/></g><path fill="url(#iunMuRc)" class="rmw-9s7sx"/><g filter="url(#iOgNRxm)"><path fill="url(#ifULk3b)" class="sy1zgqbhn"/><path fill="url(#ism7N9d)" class="sy1zgqbhn"/><path fill="url(#iQFHp0R)" class="sy1zgqbhn"/><path fill="url(#i5o76Cm)" class="sy1zgqbhn"/><path fill="url(#iuKn5Xs)" class="sy1zgqbhn"/></g><g filter="url(#iHq6wUC)"><path class="v2d5x5b0b"/></g><g filter="url(#i4M1wZb)"><path class="g5dwguodp"/></g><g filter="url(#ipjIwKe)"><path class="k1-2mnnxu"/><path fill="url(#iGkOv8b)" class="diyc2abac"/><path fill="url(#iC1QSpf)" class="diyc2abac"/></g><g filter="url(#iORl7xe)"><path class="cz72ar2pi"/><path fill="url(#iTo0jcb)" class="kwow_3omf"/><path fill="url(#iDtOKpp)" class="kwow_3omf"/></g><path class="qrqkgk68o"/><path fill="url(#i6RoLle)" class="f4c48qbpa"/><path class="rrxj9bckx"/><g filter="url(#i4afJdd)"><path class="b5t1rjggp"/><path fill="url(#iX81axc)" class="m7qzf0bah"/></g><g filter="url(#iNzoZnb)"><path fill="url(#iNk0aMd)" class="kkcj50baa"/></g><path class="j4v0ojb2o"/><path fill="url(#iR9eqAe)" class="bdcjj-bzz"/><path class="xzzn0pbnc"/><g filter="url(#iIwdsMe)"><path fill="url(#ioWEwIe)" class="bk4v9v6pj"/></g><g filter="url(#iK5Vm2c)"><ellipse transform="rotate(-27.914 14.993 7.596)" class="dm7l30bog"/><ellipse fill="url(#iSxg34d)" transform="rotate(-27.914 14.993 7.596)" class="gtwdzjt0y"/></g><path fill="url(#incEv1N)" class="zchm_v6mk"/><path fill="url(#iTlhc8d)" class="zchm_v6mk"/><path fill="url(#iCZQsye)" class="zchm_v6mk"/><path fill="url(#i1KWcWd)" class="zchm_v6mk"/><path fill="url(#iFWNf7c)" class="xlr_mq0xb"/><path fill="url(#i3ZjXMb)" class="xlr_mq0xb"/><g filter="url(#i8ESLvJ)"><path fill="url(#ikkNube)" class="o7l-q1nix"/></g><g filter="url(#iymU89L)"><path fill="url(#ieIRJeH)" class="ghbnzyqzr"/></g><g filter="url(#iOpH9YS)" class="mc2zb0bvp"><path class="ckqr_ab5f"/></g><defs><radialGradient id="iIk56Pc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.87825 -2.80633 3.32449 -2.22505 16.838 21.301)" gradientUnits="userSpaceOnUse"><stop class="vvvf-bx0b"/><stop offset="1" class="rivz2obdn"/></radialGradient><radialGradient id="i96BfVc" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.75045 -10.1868 0 3.092 .28)" gradientUnits="userSpaceOnUse"><stop offset=".356" class="vm1_cbcaw"/><stop offset="1" class="k356i5yuc"/></radialGradient><radialGradient id="iIRexfS" cx="0" cy="0" r="1" gradientTransform="rotate(-58.508 8.125 5.097)scale(2.87644 1.6899)" gradientUnits="userSpaceOnUse"><stop offset=".419" class="uodqeubaz"/><stop offset="1" class="pha_6_rva"/></radialGradient><radialGradient id="i8mbSfd" cx="0" cy="0" r="1" gradientTransform="matrix(.46404 .88388 -1.60027 .84014 1.815 6.289)" gradientUnits="userSpaceOnUse"><stop class="x6_m96bez"/><stop offset="1" class="s2ceddo5o"/></radialGradient><radialGradient id="ioitlCc" cx="0" cy="0" r="1" gradientTransform="rotate(141.509 11.379 5.864)scale(3.31383 3.4775)" gradientUnits="userSpaceOnUse"><stop class="nw_aknb7y"/><stop offset="1" class="pt-h1ccpi"/></radialGradient><radialGradient id="i5Ao9Gd" cx="0" cy="0" r="1" gradientTransform="matrix(.35156 .89062 -.53122 .2097 23.216 2.575)" gradientUnits="userSpaceOnUse"><stop offset=".22" class="vw5e4lbve"/><stop offset="1" class="v_k-57lgf"/></radialGradient><radialGradient id="i8KfH3d" cx="0" cy="0" r="1" gradientTransform="rotate(78.781 8.915 17.107)scale(1.04377 .3506)" gradientUnits="userSpaceOnUse"><stop class="s_et88bec"/><stop offset="1" class="qlfye6p8o"/></radialGradient><radialGradient id="iEdEbnd" cx="0" cy="0" r="1" gradientTransform="matrix(-.6346 .22 -.12993 -.3748 24.731 3.528)" gradientUnits="userSpaceOnUse"><stop class="s_et88bec"/><stop offset="1" class="qlfye6p8o"/></radialGradient><radialGradient id="i5syKFD" cx="0" cy="0" r="1" gradientTransform="rotate(-105.819 17.69 2.831)scale(4.87202 1.60555)" gradientUnits="userSpaceOnUse"><stop class="ip469ff8c"/><stop offset="1" class="v0q_-i93u"/></radialGradient><radialGradient id="ix4g9SG" cx="0" cy="0" r="1" gradientTransform="matrix(1.34375 3.125 -1.0965 .4715 17.1 19.904)" gradientUnits="userSpaceOnUse"><stop offset=".17" class="sl-3t4bfx"/><stop offset="1" class="zeih87brn"/></radialGradient><radialGradient id="iJXRjGd" cx="0" cy="0" r="1" gradientTransform="matrix(-.07031 -.73437 .44794 -.04289 16.242 18.481)" gradientUnits="userSpaceOnUse"><stop class="c6dvfyb6s"/><stop offset="1" class="oz3_ipb8v"/></radialGradient><radialGradient id="iHjBAxX" cx="0" cy="0" r="1" gradientTransform="matrix(-.20312 2.82812 -.75946 -.05455 15.241 19.966)" gradientUnits="userSpaceOnUse"><stop class="xo-vurl-f"/><stop offset="1" class="un08nrbhl"/></radialGradient><radialGradient id="iVXCTAc" cx="0" cy="0" r="1" gradientTransform="matrix(-.26562 3.09375 -.85026 -.073 15.348 26.277)" gradientUnits="userSpaceOnUse"><stop offset=".085" class="j7smtkbjw"/><stop offset="1" class="xgtw6wrae"/></radialGradient><radialGradient id="iDv7Hjb" cx="0" cy="0" r="1" gradientTransform="matrix(-.07031 -.19922 1.40814 -.49699 14.503 29.465)" gradientUnits="userSpaceOnUse"><stop class="p5u-_cblu"/><stop offset="1" class="uowu7rarb"/></radialGradient><radialGradient id="iznQ8ib" cx="0" cy="0" r="1" gradientTransform="matrix(.46875 1.80469 -.96535 .25074 19.32 20.568)" gradientUnits="userSpaceOnUse"><stop offset=".091" class="fgis5qzvv"/><stop offset="1" class="blsn939-n"/></radialGradient><radialGradient id="ihvNS4d" cx="0" cy="0" r="1" gradientTransform="matrix(.28516 -.16406 .55035 .95656 16.253 27.216)" gradientUnits="userSpaceOnUse"><stop offset=".122" class="s3hklabia"/><stop offset="1" class="n5igrlbfw"/></radialGradient><radialGradient id="iLjKZQG" cx="0" cy="0" r="1" gradientTransform="matrix(.4375 .1914 -.31978 .73092 6.135 15.73)" gradientUnits="userSpaceOnUse"><stop class="qya8vwbkf"/><stop offset="1" class="d0qi1-blu"/></radialGradient><radialGradient id="iCc4k6d" cx="0" cy="0" r="1" gradientTransform="rotate(-38.729 27.876 -1.303)scale(8.09176 6.39568)" gradientUnits="userSpaceOnUse"><stop offset=".76" class="tj824objr"/><stop offset="1" class="lz6zpisqv"/></radialGradient><radialGradient id="iXb4XGc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.16876 .9375 -.156 -.19448 8.314 14.542)" gradientUnits="userSpaceOnUse"><stop class="gbuovhboa"/><stop offset="1" class="yq1j9wb8r"/></radialGradient><radialGradient id="iQj6ttd" cx="0" cy="0" r="1" gradientTransform="matrix(.8047 -.67969 .45175 .53484 7.442 15.269)" gradientUnits="userSpaceOnUse"><stop offset=".644" class="scofoabvh"/><stop offset="1" class="b4zzki-mx"/></radialGradient><radialGradient id="iTOjr5j" cx="0" cy="0" r="1" gradientTransform="matrix(-1.92712 .2574 -.06658 -.49847 15.194 10.709)" gradientUnits="userSpaceOnUse"><stop class="hq3hkib4c"/><stop offset="1" class="k_rioyb_p"/></radialGradient><radialGradient id="iTSrjze" cx="0" cy="0" r="1" gradientTransform="rotate(142.326 7.146 8.847)scale(1.55953 .89404)" gradientUnits="userSpaceOnUse"><stop class="ignt4ubkd"/><stop offset="1" class="hts433_5m"/></radialGradient><radialGradient id="i0yjX3b" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.67188 4.0767 0 18.1 15.544)" gradientUnits="userSpaceOnUse"><stop class="xnxf0re5w"/><stop offset="1" class="utdakeidf"/></radialGradient><radialGradient id="ikWexdb" cx="0" cy="0" r="1" gradientTransform="rotate(62.33 -1.095 17.766)scale(1.17765 2.48248)" gradientUnits="userSpaceOnUse"><stop class="qggerob2g"/><stop offset="1" class="pn9klvbrs"/></radialGradient><radialGradient id="ihyddKX" cx="0" cy="0" r="1" gradientTransform="rotate(160.1 7.47 6.92)scale(.87221 .42588)" gradientUnits="userSpaceOnUse"><stop class="wfj08-bsk"/><stop offset="1" class="k9wpgpx3v"/></radialGradient><radialGradient id="ilgydLb" cx="0" cy="0" r="1" gradientTransform="matrix(.32449 .87518 -1.03964 .38546 18.116 8.442)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="cbylncbjf"/><stop offset="1" class="hj2nkngkt"/></radialGradient><radialGradient id="iKoyZsb" cx="0" cy="0" r="1" gradientTransform="matrix(.63983 .2011 -.62038 1.97394 13.432 8.655)" gradientUnits="userSpaceOnUse"><stop class="i4otoyosx"/><stop offset=".746" class="zqff1532o"/></radialGradient><radialGradient id="ioTu69c" cx="0" cy="0" r="1" gradientTransform="matrix(-2.26552 0 0 -4.00769 17.273 8.034)" gradientUnits="userSpaceOnUse"><stop class="e4t6-lb6y"/><stop offset="1" class="hhi9hubjb"/><stop offset="1" class="hhi9hubjb"/></radialGradient><radialGradient id="ieH1J6c" cx="0" cy="0" r="1" gradientTransform="matrix(-.75541 1.24935 -1.03143 -.62365 17.108 5.877)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="fajfg00jo"/><stop offset="1" class="wpa_x2uhd"/></radialGradient><radialGradient id="iCnkRMc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.49765 .61584 0 17.117 7.465)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="o847wybrn"/><stop offset="1" class="z-0dlhbai"/></radialGradient><radialGradient id="iYFwRtd" cx="0" cy="0" r="1" gradientTransform="matrix(.0017 -.47421 .51605 .00185 15.06 7.486)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="pxeuj6buu"/><stop offset="1" class="lg98p_5je"/></radialGradient><radialGradient id="iMq3oVc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.6818 .23241 -.5937 -9.40513 17.544 8.463)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="sim-rnb6d"/><stop offset="1" class="vx5g9qbgu"/></radialGradient><radialGradient id="ibyX2dc" cx="0" cy="0" r="1" gradientTransform="matrix(1.46725 -1.26387 .37333 .4334 13.113 6.85)" gradientUnits="userSpaceOnUse"><stop offset=".539" class="sf65_-b_u"/><stop offset="1" class="n9ebefe8q"/></radialGradient><radialGradient id="ilNzW3c" cx="0" cy="0" r="1" gradientTransform="matrix(-.10169 1.08228 -.43263 -.04065 18.46 6.77)" gradientUnits="userSpaceOnUse"><stop offset=".245" class="p54kb3bjj"/><stop offset="1" class="rm9y2hb6m"/></radialGradient><radialGradient id="icqB8hb" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.07813 -4.32751 0 16.077 6.792)" gradientUnits="userSpaceOnUse"><stop offset=".72" class="nso85qbdr"/><stop offset="1" class="yvof5m88m"/></radialGradient><radialGradient id="iyJFImd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .10578 -.33246 0 16.259 8.624)" gradientUnits="userSpaceOnUse"><stop class="eqmylox_y"/><stop offset="1" class="sicchzd0u"/></radialGradient><radialGradient id="iHIbaDc" cx="0" cy="0" r="1" gradientTransform="matrix(-.6592 .30224 -.48572 -1.05939 16.309 8.377)" gradientUnits="userSpaceOnUse"><stop offset=".714" class="cjboikbop"/><stop offset="1" class="l6ffphqdg"/></radialGradient><radialGradient id="iunMuRc" cx="0" cy="0" r="1" gradientTransform="matrix(.94558 -.46487 1.8703 3.80429 15.844 9.605)" gradientUnits="userSpaceOnUse"><stop offset=".562" class="etju2kb3q"/><stop offset="1" class="iazz9lb4s"/></radialGradient><radialGradient id="ism7N9d" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.51732 3.83713 0 13.79 6.781)" gradientUnits="userSpaceOnUse"><stop offset=".536" class="ibt06e6rm"/><stop offset="1" class="k45xjwbmq"/></radialGradient><radialGradient id="iQFHp0R" cx="0" cy="0" r="1" gradientTransform="matrix(.04942 -1.08883 1.92918 .08756 18.163 7.349)" gradientUnits="userSpaceOnUse"><stop class="c98z413ze"/><stop offset="1" class="ovvtmacpn"/></radialGradient><radialGradient id="i5o76Cm" cx="0" cy="0" r="1" gradientTransform="matrix(-1.02221 -.67231 .49351 -.75036 17.836 4.629)" gradientUnits="userSpaceOnUse"><stop class="jx9hffbwe"/><stop offset="1" class="mzj8iibqz"/></radialGradient><radialGradient id="iuKn5Xs" cx="0" cy="0" r="1" gradientTransform="matrix(.29108 .51926 -1.20235 .674 15.664 3.939)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="e8ajgab-k"/><stop offset="1" class="gxf7b0v7y"/></radialGradient><radialGradient id="iGkOv8b" cx="0" cy="0" r="1" gradientTransform="matrix(-.95387 0 0 -.35402 16.166 4.918)" gradientUnits="userSpaceOnUse"><stop class="axstwemrb"/><stop offset="1" class="ez41_pbnb"/></radialGradient><radialGradient id="iC1QSpf" cx="0" cy="0" r="1" gradientTransform="matrix(1.39462 -2.20814 2.4464 1.5451 13.703 6.626)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="hnw0p1utu"/><stop offset=".311" class="dwl_ftd7p"/><stop offset="1" class="fch_lgr5q"/></radialGradient><radialGradient id="iTo0jcb" cx="0" cy="0" r="1" gradientTransform="matrix(1.16084 -1.106 2.0248 2.1252 17.198 6.57)" gradientUnits="userSpaceOnUse"><stop offset=".857" class="stq0hsb2e"/><stop offset="1" class="i6xvtdb8e"/></radialGradient><radialGradient id="iDtOKpp" cx="0" cy="0" r="1" gradientTransform="matrix(1.40764 .16453 -.06889 .58935 16.814 5.931)" gradientUnits="userSpaceOnUse"><stop class="unyhdjbdq"/><stop offset="1" class="w0a4mmrgb"/></radialGradient><radialGradient id="i6RoLle" cx="0" cy="0" r="1" gradientTransform="matrix(0 .3516 -.55924 0 17.002 7.637)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="iX81axc" cx="0" cy="0" r="1" gradientTransform="rotate(-127.813 10.33 -.302)scale(.16393 .2257)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iR9eqAe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .3516 -.55927 0 15.11 7.637)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="iSxg34d" cx="0" cy="0" r="1" gradientTransform="matrix(-.00335 -.21411 .25737 -.00403 14.987 7.732)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iTlhc8d" cx="0" cy="0" r="1" gradientTransform="matrix(.27238 .97214 -.9275 .25987 18.058 7.644)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="xron-kbnx"/><stop offset="1" class="bzyp_ibbo"/></radialGradient><radialGradient id="iCZQsye" cx="0" cy="0" r="1" gradientTransform="matrix(.3414 -.4685 .3927 .28615 18.214 7.88)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="w_o-5kbak"/><stop offset="1" class="mb4bnzbbk"/></radialGradient><radialGradient id="i1KWcWd" cx="0" cy="0" r="1" gradientTransform="rotate(-69.263 14.89 -9.244)scale(.71843 .95992)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="sxoyafbbn"/><stop offset="1" class="tri7bg95c"/></radialGradient><radialGradient id="i3ZjXMb" cx="0" cy="0" r="1" gradientTransform="matrix(-.71862 0 0 -.80244 13.926 7.921)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="srn41o2oz"/><stop offset="1" class="dfc36bbxx"/></radialGradient><radialGradient id="ikkNube" cx="0" cy="0" r="1" gradientTransform="matrix(-.39716 .06817 -.0699 -.40722 13.927 7.922)" gradientUnits="userSpaceOnUse"><stop class="m_eaw6bxg"/><stop offset="1" class="nk_trfbso"/></radialGradient><filter id="iIOckwd" width="7.335" height="7.37" x="13.891" y="10.901" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.075" dy=".08"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.662745 0 0 0 0 1 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1147"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.08"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.513726 0 0 0 0 0.745098 0 0 0 0 0.996078 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1147" result="effect2_innerShadow_4002_1147"/></filter><filter id="ipGEO4b" width="10.517" height="10.517" x="14.14" y="4.72" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.623529 0 0 0 0 1 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1147"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.639216 0 0 0 0 1 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1147" result="effect2_innerShadow_4002_1147"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.788235 0 0 0 0 0.827451 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_1147" result="effect3_innerShadow_4002_1147"/></filter><filter id="iZftjmc" width="9.391" height="10.922" x="7.466" y="4.73" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.592157 0 0 0 0 1 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1147"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.545098 0 0 0 0 0.811765 0 0 0 0 0.831373 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1147" result="effect2_innerShadow_4002_1147"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.521569 0 0 0 0 0.662745 0 0 0 0 0.886275 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_1147" result="effect3_innerShadow_4002_1147"/></filter><filter id="iCoLqAA" width="7.298" height="7.298" x="10.845" y="10.894" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.443137 0 0 0 0 0.654902 0 0 0 0 0.905882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1147"/></filter><filter id="ihA7opd" width="3.908" height="3.642" x="9.545" y="9.059" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.505882 0 0 0 0 0.768627 0 0 0 0 0.941176 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_4002_1147"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.6 0 0 0 0 0.941176 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_dropShadow_4002_1147" result="effect2_dropShadow_4002_1147"/><feBlend in="SourceGraphic" in2="effect2_dropShadow_4002_1147" result="shape"/></filter><filter id="il9l0Ed" width="6.45" height="6.548" x="9.62" y="5.989" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.505882 0 0 0 0 0.768627 0 0 0 0 0.941176 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_4002_1147"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.6 0 0 0 0 0.941176 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_dropShadow_4002_1147" result="effect2_dropShadow_4002_1147"/><feBlend in="SourceGraphic" in2="effect2_dropShadow_4002_1147" result="shape"/></filter><filter id="i3NISle" width="3.908" height="3.642" x="18.631" y="9.059" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.505882 0 0 0 0 0.768627 0 0 0 0 0.941176 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_4002_1147"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.607843 0 0 0 0 0.968627 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_dropShadow_4002_1147" result="effect2_dropShadow_4002_1147"/><feBlend in="SourceGraphic" in2="effect2_dropShadow_4002_1147" result="shape"/></filter><filter id="iu91LJd" width="6.45" height="6.548" x="16.014" y="5.989" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.505882 0 0 0 0 0.768627 0 0 0 0 0.941176 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_4002_1147"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.607843 0 0 0 0 0.968627 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_dropShadow_4002_1147" result="effect2_dropShadow_4002_1147"/><feBlend in="SourceGraphic" in2="effect2_dropShadow_4002_1147" result="shape"/></filter><filter id="i4LDBWG" width="1.003" height="4.833" x="22.341" y="4.797" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".35" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.254902 0 0 0 0 0.239216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1147"/></filter><filter id="ia6enGc" width="4.084" height="3.799" x="20.732" y="2.116" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.05"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.917647 0 0 0 0 0.639216 0 0 0 0 0.270588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1147"/></filter><filter id="iWinbce" width="5.091" height="7.247" x="15.749" y="20.368" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".65" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.4 0 0 0 0 0.266667 0 0 0 0 0.247059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1147"/></filter><filter id="iEGKK5b" width="7.578" height="5.434" x="6.015" y="10.552" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.270588 0 0 0 0 0.345098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1147"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.486275 0 0 0 0 0.286275 0 0 0 0 0.431373 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1147" result="effect2_innerShadow_4002_1147"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.435294 0 0 0 0 0.309804 0 0 0 0 0.266667 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_1147" result="effect3_innerShadow_4002_1147"/></filter><filter id="icnGpDe" width="1.692" height="1.561" x="6.722" y="14.334" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.482353 0 0 0 0 0.266667 0 0 0 0 0.392157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1147"/></filter><filter id="irLYtDc" width="5.398" height="7.21" x="18.218" y="7.507" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.6"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.505882 0 0 0 0 0.235294 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1147"/></filter><filter id="iFe3YEb" width="4.609" height="5.161" x="19.13" y="9.308" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1147" stdDeviation=".25"/></filter><filter id="iIZgrgb" width="1.248" height="2.077" x="21.759" y="8.258" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1147" stdDeviation=".1"/></filter><filter id="iyuD9ge" width=".822" height="1.445" x="22.798" y="8.635" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1147" stdDeviation=".1"/></filter><filter id="ir4yw8e" width="4.929" height="5.398" x="13.862" y="5.36" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.494118 0 0 0 0 0.352941 0 0 0 0 0.32549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1147"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.396078 0 0 0 0 0.215686 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1147" result="effect2_innerShadow_4002_1147"/></filter><filter id="isyZx3c" width="2.757" height="3.257" x="14.617" y="6.677" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1147" stdDeviation=".5"/></filter><filter id="im6K2pc" width=".914" height="1.357" x="15.6" y="7.542" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1147" stdDeviation=".025"/></filter><filter id="isgHbtc" width="1.595" height=".665" x="15.259" y="9.04" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1147" stdDeviation=".025"/></filter><filter id="iOgNRxm" width="5.578" height="3.905" x="13.267" y="3.7" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.137255 0 0 0 0 0.0901961 0 0 0 0 0.145098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1147"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0784314 0 0 0 0 0.0352941 0 0 0 0 0.0470588 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1147" result="effect2_innerShadow_4002_1147"/></filter><filter id="iHq6wUC" width="1.07" height=".629" x="16.745" y="6.325" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.172549 0 0 0 0 0.0862745 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1147"/></filter><filter id="i4M1wZb" width="1.07" height=".623" x="14.467" y="6.331" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.172549 0 0 0 0 0.0862745 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1147"/></filter><filter id="ipjIwKe" width="2.937" height="2.658" x="13.38" y="4.436" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.286275 0 0 0 0 0.243137 0 0 0 0 0.227451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1147"/><feGaussianBlur result="effect2_foregroundBlur_4002_1147" stdDeviation=".075"/></filter><filter id="iORl7xe" width="2.551" height="2.316" x="16.117" y="4.751" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1147" stdDeviation=".025"/></filter><filter id="i4afJdd" width=".454" height=".415" x="16.627" y="7.39" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1147" stdDeviation=".05"/></filter><filter id="iNzoZnb" width=".613" height=".623" x="16.934" y="7.366" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1147" stdDeviation=".1"/></filter><filter id="iIwdsMe" width=".654" height=".677" x="15.009" y="7.338" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1147" stdDeviation=".1"/></filter><filter id="iK5Vm2c" width=".509" height=".419" x="14.739" y="7.387" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1147" stdDeviation=".05"/></filter><filter id="i8ESLvJ" width=".859" height="1.314" x="13.28" y="7.265" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1147" stdDeviation=".125"/></filter><filter id="iymU89L" width="1.41" height="1.825" x="17.698" y="7.007" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1147" stdDeviation=".25"/></filter><filter id="iOpH9YS" width="2.032" height="1.052" x="16.562" y="4.962" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1147" stdDeviation=".1"/></filter><linearGradient id="im3tg0d" x1="8.529" x2="12.668" y1="5.843" y2="9.982" gradientUnits="userSpaceOnUse"><stop class="tx327ubjh"/><stop offset="1" class="vxhtc9kgk"/></linearGradient><linearGradient id="iX1BTZW" x1="11.132" x2="10.694" y1="12.966" y2="9.06" gradientUnits="userSpaceOnUse"><stop class="ubeqdvb2g"/><stop offset="1" class="redus_bqs"/></linearGradient><linearGradient id="iDG4Gmd" x1="22.918" x2="22.549" y1="5.345" y2="6.133" gradientUnits="userSpaceOnUse"><stop offset=".167" class="zqax3vbfg"/><stop offset="1" class="z0_tnl66g"/></linearGradient><linearGradient id="i83V28c" x1="13.263" x2="14.851" y1="19.357" y2="19.357" gradientUnits="userSpaceOnUse"><stop class="x36zqabyv"/><stop offset="1" class="uktlcdafx"/></linearGradient><linearGradient id="i7QnpSd" x1="18.792" x2="16.991" y1="16.247" y2="16.247" gradientUnits="userSpaceOnUse"><stop class="utipi7g6i"/><stop offset="1" class="edfwaihfg"/></linearGradient><linearGradient id="iJU4nte" x1="13.267" x2="15.007" y1="16.431" y2="16.431" gradientUnits="userSpaceOnUse"><stop class="bjaenibkq"/><stop offset="1" class="louyt9b7g"/></linearGradient><linearGradient id="ir07lqp" x1="15.288" x2="13.817" y1="25.263" y2="25.263" gradientUnits="userSpaceOnUse"><stop offset=".267" class="jnedts9qu"/><stop offset=".945" class="jjvamgr7p"/></linearGradient><linearGradient id="is9Nicg" x1="15.46" x2="14.96" y1="26.669" y2="26.638" gradientUnits="userSpaceOnUse"><stop class="uj9y6sbjo"/><stop offset="1" class="pnh1u2g5u"/></linearGradient><linearGradient id="iZTxnje" x1="13.261" x2="13.692" y1="25.667" y2="25.667" gradientUnits="userSpaceOnUse"><stop class="o5s4dcbqc"/><stop offset="1" class="migaloo2k"/></linearGradient><linearGradient id="iR15onA" x1="15.197" x2="13.71" y1="28.891" y2="28.891" gradientUnits="userSpaceOnUse"><stop class="htqsm-l2e"/><stop offset=".159" class="zd1r_u8ze"/><stop offset=".453" class="x09-01b7i"/><stop offset="1" class="s_f01nb2h"/></linearGradient><linearGradient id="iC59Lpc" x1="18.825" x2="18.351" y1="24.378" y2="24.091" gradientUnits="userSpaceOnUse"><stop class="s5lr0-bjd"/><stop offset="1" class="p4dvxyhsv"/></linearGradient><linearGradient id="iFc3g8a" x1="15.749" x2="17.116" y1="25.981" y2="27.044" gradientUnits="userSpaceOnUse"><stop class="ilfb1o36w"/><stop offset="1" class="q6qjg9bpc"/></linearGradient><linearGradient id="icTBtvb" x1="16.029" x2="16.029" y1="10.709" y2="15.544" gradientUnits="userSpaceOnUse"><stop class="ctgol8ben"/><stop offset="1" class="d2j7ihp4i"/></linearGradient><linearGradient id="iU8dDfc" x1="13.267" x2="15.457" y1="14.741" y2="14.741" gradientUnits="userSpaceOnUse"><stop offset=".01" class="k4svfjbzs"/><stop offset="1" class="k0oa_8bou"/></linearGradient><linearGradient id="iAyTcBl" x1="22.63" x2="20.036" y1="11.605" y2="13.448" gradientUnits="userSpaceOnUse"><stop offset=".453" class="a3_z2xhkr"/><stop offset="1" class="k5r_gj7_l"/></linearGradient><linearGradient id="iVusaPe" x1="22.059" x2="21.755" y1="8.558" y2="10.249" gradientUnits="userSpaceOnUse"><stop class="ml_vtmq0l"/><stop offset="1" class="k3wixebqv"/></linearGradient><linearGradient id="iSuyLse" x1="23.372" x2="22.865" y1="9.113" y2="9.957" gradientUnits="userSpaceOnUse"><stop class="c16cce_hn"/><stop offset="1" class="zozno708c"/></linearGradient><linearGradient id="iKeySVc" x1="18.291" x2="17.195" y1="8.765" y2="8.765" gradientUnits="userSpaceOnUse"><stop class="agilw2byy"/><stop offset="1" class="h3kh2yb2k"/></linearGradient><linearGradient id="ibvlNNE" x1="16.42" x2="16.056" y1="8.327" y2="8.342" gradientUnits="userSpaceOnUse"><stop class="eqmylox_y"/><stop offset="1" class="sicchzd0u"/></linearGradient><linearGradient id="ijuGDAd" x1="16.056" x2="16.056" y1="8.82" y2="8.619" gradientUnits="userSpaceOnUse"><stop class="qsncw6btn"/><stop offset="1" class="v7xhdx32s"/></linearGradient><linearGradient id="i8Kf1Rp" x1="16.056" x2="16.056" y1="7.648" y2="7.885" gradientUnits="userSpaceOnUse"><stop class="fok393bvn"/><stop offset="1" class="y4umwkb_f"/></linearGradient><linearGradient id="i7kOwnd" x1="15.536" x2="15.674" y1="9.501" y2="9.14" gradientUnits="userSpaceOnUse"><stop class="t_m5csgaz"/><stop offset="1" class="ln8xouyxx"/></linearGradient><linearGradient id="ifULk3b" x1="19.026" x2="13.993" y1="5.581" y2="5.581" gradientUnits="userSpaceOnUse"><stop class="s5pji6bqr"/><stop offset="1" class="c7qpv738k"/></linearGradient><linearGradient id="iNk0aMd" x1="17.339" x2="17.203" y1="7.661" y2="7.744" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ioWEwIe" x1="15.433" x2="15.297" y1="7.661" y2="7.744" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="incEv1N" x1="18.846" x2="18.323" y1="7.672" y2="8.616" gradientUnits="userSpaceOnUse"><stop class="pkjt6qfem"/><stop offset="1" class="qw3t0fbxr"/></linearGradient><linearGradient id="iFWNf7c" x1="13.521" x2="14.153" y1="7.977" y2="7.922" gradientUnits="userSpaceOnUse"><stop class="lsjj5yb-k"/><stop offset="1" class="ac3zxpbrp"/></linearGradient><linearGradient id="ieIRJeH" x1="18.404" x2="18.404" y1="7.507" y2="8.332" gradientUnits="userSpaceOnUse"><stop class="x9ttejxmc"/><stop offset="1" class="nal-rljch"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-fairy-medium-dark" /></template>
<style>
.a_g2v1e7w {
  fill: var(--svg-color--fb652d, #FB652D);
  d: path("M13.263 21.733V16.26l5.529.057c0 .347.063.665.09.764l1.042 3.486l-2.33.484l-.865-2.223c-.132-.336-.285-.64-.504-.64c-.25 0-.356.391-.361.59l-.28 3.011z");
}

.a3_z2xhkr {
  stop-color: var(--svg-color--a17e73, #A17E73);
}

.ac3zxpbrp {
  stop-color: var(--svg-color--623549, #623549);
}

.agilw2byy {
  stop-color: var(--svg-color--936b5d, #936B5D);
}

.axstwemrb {
  stop-color: var(--svg-color--423c3f, #423C3F);
}

.axzx4newn {
  fill: var(--svg-color--8f6263, #8F6263);
  d: path("m17.672 21.275l-.082-.227l2.331-.48c.02.062.094.292.219.71c.125.42-.01.774-.094.899l-3.269 5.344c-.07.116-.233.128-.311.017c-.297-.42-.547-.974-.686-1.358a.55.55 0 0 1 .023-.42l1.85-4.032a.6.6 0 0 0 .019-.453");
}

.b47wb-b1b {
  d: path("m17.672 21.275l-.082-.227l2.331-.48c.02.062.094.292.219.71c.125.42-.01.774-.094.899l-3.269 5.344c-.07.116-.233.128-.311.017c-.297-.42-.547-.974-.686-1.358a.55.55 0 0 1 .023-.42l1.85-4.032a.6.6 0 0 0 .019-.453");
}

.b4zzki-mx {
  stop-color: var(--svg-color--7d534e, #7D534E);
}

.b5t1rjggp {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M16.975 7.512c.027.037-.03.082-.096.131c-.066.05-.114.084-.142.047s.004-.107.07-.156c.065-.049.14-.059.168-.022");
}

.bbyb_mbsk {
  stop-color: var(--svg-color--664842, #664842);
}

.bdcjj-bzz {
  d: path("M15.11 7.43a.387.387 0 0 0-.373.49h.747a.39.39 0 0 0-.375-.489");
}

.bjaenibkq {
  stop-color: var(--svg-color--839927, #839927);
}

.bk4v9v6pj {
  d: path("M15.463 7.772c0-.125-.101-.208-.129-.234l-.125.121l.077.157z");
}

.blsn939-n {
  stop-color: var(--svg-color--a37b73, #A37B73);
  stop-opacity: 0;
}

.burjw8bvx {
  d: path("M13.263 21.733V16.26l5.529.057c0 .347.063.665.09.764l1.042 3.486l-2.33.484l-.865-2.223c-.132-.336-.285-.64-.504-.64c-.25 0-.356.391-.361.59l-.28 3.011z");
}

.bzyp_ibbo {
  stop-color: var(--svg-color--71404f, #71404F);
}

.c16cce_hn {
  stop-color: var(--svg-color--9d7d72, #9D7D72);
}

.c6dvfyb6s {
  stop-color: var(--svg-color--e94a61, #E94A61);
}

.c7qpv738k {
  stop-color: var(--svg-color--362c2e, #362C2E);
}

.c98z413ze {
  stop-color: var(--svg-color--4f4d4d, #4F4D4D);
}

.cbylncbjf {
  stop-color: var(--svg-color--332f31, #332F31);
}

.cjboikbop {
  stop-color: var(--svg-color--744a4a, #744A4A);
  stop-opacity: 0;
}

.ckqr_ab5f {
  fill: var(--svg-color--49373d, #49373D);
  d: path("M17.873 5.582h-.901a.21.21 0 1 1 .033-.417c.234.037.545.09.753.14c.47.118.6.347.636.51a.66.66 0 0 0-.52-.233");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.ctgol8ben {
  stop-color: var(--svg-color--ff8328, #FF8328);
}

.cz72ar2pi {
  fill: var(--svg-color--2d171f, #2D171F);
  d: path("m18.315 7.016l-.012-.273a.637.637 0 0 0-.61-.618h-.606a1.05 1.05 0 0 1-.92-.546s.312-.897.826-.765c.364.093.752.233 1.057.432a1.15 1.15 0 0 1 .265 1.77");
}

.d0qi1-blu {
  stop-color: var(--svg-color--703d57, #703D57);
}

.d2j7ihp4i {
  stop-color: var(--svg-color--ff712e, #FF712E);
}

.dfc36bbxx {
  stop-color: var(--svg-color--836158, #836158);
}

.diyc2abac {
  d: path("m16.157 5.6l-.029-.058a.29.29 0 0 0-.266-.182h-.552c-.8 0-1.448.656-1.448 1.465v.119c-.147-.112-.332-.349-.332-.732c0-.464.338-.699.554-.849a1 1 0 0 0 .144-.11l.043-.045c.151-.16.421-.447.893-.572q.098-.025.195-.041c.466-.076.807.343.807.816v.184z");
}

.dm7l30bog {
  cx: 14.993px;
  cy: 7.596px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.169px;
  ry: 0.085px;
}

.dnli9p0qf {
  d: path("m15.89 7.725l-.23.796c-.047.164.066.328.226.328h.34c.16 0 .273-.166.226-.328l-.23-.796c-.05-.177-.28-.177-.331 0");
}

.dwl_ftd7p {
  stop-color: var(--svg-color--1c0c20, #1C0C20);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e4t6-lb6y {
  stop-color: var(--svg-color--9a6e61, #9A6E61);
}

.e593k4bfv {
  fill: var(--svg-color--aed62f, #AED62F);
  d: path("M13.267 16.349v-.82h5.525v.82c-2.337.148-4.276.062-5.525 0");
}

.e8ajgab-k {
  stop-color: var(--svg-color--392f31, #392F31);
}

.e9b9gabbg {
  fill: var(--svg-color--7e5a4e, #7E5A4E);
  d: path("M7.08 15.003c.177-.133.339-.264.43-.342c.416-.346.637-.217.723-.129c.1.103.145.418-.093.696c-.25.29-.51.464-.735.601c-.165.1-.46.088-.582-.062c-.238-.242-.014-.561.256-.764");
}

.eayua2tob {
  d: path("m13.312 28.098l.006 1.49c0 .169.164.288.322.231a7 7 0 0 0 1.287-.603a.47.47 0 0 0 .215-.373l.055-.894z");
}

.edfwaihfg {
  stop-color: var(--svg-color--bff332, #BFF332);
  stop-opacity: 0;
}

.eqmylox_y {
  stop-color: var(--svg-color--a17c72, #A17C72);
}

.etju2kb3q {
  stop-color: var(--svg-color--87004e, #87004E);
}

.etm0labvf {
  width: 4.843px;
  height: 8.191px;
  x: 12.963px;
  y: 13.403px;
  rx: 2.422px;
}

.ez41_pbnb {
  stop-color: var(--svg-color--423c3f, #423C3F);
  stop-opacity: 0;
}

.f4c48qbpa {
  d: path("M17.003 7.43a.387.387 0 0 1 .373.49h-.747a.388.388 0 0 1 .374-.489");
}

.f6xfjgb1y {
  fill: var(--svg-color--7d534e, #7D534E);
  d: path("M13.28 11.279c.194-.188.29-.23.313-.227v2.59c-.399.557-1.783 1.92-3.508 2.176c-1.615.24-2.64-.206-2.883-.47a4 4 0 0 0-.448.378a.44.44 0 0 1-.556.045a.444.444 0 0 1-.133-.56c.558-1.027 1.462-1.373 2.887-1.33c1.256.037 2.117-.522 2.39-.806c.566-.52 1.744-1.609 1.938-1.796");
}

.fajfg00jo {
  stop-color: var(--svg-color--855e5a, #855E5A);
}

.fch_lgr5q {
  stop-color: var(--svg-color--1c0c20, #1C0C20);
  stop-opacity: 0;
}

.ffese-y7m {
  width: 6.894px;
  height: 11.735px;
  rx: 3.447px;
}

.fgis5qzvv {
  stop-color: var(--svg-color--a37b73, #A37B73);
}

.fok393bvn {
  stop-color: var(--svg-color--865c56, #865C56);
}

.ft5dv1b6b {
  fill: none;
}

.g11vnob-s {
  fill: var(--svg-color--fff, #fff);
  d: path("M10.047 9.264a.21.21 0 1 0-.284.31l1.82 1.667l-.84.086a.21.21 0 1 0 .043.418l1.21-.124l.955.875a.21.21 0 1 0 .284-.31z");
}

.g5dwguodp {
  fill: var(--svg-color--2e201f, #2E201F);
  d: path("M14.578 6.696a1.2 1.2 0 0 1 .754-.156a.12.12 0 0 1-.03.239a.96.96 0 0 0-.633.144l-.007.005h-.001a.12.12 0 0 1-.148-.19z");
}

.gbuovhboa {
  stop-color: var(--svg-color--95726c, #95726C);
}

.ghbnzyqzr {
  d: path("m18.199 8.332l.047-.825a.414.414 0 0 1-.047.825");
}

.gtwdzjt0y {
  cx: 14.993px;
  cy: 7.596px;
  rx: 0.169px;
  ry: 0.085px;
}

.gxf7b0v7y {
  stop-color: var(--svg-color--392f31, #392F31);
  stop-opacity: 0;
}

.h3kh2yb2k {
  stop-color: var(--svg-color--936b5d, #936B5D);
  stop-opacity: 0;
}

.hhi9hubjb {
  stop-color: var(--svg-color--754c4c, #754C4C);
}

.hj2nkngkt {
  stop-color: var(--svg-color--221925, #221925);
}

.hnw0p1utu {
  stop-color: var(--svg-color--0b0306, #0B0306);
}

.hq3hkib4c {
  stop-color: var(--svg-color--e0521f, #E0521F);
}

.htqsm-l2e {
  stop-color: var(--svg-color--664e86, #664E86);
}

.hts433_5m {
  stop-color: var(--svg-color--ff9842, #FF9842);
  stop-opacity: 0;
}

.i4otoyosx {
  stop-color: var(--svg-color--3e3330, #3E3330);
}

.i6xvtdb8e {
  stop-color: var(--svg-color--545051, #545051);
}

.iazz9lb4s {
  stop-color: var(--svg-color--87004d, #87004D);
}

.ibt06e6rm {
  stop-color: var(--svg-color--3e3433, #3E3433);
}

.ignt4ubkd {
  stop-color: var(--svg-color--ff9842, #FF9842);
}

.ikgkim2qs {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M22.06 8.558v.505a1 1 0 0 0 .433.824l.215.147");
}

.ilfb1o36w {
  stop-color: var(--svg-color--352b41, #352B41);
}

.ip469ff8c {
  stop-color: var(--svg-color--ff8045, #FF8045);
}

.is89u6ban {
  d: path("M8.523 10.723a3.454 3.454 0 0 1 .006-4.88a3.454 3.454 0 0 1 4.88-.006l1.19 1.19c.338.337.602.742.775 1.188l1.2 3.086c.154.398.233.822.233 1.249v.56a2.443 2.443 0 0 1-4.17 1.727z");
}

.j4v0ojb2o {
  fill: var(--svg-color--fff, #fff);
  d: path("M15.02 7.313a.605.605 0 0 0-.587.459a.12.12 0 0 0 .116.147h.967a.1.1 0 0 0 .098-.117a.61.61 0 0 0-.594-.49");
}

.j7smtkbjw {
  stop-color: var(--svg-color--6d494d, #6D494D);
}

.jic9bm_zi {
  d: path("M15.07 10.486v.349a.24.24 0 0 0 .065.157c.135.147.326.443.456.87c.06.195.233.342.437.342a.47.47 0 0 0 .437-.342c.13-.427.322-.723.457-.87a.24.24 0 0 0 .065-.157v-.35z");
}

.jjvamgr7p {
  stop-color: var(--svg-color--815553, #815553);
}

.jnedts9qu {
  stop-color: var(--svg-color--976e6a, #976E6A);
}

.jx9hffbwe {
  stop-color: var(--svg-color--402c32, #402C32);
}

.k_rioyb_p {
  stop-color: var(--svg-color--e0521f, #E0521F);
  stop-opacity: 0;
}

.k-27-x9ja {
  d: path("M13.28 11.279c.194-.188.29-.23.313-.227v2.59c-.399.557-1.783 1.92-3.508 2.176c-1.615.24-2.64-.206-2.883-.47a4 4 0 0 0-.448.378a.44.44 0 0 1-.556.045a.444.444 0 0 1-.133-.56c.558-1.027 1.462-1.373 2.887-1.33c1.256.037 2.117-.522 2.39-.806c.566-.52 1.744-1.609 1.938-1.796");
}

.k0oa_8bou {
  stop-color: var(--svg-color--f36b26, #F36B26);
  stop-opacity: 0;
}

.k1-2mnnxu {
  fill: var(--svg-color--2d171f, #2D171F);
  d: path("m16.157 5.6l-.029-.058a.29.29 0 0 0-.266-.182h-.552c-.8 0-1.448.656-1.448 1.465v.119c-.147-.112-.332-.349-.332-.732c0-.464.338-.699.554-.849a1 1 0 0 0 .144-.11l.043-.045c.151-.16.421-.447.893-.572q.098-.025.195-.041c.466-.076.807.343.807.816v.184z");
}

.k356i5yuc {
  stop-color: var(--svg-color--91deff, #91DEFF);
}

.k3wixebqv {
  stop-color: var(--svg-color--846763, #846763);
  stop-opacity: 0;
}

.k45xjwbmq {
  stop-color: var(--svg-color--3e3433, #3E3433);
  stop-opacity: 0;
}

.k4svfjbzs {
  stop-color: var(--svg-color--d35c1b, #D35C1B);
}

.k5r_gj7_l {
  stop-color: var(--svg-color--a17e73, #A17E73);
  stop-opacity: 0;
}

.k9wpgpx3v {
  stop-color: var(--svg-color--855c58, #855C58);
  stop-opacity: 0;
}

.kkcj50baa {
  d: path("M17.347 7.766a.36.36 0 0 0-.1-.2l-.113.124l.051.098z");
}

.kwow_3omf {
  d: path("m18.315 7.016l-.012-.273a.637.637 0 0 0-.61-.618h-.606a1.05 1.05 0 0 1-.92-.546s.312-.897.826-.765c.364.093.752.233 1.057.432a1.15 1.15 0 0 1 .265 1.77");
}

.l1fas3zcg {
  d: path("M13.965 9.233a1.7 1.7 0 0 0 1.684 1.476h.818c.852 0 1.572-.63 1.684-1.476c.05-.817.102-1.63.14-2.446a.63.63 0 0 0-.598-.62h-.606a1.05 1.05 0 0 1-.959-.625a.29.29 0 0 0-.266-.182h-.552c-.8 0-1.448.656-1.448 1.465c0 .806.05 1.6.103 2.408");
}

.l6ffphqdg {
  stop-color: var(--svg-color--744a4a, #744A4A);
}

.lg98p_5je {
  stop-color: var(--svg-color--70424e, #70424E);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.ln8xouyxx {
  stop-color: var(--svg-color--866163, #866163);
  stop-opacity: 0;
}

.louyt9b7g {
  stop-color: var(--svg-color--afd730, #AFD730);
  stop-opacity: 0;
}

.lsjj5yb-k {
  stop-color: var(--svg-color--6a4544, #6A4544);
}

.lz6zpisqv {
  stop-color: var(--svg-color--6b4440, #6B4440);
}

.m_eaw6bxg {
  stop-color: var(--svg-color--57353c, #57353C);
}

.m0kz_y80u {
  d: path("m13.318 29.589l-.057-7.861l2.32.062l-.438 7.053a.47.47 0 0 1-.216.373a7 7 0 0 1-1.287.603a.242.242 0 0 1-.322-.23");
}

.m7qzf0bah {
  d: path("M16.975 7.512c.027.037-.03.082-.096.131c-.066.05-.114.084-.142.047s.004-.107.07-.156c.065-.049.14-.059.168-.022");
}

.m9o60j3-s {
  d: path("M16.016 10.71c-.437.014-1.419.083-1.984.162c-.722.102-.765.711-.765.992v3.68h5.525v-3.68c0-.28-.043-.89-.765-.992a24 24 0 0 0-1.984-.163h-.027");
}

.mb4bnzbbk {
  stop-color: var(--svg-color--7c4c46, #7C4C46);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mc2zb0bvp {
  opacity: var(--svg-opacity--0-5, 0.5);
}

.migaloo2k {
  stop-color: var(--svg-color--89625c, #89625C);
  stop-opacity: 0;
}

.ml_vtmq0l {
  stop-color: var(--svg-color--846763, #846763);
}

.mzj8iibqz {
  stop-color: var(--svg-color--402c32, #402C32);
  stop-opacity: 0;
}

.n5igrlbfw {
  stop-color: var(--svg-color--593569, #593569);
  stop-opacity: 0;
}

.n9ebefe8q {
  stop-color: var(--svg-color--4f2c2a, #4F2C2A);
  stop-opacity: 0;
}

.nal-rljch {
  stop-color: var(--svg-color--7d5449, #7D5449);
}

.nfvol29vo {
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M16.056 9.29c-.22 0-.426-.052-.6-.143c-.06-.03-.123.037-.086.09a.82.82 0 0 0 .686.368a.82.82 0 0 0 .687-.367c.037-.056-.027-.12-.086-.09c-.174.09-.378.142-.6.142Z");
}

.nk_trfbso {
  stop-color: var(--svg-color--5b3336, #5B3336);
}

.nl4f7twra {
  width: 0.703px;
  height: 4.633px;
  x: 22.341px;
  y: 4.997px;
  rx: 0.352px;
}

.nso85qbdr {
  stop-color: var(--svg-color--794755, #794755);
  stop-opacity: 0;
}

.nw_aknb7y {
  stop-color: var(--svg-color--ffc736, #FFC736);
}

.o5s4dcbqc {
  stop-color: var(--svg-color--89625c, #89625C);
}

.o7l-q1nix {
  d: path("M13.853 7.515a.414.414 0 0 0 .036.814a34 34 0 0 1-.036-.814");
}

.o847wybrn {
  stop-color: var(--svg-color--875455, #875455);
}

.oa3f9ve3k {
  d: path("M22.5 2.293a.22.22 0 0 1 .4.001l.413.896a.22.22 0 0 0 .175.126l.983.115a.22.22 0 0 1 .128.376l-.734.716a.22.22 0 0 0-.062.2l.185.926a.22.22 0 0 1-.32.237l-.864-.459a.22.22 0 0 0-.206 0l-.87.462a.22.22 0 0 1-.32-.235l.178-.932a.22.22 0 0 0-.062-.198l-.727-.718a.22.22 0 0 1 .13-.375l.98-.115a.22.22 0 0 0 .174-.125z");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.odpjwqbbc {
  fill: var(--svg-color--845b55, #845B55);
  d: path("m15.89 7.725l-.23.796c-.047.164.066.328.226.328h.34c.16 0 .273-.166.226-.328l-.23-.796c-.05-.177-.28-.177-.331 0");
}

.ovvtmacpn {
  stop-color: var(--svg-color--4f4d4d, #4F4D4D);
  stop-opacity: 0;
}

.oz3_ipb8v {
  stop-color: var(--svg-color--e94a61, #E94A61);
  stop-opacity: 0;
}

.p4dvxyhsv {
  stop-color: var(--svg-color--91676d, #91676D);
  stop-opacity: 0;
}

.p54kb3bjj {
  stop-color: var(--svg-color--98786d, #98786D);
}

.p5u-_cblu {
  stop-color: var(--svg-color--603b8b, #603B8B);
}

.pha_6_rva {
  stop-color: var(--svg-color--94d8ff, #94D8FF);
  stop-opacity: 0;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pkjt6qfem {
  stop-color: var(--svg-color--9c7b71, #9C7B71);
}

.pn9klvbrs {
  stop-color: var(--svg-color--885d55, #885D55);
}

.pnh1u2g5u {
  stop-color: var(--svg-color--896057, #896057);
  stop-opacity: 0;
}

.pt-h1ccpi {
  stop-color: var(--svg-color--febb35, #FEBB35);
}

.pv3dgeoha {
  fill: var(--svg-color--fff, #fff);
  d: path("M20.68 6.325a.21.21 0 0 1 .418.048l-.159 1.385l1.024-.928a.21.21 0 1 1 .282.311l-5.73 5.192a.21.21 0 0 1-.282-.312l4.234-3.836z");
}

.pxeuj6buu {
  stop-color: var(--svg-color--70424e, #70424E);
}

.q6qjg9bpc {
  stop-color: var(--svg-color--64468a, #64468A);
}

.qggerob2g {
  stop-color: var(--svg-color--6e3f3c, #6E3F3C);
}

.qlfye6p8o {
  stop-color: var(--svg-color--ffd545, #FFD545);
  stop-opacity: 0;
}

.qrqkgk68o {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.092 7.313c.284 0 .523.195.588.459a.12.12 0 0 1-.116.147h-.967a.1.1 0 0 1-.099-.117a.606.606 0 0 1 .594-.49");
}

.qsncw6btn {
  stop-color: var(--svg-color--7d465b, #7D465B);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qw3t0fbxr {
  stop-color: var(--svg-color--815758, #815758);
}

.qya8vwbkf {
  stop-color: var(--svg-color--86605c, #86605C);
}

.r9m8_svvg {
  width: 0.703px;
  height: 4.633px;
  x: 22.341px;
  y: 4.997px;
  fill: var(--svg-color--9a6159, #9A6159);
  rx: 0.352px;
}

.redus_bqs {
  stop-color: var(--svg-color--87c9fb, #87C9FB);
  stop-opacity: 0;
}

.rivz2obdn {
  stop-color: var(--svg-color--91e5ff, #91E5FF);
}

.rm9y2hb6m {
  stop-color: var(--svg-color--98786d, #98786D);
  stop-opacity: 0;
}

.rmw-9s7sx {
  d: path("M16.056 9.29c-.22 0-.426-.052-.6-.143c-.06-.03-.123.037-.086.09a.82.82 0 0 0 .686.368a.82.82 0 0 0 .687-.367c.037-.056-.027-.12-.086-.09c-.174.09-.378.142-.6.142");
}

.rpk2cqb3k {
  d: path("M13.95 8.576a.7.7 0 0 1-.392-.134v.404c0 .387.23.732.58.875a1.8 1.8 0 0 1-.15-.512z");
}

.rrxj9bckx {
  fill: var(--svg-color--000, #000);
  d: path("M16.782 7.817a.22.22 0 0 1 .221-.221a.22.22 0 0 1 .197.323h-.392a.2.2 0 0 1-.026-.102");
}

.s_et88bec {
  stop-color: var(--svg-color--ffd545, #FFD545);
}

.s_f01nb2h {
  stop-color: var(--svg-color--4b3866, #4B3866);
}

.s2ceddo5o {
  stop-color: var(--svg-color--80caf3, #80CAF3);
}

.s3hklabia {
  stop-color: var(--svg-color--593569, #593569);
}

.s5lr0-bjd {
  stop-color: var(--svg-color--91676d, #91676D);
}

.s5pji6bqr {
  stop-color: var(--svg-color--443237, #443237);
}

.s99p66ikg {
  fill: var(--svg-color--fff, #fff);
  d: path("M22.037 9.264a.21.21 0 1 1 .283.31l-1.819 1.667l.84.086a.21.21 0 1 1-.043.418l-1.211-.124l-.954.875a.21.21 0 1 1-.284-.31z");
}

.saunobcmg {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("m19.88 12.667l2.672 1.045a.1.1 0 0 0 .136-.085l.301-3.57");
}

.scofoabvh {
  stop-color: var(--svg-color--7d534e, #7D534E);
  stop-opacity: 0;
}

.sf65_-b_u {
  stop-color: var(--svg-color--4f2c2a, #4F2C2A);
}

.sicchzd0u {
  stop-color: var(--svg-color--a17c72, #A17C72);
  stop-opacity: 0;
}

.sim-rnb6d {
  stop-color: var(--svg-color--815f58, #815F58);
  stop-opacity: 0;
}

.sl-3t4bfx {
  stop-color: var(--svg-color--e43423, #E43423);
}

.srn41o2oz {
  stop-color: var(--svg-color--836158, #836158);
  stop-opacity: 0;
}

.stq0hsb2e {
  stop-color: var(--svg-color--545051, #545051);
  stop-opacity: 0;
}

.sxoyafbbn {
  stop-color: var(--svg-color--805d4c, #805D4C);
  stop-opacity: 0;
}

.sy1zgqbhn {
  d: path("M18.16 5.156c.223.076.423.232.55.455c.202.356.172.781-.046 1.095a.7.7 0 0 0-.118.379V7.6a.8.8 0 0 0-.289-.116l.034-.697a.63.63 0 0 0-.597-.62h-.607a1.05 1.05 0 0 1-.959-.625a.29.29 0 0 0-.266-.182h-.552c-.8 0-1.448.656-1.448 1.465l.013.666a.74.74 0 0 0-.312.114v-.52a.7.7 0 0 0-.117-.379a1.04 1.04 0 0 1-.062-1.06c.127-.24.331-.407.563-.488c.248-.088.46-.256.6-.481a1.01 1.01 0 0 1 1.253-.395a.65.65 0 0 0 .517 0a1.01 1.01 0 0 1 1.257.41c.133.22.343.38.586.464");
}

.t_m5csgaz {
  stop-color: var(--svg-color--866163, #866163);
}

.tj824objr {
  stop-color: var(--svg-color--6b4440, #6B4440);
  stop-opacity: 0;
}

.tri7bg95c {
  stop-color: var(--svg-color--805d4c, #805D4C);
}

.tx327ubjh {
  stop-color: var(--svg-color--8eefff, #8EEFFF);
}

.ubeqdvb2g {
  stop-color: var(--svg-color--87c9fb, #87C9FB);
}

.ui2im5sxy {
  d: path("M18.163 8.576a.7.7 0 0 0 .392-.134v.404c0 .387-.23.732-.58.875q.11-.236.149-.512z");
}

.uj9y6sbjo {
  stop-color: var(--svg-color--896057, #896057);
}

.uktlcdafx {
  stop-color: var(--svg-color--dd4920, #DD4920);
  stop-opacity: 0;
}

.un08nrbhl {
  stop-color: var(--svg-color--ff6737, #FF6737);
  stop-opacity: 0;
}

.unyhdjbdq {
  stop-color: var(--svg-color--200e25, #200E25);
}

.uodqeubaz {
  stop-color: var(--svg-color--94d8ff, #94D8FF);
}

.uowu7rarb {
  stop-color: var(--svg-color--603b8b, #603B8B);
  stop-opacity: 0;
}

.utdakeidf {
  stop-color: var(--svg-color--ff7e38, #FF7E38);
  stop-opacity: 0;
}

.utipi7g6i {
  stop-color: var(--svg-color--bff332, #BFF332);
}

.v_k-57lgf {
  stop-color: var(--svg-color--ffdd49, #FFDD49);
  stop-opacity: 0;
}

.v0q_-i93u {
  stop-color: var(--svg-color--ff8045, #FF8045);
  stop-opacity: 0;
}

.v2d5x5b0b {
  fill: var(--svg-color--2e201f, #2E201F);
  d: path("M17.674 6.743a.8.8 0 0 0-.298-.178c-.132-.042-.297-.053-.525-.025a.12.12 0 0 0 .029.239c.208-.026.336-.012.424.015a.6.6 0 0 1 .212.13a.12.12 0 0 0 .158-.18");
}

.v7xhdx32s {
  stop-color: var(--svg-color--7d465b, #7D465B);
  stop-opacity: 0;
}

.vjbiphb3e {
  fill: var(--svg-color--6f3f46, #6F3F46);
  d: path("m15.883 7.81l-.256.796c-.044.164.06.328.21.328h.317c.148 0 .253-.166.21-.328l-.215-.796c-.046-.177-.218-.177-.267 0");
}

.vm1_cbcaw {
  stop-color: var(--svg-color--90eeff, #90EEFF);
}

.vt36tzbwu {
  fill: var(--svg-color--855954, #855954);
  d: path("m21.499 12.27l-3.144-1.206l-.137 2.175l3.578 1.368c.185.083.652.2 1.039 0s.516-.72.531-.953l.249-4.56a.433.433 0 0 0-.433-.456h-.007a.137.137 0 0 0-.137.137v.48a.344.344 0 0 1-.687 0v-.744a.404.404 0 0 0-.805-.036c-.013.162-.03.366-.047.6c-.037.494.276.836.438.961z");
}

.vvvf-bx0b {
  stop-color: var(--svg-color--93efff, #93EFFF);
}

.vw5e4lbve {
  stop-color: var(--svg-color--ffdd49, #FFDD49);
}

.vx5g9qbgu {
  stop-color: var(--svg-color--815f58, #815F58);
}

.vxhtc9kgk {
  stop-color: var(--svg-color--8bd2ff, #8BD2FF);
}

.w_o-5kbak {
  stop-color: var(--svg-color--7c4c46, #7C4C46);
}

.w0a4mmrgb {
  stop-color: var(--svg-color--200e25, #200E25);
  stop-opacity: 0;
}

.wfj08-bsk {
  stop-color: var(--svg-color--855c58, #855C58);
}

.wpa_x2uhd {
  stop-color: var(--svg-color--855e5a, #855E5A);
  stop-opacity: 0;
}

.x09-01b7i {
  stop-color: var(--svg-color--634689, #634689);
}

.x36zqabyv {
  stop-color: var(--svg-color--c45538, #C45538);
}

.x6_m96bez {
  stop-color: var(--svg-color--85d1fb, #85D1FB);
}

.x9ttejxmc {
  stop-color: var(--svg-color--825d56, #825D56);
}

.xgq6w0b8s {
  d: path("M7.08 15.003c.177-.133.339-.264.43-.342c.416-.346.637-.217.723-.129c.1.103.145.418-.093.696c-.25.29-.51.464-.735.601c-.165.1-.46.088-.582-.062c-.238-.242-.014-.561.256-.764");
}

.xgtw6wrae {
  stop-color: var(--svg-color--8d615b, #8D615B);
  stop-opacity: 0;
}

.xhtzkfsjn {
  d: path("M13.267 16.349v-.82h5.525v.82c-2.337.148-4.276.062-5.525 0");
}

.xlr_mq0xb {
  d: path("M13.87 7.227a.697.697 0 0 0 .056 1.389a34 34 0 0 1-.056-1.39");
}

.xnxf0re5w {
  stop-color: var(--svg-color--ff7e38, #FF7E38);
}

.xo-vurl-f {
  stop-color: var(--svg-color--ff6737, #FF6737);
}

.xron-kbnx {
  stop-color: var(--svg-color--71404f, #71404F);
  stop-opacity: 0;
}

.xzzn0pbnc {
  fill: var(--svg-color--000, #000);
  d: path("M15.332 7.817a.22.22 0 0 0-.222-.221a.22.22 0 0 0-.197.323h.392a.2.2 0 0 0 .027-.102");
}

.y4umwkb_f {
  stop-color: var(--svg-color--865c56, #865C56);
  stop-opacity: 0;
}

.yq1j9wb8r {
  stop-color: var(--svg-color--95726c, #95726C);
  stop-opacity: 0;
}

.ytl8wkbiv {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.403 6.325a.21.21 0 0 0-.417.048l.159 1.385l-1.024-.928a.21.21 0 1 0-.282.311l5.73 5.192a.21.21 0 0 0 .282-.312l-4.235-3.836z");
}

.yvof5m88m {
  stop-color: var(--svg-color--723d48, #723D48);
}

.z_5s59bdn {
  width: 4.843px;
  height: 8.244px;
  rx: 2.422px;
}

.z-0dlhbai {
  stop-color: var(--svg-color--875455, #875455);
  stop-opacity: 0;
}

.z0_tnl66g {
  stop-color: var(--svg-color--6c2d29, #6C2D29);
  stop-opacity: 0;
}

.z30kudb-o {
  cx: 6.572px;
  cy: 15.685px;
  r: 0.438px;
}

.z45oacyxz {
  d: path("m17.397 26.507l-.62 1.014c-.07.116-.233.128-.311.017c-.297-.42-.547-.974-.686-1.358a.55.55 0 0 1 .023-.42l.466-1.017z");
}

.zchm_v6mk {
  d: path("M18.19 8.616q.042-.692.08-1.383a.698.698 0 0 1-.08 1.383");
}

.zd1r_u8ze {
  stop-color: var(--svg-color--6a4e8f, #6A4E8F);
}

.zeih87brn {
  stop-color: var(--svg-color--e43423, #E43423);
  stop-opacity: 0;
}

.zh46g387g {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M23.32 8.935v.258a.9.9 0 0 1-.25.617v0");
}

.zozno708c {
  stop-color: var(--svg-color--9d7d72, #9D7D72);
  stop-opacity: 0;
}

.zqax3vbfg {
  stop-color: var(--svg-color--6c2d29, #6C2D29);
}

.zqff1532o {
  stop-color: var(--svg-color--201524, #201524);
}

</style>
