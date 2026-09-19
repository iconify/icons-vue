<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#i4X72Pc)"><path fill="url(#iJt5yHd)" clip-rule="evenodd" class="ynqv6932l"/></g><g filter="url(#i64Y0uc)"><path class="wk56mbcaf"/><path fill="url(#i6MWe8c)" class="p2anc3byq"/><path fill="url(#i4J3ECd)" class="p2anc3byq"/></g><path fill="url(#ibRiAkc)" class="p2anc3byq"/><path fill="url(#imXIVRb)" class="dxctj8e-g"/><path fill="url(#iPMqXAG)" class="dxctj8e-g"/><path fill="url(#isG7eBe)" class="dxctj8e-g"/><g filter="url(#iFMSoee)"><path class="jnzd73pdm"/></g><path class="d5cxx-l5u"/><path fill="url(#iEKUpld)" class="gb6x2dbgd"/><path fill="url(#i8jrcoe)" class="gb6x2dbgd"/><path fill="url(#iwBD42c)" class="gb6x2dbgd"/><path fill="url(#iFMbnLc)" class="gb6x2dbgd"/><g filter="url(#iPAfsqU)"><path class="er9mpubba"/></g><path fill="url(#iXGPcxc)" class="dks02dh2b"/><path fill="url(#i1R420d)" class="dks02dh2b"/><path fill="url(#isZdzpb)" class="dks02dh2b"/><path fill="url(#i8zCdMb)" class="dks02dh2b"/><path fill="url(#iexbn3b)" class="dks02dh2b"/><path fill="url(#i5W57Pb)" class="dks02dh2b"/><path fill="url(#iLQz2ae)" class="dks02dh2b"/><path fill="url(#ioAwGkc)" class="omfjjubqy"/><path fill="url(#i14zSJc)" class="omfjjubqy"/><path fill="url(#iAtMGIb)" class="omfjjubqy"/><path fill="url(#iATZjnd)" class="omfjjubqy"/><path fill="url(#i3B685c)" class="omfjjubqy"/><rect transform="rotate(-26.783 21.988 4.132)" class="oc6g7x22m"/><rect fill="url(#irmV0Vd)" transform="rotate(-26.783 22.422 3.872)" class="s851v_bur"/><rect fill="url(#iDpI9Xb)" transform="rotate(-26.783 22.94 3.626)" class="dc_jxg_1l"/><rect fill="url(#iR4uGBd)" transform="rotate(-26.783 23.51 3.372)" class="btf6l4b4i"/><rect fill="url(#iCuZp1d)" transform="rotate(60 23.314 4.403)" class="xp9pwx_ha"/><g filter="url(#ig9MDPc)"><path class="f170iebxz"/><path fill="url(#i33y9ib)" class="c6vkf0h9j"/></g><g filter="url(#iPsMp6d)"><path fill="url(#iW9sR7c)" class="aq2-7whxw"/><path fill="url(#i1FbDnd)" class="aq2-7whxw"/><path fill="url(#i6CSeId)" class="aq2-7whxw"/></g><g filter="url(#ianjigc)"><path class="l_ckwhb9r"/></g><g filter="url(#i10vbZd)"><path stroke="url(#ibNnaFd)" class="pidgffbsc"/></g><g filter="url(#iKFlp1J)"><path fill="url(#ike0iiB)" class="sui_jrb9y"/></g><g filter="url(#imvPRKe)"><path fill="url(#iZ9zzDc)" class="e8xte4b3g"/></g><g filter="url(#ig29bBc)"><circle fill="url(#iQooCRb)" transform="rotate(-30 14.198 7.273)" class="c5qwelj1l"/></g><g filter="url(#ijlDWTc)"><circle fill="url(#iBbS07d)" transform="rotate(-30 14.198 7.273)" class="xvz-o2bcg"/></g><g filter="url(#i8e6ofb)"><circle fill="url(#i95hP8b)" transform="rotate(-30 17.7 5.25)" class="zjzbcmb2n"/><circle fill="url(#i35paHe)" transform="rotate(-30 17.7 5.25)" class="zjzbcmb2n"/></g><g filter="url(#iVysZWk)"><circle transform="rotate(-30 17.7 5.25)" class="d4xuw7bjr"/><circle fill="url(#idNkY3d)" transform="rotate(-30 17.7 5.25)" class="uosjpoy0e"/><circle fill="url(#iPuGBMd)" transform="rotate(-30 17.7 5.25)" class="uosjpoy0e"/></g><path fill="url(#ij5WQFe)" class="mcpykob7d"/><path fill="url(#ih5TBUd)" class="mcpykob7d"/><path fill="url(#i9clysc)" class="mcpykob7d"/><path fill="url(#iGT5avd)" class="mcpykob7d"/><path fill="url(#ikgjPrb)" class="mcpykob7d"/><path fill="url(#iG7vizc)" class="mcpykob7d"/><path fill="url(#iE1kuJb)" class="mcpykob7d"/><g filter="url(#iNlzYTd)"><path class="zbwbhx56n"/></g><g filter="url(#iRJIIBa)"><path class="xdmtkua_d"/><path fill="url(#ipVlWBe)" class="d3q1_9w8e"/><path fill="url(#iVpjIEd)" class="d3q1_9w8e"/><path fill="url(#iil1ofe)" class="d3q1_9w8e"/><path fill="url(#iB1eifc)" class="d3q1_9w8e"/></g><path stroke="url(#iLmtQVw)" class="yyxd21bco"/><path class="zwsi1kjqc"/><path fill="url(#irRXyKe)" class="z49qrhsnq"/><path class="dvezfz-li"/><g filter="url(#iW6Pbbt)"><path class="hyb4lobxd"/><path fill="url(#iCzFPlb)" class="ixyzei14o"/></g><g filter="url(#i6A38fQ)"><path fill="url(#icF1Rrb)" class="f4ps997vu"/></g><path class="qlv89tbhw"/><path fill="url(#iD8GAkd)" class="ir4zxp73q"/><path class="pn93i4bwm"/><g filter="url(#i7lhZDd)"><path fill="url(#ikcuVLe)" class="fxpscq3gj"/></g><g filter="url(#iv8qQme)"><ellipse transform="rotate(-57.914 14.877 6.5)" class="lo46ovlqs"/><ellipse fill="url(#ilQb3te)" transform="rotate(-57.914 14.877 6.5)" class="qb19334yk"/></g><g filter="url(#iJZzfMc)"><path clip-rule="evenodd" class="q7hv2ry7g"/></g><g filter="url(#i3lFbxt)"><path clip-rule="evenodd" class="jwwj-xvwr"/></g><path fill="url(#ikjJDjd)" class="ajq68ibwt"/><path fill="url(#iXlcqGe)" class="ajq68ibwt"/><path fill="url(#ierfM7o)" class="jyns-8j0n"/><path fill="url(#imMuHMr)" class="jyns-8j0n"/><g filter="url(#i7jFCKc)"><path fill="url(#ietM7oU)" class="tyj1z4y8e"/><path fill="url(#iZC5CRd)" class="tyj1z4y8e"/></g><path fill="url(#iJzowhb)" class="cp95l8b8v"/><path fill="url(#irIfDpc)" class="cp95l8b8v"/><path fill="url(#iVd3z4c)" class="cp95l8b8v"/><path fill="url(#i18yljb)" class="cp95l8b8v"/><defs><radialGradient id="i6MWe8c" cx="0" cy="0" r="1" gradientTransform="rotate(146.915 9.437 6.131)scale(4.92324 2.04943)" gradientUnits="userSpaceOnUse"><stop class="ba1yb3bji"/><stop offset="1" class="kgrhzo17p"/></radialGradient><radialGradient id="ibRiAkc" cx="0" cy="0" r="1" gradientTransform="matrix(1.4375 -.0625 .23626 5.43402 7.847 13.71)" gradientUnits="userSpaceOnUse"><stop class="wn-t5ndzy"/><stop offset="1" class="ben4f0bqs"/></radialGradient><radialGradient id="isG7eBe" cx="0" cy="0" r="1" gradientTransform="matrix(-.27344 .16016 -.21807 -.37232 26.179 2.965)" gradientUnits="userSpaceOnUse"><stop offset=".181" class="i42zc8m6u"/><stop offset="1" class="dsumrvbgt"/></radialGradient><radialGradient id="i8jrcoe" cx="0" cy="0" r="1" gradientTransform="matrix(-.875 -.46876 .24583 -.45888 15.472 29.57)" gradientUnits="userSpaceOnUse"><stop class="ynlfw99ba"/><stop offset="1" class="in-vfpgwh"/></radialGradient><radialGradient id="iwBD42c" cx="0" cy="0" r="1" gradientTransform="matrix(-.76562 .85157 -1.15842 -1.0415 14.081 27.062)" gradientUnits="userSpaceOnUse"><stop offset=".115" class="vkrof_bbk"/><stop offset="1" class="h8hiq33uv"/></radialGradient><radialGradient id="iFMbnLc" cx="0" cy="0" r="1" gradientTransform="matrix(.8125 .15625 -.58594 3.04687 12.706 28.46)" gradientUnits="userSpaceOnUse"><stop class="ilg8l_bzj"/><stop offset="1" class="s2j02zbkr"/></radialGradient><radialGradient id="i1R420d" cx="0" cy="0" r="1" gradientTransform="matrix(2.71873 -2.53127 .81258 .87276 14.504 28.023)" gradientUnits="userSpaceOnUse"><stop class="pcvpzjboo"/><stop offset="1" class="qe_2d-buv"/></radialGradient><radialGradient id="isZdzpb" cx="0" cy="0" r="1" gradientTransform="matrix(2.54688 -2.64063 .2894 .27913 13.613 26.367)" gradientUnits="userSpaceOnUse"><stop offset=".285" class="kxzgmzb5t"/><stop offset="1" class="xhu8yhbcw"/></radialGradient><radialGradient id="i8zCdMb" cx="0" cy="0" r="1" gradientTransform="matrix(-.76563 0 0 -5.02098 18.706 21.71)" gradientUnits="userSpaceOnUse"><stop offset=".001" class="keljo6scd"/><stop offset="1" class="ps4m-ab9c"/></radialGradient><radialGradient id="iexbn3b" cx="0" cy="0" r="1" gradientTransform="matrix(.04687 -.98437 1.15192 .05485 18.956 18.383)" gradientUnits="userSpaceOnUse"><stop offset=".154" class="w5oxhdc5r"/><stop offset="1" class="ebs2-pbbe"/></radialGradient><radialGradient id="i5W57Pb" cx="0" cy="0" r="1" gradientTransform="matrix(.78125 0 0 7.6823 19.316 23.07)" gradientUnits="userSpaceOnUse"><stop class="j_l_30buh"/><stop offset="1" class="xi8fv135v"/></radialGradient><radialGradient id="iLQz2ae" cx="0" cy="0" r="1" gradientTransform="matrix(3.40625 -3.34375 1.20794 1.23052 15.003 28.086)" gradientUnits="userSpaceOnUse"><stop class="ddjhanboc"/><stop offset="1" class="uu7_gub8n"/></radialGradient><radialGradient id="ioAwGkc" cx="0" cy="0" r="1" gradientTransform="rotate(150.356 9.234 7.823)scale(4.42262 6.15908)" gradientUnits="userSpaceOnUse"><stop class="no0_3dbdi"/><stop offset="1" class="truekjbvb"/></radialGradient><radialGradient id="i14zSJc" cx="0" cy="0" r="1" gradientTransform="matrix(.57404 2.73801 -4.6268 .97003 18.617 7.348)" gradientUnits="userSpaceOnUse"><stop offset=".306" class="kdxlabb_n"/><stop offset="1" class="x9_x14ckq"/></radialGradient><radialGradient id="iATZjnd" cx="0" cy="0" r="1" gradientTransform="matrix(.87501 1.59375 -2.6006 1.4278 16.629 8.054)" gradientUnits="userSpaceOnUse"><stop offset=".285" class="v2g8x4brb"/><stop offset="1" class="we0trlbug"/></radialGradient><radialGradient id="i3B685c" cx="0" cy="0" r="1" gradientTransform="matrix(1.71875 -.01563 .0588 6.46896 14.816 10.46)" gradientUnits="userSpaceOnUse"><stop class="qg0h4w_kv"/><stop offset="1" class="iich1wbqp"/></radialGradient><radialGradient id="irmV0Vd" cx="0" cy="0" r="1" gradientTransform="matrix(-.64636 .00475 -.0063 -.85808 23.098 4.54)" gradientUnits="userSpaceOnUse"><stop offset=".183" class="vr6433bkq"/><stop offset="1" class="t8qn07erm"/></radialGradient><radialGradient id="iDpI9Xb" cx="0" cy="0" r="1" gradientTransform="matrix(-.64636 .00475 -.0063 -.85808 23.617 4.294)" gradientUnits="userSpaceOnUse"><stop offset=".183" class="vr6433bkq"/><stop offset="1" class="t8qn07erm"/></radialGradient><radialGradient id="iR4uGBd" cx="0" cy="0" r="1" gradientTransform="matrix(-.64636 .00475 -.0063 -.85808 24.186 4.04)" gradientUnits="userSpaceOnUse"><stop offset=".183" class="vr6433bkq"/><stop offset="1" class="t8qn07erm"/></radialGradient><radialGradient id="iCuZp1d" cx="0" cy="0" r="1" gradientTransform="matrix(-.02457 .47352 -.46721 -.02424 23.706 4.556)" gradientUnits="userSpaceOnUse"><stop class="c0oxjfd3m"/><stop offset="1" class="hswco7bmy"/></radialGradient><radialGradient id="i33y9ib" cx="0" cy="0" r="1" gradientTransform="matrix(3.80388 .30087 -.62375 7.88601 18.914 5.695)" gradientUnits="userSpaceOnUse"><stop offset=".629" class="fka-wz-bu"/><stop offset="1" class="vlsksmbwa"/></radialGradient><radialGradient id="i1FbDnd" cx="0" cy="0" r="1" gradientTransform="matrix(1.71875 .21244 -.56207 4.54749 15.38 9.868)" gradientUnits="userSpaceOnUse"><stop offset=".204" class="v__i2ebru"/><stop offset="1" class="yrm14tb3b"/></radialGradient><radialGradient id="i6CSeId" cx="0" cy="0" r="1" gradientTransform="matrix(.04687 .51562 -1.9883 .18075 17.519 8.851)" gradientUnits="userSpaceOnUse"><stop class="hnewum4zo"/><stop offset="1" class="j297-pbqp"/></radialGradient><radialGradient id="iQooCRb" cx="0" cy="0" r="1" gradientTransform="matrix(.746 0 0 1.3055 13.488 7.273)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="crp6d4bqv"/><stop offset="1" class="lu78seb9e"/></radialGradient><radialGradient id="i35paHe" cx="0" cy="0" r="1" gradientTransform="matrix(.35143 -.2559 .29207 .40112 17.858 5.138)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="wdqn7tq-u"/><stop offset="1" class="r3t82tbzk"/></radialGradient><radialGradient id="idNkY3d" cx="0" cy="0" r="1" gradientTransform="rotate(-61.467 13.55 -12.07)scale(.7309 .4278)" gradientUnits="userSpaceOnUse"><stop offset=".755" class="n7c5lw_4k"/><stop offset=".916" class="bw8j_5egh"/></radialGradient><radialGradient id="iPuGBMd" cx="0" cy="0" r="1" gradientTransform="matrix(.11022 .1091 -.14065 .1421 17.7 5.25)" gradientUnits="userSpaceOnUse"><stop class="fa9i5bbvu"/><stop offset="1" class="x8d9utbsu"/></radialGradient><radialGradient id="ih5TBUd" cx="0" cy="0" r="1" gradientTransform="matrix(2.00548 3.47358 -4.70318 2.71538 15.559 5.542)" gradientUnits="userSpaceOnUse"><stop offset=".557" class="wy3nzacst"/><stop offset="1" class="cmee_8bgn"/></radialGradient><radialGradient id="ikgjPrb" cx="0" cy="0" r="1" gradientTransform="matrix(-.27782 -.4812 .59073 -.34106 16.549 5.292)" gradientUnits="userSpaceOnUse"><stop class="m459pab_j"/><stop offset="1" class="rcuz4uefu"/></radialGradient><radialGradient id="iG7vizc" cx="0" cy="0" r="1" gradientTransform="matrix(-.29563 -.51205 .63515 -.3667 14.869 6.244)" gradientUnits="userSpaceOnUse"><stop class="hplqxft1w"/><stop offset="1" class="ay1rn8bxh"/></radialGradient><radialGradient id="iE1kuJb" cx="0" cy="0" r="1" gradientTransform="rotate(75.651 4.468 11.692)scale(2.08053 2.36143)" gradientUnits="userSpaceOnUse"><stop class="gkl69gbyj"/><stop offset="1" class="aoj5wwr9a"/></radialGradient><radialGradient id="iB1eifc" cx="0" cy="0" r="1" gradientTransform="matrix(.04185 .07249 -.23289 .13446 16.408 6.786)" gradientUnits="userSpaceOnUse"><stop class="a7vfdrbiy"/><stop offset="1" class="x6mjr8bji"/></radialGradient><radialGradient id="irRXyKe" cx="0" cy="0" r="1" gradientTransform="rotate(60 3.495 17.153)scale(.34481 .54847)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iCzFPlb" cx="0" cy="0" r="1" gradientTransform="rotate(-157.814 8.82 1.193)scale(.16044 .22089)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iD8GAkd" cx="0" cy="0" r="1" gradientTransform="matrix(.17242 .29863 -.475 .27425 14.997 6.477)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="ilQb3te" cx="0" cy="0" r="1" gradientTransform="matrix(-.00329 -.20999 .25241 -.00395 14.87 6.633)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iXlcqGe" cx="0" cy="0" r="1" gradientTransform="rotate(-126.58 8.554 .041)scale(.57321 .14488)" gradientUnits="userSpaceOnUse"><stop class="bt8p5ibtm"/><stop offset="1" class="lzg318lcd"/></radialGradient><radialGradient id="imMuHMr" cx="0" cy="0" r="1" gradientTransform="matrix(-.23506 .12042 -.71 -1.3859 17.73 4.446)" gradientUnits="userSpaceOnUse"><stop offset=".219" class="h07hjeb1k"/><stop offset="1" class="x75d2ntsx"/></radialGradient><radialGradient id="ietM7oU" cx="0" cy="0" r="1" gradientTransform="rotate(-33.523 16.76 -19.868)scale(3.27164 12.1234)" gradientUnits="userSpaceOnUse"><stop class="fn7-6xayh"/><stop offset="1" class="chayuvnap"/></radialGradient><radialGradient id="iZC5CRd" cx="0" cy="0" r="1" gradientTransform="matrix(-.0178 -.6345 1.1245 -.03153 16.357 4.561)" gradientUnits="userSpaceOnUse"><stop class="sylx2mbjo"/><stop offset="1" class="nav-8e2lo"/></radialGradient><radialGradient id="iJzowhb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.50458 1.26263 -1.20386 -2.388 16.02 3.918)" gradientUnits="userSpaceOnUse"><stop class="blekadc8f"/><stop offset="1" class="c6xk9jx7z"/></radialGradient><radialGradient id="irIfDpc" cx="0" cy="0" r="1" gradientTransform="matrix(.09101 -2.41554 3.7426 .14102 13.41 5.946)" gradientUnits="userSpaceOnUse"><stop class="jjpmu-56c"/><stop offset="1" class="ldm9khd7d"/></radialGradient><radialGradient id="iVd3z4c" cx="0" cy="0" r="1" gradientTransform="rotate(-115.648 9.044 -2.349)scale(1.02519 2.26696)" gradientUnits="userSpaceOnUse"><stop offset=".155" class="o2ca957_x"/><stop offset="1" class="a7xagmxua"/></radialGradient><radialGradient id="i18yljb" cx="0" cy="0" r="1" gradientTransform="matrix(.34824 .52998 -2.8769 1.89034 14.009 2.929)" gradientUnits="userSpaceOnUse"><stop class="uw0kegb-q"/><stop offset="1" class="ydllxhbat"/></radialGradient><linearGradient id="iJt5yHd" x1="24.351" x2="21.294" y1="5.136" y2="11.141" gradientUnits="userSpaceOnUse"><stop class="dleo9dcux"/><stop offset=".799" class="cqf-ohbhv"/></linearGradient><linearGradient id="i4J3ECd" x1="13.831" x2="14.159" y1="9.567" y2="10.039" gradientUnits="userSpaceOnUse"><stop offset=".349" class="lr97j31fb"/><stop offset="1" class="azn0z--js"/></linearGradient><linearGradient id="imXIVRb" x1="26.253" x2="24.113" y1="3.086" y2="4.398" gradientUnits="userSpaceOnUse"><stop class="ds3hm--8v"/><stop offset="1" class="bq7w62n5j"/></linearGradient><linearGradient id="iPMqXAG" x1="25.222" x2="24.956" y1="4.086" y2="3.554" gradientUnits="userSpaceOnUse"><stop class="seeiowbir"/><stop offset="1" class="tw6dxpb7y"/></linearGradient><linearGradient id="iEKUpld" x1="14.034" x2="14.034" y1="30.422" y2="29.75" gradientUnits="userSpaceOnUse"><stop class="dhem-xbnm"/><stop offset="1" class="zn47ozbfv"/></linearGradient><linearGradient id="iXGPcxc" x1="21.816" x2="21.222" y1="22.961" y2="22.929" gradientUnits="userSpaceOnUse"><stop class="ieaclmdnn"/><stop offset="1" class="p3yd_be1u"/></linearGradient><linearGradient id="iAtMGIb" x1="18.617" x2="18.617" y1="16.367" y2="13.179" gradientUnits="userSpaceOnUse"><stop offset=".039" class="ptputobcp"/><stop offset="1" class="br5umybnw"/></linearGradient><linearGradient id="iW9sR7c" x1="17.348" x2="17.348" y1="8.75" y2="10.961" gradientUnits="userSpaceOnUse"><stop class="bw1hkxbcb"/><stop offset="1" class="tesa8u_3j"/></linearGradient><linearGradient id="ibNnaFd" x1="21.081" x2="21.081" y1="16.992" y2="27.898" gradientUnits="userSpaceOnUse"><stop class="hd06b2knh"/><stop offset="1" class="ggughpb3d"/></linearGradient><linearGradient id="ike0iiB" x1="17.644" x2="17.644" y1="18.429" y2="24.992" gradientUnits="userSpaceOnUse"><stop class="y6ovumr8k"/><stop offset="1" class="t-eeezbdl"/></linearGradient><linearGradient id="iZ9zzDc" x1="15.308" x2="15.233" y1="6.334" y2="6.472" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iBbS07d" x1="14.198" x2="13.926" y1="7.391" y2="7.391" gradientUnits="userSpaceOnUse"><stop class="wachewblq"/><stop offset="1" class="px4pa2bzd"/></linearGradient><linearGradient id="i95hP8b" x1="18.162" x2="17.814" y1="4.787" y2="5.865" gradientUnits="userSpaceOnUse"><stop class="fuy988_rs"/><stop offset="1" class="h2u-65bda"/></linearGradient><linearGradient id="ij5WQFe" x1="17.522" x2="14.958" y1="5.545" y2="7.581" gradientUnits="userSpaceOnUse"><stop class="z8y6fgvmn"/><stop offset="1" class="tqgh1edwg"/></linearGradient><linearGradient id="i9clysc" x1="14.293" x2="15.55" y1="8.159" y2="7.489" gradientUnits="userSpaceOnUse"><stop class="z3n_1mwef"/><stop offset="1" class="rvf3-0bfj"/></linearGradient><linearGradient id="iGT5avd" x1="14.632" x2="15.308" y1="8.537" y2="8.114" gradientUnits="userSpaceOnUse"><stop class="hmo3unbrx"/><stop offset="1" class="yyvs3obha"/></linearGradient><linearGradient id="ipVlWBe" x1="15.851" x2="16.196" y1="6.833" y2="6.634" gradientUnits="userSpaceOnUse"><stop class="h7h6nwjtb"/><stop offset="1" class="btip4dbzo"/></linearGradient><linearGradient id="iVpjIEd" x1="16.583" x2="16.202" y1="6.569" y2="6.782" gradientUnits="userSpaceOnUse"><stop class="ag4c77bht"/><stop offset="1" class="qb120pbsb"/></linearGradient><linearGradient id="iil1ofe" x1="16.467" x2="16.345" y1="7" y2="6.789" gradientUnits="userSpaceOnUse"><stop class="rlzetx3ey"/><stop offset="1" class="zf2atv-8x"/></linearGradient><linearGradient id="iLmtQVw" x1="16.357" x2="16.371" y1="7.857" y2="7.511" gradientUnits="userSpaceOnUse"><stop class="ry99b_nji"/><stop offset=".663" class="g6x9xncjt"/></linearGradient><linearGradient id="icF1Rrb" x1="16.901" x2="16.826" y1="5.404" y2="5.542" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ikcuVLe" x1="15.282" x2="15.207" y1="6.338" y2="6.476" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ikjJDjd" x1="13.6" x2="13.407" y1="6.459" y2="6.57" gradientUnits="userSpaceOnUse"><stop class="wr-njxl9j"/><stop offset="1" class="qxarokbzg"/></linearGradient><linearGradient id="ierfM7o" x1="17.077" x2="17.609" y1="3.951" y2="4.872" gradientUnits="userSpaceOnUse"><stop class="h2k47rign"/><stop offset="1" class="d9ll53bvt"/></linearGradient><filter id="i4X72Pc" width="8.471" height="7.176" x="17.558" y="3.965" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.847059 0 0 0 0 0.6 0 0 0 0 0.517647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22985"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.921569 0 0 0 0 0.682353 0 0 0 0 0.580392 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_22985" result="effect2_innerShadow_3987_22985"/></filter><filter id="i64Y0uc" width="18.187" height="14.194" x="8.244" y="2.37" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.568627 0 0 0 0 0.454902 0 0 0 0 0.647059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22985"/></filter><filter id="iFMSoee" width="4.793" height="2.27" x="19.515" y="28.004" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.262745 0 0 0 0 0.188235 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22985"/></filter><filter id="iPAfsqU" width="8.989" height="12.477" x="13.498" y="16.039" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.67451 0 0 0 0 0.635294 0 0 0 0 0.686275 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22985"/></filter><filter id="ig9MDPc" width="7.553" height="7.567" x="15.688" y="3.925" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.87451 0 0 0 0 0.647059 0 0 0 0 0.54902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22985"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.858824 0 0 0 0 0.611765 0 0 0 0 0.580392 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_22985" result="effect2_innerShadow_3987_22985"/></filter><filter id="iPsMp6d" width="3.395" height="2.909" x="15.65" y="8.5" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.145098 0 0 0 0 0.4 0 0 0 0 0.835294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22985"/></filter><filter id="ianjigc" width="1.789" height="3.497" x="9.424" y="12.658" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22985" stdDeviation=".125"/></filter><filter id="i10vbZd" width="2.601" height="13.601" x="19.765" y="15.504" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22985" stdDeviation=".4"/></filter><filter id="iKFlp1J" width="2.563" height="7.453" x="16.362" y="16.945" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22985" stdDeviation=".375"/></filter><filter id="imvPRKe" width=".671" height=".659" x="14.917" y="6.079" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22985" stdDeviation=".1"/></filter><filter id="ig29bBc" width="1.62" height="1.42" x="13.488" y="6.563" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.917647 0 0 0 0 0.694118 0 0 0 0 0.607843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22985"/></filter><filter id="ijlDWTc" width="1.846" height="1.846" x="13.275" y="6.35" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22985" stdDeviation=".25"/></filter><filter id="i8e6ofb" width="1.67" height="1.67" x="16.99" y="4.291" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.843137 0 0 0 0 0.623529 0 0 0 0 0.580392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22985"/></filter><filter id="iVysZWk" width="1.846" height="1.846" x="16.777" y="4.328" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22985" stdDeviation=".25"/></filter><filter id="iNlzYTd" width="2.276" height="2.633" x="15.057" y="5.376" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22985" stdDeviation=".375"/></filter><filter id="iRJIIBa" width="1.116" height="1.326" x="15.64" y="5.931" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22985" stdDeviation=".05"/></filter><filter id="iW6Pbbt" width=".372" height=".474" x="16.267" y="5.353" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22985" stdDeviation=".05"/></filter><filter id="i6A38fQ" width=".618" height=".619" x="16.541" y="5.169" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22985" stdDeviation=".1"/></filter><filter id="i7lhZDd" width=".67" height=".659" x="14.891" y="6.083" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22985" stdDeviation=".1"/></filter><filter id="iv8qQme" width=".426" height=".494" x="14.664" y="6.252" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22985" stdDeviation=".05"/></filter><filter id="iJZzfMc" width="1.355" height="1.003" x="15.732" y="3.963" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0196078 0 0 0 0 0.027451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22985"/></filter><filter id="i3lFbxt" width="1.168" height="1.316" x="13.937" y="4.902" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0196078 0 0 0 0 0.027451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22985"/></filter><filter id="i7jFCKc" width="4.108" height="2.642" x="13.173" y="3.655" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.160784 0 0 0 0 0.396078 0 0 0 0 0.721569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22985"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-golfing-light" /></template>
<style>
.a7vfdrbiy {
  stop-color: var(--svg-color--ffd7c1, #FFD7C1);
}

.a7xagmxua {
  stop-color: var(--svg-color--1a7ccc, #1A7CCC);
  stop-opacity: 0;
}

.ag4c77bht {
  stop-color: var(--svg-color--ffdfc4, #FFDFC4);
}

.ajq68ibwt {
  d: path("m13.607 6.916l-.497-.862l.44-.254a.8.8 0 0 1-.01.343a.5.5 0 0 0 .06.361l.296.512c-.099.057-.225.02-.289-.1");
}

.aoj5wwr9a {
  stop-color: var(--svg-color--a67e9c, #A67E9C);
  stop-opacity: 0;
}

.aq2-7whxw {
  d: path("M17.339 8.965a2.8 2.8 0 0 0 .847-.215l.86 2.195c-.235.121-1.715.594-2.54.43c-.824-.164-1.019-1.196-.73-1.739c.274-.609 1.118-.63 1.563-.671");
}

.ay1rn8bxh {
  stop-color: var(--svg-color--d0958d, #D0958D);
  stop-opacity: 0;
}

.azn0z--js {
  stop-color: var(--svg-color--b39fbc, #B39FBC);
  stop-opacity: 0;
}

.ba1yb3bji {
  stop-color: var(--svg-color--a99797, #A99797);
}

.ben4f0bqs {
  stop-color: var(--svg-color--b8acbd, #B8ACBD);
  stop-opacity: 0;
}

.blekadc8f {
  stop-color: var(--svg-color--30a2e5, #30A2E5);
}

.bq7w62n5j {
  stop-color: var(--svg-color--482a5b, #482A5B);
}

.br5umybnw {
  stop-color: var(--svg-color--366bc5, #366BC5);
  stop-opacity: 0;
}

.bt8p5ibtm {
  stop-color: var(--svg-color--4f4c4b, #4F4C4B);
}

.btf6l4b4i {
  width: 0.692px;
  height: 1.157px;
  x: 23.51px;
  y: 3.372px;
  rx: 0.346px;
}

.btip4dbzo {
  stop-color: var(--svg-color--dfa790, #DFA790);
  stop-opacity: 0;
}

.bw1hkxbcb {
  stop-color: var(--svg-color--2d9de0, #2D9DE0);
}

.bw8j_5egh {
  stop-color: var(--svg-color--d6a38d, #D6A38D);
}

.c0oxjfd3m {
  stop-color: var(--svg-color--e7b6a5, #E7B6A5);
}

.c5qwelj1l {
  cx: 14.198px;
  cy: 7.273px;
  r: 0.71px;
}

.c6vkf0h9j {
  d: path("M20.655 6.085a.5.5 0 0 0-.015-.253a5 5 0 0 0-.227-.524c-.02-.088-.025-.29.11-.39a.36.36 0 0 1 .335-.055a.45.45 0 0 1 .207-.285c.135-.072.298-.03.364 0c.018-.067.09-.209.23-.246a.52.52 0 0 1 .356.058c.04-.075.168-.224.359-.215c.238.012.375.262.41.45c.035.187.094.433.152.578c.059.144.118.605-.09 1.199c-.454 1.884-1.492 3.103-2.664 3.853c-1.184.758-2.454 1.008-3.297 1.083a1.1 1.1 0 1 1-.193-2.192c.636-.056 1.522-.243 2.304-.744c.682-.436 1.327-1.135 1.659-2.317");
}

.c6xk9jx7z {
  stop-color: var(--svg-color--1b96dc, #1B96DC);
}

.chayuvnap {
  stop-color: var(--svg-color--1d78b8, #1D78B8);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cmee_8bgn {
  stop-color: var(--svg-color--c9859b, #C9859B);
}

.cp95l8b8v {
  d: path("M14.432 2.709c.53-.306 1.129-.441 1.693-.237c.434.156.898.638 1.156 1.323a3 3 0 0 0-.973-.08a3.72 3.72 0 0 0-2.718 1.569a2.9 2.9 0 0 0-.417.883c-.466-.57-.65-1.21-.568-1.663c.105-.59.522-1.042 1.051-1.347z");
}

.cqf-ohbhv {
  stop-color: var(--svg-color--e0a598, #E0A598);
}

.crp6d4bqv {
  stop-color: var(--svg-color--cf9888, #CF9888);
}

.d3q1_9w8e {
  d: path("m15.745 6.24l.165.739a.23.23 0 0 0 .34.146l.29-.167a.23.23 0 0 0 .043-.368l-.557-.513c-.122-.114-.318-.001-.281.163");
}

.d4xuw7bjr {
  cx: 17.7px;
  cy: 5.251px;
  r: 0.423px;
  fill: var(--svg-color--e4af9a, #E4AF9A);
}

.d5cxx-l5u {
  fill: var(--svg-color--47385d, #47385D);
  d: path("M12.933 27.883c0-.807.458-1.16.687-1.235l1.367 1.18v1.283a.5.5 0 0 0 .188.39l.203.163c.127.094.297.238.25.414c-.082.172-.25.195-.54.195h-1.505a.65.65 0 0 1-.65-.65z");
}

.d9ll53bvt {
  stop-color: var(--svg-color--1e1521, #1E1521);
}

.dc_jxg_1l {
  width: 0.692px;
  height: 1.157px;
  x: 22.941px;
  y: 3.626px;
  rx: 0.346px;
}

.ddjhanboc {
  stop-color: var(--svg-color--8c6fa7, #8C6FA7);
}

.dhem-xbnm {
  stop-color: var(--svg-color--442563, #442563);
}

.dks02dh2b {
  d: path("M15.86 24.041a1 1 0 0 0 .274-.712l-.166-7.29h6.02l-.313 12.476H19.52l-.26-10.002a.255.255 0 0 0-.508-.004c-.05 1.195-.13 3.454-.13 4.584c0 1.213-.693 2.214-1.04 2.563l-2.472 2.288a.32.32 0 0 1-.317.081a2.2 2.2 0 0 1-.719-.424c-.252-.224-.438-.552-.546-.795a.36.36 0 0 1 .077-.392z");
}

.dleo9dcux {
  stop-color: var(--svg-color--e9b9a9, #E9B9A9);
}

.ds3hm--8v {
  stop-color: var(--svg-color--533d66, #533D66);
}

.dsumrvbgt {
  stop-color: var(--svg-color--615273, #615273);
  stop-opacity: 0;
}

.dvezfz-li {
  fill: var(--svg-color--000, #000);
  d: path("M16.504 5.81a.216.216 0 0 1 .08-.296a.216.216 0 0 1 .326.178l-.334.192a.2.2 0 0 1-.072-.074");
}

.dxctj8e-g {
  d: path("m23.103 5.351l-.5-.866l3.121-1.859a.4.4 0 0 1 .548.14l.103.171a.4.4 0 0 1-.14.549z");
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e8xte4b3g {
  d: path("M15.388 6.414c-.062-.107-.189-.127-.224-.135l-.047.163l.142.096z");
}

.ebs2-pbbe {
  stop-color: var(--svg-color--9c8cad, #9C8CAD);
  stop-opacity: 0;
}

.er9mpubba {
  fill: var(--svg-color--9785a9, #9785A9);
  d: path("M15.86 24.041a1 1 0 0 0 .274-.712l-.166-7.29h6.02l-.313 12.476H19.52l-.26-10.002a.255.255 0 0 0-.508-.004c-.05 1.195-.13 3.454-.13 4.584c0 1.213-.693 2.214-1.04 2.563l-2.472 2.288a.32.32 0 0 1-.317.081a2.2 2.2 0 0 1-.719-.424c-.252-.224-.438-.552-.546-.795a.36.36 0 0 1 .077-.392z");
}

.f170iebxz {
  fill: var(--svg-color--e7b39d, #E7B39D);
  d: path("M20.655 6.085a.5.5 0 0 0-.015-.253a5 5 0 0 0-.227-.524c-.02-.088-.025-.29.11-.39a.36.36 0 0 1 .335-.055a.45.45 0 0 1 .207-.285c.135-.072.298-.03.364 0c.018-.067.09-.209.23-.246a.52.52 0 0 1 .356.058c.04-.075.168-.224.359-.215c.238.012.375.262.41.45c.035.187.094.433.152.578c.059.144.118.605-.09 1.199c-.454 1.884-1.492 3.103-2.664 3.853c-1.184.758-2.454 1.008-3.297 1.083a1.1 1.1 0 1 1-.193-2.192c.636-.056 1.522-.243 2.304-.744c.682-.436 1.327-1.135 1.659-2.317");
}

.f4ps997vu {
  d: path("M16.96 5.49a.36.36 0 0 0-.184-.121l-.035.16l.092.059z");
}

.fa9i5bbvu {
  stop-color: var(--svg-color--d5a58e, #D5A58E);
}

.fka-wz-bu {
  stop-color: var(--svg-color--e4b79d, #E4B79D);
  stop-opacity: 0;
}

.fn7-6xayh {
  stop-color: var(--svg-color--3e82bc, #3E82BC);
}

.ft5dv1b6b {
  fill: none;
}

.fuy988_rs {
  stop-color: var(--svg-color--fbd3bd, #FBD3BD);
}

.fxpscq3gj {
  d: path("M15.362 6.418c-.062-.106-.188-.127-.224-.135l-.047.164l.142.095z");
}

.g6x9xncjt {
  stop-color: var(--svg-color--e2b0a6, #E2B0A6);
  stop-opacity: 0;
}

.gb6x2dbgd {
  d: path("M12.933 27.883c0-.807.458-1.16.687-1.235l1.367 1.18v1.283a.5.5 0 0 0 .188.39l.203.163c.127.094.297.238.25.414c-.082.172-.25.195-.54.195h-1.505a.65.65 0 0 1-.65-.65z");
}

.ggughpb3d {
  stop-color: var(--svg-color--a599b3, #A599B3);
}

.gkl69gbyj {
  stop-color: var(--svg-color--a67e9c, #A67E9C);
}

.h07hjeb1k {
  stop-color: var(--svg-color--413f3f, #413F3F);
}

.h2k47rign {
  stop-color: var(--svg-color--241521, #241521);
}

.h2u-65bda {
  stop-color: var(--svg-color--f0b8a4, #F0B8A4);
}

.h7h6nwjtb {
  stop-color: var(--svg-color--dfa790, #DFA790);
}

.h8hiq33uv {
  stop-color: var(--svg-color--271938, #271938);
  stop-opacity: 0;
}

.hd06b2knh {
  stop-color: var(--svg-color--a89eb3, #A89EB3);
}

.hmo3unbrx {
  stop-color: var(--svg-color--e8ad97, #E8AD97);
}

.hnewum4zo {
  stop-color: var(--svg-color--2f89b9, #2F89B9);
}

.hplqxft1w {
  stop-color: var(--svg-color--d0958d, #D0958D);
}

.hswco7bmy {
  stop-color: var(--svg-color--e2ac98, #E2AC98);
}

.hyb4lobxd {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M16.518 5.457c.041.018.015.084-.017.158c-.032.073-.056.126-.097.109c-.042-.018-.05-.092-.018-.166c.032-.073.09-.118.132-.1");
}

.i42zc8m6u {
  stop-color: var(--svg-color--615273, #615273);
}

.ieaclmdnn {
  stop-color: var(--svg-color--a19ca8, #A19CA8);
}

.iich1wbqp {
  stop-color: var(--svg-color--56a2e0, #56A2E0);
  stop-opacity: 0;
}

.ilg8l_bzj {
  stop-color: var(--svg-color--655e6d, #655E6D);
}

.in-vfpgwh {
  stop-color: var(--svg-color--403451, #403451);
  stop-opacity: 0;
}

.ir4zxp73q {
  d: path("M14.895 6.302a.38.38 0 0 0-.077.597l.634-.366a.382.382 0 0 0-.558-.231");
}

.ixyzei14o {
  d: path("M16.518 5.457c.041.018.015.084-.017.158c-.032.073-.056.126-.097.109c-.042-.018-.05-.092-.018-.166c.032-.073.09-.118.132-.1");
}

.j_l_30buh {
  stop-color: var(--svg-color--5d5467, #5D5467);
}

.j297-pbqp {
  stop-color: var(--svg-color--2f89b9, #2F89B9);
  stop-opacity: 0;
}

.jjpmu-56c {
  stop-color: var(--svg-color--4199e0, #4199E0);
}

.jnzd73pdm {
  fill: var(--svg-color--4c3765, #4C3765);
  d: path("M19.515 30.273v-1.77h2.16c.164.157.789.551 1.504.782c.494.131.625.488.629.621v.367z");
}

.jwwj-xvwr {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  fill-rule: evenodd;
  d: path("M14.738 5.685c-.279.128-.39.33-.408.392a.2.2 0 0 1-.384-.12c.053-.169.24-.46.625-.637a.2.2 0 0 1 .167.365");
}

.jyns-8j0n {
  d: path("m17.714 4.545l-.498-.862l-.44.254a.8.8 0 0 0 .302.163c.13.033.238.155.283.233l.278.522a.22.22 0 0 0 .075-.31");
}

.kdxlabb_n {
  stop-color: var(--svg-color--3090bc, #3090BC);
}

.keljo6scd {
  stop-color: var(--svg-color--827a8b, #827A8B);
}

.kgrhzo17p {
  stop-color: var(--svg-color--a99797, #A99797);
  stop-opacity: 0;
}

.kxzgmzb5t {
  stop-color: var(--svg-color--9f9c9d, #9F9C9D);
}

.l_ckwhb9r {
  stroke: var(--svg-color--c3b8c3, #C3B8C3);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M9.847 13.008a.53.53 0 0 0 0 .539c.131.237.719 1.277.96 1.714c.05.103.112.356-.038.543");
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.ldm9khd7d {
  stop-color: var(--svg-color--4199e0, #4199E0);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lo46ovlqs {
  cx: 14.877px;
  cy: 6.499px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.166px;
  ry: 0.084px;
}

.lr97j31fb {
  stop-color: var(--svg-color--b39fbc, #B39FBC);
}

.lu78seb9e {
  stop-color: var(--svg-color--be8c77, #BE8C77);
}

.lzg318lcd {
  stop-color: var(--svg-color--4f4c4b, #4F4C4B);
  stop-opacity: 0;
}

.m459pab_j {
  stop-color: var(--svg-color--f5b7a7, #F5B7A7);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mcpykob7d {
  d: path("M13.597 6.544c-.056-.099-.127-.264-.082-.369l-.071-.172c.053-.135.177-.11.109-.229l-.181-.314a.22.22 0 0 1 .044-.287a7 7 0 0 1 1.351-.99a7 7 0 0 1 1.532-.675a.245.245 0 0 1 .272.105l.181.315c.068.117-.185-.52-.06-.487c.26.023.669.822.742.983c.314.697.68 1.376 1.016 2.063c.317.685.067 1.435-.543 1.788l-1.182.682c-.63.364-1.385.194-1.82-.423c-.436-.637-.922-1.321-1.308-1.99");
}

.n7c5lw_4k {
  stop-color: var(--svg-color--d6a38d, #D6A38D);
  stop-opacity: 0;
}

.nav-8e2lo {
  stop-color: var(--svg-color--3386c4, #3386C4);
  stop-opacity: 0;
}

.no0_3dbdi {
  stop-color: var(--svg-color--53aff7, #53AFF7);
}

.o2ca957_x {
  stop-color: var(--svg-color--1a7ccc, #1A7CCC);
}

.oc6g7x22m {
  width: 0.692px;
  height: 1.157px;
  x: 21.988px;
  y: 4.132px;
  fill: var(--svg-color--dba489, #DBA489);
  rx: 0.346px;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.omfjjubqy {
  d: path("M15.265 9.93c.175-1.286.703-1.863 1-2.07c.51-.359 1.664-.946 3.336 0c1.757 1.093 2.403 4.056 2.375 5.374v2.805h-6v-3.242c0-.488-.106-.743-.258-.961c-.145-.258-.52-.98-.453-1.907");
}

.p2anc3byq {
  d: path("M10.286 12.984a.35.35 0 0 0-.125.474l.88 1.545a1 1 0 0 1-.374 1.364l-.115.065a1 1 0 0 1-1.363-.374l-.728-1.277a1.65 1.65 0 0 1 .617-2.25l.342-.196l16.304-9.709a.4.4 0 0 1 .548.14l.102.171a.4.4 0 0 1-.139.549z");
}

.p3yd_be1u {
  stop-color: var(--svg-color--a49faa, #A49FAA);
  stop-opacity: 0;
}

.pcvpzjboo {
  stop-color: var(--svg-color--937da8, #937DA8);
}

.pidgffbsc {
  stroke-linecap: square;
  stroke-width: var(--svg-stroke-width--0-8px, 0.8px);
  d: path("m21.16 16.71l-.188 11.188");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pn93i4bwm {
  fill: var(--svg-color--000, #000);
  d: path("M15.273 6.521a.216.216 0 0 0-.297-.08a.216.216 0 0 0-.009.372l.333-.192a.2.2 0 0 0-.027-.1");
}

.ps4m-ab9c {
  stop-color: var(--svg-color--827a8b, #827A8B);
  stop-opacity: 0;
}

.ptputobcp {
  stop-color: var(--svg-color--366bc5, #366BC5);
}

.px4pa2bzd {
  stop-color: var(--svg-color--be8474, #BE8474);
}

.q7hv2ry7g {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  fill-rule: evenodd;
  d: path("M16.049 4.929c.25-.178.48-.173.543-.159a.2.2 0 0 0 .088-.391c-.172-.04-.519-.022-.863.222a.2.2 0 0 0 .232.328");
}

.qb120pbsb {
  stop-color: var(--svg-color--ffdfc4, #FFDFC4);
  stop-opacity: 0;
}

.qb19334yk {
  cx: 14.877px;
  cy: 6.499px;
  rx: 0.166px;
  ry: 0.084px;
}

.qe_2d-buv {
  stop-color: var(--svg-color--937da8, #937DA8);
  stop-opacity: 0;
}

.qg0h4w_kv {
  stop-color: var(--svg-color--56a2e0, #56A2E0);
}

.qlv89tbhw {
  fill: var(--svg-color--fff, #fff);
  d: path("M14.76 6.246a.594.594 0 0 0-.273.677c.02.074.105.107.17.069l.822-.474a.098.098 0 0 0 .026-.149a.595.595 0 0 0-.744-.123");
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qxarokbzg {
  stop-color: var(--svg-color--423735, #423735);
}

.r3t82tbzk {
  stop-color: var(--svg-color--d9aa94, #D9AA94);
  stop-opacity: 0;
}

.rcuz4uefu {
  stop-color: var(--svg-color--f5b7a7, #F5B7A7);
  stop-opacity: 0;
}

.rlzetx3ey {
  stop-color: var(--svg-color--dc9c96, #DC9C96);
}

.rvf3-0bfj {
  stop-color: var(--svg-color--dead9d, #DEAD9D);
  stop-opacity: 0;
}

.ry99b_nji {
  stop-color: var(--svg-color--e2b0a6, #E2B0A6);
}

.s2j02zbkr {
  stop-color: var(--svg-color--655e6d, #655E6D);
  stop-opacity: 0;
}

.s851v_bur {
  width: 0.692px;
  height: 1.157px;
  x: 22.422px;
  y: 3.872px;
  rx: 0.346px;
}

.seeiowbir {
  stop-color: var(--svg-color--482c58, #482C58);
}

.sui_jrb9y {
  d: path("m17.487 23.648l-.375-5.953l1.063.5v5.453z");
}

.sylx2mbjo {
  stop-color: var(--svg-color--3386c4, #3386C4);
}

.t-eeezbdl {
  stop-color: var(--svg-color--a59ab1, #A59AB1);
  stop-opacity: 0;
}

.t8qn07erm {
  stop-color: var(--svg-color--e0a899, #E0A899);
}

.tesa8u_3j {
  stop-color: var(--svg-color--3083ea, #3083EA);
}

.tqgh1edwg {
  stop-color: var(--svg-color--eaab97, #EAAB97);
}

.truekjbvb {
  stop-color: var(--svg-color--347fda, #347FDA);
}

.tw6dxpb7y {
  stop-color: var(--svg-color--482c58, #482C58);
  stop-opacity: 0;
}

.tyj1z4y8e {
  d: path("M13.59 5.284a2.9 2.9 0 0 0-.417.883l.26.1c.194.075.416 0 .523-.18a3.4 3.4 0 0 1 1.224-1.191a3.4 3.4 0 0 1 1.645-.464a.425.425 0 0 0 .414-.362l.042-.275a3 3 0 0 0-.973-.08a3.72 3.72 0 0 0-2.718 1.57");
}

.uosjpoy0e {
  cx: 17.7px;
  cy: 5.251px;
  r: 0.423px;
}

.uu7_gub8n {
  stop-color: var(--svg-color--8c6fa7, #8C6FA7);
  stop-opacity: 0;
}

.uw0kegb-q {
  stop-color: var(--svg-color--4195cb, #4195CB);
}

.v__i2ebru {
  stop-color: var(--svg-color--579fde, #579FDE);
}

.v2g8x4brb {
  stop-color: var(--svg-color--246c9d, #246C9D);
}

.vkrof_bbk {
  stop-color: var(--svg-color--271938, #271938);
}

.vlsksmbwa {
  stop-color: var(--svg-color--e4b79d, #E4B79D);
}

.vr6433bkq {
  stop-color: var(--svg-color--ebbaaa, #EBBAAA);
}

.w5oxhdc5r {
  stop-color: var(--svg-color--7f5d9d, #7F5D9D);
}

.wachewblq {
  stop-color: var(--svg-color--ba7c6b, #BA7C6B);
}

.wdqn7tq-u {
  stop-color: var(--svg-color--d9aa94, #D9AA94);
}

.we0trlbug {
  stop-color: var(--svg-color--246c9d, #246C9D);
  stop-opacity: 0;
}

.wk56mbcaf {
  fill: var(--svg-color--afa2b8, #AFA2B8);
  d: path("M10.286 12.984a.35.35 0 0 0-.125.474l.88 1.545a1 1 0 0 1-.374 1.364l-.115.065a1 1 0 0 1-1.363-.374l-.728-1.277a1.65 1.65 0 0 1 .617-2.25l.342-.196l16.304-9.709a.4.4 0 0 1 .548.14l.102.171a.4.4 0 0 1-.139.549z");
}

.wn-t5ndzy {
  stop-color: var(--svg-color--b8acbd, #B8ACBD);
}

.wr-njxl9j {
  stop-color: var(--svg-color--1a0916, #1A0916);
}

.wy3nzacst {
  stop-color: var(--svg-color--d69e9e, #D69E9E);
  stop-opacity: 0;
}

.x6mjr8bji {
  stop-color: var(--svg-color--ffd7c1, #FFD7C1);
  stop-opacity: 0;
}

.x75d2ntsx {
  stop-color: var(--svg-color--413f3f, #413F3F);
  stop-opacity: 0;
}

.x8d9utbsu {
  stop-color: var(--svg-color--d5a58e, #D5A58E);
  stop-opacity: 0;
}

.x9_x14ckq {
  stop-color: var(--svg-color--3090bc, #3090BC);
  stop-opacity: 0;
}

.xdmtkua_d {
  fill: var(--svg-color--fbc4b1, #FBC4B1);
  d: path("m15.745 6.24l.165.739a.23.23 0 0 0 .34.146l.29-.167a.23.23 0 0 0 .043-.368l-.557-.513c-.122-.114-.318-.001-.281.163");
}

.xhu8yhbcw {
  stop-color: var(--svg-color--9f9c9d, #9F9C9D);
  stop-opacity: 0;
}

.xi8fv135v {
  stop-color: var(--svg-color--8c7e97, #8C7E97);
  stop-opacity: 0;
}

.xp9pwx_ha {
  width: 0.737px;
  height: 1.252px;
  x: 23.314px;
  y: 4.403px;
  rx: 0.369px;
}

.xvz-o2bcg {
  cx: 14.198px;
  cy: 7.273px;
  r: 0.423px;
}

.y6ovumr8k {
  stop-color: var(--svg-color--a59ab1, #A59AB1);
}

.ydllxhbat {
  stop-color: var(--svg-color--4195cb, #4195CB);
  stop-opacity: 0;
}

.ynlfw99ba {
  stop-color: var(--svg-color--403451, #403451);
}

.ynqv6932l {
  fill-rule: evenodd;
  d: path("M22.299 7.874c.852-1.082.48-2.213.219-2.677l1.915-1.082c.468.828 1.242 3.027-.406 5.12c-.89 1.13-2.33 1.567-3.484 1.753c-1.198.193-2.37.158-2.985.134l.085-2.198c.598.023 1.583.048 2.55-.108c1.012-.163 1.746-.485 2.106-.942");
}

.yrm14tb3b {
  stop-color: var(--svg-color--579fde, #579FDE);
  stop-opacity: 0;
}

.yyvs3obha {
  stop-color: var(--svg-color--e8ad97, #E8AD97);
  stop-opacity: 0;
}

.yyxd21bco {
  fill: var(--svg-color--88024e, #88024E);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M16.03 7.54c.183-.008.376-.063.556-.167a1.2 1.2 0 0 0 .423-.4a.115.115 0 0 1 .13-.048a.11.11 0 0 1 .08.114m-1.19.5l1.14-.504m-1.14.504a.115.115 0 0 0-.107.09a.11.11 0 0 0 .06.124m.047-.214l-.026.17m1.215-.67l-.05-.004m.05.004l-.05-.004m.05.004a.86.86 0 0 1-.427.688a.86.86 0 0 1-.81.026m1.188-.718a.8.8 0 0 1-.404.648a.8.8 0 0 1-.762.025m-.022.045l.022-.045m-.022.045l.022-.045");
}

.z3n_1mwef {
  stop-color: var(--svg-color--a58787, #A58787);
}

.z49qrhsnq {
  d: path("M16.502 5.373a.38.38 0 0 1 .556.233l-.634.366a.38.38 0 0 1 .078-.599");
}

.z8y6fgvmn {
  stop-color: var(--svg-color--ffdabf, #FFDABF);
}

.zbwbhx56n {
  fill: var(--svg-color--d89992, #D89992);
  d: path("m15.819 6.277l.059.8c.037.15.2.227.328.154l.272-.157c.127-.073.141-.256.03-.36l-.544-.52c-.12-.117-.184-.08-.145.083");
}

.zf2atv-8x {
  stop-color: var(--svg-color--dc9c96, #DC9C96);
  stop-opacity: 0;
}

.zjzbcmb2n {
  cx: 17.7px;
  cy: 5.251px;
  r: 0.71px;
}

.zn47ozbfv {
  stop-color: var(--svg-color--442563, #442563);
  stop-opacity: 0;
}

.zwsi1kjqc {
  fill: var(--svg-color--fff, #fff);
  d: path("M16.52 5.23c.241-.14.54-.09.725.101a.116.116 0 0 1-.027.183l-.82.474a.098.098 0 0 1-.142-.052a.594.594 0 0 1 .265-.707");
}

</style>
