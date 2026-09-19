<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#ieDqGCe)" class="ax3t7fbst"/><path fill="url(#iyfWYTb)" class="ax3t7fbst"/><path fill="url(#iDIM01A)" class="ax3t7fbst"/><path class="i1gnb4bzt"/><path fill="url(#irUBvHb)" class="td7qnxbmr"/><path fill="url(#iUY6N3Q)" class="td7qnxbmr"/><path fill="url(#inT0zab)" class="c5jm6bc5b"/><path fill="url(#iRI2yhd)" class="g3ux3cbys"/><path fill="url(#ihnjaeb)" class="ny9_xhbeh"/><path fill="url(#iAYowKd)" class="ykrihkbqd"/><path fill="url(#iDOXIQc)" class="m0er3vbow"/><g filter="url(#iIH1jyd)"><path fill="url(#iWOqpRd)" class="v9i4yfbgf"/></g><path fill="url(#iEnmIFc)" class="v9i4yfbgf"/><path fill="url(#izJSmub)" class="v9i4yfbgf"/><path fill="url(#iQ7xrob)" class="v9i4yfbgf"/><path fill="url(#iebD80b)" class="v9i4yfbgf"/><path fill="url(#ijJUfJb)" class="v9i4yfbgf"/><path fill="url(#iPOv6ud)" class="v9i4yfbgf"/><path fill="url(#i3Zvf8M)" class="v9i4yfbgf"/><g filter="url(#i1gYIwc)"><path class="nk5451p5c"/></g><g filter="url(#igpyjHe)"><path class="g-12-6bdv"/><path fill="url(#iE7AYGd)" class="e9ghhhbuh"/><path fill="url(#iB5ZgNL)" class="e9ghhhbuh"/><path fill="url(#i0MgEeS)" class="e9ghhhbuh"/><path fill="url(#i0jQF2d)" class="e9ghhhbuh"/><path fill="url(#iygWuib)" class="e9ghhhbuh"/></g><g filter="url(#i56crvd)"><path stroke="url(#inuY99d)" class="x1n2x_pbt"/></g><path fill="url(#iIsNACb)" class="segtfez6g"/><g filter="url(#iFNKp8c)"><path fill="url(#iDDU8kb)" class="e3urzdusl"/><path fill="url(#iEo9LKc)" class="e3urzdusl"/><path fill="url(#iz6yajU)" class="e3urzdusl"/><path fill="url(#ia8gaVL)" class="e3urzdusl"/><path fill="url(#iKRY11d)" class="e3urzdusl"/></g><g filter="url(#i8sTRmb)"><path class="gyf6hdc9c"/></g><g filter="url(#ivO9pJe)"><path class="cn0pc3b_h"/></g><g filter="url(#ickIGVi)"><path class="l-dnxbb6m"/><path fill="url(#ijbFdBe)" class="nvbd3gb0w"/><path fill="url(#i2dHweb)" class="nvbd3gb0w"/></g><g filter="url(#iem69gd)"><path class="wtsvdfp9l"/><path fill="url(#iX5ZeFj)" class="kylgx8brm"/><path fill="url(#i5lhG1c)" class="kylgx8brm"/><path fill="url(#i0aJt0d)" class="kylgx8brm"/></g><path class="lkqzgvv7h"/><path fill="url(#iSPWV3E)" class="y26jaac_x"/><path class="l52wxacgn"/><g filter="url(#i4UpiTb)"><path class="udkr-um3k"/><path fill="url(#iPNAJNd)" class="g0smdzbso"/></g><g filter="url(#iaeEFAe)"><path fill="url(#izSgSbd)" class="bnagblbqa"/></g><path class="ieumhfb7o"/><path fill="url(#iVKjuKc)" class="yhrpqc-is"/><path class="xv861oxon"/><g filter="url(#iHbUpxe)"><path fill="url(#isftRge)" class="qxr6d6bvb"/></g><g filter="url(#iYDhBac)"><ellipse transform="rotate(-27.914 13.542 9.816)" class="cur91yz5h"/><ellipse fill="url(#i9HExNc)" transform="rotate(-27.914 13.542 9.816)" class="v1mb2vv6g"/></g><path fill="url(#iWcm5NK)" class="m6jz2xbwk"/><path fill="url(#iwbEJmc)" class="m6jz2xbwk"/><path fill="url(#ipThnTc)" class="m6jz2xbwk"/><path fill="url(#i2bk08d)" class="m6jz2xbwk"/><path fill="url(#iazOGEb)" class="n6e91uy-z"/><path fill="url(#iELsEde)" class="n6e91uy-z"/><g filter="url(#iQ9RExd)"><path fill="url(#iMNkRuc)" class="brpuz_b9y"/></g><g filter="url(#iRKcsfd)"><path fill="url(#iOkO7Ib)" class="uap_-o0jx"/></g><g filter="url(#ieLtZtf)"><path class="kra16rbyh"/></g><g filter="url(#i6A4nMb)"><path class="sri2ty5ve"/></g><g filter="url(#i4G1RqQ)"><path fill="url(#iHXaVce)" class="jsqgobbht"/><path fill="url(#i2BUj5L)" class="jsqgobbht"/><path fill="url(#iqtSqJd)" class="jsqgobbht"/><path fill="url(#iNN1SaK)" class="jsqgobbht"/><path fill="url(#irzSjbb)" class="jsqgobbht"/><path fill="url(#ihI2zKe)" class="jsqgobbht"/></g><path fill="url(#ixwQhto)" class="ppwrykbzp"/><path fill="url(#i8N6NDd)" class="ppwrykbzp"/><path fill="url(#ilcEH9d)" class="ppwrykbzp"/><path fill="url(#iKDpaee)" class="ppwrykbzp"/><path fill="url(#i2FoUFP)" class="ppwrykbzp"/><path fill="url(#iWis4Qd)" class="w6exmsbsa"/><defs><radialGradient id="ieDqGCe" cx="0" cy="0" r="1" gradientTransform="rotate(-156.777 5.833 14.445)scale(2.6864 2.91777)" gradientUnits="userSpaceOnUse"><stop class="ina1t94tm"/><stop offset="1" class="gl470lbeq"/></radialGradient><radialGradient id="iyfWYTb" cx="0" cy="0" r="1" gradientTransform="rotate(177.157 2.332 14.994)scale(3.35044 4.79049)" gradientUnits="userSpaceOnUse"><stop offset=".764" class="f65wxmfgp"/><stop offset=".927" class="iwc2szfpk"/></radialGradient><radialGradient id="iDIM01A" cx="0" cy="0" r="1" gradientTransform="rotate(142.141 -1.796 14.45)scale(2.29569 2.48045)" gradientUnits="userSpaceOnUse"><stop class="z9sgh-b_k"/><stop offset="1" class="wpv14ybvl"/></radialGradient><radialGradient id="irUBvHb" cx="0" cy="0" r="1" gradientTransform="matrix(5.64062 -3.71875 1.03844 1.57511 27.091 30.119)" gradientUnits="userSpaceOnUse"><stop offset=".127" class="phpmogblj"/><stop offset="1" class="vcl0nfbxz"/></radialGradient><radialGradient id="iAYowKd" cx="0" cy="0" r="1" gradientTransform="rotate(69.657 1.917 20.796)scale(2.15387 2.55864)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="xsgkrbcbf"/><stop offset="1" class="ek_f7q3hx"/></radialGradient><radialGradient id="iDOXIQc" cx="0" cy="0" r="1" gradientTransform="matrix(1.47646 .46403 -1.43156 4.55498 9.939 12.26)" gradientUnits="userSpaceOnUse"><stop class="oaig2cbln"/><stop offset=".746" class="gfuj0ibqm"/></radialGradient><radialGradient id="iWOqpRd" cx="0" cy="0" r="1" gradientTransform="matrix(-5.22784 0 0 -9.248 18.803 10.828)" gradientUnits="userSpaceOnUse"><stop class="yzaj_tb_p"/><stop offset="1" class="ny0rq0bux"/></radialGradient><radialGradient id="izJSmub" cx="0" cy="0" r="1" gradientTransform="matrix(-.99815 12.76794 -10.57334 -.82659 17.577 4.914)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="ly6gn-bwx"/><stop offset=".946" class="fpnaw0o7f"/></radialGradient><radialGradient id="iQ7xrob" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.14835 1.42108 0 18.443 9.515)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="h739mqb_c"/><stop offset="1" class="px0sb7ebt"/></radialGradient><radialGradient id="iebD80b" cx="0" cy="0" r="1" gradientTransform="matrix(.00393 -1.09427 1.19083 .00428 13.695 9.561)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="kxaprmbjh"/><stop offset="1" class="vgn1hf8dm"/></radialGradient><radialGradient id="ijJUfJb" cx="0" cy="0" r="1" gradientTransform="matrix(-8.49597 .5363 -1.37 -21.7029 19.428 11.816)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="uwe7yhbem"/><stop offset="1" class="snpr2ctwr"/></radialGradient><radialGradient id="iPOv6ud" cx="0" cy="0" r="1" gradientTransform="matrix(3.0984 -3.27776 1.1999 1.13424 10.528 6.503)" gradientUnits="userSpaceOnUse"><stop offset=".428" class="mqqgujbcq"/><stop offset="1" class="fki8vhbsq"/></radialGradient><radialGradient id="i3Zvf8M" cx="0" cy="0" r="1" gradientTransform="matrix(-1.74316 2.88295 -2.3801 -1.43912 18.423 5.849)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="lombttb9q"/><stop offset="1" class="bvf2i9bjf"/></radialGradient><radialGradient id="iB5ZgNL" cx="0" cy="0" r="1" gradientTransform="matrix(0 .2441 -.76718 0 16.462 12.188)" gradientUnits="userSpaceOnUse"><stop class="t40345qox"/><stop offset="1" class="mrnsdcbqx"/></radialGradient><radialGradient id="i0jQF2d" cx="0" cy="0" r="1" gradientTransform="matrix(-1.52115 .69743 -1.12083 -2.4446 16.578 11.619)" gradientUnits="userSpaceOnUse"><stop offset=".714" class="o0aif1l1c"/><stop offset="1" class="vni43obah"/></radialGradient><radialGradient id="iIsNACb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.72074 2.8997 0 15.995 14.367)" gradientUnits="userSpaceOnUse"><stop class="jase_0f7h"/><stop offset="1" class="zn-qjxbde"/></radialGradient><radialGradient id="iEo9LKc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.50132 8.85443 0 10.766 7.935)" gradientUnits="userSpaceOnUse"><stop offset=".536" class="ibt06e6rm"/><stop offset="1" class="k45xjwbmq"/></radialGradient><radialGradient id="iz6yajU" cx="0" cy="0" r="1" gradientTransform="rotate(-87.401 15.266 -6.29)scale(2.51513 4.45631)" gradientUnits="userSpaceOnUse"><stop class="c98z413ze"/><stop offset="1" class="ovvtmacpn"/></radialGradient><radialGradient id="ia8gaVL" cx="0" cy="0" r="1" gradientTransform="matrix(-2.35883 -1.5514 1.1388 -1.7315 20.102 2.97)" gradientUnits="userSpaceOnUse"><stop class="wyv1gnbxf"/><stop offset="1" class="z6d-f52gr"/></radialGradient><radialGradient id="iKRY11d" cx="0" cy="0" r="1" gradientTransform="matrix(.90512 1.475 -3.41539 2.09582 15.09 1.376)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="qco-2_b3r"/><stop offset="1" class="zwo50zm6y"/></radialGradient><radialGradient id="ijbFdBe" cx="0" cy="0" r="1" gradientTransform="matrix(-2.20112 0 0 -.81692 16.249 3.636)" gradientUnits="userSpaceOnUse"><stop class="axstwemrb"/><stop offset="1" class="ez41_pbnb"/></radialGradient><radialGradient id="i2dHweb" cx="0" cy="0" r="1" gradientTransform="matrix(3.21816 -5.09543 5.64521 3.5654 10.565 7.579)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="hnw0p1utu"/><stop offset=".311" class="dwl_ftd7p"/><stop offset="1" class="fch_lgr5q"/></radialGradient><radialGradient id="iX5ZeFj" cx="0" cy="0" r="1" gradientTransform="matrix(3.05838 0 0 1.19577 19.41 4.413)" gradientUnits="userSpaceOnUse"><stop class="nszf4yi9c"/><stop offset="1" class="a061yvbds"/></radialGradient><radialGradient id="i5lhG1c" cx="0" cy="0" r="1" gradientTransform="matrix(2.67872 -2.55217 4.67237 4.90405 18.63 7.45)" gradientUnits="userSpaceOnUse"><stop offset=".857" class="stq0hsb2e"/><stop offset="1" class="i6xvtdb8e"/></radialGradient><radialGradient id="i0aJt0d" cx="0" cy="0" r="1" gradientTransform="matrix(3.2482 .37966 -.15896 1.35996 17.743 5.974)" gradientUnits="userSpaceOnUse"><stop class="unyhdjbdq"/><stop offset="1" class="w0a4mmrgb"/></radialGradient><radialGradient id="iSPWV3E" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.29049 0 18.177 9.911)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="iPNAJNd" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 11.422 .602)scale(.37829 .52081)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iVKjuKc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81136 -1.29056 0 13.813 9.911)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="i9HExNc" cx="0" cy="0" r="1" gradientTransform="matrix(-.00774 -.49408 .59392 -.0093 13.527 10.13)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iwbEJmc" cx="0" cy="0" r="1" gradientTransform="matrix(.62855 2.24327 -2.14025 .59968 20.613 9.925)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="uuzk4vb7h"/><stop offset="1" class="yor2p9b5i"/></radialGradient><radialGradient id="ipThnTc" cx="0" cy="0" r="1" gradientTransform="matrix(.78778 -1.0811 .90618 .66032 20.974 10.47)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="iz6q0pbtm"/><stop offset="1" class="wmov6-bei"/></radialGradient><radialGradient id="i2bk08d" cx="0" cy="0" r="1" gradientTransform="matrix(.587 -1.55042 2.07158 .7843 21.088 10.643)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="r8tuldb4n"/><stop offset="1" class="c_6967ufg"/></radialGradient><radialGradient id="iELsEde" cx="0" cy="0" r="1" gradientTransform="rotate(-173.034 5.862 4.947)scale(1.62516 1.74453)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="o8wr4h7sd"/><stop offset="1" class="t0w03e0rr"/></radialGradient><radialGradient id="iMNkRuc" cx="0" cy="0" r="1" gradientTransform="matrix(-.91648 .15731 -.19303 -1.12456 11.08 10.568)" gradientUnits="userSpaceOnUse"><stop class="ab9g3hmui"/><stop offset="1" class="bwc1tpbev"/></radialGradient><radialGradient id="i2BUj5L" cx="0" cy="0" r="1" gradientTransform="matrix(0 -7.59705 13.2772 0 17.243 31.067)" gradientUnits="userSpaceOnUse"><stop offset=".027" class="o1-qqkidl"/><stop offset="1" class="q0dxfdmim"/></radialGradient><radialGradient id="ihI2zKe" cx="0" cy="0" r="1" gradientTransform="matrix(-.78125 .4375 -.4057 -.72446 26.696 16.66)" gradientUnits="userSpaceOnUse"><stop class="nonrr22es"/><stop offset=".724" class="jehi2ihjx"/></radialGradient><radialGradient id="iWis4Qd" cx="0" cy="0" r="1" gradientTransform="matrix(-.0957 .08008 -.11939 -.14269 17.371 21.824)" gradientUnits="userSpaceOnUse"><stop class="a-otvg7dq"/><stop offset="1" class="t_w5hobcp"/></radialGradient><linearGradient id="iUY6N3Q" x1="26.607" x2="27.302" y1="28.838" y2="28.838" gradientUnits="userSpaceOnUse"><stop class="pfqkh_b6e"/><stop offset="1" class="q1cl32x8o"/><stop offset="1" class="fm6jtfbaq"/></linearGradient><linearGradient id="inT0zab" x1="16" x2="16" y1="6.703" y2="34.611" gradientUnits="userSpaceOnUse"><stop class="zaeth0b6d"/><stop offset="1" class="vuad6pb7r"/></linearGradient><linearGradient id="iRI2yhd" x1="10.918" x2="1.428" y1="24.003" y2="24.044" gradientUnits="userSpaceOnUse"><stop class="vuad6pb7r"/><stop offset="1" class="zaeth0b6d"/></linearGradient><linearGradient id="ihnjaeb" x1="22.998" x2="28.652" y1="24.02" y2="24.02" gradientUnits="userSpaceOnUse"><stop class="vuad6pb7r"/><stop offset="1" class="zaeth0b6d"/></linearGradient><linearGradient id="iEnmIFc" x1="21.153" x2="16.8" y1="12.513" y2="12.513" gradientUnits="userSpaceOnUse"><stop class="z1p__59we"/><stop offset="1" class="y6b283b4c"/></linearGradient><linearGradient id="iE7AYGd" x1="16.834" x2="15.995" y1="11.502" y2="11.537" gradientUnits="userSpaceOnUse"><stop offset=".36" class="af2d-kbww"/><stop offset="1" class="fkbu2fb2z"/></linearGradient><linearGradient id="i0MgEeS" x1="15.995" x2="15.995" y1="12.642" y2="12.177" gradientUnits="userSpaceOnUse"><stop class="y8u9aob3m"/><stop offset="1" class="w22vs7beb"/></linearGradient><linearGradient id="iygWuib" x1="15.995" x2="15.995" y1="9.808" y2="10.483" gradientUnits="userSpaceOnUse"><stop class="au2s26bkj"/><stop offset="1" class="e0f0u6bhi"/></linearGradient><linearGradient id="inuY99d" x1="14.794" x2="15.112" y1="14.213" y2="13.378" gradientUnits="userSpaceOnUse"><stop class="c2rd33bbv"/><stop offset="1" class="zcdcyccef"/></linearGradient><linearGradient id="iDDU8kb" x1="22.847" x2="11.235" y1="5.165" y2="5.165" gradientUnits="userSpaceOnUse"><stop class="l1vex1b6a"/><stop offset="1" class="kydculhfm"/></linearGradient><linearGradient id="izSgSbd" x1="18.956" x2="18.642" y1="9.965" y2="10.159" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="isftRge" x1="14.557" x2="14.243" y1="9.965" y2="10.159" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iWcm5NK" x1="22.432" x2="21.225" y1="9.992" y2="12.169" gradientUnits="userSpaceOnUse"><stop class="r7o08-b3s"/><stop offset="1" class="g6f16-bty"/></linearGradient><linearGradient id="iazOGEb" x1="10.146" x2="11.604" y1="10.696" y2="10.569" gradientUnits="userSpaceOnUse"><stop class="mlsv8jb5y"/><stop offset="1" class="l7gss9bru"/></linearGradient><linearGradient id="iOkO7Ib" x1="21.474" x2="21.474" y1="9.621" y2="11.525" gradientUnits="userSpaceOnUse"><stop class="q26gyrbrn"/><stop offset="1" class="ihk5xnqly"/></linearGradient><linearGradient id="iHXaVce" x1="7.493" x2="11.284" y1="19.754" y2="30.805" gradientUnits="userSpaceOnUse"><stop class="ux-m5bn7d"/><stop offset="1" class="l294t3zvi"/></linearGradient><linearGradient id="iqtSqJd" x1="16" x2="16" y1="16.02" y2="17.379" gradientUnits="userSpaceOnUse"><stop class="dmu1fh1sq"/><stop offset=".268" class="gzfhb8b1n"/><stop offset=".863" class="szjcm-w7x"/></linearGradient><linearGradient id="iNN1SaK" x1="5" x2="6.055" y1="24.254" y2="24.254" gradientUnits="userSpaceOnUse"><stop class="a61ap5b7j"/><stop offset="1" class="p9llu9bpa"/></linearGradient><linearGradient id="irzSjbb" x1="27" x2="25.524" y1="25.192" y2="25.192" gradientUnits="userSpaceOnUse"><stop offset=".174" class="yr342ibfl"/><stop offset="1" class="d9m_15bme"/></linearGradient><linearGradient id="ixwQhto" x1="17.977" x2="13.911" y1="23.099" y2="23.099" gradientUnits="userSpaceOnUse"><stop offset=".096" class="qufyc6r7b"/><stop offset=".13" class="xqmtwwbyq"/><stop offset=".165" class="k71v6_7um"/><stop offset="1" class="uem0lbchq"/></linearGradient><linearGradient id="i8N6NDd" x1="15.999" x2="15.999" y1="21.641" y2="23.196" gradientUnits="userSpaceOnUse"><stop class="w9bfwpbnq"/><stop offset="1" class="zt_ualb3u"/></linearGradient><linearGradient id="ilcEH9d" x1="15.999" x2="15.999" y1="21.641" y2="24.557" gradientUnits="userSpaceOnUse"><stop class="l17xqebtl"/><stop offset=".037" class="r1d3vkbxd"/><stop offset=".058" class="bowxt9bwr"/><stop offset=".097" class="g48yfbn9k"/></linearGradient><linearGradient id="iKDpaee" x1="14.444" x2="15.02" y1="23.122" y2="23.122" gradientUnits="userSpaceOnUse"><stop offset=".086" class="v1n2dlbml"/><stop offset=".663" class="ohv650iba"/></linearGradient><linearGradient id="i2FoUFP" x1="15.999" x2="15.999" y1="24.842" y2="24.168" gradientUnits="userSpaceOnUse"><stop offset=".507" class="qqk6g6zlh"/><stop offset=".736" class="auud8yb7i"/></linearGradient><filter id="iIH1jyd" width="11.22" height="12.542" x="10.932" y="4.657" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".7"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.913725 0 0 0 0 0.686275 0 0 0 0 0.592157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3_1253"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.780392 0 0 0 0 0.568627 0 0 0 0 0.486275 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3_1253" result="effect2_innerShadow_3_1253"/></filter><filter id="i1gYIwc" width="3.747" height="4.9" x="13.98" y="8.998" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_1253" stdDeviation=".5"/></filter><filter id="igpyjHe" width="2.277" height="3.3" x="14.857" y="9.608" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_1253" stdDeviation=".1"/></filter><filter id="i56crvd" width="3.718" height="1.573" x="14.136" y="13.128" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_1253" stdDeviation=".05"/></filter><filter id="iFNKp8c" width="12.873" height="8.356" x="9.559" y="1.48" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.137255 0 0 0 0 0.0901961 0 0 0 0 0.145098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3_1253"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0784314 0 0 0 0 0.0352941 0 0 0 0 0.0470588 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3_1253" result="effect2_innerShadow_3_1253"/></filter><filter id="i8sTRmb" width="2.339" height="1.19" x="17.584" y="7.144" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0588235 0 0 0 0 0.054902 0 0 0 0 0.0588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3_1253"/></filter><filter id="ivO9pJe" width="2.339" height="1.176" x="12.328" y="7.159" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0588235 0 0 0 0 0.054902 0 0 0 0 0.0588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3_1253"/></filter><filter id="ickIGVi" width="6.734" height="5.992" x="9.915" y="2.569" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.286275 0 0 0 0 0.243137 0 0 0 0 0.227451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3_1253"/><feGaussianBlur result="effect2_foregroundBlur_3_1253" stdDeviation=".125"/></filter><filter id="iem69gd" width="6.361" height="5.736" x="15.836" y="2.993" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_1253" stdDeviation=".125"/></filter><filter id="i4UpiTb" width=".787" height=".696" x="17.443" y="9.472" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_1253" stdDeviation=".05"/></filter><filter id="iaeEFAe" width=".891" height=".913" x="18.283" y="9.547" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_1253" stdDeviation=".1"/></filter><filter id="iHbUpxe" width=".986" height="1.04" x="13.841" y="9.483" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_1253" stdDeviation=".1"/></filter><filter id="iYDhBac" width=".913" height=".705" x="13.086" y="9.463" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_1253" stdDeviation=".05"/></filter><filter id="iQ9RExd" width="1.329" height="2.379" x="9.915" y="9.379" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_1253" stdDeviation=".125"/></filter><filter id="iRKcsfd" width="1.947" height="2.903" x="20.501" y="9.121" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_1253" stdDeviation=".25"/></filter><filter id="ieLtZtf" width="2.405" height="1.16" x="12.247" y="7.233" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_1253" stdDeviation=".125"/></filter><filter id="i6A4nMb" width="2.405" height="1.16" x="17.526" y="7.187" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_1253" stdDeviation=".125"/></filter><filter id="i4G1RqQ" width="22" height="14.1" x="5" y="16.02" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.678431 0 0 0 0 0.670588 0 0 0 0 0.682353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3_1253"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:technologist-light" /></template>
<style>
.a-otvg7dq {
  stop-color: var(--svg-color--806b97, #806B97);
}

.a061yvbds {
  stop-color: var(--svg-color--4e494b, #4E494B);
  stop-opacity: 0;
}

.a61ap5b7j {
  stop-color: var(--svg-color--9f93b2, #9F93B2);
}

.ab9g3hmui {
  stop-color: var(--svg-color--c18472, #C18472);
}

.af2d-kbww {
  stop-color: var(--svg-color--ffdfc7, #FFDFC7);
}

.au2s26bkj {
  stop-color: var(--svg-color--e8bba8, #E8BBA8);
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

.bbyb_mbsk {
  stop-color: var(--svg-color--664842, #664842);
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

.bvf2i9bjf {
  stop-color: var(--svg-color--f6c3b0, #F6C3B0);
  stop-opacity: 0;
}

.bwc1tpbev {
  stop-color: var(--svg-color--ca8b7a, #CA8B7A);
}

.c_6967ufg {
  stop-color: var(--svg-color--ebbb9d, #EBBB9D);
}

.c2rd33bbv {
  stop-color: var(--svg-color--e1aca6, #E1ACA6);
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

.cn0pc3b_h {
  fill: var(--svg-color--202020, #202020);
  d: path("M12.585 7.739a2.77 2.77 0 0 1 1.739-.36a.277.277 0 0 1-.068.551a2.22 2.22 0 0 0-1.386.285a1 1 0 0 0-.092.06l-.003.002a.277.277 0 0 1-.34-.439z");
}

.cur91yz5h {
  cx: 13.542px;
  cy: 9.816px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.d9m_15bme {
  stop-color: var(--svg-color--a191b5, #A191B5);
  stop-opacity: 0;
}

.dmu1fh1sq {
  stop-color: var(--svg-color--beb0b0, #BEB0B0);
}

.dwl_ftd7p {
  stop-color: var(--svg-color--1c0c20, #1C0C20);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e0f0u6bhi {
  stop-color: var(--svg-color--e8bba8, #E8BBA8);
  stop-opacity: 0;
}

.e3urzdusl {
  d: path("M20.85 4.185a2.32 2.32 0 0 1 1.268 1.051a2.37 2.37 0 0 1-.106 2.526a1.56 1.56 0 0 0-.27.875v1.188a1.7 1.7 0 0 0-.668-.268l.078-1.607a1.45 1.45 0 0 0-1.379-1.432h-1.4a2.42 2.42 0 0 1-2.211-1.443a.66.66 0 0 0-.616-.418h-1.272c-1.846 0-3.342 1.512-3.342 3.379l.03 1.537a1.7 1.7 0 0 0-.72.264v-1.2a1.56 1.56 0 0 0-.27-.875a2.39 2.39 0 0 1-.143-2.445a2.34 2.34 0 0 1 1.3-1.127a2.68 2.68 0 0 0 1.384-1.11a2.325 2.325 0 0 1 2.89-.912a1.5 1.5 0 0 0 1.194 0c.28-.118.588-.188.912-.188c.843 0 1.58.456 1.989 1.132c.307.51.79.88 1.352 1.073");
}

.e9ghhhbuh {
  d: path("m15.613 10.113l-.531 1.838c-.109.378.151.757.52.757h.787c.368 0 .629-.384.52-.757l-.531-1.838c-.114-.407-.646-.407-.765 0");
}

.ek_f7q3hx {
  stop-color: var(--svg-color--1a161e, #1A161E);
}

.ez41_pbnb {
  stop-color: var(--svg-color--423c3f, #423C3F);
  stop-opacity: 0;
}

.f65wxmfgp {
  stop-color: var(--svg-color--ffd1b6, #FFD1B6);
  stop-opacity: 0;
}

.fch_lgr5q {
  stop-color: var(--svg-color--1c0c20, #1C0C20);
  stop-opacity: 0;
}

.fkbu2fb2z {
  stop-color: var(--svg-color--ffdfc7, #FFDFC7);
  stop-opacity: 0;
}

.fki8vhbsq {
  stop-color: var(--svg-color--9f6d5c, #9F6D5C);
  stop-opacity: 0;
}

.fm6jtfbaq {
  stop-color: var(--svg-color--f5c7ad, #F5C7AD);
  stop-opacity: 0;
}

.fpnaw0o7f {
  stop-color: var(--svg-color--ca868f, #CA868F);
}

.ft5dv1b6b {
  fill: none;
}

.g-12-6bdv {
  fill: var(--svg-color--f6bfab, #F6BFAB);
  d: path("m15.613 10.113l-.531 1.838c-.109.378.151.757.52.757h.787c.368 0 .629-.384.52-.757l-.531-1.838c-.114-.407-.646-.407-.765 0");
}

.g0smdzbso {
  d: path("M18.114 9.623c.063.085-.07.189-.22.302c-.152.113-.264.192-.327.107c-.064-.085.007-.245.158-.358s.325-.136.389-.051");
}

.g3ux3cbys {
  d: path("M8.98 18.02a10.99 10.99 0 0 0-3.97 8.5l.02 3.5l4-.02z");
}

.g48yfbn9k {
  stop-color: var(--svg-color--5f447b, #5F447B);
  stop-opacity: 0;
}

.g6f16-bty {
  stop-color: var(--svg-color--f0b8a6, #F0B8A6);
}

.gfuj0ibqm {
  stop-color: var(--svg-color--1e191c, #1E191C);
}

.gl470lbeq {
  stop-color: var(--svg-color--f4c0a9, #F4C0A9);
}

.gyf6hdc9c {
  fill: var(--svg-color--202020, #202020);
  d: path("M19.728 7.848a1.85 1.85 0 0 0-.687-.411c-.305-.096-.686-.122-1.213-.057a.277.277 0 0 0 .068.55c.48-.059.776-.028.978.036c.198.062.333.163.49.3a.277.277 0 0 0 .364-.418");
}

.gzfhb8b1n {
  stop-color: var(--svg-color--beb7c7, #BEB7C7);
}

.h739mqb_c {
  stop-color: var(--svg-color--f6b8a8, #F6B8A8);
}

.hnw0p1utu {
  stop-color: var(--svg-color--0b0306, #0B0306);
}

.i1gnb4bzt {
  fill: var(--svg-color--ffd2b6, #FFD2B6);
  d: path("M29.938 30.02q.005-.082.005-.163a3.138 3.138 0 1 0-6.272.162z");
}

.i6xvtdb8e {
  stop-color: var(--svg-color--545051, #545051);
}

.ibt06e6rm {
  stop-color: var(--svg-color--3e3433, #3E3433);
}

.ieumhfb7o {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.605 9.163c-.654 0-1.205.45-1.355 1.058a.274.274 0 0 0 .267.341h2.232a.23.23 0 0 0 .227-.272a1.4 1.4 0 0 0-1.372-1.127");
}

.ihk5xnqly {
  stop-color: var(--svg-color--f6bba0, #F6BBA0);
}

.ina1t94tm {
  stop-color: var(--svg-color--dfa49e, #DFA49E);
}

.iwc2szfpk {
  stop-color: var(--svg-color--ffd1b6, #FFD1B6);
}

.iz6q0pbtm {
  stop-color: var(--svg-color--f7b99c, #F7B99C);
}

.jase_0f7h {
  stop-color: var(--svg-color--88014e, #88014E);
}

.jehi2ihjx {
  stop-color: var(--svg-color--e5dff1, #E5DFF1);
  stop-opacity: 0;
}

.jsqgobbht {
  d: path("M26.03 16.02H5.97a.97.97 0 0 0-.97.97v13.03h22V16.99a.97.97 0 0 0-.97-.97");
}

.k45xjwbmq {
  stop-color: var(--svg-color--3e3433, #3E3433);
  stop-opacity: 0;
}

.k71v6_7um {
  stop-color: var(--svg-color--51366c, #51366C);
}

.kra16rbyh {
  stroke: var(--svg-color--353535, #353535);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M12.622 8.019c.257-.185.898-.51 1.655-.382");
}

.kxaprmbjh {
  stop-color: var(--svg-color--d39991, #D39991);
}

.kydculhfm {
  stop-color: var(--svg-color--272127, #272127);
}

.kylgx8brm {
  d: path("m21.208 8.479l-.029-.631c-.01-.764-.641-1.394-1.405-1.426h-1.4c-.89 0-1.7-.486-2.124-1.26c0 0-.059-.135-.12-.368c-.257-.97.67-1.712 1.655-1.521c.974.189 2.082.517 2.902 1.052c1.745 1.137 1.44 3.188.521 4.154");
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

.l52wxacgn {
  fill: var(--svg-color--000, #000);
  d: path("M17.668 10.327a.51.51 0 0 1 .512-.511a.51.51 0 0 1 .454.746h-.905a.46.46 0 0 1-.06-.235");
}

.l7gss9bru {
  stop-color: var(--svg-color--c9887d, #C9887D);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lkqzgvv7h {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.386 9.163c.654 0 1.205.45 1.355 1.058a.274.274 0 0 1-.267.341h-2.232a.23.23 0 0 1-.227-.272c.126-.64.69-1.127 1.371-1.127");
}

.lombttb9q {
  stop-color: var(--svg-color--f6c3b0, #F6C3B0);
}

.ly6gn-bwx {
  stop-color: var(--svg-color--f7bdb2, #F7BDB2);
  stop-opacity: 0;
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

.mlsv8jb5y {
  stop-color: var(--svg-color--d19787, #D19787);
}

.mqqgujbcq {
  stop-color: var(--svg-color--9f6d5c, #9F6D5C);
}

.mrnsdcbqx {
  stop-color: var(--svg-color--ffddc7, #FFDDC7);
  stop-opacity: 0;
}

.n6e91uy-z {
  d: path("M10.951 8.969a1.62 1.62 0 0 0-1.392 1.593c0 .86.673 1.561 1.52 1.607a78 78 0 0 1-.128-3.2");
}

.nk5451p5c {
  fill: var(--svg-color--d69790, #D69790);
  d: path("m15.594 10.304l-.59 1.838c-.102.378.14.756.484.756h.731c.343 0 .586-.384.485-.756l-.495-1.838c-.106-.408-.504-.408-.615 0");
}

.nonrr22es {
  stop-color: var(--svg-color--e5dff1, #E5DFF1);
}

.nszf4yi9c {
  stop-color: var(--svg-color--4e494b, #4E494B);
}

.nvbd3gb0w {
  d: path("m16.228 5.212l-.066-.137a.66.66 0 0 0-.615-.418h-1.273c-1.846 0-3.342 1.512-3.342 3.379v.275c-.34-.259-.767-.804-.767-1.688c0-1.072.781-1.613 1.28-1.959c.14-.097.259-.18.33-.253l.1-.105c.35-.37.973-1.031 2.06-1.32a5.5 5.5 0 0 1 1.508-.165c.473.012.806.42.806.893v1.485z");
}

.ny0rq0bux {
  stop-color: var(--svg-color--d6a195, #D6A195);
}

.ny9_xhbeh {
  d: path("M23 18.03v11.98h4v-3.5c0-3.41-1.56-6.46-4-8.48");
}

.o0aif1l1c {
  stop-color: var(--svg-color--d3968c, #D3968C);
  stop-opacity: 0;
}

.o1-qqkidl {
  stop-color: var(--svg-color--78698c, #78698C);
}

.o8wr4h7sd {
  stop-color: var(--svg-color--e8af99, #E8AF99);
  stop-opacity: 0;
}

.oaig2cbln {
  stop-color: var(--svg-color--564943, #564943);
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

.p9llu9bpa {
  stop-color: var(--svg-color--9f93b2, #9F93B2);
  stop-opacity: 0;
}

.pfqkh_b6e {
  stop-color: var(--svg-color--f5c7ad, #F5C7AD);
}

.phpmogblj {
  stop-color: var(--svg-color--ffe6cb, #FFE6CB);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.ppwrykbzp {
  d: path("M14.444 21.89a.25.25 0 0 1 .25-.25h2.61a.25.25 0 0 1 .25.25v2.417a.25.25 0 0 1-.25.25h-2.61a.25.25 0 0 1-.25-.25z");
}

.px0sb7ebt {
  stop-color: var(--svg-color--f6b8a8, #F6B8A8);
  stop-opacity: 0;
}

.q0dxfdmim {
  stop-color: var(--svg-color--7a6b8e, #7A6B8E);
  stop-opacity: 0;
}

.q1cl32x8o {
  stop-color: var(--svg-color--b38f78, #B38F78);
  stop-opacity: 0;
}

.q26gyrbrn {
  stop-color: var(--svg-color--f9bb9e, #F9BB9E);
}

.qco-2_b3r {
  stop-color: var(--svg-color--484646, #484646);
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

.qxr6d6bvb {
  d: path("M14.627 10.222c0-.288-.235-.48-.298-.539l-.289.28l.178.36z");
}

.r1d3vkbxd {
  stop-color: var(--svg-color--6d5686, #6D5686);
}

.r7o08-b3s {
  stop-color: var(--svg-color--ffd6bd, #FFD6BD);
}

.r8tuldb4n {
  stop-color: var(--svg-color--ebbb9d, #EBBB9D);
  stop-opacity: 0;
}

.segtfez6g {
  d: path("M15.995 13.724c-.507 0-.984-.12-1.385-.328c-.137-.07-.284.084-.198.209c.335.508.919.846 1.583.846c.665 0 1.249-.338 1.584-.846c.086-.13-.061-.279-.198-.21a3 3 0 0 1-1.386.33");
}

.snpr2ctwr {
  stop-color: var(--svg-color--e6ad97, #E6AD97);
}

.sri2ty5ve {
  stroke: var(--svg-color--353535, #353535);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M19.557 7.972c-.258-.184-.898-.508-1.656-.38");
}

.stq0hsb2e {
  stop-color: var(--svg-color--545051, #545051);
  stop-opacity: 0;
}

.szjcm-w7x {
  stop-color: var(--svg-color--beb7c7, #BEB7C7);
  stop-opacity: 0;
}

.t_w5hobcp {
  stop-color: var(--svg-color--8d78a4, #8D78A4);
  stop-opacity: 0;
}

.t0w03e0rr {
  stop-color: var(--svg-color--e8af99, #E8AF99);
}

.t40345qox {
  stop-color: var(--svg-color--ffddc7, #FFDDC7);
}

.td7qnxbmr {
  d: path("M29.938 30.02q.005-.082.005-.163a3.138 3.138 0 1 0-6.272.162z");
}

.uap_-o0jx {
  d: path("M21.001 11.525q.059-.953.11-1.904a.955.955 0 0 1-.11 1.904");
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

.uuzk4vb7h {
  stop-color: var(--svg-color--ce978e, #CE978E);
  stop-opacity: 0;
}

.uwe7yhbem {
  stop-color: var(--svg-color--e6ad97, #E6AD97);
  stop-opacity: 0;
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

.v9i4yfbgf {
  d: path("M11.17 13.593a3.916 3.916 0 0 0 3.886 3.406h1.887a3.916 3.916 0 0 0 3.885-3.406c.119-1.884.237-3.76.325-5.643a1.45 1.45 0 0 0-1.38-1.432h-1.4a2.42 2.42 0 0 1-2.211-1.443a.66.66 0 0 0-.615-.418h-1.273c-1.846 0-3.342 1.513-3.342 3.379c0 1.86.117 3.691.239 5.557");
}

.vcl0nfbxz {
  stop-color: var(--svg-color--ffe6cb, #FFE6CB);
  stop-opacity: 0;
}

.vgn1hf8dm {
  stop-color: var(--svg-color--d39991, #D39991);
  stop-opacity: 0;
}

.vni43obah {
  stop-color: var(--svg-color--d3968c, #D3968C);
}

.vuad6pb7r {
  stop-color: var(--svg-color--1c1c1c, #1C1C1C);
}

.w0a4mmrgb {
  stop-color: var(--svg-color--200e25, #200E25);
  stop-opacity: 0;
}

.w22vs7beb {
  stop-color: var(--svg-color--d89793, #D89793);
  stop-opacity: 0;
}

.w6exmsbsa {
  fill-opacity: var(--svg-fill-opacity--0-6, 0.6);
  d: path("M14.444 21.89a.25.25 0 0 1 .25-.25h2.61a.25.25 0 0 1 .25.25v2.417a.25.25 0 0 1-.25.25h-2.61a.25.25 0 0 1-.25-.25z");
}

.w9bfwpbnq {
  stop-color: var(--svg-color--60407f, #60407F);
}

.wmov6-bei {
  stop-color: var(--svg-color--f7b99c, #F7B99C);
  stop-opacity: 0;
}

.wpv14ybvl {
  stop-color: var(--svg-color--d5a58f, #D5A58F);
  stop-opacity: 0;
}

.wtsvdfp9l {
  fill: var(--svg-color--1f151b, #1F151B);
  d: path("m21.208 8.479l-.029-.631c-.01-.764-.641-1.394-1.405-1.426h-1.4c-.89 0-1.7-.486-2.124-1.26c0 0-.059-.135-.12-.368c-.257-.97.67-1.712 1.655-1.521c.974.189 2.082.517 2.902 1.052c1.745 1.137 1.44 3.188.521 4.154");
}

.wyv1gnbxf {
  stop-color: var(--svg-color--5e5a5b, #5E5A5B);
}

.x1n2x_pbt {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M14.645 13.33c.39.203.854.32 1.35.32c.501 0 .961-.117 1.351-.32a.23.23 0 0 1 .271.044a.214.214 0 0 1 .024.272m-2.996-.317l2.934.276m-2.934-.276h-.001a.23.23 0 0 0-.271.047a.21.21 0 0 0-.023.27m.295-.317l-.233.276m3.23.041l-.063-.041m.062.041l-.062-.041m.062.041c-.348.528-.955.88-1.646.88c-.69 0-1.297-.351-1.645-.88m3.229-.041a1.9 1.9 0 0 1-1.584.846a1.9 1.9 0 0 1-1.583-.846m-.062.042l.062-.042m-.062.042l.062-.042");
}

.xqmtwwbyq {
  stop-color: var(--svg-color--614c77, #614C77);
}

.xsgkrbcbf {
  stop-color: var(--svg-color--313131, #313131);
}

.xv861oxon {
  fill: var(--svg-color--000, #000);
  d: path("M14.323 10.327a.51.51 0 0 0-.512-.511a.51.51 0 0 0-.454.746h.905a.5.5 0 0 0 .06-.235");
}

.y26jaac_x {
  d: path("M18.18 9.434a.893.893 0 0 1 .86 1.128h-1.724a.896.896 0 0 1 .864-1.128");
}

.y6b283b4c {
  stop-color: var(--svg-color--ffd6ba, #FFD6BA);
  stop-opacity: 0;
}

.y8u9aob3m {
  stop-color: var(--svg-color--d89793, #D89793);
}

.yhrpqc-is {
  d: path("M13.811 9.434a.893.893 0 0 0-.86 1.128h1.724a1 1 0 0 0 .033-.235a.9.9 0 0 0-.897-.893");
}

.ykrihkbqd {
  d: path("M20.857 12.078a1.64 1.64 0 0 0 .904-.309v.931c0 .893-.532 1.689-1.34 2.019q.257-.546.345-1.18z");
}

.yor2p9b5i {
  stop-color: var(--svg-color--ce978e, #CE978E);
}

.yr342ibfl {
  stop-color: var(--svg-color--bab9c0, #BAB9C0);
}

.yzaj_tb_p {
  stop-color: var(--svg-color--ffdcc0, #FFDCC0);
}

.z1p__59we {
  stop-color: var(--svg-color--ffd6ba, #FFD6BA);
}

.z6d-f52gr {
  stop-color: var(--svg-color--5e5a5b, #5E5A5B);
  stop-opacity: 0;
}

.z9sgh-b_k {
  stop-color: var(--svg-color--d5a58f, #D5A58F);
}

.zaeth0b6d {
  stop-color: var(--svg-color--636363, #636363);
}

.zcdcyccef {
  stop-color: var(--svg-color--e1aca6, #E1ACA6);
  stop-opacity: 0;
}

.zn-qjxbde {
  stop-color: var(--svg-color--86004d, #86004D);
}

.zt_ualb3u {
  stop-color: var(--svg-color--543870, #543870);
  stop-opacity: 0;
}

.zwo50zm6y {
  stop-color: var(--svg-color--484646, #484646);
  stop-opacity: 0;
}

</style>
