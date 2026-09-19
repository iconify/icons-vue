<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="d3v84xbvz"/><path fill="url(#iXnIFOz)" class="sv-y_db3h"/><path fill="url(#icjiz3b)" class="sv-y_db3h"/><path fill="url(#irPMG0c)" class="bz09awumf"/><path fill="url(#ioBBm9t)" class="bz09awumf"/><path fill="url(#iC169xc)" class="bz09awumf"/><path fill="url(#iAqeHDb)" class="bz09awumf"/><path fill="url(#iJFmQzc)" class="bz09awumf"/><path fill="url(#iV3ksHe)" class="bz09awumf"/><g filter="url(#i4XIbEe)"><path class="ndz83xbhi"/></g><path fill="url(#ix4jRSd)" class="ea5fknb4s"/><path fill="url(#ivnhdLc)" class="ea5fknb4s"/><path fill="url(#ilo8Chb)" class="ea5fknb4s"/><path fill="url(#iAyOAzb)" class="xqgqqubuj"/><path fill="url(#iK4VhOQ)" class="xqgqqubuj"/><path fill="url(#ivphHGw)" class="qku48ybid"/><path fill="url(#i6FFuze)" class="qku48ybid"/><g filter="url(#iBieOZd)"><path stroke="url(#iec2SjO)" class="nw3vh8b1q"/></g><path fill="url(#i4yeglb)" class="mqbqrobqd"/><path fill="url(#iEFBL9b)" class="mqbqrobqd"/><path fill="url(#iBxbLyY)" class="mqbqrobqd"/><path fill="url(#i9J11Qc)" class="mqbqrobqd"/><path fill="url(#i6ZIdXc)" class="mqbqrobqd"/><path fill="url(#irQ9rGb)" class="yfehbvbva"/><path fill="url(#igTogjb)" class="yfehbvbva"/><path fill="url(#iiC5Nwd)" class="yfehbvbva"/><path fill="url(#ibcIIhc)" class="asng40b4d"/><path fill="url(#ioXg0vb)" class="asng40b4d"/><g filter="url(#iadu2jd)"><path fill="url(#iIEYsdc)" class="e-8wx7igv"/><path fill="url(#iIEYsdc)" class="mk-ebilcn"/><path fill="url(#iIEYsdc)" class="f8tdzdb_b"/></g><g filter="url(#iyuCAxc)"><path class="sombmobgj"/></g><path fill="url(#i2mQJGr)" class="dw58htbrk"/><path fill="url(#inLKi7c)" class="d82fh7q6u"/><g filter="url(#i068zYb)"><path fill="url(#idADcPd)" class="kovujimuy"/><path fill="url(#i4kii6b)" class="kovujimuy"/></g><path fill="url(#intgILb)" class="kovujimuy"/><path fill="url(#iAlWkHe)" class="kovujimuy"/><path fill="url(#iys7Kce)" class="kovujimuy"/><path fill="url(#iu9JuMd)" class="kovujimuy"/><path fill="url(#i1Zqimd)" class="kovujimuy"/><path fill="url(#if7qvUc)" class="kovujimuy"/><path fill="url(#i4nrnof)" class="kovujimuy"/><path fill="url(#ieTXVMb)" class="kovujimuy"/><g filter="url(#iIKIscF)"><path class="eo4505igh"/></g><g filter="url(#ircD6xq)"><path class="eo-q4acak"/><path fill="url(#iVAZjKe)" class="lpl9qp38y"/><path fill="url(#iNKxKhd)" class="lpl9qp38y"/><path fill="url(#izZMLLb)" class="lpl9qp38y"/><path fill="url(#iCwOqnd)" class="lpl9qp38y"/><path fill="url(#iBdCWUc)" class="lpl9qp38y"/></g><path fill="url(#ibRPVWk)" class="lpl9qp38y"/><path fill="url(#iqCPZeb)" class="lpl9qp38y"/><g filter="url(#iQsiCle)"><path stroke="url(#i0TbZad)" class="gihtccpjx"/></g><path fill="url(#iwEQwSc)" class="btnc_wbcl"/><g filter="url(#ig3CRhd)"><path fill="url(#idFHA4c)" class="scqsk2brk"/><path fill="url(#iPWJe6c)" class="scqsk2brk"/><path fill="url(#iWRdWud)" class="scqsk2brk"/><path fill="url(#i5n8C3a)" class="scqsk2brk"/><path fill="url(#iFDXYme)" class="scqsk2brk"/></g><g filter="url(#iNw6Ncd)"><path class="pgzd_hb-w"/></g><g filter="url(#i14vjAH)"><path class="j-0fkvznr"/></g><g filter="url(#iz2g5ae)"><path class="wij0xqc2k"/><path fill="url(#iIOLv7c)" class="e4t7s32lo"/><path fill="url(#iNJlWtc)" class="e4t7s32lo"/></g><g filter="url(#ic2ltvd)"><path class="ugmfiqbct"/><path fill="url(#ieIrZQd)" class="o_3ydb9ka"/><path fill="url(#iwTfDMc)" class="o_3ydb9ka"/></g><path class="xd_ob7sqj"/><path fill="url(#i02UCVb)" class="aord1lbgb"/><path class="j_zg1fblj"/><g filter="url(#iGK4Fcd)"><path class="mgj_fsgda"/><path fill="url(#i9RacSb)" class="p0l2ijp0c"/></g><g filter="url(#i6bI4Ss)"><path fill="url(#iRxvbsJ)" class="jn-sgkb7v"/></g><path class="xw444gber"/><path fill="url(#iyQro7W)" class="qmi3_ccby"/><path class="y07ew4snc"/><g filter="url(#iw0u8we)"><path fill="url(#ieJRZqe)" class="e0_-1pbdv"/></g><g filter="url(#i4pjwce)"><ellipse transform="rotate(-27.914 13.787 9.83)" class="lfcy5gdhh"/><ellipse fill="url(#iRYQ5ic)" transform="rotate(-27.914 13.787 9.83)" class="jmrt8jyyx"/></g><path fill="url(#iZWvzIb)" class="ulavx5bri"/><path fill="url(#ihfawhe)" class="ulavx5bri"/><path fill="url(#iNEPuKe)" class="ulavx5bri"/><path fill="url(#iA6Pn2d)" class="ulavx5bri"/><path fill="url(#iCKSW2b)" class="e3-vgvbqx"/><path fill="url(#iiaZkbd)" class="e3-vgvbqx"/><g filter="url(#iRPX9hd)"><path fill="url(#iHWLvme)" class="ocaflp6cj"/></g><g filter="url(#i7gzzKx)"><path fill="url(#irIJcad)" class="njdlinyjl"/></g><g filter="url(#ip6UyFd)"><path class="tpa04nh9b"/></g><g filter="url(#iSJe64d)"><path class="d49m_4bov"/></g><g filter="url(#ic6ZJDc)"><path class="l23r02biz"/></g><g filter="url(#i6R6mRc)"><path fill="url(#i6SoBrd)" class="b2hwjccrc"/><path fill="url(#igynUhe)" class="b2hwjccrc"/></g><path fill="url(#iXy9cVc)" class="arhh_kb4p"/><path fill="url(#i4D229d)" class="arhh_kb4p"/><path fill="url(#iFvBupb)" class="arhh_kb4p"/><defs><radialGradient id="iXnIFOz" cx="0" cy="0" r="1" gradientTransform="matrix(0 10.875 -3.65625 0 23.592 23.145)" gradientUnits="userSpaceOnUse"><stop class="qs5b04nop"/><stop offset="1" class="njrkhhlfe"/></radialGradient><radialGradient id="icjiz3b" cx="0" cy="0" r="1" gradientTransform="matrix(1.3125 0 0 7.0625 8.998 21.488)" gradientUnits="userSpaceOnUse"><stop class="fx84vub6z"/><stop offset="1" class="z6io75bpj"/></radialGradient><radialGradient id="irPMG0c" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.71875 15.8584 0 16.298 21.38)" gradientUnits="userSpaceOnUse"><stop offset=".201" class="x3t2hmtbe"/><stop offset="1" class="x4e9_o_2d"/></radialGradient><radialGradient id="ioBBm9t" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.9375 -7.54205 0 16.29 16.926)" gradientUnits="userSpaceOnUse"><stop offset=".932" class="uzp4m_b3p"/><stop offset=".995" class="alc11rbtu"/></radialGradient><radialGradient id="iC169xc" cx="0" cy="0" r="1" gradientTransform="matrix(-5.88284 4.0234 -5.54695 -8.11053 15.873 15.582)" gradientUnits="userSpaceOnUse"><stop offset=".928" class="cxkgc8uxn"/><stop offset="1" class="pnxjkfbgy"/></radialGradient><radialGradient id="iAqeHDb" cx="0" cy="0" r="1" gradientTransform="matrix(6.76566 4.60934 -6.35476 9.32761 15.623 15.348)" gradientUnits="userSpaceOnUse"><stop offset=".939" class="xuw5xge2n"/><stop offset=".971" class="pwa-xfb8m"/></radialGradient><radialGradient id="iJFmQzc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -10.0625 10.6454 0 16.29 23.645)" gradientUnits="userSpaceOnUse"><stop offset=".506" class="nxet2htkz"/><stop offset="1" class="e7yn8_bej"/></radialGradient><radialGradient id="iV3ksHe" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.40625 -5.25876 0 16.29 16.094)" gradientUnits="userSpaceOnUse"><stop offset=".422" class="i8onqub3d"/><stop offset="1" class="mfkgssbjj"/></radialGradient><radialGradient id="ix4jRSd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.96875 -1.42188 1.19716 -2.49957 17.594 18.25)" gradientUnits="userSpaceOnUse"><stop class="qt57fac7h"/><stop offset="1" class="apl04vbcc"/></radialGradient><radialGradient id="ivnhdLc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .9375 -2.06 0 16.276 17.016)" gradientUnits="userSpaceOnUse"><stop class="ujwfa7bzq"/><stop offset="1" class="ocm7e7kpi"/></radialGradient><radialGradient id="ilo8Chb" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.5407 -4.26182 0 16.276 14.574)" gradientUnits="userSpaceOnUse"><stop offset=".81" class="xr7te0bkm"/><stop offset="1" class="nkvvdv5bj"/></radialGradient><radialGradient id="iK4VhOQ" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.33473 .18031 0 24.865 11.698)" gradientUnits="userSpaceOnUse"><stop class="ojstgxewy"/><stop offset="1" class="hom78lxtr"/></radialGradient><radialGradient id="ivphHGw" cx="0" cy="0" r="1" gradientTransform="matrix(-.81259 1.10067 -.98646 -.72826 25.123 12.07)" gradientUnits="userSpaceOnUse"><stop class="all-5ubma"/><stop offset=".661" class="fi917n10w"/></radialGradient><radialGradient id="i6FFuze" cx="0" cy="0" r="1" gradientTransform="matrix(.79636 -.08984 .10538 .93405 23.785 12.461)" gradientUnits="userSpaceOnUse"><stop offset=".087" class="xlrmucced"/><stop offset="1" class="ezx8m4rog"/></radialGradient><radialGradient id="iBxbLyY" cx="0" cy="0" r="1" gradientTransform="rotate(169.33 12.256 8.566)scale(1.11532 5.56401)" gradientUnits="userSpaceOnUse"><stop offset=".286" class="hye_w5bmk"/><stop offset="1" class="f2dz70yyi"/></radialGradient><radialGradient id="i9J11Qc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.3125 2.89043 0 24.623 16.926)" gradientUnits="userSpaceOnUse"><stop offset=".422" class="yl8yg_b1a"/><stop offset="1" class="codehtz3g"/></radialGradient><radialGradient id="i6ZIdXc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .39844 -1.38177 0 24.623 13.137)" gradientUnits="userSpaceOnUse"><stop offset=".161" class="jjb6zku7x"/><stop offset="1" class="dm9f9lb7m"/></radialGradient><radialGradient id="irQ9rGb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -16.3734 4.36464 0 5.295 30.026)" gradientUnits="userSpaceOnUse"><stop class="yihcw4vuy"/><stop offset=".441" class="kszwqub4g"/><stop offset="1" class="w950_6h3e"/></radialGradient><radialGradient id="igTogjb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -10.5202 .82413 0 9.06 30.026)" gradientUnits="userSpaceOnUse"><stop offset=".286" class="u3uwpbbrc"/><stop offset="1" class="ebol5nf6u"/></radialGradient><radialGradient id="ibcIIhc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.88274 -10.19308 2.86286 -.5288 25.402 30.026)" gradientUnits="userSpaceOnUse"><stop class="g27cpdbvv"/><stop offset="1" class="q3c-4jb0v"/></radialGradient><radialGradient id="ioXg0vb" cx="0" cy="0" r="1" gradientTransform="matrix(.5437 12.03342 -.70276 .03175 23.351 23.186)" gradientUnits="userSpaceOnUse"><stop offset=".177" class="lqqi92blh"/><stop offset="1" class="tcm21mbym"/></radialGradient><radialGradient id="i2mQJGr" cx="0" cy="0" r="1" gradientTransform="matrix(.76392 2.0604 -2.4476 .90748 21.14 11.823)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="cbylncbjf"/><stop offset="1" class="hj2nkngkt"/></radialGradient><radialGradient id="inLKi7c" cx="0" cy="0" r="1" gradientTransform="rotate(17.447 -35.1 39.108)scale(1.57898 4.87126)" gradientUnits="userSpaceOnUse"><stop class="i4otoyosx"/><stop offset=".746" class="zqff1532o"/></radialGradient><radialGradient id="idADcPd" cx="0" cy="0" r="1" gradientTransform="matrix(-5.33363 0 0 -9.43515 19.154 10.863)" gradientUnits="userSpaceOnUse"><stop class="e4t6-lb6y"/><stop offset="1" class="hhi9hubjb"/><stop offset="1" class="hhi9hubjb"/></radialGradient><radialGradient id="i4kii6b" cx="0" cy="0" r="1" gradientTransform="rotate(121.159 7.752 8.183)scale(3.43715 2.83765)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="fajfg00jo"/><stop offset="1" class="wpa_x2uhd"/></radialGradient><radialGradient id="iAlWkHe" cx="0" cy="0" r="1" gradientTransform="rotate(90 4.34 11.997)scale(9.50205)" gradientUnits="userSpaceOnUse"><stop offset=".674" class="okityn6gm"/><stop offset="1" class="dqo4i2bsu"/></radialGradient><radialGradient id="iys7Kce" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.17159 1.44984 0 18.787 9.523)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="o847wybrn"/><stop offset="1" class="z-0dlhbai"/></radialGradient><radialGradient id="iu9JuMd" cx="0" cy="0" r="1" gradientTransform="matrix(.00401 -1.11642 1.21493 .00436 13.943 9.57)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="pxeuj6buu"/><stop offset="1" class="lg98p_5je"/></radialGradient><radialGradient id="i1Zqimd" cx="0" cy="0" r="1" gradientTransform="rotate(176.388 9.709 6.247)scale(8.68515 22.1862)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="sim-rnb6d"/><stop offset="1" class="vx5g9qbgu"/></radialGradient><radialGradient id="if7qvUc" cx="0" cy="0" r="1" gradientTransform="matrix(3.4543 -2.97549 .8789 1.02034 9.36 8.074)" gradientUnits="userSpaceOnUse"><stop offset=".539" class="sf65_-b_u"/><stop offset="1" class="n9ebefe8q"/></radialGradient><radialGradient id="i4nrnof" cx="0" cy="0" r="1" gradientTransform="matrix(-.2394 2.54797 -1.01853 -.0957 21.947 7.886)" gradientUnits="userSpaceOnUse"><stop offset=".245" class="p54kb3bjj"/><stop offset="1" class="rm9y2hb6m"/></radialGradient><radialGradient id="ieTXVMb" cx="0" cy="0" r="1" gradientTransform="scale(6.44805 2.52208)rotate(90 .31 2.12)" gradientUnits="userSpaceOnUse"><stop offset=".634" class="rz_01_3-z"/><stop offset="1" class="wchuwfnpt"/></radialGradient><radialGradient id="iNKxKhd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .24904 -.7827 0 16.766 12.25)" gradientUnits="userSpaceOnUse"><stop class="eqmylox_y"/><stop offset="1" class="sicchzd0u"/></radialGradient><radialGradient id="iCwOqnd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.55193 .71154 -1.1435 -2.49407 16.884 11.67)" gradientUnits="userSpaceOnUse"><stop offset=".714" class="cjboikbop"/><stop offset="1" class="l6ffphqdg"/></radialGradient><radialGradient id="iqCPZeb" cx="0" cy="0" r="1" gradientTransform="rotate(136.341 6.087 9.038)scale(1.80823 2.60971)" gradientUnits="userSpaceOnUse"><stop offset=".888" class="p1yo_4s7a"/><stop offset="1" class="a1wau6blr"/></radialGradient><radialGradient id="iwEQwSc" cx="0" cy="0" r="1" gradientTransform="matrix(2.22613 -1.09443 4.40316 8.9563 15.789 14.56)" gradientUnits="userSpaceOnUse"><stop offset=".562" class="etju2kb3q"/><stop offset="1" class="iazz9lb4s"/></radialGradient><radialGradient id="iPWJe6c" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.57217 9.03361 0 10.955 7.912)" gradientUnits="userSpaceOnUse"><stop offset=".536" class="ibt06e6rm"/><stop offset="1" class="k45xjwbmq"/></radialGradient><radialGradient id="iWRdWud" cx="0" cy="0" r="1" gradientTransform="matrix(.11635 -2.56338 4.54181 .20615 21.25 9.249)" gradientUnits="userSpaceOnUse"><stop class="c98z413ze"/><stop offset="1" class="ovvtmacpn"/></radialGradient><radialGradient id="i5n8C3a" cx="0" cy="0" r="1" gradientTransform="matrix(-2.40656 -1.5828 1.16186 -1.76654 20.48 2.845)" gradientUnits="userSpaceOnUse"><stop class="jx9hffbwe"/><stop offset="1" class="mzj8iibqz"/></radialGradient><radialGradient id="iFDXYme" cx="0" cy="0" r="1" gradientTransform="rotate(60.727 6.641 13.725)scale(1.40143 3.24506)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="e8ajgab-k"/><stop offset="1" class="gxf7b0v7y"/></radialGradient><radialGradient id="iIOLv7c" cx="0" cy="0" r="1" gradientTransform="matrix(-2.24566 0 0 -.83345 16.549 3.526)" gradientUnits="userSpaceOnUse"><stop class="axstwemrb"/><stop offset="1" class="ez41_pbnb"/></radialGradient><radialGradient id="iNJlWtc" cx="0" cy="0" r="1" gradientTransform="matrix(3.28328 -5.19854 5.75946 3.63755 10.75 7.548)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="hnw0p1utu"/><stop offset=".311" class="dwl_ftd7p"/><stop offset="1" class="fch_lgr5q"/></radialGradient><radialGradient id="ieIrZQd" cx="0" cy="0" r="1" gradientTransform="matrix(2.73293 -2.6038 4.7669 5.0033 18.977 7.417)" gradientUnits="userSpaceOnUse"><stop offset=".857" class="stq0hsb2e"/><stop offset="1" class="i6xvtdb8e"/></radialGradient><radialGradient id="iwTfDMc" cx="0" cy="0" r="1" gradientTransform="matrix(3.31394 .38736 -.16218 1.38748 18.074 5.91)" gradientUnits="userSpaceOnUse"><stop class="unyhdjbdq"/><stop offset="1" class="w0a4mmrgb"/></radialGradient><radialGradient id="i02UCVb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .82774 -1.31661 0 18.516 9.928)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="i9RacSb" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 11.594 .53)scale(.38594 .53135)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iyQro7W" cx="0" cy="0" r="1" gradientTransform="matrix(0 .82778 -1.31667 0 14.064 9.928)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="iRYQ5ic" cx="0" cy="0" r="1" gradientTransform="matrix(-.0079 -.50408 .60593 -.00949 13.772 10.151)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ihfawhe" cx="0" cy="0" r="1" gradientTransform="matrix(.64127 2.28867 -2.18357 .61182 21.001 9.942)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="xron-kbnx"/><stop offset="1" class="bzyp_ibbo"/></radialGradient><radialGradient id="iNEPuKe" cx="0" cy="0" r="1" gradientTransform="matrix(.80372 -1.10298 .92452 .67368 21.37 10.498)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="w_o-5kbak"/><stop offset="1" class="mb4bnzbbk"/></radialGradient><radialGradient id="iA6Pn2d" cx="0" cy="0" r="1" gradientTransform="matrix(.59888 -1.5818 2.1135 .80018 21.485 10.674)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="sxoyafbbn"/><stop offset="1" class="tri7bg95c"/></radialGradient><radialGradient id="iiaZkbd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.69181 0 0 -1.88914 11.275 10.596)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="srn41o2oz"/><stop offset="1" class="dfc36bbxx"/></radialGradient><radialGradient id="iHWLvme" cx="0" cy="0" r="1" gradientTransform="rotate(170.26 5.187 5.78)scale(.9487 .97271)" gradientUnits="userSpaceOnUse"><stop class="m_eaw6bxg"/><stop offset="1" class="nk_trfbso"/></radialGradient><radialGradient id="i6SoBrd" cx="0" cy="0" r="1" gradientTransform="rotate(-100.732 11.912 -4.856)scale(3.6749 8.45124)" gradientUnits="userSpaceOnUse"><stop class="c3tjvjbdr"/><stop offset="1" class="ym5q1xkkz"/></radialGradient><radialGradient id="igynUhe" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.99817 -7.31619 0 16.238 2.896)" gradientUnits="userSpaceOnUse"><stop offset=".263" class="vnszicyas"/><stop offset="1" class="j-b5ok87h"/></radialGradient><radialGradient id="i4D229d" cx="0" cy="0" r="1" gradientTransform="matrix(0 .9375 -12.6875 0 22.03 2.426)" gradientUnits="userSpaceOnUse"><stop class="h02irqbsf"/><stop offset=".867" class="wntqft2su"/></radialGradient><radialGradient id="iFvBupb" cx="0" cy="0" r="1" gradientTransform="matrix(7.75 0 0 .875 7.06 3.051)" gradientUnits="userSpaceOnUse"><stop class="it16sbc4j"/><stop offset=".935" class="uo2hv248r"/></radialGradient><filter id="i4XIbEe" width="5.32" height="9.565" x="13.616" y="10.015" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1585" stdDeviation=".2"/></filter><filter id="iBieOZd" width=".65" height="8.268" x="24.401" y="3.489" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1585" stdDeviation=".125"/></filter><filter id="iadu2jd" width="8.964" height="6.734" x="11.808" y="23.311" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1585" stdDeviation=".075"/></filter><filter id="iyuCAxc" width="5.842" height="3.536" x="16.952" y="3.164" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1585" stdDeviation=".5"/></filter><filter id="i068zYb" width="11.427" height="12.791" x="11.124" y="4.567" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".7"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.494118 0 0 0 0 0.352941 0 0 0 0 0.32549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1585"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.396078 0 0 0 0 0.215686 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1585" result="effect2_innerShadow_4002_1585"/></filter><filter id="iIKIscF" width="3.782" height="4.958" x="14.254" y="9.021" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1585" stdDeviation=".5"/></filter><filter id="ircD6xq" width="2.315" height="3.358" x="15.132" y="9.622" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1585" stdDeviation=".1"/></filter><filter id="iQsiCle" width="3.784" height="1.595" x="14.398" y="13.215" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1585" stdDeviation=".05"/></filter><filter id="ig3CRhd" width="13.133" height="8.164" x="9.723" y="1.688" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.137255 0 0 0 0 0.0901961 0 0 0 0 0.145098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1585"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0784314 0 0 0 0 0.0352941 0 0 0 0 0.0470588 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1585" result="effect2_innerShadow_4002_1585"/></filter><filter id="iNw6Ncd" width="2.384" height="1.21" x="17.911" y="7.109" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.172549 0 0 0 0 0.0862745 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1585"/></filter><filter id="i14vjAH" width="2.384" height="1.196" x="12.549" y="7.123" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.172549 0 0 0 0 0.0862745 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1585"/></filter><filter id="iz2g5ae" width="7.207" height="6.603" x="9.841" y="2.192" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.286275 0 0 0 0 0.243137 0 0 0 0 0.227451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1585"/><feGaussianBlur result="effect2_foregroundBlur_4002_1585" stdDeviation=".25"/></filter><filter id="ic2ltvd" width="6.943" height="6.323" x="15.877" y="2.643" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1585" stdDeviation=".25"/></filter><filter id="iGK4Fcd" width=".799" height=".706" x="17.769" y="9.481" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1585" stdDeviation=".05"/></filter><filter id="i6bI4Ss" width=".901" height=".924" x="18.628" y="9.56" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1585" stdDeviation=".1"/></filter><filter id="iw0u8we" width=".998" height="1.053" x="14.095" y="9.495" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1585" stdDeviation=".1"/></filter><filter id="i4pjwce" width=".928" height=".715" x="13.323" y="9.473" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1585" stdDeviation=".05"/></filter><filter id="iRPX9hd" width="1.346" height="2.417" x="10.091" y="9.39" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1585" stdDeviation=".125"/></filter><filter id="i7gzzKx" width="1.966" height="2.942" x="20.833" y="9.121" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1585" stdDeviation=".25"/></filter><filter id="ip6UyFd" width="2.439" height="1.168" x="12.474" y="7.203" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1585" stdDeviation=".125"/></filter><filter id="iSJe64d" width="2.439" height="1.168" x="17.859" y="7.156" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1585" stdDeviation=".125"/></filter><filter id="ic6ZJDc" width="5.842" height="3.536" x="16.952" y="3.101" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1585" stdDeviation=".5"/></filter><filter id="i6R6mRc" width="12.586" height="3.001" x="9.977" y="3.126" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.05"/><feGaussianBlur stdDeviation=".025"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.360784 0 0 0 0 0.337255 0 0 0 0 0.372549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1585"/></filter><linearGradient id="iAyOAzb" x1="23.98" x2="25.166" y1="8.972" y2="8.972" gradientUnits="userSpaceOnUse"><stop class="pk_j5sfiy"/><stop offset="1" class="bqq6maclp"/></linearGradient><linearGradient id="iec2SjO" x1="25.226" x2="25.226" y1="3.739" y2="11.507" gradientUnits="userSpaceOnUse"><stop class="r2v6fvpbl"/><stop offset="1" class="k3o8k1bzw"/></linearGradient><linearGradient id="i4yeglb" x1="25.774" x2="23.455" y1="14.837" y2="14.837" gradientUnits="userSpaceOnUse"><stop class="clg68gimn"/><stop offset=".897" class="p-vpa1ykp"/></linearGradient><linearGradient id="iEFBL9b" x1="23.406" x2="24.469" y1="14.633" y2="14.758" gradientUnits="userSpaceOnUse"><stop class="nnh5vk6mb"/><stop offset="1" class="boxqtwbke"/></linearGradient><linearGradient id="iiC5Nwd" x1="9.205" x2="8.779" y1="28.094" y2="28.094" gradientUnits="userSpaceOnUse"><stop offset=".444" class="o2uld0acg"/><stop offset="1" class="pts6vr7ld"/></linearGradient><linearGradient id="iIEYsdc" x1="16.29" x2="16.29" y1="29.895" y2="23.461" gradientUnits="userSpaceOnUse"><stop class="gq6-o1bwg"/><stop offset="1" class="uuiv6bbmv"/></linearGradient><linearGradient id="intgILb" x1="21.552" x2="18.971" y1="12.582" y2="12.582" gradientUnits="userSpaceOnUse"><stop class="agilw2byy"/><stop offset="1" class="h3kh2yb2k"/></linearGradient><linearGradient id="iVAZjKe" x1="17.145" x2="16.29" y1="11.551" y2="11.587" gradientUnits="userSpaceOnUse"><stop offset=".36" class="eqmylox_y"/><stop offset="1" class="sicchzd0u"/></linearGradient><linearGradient id="izZMLLb" x1="16.29" x2="16.29" y1="12.713" y2="12.239" gradientUnits="userSpaceOnUse"><stop class="qsncw6btn"/><stop offset="1" class="v7xhdx32s"/></linearGradient><linearGradient id="iBdCWUc" x1="16.29" x2="16.29" y1="9.953" y2="10.511" gradientUnits="userSpaceOnUse"><stop class="fok393bvn"/><stop offset="1" class="y4umwkb_f"/></linearGradient><linearGradient id="ibRPVWk" x1="16.714" x2="16.714" y1="12.854" y2="12.657" gradientUnits="userSpaceOnUse"><stop class="a1wau6blr"/><stop offset="1" class="p1yo_4s7a"/></linearGradient><linearGradient id="i0TbZad" x1="15.064" x2="15.389" y1="14.316" y2="13.465" gradientUnits="userSpaceOnUse"><stop class="t_m5csgaz"/><stop offset="1" class="ln8xouyxx"/></linearGradient><linearGradient id="idFHA4c" x1="23.281" x2="11.434" y1="5.085" y2="5.085" gradientUnits="userSpaceOnUse"><stop class="s5pji6bqr"/><stop offset="1" class="c7qpv738k"/></linearGradient><linearGradient id="iRxvbsJ" x1="19.31" x2="18.99" y1="9.983" y2="10.18" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ieJRZqe" x1="14.823" x2="14.503" y1="9.983" y2="10.18" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iZWvzIb" x1="22.857" x2="21.625" y1="10.01" y2="12.23" gradientUnits="userSpaceOnUse"><stop class="pkjt6qfem"/><stop offset="1" class="qw3t0fbxr"/></linearGradient><linearGradient id="iCKSW2b" x1="10.322" x2="11.81" y1="10.729" y2="10.599" gradientUnits="userSpaceOnUse"><stop class="lsjj5yb-k"/><stop offset="1" class="ac3zxpbrp"/></linearGradient><linearGradient id="irIJcad" x1="21.816" x2="21.816" y1="9.621" y2="11.563" gradientUnits="userSpaceOnUse"><stop class="x9ttejxmc"/><stop offset="1" class="nal-rljch"/></linearGradient><linearGradient id="iXy9cVc" x1="18.061" x2="16.779" y1="3.989" y2="-.386" gradientUnits="userSpaceOnUse"><stop class="i2fz9bb0r"/><stop offset="1" class="xp7dwurxx"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:student-medium-dark" /></template>
<style>
.a1wau6blr {
  stop-color: var(--svg-color--6d3945, #6D3945);
}

.ac3zxpbrp {
  stop-color: var(--svg-color--623549, #623549);
}

.agilw2byy {
  stop-color: var(--svg-color--936b5d, #936B5D);
}

.alc11rbtu {
  stop-color: var(--svg-color--342542, #342542);
}

.all-5ubma {
  stop-color: var(--svg-color--686071, #686071);
}

.aord1lbgb {
  d: path("M18.518 9.441a.91.91 0 0 1 .878 1.151h-1.76a.914.914 0 0 1 .882-1.15");
}

.apl04vbcc {
  stop-color: var(--svg-color--5a3126, #5A3126);
}

.arhh_kb4p {
  d: path("M24.233 3.636H8.263c-.44 0-.8-.36-.8-.8s.36-.8.8-.8h15.96c.44 0 .8.36.8.8c.01.44-.35.8-.79.8");
}

.asng40b4d {
  d: path("M23.52 30.026V18.239a10.97 10.97 0 0 1 3.765 8.287v3.5z");
}

.axstwemrb {
  stop-color: var(--svg-color--423c3f, #423C3F);
}

.b2hwjccrc {
  d: path("m9.977 5.258l1.21-1.972l10.258-.11l1.117 2.02c-4.664 1.61-10.496.797-12.585.062");
}

.bbyb_mbsk {
  stop-color: var(--svg-color--664842, #664842);
}

.boxqtwbke {
  stop-color: var(--svg-color--fbb229, #FBB229);
  stop-opacity: 0;
}

.bqq6maclp {
  stop-color: var(--svg-color--61546d, #61546D);
}

.btnc_wbcl {
  d: path("M16.29 13.818a3.1 3.1 0 0 1-1.413-.335c-.14-.071-.29.086-.203.213c.342.518.938.863 1.616.863s1.274-.345 1.615-.863c.088-.132-.062-.284-.202-.213a3.05 3.05 0 0 1-1.413.335");
}

.bz09awumf {
  d: path("M23.311 18.125a.24.24 0 0 0-.059-.29c-1.856-1.603-4.346-2.487-6.954-2.487s-5.113.894-6.97 2.487a.24.24 0 0 0-.06.29c1.276 2.6 3.756 4.614 7.03 4.614s5.73-2.015 7.013-4.614");
}

.bzyp_ibbo {
  stop-color: var(--svg-color--71404f, #71404F);
}

.c3tjvjbdr {
  stop-color: var(--svg-color--534d5a, #534D5A);
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

.cxkgc8uxn {
  stop-color: var(--svg-color--6a656f, #6A656F);
  stop-opacity: 0;
}

.d3v84xbvz {
  fill: var(--svg-color--56436b, #56436B);
  d: path("M16.295 15.525c-6.07 0-11 4.92-11 11v3.5h21.99v-3.5c0-6.08-4.92-11-10.99-11");
}

.d49m_4bov {
  stroke: var(--svg-color--433739, #433739);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M19.923 7.95c-.262-.188-.916-.52-1.689-.39");
}

.d82fh7q6u {
  d: path("M11.33 12.138a1.67 1.67 0 0 1-.923-.315v.95c0 .91.543 1.723 1.368 2.06a4.2 4.2 0 0 1-.352-1.204z");
}

.dfc36bbxx {
  stop-color: var(--svg-color--836158, #836158);
}

.dm9f9lb7m {
  stop-color: var(--svg-color--eba429, #EBA429);
  stop-opacity: 0;
}

.dqo4i2bsu {
  stop-color: var(--svg-color--5f3241, #5F3241);
}

.dw58htbrk {
  d: path("M21.25 12.138c.342-.011.662-.127.923-.315v.95c0 .91-.543 1.723-1.368 2.06c.173-.37.293-.774.352-1.204z");
}

.dwl_ftd7p {
  stop-color: var(--svg-color--1c0c20, #1C0C20);
}

.e-8wx7igv {
  d: path("M11.958 23.802c0-.188.155-.34.346-.34s.345.152.345.34v6.093h-.691z");
}

.e0_-1pbdv {
  d: path("M14.894 10.245c0-.295-.24-.49-.304-.55l-.294.284l.18.369z");
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e3-vgvbqx {
  d: path("M11.144 8.961a1.656 1.656 0 0 0-1.42 1.63c0 .877.686 1.593 1.551 1.64a80 80 0 0 1-.131-3.27");
}

.e4t6-lb6y {
  stop-color: var(--svg-color--9a6e61, #9A6E61);
}

.e4t7s32lo {
  d: path("M16.527 5.134a3 3 0 0 1-.067-.14a.68.68 0 0 0-.628-.427h-1.299c-1.883 0-3.409 1.543-3.409 3.448v.28c-.347-.264-.783-.82-.783-1.722c0-1.093.798-1.646 1.306-1.998c.144-.1.265-.184.338-.259l.101-.107c.357-.378.992-1.052 2.102-1.346a5.6 5.6 0 0 1 1.554-.168c.473.012.807.42.807.893V5.12z");
}

.e7yn8_bej {
  stop-color: var(--svg-color--57525d, #57525D);
}

.e8ajgab-k {
  stop-color: var(--svg-color--392f31, #392F31);
}

.ea5fknb4s {
  d: path("M15.996 18.896c.063.043.17.08.28.084a.56.56 0 0 0 .28-.084c1.017-.696 1.78-1.39 1.78-2.587v-3.633c0-1.14-.92-2.06-2.06-2.06s-2.06.92-2.06 2.06v3.633c0 1.197.764 1.89 1.78 2.587");
}

.ebol5nf6u {
  stop-color: var(--svg-color--4f445b, #4F445B);
  stop-opacity: 0;
}

.eo-q4acak {
  fill: var(--svg-color--7c5150, #7C5150);
  d: path("m15.9 10.133l-.542 1.876c-.111.386.155.771.53.771h.803c.376 0 .642-.391.531-.771l-.542-1.876c-.116-.415-.658-.415-.78 0");
}

.eo4505igh {
  fill: var(--svg-color--6f3f46, #6F3F46);
  d: path("m15.88 10.333l-.602 1.876c-.103.385.144.771.494.771h.746c.35 0 .598-.392.495-.771l-.505-1.876c-.108-.415-.514-.415-.627 0");
}

.eqmylox_y {
  stop-color: var(--svg-color--a17c72, #A17C72);
}

.etju2kb3q {
  stop-color: var(--svg-color--87004e, #87004E);
}

.ez41_pbnb {
  stop-color: var(--svg-color--423c3f, #423C3F);
  stop-opacity: 0;
}

.ezx8m4rog {
  stop-color: var(--svg-color--685352, #685352);
  stop-opacity: 0;
}

.f2dz70yyi {
  stop-color: var(--svg-color--ffd93a, #FFD93A);
  stop-opacity: 0;
}

.f8tdzdb_b {
  d: path("M19.93 23.802c0-.188.155-.34.346-.34s.346.152.346.34v6.093h-.691z");
}

.fajfg00jo {
  stop-color: var(--svg-color--855e5a, #855E5A);
}

.fch_lgr5q {
  stop-color: var(--svg-color--1c0c20, #1C0C20);
  stop-opacity: 0;
}

.fi917n10w {
  stop-color: var(--svg-color--402a4c, #402A4C);
}

.fok393bvn {
  stop-color: var(--svg-color--865c56, #865C56);
}

.ft5dv1b6b {
  fill: none;
}

.fx84vub6z {
  stop-color: var(--svg-color--5d516a, #5D516A);
}

.g27cpdbvv {
  stop-color: var(--svg-color--736782, #736782);
}

.gihtccpjx {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M14.911 13.416a.23.23 0 0 0-.275.048a.215.215 0 0 0-.024.274c.356.538.974.896 1.678.896s1.323-.358 1.678-.896a.22.22 0 0 0-.024-.277a.23.23 0 0 0-.275-.045a3 3 0 0 1-1.38.327c-.505 0-.98-.12-1.378-.327Z");
}

.gq6-o1bwg {
  stop-color: var(--svg-color--3f3748, #3F3748);
}

.gxf7b0v7y {
  stop-color: var(--svg-color--392f31, #392F31);
  stop-opacity: 0;
}

.h02irqbsf {
  stop-color: var(--svg-color--6a6273, #6A6273);
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

.hom78lxtr {
  stop-color: var(--svg-color--70635d, #70635D);
  stop-opacity: 0;
}

.hye_w5bmk {
  stop-color: var(--svg-color--ffd93a, #FFD93A);
}

.i2fz9bb0r {
  stop-color: var(--svg-color--3d294b, #3D294B);
}

.i4otoyosx {
  stop-color: var(--svg-color--3e3330, #3E3330);
}

.i6xvtdb8e {
  stop-color: var(--svg-color--545051, #545051);
}

.i8onqub3d {
  stop-color: var(--svg-color--170919, #170919);
}

.iazz9lb4s {
  stop-color: var(--svg-color--87004d, #87004D);
}

.ibt06e6rm {
  stop-color: var(--svg-color--3e3433, #3E3433);
}

.it16sbc4j {
  stop-color: var(--svg-color--75707b, #75707B);
}

.j_zg1fblj {
  fill: var(--svg-color--000, #000);
  d: path("M17.997 10.352a.52.52 0 0 1 .521-.522a.52.52 0 0 1 .464.762h-.923a.5.5 0 0 1-.062-.24");
}

.j-0fkvznr {
  fill: var(--svg-color--2e201f, #2E201F);
  d: path("M12.81 7.711a2.83 2.83 0 0 1 1.774-.367a.283.283 0 1 1-.069.562a2.26 2.26 0 0 0-1.414.29a1 1 0 0 0-.094.062l-.003.002a.283.283 0 0 1-.346-.448z");
}

.j-b5ok87h {
  stop-color: var(--svg-color--160c20, #160C20);
  stop-opacity: 0;
}

.jjb6zku7x {
  stop-color: var(--svg-color--845d03, #845D03);
}

.jmrt8jyyx {
  cx: 13.787px;
  cy: 9.83px;
  rx: 0.398px;
  ry: 0.201px;
}

.jn-sgkb7v {
  d: path("M19.33 10.232a.86.86 0 0 0-.237-.472l-.265.29l.12.234z");
}

.jx9hffbwe {
  stop-color: var(--svg-color--402c32, #402C32);
}

.k3o8k1bzw {
  stop-color: var(--svg-color--504b55, #504B55);
}

.k45xjwbmq {
  stop-color: var(--svg-color--3e3433, #3E3433);
  stop-opacity: 0;
}

.kovujimuy {
  d: path("M11.367 13.684a3.995 3.995 0 0 0 3.965 3.474h1.924a3.995 3.995 0 0 0 3.965-3.475c.12-1.921.241-3.835.33-5.756a1.48 1.48 0 0 0-1.406-1.461h-1.429a2.47 2.47 0 0 1-2.256-1.472a.68.68 0 0 0-.628-.427h-1.299c-1.883 0-3.409 1.543-3.409 3.447c0 1.899.119 3.766.243 5.67");
}

.kszwqub4g {
  stop-color: var(--svg-color--58496a, #58496A);
}

.l23r02biz {
  fill: var(--svg-color--49373d, #49373D);
  d: path("M20.568 5.088h-2.123a.492.492 0 1 1 .078-.98c.551.087 1.283.21 1.773.331c1.107.275 1.413.814 1.498 1.198a1.54 1.54 0 0 0-1.226-.549");
}

.l6ffphqdg {
  stop-color: var(--svg-color--744a4a, #744A4A);
}

.lfcy5gdhh {
  cx: 13.787px;
  cy: 9.83px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.398px;
  ry: 0.201px;
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

.lpl9qp38y {
  d: path("m15.9 10.133l-.542 1.876c-.111.386.155.771.53.771h.803c.376 0 .642-.391.531-.771l-.542-1.876c-.116-.415-.658-.415-.78 0");
}

.lqqi92blh {
  stop-color: var(--svg-color--3f2a51, #3F2A51);
}

.lsjj5yb-k {
  stop-color: var(--svg-color--6a4544, #6A4544);
}

.m_eaw6bxg {
  stop-color: var(--svg-color--57353c, #57353C);
}

.mb4bnzbbk {
  stop-color: var(--svg-color--7c4c46, #7C4C46);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mfkgssbjj {
  stop-color: var(--svg-color--361e27, #361E27);
  stop-opacity: 0;
}

.mgj_fsgda {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.451 9.634c.065.086-.07.192-.224.308c-.155.115-.269.196-.334.11c-.065-.088.008-.251.162-.367s.332-.138.396-.051");
}

.mk-ebilcn {
  d: path("M15.944 23.802c0-.188.155-.34.346-.34s.346.152.346.34v6.093h-.692z");
}

.mqbqrobqd {
  d: path("m23.77 13.636l-.517 2.238a.45.45 0 0 0 .445.551h1.863a.45.45 0 0 0 .43-.557l-.542-2.239a.5.5 0 0 0-.485-.381h-.707a.5.5 0 0 0-.488.388");
}

.mzj8iibqz {
  stop-color: var(--svg-color--402c32, #402C32);
  stop-opacity: 0;
}

.n9ebefe8q {
  stop-color: var(--svg-color--4f2c2a, #4F2C2A);
  stop-opacity: 0;
}

.nal-rljch {
  stop-color: var(--svg-color--7d5449, #7D5449);
}

.ndz83xbhi {
  stroke: var(--svg-color--1f0f21, #1F0F21);
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M15.996 18.896c.063.043.17.08.28.084a.56.56 0 0 0 .28-.084c1.017-.696 1.78-1.39 1.78-2.587v-3.633c0-1.14-.92-2.06-2.06-2.06s-2.06.92-2.06 2.06v3.633c0 1.197.764 1.89 1.78 2.587Z");
}

.njdlinyjl {
  d: path("M21.333 11.563q.06-.972.113-1.942a.975.975 0 0 1-.113 1.941");
}

.njrkhhlfe {
  stop-color: var(--svg-color--70647f, #70647F);
  stop-opacity: 0;
}

.nk_trfbso {
  stop-color: var(--svg-color--5b3336, #5B3336);
}

.nkvvdv5bj {
  stop-color: var(--svg-color--582f25, #582F25);
}

.nnh5vk6mb {
  stop-color: var(--svg-color--bd9130, #BD9130);
}

.nw3vh8b1q {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M24.726 3.74v7.767");
}

.nxet2htkz {
  stop-color: var(--svg-color--57525d, #57525D);
  stop-opacity: 0;
}

.o_3ydb9ka {
  d: path("m21.608 8.466l-.03-.644c-.01-.779-.654-1.422-1.433-1.454h-1.429a2.47 2.47 0 0 1-2.167-1.285s-.065-.152-.131-.41c-.248-.972.678-1.707 1.658-1.492c.968.212 2.07.57 2.907 1.117c1.78 1.161 1.562 3.183.625 4.168");
}

.o2uld0acg {
  stop-color: var(--svg-color--433850, #433850);
}

.o847wybrn {
  stop-color: var(--svg-color--875455, #875455);
}

.ocaflp6cj {
  d: path("M11.102 9.64a.975.975 0 0 0 .085 1.917a79 79 0 0 1-.085-1.917");
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

.okityn6gm {
  stop-color: var(--svg-color--713f52, #713F52);
  stop-opacity: 0;
}

.ovvtmacpn {
  stop-color: var(--svg-color--4f4d4d, #4F4D4D);
  stop-opacity: 0;
}

.p-vpa1ykp {
  stop-color: var(--svg-color--faac28, #FAAC28);
}

.p0l2ijp0c {
  d: path("M18.451 9.634c.065.086-.07.192-.224.308c-.155.115-.269.196-.334.11c-.065-.088.008-.251.162-.367s.332-.138.396-.051");
}

.p1yo_4s7a {
  stop-color: var(--svg-color--6d3945, #6D3945);
  stop-opacity: 0;
}

.p54kb3bjj {
  stop-color: var(--svg-color--98786d, #98786D);
}

.pgzd_hb-w {
  fill: var(--svg-color--2e201f, #2E201F);
  d: path("M20.098 7.823a1.9 1.9 0 0 0-.701-.42c-.31-.098-.7-.124-1.237-.058a.283.283 0 0 0 .069.562c.49-.06.791-.03.998.036c.202.063.34.167.5.306a.283.283 0 0 0 .371-.426");
}

.pk_j5sfiy {
  stop-color: var(--svg-color--33203c, #33203C);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pkjt6qfem {
  stop-color: var(--svg-color--9c7b71, #9C7B71);
}

.pnxjkfbgy {
  stop-color: var(--svg-color--6a656f, #6A656F);
}

.pts6vr7ld {
  stop-color: var(--svg-color--433850, #433850);
  stop-opacity: 0;
}

.pwa-xfb8m {
  stop-color: var(--svg-color--655f6b, #655F6B);
}

.pxeuj6buu {
  stop-color: var(--svg-color--70424e, #70424E);
}

.q3c-4jb0v {
  stop-color: var(--svg-color--5f5070, #5F5070);
}

.qku48ybid {
  d: path("M24.223 11.675a.838.838 0 1 0 .8 0z");
}

.qmi3_ccby {
  d: path("M14.062 9.44a.91.91 0 0 0-.878 1.152h1.76a1 1 0 0 0 .032-.24a.917.917 0 0 0-.914-.911");
}

.qs5b04nop {
  stop-color: var(--svg-color--70647f, #70647F);
}

.qsncw6btn {
  stop-color: var(--svg-color--7d465b, #7D465B);
}

.qt57fac7h {
  stop-color: var(--svg-color--714a4b, #714A4B);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qw3t0fbxr {
  stop-color: var(--svg-color--815758, #815758);
}

.r2v6fvpbl {
  stop-color: var(--svg-color--60546c, #60546C);
}

.rm9y2hb6m {
  stop-color: var(--svg-color--98786d, #98786D);
  stop-opacity: 0;
}

.rz_01_3-z {
  stop-color: var(--svg-color--60343a, #60343A);
}

.s5pji6bqr {
  stop-color: var(--svg-color--443237, #443237);
}

.scqsk2brk {
  d: path("M21.243 4.085c.525.18.996.548 1.293 1.073a2.42 2.42 0 0 1-.108 2.577a1.6 1.6 0 0 0-.276.892V9.84a1.8 1.8 0 0 0-.68-.273l.08-1.64a1.48 1.48 0 0 0-1.407-1.46h-1.429a2.47 2.47 0 0 1-2.256-1.472a.68.68 0 0 0-.628-.427h-1.299c-1.883 0-3.409 1.543-3.409 3.447l.032 1.569c-.26.038-.53.124-.735.269V8.627c0-.317-.098-.63-.276-.892a2.44 2.44 0 0 1-.146-2.495a2.4 2.4 0 0 1 1.326-1.15a2.74 2.74 0 0 0 1.412-1.132c.422-.673 1.163-.77 2.013-.77c.33 0 .644.07.936.191c.39.17.828.17 1.217 0a2.4 2.4 0 0 1 .931-.191c.86 0 1.613.113 2.03.803c.313.52.805.897 1.38 1.094");
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

.sombmobgj {
  fill: var(--svg-color--504a4c, #504A4C);
  d: path("M20.568 5.151h-2.123a.492.492 0 1 1 .078-.98c.551.087 1.283.21 1.773.331c1.107.275 1.413.814 1.498 1.198a1.54 1.54 0 0 0-1.226-.549");
}

.srn41o2oz {
  stop-color: var(--svg-color--836158, #836158);
  stop-opacity: 0;
}

.stq0hsb2e {
  stop-color: var(--svg-color--545051, #545051);
  stop-opacity: 0;
}

.sv-y_db3h {
  d: path("M16.295 15.525c-6.07 0-11 4.92-11 11v3.5h21.99v-3.5c0-6.08-4.92-11-10.99-11");
}

.sxoyafbbn {
  stop-color: var(--svg-color--805d4c, #805D4C);
  stop-opacity: 0;
}

.t_m5csgaz {
  stop-color: var(--svg-color--866163, #866163);
}

.tcm21mbym {
  stop-color: var(--svg-color--3f2a51, #3F2A51);
  stop-opacity: 0;
}

.tpa04nh9b {
  stroke: var(--svg-color--433739, #433739);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M12.849 7.997c.262-.188.915-.52 1.688-.39");
}

.tri7bg95c {
  stop-color: var(--svg-color--805d4c, #805D4C);
}

.u3uwpbbrc {
  stop-color: var(--svg-color--4f445b, #4F445B);
}

.ugmfiqbct {
  fill: var(--svg-color--2d171f, #2D171F);
  d: path("m21.608 8.466l-.03-.644c-.01-.779-.654-1.422-1.433-1.454h-1.429a2.47 2.47 0 0 1-2.167-1.285s-.065-.152-.131-.41c-.248-.972.678-1.707 1.658-1.492c.968.212 2.07.57 2.907 1.117c1.78 1.161 1.562 3.183.625 4.168");
}

.ujwfa7bzq {
  stop-color: var(--svg-color--643548, #643548);
}

.ulavx5bri {
  d: path("M21.312 12.23q.102-1.628.188-3.255a1.642 1.642 0 0 1-.189 3.255");
}

.unyhdjbdq {
  stop-color: var(--svg-color--200e25, #200E25);
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

.v7xhdx32s {
  stop-color: var(--svg-color--7d465b, #7D465B);
  stop-opacity: 0;
}

.vnszicyas {
  stop-color: var(--svg-color--160c20, #160C20);
}

.vx5g9qbgu {
  stop-color: var(--svg-color--815f58, #815F58);
}

.w_o-5kbak {
  stop-color: var(--svg-color--7c4c46, #7C4C46);
}

.w0a4mmrgb {
  stop-color: var(--svg-color--200e25, #200E25);
  stop-opacity: 0;
}

.w950_6h3e {
  stop-color: var(--svg-color--4d4159, #4D4159);
}

.wchuwfnpt {
  stop-color: var(--svg-color--60343a, #60343A);
  stop-opacity: 0;
}

.wij0xqc2k {
  fill: var(--svg-color--2d171f, #2D171F);
  d: path("M16.527 5.134a3 3 0 0 1-.067-.14a.68.68 0 0 0-.628-.427h-1.299c-1.883 0-3.409 1.543-3.409 3.448v.28c-.347-.264-.783-.82-.783-1.722c0-1.093.798-1.646 1.306-1.998c.144-.1.265-.184.338-.259l.101-.107c.357-.378.992-1.052 2.102-1.346a5.6 5.6 0 0 1 1.554-.168c.473.012.807.42.807.893V5.12z");
}

.wntqft2su {
  stop-color: var(--svg-color--696070, #696070);
  stop-opacity: 0;
}

.wpa_x2uhd {
  stop-color: var(--svg-color--855e5a, #855E5A);
  stop-opacity: 0;
}

.x3t2hmtbe {
  stop-color: var(--svg-color--46404e, #46404E);
}

.x4e9_o_2d {
  stop-color: var(--svg-color--3a3142, #3A3142);
}

.x9ttejxmc {
  stop-color: var(--svg-color--825d56, #825D56);
}

.xd_ob7sqj {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.73 9.164c.666 0 1.229.46 1.382 1.08a.28.28 0 0 1-.273.348h-2.277a.235.235 0 0 1-.232-.277a1.426 1.426 0 0 1 1.4-1.15");
}

.xlrmucced {
  stop-color: var(--svg-color--685352, #685352);
}

.xp7dwurxx {
  stop-color: var(--svg-color--433a4d, #433A4D);
}

.xqgqqubuj {
  d: path("M25.023 11.698V2.835h-.8v8.863z");
}

.xr7te0bkm {
  stop-color: var(--svg-color--582f25, #582F25);
  stop-opacity: 0;
}

.xron-kbnx {
  stop-color: var(--svg-color--71404f, #71404F);
  stop-opacity: 0;
}

.xuw5xge2n {
  stop-color: var(--svg-color--655f6b, #655F6B);
  stop-opacity: 0;
}

.xw444gber {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.85 9.164c-.666 0-1.229.459-1.382 1.08a.28.28 0 0 0 .273.348h2.277c.145 0 .26-.133.232-.278a1.43 1.43 0 0 0-1.4-1.15");
}

.y07ew4snc {
  fill: var(--svg-color--000, #000);
  d: path("M14.583 10.352a.52.52 0 0 0-.521-.522a.52.52 0 0 0-.464.762h.923a.5.5 0 0 0 .062-.24");
}

.y4umwkb_f {
  stop-color: var(--svg-color--865c56, #865C56);
  stop-opacity: 0;
}

.yfehbvbva {
  d: path("M9.06 30.026V18.239a10.97 10.97 0 0 0-3.765 8.287v3.5z");
}

.yihcw4vuy {
  stop-color: var(--svg-color--766c83, #766C83);
}

.yl8yg_b1a {
  stop-color: var(--svg-color--9b6733, #9B6733);
}

.ym5q1xkkz {
  stop-color: var(--svg-color--372e41, #372E41);
}

.z-0dlhbai {
  stop-color: var(--svg-color--875455, #875455);
  stop-opacity: 0;
}

.z6io75bpj {
  stop-color: var(--svg-color--5d516a, #5D516A);
  stop-opacity: 0;
}

.zqff1532o {
  stop-color: var(--svg-color--201524, #201524);
}

</style>
