<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="tn6wjvglz"/><path fill="url(#iOIQJEb)" class="ewb43p53t"/><path fill="url(#i3eHjad)" class="ewb43p53t"/><path fill="url(#iZ96k5J)" class="v0l_8scyz"/><path fill="url(#iOr9pyb)" class="v0l_8scyz"/><path fill="url(#iiHhalc)" class="v0l_8scyz"/><path fill="url(#ijMLlci)" class="v0l_8scyz"/><path fill="url(#iRKXgCd)" class="v0l_8scyz"/><path fill="url(#iXwkCsc)" class="v0l_8scyz"/><g filter="url(#i4N0aFb)"><path class="g6qclmb_w"/></g><path fill="url(#iUDoAAd)" class="yszt_hbvt"/><path fill="url(#ibPMgcd)" class="yszt_hbvt"/><path fill="url(#iKuPJPc)" class="yszt_hbvt"/><path fill="url(#iXml3Ib)" class="mflsd_8gr"/><path fill="url(#ixmuDQb)" class="mflsd_8gr"/><path fill="url(#iub4bZb)" class="xake013ra"/><path fill="url(#iQRmRkc)" class="xake013ra"/><g filter="url(#iN31Bwc)"><path stroke="url(#ixM8XWv)" class="br6t0k2ng"/></g><path fill="url(#ihCeaXT)" class="mhr01db-d"/><path fill="url(#ig3RJpd)" class="mhr01db-d"/><path fill="url(#iq3HtDd)" class="mhr01db-d"/><path fill="url(#iiIPXae)" class="mhr01db-d"/><path fill="url(#iSQtKYc)" class="mhr01db-d"/><path fill="url(#iKyOjPc)" class="agbbjzbaq"/><path fill="url(#iVKMgee)" class="agbbjzbaq"/><path fill="url(#i0FYHfb)" class="agbbjzbaq"/><path fill="url(#iDxdMte)" class="dbh01kbag"/><path fill="url(#iAdqUOc)" class="dbh01kbag"/><g filter="url(#igx2wLd)"><path fill="url(#inSqfib)" class="ecythijsc"/><path fill="url(#inSqfib)" class="qjyxreeei"/><path fill="url(#inSqfib)" class="b7vupxbfn"/></g><g filter="url(#iCq3Jbe)"><path stroke="url(#iYgEH6c)" class="n4rai2b0j"/></g><g filter="url(#igfxB8c)"><circle fill="url(#iOPYSBl)" class="cfq5m8qsc"/></g><g filter="url(#iXl6Xje)"><circle fill="url(#iQJnEPc)" class="nicrgbvxe"/></g><g filter="url(#ioKbnLe)"><circle fill="url(#idQPpUc)" class="r6yt98gpd"/><circle fill="url(#iL2jfKe)" class="r6yt98gpd"/></g><g filter="url(#ifDlwrd)"><circle class="chd7g59pz"/><circle fill="url(#i4fiAgb)" class="ll3wa7t-s"/><circle fill="url(#ixmGPsb)" class="ll3wa7t-s"/></g><g filter="url(#i3x42bn)"><path fill="url(#ioQYOAd)" class="a56fzubij"/><path fill="url(#iKduGdI)" class="a56fzubij"/><path fill="url(#iURwzkd)" class="a56fzubij"/></g><path fill="url(#iA245Mc)" class="umewckbdr"/><path fill="url(#iVoGIHc)" class="umewckbdr"/><path fill="url(#i5OVrqc)" class="umewckbdr"/><path fill="url(#ip94RAc)" class="umewckbdr"/><g filter="url(#iHpaQqe)"><path fill="url(#iqGhaVd)" class="sxuwn08cd"/></g><g filter="url(#iFKioac)"><path class="p2mxuyjvl"/><path fill="url(#iDsUPni)" class="w_nxyfbbu"/><path fill="url(#iLTxqje)" class="w_nxyfbbu"/><path fill="url(#ib2bMGb)" class="w_nxyfbbu"/><path fill="url(#i60sW6c)" class="w_nxyfbbu"/></g><g filter="url(#iNhnRid)"><path class="f3z36iruz"/></g><g filter="url(#ivyOk9A)"><path class="vopp78fgb"/><path fill="url(#ioA2Qdc)" class="b-4bzhbgr"/><path fill="url(#i03n6Ib)" class="b-4bzhbgr"/><path fill="url(#iF5eq3d)" class="b-4bzhbgr"/><path fill="url(#iKHCYqc)" class="b-4bzhbgr"/></g><path fill="url(#iyX10Ts)" class="b-4bzhbgr"/><path stroke="url(#imTVHgd)" class="u7-7qmj7y"/><g filter="url(#iuqSbWc)"><path class="ok9hx2b1q"/><path fill="url(#ioZ2Prd)" class="kz27rcb6q"/></g><g filter="url(#iiPvwoX)"><path class="xe5zx4bjw"/><path fill="url(#iLSEBCb)" class="adtcld-hx"/></g><path class="agn685beh"/><path fill="url(#ikbhmnc)" class="on9q3nb1s"/><path class="w5mnd9f3m"/><g filter="url(#iAPAc9c)"><path class="m8d_deb4d"/><path fill="url(#i7BBPkd)" class="yxa_s2blq"/></g><g filter="url(#ikPwq2c)"><path fill="url(#i9MBP4w)" class="ndyuaipuo"/></g><path class="qa77lzb-g"/><path fill="url(#iSEuuRd)" class="vhkorlswl"/><path class="hlv_4i1to"/><g filter="url(#iR9GGHz)"><path fill="url(#igFJ0YU)" class="kkxwdemyb"/></g><g filter="url(#ilVyDzP)"><ellipse transform="rotate(-27.914 13.996 9.914)" class="v_y-o2sia"/><ellipse fill="url(#i6M4C4b)" transform="rotate(-27.914 13.996 9.914)" class="pgp8ppb5c"/></g><g filter="url(#iyFZzcd)"><path stroke="url(#iM7byrb)" class="smifev0ni"/></g><g filter="url(#iDVNSNb)"><path stroke="url(#i2ZUxyb)" class="d_0-mvbzd"/></g><g filter="url(#iTACdce)"><path stroke="url(#iWDryXb)" class="svvtcsbah"/></g><g filter="url(#i01u99t)"><path fill="url(#iyxsk4c)" class="g058wfe4o"/><path fill="url(#iJYzMzB)" class="g058wfe4o"/></g><path fill="url(#itl0spb)" class="n9d9gzbvc"/><path fill="url(#i9B66le)" class="n9d9gzbvc"/><path fill="url(#if49GLX)" class="n9d9gzbvc"/><defs><radialGradient id="iOIQJEb" cx="0" cy="0" r="1" gradientTransform="matrix(0 10.875 -3.65625 0 23.782 23.145)" gradientUnits="userSpaceOnUse"><stop class="qs5b04nop"/><stop offset="1" class="njrkhhlfe"/></radialGradient><radialGradient id="i3eHjad" cx="0" cy="0" r="1" gradientTransform="matrix(1.3125 0 0 7.0625 9.188 21.488)" gradientUnits="userSpaceOnUse"><stop class="fx84vub6z"/><stop offset="1" class="z6io75bpj"/></radialGradient><radialGradient id="iZ96k5J" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.71875 13.6527 0 16.488 21.38)" gradientUnits="userSpaceOnUse"><stop class="xxaet9bhw"/><stop offset="1" class="zvl8nq86d"/></radialGradient><radialGradient id="iOr9pyb" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.9375 -7.54205 0 16.48 16.926)" gradientUnits="userSpaceOnUse"><stop offset=".932" class="uzp4m_b3p"/><stop offset=".995" class="alc11rbtu"/></radialGradient><radialGradient id="iiHhalc" cx="0" cy="0" r="1" gradientTransform="matrix(-5.88284 4.0234 -5.54695 -8.11053 16.063 15.582)" gradientUnits="userSpaceOnUse"><stop offset=".928" class="cxkgc8uxn"/><stop offset="1" class="pnxjkfbgy"/></radialGradient><radialGradient id="ijMLlci" cx="0" cy="0" r="1" gradientTransform="matrix(6.76566 4.60934 -6.35476 9.32761 15.813 15.348)" gradientUnits="userSpaceOnUse"><stop offset=".933" class="cxkgc8uxn"/><stop offset="1" class="e8o_wr2lc"/></radialGradient><radialGradient id="iRKXgCd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -10.0625 10.6454 0 16.48 23.645)" gradientUnits="userSpaceOnUse"><stop offset=".506" class="nxet2htkz"/><stop offset="1" class="e7yn8_bej"/></radialGradient><radialGradient id="iXwkCsc" cx="0" cy="0" r="1" gradientTransform="rotate(85.281 -.137 16.025)scale(4.21461 7.75523)" gradientUnits="userSpaceOnUse"><stop offset=".316" class="w7sh5cjwf"/><stop offset="1" class="ddl9sxmqm"/></radialGradient><radialGradient id="iUDoAAd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.96875 -1.42188 1.19716 -2.49957 17.784 18.25)" gradientUnits="userSpaceOnUse"><stop class="qt57fac7h"/><stop offset="1" class="apl04vbcc"/></radialGradient><radialGradient id="ibPMgcd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .9375 -2.06 0 16.466 17.016)" gradientUnits="userSpaceOnUse"><stop class="ujwfa7bzq"/><stop offset="1" class="ocm7e7kpi"/></radialGradient><radialGradient id="iKuPJPc" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.5407 -4.26182 0 16.466 14.574)" gradientUnits="userSpaceOnUse"><stop offset=".81" class="xr7te0bkm"/><stop offset="1" class="nkvvdv5bj"/></radialGradient><radialGradient id="ixmuDQb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.33473 .18031 0 25.055 11.698)" gradientUnits="userSpaceOnUse"><stop class="ojstgxewy"/><stop offset="1" class="hom78lxtr"/></radialGradient><radialGradient id="iub4bZb" cx="0" cy="0" r="1" gradientTransform="matrix(-.81259 1.10067 -.98646 -.72826 25.313 12.07)" gradientUnits="userSpaceOnUse"><stop class="all-5ubma"/><stop offset=".661" class="fi917n10w"/></radialGradient><radialGradient id="iQRmRkc" cx="0" cy="0" r="1" gradientTransform="matrix(.79636 -.08984 .10538 .93405 23.976 12.461)" gradientUnits="userSpaceOnUse"><stop offset=".087" class="xlrmucced"/><stop offset="1" class="ezx8m4rog"/></radialGradient><radialGradient id="ig3RJpd" cx="0" cy="0" r="1" gradientTransform="rotate(169.33 12.35 8.575)scale(1.11532 5.56401)" gradientUnits="userSpaceOnUse"><stop offset=".286" class="hye_w5bmk"/><stop offset="1" class="f2dz70yyi"/></radialGradient><radialGradient id="iq3HtDd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .39844 -1.38177 0 24.813 13.137)" gradientUnits="userSpaceOnUse"><stop offset=".161" class="jjb6zku7x"/><stop offset="1" class="dm9f9lb7m"/></radialGradient><radialGradient id="iSQtKYc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.3125 2.89043 0 24.813 16.926)" gradientUnits="userSpaceOnUse"><stop offset=".422" class="irf74zkjs"/><stop offset="1" class="codehtz3g"/></radialGradient><radialGradient id="iKyOjPc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -16.3734 4.36464 0 5.485 30.026)" gradientUnits="userSpaceOnUse"><stop class="yihcw4vuy"/><stop offset=".441" class="kszwqub4g"/><stop offset="1" class="w950_6h3e"/></radialGradient><radialGradient id="iVKMgee" cx="0" cy="0" r="1" gradientTransform="matrix(0 -10.5202 .82413 0 9.25 30.026)" gradientUnits="userSpaceOnUse"><stop offset=".286" class="u3uwpbbrc"/><stop offset="1" class="ebol5nf6u"/></radialGradient><radialGradient id="iDxdMte" cx="0" cy="0" r="1" gradientTransform="matrix(-1.88274 -10.19308 2.86286 -.5288 25.592 30.026)" gradientUnits="userSpaceOnUse"><stop class="g27cpdbvv"/><stop offset="1" class="q3c-4jb0v"/></radialGradient><radialGradient id="iAdqUOc" cx="0" cy="0" r="1" gradientTransform="matrix(.5437 12.03342 -.70276 .03175 23.542 23.187)" gradientUnits="userSpaceOnUse"><stop offset=".177" class="lqqi92blh"/><stop offset="1" class="tcm21mbym"/></radialGradient><radialGradient id="iOPYSBl" cx="0" cy="0" r="1" gradientTransform="matrix(1.76937 0 0 3.09641 10 10.698)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="gsgzrwbpm"/><stop offset="1" class="nhrtbwabt"/></radialGradient><radialGradient id="iL2jfKe" cx="0" cy="0" r="1" gradientTransform="rotate(-36.06 26.85 -28.042)scale(1.0311 1.17686)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="ywu0pr7ii"/><stop offset="1" class="pw1h71b2a"/></radialGradient><radialGradient id="i4fiAgb" cx="0" cy="0" r="1" gradientTransform="matrix(.82806 -1.523 .89142 .48467 21.234 11.526)" gradientUnits="userSpaceOnUse"><stop offset=".755" class="evklql54e"/><stop offset=".916" class="ppo67rb9b"/></radialGradient><radialGradient id="ixmGPsb" cx="0" cy="0" r="1" gradientTransform="matrix(.26143 .25878 -.3336 .33702 21.276 10.699)" gradientUnits="userSpaceOnUse"><stop class="o45oetbxg"/><stop offset="1" class="mfyy4ibhn"/></radialGradient><radialGradient id="iKduGdI" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.31788 1.62201 0 18.837 9.416)" gradientUnits="userSpaceOnUse"><stop class="q3kvcibxc"/><stop offset="1" class="kz100sbcz"/></radialGradient><radialGradient id="iURwzkd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.38547 1.72295 0 14.24 9.551)" gradientUnits="userSpaceOnUse"><stop class="z_g0j449a"/><stop offset="1" class="s5xtkwbhw"/></radialGradient><radialGradient id="i5OVrqc" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.24522 -11.1924 0 16.167 8.91)" gradientUnits="userSpaceOnUse"><stop offset=".617" class="o5f-dj5qd"/><stop offset="1" class="h0kw0pcvl"/></radialGradient><radialGradient id="ip94RAc" cx="0" cy="0" r="1" gradientTransform="rotate(86.463 5.645 11.068)scale(2.53608 7.20239)" gradientUnits="userSpaceOnUse"><stop offset=".598" class="bpls9lmeu"/><stop offset="1" class="qsa70ab7n"/></radialGradient><radialGradient id="iDsUPni" cx="0" cy="0" r="1" gradientTransform="matrix(.80441 -2.98106 1.10547 .2983 20.852 6.558)" gradientUnits="userSpaceOnUse"><stop class="v4bc9u3un"/><stop offset="1" class="o90gcpqxu"/></radialGradient><radialGradient id="iLTxqje" cx="0" cy="0" r="1" gradientTransform="matrix(3.85645 .35489 -.19082 2.07359 19.196 4.784)" gradientUnits="userSpaceOnUse"><stop offset=".122" class="tti32obdt"/><stop offset="1" class="cpvxurbrw"/></radialGradient><radialGradient id="ib2bMGb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.69305 -2.62206 0 16.471 2.026)" gradientUnits="userSpaceOnUse"><stop class="vpyj0s_ar"/><stop offset="1" class="lkn2u3bae"/></radialGradient><radialGradient id="i60sW6c" cx="0" cy="0" r="1" gradientTransform="matrix(3.09935 -2.27128 3.55836 4.85567 9.969 8.9)" gradientUnits="userSpaceOnUse"><stop class="zk3m83b4g"/><stop offset="1" class="gey-evbzc"/></radialGradient><radialGradient id="iKHCYqc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .19853 -.63782 0 16.801 12.318)" gradientUnits="userSpaceOnUse"><stop class="w-44tpbkk"/><stop offset="1" class="d52rddbnb"/></radialGradient><radialGradient id="ioZ2Prd" cx="0" cy="0" r="1" gradientTransform="matrix(.10506 -.60825 1.79947 .3108 18.934 8.597)" gradientUnits="userSpaceOnUse"><stop class="ne4llzbvb"/><stop offset="1" class="vgfjqtbdb"/></radialGradient><radialGradient id="iLSEBCb" cx="0" cy="0" r="1" gradientTransform="rotate(-80.2 11.976 -3.862)scale(.61726 1.82621)" gradientUnits="userSpaceOnUse"><stop class="ne4llzbvb"/><stop offset="1" class="vgfjqtbdb"/></radialGradient><radialGradient id="ikbhmnc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81784 -1.30086 0 18.668 10.01)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="i7BBPkd" cx="0" cy="0" r="1" gradientTransform="matrix(-.23432 -.30195 .41571 -.3226 18.44 10.096)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iSEuuRd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81788 -1.30093 0 14.269 10.01)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="i6M4C4b" cx="0" cy="0" r="1" gradientTransform="matrix(-.00782 -.4992 .60005 -.0094 13.981 10.232)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iyxsk4c" cx="0" cy="0" r="1" gradientTransform="matrix(-.6666 -3.56716 3.98507 -.7447 19.009 5.91)" gradientUnits="userSpaceOnUse"><stop offset=".11" class="l382wkm5r"/><stop offset="1" class="ym5q1xkkz"/></radialGradient><radialGradient id="iJYzMzB" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.97411 -7.12707 0 16.415 2.9)" gradientUnits="userSpaceOnUse"><stop offset=".263" class="vnszicyas"/><stop offset="1" class="j-b5ok87h"/></radialGradient><radialGradient id="i9B66le" cx="0" cy="0" r="1" gradientTransform="matrix(0 .9375 -12.6875 0 22.22 2.426)" gradientUnits="userSpaceOnUse"><stop class="g_-uv52uc"/><stop offset=".867" class="wntqft2su"/></radialGradient><radialGradient id="if49GLX" cx="0" cy="0" r="1" gradientTransform="matrix(7.75 0 0 .875 7.25 3.051)" gradientUnits="userSpaceOnUse"><stop class="it16sbc4j"/><stop offset=".935" class="uo2hv248r"/></radialGradient><linearGradient id="iXml3Ib" x1="24.17" x2="25.356" y1="8.972" y2="8.972" gradientUnits="userSpaceOnUse"><stop class="pk_j5sfiy"/><stop offset="1" class="bqq6maclp"/></linearGradient><linearGradient id="ixM8XWv" x1="25.416" x2="25.416" y1="3.739" y2="11.507" gradientUnits="userSpaceOnUse"><stop class="r2v6fvpbl"/><stop offset="1" class="k3o8k1bzw"/></linearGradient><linearGradient id="ihCeaXT" x1="25.965" x2="23.645" y1="14.837" y2="14.837" gradientUnits="userSpaceOnUse"><stop class="clg68gimn"/><stop offset=".897" class="p-vpa1ykp"/></linearGradient><linearGradient id="iiIPXae" x1="23.764" x2="24.639" y1="14.516" y2="14.696" gradientUnits="userSpaceOnUse"><stop class="ud98q8dic"/><stop offset="1" class="yn026ikmt"/></linearGradient><linearGradient id="i0FYHfb" x1="9.395" x2="8.969" y1="28.094" y2="28.094" gradientUnits="userSpaceOnUse"><stop offset=".444" class="o2uld0acg"/><stop offset="1" class="pts6vr7ld"/></linearGradient><linearGradient id="inSqfib" x1="16.48" x2="16.48" y1="29.895" y2="23.461" gradientUnits="userSpaceOnUse"><stop class="gq6-o1bwg"/><stop offset="1" class="uuiv6bbmv"/></linearGradient><linearGradient id="iYgEH6c" x1="13.432" x2="14.004" y1="4.477" y2="5.814" gradientUnits="userSpaceOnUse"><stop class="riyyv6xjv"/><stop offset="1" class="lfjsh038a"/></linearGradient><linearGradient id="iQJnEPc" x1="11.684" x2="11.038" y1="10.979" y2="10.979" gradientUnits="userSpaceOnUse"><stop class="jrtbzwbyo"/><stop offset="1" class="xh6agdcni"/></linearGradient><linearGradient id="idQPpUc" x1="22.371" x2="21.546" y1="9.598" y2="12.155" gradientUnits="userSpaceOnUse"><stop class="z3o7w4-ew"/><stop offset="1" class="uddso4bed"/></linearGradient><linearGradient id="ioQYOAd" x1="20.541" x2="12.841" y1="11.091" y2="12.238" gradientUnits="userSpaceOnUse"><stop class="ah-u2v6vh"/><stop offset="1" class="hp2sktbkw"/></linearGradient><linearGradient id="iA245Mc" x1="11.031" x2="12.928" y1="13.809" y2="13.742" gradientUnits="userSpaceOnUse"><stop class="wgn2-qn3r"/><stop offset="1" class="cyilnmbju"/></linearGradient><linearGradient id="iVoGIHc" x1="21.376" x2="20.311" y1="12.964" y2="12.863" gradientUnits="userSpaceOnUse"><stop class="y91wuhb_y"/><stop offset="1" class="dfnybco8z"/></linearGradient><linearGradient id="iqGhaVd" x1="15.929" x2="24.14" y1="8.716" y2="5.776" gradientUnits="userSpaceOnUse"><stop class="y3qu8-b1b"/><stop offset="1" class="c0g7wdubv"/></linearGradient><linearGradient id="ioA2Qdc" x1="15.6" x2="16.546" y1="11.756" y2="11.756" gradientUnits="userSpaceOnUse"><stop class="tye5yqhfq"/><stop offset="1" class="rb8odhbtu"/></linearGradient><linearGradient id="i03n6Ib" x1="17.417" x2="16.383" y1="12.081" y2="12.066" gradientUnits="userSpaceOnUse"><stop class="w6mxzsbgv"/><stop offset="1" class="ylom6naui"/></linearGradient><linearGradient id="iF5eq3d" x1="16.667" x2="16.667" y1="12.829" y2="12.252" gradientUnits="userSpaceOnUse"><stop class="hlulkvo5l"/><stop offset="1" class="y_z4ite8v"/></linearGradient><linearGradient id="iyX10Ts" x1="16.598" x2="16.598" y1="12.872" y2="12.703" gradientUnits="userSpaceOnUse"><stop class="ahyqmxbmp"/><stop offset="1" class="g67mx8b1h"/></linearGradient><linearGradient id="imTVHgd" x1="15.426" x2="15.864" y1="14.457" y2="13.764" gradientUnits="userSpaceOnUse"><stop class="lwz87437z"/><stop offset=".663" class="c7jfumw-i"/></linearGradient><linearGradient id="i9MBP4w" x1="19.453" x2="19.136" y1="10.066" y2="10.261" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="igFJ0YU" x1="15.02" x2="14.703" y1="10.066" y2="10.261" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iM7byrb" x1="19.468" x2="19.044" y1="7.907" y2="7.042" gradientUnits="userSpaceOnUse"><stop class="v9-6-sbuc"/><stop offset="1" class="q8x82vmoe"/></linearGradient><linearGradient id="i2ZUxyb" x1="14.12" x2="12.921" y1="7.779" y2="7.276" gradientUnits="userSpaceOnUse"><stop class="v9-6-sbuc"/><stop offset="1" class="q8x82vmoe"/></linearGradient><linearGradient id="iWDryXb" x1="11.771" x2="11.771" y1="5.748" y2="7.922" gradientUnits="userSpaceOnUse"><stop offset=".228" class="tkijdf1cs"/><stop offset="1" class="wg8zzjbli"/></linearGradient><linearGradient id="itl0spb" x1="18.25" x2="16.969" y1="3.989" y2="-.386" gradientUnits="userSpaceOnUse"><stop class="i2fz9bb0r"/><stop offset="1" class="xp7dwurxx"/></linearGradient><filter id="i4N0aFb" width="5.32" height="9.565" x="13.806" y="10.015" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1587" stdDeviation=".2"/></filter><filter id="iN31Bwc" width=".65" height="8.268" x="24.591" y="3.489" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1587" stdDeviation=".125"/></filter><filter id="igx2wLd" width="8.964" height="6.734" x="11.998" y="23.311" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1587" stdDeviation=".075"/></filter><filter id="iCq3Jbe" width="1.172" height="2.394" x="13.132" y="3.816" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1587" stdDeviation=".125"/></filter><filter id="igfxB8c" width="3.567" height="3.367" x="10.001" y="9.015" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.517647 0 0 0 0 0.384314 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1587"/></filter><filter id="iXl6Xje" width="3.006" height="3.006" x="10.181" y="9.195" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1587" stdDeviation=".25"/></filter><filter id="ioKbnLe" width="3.617" height="3.617" x="19.593" y="8.765" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.482353 0 0 0 0 0.278431 0 0 0 0 0.372549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1587"/></filter><filter id="ifDlwrd" width="3.006" height="3.006" x="19.773" y="9.195" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1587" stdDeviation=".25"/></filter><filter id="i3x42bn" width="10.459" height="12.227" x="11.271" y="5.027" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.137255 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1587"/></filter><filter id="iHpaQqe" width="8.281" height="7.092" x="14.636" y="3.662" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1587" stdDeviation="1"/></filter><filter id="iFKioac" width="12.706" height="8.61" x="10.118" y="1.526" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0392157 0 0 0 0 0.00784314 0 0 0 0 0.0196078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1587"/></filter><filter id="iNhnRid" width="3.274" height="4.203" x="14.593" y="9.541" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1587" stdDeviation=".375"/></filter><filter id="ivyOk9A" width="2.392" height="3.203" x="15.275" y="9.876" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1587" stdDeviation=".125"/></filter><filter id="iuqSbWc" width="3.002" height="1.885" x="17.663" y="7.022" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.156863 0 0 0 0 0.0784314 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1587"/></filter><filter id="iiPvwoX" width="3.002" height="1.885" x="12.473" y="7.022" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.156863 0 0 0 0 0.0784314 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1587"/></filter><filter id="iAPAc9c" width=".793" height=".701" x="17.929" y="9.567" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1587" stdDeviation=".05"/></filter><filter id="ikPwq2c" width=".896" height=".919" x="18.776" y="9.645" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1587" stdDeviation=".1"/></filter><filter id="iR9GGHz" width=".992" height="1.047" x="14.298" y="9.581" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1587" stdDeviation=".1"/></filter><filter id="ilVyDzP" width=".92" height=".71" x="13.536" y="9.559" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1587" stdDeviation=".05"/></filter><filter id="iyFZzcd" width="3.065" height="1.635" x="17.546" y="7.176" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1587" stdDeviation=".25"/></filter><filter id="iDVNSNb" width="3.143" height="1.692" x="12.283" y="7.241" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1587" stdDeviation=".25"/></filter><filter id="iTACdce" width="1.01" height="2.282" x="11.266" y="5.472" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1587" stdDeviation=".125"/></filter><filter id="i01u99t" width="12.261" height="2.966" x="10.315" y="3.126" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.05"/><feGaussianBlur stdDeviation=".025"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.360784 0 0 0 0 0.337255 0 0 0 0 0.372549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1587"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-student-medium-dark" /></template>
<style>
.a56fzubij {
  d: path("m11.33 10.08l.049.002s-.054-.86-.108-1.452c0-.269.108-.591.324-.753l.162-.16c.27-.216.379-.539.379-.861v-.86c0-.27.162-.485.433-.538c.648-.162 2-.43 3.948-.43s3.299.268 3.948.43c.216.053.432.268.432.537v.86c0 .323.163.646.379.861c.506.355.475.55.433.968a45 45 0 0 0-.109 1.452h.019l-.268 3.99c-.162 1.785-1.565 3.029-3.237 3.029h-3.237c-1.727 0-3.075-1.244-3.237-3.028z");
}

