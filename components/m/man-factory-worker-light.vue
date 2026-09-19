<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iZRHZAb)"><path fill="url(#i1Pd52d)" class="e5n7-cbky"/><path fill="url(#iM6rPqd)" class="e5n7-cbky"/></g><g filter="url(#i64R2qd)"><path class="ii_vcdblz"/></g><g filter="url(#ixBroSd)"><path class="x9-b3hbfy"/></g><g filter="url(#iFK5c4r)"><path class="a424ylq9x"/><path fill="url(#i7bctJc)" class="m3dxw5b4u"/><path fill="url(#izNqDsc)" class="m3dxw5b4u"/><path fill="url(#it3vqkc)" class="m3dxw5b4u"/></g><path class="a1i_j40xh"/><path fill="url(#igSiocc)" class="rq76sybla"/><path fill="url(#iQD9PdN)" class="rq76sybla"/><path fill="url(#ifkmApd)" class="rq76sybla"/><path fill="url(#iUzRGHc)" class="rq76sybla"/><path fill="url(#iZLtlOc)" class="ndlc49hkf"/><path fill="url(#iHff3Oe)" class="ndlc49hkf"/><path fill="url(#iFGxoeb)" class="lt_b3wboz"/><path fill="url(#i5m29vW)" class="lt_b3wboz"/><path class="vbc9nqbss"/><path fill="url(#iPRoNnL)" class="pi6c47yng"/><path class="javsik_yi"/><path fill="url(#iOgo57h)" class="u-q3e7b8s"/><path fill="url(#iI8KLcb)" class="g7oiw84_l"/><path fill="url(#i3MqPDW)" class="fbjx3y-qb"/><path fill="url(#i8fe9wd)" class="fbjx3y-qb"/><g filter="url(#ieYSRdc)"><path class="kc9q3mbff"/><path fill="url(#ifFH9Wc)" class="qv8wc6zla"/></g><path fill="url(#iUEJUid)" class="ue1gv6enh"/><path fill="url(#i294t4w)" class="ue1gv6enh"/><g filter="url(#iCKeXJc)"><path fill="url(#igKMsTc)" class="na59ribzw"/></g><path class="vczswwwcd"/><g filter="url(#iXfPa4c)"><path fill="url(#iOKq7lc)" class="qtzewq2gr"/><path fill="url(#iI8fpid)" class="qtzewq2gr"/><path fill="url(#ivXSXbb)" class="qtzewq2gr"/><path fill="url(#inoTRvd)" class="qtzewq2gr"/><path fill="url(#ifrujYb)" class="qtzewq2gr"/></g><path fill="url(#iElbqJe)" class="qtzewq2gr"/><g filter="url(#idmYcyi)"><path stroke="url(#ivhW0ze)" class="bzs2-ddka"/></g><g filter="url(#i6pBGPb)"><path stroke="url(#iNT2srd)" class="pjsi77bhr"/></g><g filter="url(#if7CVfd)"><path stroke="url(#iflwwud)" class="oool1tdti"/></g><g filter="url(#i9ts5Td)"><circle fill="url(#iUuo56b)" class="i4ysa-bno"/></g><g filter="url(#ieWpm5b)"><circle fill="url(#i9b7Qne)" class="i8i6txbig"/></g><circle fill="url(#iCjRWPd)" class="wct4qccbg"/><g filter="url(#iBiVmCd)"><circle fill="url(#i9KnjYb)" class="hh437879c"/></g><g filter="url(#i0DCpRb)"><path fill="url(#iEGaybd)" class="dlrwjtb7t"/></g><path fill="url(#iHV1Z2d)" class="dlrwjtb7t"/><path fill="url(#if5SiBb)" class="dlrwjtb7t"/><path fill="url(#iSrunrb)" class="dlrwjtb7t"/><path fill="url(#il60LuX)" class="dlrwjtb7t"/><path fill="url(#isqhFbe)" class="dlrwjtb7t"/><path fill="url(#ir5i89O)" class="dlrwjtb7t"/><path fill="url(#injMcVd)" class="dlrwjtb7t"/><g filter="url(#iegn2gL)"><path class="uit74mbey"/><path fill="url(#is4oeLb)" class="ybrylxbuq"/><path fill="url(#i5RNXhc)" class="ybrylxbuq"/><path fill="url(#iLS37Ld)" class="ybrylxbuq"/><path fill="url(#iK5yQFd)" class="ybrylxbuq"/><path fill="url(#iDPgS1a)" class="ybrylxbuq"/><path fill="url(#iZ8VHxd)" class="ybrylxbuq"/></g><path class="amp4-rn4i"/><path fill="url(#iI58sCd)" class="ybrylxbuq"/><path fill="url(#iHlPSME)" class="ybrylxbuq"/><g filter="url(#ioEifvj)"><path class="w4rn2oska"/></g><g filter="url(#ibodtte)"><path class="emv4mnw3h"/><path fill="url(#id8955d)" class="b175b4n1p"/><path fill="url(#i74JuCP)" class="b175b4n1p"/><path fill="url(#iV0qdCb)" class="b175b4n1p"/><path fill="url(#iQc3S4c)" class="b175b4n1p"/><path fill="url(#inYxWIc)" class="b175b4n1p"/></g><g filter="url(#iWgl7Ke)"><path stroke="url(#ixJLKSd)" class="grd6gl_rz"/></g><path fill="url(#iVZaHRf)" class="t4vmfmb4r"/><path class="jwqe_jbgo"/><path fill="url(#iC4ORHc)" class="cwr7ndbvn"/><path class="hdusbzsjg"/><g filter="url(#i743C3b)"><path class="jl9xgibbw"/><path fill="url(#iZmGKKW)" class="b0svlhbnq"/></g><g filter="url(#im0QJ3c)"><path fill="url(#ivjr05J)" class="hyj07d54k"/></g><path class="uf734fbqu"/><path fill="url(#imbF5Lg)" class="i9v5wucat"/><path class="tr80mtbrp"/><g filter="url(#ixXAIzx)"><path fill="url(#iilVjNe)" class="rj390kbfq"/></g><g filter="url(#iwlmzgb)"><ellipse transform="rotate(-27.914 12.393 9.954)" class="kyknafbgp"/><ellipse fill="url(#iuoxayc)" transform="rotate(-27.914 12.393 9.954)" class="jht53ab1w"/></g><g filter="url(#iOmt9Hc)"><path clip-rule="evenodd" class="jio9fxbvr"/></g><g filter="url(#iJ0eVge)"><path class="h24jl46mm"/></g><g filter="url(#iTqDVvc)"><path clip-rule="evenodd" class="q1_4ocb7a"/></g><g filter="url(#iWwA2iW)"><path class="al5ad0b-q"/></g><path fill="url(#icBL91d)" class="iycy_sbnz"/><path fill="url(#ibvcPeT)" class="g9arp8b8o"/><path fill="url(#ic8iSPb)" class="g9arp8b8o"/><path fill="url(#iLeaTZU)" class="sb1phf9zd"/><path fill="url(#iE9kqQd)" class="sb1phf9zd"/><path fill="url(#ijzTWdd)" class="ltwsa8bld"/><path fill="url(#iT74aTv)" class="ltwsa8bld"/><path fill="url(#ivqY3ab)" class="ltwsa8bld"/><g filter="url(#imz7Ase)"><path fill="url(#iCmdwmN)" class="o12zmvuzn"/></g><g filter="url(#imWnWOr)"><path class="ojb-ttbmo"/></g><g filter="url(#iMIvJnc)"><path class="ac3zfwb5z"/></g><defs><radialGradient id="iM6rPqd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -6.5 5.875 0 20.418 30)" gradientUnits="userSpaceOnUse"><stop class="bbqwceq4e"/><stop offset="1" class="s5pm96b_v"/></radialGradient><radialGradient id="i7bctJc" cx="0" cy="0" r="1" gradientTransform="rotate(137.578 3.33 12.372)scale(3.51039 2.85287)" gradientUnits="userSpaceOnUse"><stop class="ypv_kpaja"/><stop offset="1" class="iv7bj_baj"/></radialGradient><radialGradient id="izNqDsc" cx="0" cy="0" r="1" gradientTransform="matrix(-.875 1.72406 -2.87775 -1.46054 13.106 16.844)" gradientUnits="userSpaceOnUse"><stop offset=".316" class="d7sh3eboe"/><stop offset="1" class="tizux9w7p"/></radialGradient><radialGradient id="ifkmApd" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.94352 -1.86047 0 16.66 16.037)" gradientUnits="userSpaceOnUse"><stop offset=".368" class="rtj8_6bqg"/><stop offset="1" class="m8_l30tsr"/></radialGradient><radialGradient id="iUzRGHc" cx="0" cy="0" r="1" gradientTransform="matrix(-.94683 2.47509 -1.65865 -.6345 15.664 17.448)" gradientUnits="userSpaceOnUse"><stop offset=".307" class="s1rw4px-b"/><stop offset="1" class="p3_97vb4n"/></radialGradient><radialGradient id="iFGxoeb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -10.1875 3.9375 0 6.668 30)" gradientUnits="userSpaceOnUse"><stop class="mx797o4di"/><stop offset="1" class="m1_q07_me"/></radialGradient><radialGradient id="iPRoNnL" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.625 -3.70312 0 24.043 20.063)" gradientUnits="userSpaceOnUse"><stop offset=".141" class="p7prpqhjw"/><stop offset="1" class="m4mhe8bqv"/></radialGradient><radialGradient id="iOgo57h" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.76563 6.85285 0 14.734 21.438)" gradientUnits="userSpaceOnUse"><stop offset=".469" class="ee8yo8bto"/><stop offset="1" class="dn7nvsb1v"/></radialGradient><radialGradient id="iI8KLcb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.58518 -2.15241 0 14.79 16.917)" gradientUnits="userSpaceOnUse"><stop offset=".181" class="o1gf6ebie"/><stop offset=".707" class="y13139flk"/><stop offset="1" class="g67_t8fua"/></radialGradient><radialGradient id="i3MqPDW" cx="0" cy="0" r="1" gradientTransform="rotate(154.424 10.772 15.093)scale(2.44794 2.40172)" gradientUnits="userSpaceOnUse"><stop offset=".524" class="tj2vllbvr"/><stop offset=".956" class="fop80r8ws"/></radialGradient><radialGradient id="i8fe9wd" cx="0" cy="0" r="1" gradientTransform="matrix(.78818 -.60013 .4599 .60401 26.205 23.598)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="q7l79-2rh"/><stop offset="1" class="aszpk2bre"/></radialGradient><radialGradient id="ifFH9Wc" cx="0" cy="0" r="1" gradientTransform="rotate(-45 32.088 -22.467)scale(.99437 .32275)" gradientUnits="userSpaceOnUse"><stop offset=".383" class="ky_dg6bhp"/><stop offset="1" class="qwfi8obtf"/></radialGradient><radialGradient id="i294t4w" cx="0" cy="0" r="1" gradientTransform="matrix(-1.45773 0 0 -.25781 25.259 22.922)" gradientUnits="userSpaceOnUse"><stop class="wp6rq3sqk"/><stop offset="1" class="hnxygroex"/></radialGradient><radialGradient id="iI8fpid" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8017 -1.35439 0 24.568 25.305)" gradientUnits="userSpaceOnUse"><stop offset=".106" class="uzac_3qef"/><stop offset="1" class="b570nlb5r"/></radialGradient><radialGradient id="ivXSXbb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .85938 -1.45182 0 24.568 26.6)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="uzac_3qef"/><stop offset="1" class="b570nlb5r"/></radialGradient><radialGradient id="inoTRvd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .71875 -1.21425 0 24.568 27.85)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="uzac_3qef"/><stop offset="1" class="b570nlb5r"/></radialGradient><radialGradient id="ifrujYb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .79938 -1.7273 0 24.568 29.2)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="uzac_3qef"/><stop offset="1" class="b570nlb5r"/></radialGradient><radialGradient id="iElbqJe" cx="0" cy="0" r="1" gradientTransform="scale(3.72384 5.01752)rotate(90 1.09 6.07)" gradientUnits="userSpaceOnUse"><stop class="b4rjnnb6m"/><stop offset="1" class="bgp-eqwmb"/></radialGradient><radialGradient id="iUuo56b" cx="0" cy="0" r="1" gradientTransform="matrix(1.87734 3.31408 -3.81282 2.15986 10.317 9.32)" gradientUnits="userSpaceOnUse"><stop class="odxs-cbnv"/><stop offset="1" class="a02_cfb_b"/></radialGradient><radialGradient id="iCjRWPd" cx="0" cy="0" r="1" gradientTransform="rotate(134.683 7.852 8.74)scale(4.53896 6.89663)" gradientUnits="userSpaceOnUse"><stop class="u_qgni50q"/><stop offset="1" class="wg0u_rd0m"/><stop offset="1" class="alkmbvb7w"/></radialGradient><radialGradient id="i9KnjYb" cx="0" cy="0" r="1" gradientTransform="matrix(1.6854 -.20723 .11408 .92781 18.244 10.936)" gradientUnits="userSpaceOnUse"><stop class="z2op5sb3v"/><stop offset="1" class="ig-3c1b3u"/></radialGradient><radialGradient id="iEGaybd" cx="0" cy="0" r="1" gradientTransform="matrix(-5.28765 0 0 -8.98131 17.66 11.117)" gradientUnits="userSpaceOnUse"><stop class="yzaj_tb_p"/><stop offset="1" class="ny0rq0bux"/></radialGradient><radialGradient id="iHV1Z2d" cx="0" cy="0" r="1" gradientTransform="matrix(0 12.1137 -10.4474 0 15.411 5.655)" gradientUnits="userSpaceOnUse"><stop offset=".774" class="dkc_aibit"/><stop offset=".973" class="h6pwsobze"/></radialGradient><radialGradient id="if5SiBb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.2203 1.57793 0 17.098 10.03)" gradientUnits="userSpaceOnUse"><stop class="xuipl1bei"/><stop offset="1" class="f165ur9pt"/></radialGradient><radialGradient id="il60LuX" cx="0" cy="0" r="1" gradientTransform="matrix(1.20662 3.72044 -4.60978 1.49505 11.22 7.233)" gradientUnits="userSpaceOnUse"><stop class="ysugf1aqs"/><stop offset="1" class="lkgptrbsy"/></radialGradient><radialGradient id="isqhFbe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.39888 1.45417 0 12.921 9.97)" gradientUnits="userSpaceOnUse"><stop offset=".404" class="kg3uvq1fk"/><stop offset="1" class="n26l-i5_v"/></radialGradient><radialGradient id="injMcVd" cx="0" cy="0" r="1" gradientTransform="matrix(-.40221 6.96464 -7.77033 -.44874 20.037 7.62)" gradientUnits="userSpaceOnUse"><stop offset=".057" class="tpyby8h1l"/><stop offset="1" class="fo2kykbuh"/></radialGradient><radialGradient id="is4oeLb" cx="0" cy="0" r="1" gradientTransform="rotate(127.807 8.514 6.057)scale(5.58654 9.5004)" gradientUnits="userSpaceOnUse"><stop class="ck410xb1o"/><stop offset="1" class="qeh0r4bjq"/></radialGradient><radialGradient id="iLS37Ld" cx="0" cy="0" r="1" gradientTransform="matrix(-.18385 -1.98553 .97514 -.0903 10.719 7.103)" gradientUnits="userSpaceOnUse"><stop offset=".222" class="euj6xpbnj"/><stop offset="1" class="hchnd0bsx"/></radialGradient><radialGradient id="iK5yQFd" cx="0" cy="0" r="1" gradientTransform="rotate(-66.4 16.4 -10.059)scale(2.13845 1.74407)" gradientUnits="userSpaceOnUse"><stop offset=".479" class="ghdrqrbfe"/><stop offset="1" class="d7zypgbet"/></radialGradient><radialGradient id="iDPgS1a" cx="0" cy="0" r="1" gradientTransform="matrix(.9893 1.22755 -1.08384 .87349 14.067 2.157)" gradientUnits="userSpaceOnUse"><stop class="wn92vfpti"/><stop offset="1" class="t4clght5m"/></radialGradient><radialGradient id="iZ8VHxd" cx="0" cy="0" r="1" gradientTransform="matrix(1.4459 -3.025 1.04518 .49958 19.015 6.524)" gradientUnits="userSpaceOnUse"><stop class="hye_w5bmk"/><stop offset="1" class="f2dz70yyi"/></radialGradient><radialGradient id="iHlPSME" cx="0" cy="0" r="1" gradientTransform="matrix(.2578 -1.89062 1.57611 .21492 20.49 9.762)" gradientUnits="userSpaceOnUse"><stop class="h1w1jc3ne"/><stop offset="1" class="yxyzwolxt"/></radialGradient><radialGradient id="i74JuCP" cx="0" cy="0" r="1" gradientTransform="matrix(0 .22489 -.76432 0 15.304 12.356)" gradientUnits="userSpaceOnUse"><stop class="t40345qox"/><stop offset="1" class="mrnsdcbqx"/></radialGradient><radialGradient id="iQc3S4c" cx="0" cy="0" r="1" gradientTransform="rotate(157.024 6.508 7.483)scale(1.64605 2.5094)" gradientUnits="userSpaceOnUse"><stop offset=".714" class="o0aif1l1c"/><stop offset="1" class="vni43obah"/></radialGradient><radialGradient id="iVZaHRf" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.71805 2.88888 0 14.84 14.488)" gradientUnits="userSpaceOnUse"><stop class="jase_0f7h"/><stop offset="1" class="zn-qjxbde"/></radialGradient><radialGradient id="iC4ORHc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .80829 -1.28568 0 17.012 10.049)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="iZmGKKW" cx="0" cy="0" r="1" gradientTransform="matrix(-.23105 -.29773 .40992 -.31811 16.784 10.132)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="imbF5Lg" cx="0" cy="0" r="1" gradientTransform="matrix(0 .80833 -1.28574 0 12.663 10.049)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="iuoxayc" cx="0" cy="0" r="1" gradientTransform="matrix(-.0077 -.49224 .59169 -.00926 12.379 10.267)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ic8iSPb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.3125 -.47665 0 23.309 6.469)" gradientUnits="userSpaceOnUse"><stop offset=".167" class="y66dh_b5l"/><stop offset="1" class="nzjwoybta"/></radialGradient><radialGradient id="iLeaTZU" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.40034 6.13 0 14.849 7.33)" gradientUnits="userSpaceOnUse"><stop offset=".671" class="ixw-oi7aq"/><stop offset="1" class="mguibccfx"/></radialGradient><radialGradient id="ijzTWdd" cx="0" cy="0" r="1" gradientTransform="rotate(129.472 9.359 6.843)scale(6.19389 12.2026)" gradientUnits="userSpaceOnUse"><stop class="qyg3b1b6n"/><stop offset="1" class="p64oiyb7x"/></radialGradient><radialGradient id="iT74aTv" cx="0" cy="0" r="1" gradientTransform="rotate(146.725 7.907 4.576)scale(9.56883 10.9225)" gradientUnits="userSpaceOnUse"><stop offset=".512" class="yytwt1d8s"/><stop offset="1" class="s1a8ycb7r"/></radialGradient><radialGradient id="iCmdwmN" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.71875 -10.576 0 14.791 6.156)" gradientUnits="userSpaceOnUse"><stop class="z2rllvutr"/><stop offset="1" class="t8ye-ilvp"/></radialGradient><filter id="iZRHZAb" width="22.99" height="15" x="3.739" y="15.5" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy=".5"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.211765 0 0 0 0 0.431373 0 0 0 0 0.631373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2034"/></filter><filter id="i64R2qd" width="5.492" height="8.119" x="9.76" y="14.781" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2034" stdDeviation=".5"/></filter><filter id="ixBroSd" width="5.492" height="8.113" x="13.872" y="15.006" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2034" stdDeviation=".5"/></filter><filter id="iFK5c4r" width="3.592" height="6.219" x="10.712" y="15.408" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.137255 0 0 0 0 0.337255 0 0 0 0 0.811765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2034"/></filter><filter id="ieYSRdc" width="3.02" height="8.58" x="23.729" y="14.21" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.505882 0 0 0 0 0.501961 0 0 0 0 0.529412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2034"/></filter><filter id="iCKeXJc" width="3.675" height="3.685" x="24.636" y="12.621" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.447059 0 0 0 0 0.870588 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2034"/></filter><filter id="iXfPa4c" width="4.468" height="5.556" x="22.131" y="24.444" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.729412 0 0 0 0 0.509804 0 0 0 0 0.603922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2034"/></filter><filter id="idmYcyi" width="2.097" height=".3" x="22.598" y="25.852" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2034" stdDeviation=".05"/></filter><filter id="i6pBGPb" width="2.097" height=".3" x="22.52" y="27.157" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2034" stdDeviation=".05"/></filter><filter id="if7CVfd" width="2.097" height=".3" x="22.598" y="28.461" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2034" stdDeviation=".05"/></filter><filter id="i9ts5Td" width="3.427" height="3.327" x="8.445" y="9.065" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.854902 0 0 0 0 0.639216 0 0 0 0 0.576471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2034"/></filter><filter id="ieWpm5b" width="2.483" height="2.483" x="8.867" y="9.487" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2034" stdDeviation=".125"/></filter><filter id="iBiVmCd" width="2.483" height="2.483" x="18.347" y="9.487" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2034" stdDeviation=".125"/></filter><filter id="i0DCpRb" width="11.337" height="12.186" x="9.7" y="5.124" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".7"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.913725 0 0 0 0 0.686275 0 0 0 0 0.592157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2034"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.780392 0 0 0 0 0.568627 0 0 0 0 0.486275 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2034" result="effect2_innerShadow_4002_2034"/></filter><filter id="iegn2gL" width="12.557" height="8.265" x="8.561" y="1.907" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.984314 0 0 0 0 0.584314 0 0 0 0 0.129412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2034"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.972549 0 0 0 0 0.572549 0 0 0 0 0.0156863 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2034" result="effect2_innerShadow_4002_2034"/></filter><filter id="ioEifvj" width="3.754" height="4.672" x="12.725" y="9.326" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2034" stdDeviation=".5"/></filter><filter id="ibodtte" width="2.27" height="3.072" x="13.705" y="9.963" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2034" stdDeviation=".1"/></filter><filter id="iWgl7Ke" width="3.606" height="1.469" x="13.037" y="13.303" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2034" stdDeviation=".05"/></filter><filter id="i743C3b" width=".785" height=".694" x="16.279" y="9.611" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2034" stdDeviation=".05"/></filter><filter id="im0QJ3c" width=".889" height=".911" x="17.116" y="9.685" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2034" stdDeviation=".1"/></filter><filter id="ixXAIzx" width=".984" height="1.038" x="12.69" y="9.622" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2034" stdDeviation=".1"/></filter><filter id="iwlmzgb" width=".91" height=".703" x="11.938" y="9.602" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2034" stdDeviation=".05"/></filter><filter id="iOmt9Hc" width="2.693" height="1.592" x="16.099" y="7.379" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0588235 0 0 0 0 0.054902 0 0 0 0 0.0588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2034"/></filter><filter id="iJ0eVge" width="2.499" height="1.193" x="16.195" y="7.634" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2034" stdDeviation=".125"/></filter><filter id="iTqDVvc" width="2.693" height="1.592" x="10.988" y="7.379" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0588235 0 0 0 0 0.054902 0 0 0 0 0.0588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2034"/></filter><filter id="iWwA2iW" width="2.402" height="1.2" x="11.084" y="7.564" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2034" stdDeviation=".125"/></filter><filter id="imz7Ase" width="15.17" height="4.76" x="7.155" y="5.371" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.588235 0 0 0 0 0.47451 0 0 0 0 0.827451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2034"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.423529 0 0 0 0 0.329412 0 0 0 0 0.627451 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2034" result="effect2_innerShadow_4002_2034"/></filter><filter id="imWnWOr" width="9.99" height="2.47" x="9.739" y="2" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.670588 0 0 0 0 0.843137 0 0 0 0 0.835294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2034"/></filter><filter id="iMIvJnc" width="6.31" height="2.47" x="13.419" y="2" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".1"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.552941 0 0 0 0 0.890196 0 0 0 0 0.92549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2034"/></filter><linearGradient id="i1Pd52d" x1="14.735" x2="14.735" y1="16.438" y2="30.563" gradientUnits="userSpaceOnUse"><stop class="troaenb0e"/><stop offset="1" class="jsbk_hbmd"/></linearGradient><linearGradient id="it3vqkc" x1="10.637" x2="11.379" y1="18.219" y2="18.242" gradientUnits="userSpaceOnUse"><stop offset=".344" class="u9ri-jbkw"/><stop offset="1" class="j0xtzac4y"/></linearGradient><linearGradient id="igSiocc" x1="18.805" x2="18.012" y1="18.937" y2="18.937" gradientUnits="userSpaceOnUse"><stop class="ph46gxbvy"/><stop offset="1" class="s21zh4b3w"/></linearGradient><linearGradient id="iQD9PdN" x1="16.746" x2="17.254" y1="20.766" y2="19.984" gradientUnits="userSpaceOnUse"><stop class="sq-bwm1qa"/><stop offset="1" class="s21zh4b3w"/></linearGradient><linearGradient id="iZLtlOc" x1="8.242" x2="21.651" y1="9.948" y2="9.948" gradientUnits="userSpaceOnUse"><stop offset=".006" class="z-f4zlb4n"/><stop offset="1" class="z88owpbip"/></linearGradient><linearGradient id="iHff3Oe" x1="17.985" x2="17.985" y1="10.031" y2="9.742" gradientUnits="userSpaceOnUse"><stop class="q9u3nxbxg"/><stop offset="1" class="lvlvw7bgp"/></linearGradient><linearGradient id="i5m29vW" x1="7.769" x2="5.387" y1="27.844" y2="27.844" gradientUnits="userSpaceOnUse"><stop class="r5fk93cur"/><stop offset="1" class="bl3c3b0wv"/></linearGradient><linearGradient id="iUEJUid" x1="25.259" x2="23.652" y1="24.265" y2="24.265" gradientUnits="userSpaceOnUse"><stop class="ec1jnjbjz"/><stop offset="1" class="yd41utmlw"/></linearGradient><linearGradient id="igKMsTc" x1="25.442" x2="26.863" y1="15.852" y2="14.43" gradientUnits="userSpaceOnUse"><stop class="avgmeibok"/><stop offset="1" class="lasn3qwok"/></linearGradient><linearGradient id="iOKq7lc" x1="26.159" x2="22.131" y1="28.063" y2="28.063" gradientUnits="userSpaceOnUse"><stop offset=".146" class="v5rheyc4i"/><stop offset=".861" class="j1qr75obr"/></linearGradient><linearGradient id="ivhW0ze" x1="22.748" x2="24.458" y1="26.08" y2="26.08" gradientUnits="userSpaceOnUse"><stop class="vx-77wbda"/><stop offset="1" class="r0p9vfbnw"/></linearGradient><linearGradient id="iNT2srd" x1="22.67" x2="24.38" y1="27.385" y2="27.385" gradientUnits="userSpaceOnUse"><stop class="vx-77wbda"/><stop offset="1" class="r0p9vfbnw"/></linearGradient><linearGradient id="iflwwud" x1="22.748" x2="24.458" y1="28.689" y2="28.689" gradientUnits="userSpaceOnUse"><stop class="vx-77wbda"/><stop offset="1" class="r0p9vfbnw"/></linearGradient><linearGradient id="i9b7Qne" x1="11.1" x2="9.273" y1="10.643" y2="10.767" gradientUnits="userSpaceOnUse"><stop class="tm3a41odp"/><stop offset="1" class="r8mrl8bdh"/></linearGradient><linearGradient id="iSrunrb" x1="9.7" x2="11.033" y1="11.846" y2="11.717" gradientUnits="userSpaceOnUse"><stop offset=".305" class="p09lm7njz"/><stop offset="1" class="qvxq5kbmq"/></linearGradient><linearGradient id="ir5i89O" x1="14.869" x2="14.869" y1="7.192" y2="7.54" gradientUnits="userSpaceOnUse"><stop class="zkm-wz_md"/><stop offset="1" class="hybgezb9r"/></linearGradient><linearGradient id="i5RNXhc" x1="9.996" x2="12.888" y1="10.462" y2="5.326" gradientUnits="userSpaceOnUse"><stop class="kyzs66gfi"/><stop offset="1" class="zsx4vmb0f"/></linearGradient><linearGradient id="iI58sCd" x1="9.075" x2="9.87" y1="9.597" y2="9.453" gradientUnits="userSpaceOnUse"><stop offset=".171" class="z0tfc7bnd"/><stop offset="1" class="vmw-awokf"/></linearGradient><linearGradient id="id8955d" x1="15.775" x2="14.841" y1="11.681" y2="11.77" gradientUnits="userSpaceOnUse"><stop class="af2d-kbww"/><stop offset="1" class="fkbu2fb2z"/></linearGradient><linearGradient id="iV0qdCb" x1="14.84" x2="14.84" y1="12.774" y2="12.346" gradientUnits="userSpaceOnUse"><stop class="y8u9aob3m"/><stop offset="1" class="w22vs7beb"/></linearGradient><linearGradient id="inYxWIc" x1="14.84" x2="14.84" y1="10.163" y2="10.786" gradientUnits="userSpaceOnUse"><stop class="au2s26bkj"/><stop offset="1" class="e0f0u6bhi"/></linearGradient><linearGradient id="ixJLKSd" x1="13.643" x2="13.96" y1="14.334" y2="13.503" gradientUnits="userSpaceOnUse"><stop class="uhvh9szrw"/><stop offset="1" class="ges79ib3m"/></linearGradient><linearGradient id="ivjr05J" x1="17.786" x2="17.474" y1="10.103" y2="10.295" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iilVjNe" x1="13.405" x2="13.092" y1="10.103" y2="10.295" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="icBL91d" x1="6.356" x2="7.059" y1="7.633" y2="6.703" gradientUnits="userSpaceOnUse"><stop class="qo28zhh9b"/><stop offset="1" class="yhrc8s1zu"/></linearGradient><linearGradient id="ibvcPeT" x1="22.462" x2="22.462" y1="6" y2="8.01" gradientUnits="userSpaceOnUse"><stop class="ott3_jqut"/><stop offset="1" class="l8p6brbrs"/></linearGradient><linearGradient id="iE9kqQd" x1="15.051" x2="15.051" y1="7.33" y2="7.174" gradientUnits="userSpaceOnUse"><stop class="j3h4o1d7b"/><stop offset="1" class="lo1ogpbbw"/></linearGradient><linearGradient id="ivqY3ab" x1="6.787" x2="7.841" y1="7.125" y2="7.125" gradientUnits="userSpaceOnUse"><stop class="it1_ig0bc"/><stop offset="1" class="qgmif2bih"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-factory-worker-light" /></template>
<style>
.a02_cfb_b {
  stop-color: var(--svg-color--c8887e, #C8887E);
}

.a1i_j40xh {
  fill: var(--svg-color--3c77cf, #3C77CF);
  d: path("M18.804 16.276v4.576c.003.26-.023.578-.25.718c-.233.145-.58-.018-.742-.14l-2.5-1.766v-4.15c1.228.064 2.403.329 3.492.762");
}

.a424ylq9x {
  fill: var(--svg-color--3674c9, #3674C9);
  d: path("M10.812 16.221v4.63c-.002.26.024.579.25.72c.234.144.581-.019.743-.141l2.5-1.766v-4.156a11 11 0 0 0-3.493.713");
}

.ac3zfwb5z {
  fill: var(--svg-color--8cf5ff, #8CF5FF);
  d: path("m16.169 2l-2.45 2.37h5.45c.31 0 .56-.25.56-.56V2.19c-.4-.12-.83-.19-1.27-.19z");
}

.af2d-kbww {
  stop-color: var(--svg-color--ffdfc7, #FFDFC7);
}

.al5ad0b-q {
  stroke: var(--svg-color--353535, #353535);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M11.459 8.39c.208-.192.8-.518 1.651-.438");
}

.alkmbvb7w {
  stop-color: var(--svg-color--d5a89f, #D5A89F);
}

.amp4-rn4i {
  fill: var(--svg-color--100414, #100414);
  d: path("m19.642 4.274l.428.212c.748.372 1.176 1.223 1.015 2.126l-.588 3.03c-.052.312-.259.523-.57.53c.036-.501.069-1.31.082-1.439c.043-.431-.025-.558-.42-.952c-.214-.212-.375-.531-.375-.85v-.85c0-.266-.213-.479-.427-.532c-.642-.16-1.978-.425-3.902-.425s-3.26.266-3.902.425a.52.52 0 0 0-.428.531v.85c0 .32-.107.639-.374.851l-.16.16c-.214.16-.322.492-.322.758c.014.155.035 1.048.059 1.419a.63.63 0 0 1-.592-.53l-.588-3.03c-.107-.85.32-1.7 1.069-2.072c1.01-.443 1.378-1.115 2.191-1.807c.588-.531 1.443-.69 2.192-.319a2.93 2.93 0 0 0 1.657 0c.801-.266 1.71-.053 2.351.532l.802.797c.214.266.481.425.802.585");
}

.aszpk2bre {
  stop-color: var(--svg-color--f7ceb9, #F7CEB9);
  stop-opacity: 0;
}

.au2s26bkj {
  stop-color: var(--svg-color--e8bba8, #E8BBA8);
}

.avgmeibok {
  stop-color: var(--svg-color--73d7ff, #73D7FF);
}

.b0svlhbnq {
  d: path("M16.948 9.762c.063.085-.07.188-.22.3c-.15.113-.262.192-.325.107c-.064-.084.007-.244.158-.357c.15-.112.323-.135.387-.05");
}

.b175b4n1p {
  d: path("m14.459 10.445l-.53 1.693a.537.537 0 0 0 .52.697h.783a.54.54 0 0 0 .518-.697l-.53-1.694c-.113-.375-.642-.375-.761 0");
}

.b4rjnnb6m {
  stop-color: var(--svg-color--ffe0c3, #FFE0C3);
}

.b570nlb5r {
  stop-color: var(--svg-color--ffd1bb, #FFD1BB);
  stop-opacity: 0;
}

.bbqwceq4e {
  stop-color: var(--svg-color--3878e5, #3878E5);
}

.bbyb_mbsk {
  stop-color: var(--svg-color--664842, #664842);
}

.bgp-eqwmb {
  stop-color: var(--svg-color--ffe0c3, #FFE0C3);
  stop-opacity: 0;
}

.bl3c3b0wv {
  stop-color: var(--svg-color--3e6fc6, #3E6FC6);
  stop-opacity: 0;
}

.bzs2-ddka {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M22.748 26.002h1.797");
}

.ck410xb1o {
  stop-color: var(--svg-color--ffe336, #FFE336);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cwr7ndbvn {
  d: path("M17.013 9.574a.89.89 0 0 1 .857 1.123h-1.718a.893.893 0 0 1 .86-1.124");
}

.d7sh3eboe {
  stop-color: var(--svg-color--26386d, #26386D);
}

.d7zypgbet {
  stop-color: var(--svg-color--e57d1c, #E57D1C);
  stop-opacity: 0;
}

.dkc_aibit {
  stop-color: var(--svg-color--d49da0, #D49DA0);
  stop-opacity: 0;
}

.dlrwjtb7t {
  d: path("M9.758 10.118A30 30 0 0 1 9.7 8.685c0-.266.107-.585.32-.744l.161-.16c.267-.212.374-.531.374-.85v-.85c0-.266.16-.479.428-.532c.641-.16 1.977-.425 3.902-.425c1.924 0 3.26.266 3.902.425c.213.053.427.266.427.532v.85c0 .319.16.638.375.85c.5.351.469.544.427.957c-.013.128-.053 1.19-.089 1.435l-.265 3.944c-.16 1.764-1.546 2.993-3.199 2.993h-3.199c-1.706 0-3.04-1.23-3.2-2.993z");
}

.dn7nvsb1v {
  stop-color: var(--svg-color--806879, #806879);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e0f0u6bhi {
  stop-color: var(--svg-color--e8bba8, #E8BBA8);
  stop-opacity: 0;
}

.e5n7-cbky {
  d: path("M14.739 15.5c-6.07 0-11 4.92-11 11V30h20.99a1 1 0 0 0 1-1v-2.5c0-6.08-4.92-11-10.99-11");
}

.ec1jnjbjz {
  stop-color: var(--svg-color--675479, #675479);
}

.ee8yo8bto {
  stop-color: var(--svg-color--806879, #806879);
  stop-opacity: 0;
}

.emv4mnw3h {
  fill: var(--svg-color--e1ab97, #E1AB97);
  d: path("m14.459 10.445l-.53 1.693a.537.537 0 0 0 .52.697h.783a.54.54 0 0 0 .518-.697l-.53-1.694c-.113-.375-.642-.375-.761 0");
}

.euj6xpbnj {
  stop-color: var(--svg-color--ffb42c, #FFB42C);
}

.f165ur9pt {
  stop-color: var(--svg-color--dea69b, #DEA69B);
  stop-opacity: 0;
}

.f2dz70yyi {
  stop-color: var(--svg-color--ffd93a, #FFD93A);
  stop-opacity: 0;
}

.fbjx3y-qb {
  d: path("M25.449 23.1c.55 0 1 .45 1 1v2.29h-2V24.1c0-.55.45-1 1-1");
}

.fkbu2fb2z {
  stop-color: var(--svg-color--ffdfc7, #FFDFC7);
  stop-opacity: 0;
}

.fo2kykbuh {
  stop-color: var(--svg-color--daa39b, #DAA39B);
  stop-opacity: 0;
}

.fop80r8ws {
  stop-color: var(--svg-color--c79175, #C79175);
}

.ft5dv1b6b {
  fill: none;
}

.g67_t8fua {
  stop-color: var(--svg-color--8d535a, #8D535A);
}

.g7oiw84_l {
  d: path("M14.79 18.103c-1.239 0-2.239-.948-2.239-2.122v-2.638c0-1.164 1-2.112 2.24-2.112c1.239 0 2.239.948 2.239 2.122v2.638c-.011 1.164-1.011 2.112-2.24 2.112");
}

.g9arp8b8o {
  d: path("M22.819 8.01h-.713a.49.49 0 0 1-.49-.49V6.49c-.01-.27.21-.49.49-.49h.713c.27 0 .49.22.49.49v1.02c0 .28-.22.5-.49.5");
}

.ges79ib3m {
  stop-color: var(--svg-color--e3b2a8, #E3B2A8);
  stop-opacity: 0;
}

.ghdrqrbfe {
  stop-color: var(--svg-color--e57d1c, #E57D1C);
}

.grd6gl_rz {
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M13.483 13.476a.2.2 0 0 0-.242.042a.186.186 0 0 0-.02.239c.343.519.94.865 1.619.865c.68 0 1.276-.346 1.619-.865a.19.19 0 0 0-.02-.241a.2.2 0 0 0-.241-.04h-.001a2.9 2.9 0 0 1-1.357.322c-.498 0-.965-.117-1.357-.322Z");
}

.h1w1jc3ne {
  stop-color: var(--svg-color--1f1d20, #1F1D20);
}

.h24jl46mm {
  stroke: var(--svg-color--353535, #353535);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M18.32 8.452c-.477-.336-1.087-.492-1.75-.43");
}

.h6pwsobze {
  stop-color: var(--svg-color--b67999, #B67999);
}

.hchnd0bsx {
  stop-color: var(--svg-color--ffb42c, #FFB42C);
  stop-opacity: 0;
}

.hdusbzsjg {
  fill: var(--svg-color--000, #000);
  d: path("M16.504 10.463c0-.283.226-.51.51-.51a.507.507 0 0 1 .452.744h-.901a.46.46 0 0 1-.061-.234");
}

.hh437879c {
  cx: 19.589px;
  cy: 10.729px;
  r: 0.991px;
}

.hnxygroex {
  stop-color: var(--svg-color--624b78, #624B78);
  stop-opacity: 0;
}

.hybgezb9r {
  stop-color: var(--svg-color--aa707a, #AA707A);
  stop-opacity: 0;
}

.hye_w5bmk {
  stop-color: var(--svg-color--ffd93a, #FFD93A);
}

.hyj07d54k {
  d: path("M17.805 10.346a.84.84 0 0 0-.23-.461l-.26.284l.118.227z");
}

.i4ysa-bno {
  cx: 10.109px;
  cy: 10.729px;
  r: 1.664px;
}

.i8i6txbig {
  cx: 10.109px;
  cy: 10.729px;
  r: 0.991px;
}

.i9v5wucat {
  d: path("M12.661 9.574a.89.89 0 0 0-.856 1.123h1.717a1 1 0 0 0 .033-.234a.895.895 0 0 0-.894-.89");
}

.ig-3c1b3u {
  stop-color: var(--svg-color--976763, #976763);
}

.ii_vcdblz {
  fill: var(--svg-color--1e6dc3, #1E6DC3);
  d: path("M10.76 16.494v4.63c-.002.26.024.579.25.72c.234.144.581-.02.743-.142l2.5-1.765V15.78a11 11 0 0 0-3.492.713");
}

.it1_ig0bc {
  stop-color: var(--svg-color--57525e, #57525E);
}

.iv7bj_baj {
  stop-color: var(--svg-color--4680db, #4680DB);
  stop-opacity: 0;
}

.ixw-oi7aq {
  stop-color: var(--svg-color--3d3248, #3D3248);
}

.iycy_sbnz {
  d: path("M7.366 8.01h-.707a.49.49 0 0 1-.49-.49V6.49c-.01-.27.21-.49.49-.49h.707c.27 0 .49.22.49.49v1.02c0 .28-.22.5-.49.5");
}

.j0xtzac4y {
  stop-color: var(--svg-color--4d79b0, #4D79B0);
  stop-opacity: 0;
}

.j1qr75obr {
  stop-color: var(--svg-color--d8a696, #D8A696);
}

.j3h4o1d7b {
  stop-color: var(--svg-color--391f48, #391F48);
}

.jase_0f7h {
  stop-color: var(--svg-color--88014e, #88014E);
}

.javsik_yi {
  fill: var(--svg-color--f3d8ed, #F3D8ED);
  d: path("m15.659 19.69l-.65.58c-.16.14-.39.14-.55 0l-.65-.58a3.45 3.45 0 0 1-1.14-2.55v-3.09a2.07 2.07 0 0 1 2.07-2.05c1.14 0 2.06.92 2.06 2.06v3.09c-.01.97-.42 1.89-1.14 2.54");
}

.jht53ab1w {
  cx: 12.393px;
  cy: 9.954px;
  rx: 0.388px;
  ry: 0.196px;
}

.jio9fxbvr {
  fill: var(--svg-color--202020, #202020);
  fill-rule: evenodd;
  d: path("M16.614 8.53c.717-.066 1.177.214 1.288.317a.47.47 0 1 0 .638-.693c-.305-.28-1.028-.653-2.014-.56a.47.47 0 0 0 .087.937");
}

.jl9xgibbw {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M16.948 9.762c.063.085-.07.188-.22.3c-.15.113-.262.192-.325.107c-.064-.084.007-.244.158-.357c.15-.112.323-.135.387-.05");
}

.jsbk_hbmd {
  stop-color: var(--svg-color--3e80ff, #3E80FF);
}

.jwqe_jbgo {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.22 9.303c.65 0 1.2.449 1.35 1.055a.273.273 0 0 1-.268.34H16.08a.23.23 0 0 1-.227-.271a1.39 1.39 0 0 1 1.366-1.124");
}

.kc9q3mbff {
  fill: var(--svg-color--c6c6c6, #C6C6C6);
  d: path("m26.449 14.92l-.71-.71l-1.42 1.42c-.38.38-.59.89-.59 1.42v5.54h1v-5.74c0-.14.05-.27.15-.37z");
}

.kg3uvq1fk {
  stop-color: var(--svg-color--d1978d, #D1978D);
}

.ky_dg6bhp {
  stop-color: var(--svg-color--b0b0b0, #B0B0B0);
}

.kyknafbgp {
  cx: 12.393px;
  cy: 9.954px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.388px;
  ry: 0.196px;
}

.kyzs66gfi {
  stop-color: var(--svg-color--e07027, #E07027);
}

.l8p6brbrs {
  stop-color: var(--svg-color--38234f, #38234F);
}

.lasn3qwok {
  stop-color: var(--svg-color--93ffff, #93FFFF);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lkgptrbsy {
  stop-color: var(--svg-color--b97985, #B97985);
  stop-opacity: 0;
}

.lo1ogpbbw {
  stop-color: var(--svg-color--391f48, #391F48);
  stop-opacity: 0;
}

.lt_b3wboz {
  d: path("m3.769 30l4-.02l-.06-11.94a11 11 0 0 0-3.563 5.482c-.262.948-.4 1.947-.397 2.978z");
}

.ltwsa8bld {
  d: path("M7.757 10.031c.21-.47 1.98-4.06 7.03-4.06c5.6 0 7.04 4.06 7.04 4.06h.47c.27 0 .48-.22.48-.48v-3.24c0-2.36-1.91-4.27-4.27-4.27h-7.45a4.253 4.253 0 0 0-4.27 4.26v3.24c0 .27.21.49.48.49z");
}

.lvlvw7bgp {
  stop-color: var(--svg-color--513a64, #513A64);
  stop-opacity: 0;
}

.m1_q07_me {
  stop-color: var(--svg-color--6899f0, #6899F0);
}

.m3dxw5b4u {
  d: path("M10.812 16.221v4.63c-.002.26.024.579.25.72c.234.144.581-.019.743-.141l2.5-1.766v-4.156a11 11 0 0 0-3.493.713");
}

.m4mhe8bqv {
  stop-color: var(--svg-color--4f94d3, #4F94D3);
  stop-opacity: 0;
}

.m8_l30tsr {
  stop-color: var(--svg-color--2a3765, #2A3765);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mguibccfx {
  stop-color: var(--svg-color--2a193d, #2A193D);
}

.mrnsdcbqx {
  stop-color: var(--svg-color--ffddc7, #FFDDC7);
  stop-opacity: 0;
}

.mx797o4di {
  stop-color: var(--svg-color--4086f6, #4086F6);
}

.n26l-i5_v {
  stop-color: var(--svg-color--d1978d, #D1978D);
  stop-opacity: 0;
}

.na59ribzw {
  d: path("M28.245 13.16c.081-.326-.151-.554-.478-.472c-.878.18-2.296.406-2.714.954c-.571.613-.55 1.582.03 2.184a1.577 1.577 0 0 0 2.256.01c.503-.512.733-1.836.906-2.676");
}

.ndlc49hkf {
  d: path("M21.974 6.741H7.744v3.29h14.23z");
}

.ny0rq0bux {
  stop-color: var(--svg-color--d6a195, #D6A195);
}

.nzjwoybta {
  stop-color: var(--svg-color--675878, #675878);
  stop-opacity: 0;
}

.o0aif1l1c {
  stop-color: var(--svg-color--d3968c, #D3968C);
  stop-opacity: 0;
}

.o12zmvuzn {
  d: path("M20.756 7.641a7.5 7.5 0 0 0-2.31-1.49c-1.09-.45-2.32-.68-3.66-.68c-1.22 0-2.36.2-3.38.6c-.84.33-1.61.79-2.28 1.38c-1.16 1-1.69 2.07-1.83 2.37c-.03.07-.04.14-.04.21h.5c.21-.47 1.98-4.06 7.03-4.06c5.6 0 7.04 4.06 7.04 4.06h.5c0-.06-.01-.11-.03-.17c-.01-.05-.41-1.14-1.54-2.22");
}

.o1gf6ebie {
  stop-color: var(--svg-color--cf89ac, #CF89AC);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.odxs-cbnv {
  stop-color: var(--svg-color--ad7062, #AD7062);
}

.ojb-ttbmo {
  fill: var(--svg-color--c4ffff, #C4FFFF);
  d: path("M10.299 4.37h8.87c.31 0 .56-.25.56-.56V2.19c-.4-.12-.83-.19-1.27-.19h-7.45c-.44 0-.87.07-1.27.19v1.62c0 .31.25.56.56.56");
}

.oool1tdti {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M22.748 28.611h1.797");
}

.ott3_jqut {
  stop-color: var(--svg-color--534065, #534065);
}

.p09lm7njz {
  stop-color: var(--svg-color--e4aa96, #E4AA96);
}

.p3_97vb4n {
  stop-color: var(--svg-color--465e8a, #465E8A);
  stop-opacity: 0;
}

.p64oiyb7x {
  stop-color: var(--svg-color--55406a, #55406A);
}

.p7prpqhjw {
  stop-color: var(--svg-color--5da7f2, #5DA7F2);
}

.ph46gxbvy {
  stop-color: var(--svg-color--4f8dd8, #4F8DD8);
}

.pi6c47yng {
  d: path("M21.729 18.01v11.98h3a1 1 0 0 0 1-1v-2.5c0-3.41-1.55-6.46-4-8.48");
}

.pjsi77bhr {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M22.67 27.307h1.797");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.q1_4ocb7a {
  fill: var(--svg-color--202020, #202020);
  fill-rule: evenodd;
  d: path("M13.066 8.53c-.717-.066-1.177.214-1.288.317a.47.47 0 1 1-.638-.693c.305-.28 1.028-.653 2.014-.56a.47.47 0 0 1-.088.937");
}

.q7l79-2rh {
  stop-color: var(--svg-color--f7ceb9, #F7CEB9);
}

.q9u3nxbxg {
  stop-color: var(--svg-color--513a64, #513A64);
}

.qeh0r4bjq {
  stop-color: var(--svg-color--ffe336, #FFE336);
  stop-opacity: 0;
}

.qgmif2bih {
  stop-color: var(--svg-color--57525e, #57525E);
  stop-opacity: 0;
}

.qo28zhh9b {
  stop-color: var(--svg-color--3a2252, #3A2252);
}

.qtzewq2gr {
  d: path("M22.13 25.326c0-.402.326-.732.727-.732h2.392a1.2 1.2 0 0 1 1.2 1.2V29a1 1 0 0 1-1 1h-2.592a.731.731 0 0 1-.319-1.389a.735.735 0 0 1 0-1.314a.735.735 0 0 1 0-1.314a.74.74 0 0 1-.407-.657");
}

.qv8wc6zla {
  d: path("m26.449 14.92l-.71-.71l-1.42 1.42c-.38.38-.59.89-.59 1.42v5.54h1v-5.74c0-.14.05-.27.15-.37z");
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qvxq5kbmq {
  stop-color: var(--svg-color--e4aa96, #E4AA96);
  stop-opacity: 0;
}

.qwfi8obtf {
  stop-color: var(--svg-color--b0b0b0, #B0B0B0);
  stop-opacity: 0;
}

.qyg3b1b6n {
  stop-color: var(--svg-color--6f5b84, #6F5B84);
}

.r0p9vfbnw {
  stop-color: var(--svg-color--ca8b73, #CA8B73);
  stop-opacity: 0;
}

.r5fk93cur {
  stop-color: var(--svg-color--2869c1, #2869C1);
}

.r8mrl8bdh {
  stop-color: var(--svg-color--b27263, #B27263);
}

.rj390kbfq {
  d: path("M13.474 10.359c0-.288-.234-.48-.297-.537l-.287.278l.176.36z");
}

.rq76sybla {
  d: path("M18.804 16.276v4.576c.003.26-.023.578-.25.718c-.233.145-.58-.018-.742-.14l-2.5-1.766v-4.15c1.228.064 2.403.329 3.492.762");
}

.rtj8_6bqg {
  stop-color: var(--svg-color--2a3765, #2A3765);
}

.s1a8ycb7r {
  stop-color: var(--svg-color--362d41, #362D41);
}

.s1rw4px-b {
  stop-color: var(--svg-color--465e8a, #465E8A);
}

.s21zh4b3w {
  stop-color: var(--svg-color--3d78d0, #3D78D0);
  stop-opacity: 0;
}

.s5pm96b_v {
  stop-color: var(--svg-color--3578e5, #3578E5);
  stop-opacity: 0;
}

.sb1phf9zd {
  d: path("M20.979 4.68H8.719v2.65h12.26z");
}

.sq-bwm1qa {
  stop-color: var(--svg-color--1f54c5, #1F54C5);
}

.t40345qox {
  stop-color: var(--svg-color--ffddc7, #FFDDC7);
}

.t4clght5m {
  stop-color: var(--svg-color--ffce2c, #FFCE2C);
  stop-opacity: 0;
}

.t4vmfmb4r {
  d: path("M14.84 13.848c-.506 0-.981-.12-1.38-.327c-.137-.07-.284.084-.198.208c.334.506.916.843 1.578.843s1.244-.337 1.577-.843c.086-.13-.06-.278-.197-.208c-.4.208-.87.327-1.38.327");
}

.t8ye-ilvp {
  stop-color: var(--svg-color--7b51c6, #7B51C6);
}

.tizux9w7p {
  stop-color: var(--svg-color--3877cc, #3877CC);
  stop-opacity: 0;
}

.tj2vllbvr {
  stop-color: var(--svg-color--f3c6af, #F3C6AF);
}

.tm3a41odp {
  stop-color: var(--svg-color--bb7c70, #BB7C70);
}

.tpyby8h1l {
  stop-color: var(--svg-color--814b5f, #814B5F);
}

.tr80mtbrp {
  fill: var(--svg-color--000, #000);
  d: path("M13.17 10.463a.507.507 0 0 0-.508-.51a.507.507 0 0 0-.453.744h.901a.5.5 0 0 0 .06-.234");
}

.troaenb0e {
  stop-color: var(--svg-color--428ef7, #428EF7);
}

.u_qgni50q {
  stop-color: var(--svg-color--7d4f4e, #7D4F4E);
}

.u-q3e7b8s {
  d: path("m15.659 19.69l-.65.58c-.16.14-.39.14-.55 0l-.65-.58a3.45 3.45 0 0 1-1.14-2.55v-3.09a2.07 2.07 0 0 1 2.07-2.05c1.14 0 2.06.92 2.06 2.06v3.09c-.01.97-.42 1.89-1.14 2.54");
}

.u9ri-jbkw {
  stop-color: var(--svg-color--547eb3, #547EB3);
}

.ue1gv6enh {
  d: path("M25.259 25.94h-2.05v-3c0-.19.16-.35.35-.35h1.35c.19 0 .35.16.35.35z");
}

.uf734fbqu {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.455 9.303c-.65 0-1.2.449-1.35 1.055a.273.273 0 0 0 .267.34h2.223a.23.23 0 0 0 .226-.271a1.396 1.396 0 0 0-1.366-1.124");
}

.uhvh9szrw {
  stop-color: var(--svg-color--e3b2a8, #E3B2A8);
}

.uit74mbey {
  fill: var(--svg-color--ffa91b, #FFA91B);
  d: path("m19.642 4.274l.428.212c.748.372 1.176 1.223 1.015 2.126l-.588 3.03c-.052.312-.259.523-.57.53c.036-.501.069-1.31.082-1.439c.043-.431-.025-.558-.42-.952c-.214-.212-.375-.531-.375-.85v-.85c0-.266-.213-.479-.427-.532c-.642-.16-1.978-.425-3.902-.425s-3.26.266-3.902.425a.52.52 0 0 0-.428.531v.85c0 .32-.107.639-.374.851l-.16.16c-.214.16-.322.492-.322.758c.014.155.035 1.048.059 1.419a.63.63 0 0 1-.592-.53l-.588-3.03c-.107-.85.32-1.7 1.069-2.072c1.01-.443 1.378-1.115 2.191-1.807c.588-.531 1.443-.69 2.192-.319a2.93 2.93 0 0 0 1.657 0c.801-.266 1.71-.053 2.351.532l.802.797c.214.266.481.425.802.585");
}

.uzac_3qef {
  stop-color: var(--svg-color--ffd1bb, #FFD1BB);
}

.v5rheyc4i {
  stop-color: var(--svg-color--ffd7bf, #FFD7BF);
}

.vbc9nqbss {
  fill: var(--svg-color--1e64bd, #1E64BD);
  d: path("M21.729 18.01v11.98h3a1 1 0 0 0 1-1v-2.5c0-3.41-1.55-6.46-4-8.48");
}

.vczswwwcd {
  fill: var(--svg-color--fff, #fff);
  d: path("M26.151 15.597a.85.85 0 1 0 0-1.7a.85.85 0 0 0 0 1.7");
}

.vmw-awokf {
  stop-color: var(--svg-color--372e2c, #372E2C);
  stop-opacity: 0;
}

.vni43obah {
  stop-color: var(--svg-color--d3968c, #D3968C);
}

.vx-77wbda {
  stop-color: var(--svg-color--ca8b73, #CA8B73);
}

.w22vs7beb {
  stop-color: var(--svg-color--d89793, #D89793);
  stop-opacity: 0;
}

.w4rn2oska {
  fill: var(--svg-color--d69790, #D69790);
  d: path("m14.566 10.607l-.818 1.694c-.101.348.142.697.486.697h.735c.345 0 .588-.354.487-.697l-.497-1.694c-.107-.375-.282-.375-.393 0");
}

.wct4qccbg {
  cx: 19.589px;
  cy: 10.729px;
  r: 1.664px;
}

.wg0u_rd0m {
  stop-color: var(--svg-color--c49888, #C49888);
}

.wn92vfpti {
  stop-color: var(--svg-color--ffce2c, #FFCE2C);
}

.wp6rq3sqk {
  stop-color: var(--svg-color--6e5981, #6E5981);
}

.x9-b3hbfy {
  fill: var(--svg-color--1e6dc3, #1E6DC3);
  d: path("M18.365 16.768v4.575c.002.26-.024.578-.25.719c-.234.145-.581-.018-.743-.14l-2.5-1.766v-4.15c1.229.064 2.403.328 3.492.762");
}

.xuipl1bei {
  stop-color: var(--svg-color--dea69b, #DEA69B);
}

.y13139flk {
  stop-color: var(--svg-color--dd9ead, #DD9EAD);
}

.y66dh_b5l {
  stop-color: var(--svg-color--675878, #675878);
}

.y8u9aob3m {
  stop-color: var(--svg-color--d89793, #D89793);
}

.ybrylxbuq {
  d: path("m19.642 4.274l.428.212c.748.372 1.176 1.223 1.015 2.126l-.588 3.03c-.052.312-.259.523-.57.53c.036-.501.069-1.31.082-1.439c.043-.431-.025-.558-.42-.952c-.214-.212-.375-.531-.375-.85v-.85c0-.266-.213-.479-.427-.532c-.642-.16-1.978-.425-3.902-.425s-3.26.266-3.902.425a.52.52 0 0 0-.428.531v.85c0 .32-.107.639-.374.851l-.16.16c-.214.16-.322.492-.322.758c.014.155.035 1.048.059 1.419a.63.63 0 0 1-.592-.53l-.588-3.03c-.107-.85.32-1.7 1.069-2.072c1.01-.443 1.378-1.115 2.191-1.807c.588-.531 1.443-.69 2.192-.319a2.93 2.93 0 0 0 1.657 0c.801-.266 1.71-.053 2.351.532l.802.797c.214.266.481.425.802.585");
}

.yd41utmlw {
  stop-color: var(--svg-color--32263f, #32263F);
}

.yhrc8s1zu {
  stop-color: var(--svg-color--31263f, #31263F);
}

.ypv_kpaja {
  stop-color: var(--svg-color--4680db, #4680DB);
}

.ysugf1aqs {
  stop-color: var(--svg-color--b97985, #B97985);
}

.yxyzwolxt {
  stop-color: var(--svg-color--1f1d20, #1F1D20);
  stop-opacity: 0;
}

.yytwt1d8s {
  stop-color: var(--svg-color--362d41, #362D41);
  stop-opacity: 0;
}

.yzaj_tb_p {
  stop-color: var(--svg-color--ffdcc0, #FFDCC0);
}

.z-f4zlb4n {
  stop-color: var(--svg-color--251229, #251229);
}

.z0tfc7bnd {
  stop-color: var(--svg-color--372e2c, #372E2C);
}

.z2op5sb3v {
  stop-color: var(--svg-color--b28477, #B28477);
}

.z2rllvutr {
  stop-color: var(--svg-color--8c68d5, #8C68D5);
}

.z88owpbip {
  stop-color: var(--svg-color--24132c, #24132C);
}

.zkm-wz_md {
  stop-color: var(--svg-color--aa707a, #AA707A);
}

.zn-qjxbde {
  stop-color: var(--svg-color--86004d, #86004D);
}

.zsx4vmb0f {
  stop-color: var(--svg-color--e07027, #E07027);
  stop-opacity: 0;
}

</style>
