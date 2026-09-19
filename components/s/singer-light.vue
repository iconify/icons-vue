<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iEBpaBc)"><path class="jcqxl8b5s"/><path fill="url(#iXFlnfU)" class="lo-fmbbpb"/></g><path fill="url(#i3O6tsw)" class="df35bcbhy"/><path fill="url(#iWeaGge)" class="df35bcbhy"/><path fill="url(#i8ASabe)" class="i4c7gf1nk"/><path fill="url(#iBPwj9b)" class="i4c7gf1nk"/><path fill="url(#iA0fDPb)" class="g-2q6vgre"/><path fill="url(#iLIsCdb)" class="g-2q6vgre"/><path fill="url(#ic6GODe)" class="g-2q6vgre"/><path fill="url(#idgJIee)" class="g-2q6vgre"/><path fill="url(#iDyZIMe)" class="u0q_obb8r"/><path fill="url(#i9uzLSc)" class="u0q_obb8r"/><path fill="url(#ibclZGb)" class="u0q_obb8r"/><path fill="url(#iQ98CNC)" class="u0q_obb8r"/><path fill="url(#i5xJVwd)" class="u0q_obb8r"/><path fill="url(#iQx0jab)" class="w4q61yb8g"/><path fill="url(#ikloHad)" class="wiodrpp6l"/><path fill="url(#iFyhDHb)" class="cun4e9f-e"/><path fill="url(#iVeTNJB)" class="m9f_4xbpp"/><path fill="url(#izPx5bc)" class="m9f_4xbpp"/><path fill="url(#iYF0vvd)" class="m9f_4xbpp"/><path fill="url(#iBlUQJb)" class="hermhta_f"/><path fill="url(#iSy5w9b)" class="hermhta_f"/><path fill="url(#iI9zMWX)" class="afufpnb6s"/><path fill="url(#iCkmqGB)" class="afufpnb6s"/><path fill="url(#iSFmeKc)" class="afufpnb6s"/><path fill="url(#iZvUCMe)" class="afufpnb6s"/><g filter="url(#icK4n7d)"><path fill="url(#iJh6oKe)" class="rgp37jb6d"/><path fill="url(#ixrxomN)" class="rgp37jb6d"/><path fill="url(#imRN4ac)" class="rgp37jb6d"/></g><path fill="url(#ij3ewQb)" class="pej7ph77g"/><path fill="url(#iH4wEId)" class="pej7ph77g"/><path fill="url(#i7520Ab)" class="pej7ph77g"/><g filter="url(#iJV1Ise)"><path fill="url(#iqvqfsd)" class="flvbp4biy"/></g><g filter="url(#igxv0vc)"><circle fill="url(#idiYXgd)" class="a6y6-g7uw"/></g><g filter="url(#iRp037d)"><circle fill="url(#iduqbVx)" class="tyj09bbmz"/><circle fill="url(#iNEGdue)" class="tyj09bbmz"/></g><g filter="url(#iNmj8Qg)"><path fill="url(#i7E2VTd)" class="fk97krmxu"/><path fill="url(#iw4u0fe)" class="fk97krmxu"/><path fill="url(#i8SWTub)" class="fk97krmxu"/><path fill="url(#iJMZOEd)" class="fk97krmxu"/><path fill="url(#i8rKfpc)" class="fk97krmxu"/></g><g filter="url(#iyRlQze)"><path fill="url(#i2QeA7b)" class="fk97krmxu"/><path fill="url(#ilu2njK)" class="fk97krmxu"/><path fill="url(#is2VNye)" class="fk97krmxu"/><path fill="url(#i5Q6SSb)" class="fk97krmxu"/><path fill="url(#ibymVJd)" class="fk97krmxu"/></g><path fill="url(#i8z2Ydc)" class="fk97krmxu"/><g filter="url(#iZtfnxe)"><path stroke="url(#it6XFMZ)" class="d0mmm9b4e"/></g><g filter="url(#ivq3Sqb)"><path stroke="url(#i99kP9c)" class="t4qzv1a_c"/></g><g filter="url(#i3b0wAd)"><path stroke="url(#i4XXyNd)" class="gu_vetbpq"/></g><path fill="url(#iX0cTyb)" class="wd-lahbcd"/><path fill="url(#iGXpa7d)" class="y6pg1ac6x"/><g filter="url(#iJelrid)"><path fill="url(#iI9vYgb)" class="n1rziy04p"/></g><path fill="url(#it5knMc)" class="n1rziy04p"/><path fill="url(#ifnFNge)" class="n1rziy04p"/><path fill="url(#iQ8H8Zc)" class="n1rziy04p"/><path fill="url(#ilGmhOc)" class="n1rziy04p"/><path fill="url(#iOQzRyc)" class="n1rziy04p"/><path fill="url(#i3CWNPe)" class="n1rziy04p"/><path fill="url(#iZpMgic)" class="n1rziy04p"/><g filter="url(#i3wImXb)"><path class="x1f6tb8tf"/></g><g filter="url(#idpjKBb)"><path class="sy6d7pk7v"/><path fill="url(#iMR0wwc)" class="th3pfkb5a"/><path fill="url(#iS1bEud)" class="th3pfkb5a"/><path fill="url(#i82cXOb)" class="th3pfkb5a"/><path fill="url(#iGZmFAc)" class="th3pfkb5a"/><path fill="url(#i1oJlIZ)" class="th3pfkb5a"/></g><path fill="url(#i7eNm5c)" class="nu2pufskf"/><path fill="url(#ib6Qk8c)" class="nu2pufskf"/><g filter="url(#iOWRzyb)"><path stroke="url(#iCk9Lcb)" class="s_xenjqok"/></g><path fill="url(#ie8oald)" class="gwuidobvq"/><g filter="url(#iaqhOWu)"><path fill="url(#i7r22XZ)" class="h22liacde"/><path fill="url(#iOxj3De)" class="h22liacde"/><path fill="url(#iwB65ib)" class="h22liacde"/><path fill="url(#iCYepee)" class="h22liacde"/><path fill="url(#iwPnuhG)" class="h22liacde"/></g><g filter="url(#iyX88we)"><path class="v_vak_bqs"/></g><g filter="url(#iyXKrsc)"><path class="o6y3inocw"/></g><g filter="url(#iTkk1uv)"><path class="sgr5pgbdc"/><path fill="url(#iCnfVSC)" class="id_kmv85a"/><path fill="url(#isGlnqc)" class="id_kmv85a"/></g><g filter="url(#ivJopsc)"><path class="utuwn8bka"/><path fill="url(#iqXPmfd)" class="tfvicabxd"/><path fill="url(#iTmUtbc)" class="tfvicabxd"/><path fill="url(#ioCvMce)" class="tfvicabxd"/></g><path class="a4rlmccjk"/><path fill="url(#iYpBNFc)" class="qd7mo_tmu"/><path class="b8gbq2b3g"/><g filter="url(#ijXcQcd)"><path class="u6yfg2bxw"/><path fill="url(#icDoFre)" class="ok8c2wwnd"/></g><g filter="url(#i2Gfb3c)"><path fill="url(#i6c1LpL)" class="lsqjnabcm"/></g><path class="rq3o4j_li"/><path fill="url(#ij5DmBe)" class="schxz9brm"/><path class="dy8v3qbbv"/><g filter="url(#irSmySd)"><path fill="url(#il48gxc)" class="r4_7h8b7x"/></g><g filter="url(#is0hizR)"><ellipse transform="rotate(-27.914 12.644 11.32)" class="qtl5eyb7j"/><ellipse fill="url(#iPxc2sP)" transform="rotate(-27.914 12.644 11.32)" class="md5uzqs3z"/></g><path fill="url(#iu2nseb)" class="y3z4eqobc"/><path fill="url(#iLDIqEb)" class="y3z4eqobc"/><path fill="url(#ikrIqTc)" class="y3z4eqobc"/><path fill="url(#igoxqjH)" class="y3z4eqobc"/><path fill="url(#i2CEYGe)" class="q_js7pcgc"/><path fill="url(#i4AgJBc)" class="q_js7pcgc"/><g filter="url(#ioG7TmG)"><path fill="url(#ijxFftc)" class="qw36p19is"/></g><g filter="url(#ileQpMe)"><path fill="url(#ipBuVXc)" class="qumd8gbzx"/></g><g filter="url(#imejd0b)"><path class="cy4714b5o"/></g><g filter="url(#iigoYxc)"><path class="d1t5g4bps"/></g><defs><radialGradient id="i3O6tsw" cx="0" cy="0" r="1" gradientTransform="matrix(3.125 1 -2.08207 6.50646 3.708 25.614)" gradientUnits="userSpaceOnUse"><stop offset=".176" class="li28y9bsf"/><stop offset="1" class="o1jwunhtj"/></radialGradient><radialGradient id="i8ASabe" cx="0" cy="0" r="1" gradientTransform="rotate(110.288 4.667 19.546)scale(5.49596 3.74438)" gradientUnits="userSpaceOnUse"><stop class="oe2xm9ikp"/><stop offset="1" class="d6d59o0ou"/></radialGradient><radialGradient id="ic6GODe" cx="0" cy="0" r="1" gradientTransform="matrix(-2.71872 5.59376 -.25587 -.12436 24.239 17.896)" gradientUnits="userSpaceOnUse"><stop class="mnp72frot"/><stop offset="1" class="l4rg4-bid"/></radialGradient><radialGradient id="i9uzLSc" cx="0" cy="0" r="1" gradientTransform="rotate(-101.597 18.161 8.93)scale(6.81742 .9881)" gradientUnits="userSpaceOnUse"><stop class="rzqjthgas"/><stop offset="1" class="ejynn6b3w"/></radialGradient><radialGradient id="iQ98CNC" cx="0" cy="0" r="1" gradientTransform="matrix(-1.80897 .6578 -1.95135 -5.36624 12.187 17.781)" gradientUnits="userSpaceOnUse"><stop class="i03-jcbks"/><stop offset="1" class="m27qtcbgg"/></radialGradient><radialGradient id="iVeTNJB" cx="0" cy="0" r="1" gradientTransform="matrix(0 9.50857 -5.52096 0 15.106 20.262)" gradientUnits="userSpaceOnUse"><stop offset=".092" class="vla5fnbfs"/><stop offset=".905" class="oi9-i7f4a"/></radialGradient><radialGradient id="izPx5bc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -7.08205 11.2731 0 15.106 24.206)" gradientUnits="userSpaceOnUse"><stop offset=".717" class="qgzgmyhdj"/><stop offset=".937" class="dzrlfbban"/></radialGradient><radialGradient id="iBlUQJb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.36264 1.13067 -1.10926 -2.3179 28.941 21.854)" gradientUnits="userSpaceOnUse"><stop offset=".524" class="tj2vllbvr"/><stop offset=".956" class="fop80r8ws"/></radialGradient><radialGradient id="iSy5w9b" cx="0" cy="0" r="1" gradientTransform="matrix(.84335 -.64209 .49204 .64628 28.086 21.363)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="q7l79-2rh"/><stop offset="1" class="aszpk2bre"/></radialGradient><radialGradient id="iCkmqGB" cx="0" cy="0" r="1" gradientTransform="rotate(148.849 11.3 12.08)scale(4.17157)" gradientUnits="userSpaceOnUse"><stop offset=".838" class="wc1l7vbis"/><stop offset="1" class="oa317xagd"/></radialGradient><radialGradient id="iSFmeKc" cx="0" cy="0" r="1" gradientTransform="matrix(1.26514 1.24827 -2.90348 2.94272 23.842 15.211)" gradientUnits="userSpaceOnUse"><stop class="ky_indbcd"/><stop offset="1" class="s_ufbeclz"/></radialGradient><radialGradient id="iZvUCMe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.37479 2.10625 0 26.912 16.569)" gradientUnits="userSpaceOnUse"><stop class="qkb33eb6n"/><stop offset="1" class="q-0s8ibrs"/></radialGradient><radialGradient id="ixrxomN" cx="0" cy="0" r="1" gradientTransform="matrix(0 .4408 -2.66861 0 27.506 16.96)" gradientUnits="userSpaceOnUse"><stop class="zxhnj4bqq"/><stop offset="1" class="hf-5q38gm"/></radialGradient><radialGradient id="iqvqfsd" cx="0" cy="0" r="1" gradientTransform="matrix(-.4998 .66245 -.66245 -.4998 25.98 20.831)" gradientUnits="userSpaceOnUse"><stop class="dg3rcdvoo"/><stop offset="1" class="r0tyikbvd"/></radialGradient><radialGradient id="idiYXgd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.39063 -2.6875 6.04551 -3.1282 15.925 20.105)" gradientUnits="userSpaceOnUse"><stop offset=".148" class="q1ssh2bkr"/><stop offset="1" class="bxgr47tif"/></radialGradient><radialGradient id="iduqbVx" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.5843 -1.90116 0 15.15 18.44)" gradientUnits="userSpaceOnUse"><stop class="gni8qzbvw"/><stop offset=".678" class="s562n-brd"/></radialGradient><radialGradient id="iNEGdue" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.20271 -3.11798 0 13.528 17.765)" gradientUnits="userSpaceOnUse"><stop offset=".283" class="l47zbgb1p"/><stop offset="1" class="j7xq08bnc"/></radialGradient><radialGradient id="iw4u0fe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8787 -1.6371 0 26.073 23.37)" gradientUnits="userSpaceOnUse"><stop offset=".106" class="yhi4l7bah"/><stop offset="1" class="sbugs4b_s"/></radialGradient><radialGradient id="i8SWTub" cx="0" cy="0" r="1" gradientTransform="matrix(0 .94192 -1.75486 0 26.073 24.788)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="yhi4l7bah"/><stop offset="1" class="sbugs4b_s"/></radialGradient><radialGradient id="iJMZOEd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .78779 -1.4677 0 26.073 26.158)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="yhi4l7bah"/><stop offset="1" class="sbugs4b_s"/></radialGradient><radialGradient id="i8rKfpc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .87616 -2.08784 0 26.073 27.64)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="yhi4l7bah"/><stop offset="1" class="sbugs4b_s"/></radialGradient><radialGradient id="ilu2njK" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8787 -1.6371 0 26.073 23.37)" gradientUnits="userSpaceOnUse"><stop offset=".106" class="uzac_3qef"/><stop offset="1" class="b570nlb5r"/></radialGradient><radialGradient id="is2VNye" cx="0" cy="0" r="1" gradientTransform="matrix(0 .94192 -1.75486 0 26.073 24.788)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="uzac_3qef"/><stop offset="1" class="b570nlb5r"/></radialGradient><radialGradient id="i5Q6SSb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .78779 -1.4677 0 26.073 26.158)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="uzac_3qef"/><stop offset="1" class="b570nlb5r"/></radialGradient><radialGradient id="ibymVJd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .87616 -2.08784 0 26.073 27.64)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="uzac_3qef"/><stop offset="1" class="b570nlb5r"/></radialGradient><radialGradient id="i8z2Ydc" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.49946 -4.50112 0 28.605 23.016)" gradientUnits="userSpaceOnUse"><stop class="b4rjnnb6m"/><stop offset="1" class="bgp-eqwmb"/></radialGradient><radialGradient id="iX0cTyb" cx="0" cy="0" r="1" gradientTransform="rotate(69.657 .387 20.902)scale(2.15387 2.55864)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="xsgkrbcbf"/><stop offset="1" class="ek_f7q3hx"/></radialGradient><radialGradient id="iGXpa7d" cx="0" cy="0" r="1" gradientTransform="matrix(1.47646 .46403 -1.43156 4.55498 9.041 13.763)" gradientUnits="userSpaceOnUse"><stop class="oaig2cbln"/><stop offset=".746" class="gfuj0ibqm"/></radialGradient><radialGradient id="iI9vYgb" cx="0" cy="0" r="1" gradientTransform="matrix(-5.22784 0 0 -9.248 17.905 12.332)" gradientUnits="userSpaceOnUse"><stop class="yzaj_tb_p"/><stop offset="1" class="ny0rq0bux"/></radialGradient><radialGradient id="ifnFNge" cx="0" cy="0" r="1" gradientTransform="matrix(0 12.6002 -10.4345 0 16.68 6.16)" gradientUnits="userSpaceOnUse"><stop offset=".728" class="ela9eybsj"/><stop offset="1" class="x31umkbcn"/></radialGradient><radialGradient id="iQ8H8Zc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.14835 1.42108 0 17.545 11.019)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="h739mqb_c"/><stop offset="1" class="px0sb7ebt"/></radialGradient><radialGradient id="ilGmhOc" cx="0" cy="0" r="1" gradientTransform="matrix(.00393 -1.09427 1.19083 .00428 12.797 11.065)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="kxaprmbjh"/><stop offset="1" class="vgn1hf8dm"/></radialGradient><radialGradient id="iOQzRyc" cx="0" cy="0" r="1" gradientTransform="matrix(-8.49597 .5363 -1.37 -21.7029 18.53 13.32)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="uwe7yhbem"/><stop offset="1" class="snpr2ctwr"/></radialGradient><radialGradient id="i3CWNPe" cx="0" cy="0" r="1" gradientTransform="matrix(3.0984 -3.27776 1.1999 1.13424 9.63 8.006)" gradientUnits="userSpaceOnUse"><stop offset=".428" class="mqqgujbcq"/><stop offset="1" class="fki8vhbsq"/></radialGradient><radialGradient id="iZpMgic" cx="0" cy="0" r="1" gradientTransform="matrix(-1.74316 2.88295 -2.3801 -1.43912 17.525 7.352)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="lombttb9q"/><stop offset="1" class="bvf2i9bjf"/></radialGradient><radialGradient id="iS1bEud" cx="0" cy="0" r="1" gradientTransform="matrix(0 .2441 -.76718 0 15.564 13.692)" gradientUnits="userSpaceOnUse"><stop class="t40345qox"/><stop offset="1" class="mrnsdcbqx"/></radialGradient><radialGradient id="iGZmFAc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.52115 .69743 -1.12083 -2.4446 15.68 13.123)" gradientUnits="userSpaceOnUse"><stop offset=".714" class="o0aif1l1c"/><stop offset="1" class="vni43obah"/></radialGradient><radialGradient id="i7eNm5c" cx="0" cy="0" r="1" gradientTransform="matrix(-2.9117 6.52447 -8.23836 -3.67657 14.666 6.713)" gradientUnits="userSpaceOnUse"><stop class="jy25td8rp"/><stop offset="1" class="xftsofb3t"/></radialGradient><radialGradient id="ib6Qk8c" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.29688 1.23651 0 13.134 11.182)" gradientUnits="userSpaceOnUse"><stop offset=".545" class="hkf1_jbsj"/><stop offset="1" class="wrhkd7bsy"/></radialGradient><radialGradient id="ie8oald" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.72074 2.8997 0 15.098 15.87)" gradientUnits="userSpaceOnUse"><stop class="jase_0f7h"/><stop offset="1" class="zn-qjxbde"/></radialGradient><radialGradient id="iOxj3De" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.50132 8.85443 0 9.868 9.44)" gradientUnits="userSpaceOnUse"><stop offset=".536" class="ibt06e6rm"/><stop offset="1" class="k45xjwbmq"/></radialGradient><radialGradient id="iwB65ib" cx="0" cy="0" r="1" gradientTransform="rotate(-87.401 15.603 -5.068)scale(2.51513 4.45631)" gradientUnits="userSpaceOnUse"><stop class="c98z413ze"/><stop offset="1" class="ovvtmacpn"/></radialGradient><radialGradient id="iCYepee" cx="0" cy="0" r="1" gradientTransform="rotate(-146.667 10.272 -.638)scale(2.82328 2.07243)" gradientUnits="userSpaceOnUse"><stop class="wyv1gnbxf"/><stop offset="1" class="z6d-f52gr"/></radialGradient><radialGradient id="iwPnuhG" cx="0" cy="0" r="1" gradientTransform="matrix(.90512 1.475 -3.41539 2.09582 14.192 2.88)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="qco-2_b3r"/><stop offset="1" class="zwo50zm6y"/></radialGradient><radialGradient id="iCnfVSC" cx="0" cy="0" r="1" gradientTransform="matrix(-2.20112 0 0 -.81692 15.351 5.14)" gradientUnits="userSpaceOnUse"><stop class="axstwemrb"/><stop offset="1" class="ez41_pbnb"/></radialGradient><radialGradient id="isGlnqc" cx="0" cy="0" r="1" gradientTransform="matrix(3.21816 -5.09543 5.64521 3.5654 9.667 9.082)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="hnw0p1utu"/><stop offset=".311" class="dwl_ftd7p"/><stop offset="1" class="fch_lgr5q"/></radialGradient><radialGradient id="iqXPmfd" cx="0" cy="0" r="1" gradientTransform="matrix(3.05838 0 0 1.19577 18.512 5.917)" gradientUnits="userSpaceOnUse"><stop class="nszf4yi9c"/><stop offset="1" class="a061yvbds"/></radialGradient><radialGradient id="iTmUtbc" cx="0" cy="0" r="1" gradientTransform="matrix(2.67872 -2.55217 4.67237 4.90405 17.731 8.954)" gradientUnits="userSpaceOnUse"><stop offset=".857" class="stq0hsb2e"/><stop offset="1" class="i6xvtdb8e"/></radialGradient><radialGradient id="ioCvMce" cx="0" cy="0" r="1" gradientTransform="matrix(3.2482 .37966 -.15896 1.35996 16.845 7.478)" gradientUnits="userSpaceOnUse"><stop class="unyhdjbdq"/><stop offset="1" class="w0a4mmrgb"/></radialGradient><radialGradient id="iYpBNFc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.29049 0 17.28 11.415)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="icDoFre" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 11.342 1.574)scale(.37829 .52081)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ij5DmBe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81136 -1.29056 0 12.915 11.415)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="iPxc2sP" cx="0" cy="0" r="1" gradientTransform="matrix(-.00774 -.49408 .59392 -.0093 12.63 11.633)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iLDIqEb" cx="0" cy="0" r="1" gradientTransform="matrix(.62855 2.24327 -2.14025 .59968 19.715 11.43)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="uuzk4vb7h"/><stop offset="1" class="yor2p9b5i"/></radialGradient><radialGradient id="ikrIqTc" cx="0" cy="0" r="1" gradientTransform="matrix(.78778 -1.0811 .90618 .66032 20.076 11.974)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="iz6q0pbtm"/><stop offset="1" class="wmov6-bei"/></radialGradient><radialGradient id="igoxqjH" cx="0" cy="0" r="1" gradientTransform="matrix(.587 -1.55042 2.07158 .7843 20.19 12.146)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="r8tuldb4n"/><stop offset="1" class="c_6967ufg"/></radialGradient><radialGradient id="i4AgJBc" cx="0" cy="0" r="1" gradientTransform="rotate(-173.034 5.458 5.726)scale(1.62516 1.74453)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="o8wr4h7sd"/><stop offset="1" class="t0w03e0rr"/></radialGradient><radialGradient id="ijxFftc" cx="0" cy="0" r="1" gradientTransform="matrix(-.91648 .15731 -.19303 -1.12456 10.183 12.072)" gradientUnits="userSpaceOnUse"><stop class="ab9g3hmui"/><stop offset="1" class="bwc1tpbev"/></radialGradient><linearGradient id="iXFlnfU" x1="16.901" x2="15.504" y1="26.136" y2="25.833" gradientUnits="userSpaceOnUse"><stop class="k6k-6oblx"/><stop offset="1" class="l5x5or5jn"/></linearGradient><linearGradient id="iWeaGge" x1="7.199" x2="6.027" y1="25.935" y2="25.935" gradientUnits="userSpaceOnUse"><stop class="xfetrrneo"/><stop offset="1" class="n0fg5jb7h"/></linearGradient><linearGradient id="iBPwj9b" x1="23.128" x2="23.77" y1="26.021" y2="25.989" gradientUnits="userSpaceOnUse"><stop offset=".478" class="g2cjljmej"/><stop offset="1" class="h5gp5h3ar"/></linearGradient><linearGradient id="iA0fDPb" x1="22.77" x2="18.395" y1="16.006" y2="28.516" gradientUnits="userSpaceOnUse"><stop class="qm8srpk6b"/><stop offset="1" class="knnk86b5x"/></linearGradient><linearGradient id="iLIsCdb" x1="16.824" x2="17.431" y1="26.506" y2="26.57" gradientUnits="userSpaceOnUse"><stop class="o_frn_b6l"/><stop offset="1" class="ohgvqyqas"/></linearGradient><linearGradient id="idgJIee" x1="20.787" x2="20.787" y1="16.006" y2="16.828" gradientUnits="userSpaceOnUse"><stop offset=".165" class="oy7fe6bjb"/><stop offset="1" class="ivc982b0q"/></linearGradient><linearGradient id="iDyZIMe" x1="7.895" x2="11.895" y1="17.646" y2="28.896" gradientUnits="userSpaceOnUse"><stop class="e55i1-bjj"/><stop offset="1" class="rqyrdfbps"/></linearGradient><linearGradient id="ibclZGb" x1="8.35" x2="9.063" y1="15.259" y2="19.316" gradientUnits="userSpaceOnUse"><stop class="agyv0c9kf"/><stop offset="1" class="vxg8xmb_d"/></linearGradient><linearGradient id="i5xJVwd" x1="7.895" x2="8.309" y1="22.583" y2="22.38" gradientUnits="userSpaceOnUse"><stop class="maqiohbml"/><stop offset="1" class="qndc1xila"/></linearGradient><linearGradient id="iQx0jab" x1="23.395" x2="21.614" y1="26.052" y2="26.052" gradientUnits="userSpaceOnUse"><stop class="tsgwb3b4a"/><stop offset="1" class="nvk1b4bey"/></linearGradient><linearGradient id="ikloHad" x1="8.114" x2="10.395" y1="27.864" y2="26.708" gradientUnits="userSpaceOnUse"><stop class="h1snaz72e"/><stop offset="1" class="kvxpklbcz"/></linearGradient><linearGradient id="iFyhDHb" x1="15.111" x2="15.111" y1="17.406" y2="28.51" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="iYF0vvd" x1="17.886" x2="15.925" y1="22.096" y2="21.768" gradientUnits="userSpaceOnUse"><stop offset=".196" class="ipymgraih"/><stop offset=".671" class="nazw5jbsw"/></linearGradient><linearGradient id="iI9zMWX" x1="25.739" x2="25.739" y1="15.702" y2="19.759" gradientUnits="userSpaceOnUse"><stop offset=".313" class="wprwrdbxj"/><stop offset=".562" class="ax-d4eb4u"/></linearGradient><linearGradient id="iJh6oKe" x1="25.933" x2="25.792" y1="16.638" y2="17.841" gradientUnits="userSpaceOnUse"><stop offset=".12" class="qcwm1i13v"/><stop offset="1" class="s0eee-boz"/></linearGradient><linearGradient id="imRN4ac" x1="23.236" x2="23.363" y1="16.575" y2="17.011" gradientUnits="userSpaceOnUse"><stop class="wtu393bab"/><stop offset="1" class="ce_wr9jxr"/></linearGradient><linearGradient id="ij3ewQb" x1="26.936" x2="24.648" y1="21.145" y2="21.145" gradientUnits="userSpaceOnUse"><stop class="j-x55pbxn"/><stop offset="1" class="zg05wl6cw"/></linearGradient><linearGradient id="iH4wEId" x1="24.466" x2="24.847" y1="20.987" y2="20.959" gradientUnits="userSpaceOnUse"><stop class="fs7-dablt"/><stop offset="1" class="zg97ljbvw"/></linearGradient><linearGradient id="i7520Ab" x1="27.084" x2="26.822" y1="20.859" y2="20.835" gradientUnits="userSpaceOnUse"><stop class="qna0z9q7a"/><stop offset="1" class="toldersuv"/></linearGradient><linearGradient id="i7E2VTd" x1="27.996" x2="23.128" y1="26.392" y2="26.392" gradientUnits="userSpaceOnUse"><stop offset=".146" class="hqh-1rbea"/><stop offset=".861" class="id19t5fes"/></linearGradient><linearGradient id="i2QeA7b" x1="27.996" x2="23.128" y1="26.392" y2="26.392" gradientUnits="userSpaceOnUse"><stop offset=".146" class="v5rheyc4i"/><stop offset=".861" class="j1qr75obr"/></linearGradient><linearGradient id="it6XFMZ" x1="23.742" x2="25.663" y1="24.189" y2="24.189" gradientUnits="userSpaceOnUse"><stop class="vx-77wbda"/><stop offset="1" class="r0p9vfbnw"/></linearGradient><linearGradient id="i99kP9c" x1="23.742" x2="25.663" y1="25.631" y2="25.631" gradientUnits="userSpaceOnUse"><stop class="vx-77wbda"/><stop offset="1" class="r0p9vfbnw"/></linearGradient><linearGradient id="i4XXyNd" x1="23.742" x2="25.663" y1="27.061" y2="27.061" gradientUnits="userSpaceOnUse"><stop class="vx-77wbda"/><stop offset="1" class="r0p9vfbnw"/></linearGradient><linearGradient id="it5knMc" x1="20.255" x2="15.902" y1="14.017" y2="14.017" gradientUnits="userSpaceOnUse"><stop class="z1p__59we"/><stop offset="1" class="y6b283b4c"/></linearGradient><linearGradient id="iMR0wwc" x1="15.936" x2="15.098" y1="13.006" y2="13.041" gradientUnits="userSpaceOnUse"><stop offset=".36" class="af2d-kbww"/><stop offset="1" class="fkbu2fb2z"/></linearGradient><linearGradient id="i82cXOb" x1="15.098" x2="15.098" y1="14.146" y2="13.681" gradientUnits="userSpaceOnUse"><stop class="y8u9aob3m"/><stop offset="1" class="w22vs7beb"/></linearGradient><linearGradient id="i1oJlIZ" x1="15.098" x2="15.098" y1="11.312" y2="11.987" gradientUnits="userSpaceOnUse"><stop class="au2s26bkj"/><stop offset="1" class="e0f0u6bhi"/></linearGradient><linearGradient id="iCk9Lcb" x1="13.896" x2="14.214" y1="15.716" y2="14.882" gradientUnits="userSpaceOnUse"><stop class="c2rd33bbv"/><stop offset="1" class="zcdcyccef"/></linearGradient><linearGradient id="i7r22XZ" x1="21.95" x2="10.337" y1="6.669" y2="6.669" gradientUnits="userSpaceOnUse"><stop class="l1vex1b6a"/><stop offset="1" class="kydculhfm"/></linearGradient><linearGradient id="i6c1LpL" x1="18.058" x2="17.744" y1="11.469" y2="11.662" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="il48gxc" x1="13.659" x2="13.346" y1="11.469" y2="11.662" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iu2nseb" x1="21.534" x2="20.327" y1="11.496" y2="13.672" gradientUnits="userSpaceOnUse"><stop class="r7o08-b3s"/><stop offset="1" class="g6f16-bty"/></linearGradient><linearGradient id="i2CEYGe" x1="9.248" x2="10.706" y1="12.2" y2="12.073" gradientUnits="userSpaceOnUse"><stop class="mlsv8jb5y"/><stop offset="1" class="l7gss9bru"/></linearGradient><linearGradient id="ipBuVXc" x1="20.577" x2="20.577" y1="11.125" y2="13.028" gradientUnits="userSpaceOnUse"><stop class="q26gyrbrn"/><stop offset="1" class="ihk5xnqly"/></linearGradient><filter id="iEBpaBc" width="5.513" height="4.74" x="12.848" y="23.766" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.976471 0 0 0 0 0.780392 0 0 0 0 0.866667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2324"/></filter><filter id="icK4n7d" width="6.102" height="1.228" x="22.791" y="16.476" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.05"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.647059 0 0 0 0 0.47451 0 0 0 0 0.54902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2324"/></filter><filter id="iJV1Ise" width="1.075" height="1.075" x="25.198" y="20.609" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".025"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.694118 0 0 0 0 0.560784 0 0 0 0 0.764706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2324"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".025"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.917647 0 0 0 0 0.87451 0 0 0 0 0.976471 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2324" result="effect2_innerShadow_4002_2324"/></filter><filter id="igxv0vc" width="5.967" height="5.967" x="12.166" y="14.673" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2324" stdDeviation=".125"/></filter><filter id="iRp037d" width="5.612" height="5.612" x="12.343" y="14.959" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2324" stdDeviation=".2"/></filter><filter id="iNmj8Qg" width="5.369" height="6.076" x="23.128" y="22.44" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.658824 0 0 0 0 0.443137 0 0 0 0 0.411765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2324"/></filter><filter id="iyRlQze" width="5.369" height="6.076" x="23.128" y="22.44" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.729412 0 0 0 0 0.509804 0 0 0 0 0.603922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2324"/></filter><filter id="iZtfnxe" width="2.319" height=".3" x="23.592" y="23.961" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2324" stdDeviation=".05"/></filter><filter id="ivq3Sqb" width="2.319" height=".3" x="23.592" y="25.403" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2324" stdDeviation=".05"/></filter><filter id="i3b0wAd" width="2.319" height=".3" x="23.592" y="26.833" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2324" stdDeviation=".05"/></filter><filter id="iJelrid" width="11.22" height="12.542" x="10.034" y="6.161" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".7"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.913725 0 0 0 0 0.686275 0 0 0 0 0.592157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2324"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.780392 0 0 0 0 0.568627 0 0 0 0 0.486275 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2324" result="effect2_innerShadow_4002_2324"/></filter><filter id="i3wImXb" width="3.747" height="4.9" x="13.082" y="10.502" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2324" stdDeviation=".5"/></filter><filter id="idpjKBb" width="2.277" height="3.3" x="13.959" y="11.111" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2324" stdDeviation=".1"/></filter><filter id="iOWRzyb" width="3.718" height="1.573" x="13.238" y="14.632" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2324" stdDeviation=".05"/></filter><filter id="iaqhOWu" width="12.873" height="8.357" x="8.661" y="2.984" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.137255 0 0 0 0 0.0901961 0 0 0 0 0.145098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2324"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0784314 0 0 0 0 0.0352941 0 0 0 0 0.0470588 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2324" result="effect2_innerShadow_4002_2324"/></filter><filter id="iyX88we" width="2.339" height="1.19" x="16.687" y="8.648" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0588235 0 0 0 0 0.054902 0 0 0 0 0.0588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2324"/></filter><filter id="iyXKrsc" width="2.339" height="1.176" x="11.431" y="8.663" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0588235 0 0 0 0 0.054902 0 0 0 0 0.0588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2324"/></filter><filter id="iTkk1uv" width="6.734" height="5.992" x="9.017" y="4.073" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.286275 0 0 0 0 0.243137 0 0 0 0 0.227451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2324"/><feGaussianBlur result="effect2_foregroundBlur_4002_2324" stdDeviation=".125"/></filter><filter id="ivJopsc" width="6.361" height="5.736" x="14.939" y="4.497" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2324" stdDeviation=".125"/></filter><filter id="ijXcQcd" width=".787" height=".696" x="16.545" y="10.975" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2324" stdDeviation=".05"/></filter><filter id="i2Gfb3c" width=".891" height=".913" x="17.385" y="11.05" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2324" stdDeviation=".1"/></filter><filter id="irSmySd" width=".986" height="1.04" x="12.943" y="10.987" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2324" stdDeviation=".1"/></filter><filter id="is0hizR" width=".913" height=".705" x="12.188" y="10.967" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2324" stdDeviation=".05"/></filter><filter id="ioG7TmG" width="1.329" height="2.379" x="9.017" y="10.883" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2324" stdDeviation=".125"/></filter><filter id="ileQpMe" width="1.947" height="2.903" x="19.603" y="10.625" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2324" stdDeviation=".25"/></filter><filter id="imejd0b" width="2.405" height="1.16" x="11.349" y="8.737" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2324" stdDeviation=".125"/></filter><filter id="iigoYxc" width="2.405" height="1.16" x="16.628" y="8.691" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2324" stdDeviation=".125"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:singer-light" /></template>
<style>
.a061yvbds {
  stop-color: var(--svg-color--4e494b, #4E494B);
  stop-opacity: 0;
}

.a4rlmccjk {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.489 10.667c.653 0 1.204.45 1.354 1.058a.274.274 0 0 1-.267.341h-2.231a.23.23 0 0 1-.228-.272a1.4 1.4 0 0 1 1.371-1.128");
}

.a6y6-g7uw {
  cx: 15.149px;
  cy: 17.656px;
  r: 2.734px;
}

.ab9g3hmui {
  stop-color: var(--svg-color--c18472, #C18472);
}

.af2d-kbww {
  stop-color: var(--svg-color--ffdfc7, #FFDFC7);
}

.afufpnb6s {
  d: path("M25.766 19.705a2.498 2.498 0 1 0 0-4.997a2.498 2.498 0 0 0 0 4.996");
}

.agyv0c9kf {
  stop-color: var(--svg-color--c46d3a, #C46D3A);
}

.aszpk2bre {
  stop-color: var(--svg-color--f7ceb9, #F7CEB9);
  stop-opacity: 0;
}

.au2s26bkj {
  stop-color: var(--svg-color--e8bba8, #E8BBA8);
}

.ax-d4eb4u {
  stop-color: var(--svg-color--562d79, #562D79);
}

.axstwemrb {
  stop-color: var(--svg-color--423c3f, #423C3F);
}

.b4rjnnb6m {
  stop-color: var(--svg-color--ffe0c3, #FFE0C3);
}

.b570nlb5r {
  stop-color: var(--svg-color--ffd1bb, #FFD1BB);
  stop-opacity: 0;
}

.b8gbq2b3g {
  fill: var(--svg-color--000, #000);
  d: path("M16.77 11.83a.51.51 0 0 1 .512-.51a.51.51 0 0 1 .454.746h-.905a.46.46 0 0 1-.06-.235");
}

.bbyb_mbsk {
  stop-color: var(--svg-color--664842, #664842);
}

.bgp-eqwmb {
  stop-color: var(--svg-color--ffe0c3, #FFE0C3);
  stop-opacity: 0;
}

.bvf2i9bjf {
  stop-color: var(--svg-color--f6c3b0, #F6C3B0);
  stop-opacity: 0;
}

.bwc1tpbev {
  stop-color: var(--svg-color--ca8b7a, #CA8B7A);
}

.bxgr47tif {
  stop-color: var(--svg-color--d48070, #D48070);
}

.c_6967ufg {
  stop-color: var(--svg-color--ebbb9d, #EBBB9D);
}

.c2rd33bbv {
  stop-color: var(--svg-color--e1aca6, #E1ACA6);
}

.c98z413ze {
  stop-color: var(--svg-color--4f4d4d, #4F4D4D);
}

.ce_wr9jxr {
  stop-color: var(--svg-color--b19a83, #B19A83);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cun4e9f-e {
  d: path("M15.118 17.406c-1.16 0-2.3.17-3.38.49l1.1 5.87c.72.28 1.5.44 2.32.44c.77 0 1.51-.14 2.19-.38l1.11-5.92c-1.05-.33-2.18-.5-3.34-.5");
}

.cy4714b5o {
  stroke: var(--svg-color--353535, #353535);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M11.724 9.523c.257-.185.898-.51 1.656-.382");
}

.d0mmm9b4e {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.742 24.111h2.02");
}

.d1t5g4bps {
  stroke: var(--svg-color--353535, #353535);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M18.659 9.476c-.257-.184-.898-.508-1.656-.381");
}

.d6d59o0ou {
  stop-color: var(--svg-color--4d396f, #4D396F);
}

.df35bcbhy {
  d: path("M7.078 28.506v-7.93a11.75 11.75 0 0 0-3.18 5.04l-.03.09c-.29.91-.51 1.85-.66 2.8z");
}

.dg3rcdvoo {
  stop-color: var(--svg-color--d2bfe7, #D2BFE7);
}

.dwl_ftd7p {
  stop-color: var(--svg-color--1c0c20, #1C0C20);
}

.dy8v3qbbv {
  fill: var(--svg-color--000, #000);
  d: path("M13.425 11.83a.51.51 0 0 0-.511-.51a.51.51 0 0 0-.455.746h.905a.5.5 0 0 0 .06-.235");
}

.dzrlfbban {
  stop-color: var(--svg-color--c1745e, #C1745E);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e0f0u6bhi {
  stop-color: var(--svg-color--e8bba8, #E8BBA8);
  stop-opacity: 0;
}

.e55i1-bjj {
  stop-color: var(--svg-color--e86b1f, #E86B1F);
}

.ejynn6b3w {
  stop-color: var(--svg-color--ef5945, #EF5945);
  stop-opacity: 0;
}

.ek_f7q3hx {
  stop-color: var(--svg-color--1a161e, #1A161E);
}

.ela9eybsj {
  stop-color: var(--svg-color--d08e98, #D08E98);
  stop-opacity: 0;
}

.ez41_pbnb {
  stop-color: var(--svg-color--423c3f, #423C3F);
  stop-opacity: 0;
}

.fch_lgr5q {
  stop-color: var(--svg-color--1c0c20, #1C0C20);
  stop-opacity: 0;
}

.fk97krmxu {
  d: path("M23.128 23.393c0-.44.365-.803.816-.803h3.054c.745 0 1.349.59 1.349 1.316v3.514c0 .605-.503 1.096-1.124 1.096h-3.28a.81.81 0 0 1-.816-.802c0-.315.187-.59.458-.72a.8.8 0 0 1-.457-.72a.8.8 0 0 1 .457-.72a.8.8 0 0 1-.457-.721c0-.314.186-.59.457-.72a.8.8 0 0 1-.457-.72");
}

.fkbu2fb2z {
  stop-color: var(--svg-color--ffdfc7, #FFDFC7);
  stop-opacity: 0;
}

.fki8vhbsq {
  stop-color: var(--svg-color--9f6d5c, #9F6D5C);
  stop-opacity: 0;
}

.flvbp4biy {
  d: path("M25.736 21.634a.487.487 0 1 0 0-.975a.487.487 0 0 0 0 .975");
}

.fop80r8ws {
  stop-color: var(--svg-color--c79175, #C79175);
}

.fs7-dablt {
  stop-color: var(--svg-color--a0768f, #A0768F);
}

.ft5dv1b6b {
  fill: none;
}

.g-2q6vgre {
  d: path("M24.313 16.52h-5.58l-2.274 11.996h3.149l5.325-11.017a.685.685 0 0 0-.62-.98");
}

.g2cjljmej {
  stop-color: var(--svg-color--604e83, #604E83);
}

.g6f16-bty {
  stop-color: var(--svg-color--f0b8a6, #F0B8A6);
}

.gfuj0ibqm {
  stop-color: var(--svg-color--1e191c, #1E191C);
}

.gni8qzbvw {
  stop-color: var(--svg-color--ce7d85, #CE7D85);
}

.gu_vetbpq {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.742 26.983h2.02");
}

.gwuidobvq {
  d: path("M15.098 15.228c-.508 0-.985-.12-1.386-.328c-.137-.07-.284.084-.198.209c.335.507.919.846 1.584.846c.664 0 1.248-.339 1.583-.846c.086-.13-.061-.28-.198-.21a3 3 0 0 1-1.386.329");
}

.h_j9u0wvt {
  stop-color: var(--svg-color--e6e6e6, #E6E6E6);
}

.h1snaz72e {
  stop-color: var(--svg-color--665395, #665395);
}

.h22liacde {
  d: path("M19.952 5.689c.515.177.976.536 1.268 1.05a2.37 2.37 0 0 1-.106 2.527a1.56 1.56 0 0 0-.27.874v1.188a1.7 1.7 0 0 0-.668-.268l.079-1.606a1.45 1.45 0 0 0-1.38-1.432h-1.4a2.42 2.42 0 0 1-2.211-1.443a.66.66 0 0 0-.615-.418h-1.273c-1.846 0-3.342 1.512-3.342 3.379l.03 1.537a1.7 1.7 0 0 0-.72.264v-1.2a1.56 1.56 0 0 0-.27-.875a2.39 2.39 0 0 1-.143-2.446a2.34 2.34 0 0 1 1.3-1.126a2.68 2.68 0 0 0 1.384-1.11a2.325 2.325 0 0 1 2.89-.912a1.5 1.5 0 0 0 1.194 0c.28-.118.588-.188.912-.188c.843 0 1.58.456 1.989 1.132c.307.51.79.88 1.352 1.073");
}

.h5gp5h3ar {
  stop-color: var(--svg-color--604e83, #604E83);
  stop-opacity: 0;
}

.h739mqb_c {
  stop-color: var(--svg-color--f6b8a8, #F6B8A8);
}

.hermhta_f {
  d: path("M27.277 20.83c.59 0 1.07.48 1.07 1.07v2.45h-2.14V21.9c0-.59.48-1.07 1.07-1.07");
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

.hqh-1rbea {
  stop-color: var(--svg-color--f3c29f, #F3C29F);
}

.i03-jcbks {
  stop-color: var(--svg-color--d14708, #D14708);
}

.i4c7gf1nk {
  d: path("M27.018 28.506c-.14-.96-.36-1.91-.65-2.84a11.77 11.77 0 0 0-3.24-5.13v7.97z");
}

.i6xvtdb8e {
  stop-color: var(--svg-color--545051, #545051);
}

.ibt06e6rm {
  stop-color: var(--svg-color--3e3433, #3E3433);
}

.id_kmv85a {
  d: path("m15.33 6.716l-.066-.137a.66.66 0 0 0-.615-.418h-1.273c-1.846 0-3.342 1.512-3.342 3.379v.275c-.34-.259-.767-.805-.767-1.688c0-1.072.782-1.614 1.28-1.96c.14-.097.26-.179.33-.252l.1-.105c.35-.371.973-1.032 2.06-1.32a5.5 5.5 0 0 1 1.508-.165c.473.011.806.42.806.892v1.485z");
}

.id19t5fes {
  stop-color: var(--svg-color--c68b80, #C68B80);
}

.ihk5xnqly {
  stop-color: var(--svg-color--f6bba0, #F6BBA0);
}

.ipymgraih {
  stop-color: var(--svg-color--bf7161, #BF7161);
}

.ivc982b0q {
  stop-color: var(--svg-color--e48043, #E48043);
  stop-opacity: 0;
}

.iz6q0pbtm {
  stop-color: var(--svg-color--f7b99c, #F7B99C);
}

.j-x55pbxn {
  stop-color: var(--svg-color--d9cbea, #D9CBEA);
}

.j1qr75obr {
  stop-color: var(--svg-color--d8a696, #D8A696);
}

.j7xq08bnc {
  stop-color: var(--svg-color--e08a82, #E08A82);
  stop-opacity: 0;
}

.jase_0f7h {
  stop-color: var(--svg-color--88014e, #88014E);
}

.jcqxl8b5s {
  fill: var(--svg-color--e7c1f2, #E7C1F2);
  d: path("M12.848 23.766v4.74h5.313l-.803-4.69c-.68.25-1.42.38-2.19.38c-.81.01-1.6-.15-2.32-.43");
}

.jy25td8rp {
  stop-color: var(--svg-color--e82d86, #E82D86);
}

.k45xjwbmq {
  stop-color: var(--svg-color--3e3433, #3E3433);
  stop-opacity: 0;
}

.k6k-6oblx {
  stop-color: var(--svg-color--c296bf, #C296BF);
}

.knnk86b5x {
  stop-color: var(--svg-color--d53939, #D53939);
}

.kt__1405u {
  stop-color: var(--svg-color--ccc, #CCC);
}

.kvxpklbcz {
  stop-color: var(--svg-color--5d4c7d, #5D4C7D);
}

.kxaprmbjh {
  stop-color: var(--svg-color--d39991, #D39991);
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

.l47zbgb1p {
  stop-color: var(--svg-color--e08a82, #E08A82);
}

.l4rg4-bid {
  stop-color: var(--svg-color--f6874a, #F6874A);
  stop-opacity: 0;
}

.l5x5or5jn {
  stop-color: var(--svg-color--e7c1f5, #E7C1F5);
  stop-opacity: 0;
}

.l7gss9bru {
  stop-color: var(--svg-color--c9887d, #C9887D);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.li28y9bsf {
  stop-color: var(--svg-color--675890, #675890);
}

.lo-fmbbpb {
  d: path("M12.848 23.766v4.74h5.313l-.803-4.69c-.68.25-1.42.38-2.19.38c-.81.01-1.6-.15-2.32-.43");
}

.lombttb9q {
  stop-color: var(--svg-color--f6c3b0, #F6C3B0);
}

.lsqjnabcm {
  d: path("M18.077 11.713a.84.84 0 0 0-.232-.462l-.26.285l.118.228z");
}

.m27qtcbgg {
  stop-color: var(--svg-color--d14708, #D14708);
  stop-opacity: 0;
}

.m9f_4xbpp {
  d: path("M15.118 16.319c-1.16 0-2.487.208-3.567.58l1.29 6.873c.72.324 1.497.434 2.317.434c.77 0 1.51-.074 2.19-.352l1.313-6.956c-1.05-.382-2.384-.58-3.544-.58");
}

.maqiohbml {
  stop-color: var(--svg-color--ec7046, #EC7046);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.md5uzqs3z {
  cx: 12.644px;
  cy: 11.319px;
  rx: 0.39px;
  ry: 0.197px;
}

.mlsv8jb5y {
  stop-color: var(--svg-color--d19787, #D19787);
}

.mnp72frot {
  stop-color: var(--svg-color--f6874a, #F6874A);
}

.mqqgujbcq {
  stop-color: var(--svg-color--9f6d5c, #9F6D5C);
}

.mrnsdcbqx {
  stop-color: var(--svg-color--ffddc7, #FFDDC7);
  stop-opacity: 0;
}

.n0fg5jb7h {
  stop-color: var(--svg-color--504665, #504665);
  stop-opacity: 0;
}

.n1rziy04p {
  d: path("M10.273 15.096a3.916 3.916 0 0 0 3.885 3.406h1.887a3.916 3.916 0 0 0 3.886-3.406c.118-1.883.236-3.76.324-5.642a1.45 1.45 0 0 0-1.38-1.432h-1.4a2.42 2.42 0 0 1-2.211-1.443a.66.66 0 0 0-.615-.418h-1.273c-1.846 0-3.342 1.512-3.342 3.379c0 1.86.117 3.691.239 5.556");
}

.nazw5jbsw {
  stop-color: var(--svg-color--db9282, #DB9282);
  stop-opacity: 0;
}

.nszf4yi9c {
  stop-color: var(--svg-color--4e494b, #4E494B);
}

.nu2pufskf {
  d: path("M15.103 6.298a.66.66 0 0 0-.402-.137h-1.273a3.3 3.3 0 0 0-.541.044l-2.248 6.618h1.809l-.508 2.688l3.687-5.133h-1.883z");
}

.nvk1b4bey {
  stop-color: var(--svg-color--5f4b8a, #5F4B8A);
}

.ny0rq0bux {
  stop-color: var(--svg-color--d6a195, #D6A195);
}

.o_frn_b6l {
  stop-color: var(--svg-color--cc2820, #CC2820);
}

.o0aif1l1c {
  stop-color: var(--svg-color--d3968c, #D3968C);
  stop-opacity: 0;
}

.o1jwunhtj {
  stop-color: var(--svg-color--58497e, #58497E);
}

.o6y3inocw {
  fill: var(--svg-color--202020, #202020);
  d: path("M11.687 9.243a2.77 2.77 0 0 1 1.739-.36a.277.277 0 1 1-.068.55a2.22 2.22 0 0 0-1.386.286a1 1 0 0 0-.092.06l-.003.002a.277.277 0 0 1-.34-.439z");
}

.o8wr4h7sd {
  stop-color: var(--svg-color--e8af99, #E8AF99);
  stop-opacity: 0;
}

.oa317xagd {
  stop-color: var(--svg-color--673d45, #673D45);
}

.oaig2cbln {
  stop-color: var(--svg-color--564943, #564943);
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

.oi9-i7f4a {
  stop-color: var(--svg-color--d17e71, #D17E71);
}

.ok8c2wwnd {
  d: path("M17.216 11.127c.063.085-.07.189-.22.302c-.152.113-.264.192-.327.107c-.064-.085.007-.245.158-.358c.151-.114.325-.136.389-.051");
}

.ovvtmacpn {
  stop-color: var(--svg-color--4f4d4d, #4F4D4D);
  stop-opacity: 0;
}

.oy7fe6bjb {
  stop-color: var(--svg-color--e48043, #E48043);
}

.pej7ph77g {
  d: path("M25.726 26.346a.784.784 0 0 1-.782-.711l-.67-6.428l2.975.01l-.731 6.428a.8.8 0 0 1-.792.7");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.px0sb7ebt {
  stop-color: var(--svg-color--f6b8a8, #F6B8A8);
  stop-opacity: 0;
}

.q_js7pcgc {
  d: path("M10.053 10.472a1.62 1.62 0 0 0-1.392 1.594c0 .859.673 1.56 1.521 1.607a78 78 0 0 1-.129-3.2");
}

.q-0s8ibrs {
  stop-color: var(--svg-color--7d718c, #7D718C);
  stop-opacity: 0;
}

.q1ssh2bkr {
  stop-color: var(--svg-color--edaa9c, #EDAA9C);
}

.q26gyrbrn {
  stop-color: var(--svg-color--f9bb9e, #F9BB9E);
}

.q7l79-2rh {
  stop-color: var(--svg-color--f7ceb9, #F7CEB9);
}

.qco-2_b3r {
  stop-color: var(--svg-color--484646, #484646);
}

.qcwm1i13v {
  stop-color: var(--svg-color--bfbac7, #BFBAC7);
}

.qd7mo_tmu {
  d: path("M17.282 10.938a.893.893 0 0 1 .86 1.128h-1.724a.896.896 0 0 1 .864-1.128");
}

.qgzgmyhdj {
  stop-color: var(--svg-color--c1745e, #C1745E);
  stop-opacity: 0;
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

.qtl5eyb7j {
  cx: 12.644px;
  cy: 11.319px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.qumd8gbzx {
  d: path("M20.103 13.028q.059-.952.111-1.903a.956.956 0 0 1-.11 1.903");
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qw36p19is {
  d: path("M10.012 11.133a.956.956 0 0 0 .084 1.88a78 78 0 0 1-.084-1.88");
}

.r0p9vfbnw {
  stop-color: var(--svg-color--ca8b73, #CA8B73);
  stop-opacity: 0;
}

.r0tyikbvd {
  stop-color: var(--svg-color--c0a6d9, #C0A6D9);
}

.r4_7h8b7x {
  d: path("M13.729 11.726c0-.289-.235-.48-.298-.539l-.288.279l.177.361z");
}

.r7o08-b3s {
  stop-color: var(--svg-color--ffd6bd, #FFD6BD);
}

.r8tuldb4n {
  stop-color: var(--svg-color--ebbb9d, #EBBB9D);
  stop-opacity: 0;
}

.rgp37jb6d {
  d: path("m28.214 16.546l-4.844-.02a.57.57 0 0 0-.58.579c0 .325.255.578.58.578l4.844.02a.57.57 0 0 0 .578-.578a.585.585 0 0 0-.578-.579");
}

.rq3o4j_li {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.707 10.667c-.654 0-1.205.45-1.355 1.058a.274.274 0 0 0 .267.341h2.232a.23.23 0 0 0 .227-.272a1.4 1.4 0 0 0-1.371-1.128");
}

.rqyrdfbps {
  stop-color: var(--svg-color--e22f38, #E22F38);
}

.rzqjthgas {
  stop-color: var(--svg-color--ef5945, #EF5945);
}

.s_ufbeclz {
  stop-color: var(--svg-color--463358, #463358);
  stop-opacity: 0;
}

.s_xenjqok {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M13.747 14.833h-.001a.23.23 0 0 0-.271.047a.21.21 0 0 0-.023.27c.348.528.955.88 1.646.88c.69 0 1.297-.352 1.645-.88a.214.214 0 0 0-.023-.273a.23.23 0 0 0-.271-.044c-.39.203-.85.32-1.352.32a2.9 2.9 0 0 1-1.35-.32Z");
}

.s0eee-boz {
  stop-color: var(--svg-color--aa7bd1, #AA7BD1);
}

.s562n-brd {
  stop-color: var(--svg-color--d78889, #D78889);
}

.sbugs4b_s {
  stop-color: var(--svg-color--f2c49e, #F2C49E);
  stop-opacity: 0;
}

.schxz9brm {
  d: path("M12.914 10.938a.893.893 0 0 0-.86 1.128h1.724a1 1 0 0 0 .032-.235a.9.9 0 0 0-.896-.893");
}

.sgr5pgbdc {
  fill: var(--svg-color--23181c, #23181C);
  d: path("m15.33 6.716l-.066-.137a.66.66 0 0 0-.615-.418h-1.273c-1.846 0-3.342 1.512-3.342 3.379v.275c-.34-.259-.767-.805-.767-1.688c0-1.072.782-1.614 1.28-1.96c.14-.097.26-.179.33-.252l.1-.105c.35-.371.973-1.032 2.06-1.32a5.5 5.5 0 0 1 1.508-.165c.473.011.806.42.806.892v1.485z");
}

.snpr2ctwr {
  stop-color: var(--svg-color--e6ad97, #E6AD97);
}

.stq0hsb2e {
  stop-color: var(--svg-color--545051, #545051);
  stop-opacity: 0;
}

.sy6d7pk7v {
  fill: var(--svg-color--f6bfab, #F6BFAB);
  d: path("m14.715 11.617l-.531 1.838c-.109.378.152.757.52.757h.787c.369 0 .629-.384.52-.757l-.531-1.838c-.114-.407-.646-.407-.765 0");
}

.t0w03e0rr {
  stop-color: var(--svg-color--e8af99, #E8AF99);
}

.t40345qox {
  stop-color: var(--svg-color--ffddc7, #FFDDC7);
}

.t4qzv1a_c {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.742 25.553h2.02");
}

.tfvicabxd {
  d: path("m20.31 9.983l-.029-.632c-.01-.763-.641-1.393-1.405-1.425h-1.4c-.89 0-1.7-.486-2.124-1.26c0 0-.059-.135-.12-.368c-.256-.97.67-1.712 1.655-1.521c.974.189 2.083.517 2.903 1.052c1.744 1.137 1.439 3.188.52 4.154");
}

.th3pfkb5a {
  d: path("m14.715 11.617l-.531 1.838c-.109.378.152.757.52.757h.787c.369 0 .629-.384.52-.757l-.531-1.838c-.114-.407-.646-.407-.765 0");
}

.tj2vllbvr {
  stop-color: var(--svg-color--f3c6af, #F3C6AF);
}

.toldersuv {
  stop-color: var(--svg-color--d3c3e5, #D3C3E5);
  stop-opacity: 0;
}

.tsgwb3b4a {
  stop-color: var(--svg-color--7c739f, #7C739F);
}

.tyj09bbmz {
  cx: 15.149px;
  cy: 17.765px;
  r: 2.406px;
}

.u0q_obb8r {
  d: path("M5.405 16.527h6.086l2.248 11.989h-2.79l-5.88-11.529c-.086-.125-.07-.46.336-.46");
}

.u6yfg2bxw {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M17.216 11.127c.063.085-.07.189-.22.302c-.152.113-.264.192-.327.107c-.064-.085.007-.245.158-.358c.151-.114.325-.136.389-.051");
}

.unyhdjbdq {
  stop-color: var(--svg-color--200e25, #200E25);
}

.utuwn8bka {
  fill: var(--svg-color--1f151b, #1F151B);
  d: path("m20.31 9.983l-.029-.632c-.01-.763-.641-1.393-1.405-1.425h-1.4c-.89 0-1.7-.486-2.124-1.26c0 0-.059-.135-.12-.368c-.256-.97.67-1.712 1.655-1.521c.974.189 2.083.517 2.903 1.052c1.744 1.137 1.439 3.188.52 4.154");
}

.uuzk4vb7h {
  stop-color: var(--svg-color--ce978e, #CE978E);
  stop-opacity: 0;
}

.uwe7yhbem {
  stop-color: var(--svg-color--e6ad97, #E6AD97);
  stop-opacity: 0;
}

.uzac_3qef {
  stop-color: var(--svg-color--ffd1bb, #FFD1BB);
}

.v_vak_bqs {
  fill: var(--svg-color--202020, #202020);
  d: path("M18.83 9.352a1.85 1.85 0 0 0-.687-.412c-.304-.095-.686-.121-1.213-.057a.277.277 0 1 0 .068.551c.48-.059.776-.028.978.036c.198.062.333.163.49.3a.277.277 0 0 0 .364-.418");
}

.v5rheyc4i {
  stop-color: var(--svg-color--ffd7bf, #FFD7BF);
}

.vgn1hf8dm {
  stop-color: var(--svg-color--d39991, #D39991);
  stop-opacity: 0;
}

.vla5fnbfs {
  stop-color: var(--svg-color--f7b6a5, #F7B6A5);
}

.vni43obah {
  stop-color: var(--svg-color--d3968c, #D3968C);
}

.vx-77wbda {
  stop-color: var(--svg-color--ca8b73, #CA8B73);
}

.vxg8xmb_d {
  stop-color: var(--svg-color--c46d3a, #C46D3A);
  stop-opacity: 0;
}

.w0a4mmrgb {
  stop-color: var(--svg-color--200e25, #200E25);
  stop-opacity: 0;
}

.w22vs7beb {
  stop-color: var(--svg-color--d89793, #D89793);
  stop-opacity: 0;
}

.w4q61yb8g {
  d: path("M23.128 28.506v-7.268l-3.52 7.268z");
}

.wc1l7vbis {
  stop-color: var(--svg-color--473558, #473558);
  stop-opacity: 0;
}

.wd-lahbcd {
  d: path("M19.959 13.581c.335-.01.649-.124.904-.308v.93c0 .894-.532 1.69-1.34 2.02a4.1 4.1 0 0 0 .345-1.18z");
}

.wiodrpp6l {
  d: path("M7.078 28.506h3.87l-3.87-7.596z");
}

.wmov6-bei {
  stop-color: var(--svg-color--f7b99c, #F7B99C);
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

.wyv1gnbxf {
  stop-color: var(--svg-color--5e5a5b, #5E5A5B);
}

.x1f6tb8tf {
  fill: var(--svg-color--d69790, #D69790);
  d: path("m14.696 11.808l-.59 1.838c-.101.378.14.756.484.756h.732c.343 0 .585-.384.484-.756l-.495-1.838c-.106-.408-.504-.408-.615 0");
}

.x31umkbcn {
  stop-color: var(--svg-color--cc7b85, #CC7B85);
}

.xfetrrneo {
  stop-color: var(--svg-color--504665, #504665);
}

.xftsofb3t {
  stop-color: var(--svg-color--d42552, #D42552);
}

.xsgkrbcbf {
  stop-color: var(--svg-color--313131, #313131);
}

.y3z4eqobc {
  d: path("M20.02 13.673c.065-1.065.129-2.128.184-3.192a1.61 1.61 0 0 1-.184 3.191");
}

.y6b283b4c {
  stop-color: var(--svg-color--ffd6ba, #FFD6BA);
  stop-opacity: 0;
}

.y6pg1ac6x {
  d: path("M10.236 13.581a1.64 1.64 0 0 1-.904-.308v.93c0 .894.532 1.69 1.34 2.02a4.1 4.1 0 0 1-.345-1.18z");
}

.y8u9aob3m {
  stop-color: var(--svg-color--d89793, #D89793);
}

.yhi4l7bah {
  stop-color: var(--svg-color--f8c8ad, #F8C8AD);
}

.yor2p9b5i {
  stop-color: var(--svg-color--ce978e, #CE978E);
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

.zcdcyccef {
  stop-color: var(--svg-color--e1aca6, #E1ACA6);
  stop-opacity: 0;
}

.zg05wl6cw {
  stop-color: var(--svg-color--a78bc1, #A78BC1);
}

.zg97ljbvw {
  stop-color: var(--svg-color--ad93c6, #AD93C6);
  stop-opacity: 0;
}

.zn-qjxbde {
  stop-color: var(--svg-color--86004d, #86004D);
}

.zwo50zm6y {
  stop-color: var(--svg-color--484646, #484646);
  stop-opacity: 0;
}

.zxhnj4bqq {
  stop-color: var(--svg-color--eae5f7, #EAE5F7);
}

</style>
