<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#igd8dQd)"><path fill="url(#iBSeWTd)" clip-rule="evenodd" class="g_m0pqbwp"/></g><g filter="url(#iDSA5fe)"><path class="r_cqmnbub"/><path fill="url(#ixncRHb)" class="f3w47v2yn"/><path fill="url(#iU1pq3c)" class="f3w47v2yn"/></g><path fill="url(#iptw2dB)" class="f3w47v2yn"/><path fill="url(#i0TFPCd)" class="mz4qvhb4h"/><path fill="url(#iN7krAc)" class="mz4qvhb4h"/><path fill="url(#iePEuqm)" class="mz4qvhb4h"/><g filter="url(#iBUGFMU)"><path class="myp6-c8zc"/></g><path class="jc3yfml4c"/><path fill="url(#im7w9Bc)" class="kczk9kbyu"/><path fill="url(#ixXlAFe)" class="kczk9kbyu"/><path fill="url(#ivTrfAx)" class="kczk9kbyu"/><path fill="url(#iYmM2HL)" class="kczk9kbyu"/><g filter="url(#iG5KRQd)"><path class="edpkxhbmk"/></g><path fill="url(#iF5pjDc)" class="vp_s2ybyh"/><path fill="url(#iOrbYjb)" class="vp_s2ybyh"/><path fill="url(#iKuH7Zc)" class="vp_s2ybyh"/><path fill="url(#imDzrvc)" class="vp_s2ybyh"/><path fill="url(#i4tvT8b)" class="vp_s2ybyh"/><path fill="url(#irjx2Ke)" class="vp_s2ybyh"/><path fill="url(#ip5pPye)" class="vp_s2ybyh"/><path fill="url(#iC8fI6N)" class="yq02ovbhw"/><path fill="url(#i63R6we)" class="yq02ovbhw"/><path fill="url(#imovJzc)" class="yq02ovbhw"/><path fill="url(#iG0KzQb)" class="yq02ovbhw"/><path fill="url(#iKoUxKv)" class="yq02ovbhw"/><rect transform="rotate(-26.783 20.65 4.062)" class="tm9ge0ksj"/><rect fill="url(#it1uFsd)" transform="rotate(-26.783 21.084 3.802)" class="nzjvvub-c"/><rect fill="url(#i9MKREc)" transform="rotate(-26.783 21.603 3.556)" class="qufu6rbna"/><rect fill="url(#iCxa9sQ)" transform="rotate(-26.783 22.173 3.302)" class="p8tnwrsus"/><rect fill="url(#iGhf5ud)" transform="rotate(60 21.976 4.334)" class="bgipjcbid"/><g filter="url(#ifDCxMd)"><path class="gg83kth0e"/><path fill="url(#iLjVJxc)" class="ovf3vxbzm"/></g><g filter="url(#iMQrnyd)"><path fill="url(#iMVtKnb)" class="rhiww0bbp"/><path fill="url(#ioVw4pC)" class="rhiww0bbp"/><path fill="url(#iuNa5db)" class="rhiww0bbp"/></g><g filter="url(#iK7rwne)"><path class="eb4a0-btu"/></g><g filter="url(#ilLusvc)"><path stroke="url(#i78SbVd)" class="pcgk580qn"/></g><g filter="url(#ie1Xtoc)"><path fill="url(#iNVF4nb)" class="i6of5ub8a"/></g><g filter="url(#isa4ylc)"><circle fill="url(#iJc4TYb)" transform="rotate(-30 12.912 7.202)" class="umkjkab9d"/></g><g filter="url(#i1OsYee)"><circle fill="url(#ieECPYc)" transform="rotate(-30 12.913 7.202)" class="q9oar8avv"/></g><g filter="url(#iCYNDSb)"><circle fill="url(#iNnHpCe)" transform="rotate(-30 16.388 5.196)" class="qqs95c6di"/><circle fill="url(#iN94wXb)" transform="rotate(-30 16.388 5.196)" class="qqs95c6di"/></g><g filter="url(#imlFpod)"><circle transform="rotate(-30 16.388 5.196)" class="fwgda7b_n"/><circle fill="url(#ix4Blcb)" transform="rotate(-30 16.388 5.196)" class="bgix5w8bi"/><circle fill="url(#ie0NpAe)" transform="rotate(-30 16.388 5.196)" class="bgix5w8bi"/></g><path fill="url(#iPDFZrb)" class="b-8nxnbib"/><path fill="url(#iMMBehE)" class="b-8nxnbib"/><path fill="url(#iZQ9Oxe)" class="b-8nxnbib"/><path fill="url(#iPM6jWd)" class="rzqsmx-ec"/><path fill="url(#iuqF3he)" class="rzqsmx-ec"/><path fill="url(#ij3KZEc)" class="rzqsmx-ec"/><path fill="url(#iICz0td)" class="rzqsmx-ec"/><g filter="url(#i30Q4cb)"><path class="srjhkll6u"/></g><g filter="url(#ipR4LFd)"><path class="b9nsdqnbu"/><path fill="url(#ixzPcmb)" class="e5gyn6bbf"/><path fill="url(#iPphXub)" class="e5gyn6bbf"/><path fill="url(#iXj58Ri)" class="e5gyn6bbf"/><path fill="url(#iCjkG6c)" class="e5gyn6bbf"/><path fill="url(#iGGCcJd)" class="e5gyn6bbf"/></g><path stroke="url(#i8yjXHw)" class="rrklpabdz"/><path class="ypda30bla"/><path fill="url(#iVVVW7d)" class="dot96db_j"/><path class="xi1si-bir"/><g filter="url(#iZkoE6J)"><path class="ds7ca5bpo"/><path fill="url(#i28QHHb)" class="npyn8ub8m"/></g><g filter="url(#iqQcgIe)"><path fill="url(#i9cj4hd)" class="iupk35v1d"/></g><path class="maf7hnplt"/><path fill="url(#iobebCb)" class="vpmiz7bmj"/><path class="k3aooj8cu"/><g filter="url(#iRtqu2w)"><path fill="url(#iqYpYcR)" class="y8ripg49t"/></g><g filter="url(#ieBSp0E)"><ellipse transform="rotate(-57.914 13.586 6.435)" class="ft15lhbdp"/><ellipse fill="url(#i01PXKb)" transform="rotate(-57.914 13.586 6.435)" class="c3g1nwzlr"/></g><g filter="url(#iKaLENd)"><path clip-rule="evenodd" class="sxbbp5buq"/></g><g filter="url(#iz9Jdtk)"><path clip-rule="evenodd" class="o3mu6acyn"/></g><path fill="url(#iArQR8d)" class="g2-b79boq"/><path fill="url(#iMlYTAZ)" class="nw575mbko"/><g filter="url(#iuMkQmc)"><path fill="url(#iBmJYQd)" class="ufp05kbjw"/><path fill="url(#ijVbdSb)" class="ufp05kbjw"/></g><path fill="url(#izGDB5d)" class="xezbdyc0d"/><path fill="url(#ifuQXZc)" class="xezbdyc0d"/><path fill="url(#iLWcEIc)" class="xezbdyc0d"/><path fill="url(#itc9wGc)" class="xezbdyc0d"/><defs><radialGradient id="ixncRHb" cx="0" cy="0" r="1" gradientTransform="rotate(146.915 8.778 5.898)scale(4.92324 2.04943)" gradientUnits="userSpaceOnUse"><stop class="ba1yb3bji"/><stop offset="1" class="kgrhzo17p"/></radialGradient><radialGradient id="iptw2dB" cx="0" cy="0" r="1" gradientTransform="matrix(1.4375 -.0625 .23626 5.43402 6.51 13.641)" gradientUnits="userSpaceOnUse"><stop class="wn-t5ndzy"/><stop offset="1" class="ben4f0bqs"/></radialGradient><radialGradient id="iePEuqm" cx="0" cy="0" r="1" gradientTransform="matrix(-.27344 .16016 -.21807 -.37232 24.841 2.895)" gradientUnits="userSpaceOnUse"><stop offset=".181" class="i42zc8m6u"/><stop offset="1" class="dsumrvbgt"/></radialGradient><radialGradient id="ixXlAFe" cx="0" cy="0" r="1" gradientTransform="matrix(-.875 -.46876 .24583 -.45888 14.134 29.5)" gradientUnits="userSpaceOnUse"><stop class="ynlfw99ba"/><stop offset="1" class="in-vfpgwh"/></radialGradient><radialGradient id="ivTrfAx" cx="0" cy="0" r="1" gradientTransform="matrix(-.76562 .85157 -1.15842 -1.0415 12.743 26.993)" gradientUnits="userSpaceOnUse"><stop offset=".115" class="vkrof_bbk"/><stop offset="1" class="h8hiq33uv"/></radialGradient><radialGradient id="iYmM2HL" cx="0" cy="0" r="1" gradientTransform="matrix(.8125 .15625 -.58594 3.04687 11.368 28.391)" gradientUnits="userSpaceOnUse"><stop class="ilg8l_bzj"/><stop offset="1" class="s2j02zbkr"/></radialGradient><radialGradient id="iOrbYjb" cx="0" cy="0" r="1" gradientTransform="matrix(2.71873 -2.53127 .81258 .87276 13.166 27.954)" gradientUnits="userSpaceOnUse"><stop class="pcvpzjboo"/><stop offset="1" class="qe_2d-buv"/></radialGradient><radialGradient id="iKuH7Zc" cx="0" cy="0" r="1" gradientTransform="matrix(2.54688 -2.64063 .2894 .27913 12.275 26.297)" gradientUnits="userSpaceOnUse"><stop offset=".285" class="kxzgmzb5t"/><stop offset="1" class="xhu8yhbcw"/></radialGradient><radialGradient id="imDzrvc" cx="0" cy="0" r="1" gradientTransform="matrix(-.76563 0 0 -5.02098 17.369 21.641)" gradientUnits="userSpaceOnUse"><stop offset=".001" class="keljo6scd"/><stop offset="1" class="ps4m-ab9c"/></radialGradient><radialGradient id="i4tvT8b" cx="0" cy="0" r="1" gradientTransform="matrix(.04687 -.98437 1.15192 .05485 17.619 18.313)" gradientUnits="userSpaceOnUse"><stop offset=".154" class="w5oxhdc5r"/><stop offset="1" class="ebs2-pbbe"/></radialGradient><radialGradient id="irjx2Ke" cx="0" cy="0" r="1" gradientTransform="matrix(.78125 0 0 7.6823 17.978 23)" gradientUnits="userSpaceOnUse"><stop class="j_l_30buh"/><stop offset="1" class="xi8fv135v"/></radialGradient><radialGradient id="ip5pPye" cx="0" cy="0" r="1" gradientTransform="matrix(3.40625 -3.34375 1.20794 1.23052 13.666 28.016)" gradientUnits="userSpaceOnUse"><stop class="ddjhanboc"/><stop offset="1" class="uu7_gub8n"/></radialGradient><radialGradient id="iC8fI6N" cx="0" cy="0" r="1" gradientTransform="rotate(150.356 8.574 7.61)scale(4.42262 6.15908)" gradientUnits="userSpaceOnUse"><stop class="no0_3dbdi"/><stop offset="1" class="truekjbvb"/></radialGradient><radialGradient id="i63R6we" cx="0" cy="0" r="1" gradientTransform="matrix(.57404 2.73801 -4.6268 .97003 17.28 7.278)" gradientUnits="userSpaceOnUse"><stop offset=".306" class="kdxlabb_n"/><stop offset="1" class="x9_x14ckq"/></radialGradient><radialGradient id="iG0KzQb" cx="0" cy="0" r="1" gradientTransform="matrix(.87501 1.59375 -2.6006 1.4278 15.291 7.985)" gradientUnits="userSpaceOnUse"><stop offset=".285" class="v2g8x4brb"/><stop offset="1" class="we0trlbug"/></radialGradient><radialGradient id="iKoUxKv" cx="0" cy="0" r="1" gradientTransform="matrix(1.71875 -.01563 .0588 6.46896 13.478 10.391)" gradientUnits="userSpaceOnUse"><stop class="qg0h4w_kv"/><stop offset="1" class="iich1wbqp"/></radialGradient><radialGradient id="it1uFsd" cx="0" cy="0" r="1" gradientTransform="matrix(-.64636 .00475 -.0063 -.85808 21.76 4.47)" gradientUnits="userSpaceOnUse"><stop offset=".183" class="cuertacie"/><stop offset="1" class="w_jlcfbxk"/></radialGradient><radialGradient id="i9MKREc" cx="0" cy="0" r="1" gradientTransform="matrix(-.64636 .00475 -.0063 -.85808 22.28 4.225)" gradientUnits="userSpaceOnUse"><stop offset=".183" class="cuertacie"/><stop offset="1" class="w_jlcfbxk"/></radialGradient><radialGradient id="iCxa9sQ" cx="0" cy="0" r="1" gradientTransform="matrix(-.64636 .00475 -.0063 -.85808 22.849 3.97)" gradientUnits="userSpaceOnUse"><stop offset=".183" class="cuertacie"/><stop offset="1" class="w_jlcfbxk"/></radialGradient><radialGradient id="iGhf5ud" cx="0" cy="0" r="1" gradientTransform="matrix(-.02457 .47352 -.46721 -.02424 22.369 4.486)" gradientUnits="userSpaceOnUse"><stop class="oql8gccaf"/><stop offset="1" class="t3--w_blh"/></radialGradient><radialGradient id="iLjVJxc" cx="0" cy="0" r="1" gradientTransform="matrix(3.80388 .30087 -.62375 7.88601 17.576 5.625)" gradientUnits="userSpaceOnUse"><stop offset=".629" class="lzzs11bzy"/><stop offset="1" class="rovuy_e_s"/></radialGradient><radialGradient id="ioVw4pC" cx="0" cy="0" r="1" gradientTransform="matrix(1.71875 .21242 -.56203 4.5475 14.04 9.797)" gradientUnits="userSpaceOnUse"><stop offset=".204" class="v__i2ebru"/><stop offset="1" class="yrm14tb3b"/></radialGradient><radialGradient id="iuNa5db" cx="0" cy="0" r="1" gradientTransform="matrix(.04687 .51562 -1.9883 .18075 16.181 8.782)" gradientUnits="userSpaceOnUse"><stop class="hnewum4zo"/><stop offset="1" class="j297-pbqp"/></radialGradient><radialGradient id="iJc4TYb" cx="0" cy="0" r="1" gradientTransform="matrix(.74021 0 0 1.29538 12.208 7.202)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="gsgzrwbpm"/><stop offset="1" class="nhrtbwabt"/></radialGradient><radialGradient id="iN94wXb" cx="0" cy="0" r="1" gradientTransform="matrix(.3487 -.25391 .2898 .398 16.545 5.084)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="ywu0pr7ii"/><stop offset="1" class="pw1h71b2a"/></radialGradient><radialGradient id="ix4Blcb" cx="0" cy="0" r="1" gradientTransform="matrix(.34641 -.63715 .37293 .20276 16.37 5.542)" gradientUnits="userSpaceOnUse"><stop offset=".755" class="evklql54e"/><stop offset=".916" class="ppo67rb9b"/></radialGradient><radialGradient id="ie0NpAe" cx="0" cy="0" r="1" gradientTransform="rotate(44.708 1.876 22.523)scale(.15389 .19838)" gradientUnits="userSpaceOnUse"><stop class="o45oetbxg"/><stop offset="1" class="mfyy4ibhn"/></radialGradient><radialGradient id="iMMBehE" cx="0" cy="0" r="1" gradientTransform="matrix(-.27567 -.47747 .58518 -.33785 15.24 5.24)" gradientUnits="userSpaceOnUse"><stop class="q3kvcibxc"/><stop offset="1" class="kz100sbcz"/></radialGradient><radialGradient id="iZQ9Oxe" cx="0" cy="0" r="1" gradientTransform="matrix(-.2898 -.50195 .6216 -.35888 13.61 6.245)" gradientUnits="userSpaceOnUse"><stop class="z_g0j449a"/><stop offset="1" class="s5xtkwbhw"/></radialGradient><radialGradient id="ij3KZEc" cx="0" cy="0" r="1" gradientTransform="matrix(1.86576 3.2316 -4.36822 2.522 14.171 5.612)" gradientUnits="userSpaceOnUse"><stop offset=".619" class="rko8b-bmk"/><stop offset="1" class="whxihzpaf"/></radialGradient><radialGradient id="iICz0td" cx="0" cy="0" r="1" gradientTransform="matrix(.91759 1.58931 -2.34636 1.35467 13.956 4.89)" gradientUnits="userSpaceOnUse"><stop offset=".154" class="tcgi-acxh"/><stop offset="1" class="q9-x6bbmc"/></radialGradient><radialGradient id="iCjkG6c" cx="0" cy="0" r="1" gradientTransform="rotate(59.999 1.733 16.441)scale(.08305 .26684)" gradientUnits="userSpaceOnUse"><stop class="w-44tpbkk"/><stop offset="1" class="d52rddbnb"/></radialGradient><radialGradient id="iVVVW7d" cx="0" cy="0" r="1" gradientTransform="rotate(60 2.893 15.996)scale(.34214 .54421)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="i28QHHb" cx="0" cy="0" r="1" gradientTransform="matrix(-.14771 -.06024 .08294 -.20337 15.233 5.571)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iobebCb" cx="0" cy="0" r="1" gradientTransform="rotate(60 1.3 15.075)scale(.34216 .54424)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="i01PXKb" cx="0" cy="0" r="1" gradientTransform="matrix(-.00326 -.20796 .24998 -.00391 13.58 6.568)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iBmJYQd" cx="0" cy="0" r="1" gradientTransform="rotate(-33.523 16.208 -17.814)scale(3.24627 12.0294)" gradientUnits="userSpaceOnUse"><stop class="fn7-6xayh"/><stop offset="1" class="chayuvnap"/></radialGradient><radialGradient id="ijVbdSb" cx="0" cy="0" r="1" gradientTransform="rotate(-91.606 9.796 -5.042)scale(.62983 1.11621)" gradientUnits="userSpaceOnUse"><stop class="sylx2mbjo"/><stop offset="1" class="nav-8e2lo"/></radialGradient><radialGradient id="izGDB5d" cx="0" cy="0" r="1" gradientTransform="matrix(-2.48517 1.25285 -1.19452 -2.36948 14.777 3.97)" gradientUnits="userSpaceOnUse"><stop class="blekadc8f"/><stop offset="1" class="c6xk9jx7z"/></radialGradient><radialGradient id="ifuQXZc" cx="0" cy="0" r="1" gradientTransform="matrix(.09032 -2.3968 3.71358 .13994 12.187 5.983)" gradientUnits="userSpaceOnUse"><stop class="jjpmu-56c"/><stop offset="1" class="ldm9khd7d"/></radialGradient><radialGradient id="iLWcEIc" cx="0" cy="0" r="1" gradientTransform="rotate(-115.648 8.44 -1.937)scale(1.01724 2.24938)" gradientUnits="userSpaceOnUse"><stop offset=".155" class="o2ca957_x"/><stop offset="1" class="a7xagmxua"/></radialGradient><radialGradient id="itc9wGc" cx="0" cy="0" r="1" gradientTransform="matrix(.34554 .52587 -2.8546 1.87567 12.781 2.989)" gradientUnits="userSpaceOnUse"><stop class="uw0kegb-q"/><stop offset="1" class="ydllxhbat"/></radialGradient><linearGradient id="iBSeWTd" x1="23.013" x2="19.956" y1="5.067" y2="11.072" gradientUnits="userSpaceOnUse"><stop class="fu0pwxb1a"/><stop offset=".799" class="krbp1tz0u"/></linearGradient><linearGradient id="iU1pq3c" x1="12.493" x2="12.822" y1="9.497" y2="9.969" gradientUnits="userSpaceOnUse"><stop offset=".349" class="lr97j31fb"/><stop offset="1" class="azn0z--js"/></linearGradient><linearGradient id="i0TFPCd" x1="24.916" x2="22.775" y1="3.016" y2="4.329" gradientUnits="userSpaceOnUse"><stop class="ds3hm--8v"/><stop offset="1" class="bq7w62n5j"/></linearGradient><linearGradient id="iN7krAc" x1="23.884" x2="23.619" y1="4.016" y2="3.485" gradientUnits="userSpaceOnUse"><stop class="seeiowbir"/><stop offset="1" class="tw6dxpb7y"/></linearGradient><linearGradient id="im7w9Bc" x1="12.697" x2="12.697" y1="30.352" y2="29.68" gradientUnits="userSpaceOnUse"><stop class="dhem-xbnm"/><stop offset="1" class="zn47ozbfv"/></linearGradient><linearGradient id="iF5pjDc" x1="20.478" x2="19.884" y1="22.891" y2="22.86" gradientUnits="userSpaceOnUse"><stop class="ieaclmdnn"/><stop offset="1" class="p3yd_be1u"/></linearGradient><linearGradient id="imovJzc" x1="17.279" x2="17.279" y1="16.297" y2="13.11" gradientUnits="userSpaceOnUse"><stop offset=".039" class="ptputobcp"/><stop offset="1" class="br5umybnw"/></linearGradient><linearGradient id="iMVtKnb" x1="16.011" x2="16.011" y1="8.68" y2="10.891" gradientUnits="userSpaceOnUse"><stop class="bw1hkxbcb"/><stop offset="1" class="tesa8u_3j"/></linearGradient><linearGradient id="i78SbVd" x1="19.744" x2="19.744" y1="16.922" y2="27.828" gradientUnits="userSpaceOnUse"><stop class="hd06b2knh"/><stop offset="1" class="ggughpb3d"/></linearGradient><linearGradient id="iNVF4nb" x1="16.306" x2="16.306" y1="18.36" y2="24.922" gradientUnits="userSpaceOnUse"><stop class="y6ovumr8k"/><stop offset="1" class="t-eeezbdl"/></linearGradient><linearGradient id="ieECPYc" x1="12.913" x2="12.643" y1="7.32" y2="7.32" gradientUnits="userSpaceOnUse"><stop class="jrtbzwbyo"/><stop offset="1" class="xh6agdcni"/></linearGradient><linearGradient id="iNnHpCe" x1="16.846" x2="16.501" y1="4.736" y2="5.805" gradientUnits="userSpaceOnUse"><stop class="z3o7w4-ew"/><stop offset="1" class="uddso4bed"/></linearGradient><linearGradient id="iPDFZrb" x1="16.205" x2="13.665" y1="5.491" y2="7.507" gradientUnits="userSpaceOnUse"><stop class="ah-u2v6vh"/><stop offset="1" class="hp2sktbkw"/></linearGradient><linearGradient id="iPM6jWd" x1="13.343" x2="14.014" y1="8.457" y2="8.037" gradientUnits="userSpaceOnUse"><stop class="wgn2-qn3r"/><stop offset="1" class="cyilnmbju"/></linearGradient><linearGradient id="iuqF3he" x1="16.899" x2="16.494" y1="5.996" y2="6.181" gradientUnits="userSpaceOnUse"><stop class="y91wuhb_y"/><stop offset="1" class="dfnybco8z"/></linearGradient><linearGradient id="ixzPcmb" x1="14.553" x2="14.895" y1="6.766" y2="6.569" gradientUnits="userSpaceOnUse"><stop class="tye5yqhfq"/><stop offset="1" class="rb8odhbtu"/></linearGradient><linearGradient id="iPphXub" x1="15.279" x2="14.901" y1="6.504" y2="6.715" gradientUnits="userSpaceOnUse"><stop class="w6mxzsbgv"/><stop offset="1" class="ylom6naui"/></linearGradient><linearGradient id="iXj58Ri" x1="15.164" x2="15.043" y1="6.932" y2="6.723" gradientUnits="userSpaceOnUse"><stop class="hlulkvo5l"/><stop offset="1" class="y_z4ite8v"/></linearGradient><linearGradient id="iGGCcJd" x1="14.527" x2="14.81" y1="5.994" y2="6.483" gradientUnits="userSpaceOnUse"><stop class="gh5tpcc0r"/><stop offset="1" class="rpp-doqri"/></linearGradient><linearGradient id="i8yjXHw" x1="15.054" x2="15.068" y1="7.782" y2="7.439" gradientUnits="userSpaceOnUse"><stop class="lwz87437z"/><stop offset=".663" class="c7jfumw-i"/></linearGradient><linearGradient id="i9cj4hd" x1="15.595" x2="15.521" y1="5.348" y2="5.485" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iqYpYcR" x1="13.988" x2="13.915" y1="6.275" y2="6.412" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iArQR8d" x1="12.364" x2="12.184" y1="6.499" y2="6.603" gradientUnits="userSpaceOnUse"><stop class="gfuj0ibqm"/><stop offset="1" class="jhxo97b8s"/></linearGradient><linearGradient id="iMlYTAZ" x1="16.08" x2="16.26" y1="4.353" y2="4.249" gradientUnits="userSpaceOnUse"><stop offset=".548" class="j9k2-bbvj"/><stop offset="1" class="mm0r6cb0n"/></linearGradient><filter id="igd8dQd" width="8.471" height="7.176" x="16.221" y="3.896" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.447059 0 0 0 0 0.262745 0 0 0 0 0.247059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22981"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.529412 0 0 0 0 0.380392 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_22981" result="effect2_innerShadow_3987_22981"/></filter><filter id="iDSA5fe" width="18.187" height="14.194" x="6.907" y="2.3" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.568627 0 0 0 0 0.454902 0 0 0 0 0.647059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22981"/></filter><filter id="iBUGFMU" width="4.793" height="2.27" x="18.177" y="27.934" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.262745 0 0 0 0 0.188235 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22981"/></filter><filter id="iG5KRQd" width="8.989" height="12.477" x="12.161" y="15.969" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.67451 0 0 0 0 0.635294 0 0 0 0 0.686275 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22981"/></filter><filter id="ifDCxMd" width="7.553" height="7.567" x="14.351" y="3.855" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.435294 0 0 0 0 0.278431 0 0 0 0 0.239216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22981"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.494118 0 0 0 0 0.309804 0 0 0 0 0.345098 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_22981" result="effect2_innerShadow_3987_22981"/></filter><filter id="iMQrnyd" width="3.395" height="2.909" x="14.313" y="8.43" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.145098 0 0 0 0 0.4 0 0 0 0 0.835294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22981"/></filter><filter id="iK7rwne" width="1.789" height="3.497" x="8.087" y="12.588" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22981" stdDeviation=".125"/></filter><filter id="ilLusvc" width="2.601" height="13.601" x="18.427" y="15.434" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22981" stdDeviation=".4"/></filter><filter id="ie1Xtoc" width="2.563" height="7.453" x="15.025" y="16.875" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22981" stdDeviation=".375"/></filter><filter id="isa4ylc" width="1.609" height="1.409" x="12.208" y="6.498" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.517647 0 0 0 0 0.384314 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22981"/></filter><filter id="i1OsYee" width="1.84" height="1.839" x="11.993" y="6.283" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22981" stdDeviation=".25"/></filter><filter id="iCYNDSb" width="1.659" height="1.659" x="15.684" y="4.242" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.482353 0 0 0 0 0.278431 0 0 0 0 0.372549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22981"/></filter><filter id="imlFpod" width="1.84" height="1.839" x="15.468" y="4.276" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22981" stdDeviation=".25"/></filter><filter id="i30Q4cb" width="2.27" height="2.624" x="13.759" y="5.314" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22981" stdDeviation=".375"/></filter><filter id="ipR4LFd" width="1.109" height="1.317" x="14.343" y="5.87" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22981" stdDeviation=".05"/></filter><filter id="iZkoE6J" width=".372" height=".472" x="14.965" y="5.297" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22981" stdDeviation=".05"/></filter><filter id="iqQcgIe" width=".617" height=".618" x="15.236" y="5.113" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22981" stdDeviation=".1"/></filter><filter id="iRtqu2w" width=".669" height=".657" x="13.599" y="6.021" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22981" stdDeviation=".1"/></filter><filter id="ieBSp0E" width=".424" height=".492" x="13.374" y="6.189" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22981" stdDeviation=".05"/></filter><filter id="iKaLENd" width="1.347" height=".998" x="14.49" y="4.012" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.156863 0 0 0 0 0.0784314 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22981"/></filter><filter id="iz9Jdtk" width="1.161" height="1.309" x="12.71" y="4.944" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.156863 0 0 0 0 0.0784314 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22981"/></filter><filter id="iuMkQmc" width="4.076" height="2.621" x="11.951" y="3.709" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.160784 0 0 0 0 0.396078 0 0 0 0 0.721569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22981"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-golfing-medium-dark" /></template>
<style>
.a7xagmxua {
  stop-color: var(--svg-color--1a7ccc, #1A7CCC);
  stop-opacity: 0;
}

.ah-u2v6vh {
  stop-color: var(--svg-color--9b6c5e, #9B6C5E);
}

.azn0z--js {
  stop-color: var(--svg-color--b39fbc, #B39FBC);
  stop-opacity: 0;
}

.b-8nxnbib {
  d: path("M12.317 6.479c-.057-.098-.127-.262-.082-.366l-.07-.17c.052-.135.175-.11.108-.227l-.18-.312a.22.22 0 0 1 .044-.285a7 7 0 0 1 1.34-.982a7 7 0 0 1 1.52-.67a.24.24 0 0 1 .27.104l.18.312c.067.117.02-.389.143-.356c.258.023.461.688.533.849c.312.691.674 1.365 1.01 2.046c.314.68.066 1.425-.54 1.775l-1.173.677c-.626.36-1.374.192-1.806-.42c-.433-.632-.914-1.311-1.298-1.975");
}

.b9nsdqnbu {
  fill: var(--svg-color--8c5f5e, #8C5F5E);
  d: path("m14.447 6.178l.165.732a.227.227 0 0 0 .337.146l.288-.166a.228.228 0 0 0 .042-.365l-.552-.509c-.121-.113-.315-.001-.28.162");
}

.ba1yb3bji {
  stop-color: var(--svg-color--a99797, #A99797);
}

.ben4f0bqs {
  stop-color: var(--svg-color--b8acbd, #B8ACBD);
  stop-opacity: 0;
}

.bgipjcbid {
  width: 0.737px;
  height: 1.252px;
  x: 21.976px;
  y: 4.334px;
  rx: 0.369px;
}

.bgix5w8bi {
  cx: 16.388px;
  cy: 5.196px;
  r: 0.42px;
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

.bw1hkxbcb {
  stop-color: var(--svg-color--2d9de0, #2D9DE0);
}

.c3g1nwzlr {
  cx: 13.586px;
  cy: 6.435px;
  rx: 0.164px;
  ry: 0.083px;
}

.c6xk9jx7z {
  stop-color: var(--svg-color--1b96dc, #1B96DC);
}

.c7jfumw-i {
  stop-color: var(--svg-color--865e63, #865E63);
  stop-opacity: 0;
}

.chayuvnap {
  stop-color: var(--svg-color--1d78b8, #1D78B8);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cuertacie {
  stop-color: var(--svg-color--8c6d67, #8C6D67);
}

.cyilnmbju {
  stop-color: var(--svg-color--84615a, #84615A);
  stop-opacity: 0;
}

.d52rddbnb {
  stop-color: var(--svg-color--976f6a, #976F6A);
  stop-opacity: 0;
}

.ddjhanboc {
  stop-color: var(--svg-color--8c6fa7, #8C6FA7);
}

.dfnybco8z {
  stop-color: var(--svg-color--966d5f, #966D5F);
  stop-opacity: 0;
}

.dhem-xbnm {
  stop-color: var(--svg-color--442563, #442563);
}

.dot96db_j {
  d: path("M15.2 5.318a.376.376 0 0 1 .551.23l-.63.364a.378.378 0 0 1 .078-.594");
}

.ds3hm--8v {
  stop-color: var(--svg-color--533d66, #533D66);
}

.ds7ca5bpo {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M15.215 5.4c.041.018.015.084-.017.157c-.031.073-.055.126-.097.108c-.04-.017-.049-.09-.017-.164c.031-.073.09-.118.131-.1");
}

.dsumrvbgt {
  stop-color: var(--svg-color--615273, #615273);
  stop-opacity: 0;
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e5gyn6bbf {
  d: path("m14.447 6.178l.165.732a.227.227 0 0 0 .337.146l.288-.166a.228.228 0 0 0 .042-.365l-.552-.509c-.121-.113-.315-.001-.28.162");
}

.eb4a0-btu {
  stroke: var(--svg-color--c3b8c3, #C3B8C3);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M8.51 12.938a.53.53 0 0 0 0 .539c.13.237.718 1.277.96 1.715c.05.103.111.355-.039.543");
}

.ebs2-pbbe {
  stop-color: var(--svg-color--9c8cad, #9C8CAD);
  stop-opacity: 0;
}

.edpkxhbmk {
  fill: var(--svg-color--9785a9, #9785A9);
  d: path("M14.522 23.971a1 1 0 0 0 .275-.711l-.167-7.29h6.02l-.312 12.476H18.18l-.259-10.002a.255.255 0 0 0-.509-.005c-.049 1.196-.13 3.455-.13 4.585c0 1.212-.693 2.213-1.04 2.562l-2.472 2.288a.32.32 0 0 1-.317.082a2.2 2.2 0 0 1-.718-.424c-.252-.225-.439-.553-.547-.795a.36.36 0 0 1 .078-.393z");
}

.evklql54e {
  stop-color: var(--svg-color--73443e, #73443E);
  stop-opacity: 0;
}

.f3w47v2yn {
  d: path("M8.948 12.914a.35.35 0 0 0-.125.474l.88 1.545a1 1 0 0 1-.373 1.364l-.115.066a1 1 0 0 1-1.364-.374l-.728-1.278a1.65 1.65 0 0 1 .617-2.25l.343-.195l16.303-9.71a.4.4 0 0 1 .549.14l.102.172a.4.4 0 0 1-.14.548z");
}

.fn7-6xayh {
  stop-color: var(--svg-color--3e82bc, #3E82BC);
}

.ft15lhbdp {
  cx: 13.586px;
  cy: 6.435px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.164px;
  ry: 0.083px;
}

.ft5dv1b6b {
  fill: none;
}

.fu0pwxb1a {
  stop-color: var(--svg-color--82615c, #82615C);
}

.fwgda7b_n {
  cx: 16.388px;
  cy: 5.196px;
  r: 0.42px;
  fill: var(--svg-color--7a5654, #7A5654);
}

.g_m0pqbwp {
  fill-rule: evenodd;
  d: path("M20.961 7.804c.852-1.082.481-2.213.22-2.677l1.915-1.081c.467.827 1.242 3.026-.406 5.12c-.89 1.13-2.33 1.566-3.484 1.752c-1.198.193-2.37.158-2.985.135l.084-2.199c.599.023 1.583.048 2.55-.108c1.012-.163 1.746-.484 2.106-.942");
}

.g2-b79boq {
  d: path("m12.382 6.945l-.493-.855l.436-.252a.8.8 0 0 1-.01.34a.5.5 0 0 0 .06.36l.293.507c-.097.056-.222.02-.286-.1");
}

.gfuj0ibqm {
  stop-color: var(--svg-color--1e191c, #1E191C);
}

.gg83kth0e {
  fill: var(--svg-color--7c564f, #7C564F);
  d: path("M19.317 6.016a.5.5 0 0 0-.015-.254a5 5 0 0 0-.227-.523c-.02-.089-.025-.29.11-.39a.36.36 0 0 1 .336-.056a.45.45 0 0 1 .207-.285c.134-.072.298-.03.363 0c.018-.066.09-.208.23-.246a.52.52 0 0 1 .356.059c.04-.076.169-.224.36-.215c.238.012.374.262.41.45c.035.187.093.433.152.577c.058.145.117.606-.09 1.2h-.001c-.454 1.884-1.492 3.103-2.664 3.853c-1.184.758-2.454 1.008-3.297 1.082a1.1 1.1 0 0 1-.193-2.191c.636-.056 1.522-.244 2.304-.744c.683-.437 1.327-1.135 1.66-2.317");
}

.ggughpb3d {
  stop-color: var(--svg-color--a599b3, #A599B3);
}

.gh5tpcc0r {
  stop-color: var(--svg-color--764e53, #764E53);
}

.gsgzrwbpm {
  stop-color: var(--svg-color--664249, #664249);
}

.h8hiq33uv {
  stop-color: var(--svg-color--271938, #271938);
  stop-opacity: 0;
}

.hd06b2knh {
  stop-color: var(--svg-color--a89eb3, #A89EB3);
}

.hlulkvo5l {
  stop-color: var(--svg-color--7c4559, #7C4559);
}

.hnewum4zo {
  stop-color: var(--svg-color--2f89b9, #2F89B9);
}

.hp2sktbkw {
  stop-color: var(--svg-color--744d4a, #744D4A);
}

.i42zc8m6u {
  stop-color: var(--svg-color--615273, #615273);
}

.i6of5ub8a {
  d: path("m16.15 23.579l-.375-5.954l1.062.5v5.453z");
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

.iupk35v1d {
  d: path("M15.653 5.433a.35.35 0 0 0-.182-.12l-.035.159l.091.058z");
}

.j_l_30buh {
  stop-color: var(--svg-color--5d5467, #5D5467);
}

.j297-pbqp {
  stop-color: var(--svg-color--2f89b9, #2F89B9);
  stop-opacity: 0;
}

.j9k2-bbvj {
  stop-color: var(--svg-color--252224, #252224);
}

.jc3yfml4c {
  fill: var(--svg-color--47385d, #47385D);
  d: path("M11.595 27.813c0-.806.458-1.159.688-1.235l1.367 1.18v1.283a.5.5 0 0 0 .187.39l.203.163c.128.094.297.238.25.414c-.082.172-.25.195-.539.195h-1.506a.65.65 0 0 1-.65-.65z");
}

.jhxo97b8s {
  stop-color: var(--svg-color--463f3d, #463F3D);
}

.jjpmu-56c {
  stop-color: var(--svg-color--4199e0, #4199E0);
}

.jrtbzwbyo {
  stop-color: var(--svg-color--553038, #553038);
}

.k3aooj8cu {
  fill: var(--svg-color--000, #000);
  d: path("M13.978 6.457a.214.214 0 0 0-.294-.079a.214.214 0 0 0-.008.368l.33-.19a.2.2 0 0 0-.028-.099");
}

.kczk9kbyu {
  d: path("M11.595 27.813c0-.806.458-1.159.688-1.235l1.367 1.18v1.283a.5.5 0 0 0 .187.39l.203.163c.128.094.297.238.25.414c-.082.172-.25.195-.539.195h-1.506a.65.65 0 0 1-.65-.65z");
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

.krbp1tz0u {
  stop-color: var(--svg-color--7d4f55, #7D4F55);
}

.kxzgmzb5t {
  stop-color: var(--svg-color--9f9c9d, #9F9C9D);
}

.kz100sbcz {
  stop-color: var(--svg-color--855354, #855354);
  stop-opacity: 0;
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

.lr97j31fb {
  stop-color: var(--svg-color--b39fbc, #B39FBC);
}

.lwz87437z {
  stop-color: var(--svg-color--865e63, #865E63);
}

.lzzs11bzy {
  stop-color: var(--svg-color--917169, #917169);
  stop-opacity: 0;
}

.maf7hnplt {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.471 6.183a.59.59 0 0 0-.272.673c.02.073.105.105.17.068l.815-.47a.097.097 0 0 0 .026-.148a.59.59 0 0 0-.739-.123");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mfyy4ibhn {
  stop-color: var(--svg-color--6c443e, #6C443E);
  stop-opacity: 0;
}

.mm0r6cb0n {
  stop-color: var(--svg-color--5b5a5a, #5B5A5A);
}

.myp6-c8zc {
  fill: var(--svg-color--4c3765, #4C3765);
  d: path("M18.177 30.204v-1.77h2.16c.164.156.79.55 1.504.781c.494.131.625.488.63.621v.367z");
}

.mz4qvhb4h {
  d: path("m21.765 5.282l-.5-.866l3.122-1.86a.4.4 0 0 1 .548.14l.102.172a.4.4 0 0 1-.139.548z");
}

.nav-8e2lo {
  stop-color: var(--svg-color--3386c4, #3386C4);
  stop-opacity: 0;
}

.nhrtbwabt {
  stop-color: var(--svg-color--613641, #613641);
}

.no0_3dbdi {
  stop-color: var(--svg-color--53aff7, #53AFF7);
}

.npyn8ub8m {
  d: path("M15.215 5.4c.041.018.015.084-.017.157c-.031.073-.055.126-.097.108c-.04-.017-.049-.09-.017-.164c.031-.073.09-.118.131-.1");
}

.nw575mbko {
  d: path("m16.457 4.593l-.494-.856l-.437.253c.047.04.172.13.3.162a.5.5 0 0 1 .281.23l.276.518a.22.22 0 0 0 .074-.307");
}

.nzjvvub-c {
  width: 0.692px;
  height: 1.157px;
  x: 21.084px;
  y: 3.802px;
  rx: 0.346px;
}

.o2ca957_x {
  stop-color: var(--svg-color--1a7ccc, #1A7CCC);
}

.o3mu6acyn {
  fill: var(--svg-color--261629, #261629);
  fill-rule: evenodd;
  d: path("M13.505 5.724c-.277.127-.387.327-.406.389a.2.2 0 0 1-.38-.12c.052-.167.239-.456.62-.631a.2.2 0 1 1 .166.362");
}

.o45oetbxg {
  stop-color: var(--svg-color--6c443e, #6C443E);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oql8gccaf {
  stop-color: var(--svg-color--876b66, #876B66);
}

.ovf3vxbzm {
  d: path("M19.317 6.016a.5.5 0 0 0-.015-.254a5 5 0 0 0-.227-.523c-.02-.089-.025-.29.11-.39a.36.36 0 0 1 .336-.056a.45.45 0 0 1 .207-.285c.134-.072.298-.03.363 0c.018-.066.09-.208.23-.246a.52.52 0 0 1 .356.059c.04-.076.169-.224.36-.215c.238.012.374.262.41.45c.035.187.093.433.152.577c.058.145.117.606-.09 1.2h-.001c-.454 1.884-1.492 3.103-2.664 3.853c-1.184.758-2.454 1.008-3.297 1.082a1.1 1.1 0 0 1-.193-2.191c.636-.056 1.522-.244 2.304-.744c.683-.437 1.327-1.135 1.66-2.317");
}

.p3yd_be1u {
  stop-color: var(--svg-color--a49faa, #A49FAA);
  stop-opacity: 0;
}

.p8tnwrsus {
  width: 0.692px;
  height: 1.157px;
  x: 22.173px;
  y: 3.302px;
  rx: 0.346px;
}

.pcgk580qn {
  stroke-linecap: square;
  stroke-width: var(--svg-stroke-width--0-8px, 0.8px);
  d: path("m19.822 16.641l-.188 11.188");
}

.pcvpzjboo {
  stop-color: var(--svg-color--937da8, #937DA8);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.ppo67rb9b {
  stop-color: var(--svg-color--73443e, #73443E);
}

.ps4m-ab9c {
  stop-color: var(--svg-color--827a8b, #827A8B);
  stop-opacity: 0;
}

.ptputobcp {
  stop-color: var(--svg-color--366bc5, #366BC5);
}

.pw1h71b2a {
  stop-color: var(--svg-color--7c524c, #7C524C);
  stop-opacity: 0;
}

.q3kvcibxc {
  stop-color: var(--svg-color--855354, #855354);
}

.q9-x6bbmc {
  stop-color: var(--svg-color--633e4f, #633E4F);
  stop-opacity: 0;
}

.q9oar8avv {
  cx: 12.913px;
  cy: 7.202px;
  r: 0.42px;
}

.qe_2d-buv {
  stop-color: var(--svg-color--937da8, #937DA8);
  stop-opacity: 0;
}

.qg0h4w_kv {
  stop-color: var(--svg-color--56a2e0, #56A2E0);
}

.qqs95c6di {
  cx: 16.388px;
  cy: 5.196px;
  r: 0.704px;
}

.qufu6rbna {
  width: 0.692px;
  height: 1.157px;
  x: 21.603px;
  y: 3.556px;
  rx: 0.346px;
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r_cqmnbub {
  fill: var(--svg-color--afa2b8, #AFA2B8);
  d: path("M8.948 12.914a.35.35 0 0 0-.125.474l.88 1.545a1 1 0 0 1-.373 1.364l-.115.066a1 1 0 0 1-1.364-.374l-.728-1.278a1.65 1.65 0 0 1 .617-2.25l.343-.195l16.303-9.71a.4.4 0 0 1 .549.14l.102.172a.4.4 0 0 1-.14.548z");
}

.rb8odhbtu {
  stop-color: var(--svg-color--754e46, #754E46);
  stop-opacity: 0;
}

.rhiww0bbp {
  d: path("M16.001 8.895c.328-.031.652-.125.848-.215l.86 2.195c-.235.121-1.716.594-2.54.43s-1.02-1.195-.73-1.738c.273-.61 1.118-.63 1.562-.672");
}

.rko8b-bmk {
  stop-color: var(--svg-color--714250, #714250);
  stop-opacity: 0;
}

.rovuy_e_s {
  stop-color: var(--svg-color--917169, #917169);
}

.rpp-doqri {
  stop-color: var(--svg-color--764e53, #764E53);
  stop-opacity: 0;
}

.rrklpabdz {
  fill: var(--svg-color--88014f, #88014F);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M15.91 6.97a.11.11 0 0 0-.08-.113a.115.115 0 0 0-.128.048a1.2 1.2 0 0 1-.42.396c-.179.103-.37.158-.552.166a.115.115 0 0 0-.107.088c-.01.045.005.1.059.125m1.228-.71l-.05-.003zm0 0a.85.85 0 0 1-.425.683a.85.85 0 0 1-.803.027m0 0l.022-.045m-.022.045l.022-.045m0 0a.8.8 0 0 0 .756-.025a.8.8 0 0 0 .4-.643c.004-.066-.08-.089-.116-.035a1.26 1.26 0 0 1-.437.412a1.3 1.3 0 0 1-.575.173c-.065.003-.086.09-.028.118Z");
}

.rzqsmx-ec {
  d: path("M12.317 6.479c-.057-.098-.127-.262-.082-.366l-.07-.17c.052-.135.175-.11.108-.227l-.18-.312a.22.22 0 0 1 .044-.285a7 7 0 0 1 1.34-.982a7 7 0 0 1 1.52-.67a.24.24 0 0 1 .27.104l-.155-.345c.067.117.303.156.426.189c.258.022.513.8.585.96c.312.692.674 1.366 1.01 2.047c.314.68.066 1.425-.54 1.775l-1.173.677c-.626.36-1.374.192-1.806-.42c-.433-.632-.914-1.311-1.298-1.975");
}

.s2j02zbkr {
  stop-color: var(--svg-color--655e6d, #655E6D);
  stop-opacity: 0;
}

.s5xtkwbhw {
  stop-color: var(--svg-color--6f414d, #6F414D);
  stop-opacity: 0;
}

.seeiowbir {
  stop-color: var(--svg-color--482c58, #482C58);
}

.srjhkll6u {
  fill: var(--svg-color--71404a, #71404A);
  d: path("m14.52 6.214l.06.794c.036.15.199.226.325.153l.27-.156c.126-.073.14-.254.03-.358l-.54-.516c-.118-.115-.183-.078-.144.083");
}

.sxbbp5buq {
  fill: var(--svg-color--261629, #261629);
  fill-rule: evenodd;
  d: path("M14.805 4.973c.249-.176.476-.17.54-.157a.2.2 0 1 0 .086-.388c-.17-.039-.514-.022-.857.22a.2.2 0 1 0 .23.325");
}

.sylx2mbjo {
  stop-color: var(--svg-color--3386c4, #3386C4);
}

.t-eeezbdl {
  stop-color: var(--svg-color--a59ab1, #A59AB1);
  stop-opacity: 0;
}

.t3--w_blh {
  stop-color: var(--svg-color--79534a, #79534A);
}

.tcgi-acxh {
  stop-color: var(--svg-color--563450, #563450);
}

.tesa8u_3j {
  stop-color: var(--svg-color--3083ea, #3083EA);
}

.tm9ge0ksj {
  width: 0.692px;
  height: 1.157px;
  x: 20.651px;
  y: 4.062px;
  fill: var(--svg-color--6f4d40, #6F4D40);
  rx: 0.346px;
}

.truekjbvb {
  stop-color: var(--svg-color--347fda, #347FDA);
}

.tw6dxpb7y {
  stop-color: var(--svg-color--482c58, #482C58);
  stop-opacity: 0;
}

.tye5yqhfq {
  stop-color: var(--svg-color--754e46, #754E46);
}

.uddso4bed {
  stop-color: var(--svg-color--855a5b, #855A5B);
}

.ufp05kbjw {
  d: path("M12.365 5.326a2.9 2.9 0 0 0-.414.876l.257.1c.194.073.414 0 .52-.178a3.4 3.4 0 0 1 1.215-1.183a3.4 3.4 0 0 1 1.632-.46a.42.42 0 0 0 .41-.36l.043-.272a3 3 0 0 0-.966-.08a3.7 3.7 0 0 0-2.697 1.557");
}

.umkjkab9d {
  cx: 12.912px;
  cy: 7.202px;
  r: 0.704px;
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

.vp_s2ybyh {
  d: path("M14.522 23.971a1 1 0 0 0 .275-.711l-.167-7.29h6.02l-.312 12.476H18.18l-.259-10.002a.255.255 0 0 0-.509-.005c-.049 1.196-.13 3.455-.13 4.585c0 1.212-.693 2.213-1.04 2.562l-2.472 2.288a.32.32 0 0 1-.317.082a2.2 2.2 0 0 1-.718-.424c-.252-.225-.439-.553-.547-.795a.36.36 0 0 1 .078-.393z");
}

.vpmiz7bmj {
  d: path("M13.604 6.239a.376.376 0 0 0-.076.593l.63-.364a.38.38 0 0 0-.553-.23");
}

.w_jlcfbxk {
  stop-color: var(--svg-color--794b50, #794B50);
}

.w-44tpbkk {
  stop-color: var(--svg-color--976f6a, #976F6A);
}

.w5oxhdc5r {
  stop-color: var(--svg-color--7f5d9d, #7F5D9D);
}

.w6mxzsbgv {
  stop-color: var(--svg-color--9d766b, #9D766B);
}

.we0trlbug {
  stop-color: var(--svg-color--246c9d, #246C9D);
  stop-opacity: 0;
}

.wgn2-qn3r {
  stop-color: var(--svg-color--84615a, #84615A);
}

.whxihzpaf {
  stop-color: var(--svg-color--5f3e52, #5F3E52);
}

.wn-t5ndzy {
  stop-color: var(--svg-color--b8acbd, #B8ACBD);
}

.x9_x14ckq {
  stop-color: var(--svg-color--3090bc, #3090BC);
  stop-opacity: 0;
}

.xezbdyc0d {
  d: path("M13.201 2.77c.526-.303 1.12-.437 1.68-.234c.43.155.891.633 1.147 1.313a3 3 0 0 0-.966-.08a3.7 3.7 0 0 0-2.697 1.557a2.9 2.9 0 0 0-.413.876c-.463-.565-.644-1.2-.564-1.65c.105-.586.518-1.034 1.043-1.337z");
}

.xh6agdcni {
  stop-color: var(--svg-color--59323c, #59323C);
}

.xhu8yhbcw {
  stop-color: var(--svg-color--9f9c9d, #9F9C9D);
  stop-opacity: 0;
}

.xi1si-bir {
  fill: var(--svg-color--000, #000);
  d: path("M15.2 5.751a.214.214 0 0 1 .08-.294a.214.214 0 0 1 .322.177l-.33.19a.2.2 0 0 1-.071-.073");
}

.xi8fv135v {
  stop-color: var(--svg-color--8c7e97, #8C7E97);
  stop-opacity: 0;
}

.y_z4ite8v {
  stop-color: var(--svg-color--7c4559, #7C4559);
  stop-opacity: 0;
}

.y6ovumr8k {
  stop-color: var(--svg-color--a59ab1, #A59AB1);
}

.y8ripg49t {
  d: path("M14.068 6.355c-.061-.106-.187-.127-.223-.134l-.046.162l.14.095z");
}

.y91wuhb_y {
  stop-color: var(--svg-color--966d5f, #966D5F);
}

.ydllxhbat {
  stop-color: var(--svg-color--4195cb, #4195CB);
  stop-opacity: 0;
}

.ylom6naui {
  stop-color: var(--svg-color--9d766b, #9D766B);
  stop-opacity: 0;
}

.ynlfw99ba {
  stop-color: var(--svg-color--403451, #403451);
}

.ypda30bla {
  fill: var(--svg-color--fff, #fff);
  d: path("M15.218 5.175a.59.59 0 0 1 .718.1a.116.116 0 0 1-.026.182l-.815.47a.097.097 0 0 1-.14-.051a.59.59 0 0 1 .263-.701");
}

.yq02ovbhw {
  d: path("M13.927 9.86c.176-1.285.703-1.862 1-2.07c.51-.359 1.664-.946 3.336 0c1.758 1.093 2.404 4.057 2.375 5.374v2.805h-6v-3.242c0-.488-.105-.742-.258-.961c-.144-.258-.52-.98-.453-1.906");
}

.yrm14tb3b {
  stop-color: var(--svg-color--579fde, #579FDE);
  stop-opacity: 0;
}

.ywu0pr7ii {
  stop-color: var(--svg-color--7c524c, #7C524C);
}

.z_g0j449a {
  stop-color: var(--svg-color--6f414d, #6F414D);
}

.z3o7w4-ew {
  stop-color: var(--svg-color--96776b, #96776B);
}

.zn47ozbfv {
  stop-color: var(--svg-color--442563, #442563);
  stop-opacity: 0;
}

</style>
