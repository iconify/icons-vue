<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><rect fill="url(#iGKrojZ)" transform="rotate(26.961 19.37 13.47)" class="b1ysgbbus"/><g filter="url(#iVvicGb)"><path class="snq5xhi6c"/></g><circle fill="url(#igd0DZc)" class="idljld4zp"/><circle fill="url(#igS1Qbd)" class="idljld4zp"/><circle fill="url(#iz32gEQ)" class="idljld4zp"/><circle fill="url(#ijFkTLU)" class="idljld4zp"/><g filter="url(#iiCPxyc)"><path fill="url(#i0yZFVd)" class="sepv3nkwr"/></g><path fill="url(#ih4xptb)" class="b1yazzwzl"/><path fill="url(#iN28qhb)" class="b1yazzwzl"/><path fill="url(#iCUMoEc)" class="of70meq1k"/><path fill="url(#idv3syc)" class="of70meq1k"/><g filter="url(#i2lGNkb)"><path fill="url(#iQfxCxb)" class="ga-j-qbpm"/><path fill="url(#ihvu0fe)" class="ga-j-qbpm"/><path fill="url(#irTWmse)" class="ga-j-qbpm"/></g><g filter="url(#iPcAGUc)"><path fill="url(#ihTfWPe)" class="vuejbwbij"/><path fill="url(#ieA83vb)" class="vuejbwbij"/></g><path fill="url(#iA0XN4g)" class="qexsyge6i"/><path fill="url(#is6z78C)" class="qexsyge6i"/><path fill="url(#iXmTP2b)" class="u072kwb9c"/><path fill="url(#iwnOGxb)" class="u072kwb9c"/><path fill="url(#imDgmed)" class="u072kwb9c"/><path fill="url(#imHw3yb)" class="u072kwb9c"/><path class="thhwo06ax"/><path fill="url(#iB3O36Y)" class="ginv3dbis"/><path fill="url(#i2oUhlc)" class="ginv3dbis"/><path fill="url(#iLGf6rd)" class="ginv3dbis"/><g filter="url(#iLT5Tid)"><path class="sa73rem9k"/><path fill="url(#ipRtVxG)" class="j88k0lalk"/><path fill="url(#ix89MNd)" class="j88k0lalk"/><path fill="url(#iXt88Ec)" class="j88k0lalk"/></g><g filter="url(#i4l7ZsZ)"><path fill="url(#i8Nc0jI)" class="dc-w_nb2z"/><path fill="url(#iBwCx9d)" class="dc-w_nb2z"/></g><g filter="url(#ifrMYwd)"><path fill="url(#i4iFAyd)" class="xcwnd6bms"/><path fill="url(#iOQGJ1x)" class="xcwnd6bms"/></g><g filter="url(#ilxdgoe)"><path fill="url(#if2UIRn)" clip-rule="evenodd" class="y_4pajl7d"/></g><path class="stz6elb6u"/><path fill="url(#iCqAaCc)" class="eikeckbha"/><path fill="url(#iTEnVmd)" class="eikeckbha"/><path clip-rule="evenodd" class="qc5t8db-b"/><path fill="url(#i6NSaLc)" clip-rule="evenodd" class="x99s9tbej"/><path clip-rule="evenodd" class="x5036tbci"/><path fill="url(#iegrDeg)" clip-rule="evenodd" class="y8eztfbsi"/><path clip-rule="evenodd" class="h8mf77buf"/><path fill="url(#iI5xoGs)" clip-rule="evenodd" class="t7cma5ywk"/><path clip-rule="evenodd" class="n89_5nb9r"/><path fill="url(#iiMj71d)" clip-rule="evenodd" class="viuz5dbki"/><path fill="url(#i0vUcqd)" clip-rule="evenodd" class="s4af_bb4s"/><g filter="url(#itnVjlc)"><path fill="url(#ig7EJld)" class="p3ru7q3ze"/><path fill="url(#i4TzDAb)" class="p3ru7q3ze"/></g><path fill="url(#iK2UlDc)" class="p3ru7q3ze"/><path fill="url(#iGUHBdd)" clip-rule="evenodd" class="y_4pajl7d"/><g filter="url(#iKQucmc)"><circle fill="url(#i9uUZMw)" class="ak2kuya8m"/></g><circle fill="url(#iafq3Ud)" class="ak2kuya8m"/><g filter="url(#iPBXUFc)"><circle fill="url(#iAjkNEM)" class="gtdfzvb-d"/></g><g filter="url(#isqEbFb)"><circle fill="url(#iot4cHB)" class="uk_8-tw2z"/><circle fill="url(#iqWFugc)" class="uk_8-tw2z"/></g><g filter="url(#ikE92Lm)"><circle class="dwmdrq4-i"/><circle fill="url(#i9V5Sqd)" class="xqqpogm7y"/><circle fill="url(#iy5BWPd)" class="xqqpogm7y"/></g><g filter="url(#iRIO63d)"><path fill="url(#iGDhgxd)" class="f8nqagboh"/><path fill="url(#iWhjIgd)" class="f8nqagboh"/><path fill="url(#ikYYx4c)" class="f8nqagboh"/></g><path fill="url(#iD3Lnsd)" class="ivvzkzyvu"/><path fill="url(#i4458nd)" class="ivvzkzyvu"/><path fill="url(#iu2sqPc)" class="ivvzkzyvu"/><g filter="url(#i1fb6Ib)"><path fill="url(#iZdgi3b)" class="qgy1d6uwa"/></g><g filter="url(#iK1JE5d)"><path class="xryjwwrmy"/><path fill="url(#irxdI1B)" class="epsd93bnv"/><path fill="url(#ir7Sccc)" class="epsd93bnv"/><path fill="url(#ilxa8Uc)" class="epsd93bnv"/><path fill="url(#iu1oh4c)" class="epsd93bnv"/></g><g filter="url(#i6ses6W)"><path class="r8ef-k39g"/></g><g filter="url(#iq83Ivb)"><path class="miwjp6b7g"/><path fill="url(#i1tQzLc)" class="xyeix3b7z"/><path fill="url(#iMaJkbb)" class="xyeix3b7z"/><path fill="url(#iIokemN)" class="xyeix3b7z"/><path fill="url(#idrpZle)" class="xyeix3b7z"/></g><path stroke="url(#iNK680d)" class="ay5-f4_3t"/><g filter="url(#iCRIfrd)"><path class="yrp6iebks"/><path fill="url(#iHG1e6b)" class="ue9_nibqv"/></g><g filter="url(#igKXI7Q)"><path class="s5tp33mbf"/><path fill="url(#iZEvdZb)" class="yo43zmb5m"/></g><path class="yz1zcsbvd"/><path fill="url(#iOVnwpb)" class="hq2xmibfx"/><path class="ve-itr7ex"/><g filter="url(#iofaCQb)"><path class="qysvg004b"/><path fill="url(#i4fHRgb)" class="e4tqe_ftq"/></g><g filter="url(#igt5mhe)"><path fill="url(#i4rcH1c)" class="hx2_avbkm"/></g><path class="m_hc3t5pq"/><path fill="url(#iz7UZze)" class="m16zjqbqa"/><path class="b_tb2tvui"/><g filter="url(#iUSzuvb)"><path fill="url(#iGkKLme)" class="crfmvdbeh"/></g><g filter="url(#isqxfSd)"><ellipse transform="rotate(-27.914 11.744 5.653)" class="h9h99sbjz"/><ellipse fill="url(#iE8VQYd)" transform="rotate(-27.914 11.744 5.653)" class="f0cdn8__t"/></g><g filter="url(#iHKEZfd)"><path stroke="url(#iu6pJKe)" class="e5edx9bib"/></g><g filter="url(#ixfIYTd)"><path stroke="url(#iQggcue)" class="x-3oyg2db"/></g><g filter="url(#irvYCmA)"><path stroke="url(#ixwRf1c)" class="l8siv2hwp"/></g><path fill="url(#iUDE0ye)" class="dmwymqbmp"/><path fill="url(#ipkOA9c)" class="dmwymqbmp"/><path fill="url(#iy9n8Je)" class="dmwymqbmp"/><path fill="url(#isLzyyb)" class="dmwymqbmp"/><g filter="url(#ivOdQ0b)"><path class="rudj2xgsn"/></g><g filter="url(#icB2EPd)"><path class="j9f4fjdso"/><path fill="url(#ikDRoLc)" class="hpxf53bap"/></g><defs><radialGradient id="iGKrojZ" cx="0" cy="0" r="1" gradientTransform="matrix(0 .55552 -.42115 0 19.7 14.025)" gradientUnits="userSpaceOnUse"><stop offset=".464" class="cu-ecjbbc"/><stop offset="1" class="qb2q8bclu"/></radialGradient><radialGradient id="igS1Qbd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.65625 1.65625 -1.54687 -1.54687 6.337 18.361)" gradientUnits="userSpaceOnUse"><stop class="mdx4akbxm"/><stop offset="1" class="t5qac2c1p"/></radialGradient><radialGradient id="iz32gEQ" cx="0" cy="0" r="1" gradientTransform="rotate(-174.823 3.309 9.543)scale(3.29739 3.69421)" gradientUnits="userSpaceOnUse"><stop offset=".439" class="mneu5xbew"/><stop offset=".947" class="fqax45bnt"/></radialGradient><radialGradient id="ijFkTLU" cx="0" cy="0" r="1" gradientTransform="matrix(-.4375 3.98763 -3.995 -.4383 5.462 18.08)" gradientUnits="userSpaceOnUse"><stop offset=".682" class="w7i-07blq"/><stop offset="1" class="o27_2ebdq"/></radialGradient><radialGradient id="i0yZFVd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.34374 .78906 -.8071 -1.37445 6.282 18.838)" gradientUnits="userSpaceOnUse"><stop offset=".198" class="rx_o_e39d"/><stop offset="1" class="ancrqsbmw"/></radialGradient><radialGradient id="ih4xptb" cx="0" cy="0" r="1" gradientTransform="matrix(.93752 -4.625 2.23622 .4533 11.555 25.112)" gradientUnits="userSpaceOnUse"><stop offset=".131" class="illubsb_v"/><stop offset="1" class="guxv2rb-g"/></radialGradient><radialGradient id="iN28qhb" cx="0" cy="0" r="1" gradientTransform="matrix(3.8125 -.34375 .46441 5.15075 9.868 22.705)" gradientUnits="userSpaceOnUse"><stop offset=".617" class="xs_h82bcz"/><stop offset="1" class="q7m_lo14i"/></radialGradient><radialGradient id="iQfxCxb" cx="0" cy="0" r="1" gradientTransform="matrix(1.34136 3.28833 -5.45057 2.22337 6.741 26.6)" gradientUnits="userSpaceOnUse"><stop class="vhhvj2t-s"/><stop offset="1" class="so34edl-m"/></radialGradient><radialGradient id="ihvu0fe" cx="0" cy="0" r="1" gradientTransform="matrix(-.30078 .14845 -.19933 -.40386 10.865 26.557)" gradientUnits="userSpaceOnUse"><stop class="wg6epmg7n"/><stop offset="1" class="gc9u7lbfl"/></radialGradient><radialGradient id="irTWmse" cx="0" cy="0" r="1" gradientTransform="rotate(52.306 -21.848 22.547)scale(.76023 .57466)" gradientUnits="userSpaceOnUse"><stop class="wg6epmg7n"/><stop offset="1" class="gc9u7lbfl"/></radialGradient><radialGradient id="iA0XN4g" cx="0" cy="0" r="1" gradientTransform="rotate(153.3 8.343 12.624)scale(2.99172 1.46479)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="akiqkcbyd"/><stop offset="1" class="pydwqlfbr"/></radialGradient><radialGradient id="iXmTP2b" cx="0" cy="0" r="1" gradientTransform="rotate(153.02 9.532 12.326)scale(1.92866 1.03496)" gradientUnits="userSpaceOnUse"><stop offset=".154" class="pa6b3tb0c"/><stop offset="1" class="sdljx8amv"/></radialGradient><radialGradient id="imDgmed" cx="0" cy="0" r="1" gradientTransform="matrix(-1.21874 .66407 -.44091 -.8092 23.174 18.11)" gradientUnits="userSpaceOnUse"><stop offset=".342" class="don2uv-3m"/><stop offset="1" class="gpus1rbiy"/></radialGradient><radialGradient id="imHw3yb" cx="0" cy="0" r="1" gradientTransform="rotate(112.416 5.88 17.726)scale(2.70434 1.05462)" gradientUnits="userSpaceOnUse"><stop offset=".566" class="n30gi-53g"/><stop offset="1" class="tt7xwipig"/></radialGradient><radialGradient id="iB3O36Y" cx="0" cy="0" r="1" gradientTransform="matrix(-2.5 2.10937 -4.01056 -4.75325 19.634 19.83)" gradientUnits="userSpaceOnUse"><stop offset=".379" class="o7o4d8pps"/><stop offset=".92" class="j1n_ptbit"/></radialGradient><radialGradient id="i2oUhlc" cx="0" cy="0" r="1" gradientTransform="matrix(1.92188 1.03124 -1.60806 2.99689 16.696 19.143)" gradientUnits="userSpaceOnUse"><stop offset=".429" class="eaj548bgj"/><stop offset="1" class="cxprecb8d"/></radialGradient><radialGradient id="iLGf6rd" cx="0" cy="0" r="1" gradientTransform="matrix(-.87818 .60937 -1.28653 -1.85405 19.918 18.752)" gradientUnits="userSpaceOnUse"><stop offset=".183" class="bnpz8rbzn"/><stop offset="1" class="awgn1c4se"/></radialGradient><radialGradient id="ipRtVxG" cx="0" cy="0" r="1" gradientTransform="matrix(.28125 -3.875 4.85233 .35219 16.493 20.924)" gradientUnits="userSpaceOnUse"><stop class="c-qpqdbmc"/><stop offset="1" class="cy6exab_x"/></radialGradient><radialGradient id="ix89MNd" cx="0" cy="0" r="1" gradientTransform="rotate(-75.406 21.679 2.265)scale(3.74586 2.0917)" gradientUnits="userSpaceOnUse"><stop class="sn3dy7bnn"/><stop offset="1" class="qu4z4jkud"/></radialGradient><radialGradient id="iXt88Ec" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.89062 -2.42602 0 16.93 16.846)" gradientUnits="userSpaceOnUse"><stop offset=".301" class="u_3e452pz"/><stop offset="1" class="t5f4fqbxv"/></radialGradient><radialGradient id="i8Nc0jI" cx="0" cy="0" r="1" gradientTransform="rotate(159.963 11.46 11.54)scale(2.82739 3.3966)" gradientUnits="userSpaceOnUse"><stop offset=".207" class="xu1e5_bcz"/><stop offset="1" class="jixz69llq"/></radialGradient><radialGradient id="if2UIRn" cx="0" cy="0" r="1" gradientTransform="matrix(3.40624 -1.28127 .66322 1.76315 6.712 13.924)" gradientUnits="userSpaceOnUse"><stop class="diezlkbrv"/><stop offset="1" class="qrb0sjbdn"/></radialGradient><radialGradient id="iCqAaCc" cx="0" cy="0" r="1" gradientTransform="matrix(2.34375 1.71875 -2.5451 3.4706 12.493 8.049)" gradientUnits="userSpaceOnUse"><stop offset=".172" class="mf5e09ark"/><stop offset="1" class="kqsf2kvhx"/></radialGradient><radialGradient id="iTEnVmd" cx="0" cy="0" r="1" gradientTransform="matrix(3.34375 -1 4.7268 15.80522 13.295 9.934)" gradientUnits="userSpaceOnUse"><stop offset=".67" class="lakgv5bqc"/><stop offset=".945" class="p3cy4lbfc"/></radialGradient><radialGradient id="i6NSaLc" cx="0" cy="0" r="1" gradientTransform="rotate(154.153 1.22 7.576)scale(1.51176 .82196)" gradientUnits="userSpaceOnUse"><stop offset=".361" class="qpbv0c39t"/><stop offset="1" class="xjnuavuoc"/></radialGradient><radialGradient id="iegrDeg" cx="0" cy="0" r="1" gradientTransform="rotate(149.949 .803 7.929)scale(1.74533 1.04837)" gradientUnits="userSpaceOnUse"><stop offset=".361" class="qpbv0c39t"/><stop offset="1" class="xjnuavuoc"/></radialGradient><radialGradient id="iI5xoGs" cx="0" cy="0" r="1" gradientTransform="matrix(-1.49195 .93111 -.57955 -.92863 5.337 14.93)" gradientUnits="userSpaceOnUse"><stop offset=".361" class="qpbv0c39t"/><stop offset="1" class="xjnuavuoc"/></radialGradient><radialGradient id="iiMj71d" cx="0" cy="0" r="1" gradientTransform="rotate(149.08 .7 8.37)scale(1.53562 .93807)" gradientUnits="userSpaceOnUse"><stop offset=".361" class="qpbv0c39t"/><stop offset="1" class="xjnuavuoc"/></radialGradient><radialGradient id="i0vUcqd" cx="0" cy="0" r="1" gradientTransform="rotate(129.668 -.12 8.922)scale(1.13713 .21244)" gradientUnits="userSpaceOnUse"><stop class="nm4xmabvr"/><stop offset="1" class="b4mlr_y9s"/></radialGradient><radialGradient id="ig7EJld" cx="0" cy="0" r="1" gradientTransform="matrix(-3.12494 8.57033 -5.82186 -2.12278 16.9 7.479)" gradientUnits="userSpaceOnUse"><stop offset=".205" class="uqxno_b8g"/><stop offset=".81" class="d4a71bwtp"/></radialGradient><radialGradient id="i4TzDAb" cx="0" cy="0" r="1" gradientTransform="rotate(-104.504 15.358 1.219)scale(8.36833 2.71135)" gradientUnits="userSpaceOnUse"><stop class="g_v4sglua"/><stop offset="1" class="o67susxgp"/></radialGradient><radialGradient id="iK2UlDc" cx="0" cy="0" r="1" gradientTransform="rotate(112.005 5.271 8.996)scale(4.08677 4.31955)" gradientUnits="userSpaceOnUse"><stop offset=".108" class="ip3ktqbqy"/><stop offset="1" class="whspc9bgn"/></radialGradient><radialGradient id="iGUHBdd" cx="0" cy="0" r="1" gradientTransform="matrix(2.53394 .29688 -.19207 1.63939 5.897 13.22)" gradientUnits="userSpaceOnUse"><stop offset=".303" class="wloocxb2w"/><stop offset="1" class="g8dpdlbxs"/></radialGradient><radialGradient id="i9uUZMw" cx="0" cy="0" r="1" gradientTransform="matrix(.79446 0 0 1.39031 9.95 6.005)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="n91c-gs8j"/><stop offset="1" class="qo7u-3bcf"/></radialGradient><radialGradient id="iafq3Ud" cx="0" cy="0" r="1" gradientTransform="rotate(-124.98 7.114 .593)scale(.75004)" gradientUnits="userSpaceOnUse"><stop offset=".34" class="ev4-2pfvs"/><stop offset="1" class="w_j-6pbpp"/></radialGradient><radialGradient id="iqWFugc" cx="0" cy="0" r="1" gradientTransform="matrix(.37426 -.27252 .31105 .42717 15.182 5.886)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="cu-ecjbbc"/><stop offset="1" class="a1ftncccj"/></radialGradient><radialGradient id="i9V5Sqd" cx="0" cy="0" r="1" gradientTransform="rotate(-61.467 12.86 -9.421)scale(.77838 .45559)" gradientUnits="userSpaceOnUse"><stop offset=".755" class="d66ufbbtl"/><stop offset=".916" class="f7hwkw-sq"/></radialGradient><radialGradient id="iy5BWPd" cx="0" cy="0" r="1" gradientTransform="matrix(.11738 .1162 -.14979 .15132 15.014 6.006)" gradientUnits="userSpaceOnUse"><stop class="suj-pjbhk"/><stop offset="1" class="dg9o8ubcl"/></radialGradient><radialGradient id="iWhjIgd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.59174 .7283 0 13.918 5.43)" gradientUnits="userSpaceOnUse"><stop class="e6v6vrbif"/><stop offset="1" class="qmnjff_ag"/></radialGradient><radialGradient id="ikYYx4c" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.62208 .77362 0 11.855 5.49)" gradientUnits="userSpaceOnUse"><stop class="c02-eqbxv"/><stop offset="1" class="mmmkqcbgq"/></radialGradient><radialGradient id="iu2sqPc" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.77044 -4.67322 0 12.798 5.311)" gradientUnits="userSpaceOnUse"><stop offset=".608" class="dcym8repk"/><stop offset=".884" class="fkee40m0y"/><stop offset="1" class="an_-aznlj"/></radialGradient><radialGradient id="irxdI1B" cx="0" cy="0" r="1" gradientTransform="matrix(.36119 -1.33851 .49636 .13394 14.823 4.146)" gradientUnits="userSpaceOnUse"><stop class="ki2rd4v4k"/><stop offset="1" class="tp9jx5j2y"/></radialGradient><radialGradient id="ir7Sccc" cx="0" cy="0" r="1" gradientTransform="matrix(1.73157 .15935 -.08568 .93105 14.08 3.35)" gradientUnits="userSpaceOnUse"><stop offset=".392" class="je_aabb8l"/><stop offset="1" class="ivhsfvmdg"/></radialGradient><radialGradient id="ilxa8Uc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .7602 -1.17732 0 12.856 2.112)" gradientUnits="userSpaceOnUse"><stop class="n7o-m0b5s"/><stop offset="1" class="xp-9f0bqu"/></radialGradient><radialGradient id="iu1oh4c" cx="0" cy="0" r="1" gradientTransform="matrix(1.39163 -1.01982 1.59772 2.18022 9.937 5.198)" gradientUnits="userSpaceOnUse"><stop class="ux7-g74jy"/><stop offset="1" class="dd8hfetks"/></radialGradient><radialGradient id="idrpZle" cx="0" cy="0" r="1" gradientTransform="matrix(0 .08914 -.28639 0 13.004 6.733)" gradientUnits="userSpaceOnUse"><stop class="mifq-tdon"/><stop offset="1" class="n-ko-_w7d"/></radialGradient><radialGradient id="iHG1e6b" cx="0" cy="0" r="1" gradientTransform="rotate(-80.201 9.986 -5.76)scale(.27715 .81995)" gradientUnits="userSpaceOnUse"><stop class="fr4wpbo2m"/><stop offset="1" class="xo-sv8bhm"/></radialGradient><radialGradient id="iZEvdZb" cx="0" cy="0" r="1" gradientTransform="rotate(-80.2 8.821 -4.375)scale(.27715 .81999)" gradientUnits="userSpaceOnUse"><stop class="fr4wpbo2m"/><stop offset="1" class="xo-sv8bhm"/></radialGradient><radialGradient id="iOVnwpb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .36721 -.5841 0 13.842 5.697)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="i4fHRgb" cx="0" cy="0" r="1" gradientTransform="matrix(-.10497 -.13527 .18623 -.14452 13.74 5.735)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iz7UZze" cx="0" cy="0" r="1" gradientTransform="matrix(0 .36723 -.58413 0 11.867 5.697)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iE8VQYd" cx="0" cy="0" r="1" gradientTransform="matrix(-.0035 -.22363 .26881 -.0042 11.738 5.796)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iUDE0ye" cx="0" cy="0" r="1" gradientTransform="matrix(-3.75 0 0 -3.07783 14.443 3.733)" gradientUnits="userSpaceOnUse"><stop offset=".217" class="e3m1knbgu"/><stop offset="1" class="o-iz-vbwp"/></radialGradient><radialGradient id="isLzyyb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.16797 0 0 -.11719 15.271 3.202)" gradientUnits="userSpaceOnUse"><stop offset=".083" class="jy7vazb8a"/><stop offset="1" class="oha5hfbwc"/></radialGradient><radialGradient id="ikDRoLc" cx="0" cy="0" r="1" gradientTransform="rotate(-50.981 21.243 -14.137)scale(2.33289 4.31503)" gradientUnits="userSpaceOnUse"><stop offset=".239" class="ks47q0bjb"/><stop offset="1" class="ep0hblblj"/></radialGradient><filter id="iVvicGb" width="7.486" height="8.65" x="14.87" y="7.274" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.584314 0 0 0 0 0.341176 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23231"/></filter><filter id="iiCPxyc" width="5.439" height="5.49" x="2.462" y="16.577" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.05"/><feGaussianBlur stdDeviation=".025"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.298039 0 0 0 0 0.223529 0 0 0 0 0.266667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23231"/></filter><filter id="i2lGNkb" width="6.264" height="4.296" x="4.74" y="25.692" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.27451 0 0 0 0 0.505882 0 0 0 0 0.733333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23231"/></filter><filter id="iPcAGUc" width="5.105" height="3.176" x="4.74" y="26.713" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.705882 0 0 0 0 0.564706 0 0 0 0 0.831373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23231"/></filter><filter id="iLT5Tid" width="7.339" height="5.547" x="11.424" y="16.846" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.25 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23231"/></filter><filter id="i4l7ZsZ" width="5.437" height="5.553" x="22.676" y="16.226" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.356863 0 0 0 0 0.4 0 0 0 0 0.858824 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23231"/></filter><filter id="ifrMYwd" width="2.689" height="5.353" x="25.224" y="16.326" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.94902 0 0 0 0 0.92549 0 0 0 0 0.972549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23231"/></filter><filter id="ilxdgoe" width="8.098" height="6.294" x="5.657" y="8.504" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy="-.4"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.639216 0 0 0 0 0.419608 0 0 0 0 0.439216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23231"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.498039 0 0 0 0 0.247059 0 0 0 0 0.298039 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23231" result="effect2_innerShadow_3987_23231"/></filter><filter id="itnVjlc" width="7.636" height="9.986" x="11.582" y="7.079" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.4"/><feGaussianBlur stdDeviation="1.25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.227451 0 0 0 0 0.34902 0 0 0 0 0.643137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23231"/></filter><filter id="iKQucmc" width="1.712" height="1.512" x="9.951" y="5.25" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.619608 0 0 0 0 0.470588 0 0 0 0 0.407843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23231"/></filter><filter id="iPBXUFc" width="1.901" height="1.901" x="9.756" y="5.055" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23231" stdDeviation=".25"/></filter><filter id="isqEbFb" width="1.762" height="1.762" x="14.258" y="5" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.584314 0 0 0 0 0.368627 0 0 0 0 0.470588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23231"/></filter><filter id="ikE92Lm" width="1.901" height="1.901" x="14.063" y="5.055" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23231" stdDeviation=".25"/></filter><filter id="iRIO63d" width="4.696" height="5.595" x="10.521" y="3.459" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.305882 0 0 0 0 0.2 0 0 0 0 0.172549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23231"/></filter><filter id="i1fb6Ib" width="3.922" height="3.388" x="11.933" y="2.459" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23231" stdDeviation=".5"/></filter><filter id="iK1JE5d" width="5.705" height="3.741" x="10.004" y="2.012" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.207843 0 0 0 0 0.109804 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23231"/></filter><filter id="i6ses6W" width="2.297" height="2.714" x="11.6" y="5.072" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23231" stdDeviation=".375"/></filter><filter id="iq83Ivb" width="1.05" height="1.414" x="12.331" y="5.648" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23231" stdDeviation=".05"/></filter><filter id="iCRIfrd" width="1.486" height="1.067" x="13.391" y="4.135" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.156863 0 0 0 0 0.152941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23231"/></filter><filter id="igKXI7Q" width="1.486" height="1.067" x="11.061" y="4.135" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.156863 0 0 0 0 0.152941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23231"/></filter><filter id="iofaCQb" width=".466" height=".425" x="13.456" y="5.443" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23231" stdDeviation=".05"/></filter><filter id="igt5mhe" width=".622" height=".632" x="13.781" y="5.422" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23231" stdDeviation=".1"/></filter><filter id="iUSzuvb" width=".665" height=".69" x="11.77" y="5.393" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23231" stdDeviation=".1"/></filter><filter id="isqxfSd" width=".523" height=".428" x="11.483" y="5.439" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23231" stdDeviation=".05"/></filter><filter id="iHKEZfd" width="1.337" height=".695" x="13.358" y="4.444" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23231" stdDeviation=".1"/></filter><filter id="ixfIYTd" width="1.372" height=".721" x="10.995" y="4.472" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23231" stdDeviation=".1"/></filter><filter id="irvYCmA" width=".867" height="1.438" x="10.312" y="3.452" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23231" stdDeviation=".125"/></filter><filter id="ivOdQ0b" width="2.625" height="5.367" x="19.763" y="9.301" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23231" stdDeviation=".25"/></filter><filter id="icB2EPd" width="3.404" height="3.248" x="18.396" y="8.299" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.792157 0 0 0 0 0.760784 0 0 0 0 0.756863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23231"/></filter><linearGradient id="igd0DZc" x1="4.743" x2="6.868" y1="18.986" y2="21.111" gradientUnits="userSpaceOnUse"><stop class="v616eizae"/><stop offset=".904" class="zbj0d-fph"/></linearGradient><linearGradient id="iCUMoEc" x1="11.118" x2="8.993" y1="26.299" y2="25.549" gradientUnits="userSpaceOnUse"><stop class="g7n19jw2p"/><stop offset="1" class="lw0wsfo7o"/></linearGradient><linearGradient id="idv3syc" x1="8.915" x2="10.134" y1="25.299" y2="25.763" gradientUnits="userSpaceOnUse"><stop class="ykf__gbvs"/><stop offset="1" class="jpzj4ccfh"/></linearGradient><linearGradient id="ihTfWPe" x1="5.181" x2="9.845" y1="27.205" y2="29.737" gradientUnits="userSpaceOnUse"><stop class="rtyid72og"/><stop offset="1" class="bcnephb9f"/></linearGradient><linearGradient id="ieA83vb" x1="7.524" x2="7.466" y1="28.135" y2="28.241" gradientUnits="userSpaceOnUse"><stop offset=".401" class="poy_ydb2w"/><stop offset="1" class="f_xo_r1_u"/></linearGradient><linearGradient id="is6z78C" x1="21.97" x2="21.54" y1="21.127" y2="20.354" gradientUnits="userSpaceOnUse"><stop class="va2m8brjv"/><stop offset="1" class="f3-q9vb4v"/></linearGradient><linearGradient id="iwnOGxb" x1="23.368" x2="23.009" y1="20.408" y2="19.674" gradientUnits="userSpaceOnUse"><stop class="wh6te8bft"/><stop offset="1" class="yodkvfdyw"/></linearGradient><linearGradient id="iBwCx9d" x1="26.313" x2="26.114" y1="18.838" y2="18.924" gradientUnits="userSpaceOnUse"><stop offset=".244" class="jylqepbzd"/><stop offset="1" class="v2dwqfdba"/><stop offset="1" class="byifs8b3c"/></linearGradient><linearGradient id="i4iFAyd" x1="27.532" x2="25.439" y1="21.149" y2="16.272" gradientUnits="userSpaceOnUse"><stop class="rtyid72og"/><stop offset="1" class="bcnephb9f"/></linearGradient><linearGradient id="iOQGJ1x" x1="26.269" x2="26.38" y1="18.967" y2="18.921" gradientUnits="userSpaceOnUse"><stop offset=".401" class="vvs_3yeki"/><stop offset="1" class="waplrebxe"/></linearGradient><linearGradient id="iAjkNEM" x1="10.707" x2="10.417" y1="6.132" y2="6.132" gradientUnits="userSpaceOnUse"><stop class="vo9agqbnp"/><stop offset="1" class="fwwugibmc"/></linearGradient><linearGradient id="iot4cHB" x1="15.505" x2="15.135" y1="5.511" y2="6.66" gradientUnits="userSpaceOnUse"><stop class="ix2ytv1nc"/><stop offset="1" class="sla6kib8v"/></linearGradient><linearGradient id="iGDhgxd" x1="14.683" x2="11.226" y1="6.182" y2="6.697" gradientUnits="userSpaceOnUse"><stop class="f43nfdclv"/><stop offset="1" class="ixdockwro"/></linearGradient><linearGradient id="iD3Lnsd" x1="10.413" x2="11.265" y1="7.402" y2="7.372" gradientUnits="userSpaceOnUse"><stop class="xaj4s_mqh"/><stop offset="1" class="nzdq87b8k"/></linearGradient><linearGradient id="i4458nd" x1="15.084" x2="14.58" y1="7.021" y2="6.977" gradientUnits="userSpaceOnUse"><stop class="mxfqo-b2y"/><stop offset="1" class="z8_150olp"/></linearGradient><linearGradient id="iZdgi3b" x1="12.615" x2="16.302" y1="4.831" y2="3.51" gradientUnits="userSpaceOnUse"><stop class="m26ledckw"/><stop offset="1" class="yudgedput"/></linearGradient><linearGradient id="i1tQzLc" x1="12.465" x2="12.89" y1="6.48" y2="6.48" gradientUnits="userSpaceOnUse"><stop class="brzpz-p3w"/><stop offset="1" class="qxphtrj0e"/></linearGradient><linearGradient id="iMaJkbb" x1="13.281" x2="12.817" y1="6.626" y2="6.62" gradientUnits="userSpaceOnUse"><stop class="hcuo1obkg"/><stop offset="1" class="soj01hbui"/></linearGradient><linearGradient id="iIokemN" x1="12.944" x2="12.944" y1="6.962" y2="6.703" gradientUnits="userSpaceOnUse"><stop class="xk94moblk"/><stop offset="1" class="v1vf9kb3x"/></linearGradient><linearGradient id="iNK680d" x1="12.387" x2="12.584" y1="7.694" y2="7.382" gradientUnits="userSpaceOnUse"><stop class="ssfga94sp"/><stop offset=".663" class="t-wcrfbaw"/></linearGradient><linearGradient id="i4rcH1c" x1="14.195" x2="14.053" y1="5.721" y2="5.809" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iGkKLme" x1="12.204" x2="12.062" y1="5.721" y2="5.809" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iu6pJKe" x1="14.202" x2="14.011" y1="4.753" y2="4.364" gradientUnits="userSpaceOnUse"><stop class="bac636b7w"/><stop offset="1" class="eqzjb1bwj"/></linearGradient><linearGradient id="iQggcue" x1="11.8" x2="11.262" y1="4.695" y2="4.469" gradientUnits="userSpaceOnUse"><stop class="bac636b7w"/><stop offset="1" class="eqzjb1bwj"/></linearGradient><linearGradient id="ixwRf1c" x1="10.746" x2="10.746" y1="3.783" y2="4.759" gradientUnits="userSpaceOnUse"><stop offset=".228" class="zw2ljvb-t"/><stop offset="1" class="ohs50t_5m"/></linearGradient><linearGradient id="ipkOA9c" x1="9.826" x2="13.537" y1="3.92" y2="3.92" gradientUnits="userSpaceOnUse"><stop class="uul9_ttvm"/><stop offset="1" class="hwrqknt4x"/></linearGradient><linearGradient id="iy9n8Je" x1="13.599" x2="13.599" y1="4.264" y2="4.147" gradientUnits="userSpaceOnUse"><stop class="g0kn9gb3f"/><stop offset="1" class="nqhicrryp"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-bouncing-ball-medium" /></template>
<style>
.a1ftncccj {
  stop-color: var(--svg-color--8f6459, #8F6459);
  stop-opacity: 0;
}

.ak2kuya8m {
  cx: 10.707px;
  cy: 6.005px;
  r: 0.756px;
}

.akiqkcbyd {
  stop-color: var(--svg-color--af8173, #AF8173);
}

.an_-aznlj {
  stop-color: var(--svg-color--7c5267, #7C5267);
}

.ancrqsbmw {
  stop-color: var(--svg-color--4c3945, #4C3945);
}

.awgn1c4se {
  stop-color: var(--svg-color--9e99a0, #9E99A0);
  stop-opacity: 0;
}

.ay5-f4_3t {
  fill: var(--svg-color--88024e, #88024E);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M12.252 7.23c.174.09.382.142.604.142a1.3 1.3 0 0 0 .604-.143a.12.12 0 0 1 .142.024a.11.11 0 0 1 .012.143m-1.362-.167l1.32.14m-1.32-.14a.12.12 0 0 0-.142.025a.11.11 0 0 0-.012.142m.154-.167l-.113.14m1.475.027l-.041-.028m.041.028l-.041-.028m.041.028a.9.9 0 0 1-.758.405a.9.9 0 0 1-.758-.405m1.475-.028a.86.86 0 0 1-.717.383a.86.86 0 0 1-.716-.383m-.042.028l.041-.028m-.041.028l.041-.028");
}

.b_tb2tvui {
  fill: var(--svg-color--000, #000);
  d: path("M12.098 5.885a.23.23 0 0 0-.232-.232a.23.23 0 0 0-.205.338h.41a.23.23 0 0 0 .027-.106");
}

.b1yazzwzl {
  d: path("m11 20.604l.673-.75l2.336 1.86c-.07.046-.328.207-.797.476c-.644.412-1.029 1.088-1.14 1.375l-1.493 3.703l-1.977-.969c.326-.86 1.06-2.837 1.391-3.875s.81-1.646 1.008-1.82");
}

.b1ysgbbus {
  width: 0.659px;
  height: 1.111px;
  x: 19.37px;
  y: 13.469px;
  rx: 0.33px;
}

.b4mlr_y9s {
  stop-color: var(--svg-color--b08971, #B08971);
}

.bac636b7w {
  stop-color: var(--svg-color--5b4545, #5B4545);
}

.bcnephb9f {
  stop-color: var(--svg-color--d4c1e8, #D4C1E8);
}

.bnpz8rbzn {
  stop-color: var(--svg-color--9e99a0, #9E99A0);
}

.brzpz-p3w {
  stop-color: var(--svg-color--8b6455, #8B6455);
}

.byifs8b3c {
  stop-color: var(--svg-color--ff6937, #FF6937);
  stop-opacity: 0;
}

.c-qpqdbmc {
  stop-color: var(--svg-color--806d93, #806D93);
}

.c02-eqbxv {
  stop-color: var(--svg-color--8f5d65, #8F5D65);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.crfmvdbeh {
  d: path("M12.235 5.837c0-.13-.106-.217-.135-.244l-.13.127l.08.163z");
}

.cu-ecjbbc {
  stop-color: var(--svg-color--8f6459, #8F6459);
}

.cxprecb8d {
  stop-color: var(--svg-color--93869f, #93869F);
  stop-opacity: 0;
}

.cy6exab_x {
  stop-color: var(--svg-color--806d93, #806D93);
  stop-opacity: 0;
}

.d4a71bwtp {
  stop-color: var(--svg-color--3b8be5, #3B8BE5);
}

.d66ufbbtl {
  stop-color: var(--svg-color--8a5d55, #8A5D55);
  stop-opacity: 0;
}

.dc-w_nb2z {
  d: path("M23.563 19.82v-.779a.27.27 0 0 0-.277-.293c-.162.01-.507-.055-.594-.394c-.087-.34.206-.574.363-.65l2.362-1.327a.4.4 0 0 1 .566.195l1.907 4.586a.3.3 0 0 1-.18.4l-.568.194a.53.53 0 0 1-.625-.246c-.766-1.312-1.607-1.506-2.042-1.521a1.4 1.4 0 0 0-.51.09c-.185.064-.402-.06-.402-.255");
}

.dcym8repk {
  stop-color: var(--svg-color--9b7168, #9B7168);
  stop-opacity: 0;
}

.dd8hfetks {
  stop-color: var(--svg-color--4e3c3a, #4E3C3A);
  stop-opacity: 0;
}

.dg9o8ubcl {
  stop-color: var(--svg-color--895f52, #895F52);
  stop-opacity: 0;
}

.diezlkbrv {
  stop-color: var(--svg-color--9b7264, #9B7264);
}

.dmwymqbmp {
  d: path("M9.826 3.302a.1.1 0 0 1 .1-.1h5.925a.1.1 0 0 1 .1.1v.862a.1.1 0 0 1-.1.1H9.926a.1.1 0 0 1-.1-.1z");
}

.don2uv-3m {
  stop-color: var(--svg-color--9c7f8c, #9C7F8C);
}

.dwmdrq4-i {
  cx: 15.014px;
  cy: 6.006px;
  r: 0.45px;
  fill: var(--svg-color--a57c70, #A57C70);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e3m1knbgu {
  stop-color: var(--svg-color--e7dff1, #E7DFF1);
}

.e4tqe_ftq {
  d: path("M13.814 5.566c.029.039-.031.086-.1.137c-.068.05-.12.087-.148.048c-.029-.038.003-.11.072-.162c.068-.051.147-.061.176-.023");
}

.e5edx9bib {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M13.608 4.709c.194-.034.574-.025.837.18");
}

.e6v6vrbif {
  stop-color: var(--svg-color--ab7773, #AB7773);
}

.eaj548bgj {
  stop-color: var(--svg-color--695279, #695279);
}

.eikeckbha {
  d: path("M11.657 11.705c-.238-1.5.143-2.745.383-3.125c.293-.606.987-.804 1.296-.828h2.438c.386.577.634 1.595.744 2.24c.034.203.078.404.145.6c.365 1.063 1.627 4.74 2.14 6.133a.253.253 0 0 1-.239.34h-5.25a.57.57 0 0 1-.55-.391c-.423-1.315-.893-3.616-1.107-4.969");
}

.ep0hblblj {
  stop-color: var(--svg-color--c1add1, #C1ADD1);
  stop-opacity: 0;
}

.epsd93bnv {
  d: path("m15.038 3.073l.194.096a.89.89 0 0 1 .461.966l-.267 1.377c-.024.142-.118.237-.259.24l-.008.001s.024-.41.049-.652c.02-.196-.015-.256-.195-.435a.57.57 0 0 1-.17-.386v-.386a.26.26 0 0 0-.194-.242c-.291-.072-.898-.193-1.773-.193s-1.48.12-1.772.193a.235.235 0 0 0-.195.242v.386c0 .145-.048.29-.17.386l-.072.073c-.098.072-.146.217-.146.338c.024.266.048.652.048.652h-.022a.29.29 0 0 1-.269-.242l-.267-1.376a.92.92 0 0 1 .486-.942l.194-.096c.121-.073.243-.17.364-.266l.437-.458a.89.89 0 0 1 .996-.145c.243.072.51.072.753 0a1.09 1.09 0 0 1 1.068.241l.364.362c.098.121.219.193.365.266");
}

.eqzjb1bwj {
  stop-color: var(--svg-color--5b4545, #5B4545);
  stop-opacity: 0;
}

.ev4-2pfvs {
  stop-color: var(--svg-color--834e63, #834E63);
}

.f_xo_r1_u {
  stop-color: var(--svg-color--e4d5e5, #E4D5E5);
  stop-opacity: 0;
}

.f0cdn8__t {
  cx: 11.744px;
  cy: 5.653px;
  rx: 0.176px;
  ry: 0.089px;
}

.f3-q9vb4v {
  stop-color: var(--svg-color--ad7c77, #AD7C77);
  stop-opacity: 0;
}

.f43nfdclv {
  stop-color: var(--svg-color--c69980, #C69980);
}

.f7hwkw-sq {
  stop-color: var(--svg-color--8a5d55, #8A5D55);
}

.f8nqagboh {
  d: path("M10.547 5.728h.022s-.024-.385-.048-.651c0-.12.048-.266.146-.338l.072-.073a.48.48 0 0 0 .17-.386v-.386c0-.12.073-.218.195-.242a7.4 7.4 0 0 1 1.772-.193c.875 0 1.482.12 1.773.193a.26.26 0 0 1 .194.242v.386c0 .145.073.29.17.386c.228.16.213.247.195.435a21 21 0 0 0-.049.652h.008l-.12 1.792c-.073.801-.703 1.36-1.453 1.36H12.14c-.775 0-1.38-.559-1.453-1.36z");
}

.fkee40m0y {
  stop-color: var(--svg-color--8f5d78, #8F5D78);
}

.fqax45bnt {
  stop-color: var(--svg-color--bf5347, #BF5347);
}

.fr4wpbo2m {
  stop-color: var(--svg-color--422235, #422235);
}

.ft5dv1b6b {
  fill: none;
}

.fwwugibmc {
  stop-color: var(--svg-color--6e464d, #6E464D);
}

.g_v4sglua {
  stop-color: var(--svg-color--5290df, #5290DF);
}

.g0kn9gb3f {
  stop-color: var(--svg-color--b391c2, #B391C2);
}

.g7n19jw2p {
  stop-color: var(--svg-color--e2cded, #E2CDED);
}

.g8dpdlbxs {
  stop-color: var(--svg-color--a7836a, #A7836A);
  stop-opacity: 0;
}

.ga-j-qbpm {
  d: path("m9.12 25.79l.482.61a.27.27 0 0 0 .399.06c.12-.109.433-.272.71-.06c.279.213.195.579.118.735L9.797 29.64a.4.4 0 0 1-.564.197l-4.34-2.418a.3.3 0 0 1-.105-.425l.326-.506a.53.53 0 0 1 .643-.193c1.414.556 2.194.186 2.545-.071a1.4 1.4 0 0 0 .345-.387c.104-.165.353-.202.473-.049");
}

.gc9u7lbfl {
  stop-color: var(--svg-color--53adfa, #53ADFA);
  stop-opacity: 0;
}

.ginv3dbis {
  d: path("M18.292 22.659c-1.2-.713-1.919-1.898-2.143-2.454l2.156-3.015c.378.41 1.05 1.396 1.46 2.022a.9.9 0 0 1 .148.584c-.12 1.06-.567 2.06-.923 2.675a.505.505 0 0 1-.698.188");
}

.gpus1rbiy {
  stop-color: var(--svg-color--ccbdcf, #CCBDCF);
  stop-opacity: 0;
}

.gtdfzvb-d {
  cx: 10.707px;
  cy: 6.006px;
  r: 0.45px;
}

.guxv2rb-g {
  stop-color: var(--svg-color--8d6353, #8D6353);
}

.h8mf77buf {
  fill: var(--svg-color--af8870, #AF8870);
  fill-rule: evenodd;
  d: path("M5.125 14.597c-.293.2-.45.423-.481.5a.415.415 0 1 1-.768-.315c.11-.269.397-.608.78-.87c.398-.272.941-.49 1.589-.457a.415.415 0 0 1-.042.829a1.75 1.75 0 0 0-1.078.313");
}

.h9h99sbjz {
  cx: 11.744px;
  cy: 5.653px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.176px;
  ry: 0.089px;
}

.hcuo1obkg {
  stop-color: var(--svg-color--cda186, #CDA186);
}

.hpxf53bap {
  d: path("M19.324 8.304a.095.095 0 0 0-.107.03c-.44.55-.75 1.567-.821 2.056c.167.063.314.137.432.226c.418.266.704.576.875.93c.812-.549 1.637-.802 2.096-.855c-.34-.803-.92-1.49-1.734-2.009a4 4 0 0 0-.741-.378");
}

.hq2xmibfx {
  d: path("M13.843 5.48a.404.404 0 0 1 .39.511h-.78a.406.406 0 0 1 .391-.51");
}

.hwrqknt4x {
  stop-color: var(--svg-color--d3c9dc, #D3C9DC);
  stop-opacity: 0;
}

.hx2_avbkm {
  d: path("M14.203 5.832a.4.4 0 0 0-.104-.21l-.118.13l.053.103z");
}

.idljld4zp {
  cx: 5.18px;
  cy: 19.346px;
  r: 2.721px;
}

.illubsb_v {
  stop-color: var(--svg-color--bd8b7f, #BD8B7F);
}

.ip3ktqbqy {
  stop-color: var(--svg-color--39bbf9, #39BBF9);
}

.ivhsfvmdg {
  stop-color: var(--svg-color--644949, #644949);
  stop-opacity: 0;
}

.ivvzkzyvu {
  d: path("M10.52 5.077c0-.12.05-.266.147-.338l.072-.073a.48.48 0 0 0 .17-.386v-.386c0-.12.073-.218.195-.242a7.4 7.4 0 0 1 1.772-.193c.875 0 1.482.12 1.773.193a.26.26 0 0 1 .194.242v.386c0 .145.073.29.17.386c.228.16.213.247.195.435a21 21 0 0 0-.049.652h.008l-.12 1.792c-.073.801-.703 1.36-1.453 1.36H12.14c-.775 0-1.38-.559-1.453-1.36c-.063-.822-.091-1.647-.166-2.468");
}

.ix2ytv1nc {
  stop-color: var(--svg-color--cca68c, #CCA68C);
}

.ixdockwro {
  stop-color: var(--svg-color--916762, #916762);
}

.j1n_ptbit {
  stop-color: var(--svg-color--7b5a93, #7B5A93);
}

.j88k0lalk {
  d: path("M12.962 17.455c.094-.275.216-.52.265-.61h5.149c.539 1.52-.652 2.927-1.2 3.24c-.978.6-2.892 1.779-3.085 1.898c-.242.148-.512.238-.73.066c-.759-.531-1.555-1.508-1.844-2.008c-.232-.4.023-.74.18-.86c.827-.698 1.148-1.382 1.265-1.726");
}

.j9f4fjdso {
  fill: var(--svg-color--e8e5eb, #E8E5EB);
  d: path("M19.324 8.304a.095.095 0 0 0-.107.03c-.44.55-.75 1.567-.821 2.056c.167.063.314.137.432.226c.418.266.704.576.875.93c.812-.549 1.637-.802 2.096-.855c-.34-.803-.92-1.49-1.734-2.009a4 4 0 0 0-.741-.378");
}

.je_aabb8l {
  stop-color: var(--svg-color--644949, #644949);
}

.jixz69llq {
  stop-color: var(--svg-color--3c93f1, #3C93F1);
}

.jpzj4ccfh {
  stop-color: var(--svg-color--c4b0ca, #C4B0CA);
  stop-opacity: 0;
}

.jy7vazb8a {
  stop-color: var(--svg-color--f0eaf5, #F0EAF5);
}

.jylqepbzd {
  stop-color: var(--svg-color--4079dd, #4079DD);
}

.ki2rd4v4k {
  stop-color: var(--svg-color--554042, #554042);
}

.kqsf2kvhx {
  stop-color: var(--svg-color--996d5c, #996D5C);
  stop-opacity: 0;
}

.ks47q0bjb {
  stop-color: var(--svg-color--9f6ea3, #9F6EA3);
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.l8siv2hwp {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M10.804 3.827v.407c-.004.067-.032.217-.117.281");
}

.lakgv5bqc {
  stop-color: var(--svg-color--b38970, #B38970);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lw0wsfo7o {
  stop-color: var(--svg-color--c5b1cb, #C5B1CB);
}

.m_hc3t5pq {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.773 5.358a.63.63 0 0 0-.613.48c-.02.078.04.153.12.153h1.01a.104.104 0 0 0 .104-.123a.634.634 0 0 0-.621-.51");
}

.m16zjqbqa {
  d: path("M11.866 5.48a.404.404 0 0 0-.389.511h.78a.407.407 0 0 0-.391-.51");
}

.m26ledckw {
  stop-color: var(--svg-color--c89f8b, #C89F8B);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mdx4akbxm {
  stop-color: var(--svg-color--ff8c60, #FF8C60);
}

.mf5e09ark {
  stop-color: var(--svg-color--7e4944, #7E4944);
}

.mifq-tdon {
  stop-color: var(--svg-color--c39787, #C39787);
}

.miwjp6b7g {
  fill: var(--svg-color--b7877d, #B7877D);
  d: path("m12.683 5.876l-.24.77a.244.244 0 0 0 .235.316h.356c.167 0 .285-.16.236-.316l-.24-.77c-.052-.17-.293-.17-.347 0");
}

.mmmkqcbgq {
  stop-color: var(--svg-color--8f5d65, #8F5D65);
  stop-opacity: 0;
}

.mneu5xbew {
  stop-color: var(--svg-color--fa4e2e, #FA4E2E);
  stop-opacity: 0;
}

.mxfqo-b2y {
  stop-color: var(--svg-color--c1987f, #C1987F);
}

.n-ko-_w7d {
  stop-color: var(--svg-color--c39787, #C39787);
  stop-opacity: 0;
}

.n30gi-53g {
  stop-color: var(--svg-color--a471bc, #A471BC);
}

.n7o-m0b5s {
  stop-color: var(--svg-color--624c49, #624C49);
}

.n89_5nb9r {
  fill: var(--svg-color--af8870, #AF8870);
  fill-rule: evenodd;
  d: path("M6.293 14.778c-.79-.084-1.136.337-1.209.514a.415.415 0 1 1-.768-.315c.211-.515.904-1.147 2.065-1.024a.415.415 0 1 1-.088.825");
}

.n91c-gs8j {
  stop-color: var(--svg-color--865d5f, #865D5F);
}

.nm4xmabvr {
  stop-color: var(--svg-color--c09989, #C09989);
}

.nqhicrryp {
  stop-color: var(--svg-color--b391c2, #B391C2);
  stop-opacity: 0;
}

.nzdq87b8k {
  stop-color: var(--svg-color--9b7569, #9B7569);
  stop-opacity: 0;
}

.o-iz-vbwp {
  stop-color: var(--svg-color--b7a8c2, #B7A8C2);
}

.o27_2ebdq {
  stop-color: var(--svg-color--d85b75, #D85B75);
}

.o67susxgp {
  stop-color: var(--svg-color--51b1ff, #51B1FF);
  stop-opacity: 0;
}

.o7o4d8pps {
  stop-color: var(--svg-color--92869f, #92869F);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.of70meq1k {
  d: path("m11.432 25.15l-.853 2.118l-1.977-.969c.176-.463.47-1.25.755-2.041z");
}

.oha5hfbwc {
  stop-color: var(--svg-color--f0eaf5, #F0EAF5);
  stop-opacity: 0;
}

.ohs50t_5m {
  stop-color: var(--svg-color--4a3236, #4A3236);
  stop-opacity: 0;
}

.p3cy4lbfc {
  stop-color: var(--svg-color--b38970, #B38970);
}

.p3ru7q3ze {
  d: path("M11.884 8.91c.147.244.5.623 1.02.623c.886 0 1.253-.43 1.542-1.101c.124-.288.365-.79.438-.953c.695.105.89.273.89.273l.008.012c-.149.277-.4.78-.453.984c-.07.274-.238 1.051.25 1.688c.373.486.812.598 1.233.588c.48 1.403 1.533 4.46 1.99 5.7a.253.253 0 0 1-.238.34h-5.25a.57.57 0 0 1-.55-.39c-.423-1.315-.893-3.616-1.107-4.969c-.19-1.197.014-2.232.227-2.794");
}

.pa6b3tb0c {
  stop-color: var(--svg-color--cfbedb, #CFBEDB);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.poy_ydb2w {
  stop-color: var(--svg-color--e4d5e5, #E4D5E5);
}

.pydwqlfbr {
  stop-color: var(--svg-color--9c7460, #9C7460);
}

.q7m_lo14i {
  stop-color: var(--svg-color--925971, #925971);
}

.qb2q8bclu {
  stop-color: var(--svg-color--8a494a, #8A494A);
}

.qc5t8db-b {
  fill: var(--svg-color--af8870, #AF8870);
  fill-rule: evenodd;
  d: path("M6.322 13.685c-.775-.132-1.17.089-1.3.289a.415.415 0 1 1-.696-.451c.391-.605 1.214-.814 2.135-.657a.415.415 0 1 1-.14.819");
}

.qexsyge6i {
  d: path("M19.267 22.455c-.213.09-.352.07-.372.047l.754-2.93a.72.72 0 0 0 .555-.039l3.11-1.75l.726 2.145c-1.518.805-4.561 2.437-4.773 2.527");
}

.qgy1d6uwa {
  d: path("m14.65 3.46l-1.393.464a.474.474 0 0 0 .213.92l1.385-.186z");
}

.qmnjff_ag {
  stop-color: var(--svg-color--ab7773, #AB7773);
  stop-opacity: 0;
}

.qo7u-3bcf {
  stop-color: var(--svg-color--76594a, #76594A);
}

.qpbv0c39t {
  stop-color: var(--svg-color--9c5c64, #9C5C64);
}

.qrb0sjbdn {
  stop-color: var(--svg-color--8b6757, #8B6757);
}

.qu4z4jkud {
  stop-color: var(--svg-color--9380a4, #9380A4);
  stop-opacity: 0;
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qxphtrj0e {
  stop-color: var(--svg-color--8b6455, #8B6455);
  stop-opacity: 0;
}

.qysvg004b {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M13.814 5.566c.029.039-.031.086-.1.137c-.068.05-.12.087-.148.048c-.029-.038.003-.11.072-.162c.068-.051.147-.061.176-.023");
}

.r8ef-k39g {
  fill: var(--svg-color--87565c, #87565C);
  d: path("m12.731 5.95l-.371.77c-.046.158.065.316.221.316h.334c.156 0 .267-.16.22-.316l-.225-.77c-.048-.17-.128-.17-.179 0");
}

.rtyid72og {
  stop-color: var(--svg-color--d5c2e7, #D5C2E7);
}

.rudj2xgsn {
  fill: var(--svg-color--c8a08c, #C8A08C);
  d: path("M20.857 14.169c.475-1.675-.198-3.354-.594-3.985l.782-.383c.906 1.672.953 2.774.734 3.618z");
}

.rx_o_e39d {
  stop-color: var(--svg-color--4d3a45, #4D3A45);
}

.s4af_bb4s {
  fill-rule: evenodd;
  d: path("M7.132 13.933a.415.415 0 0 1 .118.575a8 8 0 0 1-.913 1.13a.415.415 0 1 1-.602-.57l.005-.005c.16-.169.494-.522.817-1.012a.415.415 0 0 1 .575-.118");
}

.s5tp33mbf {
  fill: var(--svg-color--4c3230, #4C3230);
  d: path("m11.148 4.774l.001-.001l.002-.002l.006-.004l.07-.049a1.28 1.28 0 0 1 .866-.167a.242.242 0 0 1-.076.478a.8.8 0 0 0-.534.099l-.028.02a.242.242 0 0 1-.307-.374");
}

.sa73rem9k {
  fill: var(--svg-color--83788b, #83788B);
  d: path("M12.962 17.455c.094-.275.216-.52.265-.61h5.149c.539 1.52-.652 2.927-1.2 3.24c-.978.6-2.892 1.779-3.085 1.898c-.242.148-.512.238-.73.066c-.759-.531-1.555-1.508-1.844-2.008c-.232-.4.023-.74.18-.86c.827-.698 1.148-1.382 1.265-1.726");
}

.sdljx8amv {
  stop-color: var(--svg-color--c7b9c5, #C7B9C5);
}

.sepv3nkwr {
  d: path("M5.527 16.647c.013.613.238 1.167.598 1.588l.897-.892q.093.085.176.178l-.9.895a2.23 2.23 0 0 0 1.586.621q.014.123.017.25h-.065a2.48 2.48 0 0 1-1.716-.695l-.777.773l1.754 1.913q-.088.089-.185.168l-1.746-1.905l-.77.765c.422.461.689 1.08.714 1.761a3 3 0 0 1-.25-.018a2.5 2.5 0 0 0-.64-1.567l-.877.872a3 3 0 0 1-.177-.178l.876-.87a2.23 2.23 0 0 0-1.556-.575a3 3 0 0 1-.024-.25l.091-.001c.638 0 1.22.245 1.666.65l.778-.773l-1.758-1.918q.088-.09.184-.17l1.751 1.911l.774-.769a2.77 2.77 0 0 1-.671-1.784q.127.005.25.02");
}

.sla6kib8v {
  stop-color: var(--svg-color--ae7f75, #AE7F75);
}

.sn3dy7bnn {
  stop-color: var(--svg-color--9380a4, #9380A4);
}

.snq5xhi6c {
  fill: var(--svg-color--b38c70, #B38C70);
  d: path("M15.216 10.026q.558-.015 1.474.059c.827.064 1.691.195 2.138.53c.582.371.909.828 1.026 1.372c.133.614.023 1.139-.23 1.8l-.15.383c-.125.312-.24.6-.288.801c-.06.258.098.433.404.437a.18.18 0 0 1 .14.068a.4.4 0 0 0 .206.147c.082.022.14.017.22.01q.044-.005.1-.008a.14.14 0 0 1 .117.06a.33.33 0 0 0 .2.146a.45.45 0 0 0 .244-.017a.2.2 0 0 1 .172.021a.6.6 0 0 0 .205.085c.14.02.305-.039.367-.234c.035-.108.08-.297.121-.476c.098-.417.25-.821.25-1.255a4.94 4.94 0 0 0 .121-2.46c-.248-1.15-.915-2.13-1.988-2.813c-1.177-.75-3.758-.943-5.022-.903l-.173.005v2.25q.148-.001.346-.008");
}

.so34edl-m {
  stop-color: var(--svg-color--3d94fa, #3D94FA);
}

.soj01hbui {
  stop-color: var(--svg-color--cda186, #CDA186);
  stop-opacity: 0;
}

.ssfga94sp {
  stop-color: var(--svg-color--a87d7b, #A87D7B);
}

.stz6elb6u {
  fill: var(--svg-color--caa18d, #CAA18D);
  d: path("M11.657 11.705c-.238-1.5.143-2.745.383-3.125c.293-.606.987-.804 1.296-.828h2.438c.386.577.634 1.595.744 2.24c.034.203.078.404.145.6c.365 1.063 1.627 4.74 2.14 6.133a.253.253 0 0 1-.239.34h-5.25a.57.57 0 0 1-.55-.391c-.423-1.315-.893-3.616-1.107-4.969");
}

.suj-pjbhk {
  stop-color: var(--svg-color--895f52, #895F52);
}

.t-wcrfbaw {
  stop-color: var(--svg-color--a87d7b, #A87D7B);
  stop-opacity: 0;
}

.t5f4fqbxv {
  stop-color: var(--svg-color--84798d, #84798D);
  stop-opacity: 0;
}

.t5qac2c1p {
  stop-color: var(--svg-color--ff8c60, #FF8C60);
  stop-opacity: 0;
}

.t7cma5ywk {
  fill-rule: evenodd;
  d: path("M5.125 14.597c-.293.2-.45.423-.481.5a.415.415 0 1 1-.768-.315c.11-.269.397-.608.78-.87c.398-.272.941-.49 1.589-.457a.415.415 0 0 1-.042.829a1.75 1.75 0 0 0-1.078.313");
}

.thhwo06ax {
  fill: var(--svg-color--92869e, #92869E);
  d: path("M18.292 22.659c-1.2-.713-1.919-1.898-2.143-2.454l2.156-3.015c.378.41 1.05 1.396 1.46 2.022a.9.9 0 0 1 .148.584c-.12 1.06-.567 2.06-.923 2.675a.505.505 0 0 1-.698.188");
}

.tp9jx5j2y {
  stop-color: var(--svg-color--554042, #554042);
  stop-opacity: 0;
}

.tt7xwipig {
  stop-color: var(--svg-color--a471bc, #A471BC);
  stop-opacity: 0;
}

.u_3e452pz {
  stop-color: var(--svg-color--918b96, #918B96);
}

.u072kwb9c {
  d: path("m22.282 20.864l.03-.017l1.728-.92l-.727-2.144l-2.087 1.175z");
}

.ue9_nibqv {
  d: path("m14.54 4.774l-.001-.001l-.002-.002l-.006-.004l-.07-.049a1.28 1.28 0 0 0-.866-.167a.242.242 0 1 0 .076.478a.8.8 0 0 1 .534.099l.028.02a.242.242 0 0 0 .307-.374");
}

.uk_8-tw2z {
  cx: 15.014px;
  cy: 6.005px;
  r: 0.756px;
}

.uqxno_b8g {
  stop-color: var(--svg-color--3da9fd, #3DA9FD);
}

.uul9_ttvm {
  stop-color: var(--svg-color--98919c, #98919C);
}

.ux7-g74jy {
  stop-color: var(--svg-color--4e3c3a, #4E3C3A);
}

.v1vf9kb3x {
  stop-color: var(--svg-color--9c6073, #9C6073);
  stop-opacity: 0;
}

.v2dwqfdba {
  stop-color: var(--svg-color--4079dd, #4079DD);
  stop-opacity: 0;
}

.v616eizae {
  stop-color: var(--svg-color--f84c2c, #F84C2C);
}

.va2m8brjv {
  stop-color: var(--svg-color--9a6183, #9A6183);
}

.ve-itr7ex {
  fill: var(--svg-color--000, #000);
  d: path("M13.612 5.885a.23.23 0 0 1 .232-.232a.23.23 0 0 1 .205.338h-.41a.2.2 0 0 1-.027-.106");
}

.vhhvj2t-s {
  stop-color: var(--svg-color--3e98f5, #3E98F5);
}

.viuz5dbki {
  fill-rule: evenodd;
  d: path("M6.293 14.778c-.79-.084-1.136.337-1.209.514a.415.415 0 1 1-.768-.315c.211-.515.904-1.147 2.065-1.024a.415.415 0 1 1-.088.825");
}

.vo9agqbnp {
  stop-color: var(--svg-color--694448, #694448);
}

.vuejbwbij {
  d: path("M9.794 29.418a.1.1 0 0 1 .043.125l-.04.098a.4.4 0 0 1-.564.197l-4.34-2.418a.3.3 0 0 1-.106-.425l.106-.164a.15.15 0 0 1 .2-.05z");
}

.vvs_3yeki {
  stop-color: var(--svg-color--bfa7d0, #BFA7D0);
}

.w_j-6pbpp {
  stop-color: var(--svg-color--834e63, #834E63);
  stop-opacity: 0;
}

.w7i-07blq {
  stop-color: var(--svg-color--f25c44, #F25C44);
  stop-opacity: 0;
}

.waplrebxe {
  stop-color: var(--svg-color--bfa7d0, #BFA7D0);
  stop-opacity: 0;
}

.wg6epmg7n {
  stop-color: var(--svg-color--53adfa, #53ADFA);
}

.wh6te8bft {
  stop-color: var(--svg-color--bb98d6, #BB98D6);
}

.whspc9bgn {
  stop-color: var(--svg-color--39bbf9, #39BBF9);
  stop-opacity: 0;
}

.wloocxb2w {
  stop-color: var(--svg-color--a7836a, #A7836A);
}

.x-3oyg2db {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M11.245 4.943c.148-.13.471-.268.872-.204");
}

.x5036tbci {
  fill: var(--svg-color--af8870, #AF8870);
  fill-rule: evenodd;
  d: path("M5.23 14.105c-.306.178-.45.37-.473.426a.415.415 0 0 1-.768-.315c.12-.291.436-.603.824-.828c.407-.237.95-.414 1.58-.382a.415.415 0 1 1-.042.829a2.03 2.03 0 0 0-1.12.27");
}

.x99s9tbej {
  fill-rule: evenodd;
  d: path("M6.322 13.685c-.775-.132-1.17.089-1.3.289a.415.415 0 1 1-.696-.451c.391-.605 1.214-.814 2.135-.657a.415.415 0 1 1-.14.819");
}

.xaj4s_mqh {
  stop-color: var(--svg-color--9b7569, #9B7569);
}

.xcwnd6bms {
  d: path("M25.282 16.554a.1.1 0 0 1 .044-.125l.091-.052a.4.4 0 0 1 .566.195l1.907 4.586a.3.3 0 0 1-.18.4l-.184.063a.15.15 0 0 1-.187-.085z");
}

.xjnuavuoc {
  stop-color: var(--svg-color--9c5c64, #9C5C64);
  stop-opacity: 0;
}

.xk94moblk {
  stop-color: var(--svg-color--9c6073, #9C6073);
}

.xo-sv8bhm {
  stop-color: var(--svg-color--422235, #422235);
  stop-opacity: 0;
}

.xp-9f0bqu {
  stop-color: var(--svg-color--624c49, #624C49);
  stop-opacity: 0;
}

.xqqpogm7y {
  cx: 15.014px;
  cy: 6.006px;
  r: 0.45px;
}

.xryjwwrmy {
  fill: var(--svg-color--4f3332, #4F3332);
  d: path("m15.038 3.073l.194.096a.89.89 0 0 1 .461.966l-.267 1.377c-.024.142-.118.237-.259.24l-.008.001s.024-.41.049-.652c.02-.196-.015-.256-.195-.435a.57.57 0 0 1-.17-.386v-.386a.26.26 0 0 0-.194-.242c-.291-.072-.898-.193-1.773-.193s-1.48.12-1.772.193a.235.235 0 0 0-.195.242v.386c0 .145-.048.29-.17.386l-.072.073c-.098.072-.146.217-.146.338c.024.266.048.652.048.652h-.022a.29.29 0 0 1-.269-.242l-.267-1.376a.92.92 0 0 1 .486-.942l.194-.096c.121-.073.243-.17.364-.266l.437-.458a.89.89 0 0 1 .996-.145c.243.072.51.072.753 0a1.09 1.09 0 0 1 1.068.241l.364.362c.098.121.219.193.365.266");
}

.xs_h82bcz {
  stop-color: var(--svg-color--925971, #925971);
  stop-opacity: 0;
}

.xu1e5_bcz {
  stop-color: var(--svg-color--3c92ef, #3C92EF);
}

.xyeix3b7z {
  d: path("m12.683 5.876l-.24.77a.244.244 0 0 0 .235.316h.356c.167 0 .285-.16.236-.316l-.24-.77c-.052-.17-.293-.17-.347 0");
}

.y_4pajl7d {
  fill-rule: evenodd;
  d: path("m11.974 8.996l.053-.092l1.728 1.008l-.074.127c-.712 1.224-1.57 2.698-3.676 3.891c-.768.435-1.654.656-2.381.773c-.257.041-.503.07-.729.091c-.55.05-.994-.403-.988-.955l.01-1.024c.251.002.784.01 1.39-.087c.617-.098 1.238-.27 1.712-.538c1.633-.925 2.26-2.001 2.955-3.194");
}

.y8eztfbsi {
  fill-rule: evenodd;
  d: path("M5.23 14.105c-.306.178-.45.37-.473.426a.415.415 0 0 1-.768-.315c.12-.291.436-.603.824-.828c.407-.237.95-.414 1.58-.382a.415.415 0 1 1-.042.829a2.03 2.03 0 0 0-1.12.27");
}

.ykf__gbvs {
  stop-color: var(--svg-color--a38f93, #A38F93);
}

.yo43zmb5m {
  d: path("m11.148 4.774l.001-.001l.002-.002l.006-.004l.07-.049a1.28 1.28 0 0 1 .866-.167a.242.242 0 0 1-.076.478a.8.8 0 0 0-.534.099l-.028.02a.242.242 0 0 1-.307-.374");
}

.yodkvfdyw {
  stop-color: var(--svg-color--bb98d6, #BB98D6);
  stop-opacity: 0;
}

.yrp6iebks {
  fill: var(--svg-color--4c3230, #4C3230);
  d: path("m14.54 4.774l-.001-.001l-.002-.002l-.006-.004l-.07-.049a1.28 1.28 0 0 0-.866-.167a.242.242 0 1 0 .076.478a.8.8 0 0 1 .534.099l.028.02a.242.242 0 0 0 .307-.374");
}

.yudgedput {
  stop-color: var(--svg-color--c89f8b, #C89F8B);
  stop-opacity: 0;
}

.yz1zcsbvd {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.937 5.358a.63.63 0 0 1 .613.48a.124.124 0 0 1-.12.153h-1.01a.104.104 0 0 1-.103-.123a.63.63 0 0 1 .62-.51");
}

.z8_150olp {
  stop-color: var(--svg-color--c1987f, #C1987F);
  stop-opacity: 0;
}

.zbj0d-fph {
  stop-color: var(--svg-color--ff7937, #FF7937);
}

.zw2ljvb-t {
  stop-color: var(--svg-color--4a3236, #4A3236);
}

</style>
