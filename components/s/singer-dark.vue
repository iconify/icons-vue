<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iGS1ARd)"><path class="dqa4_dciz"/><path fill="url(#ijs6MRb)" class="qd55obbpm"/></g><path fill="url(#iusfDlx)" class="c5q7122zr"/><path fill="url(#iVWeYuc)" class="c5q7122zr"/><path fill="url(#i1mlueb)" class="laenz-bql"/><path fill="url(#i3Sh0Me)" class="laenz-bql"/><path fill="url(#iRwJRdd)" class="wieq7abdc"/><path fill="url(#idWSGXe)" class="wieq7abdc"/><path fill="url(#i3rHTFb)" class="wieq7abdc"/><path fill="url(#iHEj4Hy)" class="wieq7abdc"/><path fill="url(#igVhnne)" class="yebmocc2p"/><path fill="url(#ioGO8Wc)" class="yebmocc2p"/><path fill="url(#iJmVmgb)" class="yebmocc2p"/><path fill="url(#iutyKpc)" class="yebmocc2p"/><path fill="url(#idKug7c)" class="yebmocc2p"/><path fill="url(#imWK0ae)" class="u5h71mb8p"/><path fill="url(#iFkg6vb)" class="ifmu2bbjb"/><path fill="url(#izb8H2b)" class="zc7yzq-8f"/><path fill="url(#ik2cKhe)" class="nzlkhptrb"/><path fill="url(#il3Oeir)" class="nzlkhptrb"/><path fill="url(#iMgWmrc)" class="nzlkhptrb"/><path fill="url(#i0zzLub)" class="nzlkhptrb"/><path fill="url(#isKPMTd)" class="ubrvwpbys"/><path fill="url(#ilIicsc)" class="ubrvwpbys"/><path fill="url(#iTohMAc)" class="bn25ibyvi"/><path fill="url(#ib4I5td)" class="bn25ibyvi"/><path fill="url(#iyulusd)" class="bn25ibyvi"/><path fill="url(#iqJGQcd)" class="bn25ibyvi"/><g filter="url(#iqJKIUc)"><path fill="url(#it2HJAe)" class="vsx0ybblj"/><path fill="url(#isMJFCe)" class="vsx0ybblj"/><path fill="url(#iRcFHzd)" class="vsx0ybblj"/></g><path fill="url(#ib01T2c)" class="mj7of5vyp"/><path fill="url(#iL5Bq5b)" class="mj7of5vyp"/><path fill="url(#iPzWPCc)" class="mj7of5vyp"/><g filter="url(#iyakMiK)"><path fill="url(#i55YfdB)" class="ijj3iu5hn"/></g><g filter="url(#iBqt8fb)"><circle fill="url(#imT8q9v)" class="gn190fg6k"/></g><g filter="url(#iwBIHQe)"><circle fill="url(#iLGoEPb)" class="ptdv5_kap"/></g><path fill="url(#ihHFTFe)" class="k-v83l39e"/><path fill="url(#iFNr8Xj)" class="zv7vnvb8h"/><g filter="url(#iV9Ajbd)"><path fill="url(#i7Rlxoc)" class="uyyuv9bgc"/></g><path fill="url(#i81GwYy)" class="uyyuv9bgc"/><path fill="url(#iaGI4jb)" class="uyyuv9bgc"/><path fill="url(#iWg5aPc)" class="uyyuv9bgc"/><path fill="url(#i1F1ecb)" class="uyyuv9bgc"/><path fill="url(#iRk9oCe)" class="uyyuv9bgc"/><path fill="url(#i6FcH6d)" class="uyyuv9bgc"/><path fill="url(#iZvKJpb)" class="uyyuv9bgc"/><path fill="url(#iqpkUwc)" class="uyyuv9bgc"/><path fill="url(#iq5cLqb)" class="uyyuv9bgc"/><g filter="url(#iPlNqob)"><path class="bs4j4xojh"/></g><g filter="url(#iLcve4b)"><path class="o80hv4hxf"/><path fill="url(#i9eieKb)" class="glk19gb1l"/><path fill="url(#iLJZqqd)" class="glk19gb1l"/><path fill="url(#izzeIab)" class="glk19gb1l"/><path fill="url(#iHz4g6b)" class="glk19gb1l"/><path fill="url(#i3o89Hb)" class="glk19gb1l"/></g><g filter="url(#iEOZvBc)"><path stroke="url(#iAo7N8b)" class="ika489brf"/></g><path fill="url(#i0qAbrb)" class="yk2-i9bly"/><g filter="url(#iGvc3Hc)"><path fill="url(#iDUOPge)" class="dn78wjc6c"/><path fill="url(#iLGRmve)" class="dn78wjc6c"/><path fill="url(#isnOVpd)" class="dn78wjc6c"/><path fill="url(#iMLOA3c)" class="dn78wjc6c"/><path fill="url(#i9uQ2nc)" class="dn78wjc6c"/></g><path fill="url(#iLsEcMd)" class="bfjow4buj"/><path fill="url(#i1UXKmc)" class="bfjow4buj"/><g filter="url(#iY6H0Ol)"><path class="kb6w1kbcz"/></g><g filter="url(#ixOip6v)"><path class="pay-csrgk"/></g><g filter="url(#ivEyoMe)"><path class="f5bb765yl"/><path fill="url(#iqB5G8d)" class="g8jw3blad"/><path fill="url(#irbm1eb)" class="g8jw3blad"/></g><g filter="url(#ilEbkIc)"><path class="kqp7-v86v"/><path fill="url(#if8hKCH)" class="z24iv1bpu"/></g><path class="k8g6gxbzb"/><path fill="url(#iQMfn3c)" class="gxelnbrlp"/><path class="fd9sf-bzr"/><g filter="url(#ivdnwNb)"><path class="qulvfvjgo"/><path fill="url(#ilgfImx)" class="hs9_myl3k"/></g><g filter="url(#iAfkq1b)"><path fill="url(#iatORCe)" class="zdu1adb9p"/></g><path class="u9s9v_rvl"/><path fill="url(#iOVdENc)" class="j02-mgb1p"/><path class="fscu5zbfy"/><g filter="url(#ilFKkLb)"><path fill="url(#ircmWld)" class="u7gmkzbsy"/></g><g filter="url(#iYlDfDb)"><ellipse transform="rotate(-27.914 12.696 11.34)" class="p5yl65bxk"/><ellipse fill="url(#iJ3BwMc)" transform="rotate(-27.914 12.696 11.34)" class="ikoqanbap"/></g><path fill="url(#i3I40Xd)" class="m5qdgwi3b"/><path fill="url(#iSX2N5d)" class="m5qdgwi3b"/><path fill="url(#iKh05lc)" class="m5qdgwi3b"/><path fill="url(#iGfzc4c)" class="m5qdgwi3b"/><path fill="url(#ifAhCBd)" class="i-61dw_ju"/><path fill="url(#i2daQlb)" class="i-61dw_ju"/><g filter="url(#ifeIajd)"><path fill="url(#iK8NKab)" class="x_787yb7u"/></g><g filter="url(#inyLfjb)"><path fill="url(#ikbiMEn)" class="rle4a4b2p"/></g><g filter="url(#iN1mXNd)"><path class="qrdxw82pj"/></g><g filter="url(#iK7o7qs)"><path class="x2po9qb3q"/></g><g filter="url(#iquQyTb)"><path class="fokj2vbyv"/></g><g filter="url(#iYjY0Zc)"><path fill="url(#iSfpgvb)" class="o8fqlybaq"/><path fill="url(#iD3EEee)" class="o8fqlybaq"/><path fill="url(#iLKt4Gd)" class="o8fqlybaq"/><path fill="url(#iQvcjMc)" class="o8fqlybaq"/><path fill="url(#izunZ9c)" class="o8fqlybaq"/></g><g filter="url(#ie19YEd)"><path stroke="url(#isOVvhb)" class="gnpanyxaf"/></g><g filter="url(#imz8Lze)"><path stroke="url(#iy8fC4c)" class="afbr7bclm"/></g><g filter="url(#iqURcAb)"><path stroke="url(#i8auW6c)" class="pl4qbm_2r"/></g><defs><radialGradient id="iusfDlx" cx="0" cy="0" r="1" gradientTransform="matrix(3.125 1 -2.08207 6.50646 3.708 25.594)" gradientUnits="userSpaceOnUse"><stop offset=".176" class="li28y9bsf"/><stop offset="1" class="o1jwunhtj"/></radialGradient><radialGradient id="i1mlueb" cx="0" cy="0" r="1" gradientTransform="rotate(110.288 4.674 19.536)scale(5.49596 3.74438)" gradientUnits="userSpaceOnUse"><stop class="oe2xm9ikp"/><stop offset="1" class="d6d59o0ou"/></radialGradient><radialGradient id="i3rHTFb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.71872 5.59376 -.25587 -.12436 24.239 17.875)" gradientUnits="userSpaceOnUse"><stop class="mnp72frot"/><stop offset="1" class="l4rg4-bid"/></radialGradient><radialGradient id="ioGO8Wc" cx="0" cy="0" r="1" gradientTransform="rotate(-101.597 18.153 8.92)scale(6.81742 .9881)" gradientUnits="userSpaceOnUse"><stop class="rzqjthgas"/><stop offset="1" class="ejynn6b3w"/></radialGradient><radialGradient id="iutyKpc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.80897 .6578 -1.95135 -5.36624 12.187 17.76)" gradientUnits="userSpaceOnUse"><stop class="i03-jcbks"/><stop offset="1" class="m27qtcbgg"/></radialGradient><radialGradient id="ik2cKhe" cx="0" cy="0" r="1" gradientTransform="matrix(0 9.50857 -5.52096 0 15.106 20.242)" gradientUnits="userSpaceOnUse"><stop class="ciisz2bnx"/><stop offset=".766" class="q289q0b5r"/></radialGradient><radialGradient id="il3Oeir" cx="0" cy="0" r="1" gradientTransform="matrix(0 -7.08205 11.2731 0 15.106 24.185)" gradientUnits="userSpaceOnUse"><stop offset=".717" class="x9ass5qdk"/><stop offset=".937" class="jzj-p5npf"/></radialGradient><radialGradient id="i0zzLub" cx="0" cy="0" r="1" gradientTransform="matrix(1.32816 -5.1875 .72473 .18555 15.998 24.826)" gradientUnits="userSpaceOnUse"><stop class="uv8l2wb3q"/><stop offset="1" class="gw6xrksmk"/></radialGradient><radialGradient id="isKPMTd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.86746 1.86213 -2.30086 -2.30745 28.446 21.102)" gradientUnits="userSpaceOnUse"><stop offset=".493" class="k7qyxzbsl"/><stop offset=".946" class="zdypug-8z"/></radialGradient><radialGradient id="ilIicsc" cx="0" cy="0" r="1" gradientTransform="matrix(.84335 -.64209 .3353 .44041 28.086 21.342)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="m8ott3b3k"/><stop offset="1" class="zk5cvukoj"/></radialGradient><radialGradient id="ib4I5td" cx="0" cy="0" r="1" gradientTransform="rotate(148.849 11.302 12.07)scale(4.17157)" gradientUnits="userSpaceOnUse"><stop offset=".838" class="wc1l7vbis"/><stop offset="1" class="oa317xagd"/></radialGradient><radialGradient id="iyulusd" cx="0" cy="0" r="1" gradientTransform="matrix(1.26514 1.24827 -2.90348 2.94272 23.842 15.19)" gradientUnits="userSpaceOnUse"><stop class="ky_indbcd"/><stop offset="1" class="s_ufbeclz"/></radialGradient><radialGradient id="iqJGQcd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.37479 2.10625 0 26.912 16.549)" gradientUnits="userSpaceOnUse"><stop class="qkb33eb6n"/><stop offset="1" class="q-0s8ibrs"/></radialGradient><radialGradient id="isMJFCe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .4408 -2.66861 0 27.506 16.94)" gradientUnits="userSpaceOnUse"><stop class="zxhnj4bqq"/><stop offset="1" class="hf-5q38gm"/></radialGradient><radialGradient id="i55YfdB" cx="0" cy="0" r="1" gradientTransform="matrix(-.4998 .66245 -.66245 -.4998 25.98 20.81)" gradientUnits="userSpaceOnUse"><stop class="dg3rcdvoo"/><stop offset="1" class="r0tyikbvd"/></radialGradient><radialGradient id="imT8q9v" cx="0" cy="0" r="1" gradientTransform="rotate(-118.985 14.068 5.314)scale(1.96318)" gradientUnits="userSpaceOnUse"><stop class="u8i6mckyj"/><stop offset="1" class="gainhdclb"/></radialGradient><radialGradient id="iLGoEPb" cx="0" cy="0" r="1" gradientTransform="rotate(43.152 -15.753 26.546)scale(2.9724 3.56688)" gradientUnits="userSpaceOnUse"><stop class="bc18wu-1h"/><stop offset=".865" class="m5aoovb9d"/></radialGradient><radialGradient id="ihHFTFe" cx="0" cy="0" r="1" gradientTransform="rotate(69.657 .398 20.95)scale(2.15388 2.55864)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="rra4r9bnq"/><stop offset="1" class="pft2s7y0a"/></radialGradient><radialGradient id="iFNr8Xj" cx="0" cy="0" r="1" gradientTransform="matrix(1.47646 .46402 -1.43155 4.555 9.093 13.783)" gradientUnits="userSpaceOnUse"><stop class="gg1n47rtb"/><stop offset=".746" class="q53v6mhsp"/></radialGradient><radialGradient id="i7Rlxoc" cx="0" cy="0" r="1" gradientTransform="matrix(-5.22785 0 0 -9.24802 17.957 12.352)" gradientUnits="userSpaceOnUse"><stop class="k53yjlbth"/><stop offset="1" class="ahguepbtf"/></radialGradient><radialGradient id="iaGI4jb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.02223 12.42352 -10.28813 -.84653 16.731 6.438)" gradientUnits="userSpaceOnUse"><stop offset=".767" class="c2_7179_n"/><stop offset=".997" class="h1qder98v"/></radialGradient><radialGradient id="iWg5aPc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.14835 1.42108 0 17.597 11.039)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="asp-974pn"/><stop offset="1" class="l2dudh2nh"/></radialGradient><radialGradient id="i1F1ecb" cx="0" cy="0" r="1" gradientTransform="rotate(-89.794 11.987 -.905)scale(1.09429 1.19084)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="ww86j5--q"/><stop offset="1" class="mfkgssbjj"/></radialGradient><radialGradient id="iRk9oCe" cx="0" cy="0" r="1" gradientTransform="matrix(-8.49599 .5363 -1.37 -21.703 18.582 13.34)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="o-j_7gbpq"/><stop offset="1" class="j-n0q842a"/></radialGradient><radialGradient id="i6FcH6d" cx="0" cy="0" r="1" gradientTransform="matrix(4.073 -2.6483 .96946 1.491 9.682 8.027)" gradientUnits="userSpaceOnUse"><stop offset=".38" class="xjcxgac6b"/><stop offset="1" class="psn4zabca"/></radialGradient><radialGradient id="iZvKJpb" cx="0" cy="0" r="1" gradientTransform="rotate(95.368 6.052 14.138)scale(2.50844 1.00273)" gradientUnits="userSpaceOnUse"><stop offset=".245" class="x73tbcc6t"/><stop offset="1" class="sbhjtg7pq"/></radialGradient><radialGradient id="iqpkUwc" cx="0" cy="0" r="1" gradientTransform="rotate(121.159 6.71 8.643)scale(3.36898 2.78137)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="f28ypccjc"/><stop offset="1" class="zkb-swu-c"/></radialGradient><radialGradient id="iLJZqqd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .2441 -.76718 0 15.616 13.712)" gradientUnits="userSpaceOnUse"><stop class="txgsuxr-c"/><stop offset="1" class="a4rldd3-z"/></radialGradient><radialGradient id="iHz4g6b" cx="0" cy="0" r="1" gradientTransform="matrix(-1.52115 .69743 -1.12083 -2.4446 15.732 13.143)" gradientUnits="userSpaceOnUse"><stop offset=".714" class="p8isx8b7k"/><stop offset="1" class="w37r5utea"/></radialGradient><radialGradient id="i0qAbrb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.72074 2.89971 0 15.15 15.891)" gradientUnits="userSpaceOnUse"><stop class="w189cfbhy"/><stop offset="1" class="z5a_p6x5j"/></radialGradient><radialGradient id="iLGRmve" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.50133 8.85445 0 9.92 9.46)" gradientUnits="userSpaceOnUse"><stop offset=".536" class="ibt06e6rm"/><stop offset="1" class="k45xjwbmq"/></radialGradient><radialGradient id="isnOVpd" cx="0" cy="0" r="1" gradientTransform="rotate(-87.401 15.64 -5.085)scale(2.51513 4.45631)" gradientUnits="userSpaceOnUse"><stop class="c98z413ze"/><stop offset="1" class="ovvtmacpn"/></radialGradient><radialGradient id="iMLOA3c" cx="0" cy="0" r="1" gradientTransform="matrix(-2.35883 -1.5514 1.13881 -1.7315 19.256 4.493)" gradientUnits="userSpaceOnUse"><stop class="wyv1gnbxf"/><stop offset="1" class="z6d-f52gr"/></radialGradient><radialGradient id="i9uQ2nc" cx="0" cy="0" r="1" gradientTransform="matrix(.90511 1.475 -3.4154 2.09582 14.245 2.901)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="qco-2_b3r"/><stop offset="1" class="zwo50zm6y"/></radialGradient><radialGradient id="iLsEcMd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.9117 6.52447 -8.23836 -3.67657 14.67 6.733)" gradientUnits="userSpaceOnUse"><stop class="jy25td8rp"/><stop offset="1" class="xftsofb3t"/></radialGradient><radialGradient id="i1UXKmc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.29688 1.23651 0 13.137 11.202)" gradientUnits="userSpaceOnUse"><stop offset=".545" class="hkf1_jbsj"/><stop offset="1" class="wrhkd7bsy"/></radialGradient><radialGradient id="iqB5G8d" cx="0" cy="0" r="1" gradientTransform="matrix(-2.20113 0 0 -.81692 15.403 5.16)" gradientUnits="userSpaceOnUse"><stop class="axstwemrb"/><stop offset="1" class="ez41_pbnb"/></radialGradient><radialGradient id="irbm1eb" cx="0" cy="0" r="1" gradientTransform="matrix(3.2182 -5.09542 5.6452 3.56544 9.719 9.103)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="hnw0p1utu"/><stop offset=".311" class="dwl_ftd7p"/><stop offset="1" class="fch_lgr5q"/></radialGradient><radialGradient id="if8hKCH" cx="0" cy="0" r="1" gradientTransform="rotate(6.667 -55.919 148.807)scale(3.27033 1.36922)" gradientUnits="userSpaceOnUse"><stop class="unyhdjbdq"/><stop offset="1" class="w0a4mmrgb"/></radialGradient><radialGradient id="iQMfn3c" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.2905 0 17.332 11.436)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="ilgfImx" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 11.373 1.572)scale(.37829 .52081)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iOVdENc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81136 -1.29056 0 12.968 11.436)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="iJ3BwMc" cx="0" cy="0" r="1" gradientTransform="matrix(-.00774 -.49408 .59392 -.0093 12.681 11.654)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iSX2N5d" cx="0" cy="0" r="1" gradientTransform="matrix(.62855 2.24328 -2.14025 .59968 19.767 11.45)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="xbtbagqno"/><stop offset="1" class="epf-qq6ay"/></radialGradient><radialGradient id="iKh05lc" cx="0" cy="0" r="1" gradientTransform="matrix(.78778 -1.0811 .90618 .66032 20.128 11.994)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="akw4fybhj"/><stop offset="1" class="qoxj776_o"/></radialGradient><radialGradient id="iGfzc4c" cx="0" cy="0" r="1" gradientTransform="matrix(.587 -1.55042 2.07158 .7843 20.242 12.166)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="c5e-i-5dw"/><stop offset=".966" class="szee5wb8m"/></radialGradient><radialGradient id="i2daQlb" cx="0" cy="0" r="1" gradientTransform="rotate(101.248 .176 9.865)scale(2.11668 2.08089)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="ay2574bqt"/><stop offset="1" class="g1u_xnbmn"/></radialGradient><radialGradient id="iK8NKab" cx="0" cy="0" r="1" gradientTransform="matrix(-.91648 .1573 -.06938 -.40422 10.234 12.094)" gradientUnits="userSpaceOnUse"><stop class="c4l15nbte"/><stop offset="1" class="r95ztqgly"/></radialGradient><radialGradient id="iD3EEee" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8787 -1.6371 0 26.073 23.35)" gradientUnits="userSpaceOnUse"><stop offset=".106" class="entsizubv"/><stop offset="1" class="wj9mtgody"/></radialGradient><radialGradient id="iLKt4Gd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .94192 -1.75486 0 26.073 24.768)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="entsizubv"/><stop offset="1" class="wj9mtgody"/></radialGradient><radialGradient id="iQvcjMc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .78779 -1.4677 0 26.073 26.138)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="entsizubv"/><stop offset="1" class="wj9mtgody"/></radialGradient><radialGradient id="izunZ9c" cx="0" cy="0" r="1" gradientTransform="matrix(0 .87616 -2.08784 0 26.073 27.62)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="entsizubv"/><stop offset="1" class="wj9mtgody"/></radialGradient><linearGradient id="ijs6MRb" x1="16.901" x2="15.504" y1="26.116" y2="25.813" gradientUnits="userSpaceOnUse"><stop class="k6k-6oblx"/><stop offset="1" class="l5x5or5jn"/></linearGradient><linearGradient id="iVWeYuc" x1="7.199" x2="6.027" y1="25.915" y2="25.915" gradientUnits="userSpaceOnUse"><stop class="xfetrrneo"/><stop offset="1" class="n0fg5jb7h"/></linearGradient><linearGradient id="i3Sh0Me" x1="23.128" x2="23.77" y1="26" y2="25.969" gradientUnits="userSpaceOnUse"><stop offset=".478" class="g2cjljmej"/><stop offset="1" class="h5gp5h3ar"/></linearGradient><linearGradient id="iRwJRdd" x1="22.77" x2="18.395" y1="15.985" y2="28.495" gradientUnits="userSpaceOnUse"><stop class="qm8srpk6b"/><stop offset="1" class="knnk86b5x"/></linearGradient><linearGradient id="idWSGXe" x1="16.824" x2="17.431" y1="26.486" y2="26.55" gradientUnits="userSpaceOnUse"><stop class="o_frn_b6l"/><stop offset="1" class="ohgvqyqas"/></linearGradient><linearGradient id="iHEj4Hy" x1="20.787" x2="20.787" y1="15.985" y2="16.808" gradientUnits="userSpaceOnUse"><stop offset=".165" class="oy7fe6bjb"/><stop offset="1" class="ivc982b0q"/></linearGradient><linearGradient id="igVhnne" x1="7.895" x2="11.895" y1="17.625" y2="28.875" gradientUnits="userSpaceOnUse"><stop class="e55i1-bjj"/><stop offset="1" class="rqyrdfbps"/></linearGradient><linearGradient id="iJmVmgb" x1="8.35" x2="9.063" y1="15.239" y2="19.296" gradientUnits="userSpaceOnUse"><stop class="agyv0c9kf"/><stop offset="1" class="vxg8xmb_d"/></linearGradient><linearGradient id="idKug7c" x1="7.895" x2="8.309" y1="22.563" y2="22.36" gradientUnits="userSpaceOnUse"><stop class="maqiohbml"/><stop offset="1" class="qndc1xila"/></linearGradient><linearGradient id="imWK0ae" x1="23.395" x2="21.614" y1="26.032" y2="26.032" gradientUnits="userSpaceOnUse"><stop class="tsgwb3b4a"/><stop offset="1" class="nvk1b4bey"/></linearGradient><linearGradient id="iFkg6vb" x1="8.114" x2="10.395" y1="27.844" y2="26.688" gradientUnits="userSpaceOnUse"><stop class="h1snaz72e"/><stop offset="1" class="kvxpklbcz"/></linearGradient><linearGradient id="izb8H2b" x1="15.111" x2="15.111" y1="17.386" y2="28.49" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="iMgWmrc" x1="17.905" x2="16.316" y1="22.093" y2="21.8" gradientUnits="userSpaceOnUse"><stop offset=".061" class="n9lqzvocu"/><stop offset=".066" class="n9lqzvocu"/><stop offset="1" class="komjktb1e"/></linearGradient><linearGradient id="iTohMAc" x1="25.739" x2="25.739" y1="15.682" y2="19.738" gradientUnits="userSpaceOnUse"><stop offset=".313" class="wprwrdbxj"/><stop offset=".562" class="ax-d4eb4u"/></linearGradient><linearGradient id="it2HJAe" x1="25.933" x2="25.792" y1="16.618" y2="17.821" gradientUnits="userSpaceOnUse"><stop offset=".12" class="qcwm1i13v"/><stop offset="1" class="s0eee-boz"/></linearGradient><linearGradient id="iRcFHzd" x1="23.236" x2="23.363" y1="16.554" y2="16.991" gradientUnits="userSpaceOnUse"><stop class="wtu393bab"/><stop offset="1" class="ce_wr9jxr"/></linearGradient><linearGradient id="ib01T2c" x1="26.936" x2="24.648" y1="21.125" y2="21.125" gradientUnits="userSpaceOnUse"><stop class="j-x55pbxn"/><stop offset="1" class="zg05wl6cw"/></linearGradient><linearGradient id="iL5Bq5b" x1="24.466" x2="24.847" y1="20.967" y2="20.939" gradientUnits="userSpaceOnUse"><stop class="fs7-dablt"/><stop offset="1" class="zg97ljbvw"/></linearGradient><linearGradient id="iPzWPCc" x1="27.084" x2="26.822" y1="20.838" y2="20.815" gradientUnits="userSpaceOnUse"><stop class="qna0z9q7a"/><stop offset="1" class="toldersuv"/></linearGradient><linearGradient id="i81GwYy" x1="20.307" x2="15.954" y1="14.037" y2="14.037" gradientUnits="userSpaceOnUse"><stop class="k53yjlbth"/><stop offset="1" class="prh5swccd"/></linearGradient><linearGradient id="iq5cLqb" x1="15.197" x2="15.197" y1="18.604" y2="17.964" gradientUnits="userSpaceOnUse"><stop class="dn2_hckup"/><stop offset="1" class="jk-0m6p0q"/></linearGradient><linearGradient id="i9eieKb" x1="15.988" x2="15.15" y1="13.027" y2="13.062" gradientUnits="userSpaceOnUse"><stop offset=".36" class="d8gqn2snf"/><stop offset="1" class="oz5jd4bmy"/></linearGradient><linearGradient id="izzeIab" x1="15.15" x2="15.15" y1="14.166" y2="13.701" gradientUnits="userSpaceOnUse"><stop class="abx50lnlm"/><stop offset="1" class="u-2msu4yh"/></linearGradient><linearGradient id="i3o89Hb" x1="15.15" x2="15.15" y1="11.211" y2="12.007" gradientUnits="userSpaceOnUse"><stop class="o2r2q6blp"/><stop offset="1" class="kh_x-hbqh"/></linearGradient><linearGradient id="iAo7N8b" x1="13.948" x2="14.266" y1="15.737" y2="14.902" gradientUnits="userSpaceOnUse"><stop class="ob3l4g_ys"/><stop offset="1" class="fglza-d-f"/></linearGradient><linearGradient id="iDUOPge" x1="22.002" x2="10.389" y1="6.689" y2="6.689" gradientUnits="userSpaceOnUse"><stop class="l1vex1b6a"/><stop offset="1" class="kydculhfm"/></linearGradient><linearGradient id="iatORCe" x1="18.11" x2="17.796" y1="11.49" y2="11.683" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ircmWld" x1="13.711" x2="13.398" y1="11.489" y2="11.683" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i3I40Xd" x1="21.586" x2="20.379" y1="11.516" y2="13.693" gradientUnits="userSpaceOnUse"><stop class="lwf47ccyr"/><stop offset="1" class="bmcblacal"/></linearGradient><linearGradient id="ifAhCBd" x1="9.3" x2="10.758" y1="12.22" y2="12.093" gradientUnits="userSpaceOnUse"><stop class="jrlin1f0e"/><stop offset="1" class="zzkrmpd6m"/></linearGradient><linearGradient id="ikbiMEn" x1="20.566" x2="20.566" y1="11.135" y2="13.038" gradientUnits="userSpaceOnUse"><stop class="q3b-p60-b"/><stop offset="1" class="v3ih9bcyp"/></linearGradient><linearGradient id="iSfpgvb" x1="27.996" x2="23.128" y1="26.372" y2="26.372" gradientUnits="userSpaceOnUse"><stop offset=".146" class="o3k0towjz"/><stop offset=".861" class="qxb7siz6w"/></linearGradient><linearGradient id="isOVvhb" x1="23.742" x2="25.663" y1="24.169" y2="24.169" gradientUnits="userSpaceOnUse"><stop class="wj3drmbex"/><stop offset="1" class="ur8e5kbgj"/></linearGradient><linearGradient id="iy8fC4c" x1="23.742" x2="25.663" y1="25.611" y2="25.611" gradientUnits="userSpaceOnUse"><stop class="wj3drmbex"/><stop offset="1" class="ur8e5kbgj"/></linearGradient><linearGradient id="i8auW6c" x1="23.742" x2="25.663" y1="27.041" y2="27.041" gradientUnits="userSpaceOnUse"><stop class="wj3drmbex"/><stop offset="1" class="ur8e5kbgj"/></linearGradient><filter id="iGS1ARd" width="5.513" height="4.74" x="12.848" y="23.745" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.976471 0 0 0 0 0.780392 0 0 0 0 0.866667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2312"/></filter><filter id="iqJKIUc" width="6.102" height="1.228" x="22.791" y="16.456" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.05"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.647059 0 0 0 0 0.47451 0 0 0 0 0.54902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2312"/></filter><filter id="iyakMiK" width="1.075" height="1.075" x="25.198" y="20.588" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".025"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.694118 0 0 0 0 0.560784 0 0 0 0 0.764706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2312"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".025"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.917647 0 0 0 0 0.87451 0 0 0 0 0.976471 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2312" result="effect2_innerShadow_4002_2312"/></filter><filter id="iBqt8fb" width="5.967" height="5.967" x="12.166" y="14.761" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2312" stdDeviation=".125"/></filter><filter id="iwBIHQe" width="5.813" height="5.813" x="12.243" y="14.839" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2312" stdDeviation=".25"/></filter><filter id="iV9Ajbd" width="11.22" height="12.542" x="10.086" y="6.181" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.333333 0 0 0 0 0.270588 0 0 0 0 0.258824 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2312"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.145098 0 0 0 0 0.0705882 0 0 0 0 0.0745098 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2312" result="effect2_innerShadow_4002_2312"/></filter><filter id="iPlNqob" width="3.747" height="4.9" x="13.134" y="10.527" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2312" stdDeviation=".5"/></filter><filter id="iLcve4b" width="2.277" height="3.3" x="14.011" y="11.132" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2312" stdDeviation=".1"/></filter><filter id="iEOZvBc" width="3.718" height="1.573" x="13.29" y="14.652" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2312" stdDeviation=".05"/></filter><filter id="iGvc3Hc" width="12.873" height="8.357" x="8.713" y="3.005" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.137255 0 0 0 0 0.0901961 0 0 0 0 0.145098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2312"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0784314 0 0 0 0 0.0352941 0 0 0 0 0.0470588 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2312" result="effect2_innerShadow_4002_2312"/></filter><filter id="iY6H0Ol" width="2.339" height="1.19" x="16.739" y="8.668" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0588235 0 0 0 0 0.054902 0 0 0 0 0.0588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2312"/></filter><filter id="ixOip6v" width="2.339" height="1.176" x="11.482" y="8.683" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0588235 0 0 0 0 0.054902 0 0 0 0 0.0588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2312"/></filter><filter id="ivEyoMe" width="6.734" height="5.992" x="9.069" y="4.093" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.286275 0 0 0 0 0.243137 0 0 0 0 0.227451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2312"/><feGaussianBlur result="effect2_foregroundBlur_4002_2312" stdDeviation=".125"/></filter><filter id="ilEbkIc" width="6.362" height="5.736" x="14.991" y="4.517" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.305882 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2312"/><feGaussianBlur result="effect2_foregroundBlur_4002_2312" stdDeviation=".125"/></filter><filter id="ivdnwNb" width=".787" height=".696" x="16.597" y="10.996" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2312" stdDeviation=".05"/></filter><filter id="iAfkq1b" width=".891" height=".913" x="17.438" y="11.071" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2312" stdDeviation=".1"/></filter><filter id="ilFKkLb" width=".986" height="1.04" x="12.995" y="11.007" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2312" stdDeviation=".1"/></filter><filter id="iYlDfDb" width=".913" height=".705" x="12.24" y="10.988" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2312" stdDeviation=".05"/></filter><filter id="ifeIajd" width="1.329" height="2.379" x="9.069" y="10.903" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2312" stdDeviation=".125"/></filter><filter id="inyLfjb" width="1.947" height="2.903" x="19.593" y="10.635" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2312" stdDeviation=".25"/></filter><filter id="iN1mXNd" width="2.405" height="1.16" x="11.402" y="8.758" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2312" stdDeviation=".125"/></filter><filter id="iK7o7qs" width="2.405" height="1.16" x="16.68" y="8.712" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2312" stdDeviation=".125"/></filter><filter id="iquQyTb" width="5.266" height="3.006" x="16.029" y="5.036" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2312" stdDeviation=".375"/></filter><filter id="iYjY0Zc" width="5.369" height="6.076" x="23.128" y="22.42" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.196078 0 0 0 0 0.117647 0 0 0 0 0.145098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2312"/></filter><filter id="ie19YEd" width="2.319" height=".3" x="23.592" y="23.941" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2312" stdDeviation=".05"/></filter><filter id="imz8Lze" width="2.319" height=".3" x="23.592" y="25.383" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2312" stdDeviation=".05"/></filter><filter id="iqURcAb" width="2.319" height=".3" x="23.592" y="26.813" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2312" stdDeviation=".05"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:singer-dark" /></template>
<style>
.a4rldd3-z {
  stop-color: var(--svg-color--685554, #685554);
  stop-opacity: 0;
}

.abx50lnlm {
  stop-color: var(--svg-color--3e2230, #3E2230);
}

.afbr7bclm {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.742 25.533h2.02");
}

.agyv0c9kf {
  stop-color: var(--svg-color--c46d3a, #C46D3A);
}

.ahguepbtf {
  stop-color: var(--svg-color--3c2828, #3C2828);
}

.akw4fybhj {
  stop-color: var(--svg-color--351b1e, #351B1E);
}

.asp-974pn {
  stop-color: var(--svg-color--432728, #432728);
}

.ax-d4eb4u {
  stop-color: var(--svg-color--562d79, #562D79);
}

.axstwemrb {
  stop-color: var(--svg-color--423c3f, #423C3F);
}

.ay2574bqt {
  stop-color: var(--svg-color--301929, #301929);
  stop-opacity: 0;
}

.bbyb_mbsk {
  stop-color: var(--svg-color--664842, #664842);
}

.bc18wu-1h {
  stop-color: var(--svg-color--33191c, #33191C);
}

.bfjow4buj {
  d: path("M15.107 6.318a.66.66 0 0 0-.402-.137h-1.273a3.3 3.3 0 0 0-.541.044l-2.248 6.619h1.809l-.508 2.687l3.688-5.133h-1.883z");
}

.bmcblacal {
  stop-color: var(--svg-color--492f32, #492F32);
}

.bn25ibyvi {
  d: path("M25.766 19.684a2.498 2.498 0 1 0 0-4.996a2.498 2.498 0 0 0 0 4.996");
}

.bs4j4xojh {
  fill: var(--svg-color--331e24, #331E24);
  d: path("m14.748 11.833l-.59 1.838c-.101.378.14.757.484.757h.732c.343 0 .585-.384.484-.757l-.495-1.838c-.106-.407-.504-.407-.615 0");
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

.c5q7122zr {
  d: path("M7.078 28.485v-7.93a11.75 11.75 0 0 0-3.18 5.04l-.03.09c-.29.91-.51 1.85-.66 2.8z");
}

.c98z413ze {
  stop-color: var(--svg-color--4f4d4d, #4F4D4D);
}

.ce_wr9jxr {
  stop-color: var(--svg-color--b19a83, #B19A83);
  stop-opacity: 0;
}

.ciisz2bnx {
  stop-color: var(--svg-color--472f2e, #472F2E);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.d6d59o0ou {
  stop-color: var(--svg-color--4d396f, #4D396F);
}

.d8gqn2snf {
  stop-color: var(--svg-color--66514e, #66514E);
}

.dg3rcdvoo {
  stop-color: var(--svg-color--d2bfe7, #D2BFE7);
}

.dn2_hckup {
  stop-color: var(--svg-color--49201f, #49201F);
}

.dn78wjc6c {
  d: path("M20.005 5.709c.514.177.975.536 1.267 1.051a2.37 2.37 0 0 1-.106 2.527a1.56 1.56 0 0 0-.27.874v1.188a1.75 1.75 0 0 0-.668-.268l.079-1.607a1.45 1.45 0 0 0-1.38-1.432h-1.4a2.42 2.42 0 0 1-2.211-1.443a.66.66 0 0 0-.615-.418h-1.273c-1.846 0-3.342 1.513-3.342 3.38l.031 1.536a1.7 1.7 0 0 0-.72.264v-1.2a1.56 1.56 0 0 0-.27-.874a2.39 2.39 0 0 1-.144-2.446a2.34 2.34 0 0 1 1.3-1.127a2.68 2.68 0 0 0 1.384-1.11a2.325 2.325 0 0 1 2.89-.912a1.5 1.5 0 0 0 1.194 0c.28-.118.589-.187.912-.187c.843 0 1.58.455 1.989 1.131c.308.51.79.88 1.352 1.073");
}

.dqa4_dciz {
  fill: var(--svg-color--e7c1f2, #E7C1F2);
  d: path("M12.848 23.746v4.74h5.313l-.803-4.69c-.68.25-1.42.38-2.19.38c-.81.01-1.6-.15-2.32-.43");
}

.dwl_ftd7p {
  stop-color: var(--svg-color--1c0c20, #1C0C20);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e55i1-bjj {
  stop-color: var(--svg-color--e86b1f, #E86B1F);
}

.ejynn6b3w {
  stop-color: var(--svg-color--ef5945, #EF5945);
  stop-opacity: 0;
}

.entsizubv {
  stop-color: var(--svg-color--5e4745, #5E4745);
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

.f5bb765yl {
  fill: var(--svg-color--23181c, #23181C);
  d: path("m15.382 6.736l-.066-.137a.66.66 0 0 0-.615-.418h-1.273c-1.846 0-3.342 1.512-3.342 3.379v.275c-.34-.259-.767-.804-.767-1.688c0-1.071.781-1.613 1.28-1.959c.14-.097.26-.18.33-.253l.1-.105c.35-.37.973-1.031 2.06-1.32a5.5 5.5 0 0 1 1.508-.165c.473.012.806.42.806.893v1.485z");
}

.fch_lgr5q {
  stop-color: var(--svg-color--1c0c20, #1C0C20);
  stop-opacity: 0;
}

.fd9sf-bzr {
  fill: var(--svg-color--000, #000);
  d: path("M16.823 11.851c0-.284.227-.511.51-.511a.51.51 0 0 1 .455.746h-.904a.46.46 0 0 1-.061-.235");
}

.fglza-d-f {
  stop-color: var(--svg-color--40222d, #40222D);
  stop-opacity: 0;
}

.fokj2vbyv {
  fill: var(--svg-color--504a4c, #504A4C);
  d: path("M19.343 6.753h-2.081a.483.483 0 1 1 .077-.96c.54.085 1.257.205 1.737.324c1.085.27 1.385.798 1.469 1.175a1.51 1.51 0 0 0-1.203-.539");
}

.fs7-dablt {
  stop-color: var(--svg-color--a0768f, #A0768F);
}

.fscu5zbfy {
  fill: var(--svg-color--000, #000);
  d: path("M13.477 11.851a.51.51 0 0 0-.511-.511a.51.51 0 0 0-.455.746h.905a.5.5 0 0 0 .06-.235");
}

.ft5dv1b6b {
  fill: none;
}

.g1u_xnbmn {
  stop-color: var(--svg-color--301929, #301929);
}

.g2cjljmej {
  stop-color: var(--svg-color--604e83, #604E83);
}

.g8jw3blad {
  d: path("m15.382 6.736l-.066-.137a.66.66 0 0 0-.615-.418h-1.273c-1.846 0-3.342 1.512-3.342 3.379v.275c-.34-.259-.767-.804-.767-1.688c0-1.071.781-1.613 1.28-1.959c.14-.097.26-.18.33-.253l.1-.105c.35-.37.973-1.031 2.06-1.32a5.5 5.5 0 0 1 1.508-.165c.473.012.806.42.806.893v1.485z");
}

.gainhdclb {
  stop-color: var(--svg-color--564746, #564746);
  stop-opacity: 0;
}

.gg1n47rtb {
  stop-color: var(--svg-color--463c39, #463C39);
}

.glk19gb1l {
  d: path("m14.767 11.637l-.531 1.838c-.109.379.152.757.52.757h.787c.369 0 .629-.384.52-.757l-.531-1.838c-.114-.407-.645-.407-.765 0");
}

.gn190fg6k {
  cx: 15.149px;
  cy: 17.745px;
  r: 2.734px;
}

.gnpanyxaf {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.742 24.09h2.02");
}

.gw6xrksmk {
  stop-color: var(--svg-color--503f3f, #503F3F);
  stop-opacity: 0;
}

.gxelnbrlp {
  d: path("M17.334 10.959a.893.893 0 0 1 .86 1.127H16.47a.896.896 0 0 1 .864-1.128");
}

.h_j9u0wvt {
  stop-color: var(--svg-color--e6e6e6, #E6E6E6);
}

.h1qder98v {
  stop-color: var(--svg-color--432742, #432742);
}

.h1snaz72e {
  stop-color: var(--svg-color--665395, #665395);
}

.h5gp5h3ar {
  stop-color: var(--svg-color--604e83, #604E83);
  stop-opacity: 0;
}

.hf-5q38gm {
  stop-color: var(--svg-color--c1bcc8, #C1BCC8);
  stop-opacity: 0;
}

.hkf1_jbsj {
  stop-color: var(--svg-color--be2252, #BE2252);
}

.hnw0p1utu {
  stop-color: var(--svg-color--0b0306, #0B0306);
}

.hs9_myl3k {
  d: path("M17.268 11.147c.063.085-.07.189-.22.302c-.152.113-.264.193-.327.107c-.064-.085.007-.245.158-.358s.325-.136.389-.05");
}

.i-61dw_ju {
  d: path("M10.096 10.493a1.61 1.61 0 0 0 .138 3.2a78 78 0 0 1-.138-3.2");
}

.i03-jcbks {
  stop-color: var(--svg-color--d14708, #D14708);
}

.ibt06e6rm {
  stop-color: var(--svg-color--3e3433, #3E3433);
}

.ifmu2bbjb {
  d: path("M7.078 28.485h3.87l-3.87-7.595z");
}

.ijj3iu5hn {
  d: path("M25.736 21.613a.487.487 0 1 0 0-.974a.487.487 0 0 0 0 .974");
}

.ika489brf {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M13.799 14.854h-.001a.23.23 0 0 0-.271.046a.21.21 0 0 0-.023.27c.348.529.955.88 1.646.88c.69 0 1.297-.352 1.645-.88a.214.214 0 0 0-.023-.272a.23.23 0 0 0-.271-.045c-.39.204-.85.32-1.352.32a2.9 2.9 0 0 1-1.35-.32Z");
}

.ikoqanbap {
  cx: 12.696px;
  cy: 11.34px;
  rx: 0.39px;
  ry: 0.197px;
}

.ivc982b0q {
  stop-color: var(--svg-color--e48043, #E48043);
  stop-opacity: 0;
}

.j-n0q842a {
  stop-color: var(--svg-color--564440, #564440);
}

.j-x55pbxn {
  stop-color: var(--svg-color--d9cbea, #D9CBEA);
}

.j02-mgb1p {
  d: path("M12.966 10.959a.893.893 0 0 0-.86 1.127h1.724a1 1 0 0 0 .032-.235a.9.9 0 0 0-.896-.892");
}

.jk-0m6p0q {
  stop-color: var(--svg-color--49201f, #49201F);
  stop-opacity: 0;
}

.jrlin1f0e {
  stop-color: var(--svg-color--372425, #372425);
}

.jy25td8rp {
  stop-color: var(--svg-color--e82d86, #E82D86);
}

.jzj-p5npf {
  stop-color: var(--svg-color--2a1a19, #2A1A19);
}

.k-v83l39e {
  d: path("M20.01 13.602c.336-.011.65-.125.906-.309v.931c0 .893-.533 1.689-1.341 2.02q.256-.547.346-1.18z");
}

.k45xjwbmq {
  stop-color: var(--svg-color--3e3433, #3E3433);
  stop-opacity: 0;
}

.k53yjlbth {
  stop-color: var(--svg-color--563b38, #563B38);
}

.k6k-6oblx {
  stop-color: var(--svg-color--c296bf, #C296BF);
}

.k7qyxzbsl {
  stop-color: var(--svg-color--4b312d, #4B312D);
}

.k8g6gxbzb {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.54 10.687c.654 0 1.205.45 1.355 1.059a.274.274 0 0 1-.267.34h-2.231a.23.23 0 0 1-.228-.271a1.4 1.4 0 0 1 1.372-1.128");
}

.kb6w1kbcz {
  fill: var(--svg-color--202020, #202020);
  d: path("M18.883 9.372a1.85 1.85 0 0 0-.688-.411c-.304-.096-.685-.122-1.212-.057a.277.277 0 1 0 .067.55c.481-.058.776-.028.979.036c.198.062.332.163.49.3a.277.277 0 1 0 .364-.418");
}

.kh_x-hbqh {
  stop-color: var(--svg-color--4b302a, #4B302A);
  stop-opacity: 0;
}

.knnk86b5x {
  stop-color: var(--svg-color--d53939, #D53939);
}

.komjktb1e {
  stop-color: var(--svg-color--412a29, #412A29);
  stop-opacity: 0;
}

.kqp7-v86v {
  fill: var(--svg-color--1f151b, #1F151B);
  d: path("m20.362 10.003l-.029-.631c-.01-.764-.641-1.394-1.405-1.426h-1.4c-.89 0-1.7-.486-2.124-1.26c0 0-.059-.135-.12-.368c-.257-.97.67-1.712 1.655-1.521c.974.189 2.082.517 2.902 1.052c1.745 1.138 1.44 3.188.521 4.154");
}

.kt__1405u {
  stop-color: var(--svg-color--ccc, #CCC);
}

.kvxpklbcz {
  stop-color: var(--svg-color--5d4c7d, #5D4C7D);
}

.ky_indbcd {
  stop-color: var(--svg-color--7b5e40, #7B5E40);
}

.kydculhfm {
  stop-color: var(--svg-color--272127, #272127);
}

.l1vex1b6a {
  stop-color: var(--svg-color--443d40, #443D40);
}

.l2dudh2nh {
  stop-color: var(--svg-color--432728, #432728);
  stop-opacity: 0;
}

.l4rg4-bid {
  stop-color: var(--svg-color--f6874a, #F6874A);
  stop-opacity: 0;
}

.l5x5or5jn {
  stop-color: var(--svg-color--e7c1f5, #E7C1F5);
  stop-opacity: 0;
}

.laenz-bql {
  d: path("M27.018 28.485c-.14-.96-.36-1.91-.65-2.84a11.77 11.77 0 0 0-3.24-5.13v7.97z");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.li28y9bsf {
  stop-color: var(--svg-color--675890, #675890);
}

.lwf47ccyr {
  stop-color: var(--svg-color--62504f, #62504F);
}

.m27qtcbgg {
  stop-color: var(--svg-color--d14708, #D14708);
  stop-opacity: 0;
}

.m5aoovb9d {
  stop-color: var(--svg-color--3a1d23, #3A1D23);
}

.m5qdgwi3b {
  d: path("M20.071 13.693q.1-1.596.185-3.192a1.61 1.61 0 0 1-.185 3.192");
}

.m8ott3b3k {
  stop-color: var(--svg-color--675655, #675655);
}

.maqiohbml {
  stop-color: var(--svg-color--ec7046, #EC7046);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mfkgssbjj {
  stop-color: var(--svg-color--361e27, #361E27);
  stop-opacity: 0;
}

.mj7of5vyp {
  d: path("M25.726 26.325a.784.784 0 0 1-.782-.71l-.67-6.429l2.975.01l-.731 6.429a.8.8 0 0 1-.792.7");
}

.mnp72frot {
  stop-color: var(--svg-color--f6874a, #F6874A);
}

.n0fg5jb7h {
  stop-color: var(--svg-color--504665, #504665);
  stop-opacity: 0;
}

.n9lqzvocu {
  stop-color: var(--svg-color--2b1417, #2B1417);
}

.nvk1b4bey {
  stop-color: var(--svg-color--5f4b8a, #5F4B8A);
}

.nzlkhptrb {
  d: path("M15.118 16.298c-1.16 0-2.487.209-3.567.58l1.29 6.873c.72.325 1.497.434 2.317.434c.77 0 1.51-.073 2.19-.351l1.313-6.956c-1.05-.383-2.384-.58-3.544-.58");
}

.o_frn_b6l {
  stop-color: var(--svg-color--cc2820, #CC2820);
}

.o-j_7gbpq {
  stop-color: var(--svg-color--564440, #564440);
  stop-opacity: 0;
}

.o1jwunhtj {
  stop-color: var(--svg-color--58497e, #58497E);
}

.o2r2q6blp {
  stop-color: var(--svg-color--4b302a, #4B302A);
}

.o3k0towjz {
  stop-color: var(--svg-color--533632, #533632);
}

.o80hv4hxf {
  fill: var(--svg-color--402929, #402929);
  d: path("m14.767 11.637l-.531 1.838c-.109.379.152.757.52.757h.787c.369 0 .629-.384.52-.757l-.531-1.838c-.114-.407-.645-.407-.765 0");
}

.o8fqlybaq {
  d: path("M23.128 23.372a.81.81 0 0 1 .816-.802h3.054c.745 0 1.349.589 1.349 1.315V27.4c0 .606-.503 1.096-1.124 1.096h-3.28a.81.81 0 0 1-.816-.802c0-.314.187-.589.458-.72a.8.8 0 0 1-.457-.72c0-.314.186-.59.457-.72a.8.8 0 0 1-.457-.72a.8.8 0 0 1 .457-.72a.8.8 0 0 1-.457-.72");
}

.oa317xagd {
  stop-color: var(--svg-color--673d45, #673D45);
}

.ob3l4g_ys {
  stop-color: var(--svg-color--584a4a, #584A4A);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oe2xm9ikp {
  stop-color: var(--svg-color--746b8d, #746B8D);
}

.ohgvqyqas {
  stop-color: var(--svg-color--cc2820, #CC2820);
  stop-opacity: 0;
}

.ovvtmacpn {
  stop-color: var(--svg-color--4f4d4d, #4F4D4D);
  stop-opacity: 0;
}

.oy7fe6bjb {
  stop-color: var(--svg-color--e48043, #E48043);
}

.oz5jd4bmy {
  stop-color: var(--svg-color--66514e, #66514E);
  stop-opacity: 0;
}

.p5yl65bxk {
  cx: 12.696px;
  cy: 11.34px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.p8isx8b7k {
  stop-color: var(--svg-color--3e2b29, #3E2B29);
  stop-opacity: 0;
}

.pay-csrgk {
  fill: var(--svg-color--202020, #202020);
  d: path("M11.739 9.263a2.77 2.77 0 0 1 1.739-.36a.277.277 0 1 1-.068.551a2.22 2.22 0 0 0-1.387.285a1 1 0 0 0-.091.06l-.003.002a.277.277 0 0 1-.34-.439z");
}

.pft2s7y0a {
  stop-color: var(--svg-color--221c27, #221C27);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pl4qbm_2r {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.742 26.963h2.02");
}

.prh5swccd {
  stop-color: var(--svg-color--563b38, #563B38);
  stop-opacity: 0;
}

.psn4zabca {
  stop-color: var(--svg-color--231112, #231112);
  stop-opacity: 0;
}

.ptdv5_kap {
  cx: 15.149px;
  cy: 17.745px;
  r: 2.406px;
}

.q-0s8ibrs {
  stop-color: var(--svg-color--7d718c, #7D718C);
  stop-opacity: 0;
}

.q289q0b5r {
  stop-color: var(--svg-color--281314, #281314);
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

.qcwm1i13v {
  stop-color: var(--svg-color--bfbac7, #BFBAC7);
}

.qd55obbpm {
  d: path("M12.848 23.746v4.74h5.313l-.803-4.69c-.68.25-1.42.38-2.19.38c-.81.01-1.6-.15-2.32-.43");
}

.qkb33eb6n {
  stop-color: var(--svg-color--7d718c, #7D718C);
}

.qm8srpk6b {
  stop-color: var(--svg-color--f98026, #F98026);
}

.qna0z9q7a {
  stop-color: var(--svg-color--cbc6d6, #CBC6D6);
}

.qndc1xila {
  stop-color: var(--svg-color--ec7046, #EC7046);
  stop-opacity: 0;
}

.qoxj776_o {
  stop-color: var(--svg-color--351b1e, #351B1E);
  stop-opacity: 0;
}

.qrdxw82pj {
  stroke: var(--svg-color--353535, #353535);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M11.777 9.543c.257-.184.897-.509 1.655-.381");
}

.qulvfvjgo {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M17.268 11.147c.063.085-.07.189-.22.302c-.152.113-.264.193-.327.107c-.064-.085.007-.245.158-.358s.325-.136.389-.05");
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qxb7siz6w {
  stop-color: var(--svg-color--3f282a, #3F282A);
}

.r0tyikbvd {
  stop-color: var(--svg-color--c0a6d9, #C0A6D9);
}

.r95ztqgly {
  stop-color: var(--svg-color--271416, #271416);
}

.rle4a4b2p {
  d: path("M20.093 13.038q.057-.952.11-1.903a.956.956 0 0 1-.11 1.903");
}

.rqyrdfbps {
  stop-color: var(--svg-color--e22f38, #E22F38);
}

.rra4r9bnq {
  stop-color: var(--svg-color--3c3b3c, #3C3B3C);
}

.rzqjthgas {
  stop-color: var(--svg-color--ef5945, #EF5945);
}

.s_ufbeclz {
  stop-color: var(--svg-color--463358, #463358);
  stop-opacity: 0;
}

.s0eee-boz {
  stop-color: var(--svg-color--aa7bd1, #AA7BD1);
}

.sbhjtg7pq {
  stop-color: var(--svg-color--6b5b59, #6B5B59);
  stop-opacity: 0;
}

.szee5wb8m {
  stop-color: var(--svg-color--361c1e, #361C1E);
}

.toldersuv {
  stop-color: var(--svg-color--d3c3e5, #D3C3E5);
  stop-opacity: 0;
}

.tsgwb3b4a {
  stop-color: var(--svg-color--7c739f, #7C739F);
}

.txgsuxr-c {
  stop-color: var(--svg-color--685554, #685554);
}

.u-2msu4yh {
  stop-color: var(--svg-color--3e2230, #3E2230);
  stop-opacity: 0;
}

.u5h71mb8p {
  d: path("M23.128 28.485v-7.267l-3.52 7.267z");
}

.u7gmkzbsy {
  d: path("M13.781 11.746c0-.288-.235-.48-.298-.539l-.288.28l.177.36z");
}

.u8i6mckyj {
  stop-color: var(--svg-color--564746, #564746);
}

.u9s9v_rvl {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.759 10.687c-.653 0-1.205.45-1.355 1.059a.273.273 0 0 0 .268.34h2.23a.23.23 0 0 0 .228-.272a1.4 1.4 0 0 0-1.371-1.127");
}

.ubrvwpbys {
  d: path("M27.277 20.81c.59 0 1.07.48 1.07 1.07v2.45h-2.14v-2.45c0-.59.48-1.07 1.07-1.07");
}

.unyhdjbdq {
  stop-color: var(--svg-color--200e25, #200E25);
}

.ur8e5kbgj {
  stop-color: var(--svg-color--2e1c1e, #2E1C1E);
  stop-opacity: 0;
}

.uv8l2wb3q {
  stop-color: var(--svg-color--503f3f, #503F3F);
}

.uyyuv9bgc {
  d: path("M10.325 15.117a3.916 3.916 0 0 0 3.885 3.406h1.887a3.916 3.916 0 0 0 3.886-3.406c.117-1.884.236-3.76.324-5.643a1.45 1.45 0 0 0-1.38-1.432h-1.4a2.42 2.42 0 0 1-2.211-1.443a.66.66 0 0 0-.615-.418h-1.273c-1.846 0-3.342 1.513-3.342 3.38c0 1.86.117 3.69.239 5.556");
}

.v3ih9bcyp {
  stop-color: var(--svg-color--3e2724, #3E2724);
}

.vsx0ybblj {
  d: path("m28.214 16.526l-4.844-.02a.57.57 0 0 0-.58.578c0 .325.255.58.58.58l4.844.02a.57.57 0 0 0 .578-.58a.585.585 0 0 0-.578-.578");
}

.vxg8xmb_d {
  stop-color: var(--svg-color--c46d3a, #C46D3A);
  stop-opacity: 0;
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

.wc1l7vbis {
  stop-color: var(--svg-color--473558, #473558);
  stop-opacity: 0;
}

.wieq7abdc {
  d: path("M24.313 16.499h-5.58l-2.274 11.996h3.149l5.325-11.016a.685.685 0 0 0-.62-.98");
}

.wj3drmbex {
  stop-color: var(--svg-color--2e1c1e, #2E1C1E);
}

.wj9mtgody {
  stop-color: var(--svg-color--533531, #533531);
  stop-opacity: 0;
}

.wprwrdbxj {
  stop-color: var(--svg-color--453357, #453357);
}

.wrhkd7bsy {
  stop-color: var(--svg-color--be2252, #BE2252);
  stop-opacity: 0;
}

.wtu393bab {
  stop-color: var(--svg-color--b19a83, #B19A83);
}

.ww86j5--q {
  stop-color: var(--svg-color--361e27, #361E27);
}

.wyv1gnbxf {
  stop-color: var(--svg-color--5e5a5b, #5E5A5B);
}

.x_787yb7u {
  d: path("M10.064 11.153a.956.956 0 0 0 .084 1.88a78 78 0 0 1-.084-1.88");
}

.x2po9qb3q {
  stroke: var(--svg-color--353535, #353535);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M18.71 9.497c-.256-.185-.897-.509-1.655-.382");
}

.x73tbcc6t {
  stop-color: var(--svg-color--6b5b59, #6B5B59);
}

.x9ass5qdk {
  stop-color: var(--svg-color--2a1a19, #2A1A19);
  stop-opacity: 0;
}

.xbtbagqno {
  stop-color: var(--svg-color--301924, #301924);
  stop-opacity: 0;
}

.xfetrrneo {
  stop-color: var(--svg-color--504665, #504665);
}

.xftsofb3t {
  stop-color: var(--svg-color--d42552, #D42552);
}

.xjcxgac6b {
  stop-color: var(--svg-color--231112, #231112);
}

.yebmocc2p {
  d: path("M5.405 16.507h6.086l2.248 11.988h-2.79l-5.88-11.528c-.086-.125-.07-.46.336-.46");
}

.yk2-i9bly {
  d: path("M15.15 15.248c-.508 0-.985-.119-1.386-.328c-.137-.07-.284.085-.198.209c.335.508.919.846 1.583.846c.665 0 1.249-.338 1.584-.846c.086-.13-.061-.279-.198-.209a3 3 0 0 1-1.386.328");
}

.z24iv1bpu {
  d: path("m20.362 10.003l-.029-.631c-.01-.764-.641-1.394-1.405-1.426h-1.4c-.89 0-1.7-.486-2.124-1.26c0 0-.059-.135-.12-.368c-.257-.97.67-1.712 1.655-1.521c.974.189 2.082.517 2.902 1.052c1.745 1.138 1.44 3.188.521 4.154");
}

.z5a_p6x5j {
  stop-color: var(--svg-color--290017, #290017);
}

.z6d-f52gr {
  stop-color: var(--svg-color--5e5a5b, #5E5A5B);
  stop-opacity: 0;
}

.zc7yzq-8f {
  d: path("M15.118 17.385c-1.16 0-2.3.17-3.38.49l1.1 5.87c.72.28 1.5.44 2.32.44c.77 0 1.51-.14 2.19-.38l1.11-5.92c-1.05-.33-2.18-.5-3.34-.5");
}

.zdu1adb9p {
  d: path("M18.129 11.734a.84.84 0 0 0-.232-.463l-.26.285l.118.228z");
}

.zdypug-8z {
  stop-color: var(--svg-color--2b1820, #2B1820);
}

.zg05wl6cw {
  stop-color: var(--svg-color--a78bc1, #A78BC1);
}

.zg97ljbvw {
  stop-color: var(--svg-color--ad93c6, #AD93C6);
  stop-opacity: 0;
}

.zk5cvukoj {
  stop-color: var(--svg-color--675655, #675655);
  stop-opacity: 0;
}

.zkb-swu-c {
  stop-color: var(--svg-color--534445, #534445);
  stop-opacity: 0;
}

.zv7vnvb8h {
  d: path("M10.288 13.602a1.64 1.64 0 0 1-.904-.309v.931c0 .893.532 1.689 1.34 2.02a4.1 4.1 0 0 1-.345-1.18z");
}

.zwo50zm6y {
  stop-color: var(--svg-color--484646, #484646);
  stop-opacity: 0;
}

.zxhnj4bqq {
  stop-color: var(--svg-color--eae5f7, #EAE5F7);
}

.zzkrmpd6m {
  stop-color: var(--svg-color--281919, #281919);
}

</style>
