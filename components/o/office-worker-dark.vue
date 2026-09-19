<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#itwjuGd)" class="rcayb3bkj"/><path fill="url(#iE4zvIc)" class="rcayb3bkj"/><g filter="url(#i6xf9Gd)"><path class="n7nofjg9b"/></g><g filter="url(#iTO9ytd)"><path class="b8sq8rb4i"/></g><path fill="url(#iHGciyV)" class="tdf3qncxe"/><path fill="url(#ifOjzqb)" class="tdf3qncxe"/><path fill="url(#irxNHre)" class="tdf3qncxe"/><path fill="url(#iSmSTdd)" class="ek7dch7bb"/><path fill="url(#i7N7roe)" class="ek7dch7bb"/><g filter="url(#iQhLMte)"><path fill="url(#it0KOYd)" class="vdnfm5b6h"/><path fill="url(#i4IGm8B)" class="vdnfm5b6h"/><path fill="url(#ibP8GKd)" class="vdnfm5b6h"/></g><path fill="url(#iVbnfvc)" class="vdnfm5b6h"/><path fill="url(#i9FzJAe)" class="vdnfm5b6h"/><g filter="url(#iFf14je)"><path fill="url(#iBa4Lqe)" class="e7312lgsb"/></g><g filter="url(#iQllVJb)"><path class="iz1d5e4ym"/><path fill="url(#iM3cW9c)" class="z0r2z4ozn"/></g><path fill="url(#iZrt83c)" class="opufzcbxv"/><path fill="url(#iFA624c)" class="opufzcbxv"/><path fill="url(#ipKarje)" class="i6e4ojbas"/><path fill="url(#i8RQtVc)" class="gbna_dbvj"/><path fill="url(#iphSgve)" class="gbna_dbvj"/><path fill="url(#i7uaRbe)" class="gbna_dbvj"/><path fill="url(#iXOpeJb)" class="qizb_vekv"/><path fill="url(#itbD3Pe)" class="vfgs--nyf"/><path fill="url(#i2X4ycc)" class="ysczrvbme"/><g filter="url(#iETAGRI)"><path fill="url(#iDK4yCb)" class="towujmbdp"/></g><path fill="url(#iRFn8Vd)" class="towujmbdp"/><path fill="url(#ixstGzd)" class="towujmbdp"/><path fill="url(#iFZtBNc)" class="towujmbdp"/><path fill="url(#ipZHgOe)" class="towujmbdp"/><path fill="url(#i8sVBGd)" class="towujmbdp"/><path fill="url(#i8Xqr6c)" class="towujmbdp"/><path fill="url(#iYKKWMy)" class="towujmbdp"/><path fill="url(#iq14JQb)" class="towujmbdp"/><g filter="url(#iHSNkue)"><path class="iqsab6bwn"/></g><g filter="url(#iVWiN7c)"><path class="z6710lbls"/><path fill="url(#iJEmYhd)" class="ofpu2658u"/><path fill="url(#iZJ0h8d)" class="ofpu2658u"/><path fill="url(#ircz3Ud)" class="ofpu2658u"/><path fill="url(#iFicEMe)" class="ofpu2658u"/><path fill="url(#itNp8Lf)" class="ofpu2658u"/></g><g filter="url(#iVnuaqd)"><path stroke="url(#iMVvDle)" class="pjr4h6igj"/></g><path fill="url(#iCpPHKe)" class="ju5xortti"/><g filter="url(#izrchpe)"><path fill="url(#i1JeUId)" class="wa6xe0kuv"/><path fill="url(#iXjYTfc)" class="wa6xe0kuv"/><path fill="url(#iyK5WMd)" class="wa6xe0kuv"/><path fill="url(#iY9DRTd)" class="wa6xe0kuv"/><path fill="url(#iBTTw1d)" class="wa6xe0kuv"/></g><g filter="url(#idnOdid)"><path class="ikc89k2zb"/></g><g filter="url(#i55AqKd)"><path class="i7axa40rj"/></g><g filter="url(#ihpqSOe)"><path class="q8ssiqb4v"/><path fill="url(#iQPSPsd)" class="if9m-_jjq"/><path fill="url(#io9B8De)" class="if9m-_jjq"/></g><g filter="url(#iefN7Uc)"><path class="drz00ybcc"/><path fill="url(#iNHKRSL)" class="zun7cwsfu"/></g><path class="l86bbzbif"/><path fill="url(#i2PphLd)" class="e_k_r1b6b"/><path class="tttj9obbz"/><g filter="url(#ilQk24b)"><path class="nc0f44b_n"/><path fill="url(#ibJXotc)" class="xvb2xjtdz"/></g><g filter="url(#iSJoxub)"><path fill="url(#iqXBaGd)" class="f774xw8rh"/></g><path class="mb4wf7bdl"/><path fill="url(#ifCONjP)" class="zgremsb0w"/><path class="yrfmvob0h"/><g filter="url(#iuwX5Ii)"><path fill="url(#ivy9vTr)" class="fdo21xdaw"/></g><g filter="url(#i19Oedd)"><ellipse transform="rotate(-27.914 13.532 9.906)" class="wnbqysako"/><ellipse fill="url(#iCgFc5b)" transform="rotate(-27.914 13.532 9.906)" class="qf6e74eta"/></g><path fill="url(#ild0WXd)" class="h-tzeetfe"/><path fill="url(#iWbma7b)" class="h-tzeetfe"/><path fill="url(#i1Bx9Fe)" class="h-tzeetfe"/><path fill="url(#iG1bbtc)" class="h-tzeetfe"/><path fill="url(#iVrF2pc)" class="ovkw86iay"/><path fill="url(#iyZFVmb)" class="ovkw86iay"/><g filter="url(#iBjSuVd)"><path fill="url(#iGxqFxA)" class="nrkgi2e5x"/></g><g filter="url(#iHhejSc)"><path fill="url(#iwpCArc)" class="bln75_hlz"/></g><g filter="url(#i7DYwVb)"><path class="kvqehyhai"/></g><g filter="url(#igPSQ2d)"><path class="sd67c4b8e"/></g><g filter="url(#iWyUT6b)"><path class="ymkg85dzi"/></g><defs><radialGradient id="iE4zvIc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -16.4313 6.37009 0 22.995 25.412)" gradientUnits="userSpaceOnUse"><stop offset=".156" class="m5bm-ccxd"/><stop offset="1" class="q8ootib3t"/></radialGradient><radialGradient id="iHGciyV" cx="0" cy="0" r="1" gradientTransform="matrix(0 10.1215 -4.59696 0 16 22.984)" gradientUnits="userSpaceOnUse"><stop offset=".397" class="wdy63qb5p"/><stop offset="1" class="gkzmut59n"/></radialGradient><radialGradient id="iSmSTdd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -10.3135 1.68433 0 25 29.919)" gradientUnits="userSpaceOnUse"><stop class="omh3jbc5e"/><stop offset="1" class="g1k32m_rh"/></radialGradient><radialGradient id="ibP8GKd" cx="0" cy="0" r="1" gradientTransform="rotate(126.18 2.723 11.627)scale(2.59394 3.59462)" gradientUnits="userSpaceOnUse"><stop class="yfhz1ybyq"/><stop offset="1" class="kyt4h2bsk"/></radialGradient><radialGradient id="i9FzJAe" cx="0" cy="0" r="1" gradientTransform="matrix(1.09375 -.3125 .15357 .53751 11.395 19.675)" gradientUnits="userSpaceOnUse"><stop offset=".241" class="som6k-b6q"/><stop offset="1" class="pc2b66ykc"/></radialGradient><radialGradient id="iZrt83c" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.75 -4.3769 0 16 18.433)" gradientUnits="userSpaceOnUse"><stop offset=".362" class="ft6yvtbqk"/><stop offset="1" class="i_25dj3ib"/></radialGradient><radialGradient id="iFA624c" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.1875 6.81546 0 16 20.93)" gradientUnits="userSpaceOnUse"><stop offset=".533" class="kx98i3bkm"/><stop offset=".876" class="mf716dhmi"/></radialGradient><radialGradient id="i8RQtVc" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.8125 -3.45478 0 15.983 21.324)" gradientUnits="userSpaceOnUse"><stop offset=".006" class="lv0iykbih"/><stop offset=".94" class="s3tb_6b2n"/></radialGradient><radialGradient id="iXOpeJb" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.48828 -3.72875 0 16.03 17.18)" gradientUnits="userSpaceOnUse"><stop offset=".272" class="spf0krb0n"/><stop offset="1" class="u-xq04bhh"/></radialGradient><radialGradient id="itbD3Pe" cx="0" cy="0" r="1" gradientTransform="rotate(69.657 1.846 20.834)scale(2.15388 2.55864)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="rra4r9bnq"/><stop offset="1" class="pft2s7y0a"/></radialGradient><radialGradient id="i2X4ycc" cx="0" cy="0" r="1" gradientTransform="matrix(1.47646 .46402 -1.43155 4.555 9.929 12.35)" gradientUnits="userSpaceOnUse"><stop class="gg1n47rtb"/><stop offset=".746" class="q53v6mhsp"/></radialGradient><radialGradient id="iDK4yCb" cx="0" cy="0" r="1" gradientTransform="matrix(-5.22785 0 0 -9.24802 18.793 10.918)" gradientUnits="userSpaceOnUse"><stop class="k53yjlbth"/><stop offset="1" class="ahguepbtf"/></radialGradient><radialGradient id="ixstGzd" cx="0" cy="0" r="1" gradientTransform="matrix(0 12.4205 -10.2856 0 16.025 4.943)" gradientUnits="userSpaceOnUse"><stop offset=".603" class="xdvo8i67g"/><stop offset=".752" class="ce5p2kror"/><stop offset="1" class="urxzjr7gr"/></radialGradient><radialGradient id="iFZtBNc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.14835 1.42108 0 18.432 9.606)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="asp-974pn"/><stop offset="1" class="l2dudh2nh"/></radialGradient><radialGradient id="ipZHgOe" cx="0" cy="0" r="1" gradientTransform="rotate(-89.794 11.686 -2.041)scale(1.09429 1.19084)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="ww86j5--q"/><stop offset="1" class="mfkgssbjj"/></radialGradient><radialGradient id="i8sVBGd" cx="0" cy="0" r="1" gradientTransform="matrix(-8.49599 .5363 -1.37 -21.703 19.418 11.906)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="o-j_7gbpq"/><stop offset="1" class="j-n0q842a"/></radialGradient><radialGradient id="i8Xqr6c" cx="0" cy="0" r="1" gradientTransform="matrix(4.073 -2.6483 .96946 1.491 10.518 6.593)" gradientUnits="userSpaceOnUse"><stop offset=".38" class="xjcxgac6b"/><stop offset="1" class="psn4zabca"/></radialGradient><radialGradient id="iYKKWMy" cx="0" cy="0" r="1" gradientTransform="matrix(-.23467 2.49744 -.99833 -.0938 21.53 8)" gradientUnits="userSpaceOnUse"><stop offset=".245" class="x73tbcc6t"/><stop offset="1" class="sbhjtg7pq"/></radialGradient><radialGradient id="iq14JQb" cx="0" cy="0" r="1" gradientTransform="rotate(121.159 7.531 8.161)scale(3.36898 2.78137)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="f28ypccjc"/><stop offset="1" class="zkb-swu-c"/></radialGradient><radialGradient id="iZJ0h8d" cx="0" cy="0" r="1" gradientTransform="matrix(0 .2441 -.76718 0 16.451 12.28)" gradientUnits="userSpaceOnUse"><stop class="txgsuxr-c"/><stop offset="1" class="a4rldd3-z"/></radialGradient><radialGradient id="iFicEMe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.52115 .69743 -1.12083 -2.4446 16.568 11.71)" gradientUnits="userSpaceOnUse"><stop offset=".714" class="p8isx8b7k"/><stop offset="1" class="w37r5utea"/></radialGradient><radialGradient id="iCpPHKe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.72074 2.89971 0 15.985 14.458)" gradientUnits="userSpaceOnUse"><stop class="w189cfbhy"/><stop offset="1" class="z5a_p6x5j"/></radialGradient><radialGradient id="iXjYTfc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.50133 8.85445 0 10.755 8.026)" gradientUnits="userSpaceOnUse"><stop offset=".536" class="ibt06e6rm"/><stop offset="1" class="k45xjwbmq"/></radialGradient><radialGradient id="iyK5WMd" cx="0" cy="0" r="1" gradientTransform="rotate(-87.401 15.308 -6.238)scale(2.51513 4.45631)" gradientUnits="userSpaceOnUse"><stop class="c98z413ze"/><stop offset="1" class="ovvtmacpn"/></radialGradient><radialGradient id="iY9DRTd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.35883 -1.5514 1.13881 -1.7315 20.092 3.06)" gradientUnits="userSpaceOnUse"><stop class="wyv1gnbxf"/><stop offset="1" class="z6d-f52gr"/></radialGradient><radialGradient id="iBTTw1d" cx="0" cy="0" r="1" gradientTransform="matrix(.90511 1.475 -3.4154 2.09582 15.08 1.468)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="qco-2_b3r"/><stop offset="1" class="zwo50zm6y"/></radialGradient><radialGradient id="iQPSPsd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.20113 0 0 -.81692 16.238 3.727)" gradientUnits="userSpaceOnUse"><stop class="axstwemrb"/><stop offset="1" class="ez41_pbnb"/></radialGradient><radialGradient id="io9B8De" cx="0" cy="0" r="1" gradientTransform="rotate(-57.724 12.235 -5.74)scale(6.02662 6.67688)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="hnw0p1utu"/><stop offset=".311" class="dwl_ftd7p"/><stop offset="1" class="fch_lgr5q"/></radialGradient><radialGradient id="iNHKRSL" cx="0" cy="0" r="1" gradientTransform="rotate(6.667 -43.197 155.264)scale(3.27033 1.36922)" gradientUnits="userSpaceOnUse"><stop class="unyhdjbdq"/><stop offset="1" class="w0a4mmrgb"/></radialGradient><radialGradient id="i2PphLd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.2905 0 18.167 10.002)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="ibJXotc" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 11.44 .65)scale(.37829 .52081)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ifCONjP" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81136 -1.29056 0 13.803 10.002)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="iCgFc5b" cx="0" cy="0" r="1" gradientTransform="matrix(-.00774 -.49408 .59392 -.0093 13.517 10.221)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iWbma7b" cx="0" cy="0" r="1" gradientTransform="matrix(.62855 2.24328 -2.14025 .59968 20.603 10.016)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="xbtbagqno"/><stop offset="1" class="epf-qq6ay"/></radialGradient><radialGradient id="i1Bx9Fe" cx="0" cy="0" r="1" gradientTransform="matrix(.78778 -1.0811 .90618 .66032 20.963 10.56)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="akw4fybhj"/><stop offset="1" class="qoxj776_o"/></radialGradient><radialGradient id="iG1bbtc" cx="0" cy="0" r="1" gradientTransform="matrix(.587 -1.55042 2.07158 .7843 21.077 10.733)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="c5e-i-5dw"/><stop offset=".966" class="szee5wb8m"/></radialGradient><radialGradient id="iyZFVmb" cx="0" cy="0" r="1" gradientTransform="rotate(101.248 1.182 9.492)scale(2.11668 2.08089)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="ay2574bqt"/><stop offset="1" class="g1u_xnbmn"/></radialGradient><radialGradient id="iGxqFxA" cx="0" cy="0" r="1" gradientTransform="matrix(-.91648 .1573 -.06938 -.40422 11.07 10.659)" gradientUnits="userSpaceOnUse"><stop class="c4l15nbte"/><stop offset="1" class="r95ztqgly"/></radialGradient><linearGradient id="itwjuGd" x1="16" x2="16" y1="16.23" y2="31.168" gradientUnits="userSpaceOnUse"><stop class="hac9w68gp"/><stop offset="1" class="u61ykmvtc"/></linearGradient><linearGradient id="ifOjzqb" x1="18.903" x2="17.059" y1="25.23" y2="25.23" gradientUnits="userSpaceOnUse"><stop class="ugh29hhiz"/><stop offset="1" class="knib4pb5u"/></linearGradient><linearGradient id="irxNHre" x1="15.591" x2="15.669" y1="17.777" y2="21.668" gradientUnits="userSpaceOnUse"><stop class="ft2atdbel"/><stop offset="1" class="r8964-bmu"/></linearGradient><linearGradient id="i7N7roe" x1="23" x2="23.744" y1="29.406" y2="29.382" gradientUnits="userSpaceOnUse"><stop offset=".276" class="alwwvg18b"/><stop offset="1" class="r8-nbsf4i"/></linearGradient><linearGradient id="it0KOYd" x1="11.902" x2="11.902" y1="16.009" y2="29.909" gradientUnits="userSpaceOnUse"><stop class="j-er45bzw"/><stop offset=".524" class="iwz00abqx"/></linearGradient><linearGradient id="i4IGm8B" x1="13.671" x2="13.05" y1="22.468" y2="22.468" gradientUnits="userSpaceOnUse"><stop class="recxkftoe"/><stop offset="1" class="btkjyionj"/></linearGradient><linearGradient id="iVbnfvc" x1="11.902" x2="12.839" y1="25.885" y2="25.483" gradientUnits="userSpaceOnUse"><stop offset=".196" class="yqlqjsfuk"/><stop offset="1" class="c8t-c_brq"/></linearGradient><linearGradient id="iBa4Lqe" x1="15.988" x2="15.988" y1="18.902" y2="20.887" gradientUnits="userSpaceOnUse"><stop offset=".006" class="mu96iuqwe"/><stop offset="1" class="p-sb3ibac"/></linearGradient><linearGradient id="iM3cW9c" x1="18.71" x2="20.111" y1="21.516" y2="21.516" gradientUnits="userSpaceOnUse"><stop offset=".093" class="fxp5v2b6t"/><stop offset="1" class="zm9c_pbne"/></linearGradient><linearGradient id="ipKarje" x1="9.452" x2="7.02" y1="23.926" y2="23.926" gradientUnits="userSpaceOnUse"><stop class="rpmno-b9y"/><stop offset="1" class="a9ts2kezv"/></linearGradient><linearGradient id="iphSgve" x1="14.606" x2="14.899" y1="24.789" y2="24.828" gradientUnits="userSpaceOnUse"><stop class="jybxgogov"/><stop offset="1" class="rop63gbyj"/></linearGradient><linearGradient id="i7uaRbe" x1="17.411" x2="17.012" y1="24.605" y2="24.652" gradientUnits="userSpaceOnUse"><stop class="jybxgogov"/><stop offset="1" class="rop63gbyj"/></linearGradient><linearGradient id="iRFn8Vd" x1="21.142" x2="16.79" y1="12.604" y2="12.604" gradientUnits="userSpaceOnUse"><stop class="k53yjlbth"/><stop offset="1" class="prh5swccd"/></linearGradient><linearGradient id="iJEmYhd" x1="16.823" x2="15.985" y1="11.593" y2="11.628" gradientUnits="userSpaceOnUse"><stop offset=".36" class="d8gqn2snf"/><stop offset="1" class="oz5jd4bmy"/></linearGradient><linearGradient id="ircz3Ud" x1="15.985" x2="15.985" y1="12.732" y2="12.268" gradientUnits="userSpaceOnUse"><stop class="abx50lnlm"/><stop offset="1" class="u-2msu4yh"/></linearGradient><linearGradient id="itNp8Lf" x1="15.985" x2="15.985" y1="9.778" y2="10.574" gradientUnits="userSpaceOnUse"><stop class="o2r2q6blp"/><stop offset="1" class="kh_x-hbqh"/></linearGradient><linearGradient id="iMVvDle" x1="14.783" x2="15.102" y1="14.303" y2="13.469" gradientUnits="userSpaceOnUse"><stop class="ob3l4g_ys"/><stop offset="1" class="fglza-d-f"/></linearGradient><linearGradient id="i1JeUId" x1="22.837" x2="11.225" y1="5.256" y2="5.256" gradientUnits="userSpaceOnUse"><stop class="l1vex1b6a"/><stop offset="1" class="kydculhfm"/></linearGradient><linearGradient id="iqXBaGd" x1="18.945" x2="18.631" y1="10.056" y2="10.249" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ivy9vTr" x1="14.547" x2="14.233" y1="10.056" y2="10.249" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ild0WXd" x1="22.421" x2="21.215" y1="10.083" y2="12.259" gradientUnits="userSpaceOnUse"><stop class="lwf47ccyr"/><stop offset="1" class="bmcblacal"/></linearGradient><linearGradient id="iVrF2pc" x1="10.135" x2="11.594" y1="10.787" y2="10.659" gradientUnits="userSpaceOnUse"><stop class="jrlin1f0e"/><stop offset="1" class="zzkrmpd6m"/></linearGradient><linearGradient id="iwpCArc" x1="21.401" x2="21.401" y1="9.701" y2="11.604" gradientUnits="userSpaceOnUse"><stop class="q3b-p60-b"/><stop offset="1" class="v3ih9bcyp"/></linearGradient><filter id="i6xf9Gd" width="6.556" height="14.595" x="9.212" y="15.766" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2093" stdDeviation=".5"/></filter><filter id="iTO9ytd" width="3.95" height="13.362" x="17.96" y="16.244" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2093" stdDeviation=".375"/></filter><filter id="iQhLMte" width="2.897" height="14" x="10.503" y="16.009" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.403922 0 0 0 0 0.368627 0 0 0 0 0.494118 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2093"/></filter><filter id="iFf14je" width="2.734" height="2.883" x="14.624" y="18.146" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.156863 0 0 0 0 0.0980392 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2093"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.156863 0 0 0 0 0.0980392 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2093" result="effect2_innerShadow_4002_2093"/></filter><filter id="iQllVJb" width="2.902" height="14.05" x="18.61" y="15.959" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.415686 0 0 0 0 0.584314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2093"/></filter><filter id="iETAGRI" width="11.22" height="12.542" x="10.922" y="4.748" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.333333 0 0 0 0 0.270588 0 0 0 0 0.258824 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2093"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.145098 0 0 0 0 0.0705882 0 0 0 0 0.0745098 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2093" result="effect2_innerShadow_4002_2093"/></filter><filter id="iHSNkue" width="3.747" height="4.9" x="13.97" y="9.094" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2093" stdDeviation=".5"/></filter><filter id="iVWiN7c" width="2.277" height="3.3" x="14.847" y="9.698" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2093" stdDeviation=".1"/></filter><filter id="iVnuaqd" width="3.718" height="1.573" x="14.126" y="13.219" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2093" stdDeviation=".05"/></filter><filter id="izrchpe" width="12.873" height="8.356" x="9.549" y="1.571" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.137255 0 0 0 0 0.0901961 0 0 0 0 0.145098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2093"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0784314 0 0 0 0 0.0352941 0 0 0 0 0.0470588 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2093" result="effect2_innerShadow_4002_2093"/></filter><filter id="idnOdid" width="2.339" height="1.19" x="17.575" y="7.235" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0588235 0 0 0 0 0.054902 0 0 0 0 0.0588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2093"/></filter><filter id="i55AqKd" width="2.339" height="1.176" x="12.318" y="7.249" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0588235 0 0 0 0 0.054902 0 0 0 0 0.0588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2093"/></filter><filter id="ihpqSOe" width="6.734" height="5.992" x="9.904" y="2.66" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.286275 0 0 0 0 0.243137 0 0 0 0 0.227451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2093"/><feGaussianBlur result="effect2_foregroundBlur_4002_2093" stdDeviation=".125"/></filter><filter id="iefN7Uc" width="6.362" height="5.736" x="15.826" y="3.084" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.305882 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2093"/><feGaussianBlur result="effect2_foregroundBlur_4002_2093" stdDeviation=".125"/></filter><filter id="ilQk24b" width=".787" height=".696" x="17.433" y="9.562" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2093" stdDeviation=".05"/></filter><filter id="iSJoxub" width=".891" height=".913" x="18.273" y="9.637" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2093" stdDeviation=".1"/></filter><filter id="iuwX5Ii" width=".986" height="1.04" x="13.83" y="9.574" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2093" stdDeviation=".1"/></filter><filter id="i19Oedd" width=".913" height=".705" x="13.075" y="9.554" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2093" stdDeviation=".05"/></filter><filter id="iBjSuVd" width="1.329" height="2.379" x="9.904" y="9.47" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2093" stdDeviation=".125"/></filter><filter id="iHhejSc" width="1.947" height="2.903" x="20.428" y="9.201" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2093" stdDeviation=".25"/></filter><filter id="i7DYwVb" width="2.405" height="1.16" x="12.237" y="7.324" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2093" stdDeviation=".125"/></filter><filter id="igPSQ2d" width="2.405" height="1.16" x="17.516" y="7.278" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2093" stdDeviation=".125"/></filter><filter id="iWyUT6b" width="5.266" height="3.005" x="16.864" y="3.603" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2093" stdDeviation=".375"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:office-worker-dark" /></template>
<style>
.a4rldd3-z {
  stop-color: var(--svg-color--685554, #685554);
  stop-opacity: 0;
}

.a9ts2kezv {
  stop-color: var(--svg-color--584a7e, #584A7E);
  stop-opacity: 0;
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

.alwwvg18b {
  stop-color: var(--svg-color--504176, #504176);
}

.asp-974pn {
  stop-color: var(--svg-color--432728, #432728);
}

.axstwemrb {
  stop-color: var(--svg-color--423c3f, #423C3F);
}

.ay2574bqt {
  stop-color: var(--svg-color--301929, #301929);
  stop-opacity: 0;
}

.b8sq8rb4i {
  fill: var(--svg-color--463d68, #463D68);
  d: path("m20.905 21.1l-1.19-.828a.23.23 0 0 1 .166-.393h.919a.252.252 0 0 0 .227-.359l-1.076-2.29a8 8 0 0 0-.646-.236h-.595v11.861l2.404-6.872a.85.85 0 0 0-.21-.883");
}

.bbyb_mbsk {
  stop-color: var(--svg-color--664842, #664842);
}

.bln75_hlz {
  d: path("M20.928 11.605q.059-.953.11-1.904a.956.956 0 0 1-.11 1.903");
}

.bmcblacal {
  stop-color: var(--svg-color--492f32, #492F32);
}

.btkjyionj {
  stop-color: var(--svg-color--553a63, #553A63);
  stop-opacity: 0;
}

.c4l15nbte {
  stop-color: var(--svg-color--2c1d22, #2C1D22);
}

.c5e-i-5dw {
  stop-color: var(--svg-color--361c1e, #361C1E);
  stop-opacity: 0;
}

.c8t-c_brq {
  stop-color: var(--svg-color--594c7d, #594C7D);
  stop-opacity: 0;
}

.c98z413ze {
  stop-color: var(--svg-color--4f4d4d, #4F4D4D);
}

.ce5p2kror {
  stop-color: var(--svg-color--3d2032, #3D2032);
  stop-opacity: 0.038;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.d8gqn2snf {
  stop-color: var(--svg-color--66514e, #66514E);
}

.drz00ybcc {
  fill: var(--svg-color--1f151b, #1F151B);
  d: path("m21.198 8.57l-.03-.632c-.01-.763-.64-1.393-1.405-1.425h-1.4a2.42 2.42 0 0 1-2.124-1.26s-.058-.135-.12-.368c-.256-.97.671-1.712 1.656-1.521c.973.189 2.082.517 2.902 1.051c1.745 1.138 1.44 3.189.52 4.155");
}

.dwl_ftd7p {
  stop-color: var(--svg-color--1c0c20, #1C0C20);
}

.e_k_r1b6b {
  d: path("M18.17 9.525a.893.893 0 0 1 .86 1.128h-1.725a.896.896 0 0 1 .864-1.128");
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e7312lgsb {
  d: path("m16.01 18.246l-1.24 1.204a.15.15 0 0 0-.033.168l.547 1.26c.04.092.13.15.23.15h.952c.1 0 .19-.059.23-.15l.55-1.28a.15.15 0 0 0-.033-.167z");
}

.ek7dch7bb {
  d: path("M23 17.937v11.982h4v-3.5a10.98 10.98 0 0 0-4-8.483");
}

.epf-qq6ay {
  stop-color: var(--svg-color--301924, #301924);
}

.ez41_pbnb {
  stop-color: var(--svg-color--423c3f, #423C3F);
  stop-opacity: 0;
}

.f28ypccjc {
  stop-color: var(--svg-color--534445, #534445);
}

.f774xw8rh {
  d: path("M18.964 10.3a.84.84 0 0 0-.231-.463l-.26.286l.117.228z");
}

.fch_lgr5q {
  stop-color: var(--svg-color--1c0c20, #1C0C20);
  stop-opacity: 0;
}

.fdo21xdaw {
  d: path("M14.617 10.313c0-.289-.235-.481-.298-.54l-.289.28l.178.361z");
}

.fglza-d-f {
  stop-color: var(--svg-color--40222d, #40222D);
  stop-opacity: 0;
}

.ft2atdbel {
  stop-color: var(--svg-color--877f93, #877F93);
}

.ft5dv1b6b {
  fill: none;
}

.ft6yvtbqk {
  stop-color: var(--svg-color--cac3d3, #CAC3D3);
}

.fxp5v2b6t {
  stop-color: var(--svg-color--453d68, #453D68);
}

.g1k32m_rh {
  stop-color: var(--svg-color--6d6193, #6D6193);
}

.g1u_xnbmn {
  stop-color: var(--svg-color--301929, #301929);
}

.gbna_dbvj {
  d: path("M15.505 21.029a.25.25 0 0 0-.247.212l-1.328 8.668h4.11l-1.318-8.668a.25.25 0 0 0-.247-.212z");
}

.gg1n47rtb {
  stop-color: var(--svg-color--463c39, #463C39);
}

.gkzmut59n {
  stop-color: var(--svg-color--a89cb3, #A89CB3);
}

.h-tzeetfe {
  d: path("M20.907 12.26q.1-1.597.185-3.192a1.61 1.61 0 0 1-.185 3.191");
}

.hac9w68gp {
  stop-color: var(--svg-color--534973, #534973);
}

.hnw0p1utu {
  stop-color: var(--svg-color--0b0306, #0B0306);
}

.i_25dj3ib {
  stop-color: var(--svg-color--a093a3, #A093A3);
}

.i6e4ojbas {
  d: path("M7.032 29.919H8.97V17.955a11 11 0 0 0-3.656 5.842a11 11 0 0 0-.304 2.632l.02 3.49z");
}

.i7axa40rj {
  fill: var(--svg-color--202020, #202020);
  d: path("M12.574 7.83a2.77 2.77 0 0 1 1.739-.36a.277.277 0 1 1-.067.55a2.22 2.22 0 0 0-1.387.286a1 1 0 0 0-.092.06l-.002.001a.277.277 0 0 1-.34-.438z");
}

.ibt06e6rm {
  stop-color: var(--svg-color--3e3433, #3E3433);
}

.if9m-_jjq {
  d: path("m16.218 5.303l-.067-.137a.66.66 0 0 0-.615-.418h-1.273c-1.845 0-3.341 1.512-3.341 3.379v.275c-.34-.259-.768-.805-.768-1.688c0-1.072.782-1.613 1.28-1.959c.141-.098.26-.18.331-.253l.1-.105c.35-.37.972-1.031 2.06-1.32a5.5 5.5 0 0 1 1.507-.165c.473.011.806.42.806.892V5.29z");
}

.ikc89k2zb {
  fill: var(--svg-color--202020, #202020);
  d: path("M19.718 7.939a1.85 1.85 0 0 0-.687-.412c-.305-.096-.686-.121-1.213-.057a.277.277 0 1 0 .067.55c.482-.058.776-.028.98.036c.197.063.332.164.489.3a.277.277 0 0 0 .364-.417");
}

.iqsab6bwn {
  fill: var(--svg-color--331e24, #331E24);
  d: path("m15.584 10.4l-.591 1.838c-.101.378.141.756.484.756h.732c.343 0 .585-.384.485-.756l-.495-1.838c-.106-.408-.504-.408-.615 0");
}

.iwz00abqx {
  stop-color: var(--svg-color--5f5289, #5F5289);
}

.iz1d5e4ym {
  fill: var(--svg-color--605890, #605890);
  d: path("m21.22 21.039l-1.36-1.33a.262.262 0 0 1 .19-.45h1.05c.21 0 .35-.22.26-.41l-1.23-2.62c-.24-.1-.49-.19-.74-.27h-.68v13.95l2.75-7.86c.12-.36.03-.75-.24-1.01");
}

.j-er45bzw {
  stop-color: var(--svg-color--544a76, #544A76);
}

.j-n0q842a {
  stop-color: var(--svg-color--564440, #564440);
}

.jrlin1f0e {
  stop-color: var(--svg-color--372425, #372425);
}

.ju5xortti {
  d: path("M15.985 13.815c-.507 0-.984-.12-1.385-.328c-.137-.07-.285.084-.198.208c.335.508.918.846 1.583.846s1.249-.338 1.583-.846c.087-.129-.06-.278-.198-.209a3 3 0 0 1-1.385.329");
}

.jybxgogov {
  stop-color: var(--svg-color--2b1b3a, #2B1B3A);
}

.k45xjwbmq {
  stop-color: var(--svg-color--3e3433, #3E3433);
  stop-opacity: 0;
}

.k53yjlbth {
  stop-color: var(--svg-color--563b38, #563B38);
}

.kh_x-hbqh {
  stop-color: var(--svg-color--4b302a, #4B302A);
  stop-opacity: 0;
}

.knib4pb5u {
  stop-color: var(--svg-color--c7bcd2, #C7BCD2);
  stop-opacity: 0;
}

.kvqehyhai {
  stroke: var(--svg-color--353535, #353535);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M12.612 8.11c.257-.185.898-.51 1.655-.382");
}

.kx98i3bkm {
  stop-color: var(--svg-color--837a8d, #837A8D);
  stop-opacity: 0;
}

.kydculhfm {
  stop-color: var(--svg-color--272127, #272127);
}

.kyt4h2bsk {
  stop-color: var(--svg-color--3c2e57, #3C2E57);
  stop-opacity: 0;
}

.l1vex1b6a {
  stop-color: var(--svg-color--443d40, #443D40);
}

.l2dudh2nh {
  stop-color: var(--svg-color--432728, #432728);
  stop-opacity: 0;
}

.l86bbzbif {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.376 9.253c.653 0 1.205.45 1.355 1.06a.274.274 0 0 1-.268.34h-2.23a.23.23 0 0 1-.228-.272a1.4 1.4 0 0 1 1.371-1.128");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lv0iykbih {
  stop-color: var(--svg-color--56406d, #56406D);
}

.lwf47ccyr {
  stop-color: var(--svg-color--62504f, #62504F);
}

.m5bm-ccxd {
  stop-color: var(--svg-color--7b74a6, #7B74A6);
}

.mb4wf7bdl {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.594 9.253c-.653 0-1.204.45-1.355 1.06c-.044.174.09.34.268.34h2.231a.23.23 0 0 0 .228-.272a1.4 1.4 0 0 0-1.372-1.128");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mf716dhmi {
  stop-color: var(--svg-color--544a5f, #544A5F);
}

.mfkgssbjj {
  stop-color: var(--svg-color--361e27, #361E27);
  stop-opacity: 0;
}

.mu96iuqwe {
  stop-color: var(--svg-color--4b375e, #4B375E);
}

.n7nofjg9b {
  fill: var(--svg-color--41355c, #41355C);
  d: path("M13.419 16.768c-.513 0-1.296-.03-1.77.166l-1.38 2.724c-.09.19.06.41.27.41h1.55c.24 0 .35.29.19.45l-1.78 1.342c-.26.26-.36.65-.23 1l2.912 6.501l1.587-1.116l-1.34-11.477z");
}

.nc0f44b_n {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.104 9.714c.063.085-.07.189-.22.301c-.152.114-.264.193-.328.108c-.063-.085.008-.246.159-.359c.15-.113.325-.135.389-.05");
}

.nrkgi2e5x {
  d: path("M10.9 9.72a.956.956 0 0 0 .083 1.88a78 78 0 0 1-.083-1.88");
}

.o-j_7gbpq {
  stop-color: var(--svg-color--564440, #564440);
  stop-opacity: 0;
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

.ofpu2658u {
  d: path("m15.603 10.204l-.531 1.838c-.109.378.151.757.52.757h.786c.37 0 .63-.384.521-.757l-.531-1.838c-.114-.407-.646-.407-.765 0");
}

.omh3jbc5e {
  stop-color: var(--svg-color--776d9f, #776D9F);
}

.opufzcbxv {
  d: path("M16 14.976h-2.71v4.74c0 .31.36.49.61.29l2.1-1.393l2.1 1.393c.25.2.61.02.61-.29v-4.74z");
}

.ovkw86iay {
  d: path("M10.931 9.06a1.61 1.61 0 0 0 .139 3.2a78 78 0 0 1-.139-3.2");
}

.ovvtmacpn {
  stop-color: var(--svg-color--4f4d4d, #4F4D4D);
  stop-opacity: 0;
}

.oz5jd4bmy {
  stop-color: var(--svg-color--66514e, #66514E);
  stop-opacity: 0;
}

.p-sb3ibac {
  stop-color: var(--svg-color--483b55, #483B55);
}

.p8isx8b7k {
  stop-color: var(--svg-color--3e2b29, #3E2B29);
  stop-opacity: 0;
}

.pc2b66ykc {
  stop-color: var(--svg-color--4b3b6d, #4B3B6D);
  stop-opacity: 0;
}

.pft2s7y0a {
  stop-color: var(--svg-color--221c27, #221C27);
}

.pjr4h6igj {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M14.634 13.42a.23.23 0 0 0-.271.047a.21.21 0 0 0-.024.27c.349.528.956.88 1.646.88s1.297-.352 1.646-.88a.214.214 0 0 0-.024-.273a.23.23 0 0 0-.27-.044h-.001c-.39.203-.85.32-1.35.32a2.9 2.9 0 0 1-1.352-.32Z");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.prh5swccd {
  stop-color: var(--svg-color--563b38, #563B38);
  stop-opacity: 0;
}

.psn4zabca {
  stop-color: var(--svg-color--231112, #231112);
  stop-opacity: 0;
}

.q3b-p60-b {
  stop-color: var(--svg-color--4c3838, #4C3838);
}

.q53v6mhsp {
  stop-color: var(--svg-color--1b141e, #1B141E);
}

.q8ootib3t {
  stop-color: var(--svg-color--5f5490, #5F5490);
  stop-opacity: 0;
}

.q8ssiqb4v {
  fill: var(--svg-color--23181c, #23181C);
  d: path("m16.218 5.303l-.067-.137a.66.66 0 0 0-.615-.418h-1.273c-1.845 0-3.341 1.512-3.341 3.379v.275c-.34-.259-.768-.805-.768-1.688c0-1.072.782-1.613 1.28-1.959c.141-.098.26-.18.331-.253l.1-.105c.35-.37.972-1.031 2.06-1.32a5.5 5.5 0 0 1 1.507-.165c.473.011.806.42.806.892V5.29z");
}

.qco-2_b3r {
  stop-color: var(--svg-color--484646, #484646);
}

.qf6e74eta {
  cx: 13.532px;
  cy: 9.906px;
  rx: 0.39px;
  ry: 0.197px;
}

.qizb_vekv {
  d: path("M14.045 16.809c.02.213.205.69.746 1.054c.214.144 1.213.629 1.193.62c.156-.079.807-.3 1.284-.62c.54-.363.725-.84.746-1.054l-1.985-.954z");
}

.qoxj776_o {
  stop-color: var(--svg-color--351b1e, #351B1E);
  stop-opacity: 0;
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r8-nbsf4i {
  stop-color: var(--svg-color--504176, #504176);
  stop-opacity: 0;
}

.r8964-bmu {
  stop-color: var(--svg-color--877f93, #877F93);
  stop-opacity: 0;
}

.r95ztqgly {
  stop-color: var(--svg-color--271416, #271416);
}

.rcayb3bkj {
  d: path("M16 15.419c-6.08 0-11 4.92-11 11v3.5h22v-3.5c0-6.07-4.93-11-11-11");
}

.recxkftoe {
  stop-color: var(--svg-color--3e305b, #3E305B);
}

.rop63gbyj {
  stop-color: var(--svg-color--2b1b3a, #2B1B3A);
  stop-opacity: 0;
}

.rpmno-b9y {
  stop-color: var(--svg-color--41375c, #41375C);
}

.rra4r9bnq {
  stop-color: var(--svg-color--3c3b3c, #3C3B3C);
}

.s3tb_6b2n {
  stop-color: var(--svg-color--3d3247, #3D3247);
}

.sbhjtg7pq {
  stop-color: var(--svg-color--6b5b59, #6B5B59);
  stop-opacity: 0;
}

.sd67c4b8e {
  stroke: var(--svg-color--353535, #353535);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M19.546 8.063c-.257-.184-.897-.508-1.655-.381");
}

.som6k-b6q {
  stop-color: var(--svg-color--4b3b6d, #4B3B6D);
}

.spf0krb0n {
  stop-color: var(--svg-color--331b22, #331B22);
}

.szee5wb8m {
  stop-color: var(--svg-color--361c1e, #361C1E);
}

.tdf3qncxe {
  d: path("M18.71 16.039h-5.42v13.89h5.42z");
}

.towujmbdp {
  d: path("M11.16 13.683a3.916 3.916 0 0 0 3.886 3.406h1.886a3.916 3.916 0 0 0 3.886-3.406c.118-1.883.237-3.76.324-5.642a1.45 1.45 0 0 0-1.379-1.432h-1.4c-.955 0-1.82-.563-2.212-1.443a.66.66 0 0 0-.615-.418h-1.273c-1.845 0-3.341 1.512-3.341 3.379c0 1.86.116 3.69.238 5.556");
}

.tttj9obbz {
  fill: var(--svg-color--000, #000);
  d: path("M17.658 10.418a.51.51 0 0 1 .511-.512a.51.51 0 0 1 .455.747h-.905a.46.46 0 0 1-.06-.235");
}

.txgsuxr-c {
  stop-color: var(--svg-color--685554, #685554);
}

.u-2msu4yh {
  stop-color: var(--svg-color--3e2230, #3E2230);
  stop-opacity: 0;
}

.u-xq04bhh {
  stop-color: var(--svg-color--352121, #352121);
}

.u61ykmvtc {
  stop-color: var(--svg-color--584982, #584982);
}

.ugh29hhiz {
  stop-color: var(--svg-color--7a6c85, #7A6C85);
}

.unyhdjbdq {
  stop-color: var(--svg-color--200e25, #200E25);
}

.urxzjr7gr {
  stop-color: var(--svg-color--3e1744, #3E1744);
}

.v3ih9bcyp {
  stop-color: var(--svg-color--3e2724, #3E2724);
}

.vdnfm5b6h {
  d: path("M13.29 16.009h-.85c-.18.06-.36.13-.53.2l-1.27 2.69c-.09.19.06.41.27.41h1.05c.24 0 .35.29.19.45l-1.36 1.33c-.26.26-.36.65-.23 1l2.73 7.82h.01v-13.9z");
}

.vfgs--nyf {
  d: path("M20.847 12.168c.335-.01.649-.124.904-.308v.93c0 .894-.532 1.69-1.34 2.02a4.1 4.1 0 0 0 .345-1.18z");
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

.wa6xe0kuv {
  d: path("M20.84 4.276c.514.177.976.536 1.268 1.051A2.37 2.37 0 0 1 22 7.853a1.56 1.56 0 0 0-.27.875v1.188a1.7 1.7 0 0 0-.667-.269l.078-1.606a1.45 1.45 0 0 0-1.379-1.432h-1.4c-.955 0-1.82-.563-2.212-1.443a.66.66 0 0 0-.615-.418h-1.273c-1.845 0-3.341 1.512-3.341 3.379l.03 1.537a1.7 1.7 0 0 0-.72.264v-1.2a1.56 1.56 0 0 0-.27-.875a2.39 2.39 0 0 1-.143-2.446a2.35 2.35 0 0 1 1.3-1.126a2.68 2.68 0 0 0 1.383-1.11a2.325 2.325 0 0 1 2.89-.912a1.5 1.5 0 0 0 1.194 0c.281-.118.589-.188.913-.188c.843 0 1.58.456 1.988 1.132c.308.51.79.88 1.353 1.073");
}

.wdy63qb5p {
  stop-color: var(--svg-color--c6bbd1, #C6BBD1);
}

.wnbqysako {
  cx: 13.532px;
  cy: 9.906px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
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

.xdvo8i67g {
  stop-color: var(--svg-color--3d2031, #3D2031);
  stop-opacity: 0;
}

.xjcxgac6b {
  stop-color: var(--svg-color--231112, #231112);
}

.xvb2xjtdz {
  d: path("M18.104 9.714c.063.085-.07.189-.22.301c-.152.114-.264.193-.328.108c-.063-.085.008-.246.159-.359c.15-.113.325-.135.389-.05");
}

.yfhz1ybyq {
  stop-color: var(--svg-color--3c2e57, #3C2E57);
}

.ymkg85dzi {
  fill: var(--svg-color--504a4c, #504A4C);
  d: path("M20.178 5.32h-2.08a.483.483 0 1 1 .076-.961c.54.086 1.257.206 1.737.325c1.086.27 1.386.798 1.47 1.175a1.51 1.51 0 0 0-1.203-.539");
}

.yqlqjsfuk {
  stop-color: var(--svg-color--55477c, #55477C);
}

.yrfmvob0h {
  fill: var(--svg-color--000, #000);
  d: path("M14.312 10.418a.51.51 0 0 0-.51-.512a.51.51 0 0 0-.455.747h.905a.5.5 0 0 0 .06-.235");
}

.ysczrvbme {
  d: path("M11.124 12.168a1.64 1.64 0 0 1-.905-.308v.93c0 .894.533 1.69 1.341 2.02a4.1 4.1 0 0 1-.346-1.18z");
}

.z0r2z4ozn {
  d: path("m21.22 21.039l-1.36-1.33a.262.262 0 0 1 .19-.45h1.05c.21 0 .35-.22.26-.41l-1.23-2.62c-.24-.1-.49-.19-.74-.27h-.68v13.95l2.75-7.86c.12-.36.03-.75-.24-1.01");
}

.z5a_p6x5j {
  stop-color: var(--svg-color--290017, #290017);
}

.z6710lbls {
  fill: var(--svg-color--402929, #402929);
  d: path("m15.603 10.204l-.531 1.838c-.109.378.151.757.52.757h.786c.37 0 .63-.384.521-.757l-.531-1.838c-.114-.407-.646-.407-.765 0");
}

.z6d-f52gr {
  stop-color: var(--svg-color--5e5a5b, #5E5A5B);
  stop-opacity: 0;
}

.zgremsb0w {
  d: path("M13.801 9.525a.893.893 0 0 0-.86 1.128h1.724a1 1 0 0 0 .033-.235a.9.9 0 0 0-.897-.893");
}

.zkb-swu-c {
  stop-color: var(--svg-color--534445, #534445);
  stop-opacity: 0;
}

.zm9c_pbne {
  stop-color: var(--svg-color--625a91, #625A91);
  stop-opacity: 0;
}

.zun7cwsfu {
  d: path("m21.198 8.57l-.03-.632c-.01-.763-.64-1.393-1.405-1.425h-1.4a2.42 2.42 0 0 1-2.124-1.26s-.058-.135-.12-.368c-.256-.97.671-1.712 1.656-1.521c.973.189 2.082.517 2.902 1.051c1.745 1.138 1.44 3.189.52 4.155");
}

.zwo50zm6y {
  stop-color: var(--svg-color--484646, #484646);
  stop-opacity: 0;
}

.zzkrmpd6m {
  stop-color: var(--svg-color--281919, #281919);
}

</style>
