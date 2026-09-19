<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#ipot32b)" class="ax3t7fbst"/><path fill="url(#ir8tAWb)" class="ax3t7fbst"/><path class="t9w88ccap"/><path fill="url(#icKH4Wd)" class="td7qnxbmr"/><path fill="url(#iqqDZPU)" class="td7qnxbmr"/><path fill="url(#inT0zab)" class="c5jm6bc5b"/><path fill="url(#iRI2yhd)" class="g3ux3cbys"/><path fill="url(#ihnjaeb)" class="ny9_xhbeh"/><path fill="url(#izJjw7h)" class="rt1r2lbdx"/><path fill="url(#iic3tui)" class="m0er3vbow"/><g filter="url(#io2vxuc)"><path fill="url(#imOjykb)" class="pxaxwjbdw"/></g><path fill="url(#i5oAUre)" class="pxaxwjbdw"/><path fill="url(#i80v9xe)" class="pxaxwjbdw"/><path fill="url(#i54xoid)" class="pxaxwjbdw"/><path fill="url(#iDzdrhT)" class="pxaxwjbdw"/><path fill="url(#i5oApQe)" class="pxaxwjbdw"/><path fill="url(#i1WHs0d)" class="pxaxwjbdw"/><path fill="url(#i8hTjFc)" class="pxaxwjbdw"/><path fill="url(#iFF0xDd)" class="pxaxwjbdw"/><path fill="url(#iJic4Jc)" class="pxaxwjbdw"/><g filter="url(#i4LjAzb)"><path class="cxt8_ibda"/></g><g filter="url(#imtVQ9c)"><path class="jk21n9bik"/><path fill="url(#iCPoyre)" class="am-vu7akn"/><path fill="url(#iUkoupd)" class="am-vu7akn"/><path fill="url(#ia8Edmc)" class="am-vu7akn"/><path fill="url(#iWdutze)" class="am-vu7akn"/><path fill="url(#iF8IJbc)" class="am-vu7akn"/></g><g filter="url(#iFpeOHe)"><path stroke="url(#i5oWiEb)" class="bf6_qrkvm"/></g><path fill="url(#iaiWwfm)" class="segtfez6g"/><g filter="url(#ipRVF5c)"><path fill="url(#iXLeT0c)" class="ua_qcxh-g"/><path fill="url(#iKmZfRO)" class="ua_qcxh-g"/><path fill="url(#iz6yajU)" class="ua_qcxh-g"/><path fill="url(#iboHIOd)" class="ua_qcxh-g"/><path fill="url(#in645qc)" class="ua_qcxh-g"/></g><g filter="url(#ihuSXed)"><path class="v8idy2p3c"/></g><g filter="url(#idyVmQd)"><path class="jzh_zdb1u"/></g><g filter="url(#iSIWInc)"><path class="l-dnxbb6m"/><path fill="url(#i11kTMe)" class="nvbd3gb0w"/><path fill="url(#iwgSYWb)" class="nvbd3gb0w"/></g><g filter="url(#ibwtOYc)"><path class="gc1t1221f"/><path fill="url(#iANOTnb)" class="a7w75bcbh"/></g><path class="lkqzgvv7h"/><path fill="url(#iOA0COd)" class="y26jaac_x"/><path class="nhtj7e8qx"/><g filter="url(#iJXdvUp)"><path class="udkr-um3k"/><path fill="url(#iPNAJNd)" class="g0smdzbso"/></g><g filter="url(#iW09Y1B)"><path fill="url(#izSgSbd)" class="bnagblbqa"/></g><path class="azmmzob6j"/><path fill="url(#iVKjuKc)" class="nv2d3lbzc"/><path class="ih-ladlvk"/><g filter="url(#iIsxpve)"><path fill="url(#ii3Kgmd)" class="t5hji7b2p"/></g><g filter="url(#iuXbOjd)"><ellipse transform="rotate(-27.914 13.542 9.816)" class="cur91yz5h"/><ellipse fill="url(#i9HExNc)" transform="rotate(-27.914 13.542 9.816)" class="v1mb2vv6g"/></g><path fill="url(#iXmZKhe)" class="m6jz2xbwk"/><path fill="url(#iuto5Jc)" class="m6jz2xbwk"/><path fill="url(#iIw07Jc)" class="m6jz2xbwk"/><path fill="url(#iT1x99d)" class="m6jz2xbwk"/><path fill="url(#iLK2LhF)" class="edicxsbpr"/><path fill="url(#iAmufCc)" class="edicxsbpr"/><g filter="url(#iwEMbGb)"><path fill="url(#iON3vBo)" class="brpuz_b9y"/></g><g filter="url(#iqVDOCe)"><path fill="url(#icK93Md)" class="ev2lxub8z"/></g><g filter="url(#ikT9wUd)"><path class="h12s_qbsc"/></g><g filter="url(#iUNaECc)"><path class="knye9dzad"/></g><g filter="url(#ihQEIme)"><path class="iesato94l"/></g><g filter="url(#iYsaczb)"><path fill="url(#iHXaVce)" class="jsqgobbht"/><path fill="url(#i2BUj5L)" class="jsqgobbht"/><path fill="url(#iqtSqJd)" class="jsqgobbht"/><path fill="url(#iNN1SaK)" class="jsqgobbht"/><path fill="url(#irzSjbb)" class="jsqgobbht"/><path fill="url(#ihI2zKe)" class="jsqgobbht"/></g><path fill="url(#ixwQhto)" class="ppwrykbzp"/><path fill="url(#i8N6NDd)" class="ppwrykbzp"/><path fill="url(#ilcEH9d)" class="ppwrykbzp"/><path fill="url(#iKDpaee)" class="ppwrykbzp"/><path fill="url(#i2FoUFP)" class="ppwrykbzp"/><path fill="url(#iWis4Qd)" class="w6exmsbsa"/><defs><radialGradient id="ipot32b" cx="0" cy="0" r="1" gradientTransform="matrix(2.80769 -1.3591 1.47615 3.04949 2.747 30.02)" gradientUnits="userSpaceOnUse"><stop offset=".406" class="xomn_jqkl"/><stop offset="1" class="yvpae5bzc"/></radialGradient><radialGradient id="ir8tAWb" cx="0" cy="0" r="1" gradientTransform="rotate(177.157 2.332 14.994)scale(3.35044 4.79049)" gradientUnits="userSpaceOnUse"><stop offset=".764" class="ff9bywbjm"/><stop offset=".927" class="bf-s3qwzt"/></radialGradient><radialGradient id="icKH4Wd" cx="0" cy="0" r="1" gradientTransform="matrix(5.64062 -3.71875 1.03844 1.57511 27.091 30.119)" gradientUnits="userSpaceOnUse"><stop offset=".127" class="nbncwobqn"/><stop offset=".988" class="n55x1ubvq"/></radialGradient><radialGradient id="izJjw7h" cx="0" cy="0" r="1" gradientTransform="rotate(69.657 1.917 20.796)scale(2.15388 2.55864)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="rra4r9bnq"/><stop offset="1" class="pft2s7y0a"/></radialGradient><radialGradient id="iic3tui" cx="0" cy="0" r="1" gradientTransform="matrix(1.47646 .46403 -1.43157 4.55499 9.94 12.26)" gradientUnits="userSpaceOnUse"><stop class="gg1n47rtb"/><stop offset=".746" class="q53v6mhsp"/></radialGradient><radialGradient id="imOjykb" cx="0" cy="0" r="1" gradientTransform="matrix(-5.22785 0 0 -9.24802 18.803 10.828)" gradientUnits="userSpaceOnUse"><stop class="k53yjlbth"/><stop offset="1" class="ahguepbtf"/></radialGradient><radialGradient id="i80v9xe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.02223 12.42352 -10.28813 -.84653 17.577 4.914)" gradientUnits="userSpaceOnUse"><stop offset=".767" class="c2_7179_n"/><stop offset=".997" class="h1qder98v"/></radialGradient><radialGradient id="i54xoid" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.14835 1.42108 0 18.443 9.515)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="asp-974pn"/><stop offset="1" class="l2dudh2nh"/></radialGradient><radialGradient id="iDzdrhT" cx="0" cy="0" r="1" gradientTransform="matrix(.00393 -1.09428 1.19083 .00428 13.695 9.56)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="ww86j5--q"/><stop offset="1" class="mfkgssbjj"/></radialGradient><radialGradient id="i5oApQe" cx="0" cy="0" r="1" gradientTransform="matrix(-8.49599 .5363 -1.37 -21.703 19.428 11.816)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="o-j_7gbpq"/><stop offset="1" class="j-n0q842a"/></radialGradient><radialGradient id="i1WHs0d" cx="0" cy="0" r="1" gradientTransform="matrix(4.073 -2.6483 .96946 1.491 10.528 6.502)" gradientUnits="userSpaceOnUse"><stop offset=".38" class="xjcxgac6b"/><stop offset="1" class="psn4zabca"/></radialGradient><radialGradient id="i8hTjFc" cx="0" cy="0" r="1" gradientTransform="rotate(95.368 7.17 13.76)scale(2.50844 1.00273)" gradientUnits="userSpaceOnUse"><stop offset=".245" class="x73tbcc6t"/><stop offset="1" class="sbhjtg7pq"/></radialGradient><radialGradient id="iFF0xDd" cx="0" cy="0" r="1" gradientTransform="rotate(121.159 7.562 8.119)scale(3.36898 2.78137)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="f28ypccjc"/><stop offset="1" class="zkb-swu-c"/></radialGradient><radialGradient id="iUkoupd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .2441 -.76718 0 16.462 12.188)" gradientUnits="userSpaceOnUse"><stop class="txgsuxr-c"/><stop offset="1" class="a4rldd3-z"/></radialGradient><radialGradient id="iWdutze" cx="0" cy="0" r="1" gradientTransform="matrix(-1.52115 .69743 -1.12083 -2.4446 16.578 11.619)" gradientUnits="userSpaceOnUse"><stop offset=".714" class="p8isx8b7k"/><stop offset="1" class="w37r5utea"/></radialGradient><radialGradient id="iaiWwfm" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.72074 2.89971 0 15.995 14.367)" gradientUnits="userSpaceOnUse"><stop class="w189cfbhy"/><stop offset="1" class="z5a_p6x5j"/></radialGradient><radialGradient id="iKmZfRO" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.50133 8.85445 0 10.766 7.936)" gradientUnits="userSpaceOnUse"><stop offset=".536" class="ibt06e6rm"/><stop offset="1" class="k45xjwbmq"/></radialGradient><radialGradient id="iz6yajU" cx="0" cy="0" r="1" gradientTransform="rotate(-87.401 15.266 -6.29)scale(2.51513 4.45631)" gradientUnits="userSpaceOnUse"><stop class="c98z413ze"/><stop offset="1" class="ovvtmacpn"/></radialGradient><radialGradient id="iboHIOd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.35883 -1.5514 1.13881 -1.7315 20.102 2.97)" gradientUnits="userSpaceOnUse"><stop class="wyv1gnbxf"/><stop offset="1" class="z6d-f52gr"/></radialGradient><radialGradient id="in645qc" cx="0" cy="0" r="1" gradientTransform="matrix(.90511 1.475 -3.4154 2.09582 15.09 1.377)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="qco-2_b3r"/><stop offset="1" class="zwo50zm6y"/></radialGradient><radialGradient id="i11kTMe" cx="0" cy="0" r="1" gradientTransform="matrix(-2.20113 0 0 -.81692 16.249 3.636)" gradientUnits="userSpaceOnUse"><stop class="axstwemrb"/><stop offset="1" class="ez41_pbnb"/></radialGradient><radialGradient id="iwgSYWb" cx="0" cy="0" r="1" gradientTransform="rotate(-57.724 12.158 -5.795)scale(6.02662 6.67688)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="hnw0p1utu"/><stop offset=".311" class="dwl_ftd7p"/><stop offset="1" class="fch_lgr5q"/></radialGradient><radialGradient id="iANOTnb" cx="0" cy="0" r="1" gradientTransform="rotate(6.667 -42.412 155.307)scale(3.27033 1.36922)" gradientUnits="userSpaceOnUse"><stop class="unyhdjbdq"/><stop offset="1" class="w0a4mmrgb"/></radialGradient><radialGradient id="iOA0COd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.2905 0 18.177 9.911)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="iPNAJNd" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 11.422 .602)scale(.37829 .52081)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iVKjuKc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81136 -1.29056 0 13.813 9.911)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="i9HExNc" cx="0" cy="0" r="1" gradientTransform="matrix(-.00774 -.49408 .59392 -.0093 13.527 10.13)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iuto5Jc" cx="0" cy="0" r="1" gradientTransform="matrix(.62855 2.24328 -2.14025 .59968 20.613 9.925)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="xbtbagqno"/><stop offset="1" class="epf-qq6ay"/></radialGradient><radialGradient id="iIw07Jc" cx="0" cy="0" r="1" gradientTransform="matrix(.78778 -1.0811 .90618 .66032 20.974 10.47)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="akw4fybhj"/><stop offset="1" class="qoxj776_o"/></radialGradient><radialGradient id="iT1x99d" cx="0" cy="0" r="1" gradientTransform="matrix(.587 -1.55042 2.07158 .7843 21.087 10.643)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="c5e-i-5dw"/><stop offset=".966" class="szee5wb8m"/></radialGradient><radialGradient id="iAmufCc" cx="0" cy="0" r="1" gradientTransform="rotate(101.248 1.225 9.45)scale(2.11668 2.08089)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="ay2574bqt"/><stop offset="1" class="g1u_xnbmn"/></radialGradient><radialGradient id="iON3vBo" cx="0" cy="0" r="1" gradientTransform="matrix(-.91648 .1573 -.06938 -.40422 11.08 10.568)" gradientUnits="userSpaceOnUse"><stop class="c4l15nbte"/><stop offset="1" class="r95ztqgly"/></radialGradient><radialGradient id="i2BUj5L" cx="0" cy="0" r="1" gradientTransform="matrix(0 -7.59705 13.2772 0 17.243 31.067)" gradientUnits="userSpaceOnUse"><stop offset=".027" class="o1-qqkidl"/><stop offset="1" class="q0dxfdmim"/></radialGradient><radialGradient id="ihI2zKe" cx="0" cy="0" r="1" gradientTransform="matrix(-.78125 .4375 -.4057 -.72446 26.696 16.66)" gradientUnits="userSpaceOnUse"><stop class="nonrr22es"/><stop offset=".724" class="jehi2ihjx"/></radialGradient><radialGradient id="iWis4Qd" cx="0" cy="0" r="1" gradientTransform="matrix(-.0957 .08008 -.11939 -.14269 17.371 21.824)" gradientUnits="userSpaceOnUse"><stop class="a-otvg7dq"/><stop offset="1" class="t_w5hobcp"/></radialGradient><linearGradient id="iqqDZPU" x1="26.966" x2="27.302" y1="28.838" y2="28.838" gradientUnits="userSpaceOnUse"><stop class="msex9gbuq"/><stop offset="1" class="eu7hrybov"/></linearGradient><linearGradient id="inT0zab" x1="16" x2="16" y1="6.703" y2="34.611" gradientUnits="userSpaceOnUse"><stop class="zaeth0b6d"/><stop offset="1" class="vuad6pb7r"/></linearGradient><linearGradient id="iRI2yhd" x1="10.918" x2="1.428" y1="24.003" y2="24.044" gradientUnits="userSpaceOnUse"><stop class="vuad6pb7r"/><stop offset="1" class="zaeth0b6d"/></linearGradient><linearGradient id="ihnjaeb" x1="22.998" x2="28.652" y1="24.02" y2="24.02" gradientUnits="userSpaceOnUse"><stop class="vuad6pb7r"/><stop offset="1" class="zaeth0b6d"/></linearGradient><linearGradient id="i5oAUre" x1="21.153" x2="16.8" y1="12.513" y2="12.513" gradientUnits="userSpaceOnUse"><stop class="k53yjlbth"/><stop offset="1" class="prh5swccd"/></linearGradient><linearGradient id="iJic4Jc" x1="16.042" x2="16.042" y1="17.08" y2="16.439" gradientUnits="userSpaceOnUse"><stop class="dn2_hckup"/><stop offset="1" class="jk-0m6p0q"/></linearGradient><linearGradient id="iCPoyre" x1="16.834" x2="15.996" y1="11.502" y2="11.537" gradientUnits="userSpaceOnUse"><stop offset=".36" class="d8gqn2snf"/><stop offset="1" class="oz5jd4bmy"/></linearGradient><linearGradient id="ia8Edmc" x1="15.996" x2="15.996" y1="12.642" y2="12.177" gradientUnits="userSpaceOnUse"><stop class="abx50lnlm"/><stop offset="1" class="u-2msu4yh"/></linearGradient><linearGradient id="iF8IJbc" x1="15.996" x2="15.996" y1="9.687" y2="10.483" gradientUnits="userSpaceOnUse"><stop class="o2r2q6blp"/><stop offset="1" class="kh_x-hbqh"/></linearGradient><linearGradient id="i5oWiEb" x1="14.794" x2="15.112" y1="14.213" y2="13.378" gradientUnits="userSpaceOnUse"><stop class="ob3l4g_ys"/><stop offset="1" class="fglza-d-f"/></linearGradient><linearGradient id="iXLeT0c" x1="22.848" x2="11.235" y1="5.165" y2="5.165" gradientUnits="userSpaceOnUse"><stop class="l1vex1b6a"/><stop offset="1" class="kydculhfm"/></linearGradient><linearGradient id="izSgSbd" x1="18.956" x2="18.642" y1="9.965" y2="10.159" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ii3Kgmd" x1="14.557" x2="14.244" y1="9.965" y2="10.159" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iXmZKhe" x1="22.432" x2="21.225" y1="9.992" y2="12.169" gradientUnits="userSpaceOnUse"><stop class="lwf47ccyr"/><stop offset="1" class="bmcblacal"/></linearGradient><linearGradient id="iLK2LhF" x1="10.146" x2="11.604" y1="10.696" y2="10.569" gradientUnits="userSpaceOnUse"><stop class="jrlin1f0e"/><stop offset="1" class="zzkrmpd6m"/></linearGradient><linearGradient id="icK93Md" x1="21.412" x2="21.412" y1="9.611" y2="11.514" gradientUnits="userSpaceOnUse"><stop class="q3b-p60-b"/><stop offset="1" class="v3ih9bcyp"/></linearGradient><linearGradient id="iHXaVce" x1="7.493" x2="11.284" y1="19.754" y2="30.805" gradientUnits="userSpaceOnUse"><stop class="ux-m5bn7d"/><stop offset="1" class="l294t3zvi"/></linearGradient><linearGradient id="iqtSqJd" x1="16" x2="16" y1="16.02" y2="17.379" gradientUnits="userSpaceOnUse"><stop class="dmu1fh1sq"/><stop offset=".268" class="gzfhb8b1n"/><stop offset=".863" class="szjcm-w7x"/></linearGradient><linearGradient id="iNN1SaK" x1="5" x2="6.055" y1="24.254" y2="24.254" gradientUnits="userSpaceOnUse"><stop class="a61ap5b7j"/><stop offset="1" class="p9llu9bpa"/></linearGradient><linearGradient id="irzSjbb" x1="27" x2="25.524" y1="25.192" y2="25.192" gradientUnits="userSpaceOnUse"><stop offset=".174" class="yr342ibfl"/><stop offset="1" class="d9m_15bme"/></linearGradient><linearGradient id="ixwQhto" x1="17.977" x2="13.911" y1="23.099" y2="23.099" gradientUnits="userSpaceOnUse"><stop offset=".096" class="qufyc6r7b"/><stop offset=".13" class="xqmtwwbyq"/><stop offset=".165" class="k71v6_7um"/><stop offset="1" class="uem0lbchq"/></linearGradient><linearGradient id="i8N6NDd" x1="15.999" x2="15.999" y1="21.641" y2="23.196" gradientUnits="userSpaceOnUse"><stop class="w9bfwpbnq"/><stop offset="1" class="zt_ualb3u"/></linearGradient><linearGradient id="ilcEH9d" x1="15.999" x2="15.999" y1="21.641" y2="24.557" gradientUnits="userSpaceOnUse"><stop class="l17xqebtl"/><stop offset=".037" class="r1d3vkbxd"/><stop offset=".058" class="bowxt9bwr"/><stop offset=".097" class="g48yfbn9k"/></linearGradient><linearGradient id="iKDpaee" x1="14.444" x2="15.02" y1="23.122" y2="23.122" gradientUnits="userSpaceOnUse"><stop offset=".086" class="v1n2dlbml"/><stop offset=".663" class="ohv650iba"/></linearGradient><linearGradient id="i2FoUFP" x1="15.999" x2="15.999" y1="24.842" y2="24.168" gradientUnits="userSpaceOnUse"><stop offset=".507" class="qqk6g6zlh"/><stop offset=".736" class="auud8yb7i"/></linearGradient><filter id="io2vxuc" width="11.22" height="12.542" x="10.932" y="4.657" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.333333 0 0 0 0 0.270588 0 0 0 0 0.258824 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3_799"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.145098 0 0 0 0 0.0705882 0 0 0 0 0.0745098 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3_799" result="effect2_innerShadow_3_799"/></filter><filter id="i4LjAzb" width="3.747" height="4.9" x="13.98" y="9.003" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_799" stdDeviation=".5"/></filter><filter id="imtVQ9c" width="2.277" height="3.3" x="14.857" y="9.608" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_799" stdDeviation=".1"/></filter><filter id="iFpeOHe" width="3.718" height="1.573" x="14.136" y="13.128" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_799" stdDeviation=".05"/></filter><filter id="ipRVF5c" width="12.873" height="8.356" x="9.559" y="1.48" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.137255 0 0 0 0 0.0901961 0 0 0 0 0.145098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3_799"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0784314 0 0 0 0 0.0352941 0 0 0 0 0.0470588 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3_799" result="effect2_innerShadow_3_799"/></filter><filter id="ihuSXed" width="2.339" height="1.19" x="17.585" y="7.144" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0588235 0 0 0 0 0.054902 0 0 0 0 0.0588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3_799"/></filter><filter id="idyVmQd" width="2.339" height="1.176" x="12.328" y="7.159" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0588235 0 0 0 0 0.054902 0 0 0 0 0.0588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3_799"/></filter><filter id="iSIWInc" width="6.734" height="5.992" x="9.915" y="2.569" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.286275 0 0 0 0 0.243137 0 0 0 0 0.227451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3_799"/><feGaussianBlur result="effect2_foregroundBlur_3_799" stdDeviation=".125"/></filter><filter id="ibwtOYc" width="6.361" height="5.736" x="15.836" y="2.993" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.305882 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3_799"/><feGaussianBlur result="effect2_foregroundBlur_3_799" stdDeviation=".125"/></filter><filter id="iJXdvUp" width=".787" height=".696" x="17.443" y="9.472" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_799" stdDeviation=".05"/></filter><filter id="iW09Y1B" width=".891" height=".913" x="18.283" y="9.547" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_799" stdDeviation=".1"/></filter><filter id="iIsxpve" width=".986" height="1.04" x="13.841" y="9.483" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_799" stdDeviation=".1"/></filter><filter id="iuXbOjd" width=".913" height=".705" x="13.086" y="9.463" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_799" stdDeviation=".05"/></filter><filter id="iwEMbGb" width="1.329" height="2.379" x="9.915" y="9.379" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_799" stdDeviation=".125"/></filter><filter id="iqVDOCe" width="1.947" height="2.903" x="20.438" y="9.111" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_799" stdDeviation=".25"/></filter><filter id="ikT9wUd" width="2.405" height="1.16" x="12.247" y="7.233" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_799" stdDeviation=".125"/></filter><filter id="iUNaECc" width="2.405" height="1.16" x="17.526" y="7.187" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_799" stdDeviation=".125"/></filter><filter id="ihQEIme" width="5.266" height="3.005" x="16.875" y="3.512" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_799" stdDeviation=".375"/></filter><filter id="iYsaczb" width="22" height="14.1" x="5" y="16.02" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.678431 0 0 0 0 0.670588 0 0 0 0 0.682353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3_799"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:technologist-dark" /></template>
<style>
.a-otvg7dq {
  stop-color: var(--svg-color--806b97, #806B97);
}

.a4rldd3-z {
  stop-color: var(--svg-color--685554, #685554);
  stop-opacity: 0;
}

.a61ap5b7j {
  stop-color: var(--svg-color--9f93b2, #9F93B2);
}

.a7w75bcbh {
  d: path("m21.208 8.479l-.03-.631c-.01-.764-.64-1.394-1.404-1.426h-1.4c-.89 0-1.7-.486-2.124-1.26c0 0-.059-.135-.12-.368c-.257-.97.67-1.712 1.655-1.521c.974.189 2.082.517 2.902 1.052c1.745 1.137 1.44 3.188.521 4.154");
}

.abx50lnlm {
  stop-color: var(--svg-color--3e2230, #3E2230);
}

.ahguepbtf {
  stop-color: var(--svg-color--3c2828, #3C2828);
}

.akw4fybhj {
  stop-color: var(--svg-color--351b1e, #351B1E);
}

.am-vu7akn {
  d: path("m15.613 10.113l-.531 1.838c-.109.378.152.757.52.757h.787c.369 0 .629-.384.52-.757l-.531-1.838c-.114-.407-.645-.407-.765 0");
}

.asp-974pn {
  stop-color: var(--svg-color--432728, #432728);
}

.auud8yb7i {
  stop-color: var(--svg-color--4a3261, #4A3261);
  stop-opacity: 0;
}

.ax3t7fbst {
  d: path("M8.329 30.02q.004-.082.004-.163a3.138 3.138 0 1 0-6.271.162z");
}

.axstwemrb {
  stop-color: var(--svg-color--423c3f, #423C3F);
}

.ay2574bqt {
  stop-color: var(--svg-color--301929, #301929);
  stop-opacity: 0;
}

.azmmzob6j {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.605 9.163c-.654 0-1.205.45-1.355 1.058a.274.274 0 0 0 .267.341h2.232a.23.23 0 0 0 .227-.272a1.4 1.4 0 0 0-1.371-1.127");
}

.bbyb_mbsk {
  stop-color: var(--svg-color--664842, #664842);
}

.bf-s3qwzt {
  stop-color: var(--svg-color--634d49, #634D49);
}

.bf6_qrkvm {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M14.645 13.33h-.001a.23.23 0 0 0-.271.046a.21.21 0 0 0-.023.27c.348.528.955.88 1.645.88s1.298-.352 1.646-.88a.214.214 0 0 0-.023-.272a.23.23 0 0 0-.271-.045c-.39.204-.85.32-1.352.32a2.9 2.9 0 0 1-1.35-.32Z");
}

.bmcblacal {
  stop-color: var(--svg-color--492f32, #492F32);
}

.bnagblbqa {
  d: path("M18.975 10.21a.84.84 0 0 0-.232-.463l-.26.285l.118.228z");
}

.bowxt9bwr {
  stop-color: var(--svg-color--6f5783, #6F5783);
}

.brpuz_b9y {
  d: path("M10.91 9.63a.956.956 0 0 0 .083 1.878a78 78 0 0 1-.083-1.879");
}

.c2_7179_n {
  stop-color: var(--svg-color--432742, #432742);
  stop-opacity: 0;
}

.c4l15nbte {
  stop-color: var(--svg-color--2c1d22, #2C1D22);
}

.c5e-i-5dw {
  stop-color: var(--svg-color--361c1e, #361C1E);
  stop-opacity: 0;
}

.c5jm6bc5b {
  d: path("M16 15.52c-6.07 0-11 4.92-11 11v3.5h22v-3.5c0-6.08-4.93-11-11-11");
}

.c98z413ze {
  stop-color: var(--svg-color--4f4d4d, #4F4D4D);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cur91yz5h {
  cx: 13.542px;
  cy: 9.816px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.cxt8_ibda {
  fill: var(--svg-color--331e24, #331E24);
  d: path("m15.594 10.309l-.59 1.838c-.102.378.14.756.484.756h.731c.343 0 .586-.383.485-.756l-.495-1.838c-.106-.407-.504-.407-.615 0");
}

.d8gqn2snf {
  stop-color: var(--svg-color--66514e, #66514E);
}

.d9m_15bme {
  stop-color: var(--svg-color--a191b5, #A191B5);
  stop-opacity: 0;
}

.dmu1fh1sq {
  stop-color: var(--svg-color--beb0b0, #BEB0B0);
}

.dn2_hckup {
  stop-color: var(--svg-color--49201f, #49201F);
}

.dwl_ftd7p {
  stop-color: var(--svg-color--1c0c20, #1C0C20);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.edicxsbpr {
  d: path("M10.942 8.969a1.61 1.61 0 0 0 .138 3.2a78 78 0 0 1-.139-3.2");
}

.epf-qq6ay {
  stop-color: var(--svg-color--301924, #301924);
}

.eu7hrybov {
  stop-color: var(--svg-color--533e40, #533E40);
  stop-opacity: 0;
}

.ev2lxub8z {
  d: path("M20.938 11.514q.059-.952.111-1.903a.956.956 0 0 1-.11 1.903");
}

.ez41_pbnb {
  stop-color: var(--svg-color--423c3f, #423C3F);
  stop-opacity: 0;
}

.f28ypccjc {
  stop-color: var(--svg-color--534445, #534445);
}

.fch_lgr5q {
  stop-color: var(--svg-color--1c0c20, #1C0C20);
  stop-opacity: 0;
}

.ff9bywbjm {
  stop-color: var(--svg-color--634d49, #634D49);
  stop-opacity: 0;
}

.fglza-d-f {
  stop-color: var(--svg-color--40222d, #40222D);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.g0smdzbso {
  d: path("M18.114 9.623c.063.085-.07.189-.22.302c-.152.113-.264.192-.327.107c-.064-.085.007-.245.158-.358s.325-.136.389-.051");
}

.g1u_xnbmn {
  stop-color: var(--svg-color--301929, #301929);
}

.g3ux3cbys {
  d: path("M8.98 18.02a10.99 10.99 0 0 0-3.97 8.5l.02 3.5l4-.02z");
}

.g48yfbn9k {
  stop-color: var(--svg-color--5f447b, #5F447B);
  stop-opacity: 0;
}

.gc1t1221f {
  fill: var(--svg-color--1f151b, #1F151B);
  d: path("m21.208 8.479l-.03-.631c-.01-.764-.64-1.394-1.404-1.426h-1.4c-.89 0-1.7-.486-2.124-1.26c0 0-.059-.135-.12-.368c-.257-.97.67-1.712 1.655-1.521c.974.189 2.082.517 2.902 1.052c1.745 1.137 1.44 3.188.521 4.154");
}

.gg1n47rtb {
  stop-color: var(--svg-color--463c39, #463C39);
}

.gzfhb8b1n {
  stop-color: var(--svg-color--beb7c7, #BEB7C7);
}

.h12s_qbsc {
  stroke: var(--svg-color--353535, #353535);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M12.622 8.019c.257-.185.898-.51 1.656-.382");
}

.h1qder98v {
  stop-color: var(--svg-color--432742, #432742);
}

.hnw0p1utu {
  stop-color: var(--svg-color--0b0306, #0B0306);
}

.ibt06e6rm {
  stop-color: var(--svg-color--3e3433, #3E3433);
}

.iesato94l {
  fill: var(--svg-color--504a4c, #504A4C);
  d: path("M20.188 5.23h-2.08a.483.483 0 1 1 .077-.962c.54.086 1.256.206 1.737.325c1.085.27 1.385.798 1.469 1.175a1.51 1.51 0 0 0-1.203-.539");
}

.ih-ladlvk {
  fill: var(--svg-color--000, #000);
  d: path("M14.323 10.327a.51.51 0 0 0-.511-.511a.51.51 0 0 0-.455.746h.905a.5.5 0 0 0 .06-.235");
}

.j-n0q842a {
  stop-color: var(--svg-color--564440, #564440);
}

.jehi2ihjx {
  stop-color: var(--svg-color--e5dff1, #E5DFF1);
  stop-opacity: 0;
}

.jk-0m6p0q {
  stop-color: var(--svg-color--49201f, #49201F);
  stop-opacity: 0;
}

.jk21n9bik {
  fill: var(--svg-color--402929, #402929);
  d: path("m15.613 10.113l-.531 1.838c-.109.378.152.757.52.757h.787c.369 0 .629-.384.52-.757l-.531-1.838c-.114-.407-.645-.407-.765 0");
}

.jrlin1f0e {
  stop-color: var(--svg-color--372425, #372425);
}

.jsqgobbht {
  d: path("M26.03 16.02H5.97a.97.97 0 0 0-.97.97v13.03h22V16.99a.97.97 0 0 0-.97-.97");
}

.jzh_zdb1u {
  fill: var(--svg-color--202020, #202020);
  d: path("M12.585 7.739a2.77 2.77 0 0 1 1.739-.36a.277.277 0 1 1-.068.551a2.22 2.22 0 0 0-1.387.285a1 1 0 0 0-.091.06l-.003.002a.277.277 0 0 1-.34-.439z");
}

.k45xjwbmq {
  stop-color: var(--svg-color--3e3433, #3E3433);
  stop-opacity: 0;
}

.k53yjlbth {
  stop-color: var(--svg-color--563b38, #563B38);
}

.k71v6_7um {
  stop-color: var(--svg-color--51366c, #51366C);
}

.kh_x-hbqh {
  stop-color: var(--svg-color--4b302a, #4B302A);
  stop-opacity: 0;
}

.knye9dzad {
  stroke: var(--svg-color--353535, #353535);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M19.557 7.972c-.257-.184-.898-.508-1.656-.38");
}

.kydculhfm {
  stop-color: var(--svg-color--272127, #272127);
}

.l-dnxbb6m {
  fill: var(--svg-color--23181c, #23181C);
  d: path("m16.228 5.212l-.066-.137a.66.66 0 0 0-.615-.418h-1.273c-1.846 0-3.342 1.512-3.342 3.379v.275c-.34-.259-.767-.804-.767-1.688c0-1.072.781-1.613 1.28-1.959c.14-.097.259-.18.33-.253l.1-.105c.35-.37.973-1.031 2.06-1.32a5.5 5.5 0 0 1 1.508-.165c.473.012.806.42.806.893v1.485z");
}

.l17xqebtl {
  stop-color: var(--svg-color--594170, #594170);
}

.l1vex1b6a {
  stop-color: var(--svg-color--443d40, #443D40);
}

.l294t3zvi {
  stop-color: var(--svg-color--847498, #847498);
}

.l2dudh2nh {
  stop-color: var(--svg-color--432728, #432728);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lkqzgvv7h {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.386 9.163c.654 0 1.205.45 1.355 1.058a.274.274 0 0 1-.267.341h-2.232a.23.23 0 0 1-.227-.272c.126-.64.69-1.127 1.371-1.127");
}

.lwf47ccyr {
  stop-color: var(--svg-color--62504f, #62504F);
}

.m0er3vbow {
  d: path("M11.134 12.078a1.64 1.64 0 0 1-.904-.309v.931c0 .893.532 1.689 1.34 2.019a4.1 4.1 0 0 1-.345-1.18z");
}

.m6jz2xbwk {
  d: path("M20.917 12.169q.1-1.597.185-3.192a1.61 1.61 0 0 1-.185 3.192");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mfkgssbjj {
  stop-color: var(--svg-color--361e27, #361E27);
  stop-opacity: 0;
}

.msex9gbuq {
  stop-color: var(--svg-color--533e40, #533E40);
}

.n55x1ubvq {
  stop-color: var(--svg-color--533837, #533837);
  stop-opacity: 0;
}

.nbncwobqn {
  stop-color: var(--svg-color--6b5957, #6B5957);
}

.nhtj7e8qx {
  fill: var(--svg-color--000, #000);
  d: path("M17.669 10.327c0-.284.227-.511.51-.511a.51.51 0 0 1 .455.746h-.905a.46.46 0 0 1-.06-.235");
}

.nonrr22es {
  stop-color: var(--svg-color--e5dff1, #E5DFF1);
}

.nv2d3lbzc {
  d: path("M13.812 9.434a.893.893 0 0 0-.86 1.128h1.724a1 1 0 0 0 .032-.235a.9.9 0 0 0-.896-.893");
}

.nvbd3gb0w {
  d: path("m16.228 5.212l-.066-.137a.66.66 0 0 0-.615-.418h-1.273c-1.846 0-3.342 1.512-3.342 3.379v.275c-.34-.259-.767-.804-.767-1.688c0-1.072.781-1.613 1.28-1.959c.14-.097.259-.18.33-.253l.1-.105c.35-.37.973-1.031 2.06-1.32a5.5 5.5 0 0 1 1.508-.165c.473.012.806.42.806.893v1.485z");
}

.ny9_xhbeh {
  d: path("M23 18.03v11.98h4v-3.5c0-3.41-1.56-6.46-4-8.48");
}

.o-j_7gbpq {
  stop-color: var(--svg-color--564440, #564440);
  stop-opacity: 0;
}

.o1-qqkidl {
  stop-color: var(--svg-color--78698c, #78698C);
}

.o2r2q6blp {
  stop-color: var(--svg-color--4b302a, #4B302A);
}

.ob3l4g_ys {
  stop-color: var(--svg-color--584a4a, #584A4A);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ohv650iba {
  stop-color: var(--svg-color--52376c, #52376C);
  stop-opacity: 0;
}

.ovvtmacpn {
  stop-color: var(--svg-color--4f4d4d, #4F4D4D);
  stop-opacity: 0;
}

.oz5jd4bmy {
  stop-color: var(--svg-color--66514e, #66514E);
  stop-opacity: 0;
}

.p8isx8b7k {
  stop-color: var(--svg-color--3e2b29, #3E2B29);
  stop-opacity: 0;
}

.p9llu9bpa {
  stop-color: var(--svg-color--9f93b2, #9F93B2);
  stop-opacity: 0;
}

.pft2s7y0a {
  stop-color: var(--svg-color--221c27, #221C27);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.ppwrykbzp {
  d: path("M14.444 21.89a.25.25 0 0 1 .25-.25h2.61a.25.25 0 0 1 .25.25v2.417a.25.25 0 0 1-.25.25h-2.61a.25.25 0 0 1-.25-.25z");
}

.prh5swccd {
  stop-color: var(--svg-color--563b38, #563B38);
  stop-opacity: 0;
}

.psn4zabca {
  stop-color: var(--svg-color--231112, #231112);
  stop-opacity: 0;
}

.pxaxwjbdw {
  d: path("M11.17 13.593a3.916 3.916 0 0 0 3.886 3.405h1.887a3.916 3.916 0 0 0 3.885-3.406c.118-1.883.237-3.76.325-5.642a1.45 1.45 0 0 0-1.38-1.432h-1.4a2.42 2.42 0 0 1-2.211-1.443a.66.66 0 0 0-.615-.418h-1.273c-1.846 0-3.342 1.512-3.342 3.379c0 1.86.116 3.691.239 5.557");
}

.q0dxfdmim {
  stop-color: var(--svg-color--7a6b8e, #7A6B8E);
  stop-opacity: 0;
}

.q3b-p60-b {
  stop-color: var(--svg-color--4c3838, #4C3838);
}

.q53v6mhsp {
  stop-color: var(--svg-color--1b141e, #1B141E);
}

.qco-2_b3r {
  stop-color: var(--svg-color--484646, #484646);
}

.qoxj776_o {
  stop-color: var(--svg-color--351b1e, #351B1E);
  stop-opacity: 0;
}

.qqk6g6zlh {
  stop-color: var(--svg-color--3d2555, #3D2555);
}

.qufyc6r7b {
  stop-color: var(--svg-color--56416b, #56416B);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r1d3vkbxd {
  stop-color: var(--svg-color--6d5686, #6D5686);
}

.r95ztqgly {
  stop-color: var(--svg-color--271416, #271416);
}

.rra4r9bnq {
  stop-color: var(--svg-color--3c3b3c, #3C3B3C);
}

.rt1r2lbdx {
  d: path("M20.857 12.078a1.64 1.64 0 0 0 .904-.309v.931c0 .893-.532 1.689-1.34 2.019q.256-.546.345-1.18z");
}

.sbhjtg7pq {
  stop-color: var(--svg-color--6b5b59, #6B5B59);
  stop-opacity: 0;
}

.segtfez6g {
  d: path("M15.995 13.724c-.507 0-.984-.12-1.385-.328c-.137-.07-.284.084-.198.209c.335.508.919.846 1.583.846c.665 0 1.249-.338 1.584-.846c.086-.13-.061-.279-.198-.21a3 3 0 0 1-1.386.33");
}

.szee5wb8m {
  stop-color: var(--svg-color--361c1e, #361C1E);
}

.szjcm-w7x {
  stop-color: var(--svg-color--beb7c7, #BEB7C7);
  stop-opacity: 0;
}

.t_w5hobcp {
  stop-color: var(--svg-color--8d78a4, #8D78A4);
  stop-opacity: 0;
}

.t5hji7b2p {
  d: path("M14.627 10.222c0-.289-.235-.48-.298-.539l-.288.279l.177.361z");
}

.t9w88ccap {
  fill: var(--svg-color--533836, #533836);
  d: path("M29.938 30.02q.005-.082.005-.163a3.138 3.138 0 1 0-6.272.162z");
}

.td7qnxbmr {
  d: path("M29.938 30.02q.005-.082.005-.163a3.138 3.138 0 1 0-6.272.162z");
}

.txgsuxr-c {
  stop-color: var(--svg-color--685554, #685554);
}

.u-2msu4yh {
  stop-color: var(--svg-color--3e2230, #3E2230);
  stop-opacity: 0;
}

.ua_qcxh-g {
  d: path("M20.85 4.185a2.32 2.32 0 0 1 1.268 1.051a2.37 2.37 0 0 1-.106 2.526c-.175.258-.27.564-.27.875v1.188a1.75 1.75 0 0 0-.668-.268l.079-1.607a1.45 1.45 0 0 0-1.38-1.432h-1.4a2.42 2.42 0 0 1-2.211-1.443a.66.66 0 0 0-.615-.418h-1.273c-1.846 0-3.342 1.512-3.342 3.379l.03 1.537a1.7 1.7 0 0 0-.72.264v-1.2a1.56 1.56 0 0 0-.27-.875a2.39 2.39 0 0 1-.143-2.445a2.34 2.34 0 0 1 1.3-1.127a2.68 2.68 0 0 0 1.384-1.11a2.325 2.325 0 0 1 2.89-.912a1.5 1.5 0 0 0 1.194 0c.28-.118.588-.188.912-.188c.843 0 1.58.456 1.989 1.132c.307.51.79.88 1.352 1.073");
}

.udkr-um3k {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.114 9.623c.063.085-.07.189-.22.302c-.152.113-.264.192-.327.107c-.064-.085.007-.245.158-.358s.325-.136.389-.051");
}

.uem0lbchq {
  stop-color: var(--svg-color--4f3568, #4F3568);
}

.unyhdjbdq {
  stop-color: var(--svg-color--200e25, #200E25);
}

.ux-m5bn7d {
  stop-color: var(--svg-color--ab9cbe, #AB9CBE);
}

.v1mb2vv6g {
  cx: 13.542px;
  cy: 9.816px;
  rx: 0.39px;
  ry: 0.197px;
}

.v1n2dlbml {
  stop-color: var(--svg-color--3b2b50, #3B2B50);
}

.v3ih9bcyp {
  stop-color: var(--svg-color--3e2724, #3E2724);
}

.v8idy2p3c {
  fill: var(--svg-color--202020, #202020);
  d: path("M19.729 7.848a1.85 1.85 0 0 0-.688-.411c-.304-.096-.685-.122-1.213-.057a.277.277 0 1 0 .068.55c.481-.059.776-.028.978.036c.199.062.333.163.49.3a.277.277 0 1 0 .364-.418");
}

.vuad6pb7r {
  stop-color: var(--svg-color--1c1c1c, #1C1C1C);
}

.w0a4mmrgb {
  stop-color: var(--svg-color--200e25, #200E25);
  stop-opacity: 0;
}

.w189cfbhy {
  stop-color: var(--svg-color--290018, #290018);
}

.w37r5utea {
  stop-color: var(--svg-color--3f2c2a, #3F2C2A);
}

.w6exmsbsa {
  fill-opacity: var(--svg-fill-opacity--0-6, 0.6);
  d: path("M14.444 21.89a.25.25 0 0 1 .25-.25h2.61a.25.25 0 0 1 .25.25v2.417a.25.25 0 0 1-.25.25h-2.61a.25.25 0 0 1-.25-.25z");
}

.w9bfwpbnq {
  stop-color: var(--svg-color--60407f, #60407F);
}

.ww86j5--q {
  stop-color: var(--svg-color--361e27, #361E27);
}

.wyv1gnbxf {
  stop-color: var(--svg-color--5e5a5b, #5E5A5B);
}

.x73tbcc6t {
  stop-color: var(--svg-color--6b5b59, #6B5B59);
}

.xbtbagqno {
  stop-color: var(--svg-color--301924, #301924);
  stop-opacity: 0;
}

.xjcxgac6b {
  stop-color: var(--svg-color--231112, #231112);
}

.xomn_jqkl {
  stop-color: var(--svg-color--503c3b, #503C3B);
}

.xqmtwwbyq {
  stop-color: var(--svg-color--614c77, #614C77);
}

.y26jaac_x {
  d: path("M18.18 9.434a.893.893 0 0 1 .86 1.128h-1.724a.896.896 0 0 1 .864-1.128");
}

.yr342ibfl {
  stop-color: var(--svg-color--bab9c0, #BAB9C0);
}

.yvpae5bzc {
  stop-color: var(--svg-color--3b2a28, #3B2A28);
}

.z5a_p6x5j {
  stop-color: var(--svg-color--290017, #290017);
}

.z6d-f52gr {
  stop-color: var(--svg-color--5e5a5b, #5E5A5B);
  stop-opacity: 0;
}

.zaeth0b6d {
  stop-color: var(--svg-color--636363, #636363);
}

.zkb-swu-c {
  stop-color: var(--svg-color--534445, #534445);
  stop-opacity: 0;
}

.zt_ualb3u {
  stop-color: var(--svg-color--543870, #543870);
  stop-opacity: 0;
}

.zwo50zm6y {
  stop-color: var(--svg-color--484646, #484646);
  stop-opacity: 0;
}

.zzkrmpd6m {
  stop-color: var(--svg-color--281919, #281919);
}

</style>
