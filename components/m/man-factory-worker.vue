<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iXCDk9d)"><path fill="url(#i1Pd52d)" class="e5n7-cbky"/><path fill="url(#iM6rPqd)" class="e5n7-cbky"/></g><g filter="url(#iHh8cSd)"><path class="ii_vcdblz"/></g><g filter="url(#iHToNNx)"><path class="x9-b3hbfy"/></g><g filter="url(#iSJjM5x)"><path class="a424ylq9x"/><path fill="url(#i7bctJc)" class="m3dxw5b4u"/><path fill="url(#izNqDsc)" class="m3dxw5b4u"/><path fill="url(#it3vqkc)" class="m3dxw5b4u"/></g><path class="a1i_j40xh"/><path fill="url(#igSiocc)" class="rq76sybla"/><path fill="url(#iQD9PdN)" class="rq76sybla"/><path fill="url(#ifkmApd)" class="rq76sybla"/><path fill="url(#iUzRGHc)" class="rq76sybla"/><path fill="url(#iZLtlOc)" class="ndlc49hkf"/><path fill="url(#iHff3Oe)" class="ndlc49hkf"/><path fill="url(#iFGxoeb)" class="lt_b3wboz"/><path fill="url(#i5m29vW)" class="lt_b3wboz"/><path class="vbc9nqbss"/><path fill="url(#iPRoNnL)" class="pi6c47yng"/><path class="javsik_yi"/><path fill="url(#iOgo57h)" class="u-q3e7b8s"/><path fill="url(#iZjLroc)" class="js7qsnbrb"/><path fill="url(#iw3Aprr)" class="js7qsnbrb"/><path fill="url(#iXmKX4d)" class="js7qsnbrb"/><path fill="url(#inGd3Ee)" class="fbjx3y-qb"/><g filter="url(#i8dAUrc)"><path class="kc9q3mbff"/><path fill="url(#ifFH9Wc)" class="qv8wc6zla"/></g><path fill="url(#iNUFY3c)" class="ue1gv6enh"/><path fill="url(#ilud8bb)" class="ue1gv6enh"/><g filter="url(#ixv1Amb)"><path fill="url(#igKMsTc)" class="na59ribzw"/></g><path class="vczswwwcd"/><g filter="url(#iR2YZJc)"><path fill="url(#iR8tYHf)" class="qtzewq2gr"/><path fill="url(#iUsyeEb)" class="qtzewq2gr"/><path fill="url(#i9vzj2O)" class="qtzewq2gr"/><path fill="url(#ijLycSc)" class="qtzewq2gr"/><path fill="url(#iXao1Dd)" class="qtzewq2gr"/></g><g filter="url(#i7Mfa6b)"><path stroke="url(#idYJate)" class="b_8rrzerq"/></g><g filter="url(#iBXe37z)"><path stroke="url(#iSCMlmz)" class="fuw705b0o"/></g><g filter="url(#iyWMnFW)"><path stroke="url(#iVDbSlO)" class="gpbr0qbhd"/></g><circle fill="url(#iNK15Nc)" class="i4ysa-bno"/><g filter="url(#iHKVMLe)"><circle fill="url(#iOwVpEe)" class="i8i6txbig"/></g><g filter="url(#i7dZ9Ae)"><circle fill="url(#iM934oc)" class="wct4qccbg"/></g><g filter="url(#iWD6jDx)"><circle class="s2toruu7e"/></g><path fill="url(#iTnnaLm)" class="dlrwjtb7t"/><path fill="url(#iNsMHuc)" class="dlrwjtb7t"/><path fill="url(#iJzxHWd)" class="dlrwjtb7t"/><path fill="url(#ifMf5Tc)" class="dlrwjtb7t"/><path fill="url(#iT70dge)" class="dlrwjtb7t"/><path fill="url(#imGI7zd)" class="dlrwjtb7t"/><path fill="url(#ixYkibb)" class="dlrwjtb7t"/><path fill="url(#igYrhEv)" class="dlrwjtb7t"/><g filter="url(#iioabKh)"><path class="uit74mbey"/><path fill="url(#is4oeLb)" class="ybrylxbuq"/><path fill="url(#i5RNXhc)" class="ybrylxbuq"/><path fill="url(#iLS37Ld)" class="ybrylxbuq"/><path fill="url(#iK5yQFd)" class="ybrylxbuq"/><path fill="url(#iDPgS1a)" class="ybrylxbuq"/><path fill="url(#iZ8VHxd)" class="ybrylxbuq"/></g><path class="t6ctewbxe"/><path fill="url(#intDisc)" class="ybrylxbuq"/><path fill="url(#iJfxUeQ)" class="ybrylxbuq"/><g filter="url(#iPfPUEd)"><path class="b678z9q7t"/></g><g filter="url(#im0ncmc)"><path class="ssa8d9tlu"/><path fill="url(#iYezi0b)" class="b175b4n1p"/><path fill="url(#ifW1AHd)" class="b175b4n1p"/><path fill="url(#iR5AiDd)" class="b175b4n1p"/></g><path fill="url(#i6S28od)" class="b175b4n1p"/><g filter="url(#iC6Vtib)"><path stroke="url(#i6Fxnce)" class="e0vz7ns1x"/></g><path class="isl9ubb5b"/><path class="jwqe_jbgo"/><path fill="url(#ivwcJoh)" class="cwr7ndbvn"/><path class="hdusbzsjg"/><g filter="url(#iVARZDe)"><path class="jl9xgibbw"/><path fill="url(#iZmGKKW)" class="b0svlhbnq"/></g><g filter="url(#i5l1qpe)"><path fill="url(#ivjr05J)" class="hyj07d54k"/></g><path class="uf734fbqu"/><path fill="url(#idq5ksb)" class="i9v5wucat"/><path class="tr80mtbrp"/><g filter="url(#iONtyDc)"><path fill="url(#iilVjNe)" class="rj390kbfq"/></g><g filter="url(#il7n6gv)"><ellipse transform="rotate(-27.914 12.393 9.954)" class="kyknafbgp"/><ellipse fill="url(#iuoxayc)" transform="rotate(-27.914 12.393 9.954)" class="jht53ab1w"/></g><g filter="url(#iv4tVdg)"><path clip-rule="evenodd" class="zdqjaelxd"/></g><g filter="url(#iWI4Ucb)"><path class="nw6o_7biu"/></g><g filter="url(#iv55ieS)"><path clip-rule="evenodd" class="ooite7b2u"/></g><g filter="url(#ionWRpd)"><path class="urzh-1b0a"/></g><path fill="url(#icBL91d)" class="iycy_sbnz"/><path fill="url(#ibvcPeT)" class="g9arp8b8o"/><path fill="url(#ic8iSPb)" class="g9arp8b8o"/><path fill="url(#iLeaTZU)" class="sb1phf9zd"/><path fill="url(#iE9kqQd)" class="sb1phf9zd"/><path fill="url(#ijzTWdd)" class="ltwsa8bld"/><path fill="url(#iT74aTv)" class="ltwsa8bld"/><path fill="url(#ivqY3ab)" class="ltwsa8bld"/><g filter="url(#iET0Vmd)"><path fill="url(#iCmdwmN)" class="o12zmvuzn"/></g><g filter="url(#i8yhr9I)"><path class="ojb-ttbmo"/></g><g filter="url(#ig8juOd)"><path class="ac3zfwb5z"/></g><defs><radialGradient id="iM6rPqd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -6.5 5.875 0 20.418 30)" gradientUnits="userSpaceOnUse"><stop class="bbqwceq4e"/><stop offset="1" class="s5pm96b_v"/></radialGradient><radialGradient id="i7bctJc" cx="0" cy="0" r="1" gradientTransform="rotate(137.578 3.33 12.372)scale(3.51039 2.85287)" gradientUnits="userSpaceOnUse"><stop class="ypv_kpaja"/><stop offset="1" class="iv7bj_baj"/></radialGradient><radialGradient id="izNqDsc" cx="0" cy="0" r="1" gradientTransform="matrix(-.875 1.72406 -2.87775 -1.46054 13.106 16.844)" gradientUnits="userSpaceOnUse"><stop offset=".316" class="d7sh3eboe"/><stop offset="1" class="tizux9w7p"/></radialGradient><radialGradient id="ifkmApd" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.94352 -1.86047 0 16.66 16.037)" gradientUnits="userSpaceOnUse"><stop offset=".368" class="rtj8_6bqg"/><stop offset="1" class="m8_l30tsr"/></radialGradient><radialGradient id="iUzRGHc" cx="0" cy="0" r="1" gradientTransform="matrix(-.94683 2.47509 -1.65865 -.6345 15.664 17.448)" gradientUnits="userSpaceOnUse"><stop offset=".307" class="s1rw4px-b"/><stop offset="1" class="p3_97vb4n"/></radialGradient><radialGradient id="iFGxoeb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -10.1875 3.9375 0 6.668 30)" gradientUnits="userSpaceOnUse"><stop class="mx797o4di"/><stop offset="1" class="m1_q07_me"/></radialGradient><radialGradient id="iPRoNnL" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.625 -3.70312 0 24.043 20.063)" gradientUnits="userSpaceOnUse"><stop offset=".141" class="p7prpqhjw"/><stop offset="1" class="m4mhe8bqv"/></radialGradient><radialGradient id="iOgo57h" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.76563 6.85285 0 14.734 21.438)" gradientUnits="userSpaceOnUse"><stop offset=".469" class="ee8yo8bto"/><stop offset="1" class="dn7nvsb1v"/></radialGradient><radialGradient id="iZjLroc" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.99306 -2.2392 0 14.79 16.917)" gradientUnits="userSpaceOnUse"><stop offset=".34" class="n1xazwzir"/><stop offset="1" class="i15bqbcto"/></radialGradient><radialGradient id="ifFH9Wc" cx="0" cy="0" r="1" gradientTransform="rotate(-45 32.088 -22.467)scale(.99437 .32275)" gradientUnits="userSpaceOnUse"><stop offset=".383" class="ky_dg6bhp"/><stop offset="1" class="qwfi8obtf"/></radialGradient><radialGradient id="ilud8bb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.45773 0 0 -.25781 25.259 22.922)" gradientUnits="userSpaceOnUse"><stop class="xy5k-abzm"/><stop offset="1" class="hnxygroex"/></radialGradient><radialGradient id="iUsyeEb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.44615 2.39061 -1.97778 -1.19642 26.449 24.594)" gradientUnits="userSpaceOnUse"><stop class="tqgfgwd_y"/><stop offset="1" class="de0rqgbhp"/></radialGradient><radialGradient id="i9vzj2O" cx="0" cy="0" r="1" gradientTransform="matrix(2.3125 0 0 .46609 22.317 25.97)" gradientUnits="userSpaceOnUse"><stop offset=".248" class="h97sosa1o"/><stop offset="1" class="bzewrsgmw"/></radialGradient><radialGradient id="ijLycSc" cx="0" cy="0" r="1" gradientTransform="matrix(2.59241 0 0 .5225 22.13 27.297)" gradientUnits="userSpaceOnUse"><stop offset=".248" class="h97sosa1o"/><stop offset="1" class="bzewrsgmw"/></radialGradient><radialGradient id="iXao1Dd" cx="0" cy="0" r="1" gradientTransform="matrix(2.71875 0 0 .32813 22.036 28.564)" gradientUnits="userSpaceOnUse"><stop offset=".248" class="h97sosa1o"/><stop offset="1" class="bzewrsgmw"/></radialGradient><radialGradient id="iNK15Nc" cx="0" cy="0" r="1" gradientTransform="matrix(1.79644 -1.82143 3.66937 3.61902 8.445 11.578)" gradientUnits="userSpaceOnUse"><stop offset=".315" class="xkounabyd"/><stop offset="1" class="r4_b5mbls"/></radialGradient><radialGradient id="iM934oc" cx="0" cy="0" r="1" gradientTransform="rotate(109.866 7.11 12.033)scale(2.90471)" gradientUnits="userSpaceOnUse"><stop class="fjehlo_qb"/><stop offset=".641" class="hbmipr16q"/></radialGradient><radialGradient id="iJzxHWd" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.55554 -9.76888 0 15.329 9.143)" gradientUnits="userSpaceOnUse"><stop offset=".56" class="l58-idrcp"/><stop offset="1" class="kcal37bgz"/></radialGradient><radialGradient id="ifMf5Tc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.3025 1.60308 0 17.178 9.462)" gradientUnits="userSpaceOnUse"><stop class="qvori65vn"/><stop offset="1" class="l_2mr6b5e"/></radialGradient><radialGradient id="iT70dge" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.38599 1.72361 0 12.636 9.428)" gradientUnits="userSpaceOnUse"><stop class="waf9s5hfu"/><stop offset="1" class="qibk7dfmm"/></radialGradient><radialGradient id="imGI7zd" cx="0" cy="0" r="1" gradientTransform="rotate(92.495 6.82 12.932)scale(6.52285 6.3848)" gradientUnits="userSpaceOnUse"><stop class="yxusxvmhb"/><stop offset="1" class="u4whumb4c"/></radialGradient><radialGradient id="ixYkibb" cx="0" cy="0" r="1" gradientTransform="rotate(119.745 3.103 6.401)scale(7.50558 4.86482)" gradientUnits="userSpaceOnUse"><stop class="ui2qblbap"/><stop offset="1" class="yvj3l2b7i"/></radialGradient><radialGradient id="is4oeLb" cx="0" cy="0" r="1" gradientTransform="rotate(127.807 8.514 6.057)scale(5.58654 9.5004)" gradientUnits="userSpaceOnUse"><stop class="ck410xb1o"/><stop offset="1" class="qeh0r4bjq"/></radialGradient><radialGradient id="iLS37Ld" cx="0" cy="0" r="1" gradientTransform="matrix(-.18385 -1.98553 .97514 -.0903 10.719 7.103)" gradientUnits="userSpaceOnUse"><stop offset=".222" class="euj6xpbnj"/><stop offset="1" class="hchnd0bsx"/></radialGradient><radialGradient id="iK5yQFd" cx="0" cy="0" r="1" gradientTransform="rotate(-66.4 16.4 -10.059)scale(2.13845 1.74407)" gradientUnits="userSpaceOnUse"><stop offset=".479" class="ghdrqrbfe"/><stop offset="1" class="d7zypgbet"/></radialGradient><radialGradient id="iDPgS1a" cx="0" cy="0" r="1" gradientTransform="matrix(.9893 1.22755 -1.08384 .87349 14.067 2.157)" gradientUnits="userSpaceOnUse"><stop class="wn92vfpti"/><stop offset="1" class="t4clght5m"/></radialGradient><radialGradient id="iZ8VHxd" cx="0" cy="0" r="1" gradientTransform="matrix(1.4459 -3.025 1.04518 .49958 19.015 6.524)" gradientUnits="userSpaceOnUse"><stop class="hye_w5bmk"/><stop offset="1" class="f2dz70yyi"/></radialGradient><radialGradient id="i6Fxnce" cx="0" cy="0" r="1" gradientTransform="matrix(.02452 -.62507 1.87523 .07355 14.756 14.726)" gradientUnits="userSpaceOnUse"><stop class="zjmwko4fr"/><stop offset="1" class="md9bsbc9k"/></radialGradient><radialGradient id="ivwcJoh" cx="0" cy="0" r="1" gradientTransform="matrix(0 .9 -1.06492 0 17.011 10.381)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iZmGKKW" cx="0" cy="0" r="1" gradientTransform="matrix(-.23105 -.29773 .40992 -.31811 16.784 10.132)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="idq5ksb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .90004 -1.06498 0 12.663 10.381)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iuoxayc" cx="0" cy="0" r="1" gradientTransform="matrix(-.0077 -.49224 .59169 -.00926 12.379 10.267)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ic8iSPb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.3125 -.47665 0 23.309 6.469)" gradientUnits="userSpaceOnUse"><stop offset=".167" class="y66dh_b5l"/><stop offset="1" class="nzjwoybta"/></radialGradient><radialGradient id="iLeaTZU" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.40034 6.13 0 14.849 7.33)" gradientUnits="userSpaceOnUse"><stop offset=".671" class="ixw-oi7aq"/><stop offset="1" class="mguibccfx"/></radialGradient><radialGradient id="ijzTWdd" cx="0" cy="0" r="1" gradientTransform="rotate(129.472 9.359 6.843)scale(6.19389 12.2026)" gradientUnits="userSpaceOnUse"><stop class="qyg3b1b6n"/><stop offset="1" class="p64oiyb7x"/></radialGradient><radialGradient id="iT74aTv" cx="0" cy="0" r="1" gradientTransform="rotate(146.725 7.907 4.576)scale(9.56883 10.9225)" gradientUnits="userSpaceOnUse"><stop offset=".512" class="yytwt1d8s"/><stop offset="1" class="s1a8ycb7r"/></radialGradient><radialGradient id="iCmdwmN" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.71875 -10.576 0 14.791 6.156)" gradientUnits="userSpaceOnUse"><stop class="z2rllvutr"/><stop offset="1" class="t8ye-ilvp"/></radialGradient><linearGradient id="i1Pd52d" x1="14.735" x2="14.735" y1="16.438" y2="30.563" gradientUnits="userSpaceOnUse"><stop class="troaenb0e"/><stop offset="1" class="jsbk_hbmd"/></linearGradient><linearGradient id="it3vqkc" x1="10.637" x2="11.379" y1="18.219" y2="18.242" gradientUnits="userSpaceOnUse"><stop offset=".344" class="u9ri-jbkw"/><stop offset="1" class="j0xtzac4y"/></linearGradient><linearGradient id="igSiocc" x1="18.805" x2="18.012" y1="18.937" y2="18.937" gradientUnits="userSpaceOnUse"><stop class="ph46gxbvy"/><stop offset="1" class="s21zh4b3w"/></linearGradient><linearGradient id="iQD9PdN" x1="16.746" x2="17.254" y1="20.766" y2="19.984" gradientUnits="userSpaceOnUse"><stop class="sq-bwm1qa"/><stop offset="1" class="s21zh4b3w"/></linearGradient><linearGradient id="iZLtlOc" x1="8.242" x2="21.651" y1="9.948" y2="9.948" gradientUnits="userSpaceOnUse"><stop offset=".006" class="z-f4zlb4n"/><stop offset="1" class="z88owpbip"/></linearGradient><linearGradient id="iHff3Oe" x1="17.985" x2="17.985" y1="10.031" y2="9.742" gradientUnits="userSpaceOnUse"><stop class="q9u3nxbxg"/><stop offset="1" class="lvlvw7bgp"/></linearGradient><linearGradient id="i5m29vW" x1="7.769" x2="5.387" y1="27.844" y2="27.844" gradientUnits="userSpaceOnUse"><stop class="r5fk93cur"/><stop offset="1" class="bl3c3b0wv"/></linearGradient><linearGradient id="iw3Aprr" x1="12.296" x2="13.342" y1="16.885" y2="16.885" gradientUnits="userSpaceOnUse"><stop class="edqjrix7t"/><stop offset="1" class="drdl8fi2k"/></linearGradient><linearGradient id="iXmKX4d" x1="17.593" x2="15.999" y1="16.885" y2="16.885" gradientUnits="userSpaceOnUse"><stop class="edqjrix7t"/><stop offset="1" class="drdl8fi2k"/></linearGradient><linearGradient id="inGd3Ee" x1="25.452" x2="25.452" y1="21.452" y2="27.847" gradientUnits="userSpaceOnUse"><stop class="m2g4nbcbq"/><stop offset="1" class="w9napxb6c"/></linearGradient><linearGradient id="iNUFY3c" x1="25.259" x2="23.652" y1="24.265" y2="24.265" gradientUnits="userSpaceOnUse"><stop offset=".006" class="m7592x5al"/><stop offset="1" class="nnhfo6p_l"/></linearGradient><linearGradient id="igKMsTc" x1="25.442" x2="26.863" y1="15.852" y2="14.43" gradientUnits="userSpaceOnUse"><stop class="avgmeibok"/><stop offset="1" class="lasn3qwok"/></linearGradient><linearGradient id="iR8tYHf" x1="26.159" x2="22.131" y1="28.063" y2="28.063" gradientUnits="userSpaceOnUse"><stop class="ut7pv-xgw"/><stop offset=".861" class="oltxz8b0t"/></linearGradient><linearGradient id="idYJate" x1="24.429" x2="22.593" y1="26.002" y2="26.002" gradientUnits="userSpaceOnUse"><stop class="cu_6wobdp"/><stop offset="1" class="glaz8zb9m"/></linearGradient><linearGradient id="iSCMlmz" x1="24.351" x2="22.515" y1="27.307" y2="27.307" gradientUnits="userSpaceOnUse"><stop class="cu_6wobdp"/><stop offset="1" class="glaz8zb9m"/></linearGradient><linearGradient id="iVDbSlO" x1="24.429" x2="22.593" y1="28.611" y2="28.611" gradientUnits="userSpaceOnUse"><stop class="cu_6wobdp"/><stop offset="1" class="glaz8zb9m"/></linearGradient><linearGradient id="iOwVpEe" x1="10.109" x2="9.47" y1="11.007" y2="11.007" gradientUnits="userSpaceOnUse"><stop class="qkrb-k0fv"/><stop offset="1" class="lhl27y5mc"/></linearGradient><linearGradient id="iTnnaLm" x1="18.862" x2="11.252" y1="11.117" y2="12.251" gradientUnits="userSpaceOnUse"><stop class="p8j84vbpc"/><stop offset=".916" class="as9qb1byz"/></linearGradient><linearGradient id="iNsMHuc" x1="9.463" x2="11.767" y1="13.803" y2="13.503" gradientUnits="userSpaceOnUse"><stop class="a99w59rao"/><stop offset="1" class="x2u305zwp"/></linearGradient><linearGradient id="igYrhEv" x1="14.869" x2="14.869" y1="7.233" y2="7.546" gradientUnits="userSpaceOnUse"><stop class="xi-ek5kdw"/><stop offset="1" class="ooz3dpb3k"/></linearGradient><linearGradient id="i5RNXhc" x1="9.996" x2="12.888" y1="10.462" y2="5.326" gradientUnits="userSpaceOnUse"><stop class="kyzs66gfi"/><stop offset="1" class="zsx4vmb0f"/></linearGradient><linearGradient id="intDisc" x1="20.853" x2="19.975" y1="9.276" y2="9.13" gradientUnits="userSpaceOnUse"><stop class="o5yh0tbjp"/><stop offset="1" class="w4pbwv9ce"/></linearGradient><linearGradient id="iJfxUeQ" x1="8.561" x2="9.434" y1="8.436" y2="8.355" gradientUnits="userSpaceOnUse"><stop class="i_-q_gb1v"/><stop offset="1" class="ulb6xmbnw"/></linearGradient><linearGradient id="iYezi0b" x1="13.979" x2="14.914" y1="11.774" y2="11.774" gradientUnits="userSpaceOnUse"><stop class="vrar8hnmh"/><stop offset="1" class="ry_l2ebgl"/></linearGradient><linearGradient id="ifW1AHd" x1="15.775" x2="14.753" y1="12.095" y2="12.081" gradientUnits="userSpaceOnUse"><stop class="hmiraywql"/><stop offset="1" class="l99c_58cs"/></linearGradient><linearGradient id="iR5AiDd" x1="15.034" x2="15.034" y1="12.835" y2="12.264" gradientUnits="userSpaceOnUse"><stop class="wno2x162j"/><stop offset="1" class="hog28xbdu"/></linearGradient><linearGradient id="i6S28od" x1="14.965" x2="14.965" y1="12.877" y2="12.71" gradientUnits="userSpaceOnUse"><stop class="hi_3gxb3d"/><stop offset="1" class="uco9ljbwd"/></linearGradient><linearGradient id="ivjr05J" x1="17.786" x2="17.474" y1="10.103" y2="10.295" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iilVjNe" x1="13.405" x2="13.092" y1="10.103" y2="10.295" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="icBL91d" x1="6.356" x2="7.059" y1="7.633" y2="6.703" gradientUnits="userSpaceOnUse"><stop class="qo28zhh9b"/><stop offset="1" class="yhrc8s1zu"/></linearGradient><linearGradient id="ibvcPeT" x1="22.462" x2="22.462" y1="6" y2="8.01" gradientUnits="userSpaceOnUse"><stop class="ott3_jqut"/><stop offset="1" class="l8p6brbrs"/></linearGradient><linearGradient id="iE9kqQd" x1="15.051" x2="15.051" y1="7.33" y2="7.174" gradientUnits="userSpaceOnUse"><stop class="j3h4o1d7b"/><stop offset="1" class="lo1ogpbbw"/></linearGradient><linearGradient id="ivqY3ab" x1="6.787" x2="7.841" y1="7.125" y2="7.125" gradientUnits="userSpaceOnUse"><stop class="it1_ig0bc"/><stop offset="1" class="qgmif2bih"/></linearGradient><filter id="iXCDk9d" width="22.99" height="15" x="3.739" y="15.5" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy=".5"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.211765 0 0 0 0 0.431373 0 0 0 0 0.631373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2019"/></filter><filter id="iHh8cSd" width="5.492" height="8.119" x="9.76" y="14.781" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2019" stdDeviation=".5"/></filter><filter id="iHToNNx" width="5.492" height="8.113" x="13.872" y="15.006" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2019" stdDeviation=".5"/></filter><filter id="iSJjM5x" width="3.592" height="6.219" x="10.712" y="15.408" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.137255 0 0 0 0 0.337255 0 0 0 0 0.811765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2019"/></filter><filter id="i8dAUrc" width="3.02" height="8.58" x="23.729" y="14.21" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.505882 0 0 0 0 0.501961 0 0 0 0 0.529412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2019"/></filter><filter id="ixv1Amb" width="3.675" height="3.685" x="24.636" y="12.621" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.447059 0 0 0 0 0.870588 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2019"/></filter><filter id="iR2YZJc" width="4.618" height="5.556" x="22.131" y="24.444" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.15"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.905882 0 0 0 0 0.521569 0 0 0 0 0.364706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2019"/></filter><filter id="i7Mfa6b" width="2.047" height=".25" x="22.623" y="25.877" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2019" stdDeviation=".05"/></filter><filter id="iBXe37z" width="2.047" height=".25" x="22.545" y="27.182" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2019" stdDeviation=".05"/></filter><filter id="iyWMnFW" width="2.047" height=".25" x="22.623" y="28.486" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2019" stdDeviation=".05"/></filter><filter id="iHKVMLe" width="2.483" height="2.483" x="8.867" y="9.487" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2019" stdDeviation=".125"/></filter><filter id="i7dZ9Ae" width="3.477" height="3.477" x="17.925" y="8.915" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.15"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.839216 0 0 0 0 0.615686 0 0 0 0 0.337255 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2019"/></filter><filter id="iWD6jDx" width="2.483" height="2.483" x="18.347" y="9.487" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2019" stdDeviation=".125"/></filter><filter id="iioabKh" width="12.557" height="8.265" x="8.561" y="1.907" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.984314 0 0 0 0 0.584314 0 0 0 0 0.129412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2019"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.972549 0 0 0 0 0.572549 0 0 0 0 0.0156863 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2019" result="effect2_innerShadow_4002_2019"/></filter><filter id="iPfPUEd" width="3.254" height="4.172" x="12.975" y="9.576" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2019" stdDeviation=".375"/></filter><filter id="im0ncmc" width="2.37" height="3.172" x="13.655" y="9.913" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2019" stdDeviation=".125"/></filter><filter id="iC6Vtib" width="3.606" height="1.469" x="13.037" y="13.303" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2019" stdDeviation=".05"/></filter><filter id="iVARZDe" width=".785" height=".694" x="16.279" y="9.611" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2019" stdDeviation=".05"/></filter><filter id="i5l1qpe" width=".889" height=".911" x="17.116" y="9.685" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2019" stdDeviation=".1"/></filter><filter id="iONtyDc" width=".984" height="1.038" x="12.69" y="9.622" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2019" stdDeviation=".1"/></filter><filter id="il7n6gv" width=".91" height=".703" x="11.938" y="9.602" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2019" stdDeviation=".05"/></filter><filter id="iv4tVdg" width="2.593" height="1.642" x="16.099" y="7.579" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.588235 0 0 0 0 0.188235 0 0 0 0 0.0862745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2019"/></filter><filter id="iWI4Ucb" width="2.499" height="1.193" x="16.195" y="7.634" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2019" stdDeviation=".125"/></filter><filter id="iv55ieS" width="2.593" height="1.642" x="10.988" y="7.579" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.588235 0 0 0 0 0.188235 0 0 0 0 0.0862745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2019"/></filter><filter id="ionWRpd" width="2.402" height="1.2" x="11.084" y="7.564" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2019" stdDeviation=".125"/></filter><filter id="iET0Vmd" width="15.17" height="4.76" x="7.155" y="5.371" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.588235 0 0 0 0 0.47451 0 0 0 0 0.827451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2019"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.423529 0 0 0 0 0.329412 0 0 0 0 0.627451 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2019" result="effect2_innerShadow_4002_2019"/></filter><filter id="i8yhr9I" width="9.99" height="2.47" x="9.739" y="2" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.670588 0 0 0 0 0.843137 0 0 0 0 0.835294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2019"/></filter><filter id="ig8juOd" width="6.31" height="2.47" x="13.419" y="2" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".1"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.552941 0 0 0 0 0.890196 0 0 0 0 0.92549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2019"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-factory-worker" /></template>
<style>
.a1i_j40xh {
  fill: var(--svg-color--3c77cf, #3C77CF);
  d: path("M18.804 16.276v4.576c.003.26-.023.578-.25.718c-.233.145-.58-.018-.742-.14l-2.5-1.766v-4.15c1.228.064 2.403.329 3.492.762");
}

.a424ylq9x {
  fill: var(--svg-color--3674c9, #3674C9);
  d: path("M10.812 16.221v4.63c-.002.26.024.579.25.72c.234.144.581-.019.743-.141l2.5-1.766v-4.156a11 11 0 0 0-3.493.713");
}

.a99w59rao {
  stop-color: var(--svg-color--d19c3a, #D19C3A);
}

.ac3zfwb5z {
  fill: var(--svg-color--8cf5ff, #8CF5FF);
  d: path("m16.169 2l-2.45 2.37h5.45c.31 0 .56-.25.56-.56V2.19c-.4-.12-.83-.19-1.27-.19z");
}

.as9qb1byz {
  stop-color: var(--svg-color--f9a528, #F9A528);
}

.avgmeibok {
  stop-color: var(--svg-color--73d7ff, #73D7FF);
}

.b_8rrzerq {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-05px, 0.05px);
  d: path("M22.748 26.002h1.797");
}

.b0svlhbnq {
  d: path("M16.948 9.762c.063.085-.07.188-.22.3c-.15.113-.262.192-.325.107c-.064-.084.007-.244.158-.357c.15-.112.323-.135.387-.05");
}

.b175b4n1p {
  d: path("m14.459 10.445l-.53 1.693a.537.537 0 0 0 .52.697h.783a.54.54 0 0 0 .518-.697l-.53-1.694c-.113-.375-.642-.375-.761 0");
}

.b678z9q7t {
  fill: var(--svg-color--f1901c, #F1901C);
  d: path("m14.566 10.607l-.818 1.694c-.101.348.142.697.486.697h.735c.345 0 .588-.354.487-.697l-.497-1.694c-.107-.375-.282-.375-.393 0");
}

.bbqwceq4e {
  stop-color: var(--svg-color--3878e5, #3878E5);
}

.bl3c3b0wv {
  stop-color: var(--svg-color--3e6fc6, #3E6FC6);
  stop-opacity: 0;
}

.bzewrsgmw {
  stop-color: var(--svg-color--df9728, #DF9728);
  stop-opacity: 0;
}

.ck410xb1o {
  stop-color: var(--svg-color--ffe336, #FFE336);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cu_6wobdp {
  stop-color: var(--svg-color--c88714, #C88714);
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

.de0rqgbhp {
  stop-color: var(--svg-color--ffe136, #FFE136);
  stop-opacity: 0;
}

.dlrwjtb7t {
  d: path("M9.758 10.118A30 30 0 0 1 9.7 8.685c0-.266.107-.585.32-.744l.161-.16c.267-.212.374-.531.374-.85v-.85c0-.266.16-.479.428-.532c.641-.16 1.977-.425 3.902-.425c1.924 0 3.26.266 3.902.425c.213.053.427.266.427.532v.85c0 .319.16.638.375.85c.5.351.469.544.427.957c-.013.128-.053 1.19-.089 1.435l-.265 3.944c-.16 1.764-1.546 2.993-3.199 2.993h-3.199c-1.706 0-3.04-1.23-3.2-2.993z");
}

.dn7nvsb1v {
  stop-color: var(--svg-color--806879, #806879);
}

.drdl8fi2k {
  stop-color: var(--svg-color--724526, #724526);
  stop-opacity: 0;
}

.e0vz7ns1x {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M14.84 13.848c-.506 0-.981-.12-1.38-.328c-.137-.069-.284.085-.198.209c.334.505.916.842 1.578.842s1.244-.337 1.577-.842c.086-.13-.06-.278-.197-.209c-.4.209-.87.328-1.38.328Z");
}

.e5n7-cbky {
  d: path("M14.739 15.5c-6.07 0-11 4.92-11 11V30h20.99a1 1 0 0 0 1-1v-2.5c0-6.08-4.92-11-10.99-11");
}

.edqjrix7t {
  stop-color: var(--svg-color--724526, #724526);
}

.ee8yo8bto {
  stop-color: var(--svg-color--806879, #806879);
  stop-opacity: 0;
}

.euj6xpbnj {
  stop-color: var(--svg-color--ffb42c, #FFB42C);
}

.f2dz70yyi {
  stop-color: var(--svg-color--ffd93a, #FFD93A);
  stop-opacity: 0;
}

.fbjx3y-qb {
  d: path("M25.449 23.1c.55 0 1 .45 1 1v2.29h-2V24.1c0-.55.45-1 1-1");
}

.fjehlo_qb {
  stop-color: var(--svg-color--935806, #935806);
}

.ft5dv1b6b {
  fill: none;
}

.fuw705b0o {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-05px, 0.05px);
  d: path("M22.67 27.307h1.797");
}

.g9arp8b8o {
  d: path("M22.819 8.01h-.713a.49.49 0 0 1-.49-.49V6.49c-.01-.27.21-.49.49-.49h.713c.27 0 .49.22.49.49v1.02c0 .28-.22.5-.49.5");
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.ghdrqrbfe {
  stop-color: var(--svg-color--e57d1c, #E57D1C);
}

.glaz8zb9m {
  stop-color: var(--svg-color--c07200, #C07200);
}

.gpbr0qbhd {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-05px, 0.05px);
  d: path("M22.748 28.611h1.797");
}

.h97sosa1o {
  stop-color: var(--svg-color--df9728, #DF9728);
}

.hbmipr16q {
  stop-color: var(--svg-color--e9af37, #E9AF37);
}

.hchnd0bsx {
  stop-color: var(--svg-color--ffb42c, #FFB42C);
  stop-opacity: 0;
}

.hdusbzsjg {
  fill: var(--svg-color--000, #000);
  d: path("M16.504 10.463c0-.283.226-.51.51-.51a.507.507 0 0 1 .452.744h-.901a.46.46 0 0 1-.061-.234");
}

.hi_3gxb3d {
  stop-color: var(--svg-color--e88613, #E88613);
}

.hmiraywql {
  stop-color: var(--svg-color--ffe721, #FFE721);
}

.hnxygroex {
  stop-color: var(--svg-color--624b78, #624B78);
  stop-opacity: 0;
}

.hog28xbdu {
  stop-color: var(--svg-color--eb8a1c, #EB8A1C);
  stop-opacity: 0;
}

.hye_w5bmk {
  stop-color: var(--svg-color--ffd93a, #FFD93A);
}

.hyj07d54k {
  d: path("M17.805 10.346a.84.84 0 0 0-.23-.461l-.26.284l.118.227z");
}

.i_-q_gb1v {
  stop-color: var(--svg-color--692c08, #692C08);
}

.i15bqbcto {
  stop-color: var(--svg-color--ae7b1d, #AE7B1D);
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

.ii_vcdblz {
  fill: var(--svg-color--1e6dc3, #1E6DC3);
  d: path("M10.76 16.494v4.63c-.002.26.024.579.25.72c.234.144.581-.02.743-.142l2.5-1.765V15.78a11 11 0 0 0-3.492.713");
}

.isl9ubb5b {
  fill: var(--svg-color--8a004f, #8A004F);
  d: path("M14.84 13.848c-.506 0-.981-.12-1.38-.328c-.137-.069-.284.085-.198.209c.334.505.916.842 1.578.842s1.244-.337 1.577-.842c.086-.13-.06-.278-.197-.209c-.4.209-.87.328-1.38.328");
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

.j3h4o1d7b {
  stop-color: var(--svg-color--391f48, #391F48);
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

.jl9xgibbw {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M16.948 9.762c.063.085-.07.188-.22.3c-.15.113-.262.192-.325.107c-.064-.084.007-.244.158-.357c.15-.112.323-.135.387-.05");
}

.js7qsnbrb {
  d: path("M14.79 18.103c-1.239 0-2.239-.948-2.239-2.123v-2.637c0-1.164 1-2.112 2.24-2.112c1.239 0 2.239.948 2.239 2.122v2.638c-.011 1.164-1.011 2.112-2.24 2.112");
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

.kcal37bgz {
  stop-color: var(--svg-color--d07f50, #D07F50);
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

.l_2mr6b5e {
  stop-color: var(--svg-color--ffba0d, #FFBA0D);
  stop-opacity: 0;
}

.l58-idrcp {
  stop-color: var(--svg-color--f49a3e, #F49A3E);
  stop-opacity: 0;
}

.l8p6brbrs {
  stop-color: var(--svg-color--38234f, #38234F);
}

.l99c_58cs {
  stop-color: var(--svg-color--ffe721, #FFE721);
  stop-opacity: 0;
}

.lasn3qwok {
  stop-color: var(--svg-color--93ffff, #93FFFF);
}

.lhl27y5mc {
  stop-color: var(--svg-color--c27521, #C27521);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
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

.m2g4nbcbq {
  stop-color: var(--svg-color--f4c222, #F4C222);
}

.m3dxw5b4u {
  d: path("M10.812 16.221v4.63c-.002.26.024.579.25.72c.234.144.581-.019.743-.141l2.5-1.766v-4.156a11 11 0 0 0-3.493.713");
}

.m4mhe8bqv {
  stop-color: var(--svg-color--4f94d3, #4F94D3);
  stop-opacity: 0;
}

.m7592x5al {
  stop-color: var(--svg-color--6e5584, #6E5584);
}

.m8_l30tsr {
  stop-color: var(--svg-color--2a3765, #2A3765);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.md9bsbc9k {
  stop-color: var(--svg-color--ffbe30, #FFBE30);
  stop-opacity: 0;
}

.mguibccfx {
  stop-color: var(--svg-color--2a193d, #2A193D);
}

.mx797o4di {
  stop-color: var(--svg-color--4086f6, #4086F6);
}

.n1xazwzir {
  stop-color: var(--svg-color--e0992d, #E0992D);
}

.na59ribzw {
  d: path("M28.245 13.16c.081-.326-.151-.554-.478-.472c-.878.18-2.296.406-2.714.954c-.571.613-.55 1.582.03 2.184a1.577 1.577 0 0 0 2.256.01c.503-.512.733-1.836.906-2.676");
}

.ndlc49hkf {
  d: path("M21.974 6.741H7.744v3.29h14.23z");
}

.nnhfo6p_l {
  stop-color: var(--svg-color--48345f, #48345F);
}

.nw6o_7biu {
  stroke: var(--svg-color--b75e4f, #B75E4F);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M18.32 8.452c-.477-.336-1.087-.492-1.75-.43");
}

.nzjwoybta {
  stop-color: var(--svg-color--675878, #675878);
  stop-opacity: 0;
}

.o12zmvuzn {
  d: path("M20.756 7.641a7.5 7.5 0 0 0-2.31-1.49c-1.09-.45-2.32-.68-3.66-.68c-1.22 0-2.36.2-3.38.6c-.84.33-1.61.79-2.28 1.38c-1.16 1-1.69 2.07-1.83 2.37c-.03.07-.04.14-.04.21h.5c.21-.47 1.98-4.06 7.03-4.06c5.6 0 7.04 4.06 7.04 4.06h.5c0-.06-.01-.11-.03-.17c-.01-.05-.41-1.14-1.54-2.22");
}

.o5yh0tbjp {
  stop-color: var(--svg-color--703308, #703308);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ojb-ttbmo {
  fill: var(--svg-color--c4ffff, #C4FFFF);
  d: path("M10.299 4.37h8.87c.31 0 .56-.25.56-.56V2.19c-.4-.12-.83-.19-1.27-.19h-7.45c-.44 0-.87.07-1.27.19v1.62c0 .31.25.56.56.56");
}

.oltxz8b0t {
  stop-color: var(--svg-color--df9e26, #DF9E26);
}

.ooite7b2u {
  fill: var(--svg-color--b5404c, #B5404C);
  fill-rule: evenodd;
  d: path("M13.066 8.53c-.717-.066-1.177.213-1.288.316a.47.47 0 1 1-.638-.692c.305-.281 1.028-.653 2.014-.56a.47.47 0 0 1-.088.937");
}

.ooz3dpb3k {
  stop-color: var(--svg-color--b76518, #B76518);
  stop-opacity: 0;
}

.ott3_jqut {
  stop-color: var(--svg-color--534065, #534065);
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

.p8j84vbpc {
  stop-color: var(--svg-color--ffd530, #FFD530);
}

.ph46gxbvy {
  stop-color: var(--svg-color--4f8dd8, #4F8DD8);
}

.pi6c47yng {
  d: path("M21.729 18.01v11.98h3a1 1 0 0 0 1-1v-2.5c0-3.41-1.55-6.46-4-8.48");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
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

.qibk7dfmm {
  stop-color: var(--svg-color--ee911a, #EE911A);
  stop-opacity: 0;
}

.qkrb-k0fv {
  stop-color: var(--svg-color--bb6e1f, #BB6E1F);
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

.qvori65vn {
  stop-color: var(--svg-color--ffba0d, #FFBA0D);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qwfi8obtf {
  stop-color: var(--svg-color--b0b0b0, #B0B0B0);
  stop-opacity: 0;
}

.qyg3b1b6n {
  stop-color: var(--svg-color--6f5b84, #6F5B84);
}

.r4_b5mbls {
  stop-color: var(--svg-color--8d5004, #8D5004);
}

.r5fk93cur {
  stop-color: var(--svg-color--2869c1, #2869C1);
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

.ry_l2ebgl {
  stop-color: var(--svg-color--faa416, #FAA416);
  stop-opacity: 0;
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

.s2toruu7e {
  cx: 19.589px;
  cy: 10.729px;
  r: 0.991px;
  fill: var(--svg-color--c58123, #C58123);
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

.ssa8d9tlu {
  fill: var(--svg-color--ffc32d, #FFC32D);
  d: path("m14.459 10.445l-.53 1.693a.537.537 0 0 0 .52.697h.783a.54.54 0 0 0 .518-.697l-.53-1.694c-.113-.375-.642-.375-.761 0");
}

.t4clght5m {
  stop-color: var(--svg-color--ffce2c, #FFCE2C);
  stop-opacity: 0;
}

.t6ctewbxe {
  fill: var(--svg-color--b7521f, #B7521F);
  d: path("m19.642 4.274l.428.212c.748.372 1.176 1.223 1.015 2.126l-.588 3.03c-.052.312-.259.523-.57.53c.036-.501.069-1.31.082-1.439c.043-.431-.025-.558-.42-.952c-.214-.212-.375-.531-.375-.85v-.85c0-.266-.213-.479-.427-.532c-.642-.16-1.978-.425-3.902-.425s-3.26.266-3.902.425a.52.52 0 0 0-.428.531v.85c0 .32-.107.639-.374.851l-.16.16c-.214.16-.322.492-.322.758c.014.155.035 1.048.059 1.419a.63.63 0 0 1-.592-.53l-.588-3.03c-.107-.85.32-1.7 1.069-2.072c1.01-.443 1.378-1.115 2.191-1.807c.588-.531 1.443-.69 2.192-.319a2.93 2.93 0 0 0 1.657 0c.801-.266 1.71-.053 2.351.532l.802.797c.214.266.481.425.802.585");
}

.t8ye-ilvp {
  stop-color: var(--svg-color--7b51c6, #7B51C6);
}

.tizux9w7p {
  stop-color: var(--svg-color--3877cc, #3877CC);
  stop-opacity: 0;
}

.tqgfgwd_y {
  stop-color: var(--svg-color--ffe136, #FFE136);
}

.tr80mtbrp {
  fill: var(--svg-color--000, #000);
  d: path("M13.17 10.463a.507.507 0 0 0-.508-.51a.507.507 0 0 0-.453.744h.901a.5.5 0 0 0 .06-.234");
}

.troaenb0e {
  stop-color: var(--svg-color--428ef7, #428EF7);
}

.u-q3e7b8s {
  d: path("m15.659 19.69l-.65.58c-.16.14-.39.14-.55 0l-.65-.58a3.45 3.45 0 0 1-1.14-2.55v-3.09a2.07 2.07 0 0 1 2.07-2.05c1.14 0 2.06.92 2.06 2.06v3.09c-.01.97-.42 1.89-1.14 2.54");
}

.u4whumb4c {
  stop-color: var(--svg-color--f19f2c, #F19F2C);
  stop-opacity: 0;
}

.u9ri-jbkw {
  stop-color: var(--svg-color--547eb3, #547EB3);
}

.uco9ljbwd {
  stop-color: var(--svg-color--e88613, #E88613);
  stop-opacity: 0;
}

.ue1gv6enh {
  d: path("M25.259 25.94h-2.05v-3c0-.19.16-.35.35-.35h1.35c.19 0 .35.16.35.35z");
}

.uf734fbqu {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.455 9.303c-.65 0-1.2.449-1.35 1.055a.273.273 0 0 0 .267.34h2.223a.23.23 0 0 0 .226-.271a1.396 1.396 0 0 0-1.366-1.124");
}

.ui2qblbap {
  stop-color: var(--svg-color--984a0a, #984A0A);
}

.uit74mbey {
  fill: var(--svg-color--ffa91b, #FFA91B);
  d: path("m19.642 4.274l.428.212c.748.372 1.176 1.223 1.015 2.126l-.588 3.03c-.052.312-.259.523-.57.53c.036-.501.069-1.31.082-1.439c.043-.431-.025-.558-.42-.952c-.214-.212-.375-.531-.375-.85v-.85c0-.266-.213-.479-.427-.532c-.642-.16-1.978-.425-3.902-.425s-3.26.266-3.902.425a.52.52 0 0 0-.428.531v.85c0 .32-.107.639-.374.851l-.16.16c-.214.16-.322.492-.322.758c.014.155.035 1.048.059 1.419a.63.63 0 0 1-.592-.53l-.588-3.03c-.107-.85.32-1.7 1.069-2.072c1.01-.443 1.378-1.115 2.191-1.807c.588-.531 1.443-.69 2.192-.319a2.93 2.93 0 0 0 1.657 0c.801-.266 1.71-.053 2.351.532l.802.797c.214.266.481.425.802.585");
}

.ulb6xmbnw {
  stop-color: var(--svg-color--692c08, #692C08);
  stop-opacity: 0;
}

.urzh-1b0a {
  stroke: var(--svg-color--b75e4f, #B75E4F);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M11.459 8.39c.208-.192.8-.518 1.651-.438");
}

.ut7pv-xgw {
  stop-color: var(--svg-color--ffe132, #FFE132);
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.vbc9nqbss {
  fill: var(--svg-color--1e64bd, #1E64BD);
  d: path("M21.729 18.01v11.98h3a1 1 0 0 0 1-1v-2.5c0-3.41-1.55-6.46-4-8.48");
}

.vczswwwcd {
  fill: var(--svg-color--fff, #fff);
  d: path("M26.151 15.597a.85.85 0 1 0 0-1.7a.85.85 0 0 0 0 1.7");
}

.vrar8hnmh {
  stop-color: var(--svg-color--faa416, #FAA416);
}

.w4pbwv9ce {
  stop-color: var(--svg-color--703308, #703308);
  stop-opacity: 0;
}

.w9napxb6c {
  stop-color: var(--svg-color--f5891f, #F5891F);
}

.waf9s5hfu {
  stop-color: var(--svg-color--ee911a, #EE911A);
}

.wct4qccbg {
  cx: 19.589px;
  cy: 10.729px;
  r: 1.664px;
}

.wn92vfpti {
  stop-color: var(--svg-color--ffce2c, #FFCE2C);
}

.wno2x162j {
  stop-color: var(--svg-color--eb8a1c, #EB8A1C);
}

.x2u305zwp {
  stop-color: var(--svg-color--d19c3a, #D19C3A);
  stop-opacity: 0;
}

.x9-b3hbfy {
  fill: var(--svg-color--1e6dc3, #1E6DC3);
  d: path("M18.365 16.768v4.575c.002.26-.024.578-.25.719c-.234.145-.581-.018-.743-.14l-2.5-1.766v-4.15c1.229.064 2.403.328 3.492.762");
}

.xi-ek5kdw {
  stop-color: var(--svg-color--b76518, #B76518);
}

.xkounabyd {
  stop-color: var(--svg-color--c58932, #C58932);
}

.xy5k-abzm {
  stop-color: var(--svg-color--755d8e, #755D8E);
}

.y66dh_b5l {
  stop-color: var(--svg-color--675878, #675878);
}

.ybrylxbuq {
  d: path("m19.642 4.274l.428.212c.748.372 1.176 1.223 1.015 2.126l-.588 3.03c-.052.312-.259.523-.57.53c.036-.501.069-1.31.082-1.439c.043-.431-.025-.558-.42-.952c-.214-.212-.375-.531-.375-.85v-.85c0-.266-.213-.479-.427-.532c-.642-.16-1.978-.425-3.902-.425s-3.26.266-3.902.425a.52.52 0 0 0-.428.531v.85c0 .32-.107.639-.374.851l-.16.16c-.214.16-.322.492-.322.758c.014.155.035 1.048.059 1.419a.63.63 0 0 1-.592-.53l-.588-3.03c-.107-.85.32-1.7 1.069-2.072c1.01-.443 1.378-1.115 2.191-1.807c.588-.531 1.443-.69 2.192-.319a2.93 2.93 0 0 0 1.657 0c.801-.266 1.71-.053 2.351.532l.802.797c.214.266.481.425.802.585");
}

.yhrc8s1zu {
  stop-color: var(--svg-color--31263f, #31263F);
}

.ypv_kpaja {
  stop-color: var(--svg-color--4680db, #4680DB);
}

.yvj3l2b7i {
  stop-color: var(--svg-color--f19331, #F19331);
  stop-opacity: 0;
}

.yxusxvmhb {
  stop-color: var(--svg-color--964a0a, #964A0A);
}

.yytwt1d8s {
  stop-color: var(--svg-color--362d41, #362D41);
  stop-opacity: 0;
}

.z-f4zlb4n {
  stop-color: var(--svg-color--251229, #251229);
}

.z2rllvutr {
  stop-color: var(--svg-color--8c68d5, #8C68D5);
}

.z88owpbip {
  stop-color: var(--svg-color--24132c, #24132C);
}

.zdqjaelxd {
  fill: var(--svg-color--b5404c, #B5404C);
  fill-rule: evenodd;
  d: path("M16.614 8.53c.717-.066 1.177.213 1.288.316a.47.47 0 1 0 .638-.692c-.305-.281-1.028-.653-2.014-.56a.47.47 0 0 0 .087.937");
}

.zjmwko4fr {
  stop-color: var(--svg-color--ffd069, #FFD069);
}

.zsx4vmb0f {
  stop-color: var(--svg-color--e07027, #E07027);
  stop-opacity: 0;
}

</style>
