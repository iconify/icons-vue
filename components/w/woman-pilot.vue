<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#isi4qAD)" class="zbniv-bew"/><path fill="url(#iQ1mNIb)" class="zbniv-bew"/><path fill="url(#iV9AAxc)" class="zbniv-bew"/><path fill="url(#iHvesle)" class="zbniv-bew"/><path fill="url(#idkFEne)" class="zbniv-bew"/><path fill="url(#iG8RLZc)" class="zbniv-bew"/><path fill="url(#icYZnJe)" class="zbniv-bew"/><path fill="url(#itJrsyC)" class="zbniv-bew"/><path fill="url(#i3k8mtc)" class="c1erwxb4g"/><path fill="url(#iJR6idd)" class="c1erwxb4g"/><path fill="url(#i0YSB3d)" class="p77532b6v"/><path fill="url(#iu8Rwfe)" class="p77532b6v"/><path fill="url(#iGhpVwC)" class="o7egzrbpm"/><path fill="url(#ilCO5Yb)" class="o7egzrbpm"/><path fill="url(#irWSoTc)" class="o7egzrbpm"/><path fill="url(#iPHUAte)" class="vw7_gxbgg"/><path fill="url(#isNKkbc)" class="vw7_gxbgg"/><path fill="url(#i3TxftV)" class="vw7_gxbgg"/><path fill="url(#iGs5oId)" class="vw7_gxbgg"/><g filter="url(#iQJ5AQO)"><path class="bpkuhdbht"/></g><path fill="url(#iCpmLAe)" class="ama8_rb1i"/><g filter="url(#iMpohFc)"><path class="nm038jbsl"/></g><g filter="url(#i49qdkq)"><path fill="url(#iKhME0b)" class="fa1pvobka"/><path fill="url(#i1ARehb)" class="fa1pvobka"/><path fill="url(#irwsJcc)" class="fa1pvobka"/></g><path fill="url(#i77gfyd)" class="fa1pvobka"/><g filter="url(#i04R72d)"><path class="mlltz6o2j"/></g><g filter="url(#iMYPbvc)"><path fill="url(#ipQ6fvd)" class="o3d2umjfs"/><path fill="url(#iNdAWxe)" class="o3d2umjfs"/></g><path fill="url(#ipvV6nd)" class="c7o726bgx"/><path fill="url(#iHOiXmd)" class="c7o726bgx"/><path fill="url(#iiB6oye)" class="c7o726bgx"/><path fill="url(#ivDk0Kd)" class="c7o726bgx"/><g filter="url(#iJIebJd)"><path fill="url(#i46Jevc)" class="k9db2z3ho"/></g><path fill="url(#i1Ucsgd)" class="brcdblhuw"/><path fill="url(#iGJCkod)" class="brcdblhuw"/><g filter="url(#i6IOCEC)"><path class="ghe7qfbhe"/></g><g filter="url(#iGEL79b)"><path fill="url(#ir3efbD)" class="zkg4d7d0r"/></g><g filter="url(#it74ace)"><path fill="url(#ivzdGcd)" class="fp1nwtbxe"/></g><g filter="url(#i89aUjg)"><path fill="url(#iEBlfzd)" class="zx54blbrh"/></g><g filter="url(#is631Wb)"><path class="x9y52dn2t"/><path fill="url(#iOIzsce)" class="dn19lhnml"/></g><g filter="url(#iqyoJxc)"><path class="vjmrt9beo"/><path fill="url(#iFjwfIS)" class="kdu09gbus"/></g><g filter="url(#iXMCDbe)"><path fill="url(#i9blcne)" class="igf0ujbup"/><path fill="url(#iBL2ild)" class="igf0ujbup"/><path fill="url(#iuYnBkF)" class="igf0ujbup"/><path fill="url(#ixW0Osc)" class="igf0ujbup"/><path fill="url(#imhptec)" class="igf0ujbup"/><path fill="url(#ilcedRP)" class="igf0ujbup"/><path fill="url(#iqYeR6d)" class="igf0ujbup"/></g><path fill="url(#iyBsQzF)" class="igf0ujbup"/><path fill="url(#iUtbsJd)" class="igf0ujbup"/><g filter="url(#iBV6Ayb)"><path class="a4rixsbmw"/></g><g filter="url(#iKaHoge)"><path fill="url(#iv4Q3qd)" class="o5lt0ibcc"/><path fill="url(#iqPcJ6d)" class="o5lt0ibcc"/><path fill="url(#ikvSbkm)" class="o5lt0ibcc"/><path fill="url(#inHpvye)" class="o5lt0ibcc"/><path fill="url(#i03sNUc)" class="o5lt0ibcc"/></g><path fill="url(#ilurGte)" class="o5lt0ibcc"/><path fill="url(#iUN7BVc)" class="o5lt0ibcc"/><g filter="url(#iBqwjYc)"><path stroke="url(#isbe8jz)" class="pl0aa6b6u"/></g><path class="l-h8a8bdf"/><g filter="url(#iK4RtUc)"><path class="h0_ab_jhn"/></g><g filter="url(#iC9kp4c)"><path class="ko4xv101l"/></g><path class="j0s8y6b3n"/><path fill="url(#iZeD1ME)" class="srguc_odb"/><path class="nwn820bbw"/><g filter="url(#iEtMDre)"><path class="o5lkxgbrw"/><path fill="url(#iWqPNsc)" class="wt2my6bsb"/></g><g filter="url(#iLqsTLe)"><path fill="url(#iYM2bzd)" class="xsdatwbtp"/></g><path class="tow72abrm"/><path fill="url(#iWbOR6c)" class="yolj3cc6n"/><path class="ldk8wmbpo"/><g filter="url(#iJ1075b)"><path fill="url(#ihOLrLb)" class="ci-y5kwyd"/></g><g filter="url(#ij9wz2c)"><ellipse transform="rotate(-27.914 13.657 9.954)" class="aq7surbst"/><ellipse fill="url(#iShnOIs)" transform="rotate(-27.914 13.657 9.954)" class="ktwqtybad"/></g><path fill="url(#iuby7lc)" class="xmvyn4b4c"/><path fill="url(#ioURXze)" class="xmvyn4b4c"/><path fill="url(#iYP29td)" class="xmvyn4b4c"/><g filter="url(#i5KeReY)"><path fill="url(#ipjoR9d)" class="kxz3h33un"/></g><path fill="url(#i09GSsc)" class="gkzo5sbtx"/><path fill="url(#ihB3Efe)" class="gkzo5sbtx"/><path fill="url(#iJise2s)" class="gkzo5sbtx"/><g filter="url(#iEcT02c)"><path class="akjc-abeb"/></g><g filter="url(#iOwEk1g)"><path fill="url(#i9nU91b)" class="bd3fat0fh"/><path fill="url(#ifnyG6d)" class="bd3fat0fh"/></g><g filter="url(#iKQ9qdc)"><path fill="url(#iAicMOX)" class="hsnafjbld"/></g><g filter="url(#iApUU1c)"><path fill="url(#iny7Hmc)" class="se1t3cc_z"/></g><path fill="url(#ijStJyn)" class="se1t3cc_z"/><defs><radialGradient id="isi4qAD" cx="0" cy="0" r="1" gradientTransform="rotate(117.411 8.245 10.174)scale(10.7792 15.8481)" gradientUnits="userSpaceOnUse"><stop class="d1gmbpsvf"/><stop offset="1" class="yt06xdhnw"/></radialGradient><radialGradient id="iQ1mNIb" cx="0" cy="0" r="1" gradientTransform="matrix(1.7749 -5.25 12.54346 4.24063 16.11 16.476)" gradientUnits="userSpaceOnUse"><stop class="bp7iblb8z"/><stop offset="1" class="shhfenbna"/></radialGradient><radialGradient id="iV9AAxc" cx="0" cy="0" r="1" gradientTransform="matrix(2.3125 -3.3125 7.52527 5.2535 19.885 16.57)" gradientUnits="userSpaceOnUse"><stop class="pywuu8shy"/><stop offset="1" class="vcv540btm"/></radialGradient><radialGradient id="iHvesle" cx="0" cy="0" r="1" gradientTransform="rotate(118.371 3.511 6.626)scale(4.07744 1.13569)" gradientUnits="userSpaceOnUse"><stop class="u01r0dbvg"/><stop offset="1" class="t3gcb7c_t"/></radialGradient><radialGradient id="idkFEne" cx="0" cy="0" r="1" gradientTransform="matrix(-.64062 1.9375 -1.31821 -.43586 11.65 8.883)" gradientUnits="userSpaceOnUse"><stop offset=".691" class="zb7xstuoh"/><stop offset="1" class="jx385lbqa"/></radialGradient><radialGradient id="iG8RLZc" cx="0" cy="0" r="1" gradientTransform="rotate(-35.146 31.719 -13.207)scale(12.5943 18.3026)" gradientUnits="userSpaceOnUse"><stop offset=".695" class="m5ublobmy"/><stop offset="1" class="xr8yokb7p"/></radialGradient><radialGradient id="icYZnJe" cx="0" cy="0" r="1" gradientTransform="matrix(.46875 1.42188 -.81374 .26827 20.713 7.898)" gradientUnits="userSpaceOnUse"><stop offset=".269" class="uu4l3fdyj"/><stop offset="1" class="j3io_pbeo"/></radialGradient><radialGradient id="itJrsyC" cx="0" cy="0" r="1" gradientTransform="matrix(.6875 1.5 -.8264 .37877 23.307 12.883)" gradientUnits="userSpaceOnUse"><stop class="um-di3lxj"/><stop offset="1" class="qq9ksubup"/></radialGradient><radialGradient id="iJR6idd" cx="0" cy="0" r="1" gradientTransform="matrix(-4.03125 0 0 -12.2293 23.358 24.383)" gradientUnits="userSpaceOnUse"><stop offset=".202" class="s59tlt20i"/><stop offset="1" class="dimomr5au"/></radialGradient><radialGradient id="i0YSB3d" cx="0" cy="0" r="1" gradientTransform="matrix(0 -10.4916 2.16348 0 25.197 29.98)" gradientUnits="userSpaceOnUse"><stop offset=".24" class="izw19gb1b"/><stop offset="1" class="pk_fxjb0k"/></radialGradient><radialGradient id="iu8Rwfe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -13.6896 .7187 0 23.264 29.98)" gradientUnits="userSpaceOnUse"><stop offset=".304" class="v7hn87gdb"/><stop offset="1" class="yfv60kbve"/></radialGradient><radialGradient id="iGhpVwC" cx="0" cy="0" r="1" gradientTransform="matrix(0 -9.94746 4.23507 0 6.75 29.98)" gradientUnits="userSpaceOnUse"><stop offset=".26" class="ydmi_gbdg"/><stop offset="1" class="j_s_0lsgx"/></radialGradient><radialGradient id="irWSoTc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.70333 0 0 -15.6939 8.842 29.616)" gradientUnits="userSpaceOnUse"><stop offset=".741" class="kolzjh1uk"/><stop offset="1" class="oqr8hmbdg"/></radialGradient><radialGradient id="iPHUAte" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.91012 -3.40129 0 16.134 23.035)" gradientUnits="userSpaceOnUse"><stop offset=".563" class="w4yfy3zsx"/><stop offset="1" class="b0hon_b8a"/></radialGradient><radialGradient id="iGs5oId" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.1875 .46252 0 18.389 30.195)" gradientUnits="userSpaceOnUse"><stop class="zj0khrbgv"/><stop offset="1" class="rndoiibli"/></radialGradient><radialGradient id="iCpmLAe" cx="0" cy="0" r="1" gradientTransform="matrix(0 9.70312 -1.55313 0 16.125 21.023)" gradientUnits="userSpaceOnUse"><stop offset=".006" class="g-uemq__p"/><stop offset=".907" class="ny-qt-bge"/></radialGradient><radialGradient id="i1ARehb" cx="0" cy="0" r="1" gradientTransform="rotate(122.782 2.566 11.926)scale(3.60548 4.04568)" gradientUnits="userSpaceOnUse"><stop class="hqfmlmg6f"/><stop offset="1" class="oyco1db5g"/></radialGradient><radialGradient id="irwsJcc" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.08638 -1.3984 0 13.429 23.2)" gradientUnits="userSpaceOnUse"><stop class="n-1p2p9pr"/><stop offset="1" class="v-e2dxczh"/></radialGradient><radialGradient id="iNdAWxe" cx="0" cy="0" r="1" gradientTransform="matrix(.8125 1.37956 -1.6894 .99499 19.17 15.847)" gradientUnits="userSpaceOnUse"><stop class="mgj3nfyon"/><stop offset="1" class="e6sjkybst"/></radialGradient><radialGradient id="ipvV6nd" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.15625 -4.85106 0 16.14 18.669)" gradientUnits="userSpaceOnUse"><stop offset=".519" class="dsfnryq2l"/><stop offset="1" class="e3skdu--u"/></radialGradient><radialGradient id="iHOiXmd" cx="0" cy="0" r="1" gradientTransform="matrix(-1 -.96876 2.18983 -2.26044 15.373 19.664)" gradientUnits="userSpaceOnUse"><stop class="ng9k9ab_a"/><stop offset="1" class="o-y5a1rmp"/></radialGradient><radialGradient id="i1Ucsgd" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.84296 -2.91711 0 16.11 16.639)" gradientUnits="userSpaceOnUse"><stop class="zcj0u6bne"/><stop offset="1" class="g1d8rwfyt"/></radialGradient><radialGradient id="iGJCkod" cx="0" cy="0" r="1" gradientTransform="matrix(-2.87842 1.04823 -1.9814 -5.44089 17.07 16.275)" gradientUnits="userSpaceOnUse"><stop offset=".731" class="it7s2bcbc"/><stop offset="1" class="zkxi7ub1c"/></radialGradient><radialGradient id="iEBlfzd" cx="0" cy="0" r="1" gradientTransform="matrix(2.48905 -1.13139 1.38138 3.03902 20.15 11.086)" gradientUnits="userSpaceOnUse"><stop offset=".572" class="qtr_-gj2q"/><stop offset=".905" class="yomsttbzk"/></radialGradient><radialGradient id="iOIzsce" cx="0" cy="0" r="1" gradientTransform="rotate(-20.298 40.756 -52.385)scale(1.30459)" gradientUnits="userSpaceOnUse"><stop offset=".71" class="iy3kcbc1e"/><stop offset="1" class="nfa0q6zfs"/></radialGradient><radialGradient id="iFjwfIS" cx="0" cy="0" r="1" gradientTransform="matrix(-1.07411 0 0 -1.02745 11.444 10.647)" gradientUnits="userSpaceOnUse"><stop offset=".415" class="e3owjub-t"/><stop offset="1" class="qb0464bzj"/></radialGradient><radialGradient id="i9blcne" cx="0" cy="0" r="1" gradientTransform="rotate(155.244 8.375 7.136)scale(7.16175 9.58588)" gradientUnits="userSpaceOnUse"><stop class="wa9cqx9pi"/><stop offset="1" class="m45oyzb-o"/></radialGradient><radialGradient id="iBL2ild" cx="0" cy="0" r="1" gradientTransform="matrix(-2.10973 1.11592 -.94678 -1.78996 18.01 10.807)" gradientUnits="userSpaceOnUse"><stop class="pb_rvfc5z"/><stop offset="1" class="v2k4g1b_w"/></radialGradient><radialGradient id="iuYnBkF" cx="0" cy="0" r="1" gradientTransform="matrix(.8369 -4.04513 5.13253 1.06187 13.931 16.892)" gradientUnits="userSpaceOnUse"><stop class="wrs_9y9vq"/><stop offset="1" class="z-gb6n28y"/></radialGradient><radialGradient id="ixW0Osc" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.12342 -7.83035 0 15.849 9.626)" gradientUnits="userSpaceOnUse"><stop offset=".619" class="qc4nwqgtj"/><stop offset=".989" class="pyv8a42je"/></radialGradient><radialGradient id="imhptec" cx="0" cy="0" r="1" gradientTransform="matrix(-5.42256 1.49953 -2.58173 -9.33598 16.738 11.766)" gradientUnits="userSpaceOnUse"><stop offset=".877" class="ud-bjxb5c"/><stop offset="1" class="a9dfe182j"/></radialGradient><radialGradient id="ilcedRP" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.15077 1.41231 0 18.412 9.691)" gradientUnits="userSpaceOnUse"><stop class="e0lgwbeaw"/><stop offset="1" class="y7n0ymbzx"/></radialGradient><radialGradient id="iqYeR6d" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.36 1.55865 0 14.192 9.778)" gradientUnits="userSpaceOnUse"><stop class="w2e_edyjl"/><stop offset="1" class="gsggv-b-p"/></radialGradient><radialGradient id="iyBsQzF" cx="0" cy="0" r="1" gradientTransform="matrix(-1.34695 0 0 -9.17099 21.206 11.179)" gradientUnits="userSpaceOnUse"><stop class="f902gfhfn"/><stop offset="1" class="jh40i5bvl"/></radialGradient><radialGradient id="iUtbsJd" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.85168 -5.88734 0 15.343 7.706)" gradientUnits="userSpaceOnUse"><stop offset=".492" class="x_vcunbec"/><stop offset="1" class="hqub0490e"/></radialGradient><radialGradient id="iqPcJ6d" cx="0" cy="0" r="1" gradientTransform="matrix(-.69746 -2.44974 1.40177 -.3991 16.895 11.905)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="itt9z7bbf"/><stop offset="1" class="eh2hzabiv"/></radialGradient><radialGradient id="iUN7BVc" cx="0" cy="0" r="1" gradientTransform="rotate(144.462 6.349 8.401)scale(1.57489 2.10945)" gradientUnits="userSpaceOnUse"><stop offset=".797" class="e6-lebcyw"/><stop offset="1" class="b8os9sbcy"/></radialGradient><radialGradient id="iZeD1ME" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.29049 0 18.292 10.05)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iWqPNsc" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 11.514 .644)scale(.37798 .52039)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iWbOR6c" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.2905 0 13.928 10.05)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iShnOIs" cx="0" cy="0" r="1" gradientTransform="matrix(-.00773 -.49366 .5934 -.0093 13.642 10.269)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iuby7lc" cx="0" cy="0" r="1" gradientTransform="matrix(-.31252 4.2792 -11.47135 -.83777 16.62 1.978)" gradientUnits="userSpaceOnUse"><stop offset=".267" class="ucx7riblp"/><stop offset="1" class="fxe3zh8pp"/></radialGradient><radialGradient id="ioURXze" cx="0" cy="0" r="1" gradientTransform="matrix(-4.625 0 0 -1.29228 20.932 4.289)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="x6mjrexfr"/><stop offset="1" class="pj095ubna"/></radialGradient><radialGradient id="iYP29td" cx="0" cy="0" r="1" gradientTransform="matrix(1.75085 0 0 2.31943 9.513 4.726)" gradientUnits="userSpaceOnUse"><stop class="a21-6lr8n"/><stop offset="1" class="ln2o6octk"/></radialGradient><radialGradient id="ipjoR9d" cx="0" cy="0" r="1" gradientTransform="rotate(-96.626 13.32 -3.901)scale(3.52078 14.6419)" gradientUnits="userSpaceOnUse"><stop offset=".064" class="q6gdl1i5d"/><stop offset=".47" class="i99yksbww"/><stop offset="1" class="viu_-ol9y"/></radialGradient><radialGradient id="ihB3Efe" cx="0" cy="0" r="1" gradientTransform="matrix(-4.4375 -.53896 .06546 -.53895 21.233 6.039)" gradientUnits="userSpaceOnUse"><stop class="qk2jzhbua"/><stop offset="1" class="nklj5u79d"/></radialGradient><radialGradient id="iJise2s" cx="0" cy="0" r="1" gradientTransform="matrix(-3.90624 -.5948 .09009 -.59163 21.233 7.04)" gradientUnits="userSpaceOnUse"><stop offset=".278" class="rgck1cbbg"/><stop offset="1" class="k3jqbac6c"/></radialGradient><radialGradient id="ifnyG6d" cx="0" cy="0" r="1" gradientTransform="rotate(-135 8.737 -1.244)scale(.62166 .97779)" gradientUnits="userSpaceOnUse"><stop offset=".382" class="hm8qkhptt"/><stop offset="1" class="xy9hyobea"/></radialGradient><radialGradient id="iny7Hmc" cx="0" cy="0" r="1" gradientTransform="matrix(-.9375 .96874 -1.00462 -.97222 16.717 4.023)" gradientUnits="userSpaceOnUse"><stop class="qga7xqb8q"/><stop offset="1" class="pp0fzgbhc"/></radialGradient><radialGradient id="ijStJyn" cx="0" cy="0" r="1" gradientTransform="matrix(.875 -.65625 1.11 1.48 16.014 4.523)" gradientUnits="userSpaceOnUse"><stop offset=".671" class="jsljpd_vj"/><stop offset="1" class="qga7xqb8q"/></radialGradient><filter id="iQJ5AQO" width="7.031" height="7.114" x="12.623" y="14.327" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2456" stdDeviation=".5"/></filter><filter id="iMpohFc" width="4.951" height="14.36" x="9.251" y="15.441" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2456" stdDeviation=".5"/></filter><filter id="i49qdkq" width="3.097" height="14.304" x="10.482" y="15.816" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.388235 0 0 0 0 0.356863 0 0 0 0 0.470588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2456"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.34902 0 0 0 0 0.290196 0 0 0 0 0.443137 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2456" result="effect2_innerShadow_4002_2456"/></filter><filter id="i04R72d" width="4.081" height="12.629" x="18.296" y="15.535" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2456" stdDeviation=".5"/></filter><filter id="iMYPbvc" width="3.042" height="14.123" x="18.599" y="15.847" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.403922 0 0 0 0 0.372549 0 0 0 0 0.541176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2456"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.380392 0 0 0 0 0.34902 0 0 0 0 0.552941 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2456" result="effect2_innerShadow_4002_2456"/></filter><filter id="iJIebJd" width="2.735" height="2.58" x="14.766" y="18.443" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.2 0 0 0 0 0.152941 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2456"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.2 0 0 0 0 0.152941 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2456" result="effect2_innerShadow_4002_2456"/></filter><filter id="i6IOCEC" width="3.151" height="1.346" x="20.668" y="19.615" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2456" stdDeviation=".1"/></filter><filter id="iGEL79b" width="2.881" height="1.03" x="20.868" y="19.71" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.823529 0 0 0 0 0.529412 0 0 0 0 0.192157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2456"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.980392 0 0 0 0 0.760784 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2456" result="effect2_innerShadow_4002_2456"/></filter><filter id="it74ace" width="3.318" height="3.218" x="9.816" y="9.038" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.768627 0 0 0 0 0.501961 0 0 0 0 0.160784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2456"/></filter><filter id="i89aUjg" width="3.218" height="3.468" x="19.329" y="8.788" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.901961 0 0 0 0 0.635294 0 0 0 0 0.180392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2456"/></filter><filter id="is631Wb" width="3.148" height="3.148" x="19.363" y="9.073" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2456" stdDeviation=".25"/></filter><filter id="iqyoJxc" width="2.648" height="2.648" x="10.12" y="9.323" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2456" stdDeviation=".125"/></filter><filter id="iXMCDbe" width="10.191" height="11.277" x="11.015" y="5.74" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.92549 0 0 0 0 0.529412 0 0 0 0 0.137255 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2456"/></filter><filter id="iBV6Ayb" width="2.877" height="3.682" x="14.509" y="9.642" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2456" stdDeviation=".25"/></filter><filter id="iKaHoge" width="2.377" height="3.182" x="14.922" y="9.753" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2456" stdDeviation=".125"/></filter><filter id="iBqwjYc" width="3.702" height="1.526" x="14.259" y="12.995" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2456" stdDeviation=".05"/></filter><filter id="iK4RtUc" width="3.001" height="1.285" x="17.052" y="9.242" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.141176 0 0 0 0 0.0862745 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2456"/></filter><filter id="iC9kp4c" width="3.001" height="1.285" x="12.167" y="9.242" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.133333 0 0 0 0 0.0784314 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2456"/></filter><filter id="iEtMDre" width=".786" height=".696" x="17.558" y="9.61" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2456" stdDeviation=".05"/></filter><filter id="iLqsTLe" width=".891" height=".913" x="18.398" y="9.685" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2456" stdDeviation=".1"/></filter><filter id="iJ1075b" width=".986" height="1.04" x="13.955" y="9.622" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2456" stdDeviation=".1"/></filter><filter id="ij9wz2c" width=".912" height=".704" x="13.2" y="9.602" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2456" stdDeviation=".05"/></filter><filter id="i5KeReY" width="10.9" height="2.77" x="10.689" y="6.11" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.286275 0 0 0 0 0.168627 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2456"/></filter><filter id="iEcT02c" width="4.831" height="2.64" x="13.724" y="2.861" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2456" stdDeviation=".125"/></filter><filter id="iOwEk1g" width="2.293" height="1.21" x="13.995" y="3.01" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.905882 0 0 0 0 0.65098 0 0 0 0 0.309804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2456"/></filter><filter id="iKQ9qdc" width="2.298" height="1.22" x="16.077" y="3" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.960784 0 0 0 0 0.752941 0 0 0 0 0.317647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2456"/></filter><filter id="iApUU1c" width="1.63" height="1.63" x="15.429" y="3.51" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.698039 0 0 0 0 0.4 0 0 0 0 0.121569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2456"/></filter><linearGradient id="i3k8mtc" x1="16.134" x2="16.134" y1="15.48" y2="29.98" gradientUnits="userSpaceOnUse"><stop class="ka-y4km4d"/><stop offset="1" class="odfguq8mk"/></linearGradient><linearGradient id="ilCO5Yb" x1="9.269" x2="7.077" y1="27.797" y2="27.797" gradientUnits="userSpaceOnUse"><stop offset=".124" class="m9kzfz-8h"/><stop offset="1" class="h_4try76x"/></linearGradient><linearGradient id="isNKkbc" x1="16.639" x2="16.639" y1="30.445" y2="28.976" gradientUnits="userSpaceOnUse"><stop class="cuwamcc7w"/><stop offset="1" class="e9vdenjit"/></linearGradient><linearGradient id="i3TxftV" x1="19.201" x2="17.295" y1="26.539" y2="26.539" gradientUnits="userSpaceOnUse"><stop class="hi4tb8d4g"/><stop offset="1" class="l6siijbzt"/></linearGradient><linearGradient id="iKhME0b" x1="13.429" x2="13.429" y1="29.351" y2="15.816" gradientUnits="userSpaceOnUse"><stop class="gxm502ben"/><stop offset="1" class="qg2z49_rr"/></linearGradient><linearGradient id="i77gfyd" x1="13.429" x2="13.429" y1="29.669" y2="23.336" gradientUnits="userSpaceOnUse"><stop offset=".306" class="ke9tt_b-u"/><stop offset="1" class="w784rnm9d"/></linearGradient><linearGradient id="ipQ6fvd" x1="18.849" x2="19.858" y1="20.726" y2="20.726" gradientUnits="userSpaceOnUse"><stop class="olptj6tus"/><stop offset="1" class="d-3cltoww"/></linearGradient><linearGradient id="iiB6oye" x1="13.717" x2="15.311" y1="16.539" y2="18.586" gradientUnits="userSpaceOnUse"><stop class="sv13rb7yi"/><stop offset="1" class="k5-d0pb7l"/></linearGradient><linearGradient id="ivDk0Kd" x1="18.576" x2="17.233" y1="16.476" y2="18.226" gradientUnits="userSpaceOnUse"><stop class="sv13rb7yi"/><stop offset="1" class="k5-d0pb7l"/></linearGradient><linearGradient id="i46Jevc" x1="16.125" x2="16.125" y1="19.205" y2="20.902" gradientUnits="userSpaceOnUse"><stop offset=".006" class="bf4zukp8q"/><stop offset="1" class="i_g168btd"/></linearGradient><linearGradient id="ir3efbD" x1="21.219" x2="23.014" y1="20.055" y2="20.69" gradientUnits="userSpaceOnUse"><stop class="uns_kgbkm"/><stop offset="1" class="vglr3ibxi"/></linearGradient><linearGradient id="ivzdGcd" x1="9.816" x2="12.775" y1="10.734" y2="10.734" gradientUnits="userSpaceOnUse"><stop class="o-5xddb6x"/><stop offset="1" class="h11_utkon"/></linearGradient><linearGradient id="iv4Q3qd" x1="16.11" x2="16.11" y1="12.685" y2="10.003" gradientUnits="userSpaceOnUse"><stop class="um-di3lxj"/><stop offset="1" class="fkdj3ejgt"/></linearGradient><linearGradient id="ikvSbkm" x1="15.064" x2="15.918" y1="11.923" y2="12.027" gradientUnits="userSpaceOnUse"><stop class="enxo4ub-d"/><stop offset="1" class="vsluyubzo"/></linearGradient><linearGradient id="inHpvye" x1="16.11" x2="16.11" y1="12.777" y2="12.167" gradientUnits="userSpaceOnUse"><stop class="kpdurub6t"/><stop offset="1" class="qwjswe-rp"/></linearGradient><linearGradient id="i03sNUc" x1="16.11" x2="16.11" y1="10.003" y2="10.987" gradientUnits="userSpaceOnUse"><stop class="lnm9oub8a"/><stop offset="1" class="r8nnw7bdp"/></linearGradient><linearGradient id="ilurGte" x1="16.189" x2="16.189" y1="12.751" y2="12.612" gradientUnits="userSpaceOnUse"><stop class="b8os9sbcy"/><stop offset="1" class="e6-lebcyw"/></linearGradient><linearGradient id="isbe8jz" x1="15.381" x2="15.834" y1="14.254" y2="13.383" gradientUnits="userSpaceOnUse"><stop class="q0k9-hbaq"/><stop offset="1" class="mhbvyzb9x"/></linearGradient><linearGradient id="iYM2bzd" x1="19.07" x2="18.757" y1="10.104" y2="10.297" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ihOLrLb" x1="14.672" x2="14.358" y1="10.104" y2="10.297" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i09GSsc" x1="17.483" x2="11.264" y1="6.82" y2="6.82" gradientUnits="userSpaceOnUse"><stop class="a_cf-ibqz"/><stop offset="1" class="ayzgumbov"/></linearGradient><linearGradient id="i9nU91b" x1="16.225" x2="14.647" y1="4.14" y2="4.14" gradientUnits="userSpaceOnUse"><stop class="whje1li3v"/><stop offset="1" class="u3hfg3htm"/></linearGradient><linearGradient id="iAicMOX" x1="18.217" x2="16.731" y1="3.148" y2="4.14" gradientUnits="userSpaceOnUse"><stop class="xgphulxrx"/><stop offset="1" class="cit_-lbel"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-pilot" /></template>
<style>
.a_cf-ibqz {
  stop-color: var(--svg-color--e3ac3f, #E3AC3F);
}

.a21-6lr8n {
  stop-color: var(--svg-color--5d5a62, #5D5A62);
}

.a4rixsbmw {
  fill: var(--svg-color--eb8b29, #EB8B29);
  d: path("m15.718 10.424l-.684 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.53-1.7c-.114-.376-.494-.376-.613 0");
}

.a9dfe182j {
  stop-color: var(--svg-color--d4993e, #D4993E);
}

.akjc-abeb {
  fill: var(--svg-color--382534, #382534);
  d: path("M16.927 4.33h.633a.2.2 0 0 0 .18-.11l.55-.95c.04-.07-.01-.16-.09-.16h-1.4a.2.2 0 0 0-.18.11l-.275.476a.8.8 0 0 0-.415.005l-.272-.47a.2.2 0 0 0-.18-.11h-1.4c-.08 0-.13.09-.09.16l.54.94c.04.07.1.11.18.11h.66a.79.79 0 1 0 1.559 0");
}

.ama8_rb1i {
  d: path("M15.651 21.023a.25.25 0 0 0-.247.212L14.07 29.98h4.12l-1.33-8.744a.25.25 0 0 0-.247-.213z");
}

.aq7surbst {
  cx: 13.657px;
  cy: 9.954px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.389px;
  ry: 0.197px;
}

.ayzgumbov {
  stop-color: var(--svg-color--b88538, #B88538);
}

.b0hon_b8a {
  stop-color: var(--svg-color--a9a0b2, #A9A0B2);
}

.b8os9sbcy {
  stop-color: var(--svg-color--e2802f, #E2802F);
}

.bd3fat0fh {
  d: path("M16.179 4.22h-1.4a.2.2 0 0 1-.18-.11l-.54-.94c-.04-.07.01-.16.09-.16h1.4a.2.2 0 0 1 .18.11l.55.95c.03.06-.02.15-.1.15");
}

.bf4zukp8q {
  stop-color: var(--svg-color--543555, #543555);
}

.bp7iblb8z {
  stop-color: var(--svg-color--803f04, #803F04);
}

.bpkuhdbht {
  fill: var(--svg-color--8f809c, #8F809C);
  d: path("M16.139 15.327h-2.516v4.74c0 .31.335.49.567.29l1.949-1.67l1.95 1.67c.231.2.566.02.566-.29v-4.74z");
}

.brcdblhuw {
  d: path("M16.11 18.482c1.79-.788 1.932-1.316 1.92-1.7v-.99h-3.84v.99c-.013.384.224.97 1.92 1.7");
}

.c1erwxb4g {
  d: path("M16.139 15.48c-6.07 0-11 4.92-11 11v3.5h21.99v-3.5c0-6.08-4.92-11-10.99-11");
}

.c7o726bgx {
  d: path("M16.14 15.263h-2.71v4.74c0 .31.36.49.61.29l2.1-1.67l2.1 1.67c.25.2.61.02.61-.29v-4.74z");
}

.ci-y5kwyd {
  d: path("M14.741 10.36c0-.288-.234-.48-.298-.538l-.288.278l.178.361z");
}

.cit_-lbel {
  stop-color: var(--svg-color--e09037, #E09037);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cuwamcc7w {
  stop-color: var(--svg-color--c2aadc, #C2AADC);
}

.d-3cltoww {
  stop-color: var(--svg-color--625990, #625990);
}

.d1gmbpsvf {
  stop-color: var(--svg-color--ffaa2d, #FFAA2D);
}

.dimomr5au {
  stop-color: var(--svg-color--6b629a, #6B629A);
  stop-opacity: 0;
}

.dn19lhnml {
  d: path("M20.938 11.721a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.dsfnryq2l {
  stop-color: var(--svg-color--c0aac0, #C0AAC0);
}

.e0lgwbeaw {
  stop-color: var(--svg-color--ffbb31, #FFBB31);
}

.e3owjub-t {
  stop-color: var(--svg-color--d67923, #D67923);
  stop-opacity: 0;
}

.e3skdu--u {
  stop-color: var(--svg-color--928392, #928392);
}

.e6-lebcyw {
  stop-color: var(--svg-color--e2802f, #E2802F);
  stop-opacity: 0;
}

.e6sjkybst {
  stop-color: var(--svg-color--504069, #504069);
  stop-opacity: 0;
}

.e9vdenjit {
  stop-color: var(--svg-color--c2aadc, #C2AADC);
  stop-opacity: 0;
}

.eh2hzabiv {
  stop-color: var(--svg-color--ffe848, #FFE848);
  stop-opacity: 0;
}

.enxo4ub-d {
  stop-color: var(--svg-color--f8a322, #F8A322);
}

.f902gfhfn {
  stop-color: var(--svg-color--ffda39, #FFDA39);
}

.fa1pvobka {
  d: path("M13.429 15.816q-.691.176-1.345.436l-.035.018l-1.27 2.69c-.09.19.05.41.26.41h1.05c.24 0 .35.29.19.45l-1.36 1.33c-.26.26-.36.65-.23 1l2.73 7.82h.01z");
}

.fkdj3ejgt {
  stop-color: var(--svg-color--f8c73f, #F8C73F);
}

.fp1nwtbxe {
  d: path("M11.425 12.256a1.61 1.61 0 1 0 0-3.218a1.61 1.61 0 0 0 0 3.218");
}

.ft5dv1b6b {
  fill: none;
}

.fxe3zh8pp {
  stop-color: var(--svg-color--3b3541, #3B3541);
}

.g-uemq__p {
  stop-color: var(--svg-color--59416c, #59416C);
}

.g1d8rwfyt {
  stop-color: var(--svg-color--de9f2d, #DE9F2D);
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.ghe7qfbhe {
  fill: var(--svg-color--473a60, #473A60);
  d: path("M23.38 19.815h-.61c-.22 0-.42.13-.516.33c-.01.019-.038.019-.038 0a.57.57 0 0 0-.516-.33h-.592c-.124 0-.23.09-.239.22c-.01.129.096.249.22.249h.152c.18 0 .18.079.213.15a.34.34 0 0 0 .306.199h.238l.54.129c.133 0 .46-.1.518-.22l.086-.199c.02-.04.057-.06.096-.06h.143c.124 0 .229-.09.238-.219c-.009-.14-.114-.249-.238-.249");
}

.gkzo5sbtx {
  d: path("M16.09 5.5h.1c.39 0 2.27.02 4.56.51c.49.1.84.53.84 1.03c-2.92-.76-5.45-.73-5.45-.73s-2.53-.03-5.45.73c0-.5.35-.93.84-1.03c2.29-.48 4.16-.51 4.56-.51");
}

.gsggv-b-p {
  stop-color: var(--svg-color--f09429, #F09429);
  stop-opacity: 0;
}

.gxm502ben {
  stop-color: var(--svg-color--605388, #605388);
}

.h_4try76x {
  stop-color: var(--svg-color--524c6a, #524C6A);
  stop-opacity: 0;
}

.h0_ab_jhn {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M17.252 10.078c.266-.467.67-.836 1.538-.836c.38 0 .747.106 1.073.37c.268.216.232.494.024.598l-.556.318c-.652-.21-1.372-.24-2.079-.45");
}

.h11_utkon {
  stop-color: var(--svg-color--b96201, #B96201);
}

.hi4tb8d4g {
  stop-color: var(--svg-color--80728b, #80728B);
}

.hm8qkhptt {
  stop-color: var(--svg-color--c47c25, #C47C25);
}

.hqfmlmg6f {
  stop-color: var(--svg-color--483555, #483555);
}

.hqub0490e {
  stop-color: var(--svg-color--e17e2b, #E17E2B);
  stop-opacity: 0;
}

.hsnafjbld {
  d: path("M16.232 4.22h1.4a.2.2 0 0 0 .18-.11l.55-.95c.04-.07-.01-.16-.09-.16h-1.4a.2.2 0 0 0-.18.11l-.55.95c-.04.07.01.16.09.16");
}

.i_g168btd {
  stop-color: var(--svg-color--483a53, #483A53);
}

.i99yksbww {
  stop-color: var(--svg-color--4f3e5f, #4F3E5F);
}

.igf0ujbup {
  d: path("M11.023 9.384h.012l-.01-.265l-.01-.306c.02-.949.574-1.316.81-1.439l.051-.02l.052-.02a2.3 2.3 0 0 0 1.19-1.235l.081-.194a.264.264 0 0 1 .462-.05a3.86 3.86 0 0 0 3.189 1.672h3.22c.18 0 1.082.088 1.136 1.333l-.119 3.073c-.123 2.802-2.312 4.684-4.983 4.684c-2.672 0-4.86-1.882-4.983-4.684z");
}

.it7s2bcbc {
  stop-color: var(--svg-color--db992f, #DB992F);
  stop-opacity: 0;
}

.itt9z7bbf {
  stop-color: var(--svg-color--ffe848, #FFE848);
}

.iy3kcbc1e {
  stop-color: var(--svg-color--ffba25, #FFBA25);
  stop-opacity: 0;
}

.izw19gb1b {
  stop-color: var(--svg-color--7d72a2, #7D72A2);
}

.j_s_0lsgx {
  stop-color: var(--svg-color--524a68, #524A68);
}

.j0s8y6b3n {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.501 9.301c.653 0 1.205.45 1.355 1.059a.274.274 0 0 1-.268.34h-2.23a.23.23 0 0 1-.228-.271A1.4 1.4 0 0 1 18.501 9.3");
}

.j3io_pbeo {
  stop-color: var(--svg-color--eb931d, #EB931D);
  stop-opacity: 0;
}

.jh40i5bvl {
  stop-color: var(--svg-color--ffda39, #FFDA39);
  stop-opacity: 0;
}

.jsljpd_vj {
  stop-color: var(--svg-color--fcbb51, #FCBB51);
  stop-opacity: 0;
}

.jx385lbqa {
  stop-color: var(--svg-color--d8711c, #D8711C);
  stop-opacity: 0;
}

.k3jqbac6c {
  stop-color: var(--svg-color--eba026, #EBA026);
  stop-opacity: 0;
}

.k5-d0pb7l {
  stop-color: var(--svg-color--987a8d, #987A8D);
  stop-opacity: 0;
}

.k9db2z3ho {
  d: path("m14.866 19.64l1.267-1.097l1.268 1.074l-.546 1.265a.24.24 0 0 1-.216.141h-1.022a.24.24 0 0 1-.216-.14z");
}

.ka-y4km4d {
  stop-color: var(--svg-color--584c78, #584C78);
}

.kdu09gbus {
  d: path("M11.444 11.721a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.ke9tt_b-u {
  stop-color: var(--svg-color--5d4f84, #5D4F84);
}

.ko4xv101l {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M14.969 10.078c-.266-.467-.67-.836-1.538-.836c-.38 0-.747.106-1.073.37c-.269.216-.232.494-.024.598l.556.318c.652-.21 1.372-.24 2.079-.45");
}

.kolzjh1uk {
  stop-color: var(--svg-color--6e638c, #6E638C);
  stop-opacity: 0;
}

.kpdurub6t {
  stop-color: var(--svg-color--e48538, #E48538);
}

.ktwqtybad {
  cx: 13.657px;
  cy: 9.954px;
  rx: 0.389px;
  ry: 0.197px;
}

.kxz3h33un {
  d: path("M16.14 6.31s-2.53-.03-5.45.73l.4.47c.73.87 1.81 1.37 2.95 1.37h4.19c1.14 0 2.22-.5 2.96-1.37l.4-.47c-2.92-.76-5.45-.73-5.45-.73");
}

.l-h8a8bdf {
  fill: var(--svg-color--8a004f, #8A004F);
  d: path("M16.11 13.559a3 3 0 0 1-1.421-.345c-.14-.073-.292.089-.203.22a1.932 1.932 0 0 0 3.25 0c.088-.136-.063-.293-.204-.22c-.411.22-.896.345-1.422.345");
}

.l6siijbzt {
  stop-color: var(--svg-color--80728b, #80728B);
  stop-opacity: 0;
}

.ldk8wmbpo {
  fill: var(--svg-color--000, #000);
  d: path("M14.437 10.465a.51.51 0 0 0-.51-.51a.51.51 0 0 0-.455.745h.905a.5.5 0 0 0 .06-.235");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.ln2o6octk {
  stop-color: var(--svg-color--3a3340, #3A3340);
  stop-opacity: 0;
}

.lnm9oub8a {
  stop-color: var(--svg-color--eda737, #EDA737);
}

.m45oyzb-o {
  stop-color: var(--svg-color--eb9235, #EB9235);
}

.m5ublobmy {
  stop-color: var(--svg-color--ffd132, #FFD132);
  stop-opacity: 0;
}

.m9kzfz-8h {
  stop-color: var(--svg-color--443a60, #443A60);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mgj3nfyon {
  stop-color: var(--svg-color--504069, #504069);
}

.mhbvyzb9x {
  stop-color: var(--svg-color--feac35, #FEAC35);
  stop-opacity: 0;
}

.mlltz6o2j {
  fill: var(--svg-color--44375d, #44375D);
  d: path("m20.19 20.458l.443 1.05c.202.26.272.65.178 1.01l-1.295 4.646l-.22-10.446l.09-.183q.507.174.989.423l.98 2.64c.07.19-.04.41-.202.41h-.816c-.187 0-.28.28-.148.45");
}

.n-1p2p9pr {
  stop-color: var(--svg-color--615589, #615589);
}

.nfa0q6zfs {
  stop-color: var(--svg-color--ffba25, #FFBA25);
}

.ng9k9ab_a {
  stop-color: var(--svg-color--d0c1d9, #D0C1D9);
}

.nklj5u79d {
  stop-color: var(--svg-color--ffcf55, #FFCF55);
  stop-opacity: 0;
}

.nm038jbsl {
  fill: var(--svg-color--44375d, #44375D);
  d: path("M12.929 16.441c-.46.117-.364.099-.8.271c-.54.784-1.546 2.199-1.85 2.873c-.09.19.05.41.26.41l1.18-.174c.24 0 .35.29.19.45l-1.37 1.196c-.26.26-.36.65-.23 1l2.894 6.334z");
}

.nwn820bbw {
  fill: var(--svg-color--000, #000);
  d: path("M17.783 10.466a.51.51 0 0 1 .511-.512a.51.51 0 0 1 .455.747h-.905a.46.46 0 0 1-.06-.236");
}

.ny-qt-bge {
  stop-color: var(--svg-color--3a3045, #3A3045);
}

.o-5xddb6x {
  stop-color: var(--svg-color--e79b27, #E79B27);
}

.o-y5a1rmp {
  stop-color: var(--svg-color--d0c1d9, #D0C1D9);
  stop-opacity: 0;
}

.o3d2umjfs {
  d: path("m19.999 19.77l1.36 1.33c.26.26.35.65.23 1.01l-2.74 7.86V16.03l.117-.183q.653.173 1.272.423l1.261 2.64c.09.19-.05.41-.26.41h-1.05c-.24 0-.36.28-.19.45");
}

.o5lkxgbrw {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.228 9.762c.064.085-.069.188-.22.301s-.263.193-.327.108c-.063-.085.008-.246.159-.359c.15-.112.325-.135.388-.05");
}

.o5lt0ibcc {
  d: path("m15.728 10.286l-.531 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.531-1.7c-.114-.377-.646-.377-.765 0");
}

.o7egzrbpm {
  d: path("M9.014 29.98V18.1a10.97 10.97 0 0 0-3.875 8.38v3.5z");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.odfguq8mk {
  stop-color: var(--svg-color--5a4b85, #5A4B85);
}

.olptj6tus {
  stop-color: var(--svg-color--56466e, #56466E);
}

.oqr8hmbdg {
  stop-color: var(--svg-color--6e638c, #6E638C);
}

.oyco1db5g {
  stop-color: var(--svg-color--483555, #483555);
  stop-opacity: 0;
}

.p77532b6v {
  d: path("M23.264 18.103V29.98h3.865v-3.5c0-3.357-1.5-6.36-3.865-8.377");
}

.pb_rvfc5z {
  stop-color: var(--svg-color--ffe842, #FFE842);
}

.pj095ubna {
  stop-color: var(--svg-color--635870, #635870);
  stop-opacity: 0;
}

.pk_fxjb0k {
  stop-color: var(--svg-color--6e658c, #6E658C);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pl0aa6b6u {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M16.11 13.559a3 3 0 0 1-1.421-.345c-.14-.073-.292.089-.203.22a1.932 1.932 0 0 0 3.25 0c.088-.136-.063-.293-.204-.22c-.411.22-.896.345-1.422.345Z");
}

.pp0fzgbhc {
  stop-color: var(--svg-color--ce8634, #CE8634);
}

.pyv8a42je {
  stop-color: var(--svg-color--bb7233, #BB7233);
}

.pywuu8shy {
  stop-color: var(--svg-color--8b550b, #8B550B);
}

.q0k9-hbaq {
  stop-color: var(--svg-color--feac35, #FEAC35);
}

.q6gdl1i5d {
  stop-color: var(--svg-color--695978, #695978);
}

.qb0464bzj {
  stop-color: var(--svg-color--d67923, #D67923);
}

.qc4nwqgtj {
  stop-color: var(--svg-color--ffb230, #FFB230);
  stop-opacity: 0;
}

.qg2z49_rr {
  stop-color: var(--svg-color--564973, #564973);
}

.qga7xqb8q {
  stop-color: var(--svg-color--fcbb51, #FCBB51);
}

.qk2jzhbua {
  stop-color: var(--svg-color--ffcf55, #FFCF55);
}

.qq9ksubup {
  stop-color: var(--svg-color--ffc134, #FFC134);
  stop-opacity: 0;
}

.qtr_-gj2q {
  stop-color: var(--svg-color--ffc531, #FFC531);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qwjswe-rp {
  stop-color: var(--svg-color--e48538, #E48538);
  stop-opacity: 0;
}

.r8nnw7bdp {
  stop-color: var(--svg-color--eda737, #EDA737);
  stop-opacity: 0;
}

.rgck1cbbg {
  stop-color: var(--svg-color--eba026, #EBA026);
}

.rndoiibli {
  stop-color: var(--svg-color--ad91ca, #AD91CA);
  stop-opacity: 0;
}

.s59tlt20i {
  stop-color: var(--svg-color--7d77a7, #7D77A7);
}

.se1t3cc_z {
  d: path("M16.219 5.14a.79.79 0 1 0 0-1.58a.79.79 0 0 0 0 1.58");
}

.shhfenbna {
  stop-color: var(--svg-color--d16a21, #D16A21);
  stop-opacity: 0;
}

.srguc_odb {
  d: path("M18.295 9.573a.892.892 0 0 1 .86 1.128H17.43a.896.896 0 0 1 .864-1.128");
}

.sv13rb7yi {
  stop-color: var(--svg-color--68565a, #68565A);
}

.t3gcb7c_t {
  stop-color: var(--svg-color--d3923d, #D3923D);
  stop-opacity: 0;
}

.tow72abrm {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.72 9.301c-.654 0-1.205.45-1.356 1.059c-.044.174.09.34.268.34h2.231a.23.23 0 0 0 .228-.271A1.4 1.4 0 0 0 13.719 9.3");
}

.u01r0dbvg {
  stop-color: var(--svg-color--d3923d, #D3923D);
}

.u3hfg3htm {
  stop-color: var(--svg-color--e2a23d, #E2A23D);
}

.ucx7riblp {
  stop-color: var(--svg-color--5d4c6d, #5D4C6D);
}

.ud-bjxb5c {
  stop-color: var(--svg-color--d4993e, #D4993E);
  stop-opacity: 0;
}

.um-di3lxj {
  stop-color: var(--svg-color--ffc134, #FFC134);
}

.uns_kgbkm {
  stop-color: var(--svg-color--e3ab3f, #E3AB3F);
}

.uu4l3fdyj {
  stop-color: var(--svg-color--eb931d, #EB931D);
}

.v-e2dxczh {
  stop-color: var(--svg-color--615589, #615589);
  stop-opacity: 0;
}

.v2k4g1b_w {
  stop-color: var(--svg-color--ffe842, #FFE842);
  stop-opacity: 0;
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.v7hn87gdb {
  stop-color: var(--svg-color--4f4175, #4F4175);
}

.vcv540btm {
  stop-color: var(--svg-color--ec8f26, #EC8F26);
  stop-opacity: 0;
}

.vglr3ibxi {
  stop-color: var(--svg-color--ecac40, #ECAC40);
}

.viu_-ol9y {
  stop-color: var(--svg-color--362c38, #362C38);
}

.vjmrt9beo {
  fill: var(--svg-color--e28527, #E28527);
  d: path("M11.444 11.721a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.vsluyubzo {
  stop-color: var(--svg-color--f8a322, #F8A322);
  stop-opacity: 0;
}

.vw7_gxbgg {
  d: path("M18.84 16.09h-5.41v13.89h5.41z");
}

.w2e_edyjl {
  stop-color: var(--svg-color--f09429, #F09429);
}

.w4yfy3zsx {
  stop-color: var(--svg-color--c7bbd0, #C7BBD0);
}

.w784rnm9d {
  stop-color: var(--svg-color--5d4f84, #5D4F84);
  stop-opacity: 0;
}

.wa9cqx9pi {
  stop-color: var(--svg-color--ffe644, #FFE644);
}

.whje1li3v {
  stop-color: var(--svg-color--d19b3e, #D19B3E);
}

.wrs_9y9vq {
  stop-color: var(--svg-color--e4883f, #E4883F);
}

.wt2my6bsb {
  d: path("M18.228 9.762c.064.085-.069.188-.22.301s-.263.193-.327.108c-.063-.085.008-.246.159-.359c.15-.112.325-.135.388-.05");
}

.x_vcunbec {
  stop-color: var(--svg-color--e17e2b, #E17E2B);
}

.x6mjrexfr {
  stop-color: var(--svg-color--635870, #635870);
}

.x9y52dn2t {
  fill: var(--svg-color--ffca38, #FFCA38);
  d: path("M20.938 11.721a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.xgphulxrx {
  stop-color: var(--svg-color--e6ac3e, #E6AC3E);
}

.xmvyn4b4c {
  d: path("M21.88 3.53c-2.66-1.66-5.7-1.55-5.74-1.55S13 1.97 10.4 3.52c-1 .6-1.19 1.96-.39 2.8l.68.72h10.9l.68-.72c.8-.83.6-2.18-.39-2.79");
}

.xr8yokb7p {
  stop-color: var(--svg-color--ffd132, #FFD132);
}

.xsdatwbtp {
  d: path("M19.09 10.347a.84.84 0 0 0-.232-.462l-.26.285l.117.228z");
}

.xy9hyobea {
  stop-color: var(--svg-color--c47c25, #C47C25);
  stop-opacity: 0;
}

.y7n0ymbzx {
  stop-color: var(--svg-color--ffbb31, #FFBB31);
  stop-opacity: 0;
}

.ydmi_gbdg {
  stop-color: var(--svg-color--5a4b81, #5A4B81);
}

.yfv60kbve {
  stop-color: var(--svg-color--514476, #514476);
  stop-opacity: 0;
}

.yolj3cc6n {
  d: path("M13.926 9.573a.893.893 0 0 0-.86 1.128h1.724a1 1 0 0 0 .033-.236a.9.9 0 0 0-.897-.892");
}

.yomsttbzk {
  stop-color: var(--svg-color--ffe549, #FFE549);
}

.yt06xdhnw {
  stop-color: var(--svg-color--da7025, #DA7025);
}

.z-gb6n28y {
  stop-color: var(--svg-color--e4883f, #E4883F);
  stop-opacity: 0;
}

.zb7xstuoh {
  stop-color: var(--svg-color--d8711c, #D8711C);
}

.zbniv-bew {
  d: path("M10.77 6.686h10.68c.092.576.528.993.98 1.424c.285.274.577.553.792.882c.625.958.461 1.953.176 2.938c-.077.263-.072.493 0 .636c.133.32.285.785.285 1.296a3.24 3.24 0 0 1-3.246 3.246h-8.654a3.24 3.24 0 0 1-3.246-3.246c0-.51.153-.976.286-1.296c.071-.143.055-.445 0-.636c-.286-.985-.45-1.98.176-2.938c.214-.33.506-.608.792-.882c.452-.431.888-.848.98-1.424");
}

.zcj0u6bne {
  stop-color: var(--svg-color--ca7c30, #CA7C30);
}

.zj0khrbgv {
  stop-color: var(--svg-color--ad91ca, #AD91CA);
}

.zkg4d7d0r {
  d: path("M23.499 19.76h-.64c-.23 0-.44.13-.54.33c-.01.02-.04.02-.04 0c-.1-.2-.31-.33-.54-.33h-.62c-.13 0-.24.09-.25.22s.1.25.23.25h.16c.04 0 .08.02.1.06l.09.2c.06.12.18.2.32.2h1.07c.14 0 .26-.08.32-.2l.09-.2a.11.11 0 0 1 .1-.06h.15c.13 0 .24-.09.25-.22c-.01-.14-.12-.25-.25-.25");
}

.zkxi7ub1c {
  stop-color: var(--svg-color--915d29, #915D29);
}

.zx54blbrh {
  d: path("M20.938 12.256a1.61 1.61 0 1 0 0-3.218a1.61 1.61 0 0 0 0 3.218");
}

</style>
