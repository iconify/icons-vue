<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iGQOI7d)"><path fill="url(#iI2ZuZd)" class="upgdf1b_h"/></g><path fill="url(#i2I0A4c)" class="pcjq3gbcg"/><path fill="url(#iRfoJ8c)" class="pcjq3gbcg"/><path fill="url(#iFE0LHb)" class="pcjq3gbcg"/><g filter="url(#iWSA44c)"><path stroke="url(#iPe9kqb)" class="p8tdqzrvo"/></g><g filter="url(#iKq0Z3b)"><path fill="url(#i47RfHc)" class="wizsfxbnq"/><path fill="url(#iDfwOGc)" class="wizsfxbnq"/><path fill="url(#inNTgsd)" class="wizsfxbnq"/></g><path fill="url(#iHJMvUi)" class="b1syjbc1x"/><path fill="url(#iVajotd)" class="b1syjbc1x"/><path fill="url(#irtf0rd)" class="b1syjbc1x"/><path fill="url(#iPRFfOc)" class="dph66t0ka"/><path fill="url(#irg7o7c)" class="dph66t0ka"/><path fill="url(#iJSE77d)" class="dph66t0ka"/><path fill="url(#iiUrcCA)" class="r3ewmblju"/><path fill="url(#ilU5EFc)" class="r3ewmblju"/><path fill="url(#iQV9krb)" class="t7pehib4f"/><g filter="url(#ivFs8Xc)"><path fill="url(#iNIzOme)" class="wxov4bcam"/><path fill="url(#ia8GasD)" class="wxov4bcam"/><path fill="url(#iVppiCc)" class="wxov4bcam"/><path fill="url(#iQkz13d)" class="wxov4bcam"/></g><g filter="url(#i8Xj76d)"><path fill="url(#ig4eJke)" class="lxewynbqt"/><path fill="url(#in96FKd)" class="lxewynbqt"/><path fill="url(#ii5mcib)" class="lxewynbqt"/><path fill="url(#iBJez3Z)" class="lxewynbqt"/></g><path fill="url(#iDIr3zb)" class="yf38yz6vj"/><g filter="url(#iGfpxsb)"><path fill="url(#iM8EScd)" class="i3x270bvu"/><path fill="url(#iPe5BkE)" class="i3x270bvu"/></g><g filter="url(#iql7GYc)"><path fill="url(#izIKJCd)" class="sax4pugkt"/></g><path fill="url(#iUbz5we)" class="uz53o4bgd"/><path clip-rule="evenodd" class="jrokyri7f"/><path fill="url(#ipD9Sbe)" clip-rule="evenodd" class="cpcxxz0lo"/><g filter="url(#itnNKpc)"><path fill="url(#ihJEoie)" class="cnmvr6bya"/><path fill="url(#iwR8Vsd)" class="cnmvr6bya"/><path fill="url(#ik1IQVb)" class="cnmvr6bya"/><path fill="url(#iFZ8Bve)" class="cnmvr6bya"/><path fill="url(#iUFWIou)" class="cnmvr6bya"/></g><g filter="url(#iHCxsMb)"><path fill="url(#ik4LXle)" class="rr0ehkyum"/><path fill="url(#i24GV1c)" class="rr0ehkyum"/><path fill="url(#iFmn0oo)" class="rr0ehkyum"/><path fill="url(#iVaMNYH)" class="rr0ehkyum"/><path fill="url(#ip4dgXd)" class="rr0ehkyum"/></g><path fill="url(#inUxtve)" class="jddhx-i6n"/><path fill="url(#ivUUTyb)" class="x1tqnze9p"/><g filter="url(#iFPYUqd)"><path stroke="url(#ihKHqMc)" class="zomjjjh-z"/></g><g filter="url(#iupZ8Ba)"><path stroke="url(#iuoE2ge)" class="fhksq8ilc"/></g><g filter="url(#iuhLa5G)"><path stroke="url(#iAbfaCe)" class="goarh-wro"/></g><g filter="url(#i9XzC1d)"><path stroke="url(#iauRZrb)" class="chixewryi"/></g><g filter="url(#iBkRzqd)"><path stroke="url(#iVJV7le)" class="wiin44g-j"/></g><g filter="url(#iB86Exe)"><path stroke="url(#iCOsk4d)" class="p2s3ado1h"/></g><g filter="url(#iZSRcUd)"><circle fill="url(#ia8togd)" class="x15sxp3lc"/></g><g filter="url(#iBCwQZe)"><circle fill="url(#iwK9gzc)" class="imbr-rb2t"/></g><g filter="url(#iIS7Zot)"><circle fill="url(#iflhWTd)" class="d-7d0zb4w"/><circle fill="url(#iGbmzLn)" class="d-7d0zb4w"/></g><g filter="url(#iV84q6b)"><circle class="ai3hwvqis"/><circle fill="url(#i4D1Xwc)" class="mjf0u6b4a"/><circle fill="url(#iVof5Rd)" class="mjf0u6b4a"/></g><g filter="url(#iCUxiic)"><path fill="url(#ipXL0Xb)" class="lbllohblp"/><path fill="url(#iFCciSc)" class="lbllohblp"/><path fill="url(#iNaSR9d)" class="lbllohblp"/><path fill="url(#ifyoCob)" class="lbllohblp"/><path fill="url(#iAE5Ujd)" class="lbllohblp"/><path fill="url(#iOzR4od)" class="lbllohblp"/></g><g filter="url(#iKBDdPI)"><path fill="url(#ikql7ne)" class="tl_2dbb_x"/></g><g filter="url(#ioZXrCc)"><path class="iybe95oky"/><path fill="url(#iMRBoYd)" class="bf2lz-yzq"/><path fill="url(#idsvcXc)" class="bf2lz-yzq"/><path fill="url(#iqBkMPe)" class="bf2lz-yzq"/><path fill="url(#iP15AGd)" class="bf2lz-yzq"/></g><g filter="url(#igKsYKc)"><path class="g58wtjbuf"/></g><g filter="url(#i9Wh95b)"><path class="gl-8uegyf"/><path fill="url(#iIQEiKe)" class="bsnzn6jsv"/><path fill="url(#im3awfe)" class="bsnzn6jsv"/><path fill="url(#iAGXz8c)" class="bsnzn6jsv"/><path fill="url(#iqc8QDm)" class="bsnzn6jsv"/></g><path fill="url(#iFEQNSb)" class="bsnzn6jsv"/><path stroke="url(#ikI42ec)" class="tvk4-xbyn"/><g filter="url(#iEpDFad)"><path class="w8755c4cc"/></g><g filter="url(#iH4zspb)"><path class="rou90ib5o"/></g><path class="ljwtm1btc"/><path fill="url(#iD5eGZI)" class="e3noj1bpe"/><path class="bn7rlk0uy"/><g filter="url(#ivwH4mh)"><path class="kja3hpbzh"/><path fill="url(#ihhTRfW)" class="p3397-qvh"/></g><g filter="url(#iR16G4c)"><path fill="url(#i1HkSnb)" class="azq7sz9ql"/></g><path class="jgy1ttwjg"/><path fill="url(#iv6Xqrc)" class="btjaclc9y"/><path class="ll06hnnpv"/><g filter="url(#i6VeTwe)"><path fill="url(#iWy5zfb)" class="e311nkbdi"/></g><g filter="url(#iCI2qUc)"><ellipse transform="rotate(-27.914 13.557 9.978)" class="mrr7h_bzd"/><ellipse fill="url(#iYKEwCe)" transform="rotate(-27.914 13.557 9.978)" class="ax1vmbb9d"/></g><g filter="url(#iauJ6ic)"><path stroke="url(#ibsno9d)" class="elsqsfztz"/></g><g filter="url(#ifqhucb)"><path stroke="url(#iZOyJye)" class="xb5iyf9xu"/></g><g filter="url(#i1u0Aeb)"><path stroke="url(#iqxzdcb)" class="fw_d1ac2c"/></g><g filter="url(#iZSQGgc)"><path fill="url(#iRFMG9w)" class="ov0ztps-s"/><path fill="url(#igEIKoc)" class="ov0ztps-s"/></g><defs><radialGradient id="iRfoJ8c" cx="0" cy="0" r="1" gradientTransform="rotate(-56.746 27.047 6.886)scale(18.2363 24.9585)" gradientUnits="userSpaceOnUse"><stop class="hpdf2p89l"/><stop offset="1" class="wfc059byj"/></radialGradient><radialGradient id="iFE0LHb" cx="0" cy="0" r="1" gradientTransform="matrix(-9.99996 -14.06247 13.90983 -9.89141 29.582 25.477)" gradientUnits="userSpaceOnUse"><stop class="od6_koblh"/><stop offset="1" class="cxrlhcc-d"/></radialGradient><radialGradient id="inNTgsd" cx="0" cy="0" r="1" gradientTransform="matrix(0 9.31138 -.61764 0 2.024 4.313)" gradientUnits="userSpaceOnUse"><stop offset=".355" class="g043vp3zf"/><stop offset="1" class="sihp1fb9k"/></radialGradient><radialGradient id="iHJMvUi" cx="0" cy="0" r="1" gradientTransform="matrix(0 14.0469 -6.21865 0 16.02 15.946)" gradientUnits="userSpaceOnUse"><stop class="zlcjw7bgf"/><stop offset="1" class="qna-_2b3m"/></radialGradient><radialGradient id="iVajotd" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.375 -2.9375 0 22.676 20.477)" gradientUnits="userSpaceOnUse"><stop class="us4ivbb3t"/><stop offset="1" class="yvo_l_bkn"/></radialGradient><radialGradient id="irtf0rd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.53125 1.53125 -1.23438 -1.23438 12.74 19.071)" gradientUnits="userSpaceOnUse"><stop class="rkna2zbug"/><stop offset="1" class="ox51r5bse"/></radialGradient><radialGradient id="iPRFfOc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -10.1875 3.85106 0 27.014 28.228)" gradientUnits="userSpaceOnUse"><stop class="rqxi6yb_m"/><stop offset="1" class="vuu7bk4vv"/></radialGradient><radialGradient id="ilU5EFc" cx="0" cy="0" r="1" gradientTransform="matrix(-6.92068 0 0 -17.2807 11.478 29.776)" gradientUnits="userSpaceOnUse"><stop offset=".576" class="qo_nu3b1v"/><stop offset="1" class="b4vmzacii"/></radialGradient><radialGradient id="iQV9krb" cx="0" cy="0" r="1" gradientTransform="matrix(3.59375 0 0 11.7969 15.207 20.29)" gradientUnits="userSpaceOnUse"><stop class="fqkeoivtf"/><stop offset="1" class="avo9uebvh"/></radialGradient><radialGradient id="ia8GasD" cx="0" cy="0" r="1" gradientTransform="matrix(-1.59385 -3.38389 2.04685 -.9641 21.25 19.437)" gradientUnits="userSpaceOnUse"><stop class="kl3ja4pbq"/><stop offset="1" class="ybzr6jbff"/></radialGradient><radialGradient id="iVppiCc" cx="0" cy="0" r="1" gradientTransform="matrix(-.9453 -1.33595 .2433 -.17216 19.692 20.447)" gradientUnits="userSpaceOnUse"><stop class="uqvywhymc"/><stop offset="1" class="y1kgfac6n"/></radialGradient><radialGradient id="iQkz13d" cx="0" cy="0" r="1" gradientTransform="matrix(.75 1.14843 -2.14967 1.40386 17.698 15.6)" gradientUnits="userSpaceOnUse"><stop offset=".359" class="fgkcx3bbf"/><stop offset="1" class="gihkuibxq"/></radialGradient><radialGradient id="in96FKd" cx="0" cy="0" r="1" gradientTransform="rotate(-88.854 17.15 3.272)scale(3.12563 1.26257)" gradientUnits="userSpaceOnUse"><stop class="kiracnbim"/><stop offset="1" class="n8mbjcbow"/></radialGradient><radialGradient id="iBJez3Z" cx="0" cy="0" r="1" gradientTransform="matrix(-.26505 .89062 -1.66708 -.49612 14.229 16.014)" gradientUnits="userSpaceOnUse"><stop offset=".219" class="fgkcx3bbf"/><stop offset="1" class="gihkuibxq"/></radialGradient><radialGradient id="iDIr3zb" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.34375 -2.51976 0 16.024 17.227)" gradientUnits="userSpaceOnUse"><stop offset=".333" class="hyk2eqbsj"/><stop offset="1" class="s-cemd13j"/></radialGradient><radialGradient id="iM8EScd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.12893 1.05533 -1.5203 -1.62634 22.656 23.764)" gradientUnits="userSpaceOnUse"><stop offset=".28" class="dqczsn00c"/><stop offset="1" class="zagqne2ck"/></radialGradient><radialGradient id="iPe5BkE" cx="0" cy="0" r="1" gradientTransform="matrix(.61902 -.52682 .31382 .36874 22.798 23.483)" gradientUnits="userSpaceOnUse"><stop class="cokz6uveh"/><stop offset="1" class="kfg1w5y8t"/></radialGradient><radialGradient id="izIKJCd" cx="0" cy="0" r="1" gradientTransform="matrix(1.16103 -.00547 .01713 3.63788 9.515 24.624)" gradientUnits="userSpaceOnUse"><stop offset=".303" class="dqumds59m"/><stop offset="1" class="vwbk5fb5n"/></radialGradient><radialGradient id="iwR8Vsd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.67187 0 0 -.65955 12.207 25.358)" gradientUnits="userSpaceOnUse"><stop class="e5ivxs1br"/><stop offset="1" class="iicpv44yj"/></radialGradient><radialGradient id="ik1IQVb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.53125 0 0 -.60407 12.223 26.64)" gradientUnits="userSpaceOnUse"><stop class="e5ivxs1br"/><stop offset="1" class="iicpv44yj"/></radialGradient><radialGradient id="iFZ8Bve" cx="0" cy="0" r="1" gradientTransform="matrix(-1.34375 0 0 -.5301 12.27 27.92)" gradientUnits="userSpaceOnUse"><stop class="e5ivxs1br"/><stop offset="1" class="iicpv44yj"/></radialGradient><radialGradient id="iUFWIou" cx="0" cy="0" r="1" gradientTransform="matrix(-1.5 0 0 -.59174 12.34 29.28)" gradientUnits="userSpaceOnUse"><stop class="e5ivxs1br"/><stop offset="1" class="iicpv44yj"/></radialGradient><radialGradient id="i24GV1c" cx="0" cy="0" r="1" gradientTransform="matrix(1.70312 0 0 .67188 21.27 25.358)" gradientUnits="userSpaceOnUse"><stop class="e5ivxs1br"/><stop offset="1" class="iicpv44yj"/></radialGradient><radialGradient id="iFmn0oo" cx="0" cy="0" r="1" gradientTransform="matrix(1.625 0 0 .64106 21.207 26.64)" gradientUnits="userSpaceOnUse"><stop class="e5ivxs1br"/><stop offset="1" class="iicpv44yj"/></radialGradient><radialGradient id="iVaMNYH" cx="0" cy="0" r="1" gradientTransform="matrix(1.5625 0 0 .6164 21.113 27.92)" gradientUnits="userSpaceOnUse"><stop class="e5ivxs1br"/><stop offset="1" class="iicpv44yj"/></radialGradient><radialGradient id="ip4dgXd" cx="0" cy="0" r="1" gradientTransform="matrix(1.4375 0 0 .56709 20.973 29.28)" gradientUnits="userSpaceOnUse"><stop class="e5ivxs1br"/><stop offset="1" class="iicpv44yj"/></radialGradient><radialGradient id="ia8togd" cx="0" cy="0" r="1" gradientTransform="matrix(1.75652 0 0 3.07393 9.592 10.757)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="x3sd7rf5r"/><stop offset="1" class="dsm4f-bda"/></radialGradient><radialGradient id="iGbmzLn" cx="0" cy="0" r="1" gradientTransform="matrix(.82748 -.60254 .68772 .94447 21.157 10.492)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="ytssyfa7a"/><stop offset="1" class="fnfe_1psv"/></radialGradient><radialGradient id="i4D1Xwc" cx="0" cy="0" r="1" gradientTransform="matrix(.82204 -1.51196 .88496 .48114 20.744 11.579)" gradientUnits="userSpaceOnUse"><stop offset=".755" class="lvos55blo"/><stop offset=".916" class="bvmj8ubsx"/></radialGradient><radialGradient id="iVof5Rd" cx="0" cy="0" r="1" gradientTransform="matrix(.25953 .2569 -.33118 .33457 20.785 10.757)" gradientUnits="userSpaceOnUse"><stop class="iqm2531qk"/><stop offset="1" class="n3g96cceg"/></radialGradient><radialGradient id="iNaSR9d" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.11187 -9.65399 0 15.713 10.558)" gradientUnits="userSpaceOnUse"><stop offset=".561" class="g0r5sc7jj"/><stop offset="1" class="i5c5eto6f"/></radialGradient><radialGradient id="ifyoCob" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.30832 1.61023 0 18.363 9.484)" gradientUnits="userSpaceOnUse"><stop class="kb28pwbin"/><stop offset="1" class="uck_nmbag"/></radialGradient><radialGradient id="iAE5Ujd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.39218 1.7313 0 13.8 9.45)" gradientUnits="userSpaceOnUse"><stop class="j7sc31byj"/><stop offset="1" class="e9zt2gbxt"/></radialGradient><radialGradient id="iOzR4od" cx="0" cy="0" r="1" gradientTransform="rotate(-166.409 11.152 7.252)scale(2.92567 1.71902)" gradientUnits="userSpaceOnUse"><stop offset=".136" class="ph-yb3bws"/><stop offset="1" class="az2la2bjr"/></radialGradient><radialGradient id="iMRBoYd" cx="0" cy="0" r="1" gradientTransform="matrix(.79857 -2.95942 1.09745 .29614 20.364 6.647)" gradientUnits="userSpaceOnUse"><stop class="ui2kgq2tt"/><stop offset="1" class="bumyo9b5s"/></radialGradient><radialGradient id="idsvcXc" cx="0" cy="0" r="1" gradientTransform="matrix(3.82845 .35231 -.18944 2.05853 18.72 4.885)" gradientUnits="userSpaceOnUse"><stop offset=".122" class="d4d293bim"/><stop offset="1" class="yf9erdbmk"/></radialGradient><radialGradient id="iqBkMPe" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.68076 -2.60303 0 16.015 2.147)" gradientUnits="userSpaceOnUse"><stop class="qc5tyzrav"/><stop offset="1" class="m_1e2qbpe"/></radialGradient><radialGradient id="iP15AGd" cx="0" cy="0" r="1" gradientTransform="matrix(3.07685 -2.2548 3.53253 4.82042 9.56 8.972)" gradientUnits="userSpaceOnUse"><stop class="gg1n47rtb"/><stop offset="1" class="uk24qccae"/></radialGradient><radialGradient id="iqc8QDm" cx="0" cy="0" r="1" gradientTransform="matrix(0 .19709 -.6332 0 16.343 12.365)" gradientUnits="userSpaceOnUse"><stop class="ldpzz4bsg"/><stop offset="1" class="xtaxaigve"/></radialGradient><radialGradient id="iD5eGZI" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8119 -1.29142 0 18.196 10.074)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="ihhTRfW" cx="0" cy="0" r="1" gradientTransform="matrix(-.23208 -.29907 .41175 -.31952 17.966 10.16)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iv6Xqrc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81194 -1.29148 0 13.829 10.074)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iYKEwCe" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 11.838 -1.52)scale(.4945 .5944)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="igEIKoc" cx="0" cy="0" r="1" gradientTransform="matrix(.90625 0 0 2.71875 11.395 10.552)" gradientUnits="userSpaceOnUse"><stop class="zobbewbqd"/><stop offset="1" class="cesjesv2y"/></radialGradient><linearGradient id="iI2ZuZd" x1="11.838" x2="31.281" y1="4.602" y2="22.838" gradientUnits="userSpaceOnUse"><stop class="lj0sm1b7l"/><stop offset=".568" class="u1egy7b7t"/><stop offset="1" class="auorgtyhp"/></linearGradient><linearGradient id="i2I0A4c" x1="30.082" x2="9.145" y1="13.29" y2="13.29" gradientUnits="userSpaceOnUse"><stop class="nfwti5bbx"/><stop offset="1" class="r4c-t7bme"/></linearGradient><linearGradient id="iPe9kqb" x1="13.457" x2="31.27" y1="3.543" y2="24.355" gradientUnits="userSpaceOnUse"><stop class="y1ij6ubnw"/><stop offset="1" class="jpk8o_7uj"/></linearGradient><linearGradient id="i47RfHc" x1="-4.887" x2="28.926" y1="25.634" y2="25.634" gradientUnits="userSpaceOnUse"><stop class="xtl7t4edr"/><stop offset="1" class="wn11gcx8f"/></linearGradient><linearGradient id="iDfwOGc" x1="3.113" x2="3.113" y1="5.196" y2="23.634" gradientUnits="userSpaceOnUse"><stop class="e1bvu4b8w"/><stop offset="1" class="jij-d9bro"/></linearGradient><linearGradient id="irg7o7c" x1="25.193" x2="25.193" y1="30.447" y2="26.631" gradientUnits="userSpaceOnUse"><stop class="ax9s6wi3k"/><stop offset="1" class="bd-canb4c"/></linearGradient><linearGradient id="iJSE77d" x1="22.426" x2="23.238" y1="29.259" y2="29.243" gradientUnits="userSpaceOnUse"><stop offset=".254" class="ja44woagt"/><stop offset="1" class="x16kbobeb"/></linearGradient><linearGradient id="iiUrcCA" x1="7.154" x2="9.548" y1="28.14" y2="28.14" gradientUnits="userSpaceOnUse"><stop class="zs64g5eig"/><stop offset="1" class="fczdhwb3o"/></linearGradient><linearGradient id="iNIzOme" x1="18.074" x2="20.87" y1="18.367" y2="18.367" gradientUnits="userSpaceOnUse"><stop class="ryydajfhb"/><stop offset=".371" class="ub4gkwbqs"/></linearGradient><linearGradient id="ig4eJke" x1="13.964" x2="11.167" y1="18.368" y2="18.368" gradientUnits="userSpaceOnUse"><stop class="ik2h44jfq"/><stop offset=".639" class="rd-uo94io"/></linearGradient><linearGradient id="ii5mcib" x1="12.129" x2="12.691" y1="16.931" y2="17.149" gradientUnits="userSpaceOnUse"><stop class="krazlsbaw"/><stop offset="1" class="cd-mikbpl"/></linearGradient><linearGradient id="iUbz5we" x1="21.863" x2="17.488" y1="24.79" y2="24.79" gradientUnits="userSpaceOnUse"><stop class="f30052bab"/><stop offset="1" class="r4xas9tfi"/></linearGradient><linearGradient id="ipD9Sbe" x1="10.334" x2="10.762" y1="23.571" y2="23.571" gradientUnits="userSpaceOnUse"><stop class="k_snybcwj"/><stop offset="1" class="a_s1o9xch"/></linearGradient><linearGradient id="ihJEoie" x1="12.52" x2="8.582" y1="28.009" y2="28.009" gradientUnits="userSpaceOnUse"><stop class="qgdka6bnc"/><stop offset="1" class="a-cpf7b0f"/></linearGradient><linearGradient id="ik4LXle" x1="22.488" x2="18.674" y1="27.602" y2="27.602" gradientUnits="userSpaceOnUse"><stop class="qd6c5fnlv"/><stop offset=".807" class="eghqjhb7i"/></linearGradient><linearGradient id="inUxtve" x1="10.801" x2="21.674" y1="21.946" y2="21.946" gradientUnits="userSpaceOnUse"><stop class="auppp8bgz"/><stop offset="1" class="auppp8bgz"/></linearGradient><linearGradient id="ivUUTyb" x1="16.42" x2="16.42" y1="21.009" y2="22.181" gradientUnits="userSpaceOnUse"><stop class="alxt_0b7l"/><stop offset="1" class="ux8m6ubss"/></linearGradient><linearGradient id="ihKHqMc" x1="19.043" x2="20.871" y1="26.11" y2="26.11" gradientUnits="userSpaceOnUse"><stop class="g2of_dbdx"/><stop offset="1" class="gugba3b_v"/></linearGradient><linearGradient id="iuoE2ge" x1="12.952" x2="10.754" y1="26.11" y2="26.11" gradientUnits="userSpaceOnUse"><stop class="mc9t6_o6r"/><stop offset="1" class="pk72hc60b"/></linearGradient><linearGradient id="iAbfaCe" x1="19.043" x2="20.871" y1="27.376" y2="27.376" gradientUnits="userSpaceOnUse"><stop class="g2of_dbdx"/><stop offset="1" class="gugba3b_v"/></linearGradient><linearGradient id="iauRZrb" x1="12.952" x2="10.754" y1="27.376" y2="27.376" gradientUnits="userSpaceOnUse"><stop class="mc9t6_o6r"/><stop offset="1" class="pk72hc60b"/></linearGradient><linearGradient id="iVJV7le" x1="19.043" x2="20.871" y1="28.642" y2="28.642" gradientUnits="userSpaceOnUse"><stop class="g2of_dbdx"/><stop offset="1" class="gugba3b_v"/></linearGradient><linearGradient id="iCOsk4d" x1="12.952" x2="10.754" y1="28.642" y2="28.642" gradientUnits="userSpaceOnUse"><stop class="mc9t6_o6r"/><stop offset="1" class="pk72hc60b"/></linearGradient><linearGradient id="iwK9gzc" x1="11.262" x2="10.621" y1="11.036" y2="11.036" gradientUnits="userSpaceOnUse"><stop class="fbs6uccsw"/><stop offset="1" class="np-b1wbds"/></linearGradient><linearGradient id="iflhWTd" x1="21.872" x2="21.053" y1="9.664" y2="12.203" gradientUnits="userSpaceOnUse"><stop class="o1rzobcjq"/><stop offset="1" class="acjykw8xe"/></linearGradient><linearGradient id="ipXL0Xb" x1="20.055" x2="12.411" y1="11.147" y2="12.286" gradientUnits="userSpaceOnUse"><stop class="cdm_o50ho"/><stop offset="1" class="ahguepbtf"/></linearGradient><linearGradient id="iFCciSc" x1="10.614" x2="12.881" y1="13.845" y2="13.703" gradientUnits="userSpaceOnUse"><stop offset=".283" class="j-n0q842a"/><stop offset="1" class="o-j_7gbpq"/></linearGradient><linearGradient id="ikql7ne" x1="16.975" x2="25.6" y1="7.766" y2="4.797" gradientUnits="userSpaceOnUse"><stop class="cgqcq-bjq"/><stop offset="1" class="o1syipbau"/></linearGradient><linearGradient id="iIQEiKe" x1="15.15" x2="16.089" y1="11.807" y2="11.807" gradientUnits="userSpaceOnUse"><stop class="o6hm6qxaj"/><stop offset="1" class="mg63gccek"/></linearGradient><linearGradient id="im3awfe" x1="16.954" x2="15.928" y1="12.129" y2="12.115" gradientUnits="userSpaceOnUse"><stop class="yww6tz8di"/><stop offset="1" class="n-4z7qb5o"/></linearGradient><linearGradient id="iAGXz8c" x1="16.21" x2="16.21" y1="12.872" y2="12.299" gradientUnits="userSpaceOnUse"><stop class="xtiplndwl"/><stop offset="1" class="h8-lntwqp"/></linearGradient><linearGradient id="iFEQNSb" x1="16.141" x2="16.141" y1="12.914" y2="12.747" gradientUnits="userSpaceOnUse"><stop class="zoxadnjxe"/><stop offset="1" class="gnvm67mtb"/></linearGradient><linearGradient id="ikI42ec" x1="14.977" x2="15.412" y1="14.489" y2="13.801" gradientUnits="userSpaceOnUse"><stop class="w1_1yhbve"/><stop offset=".663" class="zbexf6jod"/></linearGradient><linearGradient id="i1HkSnb" x1="18.974" x2="18.66" y1="10.128" y2="10.322" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iWy5zfb" x1="14.573" x2="14.259" y1="10.128" y2="10.321" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ibsno9d" x1="18.99" x2="18.57" y1="7.986" y2="7.127" gradientUnits="userSpaceOnUse"><stop class="wi8di0b_n"/><stop offset="1" class="zx1idre_k"/></linearGradient><linearGradient id="iZOyJye" x1="13.68" x2="12.49" y1="7.859" y2="7.359" gradientUnits="userSpaceOnUse"><stop class="wi8di0b_n"/><stop offset="1" class="zx1idre_k"/></linearGradient><linearGradient id="iqxzdcb" x1="11.349" x2="11.349" y1="5.842" y2="8.001" gradientUnits="userSpaceOnUse"><stop class="nc1ak66ax"/><stop offset="1" class="vpvekld5v"/></linearGradient><linearGradient id="iRFMG9w" x1="16.099" x2="16.099" y1="9.448" y2="13.229" gradientUnits="userSpaceOnUse"><stop class="os93-qygj"/><stop offset="1" class="foz7ccc1o"/></linearGradient><filter id="iGQOI7d" width="27.98" height="21.09" x="2.024" y="3.993" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.81585 0 0 0 0 0.641744 0 0 0 0 0.41905 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1657"/></filter><filter id="iWSA44c" width="27.413" height="20.785" x="2.688" y="3.837" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1657" stdDeviation=".2"/></filter><filter id="iKq0Z3b" width="27.91" height="20.96" x="2.024" y="4.013" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.3"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.85098 0 0 0 0 0.482353 0 0 0 0 0.647059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1657"/></filter><filter id="ivFs8Xc" width="2.797" height="14.493" x="18.074" y="15.5" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.380392 0 0 0 0 0.164706 0 0 0 0 0.203922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1657"/></filter><filter id="i8Xj76d" width="2.797" height="14.501" x="11.167" y="15.492" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.380392 0 0 0 0 0.164706 0 0 0 0 0.203922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1657"/></filter><filter id="iGfpxsb" width="2.1" height="3.39" x="20.967" y="23.101" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.396078 0 0 0 0 0.317647 0 0 0 0 0.301961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1657"/></filter><filter id="iql7GYc" width="2.1" height="3.29" x="8.97" y="23.093" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.32549 0 0 0 0 0.25098 0 0 0 0 0.243137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1657"/></filter><filter id="itnNKpc" width="4.793" height="5.391" x="8.97" y="24.602" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.34902 0 0 0 0 0.286275 0 0 0 0 0.27451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1657"/></filter><filter id="iHCxsMb" width="4.793" height="5.591" x="18.474" y="24.402" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.231373 0 0 0 0 0.133333 0 0 0 0 0.196078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1657"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.392157 0 0 0 0 0.313726 0 0 0 0 0.305882 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1657" result="effect2_innerShadow_4002_1657"/></filter><filter id="iFPYUqd" width="2.222" height=".3" x="18.893" y="25.882" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1657" stdDeviation=".05"/></filter><filter id="iupZ8Ba" width="2.222" height=".3" x="10.88" y="25.882" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1657" stdDeviation=".05"/></filter><filter id="iuhLa5G" width="2.222" height=".3" x="18.893" y="27.148" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1657" stdDeviation=".05"/></filter><filter id="i9XzC1d" width="2.222" height=".3" x="10.88" y="27.148" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1657" stdDeviation=".05"/></filter><filter id="iBkRzqd" width="2.222" height=".3" x="18.893" y="28.413" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1657" stdDeviation=".05"/></filter><filter id="iB86Exe" width="2.222" height=".3" x="10.88" y="28.413" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1657" stdDeviation=".05"/></filter><filter id="iZSRcUd" width="3.542" height="3.342" x="9.592" y="9.086" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.341176 0 0 0 0 0.270588 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1657"/></filter><filter id="iBCwQZe" width="2.992" height="2.992" x="9.767" y="9.261" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1657" stdDeviation=".25"/></filter><filter id="iIS7Zot" width="3.592" height="3.592" x="19.114" y="8.836" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.243137 0 0 0 0 0.141176 0 0 0 0 0.223529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1657"/></filter><filter id="iV84q6b" width="2.992" height="2.992" x="19.289" y="9.261" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1657" stdDeviation=".25"/></filter><filter id="iCUxiic" width="10.383" height="12.189" x="10.852" y="5.127" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.109804 0 0 0 0 0.0509804 0 0 0 0 0.0509804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1657"/></filter><filter id="iKBDdPI" width="6.25" height="5.07" x="15.185" y="4.127" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1657" stdDeviation=".5"/></filter><filter id="ioZXrCc" width="12.614" height="8.551" x="9.708" y="1.647" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0392157 0 0 0 0 0.00784314 0 0 0 0 0.0196078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1657"/></filter><filter id="igKsYKc" width="3.262" height="4.184" x="14.145" y="9.602" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1657" stdDeviation=".375"/></filter><filter id="i9Wh95b" width="2.379" height="3.184" x="14.826" y="9.939" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1657" stdDeviation=".125"/></filter><filter id="iEpDFad" width="2.982" height="1.874" x="17.198" y="7.105" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0196078 0 0 0 0 0.027451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1657"/></filter><filter id="iH4zspb" width="2.982" height="1.874" x="12.046" y="7.105" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0196078 0 0 0 0 0.027451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1657"/></filter><filter id="ivwH4mh" width=".787" height=".697" x="17.461" y="9.634" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1657" stdDeviation=".05"/></filter><filter id="iR16G4c" width=".892" height=".914" x="18.302" y="9.709" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1657" stdDeviation=".1"/></filter><filter id="i6VeTwe" width=".987" height="1.041" x="13.856" y="9.646" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1657" stdDeviation=".1"/></filter><filter id="iCI2qUc" width=".914" height=".705" x="13.101" y="9.626" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1657" stdDeviation=".05"/></filter><filter id="iauJ6ic" width="2.701" height="1.281" x="17.252" y="7.431" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1657" stdDeviation=".15"/></filter><filter id="ifqhucb" width="2.779" height="1.339" x="12.028" y="7.495" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1657" stdDeviation=".15"/></filter><filter id="i1u0Aeb" width="1.008" height="2.271" x="10.845" y="5.566" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1657" stdDeviation=".125"/></filter><filter id="iZSQGgc" width="10.29" height="4.16" x="10.904" y="8.942" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.381221 0 0 0 0 0.2699 0 0 0 0 0.482422 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1657"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.2 0 0 0 0 0.109804 0 0 0 0 0.211765 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1657" result="effect2_innerShadow_4002_1657"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-teacher-dark" /></template>
<style>
.a_s1o9xch {
  stop-color: var(--svg-color--6d6670, #6D6670);
  stop-opacity: 0;
}

.a-cpf7b0f {
  stop-color: var(--svg-color--3d282b, #3D282B);
}

.acjykw8xe {
  stop-color: var(--svg-color--452a31, #452A31);
}

.ahguepbtf {
  stop-color: var(--svg-color--3c2828, #3C2828);
}

.ai3hwvqis {
  cx: 20.785px;
  cy: 10.757px;
  r: 0.996px;
  fill: var(--svg-color--463133, #463133);
}

.alxt_0b7l {
  stop-color: var(--svg-color--dcd5e1, #DCD5E1);
}

.auorgtyhp {
  stop-color: var(--svg-color--d6753d, #D6753D);
}

.auppp8bgz {
  stop-color: var(--svg-color--564567, #564567);
}

.avo9uebvh {
  stop-color: var(--svg-color--544b50, #544B50);
}

.ax1vmbb9d {
  cx: 13.557px;
  cy: 9.978px;
  rx: 0.39px;
  ry: 0.197px;
}

.ax9s6wi3k {
  stop-color: var(--svg-color--614451, #614451);
}

.az2la2bjr {
  stop-color: var(--svg-color--5b4b4d, #5B4B4D);
  stop-opacity: 0;
}

.azq7sz9ql {
  d: path("M18.994 10.372a.84.84 0 0 0-.232-.463l-.26.286l.117.228z");
}

.b1syjbc1x {
  d: path("M16.024 15.493c-6.07 0-11 4.92-11 11v3.5h21.99v-3.5c0-6.08-4.92-11-10.99-11");
}

.b4vmzacii {
  stop-color: var(--svg-color--7f6260, #7F6260);
}

.bd-canb4c {
  stop-color: var(--svg-color--614451, #614451);
  stop-opacity: 0;
}

.bf2lz-yzq {
  d: path("m20.839 4.273l.429.214c.752.373 1.181 1.227 1.02 2.135l-.59 3.043c-.053.314-.26.526-.573.533h-.018s.054-.907.107-1.44c.044-.434-.032-.567-.43-.962c-.214-.213-.375-.534-.375-.854v-.854c0-.267-.215-.48-.43-.534c-.644-.16-1.986-.427-3.919-.427s-3.275.267-3.92.427a.52.52 0 0 0-.429.534v.854c0 .32-.107.64-.376.854l-.16.16c-.216.16-.323.48-.323.748c.054.587.107 1.441.107 1.441l-.049-.001a.634.634 0 0 1-.595-.533l-.59-3.043c-.108-.854.322-1.708 1.073-2.081l.43-.214c.268-.16.537-.374.805-.587L13 2.67c.59-.533 1.45-.694 2.201-.32c.537.16 1.127.16 1.664 0c.806-.267 1.719-.053 2.363.534l.805.8c.215.268.483.428.805.588");
}

.bn7rlk0uy {
  fill: var(--svg-color--000, #000);
  d: path("M17.687 10.49a.51.51 0 0 1 .511-.511a.51.51 0 0 1 .455.747h-.906a.46.46 0 0 1-.06-.236");
}

.bsnzn6jsv {
  d: path("m15.632 10.471l-.531 1.702a.54.54 0 0 0 .52.7h.787c.37 0 .63-.356.521-.7l-.531-1.702c-.114-.377-.646-.377-.766 0");
}

.btjaclc9y {
  d: path("M13.827 9.597a.893.893 0 0 0-.86 1.128h1.724a1 1 0 0 0 .033-.235a.9.9 0 0 0-.897-.893");
}

.bumyo9b5s {
  stop-color: var(--svg-color--464344, #464344);
  stop-opacity: 0;
}

.bvmj8ubsx {
  stop-color: var(--svg-color--31191a, #31191A);
}

.cd-mikbpl {
  stop-color: var(--svg-color--6f5048, #6F5048);
  stop-opacity: 0;
}

.cdm_o50ho {
  stop-color: var(--svg-color--533531, #533531);
}

.cesjesv2y {
  stop-color: var(--svg-color--52396b, #52396B);
  stop-opacity: 0;
}

.cgqcq-bjq {
  stop-color: var(--svg-color--675454, #675454);
}

.chixewryi {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M12.952 27.298H11.03");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cnmvr6bya {
  d: path("M13.363 25.362a.81.81 0 0 1-.302.668a.8.8 0 0 1 .302.636a.77.77 0 0 1-.302.637a.8.8 0 0 1 .302.637a.77.77 0 0 1-.302.636c.187.144.302.39.302.668c-.009.42-.32.75-.685.75H9.744c-.427 0-.774-.401-.774-.894v-3.604c0-.493.347-.893.774-.893h2.842c.475 0 .77.39.777.76");
}

.cokz6uveh {
  stop-color: var(--svg-color--6a5756, #6A5756);
}

.cpcxxz0lo {
  fill-rule: evenodd;
  d: path("M12.428 29.993v-8.406h-2.094v8.406z");
}

.cxrlhcc-d {
  stop-color: var(--svg-color--358175, #358175);
  stop-opacity: 0;
}

.d-7d0zb4w {
  cx: 20.785px;
  cy: 10.757px;
  r: 1.671px;
}

.d4d293bim {
  stop-color: var(--svg-color--4a4648, #4A4648);
}

.dph66t0ka {
  d: path("M22.694 29.993V17.75a10.98 10.98 0 0 1 4.32 8.744v3.5z");
}

.dqczsn00c {
  stop-color: var(--svg-color--4f3532, #4F3532);
}

.dqumds59m {
  stop-color: var(--svg-color--3c2929, #3C2929);
}

.dsm4f-bda {
  stop-color: var(--svg-color--332423, #332423);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e1bvu4b8w {
  stop-color: var(--svg-color--d78248, #D78248);
}

.e311nkbdi {
  d: path("M14.643 10.385c0-.289-.235-.481-.299-.54l-.288.28l.178.361z");
}

.e3noj1bpe {
  d: path("M18.198 9.597a.893.893 0 0 1 .86 1.129h-1.725a.897.897 0 0 1 .865-1.129");
}

.e5ivxs1br {
  stop-color: var(--svg-color--6b5858, #6B5858);
}

.e9zt2gbxt {
  stop-color: var(--svg-color--351d26, #351D26);
  stop-opacity: 0;
}

.eghqjhb7i {
  stop-color: var(--svg-color--392124, #392124);
}

.elsqsfztz {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M17.677 7.89c.43-.076 1.27-.054 1.851.398");
}

.f30052bab {
  stop-color: var(--svg-color--e9266f, #E9266F);
}

.fbs6uccsw {
  stop-color: var(--svg-color--281920, #281920);
}

.fczdhwb3o {
  stop-color: var(--svg-color--4f2e37, #4F2E37);
}

.fgkcx3bbf {
  stop-color: var(--svg-color--481e13, #481E13);
}

.fhksq8ilc {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M12.952 26.032H11.03");
}

.fnfe_1psv {
  stop-color: var(--svg-color--40272a, #40272A);
  stop-opacity: 0;
}

.foz7ccc1o {
  stop-color: var(--svg-color--251732, #251732);
}

.fqkeoivtf {
  stop-color: var(--svg-color--aba5a8, #ABA5A8);
}

.ft5dv1b6b {
  fill: none;
}

.fw_d1ac2c {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M11.478 5.94v.9c-.008.148-.07.48-.258.622");
}

.g043vp3zf {
  stop-color: var(--svg-color--bc7b53, #BC7B53);
}

.g0r5sc7jj {
  stop-color: var(--svg-color--3d2138, #3D2138);
  stop-opacity: 0;
}

.g2of_dbdx {
  stop-color: var(--svg-color--33141c, #33141C);
}

.g58wtjbuf {
  fill: var(--svg-color--332024, #332024);
  d: path("m15.74 10.634l-.822 1.702c-.101.35.143.7.489.7h.738c.346 0 .59-.356.488-.7l-.498-1.702c-.107-.376-.284-.376-.396 0");
}

.gg1n47rtb {
  stop-color: var(--svg-color--463c39, #463C39);
}

.gihkuibxq {
  stop-color: var(--svg-color--4a1d14, #4A1D14);
  stop-opacity: 0;
}

.gl-8uegyf {
  fill: var(--svg-color--4b3034, #4B3034);
  d: path("m15.632 10.471l-.531 1.702a.54.54 0 0 0 .52.7h.787c.37 0 .63-.356.521-.7l-.531-1.702c-.114-.377-.646-.377-.766 0");
}

.gnvm67mtb {
  stop-color: var(--svg-color--31171f, #31171F);
  stop-opacity: 0;
}

.goarh-wro {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M19.043 27.298h1.922");
}

.gugba3b_v {
  stop-color: var(--svg-color--33141c, #33141C);
  stop-opacity: 0;
}

.h8-lntwqp {
  stop-color: var(--svg-color--3f222f, #3F222F);
  stop-opacity: 0;
}

.hpdf2p89l {
  stop-color: var(--svg-color--25585f, #25585F);
}

.hyk2eqbsj {
  stop-color: var(--svg-color--2f1a1c, #2F1A1C);
}

.i3x270bvu {
  d: path("M22.067 23.101c.55 0 1 .45 1 1v2.29h-2v-2.29c0-.55.44-1 1-1");
}

.i5c5eto6f {
  stop-color: var(--svg-color--3d2138, #3D2138);
}

.iicpv44yj {
  stop-color: var(--svg-color--563a39, #563A39);
  stop-opacity: 0;
}

.ik2h44jfq {
  stop-color: var(--svg-color--744036, #744036);
}

.imbr-rb2t {
  cx: 11.262px;
  cy: 10.757px;
  r: 0.996px;
}

.iqm2531qk {
  stop-color: var(--svg-color--352123, #352123);
}

.iybe95oky {
  fill: var(--svg-color--21181b, #21181B);
  d: path("m20.839 4.273l.429.214c.752.373 1.181 1.227 1.02 2.135l-.59 3.043c-.053.314-.26.526-.573.533h-.018s.054-.907.107-1.44c.044-.434-.032-.567-.43-.962c-.214-.213-.375-.534-.375-.854v-.854c0-.267-.215-.48-.43-.534c-.644-.16-1.986-.427-3.919-.427s-3.275.267-3.92.427a.52.52 0 0 0-.429.534v.854c0 .32-.107.64-.376.854l-.16.16c-.216.16-.323.48-.323.748c.054.587.107 1.441.107 1.441l-.049-.001a.634.634 0 0 1-.595-.533l-.59-3.043c-.108-.854.322-1.708 1.073-2.081l.43-.214c.268-.16.537-.374.805-.587L13 2.67c.59-.533 1.45-.694 2.201-.32c.537.16 1.127.16 1.664 0c.806-.267 1.719-.053 2.363.534l.805.8c.215.268.483.428.805.588");
}

.j-n0q842a {
  stop-color: var(--svg-color--564440, #564440);
}

.j7sc31byj {
  stop-color: var(--svg-color--351d26, #351D26);
}

.ja44woagt {
  stop-color: var(--svg-color--4f2737, #4F2737);
}

.jddhx-i6n {
  d: path("M21.674 22.978v-2.286c0-.388-.36-.699-.81-.699h-8.659c-1.041 0-1.871.73-1.871 1.622c0 .753.61 1.363 1.363 1.363z");
}

.jgy1ttwjg {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.62 9.325c-.654 0-1.206.45-1.356 1.06a.274.274 0 0 0 .268.34h2.233a.23.23 0 0 0 .227-.272a1.4 1.4 0 0 0-1.372-1.128");
}

.jij-d9bro {
  stop-color: var(--svg-color--d78248, #D78248);
  stop-opacity: 0;
}

.jpk8o_7uj {
  stop-color: var(--svg-color--f69c5b, #F69C5B);
}

.jrokyri7f {
  fill: var(--svg-color--513358, #513358);
  fill-rule: evenodd;
  d: path("M12.428 29.993v-8.406h-2.094v8.406z");
}

.k_snybcwj {
  stop-color: var(--svg-color--6d6670, #6D6670);
}

.kb28pwbin {
  stop-color: var(--svg-color--412628, #412628);
}

.kfg1w5y8t {
  stop-color: var(--svg-color--6a5756, #6A5756);
  stop-opacity: 0;
}

.kiracnbim {
  stop-color: var(--svg-color--875955, #875955);
}

.kja3hpbzh {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.132 9.786c.064.085-.069.189-.22.302s-.264.192-.327.107c-.064-.085.007-.246.158-.359c.152-.113.326-.135.39-.05");
}

.kl3ja4pbq {
  stop-color: var(--svg-color--90645e, #90645E);
}

.krazlsbaw {
  stop-color: var(--svg-color--6f5048, #6F5048);
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.lbllohblp {
  d: path("m10.91 10.143l.05.002s-.054-.854-.108-1.441c0-.267.107-.588.322-.748l.161-.16c.269-.213.376-.534.376-.854v-.854a.52.52 0 0 1 .43-.534c.644-.16 1.986-.427 3.919-.427s3.275.267 3.92.427c.214.053.429.267.429.534v.854c0 .32.161.64.376.854c.502.352.471.546.43.961a46 46 0 0 0-.108 1.441h.018l-.266 3.963c-.16 1.77-1.553 3.005-3.214 3.005h-3.213c-1.714 0-3.053-1.234-3.213-3.005z");
}

.ldpzz4bsg {
  stop-color: var(--svg-color--624e4d, #624E4D);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lj0sm1b7l {
  stop-color: var(--svg-color--efbe85, #EFBE85);
}

.ljwtm1btc {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.405 9.325c.654 0 1.206.45 1.356 1.06a.274.274 0 0 1-.268.34H17.26a.23.23 0 0 1-.227-.271a1.4 1.4 0 0 1 1.372-1.13");
}

.ll06hnnpv {
  fill: var(--svg-color--000, #000);
  d: path("M14.338 10.49a.51.51 0 0 0-.511-.512a.51.51 0 0 0-.455.747h.905a.5.5 0 0 0 .061-.235");
}

.lvos55blo {
  stop-color: var(--svg-color--31191a, #31191A);
  stop-opacity: 0;
}

.lxewynbqt {
  d: path("m12.698 15.995l-1.384 2.987c-.09.19.05.41.26.41l.963-.266c.422-.105.437.277.277.437l-1.36 1.56c-.26.26-.36.65-.23 1l2.74 7.87v-14.4z");
}

.m_1e2qbpe {
  stop-color: var(--svg-color--423d3f, #423D3F);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mc9t6_o6r {
  stop-color: var(--svg-color--381d1a, #381D1A);
}

.mg63gccek {
  stop-color: var(--svg-color--3d2928, #3D2928);
  stop-opacity: 0;
}

.mjf0u6b4a {
  cx: 20.785px;
  cy: 10.757px;
  r: 0.996px;
}

.mrr7h_bzd {
  cx: 13.557px;
  cy: 9.978px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.n-4z7qb5o {
  stop-color: var(--svg-color--624d4b, #624D4B);
  stop-opacity: 0;
}

.n3g96cceg {
  stop-color: var(--svg-color--352123, #352123);
  stop-opacity: 0;
}

.n8mbjcbow {
  stop-color: var(--svg-color--875955, #875955);
  stop-opacity: 0;
}

.nc1ak66ax {
  stop-color: var(--svg-color--3c393a, #3C393A);
}

.nfwti5bbx {
  stop-color: var(--svg-color--509245, #509245);
}

.np-b1wbds {
  stop-color: var(--svg-color--27161d, #27161D);
}

.o-j_7gbpq {
  stop-color: var(--svg-color--564440, #564440);
  stop-opacity: 0;
}

.o1rzobcjq {
  stop-color: var(--svg-color--635251, #635251);
}

.o1syipbau {
  stop-color: var(--svg-color--685654, #685654);
  stop-opacity: 0;
}

.o6hm6qxaj {
  stop-color: var(--svg-color--3d2928, #3D2928);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.od6_koblh {
  stop-color: var(--svg-color--358175, #358175);
}

.os93-qygj {
  stop-color: var(--svg-color--402857, #402857);
}

.ov0ztps-s {
  d: path("M20.854 9.042h-3.47c-.3 0-.58.14-.77.37a.64.64 0 0 1-.51.24a.64.64 0 0 1-.51-.24c-.19-.23-.47-.37-.77-.37h-3.48c-.19 0-.34.15-.34.34v.22c0 .11.05.2.13.26c.04.03.07.08.07.13v1.1c0 1.05.85 1.91 1.91 1.91h.71c1.05 0 1.91-.85 1.91-1.91v-.61c.01-.2.17-.35.37-.35s.36.16.37.36v.6c0 1.05.85 1.91 1.91 1.91h.71c1.05 0 1.91-.85 1.91-1.91v-1.11c0-.05.02-.1.06-.13c.08-.06.13-.16.13-.26v-.21c0-.19-.15-.34-.34-.34m-5.46 1.95c0 .91-.74 1.65-1.65 1.65h-.55c-.91 0-1.65-.74-1.65-1.65v-.72c0-.49.39-.88.88-.88h2.08c.49 0 .89.39.89.88zm5.28 0c0 .91-.74 1.65-1.65 1.65h-.55c-.91 0-1.65-.74-1.65-1.65v-.72c0-.49.39-.88.88-.88h2.09c.49 0 .88.39.88.88z");
}

.ox51r5bse {
  stop-color: var(--svg-color--61332b, #61332B);
  stop-opacity: 0;
}

.p2s3ado1h {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M12.952 28.564H11.03");
}

.p3397-qvh {
  d: path("M18.132 9.786c.064.085-.069.189-.22.302s-.264.192-.327.107c-.064-.085.007-.246.158-.359c.152-.113.326-.135.39-.05");
}

.p8tdqzrvo {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M3.238 4.386h26.213a.1.1 0 0 1 .1.1v19.585");
}

.pcjq3gbcg {
  d: path("M3.024 23.983V4.993h25.99v18.99z");
}

.ph-yb3bws {
  stop-color: var(--svg-color--5b4b4d, #5B4B4D);
}

.pk72hc60b {
  stop-color: var(--svg-color--381d1a, #381D1A);
  stop-opacity: 0;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.qc5tyzrav {
  stop-color: var(--svg-color--423d3f, #423D3F);
}

.qd6c5fnlv {
  stop-color: var(--svg-color--593e3c, #593E3C);
}

.qgdka6bnc {
  stop-color: var(--svg-color--563032, #563032);
}

.qna-_2b3m {
  stop-color: var(--svg-color--764747, #764747);
}

.qo_nu3b1v {
  stop-color: var(--svg-color--5d3841, #5D3841);
  stop-opacity: 0;
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r3ewmblju {
  d: path("M9.314 29.993V17.75a10.98 10.98 0 0 0-4.32 8.744v3.5z");
}

.r4c-t7bme {
  stop-color: var(--svg-color--44803d, #44803D);
}

.r4xas9tfi {
  stop-color: var(--svg-color--bf1b74, #BF1B74);
}

.rd-uo94io {
  stop-color: var(--svg-color--72433e, #72433E);
}

.rkna2zbug {
  stop-color: var(--svg-color--61332b, #61332B);
}

.rou90ib5o {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("m12.238 8.035l.002-.002l.005-.004l.012-.01a2 2 0 0 1 .155-.107c.1-.063.24-.14.42-.211c.36-.142.872-.257 1.494-.158a.534.534 0 1 1-.167 1.055a1.77 1.77 0 0 0-.934.097a1.5 1.5 0 0 0-.309.165a.534.534 0 0 1-.68-.824");
}

.rqxi6yb_m {
  stop-color: var(--svg-color--7c5a5a, #7C5A5A);
}

.rr0ehkyum {
  d: path("M18.674 25.362a.81.81 0 0 0 .303.668a.8.8 0 0 0-.303.636c0 .267.116.503.303.637a.8.8 0 0 0-.303.637c0 .267.116.503.303.636a.84.84 0 0 0-.303.668c.01.42.32.75.685.75h2.935c.426 0 .773-.401.773-.894v-3.604c0-.493-.347-.893-.773-.893H19.45a.776.776 0 0 0-.777.76");
}

.ryydajfhb {
  stop-color: var(--svg-color--613327, #613327);
}

.s-cemd13j {
  stop-color: var(--svg-color--211415, #211415);
}

.sax4pugkt {
  d: path("M9.97 23.093c-.55 0-1 .45-1 1v2.29h2v-2.29c0-.55-.44-1-1-1");
}

.sihp1fb9k {
  stop-color: var(--svg-color--bc7b53, #BC7B53);
  stop-opacity: 0;
}

.t7pehib4f {
  d: path("M18.074 16.813h-4.11v13.18h4.11z");
}

.tl_2dbb_x {
  d: path("m19.982 5.127l-3.08 1.027a1.048 1.048 0 0 0 .47 2.033l3.063-.41z");
}

.tvk4-xbyn {
  fill: var(--svg-color--2a0219, #2A0219);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.652 13.517a2.96 2.96 0 0 0 1.363.323c.505 0 .97-.118 1.363-.323a.2.2 0 0 1 .242.04a.19.19 0 0 1 .021.24m-2.99-.28l2.948.253m-2.947-.253a.2.2 0 0 0-.242.041a.19.19 0 0 0-.02.24m.262-.281l-.221.253m3.21.028l-.041-.028m.041.028l-.041-.028m.041.028a1.95 1.95 0 0 1-1.626.869a1.95 1.95 0 0 1-1.626-.869m3.21-.028c-.335.508-.919.847-1.584.847s-1.25-.339-1.585-.847m-.04.028l.04-.028m-.04.028h-.001l.042-.028");
}

.u1egy7b7t {
  stop-color: var(--svg-color--e8ac81, #E8AC81);
}

.ub4gkwbqs {
  stop-color: var(--svg-color--764440, #764440);
}

.uck_nmbag {
  stop-color: var(--svg-color--412628, #412628);
  stop-opacity: 0;
}

.ui2kgq2tt {
  stop-color: var(--svg-color--464344, #464344);
}

.uk24qccae {
  stop-color: var(--svg-color--463c39, #463C39);
  stop-opacity: 0;
}

.upgdf1b_h {
  d: path("M29.394 24.983H2.644c-.34 0-.62-.28-.62-.62V4.613c0-.34.28-.62.62-.62h26.74c.35 0 .62.28.62.62v19.74a.61.61 0 0 1-.61.63");
}

.uqvywhymc {
  stop-color: var(--svg-color--8a5d57, #8A5D57);
}

.us4ivbb3t {
  stop-color: var(--svg-color--9a6d66, #9A6D66);
}

.ux8m6ubss {
  stop-color: var(--svg-color--b2acb9, #B2ACB9);
}

.uz53o4bgd {
  d: path("M10.334 21.873v8.12h11.34v-9.19c0-.45-.36-.81-.81-.81h-8.64c-1.05-.01-1.89.84-1.89 1.88");
}

.vpvekld5v {
  stop-color: var(--svg-color--3c393a, #3C393A);
  stop-opacity: 0;
}

.vuu7bk4vv {
  stop-color: var(--svg-color--735451, #735451);
}

.vwbk5fb5n {
  stop-color: var(--svg-color--180908, #180908);
}

.w1_1yhbve {
  stop-color: var(--svg-color--564848, #564848);
}

.w8755c4cc {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("M19.738 8.034h-.001l-.002-.002l-.005-.004l-.012-.01a1.4 1.4 0 0 0-.155-.107c-.1-.063-.24-.14-.42-.211a2.84 2.84 0 0 0-1.494-.158a.534.534 0 1 0 .167 1.055c.398-.063.717.01.934.097a1.5 1.5 0 0 1 .309.165a.534.534 0 0 0 .679-.825");
}

.wfc059byj {
  stop-color: var(--svg-color--25585f, #25585F);
  stop-opacity: 0;
}

.wi8di0b_n {
  stop-color: var(--svg-color--353435, #353435);
}

.wiin44g-j {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M19.043 28.564h1.922");
}

.wizsfxbnq {
  d: path("M29.014 23.983H3.024V4.993l-.92-.68c-.05.09-.08.2-.08.3v19.74c0 .35.28.62.62.62h26.74c.24 0 .44-.13.55-.33z");
}

.wn11gcx8f {
  stop-color: var(--svg-color--f1b58b, #F1B58B);
}

.wxov4bcam {
  d: path("m19.342 15.999l1.382 2.983c.09.19-.05.41-.26.41l-.964-.266c-.422-.105-.436.277-.276.437l1.36 1.56c.26.26.36.65.23 1l-2.74 7.87V15.6z");
}

.x15sxp3lc {
  cx: 11.263px;
  cy: 10.757px;
  r: 1.671px;
}

.x16kbobeb {
  stop-color: var(--svg-color--4f2737, #4F2737);
  stop-opacity: 0;
}

.x1tqnze9p {
  d: path("M11.167 21.485c0-.384.311-.695.695-.695h9.812v1.39h-9.812a.695.695 0 0 1-.695-.695");
}

.x3sd7rf5r {
  stop-color: var(--svg-color--362324, #362324);
}

.xb5iyf9xu {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M12.453 8.409c.327-.29 1.042-.594 1.929-.453");
}

.xtaxaigve {
  stop-color: var(--svg-color--624e4d, #624E4D);
  stop-opacity: 0;
}

.xtiplndwl {
  stop-color: var(--svg-color--3f222f, #3F222F);
}

.xtl7t4edr {
  stop-color: var(--svg-color--d18f7b, #D18F7B);
}

.y1ij6ubnw {
  stop-color: var(--svg-color--ffd59c, #FFD59C);
}

.y1kgfac6n {
  stop-color: var(--svg-color--8a5d57, #8A5D57);
  stop-opacity: 0;
}

.ybzr6jbff {
  stop-color: var(--svg-color--90645e, #90645E);
  stop-opacity: 0;
}

.yf38yz6vj {
  d: path("M16.024 18.663c-1.14 0-2.06-.92-2.06-2.06v-2.56c0-1.14.92-2.06 2.06-2.06s2.06.92 2.06 2.06v2.56a2.07 2.07 0 0 1-2.06 2.06");
}

.yf9erdbmk {
  stop-color: var(--svg-color--4a4648, #4A4648);
  stop-opacity: 0;
}

.ytssyfa7a {
  stop-color: var(--svg-color--40272a, #40272A);
}

.yvo_l_bkn {
  stop-color: var(--svg-color--9a6d66, #9A6D66);
  stop-opacity: 0;
}

.yww6tz8di {
  stop-color: var(--svg-color--624d4b, #624D4B);
}

.zagqne2ck {
  stop-color: var(--svg-color--2f1d1a, #2F1D1A);
}

.zbexf6jod {
  stop-color: var(--svg-color--564848, #564848);
  stop-opacity: 0;
}

.zlcjw7bgf {
  stop-color: var(--svg-color--61342d, #61342D);
}

.zobbewbqd {
  stop-color: var(--svg-color--52396b, #52396B);
}

.zomjjjh-z {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M19.043 26.032h1.922");
}

.zoxadnjxe {
  stop-color: var(--svg-color--31171f, #31171F);
}

.zs64g5eig {
  stop-color: var(--svg-color--623d44, #623D44);
}

.zx1idre_k {
  stop-color: var(--svg-color--353435, #353435);
  stop-opacity: 0;
}

</style>
