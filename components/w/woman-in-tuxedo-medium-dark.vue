<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><path id="iBlrRVb" class="njpbn0o1i"/></defs><g class="ft5dv1b6b"><g filter="url(#iqR2Ynd)"><path fill="url(#i3JkmBA)" clip-rule="evenodd" class="gkm_etb7v"/><path fill="url(#ikNzs8b)" clip-rule="evenodd" class="gkm_etb7v"/><path fill="url(#iO0LWce)" clip-rule="evenodd" class="gkm_etb7v"/><path fill="url(#i0SdSGd)" clip-rule="evenodd" class="gkm_etb7v"/><path fill="url(#iygPUEd)" clip-rule="evenodd" class="gkm_etb7v"/><path fill="url(#iJz278c)" clip-rule="evenodd" class="gkm_etb7v"/><path fill="url(#ijUMgmd)" clip-rule="evenodd" class="gkm_etb7v"/><path fill="url(#ihhovVb)" clip-rule="evenodd" class="gkm_etb7v"/><path fill="url(#iDpz9ld)" clip-rule="evenodd" class="gkm_etb7v"/><path fill="url(#iRGFPFY)" clip-rule="evenodd" class="gkm_etb7v"/><path fill="url(#iK6TXyd)" clip-rule="evenodd" class="gkm_etb7v"/></g><path fill="url(#iOTSjsd)" class="iwijhb8cc"/><path fill="url(#iVt7Kmd)" class="iwijhb8cc"/><path fill="url(#ibiLcyb)" class="iwijhb8cc"/><path fill="url(#iuyr1tn)" class="iwijhb8cc"/><path fill="url(#iwTkvTT)" class="iwijhb8cc"/><path fill="url(#iGY3pLe)" class="b_rzieh8m"/><path fill="url(#iRAxaXb)" class="b_rzieh8m"/><g filter="url(#ivLeJie)"><path fill="url(#iHafYHb)" class="uoh3u9bsv"/><path fill="url(#irRAuOe)" class="uoh3u9bsv"/></g><path fill="url(#iZDfxad)" class="wo1twgd7z"/><g filter="url(#iwiAVHd)"><path fill="url(#i0qUINb)" class="j_4_fe6ih"/><path fill="url(#iDSTCFe)" class="j_4_fe6ih"/></g><g filter="url(#ij2RA0c)"><path clip-rule="evenodd" class="ts-_p6bqx"/></g><path fill="url(#iQD9ace)" class="e2l8hyb-w"/><path fill="url(#i8s0Kbb)" class="e2l8hyb-w"/><path fill="url(#izOTSJe)" class="e2l8hyb-w"/><path fill="url(#ig0Fqhd)" class="e2l8hyb-w"/><path fill="url(#ifwpvfb)" class="hzwfg4bat"/><path fill="url(#isw1JEe)" class="hzwfg4bat"/><path fill="url(#iwDR1wV)" class="hzwfg4bat"/><path fill="url(#i1L7Mpd)" class="hzwfg4bat"/><g filter="url(#iM88w2d)"><path fill="url(#i6XAUBd)" class="lmsmt5bzm"/></g><g filter="url(#igNzdHd)"><path fill="url(#iLOUAXd)" class="poffvcb8y"/></g><path fill="url(#iHd26xe)" class="poffvcb8y"/><path fill="url(#iZCJqXd)" class="poffvcb8y"/><path fill="url(#ixvOk5d)" class="poffvcb8y"/><g filter="url(#i0ywR4h)"><path class="x4qpxczyt"/></g><g filter="url(#i6Gfheb)"><circle class="mvlg1lb-a"/></g><g filter="url(#iVMfhyb)"><circle class="ysjacm3zw"/></g><g filter="url(#ifY3ppP)"><circle fill="url(#iGv238b)" class="yzzmy4bmy"/></g><g filter="url(#ixX2ntc)"><circle fill="url(#iUdTZPc)" class="wpqym9bwz"/></g><rect fill="url(#iV8za6b)" class="epgmjx2er"/><rect fill="url(#iXy75wd)" class="epgmjx2er"/><rect fill="url(#i0eWqBe)" class="epgmjx2er"/><rect fill="url(#ihW6PAc)" class="epgmjx2er"/><g filter="url(#iJMNDjq)"><path fill="url(#i7lfzIe)" class="w5fsnhbly"/></g><path fill="url(#i8CmoBe)" class="w5fsnhbly"/><g filter="url(#iEYCWHc)"><path class="bvbk5ac3i"/><path fill="url(#i2zegdh)" class="zuim55bho"/><path fill="url(#iXYh5ub)" class="zuim55bho"/><path fill="url(#iOZTY0b)" class="zuim55bho"/></g><g filter="url(#im8jTCA)"><circle fill="url(#icPlPbd)" class="gtaq5zpgk"/><circle fill="url(#iAsT4et)" class="gtaq5zpgk"/></g><path fill="url(#if4vDlY)" class="lmkyvq38o"/><path fill="url(#iiIRDCc)" class="dc_z0_bxw"/><g filter="url(#iu4ObBb)"><path fill="url(#ib9i9tc)" class="pk3shsb1m"/></g><g filter="url(#iD0eBue)"><path fill="url(#iOML4Dd)" class="hti5s2xzi"/><path fill="url(#i6QxmMd)" class="hti5s2xzi"/></g><g filter="url(#iZjPucb)"><path class="rr035z7jd"/><path fill="url(#iCcqRwt)" class="r79fvmu0k"/></g><g filter="url(#i7eqE3b)"><path class="cc_fr1_1s"/><path fill="url(#iCgZMMc)" class="ktkcunhjc"/></g><g filter="url(#i21avLc)"><path fill="url(#iLuiDwe)" class="tpv10tb7c"/><path fill="url(#iXzC7Nd)" class="tpv10tb7c"/><path fill="url(#iJsKPZc)" class="tpv10tb7c"/><path fill="url(#ignzExc)" class="tpv10tb7c"/><path fill="url(#i0KFnTb)" class="tpv10tb7c"/><path fill="url(#iGsicwd)" class="tpv10tb7c"/><path fill="url(#iFdXOHc)" class="tpv10tb7c"/><path fill="url(#iXdRdne)" class="tpv10tb7c"/></g><path fill="url(#i4domqd)" class="tpv10tb7c"/><path fill="url(#it0zi9c)" class="tpv10tb7c"/><path fill="url(#ilKR0dH)" class="tpv10tb7c"/><g filter="url(#iL8WHVw)"><path class="gbz-ilb0d"/></g><g filter="url(#iW5JLSb)"><path class="i-vd1ians"/><path fill="url(#i87Ennc)" class="k7kmfp2ol"/><path fill="url(#iw76p3K)" class="k7kmfp2ol"/><path fill="url(#ihEYYnc)" class="k7kmfp2ol"/><path fill="url(#i0lCYAR)" class="k7kmfp2ol"/></g><g filter="url(#iua2Oxd)"><use href="#iBlrRVb"/><path stroke="url(#ihA1M1b)" class="xadf9bcdw"/></g><use href="#iBlrRVb"/><g filter="url(#iqbMqMc)"><path class="r2nms2bvi"/></g><g filter="url(#iD9EyWb)"><path class="onomtin3h"/></g><g filter="url(#ipOjRDe)"><path class="dfvy54bwo"/></g><g filter="url(#iyAqtad)"><path clip-rule="evenodd" class="c1wwrfzpb"/></g><path class="jp78e8bxj"/><path fill="url(#iuGVWGd)" class="x3uhsrvov"/><path class="rso9j8bhr"/><g filter="url(#iosf0Bb)"><path class="eytkjzmjs"/><path fill="url(#ibk3XZc)" class="h7rekkb5e"/></g><g filter="url(#iPK7h0c)"><path fill="url(#iKE2acd)" class="q5or-sbzv"/></g><path class="t2_ncgbfi"/><path fill="url(#igHlA7C)" class="jc16_9ped"/><path class="yo2rlxb6h"/><g filter="url(#i8cmuyo)"><path fill="url(#iKDvJOc)" class="sldn9dbpe"/></g><g filter="url(#iJfiAvb)"><ellipse transform="rotate(-27.914 13.559 9.862)" class="s6_65gbjh"/><ellipse fill="url(#i9MDc0m)" transform="rotate(-27.914 13.559 9.862)" class="qg_liac-i"/></g><g filter="url(#i2Vsdre)"><path class="oacz0_bgo"/></g><g filter="url(#i0OoY5b)"><path class="at-3e3s_x"/></g><g filter="url(#if5nIDc)"><path class="uv-z0kbfv"/><path fill="url(#iAx25gd)" class="sm2uv51xo"/></g><g filter="url(#iFxy7Nr)"><path class="qgsks8bel"/><path fill="url(#iz0rKte)" class="qt-8hdcxt"/><path fill="url(#iMadc1b)" class="qt-8hdcxt"/></g><g filter="url(#i83iq1b)"><path stroke="url(#izrclwb)" class="qn9z0pbfl"/></g><g filter="url(#iVDFdRb)"><path class="ci7dr71ae"/></g><defs><radialGradient id="ikNzs8b" cx="0" cy="0" r="1" gradientTransform="matrix(-.60337 4.55908 -5.69522 -.75373 15.711 13.055)" gradientUnits="userSpaceOnUse"><stop offset=".591" class="xdn388byj"/><stop offset="1" class="qwp4ni-tf"/></radialGradient><radialGradient id="iO0LWce" cx="0" cy="0" r="1" gradientTransform="matrix(-2.88301 1.94432 -2.5547 -3.78806 12.895 13.324)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="bl7uysvvb"/><stop offset="1" class="r_v2kebuk"/></radialGradient><radialGradient id="i0SdSGd" cx="0" cy="0" r="1" gradientTransform="rotate(127.405 2.922 8.148)scale(2.15225 1.65263)" gradientUnits="userSpaceOnUse"><stop offset=".334" class="l0xg-rbdf"/><stop offset="1" class="chj8m5e2t"/></radialGradient><radialGradient id="iygPUEd" cx="0" cy="0" r="1" gradientTransform="rotate(121.43 3.357 7.633)scale(2.47506 1.74346)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="kbl3igr5c"/><stop offset="1" class="glo437b-m"/></radialGradient><radialGradient id="iJz278c" cx="0" cy="0" r="1" gradientTransform="rotate(62.272 4.18 11.588)scale(2.95399 4.10059)" gradientUnits="userSpaceOnUse"><stop class="paonnib9g"/><stop offset="1" class="g0r7omboq"/></radialGradient><radialGradient id="ijUMgmd" cx="0" cy="0" r="1" gradientTransform="rotate(134.998 9.975 6.812)scale(2.03849 2.84876)" gradientUnits="userSpaceOnUse"><stop class="hx66smwtj"/><stop offset="1" class="c9_6uxbfa"/></radialGradient><radialGradient id="ihhovVb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.84366 .53637 -1.11855 -3.84482 23.521 9.704)" gradientUnits="userSpaceOnUse"><stop class="cj4rfmfkx"/><stop offset="1" class="silozpblh"/></radialGradient><radialGradient id="iDpz9ld" cx="0" cy="0" r="1" gradientTransform="rotate(165.963 10.651 7.972)scale(2.90248 3.69733)" gradientUnits="userSpaceOnUse"><stop class="mxnnm4bur"/><stop offset="1" class="jk5udqbyz"/></radialGradient><radialGradient id="iRGFPFY" cx="0" cy="0" r="1" gradientTransform="matrix(-.90444 -2.65026 2.0962 -.71536 20.745 7.27)" gradientUnits="userSpaceOnUse"><stop class="hkormb2xp"/><stop offset="1" class="e-twaac7b"/></radialGradient><radialGradient id="iK6TXyd" cx="0" cy="0" r="1" gradientTransform="matrix(1.50392 .15775 -.2556 2.43678 9.87 9.667)" gradientUnits="userSpaceOnUse"><stop class="lgjudcrkd"/><stop offset="1" class="tr7czpf3k"/></radialGradient><radialGradient id="iOTSjsd" cx="0" cy="0" r="1" gradientTransform="matrix(-10.875 0 0 -9.21464 22.408 25.376)" gradientUnits="userSpaceOnUse"><stop class="rp3tqelhu"/><stop offset="1" class="nwb1x8bnq"/></radialGradient><radialGradient id="iVt7Kmd" cx="0" cy="0" r="1" gradientTransform="rotate(133.011 2.756 10.843)scale(6.32206 7.4475)" gradientUnits="userSpaceOnUse"><stop class="cosmi4y3y"/><stop offset="1" class="fs5qncc9z"/></radialGradient><radialGradient id="ibiLcyb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.5 0 0 -14.0625 23.19 23.286)" gradientUnits="userSpaceOnUse"><stop offset=".143" class="b_mjjkbmw"/><stop offset="1" class="tg6m8fb0a"/></radialGradient><radialGradient id="iGY3pLe" cx="0" cy="0" r="1" gradientTransform="rotate(-91.369 27.271 2.64)scale(11.2456 1.27919)" gradientUnits="userSpaceOnUse"><stop offset=".008" class="uc5leibtb"/><stop offset="1" class="j8ireobfm"/><stop offset="1" class="hj096sb7e"/></radialGradient><radialGradient id="iRAxaXb" cx="0" cy="0" r="1" gradientTransform="matrix(.5755 0 0 15.6193 23.099 28.188)" gradientUnits="userSpaceOnUse"><stop offset=".167" class="n_pmxxxsa"/><stop offset="1" class="a_orf89wt"/></radialGradient><radialGradient id="iHafYHb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -11.9375 4 0 6.69 30.443)" gradientUnits="userSpaceOnUse"><stop class="cm2l5-bra"/><stop offset="1" class="z_d2yzmmm"/></radialGradient><radialGradient id="iZDfxad" cx="0" cy="0" r="1" gradientTransform="matrix(-1.55519 1.9364 -1.64284 -1.31942 8.901 18.6)" gradientUnits="userSpaceOnUse"><stop class="aba3uxblf"/><stop offset="1" class="bbv_pqbfl"/></radialGradient><radialGradient id="i0qUINb" cx="0" cy="0" r="1" gradientTransform="matrix(-.03127 9.1875 -4.7805 -.01627 17.096 22.568)" gradientUnits="userSpaceOnUse"><stop offset=".442" class="geqh5zowk"/><stop offset="1" class="u21vfmbcf"/></radialGradient><radialGradient id="iDSTCFe" cx="0" cy="0" r="1" gradientTransform="rotate(116.36 1.33 13.055)scale(5.4245 1.91221)" gradientUnits="userSpaceOnUse"><stop offset=".116" class="lf_z1-eut"/><stop offset="1" class="safapbcnd"/></radialGradient><radialGradient id="i8s0Kbb" cx="0" cy="0" r="1" gradientTransform="rotate(-148.052 10.537 8.071)scale(1.21384 4.09383)" gradientUnits="userSpaceOnUse"><stop class="ff2asxc8d"/><stop offset="1" class="c5vb29odw"/></radialGradient><radialGradient id="izOTSJe" cx="0" cy="0" r="1" gradientTransform="matrix(.7959 -.2721 .77398 2.26394 13.24 18.358)" gradientUnits="userSpaceOnUse"><stop class="vdt_t3f2x"/><stop offset="1" class="v0ftcskkn"/></radialGradient><radialGradient id="isw1JEe" cx="0" cy="0" r="1" gradientTransform="rotate(16.487 -55.16 68.502)scale(1.44847 6.30545)" gradientUnits="userSpaceOnUse"><stop offset=".616" class="fojlwlb9t"/><stop offset="1" class="cyzx27bkq"/></radialGradient><radialGradient id="iwDR1wV" cx="0" cy="0" r="1" gradientTransform="matrix(-.2731 .4204 -1.76025 -1.14347 17.274 19.237)" gradientUnits="userSpaceOnUse"><stop class="ojp787kql"/><stop offset="1" class="zhh5xs6ht"/></radialGradient><radialGradient id="iLOUAXd" cx="0" cy="0" r="1" gradientTransform="rotate(172.755 6.073 11.886)scale(1.9846 6.9682)" gradientUnits="userSpaceOnUse"><stop offset=".448" class="z58nq_enb"/><stop offset="1" class="v5ndbpbdn"/></radialGradient><radialGradient id="iHd26xe" cx="0" cy="0" r="1" gradientTransform="matrix(-.91837 1.77673 -4.30254 -2.22394 13.135 16.373)" gradientUnits="userSpaceOnUse"><stop class="ubq14mb-s"/><stop offset="1" class="q0kampb0a"/></radialGradient><radialGradient id="iZCJqXd" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.92462 -.4885 0 11.747 16.431)" gradientUnits="userSpaceOnUse"><stop offset=".252" class="ihl9krbbc"/><stop offset="1" class="vjj8ifxqk"/></radialGradient><radialGradient id="ixvOk5d" cx="0" cy="0" r="1" gradientTransform="rotate(86.901 -5.602 15.98)scale(1.69986 .36274)" gradientUnits="userSpaceOnUse"><stop offset=".136" class="jfikb2f0k"/><stop offset="1" class="k5y7j_bmf"/></radialGradient><radialGradient id="iGv238b" cx="0" cy="0" r="1" gradientTransform="rotate(135.285 2.862 16.074)scale(.5552)" gradientUnits="userSpaceOnUse"><stop offset=".118" class="t1trakjku"/><stop offset=".765" class="voa0z2bgu"/></radialGradient><radialGradient id="iUdTZPc" cx="0" cy="0" r="1" gradientTransform="rotate(135.285 3.48 14.57)scale(.5552)" gradientUnits="userSpaceOnUse"><stop offset=".118" class="t1trakjku"/><stop offset=".765" class="voa0z2bgu"/></radialGradient><radialGradient id="iXy75wd" cx="0" cy="0" r="1" gradientTransform="matrix(.75 -.54688 1.51805 2.0819 14.294 18.047)" gradientUnits="userSpaceOnUse"><stop offset=".21" class="ruy03dwsw"/><stop offset="1" class="g6612mg3v"/></radialGradient><radialGradient id="i0eWqBe" cx="0" cy="0" r="1" gradientTransform="rotate(165.804 7.091 9.02)scale(3.58723 1.18238)" gradientUnits="userSpaceOnUse"><stop class="c4u_fkb7m"/><stop offset="1" class="r5cfbubaw"/></radialGradient><radialGradient id="ihW6PAc" cx="0" cy="0" r="1" gradientTransform="matrix(3.03795 .27873 -.4484 4.8872 15.497 17.266)" gradientUnits="userSpaceOnUse"><stop offset=".657" class="ftzzr1bjs"/><stop offset="1" class="r7p6ehbnk"/></radialGradient><radialGradient id="i7lfzIe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.39331 0 0 -1.18711 18.294 18.79)" gradientUnits="userSpaceOnUse"><stop class="udzp2zp0e"/><stop offset="1" class="mgsb3vbjk"/></radialGradient><radialGradient id="i8CmoBe" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.92504 -.35938 0 18.143 18.165)" gradientUnits="userSpaceOnUse"><stop class="tayze7bgq"/><stop offset="1" class="s41karbfc"/></radialGradient><radialGradient id="iXYh5ub" cx="0" cy="0" r="1" gradientTransform="rotate(-144.958 10.448 6.885)scale(1.79393 .6786)" gradientUnits="userSpaceOnUse"><stop offset=".313" class="i8gd1zbwo"/><stop offset="1" class="fj3b0ib3x"/></radialGradient><radialGradient id="iOZTY0b" cx="0" cy="0" r="1" gradientTransform="matrix(-.73438 0 0 -1.53003 15.424 19.02)" gradientUnits="userSpaceOnUse"><stop class="p5lz4ubjd"/><stop offset="1" class="tyszy7o8n"/></radialGradient><radialGradient id="icPlPbd" cx="0" cy="0" r="1" gradientTransform="rotate(135.285 4.362 12.614)scale(.89786)" gradientUnits="userSpaceOnUse"><stop offset=".118" class="t1trakjku"/><stop offset=".765" class="voa0z2bgu"/></radialGradient><radialGradient id="iAsT4et" cx="0" cy="0" r="1" gradientTransform="matrix(-.5 -1.4336 1.50732 -.5257 16.174 19.38)" gradientUnits="userSpaceOnUse"><stop offset=".741" class="yl8zw5b_j"/><stop offset="1" class="dh4f0mlhm"/></radialGradient><radialGradient id="iOML4Dd" cx="0" cy="0" r="1" gradientTransform="matrix(2.48905 -1.13139 1.38138 3.03902 20.052 10.994)" gradientUnits="userSpaceOnUse"><stop offset=".64" class="olqyf7fmb"/><stop offset=".944" class="hpeo8yzih"/></radialGradient><radialGradient id="i6QxmMd" cx="0" cy="0" r="1" gradientTransform="matrix(1.31577 .7375 -.2085 .37199 21.083 8.874)" gradientUnits="userSpaceOnUse"><stop class="mt9k2qzvi"/><stop offset="1" class="fx1tjiblm"/></radialGradient><radialGradient id="iCcqRwt" cx="0" cy="0" r="1" gradientTransform="matrix(1.50989 -.11231 .0878 1.18032 20.404 10.667)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="l__dw9bpv"/><stop offset="1" class="wrh2b4bbx"/></radialGradient><radialGradient id="iCgZMMc" cx="0" cy="0" r="1" gradientTransform="rotate(180 5.706 5.278)scale(1.05596)" gradientUnits="userSpaceOnUse"><stop offset=".722" class="o3wo53bzp"/><stop offset="1" class="eo_7g0bzd"/></radialGradient><radialGradient id="iLuiDwe" cx="0" cy="0" r="1" gradientTransform="matrix(-6.50358 2.99902 -4.01413 -8.70492 18.872 10.018)" gradientUnits="userSpaceOnUse"><stop class="crj44uotj"/><stop offset="1" class="yamoh3dov"/></radialGradient><radialGradient id="iXzC7Nd" cx="0" cy="0" r="1" gradientTransform="rotate(156.249 7.848 7.327)scale(2.38203 1.65881)" gradientUnits="userSpaceOnUse"><stop class="up8l18w-p"/><stop offset="1" class="ai95fabuh"/></radialGradient><radialGradient id="iJsKPZc" cx="0" cy="0" r="1" gradientTransform="matrix(1.28915 -3.92836 4.98436 1.6357 13.85 16.525)" gradientUnits="userSpaceOnUse"><stop class="osxg47drp"/><stop offset="1" class="da7h3oe0u"/></radialGradient><radialGradient id="ignzExc" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.1875 -8.98428 0 16.012 9.59)" gradientUnits="userSpaceOnUse"><stop offset=".624" class="h_y8-2y_k"/><stop offset="1" class="h8ma4pq8g"/></radialGradient><radialGradient id="i0KFnTb" cx="0" cy="0" r="1" gradientTransform="rotate(168.897 8.34 6.74)scale(7.03739 12.1162)" gradientUnits="userSpaceOnUse"><stop offset=".795" class="opgioqbtx"/><stop offset="1" class="wg3eepbwp"/></radialGradient><radialGradient id="iGsicwd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.15077 1.41231 0 18.314 9.6)" gradientUnits="userSpaceOnUse"><stop class="t9k87pm2r"/><stop offset="1" class="ax9af2vtk"/></radialGradient><radialGradient id="iFdXOHc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.31251 1.50423 0 13.936 9.37)" gradientUnits="userSpaceOnUse"><stop class="x_ik4kbfh"/><stop offset="1" class="gcfqr7bfg"/></radialGradient><radialGradient id="iXdRdne" cx="0" cy="0" r="1" gradientTransform="matrix(-.87016 3.22674 -2.58193 -.69627 17.396 7.283)" gradientUnits="userSpaceOnUse"><stop class="uj7hgsb3u"/><stop offset="1" class="p88c31myn"/></radialGradient><radialGradient id="i4domqd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.28528 0 0 -6.44557 21.108 11.087)" gradientUnits="userSpaceOnUse"><stop class="zoq8fuaif"/><stop offset="1" class="ycrcotb4u"/></radialGradient><radialGradient id="it0zi9c" cx="0" cy="0" r="1" gradientTransform="rotate(-121.569 14.231 2.387)scale(1.52213 1.61741)" gradientUnits="userSpaceOnUse"><stop class="ni-4se4rm"/><stop offset="1" class="wsh5tsbcf"/></radialGradient><radialGradient id="ilKR0dH" cx="0" cy="0" r="1" gradientTransform="matrix(1.75 -1.5625 1.85526 2.0779 11.976 15.747)" gradientUnits="userSpaceOnUse"><stop class="z26rrllgi"/><stop offset="1" class="fs9pa7bci"/></radialGradient><radialGradient id="i87Ennc" cx="0" cy="0" r="1" gradientTransform="matrix(-.45554 -2.04401 .62995 -.1404 16.797 11.814)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="bof3uzbpf"/><stop offset="1" class="jaf6nfbfs"/></radialGradient><radialGradient id="i0lCYAR" cx="0" cy="0" r="1" gradientTransform="matrix(-.7794 0 0 -.2179 16.557 12.025)" gradientUnits="userSpaceOnUse"><stop class="bof3uzbpf"/><stop offset="1" class="jaf6nfbfs"/></radialGradient><radialGradient id="iuGVWGd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.29049 0 18.194 9.958)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="ibk3XZc" cx="0" cy="0" r="1" gradientTransform="matrix(-.23192 -.29886 .41145 -.3193 17.966 10.042)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="igHlA7C" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.2905 0 13.83 9.958)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="i9MDc0m" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 11.782 -1.578)scale(.49412 .59395)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iAx25gd" cx="0" cy="0" r="1" gradientTransform="rotate(-65.391 11.282 -4.147)scale(3.03069 1.55043)" gradientUnits="userSpaceOnUse"><stop class="cuv4n92_b"/><stop offset="1" class="mq6wd3bba"/></radialGradient><radialGradient id="iz0rKte" cx="0" cy="0" r="1" gradientTransform="rotate(115.684 8.135 6.95)scale(4.8729 7.96691)" gradientUnits="userSpaceOnUse"><stop offset=".639" class="ssbc2ccsr"/><stop offset="1" class="ou3onybvn"/></radialGradient><radialGradient id="iMadc1b" cx="0" cy="0" r="1" gradientTransform="matrix(-.21033 1.3672 -2.94145 -.45252 16.223 3)" gradientUnits="userSpaceOnUse"><stop class="g5d3hjacf"/><stop offset="1" class="j2p90_-bc"/></radialGradient><filter id="iqR2Ynd" width="15.268" height="15.768" x="8.503" y="1.277" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.121569 0 0 0 0 0.0705882 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3327"/></filter><filter id="ivLeJie" width="4.081" height="11.683" x="5.07" y="18.29" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.384314 0 0 0 0 0.345098 0 0 0 0 0.494118 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3327"/></filter><filter id="iwiAVHd" width="5.909" height="14.117" x="12.858" y="15.85" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.513726 0 0 0 0 0.431373 0 0 0 0 0.560784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3327"/></filter><filter id="ij2RA0c" width="7.13" height="5.229" x="12.285" y="16.141" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3327" stdDeviation=".3"/></filter><filter id="iM88w2d" width="7.239" height="14.645" x="9.195" y="15.834" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3327" stdDeviation=".5"/></filter><filter id="igNzdHd" width="5.917" height="14.259" x="10.326" y="15.708" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.235294 0 0 0 0 0.113725 0 0 0 0 0.172549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3327"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.235294 0 0 0 0 0.113725 0 0 0 0 0.172549 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3327" result="effect2_innerShadow_4002_3327"/></filter><filter id="i0ywR4h" width="6.567" height="14.209" x="15.297" y="15.758" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.75"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.407843 0 0 0 0 0.372549 0 0 0 0 0.454902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3327"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.156863 0 0 0 0 0.0901961 0 0 0 0 0.2 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3327" result="effect2_innerShadow_4002_3327"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.156863 0 0 0 0 0.0901961 0 0 0 0 0.2 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_3327" result="effect3_innerShadow_4002_3327"/></filter><filter id="i6Gfheb" width="2" height="2" x="14.731" y="24.909" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3327" stdDeviation=".25"/></filter><filter id="iVMfhyb" width="2" height="2" x="14.731" y="21.76" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3327" stdDeviation=".25"/></filter><filter id="ifY3ppP" width="1.05" height="1.05" x="15.504" y="25.085" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.180392 0 0 0 0 0.113725 0 0 0 0 0.243137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3327"/></filter><filter id="ixX2ntc" width="1.05" height="1.05" x="15.504" y="22.077" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.180392 0 0 0 0 0.113725 0 0 0 0 0.243137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3327"/></filter><filter id="iJMNDjq" width="2.465" height="2.95" x="16.029" y="17.391" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.286275 0 0 0 0 0.164706 0 0 0 0 0.223529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3327"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.239216 0 0 0 0 0.145098 0 0 0 0 0.32549 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3327" result="effect2_innerShadow_4002_3327"/></filter><filter id="iEYCWHc" width="2.365" height="2.9" x="13.731" y="17.491" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".3"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.270588 0 0 0 0 0.141176 0 0 0 0 0.2 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3327"/></filter><filter id="im8jTCA" width="1.717" height="1.717" x="15.204" y="17.847" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.180392 0 0 0 0 0.113725 0 0 0 0 0.243137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3327"/></filter><filter id="iu4ObBb" width="3.368" height="3.218" x="9.718" y="8.946" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.509804 0 0 0 0 0.376471 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3327"/></filter><filter id="iD0eBue" width="3.218" height="3.468" x="19.231" y="8.696" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.431373 0 0 0 0 0.243137 0 0 0 0 0.282353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3327"/></filter><filter id="iZjPucb" width="3.148" height="3.148" x="19.265" y="8.981" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3327" stdDeviation=".25"/></filter><filter id="i7eqE3b" width="2.648" height="2.648" x="10.022" y="9.231" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3327" stdDeviation=".125"/></filter><filter id="i21avLc" width="10.191" height="11.127" x="10.917" y="5.648" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".175"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.407843 0 0 0 0 0.223529 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3327"/></filter><filter id="iL8WHVw" width="2.877" height="3.682" x="14.411" y="9.55" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3327" stdDeviation=".25"/></filter><filter id="iW5JLSb" width="2.377" height="3.182" x="14.824" y="9.662" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3327" stdDeviation=".125"/></filter><filter id="iua2Oxd" width="3.702" height="1.526" x="14.161" y="12.903" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3327" stdDeviation=".05"/></filter><filter id="iqbMqMc" width="3.001" height="1.285" x="16.954" y="9.15" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0941176 0 0 0 0 0.0666667 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3327"/></filter><filter id="iD9EyWb" width="3.001" height="1.285" x="12.069" y="9.15" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0862745 0 0 0 0 0.054902 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3327"/></filter><filter id="ipOjRDe" width="2.453" height="1.091" x="12.204" y="7.727" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.164706 0 0 0 0 0.0901961 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3327"/></filter><filter id="iyAqtad" width="2.453" height="1.091" x="17.622" y="7.727" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.164706 0 0 0 0 0.0901961 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3327"/></filter><filter id="iosf0Bb" width=".787" height=".696" x="17.46" y="9.518" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3327" stdDeviation=".05"/></filter><filter id="iPK7h0c" width=".891" height=".913" x="18.3" y="9.593" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3327" stdDeviation=".1"/></filter><filter id="i8cmuyo" width=".986" height="1.04" x="13.857" y="9.53" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3327" stdDeviation=".1"/></filter><filter id="iJfiAvb" width=".913" height=".705" x="13.102" y="9.51" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3327" stdDeviation=".05"/></filter><filter id="i2Vsdre" width="2.261" height=".978" x="17.652" y="7.849" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3327" stdDeviation=".1"/></filter><filter id="i0OoY5b" width="2.261" height=".978" x="12.2" y="7.849" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3327" stdDeviation=".1"/></filter><filter id="if5nIDc" width="4.312" height="4.613" x="9.658" y="3.613" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.294118 0 0 0 0 0.262745 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3327"/><feGaussianBlur result="effect2_foregroundBlur_4002_3327" stdDeviation=".2"/></filter><filter id="iFxy7Nr" width="8.767" height="5.782" x="12.842" y="2.479" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".2"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.345098 0 0 0 0 0.329412 0 0 0 0 0.333333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3327"/><feGaussianBlur result="effect2_foregroundBlur_4002_3327" stdDeviation=".125"/></filter><filter id="i83iq1b" width="1.145" height="2.31" x="12.821" y="3.713" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3327" stdDeviation=".1"/></filter><filter id="iVDFdRb" width="6.927" height="3.872" x="15.181" y="4.271" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3327" stdDeviation=".5"/></filter><linearGradient id="i3JkmBA" x1="20.706" x2="13.9" y1="3.602" y2="16.207" gradientUnits="userSpaceOnUse"><stop class="c1nwhtznm"/><stop offset="1" class="ogqxd-bue"/></linearGradient><linearGradient id="iuyr1tn" x1="23.131" x2="22.971" y1="29.966" y2="29.966" gradientUnits="userSpaceOnUse"><stop class="xg711ab6m"/><stop offset="1" class="eets9_b_s"/></linearGradient><linearGradient id="iwTkvTT" x1="8.858" x2="9.061" y1="29.966" y2="29.966" gradientUnits="userSpaceOnUse"><stop class="az-h38bei"/><stop offset="1" class="fajspub8c"/></linearGradient><linearGradient id="irRAuOe" x1="9.19" x2="7.596" y1="29.973" y2="29.973" gradientUnits="userSpaceOnUse"><stop class="t1dt_ab6m"/><stop offset="1" class="a519fg_-g"/></linearGradient><linearGradient id="iQD9ace" x1="14.707" x2="12.794" y1="19.947" y2="16.473" gradientUnits="userSpaceOnUse"><stop class="z7qr8pb7n"/><stop offset="1" class="zynu2nm7a"/></linearGradient><linearGradient id="ig0Fqhd" x1="15.518" x2="15.198" y1="20.04" y2="19.939" gradientUnits="userSpaceOnUse"><stop class="x1yfsqmdm"/><stop offset="1" class="kqc3y0bzc"/></linearGradient><linearGradient id="ifwpvfb" x1="16.798" x2="18.955" y1="19.965" y2="16.867" gradientUnits="userSpaceOnUse"><stop class="d4kfw7asd"/><stop offset="1" class="ig120dbzq"/></linearGradient><linearGradient id="i1L7Mpd" x1="16.486" x2="16.722" y1="19.727" y2="19.649" gradientUnits="userSpaceOnUse"><stop class="cof-_sb7w"/><stop offset="1" class="vo3um_bur"/></linearGradient><linearGradient id="i6XAUBd" x1="12.815" x2="12.815" y1="16.834" y2="29.479" gradientUnits="userSpaceOnUse"><stop class="wm85g1cnx"/><stop offset="1" class="b0z0paczy"/></linearGradient><linearGradient id="iV8za6b" x1="17.576" x2="14.433" y1="18.505" y2="18.124" gradientUnits="userSpaceOnUse"><stop class="wwbo2fbxy"/><stop offset="1" class="ylpskf0-p"/></linearGradient><linearGradient id="i2zegdh" x1="15.205" x2="14.838" y1="19.489" y2="19.036" gradientUnits="userSpaceOnUse"><stop class="p5lz4ubjd"/><stop offset="1" class="tyszy7o8n"/></linearGradient><linearGradient id="if4vDlY" x1="8.894" x2="23.27" y1="15.42" y2="15.42" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="iiIRDCc" x1="8.894" x2="23.27" y1="15.389" y2="15.389" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="ib9i9tc" x1="9.769" x2="11.009" y1="10.642" y2="10.642" gradientUnits="userSpaceOnUse"><stop class="b9k-3ybvb"/><stop offset="1" class="vbw-bobru"/></linearGradient><linearGradient id="iw76p3K" x1="15.074" x2="16.012" y1="11.886" y2="11.886" gradientUnits="userSpaceOnUse"><stop class="rby1z7ber"/><stop offset="1" class="dl0nwov2w"/></linearGradient><linearGradient id="ihEYYnc" x1="16.012" x2="16.012" y1="12.685" y2="12.075" gradientUnits="userSpaceOnUse"><stop class="cyl8wapbv"/><stop offset="1" class="jplc2lvem"/></linearGradient><linearGradient id="ihA1M1b" x1="14.948" x2="15.409" y1="14.095" y2="13.383" gradientUnits="userSpaceOnUse"><stop class="lwz87437z"/><stop offset=".663" class="c7jfumw-i"/></linearGradient><linearGradient id="iKE2acd" x1="18.972" x2="18.659" y1="10.012" y2="10.205" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iKDvJOc" x1="14.574" x2="14.26" y1="10.012" y2="10.205" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="izrclwb" x1="13.121" x2="13.666" y1="4.357" y2="5.631" gradientUnits="userSpaceOnUse"><stop class="z66p5h_5k"/><stop offset="1" class="ll4sw0vun"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-in-tuxedo-medium-dark" /></template>
<style>
.a_orf89wt {
  stop-color: var(--svg-color--4f3b7b, #4F3B7B);
  stop-opacity: 0;
}

.a519fg_-g {
  stop-color: var(--svg-color--463766, #463766);
  stop-opacity: 0;
}

.aba3uxblf {
  stop-color: var(--svg-color--4e475c, #4E475C);
}

.ai95fabuh {
  stop-color: var(--svg-color--986b5a, #986B5A);
  stop-opacity: 0;
}

.at-3e3s_x {
  stroke: var(--svg-color--473c3c, #473C3C);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M14.16 8.182c-.322-.078-1.124-.039-1.66.345");
}

.ax9af2vtk {
  stop-color: var(--svg-color--875555, #875555);
  stop-opacity: 0;
}

.az-h38bei {
  stop-color: var(--svg-color--4b3973, #4B3973);
}

.b_mjjkbmw {
  stop-color: var(--svg-color--8179b0, #8179B0);
}

.b_rzieh8m {
  d: path("M23.099 18.29a10.68 10.68 0 0 1 3.831 8.18v3.497H23.1z");
}

.b0z0paczy {
  stop-color: var(--svg-color--4f3a77, #4F3A77);
}

.b9k-3ybvb {
  stop-color: var(--svg-color--6a4745, #6A4745);
}

.bbv_pqbfl {
  stop-color: var(--svg-color--4e475c, #4E475C);
  stop-opacity: 0;
}

.bl7uysvvb {
  stop-color: var(--svg-color--181518, #181518);
}

.bof3uzbpf {
  stop-color: var(--svg-color--a07a6f, #A07A6F);
}

.bvbk5ac3i {
  fill: var(--svg-color--543b70, #543B70);
  d: path("m14.133 17.535l1.813 1.251l-1.795 1.259a.246.246 0 0 1-.389-.187c-.04-.792-.04-1.57-.007-2.144a.239.239 0 0 1 .378-.179");
}

.c1nwhtznm {
  stop-color: var(--svg-color--45363a, #45363A);
}

.c1wwrfzpb {
  fill: var(--svg-color--352827, #352827);
  fill-rule: evenodd;
  d: path("m19.744 8.32l-.138.23za.268.268 0 0 1-.275.46l-.005-.003l-.022-.012l-.091-.046a3 3 0 0 0-.343-.135a2.3 2.3 0 0 0-1.072-.092a.268.268 0 1 1-.093-.528c.513-.09.988 0 1.328.109a3.3 3.3 0 0 1 .559.238l.01.006l.002.002z");
}

.c4u_fkb7m {
  stop-color: var(--svg-color--6c374d, #6C374D);
}

.c5vb29odw {
  stop-color: var(--svg-color--e0c6f9, #E0C6F9);
  stop-opacity: 0;
}

.c7jfumw-i {
  stop-color: var(--svg-color--865e63, #865E63);
  stop-opacity: 0;
}

.c9_6uxbfa {
  stop-color: var(--svg-color--4a4446, #4A4446);
  stop-opacity: 0;
}

.cc_fr1_1s {
  fill: var(--svg-color--5f3c45, #5F3C45);
  d: path("M11.346 11.63a1.074 1.074 0 1 0 0-2.149a1.074 1.074 0 0 0 0 2.148");
}

.chj8m5e2t {
  stop-color: var(--svg-color--040101, #040101);
  stop-opacity: 0;
}

.ci7dr71ae {
  fill: var(--svg-color--47383d, #47383D);
  d: path("m18.419 6.374l-1.426.262a.688.688 0 1 1-.125-1.365h2.341c1.384 0 1.843 1.396 1.899 1.872a3.15 3.15 0 0 0-2.69-.769");
}

.cj4rfmfkx {
  stop-color: var(--svg-color--3b3638, #3B3638);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cm2l5-bra {
  stop-color: var(--svg-color--554181, #554181);
}

.cof-_sb7w {
  stop-color: var(--svg-color--a487bb, #A487BB);
}

.cosmi4y3y {
  stop-color: var(--svg-color--4d3b5d, #4D3B5D);
}

.crj44uotj {
  stop-color: var(--svg-color--996b5e, #996B5E);
}

.cuv4n92_b {
  stop-color: var(--svg-color--433838, #433838);
}

.cyl8wapbv {
  stop-color: var(--svg-color--7c455c, #7C455C);
}

.cyzx27bkq {
  stop-color: var(--svg-color--978394, #978394);
}

.d4kfw7asd {
  stop-color: var(--svg-color--dabff4, #DABFF4);
}

.da7h3oe0u {
  stop-color: var(--svg-color--743f5a, #743F5A);
  stop-opacity: 0;
}

.dc_z0_bxw {
  d: path("M16.104 15.39h-.04c.1 0 .19 0 .29.01c-.08-.01-.17-.01-.25-.01");
}

.dfvy54bwo {
  fill: var(--svg-color--352827, #352827);
  d: path("m12.615 8.777l-.005.003a.268.268 0 0 1-.275-.46l.001-.001l.003-.002l.01-.006a2 2 0 0 1 .148-.076c.098-.047.239-.108.41-.162c.34-.109.815-.2 1.328-.11a.268.268 0 0 1-.093.529a2.3 2.3 0 0 0-1.072.092a3 3 0 0 0-.455.193");
}

.dh4f0mlhm {
  stop-color: var(--svg-color--592f4f, #592F4F);
}

.dl0nwov2w {
  stop-color: var(--svg-color--744c45, #744C45);
  stop-opacity: 0;
}

.e-twaac7b {
  stop-color: var(--svg-color--575455, #575455);
  stop-opacity: 0;
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e2l8hyb-w {
  d: path("M14.41 20.337c-1.185-1.235-1.367-4.253-1.367-4.253c.681-.36 1.548-.407 1.548-.407l1.421.79l.035 2.222l-.773 1.52c-.148.308-.608.394-.863.128");
}

.eets9_b_s {
  stop-color: var(--svg-color--4e377f, #4E377F);
  stop-opacity: 0;
}

.eo_7g0bzd {
  stop-color: var(--svg-color--5a3638, #5A3638);
}

.epgmjx2er {
  width: 3.875px;
  height: 6.133px;
  x: 14.075px;
  y: 12.709px;
  rx: 1.938px;
}

.eytkjzmjs {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.13 9.67c.064.085-.069.188-.22.301c-.15.113-.263.193-.326.108c-.064-.085.007-.246.158-.359s.325-.135.389-.05");
}

.fajspub8c {
  stop-color: var(--svg-color--4b3973, #4B3973);
  stop-opacity: 0;
}

.ff2asxc8d {
  stop-color: var(--svg-color--e0c6f9, #E0C6F9);
}

.fj3b0ib3x {
  stop-color: var(--svg-color--564561, #564561);
  stop-opacity: 0;
}

.fojlwlb9t {
  stop-color: var(--svg-color--dfc6d4, #DFC6D4);
  stop-opacity: 0;
}

.fs5qncc9z {
  stop-color: var(--svg-color--4d3b5d, #4D3B5D);
  stop-opacity: 0;
}

.fs9pa7bci {
  stop-color: var(--svg-color--6e494b, #6E494B);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.ftzzr1bjs {
  stop-color: var(--svg-color--84635f, #84635F);
  stop-opacity: 0;
}

.fx1tjiblm {
  stop-color: var(--svg-color--755041, #755041);
  stop-opacity: 0;
}

.g0r7omboq {
  stop-color: var(--svg-color--474445, #474445);
  stop-opacity: 0;
}

.g5d3hjacf {
  stop-color: var(--svg-color--4c4749, #4C4749);
}

.g6612mg3v {
  stop-color: var(--svg-color--724d4f, #724D4F);
  stop-opacity: 0;
}

.gbz-ilb0d {
  fill: var(--svg-color--70404a, #70404A);
  d: path("m15.62 10.332l-.684 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.53-1.7c-.115-.376-.494-.376-.613 0");
}

.gcfqr7bfg {
  stop-color: var(--svg-color--714350, #714350);
  stop-opacity: 0;
}

.geqh5zowk {
  stop-color: var(--svg-color--e8d4fa, #E8D4FA);
}

.gkm_etb7v {
  fill-rule: evenodd;
  d: path("M23.198 11.965a3.25 3.25 0 0 0 .323-1.427c0-.468-.096-.906-.268-1.306h.005a3 3 0 0 0-.281-.513l-.002-.003a3.24 3.24 0 0 1-.526-1.77v-.01a3.3 3.3 0 0 0-3.3-3.3a.54.54 0 0 1-.455-.233a3.3 3.3 0 0 0-2.682-1.376a3.3 3.3 0 0 0-2.682 1.376a.56.56 0 0 1-.455.233l-.085.001a3.3 3.3 0 0 0-3.214 3.298v.01a3.24 3.24 0 0 1-.526 1.771l-.003.004a3.3 3.3 0 0 0-.22 3.245a.51.51 0 0 1 0 .455a3.213 3.213 0 0 0 2.894 4.625h8.582a3.213 3.213 0 0 0 3.218-3.218a3.3 3.3 0 0 0-.323-1.407a.52.52 0 0 1 0-.455m-12.26-2.673h-.013l1.199 2.356c.123 2.802 1.217 0 3.888 0c2.672 0 3.837 3.12 3.96.317l1.136-3.197c-.054-1.245-.956-1.333-1.136-1.333h-3.22a3.86 3.86 0 0 1-3.19-1.673a.264.264 0 0 0-.46.051l-.083.194c-.225.561-.656.99-1.19 1.235q-.023.008-.05.02l-.052.02c-.236.123-.79.49-.81 1.439l.01.306z");
}

.glo437b-m {
  stop-color: var(--svg-color--040002, #040002);
  stop-opacity: 0;
}

.gtaq5zpgk {
  cx: 16.012px;
  cy: 18.755px;
  r: 0.809px;
}

.h_j9u0wvt {
  stop-color: var(--svg-color--e6e6e6, #E6E6E6);
}

.h_y8-2y_k {
  stop-color: var(--svg-color--7a475c, #7A475C);
  stop-opacity: 0;
}

.h7rekkb5e {
  d: path("M18.13 9.67c.064.085-.069.188-.22.301c-.15.113-.263.193-.326.108c-.064-.085.007-.246.158-.359s.325-.135.389-.05");
}

.h8ma4pq8g {
  stop-color: var(--svg-color--743b5d, #743B5D);
}

.hj096sb7e {
  stop-color: var(--svg-color--6b628b, #6B628B);
}

.hkormb2xp {
  stop-color: var(--svg-color--575455, #575455);
}

.hpeo8yzih {
  stop-color: var(--svg-color--9d7e72, #9D7E72);
}

.hti5s2xzi {
  d: path("M20.84 12.164a1.61 1.61 0 1 0 0-3.218a1.61 1.61 0 0 0 0 3.218");
}

.hx66smwtj {
  stop-color: var(--svg-color--4a4446, #4A4446);
}

.hzwfg4bat {
  d: path("M17.598 20.337c1.186-1.235 1.368-4.253 1.368-4.253c-.681-.36-1.548-.407-1.548-.407l-1.421.79l-.036 2.222l.774 1.52c.148.308.608.394.863.128");
}

.i-vd1ians {
  fill: var(--svg-color--8a6058, #8A6058);
  d: path("m15.63 10.194l-.532 1.7a.54.54 0 0 0 .521.7h.786a.54.54 0 0 0 .521-.7l-.531-1.7c-.114-.377-.646-.377-.765 0");
}

.i8gd1zbwo {
  stop-color: var(--svg-color--564561, #564561);
}

.ig120dbzq {
  stop-color: var(--svg-color--aea5b6, #AEA5B6);
}

.ihl9krbbc {
  stop-color: var(--svg-color--5e5962, #5E5962);
}

.iwijhb8cc {
  d: path("M5.07 26.47c0-5.796 4.7-10.62 10.5-10.62h.86c5.8 0 10.5 4.824 10.5 10.62v3.496H5.07z");
}

.j_4_fe6ih {
  d: path("M18.767 16.117a10.3 10.3 0 0 0-2.337-.267h-.86c-.795 0-1.568.09-2.312.261v5.422c0 4.175 1.065 5.972 2.654 8.433h.285c1.59-2.46 2.57-4.258 2.57-8.433z");
}

.j2p90_-bc {
  stop-color: var(--svg-color--4c4749, #4C4749);
  stop-opacity: 0;
}

.j8ireobfm {
  stop-color: var(--svg-color--72659b, #72659B);
}

.jaf6nfbfs {
  stop-color: var(--svg-color--a07a6f, #A07A6F);
  stop-opacity: 0;
}

.jc16_9ped {
  d: path("M13.828 9.481a.892.892 0 0 0-.86 1.128h1.724a1 1 0 0 0 .033-.236a.9.9 0 0 0-.897-.892");
}

.jfikb2f0k {
  stop-color: var(--svg-color--48414f, #48414F);
}

.jk5udqbyz {
  stop-color: var(--svg-color--464444, #464444);
  stop-opacity: 0;
}

.jp78e8bxj {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.403 9.209c.653 0 1.205.45 1.355 1.059a.274.274 0 0 1-.268.34h-2.23a.23.23 0 0 1-.228-.271a1.4 1.4 0 0 1 1.371-1.128");
}

.jplc2lvem {
  stop-color: var(--svg-color--7c455c, #7C455C);
  stop-opacity: 0;
}

.k5y7j_bmf {
  stop-color: var(--svg-color--48414f, #48414F);
  stop-opacity: 0;
}

.k7kmfp2ol {
  d: path("m15.63 10.194l-.532 1.7a.54.54 0 0 0 .521.7h.786a.54.54 0 0 0 .521-.7l-.531-1.7c-.114-.377-.646-.377-.765 0");
}

.kbl3igr5c {
  stop-color: var(--svg-color--040002, #040002);
}

.kqc3y0bzc {
  stop-color: var(--svg-color--ccb1e3, #CCB1E3);
  stop-opacity: 0;
}

.kt__1405u {
  stop-color: var(--svg-color--ccc, #CCC);
}

.ktkcunhjc {
  d: path("M11.346 11.63a1.074 1.074 0 1 0 0-2.149a1.074 1.074 0 0 0 0 2.148");
}

.l__dw9bpv {
  stop-color: var(--svg-color--7d4d48, #7D4D48);
  stop-opacity: 0;
}

.l0xg-rbdf {
  stop-color: var(--svg-color--040101, #040101);
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.lf_z1-eut {
  stop-color: var(--svg-color--705775, #705775);
}

.lgjudcrkd {
  stop-color: var(--svg-color--413733, #413733);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.ll4sw0vun {
  stop-color: var(--svg-color--24182d, #24182D);
}

.lmkyvq38o {
  d: path("M16.434 15.39c.25.01.51.03.77.05c-.26-.02-.51-.04-.77-.05");
}

.lmsmt5bzm {
  d: path("M11.242 18.4c-.03-1.01.55-1.42.819-1.501l.617-.066v5.373c0 3.575.239 4.663 2.733 7.12l.011.015c.047.083-.05.176-.132.12c-2.75-1.88-4.776-3.354-5.094-8.18a.187.187 0 0 1 .174-.198c.297-.019.56-.044.747-.06a.19.19 0 0 0 .171-.191c-.01-.531-.02-1.533-.046-2.431");
}

.lwz87437z {
  stop-color: var(--svg-color--865e63, #865E63);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mgsb3vbjk {
  stop-color: var(--svg-color--462c5b, #462C5B);
}

.mq6wd3bba {
  stop-color: var(--svg-color--433838, #433838);
  stop-opacity: 0;
}

.mt9k2qzvi {
  stop-color: var(--svg-color--755041, #755041);
}

.mvlg1lb-a {
  cx: 15.731px;
  cy: 25.909px;
  r: 0.5px;
  fill: var(--svg-color--c5a9df, #C5A9DF);
}

.mxnnm4bur {
  stop-color: var(--svg-color--464444, #464444);
}

.n_pmxxxsa {
  stop-color: var(--svg-color--4f3b7b, #4F3B7B);
}

.ni-4se4rm {
  stop-color: var(--svg-color--836462, #836462);
}

.njpbn0o1i {
  fill: var(--svg-color--88014f, #88014F);
  d: path("M16.012 13.467a3 3 0 0 1-1.421-.345c-.14-.073-.292.089-.203.22a1.932 1.932 0 0 0 3.249 0c.088-.136-.062-.293-.203-.22c-.412.22-.896.345-1.422.345");
}

.nwb1x8bnq {
  stop-color: var(--svg-color--594687, #594687);
}

.o3wo53bzp {
  stop-color: var(--svg-color--5a3638, #5A3638);
  stop-opacity: 0;
}

.oacz0_bgo {
  stroke: var(--svg-color--473c3c, #473C3C);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M17.952 8.182c.322-.078 1.124-.039 1.66.345");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ogqxd-bue {
  stop-color: var(--svg-color--1c151f, #1C151F);
}

.ojp787kql {
  stop-color: var(--svg-color--bb9dd6, #BB9DD6);
}

.olqyf7fmb {
  stop-color: var(--svg-color--875e5e, #875E5E);
}

.onomtin3h {
  fill: var(--svg-color--272528, #272528);
  d: path("M14.87 9.986c-.265-.467-.668-.836-1.537-.836c-.38 0-.747.106-1.073.37c-.269.216-.233.494-.024.598l.556.318c.651-.21 1.372-.24 2.078-.45");
}

.opgioqbtx {
  stop-color: var(--svg-color--805c54, #805C54);
  stop-opacity: 0;
}

.osxg47drp {
  stop-color: var(--svg-color--743f5a, #743F5A);
}

.ou3onybvn {
  stop-color: var(--svg-color--1f0d24, #1F0D24);
}

.p5lz4ubjd {
  stop-color: var(--svg-color--391f50, #391F50);
}

.p88c31myn {
  stop-color: var(--svg-color--815a5b, #815A5B);
  stop-opacity: 0;
}

.paonnib9g {
  stop-color: var(--svg-color--474445, #474445);
}

.pk3shsb1m {
  d: path("M11.327 12.164a1.61 1.61 0 1 0 0-3.218a1.61 1.61 0 0 0 0 3.218");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.poffvcb8y {
  d: path("M11.709 17.604c0-1.278.933-1.774 1.554-1.618v5.737c0 3.873 1.453 6.262 2.712 8.087c.063.091-.047.201-.138.139c-2.977-2.037-4.916-4.004-5.26-9.227a.203.203 0 0 1 .188-.215c.321-.02.606-.047.808-.065c.107-.01.188-.1.186-.207c-.011-.575-.023-1.659-.05-2.631");
}

.q0kampb0a {
  stop-color: var(--svg-color--422131, #422131);
  stop-opacity: 0;
}

.q5or-sbzv {
  d: path("M18.991 10.256a.84.84 0 0 0-.231-.463l-.26.285l.117.228z");
}

.qg_liac-i {
  cx: 13.559px;
  cy: 9.862px;
  rx: 0.39px;
  ry: 0.197px;
}

.qgsks8bel {
  fill: var(--svg-color--2f1920, #2F1920);
  d: path("M15.409 2.764c-1.133-.25-2.15.88-2.267 1.3c1.052 3.544 3.713 3.35 6.34 3.058c1.573-.175 1.743.542 1.877.889c0-3.933-3.344-4.671-5.921-5.24z");
}

.qn9z0pbfl {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M13.121 4.013c.023.243.235 1.157.545 1.71");
}

.qt-8hdcxt {
  d: path("M15.409 2.764c-1.133-.25-2.15.88-2.267 1.3c1.052 3.544 3.713 3.35 6.34 3.058c1.573-.175 1.743.542 1.877.889c0-3.933-3.344-4.671-5.921-5.24z");
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

.r2nms2bvi {
  fill: var(--svg-color--2d2b2e, #2D2B2E);
  d: path("M17.154 9.986c.266-.467.67-.836 1.538-.836c.38 0 .747.106 1.073.37c.268.216.232.494.024.598l-.556.318c-.652-.21-1.373-.24-2.079-.45");
}

.r5cfbubaw {
  stop-color: var(--svg-color--6c374d, #6C374D);
  stop-opacity: 0;
}

.r79fvmu0k {
  d: path("M20.84 11.63a1.074 1.074 0 1 0 0-2.149a1.074 1.074 0 0 0 0 2.148");
}

.r7p6ehbnk {
  stop-color: var(--svg-color--84635f, #84635F);
}

.rby1z7ber {
  stop-color: var(--svg-color--744c45, #744C45);
}

.rp3tqelhu {
  stop-color: var(--svg-color--63519f, #63519F);
}

.rr035z7jd {
  fill: var(--svg-color--845f59, #845F59);
  d: path("M20.84 11.63a1.074 1.074 0 1 0 0-2.149a1.074 1.074 0 0 0 0 2.148");
}

.rso9j8bhr {
  fill: var(--svg-color--000, #000);
  d: path("M17.685 10.373c0-.284.227-.51.511-.51a.51.51 0 0 1 .455.746h-.905a.46.46 0 0 1-.06-.236");
}

.ruy03dwsw {
  stop-color: var(--svg-color--724d4f, #724D4F);
}

.s41karbfc {
  stop-color: var(--svg-color--5a4772, #5A4772);
  stop-opacity: 0;
}

.s6_65gbjh {
  cx: 13.559px;
  cy: 9.862px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.safapbcnd {
  stop-color: var(--svg-color--937da2, #937DA2);
  stop-opacity: 0;
}

.silozpblh {
  stop-color: var(--svg-color--3b3638, #3B3638);
  stop-opacity: 0;
}

.sldn9dbpe {
  d: path("M14.644 10.269c0-.289-.235-.48-.298-.539l-.289.279l.178.361z");
}

.sm2uv51xo {
  d: path("M10.943 4.567c.566-.6 1.636-.6 2.131-.511l.396 1.29c-.253-.039-.478.05-.668.235c-.448 1.26-1.99 1.956-2.704 2.146c-.148-1.492.109-2.38.845-3.16");
}

.ssbc2ccsr {
  stop-color: var(--svg-color--1f0d24, #1F0D24);
  stop-opacity: 0;
}

.t1dt_ab6m {
  stop-color: var(--svg-color--463766, #463766);
}

.t1trakjku {
  stop-color: var(--svg-color--635275, #635275);
}

.t2_ncgbfi {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.621 9.209c-.653 0-1.205.45-1.355 1.059c-.044.174.09.34.268.34h2.231a.23.23 0 0 0 .227-.271a1.4 1.4 0 0 0-1.37-1.128");
}

.t9k87pm2r {
  stop-color: var(--svg-color--875555, #875555);
}

.tayze7bgq {
  stop-color: var(--svg-color--60556d, #60556D);
}

.tg6m8fb0a {
  stop-color: var(--svg-color--8179b0, #8179B0);
  stop-opacity: 0;
}

.tpv10tb7c {
  d: path("M10.925 9.293h.012l-.01-.266l-.01-.306c.02-.949.574-1.316.81-1.438l.051-.02l.051-.021a2.3 2.3 0 0 0 1.19-1.235l.082-.194a.264.264 0 0 1 .462-.05a3.86 3.86 0 0 0 3.189 1.673h3.22c.18 0 1.082.087 1.136 1.332l-.119 3.073c-.123 2.802-2.312 4.684-4.983 4.684c-2.672 0-4.86-1.882-4.983-4.684z");
}

.tr7czpf3k {
  stop-color: var(--svg-color--413733, #413733);
  stop-opacity: 0;
}

.ts-_p6bqx {
  fill: var(--svg-color--9c80b1, #9C80B1);
  fill-rule: evenodd;
  d: path("M12.889 16.74c-.037.825.18 2.637 1.367 3.872c.255.265.715.18.863-.13l.73-1.434l.731 1.435c.149.308.608.394.863.129c1.186-1.235 1.404-3.047 1.368-3.871h-5.922");
}

.tyszy7o8n {
  stop-color: var(--svg-color--391f50, #391F50);
  stop-opacity: 0;
}

.u21vfmbcf {
  stop-color: var(--svg-color--c6b5d5, #C6B5D5);
}

.ubq14mb-s {
  stop-color: var(--svg-color--422131, #422131);
}

.uc5leibtb {
  stop-color: var(--svg-color--796ba6, #796BA6);
}

.udzp2zp0e {
  stop-color: var(--svg-color--4e3566, #4E3566);
}

.uj7hgsb3u {
  stop-color: var(--svg-color--815a5b, #815A5B);
}

.uoh3u9bsv {
  d: path("M8.901 18.29a10.69 10.69 0 0 0-3.831 8.185v3.498H8.9z");
}

.up8l18w-p {
  stop-color: var(--svg-color--986b5a, #986B5A);
}

.uv-z0kbfv {
  fill: var(--svg-color--2a191e, #2A191E);
  d: path("M10.943 4.567c.566-.6 1.636-.6 2.131-.511l.396 1.29c-.253-.039-.478.05-.668.235c-.448 1.26-1.99 1.956-2.704 2.146c-.148-1.492.109-2.38.845-3.16");
}

.v0ftcskkn {
  stop-color: var(--svg-color--866c89, #866C89);
  stop-opacity: 0;
}

.v5ndbpbdn {
  stop-color: var(--svg-color--463856, #463856);
}

.vbw-bobru {
  stop-color: var(--svg-color--533335, #533335);
}

.vdt_t3f2x {
  stop-color: var(--svg-color--866c89, #866C89);
}

.vjj8ifxqk {
  stop-color: var(--svg-color--5e5962, #5E5962);
  stop-opacity: 0;
}

.vo3um_bur {
  stop-color: var(--svg-color--dcc1f4, #DCC1F4);
  stop-opacity: 0;
}

.voa0z2bgu {
  stop-color: var(--svg-color--47305d, #47305D);
}

.w5fsnhbly {
  d: path("m17.892 17.535l-1.813 1.251l1.795 1.259a.246.246 0 0 0 .388-.187c.041-.792.041-1.57.008-2.144a.239.239 0 0 0-.378-.179");
}

.wg3eepbwp {
  stop-color: var(--svg-color--805c54, #805C54);
}

.wm85g1cnx {
  stop-color: var(--svg-color--4b385d, #4B385D);
}

.wo1twgd7z {
  d: path("M8.901 18.29a10.68 10.68 0 0 0-3.831 8.18v3.497H8.9z");
}

.wpqym9bwz {
  cx: 16.004px;
  cy: 22.627px;
  r: 0.5px;
}

.wrh2b4bbx {
  stop-color: var(--svg-color--7d4d48, #7D4D48);
}

.wsh5tsbcf {
  stop-color: var(--svg-color--836462, #836462);
  stop-opacity: 0;
}

.wwbo2fbxy {
  stop-color: var(--svg-color--784d55, #784D55);
}

.x_ik4kbfh {
  stop-color: var(--svg-color--714350, #714350);
}

.x1yfsqmdm {
  stop-color: var(--svg-color--ab90c0, #AB90C0);
}

.x3uhsrvov {
  d: path("M18.196 9.481a.893.893 0 0 1 .86 1.128h-1.724a.896.896 0 0 1 .864-1.128");
}

.x4qpxczyt {
  fill: var(--svg-color--443452, #443452);
  d: path("M20.332 17.604c0-1.278-.933-1.774-1.555-1.618v5.737c0 3.873-1.452 6.262-2.711 8.087c-.063.091.047.201.138.139c2.976-2.037 4.915-4.004 5.26-9.227a.203.203 0 0 0-.188-.215c-.321-.02-.606-.047-.809-.065a.204.204 0 0 1-.185-.207c.011-.575.023-1.659.05-2.631");
}

.xadf9bcdw {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M16.012 13.467a3 3 0 0 1-1.421-.345c-.14-.073-.292.089-.203.22a1.932 1.932 0 0 0 3.249 0c.088-.136-.062-.293-.203-.22c-.412.22-.896.345-1.422.345Z");
}

.xdn388byj {
  stop-color: var(--svg-color--171418, #171418);
}

.xg711ab6m {
  stop-color: var(--svg-color--4e377f, #4E377F);
}

.yamoh3dov {
  stop-color: var(--svg-color--764e4c, #764E4C);
}

.ycrcotb4u {
  stop-color: var(--svg-color--986f60, #986F60);
  stop-opacity: 0;
}

.yl8zw5b_j {
  stop-color: var(--svg-color--592f4f, #592F4F);
  stop-opacity: 0;
}

.ylpskf0-p {
  stop-color: var(--svg-color--663a42, #663A42);
}

.yo2rlxb6h {
  fill: var(--svg-color--000, #000);
  d: path("M14.34 10.373a.51.51 0 0 0-.512-.51a.51.51 0 0 0-.454.746h.904a.5.5 0 0 0 .061-.236");
}

.ysjacm3zw {
  cx: 15.731px;
  cy: 22.76px;
  r: 0.5px;
  fill: var(--svg-color--bfa7d5, #BFA7D5);
}

.yzzmy4bmy {
  cx: 16.004px;
  cy: 25.635px;
  r: 0.5px;
}

.z_d2yzmmm {
  stop-color: var(--svg-color--4b435b, #4B435B);
}

.z26rrllgi {
  stop-color: var(--svg-color--6e494b, #6E494B);
}

.z58nq_enb {
  stop-color: var(--svg-color--5e536c, #5E536C);
}

.z66p5h_5k {
  stop-color: var(--svg-color--1a1316, #1A1316);
}

.z7qr8pb7n {
  stop-color: var(--svg-color--ba9fd3, #BA9FD3);
}

.zhh5xs6ht {
  stop-color: var(--svg-color--bb9dd6, #BB9DD6);
  stop-opacity: 0;
}

.zoq8fuaif {
  stop-color: var(--svg-color--986f60, #986F60);
}

.zuim55bho {
  d: path("m14.133 17.535l1.813 1.251l-1.795 1.259a.246.246 0 0 1-.389-.187c-.04-.792-.04-1.57-.007-2.144a.239.239 0 0 1 .378-.179");
}

.zynu2nm7a {
  stop-color: var(--svg-color--6b5977, #6B5977);
}

</style>
