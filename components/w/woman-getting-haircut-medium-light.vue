<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iHAV37b)"><path fill="url(#i6IsYOd)" clip-rule="evenodd" class="yyo16fhfg"/><path fill="url(#i8HqHae)" clip-rule="evenodd" class="yyo16fhfg"/><path fill="url(#iAiMQtc)" clip-rule="evenodd" class="yyo16fhfg"/><path fill="url(#i4YViYd)" clip-rule="evenodd" class="yyo16fhfg"/><path fill="url(#iYq3UEd)" clip-rule="evenodd" class="yyo16fhfg"/><path fill="url(#ixhXDHb)" clip-rule="evenodd" class="yyo16fhfg"/><path fill="url(#iRZCnhb)" clip-rule="evenodd" class="yyo16fhfg"/><path fill="url(#iwY004c)" clip-rule="evenodd" class="yyo16fhfg"/><path fill="url(#i8Cbsyb)" clip-rule="evenodd" class="yyo16fhfg"/><path fill="url(#iKjMDbe)" clip-rule="evenodd" class="yyo16fhfg"/></g><path fill="url(#iV5YFdZ)" clip-rule="evenodd" class="yyo16fhfg"/><path fill="url(#iYpna8t)" class="h064k9b1n"/><path fill="url(#iUKebPb)" class="h064k9b1n"/><path fill="url(#ic5d39d)" class="h064k9b1n"/><path fill="url(#ihEx4Ab)" class="h064k9b1n"/><path fill="url(#itb84Mb)" class="h064k9b1n"/><path fill="url(#iVhpSld)" class="nm6odobve"/><path fill="url(#il0VLoc)" class="nm6odobve"/><path class="x7bl4zbkb"/><path fill="url(#i3eTupc)" class="d0mty6dok"/><path fill="url(#iQULaLb)" class="d0mty6dok"/><path class="s9uh1ibhz"/><path fill="url(#ibRH4re)" class="x_nfl_ozw"/><path fill="url(#iZg5nnb)" class="x_nfl_ozw"/><path fill="url(#ieqwvgd)" class="r_t9aq_-g"/><path fill="url(#i3U51ac)" class="a-cgv50-r"/><path fill="url(#iaavARj)" class="c094r_bvs"/><path fill="url(#iuCwFLd)" class="c094r_bvs"/><path fill="url(#iGTaVxe)" class="c094r_bvs"/><path fill="url(#idg2PIc)" class="c094r_bvs"/><path fill="url(#ipYPb9b)" class="a41xocxec"/><path fill="url(#iwWxddP)" class="a41xocxec"/><path fill="url(#iaC38ue)" class="jrx3i8b1t"/><path fill="url(#irzfGIb)" class="jrx3i8b1t"/><g filter="url(#irqxeZN)"><circle fill="url(#iVmkACb)" class="m8gsznlzl"/><circle fill="url(#iRQA0se)" class="m8gsznlzl"/><circle fill="url(#iu94fIb)" class="m8gsznlzl"/></g><g filter="url(#igxHKbd)"><path fill="url(#if1AEES)" clip-rule="evenodd" class="bqqvv7bor"/></g><path fill="url(#ipFIR2b)" clip-rule="evenodd" class="bqqvv7bor"/><g filter="url(#ij8zYLe)"><path fill="url(#iqfCaLe)" clip-rule="evenodd" class="a4_5g-kex"/></g><g filter="url(#imNmmAc)"><circle stroke="url(#iGw8SZc)" class="gm_5gldko"/></g><g filter="url(#i9959rb)"><circle stroke="url(#i25s7Yc)" class="v83a3u3_r"/></g><g filter="url(#iuKdKLd)"><circle stroke="url(#iNMJJ0c)" class="uxe1igbwt"/></g><g filter="url(#iWIWRwM)"><circle stroke="url(#iLnBePe)" class="wj0k-xifb"/></g><g filter="url(#irzqWIi)"><path fill="url(#iYBCNGd)" class="fctahwg2u"/></g><g filter="url(#iuKTaCC)"><path fill="url(#ifDt0Sb)" class="bjg6icb4c"/><path fill="url(#ilT7t3b)" class="bjg6icb4c"/></g><g filter="url(#ijIvHlb)"><path class="tt1el8-0z"/><path fill="url(#iKlw8CX)" class="jhmvwwj-n"/></g><g filter="url(#itkmrZc)"><path class="u-2cz8img"/><path fill="url(#iQC8Mid)" class="nuj2mebaj"/></g><g filter="url(#iBADckd)"><path fill="url(#iTuHFhc)" class="qvhay2blz"/><path fill="url(#iLFXQ9c)" class="qvhay2blz"/><path fill="url(#ir0c0cd)" class="qvhay2blz"/><path fill="url(#iwNL3jb)" class="qvhay2blz"/><path fill="url(#inNaxHc)" class="qvhay2blz"/><path fill="url(#iBUCd9L)" class="qvhay2blz"/><path fill="url(#ivQvCsb)" class="qvhay2blz"/></g><path fill="url(#iqKm84b)" class="i7q3c4b_a"/><path fill="url(#iorQ2Ec)" class="i7q3c4b_a"/><g filter="url(#ilkSNpb)"><path class="jt1e3kk0x"/></g><g filter="url(#iG5MXPb)"><path class="ip_ig3ymd"/><path fill="url(#iyWvlUb)" class="v4a1t-bae"/><path fill="url(#iKNq2Kd)" class="v4a1t-bae"/><path fill="url(#idx9WSq)" class="v4a1t-bae"/></g><g filter="url(#ibntree)"><path stroke="url(#iTgmvrT)" class="m14m72bli"/></g><path class="se95iybxr"/><g filter="url(#isW47Yc)"><path class="jd8suhxpk"/></g><g filter="url(#iP9Raqc)"><path class="fcfy7lbst"/></g><g filter="url(#i3TvUrd)"><path class="ix3rj1bpb"/></g><g filter="url(#istKN6d)"><path clip-rule="evenodd" class="c12gy1bqd"/></g><path class="l6jzqxbsk"/><path fill="url(#idS0Cbc)" class="dm2loxwba"/><path class="batvhqbnr"/><g filter="url(#ikbTIQs)"><path class="qm9xdibjl"/><path fill="url(#i0XYF6b)" class="vztm_v--z"/></g><g filter="url(#iDQ94mo)"><path fill="url(#iK5Xfbb)" class="jt5or2b5w"/></g><path class="pj-m4ibrz"/><path fill="url(#iwquGsc)" class="n-5yzizlv"/><path class="lxuiw-btm"/><g filter="url(#iU7krNb)"><path fill="url(#it3g9Ac)" class="i8pojfbqt"/></g><g filter="url(#ioudHic)"><ellipse transform="rotate(-27.914 12.307 12.178)" class="jjkt6fbmu"/><ellipse fill="url(#itd3wmP)" transform="rotate(-27.914 12.307 12.178)" class="q4hm6bcis"/></g><g filter="url(#i4CI6cc)"><path class="wpaw55bnu"/></g><g filter="url(#iWbzJkd)"><path class="behdzxejw"/></g><g filter="url(#iDAZyfe)"><path fill="url(#iMjvy6N)" class="eu731sb1k"/><path fill="url(#icE50Kd)" class="eu731sb1k"/></g><g filter="url(#iJPCgnb)"><path fill="url(#iVbTTHb)" class="vg12hr_5o"/><path fill="url(#iWp9Mee)" class="vg12hr_5o"/><path fill="url(#iYGyaEV)" class="vg12hr_5o"/></g><g filter="url(#iunlXqb)"><path stroke="url(#iA9HTae)" class="nl6ccacdu"/></g><defs><radialGradient id="i8HqHae" cx="0" cy="0" r="1" gradientTransform="matrix(1.74318 -3.62044 8.25485 3.97456 19.454 18.69)" gradientUnits="userSpaceOnUse"><stop class="rjxj417_v"/><stop offset="1" class="p1sg1mumi"/></radialGradient><radialGradient id="iAiMQtc" cx="0" cy="0" r="1" gradientTransform="rotate(109.074 1.833 12.336)scale(5.77873 5.40927)" gradientUnits="userSpaceOnUse"><stop offset=".62" class="ta36f8b7v"/><stop offset="1" class="hcuenbefp"/></radialGradient><radialGradient id="i4YViYd" cx="0" cy="0" r="1" gradientTransform="rotate(142.167 3.142 9.815)scale(3.98975 4.91117)" gradientUnits="userSpaceOnUse"><stop offset=".205" class="hxuphr-8h"/><stop offset="1" class="v-9s4u7ch"/></radialGradient><radialGradient id="iYq3UEd" cx="0" cy="0" r="1" gradientTransform="rotate(125.038 1.553 9.125)scale(1.78101 1.61886)" gradientUnits="userSpaceOnUse"><stop offset=".334" class="ybvptdnhb"/><stop offset="1" class="ue-yx0baa"/></radialGradient><radialGradient id="ixhXDHb" cx="0" cy="0" r="1" gradientTransform="rotate(-167.428 5.865 5.225)scale(2.38706 3.50899)" gradientUnits="userSpaceOnUse"><stop offset=".226" class="sqmgyf2vi"/><stop offset="1" class="mvuactshi"/></radialGradient><radialGradient id="iRZCnhb" cx="0" cy="0" r="1" gradientTransform="matrix(2.16229 3.16788 -5.52839 3.77349 10.922 5.298)" gradientUnits="userSpaceOnUse"><stop class="vrnylccvf"/><stop offset="1" class="b442o21cz"/></radialGradient><radialGradient id="iwY004c" cx="0" cy="0" r="1" gradientTransform="rotate(132.51 8.562 8.019)scale(1.63713 2.28786)" gradientUnits="userSpaceOnUse"><stop class="di6ktzbyk"/><stop offset="1" class="ejv935bph"/></radialGradient><radialGradient id="i8Cbsyb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.84366 .53637 -1.16706 -4.01156 22.27 12.02)" gradientUnits="userSpaceOnUse"><stop class="kdig6mnba"/><stop offset="1" class="him6rrbhz"/></radialGradient><radialGradient id="iKjMDbe" cx="0" cy="0" r="1" gradientTransform="matrix(-3.15113 1.34089 -2.13644 -5.02072 22.002 14.802)" gradientUnits="userSpaceOnUse"><stop class="c2fnpwywz"/><stop offset="1" class="c5g3vhi-m"/></radialGradient><radialGradient id="iV5YFdZ" cx="0" cy="0" r="1" gradientTransform="matrix(-.7123 9.96875 -15.00844 -1.0724 15.473 10.853)" gradientUnits="userSpaceOnUse"><stop offset=".703" class="vscv03b8g"/><stop offset="1" class="jrzb3cb0k"/></radialGradient><radialGradient id="iYpna8t" cx="0" cy="0" r="1" gradientTransform="rotate(154.071 8.317 13.902)scale(15.0662 17.3462)" gradientUnits="userSpaceOnUse"><stop class="m5wv9vbgf"/><stop offset="1" class="ok0s313ee"/></radialGradient><radialGradient id="iUKebPb" cx="0" cy="0" r="1" gradientTransform="matrix(-7.90627 -10.81244 15.55864 -11.37678 17.476 29.861)" gradientUnits="userSpaceOnUse"><stop offset=".895" class="je8i96bea"/><stop offset="1" class="r-plgxbvx"/></radialGradient><radialGradient id="ic5d39d" cx="0" cy="0" r="1" gradientTransform="rotate(168.453 5.763 9.951)scale(5.93256 1.70339)" gradientUnits="userSpaceOnUse"><stop class="u4cmqnbdb"/><stop offset="1" class="sncijkqpo"/></radialGradient><radialGradient id="ihEx4Ab" cx="0" cy="0" r="1" gradientTransform="matrix(-3.93377 0 0 -19.371 21.553 29.356)" gradientUnits="userSpaceOnUse"><stop offset=".133" class="p47-3c-mm"/><stop offset="1" class="vzbvt7b3z"/></radialGradient><radialGradient id="itb84Mb" cx="0" cy="0" r="1" gradientTransform="matrix(1.5 0 0 23.8126 7.432 29.356)" gradientUnits="userSpaceOnUse"><stop class="g6dgamb9p"/><stop offset="1" class="hnlppfbil"/></radialGradient><radialGradient id="iVhpSld" cx="0" cy="0" r="1" gradientTransform="matrix(3.25185 0 0 9.13279 21.584 28.577)" gradientUnits="userSpaceOnUse"><stop offset=".576" class="zduonub6o"/><stop offset="1" class="cuty5mbvc"/></radialGradient><radialGradient id="il0VLoc" cx="0" cy="0" r="1" gradientTransform="matrix(.87006 0 0 11.9715 21.584 29.356)" gradientUnits="userSpaceOnUse"><stop class="iwql9tbwr"/><stop offset="1" class="cpuxbvbrp"/></radialGradient><radialGradient id="i3eTupc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.70862 0 0 -8.85437 7.317 29.356)" gradientUnits="userSpaceOnUse"><stop offset=".614" class="fxt5p0b8w"/><stop offset="1" class="f4vmrjbib"/></radialGradient><radialGradient id="iQULaLb" cx="0" cy="0" r="1" gradientTransform="matrix(-.8463 0 0 -10.457 7.317 29.356)" gradientUnits="userSpaceOnUse"><stop offset=".111" class="f3tc_zfmh"/><stop offset="1" class="nhus6q3at"/></radialGradient><radialGradient id="ibRH4re" cx="0" cy="0" r="1" gradientTransform="matrix(.5625 1.75 -3.03541 .97567 13.708 18.647)" gradientUnits="userSpaceOnUse"><stop offset=".243" class="sbc0_sbjc"/><stop offset="1" class="l5h2ci_uw"/></radialGradient><radialGradient id="iZg5nnb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.9674 2.28562 -.98994 -1.28524 17.598 19.517)" gradientUnits="userSpaceOnUse"><stop offset=".285" class="i-r212mzs"/><stop offset="1" class="td2-_ccfi"/></radialGradient><radialGradient id="iaavARj" cx="0" cy="0" r="1" gradientTransform="matrix(-6.21875 1.75 -2.17983 -7.74618 23.463 6.204)" gradientUnits="userSpaceOnUse"><stop class="x47l8abks"/><stop offset=".556" class="uhe1-9bau"/><stop offset=".899" class="wzytc_e9p"/></radialGradient><radialGradient id="iuCwFLd" cx="0" cy="0" r="1" gradientTransform="matrix(.16455 1.30288 -.72715 .09184 23.277 4.55)" gradientUnits="userSpaceOnUse"><stop offset=".181" class="h4i3jv0ko"/><stop offset="1" class="j1_ihyvvo"/></radialGradient><radialGradient id="iGTaVxe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .75 -1.93101 0 20.084 6.634)" gradientUnits="userSpaceOnUse"><stop class="jk8vytb-s"/><stop offset="1" class="d7yxou7le"/></radialGradient><radialGradient id="idg2PIc" cx="0" cy="0" r="1" gradientTransform="matrix(1.3125 1.96875 -8.17451 5.44966 20.254 6.947)" gradientUnits="userSpaceOnUse"><stop offset=".535" class="toezc-l1m"/><stop offset="1" class="p--9xsbqt"/></radialGradient><radialGradient id="iVmkACb" cx="0" cy="0" r="1" gradientTransform="rotate(141.18 10.736 7.664)scale(.43619)" gradientUnits="userSpaceOnUse"><stop offset=".168" class="cz-qsgbfy"/><stop offset="1" class="j80tr6o9y"/></radialGradient><radialGradient id="iRQA0se" cx="0" cy="0" r="1" gradientTransform="matrix(.19922 -.48438 1.17186 .48198 23.586 7.347)" gradientUnits="userSpaceOnUse"><stop offset=".147" class="m8bo-jb-t"/><stop offset="1" class="wy7e69bbh"/></radialGradient><radialGradient id="iu94fIb" cx="0" cy="0" r="1" gradientTransform="matrix(.4375 .04684 -.05916 .55254 23.361 6.91)" gradientUnits="userSpaceOnUse"><stop offset=".181" class="zk512ndyg"/><stop offset="1" class="hy0z0nf6k"/></radialGradient><radialGradient id="if1AEES" cx="0" cy="0" r="1" gradientTransform="matrix(2.20247 -1.61719 2.56784 3.49718 21.389 10.096)" gradientUnits="userSpaceOnUse"><stop offset=".205" class="cnux6p8xn"/><stop offset="1" class="jaxt-o31p"/></radialGradient><radialGradient id="iqfCaLe" cx="0" cy="0" r="1" gradientTransform="matrix(2.53124 -1.40627 1.98705 3.57664 24.535 8.273)" gradientUnits="userSpaceOnUse"><stop offset=".205" class="cnux6p8xn"/><stop offset="1" class="jaxt-o31p"/></radialGradient><radialGradient id="ifDt0Sb" cx="0" cy="0" r="1" gradientTransform="matrix(2.48905 -1.13139 1.38138 3.03902 18.8 13.31)" gradientUnits="userSpaceOnUse"><stop offset=".572" class="qmmvvysmp"/><stop offset=".905" class="epx_cgb2c"/></radialGradient><radialGradient id="ilT7t3b" cx="0" cy="0" r="1" gradientTransform="matrix(.9973 .28494 -.1498 .52432 19.823 11.09)" gradientUnits="userSpaceOnUse"><stop class="aso-vybjw"/><stop offset="1" class="krvd34mtu"/></radialGradient><radialGradient id="iKlw8CX" cx="0" cy="0" r="1" gradientTransform="rotate(-20.298 46.293 -47.503)scale(1.30459)" gradientUnits="userSpaceOnUse"><stop offset=".71" class="la61skb4q"/><stop offset="1" class="urs_pbb4x"/></radialGradient><radialGradient id="iQC8Mid" cx="0" cy="0" r="1" gradientTransform="matrix(-1.21686 0 0 -1.164 10.094 12.871)" gradientUnits="userSpaceOnUse"><stop offset=".573" class="prydr8bcy"/><stop offset="1" class="ybx_6zbxd"/></radialGradient><radialGradient id="iTuHFhc" cx="0" cy="0" r="1" gradientTransform="matrix(-6.50358 2.99902 -4.01413 -8.70492 17.62 12.334)" gradientUnits="userSpaceOnUse"><stop class="uy3z2gbbp"/><stop offset="1" class="gvh2bspmv"/></radialGradient><radialGradient id="iLFXQ9c" cx="0" cy="0" r="1" gradientTransform="matrix(-2.10973 1.11592 -.94678 -1.78996 16.66 13.031)" gradientUnits="userSpaceOnUse"><stop class="j8hkuac-d"/><stop offset="1" class="cre_5tbhq"/></radialGradient><radialGradient id="ir0c0cd" cx="0" cy="0" r="1" gradientTransform="matrix(.8369 -4.04513 5.13253 1.06187 12.58 19.116)" gradientUnits="userSpaceOnUse"><stop class="t6jzi2-1t"/><stop offset="1" class="i3g5qu-9r"/></radialGradient><radialGradient id="iwNL3jb" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.18123 -9.73459 0 14.76 12.046)" gradientUnits="userSpaceOnUse"><stop offset=".626" class="kwdmgfmeb"/><stop offset="1" class="i7ikbtc_p"/></radialGradient><radialGradient id="inNaxHc" cx="0" cy="0" r="1" gradientTransform="rotate(172.34 7.208 7.85)scale(5.78399 9.95825)" gradientUnits="userSpaceOnUse"><stop offset=".813" class="zzstxpr9j"/><stop offset="1" class="irzp_cb7o"/></radialGradient><radialGradient id="iBUCd9L" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.15077 1.65436 0 17.062 11.915)" gradientUnits="userSpaceOnUse"><stop offset=".259" class="mt3h7fbpd"/><stop offset="1" class="wcr1klbjh"/></radialGradient><radialGradient id="ivQvCsb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.36 1.55865 0 12.842 12.002)" gradientUnits="userSpaceOnUse"><stop class="r-jog4w_t"/><stop offset="1" class="xjkdvxqyn"/></radialGradient><radialGradient id="iqKm84b" cx="0" cy="0" r="1" gradientTransform="matrix(-1.34695 0 0 -4.43421 19.856 13.403)" gradientUnits="userSpaceOnUse"><stop class="yhs2bn2id"/><stop offset="1" class="g1fw3-bff"/></radialGradient><radialGradient id="iorQ2Ec" cx="0" cy="0" r="1" gradientTransform="matrix(1.15625 4.21875 -8.71783 2.38933 12.26 6.828)" gradientUnits="userSpaceOnUse"><stop class="mih5kfbap"/><stop offset="1" class="kqfxh5bnm"/></radialGradient><radialGradient id="iyWvlUb" cx="0" cy="0" r="1" gradientTransform="matrix(-.69746 -2.44974 1.40177 -.3991 15.545 14.13)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="xjug-415a"/><stop offset="1" class="bd8jqdorr"/></radialGradient><radialGradient id="idS0Cbc" cx="0" cy="0" r="1" gradientTransform="scale(1.29049 .81132)rotate(90 -1 14.129)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="i0XYF6b" cx="0" cy="0" r="1" gradientTransform="matrix(-.23192 -.29886 .41145 -.3193 16.714 12.358)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iwquGsc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.2905 0 12.578 12.274)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="itd3wmP" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 12.296 .196)scale(.49412 .59395)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iMjvy6N" cx="0" cy="0" r="1" gradientTransform="matrix(1.93486 2.6818 -5.32876 3.84458 8.803 6.623)" gradientUnits="userSpaceOnUse"><stop offset=".403" class="hi5yi9bqv"/><stop offset="1" class="d8y_5zbge"/></radialGradient><radialGradient id="icE50Kd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.87735 2.48068 -1.9455 -1.47233 12.045 6.857)" gradientUnits="userSpaceOnUse"><stop class="g6mu4o3fz"/><stop offset="1" class="dx30lgbdy"/></radialGradient><radialGradient id="iVbTTHb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.11195 4.39145 -6.24446 -3.00311 16.671 4.946)" gradientUnits="userSpaceOnUse"><stop offset=".595" class="iz4jcxg0j"/><stop offset="1" class="qflnpfbur"/></radialGradient><radialGradient id="iWp9Mee" cx="0" cy="0" r="1" gradientTransform="matrix(-.8568 3.20722 -5.72497 -1.5294 17.074 6.12)" gradientUnits="userSpaceOnUse"><stop class="mv8kv7beo"/><stop offset="1" class="g_ulzrbqz"/></radialGradient><radialGradient id="iYGyaEV" cx="0" cy="0" r="1" gradientTransform="rotate(-119.068 11.433 1.07)scale(7.21046 6.45439)" gradientUnits="userSpaceOnUse"><stop offset=".891" class="w58maet4h"/><stop offset=".979" class="drxq29wnr"/></radialGradient><filter id="iHAV37b" width="15.268" height="15.768" x="7.252" y="3.593" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.886275 0 0 0 0 0.698039 0 0 0 0 0.607843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_34"/></filter><filter id="irqxeZN" width=".726" height=".726" x="23.418" y="6.587" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.52549 0 0 0 0 0.388235 0 0 0 0 0.501961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_34"/></filter><filter id="igxHKbd" width="3.834" height="4.387" x="20.96" y="7.388" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.945098 0 0 0 0 0.45098 0 0 0 0 0.333333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_34"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.282353 0 0 0 0 0.435294 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_34" result="effect2_innerShadow_4002_34"/></filter><filter id="ij8zYLe" width="4.283" height="3.734" x="24.158" y="5.911" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.882353 0 0 0 0 0.203922 0 0 0 0 0.435294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_34"/></filter><filter id="imNmmAc" width="3.843" height="3.843" x="24.629" y="5.882" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_34" stdDeviation=".1"/></filter><filter id="i9959rb" width="2.734" height="2.734" x="25.183" y="6.436" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_34" stdDeviation=".1"/></filter><filter id="iuKdKLd" width="2.734" height="2.734" x="21.535" y="8.45" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_34" stdDeviation=".1"/></filter><filter id="iWIWRwM" width="3.805" height="3.805" x="21" y="7.915" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_34" stdDeviation=".1"/></filter><filter id="irzqWIi" width="3.368" height="3.468" x="8.466" y="11.262" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.858824 0 0 0 0 0.635294 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_34"/></filter><filter id="iuKTaCC" width="3.218" height="3.468" x="17.979" y="11.012" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.827451 0 0 0 0 0.568627 0 0 0 0 0.505882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_34"/></filter><filter id="ijIvHlb" width="3.148" height="3.148" x="18.014" y="11.297" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_34" stdDeviation=".25"/></filter><filter id="itkmrZc" width="2.948" height="2.948" x="8.62" y="11.397" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_34" stdDeviation=".2"/></filter><filter id="iBADckd" width="10.191" height="11.127" x="9.665" y="7.964" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.745098 0 0 0 0 0.486275 0 0 0 0 0.384314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_34"/></filter><filter id="ilkSNpb" width="2.877" height="3.682" x="13.16" y="11.866" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_34" stdDeviation=".25"/></filter><filter id="iG5MXPb" width="2.377" height="3.182" x="13.572" y="11.977" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_34" stdDeviation=".125"/></filter><filter id="ibntree" width="3.702" height="1.526" x="12.909" y="15.219" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_34" stdDeviation=".05"/></filter><filter id="isW47Yc" width="3.001" height="1.285" x="15.703" y="11.467" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.141176 0 0 0 0 0.0862745 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_34"/></filter><filter id="iP9Raqc" width="3.001" height="1.285" x="10.817" y="11.467" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.133333 0 0 0 0 0.0784314 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_34"/></filter><filter id="i3TvUrd" width="2.453" height="1.091" x="10.953" y="10.043" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.262745 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_34"/></filter><filter id="istKN6d" width="2.453" height="1.091" x="16.37" y="10.043" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.262745 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_34"/></filter><filter id="ikbTIQs" width=".787" height=".696" x="16.209" y="11.834" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_34" stdDeviation=".05"/></filter><filter id="iDQ94mo" width=".891" height=".913" x="17.048" y="11.909" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_34" stdDeviation=".1"/></filter><filter id="iU7krNb" width=".986" height="1.04" x="12.605" y="11.846" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_34" stdDeviation=".1"/></filter><filter id="ioudHic" width=".913" height=".705" x="11.851" y="11.826" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_34" stdDeviation=".05"/></filter><filter id="i4CI6cc" width="2.261" height=".978" x="16.4" y="10.165" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_34" stdDeviation=".1"/></filter><filter id="iWbzJkd" width="2.261" height=".978" x="10.948" y="10.165" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_34" stdDeviation=".1"/></filter><filter id="iDAZyfe" width="4.287" height="5.25" x="8.501" y="5.845" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_34" stdDeviation=".25"/></filter><filter id="iJPCgnb" width="8.914" height="5.78" x="11.443" y="4.797" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_34" stdDeviation=".125"/></filter><filter id="iunlXqb" width="1.145" height="2.31" x="11.569" y="6.029" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_34" stdDeviation=".1"/></filter><linearGradient id="i6IsYOd" x1="19.454" x2="12.649" y1="5.918" y2="18.523" gradientUnits="userSpaceOnUse"><stop class="p6otu2-6b"/><stop offset="1" class="q5mih6mme"/></linearGradient><linearGradient id="ieqwvgd" x1="7.446" x2="21.822" y1="17.711" y2="17.711" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="i3U51ac" x1="7.446" x2="21.822" y1="17.681" y2="17.681" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="ipYPb9b" x1="24.941" x2="23.75" y1="5.049" y2="4.704" gradientUnits="userSpaceOnUse"><stop class="p9lsnsm5t"/><stop offset="1" class="lapvr59ed"/></linearGradient><linearGradient id="iwWxddP" x1="23.793" x2="23.867" y1="6.542" y2="6.253" gradientUnits="userSpaceOnUse"><stop offset=".16" class="zl0fwhbas"/><stop offset="1" class="lxc0fmbqt"/></linearGradient><linearGradient id="iaC38ue" x1="22.879" x2="23.144" y1="7.398" y2="6.101" gradientUnits="userSpaceOnUse"><stop class="p9lsnsm5t"/><stop offset="1" class="lapvr59ed"/></linearGradient><linearGradient id="irzfGIb" x1="24.29" x2="24.092" y1="7.48" y2="7.424" gradientUnits="userSpaceOnUse"><stop class="jd-vaq0no"/><stop offset="1" class="gof7ehbkx"/></linearGradient><linearGradient id="ipFIR2b" x1="23.629" x2="23.57" y1="7.57" y2="7.796" gradientUnits="userSpaceOnUse"><stop offset=".209" class="ni_6htbzm"/><stop offset="1" class="ajm38_jxm"/></linearGradient><linearGradient id="iGw8SZc" x1="24.879" x2="28.069" y1="8.172" y2="6.7" gradientUnits="userSpaceOnUse"><stop offset=".616" class="w5_7ycb6b"/><stop offset=".9" class="srm_r_guo"/></linearGradient><linearGradient id="i25s7Yc" x1="25.433" x2="27.566" y1="8.05" y2="7.066" gradientUnits="userSpaceOnUse"><stop offset=".247" class="jzjqx7qlk"/><stop offset=".669" class="gl3wl_9gz"/></linearGradient><linearGradient id="iNMJJ0c" x1="21.785" x2="23.917" y1="10.064" y2="9.079" gradientUnits="userSpaceOnUse"><stop offset=".247" class="rraw6sbsp"/><stop offset=".669" class="r8ibvzbki"/></linearGradient><linearGradient id="iLnBePe" x1="24.554" x2="22.902" y1="9.276" y2="9.817" gradientUnits="userSpaceOnUse"><stop class="znwvjy5yx"/><stop offset="1" class="zi0lb2bns"/></linearGradient><linearGradient id="iYBCNGd" x1="8.466" x2="11.425" y1="12.958" y2="12.958" gradientUnits="userSpaceOnUse"><stop class="nka4--b6e"/><stop offset="1" class="aps1jhbfc"/></linearGradient><linearGradient id="iKNq2Kd" x1="13.714" x2="14.569" y1="14.147" y2="14.252" gradientUnits="userSpaceOnUse"><stop class="urkjpbftr"/><stop offset="1" class="lwjatlajn"/></linearGradient><linearGradient id="idx9WSq" x1="14.761" x2="14.761" y1="15.001" y2="14.391" gradientUnits="userSpaceOnUse"><stop class="dvyniwihb"/><stop offset="1" class="e5pm1bciq"/></linearGradient><linearGradient id="iTgmvrT" x1="14.031" x2="14.484" y1="16.478" y2="15.607" gradientUnits="userSpaceOnUse"><stop class="hvrv4iryz"/><stop offset="1" class="u1r8ksb5m"/></linearGradient><linearGradient id="iK5Xfbb" x1="17.721" x2="17.407" y1="12.328" y2="12.521" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="it3g9Ac" x1="13.322" x2="13.009" y1="12.328" y2="12.521" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iA9HTae" x1="11.869" x2="12.414" y1="6.673" y2="7.947" gradientUnits="userSpaceOnUse"><stop class="gjbrx7i8b"/><stop offset="1" class="zcr9jykfw"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-getting-haircut-medium-light" /></template>
<style>
.a-cgv50-r {
  d: path("M14.656 17.681h-.04c.1 0 .19 0 .29.01c-.08-.01-.17-.01-.25-.01");
}

.a4_5g-kex {
  fill-rule: evenodd;
  d: path("M24.45 6.655a.1.1 0 0 1 .122-.07l.36.095a.22.22 0 0 0 .216-.072a1.842 1.842 0 1 1-.412 1.52a.22.22 0 0 0-.152-.172l-.352-.094a.1.1 0 0 1-.07-.122zm1.663 1.87a.844.844 0 1 0 .872-1.444a.844.844 0 0 0-.872 1.445");
}

.a41xocxec {
  d: path("m24.334 2.644l-1.388 4.83l1.187.346l1.071-3.73a1.15 1.15 0 0 0-.784-1.421z");
}

.ajm38_jxm {
  stop-color: var(--svg-color--ff3178, #FF3178);
  stop-opacity: 0;
}

.aps1jhbfc {
  stop-color: var(--svg-color--b47860, #B47860);
}

.aso-vybjw {
  stop-color: var(--svg-color--d59566, #D59566);
}

.b442o21cz {
  stop-color: var(--svg-color--dcc893, #DCC893);
  stop-opacity: 0;
}

.batvhqbnr {
  fill: var(--svg-color--000, #000);
  d: path("M16.434 12.69a.51.51 0 0 1 .51-.512a.51.51 0 0 1 .455.747h-.905a.46.46 0 0 1-.06-.236");
}

.bd8jqdorr {
  stop-color: var(--svg-color--fdc9a8, #FDC9A8);
  stop-opacity: 0;
}

.behdzxejw {
  stroke: var(--svg-color--a57045, #A57045);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M12.91 10.499c-.323-.079-1.125-.04-1.662.344");
}

.bjg6icb4c {
  d: path("M19.588 14.48a1.61 1.61 0 1 0 0-3.218a1.61 1.61 0 0 0 0 3.218");
}

.bqqvv7bor {
  fill-rule: evenodd;
  d: path("M23.005 7.442a.1.1 0 0 0-.124.068l-.104.357a.21.21 0 0 1-.174.149a1.842 1.842 0 1 0 1.514.433a.21.21 0 0 1-.068-.22l.102-.349a.1.1 0 0 0-.069-.124zm.741 2.391a.844.844 0 1 1-1.688 0a.844.844 0 0 1 1.688 0");
}

.c094r_bvs {
  d: path("M20.71 6.65c-1.262.462-2.101.413-2.648.171L16.89 9.673c1.29.054 3.8-.332 5.563-2.383c.843-.982.996-1.91.656-2.586c-.061-.122-.183-.172-.27-.149c-.086.024-.16.109-.187.207c-.162.567-.538 1.373-1.942 1.887");
}

.c12gy1bqd {
  fill: var(--svg-color--9f6836, #9F6836);
  fill-rule: evenodd;
  d: path("m18.492 10.636l-.138.23za.268.268 0 0 1-.275.46l-.005-.003l-.022-.012l-.091-.046a3 3 0 0 0-.343-.135a2.3 2.3 0 0 0-1.071-.092a.268.268 0 1 1-.094-.528c.513-.09.989 0 1.329.109a3.3 3.3 0 0 1 .558.239l.01.005z");
}

.c2fnpwywz {
  stop-color: var(--svg-color--fff4bc, #FFF4BC);
}

.c5g3vhi-m {
  stop-color: var(--svg-color--fff4bc, #FFF4BC);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cnux6p8xn {
  stop-color: var(--svg-color--ff7046, #FF7046);
}

.cpuxbvbrp {
  stop-color: var(--svg-color--8752d9, #8752D9);
  stop-opacity: 0;
}

.cre_5tbhq {
  stop-color: var(--svg-color--ffc89e, #FFC89E);
  stop-opacity: 0;
}

.cuty5mbvc {
  stop-color: var(--svg-color--9775dd, #9775DD);
}

.cz-qsgbfy {
  stop-color: var(--svg-color--ebdbe4, #EBDBE4);
}

.d0mty6dok {
  d: path("M7.317 20.827C5.044 22.79 3.61 25.676 3.61 28.893v.463h3.708z");
}

.d7yxou7le {
  stop-color: var(--svg-color--dabd87, #DABD87);
  stop-opacity: 0;
}

.d8y_5zbge {
  stop-color: var(--svg-color--daa88f, #DAA88F);
}

.di6ktzbyk {
  stop-color: var(--svg-color--ffffbf, #FFFFBF);
}

.dm2loxwba {
  d: path("M16.945 11.797a.892.892 0 0 1 .86 1.128H16.08a.896.896 0 0 1 .864-1.128");
}

.drxq29wnr {
  stop-color: var(--svg-color--dac493, #DAC493);
}

.dvyniwihb {
  stop-color: var(--svg-color--c57f82, #C57F82);
}

.dx30lgbdy {
  stop-color: var(--svg-color--fee2a9, #FEE2A9);
  stop-opacity: 0;
}

.e5pm1bciq {
  stop-color: var(--svg-color--c57f82, #C57F82);
  stop-opacity: 0;
}

.ejv935bph {
  stop-color: var(--svg-color--ffffbf, #FFFFBF);
  stop-opacity: 0;
}

.epx_cgb2c {
  stop-color: var(--svg-color--f6c3a3, #F6C3A3);
}

.eu731sb1k {
  d: path("M9.866 6.857c.622-.553 1.517-.558 2.02-.47l.403 1.292c-.258-.04-.487.05-.68.234c-.452 1.676-2.162 1.425-2.497 2.682c-.15-1.492-.318-2.782.754-3.738");
}

.f3tc_zfmh {
  stop-color: var(--svg-color--9a6fdb, #9A6FDB);
}

.f4vmrjbib {
  stop-color: var(--svg-color--8267b6, #8267B6);
}

.fcfy7lbst {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M13.619 12.302c-.266-.467-.67-.835-1.538-.835c-.38 0-.747.105-1.072.368c-.27.217-.233.495-.025.6l.556.317c.652-.21 1.373-.24 2.079-.45");
}

.fctahwg2u {
  d: path("M10.075 14.48a1.61 1.61 0 1 0 0-3.218a1.61 1.61 0 0 0 0 3.218");
}

.ft5dv1b6b {
  fill: none;
}

.fxt5p0b8w {
  stop-color: var(--svg-color--8052c3, #8052C3);
  stop-opacity: 0;
}

.g_ulzrbqz {
  stop-color: var(--svg-color--ffffc0, #FFFFC0);
  stop-opacity: 0;
}

.g1fw3-bff {
  stop-color: var(--svg-color--f4c099, #F4C099);
  stop-opacity: 0;
}

.g6dgamb9p {
  stop-color: var(--svg-color--8654d1, #8654D1);
}

.g6mu4o3fz {
  stop-color: var(--svg-color--fee2a9, #FEE2A9);
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.gjbrx7i8b {
  stop-color: var(--svg-color--ebce91, #EBCE91);
}

.gl3wl_9gz {
  stop-color: var(--svg-color--ff7e7a, #FF7E7A);
  stop-opacity: 0;
}

.gm_5gldko {
  cx: 26.551px;
  cy: 7.804px;
  r: 1.671px;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
}

.gof7ehbkx {
  stop-color: var(--svg-color--a2889f, #A2889F);
  stop-opacity: 0;
}

.gvh2bspmv {
  stop-color: var(--svg-color--d39b88, #D39B88);
}

.h_j9u0wvt {
  stop-color: var(--svg-color--e6e6e6, #E6E6E6);
}

.h064k9b1n {
  d: path("M3.609 28.893c0-5.916 4.854-10.711 10.842-10.711s10.842 4.795 10.842 10.71v.464H3.609z");
}

.h4i3jv0ko {
  stop-color: var(--svg-color--ffdfb2, #FFDFB2);
}

.hcuenbefp {
  stop-color: var(--svg-color--c7897d, #C7897D);
  stop-opacity: 0;
}

.hi5yi9bqv {
  stop-color: var(--svg-color--daa88f, #DAA88F);
  stop-opacity: 0;
}

.him6rrbhz {
  stop-color: var(--svg-color--fffabe, #FFFABE);
  stop-opacity: 0;
}

.hnlppfbil {
  stop-color: var(--svg-color--9860d3, #9860D3);
  stop-opacity: 0;
}

.hvrv4iryz {
  stop-color: var(--svg-color--d8a29e, #D8A29E);
}

.hxuphr-8h {
  stop-color: var(--svg-color--cf987b, #CF987B);
}

.hy0z0nf6k {
  stop-color: var(--svg-color--a4888c, #A4888C);
  stop-opacity: 0;
}

.i-r212mzs {
  stop-color: var(--svg-color--ecaf9b, #ECAF9B);
}

.i3g5qu-9r {
  stop-color: var(--svg-color--b97783, #B97783);
  stop-opacity: 0;
}

.i7ikbtc_p {
  stop-color: var(--svg-color--b16c78, #B16C78);
}

.i7q3c4b_a {
  d: path("M9.673 11.608h.013l-.01-.265l-.01-.306c.02-.949.573-1.316.81-1.439q.024-.008.05-.02l.052-.02a2.3 2.3 0 0 0 1.19-1.235l.081-.194a.264.264 0 0 1 .462-.05A3.86 3.86 0 0 0 15.5 9.75h3.22c.18 0 1.081.088 1.135 1.333l-.119 3.073c-.123 2.802-2.311 4.684-4.983 4.684s-4.86-1.882-4.983-4.684z");
}

.i8pojfbqt {
  d: path("M13.392 12.585c0-.289-.235-.481-.298-.54l-.288.28l.177.361z");
}

.ip_ig3ymd {
  fill: var(--svg-color--efb696, #EFB696);
  d: path("m14.378 12.51l-.531 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.531-1.7c-.114-.377-.646-.377-.765 0");
}

.irzp_cb7o {
  stop-color: var(--svg-color--e3ab91, #E3AB91);
}

.iwql9tbwr {
  stop-color: var(--svg-color--8752d9, #8752D9);
}

.ix3rj1bpb {
  fill: var(--svg-color--9f6836, #9F6836);
  d: path("m11.363 11.093l-.004.003a.268.268 0 0 1-.276-.46l.002-.001l.002-.002l.01-.005a2 2 0 0 1 .148-.077a3 3 0 0 1 .41-.162c.34-.108.816-.2 1.329-.11a.268.268 0 0 1-.094.529a2.3 2.3 0 0 0-1.072.092a3 3 0 0 0-.455.193");
}

.iz4jcxg0j {
  stop-color: var(--svg-color--f0c6a3, #F0C6A3);
  stop-opacity: 0;
}

.j1_ihyvvo {
  stop-color: var(--svg-color--ffdfb2, #FFDFB2);
  stop-opacity: 0;
}

.j80tr6o9y {
  stop-color: var(--svg-color--c7b1b5, #C7B1B5);
}

.j8hkuac-d {
  stop-color: var(--svg-color--ffc89e, #FFC89E);
}

.jaxt-o31p {
  stop-color: var(--svg-color--ff2d78, #FF2D78);
}

.jd-vaq0no {
  stop-color: var(--svg-color--93768e, #93768E);
}

.jd8suhxpk {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M15.903 12.302c.265-.467.669-.835 1.537-.835c.38 0 .747.105 1.073.368c.269.217.233.495.025.6l-.556.317c-.652-.21-1.373-.24-2.08-.45");
}

.je8i96bea {
  stop-color: var(--svg-color--845b99, #845B99);
  stop-opacity: 0;
}

.jhmvwwj-n {
  d: path("M19.588 13.945a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.jjkt6fbmu {
  cx: 12.307px;
  cy: 12.178px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.jk8vytb-s {
  stop-color: var(--svg-color--dabd87, #DABD87);
}

.jrx3i8b1t {
  d: path("m19.686 5.22l5.42 1.537l-.338 1.189l-4.312-1.223a1.15 1.15 0 0 1-.793-1.42z");
}

.jrzb3cb0k {
  stop-color: var(--svg-color--ac7e6a, #AC7E6A);
}

.jt1e3kk0x {
  fill: var(--svg-color--c28178, #C28178);
  d: path("m14.368 12.648l-.683 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.531-1.7c-.114-.376-.493-.376-.613 0");
}

.jt5or2b5w {
  d: path("M17.74 12.572a.84.84 0 0 0-.232-.463l-.26.286l.118.228z");
}

.jzjqx7qlk {
  stop-color: var(--svg-color--ff7e7a, #FF7E7A);
}

.kdig6mnba {
  stop-color: var(--svg-color--fffabe, #FFFABE);
}

.kqfxh5bnm {
  stop-color: var(--svg-color--be7c5a, #BE7C5A);
  stop-opacity: 0;
}

.krvd34mtu {
  stop-color: var(--svg-color--d59566, #D59566);
  stop-opacity: 0;
}

.kt__1405u {
  stop-color: var(--svg-color--ccc, #CCC);
}

.kwdmgfmeb {
  stop-color: var(--svg-color--c08184, #C08184);
  stop-opacity: 0;
}

.l5h2ci_uw {
  stop-color: var(--svg-color--b97577, #B97577);
  stop-opacity: 0;
}

.l6jzqxbsk {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.152 11.525c.653 0 1.204.45 1.354 1.059a.274.274 0 0 1-.267.34h-2.231a.23.23 0 0 1-.228-.271a1.4 1.4 0 0 1 1.371-1.128");
}

.la61skb4q {
  stop-color: var(--svg-color--e3a280, #E3A280);
  stop-opacity: 0;
}

.lapvr59ed {
  stop-color: var(--svg-color--d9b4c8, #D9B4C8);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lwjatlajn {
  stop-color: var(--svg-color--d1987a, #D1987A);
  stop-opacity: 0;
}

.lxc0fmbqt {
  stop-color: var(--svg-color--c0a0b5, #C0A0B5);
  stop-opacity: 0;
}

.lxuiw-btm {
  fill: var(--svg-color--000, #000);
  d: path("M13.088 12.69a.51.51 0 0 0-.512-.512a.51.51 0 0 0-.454.747h.905a.5.5 0 0 0 .06-.236");
}

.m14m72bli {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M14.76 15.783a3 3 0 0 1-1.421-.345c-.14-.073-.292.089-.203.22a1.932 1.932 0 0 0 3.25 0c.088-.136-.063-.293-.204-.22a3 3 0 0 1-1.421.345Z");
}

.m5wv9vbgf {
  stop-color: var(--svg-color--a46ee0, #A46EE0);
}

.m8bo-jb-t {
  stop-color: var(--svg-color--996e9f, #996E9F);
}

.m8gsznlzl {
  cx: 23.731px;
  cy: 7px;
  r: 0.313px;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mih5kfbap {
  stop-color: var(--svg-color--be7c5a, #BE7C5A);
}

.mt3h7fbpd {
  stop-color: var(--svg-color--e3a48e, #E3A48E);
}

.mv8kv7beo {
  stop-color: var(--svg-color--ffffc0, #FFFFC0);
}

.mvuactshi {
  stop-color: var(--svg-color--c49070, #C49070);
  stop-opacity: 0;
}

.n-5yzizlv {
  d: path("M12.576 11.797a.892.892 0 0 0-.86 1.128h1.725a1 1 0 0 0 .032-.236a.9.9 0 0 0-.897-.892");
}

.nhus6q3at {
  stop-color: var(--svg-color--9a6fdb, #9A6FDB);
  stop-opacity: 0;
}

.ni_6htbzm {
  stop-color: var(--svg-color--b71143, #B71143);
}

.nka4--b6e {
  stop-color: var(--svg-color--c48b78, #C48B78);
}

.nl6ccacdu {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M11.87 6.33c.023.242.234 1.156.544 1.709");
}

.nm6odobve {
  d: path("M21.584 29.356h3.709v-.463c0-3.217-1.436-6.103-3.709-8.067z");
}

.nuj2mebaj {
  d: path("M10.094 13.945a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ok0s313ee {
  stop-color: var(--svg-color--8956cf, #8956CF);
}

.p--9xsbqt {
  stop-color: var(--svg-color--d2a180, #D2A180);
}

.p1sg1mumi {
  stop-color: var(--svg-color--ffc3a8, #FFC3A8);
  stop-opacity: 0;
}

.p47-3c-mm {
  stop-color: var(--svg-color--ae81f2, #AE81F2);
}

.p6otu2-6b {
  stop-color: var(--svg-color--ffffbe, #FFFFBE);
}

.p9lsnsm5t {
  stop-color: var(--svg-color--9b8299, #9B8299);
}

.pj-m4ibrz {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.37 11.525c-.654 0-1.205.45-1.355 1.059a.273.273 0 0 0 .267.34h2.232a.23.23 0 0 0 .227-.271a1.4 1.4 0 0 0-1.371-1.128");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.prydr8bcy {
  stop-color: var(--svg-color--b0725a, #B0725A);
  stop-opacity: 0;
}

.q4hm6bcis {
  cx: 12.307px;
  cy: 12.178px;
  rx: 0.39px;
  ry: 0.197px;
}

.q5mih6mme {
  stop-color: var(--svg-color--e5ae90, #E5AE90);
}

.qflnpfbur {
  stop-color: var(--svg-color--f0c6a3, #F0C6A3);
}

.qm9xdibjl {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M16.879 11.986c.064.085-.07.188-.22.301c-.151.113-.264.193-.327.108c-.064-.085.007-.246.158-.359s.326-.135.389-.05");
}

.qmmvvysmp {
  stop-color: var(--svg-color--e1a792, #E1A792);
}

.qvhay2blz {
  d: path("m9.675 11.343l-.01-.306c.02-.949.574-1.316.81-1.439q.024-.008.052-.02l.05-.02a2.3 2.3 0 0 0 1.19-1.235l.082-.194a.264.264 0 0 1 .462-.05A3.86 3.86 0 0 0 15.5 9.75h3.22c.18 0 1.081.088 1.135 1.333l-.119 3.073c-.123 2.802-2.311 4.684-4.983 4.684s-4.86-1.882-4.983-4.684z");
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r_t9aq_-g {
  d: path("M14.986 17.681c.25.01.51.03.77.05c-.26-.02-.51-.04-.77-.05");
}

.r-jog4w_t {
  stop-color: var(--svg-color--c2847a, #C2847A);
}

.r-plgxbvx {
  stop-color: var(--svg-color--845b99, #845B99);
}

.r8ibvzbki {
  stop-color: var(--svg-color--ff9266, #FF9266);
  stop-opacity: 0;
}

.rjxj417_v {
  stop-color: var(--svg-color--f9bfa4, #F9BFA4);
}

.rraw6sbsp {
  stop-color: var(--svg-color--ff9266, #FF9266);
}

.s9uh1ibhz {
  fill: var(--svg-color--d59288, #D59288);
  d: path("M12.639 17.631h3.984v1.383c0 1.1-.892 1.813-1.992 1.813s-1.992-.713-1.992-1.813z");
}

.sbc0_sbjc {
  stop-color: var(--svg-color--b97577, #B97577);
}

.se95iybxr {
  fill: var(--svg-color--88014e, #88014E);
  d: path("M14.76 15.783a3 3 0 0 1-1.421-.345c-.14-.073-.292.089-.203.22a1.932 1.932 0 0 0 3.25 0c.088-.136-.063-.293-.204-.22a3 3 0 0 1-1.421.345");
}

.sncijkqpo {
  stop-color: var(--svg-color--643a7c, #643A7C);
  stop-opacity: 0;
}

.sqmgyf2vi {
  stop-color: var(--svg-color--c49070, #C49070);
}

.srm_r_guo {
  stop-color: var(--svg-color--ff6792, #FF6792);
}

.t6jzi2-1t {
  stop-color: var(--svg-color--b97783, #B97783);
}

.ta36f8b7v {
  stop-color: var(--svg-color--c7897d, #C7897D);
}

.td2-_ccfi {
  stop-color: var(--svg-color--ecaf9b, #ECAF9B);
  stop-opacity: 0;
}

.toezc-l1m {
  stop-color: var(--svg-color--d2a180, #D2A180);
  stop-opacity: 0;
}

.tt1el8-0z {
  fill: var(--svg-color--e5aa8b, #E5AA8B);
  d: path("M19.588 13.945a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.u-2cz8img {
  fill: var(--svg-color--b47a6c, #B47A6C);
  d: path("M10.094 13.945a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.u1r8ksb5m {
  stop-color: var(--svg-color--d8a29e, #D8A29E);
  stop-opacity: 0;
}

.u4cmqnbdb {
  stop-color: var(--svg-color--412558, #412558);
}

.ue-yx0baa {
  stop-color: var(--svg-color--c58e72, #C58E72);
  stop-opacity: 0;
}

.uhe1-9bau {
  stop-color: var(--svg-color--f3ce9e, #F3CE9E);
}

.urkjpbftr {
  stop-color: var(--svg-color--d1987a, #D1987A);
}

.urs_pbb4x {
  stop-color: var(--svg-color--e3a280, #E3A280);
}

.uxe1igbwt {
  cx: 22.902px;
  cy: 9.817px;
  r: 1.117px;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
}

.uy3z2gbbp {
  stop-color: var(--svg-color--ffc59d, #FFC59D);
}

.v-9s4u7ch {
  stop-color: var(--svg-color--cf987b, #CF987B);
  stop-opacity: 0;
}

.v4a1t-bae {
  d: path("m14.378 12.51l-.531 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.531-1.7c-.114-.377-.646-.377-.765 0");
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.v83a3u3_r {
  cx: 26.551px;
  cy: 7.804px;
  r: 1.117px;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
}

.vg12hr_5o {
  d: path("M14.157 5.08c-1.133-.25-2.346.956-2.464 1.375c1.542 3.62 3.91 3.275 6.537 2.983c1.573-.174 1.743.542 1.877.889c-.435-4.057-3.369-4.677-5.95-5.247");
}

.vrnylccvf {
  stop-color: var(--svg-color--dcc893, #DCC893);
}

.vscv03b8g {
  stop-color: var(--svg-color--c7917b, #C7917B);
  stop-opacity: 0;
}

.vzbvt7b3z {
  stop-color: var(--svg-color--a46bd8, #A46BD8);
  stop-opacity: 0;
}

.vztm_v--z {
  d: path("M16.879 11.986c.064.085-.07.188-.22.301c-.151.113-.264.193-.327.108c-.064-.085.007-.246.158-.359s.326-.135.389-.05");
}

.w5_7ycb6b {
  stop-color: var(--svg-color--ff4f4f, #FF4F4F);
}

.w58maet4h {
  stop-color: var(--svg-color--dac493, #DAC493);
  stop-opacity: 0;
}

.wcr1klbjh {
  stop-color: var(--svg-color--e3a48e, #E3A48E);
  stop-opacity: 0;
}

.wj0k-xifb {
  cx: 22.902px;
  cy: 9.817px;
  r: 1.652px;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
}

.wpaw55bnu {
  stroke: var(--svg-color--a57045, #A57045);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M16.7 10.499c.323-.079 1.125-.04 1.66.344");
}

.wy7e69bbh {
  stop-color: var(--svg-color--c8b3b7, #C8B3B7);
  stop-opacity: 0;
}

.wzytc_e9p {
  stop-color: var(--svg-color--f3ce9e, #F3CE9E);
  stop-opacity: 0;
}

.x_nfl_ozw {
  d: path("M12.639 17.631h3.984v1.383c0 1.1-.892 1.813-1.992 1.813s-1.992-.713-1.992-1.813z");
}

.x47l8abks {
  stop-color: var(--svg-color--e9c198, #E9C198);
}

.x7bl4zbkb {
  fill: var(--svg-color--955ece, #955ECE);
  d: path("M7.317 20.827C5.044 22.79 3.61 25.676 3.61 28.893v.463h3.708z");
}

.xjkdvxqyn {
  stop-color: var(--svg-color--c2847a, #C2847A);
  stop-opacity: 0;
}

.xjug-415a {
  stop-color: var(--svg-color--fdc9a8, #FDC9A8);
}

.ybvptdnhb {
  stop-color: var(--svg-color--c58e72, #C58E72);
}

.ybx_6zbxd {
  stop-color: var(--svg-color--b0725a, #B0725A);
}

.yhs2bn2id {
  stop-color: var(--svg-color--f4c099, #F4C099);
}

.yyo16fhfg {
  fill-rule: evenodd;
  d: path("M21.946 14.28c.212-.434.324-.92.324-1.426c0-.467-.096-.906-.269-1.306h.005a3 3 0 0 0-.28-.513l-.003-.003a3.24 3.24 0 0 1-.526-1.77v-.01a3.3 3.3 0 0 0-3.3-3.3a.54.54 0 0 1-.454-.233a3.3 3.3 0 0 0-2.683-1.376a3.3 3.3 0 0 0-2.681 1.376a.56.56 0 0 1-.456.233l-.085.001a3.3 3.3 0 0 0-3.214 3.298v.01a3.24 3.24 0 0 1-.526 1.771l-.002.004a3.3 3.3 0 0 0-.22 3.245a.52.52 0 0 1 0 .455a3.213 3.213 0 0 0 2.894 4.625h8.582a3.213 3.213 0 0 0 3.218-3.218c0-.506-.122-.982-.324-1.407a.51.51 0 0 1 0-.455m-12.26-2.672h-.013l1.2 2.356c.122 2.802 1.216 0 3.888 0s3.836 3.12 3.96.317l1.135-3.197C19.802 9.839 18.9 9.75 18.72 9.75H15.5a3.86 3.86 0 0 1-3.189-1.673a.264.264 0 0 0-.461.051l-.082.194a2.3 2.3 0 0 1-1.19 1.235l-.051.02l-.052.02c-.236.123-.79.49-.81 1.439l.01.306z");
}

.zcr9jykfw {
  stop-color: var(--svg-color--e6bd9f, #E6BD9F);
}

.zduonub6o {
  stop-color: var(--svg-color--a677eb, #A677EB);
}

.zi0lb2bns {
  stop-color: var(--svg-color--ff5185, #FF5185);
  stop-opacity: 0;
}

.zk512ndyg {
  stop-color: var(--svg-color--a4888c, #A4888C);
}

.zl0fwhbas {
  stop-color: var(--svg-color--a28b95, #A28B95);
}

.znwvjy5yx {
  stop-color: var(--svg-color--ff5c88, #FF5C88);
}

.zzstxpr9j {
  stop-color: var(--svg-color--e3ab91, #E3AB91);
  stop-opacity: 0;
}

</style>
