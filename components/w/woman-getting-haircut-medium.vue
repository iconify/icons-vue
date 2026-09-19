<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iNEYfFe)"><path fill="url(#iSCxe7d)" clip-rule="evenodd" class="sb8u_cb-c"/><path fill="url(#iyMuAOe)" clip-rule="evenodd" class="sb8u_cb-c"/><path fill="url(#iI13cve)" clip-rule="evenodd" class="sb8u_cb-c"/><path fill="url(#iAnprtA)" clip-rule="evenodd" class="sb8u_cb-c"/><path fill="url(#iObySlb)" clip-rule="evenodd" class="sb8u_cb-c"/><path fill="url(#iXBrF1b)" clip-rule="evenodd" class="sb8u_cb-c"/><path fill="url(#i9DCblb)" clip-rule="evenodd" class="sb8u_cb-c"/><path fill="url(#iPl9Bbc)" clip-rule="evenodd" class="sb8u_cb-c"/><path fill="url(#ipGIeJc)" clip-rule="evenodd" class="sb8u_cb-c"/><path fill="url(#iv10i7c)" clip-rule="evenodd" class="sb8u_cb-c"/><path fill="url(#ihIQnbc)" clip-rule="evenodd" class="sb8u_cb-c"/><path fill="url(#ieDjf0c)" clip-rule="evenodd" class="sb8u_cb-c"/></g><path fill="url(#iQy85id)" class="b22q-7bjw"/><path fill="url(#iYogjsc)" class="b22q-7bjw"/><path fill="url(#ii6Evlb)" class="b22q-7bjw"/><path fill="url(#iUqujQc)" class="b22q-7bjw"/><path fill="url(#iZh7JXa)" class="b22q-7bjw"/><path fill="url(#ir5Lote)" class="j-nwqd29k"/><path fill="url(#iX0NMod)" class="j-nwqd29k"/><path class="pdl4e_wlg"/><path fill="url(#id6wsEb)" class="c6dc1ujaz"/><path fill="url(#iVwiwCc)" class="c6dc1ujaz"/><path class="fs7u5yb9h"/><path fill="url(#igAIMXt)" class="m_y9adbks"/><path fill="url(#iJUzvxc)" class="m_y9adbks"/><path fill="url(#iZ0cTgb)" class="qb1mpgb2h"/><path fill="url(#iY8e3Ic)" class="in09icbrd"/><g filter="url(#iMMh9Oe)"><path fill="url(#iaI7IGd)" class="sxr8b8bhx"/></g><path fill="url(#iZ0AtJb)" class="sxr8b8bhx"/><g filter="url(#iobnFeb)"><path fill="url(#iNGrClc)" class="rn5p1eb4b"/><path fill="url(#ieKljTb)" class="rn5p1eb4b"/></g><g filter="url(#il6vfCe)"><path class="hays9h1lv"/><path fill="url(#iuBd5db)" class="fe-46tb1u"/></g><g filter="url(#ibBLrZb)"><path class="zmoh4bb7n"/><path fill="url(#iZ8Y4Me)" class="u7-z7qe0s"/></g><g filter="url(#iGyqh4d)"><path fill="url(#i8vvK0d)" class="r7k06-bee"/><path fill="url(#i6RYp1a)" class="r7k06-bee"/><path fill="url(#iwFRgXc)" class="r7k06-bee"/><path fill="url(#iAj453b)" class="r7k06-bee"/><path fill="url(#iDaSBOe)" class="r7k06-bee"/><path fill="url(#iq0H8ve)" class="r7k06-bee"/><path fill="url(#isUL62d)" class="r7k06-bee"/><path fill="url(#iwWXRAh)" class="r7k06-bee"/></g><path fill="url(#ivTeJIc)" class="r7k06-bee"/><g filter="url(#iToutUd)"><path class="wn35j0bvq"/></g><g filter="url(#iaeO1Ne)"><path class="zm5tilb0e"/><path fill="url(#iGA5dBc)" class="nui84rbrp"/><path fill="url(#i6z0txc)" class="nui84rbrp"/><path fill="url(#iSLKPfd)" class="nui84rbrp"/><path fill="url(#ic6Bl9c)" class="nui84rbrp"/></g><g filter="url(#iYDX3Id)"><path stroke="url(#ilyfBLb)" class="sp9tg7b0u"/></g><path class="zfp2kqbxk"/><g filter="url(#iUyyZ8u)"><path class="lyumj-bqa"/></g><g filter="url(#ibRa1ge)"><path class="g6sggccav"/></g><g filter="url(#iV1yfQe)"><path class="r5d-i9g0y"/></g><g filter="url(#idRpTxc)"><path clip-rule="evenodd" class="bk3juebok"/></g><path class="mexp-2e5i"/><path fill="url(#ip8QmWd)" class="c5qscwb6l"/><path class="mk4_bnh3g"/><g filter="url(#iwzUbqe)"><path class="deejs6uyj"/><path fill="url(#iXvzL3d)" class="z1qbvubaz"/></g><g filter="url(#i9DD2Ae)"><path fill="url(#i6Tz9rc)" class="ng17j9ywq"/></g><path class="gvfweeb0w"/><path fill="url(#i1GQQvb)" class="ke-ph1--a"/><path class="c593ivydz"/><g filter="url(#i2797vv)"><path fill="url(#iH86Evc)" class="eiopvebmt"/></g><g filter="url(#isUgK4b)"><ellipse transform="rotate(-27.914 12.162 11.843)" class="ppfs6ii1l"/><ellipse fill="url(#imq5efc)" transform="rotate(-27.914 12.162 11.843)" class="b4odpzbcu"/></g><g filter="url(#iQL4jCq)"><path class="dith_xbip"/></g><g filter="url(#itoLUDe)"><path class="k2rr3mblh"/></g><g filter="url(#i7uEpZc)"><path class="n66_mcjdj"/><path fill="url(#i1xyfTH)" class="ww_88wb7j"/><path fill="url(#iJ69DMc)" class="ww_88wb7j"/></g><g filter="url(#ixkm4NX)"><path class="bib33-nlp"/><path fill="url(#imiEpNc)" class="t8b2byv9f"/><path fill="url(#imYqj1m)" class="t8b2byv9f"/></g><g filter="url(#i14CHFb)"><path stroke="url(#iQxyXhc)" class="noqu7fdcl"/></g><g filter="url(#iW2xwHm)"><path class="w8t5h0vvk"/></g><path fill="url(#iy5gMbb)" class="ealjxpbhd"/><path fill="url(#iWslGwx)" class="ealjxpbhd"/><path fill="url(#iYsMNpc)" class="cbf3-4bhz"/><path fill="url(#iL47qOe)" class="cbf3-4bhz"/><path fill="url(#icrVmkc)" class="t_c3bh8on"/><path fill="url(#i8xxymd)" class="t_c3bh8on"/><g filter="url(#iabcvsc)"><circle fill="url(#iDo8ZDb)" class="e8khdrxrg"/><circle fill="url(#i35dV2c)" class="e8khdrxrg"/><circle fill="url(#i7pAHce)" class="e8khdrxrg"/></g><g filter="url(#iFPb1jb)"><path fill="url(#iVTNZXc)" clip-rule="evenodd" class="bx16ajbrf"/></g><path fill="url(#iGHIt0d)" clip-rule="evenodd" class="bx16ajbrf"/><g filter="url(#i3x6Pee)"><path fill="url(#iLYXHke)" clip-rule="evenodd" class="ocgldqnbf"/></g><g filter="url(#iVJbcNb)"><circle stroke="url(#iM7AgZc)" class="xozvox-1j"/></g><g filter="url(#iNvCnpE)"><circle stroke="url(#ivl9uEd)" class="pvw7n5bfi"/></g><g filter="url(#igerwid)"><circle stroke="url(#iyIrzmd)" class="hfhsvsplb"/></g><g filter="url(#iw9nEhc)"><circle stroke="url(#iDE7V2I)" class="uc57l4x9x"/></g><defs><radialGradient id="iyMuAOe" cx="0" cy="0" r="1" gradientTransform="matrix(-.60337 4.55908 -5.69522 -.75373 14.313 15.036)" gradientUnits="userSpaceOnUse"><stop offset=".591" class="w9gpkna4y"/><stop offset="1" class="xvq3mubqy"/></radialGradient><radialGradient id="iI13cve" cx="0" cy="0" r="1" gradientTransform="matrix(-2.88301 1.94432 -2.5547 -3.78806 11.498 15.305)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="u3fmvdnwh"/><stop offset="1" class="ysga7wb0w"/></radialGradient><radialGradient id="iAnprtA" cx="0" cy="0" r="1" gradientTransform="rotate(127.405 1.734 8.793)scale(2.15225 1.65263)" gradientUnits="userSpaceOnUse"><stop offset=".334" class="jo-m975mj"/><stop offset="1" class="ecm2ecc2d"/></radialGradient><radialGradient id="iObySlb" cx="0" cy="0" r="1" gradientTransform="rotate(121.43 2.104 8.231)scale(2.47506 1.74346)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="ksj-40n4x"/><stop offset="1" class="qkj18_koj"/></radialGradient><radialGradient id="iXBrF1b" cx="0" cy="0" r="1" gradientTransform="rotate(62.272 1.843 11.422)scale(2.95399 4.10059)" gradientUnits="userSpaceOnUse"><stop class="bk_mrebvc"/><stop offset="1" class="o57gz703y"/></radialGradient><radialGradient id="i9DCblb" cx="0" cy="0" r="1" gradientTransform="rotate(134.998 8.867 7.513)scale(2.03849 2.84876)" gradientUnits="userSpaceOnUse"><stop class="g2m4aac5s"/><stop offset="1" class="tulkzacvs"/></radialGradient><radialGradient id="iPl9Bbc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.84366 .53637 -1.11855 -3.84482 22.125 11.684)" gradientUnits="userSpaceOnUse"><stop class="ii82yjbfl"/><stop offset="1" class="tobrp8lrd"/></radialGradient><radialGradient id="ipGIeJc" cx="0" cy="0" r="1" gradientTransform="rotate(165.963 9.83 8.876)scale(2.90248 3.69733)" gradientUnits="userSpaceOnUse"><stop class="gto3tpbjl"/><stop offset="1" class="k8ni71bqd"/></radialGradient><radialGradient id="iv10i7c" cx="0" cy="0" r="1" gradientTransform="matrix(-.90444 -2.65026 2.0962 -.71536 19.348 9.25)" gradientUnits="userSpaceOnUse"><stop class="j6tbtfb5n"/><stop offset="1" class="u7ezkxzae"/></radialGradient><radialGradient id="ihIQnbc" cx="0" cy="0" r="1" gradientTransform="matrix(1.50392 .15775 -.2556 2.43678 8.474 11.648)" gradientUnits="userSpaceOnUse"><stop class="r4e237cot"/><stop offset="1" class="ktpt3tb_i"/></radialGradient><radialGradient id="ieDjf0c" cx="0" cy="0" r="1" gradientTransform="rotate(-102.748 14.257 -2.383)scale(3.79787 1.37073)" gradientUnits="userSpaceOnUse"><stop class="fyy3crxae"/><stop offset="1" class="x7431zb1g"/></radialGradient><radialGradient id="iQy85id" cx="0" cy="0" r="1" gradientTransform="rotate(154.071 8.355 13.734)scale(15.0662 17.3462)" gradientUnits="userSpaceOnUse"><stop class="m5wv9vbgf"/><stop offset="1" class="ok0s313ee"/></radialGradient><radialGradient id="iYogjsc" cx="0" cy="0" r="1" gradientTransform="matrix(-7.90627 -10.81244 15.55864 -11.37678 17.476 29.526)" gradientUnits="userSpaceOnUse"><stop offset=".895" class="je8i96bea"/><stop offset="1" class="r-plgxbvx"/></radialGradient><radialGradient id="ii6Evlb" cx="0" cy="0" r="1" gradientTransform="rotate(168.453 5.78 9.783)scale(5.93256 1.70339)" gradientUnits="userSpaceOnUse"><stop class="u4cmqnbdb"/><stop offset="1" class="sncijkqpo"/></radialGradient><radialGradient id="iUqujQc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.93377 0 0 -19.371 21.553 29.02)" gradientUnits="userSpaceOnUse"><stop offset=".133" class="p47-3c-mm"/><stop offset="1" class="vzbvt7b3z"/></radialGradient><radialGradient id="iZh7JXa" cx="0" cy="0" r="1" gradientTransform="matrix(1.5 0 0 23.8126 7.432 29.02)" gradientUnits="userSpaceOnUse"><stop class="g6dgamb9p"/><stop offset="1" class="hnlppfbil"/></radialGradient><radialGradient id="ir5Lote" cx="0" cy="0" r="1" gradientTransform="matrix(3.25185 0 0 9.13279 21.584 28.242)" gradientUnits="userSpaceOnUse"><stop offset=".576" class="zduonub6o"/><stop offset="1" class="cuty5mbvc"/></radialGradient><radialGradient id="iX0NMod" cx="0" cy="0" r="1" gradientTransform="matrix(.87006 0 0 11.9715 21.584 29.02)" gradientUnits="userSpaceOnUse"><stop class="iwql9tbwr"/><stop offset="1" class="cpuxbvbrp"/></radialGradient><radialGradient id="id6wsEb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.70862 0 0 -8.85437 7.317 29.02)" gradientUnits="userSpaceOnUse"><stop offset=".614" class="fxt5p0b8w"/><stop offset="1" class="f4vmrjbib"/></radialGradient><radialGradient id="iVwiwCc" cx="0" cy="0" r="1" gradientTransform="matrix(-.8463 0 0 -10.457 7.317 29.02)" gradientUnits="userSpaceOnUse"><stop offset=".111" class="f3tc_zfmh"/><stop offset="1" class="nhus6q3at"/></radialGradient><radialGradient id="igAIMXt" cx="0" cy="0" r="1" gradientTransform="matrix(.5625 1.75 -3.03541 .97567 13.708 18.311)" gradientUnits="userSpaceOnUse"><stop offset=".243" class="dp3aelbwj"/><stop offset="1" class="pfhatbb0f"/></radialGradient><radialGradient id="iJUzvxc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.9674 2.28562 -.98994 -1.28524 17.598 19.182)" gradientUnits="userSpaceOnUse"><stop offset=".285" class="w9ofuxbnl"/><stop offset="1" class="el6nl6bas"/></radialGradient><radialGradient id="iZ0AtJb" cx="0" cy="0" r="1" gradientTransform="matrix(-.6537 -1.20346 1.36368 -.74073 9.537 14.144)" gradientUnits="userSpaceOnUse"><stop class="wlzou1bho"/><stop offset="1" class="muarw1mje"/></radialGradient><radialGradient id="iNGrClc" cx="0" cy="0" r="1" gradientTransform="matrix(2.48905 -1.13139 1.38138 3.03902 18.655 12.975)" gradientUnits="userSpaceOnUse"><stop offset=".64" class="xqzyuky4n"/><stop offset="1" class="yiz6fvgdb"/></radialGradient><radialGradient id="ieKljTb" cx="0" cy="0" r="1" gradientTransform="matrix(1.20681 0 0 .5196 19.56 10.83)" gradientUnits="userSpaceOnUse"><stop class="v4cuahbfk"/><stop offset="1" class="ame5l9u0o"/></radialGradient><radialGradient id="iuBd5db" cx="0" cy="0" r="1" gradientTransform="matrix(1.50989 -.11231 .0878 1.18032 19.007 12.648)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="j_jb06m8v"/><stop offset="1" class="t9v208shd"/></radialGradient><radialGradient id="iZ8Y4Me" cx="0" cy="0" r="1" gradientTransform="rotate(180 5.007 6.268)scale(1.05596)" gradientUnits="userSpaceOnUse"><stop offset=".722" class="w5re42dqy"/><stop offset="1" class="w4wkyodwa"/></radialGradient><radialGradient id="i8vvK0d" cx="0" cy="0" r="1" gradientTransform="rotate(155.244 7.42 7.917)scale(7.16175 9.58588)" gradientUnits="userSpaceOnUse"><stop class="ox3481l0h"/><stop offset="1" class="l65mx1yct"/></radialGradient><radialGradient id="i6RYp1a" cx="0" cy="0" r="1" gradientTransform="rotate(156.249 6.942 8.17)scale(2.38203 1.65881)" gradientUnits="userSpaceOnUse"><stop class="vw42v6b3v"/><stop offset="1" class="v5m4qhb2r"/></radialGradient><radialGradient id="iwFRgXc" cx="0" cy="0" r="1" gradientTransform="matrix(1.28915 -3.92836 4.98436 1.6357 12.454 18.506)" gradientUnits="userSpaceOnUse"><stop class="hl813wbpa"/><stop offset="1" class="a21bmlbcx"/></radialGradient><radialGradient id="iAj453b" cx="0" cy="0" r="1" gradientTransform="matrix(-1.28468 7.37319 -9.2164 -1.60583 15.639 11.582)" gradientUnits="userSpaceOnUse"><stop offset=".637" class="fa0q4x0wh"/><stop offset=".955" class="vfgk4hb_x"/></radialGradient><radialGradient id="iDaSBOe" cx="0" cy="0" r="1" gradientTransform="rotate(168.897 7.546 7.663)scale(7.03739 12.1162)" gradientUnits="userSpaceOnUse"><stop offset=".795" class="qh0bdqbav"/><stop offset="1" class="dt7ct4boy"/></radialGradient><radialGradient id="iq0H8ve" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.15077 1.41231 0 16.917 11.58)" gradientUnits="userSpaceOnUse"><stop class="azt-9rbtm"/><stop offset="1" class="ci16jsbol"/></radialGradient><radialGradient id="isUL62d" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.31251 1.50423 0 12.54 11.351)" gradientUnits="userSpaceOnUse"><stop class="zemyxxbjg"/><stop offset="1" class="k1zv-ubmt"/></radialGradient><radialGradient id="iwWXRAh" cx="0" cy="0" r="1" gradientTransform="matrix(-.87016 3.22674 -2.58193 -.69627 15.999 9.264)" gradientUnits="userSpaceOnUse"><stop class="aotu-xwil"/><stop offset="1" class="izc7dk1pl"/></radialGradient><radialGradient id="ivTeJIc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.28528 0 0 -6.44557 19.711 13.067)" gradientUnits="userSpaceOnUse"><stop class="fyxppic9g"/><stop offset="1" class="kq5b787yl"/></radialGradient><radialGradient id="iGA5dBc" cx="0" cy="0" r="1" gradientTransform="matrix(-.45554 -2.04401 .62995 -.1404 15.4 13.794)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="ab1vgh_ru"/><stop offset="1" class="f80hfjhpj"/></radialGradient><radialGradient id="ic6Bl9c" cx="0" cy="0" r="1" gradientTransform="matrix(-.7794 0 0 -.2179 15.16 14.005)" gradientUnits="userSpaceOnUse"><stop class="hjp773b9j"/><stop offset="1" class="wh0vrhbzi"/></radialGradient><radialGradient id="ip8QmWd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.29049 0 16.798 11.938)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iXvzL3d" cx="0" cy="0" r="1" gradientTransform="matrix(-.23192 -.29886 .41145 -.3193 16.57 12.023)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i1GQQvb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.2905 0 12.433 11.938)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="imq5efc" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 12.058 .1)scale(.49412 .59395)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i1xyfTH" cx="0" cy="0" r="1" gradientTransform="matrix(1.26205 -2.75541 1.4096 .64564 8.958 9.817)" gradientUnits="userSpaceOnUse"><stop class="gaydocc3b"/><stop offset="1" class="o5ryhdc_j"/></radialGradient><radialGradient id="iJ69DMc" cx="0" cy="0" r="1" gradientTransform="matrix(1.14952 -1.97524 1.06043 .61714 10.665 8.837)" gradientUnits="userSpaceOnUse"><stop class="bkfqk3fbn"/><stop offset="1" class="hrqlkdbpd"/></radialGradient><radialGradient id="imiEpNc" cx="0" cy="0" r="1" gradientTransform="rotate(115.684 6.814 7.5)scale(4.8729 7.96691)" gradientUnits="userSpaceOnUse"><stop offset=".639" class="ukea7pdhy"/><stop offset="1" class="wuqjd3b5z"/></radialGradient><radialGradient id="imYqj1m" cx="0" cy="0" r="1" gradientTransform="matrix(-.21033 1.3672 -2.94145 -.45252 14.826 4.98)" gradientUnits="userSpaceOnUse"><stop class="y3gk9pbvh"/><stop offset="1" class="j2p90_-bc"/><stop offset="1" class="ru9fl6bjc"/></radialGradient><radialGradient id="iy5gMbb" cx="0" cy="0" r="1" gradientTransform="matrix(-6.21875 1.75 -2.17983 -7.74618 23.463 5.868)" gradientUnits="userSpaceOnUse"><stop class="i_6d9dbmt"/><stop offset=".636" class="j6m48nwsx"/><stop offset=".843" class="dlahuhcsb"/></radialGradient><radialGradient id="iWslGwx" cx="0" cy="0" r="1" gradientTransform="matrix(.16455 1.30288 -.72715 .09184 23.277 4.214)" gradientUnits="userSpaceOnUse"><stop offset=".181" class="jwlik3bmw"/><stop offset="1" class="z9ctlobsv"/></radialGradient><radialGradient id="iDo8ZDb" cx="0" cy="0" r="1" gradientTransform="rotate(141.18 10.796 7.497)scale(.43619)" gradientUnits="userSpaceOnUse"><stop offset=".168" class="cz-qsgbfy"/><stop offset="1" class="j80tr6o9y"/></radialGradient><radialGradient id="i35dV2c" cx="0" cy="0" r="1" gradientTransform="matrix(.19922 -.48438 1.17186 .48198 23.586 7.011)" gradientUnits="userSpaceOnUse"><stop offset=".147" class="m8bo-jb-t"/><stop offset="1" class="wy7e69bbh"/></radialGradient><radialGradient id="i7pAHce" cx="0" cy="0" r="1" gradientTransform="matrix(.4375 .04684 -.05916 .55254 23.361 6.574)" gradientUnits="userSpaceOnUse"><stop offset=".181" class="zk512ndyg"/><stop offset="1" class="hy0z0nf6k"/></radialGradient><radialGradient id="iVTNZXc" cx="0" cy="0" r="1" gradientTransform="matrix(2.20247 -1.61719 2.56784 3.49718 21.389 9.76)" gradientUnits="userSpaceOnUse"><stop offset=".205" class="cnux6p8xn"/><stop offset="1" class="jaxt-o31p"/></radialGradient><radialGradient id="iLYXHke" cx="0" cy="0" r="1" gradientTransform="matrix(2.53124 -1.40627 1.98705 3.57664 24.535 7.937)" gradientUnits="userSpaceOnUse"><stop offset=".205" class="cnux6p8xn"/><stop offset="1" class="jaxt-o31p"/></radialGradient><filter id="iNEYfFe" width="15.268" height="15.768" x="7.107" y="3.257" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.262745 0 0 0 0 0.133333 0 0 0 0 0.184314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_31"/></filter><filter id="iMMh9Oe" width="3.368" height="3.218" x="8.321" y="10.926" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.607843 0 0 0 0 0.458824 0 0 0 0 0.403922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_31"/></filter><filter id="iobnFeb" width="3.218" height="3.468" x="17.834" y="10.676" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.556863 0 0 0 0 0.34902 0 0 0 0 0.384314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_31"/></filter><filter id="il6vfCe" width="3.148" height="3.148" x="17.869" y="10.961" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_31" stdDeviation=".25"/></filter><filter id="ibBLrZb" width="2.848" height="2.848" x="8.525" y="11.111" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_31" stdDeviation=".175"/></filter><filter id="iGyqh4d" width="10.191" height="11.127" x="9.52" y="7.629" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.407843 0 0 0 0 0.223529 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_31"/></filter><filter id="iToutUd" width="2.877" height="3.682" x="13.014" y="11.53" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_31" stdDeviation=".25"/></filter><filter id="iaeO1Ne" width="2.077" height="2.882" x="13.577" y="11.792" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_31" stdDeviation=".05"/></filter><filter id="iYDX3Id" width="3.702" height="1.526" x="12.764" y="14.884" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_31" stdDeviation=".05"/></filter><filter id="iUyyZ8u" width="3.001" height="1.285" x="15.558" y="11.131" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.117647 0 0 0 0 0.0705882 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_31"/></filter><filter id="ibRa1ge" width="3.001" height="1.285" x="10.672" y="11.131" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0862745 0 0 0 0 0.054902 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_31"/></filter><filter id="iV1yfQe" width="2.453" height="1.091" x="10.807" y="9.707" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.211765 0 0 0 0 0.121569 0 0 0 0 0.12549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_31"/></filter><filter id="idRpTxc" width="2.453" height="1.091" x="16.225" y="9.707" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.211765 0 0 0 0 0.121569 0 0 0 0 0.12549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_31"/></filter><filter id="iwzUbqe" width=".787" height=".696" x="16.064" y="11.499" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_31" stdDeviation=".05"/></filter><filter id="i9DD2Ae" width=".891" height=".913" x="16.903" y="11.573" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_31" stdDeviation=".1"/></filter><filter id="i2797vv" width=".986" height="1.04" x="12.46" y="11.51" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_31" stdDeviation=".1"/></filter><filter id="isUgK4b" width=".913" height=".705" x="11.706" y="11.49" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_31" stdDeviation=".05"/></filter><filter id="iQL4jCq" width="2.261" height=".978" x="16.255" y="9.829" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_31" stdDeviation=".1"/></filter><filter id="itoLUDe" width="2.261" height=".978" x="10.803" y="9.829" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_31" stdDeviation=".1"/></filter><filter id="i7uEpZc" width="4.312" height="4.613" x="8.261" y="5.594" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.345098 0 0 0 0 0.286275 0 0 0 0 0.27451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_31"/><feGaussianBlur result="effect2_foregroundBlur_4002_31" stdDeviation=".2"/></filter><filter id="ixkm4NX" width="8.767" height="5.782" x="11.445" y="4.459" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".2"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.415686 0 0 0 0 0.317647 0 0 0 0 0.305882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_31"/><feGaussianBlur result="effect2_foregroundBlur_4002_31" stdDeviation=".125"/></filter><filter id="i14CHFb" width="1.145" height="2.31" x="11.424" y="5.693" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_31" stdDeviation=".1"/></filter><filter id="iW2xwHm" width="6.427" height="3.372" x="14.034" y="6.502" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_31" stdDeviation=".375"/></filter><filter id="iabcvsc" width=".726" height=".726" x="23.418" y="6.251" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.52549 0 0 0 0 0.388235 0 0 0 0 0.501961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_31"/></filter><filter id="iFPb1jb" width="3.834" height="4.387" x="20.96" y="7.053" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.945098 0 0 0 0 0.45098 0 0 0 0 0.333333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_31"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.282353 0 0 0 0 0.435294 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_31" result="effect2_innerShadow_4002_31"/></filter><filter id="i3x6Pee" width="4.283" height="3.734" x="24.158" y="5.576" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.882353 0 0 0 0 0.203922 0 0 0 0 0.435294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_31"/></filter><filter id="iVJbcNb" width="3.843" height="3.843" x="24.629" y="5.546" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_31" stdDeviation=".1"/></filter><filter id="iNvCnpE" width="2.734" height="2.734" x="25.183" y="6.101" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_31" stdDeviation=".1"/></filter><filter id="igerwid" width="2.734" height="2.734" x="21.535" y="8.114" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_31" stdDeviation=".1"/></filter><filter id="iw9nEhc" width="3.805" height="3.805" x="21" y="7.579" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_31" stdDeviation=".1"/></filter><linearGradient id="iSCxe7d" x1="19.309" x2="13.174" y1="5.583" y2="16.344" gradientUnits="userSpaceOnUse"><stop class="ap760fb9g"/><stop offset="1" class="w1etxcbdz"/></linearGradient><linearGradient id="iZ0cTgb" x1="7.446" x2="21.822" y1="17.375" y2="17.375" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="iY8e3Ic" x1="7.446" x2="21.822" y1="17.345" y2="17.345" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="iaI7IGd" x1="8.321" x2="10.178" y1="12.623" y2="12.623" gradientUnits="userSpaceOnUse"><stop class="cg1k0hirj"/><stop offset="1" class="u6m78ac0i"/></linearGradient><linearGradient id="i6z0txc" x1="13.677" x2="14.616" y1="13.867" y2="13.867" gradientUnits="userSpaceOnUse"><stop class="hm31m3bmo"/><stop offset="1" class="vh12xwf7a"/></linearGradient><linearGradient id="iSLKPfd" x1="14.616" x2="14.616" y1="14.574" y2="13.947" gradientUnits="userSpaceOnUse"><stop class="us3ue9b4r"/><stop offset="1" class="hxr-reb3g"/></linearGradient><linearGradient id="ilyfBLb" x1="13.551" x2="14.012" y1="16.076" y2="15.363" gradientUnits="userSpaceOnUse"><stop class="ssfga94sp"/><stop offset=".663" class="t-wcrfbaw"/></linearGradient><linearGradient id="i6Tz9rc" x1="17.576" x2="17.262" y1="11.992" y2="12.185" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iH86Evc" x1="13.177" x2="12.864" y1="11.992" y2="12.186" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iQxyXhc" x1="11.507" x2="11.997" y1="5.583" y2="6.848" gradientUnits="userSpaceOnUse"><stop class="olrv_cchi"/><stop offset="1" class="lwhsndh-i"/></linearGradient><linearGradient id="iYsMNpc" x1="24.941" x2="23.75" y1="4.713" y2="4.369" gradientUnits="userSpaceOnUse"><stop class="p9lsnsm5t"/><stop offset="1" class="lapvr59ed"/></linearGradient><linearGradient id="iL47qOe" x1="23.793" x2="23.867" y1="6.207" y2="5.917" gradientUnits="userSpaceOnUse"><stop offset=".16" class="zl0fwhbas"/><stop offset="1" class="lxc0fmbqt"/></linearGradient><linearGradient id="icrVmkc" x1="22.879" x2="23.144" y1="7.062" y2="5.765" gradientUnits="userSpaceOnUse"><stop class="p9lsnsm5t"/><stop offset="1" class="lapvr59ed"/></linearGradient><linearGradient id="i8xxymd" x1="24.29" x2="24.092" y1="7.144" y2="7.088" gradientUnits="userSpaceOnUse"><stop class="jd-vaq0no"/><stop offset="1" class="gof7ehbkx"/></linearGradient><linearGradient id="iGHIt0d" x1="23.629" x2="23.57" y1="7.234" y2="7.46" gradientUnits="userSpaceOnUse"><stop offset=".209" class="ni_6htbzm"/><stop offset="1" class="ajm38_jxm"/></linearGradient><linearGradient id="iM7AgZc" x1="24.879" x2="28.069" y1="7.836" y2="6.364" gradientUnits="userSpaceOnUse"><stop offset=".616" class="w5_7ycb6b"/><stop offset=".9" class="srm_r_guo"/></linearGradient><linearGradient id="ivl9uEd" x1="25.433" x2="27.566" y1="7.714" y2="6.73" gradientUnits="userSpaceOnUse"><stop offset=".247" class="jzjqx7qlk"/><stop offset=".669" class="gl3wl_9gz"/></linearGradient><linearGradient id="iyIrzmd" x1="21.785" x2="23.917" y1="9.728" y2="8.744" gradientUnits="userSpaceOnUse"><stop offset=".247" class="rraw6sbsp"/><stop offset=".669" class="r8ibvzbki"/></linearGradient><linearGradient id="iDE7V2I" x1="24.554" x2="22.902" y1="8.941" y2="9.482" gradientUnits="userSpaceOnUse"><stop class="znwvjy5yx"/><stop offset="1" class="zi0lb2bns"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-getting-haircut-medium" /></template>
<style>
.a21bmlbcx {
  stop-color: var(--svg-color--945a73, #945A73);
  stop-opacity: 0;
}

.ab1vgh_ru {
  stop-color: var(--svg-color--cda38b, #CDA38B);
}

.ajm38_jxm {
  stop-color: var(--svg-color--ff3178, #FF3178);
  stop-opacity: 0;
}

.ame5l9u0o {
  stop-color: var(--svg-color--906d53, #906D53);
  stop-opacity: 0;
}

.aotu-xwil {
  stop-color: var(--svg-color--ab8179, #AB8179);
}

.ap760fb9g {
  stop-color: var(--svg-color--6d524e, #6D524E);
}

.azt-9rbtm {
  stop-color: var(--svg-color--ae7b75, #AE7B75);
}

.b22q-7bjw {
  d: path("M3.609 28.557c0-5.915 4.854-10.71 10.842-10.71s10.842 4.795 10.842 10.71v.463H3.609z");
}

.b4odpzbcu {
  cx: 12.162px;
  cy: 11.843px;
  rx: 0.39px;
  ry: 0.197px;
}

.bib33-nlp {
  fill: var(--svg-color--553836, #553836);
  d: path("M14.012 4.745c-1.132-.25-2.15.88-2.267 1.299c1.052 3.545 3.713 3.35 6.34 3.059c1.573-.175 1.743.542 1.878.888c0-3.933-3.345-4.671-5.922-5.24z");
}

.bk_mrebvc {
  stop-color: var(--svg-color--554543, #554543);
}

.bk3juebok {
  fill: var(--svg-color--432a28, #432A28);
  fill-rule: evenodd;
  d: path("m18.347 10.3l-.138.23za.268.268 0 0 1-.275.46l-.005-.002a2 2 0 0 0-.113-.059a3 3 0 0 0-.343-.135a2.3 2.3 0 0 0-1.071-.092a.268.268 0 0 1-.094-.528c.513-.09.989 0 1.329.11a3.3 3.3 0 0 1 .558.238l.01.005z");
}

.bkfqk3fbn {
  stop-color: var(--svg-color--4b2839, #4B2839);
}

.bx16ajbrf {
  fill-rule: evenodd;
  d: path("M23.005 7.107a.1.1 0 0 0-.124.068l-.104.357a.21.21 0 0 1-.174.148a1.842 1.842 0 1 0 1.514.433a.21.21 0 0 1-.068-.22l.102-.348a.1.1 0 0 0-.069-.124zm.741 2.39a.844.844 0 1 1-1.688 0a.844.844 0 0 1 1.688 0");
}

.c593ivydz {
  fill: var(--svg-color--000, #000);
  d: path("M12.943 12.354a.51.51 0 0 0-.512-.511a.51.51 0 0 0-.454.746h.905a.5.5 0 0 0 .06-.235");
}

.c5qscwb6l {
  d: path("M16.8 11.461a.893.893 0 0 1 .86 1.128h-1.724a.896.896 0 0 1 .864-1.128");
}

.c6dc1ujaz {
  d: path("M7.317 20.49c-2.273 1.964-3.708 4.85-3.708 8.067v.463h3.708z");
}

.cbf3-4bhz {
  d: path("M24.334 2.308L22.946 7.14l1.187.345l1.071-3.73a1.15 1.15 0 0 0-.784-1.421z");
}

.cg1k0hirj {
  stop-color: var(--svg-color--8d645f, #8D645F);
}

.ci16jsbol {
  stop-color: var(--svg-color--ae7b75, #AE7B75);
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

.cuty5mbvc {
  stop-color: var(--svg-color--9775dd, #9775DD);
}

.cz-qsgbfy {
  stop-color: var(--svg-color--ebdbe4, #EBDBE4);
}

.deejs6uyj {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M16.734 11.65c.064.085-.07.189-.22.302c-.151.113-.264.192-.327.107c-.064-.085.007-.245.158-.358s.325-.136.389-.05");
}

.dith_xbip {
  stroke: var(--svg-color--5b4545, #5B4545);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M16.555 10.163c.323-.079 1.125-.04 1.66.344");
}

.dlahuhcsb {
  stop-color: var(--svg-color--392426, #392426);
  stop-opacity: 0;
}

.dp3aelbwj {
  stop-color: var(--svg-color--875361, #875361);
}

.dt7ct4boy {
  stop-color: var(--svg-color--9a7267, #9A7267);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e8khdrxrg {
  cx: 23.731px;
  cy: 6.664px;
  r: 0.313px;
}

.ealjxpbhd {
  d: path("M20.71 6.314c-1.262.462-2.101.414-2.648.171L16.89 9.337c1.29.055 3.8-.332 5.563-2.383c.843-.981.996-1.91.656-2.586c-.061-.121-.183-.172-.27-.148c-.086.023-.16.108-.187.207c-.162.566-.538 1.372-1.942 1.887");
}

.ecm2ecc2d {
  stop-color: var(--svg-color--27141e, #27141E);
  stop-opacity: 0;
}

.eiopvebmt {
  d: path("M13.247 12.249c0-.288-.235-.48-.298-.539l-.288.28l.177.36z");
}

.el6nl6bas {
  stop-color: var(--svg-color--bc8d82, #BC8D82);
  stop-opacity: 0;
}

.f3tc_zfmh {
  stop-color: var(--svg-color--9a6fdb, #9A6FDB);
}

.f4vmrjbib {
  stop-color: var(--svg-color--8267b6, #8267B6);
}

.f80hfjhpj {
  stop-color: var(--svg-color--cda38b, #CDA38B);
  stop-opacity: 0;
}

.fa0q4x0wh {
  stop-color: var(--svg-color--8d5e67, #8D5E67);
  stop-opacity: 0;
}

.fe-46tb1u {
  d: path("M19.443 13.61a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.fs7u5yb9h {
  fill: var(--svg-color--a46f73, #A46F73);
  d: path("M12.639 17.295h3.984v1.383c0 1.1-.892 1.813-1.992 1.813s-1.992-.712-1.992-1.813z");
}

.ft5dv1b6b {
  fill: none;
}

.fxt5p0b8w {
  stop-color: var(--svg-color--8052c3, #8052C3);
  stop-opacity: 0;
}

.fyxppic9g {
  stop-color: var(--svg-color--c0967a, #C0967A);
}

.fyy3crxae {
  stop-color: var(--svg-color--3e2125, #3E2125);
}

.g2m4aac5s {
  stop-color: var(--svg-color--6e5350, #6E5350);
}

.g6dgamb9p {
  stop-color: var(--svg-color--8654d1, #8654D1);
}

.g6sggccav {
  fill: var(--svg-color--27232a, #27232A);
  d: path("M13.474 11.966c-.266-.466-.67-.835-1.538-.835c-.38 0-.747.105-1.072.369c-.27.217-.233.495-.025.599l.556.317c.652-.21 1.373-.239 2.079-.45");
}

.gaydocc3b {
  stop-color: var(--svg-color--5c4643, #5C4643);
}

.gl3wl_9gz {
  stop-color: var(--svg-color--ff7e7a, #FF7E7A);
  stop-opacity: 0;
}

.gof7ehbkx {
  stop-color: var(--svg-color--a2889f, #A2889F);
  stop-opacity: 0;
}

.gto3tpbjl {
  stop-color: var(--svg-color--564544, #564544);
}

.gvfweeb0w {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.225 11.19c-.654 0-1.205.45-1.355 1.058a.274.274 0 0 0 .267.341h2.231a.23.23 0 0 0 .228-.272a1.4 1.4 0 0 0-1.371-1.127");
}

.h_j9u0wvt {
  stop-color: var(--svg-color--e6e6e6, #E6E6E6);
}

.hays9h1lv {
  fill: var(--svg-color--b38574, #B38574);
  d: path("M19.443 13.61a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.hfhsvsplb {
  cx: 22.902px;
  cy: 9.482px;
  r: 1.117px;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
}

.hjp773b9j {
  stop-color: var(--svg-color--ca9f8c, #CA9F8C);
}

.hl813wbpa {
  stop-color: var(--svg-color--945a73, #945A73);
}

.hm31m3bmo {
  stop-color: var(--svg-color--875f54, #875F54);
}

.hnlppfbil {
  stop-color: var(--svg-color--9860d3, #9860D3);
  stop-opacity: 0;
}

.hrqlkdbpd {
  stop-color: var(--svg-color--4b2839, #4B2839);
  stop-opacity: 0;
}

.hxr-reb3g {
  stop-color: var(--svg-color--995c76, #995C76);
  stop-opacity: 0;
}

.hy0z0nf6k {
  stop-color: var(--svg-color--a4888c, #A4888C);
  stop-opacity: 0;
}

.i_6d9dbmt {
  stop-color: var(--svg-color--452436, #452436);
}

.ii82yjbfl {
  stop-color: var(--svg-color--604947, #604947);
}

.in09icbrd {
  d: path("M14.656 17.346h-.04c.1 0 .19 0 .29.01c-.08-.01-.17-.01-.25-.01");
}

.iwql9tbwr {
  stop-color: var(--svg-color--8752d9, #8752D9);
}

.izc7dk1pl {
  stop-color: var(--svg-color--ab8179, #AB8179);
  stop-opacity: 0;
}

.j_jb06m8v {
  stop-color: var(--svg-color--a26d62, #A26D62);
  stop-opacity: 0;
}

.j-nwqd29k {
  d: path("M21.584 29.02h3.709v-.463c0-3.217-1.436-6.103-3.709-8.066z");
}

.j2p90_-bc {
  stop-color: var(--svg-color--4c4749, #4C4749);
  stop-opacity: 0;
}

.j6m48nwsx {
  stop-color: var(--svg-color--452834, #452834);
}

.j6tbtfb5n {
  stop-color: var(--svg-color--5f4846, #5F4846);
}

.j80tr6o9y {
  stop-color: var(--svg-color--c7b1b5, #C7B1B5);
}

.jaxt-o31p {
  stop-color: var(--svg-color--ff2d78, #FF2D78);
}

.jd-vaq0no {
  stop-color: var(--svg-color--93768e, #93768E);
}

.je8i96bea {
  stop-color: var(--svg-color--845b99, #845B99);
  stop-opacity: 0;
}

.jo-m975mj {
  stop-color: var(--svg-color--27141e, #27141E);
}

.jwlik3bmw {
  stop-color: var(--svg-color--53363d, #53363D);
}

.jzjqx7qlk {
  stop-color: var(--svg-color--ff7e7a, #FF7E7A);
}

.k1zv-ubmt {
  stop-color: var(--svg-color--8f5c65, #8F5C65);
  stop-opacity: 0;
}

.k2rr3mblh {
  stroke: var(--svg-color--5b4545, #5B4545);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M12.764 10.163c-.322-.079-1.124-.04-1.66.344");
}

.k8ni71bqd {
  stop-color: var(--svg-color--564544, #564544);
  stop-opacity: 0;
}

.ke-ph1--a {
  d: path("M12.431 11.461a.893.893 0 0 0-.86 1.128h1.725a1 1 0 0 0 .032-.235a.9.9 0 0 0-.897-.893");
}

.kq5b787yl {
  stop-color: var(--svg-color--c0967a, #C0967A);
  stop-opacity: 0;
}

.ksj-40n4x {
  stop-color: var(--svg-color--230c14, #230C14);
}

.kt__1405u {
  stop-color: var(--svg-color--ccc, #CCC);
}

.ktpt3tb_i {
  stop-color: var(--svg-color--56413d, #56413D);
  stop-opacity: 0;
}

.l65mx1yct {
  stop-color: var(--svg-color--946568, #946568);
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.lapvr59ed {
  stop-color: var(--svg-color--d9b4c8, #D9B4C8);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lwhsndh-i {
  stop-color: var(--svg-color--452531, #452531);
}

.lxc0fmbqt {
  stop-color: var(--svg-color--c0a0b5, #C0A0B5);
  stop-opacity: 0;
}

.lyumj-bqa {
  fill: var(--svg-color--2f2c32, #2F2C32);
  d: path("M15.758 11.966c.265-.466.669-.835 1.537-.835c.38 0 .747.105 1.073.369c.269.217.233.495.024.599l-.556.317c-.651-.21-1.372-.239-2.078-.45");
}

.m_y9adbks {
  d: path("M12.639 17.295h3.984v1.383c0 1.1-.892 1.813-1.992 1.813s-1.992-.712-1.992-1.813z");
}

.m5wv9vbgf {
  stop-color: var(--svg-color--a46ee0, #A46EE0);
}

.m8bo-jb-t {
  stop-color: var(--svg-color--996e9f, #996E9F);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mexp-2e5i {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.007 11.19c.653 0 1.204.45 1.354 1.058a.274.274 0 0 1-.267.341h-2.232a.23.23 0 0 1-.227-.272a1.4 1.4 0 0 1 1.371-1.127");
}

.mk4_bnh3g {
  fill: var(--svg-color--000, #000);
  d: path("M16.289 12.354c0-.284.227-.511.51-.511a.51.51 0 0 1 .455.746h-.905a.46.46 0 0 1-.06-.235");
}

.muarw1mje {
  stop-color: var(--svg-color--814e62, #814E62);
  stop-opacity: 0;
}

.n66_mcjdj {
  fill: var(--svg-color--49302e, #49302E);
  d: path("M9.547 6.547c.565-.6 1.636-.6 2.13-.51l.396 1.29c-.253-.04-.295-.002-.485.183c-.138 1.093-1.376 1.757-2.886 2.197c-.149-1.492.108-2.38.845-3.16");
}

.ng17j9ywq {
  d: path("M17.595 12.236a.84.84 0 0 0-.232-.463l-.26.286l.118.228z");
}

.nhus6q3at {
  stop-color: var(--svg-color--9a6fdb, #9A6FDB);
  stop-opacity: 0;
}

.ni_6htbzm {
  stop-color: var(--svg-color--b71143, #B71143);
}

.noqu7fdcl {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M11.724 5.993c.024.243.235 1.157.545 1.71");
}

.nui84rbrp {
  d: path("m14.233 12.174l-.531 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.531-1.7c-.114-.376-.646-.376-.765 0");
}

.o57gz703y {
  stop-color: var(--svg-color--554543, #554543);
  stop-opacity: 0;
}

.o5ryhdc_j {
  stop-color: var(--svg-color--5c4643, #5C4643);
  stop-opacity: 0;
}

.ocgldqnbf {
  fill-rule: evenodd;
  d: path("M24.45 6.32a.1.1 0 0 1 .122-.071l.36.095a.22.22 0 0 0 .216-.072a1.842 1.842 0 1 1-.412 1.52a.22.22 0 0 0-.152-.172l-.352-.093a.1.1 0 0 1-.07-.123zm1.663 1.87a.844.844 0 1 0 .872-1.444a.844.844 0 0 0-.872 1.444");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ok0s313ee {
  stop-color: var(--svg-color--8956cf, #8956CF);
}

.olrv_cchi {
  stop-color: var(--svg-color--361f1f, #361F1F);
}

.ox3481l0h {
  stop-color: var(--svg-color--c79980, #C79980);
}

.p47-3c-mm {
  stop-color: var(--svg-color--ae81f2, #AE81F2);
}

.p9lsnsm5t {
  stop-color: var(--svg-color--9b8299, #9B8299);
}

.pdl4e_wlg {
  fill: var(--svg-color--955ece, #955ECE);
  d: path("M7.317 20.49c-2.273 1.964-3.708 4.85-3.708 8.067v.463h3.708z");
}

.pfhatbb0f {
  stop-color: var(--svg-color--905a5b, #905A5B);
  stop-opacity: 0;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.ppfs6ii1l {
  cx: 12.162px;
  cy: 11.843px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.pvw7n5bfi {
  cx: 26.551px;
  cy: 7.468px;
  r: 1.117px;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
}

.qb1mpgb2h {
  d: path("M14.986 17.346c.25.01.51.03.77.05c-.26-.02-.51-.04-.77-.05");
}

.qh0bdqbav {
  stop-color: var(--svg-color--9a7267, #9A7267);
  stop-opacity: 0;
}

.qkj18_koj {
  stop-color: var(--svg-color--230c14, #230C14);
  stop-opacity: 0;
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r-plgxbvx {
  stop-color: var(--svg-color--845b99, #845B99);
}

.r4e237cot {
  stop-color: var(--svg-color--56413d, #56413D);
}

.r5d-i9g0y {
  fill: var(--svg-color--432a28, #432A28);
  d: path("m11.218 10.758l-.004.002a.268.268 0 0 1-.276-.46h.002l.002-.003l.01-.005l.032-.018l.116-.059a3 3 0 0 1 .41-.162c.34-.108.816-.2 1.329-.109a.268.268 0 1 1-.094.528a2.3 2.3 0 0 0-1.071.092a3 3 0 0 0-.434.181z");
}

.r7k06-bee {
  d: path("M9.528 11.273h.013l-.01-.265l-.01-.306c.02-.95.573-1.317.81-1.44q.023-.007.05-.02l.052-.02a2.3 2.3 0 0 0 1.19-1.235l.081-.193a.264.264 0 0 1 .462-.051a3.86 3.86 0 0 0 3.19 1.673h3.22c.18 0 1.081.087 1.135 1.332l-.119 3.073c-.123 2.803-2.312 4.685-4.983 4.685s-4.86-1.882-4.983-4.685z");
}

.r8ibvzbki {
  stop-color: var(--svg-color--ff9266, #FF9266);
  stop-opacity: 0;
}

.rn5p1eb4b {
  d: path("M19.443 14.144a1.61 1.61 0 1 0 0-3.218a1.61 1.61 0 0 0 0 3.218");
}

.rraw6sbsp {
  stop-color: var(--svg-color--ff9266, #FF9266);
}

.ru9fl6bjc {
  stop-color: var(--svg-color--634945, #634945);
  stop-opacity: 0;
}

.sb8u_cb-c {
  fill-rule: evenodd;
  d: path("M21.8 13.945c.213-.435.325-.92.325-1.427c0-.467-.096-.905-.269-1.305h.005a3 3 0 0 0-.28-.513l-.003-.003a3.24 3.24 0 0 1-.526-1.771v-.01a3.3 3.3 0 0 0-3.3-3.3a.54.54 0 0 1-.455-.232a3.3 3.3 0 0 0-2.681-1.377a3.3 3.3 0 0 0-2.682 1.377a.56.56 0 0 1-.456.232l-.085.001A3.3 3.3 0 0 0 8.18 8.916v.01a3.24 3.24 0 0 1-.526 1.77l-.002.004a3.3 3.3 0 0 0-.22 3.245c.07.142.07.314 0 .456a3.213 3.213 0 0 0 2.894 4.625h8.582a3.213 3.213 0 0 0 3.218-3.219c0-.506-.122-.981-.324-1.406a.51.51 0 0 1 0-.456M9.54 11.273h-.012l1.2 2.355c.122 2.803 1.216 0 3.888 0s3.836 3.12 3.96.317l1.135-3.197c-.054-1.245-.956-1.332-1.136-1.332h-3.22a3.86 3.86 0 0 1-3.19-1.673a.264.264 0 0 0-.46.05l-.083.194a2.3 2.3 0 0 1-1.292 1.276c-.236.122-.79.49-.81 1.438l.01.306z");
}

.sncijkqpo {
  stop-color: var(--svg-color--643a7c, #643A7C);
  stop-opacity: 0;
}

.sp9tg7b0u {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M14.616 15.447c-.521 0-1.01-.125-1.422-.345c-.14-.073-.292.09-.203.22a1.932 1.932 0 0 0 3.25 0c.088-.136-.063-.293-.204-.22a3 3 0 0 1-1.421.345Z");
}

.srm_r_guo {
  stop-color: var(--svg-color--ff6792, #FF6792);
}

.ssfga94sp {
  stop-color: var(--svg-color--a87d7b, #A87D7B);
}

.sxr8b8bhx {
  d: path("M9.93 14.144a1.61 1.61 0 1 0 0-3.218a1.61 1.61 0 0 0 0 3.218");
}

.t_c3bh8on {
  d: path("m19.686 4.885l5.42 1.536l-.338 1.189l-4.312-1.223a1.15 1.15 0 0 1-.793-1.42z");
}

.t-wcrfbaw {
  stop-color: var(--svg-color--a87d7b, #A87D7B);
  stop-opacity: 0;
}

.t8b2byv9f {
  d: path("M14.012 4.745c-1.132-.25-2.15.88-2.267 1.299c1.052 3.545 3.713 3.35 6.34 3.059c1.573-.175 1.743.542 1.878.888c0-3.933-3.345-4.671-5.922-5.24z");
}

.t9v208shd {
  stop-color: var(--svg-color--a26d62, #A26D62);
}

.tobrp8lrd {
  stop-color: var(--svg-color--604947, #604947);
  stop-opacity: 0;
}

.tulkzacvs {
  stop-color: var(--svg-color--6e5350, #6E5350);
  stop-opacity: 0;
}

.u3fmvdnwh {
  stop-color: var(--svg-color--25131c, #25131C);
}

.u4cmqnbdb {
  stop-color: var(--svg-color--412558, #412558);
}

.u6m78ac0i {
  stop-color: var(--svg-color--604138, #604138);
}

.u7-z7qe0s {
  d: path("M9.95 13.61a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.u7ezkxzae {
  stop-color: var(--svg-color--5f4846, #5F4846);
  stop-opacity: 0;
}

.uc57l4x9x {
  cx: 22.902px;
  cy: 9.482px;
  r: 1.652px;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
}

.ukea7pdhy {
  stop-color: var(--svg-color--442534, #442534);
  stop-opacity: 0;
}

.us3ue9b4r {
  stop-color: var(--svg-color--995c76, #995C76);
}

.v4cuahbfk {
  stop-color: var(--svg-color--906d53, #906D53);
}

.v5m4qhb2r {
  stop-color: var(--svg-color--c4967a, #C4967A);
  stop-opacity: 0;
}

.vfgk4hb_x {
  stop-color: var(--svg-color--764c51, #764C51);
}

.vh12xwf7a {
  stop-color: var(--svg-color--875f54, #875F54);
  stop-opacity: 0;
}

.vw42v6b3v {
  stop-color: var(--svg-color--c4967a, #C4967A);
}

.vzbvt7b3z {
  stop-color: var(--svg-color--a46bd8, #A46BD8);
  stop-opacity: 0;
}

.w1etxcbdz {
  stop-color: var(--svg-color--2c1c24, #2C1C24);
}

.w4wkyodwa {
  stop-color: var(--svg-color--6c4640, #6C4640);
}

.w5_7ycb6b {
  stop-color: var(--svg-color--ff4f4f, #FF4F4F);
}

.w5re42dqy {
  stop-color: var(--svg-color--6c4640, #6C4640);
  stop-opacity: 0;
}

.w8t5h0vvk {
  fill: var(--svg-color--664a4a, #664A4A);
  d: path("m17.022 8.354l-1.425.263a.688.688 0 1 1-.125-1.365h2.34c1.385 0 1.843 1.395 1.899 1.872a3.15 3.15 0 0 0-2.69-.77");
}

.w9gpkna4y {
  stop-color: var(--svg-color--261326, #261326);
}

.w9ofuxbnl {
  stop-color: var(--svg-color--bc8d82, #BC8D82);
}

.wh0vrhbzi {
  stop-color: var(--svg-color--ca9f8c, #CA9F8C);
  stop-opacity: 0;
}

.wlzou1bho {
  stop-color: var(--svg-color--814e62, #814E62);
}

.wn35j0bvq {
  fill: var(--svg-color--88555f, #88555F);
  d: path("m14.223 12.313l-.684 1.7a.54.54 0 0 0 .521.7h.786c.37 0 .63-.356.521-.7l-.532-1.7c-.113-.377-.493-.377-.612 0");
}

.wuqjd3b5z {
  stop-color: var(--svg-color--442534, #442534);
}

.ww_88wb7j {
  d: path("M9.547 6.547c.565-.6 1.636-.6 2.13-.51l.396 1.29c-.253-.04-.295-.002-.485.183c-.138 1.093-1.376 1.757-2.886 2.197c-.149-1.492.108-2.38.845-3.16");
}

.wy7e69bbh {
  stop-color: var(--svg-color--c8b3b7, #C8B3B7);
  stop-opacity: 0;
}

.x7431zb1g {
  stop-color: var(--svg-color--3e2125, #3E2125);
  stop-opacity: 0;
}

.xozvox-1j {
  cx: 26.551px;
  cy: 7.468px;
  r: 1.671px;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
}

.xqzyuky4n {
  stop-color: var(--svg-color--b28279, #B28279);
}

.xvq3mubqy {
  stop-color: var(--svg-color--261326, #261326);
  stop-opacity: 0;
}

.y3gk9pbvh {
  stop-color: var(--svg-color--634945, #634945);
}

.yiz6fvgdb {
  stop-color: var(--svg-color--cca58b, #CCA58B);
}

.ysga7wb0w {
  stop-color: var(--svg-color--25131c, #25131C);
  stop-opacity: 0;
}

.z1qbvubaz {
  d: path("M16.734 11.65c.064.085-.07.189-.22.302c-.151.113-.264.192-.327.107c-.064-.085.007-.245.158-.358s.325-.136.389-.05");
}

.z9ctlobsv {
  stop-color: var(--svg-color--53363d, #53363D);
  stop-opacity: 0;
}

.zduonub6o {
  stop-color: var(--svg-color--a677eb, #A677EB);
}

.zemyxxbjg {
  stop-color: var(--svg-color--8f5c65, #8F5C65);
}

.zfp2kqbxk {
  fill: var(--svg-color--88024e, #88024E);
  d: path("M14.616 15.447c-.521 0-1.01-.125-1.422-.345c-.14-.073-.292.09-.203.22a1.932 1.932 0 0 0 3.25 0c.088-.136-.063-.293-.204-.22a3 3 0 0 1-1.421.345");
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

.zm5tilb0e {
  fill: var(--svg-color--b38578, #B38578);
  d: path("m14.233 12.174l-.531 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.531-1.7c-.114-.376-.646-.376-.765 0");
}

.zmoh4bb7n {
  fill: var(--svg-color--7e555a, #7E555A);
  d: path("M9.95 13.61a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.znwvjy5yx {
  stop-color: var(--svg-color--ff5c88, #FF5C88);
}

</style>