.adtcld-hx {
  d: path("m12.666 7.956l.001-.001l.002-.002l.004-.004l.013-.01l.036-.027q.045-.033.12-.08c.1-.064.243-.142.423-.213a2.86 2.86 0 0 1 1.505-.16a.538.538 0 0 1-.168 1.063a1.8 1.8 0 0 0-.941.098a1.5 1.5 0 0 0-.311.166a.538.538 0 0 1-.685-.83");
}

.agbbjzbaq {
  d: path("M9.25 30.026V18.239a10.97 10.97 0 0 0-3.765 8.287v3.5z");
}

.agn685beh {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.879 9.256c.658 0 1.214.454 1.365 1.067a.276.276 0 0 1-.27.344h-2.248a.232.232 0 0 1-.23-.274a1.41 1.41 0 0 1 1.383-1.137");
}

.ah-u2v6vh {
  stop-color: var(--svg-color--9b6c5e, #9B6C5E);
}

.ahyqmxbmp {
  stop-color: var(--svg-color--743b4a, #743B4A);
}

.alc11rbtu {
  stop-color: var(--svg-color--342542, #342542);
}

.all-5ubma {
  stop-color: var(--svg-color--686071, #686071);
}

.apl04vbcc {
  stop-color: var(--svg-color--5a3126, #5A3126);
}

.b-4bzhbgr {
  d: path("m16.086 10.41l-.536 1.714a.544.544 0 0 0 .525.705h.793a.545.545 0 0 0 .524-.705l-.535-1.713c-.115-.38-.65-.38-.771 0");
}

.b7vupxbfn {
  d: path("M20.12 23.802c0-.188.155-.34.346-.34s.346.152.346.34v6.093h-.691z");
}

.bpls9lmeu {
  stop-color: var(--svg-color--613533, #613533);
}

.bqq6maclp {
  stop-color: var(--svg-color--61546d, #61546D);
}

.br6t0k2ng {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M24.916 3.74v7.767");
}

.c0g7wdubv {
  stop-color: var(--svg-color--a27b71, #A27B71);
  stop-opacity: 0;
}

.c7jfumw-i {
  stop-color: var(--svg-color--865e63, #865E63);
  stop-opacity: 0;
}

.cfq5m8qsc {
  cx: 11.684px;
  cy: 10.698px;
  r: 1.683px;
}

.chd7g59pz {
  cx: 21.276px;
  cy: 10.698px;
  r: 1.003px;
  fill: var(--svg-color--7a5654, #7A5654);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.clg68gimn {
  stop-color: var(--svg-color--f9b72a, #F9B72A);
}

.codehtz3g {
  stop-color: var(--svg-color--db9820, #DB9820);
  stop-opacity: 0;
}

.cpvxurbrw {
  stop-color: var(--svg-color--46383d, #46383D);
  stop-opacity: 0;
}

.cxkgc8uxn {
  stop-color: var(--svg-color--6a656f, #6A656F);
  stop-opacity: 0;
}

.cyilnmbju {
  stop-color: var(--svg-color--84615a, #84615A);
  stop-opacity: 0;
}

.d_0-mvbzd {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M12.883 8.333c.33-.292 1.05-.599 1.943-.457");
}

.d52rddbnb {
  stop-color: var(--svg-color--976f6a, #976F6A);
  stop-opacity: 0;
}

.dbh01kbag {
  d: path("M23.71 30.026V18.239a10.97 10.97 0 0 1 3.765 8.287v3.5z");
}

.ddl9sxmqm {
  stop-color: var(--svg-color--1c1026, #1C1026);
  stop-opacity: 0;
}

.dfnybco8z {
  stop-color: var(--svg-color--966d5f, #966D5F);
  stop-opacity: 0;
}

.dm9f9lb7m {
  stop-color: var(--svg-color--eba429, #EBA429);
  stop-opacity: 0;
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e7yn8_bej {
  stop-color: var(--svg-color--57525d, #57525D);
}

.e8o_wr2lc {
  stop-color: var(--svg-color--615b67, #615B67);
}

.ebol5nf6u {
  stop-color: var(--svg-color--4f445b, #4F445B);
  stop-opacity: 0;
}

.ecythijsc {
  d: path("M12.148 23.802c0-.188.155-.34.346-.34s.345.152.345.34v6.093h-.691z");
}

.evklql54e {
  stop-color: var(--svg-color--73443e, #73443E);
  stop-opacity: 0;
}

.ewb43p53t {
  d: path("M16.485 15.525c-6.07 0-11 4.92-11 11v3.5h21.99v-3.5c0-6.08-4.92-11-10.99-11");
}

.ezx8m4rog {
  stop-color: var(--svg-color--685352, #685352);
  stop-opacity: 0;
}

.f2dz70yyi {
  stop-color: var(--svg-color--ffd93a, #FFD93A);
  stop-opacity: 0;
}

.f3z36iruz {
  fill: var(--svg-color--71404a, #71404A);
  d: path("m16.194 10.575l-.827 1.714c-.103.352.143.705.492.705h.743c.349 0 .595-.358.492-.705l-.502-1.714c-.108-.38-.286-.38-.398 0");
}

.fi917n10w {
  stop-color: var(--svg-color--402a4c, #402A4C);
}

.ft5dv1b6b {
  fill: none;
}

.fx84vub6z {
  stop-color: var(--svg-color--5d516a, #5D516A);
}

.g_-uv52uc {
  stop-color: var(--svg-color--696070, #696070);
}

.g058wfe4o {
  d: path("m10.315 5.239l1.186-1.953l9.844-.11l1.23 1.974c-4.663 1.61-10.17.823-12.26.089");
}

.g27cpdbvv {
  stop-color: var(--svg-color--736782, #736782);
}

.g67mx8b1h {
  stop-color: var(--svg-color--743b4a, #743B4A);
  stop-opacity: 0;
}

.g6qclmb_w {
  stroke: var(--svg-color--1f0f21, #1F0F21);
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M16.186 18.896c.063.043.17.08.28.084a.56.56 0 0 0 .28-.084c1.017-.696 1.78-1.39 1.78-2.587v-3.633c0-1.14-.92-2.06-2.06-2.06s-2.06.92-2.06 2.06v3.633c0 1.197.763 1.89 1.78 2.587Z");
}

.gey-evbzc {
  stop-color: var(--svg-color--453938, #453938);
  stop-opacity: 0;
}

.gq6-o1bwg {
  stop-color: var(--svg-color--3f3748, #3F3748);
}

.gsgzrwbpm {
  stop-color: var(--svg-color--664249, #664249);
}

.h0kw0pcvl {
  stop-color: var(--svg-color--623241, #623241);
}

.hlulkvo5l {
  stop-color: var(--svg-color--7c4559, #7C4559);
}

.hlv_4i1to {
  fill: var(--svg-color--000, #000);
  d: path("M14.782 10.43a.513.513 0 0 0-.515-.516a.513.513 0 0 0-.458.752h.912a.5.5 0 0 0 .061-.237");
}

.hom78lxtr {
  stop-color: var(--svg-color--70635d, #70635D);
  stop-opacity: 0;
}

.hp2sktbkw {
  stop-color: var(--svg-color--744d4a, #744D4A);
}

.hye_w5bmk {
  stop-color: var(--svg-color--ffd93a, #FFD93A);
}

.i2fz9bb0r {
  stop-color: var(--svg-color--3d294b, #3D294B);
}

.irf74zkjs {
  stop-color: var(--svg-color--a16739, #A16739);
}

.it16sbc4j {
  stop-color: var(--svg-color--75707b, #75707B);
}

.j-b5ok87h {
  stop-color: var(--svg-color--160c20, #160C20);
  stop-opacity: 0;
}

.jjb6zku7x {
  stop-color: var(--svg-color--845d03, #845D03);
}

.jrtbzwbyo {
  stop-color: var(--svg-color--553038, #553038);
}

.k3o8k1bzw {
  stop-color: var(--svg-color--504b55, #504B55);
}

.kkxwdemyb {
  d: path("M15.09 10.325c0-.291-.237-.486-.3-.544l-.292.282l.18.365z");
}

.kszwqub4g {
  stop-color: var(--svg-color--58496a, #58496A);
}

.kz100sbcz {
  stop-color: var(--svg-color--855354, #855354);
  stop-opacity: 0;
}

.kz27rcb6q {
  d: path("m20.222 7.956l-.002-.001l-.002-.002l-.004-.004l-.012-.01a2 2 0 0 0-.156-.108a2.6 2.6 0 0 0-.424-.212a2.86 2.86 0 0 0-1.505-.16a.538.538 0 1 0 .168 1.063c.401-.063.723.011.942.098a1.5 1.5 0 0 1 .31.166a.538.538 0 0 0 .685-.83");
}

.l382wkm5r {
  stop-color: var(--svg-color--595260, #595260);
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.lfjsh038a {
  stop-color: var(--svg-color--db6008, #DB6008);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lkn2u3bae {
  stop-color: var(--svg-color--3e3034, #3E3034);
  stop-opacity: 0;
}

.ll3wa7t-s {
  cx: 21.276px;
  cy: 10.698px;
  r: 1.003px;
}

.lqqi92blh {
  stop-color: var(--svg-color--3f2a51, #3F2A51);
}

.lwz87437z {
  stop-color: var(--svg-color--865e63, #865E63);
}

.m8d_deb4d {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.606 9.72c.064.085-.07.19-.223.304s-.266.195-.33.109c-.065-.086.007-.248.16-.363c.152-.114.328-.137.392-.05");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mflsd_8gr {
  d: path("M25.213 11.698V2.835h-.8v8.863z");
}

.mfyy4ibhn {
  stop-color: var(--svg-color--6c443e, #6C443E);
  stop-opacity: 0;
}

.mhr01db-d {
  d: path("m23.96 13.636l-.517 2.238a.45.45 0 0 0 .445.551h1.863a.45.45 0 0 0 .43-.557l-.542-2.239a.5.5 0 0 0-.485-.381h-.707a.5.5 0 0 0-.488.388");
}

.n4rai2b0j {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M13.432 4.116c.024.255.246 1.214.572 1.794");
}

.n9d9gzbvc {
  d: path("M24.423 3.636H8.453c-.44 0-.8-.36-.8-.8s.36-.8.8-.8h15.96c.44 0 .8.36.8.8c.01.44-.35.8-.79.8");
}

.ndyuaipuo {
  d: path("M19.473 10.312a.85.85 0 0 0-.234-.467l-.263.288l.119.23z");
}

.ne4llzbvb {
  stop-color: var(--svg-color--301a2d, #301A2D);
}

.nhrtbwabt {
  stop-color: var(--svg-color--613641, #613641);
}

.nicrgbvxe {
  cx: 11.684px;
  cy: 10.698px;
  r: 1.003px;
}

.njrkhhlfe {
  stop-color: var(--svg-color--70647f, #70647F);
  stop-opacity: 0;
}

.nkvvdv5bj {
  stop-color: var(--svg-color--582f25, #582F25);
}

.nxet2htkz {
  stop-color: var(--svg-color--57525d, #57525D);
  stop-opacity: 0;
}

.o2uld0acg {
  stop-color: var(--svg-color--433850, #433850);
}

.o45oetbxg {
  stop-color: var(--svg-color--6c443e, #6C443E);
}

.o5f-dj5qd {
  stop-color: var(--svg-color--7d4c5b, #7D4C5B);
  stop-opacity: 0;
}

.o90gcpqxu {
  stop-color: var(--svg-color--3d3437, #3D3437);
  stop-opacity: 0;
}

.ocm7e7kpi {
  stop-color: var(--svg-color--643548, #643548);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ojstgxewy {
  stop-color: var(--svg-color--70635d, #70635D);
}

.ok9hx2b1q {
  fill: var(--svg-color--352827, #352827);
  d: path("m20.222 7.956l-.002-.001l-.002-.002l-.004-.004l-.012-.01a2 2 0 0 0-.156-.108a2.6 2.6 0 0 0-.424-.212a2.86 2.86 0 0 0-1.505-.16a.538.538 0 1 0 .168 1.063c.401-.063.723.011.942.098a1.5 1.5 0 0 1 .31.166a.538.538 0 0 0 .685-.83");
}

.on9q3nb1s {
  d: path("M18.67 9.53a.9.9 0 0 1 .867 1.137H17.8a.903.903 0 0 1 .871-1.137");
}

.p-vpa1ykp {
  stop-color: var(--svg-color--faac28, #FAAC28);
}

.p2mxuyjvl {
  fill: var(--svg-color--27151c, #27151C);
  d: path("m21.33 4.167l.433.215c.757.376 1.19 1.237 1.027 2.151l-.595 3.065c-.053.317-.262.53-.576.538H21.6s.054-.914.108-1.452c.044-.437-.032-.57-.432-.968c-.216-.215-.379-.538-.379-.86v-.86c0-.27-.216-.485-.432-.539c-.65-.16-2.001-.43-3.948-.43s-3.3.27-3.948.43a.524.524 0 0 0-.433.538v.86c0 .323-.108.646-.379.861l-.162.161c-.216.162-.325.484-.325.753c.055.592.109 1.452.109 1.452q-.026 0-.05-.002a.64.64 0 0 1-.6-.536l-.594-3.065c-.108-.86.324-1.72 1.081-2.097l.433-.215c.27-.161.54-.376.811-.592l.974-1.021c.595-.538 1.46-.7 2.217-.323a2.97 2.97 0 0 0 1.677 0c.811-.269 1.73-.054 2.38.538l.81.806c.217.27.487.43.812.592");
}

.pgp8ppb5c {
  cx: 13.996px;
  cy: 9.914px;
  rx: 0.394px;
  ry: 0.199px;
}

.pk_j5sfiy {
  stop-color: var(--svg-color--33203c, #33203C);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pnxjkfbgy {
  stop-color: var(--svg-color--6a656f, #6A656F);
}

.ppo67rb9b {
  stop-color: var(--svg-color--73443e, #73443E);
}

.pts6vr7ld {
  stop-color: var(--svg-color--433850, #433850);
  stop-opacity: 0;
}

.pw1h71b2a {
  stop-color: var(--svg-color--7c524c, #7C524C);
  stop-opacity: 0;
}

.q3c-4jb0v {
  stop-color: var(--svg-color--5f5070, #5F5070);
}

.q3kvcibxc {
  stop-color: var(--svg-color--855354, #855354);
}

.q8x82vmoe {
  stop-color: var(--svg-color--483e3e, #483E3E);
  stop-opacity: 0;
}

.qa77lzb-g {
  fill: var(--svg-color--fff, #fff);
  d: path("M14.059 9.256c-.659 0-1.215.454-1.366 1.067a.276.276 0 0 0 .27.344h2.249a.232.232 0 0 0 .229-.274a1.41 1.41 0 0 0-1.383-1.137");
}

.qjyxreeei {
  d: path("M16.134 23.802c0-.188.155-.34.346-.34s.346.152.346.34v6.093h-.692z");
}

.qs5b04nop {
  stop-color: var(--svg-color--70647f, #70647F);
}

.qsa70ab7n {
  stop-color: var(--svg-color--613533, #613533);
  stop-opacity: 0;
}

.qt57fac7h {
  stop-color: var(--svg-color--714a4b, #714A4B);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r2v6fvpbl {
  stop-color: var(--svg-color--60546c, #60546C);
}

.r6yt98gpd {
  cx: 21.276px;
  cy: 10.698px;
  r: 1.683px;
}

.rb8odhbtu {
  stop-color: var(--svg-color--754e46, #754E46);
  stop-opacity: 0;
}

.riyyv6xjv {
  stop-color: var(--svg-color--faa719, #FAA719);
}

.s5xtkwbhw {
  stop-color: var(--svg-color--6f414d, #6F414D);
  stop-opacity: 0;
}

.smifev0ni {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M18.146 7.81c.433-.076 1.279-.054 1.864.401");
}

.svvtcsbah {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M11.9 5.847v.905c-.007.15-.07.485-.26.627");
}

.sxuwn08cd {
  d: path("m20.461 5.662l-3.103 1.034a1.056 1.056 0 0 0 .474 2.048l3.085-.413z");
}

.tcm21mbym {
  stop-color: var(--svg-color--3f2a51, #3F2A51);
  stop-opacity: 0;
}

.tkijdf1cs {
  stop-color: var(--svg-color--32272d, #32272D);
}

.tn6wjvglz {
  fill: var(--svg-color--56436b, #56436B);
  d: path("M16.485 15.525c-6.07 0-11 4.92-11 11v3.5h21.99v-3.5c0-6.08-4.92-11-10.99-11");
}

.tti32obdt {
  stop-color: var(--svg-color--46383d, #46383D);
}

.tye5yqhfq {
  stop-color: var(--svg-color--754e46, #754E46);
}

.u3uwpbbrc {
  stop-color: var(--svg-color--4f445b, #4F445B);
}

.u7-7qmj7y {
  fill: var(--svg-color--88014f, #88014F);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M18.109 13.761a.19.19 0 0 0-.021-.243a.204.204 0 0 0-.243-.04a2.96 2.96 0 0 1-1.374.326c-.504 0-.976-.119-1.373-.326a.204.204 0 0 0-.244.042a.19.19 0 0 0-.02.241m3.275 0l-.042-.027zm0 0c-.347.525-.95.875-1.638.875s-1.29-.35-1.637-.875m0 0l.041-.027m-.041.027l.041-.027m0 0c.338.511.926.852 1.596.852s1.259-.34 1.596-.853c.087-.13-.061-.28-.2-.21c-.403.21-.88.33-1.396.33c-.511 0-.992-.12-1.396-.33c-.138-.07-.287.085-.2.21Z");
}

.ud98q8dic {
  stop-color: var(--svg-color--c57e10, #C57E10);
}

.uddso4bed {
  stop-color: var(--svg-color--855a5b, #855A5B);
}

.ujwfa7bzq {
  stop-color: var(--svg-color--643548, #643548);
}

.umewckbdr {
  d: path("M11.27 8.63c0-.269.109-.591.325-.753l.162-.16c.27-.216.379-.539.379-.861v-.86c0-.27.162-.485.433-.538c.648-.162 2-.43 3.948-.43s3.299.268 3.948.43c.216.053.432.268.432.537v.86c0 .323.163.646.379.861c.506.355.475.55.433.968a45 45 0 0 0-.109 1.452h.019l-.268 3.99c-.162 1.785-1.565 3.029-3.237 3.029h-3.237c-1.727 0-3.075-1.244-3.237-3.028c-.14-1.832-.202-3.668-.37-5.497");
}

.uo2hv248r {
  stop-color: var(--svg-color--75707b, #75707B);
  stop-opacity: 0;
}

.uuiv6bbmv {
  stop-color: var(--svg-color--3f3748, #3F3748);
  stop-opacity: 0;
}

.uzp4m_b3p {
  stop-color: var(--svg-color--342542, #342542);
  stop-opacity: 0;
}

.v_y-o2sia {
  cx: 13.996px;
  cy: 9.914px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.394px;
  ry: 0.199px;
}

.v0l_8scyz {
  d: path("M23.5 18.125a.24.24 0 0 0-.058-.29c-1.856-1.603-4.346-2.487-6.954-2.487s-5.113.894-6.97 2.487a.24.24 0 0 0-.06.29c1.276 2.6 3.756 4.614 7.03 4.614s5.73-2.015 7.013-4.614");
}

.v4bc9u3un {
  stop-color: var(--svg-color--3d3437, #3D3437);
}

.v9-6-sbuc {
  stop-color: var(--svg-color--483e3e, #483E3E);
}

.vgfjqtbdb {
  stop-color: var(--svg-color--301a2d, #301A2D);
  stop-opacity: 0;
}

.vhkorlswl {
  d: path("M14.267 9.53a.9.9 0 0 0-.867 1.137h1.738a1 1 0 0 0 .033-.237a.906.906 0 0 0-.904-.9");
}

.vnszicyas {
  stop-color: var(--svg-color--160c20, #160C20);
}

.vopp78fgb {
  fill: var(--svg-color--805550, #805550);
  d: path("m16.086 10.41l-.536 1.714a.544.544 0 0 0 .525.705h.793a.545.545 0 0 0 .524-.705l-.535-1.713c-.115-.38-.65-.38-.771 0");
}

.vpyj0s_ar {
  stop-color: var(--svg-color--3e3034, #3E3034);
}

.w_nxyfbbu {
  d: path("m21.33 4.167l.433.215c.757.376 1.19 1.237 1.027 2.151l-.595 3.065c-.053.317-.262.53-.576.538H21.6s.054-.914.108-1.452c.044-.437-.032-.57-.432-.968c-.216-.215-.379-.538-.379-.86v-.86c0-.27-.216-.485-.432-.539c-.65-.16-2.001-.43-3.948-.43s-3.3.27-3.948.43a.524.524 0 0 0-.433.538v.86c0 .323-.108.646-.379.861l-.162.161c-.216.162-.325.484-.325.753c.055.592.109 1.452.109 1.452q-.026 0-.05-.002a.64.64 0 0 1-.6-.536l-.594-3.065c-.108-.86.324-1.72 1.081-2.097l.433-.215c.27-.161.54-.376.811-.592l.974-1.021c.595-.538 1.46-.7 2.217-.323a2.97 2.97 0 0 0 1.677 0c.811-.269 1.73-.054 2.38.538l.81.806c.217.27.487.43.812.592");
}

.w-44tpbkk {
  stop-color: var(--svg-color--976f6a, #976F6A);
}

.w5mnd9f3m {
  fill: var(--svg-color--000, #000);
  d: path("M18.155 10.43c0-.287.229-.516.515-.516a.513.513 0 0 1 .458.752h-.912a.47.47 0 0 1-.061-.237");
}

.w6mxzsbgv {
  stop-color: var(--svg-color--9d766b, #9D766B);
}

.w7sh5cjwf {
  stop-color: var(--svg-color--1c1026, #1C1026);
}

.w950_6h3e {
  stop-color: var(--svg-color--4d4159, #4D4159);
}

.wg8zzjbli {
  stop-color: var(--svg-color--32272d, #32272D);
  stop-opacity: 0;
}

.wgn2-qn3r {
  stop-color: var(--svg-color--84615a, #84615A);
}

.wntqft2su {
  stop-color: var(--svg-color--696070, #696070);
  stop-opacity: 0;
}

.xake013ra {
  d: path("M24.413 11.675a.838.838 0 1 0 .8 0z");
}

.xe5zx4bjw {
  fill: var(--svg-color--352827, #352827);
  d: path("m12.666 7.956l.001-.001l.002-.002l.004-.004l.013-.01l.036-.027q.045-.033.12-.08c.1-.064.243-.142.423-.213a2.86 2.86 0 0 1 1.505-.16a.538.538 0 0 1-.168 1.063a1.8 1.8 0 0 0-.941.098a1.5 1.5 0 0 0-.311.166a.538.538 0 0 1-.685-.83");
}

.xh6agdcni {
  stop-color: var(--svg-color--59323c, #59323C);
}

.xlrmucced {
  stop-color: var(--svg-color--685352, #685352);
}

.xp7dwurxx {
  stop-color: var(--svg-color--433a4d, #433A4D);
}

.xr7te0bkm {
  stop-color: var(--svg-color--582f25, #582F25);
  stop-opacity: 0;
}

.xxaet9bhw {
  stop-color: var(--svg-color--47404d, #47404D);
}

.y_z4ite8v {
  stop-color: var(--svg-color--7c4559, #7C4559);
  stop-opacity: 0;
}

.y3qu8-b1b {
  stop-color: var(--svg-color--a27b71, #A27B71);
}

.y91wuhb_y {
  stop-color: var(--svg-color--966d5f, #966D5F);
}

.yihcw4vuy {
  stop-color: var(--svg-color--766c83, #766C83);
}

.ylom6naui {
  stop-color: var(--svg-color--9d766b, #9D766B);
  stop-opacity: 0;
}

.ym5q1xkkz {
  stop-color: var(--svg-color--372e41, #372E41);
}

.yn026ikmt {
  stop-color: var(--svg-color--df8f14, #DF8F14);
  stop-opacity: 0;
}

.yszt_hbvt {
  d: path("M16.186 18.896c.063.043.17.08.28.084a.56.56 0 0 0 .28-.084c1.017-.696 1.78-1.39 1.78-2.587v-3.633c0-1.14-.92-2.06-2.06-2.06s-2.06.92-2.06 2.06v3.633c0 1.197.763 1.89 1.78 2.587");
}

.ywu0pr7ii {
  stop-color: var(--svg-color--7c524c, #7C524C);
}

.yxa_s2blq {
  d: path("M18.606 9.72c.064.085-.07.19-.223.304s-.266.195-.33.109c-.065-.086.007-.248.16-.363c.152-.114.328-.137.392-.05");
}

.z_g0j449a {
  stop-color: var(--svg-color--6f414d, #6F414D);
}

.z3o7w4-ew {
  stop-color: var(--svg-color--96776b, #96776B);
}

.z6io75bpj {
  stop-color: var(--svg-color--5d516a, #5D516A);
  stop-opacity: 0;
}

.zk3m83b4g {
  stop-color: var(--svg-color--453938, #453938);
}

.zvl8nq86d {
  stop-color: var(--svg-color--3b2d3a, #3B2D3A);
}

</style>
