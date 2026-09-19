<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iqgq2Jn)"><path fill="url(#ixMdQGd)" class="g3n8x9bkk"/></g><path fill="url(#iVnY1Pe)" class="avp9rl5kc"/><path fill="url(#ikZ7NTb)" class="avp9rl5kc"/><path fill="url(#iX9DtDc)" class="avp9rl5kc"/><g filter="url(#iejHs9v)"><path stroke="url(#i4qLbnd)" class="v2f8j5bnu"/></g><g filter="url(#ii2q5dd)"><path fill="url(#iFvU85c)" class="u4cr62b2o"/><path fill="url(#iv6up4b)" class="u4cr62b2o"/><path fill="url(#ixf7Osc)" class="u4cr62b2o"/></g><g filter="url(#id1t2wn)"><path fill="url(#iYg0Vve)" clip-rule="evenodd" class="e428bgulp"/><path fill="url(#iHHL9Yr)" clip-rule="evenodd" class="e428bgulp"/><path fill="url(#iz6MaHi)" clip-rule="evenodd" class="e428bgulp"/><path fill="url(#i5Ii3hc)" clip-rule="evenodd" class="e428bgulp"/><path fill="url(#ifmgsec)" clip-rule="evenodd" class="e428bgulp"/><path fill="url(#i2yWRWx)" clip-rule="evenodd" class="e428bgulp"/><path fill="url(#i5l41Am)" clip-rule="evenodd" class="e428bgulp"/><path fill="url(#iNT2Fmb)" clip-rule="evenodd" class="e428bgulp"/><path fill="url(#i4OpNOb)" clip-rule="evenodd" class="e428bgulp"/><path fill="url(#ibnGuDb)" clip-rule="evenodd" class="e428bgulp"/><path fill="url(#iG2Urqe)" clip-rule="evenodd" class="e428bgulp"/><path fill="url(#i0ax7jd)" clip-rule="evenodd" class="e428bgulp"/></g><path fill="url(#iIEyGAd)" class="roasoobbm"/><path fill="url(#inJkvec)" class="roasoobbm"/><path fill="url(#iQQchba)" class="roasoobbm"/><path fill="url(#if01tZd)" class="sppliabuf"/><path fill="url(#isY6DOd)" class="sppliabuf"/><path fill="url(#ipxyvTc)" class="sppliabuf"/><path fill="url(#idyIrte)" class="ooqbvibma"/><path fill="url(#iEZFUDe)" class="ooqbvibma"/><path fill="url(#irtJZqd)" class="ujr2p9fja"/><g filter="url(#i2N8dKc)"><path fill="url(#i55EHDb)" class="k7y5k59sc"/><path fill="url(#iI0yace)" class="k7y5k59sc"/><path fill="url(#i69zDSd)" class="k7y5k59sc"/><path fill="url(#iYIDAkc)" class="k7y5k59sc"/></g><g filter="url(#ilZm12d)"><path fill="url(#ivh1Vje)" class="zq99eh__o"/><path fill="url(#i6bsgtc)" class="zq99eh__o"/><path fill="url(#iEDvrEe)" class="zq99eh__o"/><path fill="url(#ia93r2d)" class="zq99eh__o"/></g><path fill="url(#i2sFUDb)" class="mg_6p4b7m"/><g filter="url(#iFuX5xc)"><path fill="url(#iK9oRId)" class="p1jbbxbeq"/><path fill="url(#iciDDPc)" class="p1jbbxbeq"/></g><g filter="url(#iSaxssd)"><path fill="url(#iOTzVhc)" class="f0put-l6q"/></g><path fill="url(#if9Plhb)" class="oovee0bmi"/><path clip-rule="evenodd" class="ba-3r0b3f"/><path fill="url(#iToNNmb)" clip-rule="evenodd" class="vblumvbgz"/><g filter="url(#i1p1BAv)"><path fill="url(#iZFFNGc)" class="ri0kcvoxm"/><path fill="url(#i3Da4Dc)" class="ri0kcvoxm"/><path fill="url(#iUJ64cc)" class="ri0kcvoxm"/><path fill="url(#iqTpwrd)" class="ri0kcvoxm"/><path fill="url(#iO6jO9d)" class="ri0kcvoxm"/></g><g filter="url(#i36fVsd)"><path fill="url(#iThE90b)" class="fjl5cjbgb"/><path fill="url(#i6eXPqk)" class="fjl5cjbgb"/><path fill="url(#iFSOk7d)" class="fjl5cjbgb"/><path fill="url(#i1vsFec)" class="fjl5cjbgb"/><path fill="url(#iLbV4de)" class="fjl5cjbgb"/></g><path fill="url(#imFDyPb)" class="amagmsv2j"/><path fill="url(#iP3vrbc)" class="kq1l1r1dg"/><g filter="url(#i1z4d7b)"><path stroke="url(#iINEqrP)" class="t2sf3o33q"/></g><g filter="url(#izzOMUv)"><path stroke="url(#i1suOTb)" class="tiwgx3b7k"/></g><g filter="url(#i9qYVre)"><path stroke="url(#iEiPrdb)" class="j67xqyuka"/></g><g filter="url(#iExrhBb)"><path stroke="url(#i45tTOd)" class="c_78n-bpz"/></g><g filter="url(#iEKO4Vw)"><path stroke="url(#i2em54b)" class="ho3qhabae"/></g><g filter="url(#iEplCNc)"><path stroke="url(#iXesFGK)" class="lxlgm8z2u"/></g><g filter="url(#ikyUtig)"><path fill="url(#ijG0xNc)" class="nsqcbcbgj"/></g><g filter="url(#iagh0JV)"><path fill="url(#iRoDQ3u)" class="l3j8m4byi"/><path fill="url(#iKQ9tze)" class="l3j8m4byi"/></g><g filter="url(#i72gUst)"><path class="god2ypupl"/><path fill="url(#i4eYO9c)" class="hfcweccdr"/></g><g filter="url(#iKvxeoe)"><path class="l13euibzn"/><path fill="url(#iW8fkeH)" class="s7wstub1z"/></g><g filter="url(#iDv4JQd)"><path fill="url(#i14PKuc)" class="te34a41ur"/><path fill="url(#i7S69he)" class="te34a41ur"/><path fill="url(#iJEnIWE)" class="te34a41ur"/><path fill="url(#iKIuZkS)" class="te34a41ur"/><path fill="url(#itDthKd)" class="te34a41ur"/><path fill="url(#ihHRjHb)" class="te34a41ur"/><path fill="url(#iF1g9tc)" class="te34a41ur"/><path fill="url(#iTWclpe)" class="te34a41ur"/></g><path fill="url(#irI3MJe)" class="te34a41ur"/><path fill="url(#inAogWb)" class="te34a41ur"/><g filter="url(#iINxf3b)"><path class="pgunbccgj"/></g><g filter="url(#iqL7qWb)"><path class="yvbzu_iwu"/><path fill="url(#iQGWL4c)" class="tn667-bso"/><path fill="url(#i7TkFyd)" class="tn667-bso"/><path fill="url(#icSJDrd)" class="tn667-bso"/><path fill="url(#ikFsHdy)" class="tn667-bso"/></g><path fill="url(#i2Dq2wb)" class="tn667-bso"/><path fill="url(#i1tWj8d)" class="tn667-bso"/><path stroke="url(#i57HXwc)" class="n6qm1fbsv"/><g filter="url(#iQJNKCb)"><path class="b8dw2ebcg"/></g><g filter="url(#iDLCVCc)"><path class="ympidy8fx"/></g><g filter="url(#iuxOt8d)"><path class="rnwnxfbrn"/></g><g filter="url(#ioa7F2c)"><path clip-rule="evenodd" class="c5_b2m31o"/></g><path class="qsvq6lbfl"/><path fill="url(#iUje65b)" class="gtfpj_bde"/><path class="s-b_u7bzo"/><g filter="url(#idOnsne)"><path class="bp26m6g5w"/><path fill="url(#iuG0Bre)" class="dobt0dgyf"/></g><g filter="url(#iMki0wb)"><path fill="url(#iLUjPOd)" class="u2v5p9bdu"/></g><path class="oqnvn8b9n"/><path fill="url(#iNXQ8Le)" class="c7gvs5ghz"/><path class="qfm16-9lg"/><g filter="url(#iJD9acd)"><path fill="url(#iEgwYbd)" class="pr1xqbb7a"/></g><g filter="url(#iAw7rCd)"><ellipse transform="rotate(-27.914 13.51 9.99)" class="jdm38tbtl"/><ellipse fill="url(#i5S1BGd)" transform="rotate(-27.914 13.51 9.99)" class="qdx7hpd4p"/></g><g filter="url(#iTmciue)"><path class="i4po81b8l"/></g><g filter="url(#ibWYEIb)"><path class="vfy6rbc0u"/></g><g filter="url(#if34ziX)"><path class="zc0i69b4g"/><path fill="url(#ifWMKHe)" class="lxfbj-bzz"/></g><g filter="url(#ibgAXhe)"><path class="vi3ro6t_p"/><path fill="url(#if31Z6d)" class="g0vfs9bkg"/><path fill="url(#innYK2T)" class="g0vfs9bkg"/></g><g filter="url(#i2bc2vd)"><path stroke="url(#iUaXgtb)" class="oraxh2cjj"/></g><g filter="url(#iyOahbe)"><path class="v50lh8z4g"/></g><g filter="url(#iK8cDGd)"><path fill="url(#i8RkZcc)" class="nxyog_b_l"/><path fill="url(#iYi8mze)" class="nxyog_b_l"/></g><defs><radialGradient id="ikZ7NTb" cx="0" cy="0" r="1" gradientTransform="rotate(-56.746 27.051 6.9)scale(18.2363 24.9585)" gradientUnits="userSpaceOnUse"><stop class="hpdf2p89l"/><stop offset="1" class="wfc059byj"/></radialGradient><radialGradient id="iX9DtDc" cx="0" cy="0" r="1" gradientTransform="matrix(-9.99996 -14.06247 13.90983 -9.89141 29.572 25.488)" gradientUnits="userSpaceOnUse"><stop class="od6_koblh"/><stop offset="1" class="cxrlhcc-d"/></radialGradient><radialGradient id="ixf7Osc" cx="0" cy="0" r="1" gradientTransform="matrix(0 9.31138 -.61764 0 2.014 4.323)" gradientUnits="userSpaceOnUse"><stop offset=".355" class="g043vp3zf"/><stop offset="1" class="sihp1fb9k"/></radialGradient><radialGradient id="iHHL9Yr" cx="0" cy="0" r="1" gradientTransform="matrix(-.60473 4.56907 -5.70769 -.75542 15.666 13.19)" gradientUnits="userSpaceOnUse"><stop offset=".591" class="xdn388byj"/><stop offset="1" class="qwp4ni-tf"/></radialGradient><radialGradient id="iz6MaHi" cx="0" cy="0" r="1" gradientTransform="rotate(146.004 4.365 8.693)scale(3.485 4.57902)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="bl7uysvvb"/><stop offset="1" class="r_v2kebuk"/></radialGradient><radialGradient id="i5Ii3hc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.31023 1.7134 -1.31566 -1.00608 11.114 10.906)" gradientUnits="userSpaceOnUse"><stop offset=".334" class="l0xg-rbdf"/><stop offset="1" class="chj8m5e2t"/></radialGradient><radialGradient id="ifmgsec" cx="0" cy="0" r="1" gradientTransform="matrix(-1.29346 2.11654 -1.49092 -.91113 11.568 8.873)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="kbl3igr5c"/><stop offset="1" class="glo437b-m"/></radialGradient><radialGradient id="i2yWRWx" cx="0" cy="0" r="1" gradientTransform="matrix(1.37744 2.6205 -3.63764 1.9121 12.441 2.608)" gradientUnits="userSpaceOnUse"><stop class="paonnib9g"/><stop offset="1" class="g0r7omboq"/></radialGradient><radialGradient id="i5l41Am" cx="0" cy="0" r="1" gradientTransform="rotate(134.998 9.936 6.863)scale(2.04296 2.855)" gradientUnits="userSpaceOnUse"><stop class="hx66smwtj"/><stop offset="1" class="c9_6uxbfa"/></radialGradient><radialGradient id="iNT2Fmb" cx="0" cy="0" r="1" gradientTransform="rotate(163.779 11.047 6.59)scale(1.9243 4.01298)" gradientUnits="userSpaceOnUse"><stop class="cj4rfmfkx"/><stop offset="1" class="silozpblh"/></radialGradient><radialGradient id="i4OpNOb" cx="0" cy="0" r="1" gradientTransform="rotate(165.963 10.629 8.038)scale(2.90884 3.70543)" gradientUnits="userSpaceOnUse"><stop class="mxnnm4bur"/><stop offset="1" class="jk5udqbyz"/></radialGradient><radialGradient id="ibnGuDb" cx="0" cy="0" r="1" gradientTransform="rotate(-108.843 13 -3.712)scale(2.80647 2.21976)" gradientUnits="userSpaceOnUse"><stop class="hkormb2xp"/><stop offset="1" class="e-twaac7b"/></radialGradient><radialGradient id="iG2Urqe" cx="0" cy="0" r="1" gradientTransform="matrix(1.50721 .1581 -.25617 2.44212 9.813 9.794)" gradientUnits="userSpaceOnUse"><stop class="lgjudcrkd"/><stop offset="1" class="tr7czpf3k"/></radialGradient><radialGradient id="i0ax7jd" cx="0" cy="0" r="1" gradientTransform="matrix(-.87415 2.7925 -2.57415 -.8058 10.325 6.699)" gradientUnits="userSpaceOnUse"><stop offset=".243" class="gcrmpdfop"/><stop offset="1" class="nd--cppfl"/></radialGradient><radialGradient id="iIEyGAd" cx="0" cy="0" r="1" gradientTransform="matrix(0 14.0469 -6.21865 0 16.01 15.957)" gradientUnits="userSpaceOnUse"><stop class="zlcjw7bgf"/><stop offset="1" class="qna-_2b3m"/></radialGradient><radialGradient id="inJkvec" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.375 -2.9375 0 22.666 20.488)" gradientUnits="userSpaceOnUse"><stop class="us4ivbb3t"/><stop offset="1" class="yvo_l_bkn"/></radialGradient><radialGradient id="iQQchba" cx="0" cy="0" r="1" gradientTransform="matrix(-1.53125 1.53125 -1.23438 -1.23438 12.728 19.082)" gradientUnits="userSpaceOnUse"><stop class="rkna2zbug"/><stop offset="1" class="ox51r5bse"/></radialGradient><radialGradient id="if01tZd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -10.1875 3.85106 0 27.004 28.238)" gradientUnits="userSpaceOnUse"><stop class="rqxi6yb_m"/><stop offset="1" class="vuu7bk4vv"/></radialGradient><radialGradient id="iEZFUDe" cx="0" cy="0" r="1" gradientTransform="matrix(-6.92068 0 0 -17.2807 11.468 29.786)" gradientUnits="userSpaceOnUse"><stop offset=".576" class="qo_nu3b1v"/><stop offset="1" class="b4vmzacii"/></radialGradient><radialGradient id="irtJZqd" cx="0" cy="0" r="1" gradientTransform="matrix(3.59375 0 0 11.7969 15.197 20.3)" gradientUnits="userSpaceOnUse"><stop class="fqkeoivtf"/><stop offset="1" class="avo9uebvh"/></radialGradient><radialGradient id="iI0yace" cx="0" cy="0" r="1" gradientTransform="matrix(-1.59385 -3.38389 2.04685 -.9641 21.24 19.447)" gradientUnits="userSpaceOnUse"><stop class="kl3ja4pbq"/><stop offset="1" class="ybzr6jbff"/></radialGradient><radialGradient id="i69zDSd" cx="0" cy="0" r="1" gradientTransform="matrix(-.9453 -1.33595 .2433 -.17216 19.681 20.456)" gradientUnits="userSpaceOnUse"><stop class="uqvywhymc"/><stop offset="1" class="y1kgfac6n"/></radialGradient><radialGradient id="iYIDAkc" cx="0" cy="0" r="1" gradientTransform="matrix(.75 1.14843 -2.14967 1.40386 17.688 15.61)" gradientUnits="userSpaceOnUse"><stop offset=".359" class="fgkcx3bbf"/><stop offset="1" class="gihkuibxq"/></radialGradient><radialGradient id="i6bsgtc" cx="0" cy="0" r="1" gradientTransform="rotate(-88.854 17.15 3.282)scale(3.12563 1.26257)" gradientUnits="userSpaceOnUse"><stop class="kiracnbim"/><stop offset="1" class="n8mbjcbow"/></radialGradient><radialGradient id="ia93r2d" cx="0" cy="0" r="1" gradientTransform="matrix(-.26505 .89062 -1.66708 -.49612 14.219 16.024)" gradientUnits="userSpaceOnUse"><stop offset=".219" class="fgkcx3bbf"/><stop offset="1" class="gihkuibxq"/></radialGradient><radialGradient id="i2sFUDb" cx="0" cy="0" r="1" gradientTransform="scale(2.51976 3.34375)rotate(90 .6 5.755)" gradientUnits="userSpaceOnUse"><stop offset=".333" class="hyk2eqbsj"/><stop offset="1" class="s-cemd13j"/></radialGradient><radialGradient id="iK9oRId" cx="0" cy="0" r="1" gradientTransform="matrix(-1.12893 1.05533 -1.5203 -1.62634 22.646 23.774)" gradientUnits="userSpaceOnUse"><stop offset=".28" class="dqczsn00c"/><stop offset="1" class="zagqne2ck"/></radialGradient><radialGradient id="iciDDPc" cx="0" cy="0" r="1" gradientTransform="matrix(.61902 -.52682 .31382 .36874 22.788 23.493)" gradientUnits="userSpaceOnUse"><stop class="cokz6uveh"/><stop offset="1" class="kfg1w5y8t"/></radialGradient><radialGradient id="iOTzVhc" cx="0" cy="0" r="1" gradientTransform="matrix(1.16103 -.00547 .01713 3.63788 9.505 24.634)" gradientUnits="userSpaceOnUse"><stop offset=".303" class="dqumds59m"/><stop offset="1" class="vwbk5fb5n"/></radialGradient><radialGradient id="i3Da4Dc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.67187 0 0 -.65955 12.197 25.368)" gradientUnits="userSpaceOnUse"><stop class="e5ivxs1br"/><stop offset="1" class="iicpv44yj"/></radialGradient><radialGradient id="iUJ64cc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.53125 0 0 -.60407 12.213 26.65)" gradientUnits="userSpaceOnUse"><stop class="e5ivxs1br"/><stop offset="1" class="iicpv44yj"/></radialGradient><radialGradient id="iqTpwrd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.34375 0 0 -.5301 12.26 27.93)" gradientUnits="userSpaceOnUse"><stop class="e5ivxs1br"/><stop offset="1" class="iicpv44yj"/></radialGradient><radialGradient id="iO6jO9d" cx="0" cy="0" r="1" gradientTransform="matrix(-1.5 0 0 -.59174 12.33 29.29)" gradientUnits="userSpaceOnUse"><stop class="e5ivxs1br"/><stop offset="1" class="iicpv44yj"/></radialGradient><radialGradient id="i6eXPqk" cx="0" cy="0" r="1" gradientTransform="matrix(1.70312 0 0 .67188 21.26 25.368)" gradientUnits="userSpaceOnUse"><stop class="e5ivxs1br"/><stop offset="1" class="iicpv44yj"/></radialGradient><radialGradient id="iFSOk7d" cx="0" cy="0" r="1" gradientTransform="matrix(1.625 0 0 .64106 21.197 26.65)" gradientUnits="userSpaceOnUse"><stop class="e5ivxs1br"/><stop offset="1" class="iicpv44yj"/></radialGradient><radialGradient id="i1vsFec" cx="0" cy="0" r="1" gradientTransform="matrix(1.5625 0 0 .6164 21.103 27.93)" gradientUnits="userSpaceOnUse"><stop class="e5ivxs1br"/><stop offset="1" class="iicpv44yj"/></radialGradient><radialGradient id="iLbV4de" cx="0" cy="0" r="1" gradientTransform="matrix(1.4375 0 0 .56709 20.963 29.29)" gradientUnits="userSpaceOnUse"><stop class="e5ivxs1br"/><stop offset="1" class="iicpv44yj"/></radialGradient><radialGradient id="iRoDQ3u" cx="0" cy="0" r="1" gradientTransform="matrix(2.4945 -1.13387 1.3844 3.04568 20.017 11.124)" gradientUnits="userSpaceOnUse"><stop offset=".64" class="ayiod_bfg"/><stop offset=".944" class="wb78_hxsc"/></radialGradient><radialGradient id="iKQ9tze" cx="0" cy="0" r="1" gradientTransform="matrix(1.31865 .73911 -.20896 .3728 21.05 9)" gradientUnits="userSpaceOnUse"><stop class="s9u3_wbrp"/><stop offset="1" class="crde6o_5i"/></radialGradient><radialGradient id="i4eYO9c" cx="0" cy="0" r="1" gradientTransform="matrix(1.5132 -.11256 .088 1.1829 20.37 10.797)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="rmmi4abgs"/><stop offset="1" class="xuyenabum"/></radialGradient><radialGradient id="iW8fkeH" cx="0" cy="0" r="1" gradientTransform="matrix(-1.20946 0 0 -.95411 11.358 10.684)" gradientUnits="userSpaceOnUse"><stop offset=".667" class="pj2ff5nxp"/><stop offset="1" class="sdufqstmc"/></radialGradient><radialGradient id="i14PKuc" cx="0" cy="0" r="1" gradientTransform="matrix(-6.51782 3.00558 -4.02292 -8.724 18.834 10.146)" gradientUnits="userSpaceOnUse"><stop class="aj61gebdf"/><stop offset="1" class="v2xpqhbrh"/></radialGradient><radialGradient id="i7S69he" cx="0" cy="0" r="1" gradientTransform="matrix(-2.0409 .9729 -.6775 -1.42126 17.8 10.99)" gradientUnits="userSpaceOnUse"><stop class="o3k0towjz"/><stop offset="1" class="x7h3p2bdy"/></radialGradient><radialGradient id="iJEnIWE" cx="0" cy="0" r="1" gradientTransform="matrix(1.07583 -3.4837 4.42016 1.36503 13.784 16.943)" gradientUnits="userSpaceOnUse"><stop class="cctx1cb1y"/><stop offset="1" class="xfmbn4_bb"/></radialGradient><radialGradient id="iKIuZkS" cx="0" cy="0" r="1" gradientTransform="matrix(-.80382 6.8149 -6.8514 -.80813 16.51 10.302)" gradientUnits="userSpaceOnUse"><stop offset=".727" class="m6mmhsf1n"/><stop offset="1" class="do3fwrbgr"/></radialGradient><radialGradient id="itDthKd" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.58129 -6.61653 0 15.706 10.536)" gradientUnits="userSpaceOnUse"><stop offset=".794" class="d0fyzsbqc"/><stop offset="1" class="n8ysctycz"/></radialGradient><radialGradient id="ihHRjHb" cx="0" cy="0" r="1" gradientTransform="rotate(168.897 8.314 6.804)scale(7.0528 12.1427)" gradientUnits="userSpaceOnUse"><stop offset=".795" class="f6uv1pf_h"/><stop offset="1" class="fp6zmm73k"/></radialGradient><radialGradient id="iF1g9tc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.15329 1.4154 0 18.275 9.726)" gradientUnits="userSpaceOnUse"><stop class="yv4uycbmh"/><stop offset="1" class="wgpm0ibqw"/></radialGradient><radialGradient id="iTWclpe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.31539 1.50752 0 13.888 9.497)" gradientUnits="userSpaceOnUse"><stop class="f82mfcbsw"/><stop offset="1" class="xkhh7vb2n"/></radialGradient><radialGradient id="irI3MJe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.2881 0 0 -6.45969 21.075 11.217)" gradientUnits="userSpaceOnUse"><stop class="jids0zpwm"/><stop offset="1" class="zz4mcgrzh"/></radialGradient><radialGradient id="inAogWb" cx="0" cy="0" r="1" gradientTransform="rotate(139.279 7.115 11.329)scale(2.41854 1.62097)" gradientUnits="userSpaceOnUse"><stop class="ybvm9tprh"/><stop offset=".694" class="yxwqgvbem"/></radialGradient><radialGradient id="iQGWL4c" cx="0" cy="0" r="1" gradientTransform="matrix(-.45654 -2.04848 .63133 -.1407 16.755 11.946)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="x_sue_b_g"/><stop offset="1" class="gl9okfban"/></radialGradient><radialGradient id="ikFsHdy" cx="0" cy="0" r="1" gradientTransform="matrix(-.7811 0 0 -.21838 16.515 12.157)" gradientUnits="userSpaceOnUse"><stop class="t5djkhb4t"/><stop offset="1" class="qm132ccsa"/></radialGradient><radialGradient id="i1tWj8d" cx="0" cy="0" r="1" gradientTransform="matrix(-1.37421 .94345 -1.13388 -1.6516 16.347 11.561)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="i669rlbzr"/><stop offset="1" class="yt9sv1b9n"/></radialGradient><radialGradient id="iUje65b" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81267 -1.29264 0 18.155 10.085)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iuG0Bre" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 11.454 .695)scale(.37892 .52167)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iNXQ8Le" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81268 -1.29265 0 13.781 10.085)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="i5S1BGd" cx="0" cy="0" r="1" gradientTransform="matrix(-.00775 -.49489 .59487 -.00931 13.495 10.305)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ifWMKHe" cx="0" cy="0" r="1" gradientTransform="matrix(1.2648 -2.76146 1.4127 .64704 10.298 7.96)" gradientUnits="userSpaceOnUse"><stop class="cuv4n92_b"/><stop offset="1" class="mq6wd3bba"/></radialGradient><radialGradient id="if31Z6d" cx="0" cy="0" r="1" gradientTransform="matrix(-2.11658 4.40107 -7.19549 -3.46048 17.884 2.742)" gradientUnits="userSpaceOnUse"><stop offset=".639" class="ssbc2ccsr"/><stop offset="1" class="ou3onybvn"/></radialGradient><radialGradient id="innYK2T" cx="0" cy="0" r="1" gradientTransform="rotate(98.746 6.755 8.497)scale(1.38631 2.98257)" gradientUnits="userSpaceOnUse"><stop class="g5d3hjacf"/><stop offset="1" class="j2p90_-bc"/></radialGradient><radialGradient id="iYi8mze" cx="0" cy="0" r="1" gradientTransform="matrix(.90625 0 0 2.71875 11.385 10.161)" gradientUnits="userSpaceOnUse"><stop class="zobbewbqd"/><stop offset="1" class="cesjesv2y"/></radialGradient><filter id="iqgq2Jn" width="27.98" height="21.09" x="2.014" y="4.003" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.81585 0 0 0 0 0.641744 0 0 0 0 0.41905 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1656"/></filter><filter id="iejHs9v" width="27.413" height="20.785" x="2.678" y="3.847" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1656" stdDeviation=".2"/></filter><filter id="ii2q5dd" width="27.91" height="20.96" x="2.014" y="4.023" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.3"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.85098 0 0 0 0 0.482353 0 0 0 0 0.647059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1656"/></filter><filter id="id1t2wn" width="15.301" height="15.801" x="8.443" y="1.387" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.121569 0 0 0 0 0.0705882 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1656"/></filter><filter id="i2N8dKc" width="2.797" height="14.493" x="18.064" y="15.51" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.380392 0 0 0 0 0.164706 0 0 0 0 0.203922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1656"/></filter><filter id="ilZm12d" width="2.797" height="14.501" x="11.157" y="15.502" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.380392 0 0 0 0 0.164706 0 0 0 0 0.203922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1656"/></filter><filter id="iFuX5xc" width="2.1" height="3.39" x="20.957" y="23.111" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.396078 0 0 0 0 0.317647 0 0 0 0 0.301961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1656"/></filter><filter id="iSaxssd" width="2.1" height="3.29" x="8.96" y="23.103" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.32549 0 0 0 0 0.25098 0 0 0 0 0.243137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1656"/></filter><filter id="i1p1BAv" width="4.793" height="5.391" x="8.96" y="24.613" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.34902 0 0 0 0 0.286275 0 0 0 0 0.27451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1656"/></filter><filter id="i36fVsd" width="4.793" height="5.591" x="18.464" y="24.413" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.231373 0 0 0 0 0.133333 0 0 0 0 0.196078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1656"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.392157 0 0 0 0 0.313726 0 0 0 0 0.305882 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1656" result="effect2_innerShadow_4002_1656"/></filter><filter id="i1z4d7b" width="2.222" height=".3" x="18.883" y="25.892" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1656" stdDeviation=".05"/></filter><filter id="izzOMUv" width="2.222" height=".3" x="10.87" y="25.892" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1656" stdDeviation=".05"/></filter><filter id="i9qYVre" width="2.222" height=".3" x="18.883" y="27.158" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1656" stdDeviation=".05"/></filter><filter id="iExrhBb" width="2.222" height=".3" x="10.87" y="27.158" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1656" stdDeviation=".05"/></filter><filter id="iEKO4Vw" width="2.222" height=".3" x="18.883" y="28.424" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1656" stdDeviation=".05"/></filter><filter id="iEplCNc" width="2.222" height=".3" x="10.87" y="28.424" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1656" stdDeviation=".05"/></filter><filter id="ikyUtig" width="3.375" height="3.225" x="9.66" y="9.072" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.337255 0 0 0 0 0.266667 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1656"/></filter><filter id="iagh0JV" width="3.225" height="3.475" x="19.194" y="8.822" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.184314 0 0 0 0 0.0901961 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1656"/></filter><filter id="i72gUst" width="3.153" height="3.153" x="19.23" y="9.108" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1656" stdDeviation=".25"/></filter><filter id="iKvxeoe" width="2.653" height="2.653" x="9.966" y="9.358" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1656" stdDeviation=".125"/></filter><filter id="iDv4JQd" width="10.213" height="11.151" x="10.862" y="5.767" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.14902 0 0 0 0 0.0901961 0 0 0 0 0.0941176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1656"/></filter><filter id="iINxf3b" width="2.881" height="3.688" x="14.366" y="9.678" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1656" stdDeviation=".25"/></filter><filter id="iqL7qWb" width="2.381" height="3.188" x="14.778" y="9.789" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1656" stdDeviation=".125"/></filter><filter id="iQJNKCb" width="3.008" height="1.288" x="16.913" y="9.276" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0941176 0 0 0 0 0.0666667 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1656"/></filter><filter id="iDLCVCc" width="3.008" height="1.288" x="12.017" y="9.276" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0862745 0 0 0 0 0.054902 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1656"/></filter><filter id="iuxOt8d" width="2.458" height="1.093" x="12.152" y="7.85" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0235294 0 0 0 0 0.0313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1656"/></filter><filter id="ioa7F2c" width="2.458" height="1.093" x="17.581" y="7.85" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0235294 0 0 0 0 0.0313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1656"/></filter><filter id="idOnsne" width=".788" height=".697" x="17.42" y="9.645" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1656" stdDeviation=".05"/></filter><filter id="iMki0wb" width=".893" height=".915" x="18.262" y="9.721" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1656" stdDeviation=".1"/></filter><filter id="iJD9acd" width=".988" height="1.042" x="13.809" y="9.657" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1656" stdDeviation=".1"/></filter><filter id="iAw7rCd" width=".914" height=".705" x="13.053" y="9.637" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1656" stdDeviation=".05"/></filter><filter id="iTmciue" width="2.864" height="1.578" x="17.313" y="7.673" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1656" stdDeviation=".2"/></filter><filter id="ibWYEIb" width="2.864" height="1.578" x="11.85" y="7.673" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1656" stdDeviation=".2"/></filter><filter id="if34ziX" width="4.419" height="4.721" x="9.501" y="3.628" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.352941 0 0 0 0 0.341176 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1656"/><feGaussianBlur result="effect2_foregroundBlur_4002_1656" stdDeviation=".25"/></filter><filter id="ibgAXhe" width="8.785" height="5.794" x="12.792" y="2.591" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".2"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.345098 0 0 0 0 0.329412 0 0 0 0 0.333333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1656"/><feGaussianBlur result="effect2_foregroundBlur_4002_1656" stdDeviation=".125"/></filter><filter id="i2bc2vd" width="1.146" height="2.313" x="12.771" y="3.828" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1656" stdDeviation=".1"/></filter><filter id="iyOahbe" width="6.438" height="3.376" x="15.387" y="4.639" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1656" stdDeviation=".375"/></filter><filter id="iK8cDGd" width="10.29" height="4.16" x="10.894" y="8.551" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.381221 0 0 0 0 0.2699 0 0 0 0 0.482422 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1656"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.2 0 0 0 0 0.109804 0 0 0 0 0.211765 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1656" result="effect2_innerShadow_4002_1656"/></filter><linearGradient id="ixMdQGd" x1="11.828" x2="31.271" y1="4.612" y2="22.848" gradientUnits="userSpaceOnUse"><stop class="lj0sm1b7l"/><stop offset=".568" class="u1egy7b7t"/><stop offset="1" class="auorgtyhp"/></linearGradient><linearGradient id="iVnY1Pe" x1="30.072" x2="9.135" y1="13.3" y2="13.3" gradientUnits="userSpaceOnUse"><stop class="nfwti5bbx"/><stop offset="1" class="r4c-t7bme"/></linearGradient><linearGradient id="i4qLbnd" x1="13.447" x2="31.259" y1="3.553" y2="24.366" gradientUnits="userSpaceOnUse"><stop class="y1ij6ubnw"/><stop offset="1" class="jpk8o_7uj"/></linearGradient><linearGradient id="iFvU85c" x1="-4.897" x2="28.916" y1="25.644" y2="25.644" gradientUnits="userSpaceOnUse"><stop class="xtl7t4edr"/><stop offset="1" class="wn11gcx8f"/></linearGradient><linearGradient id="iv6up4b" x1="3.103" x2="3.103" y1="5.206" y2="23.644" gradientUnits="userSpaceOnUse"><stop class="e1bvu4b8w"/><stop offset="1" class="jij-d9bro"/></linearGradient><linearGradient id="iYg0Vve" x1="20.672" x2="13.852" y1="3.716" y2="16.348" gradientUnits="userSpaceOnUse"><stop class="hjtn79bml"/><stop offset="1" class="a4-v90a8k"/></linearGradient><linearGradient id="isY6DOd" x1="25.183" x2="25.183" y1="30.457" y2="26.64" gradientUnits="userSpaceOnUse"><stop class="ax9s6wi3k"/><stop offset="1" class="bd-canb4c"/></linearGradient><linearGradient id="ipxyvTc" x1="22.416" x2="23.228" y1="29.269" y2="29.253" gradientUnits="userSpaceOnUse"><stop offset=".254" class="ja44woagt"/><stop offset="1" class="x16kbobeb"/></linearGradient><linearGradient id="idyIrte" x1="7.144" x2="9.538" y1="28.151" y2="28.151" gradientUnits="userSpaceOnUse"><stop class="zs64g5eig"/><stop offset="1" class="fczdhwb3o"/></linearGradient><linearGradient id="i55EHDb" x1="18.064" x2="20.86" y1="18.378" y2="18.378" gradientUnits="userSpaceOnUse"><stop class="ryydajfhb"/><stop offset=".371" class="ub4gkwbqs"/></linearGradient><linearGradient id="ivh1Vje" x1="13.954" x2="11.157" y1="18.378" y2="18.378" gradientUnits="userSpaceOnUse"><stop class="ik2h44jfq"/><stop offset=".639" class="rd-uo94io"/></linearGradient><linearGradient id="iEDvrEe" x1="12.119" x2="12.681" y1="16.941" y2="17.16" gradientUnits="userSpaceOnUse"><stop class="krazlsbaw"/><stop offset="1" class="cd-mikbpl"/></linearGradient><linearGradient id="if9Plhb" x1="21.853" x2="17.478" y1="24.8" y2="24.8" gradientUnits="userSpaceOnUse"><stop class="f30052bab"/><stop offset="1" class="r4xas9tfi"/></linearGradient><linearGradient id="iToNNmb" x1="10.324" x2="10.752" y1="23.581" y2="23.581" gradientUnits="userSpaceOnUse"><stop class="k_snybcwj"/><stop offset="1" class="a_s1o9xch"/></linearGradient><linearGradient id="iZFFNGc" x1="12.509" x2="8.572" y1="28.019" y2="28.019" gradientUnits="userSpaceOnUse"><stop class="qgdka6bnc"/><stop offset="1" class="a-cpf7b0f"/></linearGradient><linearGradient id="iThE90b" x1="22.478" x2="18.664" y1="27.613" y2="27.613" gradientUnits="userSpaceOnUse"><stop class="qd6c5fnlv"/><stop offset=".807" class="eghqjhb7i"/></linearGradient><linearGradient id="imFDyPb" x1="10.791" x2="21.664" y1="21.956" y2="21.956" gradientUnits="userSpaceOnUse"><stop class="auppp8bgz"/><stop offset="1" class="auppp8bgz"/></linearGradient><linearGradient id="iP3vrbc" x1="16.41" x2="16.41" y1="21.019" y2="22.191" gradientUnits="userSpaceOnUse"><stop class="alxt_0b7l"/><stop offset="1" class="ux8m6ubss"/></linearGradient><linearGradient id="iINEqrP" x1="19.033" x2="20.861" y1="26.121" y2="26.121" gradientUnits="userSpaceOnUse"><stop class="g2of_dbdx"/><stop offset="1" class="gugba3b_v"/></linearGradient><linearGradient id="i1suOTb" x1="12.942" x2="10.744" y1="26.121" y2="26.121" gradientUnits="userSpaceOnUse"><stop class="mc9t6_o6r"/><stop offset="1" class="pk72hc60b"/></linearGradient><linearGradient id="iEiPrdb" x1="19.033" x2="20.861" y1="27.386" y2="27.386" gradientUnits="userSpaceOnUse"><stop class="g2of_dbdx"/><stop offset="1" class="gugba3b_v"/></linearGradient><linearGradient id="i45tTOd" x1="12.942" x2="10.744" y1="27.386" y2="27.386" gradientUnits="userSpaceOnUse"><stop class="mc9t6_o6r"/><stop offset="1" class="pk72hc60b"/></linearGradient><linearGradient id="i2em54b" x1="19.033" x2="20.861" y1="28.652" y2="28.652" gradientUnits="userSpaceOnUse"><stop class="g2of_dbdx"/><stop offset="1" class="gugba3b_v"/></linearGradient><linearGradient id="iXesFGK" x1="12.942" x2="10.744" y1="28.652" y2="28.652" gradientUnits="userSpaceOnUse"><stop class="mc9t6_o6r"/><stop offset="1" class="pk72hc60b"/></linearGradient><linearGradient id="ijG0xNc" x1="9.66" x2="12.626" y1="10.771" y2="10.771" gradientUnits="userSpaceOnUse"><stop class="z_wfxjr5n"/><stop offset="1" class="qenr6bbwz"/></linearGradient><linearGradient id="i7TkFyd" x1="15.028" x2="15.969" y1="12.018" y2="12.018" gradientUnits="userSpaceOnUse"><stop class="o6hm6qxaj"/><stop offset="1" class="mg63gccek"/></linearGradient><linearGradient id="icSJDrd" x1="15.969" x2="15.969" y1="12.819" y2="12.207" gradientUnits="userSpaceOnUse"><stop class="cctx1cb1y"/><stop offset="1" class="xfmbn4_bb"/></linearGradient><linearGradient id="i2Dq2wb" x1="16.047" x2="16.047" y1="12.793" y2="12.653" gradientUnits="userSpaceOnUse"><stop class="kos78---c"/><stop offset="1" class="wq1w-qb8s"/></linearGradient><linearGradient id="i57HXwc" x1="14.902" x2="15.364" y1="14.232" y2="13.518" gradientUnits="userSpaceOnUse"><stop class="w1_1yhbve"/><stop offset=".663" class="zbexf6jod"/></linearGradient><linearGradient id="iLUjPOd" x1="18.936" x2="18.621" y1="10.14" y2="10.334" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iEgwYbd" x1="14.528" x2="14.213" y1="10.14" y2="10.334" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iUaXgtb" x1="13.071" x2="13.617" y1="4.472" y2="5.748" gradientUnits="userSpaceOnUse"><stop class="z66p5h_5k"/><stop offset="1" class="ll4sw0vun"/></linearGradient><linearGradient id="i8RkZcc" x1="16.089" x2="16.089" y1="9.057" y2="12.838" gradientUnits="userSpaceOnUse"><stop class="os93-qygj"/><stop offset="1" class="foz7ccc1o"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-teacher-dark" /></template>
<style>
.a_s1o9xch {
  stop-color: var(--svg-color--6d6670, #6D6670);
  stop-opacity: 0;
}

.a-cpf7b0f {
  stop-color: var(--svg-color--3d282b, #3D282B);
}

.a4-v90a8k {
  stop-color: var(--svg-color--1a1718, #1A1718);
}

.aj61gebdf {
  stop-color: var(--svg-color--4f322e, #4F322E);
}

.alxt_0b7l {
  stop-color: var(--svg-color--dcd5e1, #DCD5E1);
}

.amagmsv2j {
  d: path("M21.664 22.988v-2.286c0-.388-.36-.699-.81-.699h-8.659c-1.041 0-1.871.73-1.871 1.622c0 .753.61 1.363 1.363 1.363z");
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

.avp9rl5kc {
  d: path("M3.014 23.993V5.003h25.99v18.99z");
}

.ax9s6wi3k {
  stop-color: var(--svg-color--614451, #614451);
}

.ayiod_bfg {
  stop-color: var(--svg-color--493033, #493033);
}

.b4vmzacii {
  stop-color: var(--svg-color--7f6260, #7F6260);
}

.b8dw2ebcg {
  fill: var(--svg-color--2d2b2e, #2D2B2E);
  d: path("M17.113 10.114c.266-.468.67-.838 1.541-.838c.381 0 .749.106 1.075.37c.27.218.234.496.025.6l-.557.319c-.654-.211-1.376-.24-2.084-.451");
}

.ba-3r0b3f {
  fill: var(--svg-color--513358, #513358);
  fill-rule: evenodd;
  d: path("M12.418 30.003v-8.406h-2.094v8.406z");
}

.bd-canb4c {
  stop-color: var(--svg-color--614451, #614451);
  stop-opacity: 0;
}

.bl7uysvvb {
  stop-color: var(--svg-color--181518, #181518);
}

.bp26m6g5w {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.091 9.797c.064.085-.069.189-.22.302c-.152.113-.264.193-.328.108c-.063-.086.008-.246.16-.36c.15-.113.325-.135.388-.05");
}

.c_78n-bpz {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M12.942 27.308H11.02");
}

.c5_b2m31o {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  fill-rule: evenodd;
  d: path("m19.708 8.444l-.138.23za.269.269 0 0 1-.275.461h-.001l-.004-.003l-.022-.012l-.092-.046a3 3 0 0 0-.343-.135a2.3 2.3 0 0 0-1.074-.092a.269.269 0 1 1-.094-.53c.515-.09.99.001 1.332.11a3.3 3.3 0 0 1 .56.239l.009.005l.003.002z");
}

.c7gvs5ghz {
  d: path("M13.78 9.608a.894.894 0 0 0-.862 1.13h1.727a1 1 0 0 0 .032-.236a.9.9 0 0 0-.898-.894");
}

.c9_6uxbfa {
  stop-color: var(--svg-color--4a4446, #4A4446);
  stop-opacity: 0;
}

.cctx1cb1y {
  stop-color: var(--svg-color--3a1f30, #3A1F30);
}

.cd-mikbpl {
  stop-color: var(--svg-color--6f5048, #6F5048);
  stop-opacity: 0;
}

.cesjesv2y {
  stop-color: var(--svg-color--52396b, #52396B);
  stop-opacity: 0;
}

.chj8m5e2t {
  stop-color: var(--svg-color--040101, #040101);
  stop-opacity: 0;
}

.cj4rfmfkx {
  stop-color: var(--svg-color--3b3638, #3B3638);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cokz6uveh {
  stop-color: var(--svg-color--6a5756, #6A5756);
}

.crde6o_5i {
  stop-color: var(--svg-color--402824, #402824);
  stop-opacity: 0;
}

.cuv4n92_b {
  stop-color: var(--svg-color--433838, #433838);
}

.cxrlhcc-d {
  stop-color: var(--svg-color--358175, #358175);
  stop-opacity: 0;
}

.d0fyzsbqc {
  stop-color: var(--svg-color--3b232b, #3B232B);
  stop-opacity: 0;
}

.do3fwrbgr {
  stop-color: var(--svg-color--3f243b, #3F243B);
}

.dobt0dgyf {
  d: path("M18.091 9.797c.064.085-.069.189-.22.302c-.152.113-.264.193-.328.108c-.063-.086.008-.246.16-.36c.15-.113.325-.135.388-.05");
}

.dqczsn00c {
  stop-color: var(--svg-color--4f3532, #4F3532);
}

.dqumds59m {
  stop-color: var(--svg-color--3c2929, #3C2929);
}

.e-twaac7b {
  stop-color: var(--svg-color--575455, #575455);
  stop-opacity: 0;
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e1bvu4b8w {
  stop-color: var(--svg-color--d78248, #D78248);
}

.e428bgulp {
  fill-rule: evenodd;
  d: path("M23.17 12.097a3.25 3.25 0 0 0 .324-1.43c0-.469-.096-.908-.269-1.309h.005a3 3 0 0 0-.281-.514l-.002-.003a3.25 3.25 0 0 1-.528-1.775v-.01a3.307 3.307 0 0 0-3.306-3.306a.54.54 0 0 1-.457-.233a3.31 3.31 0 0 0-2.687-1.38c-1.106 0-2.09.548-2.688 1.38a.57.57 0 0 1-.456.233h-.086a3.307 3.307 0 0 0-3.22 3.306v.01c0 .63-.183 1.248-.528 1.775l-.002.004a3.3 3.3 0 0 0-.221 3.252a.52.52 0 0 1 0 .456a3.22 3.22 0 0 0 2.9 4.635h8.601a3.22 3.22 0 0 0 2.9-4.635a.52.52 0 0 1 0-.456M10.883 9.419h-.013l1.202 2.36c.123 2.809 1.22 0 3.897 0s3.844 3.127 3.968.318l1.138-3.204c-.053-1.248-.958-1.335-1.138-1.335H16.71a3.87 3.87 0 0 1-3.196-1.677a.264.264 0 0 0-.463.05l-.082.195a2.3 2.3 0 0 1-1.295 1.278c-.236.123-.791.491-.812 1.442l.01.307z");
}

.e5ivxs1br {
  stop-color: var(--svg-color--6b5858, #6B5858);
}

.eghqjhb7i {
  stop-color: var(--svg-color--392124, #392124);
}

.f0put-l6q {
  d: path("M9.96 23.103c-.55 0-1 .45-1 1v2.29h2v-2.29c0-.55-.44-1-1-1");
}

.f30052bab {
  stop-color: var(--svg-color--e9266f, #E9266F);
}

.f6uv1pf_h {
  stop-color: var(--svg-color--5e4543, #5E4543);
  stop-opacity: 0;
}

.f82mfcbsw {
  stop-color: var(--svg-color--371e27, #371E27);
}

.fczdhwb3o {
  stop-color: var(--svg-color--4f2e37, #4F2E37);
}

.fgkcx3bbf {
  stop-color: var(--svg-color--481e13, #481E13);
}

.fjl5cjbgb {
  d: path("M18.664 25.373a.81.81 0 0 0 .303.667a.8.8 0 0 0-.303.637c0 .267.116.503.303.636a.8.8 0 0 0-.303.637c0 .267.116.503.303.637a.84.84 0 0 0-.303.667c.01.42.32.75.685.75h2.935c.426 0 .773-.401.773-.894v-3.604c0-.493-.347-.893-.773-.893H19.44a.776.776 0 0 0-.777.76");
}

.foz7ccc1o {
  stop-color: var(--svg-color--251732, #251732);
}

.fp6zmm73k {
  stop-color: var(--svg-color--5e4543, #5E4543);
}

.fqkeoivtf {
  stop-color: var(--svg-color--aba5a8, #ABA5A8);
}

.ft5dv1b6b {
  fill: none;
}

.g043vp3zf {
  stop-color: var(--svg-color--bc7b53, #BC7B53);
}

.g0r7omboq {
  stop-color: var(--svg-color--474445, #474445);
  stop-opacity: 0;
}

.g0vfs9bkg {
  d: path("M15.364 2.876c-1.135-.25-2.154.882-2.272 1.302c1.054 3.553 3.721 3.358 6.354 3.066c1.576-.175 1.747.543 1.881.89c0-3.941-3.351-4.681-5.934-5.251z");
}

.g2of_dbdx {
  stop-color: var(--svg-color--33141c, #33141C);
}

.g3n8x9bkk {
  d: path("M29.384 24.993H2.634c-.34 0-.62-.28-.62-.62V4.623c0-.34.28-.62.62-.62h26.74c.35 0 .62.28.62.62v19.74a.61.61 0 0 1-.61.63");
}

.g5d3hjacf {
  stop-color: var(--svg-color--4c4749, #4C4749);
}

.gcrmpdfop {
  stop-color: var(--svg-color--585352, #585352);
}

.gihkuibxq {
  stop-color: var(--svg-color--4a1d14, #4A1D14);
  stop-opacity: 0;
}

.gl9okfban {
  stop-color: var(--svg-color--634d4b, #634D4B);
  stop-opacity: 0;
}

.glo437b-m {
  stop-color: var(--svg-color--040002, #040002);
  stop-opacity: 0;
}

.god2ypupl {
  fill: var(--svg-color--4c3637, #4C3637);
  d: path("M20.807 11.76a1.077 1.077 0 1 0 0-2.152a1.077 1.077 0 0 0 0 2.153");
}

.gtfpj_bde {
  d: path("M18.157 9.608a.894.894 0 0 1 .862 1.13h-1.727a.897.897 0 0 1 .866-1.13");
}

.gugba3b_v {
  stop-color: var(--svg-color--33141c, #33141C);
  stop-opacity: 0;
}

.hfcweccdr {
  d: path("M20.807 11.76a1.077 1.077 0 1 0 0-2.152a1.077 1.077 0 0 0 0 2.153");
}

.hjtn79bml {
  stop-color: var(--svg-color--393134, #393134);
}

.hkormb2xp {
  stop-color: var(--svg-color--575455, #575455);
}

.ho3qhabae {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M19.033 28.574h1.922");
}

.hpdf2p89l {
  stop-color: var(--svg-color--25585f, #25585F);
}

.hx66smwtj {
  stop-color: var(--svg-color--4a4446, #4A4446);
}

.hyk2eqbsj {
  stop-color: var(--svg-color--2f1a1c, #2F1A1C);
}

.i4po81b8l {
  stroke: var(--svg-color--323233, #323233);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M17.913 8.306c.323-.078 1.126-.039 1.663.345");
}

.i669rlbzr {
  stop-color: var(--svg-color--2d151c, #2D151C);
  stop-opacity: 0;
}

.iicpv44yj {
  stop-color: var(--svg-color--563a39, #563A39);
  stop-opacity: 0;
}

.ik2h44jfq {
  stop-color: var(--svg-color--744036, #744036);
}

.j2p90_-bc {
  stop-color: var(--svg-color--4c4749, #4C4749);
  stop-opacity: 0;
}

.j67xqyuka {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M19.033 27.308h1.922");
}

.ja44woagt {
  stop-color: var(--svg-color--4f2737, #4F2737);
}

.jdm38tbtl {
  cx: 13.51px;
  cy: 9.99px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.198px;
}

.jids0zpwm {
  stop-color: var(--svg-color--59403d, #59403D);
}

.jij-d9bro {
  stop-color: var(--svg-color--d78248, #D78248);
  stop-opacity: 0;
}

.jk5udqbyz {
  stop-color: var(--svg-color--464444, #464444);
  stop-opacity: 0;
}

.jpk8o_7uj {
  stop-color: var(--svg-color--f69c5b, #F69C5B);
}

.k_snybcwj {
  stop-color: var(--svg-color--6d6670, #6D6670);
}

.k7y5k59sc {
  d: path("m19.332 16.009l1.382 2.983c.09.19-.05.41-.26.41l-.964-.266c-.422-.105-.436.277-.276.437l1.36 1.56c.26.26.36.65.23 1l-2.74 7.87V15.61z");
}

.kbl3igr5c {
  stop-color: var(--svg-color--040002, #040002);
}

.kfg1w5y8t {
  stop-color: var(--svg-color--6a5756, #6A5756);
  stop-opacity: 0;
}

.kiracnbim {
  stop-color: var(--svg-color--875955, #875955);
}

.kl3ja4pbq {
  stop-color: var(--svg-color--90645e, #90645E);
}

.kos78---c {
  stop-color: var(--svg-color--311620, #311620);
}

.kq1l1r1dg {
  d: path("M11.157 21.495c0-.384.311-.695.695-.695h9.812v1.39h-9.812a.695.695 0 0 1-.695-.695");
}

.krazlsbaw {
  stop-color: var(--svg-color--6f5048, #6F5048);
}

.l0xg-rbdf {
  stop-color: var(--svg-color--040101, #040101);
}

.l13euibzn {
  fill: var(--svg-color--35252b, #35252B);
  d: path("M11.292 11.76a1.076 1.076 0 1 0 0-2.152a1.076 1.076 0 0 0 0 2.153");
}

.l3j8m4byi {
  d: path("M20.807 12.297a1.613 1.613 0 1 0 0-3.225a1.613 1.613 0 0 0 0 3.225");
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.lgjudcrkd {
  stop-color: var(--svg-color--413733, #413733);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lj0sm1b7l {
  stop-color: var(--svg-color--efbe85, #EFBE85);
}

.ll4sw0vun {
  stop-color: var(--svg-color--24182d, #24182D);
}

.lxfbj-bzz {
  d: path("M10.889 4.683c.567-.6 1.64-.602 2.135-.512l.397 1.293c-.254-.039-.48.05-.67.235c-.449 1.264-1.993 1.96-2.71 2.15c-.148-1.495.11-2.385.848-3.166");
}

.lxlgm8z2u {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M12.942 28.574H11.02");
}

.m6mmhsf1n {
  stop-color: var(--svg-color--3f243b, #3F243B);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mc9t6_o6r {
  stop-color: var(--svg-color--381d1a, #381D1A);
}

.mg_6p4b7m {
  d: path("M16.014 18.673c-1.14 0-2.06-.92-2.06-2.06v-2.56c0-1.14.92-2.06 2.06-2.06s2.06.92 2.06 2.06v2.56a2.07 2.07 0 0 1-2.06 2.06");
}

.mg63gccek {
  stop-color: var(--svg-color--3d2928, #3D2928);
  stop-opacity: 0;
}

.mq6wd3bba {
  stop-color: var(--svg-color--433838, #433838);
  stop-opacity: 0;
}

.mxnnm4bur {
  stop-color: var(--svg-color--464444, #464444);
}

.n6qm1fbsv {
  fill: var(--svg-color--2a0219, #2A0219);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.568 13.213a.205.205 0 0 0-.248.043a.2.2 0 0 0-.021.248a1.986 1.986 0 0 0 3.34 0a.2.2 0 0 0-.021-.25a.205.205 0 0 0-.248-.042c-.405.216-.882.34-1.401.34a3 3 0 0 1-1.401-.34Z");
}

.n8mbjcbow {
  stop-color: var(--svg-color--875955, #875955);
  stop-opacity: 0;
}

.n8ysctycz {
  stop-color: var(--svg-color--2b151b, #2B151B);
}

.nd--cppfl {
  stop-color: var(--svg-color--585352, #585352);
  stop-opacity: 0;
}

.nfwti5bbx {
  stop-color: var(--svg-color--509245, #509245);
}

.nsqcbcbgj {
  d: path("M11.273 12.297a1.613 1.613 0 1 0 0-3.225a1.613 1.613 0 0 0 0 3.225");
}

.nxyog_b_l {
  d: path("M20.844 8.651h-3.47c-.3 0-.58.14-.77.37a.64.64 0 0 1-.51.24a.64.64 0 0 1-.51-.24c-.19-.23-.47-.37-.77-.37h-3.48c-.19 0-.34.15-.34.34v.22c0 .11.05.2.13.26c.04.03.07.08.07.13v1.1c0 1.05.85 1.91 1.91 1.91h.71c1.05 0 1.91-.85 1.91-1.91v-.61c.01-.2.17-.35.37-.35s.36.16.37.36v.6c0 1.05.85 1.91 1.91 1.91h.71c1.05 0 1.91-.85 1.91-1.91v-1.11c0-.05.02-.1.06-.13c.08-.06.13-.16.13-.26v-.21c0-.19-.15-.34-.34-.34m-5.46 1.95c0 .91-.74 1.65-1.65 1.65h-.55c-.91 0-1.65-.74-1.65-1.65v-.72c0-.49.39-.88.88-.88h2.08c.49 0 .89.39.89.88zm5.28 0c0 .91-.74 1.65-1.65 1.65h-.55c-.91 0-1.65-.74-1.65-1.65v-.72c0-.49.39-.88.88-.88h2.09c.49 0 .88.39.88.88z");
}

.o3k0towjz {
  stop-color: var(--svg-color--533632, #533632);
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

.ooqbvibma {
  d: path("M9.304 30.003V17.76a10.98 10.98 0 0 0-4.32 8.744v3.5z");
}

.oovee0bmi {
  d: path("M10.324 21.883v8.12h11.34v-9.19c0-.45-.36-.81-.81-.81h-8.64c-1.05-.01-1.89.84-1.89 1.88");
}

.oqnvn8b9n {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.573 9.335a1.4 1.4 0 0 0-1.358 1.061a.275.275 0 0 0 .268.342h2.236a.23.23 0 0 0 .228-.273a1.404 1.404 0 0 0-1.374-1.13");
}

.oraxh2cjj {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M13.071 4.128c.024.243.235 1.158.546 1.712");
}

.os93-qygj {
  stop-color: var(--svg-color--402857, #402857);
}

.ou3onybvn {
  stop-color: var(--svg-color--1f0d24, #1F0D24);
}

.ox51r5bse {
  stop-color: var(--svg-color--61332b, #61332B);
  stop-opacity: 0;
}

.p1jbbxbeq {
  d: path("M22.057 23.111c.55 0 1 .45 1 1v2.29h-2v-2.29c0-.55.44-1 1-1");
}

.paonnib9g {
  stop-color: var(--svg-color--474445, #474445);
}

.pgunbccgj {
  fill: var(--svg-color--331b25, #331B25);
  d: path("m15.575 10.46l-.685 1.704a.54.54 0 0 0 .522.701h.788c.37 0 .63-.355.522-.7l-.533-1.704c-.114-.378-.494-.378-.614 0");
}

.pj2ff5nxp {
  stop-color: var(--svg-color--2d181a, #2D181A);
  stop-opacity: 0;
}

.pk72hc60b {
  stop-color: var(--svg-color--381d1a, #381D1A);
  stop-opacity: 0;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pr1xqbb7a {
  d: path("M14.597 10.397c0-.289-.235-.482-.298-.54l-.29.28l.178.362z");
}

.qd6c5fnlv {
  stop-color: var(--svg-color--593e3c, #593E3C);
}

.qdx7hpd4p {
  cx: 13.51px;
  cy: 9.99px;
  rx: 0.39px;
  ry: 0.198px;
}

.qenr6bbwz {
  stop-color: var(--svg-color--2a1c1f, #2A1C1F);
}

.qfm16-9lg {
  fill: var(--svg-color--000, #000);
  d: path("M14.292 10.502a.51.51 0 0 0-.512-.512a.51.51 0 0 0-.455.747h.906a.5.5 0 0 0 .06-.235");
}

.qgdka6bnc {
  stop-color: var(--svg-color--563032, #563032);
}

.qm132ccsa {
  stop-color: var(--svg-color--655251, #655251);
  stop-opacity: 0;
}

.qna-_2b3m {
  stop-color: var(--svg-color--764747, #764747);
}

.qo_nu3b1v {
  stop-color: var(--svg-color--5d3841, #5D3841);
  stop-opacity: 0;
}

.qsvq6lbfl {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.365 9.335a1.4 1.4 0 0 1 1.358 1.061a.275.275 0 0 1-.268.342h-2.236a.23.23 0 0 1-.228-.273a1.4 1.4 0 0 1 1.374-1.13");
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qwp4ni-tf {
  stop-color: var(--svg-color--171418, #171418);
  stop-opacity: 0;
}

.r_v2kebuk {
  stop-color: var(--svg-color--181518, #181518);
  stop-opacity: 0;
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

.ri0kcvoxm {
  d: path("M13.353 25.373a.81.81 0 0 1-.302.667a.8.8 0 0 1 .302.637a.77.77 0 0 1-.302.636a.8.8 0 0 1 .302.637a.77.77 0 0 1-.302.637c.187.143.302.39.302.667c-.009.42-.32.75-.685.75H9.734c-.427 0-.774-.401-.774-.894v-3.604c0-.493.347-.893.774-.893h2.842c.475 0 .77.39.777.76");
}

.rkna2zbug {
  stop-color: var(--svg-color--61332b, #61332B);
}

.rmmi4abgs {
  stop-color: var(--svg-color--371d1f, #371D1F);
  stop-opacity: 0;
}

.rnwnxfbrn {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("m12.564 8.902l-.005.003a.269.269 0 0 1-.276-.461l.002-.001l.003-.002l.009-.005a2 2 0 0 1 .149-.077c.098-.047.24-.108.41-.162a2.8 2.8 0 0 1 1.332-.11a.269.269 0 1 1-.094.53c-.4-.07-.783-.001-1.074.092a3 3 0 0 0-.456.193");
}

.roasoobbm {
  d: path("M16.014 15.503c-6.07 0-11 4.92-11 11v3.5h21.99v-3.5c0-6.08-4.92-11-10.99-11");
}

.rqxi6yb_m {
  stop-color: var(--svg-color--7c5a5a, #7C5A5A);
}

.ryydajfhb {
  stop-color: var(--svg-color--613327, #613327);
}

.s-b_u7bzo {
  fill: var(--svg-color--000, #000);
  d: path("M17.645 10.502a.51.51 0 0 1 .512-.512a.51.51 0 0 1 .456.747h-.907a.46.46 0 0 1-.06-.235");
}

.s-cemd13j {
  stop-color: var(--svg-color--211415, #211415);
}

.s7wstub1z {
  d: path("M11.292 11.76a1.076 1.076 0 1 0 0-2.152a1.076 1.076 0 0 0 0 2.153");
}

.s9u3_wbrp {
  stop-color: var(--svg-color--402824, #402824);
}

.sdufqstmc {
  stop-color: var(--svg-color--2d181a, #2D181A);
}

.sihp1fb9k {
  stop-color: var(--svg-color--bc7b53, #BC7B53);
  stop-opacity: 0;
}

.silozpblh {
  stop-color: var(--svg-color--3b3638, #3B3638);
  stop-opacity: 0;
}

.sppliabuf {
  d: path("M22.684 30.003V17.76a10.98 10.98 0 0 1 4.32 8.744v3.5z");
}

.ssbc2ccsr {
  stop-color: var(--svg-color--1f0d24, #1F0D24);
  stop-opacity: 0;
}

.t2sf3o33q {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M19.033 26.043h1.922");
}

.t5djkhb4t {
  stop-color: var(--svg-color--655251, #655251);
}

.te34a41ur {
  d: path("M10.87 9.419h.013l-.01-.266l-.01-.307c.02-.95.575-1.319.811-1.442q.024-.008.052-.02q.026-.012.05-.02a2.3 2.3 0 0 0 1.193-1.238l.082-.194a.264.264 0 0 1 .463-.051a3.87 3.87 0 0 0 3.196 1.677h3.227c.18 0 1.085.087 1.138 1.335l-.119 3.08c-.123 2.808-2.316 4.694-4.994 4.694s-4.87-1.886-4.994-4.694z");
}

.tiwgx3b7k {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M12.942 26.043H11.02");
}

.tn667-bso {
  d: path("m15.586 10.322l-.533 1.704a.54.54 0 0 0 .522.7h.788c.37 0 .63-.355.522-.7l-.533-1.704c-.114-.377-.647-.377-.766 0");
}

.tr7czpf3k {
  stop-color: var(--svg-color--413733, #413733);
  stop-opacity: 0;
}

.u1egy7b7t {
  stop-color: var(--svg-color--e8ac81, #E8AC81);
}

.u2v5p9bdu {
  d: path("M18.955 10.385a.84.84 0 0 0-.232-.464l-.261.286l.118.228z");
}

.u4cr62b2o {
  d: path("M29.004 23.993H3.014V5.003l-.92-.68c-.05.09-.08.2-.08.3v19.74c0 .35.28.62.62.62h26.74c.24 0 .44-.13.55-.33z");
}

.ub4gkwbqs {
  stop-color: var(--svg-color--764440, #764440);
}

.ujr2p9fja {
  d: path("M18.064 16.823h-4.11v13.18h4.11z");
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

.v2f8j5bnu {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M3.228 4.397h26.213a.1.1 0 0 1 .1.1v19.585");
}

.v2xpqhbrh {
  stop-color: var(--svg-color--402a29, #402A29);
}

.v50lh8z4g {
  fill: var(--svg-color--4b4648, #4B4648);
  d: path("m18.38 6.494l-1.428.263a.69.69 0 1 1-.125-1.368h2.345c1.388 0 1.847 1.398 1.903 1.876a3.15 3.15 0 0 0-2.695-.77");
}

.vblumvbgz {
  fill-rule: evenodd;
  d: path("M12.418 30.003v-8.406h-2.094v8.406z");
}

.vfy6rbc0u {
  stroke: var(--svg-color--323233, #323233);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M14.113 8.306c-.323-.078-1.126-.039-1.663.345");
}

.vi3ro6t_p {
  fill: var(--svg-color--2f2428, #2F2428);
  d: path("M15.364 2.876c-1.135-.25-2.154.882-2.272 1.302c1.054 3.553 3.721 3.358 6.354 3.066c1.576-.175 1.747.543 1.881.89c0-3.941-3.351-4.681-5.934-5.251z");
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

.wb78_hxsc {
  stop-color: var(--svg-color--6a5956, #6A5956);
}

.wfc059byj {
  stop-color: var(--svg-color--25585f, #25585F);
  stop-opacity: 0;
}

.wgpm0ibqw {
  stop-color: var(--svg-color--43272a, #43272A);
  stop-opacity: 0;
}

.wn11gcx8f {
  stop-color: var(--svg-color--f1b58b, #F1B58B);
}

.wq1w-qb8s {
  stop-color: var(--svg-color--311620, #311620);
  stop-opacity: 0;
}

.x_sue_b_g {
  stop-color: var(--svg-color--634d4b, #634D4B);
}

.x16kbobeb {
  stop-color: var(--svg-color--4f2737, #4F2737);
  stop-opacity: 0;
}

.x7h3p2bdy {
  stop-color: var(--svg-color--533632, #533632);
  stop-opacity: 0;
}

.xdn388byj {
  stop-color: var(--svg-color--171418, #171418);
}

.xfmbn4_bb {
  stop-color: var(--svg-color--3a1f30, #3A1F30);
  stop-opacity: 0;
}

.xkhh7vb2n {
  stop-color: var(--svg-color--371e27, #371E27);
  stop-opacity: 0;
}

.xtl7t4edr {
  stop-color: var(--svg-color--d18f7b, #D18F7B);
}

.xuyenabum {
  stop-color: var(--svg-color--371d1f, #371D1F);
}

.y1ij6ubnw {
  stop-color: var(--svg-color--ffd59c, #FFD59C);
}

.y1kgfac6n {
  stop-color: var(--svg-color--8a5d57, #8A5D57);
  stop-opacity: 0;
}

.ybvm9tprh {
  stop-color: var(--svg-color--594d4d, #594D4D);
}

.ybzr6jbff {
  stop-color: var(--svg-color--90645e, #90645E);
  stop-opacity: 0;
}

.ympidy8fx {
  fill: var(--svg-color--272528, #272528);
  d: path("M14.824 10.114c-.266-.468-.67-.838-1.54-.838a1.66 1.66 0 0 0-1.075.37c-.27.218-.234.496-.025.6l.557.319c.653-.211 1.376-.24 2.083-.451");
}

.yt9sv1b9n {
  stop-color: var(--svg-color--2d151c, #2D151C);
}

.yv4uycbmh {
  stop-color: var(--svg-color--43272a, #43272A);
}

.yvbzu_iwu {
  fill: var(--svg-color--4a302d, #4A302D);
  d: path("m15.586 10.322l-.533 1.704a.54.54 0 0 0 .522.7h.788c.37 0 .63-.355.522-.7l-.533-1.704c-.114-.377-.647-.377-.766 0");
}

.yvo_l_bkn {
  stop-color: var(--svg-color--9a6d66, #9A6D66);
  stop-opacity: 0;
}

.yxwqgvbem {
  stop-color: var(--svg-color--594d4d, #594D4D);
  stop-opacity: 0;
}

.z_wfxjr5n {
  stop-color: var(--svg-color--392526, #392526);
}

.z66p5h_5k {
  stop-color: var(--svg-color--1a1316, #1A1316);
}

.zagqne2ck {
  stop-color: var(--svg-color--2f1d1a, #2F1D1A);
}

.zbexf6jod {
  stop-color: var(--svg-color--564848, #564848);
  stop-opacity: 0;
}

.zc0i69b4g {
  fill: var(--svg-color--20171a, #20171A);
  d: path("M10.889 4.683c.567-.6 1.64-.602 2.135-.512l.397 1.293c-.254-.039-.48.05-.67.235c-.449 1.264-1.993 1.96-2.71 2.15c-.148-1.495.11-2.385.848-3.166");
}

.zlcjw7bgf {
  stop-color: var(--svg-color--61342d, #61342D);
}

.zobbewbqd {
  stop-color: var(--svg-color--52396b, #52396B);
}

.zq99eh__o {
  d: path("m12.688 16.005l-1.384 2.987c-.09.19.05.41.26.41l.963-.266c.422-.105.437.277.277.437l-1.36 1.56c-.26.26-.36.65-.23 1l2.74 7.87v-14.4z");
}

.zs64g5eig {
  stop-color: var(--svg-color--623d44, #623D44);
}

.zz4mcgrzh {
  stop-color: var(--svg-color--59403d, #59403D);
  stop-opacity: 0;
}

</style>
