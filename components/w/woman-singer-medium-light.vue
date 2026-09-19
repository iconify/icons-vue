<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iUFnIvP)"><path fill="url(#ivEtGDc)" clip-rule="evenodd" class="ximc_xb6l"/><path fill="url(#ielqZne)" clip-rule="evenodd" class="ximc_xb6l"/><path fill="url(#ixD2kNe)" clip-rule="evenodd" class="ximc_xb6l"/><path fill="url(#iW28o3b)" clip-rule="evenodd" class="ximc_xb6l"/><path fill="url(#ilwfZFs)" clip-rule="evenodd" class="ximc_xb6l"/><path fill="url(#iUhjple)" clip-rule="evenodd" class="ximc_xb6l"/><path fill="url(#ivPmXZb)" clip-rule="evenodd" class="ximc_xb6l"/><path fill="url(#i4SuAec)" clip-rule="evenodd" class="ximc_xb6l"/><path fill="url(#icSdJzd)" clip-rule="evenodd" class="ximc_xb6l"/><path fill="url(#iKCz1zc)" clip-rule="evenodd" class="ximc_xb6l"/></g><g filter="url(#iLPXK4d)"><path class="kf5ydzbkw"/><path fill="url(#ijkmK3c)" class="hw6w5_j-k"/></g><path fill="url(#inuVhoc)" class="pw-u_fdhk"/><path fill="url(#iR1RITc)" class="pw-u_fdhk"/><path fill="url(#ikfrscc)" class="h2jzxy-bn"/><path fill="url(#iWUfERd)" class="h2jzxy-bn"/><path fill="url(#iANN6AD)" class="ksylej4ab"/><path fill="url(#il9oWTc)" class="l2j9uceik"/><path fill="url(#iQN7nye)" class="l2j9uceik"/><path fill="url(#i5awphc)" class="l2j9uceik"/><path fill="url(#iY1pySx)" class="l2j9uceik"/><path fill="url(#iDwn6Mc)" class="zt-wrvhib"/><path fill="url(#iEY0BoG)" class="zt-wrvhib"/><path fill="url(#ivW6UiV)" class="zt-wrvhib"/><path fill="url(#i0lSTRC)" class="jgezf_b9n"/><path fill="url(#i0Y8ITc)" class="jgezf_b9n"/><path fill="url(#iuMHDjc)" class="juej_y2lu"/><path fill="url(#iqbfAwd)" class="juej_y2lu"/><path fill="url(#i0H49vd)" class="juej_y2lu"/><g filter="url(#itBasFd)"><path stroke="url(#iuC7Tfe)" class="x2gcoqb0h"/></g><path fill="url(#irrtz3c)" class="erns8wbxn"/><path fill="url(#iyZxhZc)" class="erns8wbxn"/><path fill="url(#iuP15tb)" class="erns8wbxn"/><path fill="url(#iJxz50b)" class="erns8wbxn"/><path fill="url(#iVQ306c)" class="ywl0znmqv"/><path fill="url(#iH5dEpb)" class="ywl0znmqv"/><path fill="url(#iVR9mdQ)" class="mmgungb3m"/><path fill="url(#iInrlfc)" class="mmgungb3m"/><path fill="url(#i5MbPed)" class="mmgungb3m"/><path fill="url(#icKxB2c)" class="mmgungb3m"/><g filter="url(#iNnopNe)"><path fill="url(#i18GEid)" class="h6q9k5kxv"/><path fill="url(#iDv2keZ)" class="h6q9k5kxv"/><path fill="url(#iLyFy7b)" class="h6q9k5kxv"/></g><path fill="url(#irS5kGd)" class="hso2r22lu"/><path fill="url(#i0FUNoc)" class="hso2r22lu"/><path fill="url(#iGJinme)" class="hso2r22lu"/><g filter="url(#iADtmdb)"><path fill="url(#iPeBEgd)" class="y55zg8_5g"/></g><g filter="url(#itbACud)"><path fill="url(#isGwCpA)" class="xtu76vbhx"/><path fill="url(#ijnMCWc)" class="xtu76vbhx"/><path fill="url(#iTSw0Md)" class="xtu76vbhx"/><path fill="url(#iQnJ1Fd)" class="xtu76vbhx"/><path fill="url(#is12rJb)" class="xtu76vbhx"/></g><path fill="url(#igQxdeb)" class="xtu76vbhx"/><g filter="url(#ipX1H2b)"><path stroke="url(#i6J0snd)" class="rbncc3b0e"/></g><g filter="url(#i1lyxGc)"><path stroke="url(#iGX6ajc)" class="tzt1rlcao"/></g><g filter="url(#i5ehqyw)"><path stroke="url(#iXSpwYd)" class="iw_bv4b1h"/></g><path fill="url(#iuBS74d)" class="in_wyk0zp"/><path fill="url(#iiafFze)" class="gazjkfbup"/><g filter="url(#i5ZO6ke)"><path fill="url(#id0ByPc)" class="ehim89zod"/></g><g filter="url(#iseYDIe)"><path fill="url(#iRXvHJe)" class="qhvbqzb-j"/><path fill="url(#ioHAYZb)" class="qhvbqzb-j"/></g><g filter="url(#iwIEmrd)"><path class="o551dubxt"/><path fill="url(#iKFvJtd)" class="o2pjp2s9x"/></g><g filter="url(#iHPRkYe)"><path class="hkh3fe08y"/><path fill="url(#ihapFze)" class="wspf7lbcf"/></g><g filter="url(#i3m86Bc)"><path fill="url(#iCffuJb)" class="jubvnt96z"/><path fill="url(#ikjUKte)" class="jubvnt96z"/><path fill="url(#iZEeNfc)" class="jubvnt96z"/><path fill="url(#ivFrUYd)" class="jubvnt96z"/><path fill="url(#iYSPtdc)" class="jubvnt96z"/><path fill="url(#ihLdQpF)" class="jubvnt96z"/><path fill="url(#i4oSqtd)" class="jubvnt96z"/></g><path fill="url(#iIu2b3c)" class="jd0hs4k1a"/><path fill="url(#iOcGr4d)" class="jd0hs4k1a"/><g filter="url(#iAkODae)"><path class="x86dpqvbk"/></g><g filter="url(#iSkkoRd)"><path class="uqrbjub-y"/><path fill="url(#ii0KrJc)" class="o_5b5acxl"/><path fill="url(#iUTSkGb)" class="o_5b5acxl"/><path fill="url(#im5ok8b)" class="o_5b5acxl"/></g><path fill="url(#in2AwQb)" class="o_5b5acxl"/><path fill="url(#ivRQJDb)" class="o_5b5acxl"/><path fill="url(#idUaFIb)" class="afnzx8brt"/><path fill="url(#ixxTHgK)" class="afnzx8brt"/><path stroke="url(#ije83ZW)" class="t0ll59wnp"/><g filter="url(#i0Ww1ue)"><path class="hc704m86e"/></g><g filter="url(#iJxPRsd)"><path class="qdow1lbkp"/></g><g filter="url(#ipkD0Ee)"><path class="f98cdu16e"/></g><g filter="url(#iCGbZbd)"><path clip-rule="evenodd" class="c-rb96bcs"/></g><path class="vnmg27b-x"/><path fill="url(#iAH9mBd)" class="cpxy-sbkx"/><path class="mtu07_byh"/><g filter="url(#i1T4oNc)"><path class="q50no1p9z"/><path fill="url(#io00M1d)" class="bbsv77gdb"/></g><g filter="url(#iHpJicL)"><path fill="url(#i0Qhb6d)" class="li3d_vbrb"/></g><path class="ej2dzzbwl"/><path fill="url(#iipIJib)" class="g_dlh3bqe"/><path class="f9zubnbem"/><g filter="url(#iEyqXLm)"><path fill="url(#iTAGEdX)" class="tn8wf-bbt"/></g><g filter="url(#irXKr4c)"><ellipse transform="rotate(-27.914 12.57 11.223)" class="rzie_nblj"/><ellipse fill="url(#il0veWd)" transform="rotate(-27.914 12.57 11.223)" class="rni8po62e"/></g><g filter="url(#iFA0ked)"><path class="c9h0120nf"/></g><g filter="url(#iRADfIc)"><path class="e8j8_1btj"/></g><g filter="url(#iUvdtTQ)"><path fill="url(#iJqmvGd)" class="bq5hmdb4o"/><path fill="url(#i03kb4d)" class="bq5hmdb4o"/></g><g filter="url(#i0JqyZd)"><path fill="url(#iScQArB)" class="lti-30bcb"/><path fill="url(#i85V0rb)" class="lti-30bcb"/><path fill="url(#iPR4NLc)" class="lti-30bcb"/></g><g filter="url(#iRpdftc)"><path stroke="url(#iJH0fme)" class="plknbeb7c"/></g><defs><radialGradient id="ielqZne" cx="0" cy="0" r="1" gradientTransform="matrix(1.7843 -3.70585 8.44958 4.06833 19.886 17.888)" gradientUnits="userSpaceOnUse"><stop class="rjxj417_v"/><stop offset="1" class="p1sg1mumi"/></radialGradient><radialGradient id="ixD2kNe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.93298 5.5903 -5.23289 -1.8094 14.396 13.736)" gradientUnits="userSpaceOnUse"><stop offset=".62" class="ta36f8b7v"/><stop offset="1" class="hcuenbefp"/></radialGradient><radialGradient id="iW28o3b" cx="0" cy="0" r="1" gradientTransform="matrix(-3.22546 2.5049 -3.08339 -3.97036 11.891 14.766)" gradientUnits="userSpaceOnUse"><stop offset=".205" class="hxuphr-8h"/><stop offset="1" class="v-9s4u7ch"/></radialGradient><radialGradient id="ilwfZFs" cx="0" cy="0" r="1" gradientTransform="matrix(-1.04664 1.49264 -1.35675 -.95134 10.124 12.158)" gradientUnits="userSpaceOnUse"><stop offset=".334" class="ybvptdnhb"/><stop offset="1" class="ue-yx0baa"/></radialGradient><radialGradient id="iUhjple" cx="0" cy="0" r="1" gradientTransform="matrix(-2.38479 -.53184 .7818 -3.50565 10.673 10.631)" gradientUnits="userSpaceOnUse"><stop offset=".226" class="sqmgyf2vi"/><stop offset="1" class="mvuactshi"/></radialGradient><radialGradient id="ivPmXZb" cx="0" cy="0" r="1" gradientTransform="rotate(55.684 1.62 12.648)scale(3.92597 6.85136)" gradientUnits="userSpaceOnUse"><stop class="vrnylccvf"/><stop offset="1" class="b442o21cz"/></radialGradient><radialGradient id="i4SuAec" cx="0" cy="0" r="1" gradientTransform="rotate(132.51 9.024 7.58)scale(1.67575 2.34183)" gradientUnits="userSpaceOnUse"><stop class="di6ktzbyk"/><stop offset="1" class="ejv935bph"/></radialGradient><radialGradient id="icSdJzd" cx="0" cy="0" r="1" gradientTransform="rotate(163.779 10.596 7.152)scale(1.96539 4.27643)" gradientUnits="userSpaceOnUse"><stop class="kdig6mnba"/><stop offset="1" class="him6rrbhz"/></radialGradient><radialGradient id="iKCz1zc" cx="0" cy="0" r="1" gradientTransform="rotate(156.949 9.829 9.247)scale(3.50535 5.58509)" gradientUnits="userSpaceOnUse"><stop class="c2fnpwywz"/><stop offset="1" class="c5g3vhi-m"/></radialGradient><radialGradient id="inuVhoc" cx="0" cy="0" r="1" gradientTransform="matrix(3.125 1 -2.08207 6.50646 3.708 25.896)" gradientUnits="userSpaceOnUse"><stop offset=".176" class="li28y9bsf"/><stop offset="1" class="o1jwunhtj"/></radialGradient><radialGradient id="ikfrscc" cx="0" cy="0" r="1" gradientTransform="rotate(110.288 4.569 19.687)scale(5.49596 3.74438)" gradientUnits="userSpaceOnUse"><stop class="oe2xm9ikp"/><stop offset="1" class="d6d59o0ou"/></radialGradient><radialGradient id="iY1pySx" cx="0" cy="0" r="1" gradientTransform="rotate(44.502 -14.575 38.533)scale(2.54126 2.34764)" gradientUnits="userSpaceOnUse"><stop class="apsa9cl1l"/><stop offset="1" class="ji3tmwq8i"/></radialGradient><radialGradient id="ivW6UiV" cx="0" cy="0" r="1" gradientTransform="rotate(127.231 1.558 11.246)scale(5.01003 5.42155)" gradientUnits="userSpaceOnUse"><stop offset=".054" class="mi2y_fs0q"/><stop offset="1" class="l1asq8nfe"/></radialGradient><radialGradient id="iuMHDjc" cx="0" cy="0" r="1" gradientTransform="scale(5.21858 8.19791)rotate(90 .16 2.733)" gradientUnits="userSpaceOnUse"><stop class="c45sexbab"/><stop offset="1" class="nmuomsb2n"/></radialGradient><radialGradient id="iqbfAwd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -7.03341 12.2744 0 15.098 24.488)" gradientUnits="userSpaceOnUse"><stop offset=".689" class="b533zmb1d"/><stop offset="1" class="tca_rpbvi"/></radialGradient><radialGradient id="iuC7Tfe" cx="0" cy="0" r="1" gradientTransform="rotate(-134.697 12.303 6.617)scale(2.35978 2.2583)" gradientUnits="userSpaceOnUse"><stop class="uloezobwm"/><stop offset="1" class="ze8idyb3b"/></radialGradient><radialGradient id="irrtz3c" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.44554 -3.83658 0 15.098 17.603)" gradientUnits="userSpaceOnUse"><stop class="imsnjf0rg"/><stop offset=".736" class="k7nt426pj"/></radialGradient><radialGradient id="iyZxhZc" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.08555 -.86564 0 13.195 17.502)" gradientUnits="userSpaceOnUse"><stop offset=".435" class="k46qp2buv"/><stop offset="1" class="pmqhjxbgb"/></radialGradient><radialGradient id="iuP15tb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.875 -.82178 0 17.267 17.44)" gradientUnits="userSpaceOnUse"><stop class="ldquu460t"/><stop offset="1" class="ytpyn_8cx"/></radialGradient><radialGradient id="iJxz50b" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.38834 -3.3618 0 15.098 18.042)" gradientUnits="userSpaceOnUse"><stop offset=".588" class="rratv5bkx"/><stop offset="1" class="a21xb_b5i"/></radialGradient><radialGradient id="iVQ306c" cx="0" cy="0" r="1" gradientTransform="matrix(-2.1394 1.4599 -1.43346 -2.10066 28.718 21.806)" gradientUnits="userSpaceOnUse"><stop offset=".464" class="a05f1abog"/><stop offset="1" class="u70m8cc1d"/></radialGradient><radialGradient id="iH5dEpb" cx="0" cy="0" r="1" gradientTransform="matrix(.84335 -.64209 .49204 .64628 28.086 21.644)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="hcxzg0b5c"/><stop offset="1" class="eqicngbxg"/></radialGradient><radialGradient id="iInrlfc" cx="0" cy="0" r="1" gradientTransform="rotate(148.849 11.26 12.222)scale(4.17157)" gradientUnits="userSpaceOnUse"><stop offset=".838" class="wc1l7vbis"/><stop offset="1" class="oa317xagd"/></radialGradient><radialGradient id="i5MbPed" cx="0" cy="0" r="1" gradientTransform="matrix(1.26514 1.24827 -2.90348 2.94272 23.842 15.493)" gradientUnits="userSpaceOnUse"><stop class="ky_indbcd"/><stop offset="1" class="s_ufbeclz"/></radialGradient><radialGradient id="icKxB2c" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.37479 2.10625 0 26.912 16.85)" gradientUnits="userSpaceOnUse"><stop class="qkb33eb6n"/><stop offset="1" class="q-0s8ibrs"/></radialGradient><radialGradient id="iDv2keZ" cx="0" cy="0" r="1" gradientTransform="matrix(0 .4408 -2.66861 0 27.506 17.242)" gradientUnits="userSpaceOnUse"><stop class="zxhnj4bqq"/><stop offset="1" class="hf-5q38gm"/></radialGradient><radialGradient id="iPeBEgd" cx="0" cy="0" r="1" gradientTransform="matrix(-.4998 .66245 -.66245 -.4998 25.98 21.113)" gradientUnits="userSpaceOnUse"><stop class="dg3rcdvoo"/><stop offset="1" class="r0tyikbvd"/></radialGradient><radialGradient id="ijnMCWc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8787 -1.6371 0 26.073 23.651)" gradientUnits="userSpaceOnUse"><stop offset=".106" class="yhi4l7bah"/><stop offset="1" class="sbugs4b_s"/></radialGradient><radialGradient id="iTSw0Md" cx="0" cy="0" r="1" gradientTransform="matrix(0 .94192 -1.75486 0 26.073 25.07)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="yhi4l7bah"/><stop offset="1" class="sbugs4b_s"/></radialGradient><radialGradient id="iQnJ1Fd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .78779 -1.4677 0 26.073 26.44)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="yhi4l7bah"/><stop offset="1" class="sbugs4b_s"/></radialGradient><radialGradient id="is12rJb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .87616 -2.08784 0 26.073 27.922)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="yhi4l7bah"/><stop offset="1" class="sbugs4b_s"/></radialGradient><radialGradient id="igQxdeb" cx="0" cy="0" r="1" gradientTransform="rotate(120.493 7.888 19.897)scale(6.49967 4.40837)" gradientUnits="userSpaceOnUse"><stop class="hsdt12m1i"/><stop offset="1" class="v1bt46wqv"/></radialGradient><radialGradient id="iRXvHJe" cx="0" cy="0" r="1" gradientTransform="rotate(-24.444 38.188 -38.168)scale(2.79862 3.41699)" gradientUnits="userSpaceOnUse"><stop offset=".572" class="qmmvvysmp"/><stop offset=".905" class="epx_cgb2c"/></radialGradient><radialGradient id="ioHAYZb" cx="0" cy="0" r="1" gradientTransform="matrix(1.02082 .29166 -.15334 .53669 20.263 10.108)" gradientUnits="userSpaceOnUse"><stop class="aso-vybjw"/><stop offset="1" class="krvd34mtu"/></radialGradient><radialGradient id="iKFvJtd" cx="0" cy="0" r="1" gradientTransform="rotate(-20.298 43.9 -49.17)scale(1.33536)" gradientUnits="userSpaceOnUse"><stop offset=".71" class="la61skb4q"/><stop offset="1" class="urs_pbb4x"/></radialGradient><radialGradient id="ihapFze" cx="0" cy="0" r="1" gradientTransform="matrix(-1.24557 0 0 -1.19146 10.306 11.932)" gradientUnits="userSpaceOnUse"><stop offset=".573" class="prydr8bcy"/><stop offset="1" class="ybx_6zbxd"/></radialGradient><radialGradient id="iCffuJb" cx="0" cy="0" r="1" gradientTransform="rotate(155.244 7.755 7.667)scale(7.3307 9.81201)" gradientUnits="userSpaceOnUse"><stop class="uy3z2gbbp"/><stop offset="1" class="gvh2bspmv"/></radialGradient><radialGradient id="ikjUKte" cx="0" cy="0" r="1" gradientTransform="matrix(-2.1595 1.14224 -.96911 -1.83219 17.027 12.095)" gradientUnits="userSpaceOnUse"><stop class="j8hkuac-d"/><stop offset="1" class="cre_5tbhq"/></radialGradient><radialGradient id="iZEeNfc" cx="0" cy="0" r="1" gradientTransform="rotate(-78.311 17.677 1.271)scale(4.22825 5.36486)" gradientUnits="userSpaceOnUse"><stop class="t6jzi2-1t"/><stop offset="1" class="i3g5qu-9r"/></radialGradient><radialGradient id="ivFrUYd" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.61296 -10.3198 0 15.082 11.087)" gradientUnits="userSpaceOnUse"><stop offset=".61" class="mf6_lxbuj"/><stop offset=".935" class="f-bjs_bwg"/></radialGradient><radialGradient id="iYSPtdc" cx="0" cy="0" r="1" gradientTransform="rotate(172.34 7.406 7.412)scale(5.92043 10.1932)" gradientUnits="userSpaceOnUse"><stop offset=".813" class="zzstxpr9j"/><stop offset="1" class="irzp_cb7o"/></radialGradient><radialGradient id="ihLdQpF" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.17792 1.69339 0 17.438 10.953)" gradientUnits="userSpaceOnUse"><stop offset=".259" class="mt3h7fbpd"/><stop offset="1" class="wcr1klbjh"/></radialGradient><radialGradient id="i4oSqtd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.39208 1.59542 0 13.118 11.042)" gradientUnits="userSpaceOnUse"><stop class="r-jog4w_t"/><stop offset="1" class="xjkdvxqyn"/></radialGradient><radialGradient id="iIu2b3c" cx="0" cy="0" r="1" gradientTransform="matrix(-1.37873 0 0 -4.53881 20.298 12.476)" gradientUnits="userSpaceOnUse"><stop class="yhs2bn2id"/><stop offset="1" class="g1fw3-bff"/></radialGradient><radialGradient id="iOcGr4d" cx="0" cy="0" r="1" gradientTransform="matrix(1.18352 4.31827 -8.92349 2.4457 12.523 5.746)" gradientUnits="userSpaceOnUse"><stop class="mih5kfbap"/><stop offset="1" class="kqfxh5bnm"/></radialGradient><radialGradient id="ii0KrJc" cx="0" cy="0" r="1" gradientTransform="rotate(-105.892 12.933 .613)scale(2.60718 1.49186)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="xjug-415a"/><stop offset="1" class="bd8jqdorr"/></radialGradient><radialGradient id="ivRQJDb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.31177 .93699 -1.25503 -1.75701 15.376 12.854)" gradientUnits="userSpaceOnUse"><stop offset=".797" class="atsjj9bsj"/><stop offset="1" class="vyevcqbzs"/></radialGradient><radialGradient id="idUaFIb" cx="0" cy="0" r="1" gradientTransform="rotate(159.839 6.646 6.638)scale(6.89096 6.0187)" gradientUnits="userSpaceOnUse"><stop class="ic-qqq3du"/><stop offset="1" class="w6le0vxed"/><stop offset="1" class="ym086l4wg"/></radialGradient><radialGradient id="ixxTHgK" cx="0" cy="0" r="1" gradientTransform="rotate(131.12 5.026 6.904)scale(.66525 2.54787)" gradientUnits="userSpaceOnUse"><stop offset=".203" class="ri6vfobjz"/><stop offset="1" class="vslufkb1d"/></radialGradient><radialGradient id="iAH9mBd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .83046 -1.32093 0 17.316 11.32)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="io00M1d" cx="0" cy="0" r="1" gradientTransform="matrix(-.23739 -.3059 .42116 -.32683 17.082 11.406)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iipIJib" cx="0" cy="0" r="1" gradientTransform="matrix(0 .83046 -1.32094 0 12.849 11.32)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="il0veWd" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 11.96 -.408)scale(.50578 .60796)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iJqmvGd" cx="0" cy="0" r="1" gradientTransform="rotate(54.19 -.918 11.548)scale(3.38495 6.72589)" gradientUnits="userSpaceOnUse"><stop offset=".403" class="hi5yi9bqv"/><stop offset="1" class="d8y_5zbge"/></radialGradient><radialGradient id="i03kb4d" cx="0" cy="0" r="1" gradientTransform="rotate(127.118 4.715 5.947)scale(3.18437 2.49738)" gradientUnits="userSpaceOnUse"><stop class="g6mu4o3fz"/><stop offset="1" class="dx30lgbdy"/></radialGradient><radialGradient id="iScQArB" cx="0" cy="0" r="1" gradientTransform="rotate(115.684 7.318 7.266)scale(4.98786 7.09253)" gradientUnits="userSpaceOnUse"><stop offset=".595" class="iz4jcxg0j"/><stop offset="1" class="qflnpfbur"/></radialGradient><radialGradient id="i85V0rb" cx="0" cy="0" r="1" gradientTransform="matrix(-.877 3.28288 -5.86004 -1.56548 17.45 5.02)" gradientUnits="userSpaceOnUse"><stop class="mv8kv7beo"/><stop offset="1" class="g_ulzrbqz"/></radialGradient><radialGradient id="iPR4NLc" cx="0" cy="0" r="1" gradientTransform="rotate(-119.068 11.323 .482)scale(7.38056 6.60666)" gradientUnits="userSpaceOnUse"><stop offset=".891" class="w58maet4h"/><stop offset=".979" class="drxq29wnr"/></radialGradient><linearGradient id="ivEtGDc" x1="19.886" x2="12.92" y1="4.815" y2="17.717" gradientUnits="userSpaceOnUse"><stop class="p6otu2-6b"/><stop offset="1" class="q5mih6mme"/></linearGradient><linearGradient id="ijkmK3c" x1="16.901" x2="15.504" y1="26.418" y2="26.115" gradientUnits="userSpaceOnUse"><stop class="k6k-6oblx"/><stop offset="1" class="l5x5or5jn"/></linearGradient><linearGradient id="iR1RITc" x1="7.199" x2="6.027" y1="26.217" y2="26.217" gradientUnits="userSpaceOnUse"><stop class="xfetrrneo"/><stop offset="1" class="n0fg5jb7h"/></linearGradient><linearGradient id="iWUfERd" x1="23.128" x2="23.77" y1="26.303" y2="26.271" gradientUnits="userSpaceOnUse"><stop offset=".478" class="g2cjljmej"/><stop offset="1" class="h5gp5h3ar"/></linearGradient><linearGradient id="iANN6AD" x1="23.395" x2="21.614" y1="26.334" y2="26.334" gradientUnits="userSpaceOnUse"><stop class="tsgwb3b4a"/><stop offset="1" class="nvk1b4bey"/></linearGradient><linearGradient id="il9oWTc" x1="22.77" x2="18.395" y1="16.288" y2="28.798" gradientUnits="userSpaceOnUse"><stop class="p3s97ubgt"/><stop offset="1" class="uhr48tggx"/></linearGradient><linearGradient id="iQN7nye" x1="17.486" x2="17.954" y1="23.056" y2="23.142" gradientUnits="userSpaceOnUse"><stop class="n-07uqbej"/><stop offset="1" class="k5vnjbbpd"/></linearGradient><linearGradient id="i5awphc" x1="23.501" x2="22.829" y1="20.642" y2="20.36" gradientUnits="userSpaceOnUse"><stop offset=".258" class="e6ztocy0u"/><stop offset="1" class="tjnac7b5i"/></linearGradient><linearGradient id="iDwn6Mc" x1="8.954" x2="11.895" y1="16.809" y2="29.178" gradientUnits="userSpaceOnUse"><stop class="yhs78-b2s"/><stop offset="1" class="ou99nli7g"/></linearGradient><linearGradient id="iEY0BoG" x1="13.408" x2="12.861" y1="25.876" y2="25.985" gradientUnits="userSpaceOnUse"><stop class="tyg1xhaog"/><stop offset="1" class="wn22vh-9z"/></linearGradient><linearGradient id="i0lSTRC" x1="8.114" x2="10.395" y1="28.146" y2="26.99" gradientUnits="userSpaceOnUse"><stop class="h1snaz72e"/><stop offset="1" class="kvxpklbcz"/></linearGradient><linearGradient id="i0Y8ITc" x1="9.877" x2="9.013" y1="26.165" y2="26.68" gradientUnits="userSpaceOnUse"><stop class="a9i5gdgdq"/><stop offset="1" class="qrkl270nd"/></linearGradient><linearGradient id="i0H49vd" x1="17.86" x2="16.54" y1="22.682" y2="22.523" gradientUnits="userSpaceOnUse"><stop offset=".061" class="cn0opxseg"/><stop offset="1" class="xdq9kpbfe"/></linearGradient><linearGradient id="iVR9mdQ" x1="25.739" x2="25.739" y1="15.984" y2="20.041" gradientUnits="userSpaceOnUse"><stop offset=".313" class="wprwrdbxj"/><stop offset=".562" class="ax-d4eb4u"/></linearGradient><linearGradient id="i18GEid" x1="25.933" x2="25.792" y1="16.92" y2="18.123" gradientUnits="userSpaceOnUse"><stop offset=".12" class="qcwm1i13v"/><stop offset="1" class="s0eee-boz"/></linearGradient><linearGradient id="iLyFy7b" x1="23.236" x2="23.363" y1="16.857" y2="17.293" gradientUnits="userSpaceOnUse"><stop class="wtu393bab"/><stop offset="1" class="ce_wr9jxr"/></linearGradient><linearGradient id="irS5kGd" x1="26.936" x2="24.648" y1="21.427" y2="21.427" gradientUnits="userSpaceOnUse"><stop class="j-x55pbxn"/><stop offset="1" class="zg05wl6cw"/></linearGradient><linearGradient id="i0FUNoc" x1="24.466" x2="24.847" y1="21.269" y2="21.241" gradientUnits="userSpaceOnUse"><stop class="fs7-dablt"/><stop offset="1" class="zg97ljbvw"/></linearGradient><linearGradient id="iGJinme" x1="27.084" x2="26.822" y1="21.141" y2="21.117" gradientUnits="userSpaceOnUse"><stop class="qna0z9q7a"/><stop offset="1" class="toldersuv"/></linearGradient><linearGradient id="isGwCpA" x1="27.996" x2="23.128" y1="26.674" y2="26.674" gradientUnits="userSpaceOnUse"><stop offset=".146" class="hqh-1rbea"/><stop offset=".861" class="id19t5fes"/></linearGradient><linearGradient id="i6J0snd" x1="23.742" x2="25.663" y1="24.471" y2="24.471" gradientUnits="userSpaceOnUse"><stop class="uxfooubcv"/><stop offset="1" class="ldqge0b0v"/></linearGradient><linearGradient id="iGX6ajc" x1="23.742" x2="25.663" y1="25.913" y2="25.913" gradientUnits="userSpaceOnUse"><stop class="uxfooubcv"/><stop offset="1" class="ldqge0b0v"/></linearGradient><linearGradient id="iXSpwYd" x1="23.742" x2="25.663" y1="27.343" y2="27.343" gradientUnits="userSpaceOnUse"><stop class="uxfooubcv"/><stop offset="1" class="ldqge0b0v"/></linearGradient><linearGradient id="iuBS74d" x1="7.743" x2="22.458" y1="16.855" y2="16.855" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="iiafFze" x1="7.743" x2="22.458" y1="16.824" y2="16.824" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="id0ByPc" x1="8.639" x2="11.668" y1="12.021" y2="12.021" gradientUnits="userSpaceOnUse"><stop class="nka4--b6e"/><stop offset="1" class="aps1jhbfc"/></linearGradient><linearGradient id="iUTSkGb" x1="14.011" x2="14.885" y1="13.237" y2="13.344" gradientUnits="userSpaceOnUse"><stop class="urkjpbftr"/><stop offset="1" class="lwjatlajn"/></linearGradient><linearGradient id="im5ok8b" x1="15.082" x2="15.082" y1="14.112" y2="13.487" gradientUnits="userSpaceOnUse"><stop class="dvyniwihb"/><stop offset="1" class="e5pm1bciq"/></linearGradient><linearGradient id="in2AwQb" x1="15.162" x2="15.162" y1="14.085" y2="13.942" gradientUnits="userSpaceOnUse"><stop class="vyevcqbzs"/><stop offset="1" class="atsjj9bsj"/></linearGradient><linearGradient id="ije83ZW" x1="14.336" x2="14.799" y1="15.624" y2="14.732" gradientUnits="userSpaceOnUse"><stop class="b1eb00egl"/><stop offset="1" class="t5ewf8b-q"/></linearGradient><linearGradient id="i0Qhb6d" x1="18.112" x2="17.791" y1="11.376" y2="11.573" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iTAGEdX" x1="13.61" x2="13.289" y1="11.376" y2="11.573" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iJH0fme" x1="12.123" x2="12.68" y1="5.587" y2="6.891" gradientUnits="userSpaceOnUse"><stop class="gjbrx7i8b"/><stop offset="1" class="zcr9jykfw"/></linearGradient><filter id="iUFnIvP" width="15.622" height="16.122" x="7.396" y="2.452" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.886275 0 0 0 0 0.698039 0 0 0 0 0.607843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2322"/></filter><filter id="iLPXK4d" width="5.513" height="4.74" x="12.848" y="24.047" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.976471 0 0 0 0 0.780392 0 0 0 0 0.866667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2322"/></filter><filter id="itBasFd" width="5.221" height="5.427" x="12.487" y="15.329" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2322" stdDeviation=".1"/></filter><filter id="iNnopNe" width="6.102" height="1.228" x="22.791" y="16.758" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.05"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.647059 0 0 0 0 0.47451 0 0 0 0 0.54902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2322"/></filter><filter id="iADtmdb" width="1.075" height="1.075" x="25.198" y="20.891" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".025"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.694118 0 0 0 0 0.560784 0 0 0 0 0.764706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2322"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".025"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.917647 0 0 0 0 0.87451 0 0 0 0 0.976471 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2322" result="effect2_innerShadow_4002_2322"/></filter><filter id="itbACud" width="5.369" height="6.076" x="23.128" y="22.722" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.658824 0 0 0 0 0.443137 0 0 0 0 0.411765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2322"/></filter><filter id="ipX1H2b" width="2.319" height=".3" x="23.592" y="24.243" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2322" stdDeviation=".05"/></filter><filter id="i1lyxGc" width="2.319" height=".3" x="23.592" y="25.685" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2322" stdDeviation=".05"/></filter><filter id="i5ehqyw" width="2.319" height=".3" x="23.592" y="27.115" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2322" stdDeviation=".05"/></filter><filter id="i5ZO6ke" width="3.444" height="3.544" x="8.639" y="10.284" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.858824 0 0 0 0 0.635294 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2322"/></filter><filter id="iseYDIe" width="3.294" height="3.544" x="18.376" y="10.034" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.827451 0 0 0 0 0.568627 0 0 0 0 0.505882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2322"/></filter><filter id="iwIEmrd" width="3.199" height="3.199" x="18.424" y="10.332" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2322" stdDeviation=".25"/></filter><filter id="iHPRkYe" width="2.999" height="2.999" x="8.806" y="10.432" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2322" stdDeviation=".2"/></filter><filter id="i3m86Bc" width="10.431" height="11.383" x="9.866" y="6.909" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.745098 0 0 0 0 0.486275 0 0 0 0 0.384314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2322"/></filter><filter id="iAkODae" width="2.922" height="3.745" x="13.455" y="10.914" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2322" stdDeviation=".25"/></filter><filter id="iSkkoRd" width="2.422" height="3.245" x="13.871" y="11.023" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2322" stdDeviation=".125"/></filter><filter id="i0Ww1ue" width="3.067" height="1.316" x="16.051" y="10.494" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.141176 0 0 0 0 0.0862745 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2322"/></filter><filter id="iJxPRsd" width="3.067" height="1.316" x="11.046" y="10.494" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.133333 0 0 0 0 0.0784314 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2322"/></filter><filter id="ipkD0Ee" width="2.506" height="1.112" x="11.184" y="9.041" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.262745 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2322"/></filter><filter id="iCGbZbd" width="2.506" height="1.112" x="16.729" y="9.041" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.262745 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2322"/></filter><filter id="i1T4oNc" width=".801" height=".708" x="16.566" y="10.872" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2322" stdDeviation=".05"/></filter><filter id="iHpJicL" width=".903" height=".926" x="17.428" y="10.952" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2322" stdDeviation=".1"/></filter><filter id="iEyqXLm" width="1" height="1.055" x="12.881" y="10.887" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2322" stdDeviation=".1"/></filter><filter id="irXKr4c" width=".93" height=".716" x="12.106" y="10.864" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2322" stdDeviation=".05"/></filter><filter id="iFA0ked" width="2.3" height=".987" x="16.767" y="9.169" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2322" stdDeviation=".1"/></filter><filter id="iRADfIc" width="2.3" height=".987" x="11.187" y="9.169" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2322" stdDeviation=".1"/></filter><filter id="iUvdtTQ" width="4.365" height="5.35" x="8.687" y="4.752" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2322" stdDeviation=".25"/></filter><filter id="i0JqyZd" width="9.113" height="5.905" x="11.692" y="3.672" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2322" stdDeviation=".125"/></filter><filter id="iRpdftc" width="1.158" height="2.35" x="11.823" y="4.935" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2322" stdDeviation=".1"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-singer-medium-light" /></template>
<style>
.a05f1abog {
  stop-color: var(--svg-color--deaf8e, #DEAF8E);
}

.a21xb_b5i {
  stop-color: var(--svg-color--da9e88, #DA9E88);
}

.a9i5gdgdq {
  stop-color: var(--svg-color--55447c, #55447C);
}

.afnzx8brt {
  d: path("M14.096 8.329a3.9 3.9 0 0 1-1.506-1.304a.27.27 0 0 0-.467.04l-1.906 5.611h1.895l-.522 2.921l3.92-5.504h-2.02z");
}

.aps1jhbfc {
  stop-color: var(--svg-color--b47860, #B47860);
}

.apsa9cl1l {
  stop-color: var(--svg-color--7955b5, #7955B5);
}

.aso-vybjw {
  stop-color: var(--svg-color--d59566, #D59566);
}

.atsjj9bsj {
  stop-color: var(--svg-color--c27b7c, #C27B7C);
  stop-opacity: 0;
}

.ax-d4eb4u {
  stop-color: var(--svg-color--562d79, #562D79);
}

.b1eb00egl {
  stop-color: var(--svg-color--ce9591, #CE9591);
}

.b442o21cz {
  stop-color: var(--svg-color--dcc893, #DCC893);
  stop-opacity: 0;
}

.b533zmb1d {
  stop-color: var(--svg-color--ac674f, #AC674F);
  stop-opacity: 0;
}

.bbsv77gdb {
  d: path("M17.25 11.025c.066.087-.07.193-.225.309s-.27.197-.335.11s.008-.252.162-.367c.155-.116.333-.139.398-.052");
}

.bd8jqdorr {
  stop-color: var(--svg-color--fdc9a8, #FDC9A8);
  stop-opacity: 0;
}

.bq5hmdb4o {
  d: path("M10.072 5.776c.636-.566 1.553-.572 2.068-.48l.412 1.32c-.263-.04-.498.052-.695.24c-.464 1.716-2.214 1.459-2.557 2.746c-.154-1.527-.326-2.848.772-3.826");
}

.c-rb96bcs {
  fill: var(--svg-color--9f6836, #9F6836);
  fill-rule: evenodd;
  d: path("m18.902 9.643l-.142.236za.275.275 0 0 1-.283.471l-.004-.002a1 1 0 0 0-.116-.06a3 3 0 0 0-.35-.138a2.3 2.3 0 0 0-1.098-.094a.275.275 0 0 1-.095-.54a2.9 2.9 0 0 1 1.36.11a3.4 3.4 0 0 1 .571.245l.01.006l.003.001z");
}

.c2fnpwywz {
  stop-color: var(--svg-color--fff4bc, #FFF4BC);
}

.c45sexbab {
  stop-color: var(--svg-color--e2a78f, #E2A78F);
}

.c5g3vhi-m {
  stop-color: var(--svg-color--fff4bc, #FFF4BC);
  stop-opacity: 0;
}

.c9h0120nf {
  stroke: var(--svg-color--a57045, #A57045);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M17.067 9.503c.33-.08 1.151-.04 1.7.353");
}

.ce_wr9jxr {
  stop-color: var(--svg-color--b19a83, #B19A83);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cn0opxseg {
  stop-color: var(--svg-color--a4695f, #A4695F);
}

.cpxy-sbkx {
  d: path("M17.318 10.832a.913.913 0 0 1 .88 1.154h-1.765a.917.917 0 0 1 .884-1.154");
}

.cre_5tbhq {
  stop-color: var(--svg-color--ffc89e, #FFC89E);
  stop-opacity: 0;
}

.d6d59o0ou {
  stop-color: var(--svg-color--4d396f, #4D396F);
}

.d8y_5zbge {
  stop-color: var(--svg-color--daa88f, #DAA88F);
}

.dg3rcdvoo {
  stop-color: var(--svg-color--d2bfe7, #D2BFE7);
}

.di6ktzbyk {
  stop-color: var(--svg-color--ffffbf, #FFFFBF);
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

.e6ztocy0u {
  stop-color: var(--svg-color--876bc0, #876BC0);
}

.e8j8_1btj {
  stroke: var(--svg-color--a57045, #A57045);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M13.187 9.503c-.33-.08-1.151-.04-1.7.353");
}

.ehim89zod {
  d: path("M10.286 13.579a1.647 1.647 0 1 0 0-3.294a1.647 1.647 0 0 0 0 3.294");
}

.ej2dzzbwl {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.635 10.554a1.43 1.43 0 0 0-1.387 1.084a.28.28 0 0 0 .274.348h2.284a.236.236 0 0 0 .232-.278a1.434 1.434 0 0 0-1.403-1.154");
}

.ejv935bph {
  stop-color: var(--svg-color--ffffbf, #FFFFBF);
  stop-opacity: 0;
}

.epx_cgb2c {
  stop-color: var(--svg-color--f6c3a3, #F6C3A3);
}

.eqicngbxg {
  stop-color: var(--svg-color--e6bea1, #E6BEA1);
  stop-opacity: 0;
}

.erns8wbxn {
  d: path("M12.812 15.654h4.571v2.8c0 1.261-1.023 1.977-2.285 1.977s-2.286-.716-2.286-1.978z");
}

.f-bjs_bwg {
  stop-color: var(--svg-color--c2798b, #C2798B);
}

.f98cdu16e {
  fill: var(--svg-color--9f6836, #9F6836);
  d: path("m11.604 10.112l-.004.002a.275.275 0 0 1-.283-.47l.001-.001h.001l.003-.002l.01-.006a2 2 0 0 1 .152-.079c.1-.048.244-.11.42-.165a2.9 2.9 0 0 1 1.359-.112a.274.274 0 1 1-.095.54c-.409-.071-.8 0-1.098.095a3 3 0 0 0-.466.198");
}

.f9zubnbem {
  fill: var(--svg-color--000, #000);
  d: path("M13.37 11.746a.52.52 0 0 0-.524-.524a.52.52 0 0 0-.465.764h.926a.5.5 0 0 0 .063-.24");
}

.fs7-dablt {
  stop-color: var(--svg-color--a0768f, #A0768F);
}

.ft5dv1b6b {
  fill: none;
}

.g_dlh3bqe {
  d: path("M12.847 10.832a.913.913 0 0 0-.88 1.154h1.764a1 1 0 0 0 .033-.24a.92.92 0 0 0-.917-.914");
}

.g_ulzrbqz {
  stop-color: var(--svg-color--ffffc0, #FFFFC0);
  stop-opacity: 0;
}

.g1fw3-bff {
  stop-color: var(--svg-color--f4c099, #F4C099);
  stop-opacity: 0;
}

.g2cjljmej {
  stop-color: var(--svg-color--604e83, #604E83);
}

.g6mu4o3fz {
  stop-color: var(--svg-color--fee2a9, #FEE2A9);
}

.gazjkfbup {
  d: path("M15.123 16.824h-.041c.102 0 .194 0 .297.01c-.082-.01-.174-.01-.256-.01");
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.gjbrx7i8b {
  stop-color: var(--svg-color--ebce91, #EBCE91);
}

.gvh2bspmv {
  stop-color: var(--svg-color--d39b88, #D39B88);
}

.h_j9u0wvt {
  stop-color: var(--svg-color--e6e6e6, #E6E6E6);
}

.h1snaz72e {
  stop-color: var(--svg-color--665395, #665395);
}

.h2jzxy-bn {
  d: path("M27.018 28.788c-.14-.96-.36-1.91-.65-2.84a11.77 11.77 0 0 0-3.24-5.13v7.97z");
}

.h5gp5h3ar {
  stop-color: var(--svg-color--604e83, #604E83);
  stop-opacity: 0;
}

.h6q9k5kxv {
  d: path("m28.214 16.828l-4.844-.02a.57.57 0 0 0-.58.579c0 .325.255.578.58.578l4.844.02a.57.57 0 0 0 .578-.578a.585.585 0 0 0-.578-.579");
}

.hc704m86e {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M16.251 11.349c.272-.478.685-.855 1.574-.855a1.7 1.7 0 0 1 1.098.377c.275.223.238.507.025.614l-.57.325c-.666-.216-1.404-.245-2.127-.461");
}

.hcuenbefp {
  stop-color: var(--svg-color--c7897d, #C7897D);
  stop-opacity: 0;
}

.hcxzg0b5c {
  stop-color: var(--svg-color--e6bea1, #E6BEA1);
}

.hf-5q38gm {
  stop-color: var(--svg-color--c1bcc8, #C1BCC8);
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

.hkh3fe08y {
  fill: var(--svg-color--b47a6c, #B47A6C);
  d: path("M10.306 13.031a1.1 1.1 0 1 0 0-2.199a1.1 1.1 0 0 0 0 2.2");
}

.hqh-1rbea {
  stop-color: var(--svg-color--f3c29f, #F3C29F);
}

.hsdt12m1i {
  stop-color: var(--svg-color--feca9f, #FECA9F);
}

.hso2r22lu {
  d: path("M25.726 26.628a.784.784 0 0 1-.782-.711l-.67-6.428l2.975.01l-.731 6.428a.8.8 0 0 1-.792.7");
}

.hw6w5_j-k {
  d: path("M12.848 24.048v4.74h5.313l-.803-4.69c-.68.25-1.42.38-2.19.38c-.81.01-1.6-.15-2.32-.43");
}

.hxuphr-8h {
  stop-color: var(--svg-color--cf987b, #CF987B);
}

.i3g5qu-9r {
  stop-color: var(--svg-color--b97783, #B97783);
  stop-opacity: 0;
}

.ic-qqq3du {
  stop-color: var(--svg-color--f63273, #F63273);
}

.id19t5fes {
  stop-color: var(--svg-color--c68b80, #C68B80);
}

.imsnjf0rg {
  stop-color: var(--svg-color--c07881, #C07881);
}

.in_wyk0zp {
  d: path("M15.46 16.824c.257.01.523.031.789.051c-.266-.02-.522-.04-.788-.05");
}

.irzp_cb7o {
  stop-color: var(--svg-color--e3ab91, #E3AB91);
}

.iw_bv4b1h {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.742 27.265h2.02");
}

.iz4jcxg0j {
  stop-color: var(--svg-color--f0c6a3, #F0C6A3);
  stop-opacity: 0;
}

.j-x55pbxn {
  stop-color: var(--svg-color--d9cbea, #D9CBEA);
}

.j8hkuac-d {
  stop-color: var(--svg-color--ffc89e, #FFC89E);
}

.jd0hs4k1a {
  d: path("M9.875 10.64h.012l-.01-.272l-.01-.314c.02-.97.587-1.347.829-1.472l.052-.021l.053-.021a2.36 2.36 0 0 0 1.217-1.264l.084-.198a.27.27 0 0 1 .473-.052a3.95 3.95 0 0 0 3.264 1.712h3.296c.184 0 1.108.09 1.163 1.364l-.122 3.146c-.126 2.868-2.366 4.795-5.1 4.795c-2.735 0-4.975-1.927-5.102-4.795z");
}

.jgezf_b9n {
  d: path("M7.078 28.788h3.87l-3.87-7.596z");
}

.ji3tmwq8i {
  stop-color: var(--svg-color--7955b5, #7955B5);
  stop-opacity: 0;
}

.jubvnt96z {
  d: path("m9.877 10.368l-.01-.314c.02-.97.587-1.347.829-1.472l.052-.021l.053-.021a2.36 2.36 0 0 0 1.217-1.264l.084-.198a.27.27 0 0 1 .473-.052a3.95 3.95 0 0 0 3.264 1.712h3.296c.184 0 1.108.09 1.163 1.364l-.122 3.146c-.126 2.868-2.366 4.795-5.1 4.795c-2.735 0-4.975-1.927-5.102-4.795z");
}

.juej_y2lu {
  d: path("M15.118 17.688c-1.16 0-2.298.171-3.378.491l1.098 5.869c.72.28 1.5.44 2.32.44c.77 0 1.51-.14 2.19-.38l1.11-5.92c-1.05-.33-2.18-.5-3.34-.5");
}

.k46qp2buv {
  stop-color: var(--svg-color--cf8c7f, #CF8C7F);
}

.k5vnjbbpd {
  stop-color: var(--svg-color--845ebf, #845EBF);
  stop-opacity: 0;
}

.k6k-6oblx {
  stop-color: var(--svg-color--c296bf, #C296BF);
}

.k7nt426pj {
  stop-color: var(--svg-color--c37e7d, #C37E7D);
}

.kdig6mnba {
  stop-color: var(--svg-color--fffabe, #FFFABE);
}

.kf5ydzbkw {
  fill: var(--svg-color--e7c1f2, #E7C1F2);
  d: path("M12.848 24.048v4.74h5.313l-.803-4.69c-.68.25-1.42.38-2.19.38c-.81.01-1.6-.15-2.32-.43");
}

.kqfxh5bnm {
  stop-color: var(--svg-color--be7c5a, #BE7C5A);
  stop-opacity: 0;
}

.krvd34mtu {
  stop-color: var(--svg-color--d59566, #D59566);
  stop-opacity: 0;
}

.ksylej4ab {
  d: path("M23.128 28.788v-7.303l-3.52 7.303z");
}

.kt__1405u {
  stop-color: var(--svg-color--ccc, #CCC);
}

.kvxpklbcz {
  stop-color: var(--svg-color--5d4c7d, #5D4C7D);
}

.ky_indbcd {
  stop-color: var(--svg-color--7b5e40, #7B5E40);
}

.l1asq8nfe {
  stop-color: var(--svg-color--815eb7, #815EB7);
  stop-opacity: 0;
}

.l2j9uceik {
  d: path("m24.313 16.801l-4.779.021a1 1 0 0 0-.978.816l-2.097 11.16h3.149l5.325-11.017a.685.685 0 0 0-.62-.98");
}

.l5x5or5jn {
  stop-color: var(--svg-color--e7c1f5, #E7C1F5);
  stop-opacity: 0;
}

.la61skb4q {
  stop-color: var(--svg-color--e3a280, #E3A280);
  stop-opacity: 0;
}

.ldqge0b0v {
  stop-color: var(--svg-color--c08666, #C08666);
  stop-opacity: 0;
}

.ldquu460t {
  stop-color: var(--svg-color--ca9585, #CA9585);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.li28y9bsf {
  stop-color: var(--svg-color--675890, #675890);
}

.li3d_vbrb {
  d: path("M18.131 11.625a.86.86 0 0 0-.236-.473l-.267.292l.12.233z");
}

.lti-30bcb {
  d: path("M14.464 3.957c-1.159-.256-2.402.978-2.522 1.407c1.579 3.706 4.002 3.353 6.692 3.054c1.61-.179 1.784.555 1.921.91c-.446-4.153-3.448-4.788-6.09-5.37");
}

.lwjatlajn {
  stop-color: var(--svg-color--d1987a, #D1987A);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mf6_lxbuj {
  stop-color: var(--svg-color--c4808d, #C4808D);
  stop-opacity: 0;
}

.mi2y_fs0q {
  stop-color: var(--svg-color--6c3b70, #6C3B70);
}

.mih5kfbap {
  stop-color: var(--svg-color--be7c5a, #BE7C5A);
}

.mmgungb3m {
  d: path("M25.766 19.986a2.498 2.498 0 1 0 0-4.996a2.498 2.498 0 0 0 0 4.996");
}

.mt3h7fbpd {
  stop-color: var(--svg-color--e3a48e, #E3A48E);
}

.mtu07_byh {
  fill: var(--svg-color--000, #000);
  d: path("M16.794 11.746c0-.291.233-.524.524-.524a.52.52 0 0 1 .465.764h-.926a.5.5 0 0 1-.063-.24");
}

.mv8kv7beo {
  stop-color: var(--svg-color--ffffc0, #FFFFC0);
}

.mvuactshi {
  stop-color: var(--svg-color--c49070, #C49070);
  stop-opacity: 0;
}

.n-07uqbej {
  stop-color: var(--svg-color--8e5280, #8E5280);
}

.n0fg5jb7h {
  stop-color: var(--svg-color--504665, #504665);
  stop-opacity: 0;
}

.nka4--b6e {
  stop-color: var(--svg-color--c48b78, #C48B78);
}

.nmuomsb2n {
  stop-color: var(--svg-color--b17060, #B17060);
}

.nvk1b4bey {
  stop-color: var(--svg-color--5f4b8a, #5F4B8A);
}

.o_5b5acxl {
  d: path("m14.69 11.562l-.543 1.74a.552.552 0 0 0 .533.716h.804a.554.554 0 0 0 .533-.716l-.544-1.74c-.116-.386-.66-.386-.782 0");
}

.o1jwunhtj {
  stop-color: var(--svg-color--58497e, #58497E);
}

.o2pjp2s9x {
  d: path("M20.023 13.031a1.1 1.1 0 1 0 0-2.199a1.1 1.1 0 0 0 0 2.2");
}

.o551dubxt {
  fill: var(--svg-color--e5aa8b, #E5AA8B);
  d: path("M20.023 13.031a1.1 1.1 0 1 0 0-2.199a1.1 1.1 0 0 0 0 2.2");
}

.oa317xagd {
  stop-color: var(--svg-color--673d45, #673D45);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oe2xm9ikp {
  stop-color: var(--svg-color--746b8d, #746B8D);
}

.ou99nli7g {
  stop-color: var(--svg-color--9266df, #9266DF);
}

.p1sg1mumi {
  stop-color: var(--svg-color--ffc3a8, #FFC3A8);
  stop-opacity: 0;
}

.p3s97ubgt {
  stop-color: var(--svg-color--8866b4, #8866B4);
}

.p6otu2-6b {
  stop-color: var(--svg-color--ffffbe, #FFFFBE);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.plknbeb7c {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M12.123 5.235c.024.249.24 1.184.557 1.75");
}

.pmqhjxbgb {
  stop-color: var(--svg-color--cf8c7f, #CF8C7F);
  stop-opacity: 0;
}

.prydr8bcy {
  stop-color: var(--svg-color--b0725a, #B0725A);
  stop-opacity: 0;
}

.pw-u_fdhk {
  d: path("M7.078 28.788v-7.93a11.75 11.75 0 0 0-3.18 5.04l-.03.09c-.29.91-.51 1.85-.66 2.8z");
}

.q-0s8ibrs {
  stop-color: var(--svg-color--7d718c, #7D718C);
  stop-opacity: 0;
}

.q50no1p9z {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M17.25 11.025c.066.087-.07.193-.225.309s-.27.197-.335.11s.008-.252.162-.367c.155-.116.333-.139.398-.052");
}

.q5mih6mme {
  stop-color: var(--svg-color--e5ae90, #E5AE90);
}

.qcwm1i13v {
  stop-color: var(--svg-color--bfbac7, #BFBAC7);
}

.qdow1lbkp {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M13.913 11.349c-.271-.478-.684-.855-1.573-.855c-.39 0-.765.108-1.098.377c-.276.223-.239.507-.026.614l.57.325c.667-.216 1.404-.245 2.127-.461");
}

.qflnpfbur {
  stop-color: var(--svg-color--f0c6a3, #F0C6A3);
}

.qhvbqzb-j {
  d: path("M20.023 13.579a1.647 1.647 0 1 0 0-3.294a1.647 1.647 0 0 0 0 3.294");
}

.qkb33eb6n {
  stop-color: var(--svg-color--7d718c, #7D718C);
}

.qmmvvysmp {
  stop-color: var(--svg-color--e1a792, #E1A792);
}

.qna0z9q7a {
  stop-color: var(--svg-color--cbc6d6, #CBC6D6);
}

.qrkl270nd {
  stop-color: var(--svg-color--55447c, #55447C);
  stop-opacity: 0;
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r-jog4w_t {
  stop-color: var(--svg-color--c2847a, #C2847A);
}

.r0tyikbvd {
  stop-color: var(--svg-color--c0a6d9, #C0A6D9);
}

.rbncc3b0e {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.742 24.393h2.02");
}

.ri6vfobjz {
  stop-color: var(--svg-color--860c4f, #860C4F);
}

.rjxj417_v {
  stop-color: var(--svg-color--f9bfa4, #F9BFA4);
}

.rni8po62e {
  cx: 12.571px;
  cy: 11.223px;
  rx: 0.399px;
  ry: 0.202px;
}

.rratv5bkx {
  stop-color: var(--svg-color--c9837d, #C9837D);
  stop-opacity: 0;
}

.rzie_nblj {
  cx: 12.571px;
  cy: 11.223px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.399px;
  ry: 0.202px;
}

.s_ufbeclz {
  stop-color: var(--svg-color--463358, #463358);
  stop-opacity: 0;
}

.s0eee-boz {
  stop-color: var(--svg-color--aa7bd1, #AA7BD1);
}

.sbugs4b_s {
  stop-color: var(--svg-color--f2c49e, #F2C49E);
  stop-opacity: 0;
}

.sqmgyf2vi {
  stop-color: var(--svg-color--c49070, #C49070);
}

.t0ll59wnp {
  fill: var(--svg-color--88014e, #88014E);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M13.65 14.515c.414.22.907.347 1.432.347c.53 0 1.018-.127 1.432-.347a.21.21 0 0 1 .251.042c.06.063.081.163.022.254m-3.137-.296l3.095.268m-3.095-.268a.21.21 0 0 0-.252.044a.2.2 0 0 0-.02.252m.272-.296l-.231.268m3.368.028l-.042-.027m.042.027l-.042-.027m.042.027a2.028 2.028 0 0 1-3.41 0m3.368-.027a1.977 1.977 0 0 1-3.326 0m-.042.027l.042-.027m-.042.027l.042-.027");
}

.t5ewf8b-q {
  stop-color: var(--svg-color--ce9591, #CE9591);
  stop-opacity: 0;
}

.t6jzi2-1t {
  stop-color: var(--svg-color--b97783, #B97783);
}

.ta36f8b7v {
  stop-color: var(--svg-color--c7897d, #C7897D);
}

.tca_rpbvi {
  stop-color: var(--svg-color--ac674f, #AC674F);
}

.tjnac7b5i {
  stop-color: var(--svg-color--8263bd, #8263BD);
  stop-opacity: 0;
}

.tn8wf-bbt {
  d: path("M13.68 11.638c0-.295-.24-.492-.304-.551l-.295.285l.181.37z");
}

.toldersuv {
  stop-color: var(--svg-color--d3c3e5, #D3C3E5);
  stop-opacity: 0;
}

.tsgwb3b4a {
  stop-color: var(--svg-color--7c739f, #7C739F);
}

.tyg1xhaog {
  stop-color: var(--svg-color--6e3c78, #6E3C78);
}

.tzt1rlcao {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.742 25.835h2.02");
}

.u70m8cc1d {
  stop-color: var(--svg-color--b27959, #B27959);
}

.ue-yx0baa {
  stop-color: var(--svg-color--c58e72, #C58E72);
  stop-opacity: 0;
}

.uhr48tggx {
  stop-color: var(--svg-color--7f54c6, #7F54C6);
}

.uloezobwm {
  stop-color: var(--svg-color--d39a8a, #D39A8A);
}

.uqrbjub-y {
  fill: var(--svg-color--efb696, #EFB696);
  d: path("m14.69 11.562l-.543 1.74a.552.552 0 0 0 .533.716h.804a.554.554 0 0 0 .533-.716l-.544-1.74c-.116-.386-.66-.386-.782 0");
}

.urkjpbftr {
  stop-color: var(--svg-color--d1987a, #D1987A);
}

.urs_pbb4x {
  stop-color: var(--svg-color--e3a280, #E3A280);
}

.uxfooubcv {
  stop-color: var(--svg-color--ae7759, #AE7759);
}

.uy3z2gbbp {
  stop-color: var(--svg-color--ffc59d, #FFC59D);
}

.v-9s4u7ch {
  stop-color: var(--svg-color--cf987b, #CF987B);
  stop-opacity: 0;
}

.v1bt46wqv {
  stop-color: var(--svg-color--feca9f, #FECA9F);
  stop-opacity: 0;
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.vnmg27b-x {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.53 10.554c.668 0 1.233.46 1.386 1.084a.28.28 0 0 1-.274.348H16.36a.236.236 0 0 1-.233-.278a1.43 1.43 0 0 1 1.403-1.154");
}

.vrnylccvf {
  stop-color: var(--svg-color--dcc893, #DCC893);
}

.vslufkb1d {
  stop-color: var(--svg-color--860c4f, #860C4F);
  stop-opacity: 0;
}

.vyevcqbzs {
  stop-color: var(--svg-color--c27b7c, #C27B7C);
}

.w58maet4h {
  stop-color: var(--svg-color--dac493, #DAC493);
  stop-opacity: 0;
}

.w6le0vxed {
  stop-color: var(--svg-color--bc2f50, #BC2F50);
}

.wc1l7vbis {
  stop-color: var(--svg-color--473558, #473558);
  stop-opacity: 0;
}

.wcr1klbjh {
  stop-color: var(--svg-color--e3a48e, #E3A48E);
  stop-opacity: 0;
}

.wn22vh-9z {
  stop-color: var(--svg-color--825db9, #825DB9);
  stop-opacity: 0;
}

.wprwrdbxj {
  stop-color: var(--svg-color--453357, #453357);
}

.wspf7lbcf {
  d: path("M10.306 13.031a1.1 1.1 0 1 0 0-2.199a1.1 1.1 0 0 0 0 2.2");
}

.wtu393bab {
  stop-color: var(--svg-color--b19a83, #B19A83);
}

.x2gcoqb0h {
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M12.812 15.654h4.571v2.8c0 1.261-1.023 1.977-2.285 1.977s-2.286-.716-2.286-1.978z");
}

.x86dpqvbk {
  fill: var(--svg-color--c28178, #C28178);
  d: path("m14.68 11.704l-.7 1.74a.552.552 0 0 0 .533.715h.805a.554.554 0 0 0 .533-.715l-.544-1.74c-.116-.386-.505-.386-.627 0");
}

.xdq9kpbfe {
  stop-color: var(--svg-color--b77d6c, #B77D6C);
  stop-opacity: 0;
}

.xfetrrneo {
  stop-color: var(--svg-color--504665, #504665);
}

.ximc_xb6l {
  fill-rule: evenodd;
  d: path("M22.437 13.375a3.3 3.3 0 0 0 .331-1.461c0-.478-.098-.927-.275-1.336h.006a3.3 3.3 0 0 0-.288-.525l-.002-.004a3.3 3.3 0 0 1-.539-1.812v-.01a3.38 3.38 0 0 0-3.377-3.378a.55.55 0 0 1-.466-.238a3.38 3.38 0 0 0-2.745-1.409c-1.13 0-2.134.56-2.745 1.41a.58.58 0 0 1-.466.237l-.087.001a3.38 3.38 0 0 0-3.29 3.376v.01c0 .643-.187 1.275-.539 1.813l-.002.004a3.38 3.38 0 0 0-.226 3.322a.53.53 0 0 1 0 .466a3.34 3.34 0 0 0-.331 1.44a3.29 3.29 0 0 0 3.294 3.294h8.784a3.29 3.29 0 0 0 3.294-3.294a3.34 3.34 0 0 0-.331-1.44a.53.53 0 0 1 0-.466m-12.55-2.736h-.012l1.227 2.411c.126 2.869 1.245 0 3.98 0s3.927 3.193 4.053.325l1.163-3.273c-.055-1.274-.979-1.364-1.163-1.364H15.84a3.95 3.95 0 0 1-3.264-1.712a.27.27 0 0 0-.473.052l-.084.198a2.36 2.36 0 0 1-1.322 1.306c-.242.125-.809.501-.83 1.472l.01.314z");
}

.xjkdvxqyn {
  stop-color: var(--svg-color--c2847a, #C2847A);
  stop-opacity: 0;
}

.xjug-415a {
  stop-color: var(--svg-color--fdc9a8, #FDC9A8);
}

.xtu76vbhx {
  d: path("M23.128 23.674a.81.81 0 0 1 .816-.802h3.054c.745 0 1.349.59 1.349 1.316v3.514c0 .605-.503 1.096-1.124 1.096h-3.28a.81.81 0 0 1-.816-.802c0-.315.187-.59.458-.72a.8.8 0 0 1-.457-.72c0-.315.186-.59.457-.721a.8.8 0 0 1-.457-.72c0-.314.186-.59.457-.72a.8.8 0 0 1-.457-.72");
}

.y55zg8_5g {
  d: path("M25.736 21.916a.487.487 0 1 0 0-.975a.487.487 0 0 0 0 .975");
}

.ybvptdnhb {
  stop-color: var(--svg-color--c58e72, #C58E72);
}

.ybx_6zbxd {
  stop-color: var(--svg-color--b0725a, #B0725A);
}

.yhi4l7bah {
  stop-color: var(--svg-color--f8c8ad, #F8C8AD);
}

.yhs2bn2id {
  stop-color: var(--svg-color--f4c099, #F4C099);
}

.yhs78-b2s {
  stop-color: var(--svg-color--7c5aad, #7C5AAD);
}

.ym086l4wg {
  stop-color: var(--svg-color--d5415e, #D5415E);
}

.ytpyn_8cx {
  stop-color: var(--svg-color--ca9585, #CA9585);
  stop-opacity: 0;
}

.ywl0znmqv {
  d: path("M27.277 21.112c.59 0 1.07.48 1.07 1.07v2.45h-2.14v-2.45c0-.59.48-1.07 1.07-1.07");
}

.zcr9jykfw {
  stop-color: var(--svg-color--e6bd9f, #E6BD9F);
}

.ze8idyb3b {
  stop-color: var(--svg-color--d39a8a, #D39A8A);
  stop-opacity: 0;
}

.zg05wl6cw {
  stop-color: var(--svg-color--a78bc1, #A78BC1);
}

.zg97ljbvw {
  stop-color: var(--svg-color--ad93c6, #AD93C6);
  stop-opacity: 0;
}

.zt-wrvhib {
  d: path("M5.405 16.809h5.256a1 1 0 0 1 .983.816l2.095 11.173h-2.79l-5.88-11.529c-.086-.125-.07-.46.336-.46");
}

.zxhnj4bqq {
  stop-color: var(--svg-color--eae5f7, #EAE5F7);
}

.zzstxpr9j {
  stop-color: var(--svg-color--e3ab91, #E3AB91);
  stop-opacity: 0;
}

</style>
