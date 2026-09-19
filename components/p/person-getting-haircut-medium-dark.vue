<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iRfdwVd)" class="oiin_fjbq"/><path fill="url(#iJykUxb)" class="oiin_fjbq"/><path fill="url(#i1Hukkc)" class="oiin_fjbq"/><path fill="url(#iEGQBLd)" class="oiin_fjbq"/><path fill="url(#iWl7I0c)" class="f27etvb-z"/><path fill="url(#ixgVuvd)" class="f27etvb-z"/><path class="dyv2dqb1i"/><path fill="url(#ivQWRRd)" class="p9tc7jbhr"/><path fill="url(#ixiSE2c)" class="p9tc7jbhr"/><path class="eyeyz_bgf"/><path fill="url(#iX9WC9d)" class="yp_c_-bvw"/><path fill="url(#iR42qOe)" class="yp_c_-bvw"/><path fill="url(#inI1l4c)" class="wngxwmu4i"/><path fill="url(#i7B4Sec)" class="cv7tqbbcf"/><g filter="url(#i7MOBpb)"><path fill="url(#iqXQk0d)" class="x7dxe7w9i"/><path fill="url(#iwiOJuc)" class="x7dxe7w9i"/></g><path fill="url(#iXGuUXd)" class="x7dxe7w9i"/><path fill="url(#isXViCc)" class="x7dxe7w9i"/><path fill="url(#i9AX7Ex)" class="x7dxe7w9i"/><path fill="url(#iCyoKlk)" class="x7dxe7w9i"/><path fill="url(#iseWolc)" class="x7dxe7w9i"/><path fill="url(#iT49bEx)" class="x7dxe7w9i"/><path fill="url(#icrwOkt)" class="x7dxe7w9i"/><g filter="url(#ip0Odjc)"><path class="fvq9zqbom"/></g><g filter="url(#idIbGcc)"><path class="vumen1-qb"/><path fill="url(#iXCrS5Q)" class="pdp4-s4gi"/><path fill="url(#iXXkEBc)" class="pdp4-s4gi"/><path fill="url(#inhFGYb)" class="pdp4-s4gi"/><path fill="url(#i7ym1Sb)" class="pdp4-s4gi"/><path fill="url(#ig2RFwb)" class="pdp4-s4gi"/></g><g filter="url(#iQEKyls)"><path stroke="url(#iA8drxb)" class="v5jdoj27g"/></g><path fill="url(#i0syl4b)" class="adnv0rt4z"/><g filter="url(#iC6YNHc)"><path fill="url(#iCaamCc)" class="jaylh9bud"/><path fill="url(#iGEyIRc)" class="jaylh9bud"/><path fill="url(#iKgQfKd)" class="jaylh9bud"/><path fill="url(#iiv8nbb)" class="jaylh9bud"/><path fill="url(#iIlx3Kb)" class="jaylh9bud"/></g><g filter="url(#i7zuZMg)"><path class="ig-k9ccin"/></g><g filter="url(#iZIPdab)"><path class="pajr3s_au"/></g><g filter="url(#iauvRxd)"><path class="nyl9_q-vi"/><path fill="url(#iwaZAud)" class="lbt6uzbhk"/><path fill="url(#iOz8XIc)" class="lbt6uzbhk"/></g><g filter="url(#iQH87Xd)"><path class="wslc4wv7i"/><path fill="url(#ihc0AGd)" class="jcvf07b0s"/><path fill="url(#iPFWarb)" class="jcvf07b0s"/></g><path class="mn3tp4buu"/><path fill="url(#ixTW00A)" class="bc4xc5vbf"/><path class="vai0w35mk"/><g filter="url(#iZPQ89s)"><path class="d41ag0bno"/><path fill="url(#ihgcsKd)" class="jrnu6ub_a"/></g><g filter="url(#iNOqjor)"><path fill="url(#iJSQELb)" class="a6yoydbwk"/></g><path class="j_87_bpcp"/><path fill="url(#ixC8l5d)" class="empex3b6d"/><path class="vg92nv9lu"/><g filter="url(#ionXuCH)"><path fill="url(#iJv8E3b)" class="tdh4yzbhz"/></g><g filter="url(#iLsgjIe)"><ellipse transform="rotate(-27.914 12.052 12.888)" class="sjkhe5baa"/><ellipse fill="url(#itcuQIU)" transform="rotate(-27.914 12.052 12.888)" class="gl72tciud"/></g><path fill="url(#ikijvbd)" class="xguqv2y8j"/><path fill="url(#iARvxMb)" class="xguqv2y8j"/><path fill="url(#i1ZI9Vb)" class="xguqv2y8j"/><path fill="url(#iUiukEc)" class="xguqv2y8j"/><path fill="url(#i0Tusqd)" class="rncj0aclf"/><path fill="url(#iCf0DEe)" class="rncj0aclf"/><g filter="url(#iOM3cOb)"><path fill="url(#iHulbGb)" class="otkh3_bzu"/></g><g filter="url(#iwU7GZC)"><path fill="url(#ioAYc5l)" class="w5wqkjb7p"/></g><g filter="url(#ihxttab)"><path class="wyp-dbc9s"/></g><g filter="url(#iMYXMFR)"><path class="b81amm4hu"/></g><g filter="url(#iWhf4RM)"><path class="jwtba6bgn"/></g><g filter="url(#iGRlNkc)"><path class="ryy_tk49k"/></g><g filter="url(#idLbS8d)"><path fill="url(#i30dQsd)" class="xjzbajztg"/><path fill="url(#ikEDuid)" class="xjzbajztg"/><path fill="url(#iRF8AQc)" class="xjzbajztg"/></g><path fill="url(#i3WaTLe)" class="xjzbajztg"/><path fill="url(#iDQwtcc)" class="dpzw0d72j"/><path fill="url(#imIj78b)" class="dpzw0d72j"/><path fill="url(#iVlhyVb)" class="x2w6gzeit"/><path fill="url(#i1VmOLx)" class="x2w6gzeit"/><g filter="url(#i2NOdae)"><circle fill="url(#idxVDvb)" class="uyizti7ua"/><circle fill="url(#iqa9LYd)" class="uyizti7ua"/><circle fill="url(#i1mj24b)" class="uyizti7ua"/></g><g filter="url(#ik3R4Ad)"><path fill="url(#i0KP1Ic)" clip-rule="evenodd" class="r3oqk3bzj"/></g><path fill="url(#iFfdVOe)" clip-rule="evenodd" class="r3oqk3bzj"/><g filter="url(#ilQxdOc)"><path fill="url(#izevDKv)" clip-rule="evenodd" class="pv448eb8b"/></g><g filter="url(#iJcVNiA)"><circle stroke="url(#i0xW4Ae)" class="wkfc83gpk"/></g><g filter="url(#ireDxjc)"><circle stroke="url(#iuMBfAv)" class="riffubc_b"/></g><g filter="url(#iBZBauE)"><circle stroke="url(#iAdUFzd)" class="ik-rq2b1a"/></g><g filter="url(#i2dkXSb)"><circle stroke="url(#iMNrmUc)" class="ru225nb1r"/></g><defs><radialGradient id="iRfdwVd" cx="0" cy="0" r="1" gradientTransform="rotate(154.071 8.19 14.235)scale(15.0662 17.3462)" gradientUnits="userSpaceOnUse"><stop class="qwzbgbcpc"/><stop offset="1" class="yrgygrb-x"/></radialGradient><radialGradient id="iJykUxb" cx="0" cy="0" r="1" gradientTransform="matrix(-7.90627 -10.81244 15.55864 -11.37678 17.382 30.55)" gradientUnits="userSpaceOnUse"><stop offset=".895" class="znj-7lelt"/><stop offset="1" class="w53rld2zh"/></radialGradient><radialGradient id="i1Hukkc" cx="0" cy="0" r="1" gradientTransform="matrix(-10.23463 3.91089 -1.18367 -3.09762 12.577 19.164)" gradientUnits="userSpaceOnUse"><stop offset=".212" class="u-ogyggtr"/><stop offset="1" class="tr4934b7k"/></radialGradient><radialGradient id="iEGQBLd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.6713 0 0 -14.1675 21.46 30.044)" gradientUnits="userSpaceOnUse"><stop offset=".133" class="pujgjpbud"/><stop offset="1" class="dstba7uva"/></radialGradient><radialGradient id="iWl7I0c" cx="0" cy="0" r="1" gradientTransform="matrix(3.25185 0 0 9.13279 21.49 29.265)" gradientUnits="userSpaceOnUse"><stop offset=".576" class="teikdvrbz"/><stop offset="1" class="v5czltblq"/></radialGradient><radialGradient id="ixgVuvd" cx="0" cy="0" r="1" gradientTransform="matrix(.87006 0 0 11.9715 21.49 30.044)" gradientUnits="userSpaceOnUse"><stop class="gbso5obkm"/><stop offset="1" class="x7u0pvbam"/></radialGradient><radialGradient id="ivQWRRd" cx="0" cy="0" r="1" gradientTransform="matrix(-3.70862 0 0 -8.85437 7.224 30.044)" gradientUnits="userSpaceOnUse"><stop offset=".614" class="ajnorac8k"/><stop offset="1" class="o0jyspbad"/></radialGradient><radialGradient id="ixiSE2c" cx="0" cy="0" r="1" gradientTransform="matrix(-.8463 0 0 -16.6933 7.224 30.044)" gradientUnits="userSpaceOnUse"><stop offset=".111" class="w5_5qkbkk"/><stop offset="1" class="h6pm4_bbg"/></radialGradient><radialGradient id="iX9WC9d" cx="0" cy="0" r="1" gradientTransform="matrix(.5625 1.75 -3.03541 .97567 13.614 19.68)" gradientUnits="userSpaceOnUse"><stop offset=".243" class="ib4y-yb5y"/><stop offset="1" class="p_8r96b7o"/></radialGradient><radialGradient id="iR42qOe" cx="0" cy="0" r="1" gradientTransform="matrix(-2.14587 1.92234 -.8326 -.92942 16.683 20.913)" gradientUnits="userSpaceOnUse"><stop offset=".285" class="gx_hl6bcf"/><stop offset="1" class="jq869_bzw"/></radialGradient><radialGradient id="inI1l4c" cx="0" cy="0" r="1" gradientTransform="matrix(.75838 2.04543 -2.42982 .9009 19.351 14.866)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="cbylncbjf"/><stop offset="1" class="hj2nkngkt"/></radialGradient><radialGradient id="i7B4Sec" cx="0" cy="0" r="1" gradientTransform="matrix(1.4954 .46998 -1.4499 4.6134 8.403 15.362)" gradientUnits="userSpaceOnUse"><stop class="i4otoyosx"/><stop offset=".746" class="zqff1532o"/></radialGradient><radialGradient id="iqXQk0d" cx="0" cy="0" r="1" gradientTransform="matrix(-5.29489 0 0 -9.36661 17.38 13.913)" gradientUnits="userSpaceOnUse"><stop class="e4t6-lb6y"/><stop offset="1" class="hhi9hubjb"/><stop offset="1" class="hhi9hubjb"/></radialGradient><radialGradient id="iwiOJuc" cx="0" cy="0" r="1" gradientTransform="rotate(121.159 5.996 9.227)scale(3.41218 2.81703)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="fajfg00jo"/><stop offset="1" class="wpa_x2uhd"/></radialGradient><radialGradient id="isXViCc" cx="0" cy="0" r="1" gradientTransform="matrix(0 9.04993 -12.7765 0 14.584 11.113)" gradientUnits="userSpaceOnUse"><stop offset=".825" class="y7x-29baz"/><stop offset="1" class="hjvcixbup"/></radialGradient><radialGradient id="i9AX7Ex" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.16308 1.43931 0 17.015 12.583)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="o847wybrn"/><stop offset="1" class="z-0dlhbai"/></radialGradient><radialGradient id="iCyoKlk" cx="0" cy="0" r="1" gradientTransform="matrix(.00398 -1.10831 1.2061 .00434 12.206 12.63)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="pxeuj6buu"/><stop offset="1" class="lg98p_5je"/></radialGradient><radialGradient id="iseWolc" cx="0" cy="0" r="1" gradientTransform="matrix(-8.60493 .54319 -1.38756 -21.98125 18.014 14.913)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="sim-rnb6d"/><stop offset="1" class="vx5g9qbgu"/></radialGradient><radialGradient id="iT49bEx" cx="0" cy="0" r="1" gradientTransform="matrix(3.42921 -2.95386 .87252 1.01293 7.658 11.144)" gradientUnits="userSpaceOnUse"><stop offset=".539" class="sf65_-b_u"/><stop offset="1" class="n9ebefe8q"/></radialGradient><radialGradient id="icrwOkt" cx="0" cy="0" r="1" gradientTransform="rotate(95.368 5.088 14.653)scale(2.5406 1.01559)" gradientUnits="userSpaceOnUse"><stop offset=".245" class="p54kb3bjj"/><stop offset="1" class="rm9y2hb6m"/></radialGradient><radialGradient id="iXXkEBc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .24723 -.77702 0 15.01 15.29)" gradientUnits="userSpaceOnUse"><stop class="eqmylox_y"/><stop offset="1" class="sicchzd0u"/></radialGradient><radialGradient id="i7ym1Sb" cx="0" cy="0" r="1" gradientTransform="rotate(155.369 5.957 9.008)scale(1.69487 2.72379)" gradientUnits="userSpaceOnUse"><stop offset=".714" class="cjboikbop"/><stop offset="1" class="l6ffphqdg"/></radialGradient><radialGradient id="i0syl4b" cx="0" cy="0" r="1" gradientTransform="rotate(-26.18 44.827 -21.399)scale(2.46259 9.90764)" gradientUnits="userSpaceOnUse"><stop offset=".562" class="etju2kb3q"/><stop offset="1" class="iazz9lb4s"/></radialGradient><radialGradient id="iGEyIRc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.54622 8.96799 0 9.24 10.983)" gradientUnits="userSpaceOnUse"><stop offset=".536" class="ibt06e6rm"/><stop offset="1" class="k45xjwbmq"/></radialGradient><radialGradient id="iKgQfKd" cx="0" cy="0" r="1" gradientTransform="matrix(.1155 -2.54476 4.50882 .20465 19.46 12.31)" gradientUnits="userSpaceOnUse"><stop class="c98z413ze"/><stop offset="1" class="ovvtmacpn"/></radialGradient><radialGradient id="iiv8nbb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.38908 -1.5713 1.15341 -1.7537 18.696 5.954)" gradientUnits="userSpaceOnUse"><stop class="jx9hffbwe"/><stop offset="1" class="mzj8iibqz"/></radialGradient><radialGradient id="iIlx3Kb" cx="0" cy="0" r="1" gradientTransform="matrix(.6803 1.21358 -2.8101 1.57524 13.62 4.34)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="e8ajgab-k"/><stop offset="1" class="gxf7b0v7y"/></radialGradient><radialGradient id="iwaZAud" cx="0" cy="0" r="1" gradientTransform="matrix(-2.22935 0 0 -.8274 14.794 6.629)" gradientUnits="userSpaceOnUse"><stop class="axstwemrb"/><stop offset="1" class="ez41_pbnb"/></radialGradient><radialGradient id="iOz8XIc" cx="0" cy="0" r="1" gradientTransform="matrix(3.25947 -5.16076 5.71759 3.61116 9.037 10.622)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="hnw0p1utu"/><stop offset=".311" class="dwl_ftd7p"/><stop offset="1" class="fch_lgr5q"/></radialGradient><radialGradient id="ihc0AGd" cx="0" cy="0" r="1" gradientTransform="matrix(2.71307 -2.5849 4.73229 4.96694 17.204 10.492)" gradientUnits="userSpaceOnUse"><stop offset=".857" class="stq0hsb2e"/><stop offset="1" class="i6xvtdb8e"/></radialGradient><radialGradient id="iPFWarb" cx="0" cy="0" r="1" gradientTransform="matrix(3.28987 .38453 -.161 1.3774 16.307 8.996)" gradientUnits="userSpaceOnUse"><stop class="unyhdjbdq"/><stop offset="1" class="w0a4mmrgb"/></radialGradient><radialGradient id="ixTW00A" cx="0" cy="0" r="1" gradientTransform="matrix(0 .82172 -1.30704 0 16.747 12.985)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="ihgcsKd" cx="0" cy="0" r="1" gradientTransform="matrix(-.2349 -.3027 .41673 -.32339 16.517 13.07)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ixC8l5d" cx="0" cy="0" r="1" gradientTransform="matrix(0 .82176 -1.30711 0 12.327 12.985)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="itcuQIU" cx="0" cy="0" r="1" gradientTransform="matrix(-.00784 -.50042 .60152 -.00942 12.037 13.207)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iARvxMb" cx="0" cy="0" r="1" gradientTransform="matrix(.63659 2.27204 -2.16771 .60736 19.214 12.999)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="xron-kbnx"/><stop offset="1" class="bzyp_ibbo"/></radialGradient><radialGradient id="i1ZI9Vb" cx="0" cy="0" r="1" gradientTransform="matrix(.79788 -1.09496 .9178 .66879 19.579 13.55)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="w_o-5kbak"/><stop offset="1" class="mb4bnzbbk"/></radialGradient><radialGradient id="iUiukEc" cx="0" cy="0" r="1" gradientTransform="matrix(.59452 -1.5703 2.09814 .79437 19.694 13.725)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="sxoyafbbn"/><stop offset="1" class="tri7bg95c"/></radialGradient><radialGradient id="iCf0DEe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.67952 0 0 -1.87542 9.558 13.648)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="srn41o2oz"/><stop offset="1" class="dfc36bbxx"/></radialGradient><radialGradient id="iHulbGb" cx="0" cy="0" r="1" gradientTransform="matrix(-.92823 .15935 -.16338 -.95172 9.56 13.651)" gradientUnits="userSpaceOnUse"><stop class="m_eaw6bxg"/><stop offset="1" class="nk_trfbso"/></radialGradient><radialGradient id="ikEDuid" cx="0" cy="0" r="1" gradientTransform="matrix(-.31067 .66453 -.28734 -.13433 23.331 5.359)" gradientUnits="userSpaceOnUse"><stop offset=".012" class="c3w4u4bzd"/><stop offset="1" class="jyrdn9ahj"/></radialGradient><radialGradient id="iRF8AQc" cx="0" cy="0" r="1" gradientTransform="matrix(3.40625 0 0 1.69526 17.37 7.374)" gradientUnits="userSpaceOnUse"><stop offset=".147" class="q-ihqm96i"/><stop offset="1" class="w5qj8unug"/></radialGradient><radialGradient id="i3WaTLe" cx="0" cy="0" r="1" gradientTransform="rotate(-110.771 12.129 -1.407)scale(3.83324 9.66691)" gradientUnits="userSpaceOnUse"><stop offset=".773" class="pbzhpf_jy"/><stop offset="1" class="vt-fkub8f"/></radialGradient><radialGradient id="idxVDvb" cx="0" cy="0" r="1" gradientTransform="rotate(141.18 10.662 8.025)scale(.43619)" gradientUnits="userSpaceOnUse"><stop offset=".168" class="cz-qsgbfy"/><stop offset="1" class="j80tr6o9y"/></radialGradient><radialGradient id="iqa9LYd" cx="0" cy="0" r="1" gradientTransform="matrix(.19922 -.48438 1.17186 .48198 23.68 8.035)" gradientUnits="userSpaceOnUse"><stop offset=".147" class="m8bo-jb-t"/><stop offset="1" class="wy7e69bbh"/></radialGradient><radialGradient id="i1mj24b" cx="0" cy="0" r="1" gradientTransform="matrix(.4375 .04684 -.05916 .55254 23.455 7.597)" gradientUnits="userSpaceOnUse"><stop offset=".181" class="zk512ndyg"/><stop offset="1" class="hy0z0nf6k"/></radialGradient><radialGradient id="i0KP1Ic" cx="0" cy="0" r="1" gradientTransform="matrix(2.20247 -1.61719 2.56784 3.49718 21.483 10.784)" gradientUnits="userSpaceOnUse"><stop offset=".205" class="cnux6p8xn"/><stop offset="1" class="jaxt-o31p"/></radialGradient><radialGradient id="izevDKv" cx="0" cy="0" r="1" gradientTransform="matrix(2.53124 -1.40627 1.98705 3.57664 24.63 8.96)" gradientUnits="userSpaceOnUse"><stop offset=".205" class="cnux6p8xn"/><stop offset="1" class="jaxt-o31p"/></radialGradient><filter id="i7MOBpb" width="11.351" height="12.7" x="9.409" y="7.663" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".7"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.494118 0 0 0 0 0.352941 0 0 0 0 0.32549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_27"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.396078 0 0 0 0 0.215686 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_27" result="effect2_innerShadow_4002_27"/></filter><filter id="ip0Odjc" width="3.769" height="4.937" x="12.508" y="12.078" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_27" stdDeviation=".5"/></filter><filter id="idIbGcc" width="2.101" height="3.137" x="13.486" y="12.779" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_27" stdDeviation=".05"/></filter><filter id="iQEKyls" width="3.76" height="1.587" x="12.657" y="16.245" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_27" stdDeviation=".05"/></filter><filter id="iC6YNHc" width="13.038" height="8.457" x="8.018" y="4.452" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.137255 0 0 0 0 0.0901961 0 0 0 0 0.145098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_27"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0784314 0 0 0 0 0.0352941 0 0 0 0 0.0470588 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_27" result="effect2_innerShadow_4002_27"/></filter><filter id="i7zuZMg" width="2.368" height="1.203" x="16.146" y="10.184" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.172549 0 0 0 0 0.0862745 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_27"/></filter><filter id="iZIPdab" width="2.368" height="1.188" x="10.823" y="10.199" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.172549 0 0 0 0 0.0862745 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_27"/></filter><filter id="iauvRxd" width="6.662" height="6.062" x="8.381" y="5.552" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.286275 0 0 0 0 0.243137 0 0 0 0 0.227451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_27"/><feGaussianBlur result="effect2_foregroundBlur_4002_27" stdDeviation=".125"/></filter><filter id="iQH87Xd" width="6.398" height="5.782" x="14.376" y="6.001" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_27" stdDeviation=".125"/></filter><filter id="iZPQ89s" width=".794" height=".703" x="16.005" y="12.54" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_27" stdDeviation=".05"/></filter><filter id="iNOqjor" width=".898" height=".92" x="16.857" y="12.618" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_27" stdDeviation=".1"/></filter><filter id="ionXuCH" width=".994" height="1.048" x="12.357" y="12.553" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_27" stdDeviation=".1"/></filter><filter id="iLsgjIe" width=".922" height=".711" x="11.591" y="12.532" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_27" stdDeviation=".05"/></filter><filter id="iOM3cOb" width="1.34" height="2.404" x="8.381" y="12.449" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_27" stdDeviation=".125"/></filter><filter id="iwU7GZC" width="1.959" height="2.928" x="19.043" y="12.18" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_27" stdDeviation=".25"/></filter><filter id="ihxttab" width="2.426" height="1.166" x="10.746" y="10.277" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_27" stdDeviation=".125"/></filter><filter id="iMYXMFR" width="2.426" height="1.166" x="16.092" y="10.23" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_27" stdDeviation=".125"/></filter><filter id="iWhf4RM" width="5.314" height="3.025" x="15.437" y="6.45" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_27" stdDeviation=".375"/></filter><filter id="iGRlNkc" width="5.314" height="3.025" x="15.437" y="6.513" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_27" stdDeviation=".375"/></filter><filter id="idLbS8d" width="9.109" height="4.371" x="14.746" y="5.064" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0745098 0 0 0 0 0.0235294 0 0 0 0 0.054902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_27"/></filter><filter id="i2NOdae" width=".726" height=".726" x="23.512" y="7.275" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.52549 0 0 0 0 0.388235 0 0 0 0 0.501961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_27"/></filter><filter id="ik3R4Ad" width="3.834" height="4.387" x="21.054" y="8.076" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.945098 0 0 0 0 0.45098 0 0 0 0 0.333333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_27"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.282353 0 0 0 0 0.435294 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_27" result="effect2_innerShadow_4002_27"/></filter><filter id="ilQxdOc" width="4.283" height="3.734" x="24.252" y="6.599" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.882353 0 0 0 0 0.203922 0 0 0 0 0.435294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_27"/></filter><filter id="iJcVNiA" width="3.843" height="3.843" x="24.723" y="6.57" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_27" stdDeviation=".1"/></filter><filter id="ireDxjc" width="2.734" height="2.734" x="25.278" y="7.124" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_27" stdDeviation=".1"/></filter><filter id="iBZBauE" width="2.734" height="2.734" x="21.629" y="9.138" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_27" stdDeviation=".1"/></filter><filter id="i2dkXSb" width="3.805" height="3.805" x="21.093" y="8.603" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_27" stdDeviation=".1"/></filter><linearGradient id="iXGuUXd" x1="19.76" x2="17.199" y1="15.62" y2="15.62" gradientUnits="userSpaceOnUse"><stop class="agilw2byy"/><stop offset="1" class="h3kh2yb2k"/></linearGradient><linearGradient id="iXCrS5Q" x1="15.386" x2="14.537" y1="14.596" y2="14.631" gradientUnits="userSpaceOnUse"><stop offset=".36" class="eqmylox_y"/><stop offset="1" class="sicchzd0u"/></linearGradient><linearGradient id="inhFGYb" x1="14.537" x2="14.537" y1="15.75" y2="15.279" gradientUnits="userSpaceOnUse"><stop class="qsncw6btn"/><stop offset="1" class="v7xhdx32s"/></linearGradient><linearGradient id="ig2RFwb" x1="14.537" x2="14.537" y1="13.01" y2="13.564" gradientUnits="userSpaceOnUse"><stop class="fok393bvn"/><stop offset="1" class="y4umwkb_f"/></linearGradient><linearGradient id="iA8drxb" x1="13.32" x2="13.642" y1="17.341" y2="16.496" gradientUnits="userSpaceOnUse"><stop class="t_m5csgaz"/><stop offset="1" class="ln8xouyxx"/></linearGradient><linearGradient id="iCaamCc" x1="21.477" x2="9.716" y1="8.177" y2="8.177" gradientUnits="userSpaceOnUse"><stop class="s5pji6bqr"/><stop offset="1" class="c7qpv738k"/></linearGradient><linearGradient id="iJSQELb" x1="17.535" x2="17.217" y1="13.039" y2="13.235" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iJv8E3b" x1="13.081" x2="12.763" y1="13.039" y2="13.235" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ikijvbd" x1="21.056" x2="19.834" y1="13.066" y2="15.271" gradientUnits="userSpaceOnUse"><stop class="pkjt6qfem"/><stop offset="1" class="qw3t0fbxr"/></linearGradient><linearGradient id="i0Tusqd" x1="8.612" x2="10.089" y1="13.779" y2="13.65" gradientUnits="userSpaceOnUse"><stop class="lsjj5yb-k"/><stop offset="1" class="ac3zxpbrp"/></linearGradient><linearGradient id="ioAYc5l" x1="20.023" x2="20.023" y1="12.68" y2="14.607" gradientUnits="userSpaceOnUse"><stop class="x9ttejxmc"/><stop offset="1" class="nal-rljch"/></linearGradient><linearGradient id="i30dQsd" x1="23.605" x2="17.52" y1="5.648" y2="9.336" gradientUnits="userSpaceOnUse"><stop class="bwjnn6b0s"/><stop offset="1" class="fr2kogihj"/></linearGradient><linearGradient id="iDQwtcc" x1="25.035" x2="23.843" y1="5.737" y2="5.392" gradientUnits="userSpaceOnUse"><stop class="p9lsnsm5t"/><stop offset="1" class="lapvr59ed"/></linearGradient><linearGradient id="imIj78b" x1="23.887" x2="23.961" y1="7.23" y2="6.941" gradientUnits="userSpaceOnUse"><stop offset=".16" class="zl0fwhbas"/><stop offset="1" class="lxc0fmbqt"/></linearGradient><linearGradient id="iVlhyVb" x1="22.973" x2="23.238" y1="8.086" y2="6.789" gradientUnits="userSpaceOnUse"><stop class="p9lsnsm5t"/><stop offset="1" class="lapvr59ed"/></linearGradient><linearGradient id="i1VmOLx" x1="24.384" x2="24.186" y1="8.168" y2="8.112" gradientUnits="userSpaceOnUse"><stop class="jd-vaq0no"/><stop offset="1" class="gof7ehbkx"/></linearGradient><linearGradient id="iFfdVOe" x1="23.723" x2="23.664" y1="8.258" y2="8.484" gradientUnits="userSpaceOnUse"><stop offset=".209" class="ni_6htbzm"/><stop offset="1" class="ajm38_jxm"/></linearGradient><linearGradient id="i0xW4Ae" x1="24.973" x2="28.163" y1="8.86" y2="7.388" gradientUnits="userSpaceOnUse"><stop offset=".616" class="w5_7ycb6b"/><stop offset=".9" class="srm_r_guo"/></linearGradient><linearGradient id="iuMBfAv" x1="25.528" x2="27.66" y1="8.738" y2="7.754" gradientUnits="userSpaceOnUse"><stop offset=".247" class="jzjqx7qlk"/><stop offset=".669" class="gl3wl_9gz"/></linearGradient><linearGradient id="iAdUFzd" x1="21.879" x2="24.011" y1="10.752" y2="9.768" gradientUnits="userSpaceOnUse"><stop offset=".247" class="rraw6sbsp"/><stop offset=".669" class="r8ibvzbki"/></linearGradient><linearGradient id="iMNrmUc" x1="24.648" x2="22.996" y1="9.964" y2="10.505" gradientUnits="userSpaceOnUse"><stop class="znwvjy5yx"/><stop offset="1" class="zi0lb2bns"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-getting-haircut-medium-dark" /></template>
<style>
.a6yoydbwk {
  d: path("M17.554 13.286a.85.85 0 0 0-.234-.468l-.263.289l.118.23z");
}

.ac3zxpbrp {
  stop-color: var(--svg-color--623549, #623549);
}

.adnv0rt4z {
  d: path("M14.537 16.846c-.514 0-.997-.12-1.403-.332c-.139-.071-.288.085-.2.211c.339.514.93.857 1.603.857s1.264-.343 1.604-.857c.087-.13-.062-.282-.2-.211a3 3 0 0 1-1.404.332");
}

.agilw2byy {
  stop-color: var(--svg-color--936b5d, #936B5D);
}

.ajm38_jxm {
  stop-color: var(--svg-color--ff3178, #FF3178);
  stop-opacity: 0;
}

.ajnorac8k {
  stop-color: var(--svg-color--e36750, #E36750);
  stop-opacity: 0;
}

.axstwemrb {
  stop-color: var(--svg-color--423c3f, #423C3F);
}

.b81amm4hu {
  stroke: var(--svg-color--433739, #433739);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M18.144 11.02c-.26-.186-.91-.514-1.677-.385");
}

.bbyb_mbsk {
  stop-color: var(--svg-color--664842, #664842);
}

.bc4xc5vbf {
  d: path("M16.75 12.502a.904.904 0 0 1 .87 1.142h-1.746a.907.907 0 0 1 .875-1.142");
}

.bwjnn6b0s {
  stop-color: var(--svg-color--271223, #271223);
}

.bzyp_ibbo {
  stop-color: var(--svg-color--71404f, #71404F);
}

.c3w4u4bzd {
  stop-color: var(--svg-color--32212a, #32212A);
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

.cnux6p8xn {
  stop-color: var(--svg-color--ff7046, #FF7046);
}

.cv7tqbbcf {
  d: path("M9.613 15.179a1.66 1.66 0 0 1-.916-.313v.943a2.2 2.2 0 0 0 1.358 2.045a4.1 4.1 0 0 1-.35-1.195z");
}

.cz-qsgbfy {
  stop-color: var(--svg-color--ebdbe4, #EBDBE4);
}

.d41ag0bno {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M16.683 12.693c.064.086-.07.19-.224.305c-.153.115-.266.195-.33.109c-.065-.086.007-.249.16-.363c.153-.115.33-.138.394-.051");
}

.dfc36bbxx {
  stop-color: var(--svg-color--836158, #836158);
}

.dpzw0d72j {
  d: path("m24.428 3.332l-1.388 4.83l1.187.346l1.071-3.73a1.15 1.15 0 0 0-.784-1.421z");
}

.dstba7uva {
  stop-color: var(--svg-color--ff7543, #FF7543);
  stop-opacity: 0;
}

.dwl_ftd7p {
  stop-color: var(--svg-color--1c0c20, #1C0C20);
}

.dyv2dqb1i {
  fill: var(--svg-color--ff4f19, #FF4F19);
  d: path("M7.224 21.515c-2.273 1.963-3.71 4.849-3.71 8.066v.463h3.71z");
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e4t6-lb6y {
  stop-color: var(--svg-color--9a6e61, #9A6E61);
}

.e8ajgab-k {
  stop-color: var(--svg-color--392f31, #392F31);
}

.empex3b6d {
  d: path("M12.325 12.502a.904.904 0 0 0-.871 1.142H13.2a1 1 0 0 0 .033-.239a.91.91 0 0 0-.908-.903");
}

.eqmylox_y {
  stop-color: var(--svg-color--a17c72, #A17C72);
}

.etju2kb3q {
  stop-color: var(--svg-color--87004e, #87004E);
}

.eyeyz_bgf {
  fill: var(--svg-color--894f55, #894F55);
  d: path("M12.545 18.664h3.984v1.383c0 1.1-.892 1.812-1.992 1.812s-1.992-.712-1.992-1.812z");
}

.ez41_pbnb {
  stop-color: var(--svg-color--423c3f, #423C3F);
  stop-opacity: 0;
}

.f27etvb-z {
  d: path("M21.49 30.044h3.71v-.463c0-3.217-1.437-6.103-3.71-8.066z");
}

.fajfg00jo {
  stop-color: var(--svg-color--855e5a, #855E5A);
}

.fch_lgr5q {
  stop-color: var(--svg-color--1c0c20, #1C0C20);
  stop-opacity: 0;
}

.fok393bvn {
  stop-color: var(--svg-color--865c56, #865C56);
}

.fr2kogihj {
  stop-color: var(--svg-color--251720, #251720);
}

.ft5dv1b6b {
  fill: none;
}

.fvq9zqbom {
  fill: var(--svg-color--6f3f46, #6F3F46);
  d: path("m14.13 13.387l-.598 1.862c-.102.383.143.766.49.766h.742c.347 0 .593-.389.49-.766l-.5-1.862c-.108-.412-.511-.412-.624 0");
}

.gbso5obkm {
  stop-color: var(--svg-color--ff5130, #FF5130);
}

.gl3wl_9gz {
  stop-color: var(--svg-color--ff7e7a, #FF7E7A);
  stop-opacity: 0;
}

.gl72tciud {
  cx: 12.052px;
  cy: 12.888px;
  rx: 0.395px;
  ry: 0.2px;
}

.gof7ehbkx {
  stop-color: var(--svg-color--a2889f, #A2889F);
  stop-opacity: 0;
}

.gx_hl6bcf {
  stop-color: var(--svg-color--975e54, #975E54);
}

.gxf7b0v7y {
  stop-color: var(--svg-color--392f31, #392F31);
  stop-opacity: 0;
}

.h3kh2yb2k {
  stop-color: var(--svg-color--936b5d, #936B5D);
  stop-opacity: 0;
}

.h6pm4_bbg {
  stop-color: var(--svg-color--ff6640, #FF6640);
  stop-opacity: 0;
}

.hhi9hubjb {
  stop-color: var(--svg-color--754c4c, #754C4C);
}

.hj2nkngkt {
  stop-color: var(--svg-color--221925, #221925);
}

.hjvcixbup {
  stop-color: var(--svg-color--7b3a46, #7B3A46);
}

.hnw0p1utu {
  stop-color: var(--svg-color--0b0306, #0B0306);
}

.hy0z0nf6k {
  stop-color: var(--svg-color--a4888c, #A4888C);
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

.ib4y-yb5y {
  stop-color: var(--svg-color--75343d, #75343D);
}

.ibt06e6rm {
  stop-color: var(--svg-color--3e3433, #3E3433);
}

.ig-k9ccin {
  fill: var(--svg-color--2e201f, #2E201F);
  d: path("M18.318 10.895a1.9 1.9 0 0 0-.697-.417c-.308-.097-.694-.123-1.228-.058a.28.28 0 1 0 .069.558c.487-.06.785-.029.99.036c.201.063.337.166.497.304a.28.28 0 1 0 .369-.423");
}

.ik-rq2b1a {
  cx: 22.996px;
  cy: 10.505px;
  r: 1.117px;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
}

.j_87_bpcp {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.116 12.226c-.662 0-1.22.456-1.373 1.072a.278.278 0 0 0 .271.346h2.26a.233.233 0 0 0 .23-.276a1.42 1.42 0 0 0-1.388-1.142");
}

.j80tr6o9y {
  stop-color: var(--svg-color--c7b1b5, #C7B1B5);
}

.jaxt-o31p {
  stop-color: var(--svg-color--ff2d78, #FF2D78);
}

.jaylh9bud {
  d: path("M19.454 7.185c.521.179.988.543 1.284 1.064a2.4 2.4 0 0 1-.107 2.559a1.6 1.6 0 0 0-.274.886v1.203c-.19-.132-.44-.23-.676-.272l.08-1.627a1.47 1.47 0 0 0-1.397-1.45h-1.419c-.966 0-1.842-.57-2.24-1.462a.67.67 0 0 0-.623-.423h-1.289c-1.87 0-3.384 1.532-3.384 3.422l.03 1.557a1.7 1.7 0 0 0-.729.267v-1.216a1.6 1.6 0 0 0-.274-.885a2.42 2.42 0 0 1-.145-2.477c.296-.56.774-.95 1.317-1.14a2.7 2.7 0 0 0 1.402-1.125a2.355 2.355 0 0 1 2.927-.924a1.5 1.5 0 0 0 1.209 0c.285-.12.596-.19.924-.19c.854 0 1.6.462 2.014 1.146c.312.516.8.891 1.37 1.087");
}

.jcvf07b0s {
  d: path("m19.816 11.533l-.03-.639c-.01-.773-.649-1.411-1.422-1.444h-1.419c-.9 0-1.72-.492-2.15-1.275c0 0-.064-.146-.128-.395c-.25-.971.676-1.707 1.656-1.49c.957.21 2.045.566 2.873 1.106c1.766 1.152 1.55 3.16.62 4.137");
}

.jd-vaq0no {
  stop-color: var(--svg-color--93768e, #93768E);
}

.jq869_bzw {
  stop-color: var(--svg-color--975e54, #975E54);
  stop-opacity: 0;
}

.jrnu6ub_a {
  d: path("M16.683 12.693c.064.086-.07.19-.224.305c-.153.115-.266.195-.33.109c-.065-.086.007-.249.16-.363c.153-.115.33-.138.394-.051");
}

.jwtba6bgn {
  fill: var(--svg-color--49373d, #49373D);
  d: path("M18.784 8.18h-2.108a.489.489 0 1 1 .078-.974c.547.088 1.273.209 1.76.33c1.099.272 1.402.807 1.487 1.189a1.53 1.53 0 0 0-1.217-.545");
}

.jx9hffbwe {
  stop-color: var(--svg-color--402c32, #402C32);
}

.jyrdn9ahj {
  stop-color: var(--svg-color--32212a, #32212A);
  stop-opacity: 0;
}

.jzjqx7qlk {
  stop-color: var(--svg-color--ff7e7a, #FF7E7A);
}

.k45xjwbmq {
  stop-color: var(--svg-color--3e3433, #3E3433);
  stop-opacity: 0;
}

.l6ffphqdg {
  stop-color: var(--svg-color--744a4a, #744A4A);
}

.lapvr59ed {
  stop-color: var(--svg-color--d9b4c8, #D9B4C8);
}

.lbt6uzbhk {
  d: path("m14.772 8.225l-.067-.139a.67.67 0 0 0-.623-.423h-1.289c-1.87 0-3.384 1.532-3.384 3.422v.279c-.345-.262-.778-.815-.778-1.71c0-1.085.792-1.634 1.297-1.984c.143-.099.262-.182.335-.257l.101-.106c.354-.375.985-1.044 2.086-1.337a5.5 5.5 0 0 1 1.538-.166c.472.012.806.42.806.893V8.21z");
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

.lsjj5yb-k {
  stop-color: var(--svg-color--6a4544, #6A4544);
}

.lxc0fmbqt {
  stop-color: var(--svg-color--c0a0b5, #C0A0B5);
  stop-opacity: 0;
}

.m_eaw6bxg {
  stop-color: var(--svg-color--57353c, #57353C);
}

.m8bo-jb-t {
  stop-color: var(--svg-color--996e9f, #996E9F);
}

.mb4bnzbbk {
  stop-color: var(--svg-color--7c4c46, #7C4C46);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mn3tp4buu {
  fill: var(--svg-color--fff, #fff);
  d: path("M16.959 12.226c.661 0 1.22.456 1.372 1.073a.278.278 0 0 1-.271.345H15.8a.233.233 0 0 1-.23-.276a1.416 1.416 0 0 1 1.389-1.142");
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

.ni_6htbzm {
  stop-color: var(--svg-color--b71143, #B71143);
}

.nk_trfbso {
  stop-color: var(--svg-color--5b3336, #5B3336);
}

.nyl9_q-vi {
  fill: var(--svg-color--2d171f, #2D171F);
  d: path("m14.772 8.225l-.067-.139a.67.67 0 0 0-.623-.423h-1.289c-1.87 0-3.384 1.532-3.384 3.422v.279c-.345-.262-.778-.815-.778-1.71c0-1.085.792-1.634 1.297-1.984c.143-.099.262-.182.335-.257l.101-.106c.354-.375.985-1.044 2.086-1.337a5.5 5.5 0 0 1 1.538-.166c.472.012.806.42.806.893V8.21z");
}

.o0jyspbad {
  stop-color: var(--svg-color--e36750, #E36750);
}

.o847wybrn {
  stop-color: var(--svg-color--875455, #875455);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oiin_fjbq {
  d: path("M3.515 29.58c0-5.915 4.854-10.71 10.842-10.71s10.842 4.795 10.842 10.71v.464H3.515z");
}

.otkh3_bzu {
  d: path("M9.386 12.699a.968.968 0 0 0 .085 1.903a79 79 0 0 1-.085-1.903");
}

.ovvtmacpn {
  stop-color: var(--svg-color--4f4d4d, #4F4D4D);
  stop-opacity: 0;
}

.p_8r96b7o {
  stop-color: var(--svg-color--75343d, #75343D);
  stop-opacity: 0;
}

.p54kb3bjj {
  stop-color: var(--svg-color--98786d, #98786D);
}

.p9lsnsm5t {
  stop-color: var(--svg-color--9b8299, #9B8299);
}

.p9tc7jbhr {
  d: path("M7.224 21.515c-2.273 1.963-3.71 4.849-3.71 8.066v.463h3.71z");
}

.pajr3s_au {
  fill: var(--svg-color--2e201f, #2E201F);
  d: path("M11.082 10.784a2.8 2.8 0 0 1 1.761-.364a.28.28 0 1 1-.068.558a2.25 2.25 0 0 0-1.404.288a1 1 0 0 0-.093.06l-.003.003a.28.28 0 0 1-.344-.444z");
}

.pbzhpf_jy {
  stop-color: var(--svg-color--301d23, #301D23);
  stop-opacity: 0;
}

.pdp4-s4gi {
  d: path("m14.15 13.189l-.539 1.862c-.11.383.154.766.528.766h.796c.374 0 .637-.39.527-.766l-.538-1.862c-.115-.413-.653-.413-.774 0");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pkjt6qfem {
  stop-color: var(--svg-color--9c7b71, #9C7B71);
}

.pujgjpbud {
  stop-color: var(--svg-color--ff7543, #FF7543);
}

.pv448eb8b {
  fill-rule: evenodd;
  d: path("M24.543 7.343a.1.1 0 0 1 .123-.07l.36.095a.22.22 0 0 0 .216-.072a1.842 1.842 0 1 1-.412 1.52a.22.22 0 0 0-.153-.172l-.351-.094a.1.1 0 0 1-.07-.122zm1.664 1.87a.844.844 0 1 0 .872-1.444a.844.844 0 0 0-.872 1.445");
}

.pxeuj6buu {
  stop-color: var(--svg-color--70424e, #70424E);
}

.q-ihqm96i {
  stop-color: var(--svg-color--413338, #413338);
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

.qwzbgbcpc {
  stop-color: var(--svg-color--ff702c, #FF702C);
}

.r3oqk3bzj {
  fill-rule: evenodd;
  d: path("M23.099 8.13a.1.1 0 0 0-.124.068l-.104.357a.22.22 0 0 1-.174.149a1.842 1.842 0 1 0 1.514.433a.21.21 0 0 1-.068-.22l.101-.349a.1.1 0 0 0-.068-.124zm.74 2.391a.844.844 0 1 1-1.687 0a.844.844 0 0 1 1.688 0");
}

.r8ibvzbki {
  stop-color: var(--svg-color--ff9266, #FF9266);
  stop-opacity: 0;
}

.riffubc_b {
  cx: 26.645px;
  cy: 8.492px;
  r: 1.117px;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
}

.rm9y2hb6m {
  stop-color: var(--svg-color--98786d, #98786D);
  stop-opacity: 0;
}

.rncj0aclf {
  d: path("M9.428 12.025a1.644 1.644 0 0 0-1.41 1.619c0 .87.682 1.58 1.54 1.627a79 79 0 0 1-.13-3.246");
}

.rraw6sbsp {
  stop-color: var(--svg-color--ff9266, #FF9266);
}

.ru225nb1r {
  cx: 22.996px;
  cy: 10.505px;
  r: 1.652px;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
}

.ryy_tk49k {
  fill: var(--svg-color--504a4c, #504A4C);
  d: path("M18.784 8.243h-2.108a.489.489 0 1 1 .078-.974c.547.087 1.273.209 1.76.33c1.099.272 1.402.807 1.487 1.189a1.53 1.53 0 0 0-1.217-.545");
}

.s5pji6bqr {
  stop-color: var(--svg-color--443237, #443237);
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

.sjkhe5baa {
  cx: 12.052px;
  cy: 12.888px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.395px;
  ry: 0.2px;
}

.srm_r_guo {
  stop-color: var(--svg-color--ff6792, #FF6792);
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

.t_m5csgaz {
  stop-color: var(--svg-color--866163, #866163);
}

.tdh4yzbhz {
  d: path("M13.151 13.3c0-.293-.238-.488-.302-.547l-.292.283l.18.366z");
}

.teikdvrbz {
  stop-color: var(--svg-color--ff7646, #FF7646);
}

.tr4934b7k {
  stop-color: var(--svg-color--ff5915, #FF5915);
  stop-opacity: 0;
}

.tri7bg95c {
  stop-color: var(--svg-color--805d4c, #805D4C);
}

.u-ogyggtr {
  stop-color: var(--svg-color--e73f04, #E73F04);
}

.unyhdjbdq {
  stop-color: var(--svg-color--200e25, #200E25);
}

.uyizti7ua {
  cx: 23.825px;
  cy: 7.688px;
  r: 0.313px;
}

.v5czltblq {
  stop-color: var(--svg-color--ff6635, #FF6635);
}

.v5jdoj27g {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M16.203 16.767a.216.216 0 0 0-.024-.275a.23.23 0 0 0-.273-.045a2.95 2.95 0 0 1-1.37.324a3 3 0 0 1-1.368-.324a.23.23 0 0 0-.274.047a.214.214 0 0 0-.023.273m3.332 0l-.062-.042zm0 0c-.353.534-.967.89-1.666.89a2 2 0 0 1-1.666-.89m0 0v.001l.062-.043m-.062.042l.062-.042m0 0c.34.514.93.857 1.604.857a1.92 1.92 0 0 0 1.604-.857c.087-.13-.062-.282-.2-.211a3 3 0 0 1-1.404.332c-.514 0-.997-.12-1.403-.332c-.139-.071-.288.085-.2.211Z");
}

.v7xhdx32s {
  stop-color: var(--svg-color--7d465b, #7D465B);
  stop-opacity: 0;
}

.vai0w35mk {
  fill: var(--svg-color--000, #000);
  d: path("M16.231 13.405c0-.287.23-.517.518-.517a.516.516 0 0 1 .46.756h-.916a.47.47 0 0 1-.062-.239");
}

.vg92nv9lu {
  fill: var(--svg-color--000, #000);
  d: path("M12.843 13.405a.516.516 0 0 0-.518-.517a.516.516 0 0 0-.46.756h.916a.5.5 0 0 0 .062-.239");
}

.vt-fkub8f {
  stop-color: var(--svg-color--301d23, #301D23);
}

.vumen1-qb {
  fill: var(--svg-color--845b55, #845B55);
  d: path("m14.15 13.189l-.539 1.862c-.11.383.154.766.528.766h.796c.374 0 .637-.39.527-.766l-.538-1.862c-.115-.413-.653-.413-.774 0");
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

.w5_5qkbkk {
  stop-color: var(--svg-color--ff6640, #FF6640);
}

.w5_7ycb6b {
  stop-color: var(--svg-color--ff4f4f, #FF4F4F);
}

.w53rld2zh {
  stop-color: var(--svg-color--e65d38, #E65D38);
}

.w5qj8unug {
  stop-color: var(--svg-color--413338, #413338);
  stop-opacity: 0;
}

.w5wqkjb7p {
  d: path("M19.543 14.607q.06-.963.112-1.927a.968.968 0 0 1-.112 1.927");
}

.wkfc83gpk {
  cx: 26.645px;
  cy: 8.492px;
  r: 1.671px;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
}

.wngxwmu4i {
  d: path("M19.46 15.179c.34-.011.658-.127.917-.313v.943a2.2 2.2 0 0 1-1.358 2.045q.259-.553.35-1.195z");
}

.wpa_x2uhd {
  stop-color: var(--svg-color--855e5a, #855E5A);
  stop-opacity: 0;
}

.wslc4wv7i {
  fill: var(--svg-color--2d171f, #2D171F);
  d: path("m19.816 11.533l-.03-.639c-.01-.773-.649-1.411-1.422-1.444h-1.419c-.9 0-1.72-.492-2.15-1.275c0 0-.064-.146-.128-.395c-.25-.971.676-1.707 1.656-1.49c.957.21 2.045.566 2.873 1.106c1.766 1.152 1.55 3.16.62 4.137");
}

.wy7e69bbh {
  stop-color: var(--svg-color--c8b3b7, #C8B3B7);
  stop-opacity: 0;
}

.wyp-dbc9s {
  stroke: var(--svg-color--433739, #433739);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M11.12 11.068c.26-.187.91-.516 1.677-.387");
}

.x2w6gzeit {
  d: path("m19.78 5.909l5.42 1.536l-.338 1.189L20.55 7.41a1.15 1.15 0 0 1-.793-1.42z");
}

.x7dxe7w9i {
  d: path("M9.65 16.713a3.966 3.966 0 0 0 3.936 3.45h1.91a3.966 3.966 0 0 0 3.936-3.45c.12-1.908.24-3.808.328-5.715a1.47 1.47 0 0 0-1.397-1.45h-1.418c-.967 0-1.842-.57-2.24-1.462a.67.67 0 0 0-.623-.423h-1.29c-1.868 0-3.383 1.532-3.383 3.422c0 1.885.117 3.739.241 5.628");
}

.x7u0pvbam {
  stop-color: var(--svg-color--ff5130, #FF5130);
  stop-opacity: 0;
}

.x9ttejxmc {
  stop-color: var(--svg-color--825d56, #825D56);
}

.xguqv2y8j {
  d: path("M19.522 15.27q.101-1.615.187-3.232a1.63 1.63 0 0 1-.187 3.233");
}

.xjzbajztg {
  d: path("M18.614 9.367c3.492-.378 4.66-1.906 4.922-2.867c.055-.17.122-.602 0-.957c-.097-.285-.437-.348-.593.066c-.367.89-1.172 1.305-2.04 1.453c-.866.149-1.655.227-3.062-.398c-1.004-.446-1.578-.61-2.18-.406c-.601.203-1.195.86-.773 1.867c.376.898 1.125 1.523 3.726 1.242");
}

.xron-kbnx {
  stop-color: var(--svg-color--71404f, #71404F);
  stop-opacity: 0;
}

.y4umwkb_f {
  stop-color: var(--svg-color--865c56, #865C56);
  stop-opacity: 0;
}

.y7x-29baz {
  stop-color: var(--svg-color--794057, #794057);
  stop-opacity: 0;
}

.yp_c_-bvw {
  d: path("M12.545 18.664h3.984v1.383c0 1.1-.892 1.812-1.992 1.812s-1.992-.712-1.992-1.812z");
}

.yrgygrb-x {
  stop-color: var(--svg-color--ff521f, #FF521F);
}

.z-0dlhbai {
  stop-color: var(--svg-color--875455, #875455);
  stop-opacity: 0;
}

.zi0lb2bns {
  stop-color: var(--svg-color--ff5185, #FF5185);
  stop-opacity: 0;
}

.zk512ndyg {
  stop-color: var(--svg-color--a4888c, #A4888C);
}

.zl0fwhbas {
  stop-color: var(--svg-color--a28b95, #A28B95);
}

.znj-7lelt {
  stop-color: var(--svg-color--e65d38, #E65D38);
  stop-opacity: 0;
}

.znwvjy5yx {
  stop-color: var(--svg-color--ff5c88, #FF5C88);
}

.zqff1532o {
  stop-color: var(--svg-color--201524, #201524);
}

</style>
