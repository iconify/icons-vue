<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iAFQx5b)" class="c7q2360tz"/><path fill="url(#iKio9lb)" class="c7q2360tz"/><path fill="url(#ihnU2Jc)" class="db6_2ebdb"/><g filter="url(#iNMtFGc)"><circle fill="url(#itWciSX)" transform="rotate(-10.207 9.759 11.957)" class="elx-xx7vl"/></g><g filter="url(#iffrrfQ)"><circle fill="url(#iHPrv5f)" transform="rotate(-10.207 9.759 11.957)" class="ds04t94_v"/></g><g filter="url(#iFih3Dc)"><circle fill="url(#iFMhE8c)" transform="rotate(-10.207 19.12 10.27)" class="aooawkbvj"/><circle fill="url(#iFiHnnS)" transform="rotate(-10.207 19.12 10.27)" class="aooawkbvj"/></g><g filter="url(#izFZjoc)"><circle transform="rotate(-10.207 19.12 10.271)" class="jv5wfbbwz"/><circle fill="url(#iPWJRoc)" transform="rotate(-10.207 19.12 10.271)" class="adzy3ob3n"/><circle fill="url(#isU2QPd)" transform="rotate(-10.207 19.12 10.271)" class="adzy3ob3n"/></g><g filter="url(#idPBRVb)"><path fill="url(#iL4Nvpe)" class="zf-_6rkpt"/><path fill="url(#igg4GJc)" class="zf-_6rkpt"/><path fill="url(#iA1mLOC)" class="zf-_6rkpt"/><path fill="url(#iNgUUqe)" class="zf-_6rkpt"/><path fill="url(#ilve2oc)" class="zf-_6rkpt"/><path fill="url(#iBsjgni)" class="zf-_6rkpt"/></g><path fill="url(#iIITzKk)" class="zf-_6rkpt"/><g filter="url(#ixvrpdb)"><path class="arpk24n-t"/><path fill="url(#iRSGVOe)" class="x_5m0sb4w"/><path fill="url(#iZlvH4c)" class="x_5m0sb4w"/><path fill="url(#iONKIQe)" class="x_5m0sb4w"/><path fill="url(#ikVuafd)" class="x_5m0sb4w"/><path fill="url(#ihPC9my)" class="x_5m0sb4w"/></g><path fill="url(#iZYa0Ce)" class="x_5m0sb4w"/><path fill="url(#iqYm3xb)" class="x_5m0sb4w"/><g filter="url(#ijN9QDd)"><path class="swsc53bmj"/></g><g filter="url(#iPIhWye)"><path class="gb-6mbcps"/><path fill="url(#iF6kvke)" class="fcbogs3ok"/><path fill="url(#imaQbcc)" class="fcbogs3ok"/><path fill="url(#igPUCHW)" class="fcbogs3ok"/></g><path stroke="url(#izqqREb)" class="av6a-jbun"/><g filter="url(#iuZGjwb)"><circle fill="url(#i417ePc)" class="idc069b1k"/></g><g filter="url(#iOCIehb)"><circle fill="url(#irvBg3b)" class="cbve12bca"/></g><path fill="url(#inN1ILe)" class="qyhj3zowg"/><path fill="url(#inM2y2c)" class="swa2l6hgf"/><g filter="url(#ilYy1nb)"><path stroke="url(#iNnGeDb)" class="ycy65pbdu"/><path stroke="url(#in13w2c)" class="ycy65pbdu"/></g><g filter="url(#imbmWEb)"><path stroke="url(#iihLgud)" class="vq4o9ccce"/><path stroke="url(#i5hGpQb)" class="vq4o9ccce"/></g><path class="ks-mntb1g"/><path fill="url(#ilpofpo)" class="l4zvkhbts"/><path fill="url(#iAcvHRb)" class="l4zvkhbts"/><path fill="url(#i3Lechd)" class="l4zvkhbts"/><path fill="url(#iRNcAEb)" class="l4zvkhbts"/><path fill="url(#iBOZn1c)" class="l4zvkhbts"/><path fill="url(#iY9Jetc)" class="l4zvkhbts"/><path fill="url(#i2lvSqd)" class="l4zvkhbts"/><g filter="url(#iWGK4Jc)"><path fill="url(#i52qmJQ)" class="jb9cwxb-p"/><path fill="url(#i2LHw6d)" class="jb9cwxb-p"/><path fill="url(#iwmD2Db)" class="jb9cwxb-p"/></g><path fill="url(#iaIylBd)" class="zi4jjac0b"/><g filter="url(#iXJFBge)"><path fill="url(#imcw2Db)" class="tz-ih0bsr"/><path fill="url(#iBk9dkb)" class="tz-ih0bsr"/></g><g filter="url(#i3WrbgA)"><path class="vfysexbex"/><path fill="url(#iTA9ned)" class="k4wq9eb1s"/><path fill="url(#iX13dUb)" class="k4wq9eb1s"/><path fill="url(#irqIpGe)" class="k4wq9eb1s"/><path fill="url(#iWuwqfe)" class="k4wq9eb1s"/></g><path fill="url(#iBOucue)" class="eafld2z6o"/><path fill="url(#i6whbyd)" class="eafld2z6o"/><path fill="url(#ixBBUne)" class="kncg08btb"/><path fill="url(#i8Vzoac)" class="kncg08btb"/><path fill="url(#iUub46d)" class="d81ijipjp"/><path fill="url(#iDLgzLe)" class="d81ijipjp"/><path fill="url(#iK55FrY)" class="d81ijipjp"/><path fill="url(#i7uBhTc)" class="z1oeopb3i"/><path fill="url(#iMl2yKd)" class="p4v4psbuh"/><path fill="url(#itA9pEd)" class="m0x-b6bjk"/><path fill="url(#iEOLnkc)" class="m0x-b6bjk"/><path fill="url(#iJBhAmb)" class="m0x-b6bjk"/><g filter="url(#iZQEVWc)"><path stroke="url(#iusuobu)" class="cbjdsc8pn"/></g><path fill="url(#iYKVOQd)" class="qsk_rudxu"/><path fill="url(#idtbTCb)" class="qsk_rudxu"/><path fill="url(#im6zDBb)" class="qwou5rbcb"/><g filter="url(#ieYd15c)"><path fill="url(#ioQjDDd)" class="txtd__b4r"/><path fill="url(#iURQKyc)" class="txtd__b4r"/><path fill="url(#iotMGoZ)" class="txtd__b4r"/></g><path fill="url(#iQhrPMc)" class="z05snt6nn"/><path fill="url(#i4c9nvb)" class="z05snt6nn"/><path fill="url(#iLsHL5c)" class="z05snt6nn"/><path fill="url(#iUKeZvI)" class="z05snt6nn"/><path fill="url(#idcXfld)" class="z05snt6nn"/><path class="y5me6xb0v"/><path fill="url(#iPQ9WOe)" class="mivj2qhld"/><path fill="url(#iu1VtRd)" class="mivj2qhld"/><path class="pkqh0mbji"/><path fill="url(#iReAD2d)" class="xslwfurve"/><path fill="url(#iX01Ind)" class="xslwfurve"/><path fill="url(#ihxcZvc)" class="uf2y99bpi"/><path fill="url(#ixdedGb)" class="uf2y99bpi"/><path fill="url(#i0Gc8iD)" class="uf2y99bpi"/><path fill="url(#iZUEhjc)" class="uf2y99bpi"/><path fill="url(#iJ8usnb)" class="e3q0j7v6e"/><path fill="url(#igZdJlH)" class="e3q0j7v6e"/><path fill="url(#iboR2se)" class="e3q0j7v6e"/><path fill="url(#iUFXSsd)" class="e3q0j7v6e"/><path fill="url(#iukajab)" class="lmrdcczln"/><path fill="url(#iiSY0Sd)" class="lmrdcczln"/><path fill="url(#iXQ696t)" class="lmrdcczln"/><path fill="url(#ielCcxM)" class="lmrdcczln"/><g filter="url(#iMU9YGd)"><path stroke="url(#iAUYj9n)" class="asdx8_q5v"/></g><g filter="url(#iadbN8d)" class="mc2zb0bvp"><path class="g14fqkngc"/></g><g filter="url(#i0CWrwe)" class="mc2zb0bvp"><path class="jq-5_8b0p"/></g><g filter="url(#iaZ6c3c)"><path class="sv8i3wgtb"/></g><g filter="url(#iZ4N5YL)"><path class="czy-_bb7e"/></g><g filter="url(#iw0Fz4d)"><path stroke="url(#ivUtIFd)" class="nyaikfbyz"/></g><g filter="url(#ixgWwjb)"><path stroke="url(#iHC7Rle)" class="bvahb-ydj"/></g><defs><radialGradient id="iKio9lb" cx="0" cy="0" r="1" gradientTransform="rotate(63.107 -6.099 21.736)scale(2.97834 5.11643)" gradientUnits="userSpaceOnUse"><stop offset=".114" class="hb881329x"/><stop offset="1" class="ma7f6291s"/></radialGradient><radialGradient id="itWciSX" cx="0" cy="0" r="1" gradientTransform="matrix(1.75471 0 0 3.07076 8.09 11.957)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="aik_z9b6i"/><stop offset="1" class="k1mq2zvhc"/></radialGradient><radialGradient id="iFiHnnS" cx="0" cy="0" r="1" gradientTransform="matrix(.82663 -.60192 .68701 .9435 19.493 10.006)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="g7lt91bhf"/><stop offset="1" class="ze1cb0iau"/></radialGradient><radialGradient id="iPWJRoc" cx="0" cy="0" r="1" gradientTransform="matrix(.8212 -1.5104 .88405 .48065 19.08 11.092)" gradientUnits="userSpaceOnUse"><stop offset=".69" class="ezktjkbgg"/><stop offset="1" class="j3anadbkm"/></radialGradient><radialGradient id="isU2QPd" cx="0" cy="0" r="1" gradientTransform="matrix(.25926 .25663 -.33084 .33423 19.12 10.271)" gradientUnits="userSpaceOnUse"><stop class="i4pfhbczn"/><stop offset="1" class="xjk10obil"/></radialGradient><radialGradient id="igg4GJc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.25002 8.68749 -10.5841 -3.95955 16.303 8.37)" gradientUnits="userSpaceOnUse"><stop offset=".619" class="a8mmfox5j"/><stop offset="1" class="vm3fdb8rz"/></radialGradient><radialGradient id="iNgUUqe" cx="0" cy="0" r="1" gradientTransform="rotate(-100.207 12.207 -2.179)scale(1.30697 1.60857)" gradientUnits="userSpaceOnUse"><stop class="op2kwubyv"/><stop offset="1" class="wvivicznw"/></radialGradient><radialGradient id="ilve2oc" cx="0" cy="0" r="1" gradientTransform="matrix(-.24645 -1.36874 1.70215 -.30648 12.023 10.223)" gradientUnits="userSpaceOnUse"><stop class="y7nn5tbfc"/><stop offset="1" class="uylyaxbnq"/></radialGradient><radialGradient id="iBsjgni" cx="0" cy="0" r="1" gradientTransform="matrix(1.76563 9.375 -14.97838 2.82093 13.99 8.308)" gradientUnits="userSpaceOnUse"><stop offset=".912" class="hql6ecb5z"/><stop offset=".983" class="qoa6ft6za"/></radialGradient><radialGradient id="iIITzKk" cx="0" cy="0" r="1" gradientTransform="matrix(.9375 7.15625 -1.69492 .22204 19.522 10.776)" gradientUnits="userSpaceOnUse"><stop class="l9p5r2b1o"/><stop offset="1" class="ty92xt-jo"/></radialGradient><radialGradient id="iRSGVOe" cx="0" cy="0" r="1" gradientTransform="matrix(-2.5971 4.9678 -8.44817 -4.4166 16.698 2.87)" gradientUnits="userSpaceOnUse"><stop class="qyobb4hvj"/><stop offset="1" class="szm1jtb2t"/></radialGradient><radialGradient id="iONKIQe" cx="0" cy="0" r="1" gradientTransform="matrix(-.3956 -1.82001 .89385 -.19429 9.693 8.458)" gradientUnits="userSpaceOnUse"><stop offset=".227" class="u7v6tactn"/><stop offset="1" class="hpjuubccm"/></radialGradient><radialGradient id="ikVuafd" cx="0" cy="0" r="1" gradientTransform="matrix(.49704 -2.08742 1.70245 .40537 18.283 8.657)" gradientUnits="userSpaceOnUse"><stop offset=".479" class="ls62f1bvq"/><stop offset="1" class="gx0o3oiqw"/></radialGradient><radialGradient id="ihPC9my" cx="0" cy="0" r="1" gradientTransform="matrix(1.19526 1.03636 -.91503 1.05533 12.144 2.788)" gradientUnits="userSpaceOnUse"><stop class="kxzxrmw_u"/><stop offset="1" class="vs8934bpj"/></radialGradient><radialGradient id="iZYa0Ce" cx="0" cy="0" r="1" gradientTransform="matrix(.31726 .7386 -1.21427 .52158 13.59 2.528)" gradientUnits="userSpaceOnUse"><stop offset=".208" class="dohbdcxhl"/><stop offset="1" class="bb6ud4ewj"/></radialGradient><radialGradient id="iqYm3xb" cx="0" cy="0" r="1" gradientTransform="matrix(.87296 .7545 -1.69055 1.95597 8.937 5.121)" gradientUnits="userSpaceOnUse"><stop class="w-a4mnbis"/><stop offset="1" class="ab4_rnbjl"/></radialGradient><radialGradient id="i417ePc" cx="0" cy="0" r="1" gradientTransform="rotate(-62.622 15.087 -4.218)scale(1.6697 2.16279)" gradientUnits="userSpaceOnUse"><stop offset=".053" class="pfjyiqgya"/><stop offset=".876" class="ro5jldbid"/></radialGradient><radialGradient id="irvBg3b" cx="0" cy="0" r="1" gradientTransform="rotate(-62.622 16.783 -8.354)scale(1.6697 2.16279)" gradientUnits="userSpaceOnUse"><stop offset=".127" class="ps228g2nk"/><stop offset=".535" class="t9y-_dh4s"/></radialGradient><radialGradient id="inN1ILe" cx="0" cy="0" r="1" gradientTransform="matrix(1.34375 -.2187 .3557 2.1855 10.967 11.619)" gradientUnits="userSpaceOnUse"><stop class="b1gl30tyq"/><stop offset="1" class="sk7ylfhdv"/></radialGradient><radialGradient id="inM2y2c" cx="0" cy="0" r="1" gradientTransform="matrix(1.34375 -.2187 .35569 2.1855 15.597 10.81)" gradientUnits="userSpaceOnUse"><stop class="b1gl30tyq"/><stop offset="1" class="sk7ylfhdv"/></radialGradient><radialGradient id="in13w2c" cx="0" cy="0" r="1" gradientTransform="matrix(-.17969 .22656 -.28593 -.22677 13.139 11.253)" gradientUnits="userSpaceOnUse"><stop offset=".18" class="yq-9ytfqn"/><stop offset="1" class="kloinabmx"/><stop offset="1" class="bh1-orbck"/></radialGradient><radialGradient id="i5hGpQb" cx="0" cy="0" r="1" gradientTransform="matrix(-.17969 .22656 -.28593 -.22677 17.769 10.446)" gradientUnits="userSpaceOnUse"><stop offset=".18" class="yq-9ytfqn"/><stop offset="1" class="kloinabmx"/><stop offset="1" class="bh1-orbck"/></radialGradient><radialGradient id="i3Lechd" cx="0" cy="0" r="1" gradientTransform="matrix(3.125 .78125 -.62684 2.50735 8.236 21.406)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="wla505bqs"/><stop offset="1" class="rvju2rlnj"/></radialGradient><radialGradient id="iRNcAEb" cx="0" cy="0" r="1" gradientTransform="rotate(129.369 -1.28 11.594)scale(2.35689 2.29948)" gradientUnits="userSpaceOnUse"><stop offset=".384" class="eb47hsvqu"/><stop offset="1" class="jqpapdb1m"/></radialGradient><radialGradient id="iBOZn1c" cx="0" cy="0" r="1" gradientTransform="matrix(-1.15508 -.34883 2.01874 -6.68469 8.597 30.466)" gradientUnits="userSpaceOnUse"><stop class="hk7wqt7lq"/><stop offset="1" class="g3kr4nmzl"/></radialGradient><radialGradient id="i2lvSqd" cx="0" cy="0" r="1" gradientTransform="matrix(1.82811 2.45314 -3.10932 2.3171 8.845 21.406)" gradientUnits="userSpaceOnUse"><stop offset=".629" class="t1ofhibdm"/><stop offset="1" class="imlvuhvwp"/></radialGradient><radialGradient id="i52qmJQ" cx="0" cy="0" r="1" gradientTransform="matrix(-2.0785 6 -4.46735 -1.54757 16.937 25.246)" gradientUnits="userSpaceOnUse"><stop class="v2wkn2ras"/><stop offset="1" class="yxmxw0ard"/></radialGradient><radialGradient id="i2LHw6d" cx="0" cy="0" r="1" gradientTransform="rotate(-132.901 14.963 10.378)scale(4.22338 6.72611)" gradientUnits="userSpaceOnUse"><stop class="bji58ac7a"/><stop offset="1" class="eqapwmsga"/></radialGradient><radialGradient id="iwmD2Db" cx="0" cy="0" r="1" gradientTransform="matrix(-2.62501 -3.8277 2.0945 -1.4364 21.109 26.184)" gradientUnits="userSpaceOnUse"><stop offset=".393" class="c8r1g2bnk"/><stop offset="1" class="kyl8adb5j"/></radialGradient><radialGradient id="iaIylBd" cx="0" cy="0" r="1" gradientTransform="matrix(-6.038 1.01561 -1.51165 -8.987 27.271 23.295)" gradientUnits="userSpaceOnUse"><stop class="z3zsa5bpu"/><stop offset="1" class="c_p6lvbtv"/></radialGradient><radialGradient id="imcw2Db" cx="0" cy="0" r="1" gradientTransform="rotate(164.954 9.028 12.955)scale(3.00943 4.47011)" gradientUnits="userSpaceOnUse"><stop class="dyh_p3bsl"/><stop offset="1" class="acgtzjb8q"/></radialGradient><radialGradient id="iBk9dkb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.66156 -1.3125 1.73451 -2.1958 22.802 25.966)" gradientUnits="userSpaceOnUse"><stop class="fo4qq4q_b"/><stop offset="1" class="a6ayzxb8w"/></radialGradient><radialGradient id="iTA9ned" cx="0" cy="0" r="1" gradientTransform="rotate(33.14 -38.596 40.664)scale(2.25791 .79383)" gradientUnits="userSpaceOnUse"><stop class="h47r5ibay"/><stop offset="1" class="jjp_mfbio"/></radialGradient><radialGradient id="iX13dUb" cx="0" cy="0" r="1" gradientTransform="matrix(6.57813 0 0 1.16319 12.924 30.465)" gradientUnits="userSpaceOnUse"><stop class="nbcoryb1h"/><stop offset="1" class="r8owzxbqs"/></radialGradient><radialGradient id="iWuwqfe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.02913 0 0 -3.40472 19.265 29.402)" gradientUnits="userSpaceOnUse"><stop offset=".083" class="uxh2dv17l"/><stop offset="1" class="u1zlaqbml"/></radialGradient><radialGradient id="iBOucue" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.70313 -.62842 0 19.627 28.656)" gradientUnits="userSpaceOnUse"><stop offset=".431" class="hdo03nb1p"/><stop offset="1" class="b26wppbkf"/></radialGradient><radialGradient id="i8Vzoac" cx="0" cy="0" r="1" gradientTransform="rotate(168.154 12.809 14.988)scale(6.54566 1.70736)" gradientUnits="userSpaceOnUse"><stop class="s231-6bjz"/><stop offset="1" class="s6qjzwjgb"/></radialGradient><radialGradient id="iUub46d" cx="0" cy="0" r="1" gradientTransform="matrix(.84204 2.73001 -2.93117 .90409 6.765 20.34)" gradientUnits="userSpaceOnUse"><stop class="ol95frboa"/><stop offset="1" class="i5qbulbys"/></radialGradient><radialGradient id="iDLgzLe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.28125 .87171 -.46263 -.67998 9.906 21.312)" gradientUnits="userSpaceOnUse"><stop offset=".216" class="py7fiqzvo"/><stop offset="1" class="rkoscyb2g"/></radialGradient><radialGradient id="iK55FrY" cx="0" cy="0" r="1" gradientTransform="matrix(.32031 .75 -.43392 .18532 7.164 20.95)" gradientUnits="userSpaceOnUse"><stop offset=".827" class="yassptbsb"/><stop offset="1" class="g6isq_a6x"/></radialGradient><radialGradient id="iJBhAmb" cx="0" cy="0" r="1" gradientTransform="matrix(-.3711 1.25391 -.1532 -.04534 16.01 18.94)" gradientUnits="userSpaceOnUse"><stop class="tomvu1bgl"/><stop offset="1" class="sinn-3bvk"/></radialGradient><radialGradient id="iusuobu" cx="0" cy="0" r="1" gradientTransform="matrix(-.20313 -.60156 1.71998 -.58078 9.312 23.481)" gradientUnits="userSpaceOnUse"><stop class="rihdlqb3v"/><stop offset="1" class="x7yh0i-6p"/></radialGradient><radialGradient id="idtbTCb" cx="0" cy="0" r="1" gradientTransform="matrix(-.64063 2 -.16496 -.05284 15.822 18.281)" gradientUnits="userSpaceOnUse"><stop class="njdbcpw8w"/><stop offset="1" class="p6n8nbb9p"/></radialGradient><radialGradient id="iURQKyc" cx="0" cy="0" r="1" gradientTransform="rotate(25.805 -35.675 34.487)scale(1.57936 1.44294)" gradientUnits="userSpaceOnUse"><stop offset=".127" class="l8v5z5bog"/><stop offset="1" class="ll6ec2bpd"/></radialGradient><radialGradient id="i4c9nvb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.0156 3.18752 -2.63101 -1.6637 9.455 18.927)" gradientUnits="userSpaceOnUse"><stop offset=".556" class="b1a3scalr"/><stop offset="1" class="z_gh6vsyy"/></radialGradient><radialGradient id="iLsHL5c" cx="0" cy="0" r="1" gradientTransform="rotate(119.595 -.185 11.96)scale(3.70167 1.33422)" gradientUnits="userSpaceOnUse"><stop offset=".269" class="ie-bysyvv"/><stop offset="1" class="bpneozbdy"/></radialGradient><radialGradient id="iUKeZvI" cx="0" cy="0" r="1" gradientTransform="matrix(-.1359 3.04807 -.73147 -.03261 7.275 18.583)" gradientUnits="userSpaceOnUse"><stop class="uxpb5qzbn"/><stop offset="1" class="ip8fcq0ak"/></radialGradient><radialGradient id="idcXfld" cx="0" cy="0" r="1" gradientTransform="matrix(.15625 1.04772 -1.07633 .16051 9.01 21.107)" gradientUnits="userSpaceOnUse"><stop offset=".28" class="ohwd33b2n"/><stop offset="1" class="y0dl1gblq"/></radialGradient><radialGradient id="iPQ9WOe" cx="0" cy="0" r="1" gradientTransform="matrix(.03125 -.93275 3.89243 .13041 12.72 17.99)" gradientUnits="userSpaceOnUse"><stop offset=".329" class="nu_77rrcl"/><stop offset="1" class="dnayrdbzp"/></radialGradient><radialGradient id="iu1VtRd" cx="0" cy="0" r="1" gradientTransform="rotate(153.435 5.213 10.049)scale(.78612 .35637)" gradientUnits="userSpaceOnUse"><stop class="sok9f40_l"/><stop offset="1" class="jg12b2kug"/></radialGradient><radialGradient id="iReAD2d" cx="0" cy="0" r="1" gradientTransform="rotate(-80.715 17.489 2.517)scale(.83681 3.75171)" gradientUnits="userSpaceOnUse"><stop offset=".09" class="sg8a2viwh"/><stop offset="1" class="vsvz-xe_v"/></radialGradient><radialGradient id="iX01Ind" cx="0" cy="0" r="1" gradientTransform="matrix(-1.0625 .41406 -.20022 -.51377 13.814 17.987)" gradientUnits="userSpaceOnUse"><stop offset=".283" class="dzyo4sbbn"/><stop offset="1" class="o-ef0ac2e"/></radialGradient><radialGradient id="ihxcZvc" cx="0" cy="0" r="1" gradientTransform="matrix(-.8125 1.51562 -5.32458 -2.85442 11.142 19.239)" gradientUnits="userSpaceOnUse"><stop offset=".243" class="zx-utrb8d"/><stop offset="1" class="rb5pqrony"/></radialGradient><radialGradient id="ixdedGb" cx="0" cy="0" r="1" gradientTransform="matrix(2.29688 1.78687 -.45885 .58982 11.517 19.51)" gradientUnits="userSpaceOnUse"><stop offset=".254" class="kaygmvbyu"/><stop offset="1" class="zq2cu-lqa"/></radialGradient><radialGradient id="i0Gc8iD" cx="0" cy="0" r="1" gradientTransform="rotate(136.002 2.334 12.063)scale(.96996 1.97716)" gradientUnits="userSpaceOnUse"><stop offset=".139" class="kwfaklb2u"/><stop offset="1" class="a3cf45xpc"/></radialGradient><radialGradient id="iZUEhjc" cx="0" cy="0" r="1" gradientTransform="matrix(.48047 -.3496 .60677 .83392 8.94 19.317)" gradientUnits="userSpaceOnUse"><stop offset=".269" class="kss7lepmr"/><stop offset="1" class="z8oy8ibbe"/></radialGradient><radialGradient id="iJ8usnb" cx="0" cy="0" r="1" gradientTransform="matrix(1.09945 -1.69165 1.88005 1.2219 8.87 21.935)" gradientUnits="userSpaceOnUse"><stop offset=".407" class="fjk2vysly"/><stop offset="1" class="pll5kd_nw"/></radialGradient><radialGradient id="igZdJlH" cx="0" cy="0" r="1" gradientTransform="matrix(1.15625 .84935 -.34383 .46806 10.768 20.489)" gradientUnits="userSpaceOnUse"><stop offset=".06" class="tjgs2ub-w"/><stop offset="1" class="jtvtg3bqw"/></radialGradient><radialGradient id="iboR2se" cx="0" cy="0" r="1" gradientTransform="rotate(97.522 -3.862 14.691)scale(2.32995 4.84987)" gradientUnits="userSpaceOnUse"><stop offset=".651" class="aiyo-ztfk"/><stop offset=".962" class="tlxyqtbtq"/></radialGradient><radialGradient id="iUFXSsd" cx="0" cy="0" r="1" gradientTransform="matrix(.54646 -.48802 1.62742 1.82231 7.87 21.251)" gradientUnits="userSpaceOnUse"><stop class="j4c7dkb7m"/><stop offset="1" class="gt-69vbgu"/></radialGradient><radialGradient id="iiSY0Sd" cx="0" cy="0" r="1" gradientTransform="rotate(105.675 .856 16.03)scale(1.31451 .34383)" gradientUnits="userSpaceOnUse"><stop class="cn05xwrkd"/><stop offset="1" class="k_pdrlblj"/><stop offset="1" class="n8jici3hn"/></radialGradient><radialGradient id="iXQ696t" cx="0" cy="0" r="1" gradientTransform="rotate(105.036 .737 16.506)scale(.54206 .1592)" gradientUnits="userSpaceOnUse"><stop class="em3lc9y5i"/><stop offset="1" class="k_pdrlblj"/><stop offset="1" class="n8jici3hn"/></radialGradient><radialGradient id="ielCcxM" cx="0" cy="0" r="1" gradientTransform="rotate(174.906 8.344 10.523)scale(.43997 .38553)" gradientUnits="userSpaceOnUse"><stop class="tzj34xnjq"/><stop offset="1" class="ugbytbngn"/></radialGradient><radialGradient id="iAUYj9n" cx="0" cy="0" r="1" gradientTransform="matrix(-.26365 -2.21465 3.37212 -.40144 7.768 22.28)" gradientUnits="userSpaceOnUse"><stop class="zxch6_gap"/><stop offset="1" class="upwmevb9h"/></radialGradient><linearGradient id="iAFQx5b" x1="19.224" x2="12.336" y1="19.07" y2="30.747" gradientUnits="userSpaceOnUse"><stop class="hvtvasx8l"/><stop offset="1" class="sdatcx1hi"/></linearGradient><linearGradient id="ihnU2Jc" x1="14.991" x2="17.053" y1="17.276" y2="18.339" gradientUnits="userSpaceOnUse"><stop offset=".177" class="bgziafb-g"/><stop offset="1" class="lsyue1afr"/></linearGradient><linearGradient id="iHPrv5f" x1="9.759" x2="9.118" y1="12.235" y2="12.235" gradientUnits="userSpaceOnUse"><stop class="s236rjbsc"/><stop offset="1" class="o6sle6pni"/></linearGradient><linearGradient id="iFMhE8c" x1="20.207" x2="19.388" y1="9.179" y2="11.715" gradientUnits="userSpaceOnUse"><stop class="kwz3apblc"/><stop offset="1" class="gx0xrfbie"/></linearGradient><linearGradient id="iL4Nvpe" x1="18.472" x2="11.158" y1="10.784" y2="13.257" gradientUnits="userSpaceOnUse"><stop class="b941pszbd"/><stop offset="1" class="jtnk9gb3a"/></linearGradient><linearGradient id="iA1mLOC" x1="9.668" x2="11.89" y1="15.108" y2="14.402" gradientUnits="userSpaceOnUse"><stop class="ls27mhbfe"/><stop offset="1" class="ys1ri2qqc"/></linearGradient><linearGradient id="iZlvH4c" x1="9.6" x2="11.542" y1="11.713" y2="6.126" gradientUnits="userSpaceOnUse"><stop class="ts8ii3fly"/><stop offset="1" class="zlpmx2b9v"/></linearGradient><linearGradient id="iF6kvke" x1="13.766" x2="14.69" y1="12.301" y2="12.134" gradientUnits="userSpaceOnUse"><stop class="gs643vbjw"/><stop offset="1" class="v4v-qb7kx"/></linearGradient><linearGradient id="imaQbcc" x1="15.598" x2="14.586" y1="12.299" y2="12.466" gradientUnits="userSpaceOnUse"><stop class="sbp9bz1ap"/><stop offset="1" class="xrkexibub"/></linearGradient><linearGradient id="igPUCHW" x1="14.997" x2="14.895" y1="13.161" y2="12.597" gradientUnits="userSpaceOnUse"><stop class="rxh459f4v"/><stop offset="1" class="lemuo5beu"/></linearGradient><linearGradient id="izqqREb" x1="14.071" x2="14.377" y1="14.969" y2="14.215" gradientUnits="userSpaceOnUse"><stop class="pn2_jabhi"/><stop offset=".663" class="z9945l-5h"/></linearGradient><linearGradient id="iNnGeDb" x1="11.061" x2="13.342" y1="11.661" y2="11.816" gradientUnits="userSpaceOnUse"><stop class="wiexblb8s"/><stop offset="1" class="cbopwmb0o"/></linearGradient><linearGradient id="iihLgud" x1="15.691" x2="17.972" y1="10.853" y2="11.008" gradientUnits="userSpaceOnUse"><stop class="wiexblb8s"/><stop offset="1" class="cbopwmb0o"/></linearGradient><linearGradient id="ilpofpo" x1="9.109" x2="3.64" y1="26.778" y2="25.309" gradientUnits="userSpaceOnUse"><stop class="ena81bblx"/><stop offset="1" class="hjax-mb0n"/></linearGradient><linearGradient id="iAcvHRb" x1="3.515" x2="5.486" y1="26.403" y2="26.969" gradientUnits="userSpaceOnUse"><stop class="eyx6dtigb"/><stop offset="1" class="uels9hbwx"/></linearGradient><linearGradient id="iY9Jetc" x1="9.229" x2="8.836" y1="28.796" y2="28.671" gradientUnits="userSpaceOnUse"><stop class="hkmz0xbqe"/><stop offset="1" class="s03vqlghs"/></linearGradient><linearGradient id="irqIpGe" x1="18.227" x2="17.567" y1="26.74" y2="27.634" gradientUnits="userSpaceOnUse"><stop offset=".175" class="jl9fiab1w"/><stop offset="1" class="j9aoxmbfm"/></linearGradient><linearGradient id="i6whbyd" x1="19.523" x2="19.437" y1="27.028" y2="27.536" gradientUnits="userSpaceOnUse"><stop class="byw39cbfh"/><stop offset="1" class="uvoxmwj8v"/></linearGradient><linearGradient id="ixBBUne" x1="26.546" x2="26.984" y1="27.246" y2="30.965" gradientUnits="userSpaceOnUse"><stop class="gf4r80b0w"/><stop offset="1" class="jd4hd8b4a"/></linearGradient><linearGradient id="i7uBhTc" x1="11.144" x2="10.997" y1="22.538" y2="19.895" gradientUnits="userSpaceOnUse"><stop class="fu3c0cblo"/><stop offset="1" class="pdon63boo"/></linearGradient><linearGradient id="iMl2yKd" x1="12.351" x2="11.964" y1="20.729" y2="18.747" gradientUnits="userSpaceOnUse"><stop class="fu3c0cblo"/><stop offset="1" class="pdon63boo"/></linearGradient><linearGradient id="itA9pEd" x1="16.078" x2="15.296" y1="18.527" y2="21.514" gradientUnits="userSpaceOnUse"><stop class="e6bcurcdv"/><stop offset="1" class="jxwnoqbqn"/></linearGradient><linearGradient id="iEOLnkc" x1="15.205" x2="15.428" y1="21.734" y2="20.843" gradientUnits="userSpaceOnUse"><stop class="w_57dfb5m"/><stop offset="1" class="t78i98bfv"/></linearGradient><linearGradient id="iYKVOQd" x1="14.953" x2="13.828" y1="17.762" y2="22.09" gradientUnits="userSpaceOnUse"><stop class="nn3wh7bnm"/><stop offset="1" class="tbs366q3s"/></linearGradient><linearGradient id="im6zDBb" x1="15.265" x2="14.155" y1="18.137" y2="17.778" gradientUnits="userSpaceOnUse"><stop class="h94nvm15h"/><stop offset="1" class="qtvy6rbzh"/></linearGradient><linearGradient id="ioQjDDd" x1="14.452" x2="13.223" y1="17.653" y2="22.403" gradientUnits="userSpaceOnUse"><stop class="qic_n_blg"/><stop offset="1" class="qh-ows9fr"/></linearGradient><linearGradient id="iotMGoZ" x1="12.549" x2="12.767" y1="21.468" y2="20.39" gradientUnits="userSpaceOnUse"><stop class="e122-lbju"/><stop offset="1" class="grqmao4rm"/></linearGradient><linearGradient id="iQhrPMc" x1="8.421" x2="8.964" y1="17.153" y2="21.653" gradientUnits="userSpaceOnUse"><stop class="rvz7hrbgf"/><stop offset="1" class="c6pq05twi"/></linearGradient><linearGradient id="iukajab" x1="16.521" x2="15.937" y1="19.027" y2="21.527" gradientUnits="userSpaceOnUse"><stop class="neym138jd"/><stop offset="1" class="kmp3a3cnr"/></linearGradient><linearGradient id="ivUtIFd" x1="16.866" x2="16.3" y1="7.865" y2="7.094" gradientUnits="userSpaceOnUse"><stop class="pqf0u3bgb"/><stop offset="1" class="xogpiobqs"/></linearGradient><linearGradient id="iHC7Rle" x1="11.623" x2="10.364" y1="8.679" y2="8.399" gradientUnits="userSpaceOnUse"><stop class="pqf0u3bgb"/><stop offset="1" class="xogpiobqs"/></linearGradient><filter id="iNMtFGc" width="3.539" height="3.339" x="8.089" y="10.287" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.866667 0 0 0 0 0.643137 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3543"/></filter><filter id="iffrrfQ" width="2.99" height="2.99" x="8.264" y="10.461" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3543" stdDeviation=".25"/></filter><filter id="iFih3Dc" width="3.589" height="3.589" x="17.451" y="8.351" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.768627 0 0 0 0 0.529412 0 0 0 0 0.505882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3543"/></filter><filter id="izFZjoc" width="2.99" height="2.99" x="17.625" y="8.776" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3543" stdDeviation=".25"/></filter><filter id="idPBRVb" width="10.835" height="12.629" x="8.975" y="5.274" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.752941 0 0 0 0 0.501961 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3543"/></filter><filter id="ixvrpdb" width="12.457" height="9.495" x="7.409" y="1.925" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.858824 0 0 0 0 0.690196 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3543"/></filter><filter id="ijN9QDd" width="3.25" height="4.242" x="12.879" y="9.979" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3543" stdDeviation=".375"/></filter><filter id="iPIhWye" width="2.363" height="3.224" x="13.528" y="10.3" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3543" stdDeviation=".125"/></filter><filter id="iuZGjwb" width="3.987" height="3.987" x="10.06" y="8.722" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3543" stdDeviation=".325"/></filter><filter id="iOCIehb" width="3.987" height="3.987" x="14.649" y="7.993" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3543" stdDeviation=".325"/></filter><filter id="ilYy1nb" width="2.323" height=".964" x="10.966" y="11.135" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3543" stdDeviation=".05"/></filter><filter id="imbmWEb" width="2.323" height=".964" x="15.595" y="10.327" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3543" stdDeviation=".05"/></filter><filter id="iWGK4Jc" width="11.192" height="8.359" x="11.466" y="22.356" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.290196 0 0 0 0 0.607843 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3543"/></filter><filter id="iXJFBge" width="7.407" height="8.444" x="19.048" y="19.185" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.258824 0 0 0 0 0.67451 0 0 0 0 0.45098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3543"/></filter><filter id="i3WrbgA" width="8.208" height="4.667" x="12.416" y="25.798" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.717647 0 0 0 0 0.505882 0 0 0 0 0.443137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3543"/></filter><filter id="iZQEVWc" width="3.456" height="1.701" x="7.38" y="22.268" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3543" stdDeviation=".1"/></filter><filter id="ieYd15c" width="4.309" height="4.662" x="11.043" y="16.93" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.533333 0 0 0 0 0.552941 0 0 0 0 0.619608 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3543"/></filter><filter id="iMU9YGd" width="3.647" height="2.753" x="6.263" y="20.015" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3543" stdDeviation=".05"/></filter><filter id="iadbN8d" width="2.634" height="2.141" x="16.374" y="26.255" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3543" stdDeviation=".125"/></filter><filter id="i0CWrwe" width="4.536" height="1" x="12.746" y="29.061" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3543" stdDeviation=".15"/></filter><filter id="iaZ6c3c" width="3.02" height="1.675" x="15.11" y="7.102" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.262745 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3543"/></filter><filter id="iZ4N5YL" width="2.887" height="2.131" x="10.111" y="7.853" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.262745 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3543"/></filter><filter id="iw0Fz4d" width="3.14" height="1.467" x="14.932" y="7.224" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3543" stdDeviation=".25"/></filter><filter id="ixgWwjb" width="3.066" height="2.037" x="9.888" y="8.025" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3543" stdDeviation=".25"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-feeding-baby-medium-light" /></template>
<style>
.a3cf45xpc {
  stop-color: var(--svg-color--bf8a6b, #BF8A6B);
  stop-opacity: 0;
}

.a6ayzxb8w {
  stop-color: var(--svg-color--289d47, #289D47);
  stop-opacity: 0;
}

.a8mmfox5j {
  stop-color: var(--svg-color--c49881, #C49881);
  stop-opacity: 0;
}

.ab4_rnbjl {
  stop-color: var(--svg-color--dcc291, #DCC291);
  stop-opacity: 0;
}

.acgtzjb8q {
  stop-color: var(--svg-color--3ba055, #3BA055);
}

.adzy3ob3n {
  cx: 19.12px;
  cy: 10.271px;
  r: 0.995px;
}

.aik_z9b6i {
  stop-color: var(--svg-color--c28775, #C28775);
}

.aiyo-ztfk {
  stop-color: var(--svg-color--b56e74, #B56E74);
  stop-opacity: 0;
}

.aooawkbvj {
  cx: 19.121px;
  cy: 10.27px;
  r: 1.669px;
}

.arpk24n-t {
  fill: var(--svg-color--ebcc94, #EBCC94);
  d: path("m18.025 3.887l.46.133c.806.235 1.38.998 1.381 1.92l-.042 3.095c.004.319-.163.563-.468.626l-.018.004s-.108-.902-.15-1.436c-.033-.434-.131-.55-.592-.869c-.249-.172-.464-.458-.52-.773l-.152-.84c-.047-.262-.296-.434-.516-.449c-.662-.043-2.03-.068-3.93.274s-3.172.842-3.777 1.114a.52.52 0 0 0-.328.6l.151.84c.057.315.008.65-.218.907l-.13.186c-.183.195-.232.53-.185.792c.157.567.361 1.398.361 1.398l-.048.007a.63.63 0 0 1-.68-.418L7.505 8.11c-.257-.821.014-1.737.687-2.237l.385-.286c.235-.205.461-.463.687-.72l.771-1.168c.486-.63 1.302-.94 2.108-.705a2.94 2.94 0 0 0 1.636-.295c.745-.405 1.68-.356 2.417.107l.934.645c.258.224.55.334.895.435");
}

.asdx8_q5v {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M6.593 20.215c-.206.433-.319 1.449.875 2.055s1.992.149 2.242-.156");
}

.av6a-jbun {
  fill: var(--svg-color--88024e, #88024E);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M13.58 14.07c.423.132.905.165 1.397.076a2.94 2.94 0 0 0 1.283-.558a.2.2 0 0 1 .245-.004a.19.19 0 0 1 .063.234m-2.989.252l2.943-.272m-2.943.272a.2.2 0 0 0-.23.084a.19.19 0 0 0 .022.24m.208-.324l-.173.289m3.162-.541l-.046-.02m.046.02l-.046-.02m.046.02a1.94 1.94 0 0 1-1.445 1.142a1.94 1.94 0 0 1-1.752-.566m3.151-.596c-.24.558-.754.995-1.408 1.113a1.9 1.9 0 0 1-1.708-.552m-.035.035l.035-.035m-.035.035l.035-.035");
}

.b1a3scalr {
  stop-color: var(--svg-color--b57176, #B57176);
  stop-opacity: 0;
}

.b1gl30tyq {
  stop-color: var(--svg-color--844c26, #844C26);
}

.b26wppbkf {
  stop-color: var(--svg-color--286ad9, #286AD9);
}

.b941pszbd {
  stop-color: var(--svg-color--fac39e, #FAC39E);
}

.bb6ud4ewj {
  stop-color: var(--svg-color--e1d19f, #E1D19F);
  stop-opacity: 0;
}

.bgziafb-g {
  stop-color: var(--svg-color--947175, #947175);
}

.bh1-orbck {
  stop-color: var(--svg-color--98643a, #98643A);
  stop-opacity: 0;
}

.bji58ac7a {
  stop-color: var(--svg-color--208d47, #208D47);
}

.bpneozbdy {
  stop-color: var(--svg-color--dbac8a, #DBAC8A);
  stop-opacity: 0;
}

.bvahb-ydj {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M10.513 9.437c.27-.343.92-.769 1.816-.787");
}

.byw39cbfh {
  stop-color: var(--svg-color--0e6996, #0E6996);
}

.c_p6lvbtv {
  stop-color: var(--svg-color--31be7d, #31BE7D);
}

.c6pq05twi {
  stop-color: var(--svg-color--be8777, #BE8777);
}

.c7q2360tz {
  d: path("M7.155 30.465c-1.05 0-1.9-.85-1.89-1.9l.01-2.13c0-5.77 4.79-10.46 10.69-10.46c5.91 0 10.69 4.68 10.69 10.46l.17 4.03z");
}

.c8r1g2bnk {
  stop-color: var(--svg-color--148c3e, #148C3E);
}

.cbjdsc8pn {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M7.78 23.497c.579.14 1.92.172 2.657-.828");
}

.cbopwmb0o {
  stop-color: var(--svg-color--9a663d, #9A663D);
  stop-opacity: 0;
}

.cbve12bca {
  cx: 16.643px;
  cy: 9.987px;
  r: 1.344px;
}

.cn05xwrkd {
  stop-color: var(--svg-color--fed466, #FED466);
}

.czy-_bb7e {
  fill: var(--svg-color--9a6634, #9A6634);
  d: path("m10.236 9.107l.002-.002l.003-.004l.01-.012a1.4 1.4 0 0 1 .134-.133c.087-.08.212-.18.376-.282a2.83 2.83 0 0 1 1.44-.42a.534.534 0 0 1 .023 1.067a1.77 1.77 0 0 0-.901.26a1.5 1.5 0 0 0-.274.218a.534.534 0 0 1-.814-.69");
}

.d81ijipjp {
  d: path("M10.214 22.152c-.284.88-1.448 1.292-2.6.92c-1.152-.371-1.793-1.177-1.573-2.266c.18-.888.884-1.75 2.739-1.24c1.152.372 1.718 1.706 1.434 2.586");
}

.db6_2ebdb {
  d: path("M15.685 18.996c1.06 0 1.91-.86 1.91-1.91v-2.26a1.91 1.91 0 1 0-3.82 0v2.26c-.01 1.06.85 1.91 1.91 1.91");
}

.dnayrdbzp {
  stop-color: var(--svg-color--c7977a, #C7977A);
  stop-opacity: 0;
}

.dohbdcxhl {
  stop-color: var(--svg-color--e1d19f, #E1D19F);
}

.ds04t94_v {
  cx: 9.759px;
  cy: 11.957px;
  r: 0.995px;
}

.dyh_p3bsl {
  stop-color: var(--svg-color--279f64, #279F64);
}

.dzyo4sbbn {
  stop-color: var(--svg-color--eabea3, #EABEA3);
}

.e122-lbju {
  stop-color: var(--svg-color--8b72aa, #8B72AA);
}

.e3q0j7v6e {
  d: path("M8.857 21.395c-.315.22-.723.21-.906-.11c-.391-.948.721-1.579 1.5-1.597c1.168-.027 1.75.629 1.937 1.12c.188.493.227 1.477-.671 1.54c-.804.056-.848-.5-.981-.742s-.594-.41-.879-.211");
}

.e6bcurcdv {
  stop-color: var(--svg-color--6cd9f5, #6CD9F5);
}

.eafld2z6o {
  d: path("M18.998 27.248a.15.15 0 0 1 .15-.15h.643v3.367h-.793z");
}

.eb47hsvqu {
  stop-color: var(--svg-color--2170a2, #2170A2);
}

.elx-xx7vl {
  cx: 9.759px;
  cy: 11.957px;
  r: 1.669px;
}

.em3lc9y5i {
  stop-color: var(--svg-color--fed064, #FED064);
}

.ena81bblx {
  stop-color: var(--svg-color--2f71f9, #2F71F9);
}

.eqapwmsga {
  stop-color: var(--svg-color--208d47, #208D47);
  stop-opacity: 0;
}

.eyx6dtigb {
  stop-color: var(--svg-color--4e83c4, #4E83C4);
}

.ezktjkbgg {
  stop-color: var(--svg-color--d79a76, #D79A76);
  stop-opacity: 0;
}

.fcbogs3ok {
  d: path("m14.004 10.903l-.221 1.766a.54.54 0 0 0 .636.596l.773-.14a.54.54 0 0 0 .389-.78l-.824-1.578c-.18-.35-.702-.256-.753.136");
}

.fjk2vysly {
  stop-color: var(--svg-color--ba7a7c, #BA7A7C);
}

.fo4qq4q_b {
  stop-color: var(--svg-color--289d47, #289D47);
}

.ft5dv1b6b {
  fill: none;
}

.fu3c0cblo {
  stop-color: var(--svg-color--f38820, #F38820);
}

.g14fqkngc {
  stroke: var(--svg-color--e2b79f, #E2B79F);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("m16.874 26.755l1.635 1.141");
}

.g3kr4nmzl {
  stop-color: var(--svg-color--317ff4, #317FF4);
  stop-opacity: 0;
}

.g6isq_a6x {
  stop-color: var(--svg-color--1a3f75, #1A3F75);
  stop-opacity: 0;
}

.g7lt91bhf {
  stop-color: var(--svg-color--e3ab88, #E3AB88);
}

.gb-6mbcps {
  fill: var(--svg-color--e4ac8f, #E4AC8F);
  d: path("m14.004 10.903l-.221 1.766a.54.54 0 0 0 .636.596l.773-.14a.54.54 0 0 0 .389-.78l-.824-1.578c-.18-.35-.702-.256-.753.136");
}

.gf4r80b0w {
  stop-color: var(--svg-color--27a9f1, #27A9F1);
}

.grqmao4rm {
  stop-color: var(--svg-color--b59cc2, #B59CC2);
  stop-opacity: 0;
}

.gs643vbjw {
  stop-color: var(--svg-color--cb9173, #CB9173);
}

.gt-69vbgu {
  stop-color: var(--svg-color--bb8072, #BB8072);
  stop-opacity: 0;
}

.gx0o3oiqw {
  stop-color: var(--svg-color--e3ab85, #E3AB85);
  stop-opacity: 0;
}

.gx0xrfbie {
  stop-color: var(--svg-color--dca189, #DCA189);
}

.h47r5ibay {
  stop-color: var(--svg-color--bd8677, #BD8677);
}

.h94nvm15h {
  stop-color: var(--svg-color--43b1db, #43B1DB);
}

.hb881329x {
  stop-color: var(--svg-color--1c8ec9, #1C8EC9);
}

.hdo03nb1p {
  stop-color: var(--svg-color--2176c7, #2176C7);
}

.hjax-mb0n {
  stop-color: var(--svg-color--246bda, #246BDA);
}

.hk7wqt7lq {
  stop-color: var(--svg-color--5289f2, #5289F2);
}

.hkmz0xbqe {
  stop-color: var(--svg-color--1e7eee, #1E7EEE);
}

.hpjuubccm {
  stop-color: var(--svg-color--eec19c, #EEC19C);
  stop-opacity: 0;
}

.hql6ecb5z {
  stop-color: var(--svg-color--a87f7d, #A87F7D);
  stop-opacity: 0;
}

.hvtvasx8l {
  stop-color: var(--svg-color--2ba6ec, #2BA6EC);
}

.i4pfhbczn {
  stop-color: var(--svg-color--cb8e6d, #CB8E6D);
}

.i5qbulbys {
  stop-color: var(--svg-color--1f70cf, #1F70CF);
}

.idc069b1k {
  cx: 12.054px;
  cy: 10.715px;
  r: 1.344px;
}

.ie-bysyvv {
  stop-color: var(--svg-color--dbac8a, #DBAC8A);
}

.imlvuhvwp {
  stop-color: var(--svg-color--2e71f4, #2E71F4);
  stop-opacity: 0;
}

.ip8fcq0ak {
  stop-color: var(--svg-color--cd9b7f, #CD9B7F);
  stop-opacity: 0;
}

.j3anadbkm {
  stop-color: var(--svg-color--d79a76, #D79A76);
}

.j4c7dkb7m {
  stop-color: var(--svg-color--b97d70, #B97D70);
}

.j9aoxmbfm {
  stop-color: var(--svg-color--cfae8c, #CFAE8C);
  stop-opacity: 0;
}

.jb9cwxb-p {
  d: path("M21.835 24.485c-1.17-2.04-3.78-2.73-5.81-1.56l-2.43 1.4c-2.04 1.17-2.73 3.78-1.56 5.81l.21.33h7.73l.3-.18a4.23 4.23 0 0 0 1.56-5.8");
}

.jd4hd8b4a {
  stop-color: var(--svg-color--297eff, #297EFF);
}

.jg12b2kug {
  stop-color: var(--svg-color--efc3a5, #EFC3A5);
  stop-opacity: 0;
}

.jjp_mfbio {
  stop-color: var(--svg-color--bd8677, #BD8677);
  stop-opacity: 0;
}

.jl9fiab1w {
  stop-color: var(--svg-color--cfae8c, #CFAE8C);
}

.jq-5_8b0p {
  stroke: var(--svg-color--e1ae9b, #E1AE9B);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M13.246 29.561h3.536");
}

.jqpapdb1m {
  stop-color: var(--svg-color--2374a5, #2374A5);
  stop-opacity: 0;
}

.jtnk9gb3a {
  stop-color: var(--svg-color--c9917c, #C9917C);
}

.jtvtg3bqw {
  stop-color: var(--svg-color--efc3a7, #EFC3A7);
  stop-opacity: 0;
}

.jv5wfbbwz {
  cx: 19.12px;
  cy: 10.271px;
  r: 0.995px;
  fill: var(--svg-color--d79e81, #D79E81);
}

.jxwnoqbqn {
  stop-color: var(--svg-color--3782ce, #3782CE);
}

.k_pdrlblj {
  stop-color: var(--svg-color--ebb830, #EBB830);
  stop-opacity: 0;
}

.k1mq2zvhc {
  stop-color: var(--svg-color--ba7867, #BA7867);
}

.k4wq9eb1s {
  d: path("M17.18 26.147a.937.937 0 0 0-1.12 1.498l.931.801a.1.1 0 0 1-.063.176l-3.644.072a.886.886 0 0 0 .018 1.77h6.06v-1l1.062-1.226z");
}

.kaygmvbyu {
  stop-color: var(--svg-color--e3b69c, #E3B69C);
}

.kloinabmx {
  stop-color: var(--svg-color--c26f5c, #C26F5C);
  stop-opacity: 0;
}

.kmp3a3cnr {
  stop-color: var(--svg-color--ce953a, #CE953A);
}

.kncg08btb {
  d: path("M20.616 26.242c1.597-.23 4.566-.808 6.542-1.27c1.522-.262 2.641 1.204 2.641 2.782c0 1.37-1.022 2.236-1.747 2.618a.86.86 0 0 1-.403.093h-8.014v-3.086c0-.797.281-1 .98-1.137");
}

.ks-mntb1g {
  fill: var(--svg-color--58b2ec, #58B2EC);
  d: path("m29.145 25.805l-4.94-6.05l-3.16 8.57z");
}

.kss7lepmr {
  stop-color: var(--svg-color--d1a082, #D1A082);
}

.kwfaklb2u {
  stop-color: var(--svg-color--bf8a6b, #BF8A6B);
}

.kwz3apblc {
  stop-color: var(--svg-color--f5c8a5, #F5C8A5);
}

.kxzxrmw_u {
  stop-color: var(--svg-color--fbecaf, #FBECAF);
}

.kyl8adb5j {
  stop-color: var(--svg-color--148c3e, #148C3E);
  stop-opacity: 0;
}

.l4zvkhbts {
  d: path("m2.2 30.466l2.93-9.157c.352-1.414 2.07-2.103 3.65-1.613s2.491 2.332 2.007 3.691L8.57 30.466z");
}

.l8v5z5bog {
  stop-color: var(--svg-color--6e574e, #6E574E);
}

.l9p5r2b1o {
  stop-color: var(--svg-color--f7c79e, #F7C79E);
}

.lemuo5beu {
  stop-color: var(--svg-color--c98583, #C98583);
  stop-opacity: 0;
}

.ll6ec2bpd {
  stop-color: var(--svg-color--6e574e, #6E574E);
  stop-opacity: 0;
}

.lmrdcczln {
  d: path("m15.454 21.23l.227.068a.5.5 0 0 0 .492-.12l.363-.352a.13.13 0 0 1 .128-.033l.315.084a.484.484 0 0 0 .253-.936l-.304-.082a.13.13 0 0 1-.097-.11l-.069-.439a.5.5 0 0 0-.36-.404l-.26-.072z");
}

.ls27mhbfe {
  stop-color: var(--svg-color--d99e84, #D99E84);
}

.ls62f1bvq {
  stop-color: var(--svg-color--e3ab85, #E3AB85);
}

.lsyue1afr {
  stop-color: var(--svg-color--b2968d, #B2968D);
}

.m0x-b6bjk {
  d: path("m15.53 18.33l.554.16a.15.15 0 0 1 .103.185l-.784 2.73a.15.15 0 0 1-.185.103l-.555-.16z");
}

.ma7f6291s {
  stop-color: var(--svg-color--1c8ec9, #1C8EC9);
  stop-opacity: 0;
}

.mc2zb0bvp {
  opacity: var(--svg-opacity--0-5, 0.5);
}

.mivj2qhld {
  d: path("M10.099 16.926c.356.125.481.331.515.453l.446.391l2.291.362a.92.92 0 0 0 1.062-.872a.913.913 0 0 0-.922-.95c-1.175.014-2.688.036-3.044.026c-.586-.015-.793.434-.348.59");
}

.n8jici3hn {
  stop-color: var(--svg-color--fed466, #FED466);
  stop-opacity: 0;
}

.nbcoryb1h {
  stop-color: var(--svg-color--bf7c89, #BF7C89);
}

.neym138jd {
  stop-color: var(--svg-color--f3c22a, #F3C22A);
}

.njdbcpw8w {
  stop-color: var(--svg-color--78e2ff, #78E2FF);
}

.nn3wh7bnm {
  stop-color: var(--svg-color--58d4f5, #58D4F5);
}

.nu_77rrcl {
  stop-color: var(--svg-color--c7977a, #C7977A);
}

.nyaikfbyz {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M15.557 8.002c.41-.15 1.24-.278 1.89.064");
}

.o-ef0ac2e {
  stop-color: var(--svg-color--d8a788, #D8A788);
  stop-opacity: 0;
}

.o6sle6pni {
  stop-color: var(--svg-color--b87862, #B87862);
}

.ohwd33b2n {
  stop-color: var(--svg-color--b8757a, #B8757A);
}

.ol95frboa {
  stop-color: var(--svg-color--277aa9, #277AA9);
}

.op2kwubyv {
  stop-color: var(--svg-color--e2a18c, #E2A18C);
}

.p4v4psbuh {
  d: path("M10.565 19.035c-.28.05-.54.19-.74.38c.01-.05.02-.1.04-.15l.12-.33c.28-.78 1.09-1.27 1.91-1.15l1.66.23c.42.06.72.45.66.87s-.45.72-.87.66l-1.57-.22c-.34-.26-.78-.37-1.21-.29");
}

.p6n8nbb9p {
  stop-color: var(--svg-color--78e2ff, #78E2FF);
  stop-opacity: 0;
}

.pdon63boo {
  stop-color: var(--svg-color--f38820, #F38820);
  stop-opacity: 0;
}

.pfjyiqgya {
  stop-color: var(--svg-color--ce9a7f, #CE9A7F);
}

.pkqh0mbji {
  fill: var(--svg-color--d8a888, #D8A888);
  d: path("M9.67 17.848c.243.25.33.526.343.633l.484.469l2.342.407a.89.89 0 0 0 1.024-.693a.9.9 0 0 0-.774-1.079c-1.09-.132-2.42-.305-2.78-.346c-.612-.07-.944.297-.64.61");
}

.pll5kd_nw {
  stop-color: var(--svg-color--dfae8f, #DFAE8F);
}

.pn2_jabhi {
  stop-color: var(--svg-color--d79e8e, #D79E8E);
}

.pqf0u3bgb {
  stop-color: var(--svg-color--a57146, #A57146);
}

.ps228g2nk {
  stop-color: var(--svg-color--f8bf96, #F8BF96);
}

.py7fiqzvo {
  stop-color: var(--svg-color--052e6b, #052E6B);
}

.qh-ows9fr {
  stop-color: var(--svg-color--a07cb6, #A07CB6);
}

.qic_n_blg {
  stop-color: var(--svg-color--d2c9d1, #D2C9D1);
}

.qoa6ft6za {
  stop-color: var(--svg-color--857084, #857084);
}

.qsk_rudxu {
  d: path("m11.939 16.5l3.172.884c.43.125.744.558.627.96l-.9 3.085c-.114.396-.532.607-1.024.474l-3.129-.883z");
}

.qtvy6rbzh {
  stop-color: var(--svg-color--42b8e0, #42B8E0);
}

.qwou5rbcb {
  d: path("m14.825 17.563l-2.635-.734l-1.073 3.895l2.6.733c.408.11.755-.064.85-.393l.78-2.704c.123-.39-.165-.693-.522-.797");
}

.qyhj3zowg {
  d: path("M11.073 11.384c.08-.01.16.01.22.06a1.074 1.074 0 0 0 1.6-.29c.04-.07.11-.12.19-.13c.22-.04.39.2.28.4c-.23.39-.63.68-1.1.77c-.48.08-.95-.05-1.3-.34c-.19-.14-.11-.43.11-.47");
}

.qyobb4hvj {
  stop-color: var(--svg-color--ffffc2, #FFFFC2);
}

.r8owzxbqs {
  stop-color: var(--svg-color--bf7c89, #BF7C89);
  stop-opacity: 0;
}

.rb5pqrony {
  stop-color: var(--svg-color--d5a079, #D5A079);
}

.rihdlqb3v {
  stop-color: var(--svg-color--429ce6, #429CE6);
}

.rkoscyb2g {
  stop-color: var(--svg-color--124ea0, #124EA0);
  stop-opacity: 0;
}

.ro5jldbid {
  stop-color: var(--svg-color--c38771, #C38771);
}

.rvju2rlnj {
  stop-color: var(--svg-color--1972ba, #1972BA);
  stop-opacity: 0;
}

.rvz7hrbgf {
  stop-color: var(--svg-color--cb9c79, #CB9C79);
}

.rxh459f4v {
  stop-color: var(--svg-color--c98583, #C98583);
}

.s03vqlghs {
  stop-color: var(--svg-color--1e7eee, #1E7EEE);
  stop-opacity: 0;
}

.s231-6bjz {
  stop-color: var(--svg-color--48b6ff, #48B6FF);
}

.s236rjbsc {
  stop-color: var(--svg-color--af6f5d, #AF6F5D);
}

.s6qjzwjgb {
  stop-color: var(--svg-color--48b6ff, #48B6FF);
  stop-opacity: 0;
}

.sbp9bz1ap {
  stop-color: var(--svg-color--fec8a4, #FEC8A4);
}

.sdatcx1hi {
  stop-color: var(--svg-color--1577e2, #1577E2);
}

.sg8a2viwh {
  stop-color: var(--svg-color--c58b71, #C58B71);
}

.sinn-3bvk {
  stop-color: var(--svg-color--6cd8f5, #6CD8F5);
  stop-opacity: 0;
}

.sk7ylfhdv {
  stop-color: var(--svg-color--905b2c, #905B2C);
}

.sok9f40_l {
  stop-color: var(--svg-color--efc3a5, #EFC3A5);
}

.sv8i3wgtb {
  fill: var(--svg-color--9a6634, #9A6634);
  d: path("m17.61 7.78l-.002-.001l-.002-.002l-.005-.002l-.014-.008a1.4 1.4 0 0 0-.171-.078a2.6 2.6 0 0 0-.45-.133a2.83 2.83 0 0 0-1.497.109a.534.534 0 1 0 .35 1.008c.38-.133.707-.117.936-.07a1.5 1.5 0 0 1 .333.107a.534.534 0 0 0 .521-.93");
}

.swa2l6hgf {
  d: path("M15.703 10.575c.08-.01.16.01.22.06a1.074 1.074 0 0 0 1.6-.29c.04-.07.11-.12.19-.13c.22-.04.39.2.28.4c-.23.39-.63.68-1.1.77c-.48.08-.95-.05-1.3-.34a.263.263 0 0 1 .11-.47");
}

.swsc53bmj {
  fill: var(--svg-color--c68378, #C68378);
  d: path("m14.138 11.044l-.506 1.818c-.038.362.264.663.604.601l.726-.13c.34-.061.517-.454.356-.775l-.791-1.584c-.172-.352-.345-.32-.389.07");
}

.szm1jtb2t {
  stop-color: var(--svg-color--ffffc2, #FFFFC2);
  stop-opacity: 0;
}

.t1ofhibdm {
  stop-color: var(--svg-color--3395d2, #3395D2);
}

.t78i98bfv {
  stop-color: var(--svg-color--735caf, #735CAF);
  stop-opacity: 0;
}

.t9y-_dh4s {
  stop-color: var(--svg-color--edb18c, #EDB18C);
}

.tbs366q3s {
  stop-color: var(--svg-color--4760c0, #4760C0);
}

.tjgs2ub-w {
  stop-color: var(--svg-color--efc3a7, #EFC3A7);
}

.tlxyqtbtq {
  stop-color: var(--svg-color--b56e74, #B56E74);
}

.tomvu1bgl {
  stop-color: var(--svg-color--78e0ff, #78E0FF);
}

.ts8ii3fly {
  stop-color: var(--svg-color--e8ad8e, #E8AD8E);
}

.txtd__b4r {
  d: path("m12.166 16.93l2.636.735c.357.104.645.406.521.797l-.779 2.703c-.096.33-.442.505-.851.394l-2.6-.734z");
}

.ty92xt-jo {
  stop-color: var(--svg-color--f7c79e, #F7C79E);
  stop-opacity: 0;
}

.tz-ih0bsr {
  d: path("M21.575 24.405a4.3 4.3 0 0 1 .71-5.22a4.31 4.31 0 0 0-2.61 6.21a4.304 4.304 0 0 0 6.78 1.01c-1.84.51-3.87-.26-4.88-2");
}

.tzj34xnjq {
  stop-color: var(--svg-color--ffd267, #FFD267);
}

.u1zlaqbml {
  stop-color: var(--svg-color--bc7b6b, #BC7B6B);
  stop-opacity: 0;
}

.u7v6tactn {
  stop-color: var(--svg-color--eec19c, #EEC19C);
}

.uels9hbwx {
  stop-color: var(--svg-color--5082c1, #5082C1);
  stop-opacity: 0;
}

.uf2y99bpi {
  d: path("M8.52 18.945a.28.28 0 0 1 .134-.27c.981-.69 2.005-.304 2.383 0c.304.237 1 .79 1.363 1.083c.446.36.372.961.043 1.316c-.276.298-.752.241-.93.149L9.415 19.91c-.054-.312-.234-.562-.48-.636c-.246-.075-.402-.133-.414-.329");
}

.ugbytbngn {
  stop-color: var(--svg-color--ffd267, #FFD267);
  stop-opacity: 0;
}

.upwmevb9h {
  stop-color: var(--svg-color--377dcb, #377DCB);
  stop-opacity: 0;
}

.uvoxmwj8v {
  stop-color: var(--svg-color--0e6996, #0E6996);
  stop-opacity: 0;
}

.uxh2dv17l {
  stop-color: var(--svg-color--bc7b6b, #BC7B6B);
}

.uxpb5qzbn {
  stop-color: var(--svg-color--cd9b7f, #CD9B7F);
}

.uylyaxbnq {
  stop-color: var(--svg-color--c2837a, #C2837A);
  stop-opacity: 0;
}

.v2wkn2ras {
  stop-color: var(--svg-color--31ae6a, #31AE6A);
}

.v4v-qb7kx {
  stop-color: var(--svg-color--cb9173, #CB9173);
  stop-opacity: 0;
}

.vfysexbex {
  fill: var(--svg-color--d29d8b, #D29D8B);
  d: path("M17.18 26.147a.937.937 0 0 0-1.12 1.498l.931.801a.1.1 0 0 1-.063.176l-3.644.072a.886.886 0 0 0 .018 1.77h6.06v-1l1.062-1.226z");
}

.vm3fdb8rz {
  stop-color: var(--svg-color--9a7378, #9A7378);
}

.vq4o9ccce {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M15.745 10.844c.151.14.548.37 1.063.274c.562-.107.888-.459.96-.64");
}

.vs8934bpj {
  stop-color: var(--svg-color--fbecaf, #FBECAF);
  stop-opacity: 0;
}

.vsvz-xe_v {
  stop-color: var(--svg-color--c58b71, #C58B71);
  stop-opacity: 0;
}

.w_57dfb5m {
  stop-color: var(--svg-color--735caf, #735CAF);
}

.w-a4mnbis {
  stop-color: var(--svg-color--dcc291, #DCC291);
}

.wiexblb8s {
  stop-color: var(--svg-color--9a663d, #9A663D);
}

.wla505bqs {
  stop-color: var(--svg-color--1972ba, #1972BA);
}

.wvivicznw {
  stop-color: var(--svg-color--e2a18c, #E2A18C);
  stop-opacity: 0;
}

.x_5m0sb4w {
  d: path("m18.025 3.887l.46.133c.806.235 1.38.998 1.381 1.92l-.042 3.095c.004.319-.163.563-.468.626l-.018.004s-.108-.902-.15-1.436c-.033-.434-.131-.55-.592-.869c-.249-.172-.464-.458-.52-.773l-.152-.84c-.047-.262-.296-.434-.516-.449c-.662-.043-2.03-.068-3.93.274s-3.172.842-3.777 1.114a.52.52 0 0 0-.328.6l.151.84c.057.315.008.65-.218.907l-.13.186c-.183.195-.232.53-.185.792c.157.567.361 1.398.361 1.398l-.048.007a.63.63 0 0 1-.68-.418L7.505 8.11c-.257-.821.014-1.737.687-2.237l.385-.286c.235-.205.461-.463.687-.72l.771-1.168c.486-.63 1.302-.94 2.108-.705a2.94 2.94 0 0 0 1.636-.295c.745-.405 1.68-.356 2.417.107l.934.645c.258.224.55.334.895.435");
}

.x7yh0i-6p {
  stop-color: var(--svg-color--429ce6, #429CE6);
  stop-opacity: 0;
}

.xjk10obil {
  stop-color: var(--svg-color--cb8e6d, #CB8E6D);
  stop-opacity: 0;
}

.xogpiobqs {
  stop-color: var(--svg-color--a57146, #A57146);
  stop-opacity: 0;
}

.xrkexibub {
  stop-color: var(--svg-color--fec8a4, #FEC8A4);
  stop-opacity: 0;
}

.xslwfurve {
  d: path("M9.67 17.848c.243.25.33.526.343.633l.484.469l2.342.407a.89.89 0 0 0 1.024-.693a.9.9 0 0 0-.774-1.079c-1.09-.132-2.42-.305-2.78-.346c-.612-.07-.944.297-.64.61");
}

.y0dl1gblq {
  stop-color: var(--svg-color--b8757a, #B8757A);
  stop-opacity: 0;
}

.y5me6xb0v {
  fill: var(--svg-color--d9aa86, #D9AA86);
  d: path("M10.099 16.926c.356.125.481.331.515.453l.446.391l2.291.362a.92.92 0 0 0 1.062-.872a.913.913 0 0 0-.922-.95c-1.175.014-2.688.036-3.044.026c-.586-.015-.793.434-.348.59");
}

.y7nn5tbfc {
  stop-color: var(--svg-color--c2837a, #C2837A);
}

.yassptbsb {
  stop-color: var(--svg-color--1a3f75, #1A3F75);
}

.ycy65pbdu {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M11.116 11.652c.15.14.547.37 1.062.273c.563-.106.888-.458.96-.64");
}

.yq-9ytfqn {
  stop-color: var(--svg-color--98643a, #98643A);
}

.ys1ri2qqc {
  stop-color: var(--svg-color--d99e84, #D99E84);
  stop-opacity: 0;
}

.yxmxw0ard {
  stop-color: var(--svg-color--32996b, #32996B);
}

.z_gh6vsyy {
  stop-color: var(--svg-color--ab6850, #AB6850);
}

.z05snt6nn {
  d: path("M8.13 17.708c1.031-1.086 1.92-1.37 2.32-1.375l.797.867l-.93 3.515c-.18.315-.563.996-.695 1.153c-.164.195-.735.63-1.765.238c-.888-.338-1.15-.899-1.176-1.149c.233-1.167.649-2.357 1.45-3.25");
}

.z1oeopb3i {
  d: path("m11.845 21.065l-.46-.5c-.28-.3-.68-.48-1.09-.49c-.42-.01-.82.16-1.11.46l-.17.18l.53-.95c.22-.39.59-.66 1.02-.74s.88.03 1.23.3l.99.8c.33.27.38.75.12 1.09c-.21.26-.56.35-.85.24a.9.9 0 0 0-.21-.39");
}

.z3zsa5bpu {
  stop-color: var(--svg-color--53f595, #53F595);
}

.z8oy8ibbe {
  stop-color: var(--svg-color--d1a082, #D1A082);
  stop-opacity: 0;
}

.z9945l-5h {
  stop-color: var(--svg-color--d79e8e, #D79E8E);
  stop-opacity: 0;
}

.ze1cb0iau {
  stop-color: var(--svg-color--e3ab88, #E3AB88);
  stop-opacity: 0;
}

.zf-_6rkpt {
  d: path("m9.304 11.416l.049-.007s-.204-.83-.361-1.398c-.047-.262.001-.596.184-.792l.13-.186c.226-.257.275-.591.219-.906l-.152-.84a.52.52 0 0 1 .328-.6c.605-.272 1.878-.772 3.778-1.114s3.267-.318 3.929-.274c.22.014.47.186.517.449l.15.84c.058.314.273.6.522.773c.556.257.56.453.592.868c.042.535.15 1.436.15 1.436l.017-.003l.44 3.943c.156 1.77-.995 3.23-2.627 3.524l-3.16.568c-1.684.304-3.22-.673-3.69-2.386z");
}

.zi4jjac0b {
  d: path("M23.695 27.595a4.3 4.3 0 1 0 0-8.6a4.3 4.3 0 0 0 0 8.6");
}

.zlpmx2b9v {
  stop-color: var(--svg-color--e8ad8e, #E8AD8E);
  stop-opacity: 0;
}

.zq2cu-lqa {
  stop-color: var(--svg-color--dcaa8a, #DCAA8A);
  stop-opacity: 0;
}

.zx-utrb8d {
  stop-color: var(--svg-color--dcab8c, #DCAB8C);
}

.zxch6_gap {
  stop-color: var(--svg-color--377dcb, #377DCB);
}

</style>
