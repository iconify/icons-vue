<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#ieTKKyb)" clip-rule="evenodd" class="v-p5omnxm"/><path fill="url(#ix6Vdgc)" clip-rule="evenodd" class="bqwscm-5z"/><g filter="url(#i089wFX)"><path fill="url(#iyo2Nte)" class="mxe5l-b8x"/><path fill="url(#i8SL0bb)" class="mxe5l-b8x"/></g><path fill="url(#imh6k8d)" class="qwmps2bvc"/><path fill="url(#ivkLTrd)" class="qwmps2bvc"/><g filter="url(#iImjL4s)"><path class="s9hud2bil"/></g><path fill="url(#iRHRrrd)" class="qqq97ebkd"/><path fill="url(#i4r1ieb)" class="qqq97ebkd"/><path fill="url(#i5EgdJb)" class="qqq97ebkd"/><path fill="url(#iXY8vte)" class="m8zsuwtqz"/><path fill="url(#iVX833c)" class="m8zsuwtqz"/><path fill="url(#iagd0tc)" class="m8zsuwtqz"/><path fill="url(#iLtCeJd)" class="gqrdhsbjl"/><path fill="url(#iXawENb)" class="gqrdhsbjl"/><path fill="url(#igaeHWd)" class="gqrdhsbjl"/><path class="h5ql4kb6g"/><path fill="url(#iVh47be)" class="ndxr44g2h"/><path fill="url(#i1szBMb)" class="ndxr44g2h"/><path fill="url(#iovxGFb)" class="ndxr44g2h"/><g filter="url(#iTkZEzd)"><path class="mbv-embne"/><path fill="url(#iyUX1Jd)" class="vvb767b_n"/><path fill="url(#iOLZ0cW)" class="vvb767b_n"/><path fill="url(#iOzeqFe)" class="vvb767b_n"/></g><g filter="url(#iuyJREb)"><path fill="url(#ivci6pe)" class="ha61p4glz"/></g><g filter="url(#igZxv9U)"><path fill="url(#i01NKmc)" class="xm_vkhc8e"/><path fill="url(#iqnViuc)" class="xm_vkhc8e"/></g><g filter="url(#iNPkrRl)"><path fill="url(#iFbbife)" class="d56lu3b4e"/><path fill="url(#iNNdesb)" class="d56lu3b4e"/></g><path fill="url(#i0wzcic)" class="d56lu3b4e"/><path clip-rule="evenodd" class="i19nx45cf"/><path fill="url(#itYWULc)" clip-rule="evenodd" class="y-yhajzcm"/><path clip-rule="evenodd" class="ob_jzvllb"/><path fill="url(#i06IHtd)" clip-rule="evenodd" class="md5c6jb0j"/><path clip-rule="evenodd" class="plwjkgbcu"/><path fill="url(#ikm6jCe)" clip-rule="evenodd" class="w--l981bs"/><path clip-rule="evenodd" class="m5zbi1oey"/><path fill="url(#isRiwAI)" clip-rule="evenodd" class="k5is8qewn"/><path clip-rule="evenodd" class="j51x2pblc"/><path fill="url(#iBuXhqd)" clip-rule="evenodd" class="mriigjb_g"/><path clip-rule="evenodd" class="obgxu4wfp"/><path fill="url(#i13XCdb)" clip-rule="evenodd" class="fdw6rbsah"/><path clip-rule="evenodd" class="zhncmkv5o"/><path fill="url(#i4Pdzdb)" clip-rule="evenodd" class="op0wkpb0r"/><path fill="url(#i7ixhhM)" clip-rule="evenodd" class="g3wgqm9be"/><path fill="url(#iQqVLLb)" clip-rule="evenodd" class="g3wgqm9be"/><g filter="url(#iVyO6UU)"><path class="o4k-cfqdc"/></g><g filter="url(#ih0sv0d)"><path stroke="url(#i6vmdXd)" class="eevmxtb1v"/></g><g filter="url(#ieZG7Nb)"><path class="fd18zdsfu"/></g><g filter="url(#iPaJWed)"><path stroke="url(#ijCJzkR)" class="rmafx6bat"/></g><g filter="url(#i9Qif6c)"><path class="pdh31bxtz"/></g><g filter="url(#iKmh7Ce)"><path stroke="url(#iJifgBd)" class="fvsn5ytmb"/></g><g filter="url(#ihyMPpb)"><path class="a77vmgktr"/></g><g filter="url(#iGSPjKe)"><path stroke="url(#iFR0lWc)" class="fj_0iw0tn"/></g><path fill="url(#i6krDxM)" class="ifq7qxk0q"/><path fill="url(#iaVvXOe)" class="o4ygf5iaf"/><g filter="url(#ipLyAyb)"><path fill="url(#iANFb7c)" class="p4phvc14w"/><path fill="url(#izwGjfe)" class="p4phvc14w"/></g><path fill="url(#ijmv18d)" class="p4phvc14w"/><path fill="url(#i3B1Mzd)" class="p4phvc14w"/><path fill="url(#iaM241c)" class="p4phvc14w"/><path fill="url(#ifjELCd)" class="p4phvc14w"/><path fill="url(#iSAarXe)" class="p4phvc14w"/><path fill="url(#iew4UId)" class="p4phvc14w"/><path fill="url(#ilQP9ee)" class="p4phvc14w"/><path fill="url(#iBNN9mb)" class="p4phvc14w"/><g filter="url(#im5H4Tb)"><path class="p1ciocb0r"/></g><g filter="url(#iTuzMyd)"><path class="t3ovgp71x"/><path fill="url(#iYcydze)" class="q3tga2buk"/><path fill="url(#izDI9td)" class="q3tga2buk"/><path fill="url(#i29wDId)" class="q3tga2buk"/><path fill="url(#iZtQKvb)" class="q3tga2buk"/><path fill="url(#iRxBBzb)" class="q3tga2buk"/></g><g filter="url(#inZXRFb)"><path stroke="url(#iVlUknb)" class="e7tzcnyim"/></g><path fill="url(#iz7tFEd)" class="y6wicp1sh"/><g filter="url(#isTl8vd)"><path fill="url(#iOMhtCc)" class="kecs7acmm"/></g><path fill="url(#iVDbtld)" class="kecs7acmm"/><path fill="url(#iN3jllc)" class="kecs7acmm"/><path fill="url(#iOoph7b)" class="kecs7acmm"/><g filter="url(#ifSanPc)"><path class="smnuntbvl"/></g><g filter="url(#iiynBrN)"><path class="gloxgqa0p"/></g><g filter="url(#irxFHIb)"><path class="xs1inpkme"/><path fill="url(#iTBNf4D)" class="riqghpb6w"/><path fill="url(#isg4Gpd)" class="riqghpb6w"/></g><g filter="url(#iIYGMib)"><path class="fgc8-1b6t"/><path fill="url(#iYMUPUb)" class="qqa4ton8x"/><path fill="url(#i4oMZkd)" class="qqa4ton8x"/><path fill="url(#i2nUkxc)" class="qqa4ton8x"/></g><path fill="url(#iFIB9he)" class="mquf7nbny"/><path fill="url(#iHb7k5d)" class="mquf7nbny"/><path fill="url(#i0ov8Ec)" class="mquf7nbny"/><path fill="url(#izc681b)" class="mquf7nbny"/><path fill="url(#ikYSHdd)" class="a1immybxr"/><path fill="url(#iibRymi)" class="a1immybxr"/><g filter="url(#i9W2KKd)"><path fill="url(#i2IBHbH)" class="lctmjjbod"/></g><g filter="url(#iGXs8oI)"><path fill="url(#ipbg1ae)" class="v6zgqtd0r"/></g><g filter="url(#iVZ547c)"><path class="h7u2u22up"/></g><g filter="url(#iMa8Ilc)"><path class="qgtuxkg0g"/></g><g filter="url(#iNQSkBc)"><path class="a-xq75r2y"/></g><path class="db5ke1b9h"/><g filter="url(#ingL85b)"><path class="qdrbxzb6i"/></g><path class="fimwz6btm"/><g filter="url(#ilPHZ0W)"><path class="vkakb-b8o"/></g><defs><radialGradient id="ieTKKyb" cx="0" cy="0" r="1" gradientTransform="rotate(109.231 -5.354 13.087)scale(.71158 1.43628)" gradientUnits="userSpaceOnUse"><stop class="ws2mhob-h"/><stop offset="1" class="cp-r2vxwo"/></radialGradient><radialGradient id="ix6Vdgc" cx="0" cy="0" r="1" gradientTransform="matrix(-.60937 .20323 -.41021 -1.22999 27.717 22.624)" gradientUnits="userSpaceOnUse"><stop class="kd9kwmb5m"/><stop offset="1" class="r-5q5hb6k"/></radialGradient><radialGradient id="iyo2Nte" cx="0" cy="0" r="1" gradientTransform="matrix(-4.10352 0 0 -6.94644 26.355 25.187)" gradientUnits="userSpaceOnUse"><stop offset=".289" class="sg1foi1wu"/><stop offset="1" class="p1klu8b2k"/></radialGradient><radialGradient id="i8SL0bb" cx="0" cy="0" r="1" gradientTransform="rotate(63.783 -6.868 31.62)scale(1.72425 1.82152)" gradientUnits="userSpaceOnUse"><stop class="kx-uu3bcv"/><stop offset="1" class="koh73ykov"/></radialGradient><radialGradient id="imh6k8d" cx="0" cy="0" r="1" gradientTransform="matrix(2.59375 .71875 -.52498 1.8945 9.876 28.531)" gradientUnits="userSpaceOnUse"><stop offset=".27" class="oij_789sb"/><stop offset="1" class="fgo10-bfl"/></radialGradient><radialGradient id="ivkLTrd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.40625 -.59375 1.5068 -6.10651 12.06 29.172)" gradientUnits="userSpaceOnUse"><stop offset=".753" class="jmmx0hb4k"/><stop offset="1" class="or-gk9zdk"/></radialGradient><radialGradient id="iRHRrrd" cx="0" cy="0" r="1" gradientTransform="matrix(-.875 .21875 -.60896 -2.43587 21.294 25.864)" gradientUnits="userSpaceOnUse"><stop class="l7-d3obpj"/><stop offset="1" class="awfuupnpj"/></radialGradient><radialGradient id="i4r1ieb" cx="0" cy="0" r="1" gradientTransform="matrix(2.3125 -.7705 1.76305 5.29137 5.576 25.74)" gradientUnits="userSpaceOnUse"><stop offset=".146" class="n3riwubet"/><stop offset="1" class="v-3y1-x4r"/></radialGradient><radialGradient id="i5EgdJb" cx="0" cy="0" r="1" gradientTransform="matrix(.67187 .90625 -1.49816 1.1107 7.232 23.874)" gradientUnits="userSpaceOnUse"><stop offset=".315" class="psz9wvbgc"/><stop offset="1" class="kjhv6n3zi"/></radialGradient><radialGradient id="iXY8vte" cx="0" cy="0" r="1" gradientTransform="matrix(4.5 0 0 1.90625 19.533 23.094)" gradientUnits="userSpaceOnUse"><stop class="mjvnc1bex"/><stop offset="1" class="qlzah1wzj"/></radialGradient><radialGradient id="iLtCeJd" cx="0" cy="0" r="1" gradientTransform="matrix(3.875 0 0 1.91303 8.607 22.82)" gradientUnits="userSpaceOnUse"><stop class="e11ubwgsj"/><stop offset="1" class="blyd8fb6w"/></radialGradient><radialGradient id="i1szBMb" cx="0" cy="0" r="1" gradientTransform="matrix(3.44922 -3.1199 1.05784 1.1695 7.157 23.495)" gradientUnits="userSpaceOnUse"><stop class="fr7vzibnl"/><stop offset="1" class="ql13ux9_l"/></radialGradient><radialGradient id="iovxGFb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.61326 3.09376 -1.04179 -.54325 12.24 20)" gradientUnits="userSpaceOnUse"><stop class="d-4gskbey"/><stop offset="1" class="w_0c54bla"/></radialGradient><radialGradient id="iOLZ0cW" cx="0" cy="0" r="1" gradientTransform="rotate(-142.496 17.237 7.531)scale(1.69385 2.1643)" gradientUnits="userSpaceOnUse"><stop offset=".03" class="idtmk0bzs"/><stop offset="1" class="n_iu3kb_q"/></radialGradient><radialGradient id="iOzeqFe" cx="0" cy="0" r="1" gradientTransform="matrix(4.85545 9.53121 -4.36739 2.22486 21.47 13.094)" gradientUnits="userSpaceOnUse"><stop class="g43k_w9lo"/><stop offset="1" class="b1hmbi0gc"/><stop offset="1" class="zsh0_03kt"/></radialGradient><radialGradient id="ivci6pe" cx="0" cy="0" r="1" gradientTransform="matrix(-.6875 4.03125 -8.3959 -1.43187 18.439 21.094)" gradientUnits="userSpaceOnUse"><stop offset=".126" class="ai9-2ku0o"/><stop offset=".925" class="gsv8efolz"/></radialGradient><radialGradient id="i01NKmc" cx="0" cy="0" r="1" gradientTransform="rotate(-128.1 12.068 2.398)scale(3.49455 5.00001)" gradientUnits="userSpaceOnUse"><stop class="bcjyfrafl"/><stop offset="1" class="ly19gqbcr"/></radialGradient><radialGradient id="iqnViuc" cx="0" cy="0" r="1" gradientTransform="rotate(118.757 4.54 9.687)scale(3.02046 3.40652)" gradientUnits="userSpaceOnUse"><stop offset=".363" class="ytty6sbwb"/><stop offset="1" class="louj_4_he"/></radialGradient><radialGradient id="iFbbife" cx="0" cy="0" r="1" gradientTransform="matrix(.5 8.04173 -7.73502 .48093 17.689 13.281)" gradientUnits="userSpaceOnUse"><stop offset=".296" class="ydcxvabaw"/><stop offset="1" class="hekp_gbnf"/></radialGradient><radialGradient id="iNNdesb" cx="0" cy="0" r="1" gradientTransform="rotate(141.869 7.577 10.752)scale(10.274 13.0752)" gradientUnits="userSpaceOnUse"><stop offset=".407" class="ksocwfbza"/><stop offset="1" class="ecaf6kbqo"/></radialGradient><radialGradient id="i0wzcic" cx="0" cy="0" r="1" gradientTransform="matrix(3.75 2.0625 -5.62896 10.23446 11.627 11.812)" gradientUnits="userSpaceOnUse"><stop offset=".074" class="bmu4g5dxl"/><stop offset="1" class="z321yabtz"/></radialGradient><radialGradient id="itYWULc" cx="0" cy="0" r="1" gradientTransform="matrix(.11328 .6422 -3.96388 .69921 4.51 23.047)" gradientUnits="userSpaceOnUse"><stop offset=".403" class="t2t46ho0j"/><stop offset="1" class="v5op15mpp"/></radialGradient><radialGradient id="i06IHtd" cx="0" cy="0" r="1" gradientTransform="matrix(-.11328 .6422 -3.96388 -.69922 27.49 23.047)" gradientUnits="userSpaceOnUse"><stop offset=".401" class="h9o--2dhj"/><stop offset="1" class="dranwgbob"/></radialGradient><radialGradient id="ikm6jCe" cx="0" cy="0" r="1" gradientTransform="matrix(.12686 .83746 -4.47454 .67782 4.517 23.672)" gradientUnits="userSpaceOnUse"><stop offset=".403" class="t2t46ho0j"/><stop offset="1" class="v5op15mpp"/></radialGradient><radialGradient id="isRiwAI" cx="0" cy="0" r="1" gradientTransform="matrix(-.12686 .83746 -4.47454 -.67782 27.483 23.672)" gradientUnits="userSpaceOnUse"><stop offset=".401" class="h9o--2dhj"/><stop offset="1" class="dranwgbob"/></radialGradient><radialGradient id="iBuXhqd" cx="0" cy="0" r="1" gradientTransform="matrix(.11226 .95131 -3.99486 .47143 5 24.226)" gradientUnits="userSpaceOnUse"><stop offset=".403" class="t2t46ho0j"/><stop offset="1" class="v5op15mpp"/></radialGradient><radialGradient id="i13XCdb" cx="0" cy="0" r="1" gradientTransform="rotate(96.73 2.732 24.113)scale(.95791 4.02259)" gradientUnits="userSpaceOnUse"><stop offset=".401" class="h9o--2dhj"/><stop offset="1" class="dranwgbob"/></radialGradient><radialGradient id="i4Pdzdb" cx="0" cy="0" r="1" gradientTransform="matrix(.10014 1.0686 -3.5818 .33567 5.935 24.411)" gradientUnits="userSpaceOnUse"><stop offset=".403" class="t2t46ho0j"/><stop offset="1" class="v5op15mpp"/></radialGradient><radialGradient id="iQqVLLb" cx="0" cy="0" r="1" gradientTransform="matrix(-.10014 1.0686 -3.5818 -.33567 26.065 24.411)" gradientUnits="userSpaceOnUse"><stop offset=".401" class="h9o--2dhj"/><stop offset="1" class="dranwgbob"/></radialGradient><radialGradient id="i6krDxM" cx="0" cy="0" r="1" gradientTransform="matrix(.47081 1.26984 -1.50846 .55929 19.008 8.379)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="hb-rh6b9c"/><stop offset="1" class="o5jc2cxps"/></radialGradient><radialGradient id="iaVvXOe" cx="0" cy="0" r="1" gradientTransform="matrix(.92837 .29179 -.90017 2.86405 12.212 8.687)" gradientUnits="userSpaceOnUse"><stop class="v_2gjcb5l"/><stop offset=".746" class="vzzhqfd0u"/></radialGradient><radialGradient id="iANFb7c" cx="0" cy="0" r="1" gradientTransform="matrix(-2.95842 0 0 -5.23341 17.785 7.787)" gradientUnits="userSpaceOnUse"><stop class="hdsgirtov"/><stop offset="1" class="j213y8b_z"/></radialGradient><radialGradient id="izwGjfe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.09606 1.81274 -1.49656 -.90489 17.545 4.656)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="v3vg2fbhx"/><stop offset="1" class="jon81gnkc"/></radialGradient><radialGradient id="i3B1Mzd" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.97345 -6.60297 0 16.37 3.906)" gradientUnits="userSpaceOnUse"><stop offset=".767" class="j9p73hbtq"/><stop offset=".96" class="j22t6enpy"/></radialGradient><radialGradient id="iaM241c" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.72206 .89355 0 17.558 6.961)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="kud2-ccnc"/><stop offset="1" class="qjdbe6bhy"/></radialGradient><radialGradient id="ifjELCd" cx="0" cy="0" r="1" gradientTransform="matrix(.00247 -.68806 .74877 .00269 14.573 6.99)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="g101ufbyh"/><stop offset="1" class="ofu8odbdi"/></radialGradient><radialGradient id="iSAarXe" cx="0" cy="0" r="1" gradientTransform="rotate(176.388 8.956 4.49)scale(5.35271 13.6735)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="c-0f6obbw"/><stop offset="1" class="q4oz8ebqu"/></radialGradient><radialGradient id="iew4UId" cx="0" cy="0" r="1" gradientTransform="matrix(2.1289 -1.83381 .54168 .62884 11.749 6.068)" gradientUnits="userSpaceOnUse"><stop offset=".539" class="gl-yj8bin"/><stop offset="1" class="b1x_r2coy"/></radialGradient><radialGradient id="ilQP9ee" cx="0" cy="0" r="1" gradientTransform="matrix(-.14755 1.57033 -.62773 -.05898 19.506 5.952)" gradientUnits="userSpaceOnUse"><stop offset=".245" class="y4noiz6ri"/><stop offset="1" class="n64jnw11q"/></radialGradient><radialGradient id="iBNN9mb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .54804 -1.05207 0 14.626 7.475)" gradientUnits="userSpaceOnUse"><stop class="rlwq00h2l"/><stop offset="1" class="uhv9b32lc"/></radialGradient><radialGradient id="izDI9td" cx="0" cy="0" r="1" gradientTransform="matrix(0 .15349 -.48239 0 16.313 8.642)" gradientUnits="userSpaceOnUse"><stop class="ifoj0vbnx"/><stop offset="1" class="fd01o6-ig"/></radialGradient><radialGradient id="iZtQKvb" cx="0" cy="0" r="1" gradientTransform="rotate(156.092 7.316 5.877)scale(1.16378 1.87029)" gradientUnits="userSpaceOnUse"><stop offset=".702" class="xqbp6db-u"/><stop offset="1" class="l6ffphqdg"/><stop offset="1" class="bi0efq_rm"/></radialGradient><radialGradient id="iz7tFEd" cx="0" cy="0" r="1" gradientTransform="matrix(1.37198 -.6745 2.71371 5.51983 15.71 10.065)" gradientUnits="userSpaceOnUse"><stop offset=".562" class="i_5kuqxuv"/><stop offset="1" class="iazz9lb4s"/></radialGradient><radialGradient id="iVDbtld" cx="0" cy="0" r="1" gradientTransform="matrix(1.72327 -4.49548 6.37905 2.4453 12.43 6.577)" gradientUnits="userSpaceOnUse"><stop class="gzjm9absi"/><stop offset="1" class="xys9jruze"/></radialGradient><radialGradient id="iN3jllc" cx="0" cy="0" r="1" gradientTransform="matrix(-.95531 -4.12086 5.84745 -1.35558 19.586 6.614)" gradientUnits="userSpaceOnUse"><stop offset=".303" class="gzjm9absi"/><stop offset="1" class="xys9jruze"/></radialGradient><radialGradient id="iOoph7b" cx="0" cy="0" r="1" gradientTransform="matrix(-.7118 -1.49849 1.769 -.84029 18.05 3.917)" gradientUnits="userSpaceOnUse"><stop class="vm3i05jbz"/><stop offset="1" class="o0n2z3bef"/></radialGradient><radialGradient id="iTBNf4D" cx="0" cy="0" r="1" gradientTransform="matrix(-1.38402 0 0 -.51366 16.179 3.265)" gradientUnits="userSpaceOnUse"><stop class="ur78mwbxs"/><stop offset="1" class="xxn4m8bxd"/></radialGradient><radialGradient id="isg4Gpd" cx="0" cy="0" r="1" gradientTransform="matrix(2.02353 -3.20388 3.54958 2.24187 12.605 5.744)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="oxzu0y4el"/><stop offset=".311" class="h09cq_pwq"/><stop offset="1" class="fdnwjygjt"/></radialGradient><radialGradient id="iYMUPUb" cx="0" cy="0" r="1" gradientTransform="matrix(2.21028 -1.77946 2.75778 3.42546 17.226 4.872)" gradientUnits="userSpaceOnUse"><stop class="wv5n4khjs"/><stop offset=".445" class="oywlam1jg"/></radialGradient><radialGradient id="i4oMZkd" cx="0" cy="0" r="1" gradientTransform="rotate(-41.829 16.247 -20.294)scale(2.4968 4.571)" gradientUnits="userSpaceOnUse"><stop offset=".857" class="ut-a4zo6y"/><stop offset="1" class="mw5vlrbvk"/></radialGradient><radialGradient id="i2nUkxc" cx="0" cy="0" r="1" gradientTransform="matrix(2.02797 .45533 -.19064 .84907 17.132 4.518)" gradientUnits="userSpaceOnUse"><stop class="rxg51vbwm"/><stop offset="1" class="g9z9sr5ky"/></radialGradient><radialGradient id="iHb7k5d" cx="0" cy="0" r="1" gradientTransform="rotate(74.348 4.702 16.087)scale(1.46484 1.39757)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="k-8l2bbtm"/><stop offset="1" class="j8b6y4byx"/></radialGradient><radialGradient id="i0ov8Ec" cx="0" cy="0" r="1" gradientTransform="matrix(.49534 -.67977 .56979 .4152 19.15 7.562)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="gvb-xxmau"/><stop offset="1" class="wbdnw-owo"/></radialGradient><radialGradient id="izc681b" cx="0" cy="0" r="1" gradientTransform="matrix(.36909 -.97487 1.30256 .49316 19.222 7.67)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="nx86noq5t"/><stop offset="1" class="mchm9tbqp"/></radialGradient><radialGradient id="iibRymi" cx="0" cy="0" r="1" gradientTransform="matrix(-1.04267 0 0 -1.16429 12.928 7.622)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="ok_b4wzpx"/><stop offset="1" class="mtikk0bwo"/></radialGradient><radialGradient id="i2IBHbH" cx="0" cy="0" r="1" gradientTransform="matrix(-.57626 .09892 -.10142 -.59085 12.93 7.624)" gradientUnits="userSpaceOnUse"><stop class="qkgshibem"/><stop offset="1" class="b89ok8b-l"/></radialGradient><filter id="i089wFX" width="9.729" height="6.156" x="17.627" y="21.781" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-1"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.623529 0 0 0 0 0.407843 0 0 0 0 0.435294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23991"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.576471 0 0 0 0 0.337255 0 0 0 0 0.494118 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23991" result="effect2_innerShadow_3987_23991"/></filter><filter id="iImjL4s" width="17.213" height="7.995" x="5.751" y="21.781" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-1"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.670588 0 0 0 0 0.447059 0 0 0 0 0.498039 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23991"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.611765 0 0 0 0 0.360784 0 0 0 0 0.498039 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23991" result="effect2_innerShadow_3987_23991"/></filter><filter id="iTkZEzd" width="7.621" height="12.797" x="19.836" y="11.789" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.603922 0 0 0 0 0.294118 0 0 0 0 0.239216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23991"/></filter><filter id="iuyJREb" width="8.502" height="3.19" x="11.869" y="21.123" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.262745 0 0 0 0 0.247059 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23991"/></filter><filter id="igZxv9U" width="5.834" height="4.108" x="13.158" y="10.267" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.611765 0 0 0 0 0.447059 0 0 0 0 0.372549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23991"/></filter><filter id="iNPkrRl" width="8.289" height="10.271" x="11.888" y="11.151" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.423529 0 0 0 0 0.0941176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23991"/></filter><filter id="iVyO6UU" width="1.684" height="1.255" x="5.351" y="24.025" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23991" stdDeviation=".075"/></filter><filter id="ih0sv0d" width="1.684" height="1.255" x="24.965" y="24.025" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23991" stdDeviation=".075"/></filter><filter id="ieZG7Nb" width="2.04" height="1.095" x="4.237" y="23.876" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23991" stdDeviation=".075"/></filter><filter id="iPaJWed" width="2.04" height="1.095" x="25.723" y="23.876" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23991" stdDeviation=".075"/></filter><filter id="i9Qif6c" width="2.223" height=".888" x="3.593" y="23.353" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23991" stdDeviation=".075"/></filter><filter id="iKmh7Ce" width="2.223" height=".888" x="26.184" y="23.353" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23991" stdDeviation=".075"/></filter><filter id="ihyMPpb" width="2.031" height=".566" x="3.653" y="22.931" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23991" stdDeviation=".075"/></filter><filter id="iGSPjKe" width="2.031" height=".566" x="26.317" y="22.931" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23991" stdDeviation=".075"/></filter><filter id="ipLyAyb" width="7.426" height="7.86" x="12.835" y="3.906" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".7"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.584314 0 0 0 0 0.427451 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23991"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.419608 0 0 0 0 0.25098 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23991" result="effect2_innerShadow_3987_23991"/></filter><filter id="im5H4Tb" width="3.098" height="3.823" x="14.381" y="6.268" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23991" stdDeviation=".5"/></filter><filter id="iTuzMyd" width="1.38" height="2.023" x="15.329" y="7.045" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23991" stdDeviation=".05"/></filter><filter id="inZXRFb" width="2.524" height="1.175" x="14.757" y="9.14" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23991" stdDeviation=".05"/></filter><filter id="isTl8vd" width="8.094" height="5.44" x="11.972" y="1.724" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.266667 0 0 0 0 0.152941 0 0 0 0 0.184314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23991"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.258824 0 0 0 0 0.133333 0 0 0 0 0.172549 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23991" result="effect2_innerShadow_3987_23991"/></filter><filter id="ifSanPc" width="1.508" height=".823" x="17.019" y="5.396" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.243137 0 0 0 0 0.121569 0 0 0 0 0.2 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23991"/></filter><filter id="iiynBrN" width="1.508" height=".813" x="13.713" y="5.405" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.243137 0 0 0 0 0.121569 0 0 0 0 0.2 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23991"/></filter><filter id="irxFHIb" width="4.026" height="3.649" x="12.253" y="2.656" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.364706 0 0 0 0 0.286275 0 0 0 0 0.270588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23991"/><feGaussianBlur result="effect2_foregroundBlur_3987_23991" stdDeviation=".05"/></filter><filter id="iIYGMib" width="4.733" height="3.888" x="16.029" y="2.571" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.282353 0 0 0 0 0.168627 0 0 0 0 0.188235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23991"/><feGaussianBlur result="effect2_foregroundBlur_3987_23991" stdDeviation=".075"/></filter><filter id="i9W2KKd" width="1.021" height="1.682" x="12.103" y="6.783" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23991" stdDeviation=".125"/></filter><filter id="iGXs8oI" width="1.507" height="2.105" x="18.695" y="6.567" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23991" stdDeviation=".25"/></filter><filter id="iVZ547c" width="1.341" height=".558" x="13.748" y="5.612" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23991" stdDeviation=".05"/></filter><filter id="iMa8Ilc" width="1.341" height=".558" x="17.091" y="5.578" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23991" stdDeviation=".05"/></filter><filter id="iNQSkBc" width="2.932" height="1.472" x="16.879" y="3.383" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23991" stdDeviation=".125"/></filter><filter id="ingL85b" width="1.628" height=".644" x="13.82" y="7.153" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23991" stdDeviation=".05"/></filter><filter id="ilPHZ0W" width="1.628" height=".644" x="16.609" y="7.153" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23991" stdDeviation=".05"/></filter><linearGradient id="iVX833c" x1="21.525" x2="21.525" y1="21.031" y2="22.187" gradientUnits="userSpaceOnUse"><stop class="aop12fbwl"/><stop offset="1" class="vjrb8p1-v"/></linearGradient><linearGradient id="iagd0tc" x1="18.658" x2="19.892" y1="24.315" y2="24.719" gradientUnits="userSpaceOnUse"><stop offset=".106" class="omwhmkb4w"/><stop offset="1" class="k0b-y7b8g"/></linearGradient><linearGradient id="iXawENb" x1="10.822" x2="10.822" y1="21.031" y2="22.187" gradientUnits="userSpaceOnUse"><stop class="x54l16cbw"/><stop offset="1" class="f1jial7kz"/></linearGradient><linearGradient id="igaeHWd" x1="13.689" x2="12.455" y1="24.315" y2="24.719" gradientUnits="userSpaceOnUse"><stop offset=".106" class="irp1--mlr"/><stop offset="1" class="nq1cvobrk"/></linearGradient><linearGradient id="iVh47be" x1="12.24" x2="10.033" y1="20.637" y2="20.446" gradientUnits="userSpaceOnUse"><stop offset=".184" class="ickdwm8yu"/><stop offset="1" class="m4mios-ri"/></linearGradient><linearGradient id="iyUX1Jd" x1="19.835" x2="22.042" y1="20.637" y2="20.446" gradientUnits="userSpaceOnUse"><stop offset=".184" class="rgd-j9bsm"/><stop offset="1" class="r2m9e8bad"/></linearGradient><linearGradient id="i7ixhhM" x1="26.466" x2="25.091" y1="25.203" y2="24.046" gradientUnits="userSpaceOnUse"><stop class="q91o75bcf"/><stop offset=".789" class="m-asxm1xk"/></linearGradient><linearGradient id="i6vmdXd" x1="26.516" x2="25.268" y1="25.114" y2="24.986" gradientUnits="userSpaceOnUse"><stop class="u95ub1zpg"/><stop offset="1" class="sgshpgb8b"/></linearGradient><linearGradient id="ijCJzkR" x1="27.656" x2="26.075" y1="24.793" y2="24.534" gradientUnits="userSpaceOnUse"><stop class="u95ub1zpg"/><stop offset="1" class="sgshpgb8b"/></linearGradient><linearGradient id="iJifgBd" x1="28.314" x2="26.645" y1="24.047" y2="24.143" gradientUnits="userSpaceOnUse"><stop class="u95ub1zpg"/><stop offset="1" class="sgshpgb8b"/></linearGradient><linearGradient id="iFR0lWc" x1="28.24" x2="26.724" y1="23.273" y2="23.211" gradientUnits="userSpaceOnUse"><stop class="u95ub1zpg"/><stop offset="1" class="sgshpgb8b"/></linearGradient><linearGradient id="ijmv18d" x1="19.262" x2="17.672" y1="8.846" y2="8.846" gradientUnits="userSpaceOnUse"><stop class="cgoojyxdz"/><stop offset="1" class="zvhz6qbam"/></linearGradient><linearGradient id="iYcydze" x1="16.547" x2="16.019" y1="8.211" y2="8.233" gradientUnits="userSpaceOnUse"><stop offset=".36" class="gb7af0bvz"/><stop offset="1" class="gafrz43pc"/></linearGradient><linearGradient id="i29wDId" x1="16.019" x2="16.019" y1="8.927" y2="8.635" gradientUnits="userSpaceOnUse"><stop class="q7066kb0m"/><stop offset="1" class="se5f_fbvx"/></linearGradient><linearGradient id="iRxBBzb" x1="16.019" x2="16.019" y1="7.226" y2="7.57" gradientUnits="userSpaceOnUse"><stop class="bl4x47bvc"/><stop offset="1" class="nv0opqb4i"/></linearGradient><linearGradient id="iVlUknb" x1="15.264" x2="15.464" y1="9.915" y2="9.39" gradientUnits="userSpaceOnUse"><stop class="sjwz8ccmm"/><stop offset="1" class="itcx93bci"/></linearGradient><linearGradient id="iOMhtCc" x1="20.328" x2="13.026" y1="4.226" y2="4.226" gradientUnits="userSpaceOnUse"><stop offset=".471" class="vj4yuc0qg"/><stop offset="1" class="yd6vs-kvu"/></linearGradient><linearGradient id="iFIB9he" x1="20.067" x2="19.308" y1="7.261" y2="8.63" gradientUnits="userSpaceOnUse"><stop class="r-tgpdb_v"/><stop offset="1" class="o8077h_4a"/></linearGradient><linearGradient id="ikYSHdd" x1="12.341" x2="13.258" y1="7.704" y2="7.624" gradientUnits="userSpaceOnUse"><stop class="d7c3jfbwh"/><stop offset="1" class="zvm05wbin"/></linearGradient><linearGradient id="ipbg1ae" x1="19.448" x2="19.448" y1="7.067" y2="8.172" gradientUnits="userSpaceOnUse"><stop class="aj8ithlra"/><stop offset="1" class="a9_46dbsd"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-in-lotus-position-medium" /></template>
<style>
.a-xq75r2y {
  fill: var(--svg-color--725050, #725050);
  d: path("M18.785 4.257H17.44a.312.312 0 1 1 .05-.62c.348.055.811.133 1.121.21c.701.173.895.515.949.758a.98.98 0 0 0-.776-.348");
}

.a1immybxr {
  d: path("M12.848 6.615a1.012 1.012 0 0 0 .08 2.015a49 49 0 0 1-.08-2.015");
}

.a77vmgktr {
  stroke: var(--svg-color--c0998a, #C0998A);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M3.878 23.265c.398 0 .893.047 1.58-.109");
}

.a9_46dbsd {
  stop-color: var(--svg-color--ad806f, #AD806F);
}

.ai9-2ku0o {
  stop-color: var(--svg-color--9f96a7, #9F96A7);
}

.aj8ithlra {
  stop-color: var(--svg-color--ac7f6f, #AC7F6F);
}

.aop12fbwl {
  stop-color: var(--svg-color--613226, #613226);
}

.awfuupnpj {
  stop-color: var(--svg-color--bf9785, #BF9785);
  stop-opacity: 0;
}

.b1hmbi0gc {
  stop-color: var(--svg-color--9a766b, #9A766B);
  stop-opacity: 0;
}

.b1x_r2coy {
  stop-color: var(--svg-color--63413d, #63413D);
  stop-opacity: 0;
}

.b89ok8b-l {
  stop-color: var(--svg-color--784e52, #784E52);
}

.bcjyfrafl {
  stop-color: var(--svg-color--bf9885, #BF9885);
}

.bi0efq_rm {
  stop-color: var(--svg-color--8a5f5c, #8A5F5C);
}

.bl4x47bvc {
  stop-color: var(--svg-color--a4786e, #A4786E);
}

.blyd8fb6w {
  stop-color: var(--svg-color--875f4f, #875F4F);
}

.bmu4g5dxl {
  stop-color: var(--svg-color--c56d32, #C56D32);
}

.bqwscm-5z {
  fill-rule: evenodd;
  d: path("M25.316 22.957a.5.5 0 0 0 .5.5c.632 0 1.257-.193 1.5-.268l.04-.012a.5.5 0 0 0-.292-.957l-.03.01c-.246.075-.743.227-1.218.227a.5.5 0 0 0-.5.5");
}

.c-0f6obbw {
  stop-color: var(--svg-color--987064, #987064);
  stop-opacity: 0;
}

.cgoojyxdz {
  stop-color: var(--svg-color--c2987e, #C2987E);
}

.cp-r2vxwo {
  stop-color: var(--svg-color--a47b5f, #A47B5F);
}

.d-4gskbey {
  stop-color: var(--svg-color--5b221f, #5B221F);
}

.d56lu3b4e {
  d: path("M18.892 11.153v.722a2.5 2.5 0 0 1-2.5 2.5h-.734a2.5 2.5 0 0 1-2.5-2.5v-.724a6.5 6.5 0 0 0-1.27.896v9.276h8.289v-9.276c-.198-.2-.662-.559-1.285-.894");
}

.d7c3jfbwh {
  stop-color: var(--svg-color--855d5a, #855D5A);
}

.db5ke1b9h {
  stroke: var(--svg-color--432534, #432534);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M13.97 7.303a.81.81 0 0 0 .672.344c.297 0 .591-.23.656-.344");
}

.dranwgbob {
  stop-color: var(--svg-color--88594b, #88594B);
}

.e11ubwgsj {
  stop-color: var(--svg-color--a5826e, #A5826E);
}

.e7tzcnyim {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M15.183 9.335c.24.126.529.198.836.198c.31 0 .596-.072.837-.198a.17.17 0 0 1 .203.033c.049.05.067.133.018.206m-1.894-.24l1.832.199m-1.832-.198h-.001a.17.17 0 0 0-.203.035a.16.16 0 0 0-.018.205m.222-.24l-.16.198m2.054.041l-.062-.041m.062.041l-.062-.041m.062.041c-.224.34-.614.566-1.058.566s-.833-.226-1.058-.565m2.054-.042a1.19 1.19 0 0 1-.996.532a1.19 1.19 0 0 1-.995-.532m-.063.042l.063-.042m-.063.042l.063-.042");
}

.ecaf6kbqo {
  stop-color: var(--svg-color--cc3a05, #CC3A05);
}

.eevmxtb1v {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M26.424 25.055a15 15 0 0 1-1.234-.805");
}

.f1jial7kz {
  stop-color: var(--svg-color--845c4a, #845C4A);
  stop-opacity: 0;
}

.fd01o6-ig {
  stop-color: var(--svg-color--c59a8a, #C59A8A);
  stop-opacity: 0;
}

.fd18zdsfu {
  stroke: var(--svg-color--c0998a, #C0998A);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M4.462 24.746c.41-.066 1.204-.313 1.59-.645");
}

.fdnwjygjt {
  stop-color: var(--svg-color--472438, #472438);
  stop-opacity: 0;
}

.fdw6rbsah {
  fill-rule: evenodd;
  d: path("M25.902 23.947a.4.4 0 0 0 .043.564c.34.29.628.456.903.549c.254.086.478.101.655.114l.037.002a.4.4 0 0 0 .057-.798l-.018-.001a1.8 1.8 0 0 1-.474-.075c-.156-.052-.357-.158-.64-.4a.4.4 0 0 0-.564.045");
}

.fgc8-1b6t {
  fill: var(--svg-color--563936, #563936);
  d: path("m19.297 6.31l-.019-.397a.924.924 0 0 0-.883-.897h-.88a1.52 1.52 0 0 1-1.336-.792s.453-1.307 1.204-1.138c.549.124 1.137.318 1.586.612c1.097.715.905 2.004.328 2.612");
}

.fgo10-bfl {
  stop-color: var(--svg-color--935a7c, #935A7C);
}

.fimwz6btm {
  stroke: var(--svg-color--432534, #432534);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M16.76 7.303a.81.81 0 0 0 .671.344c.297 0 .591-.23.656-.344");
}

.fj_0iw0tn {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M28.122 23.265c-.398 0-.893.047-1.58-.109");
}

.fr7vzibnl {
  stop-color: var(--svg-color--c79d88, #C79D88);
}

.ft5dv1b6b {
  fill: none;
}

.fvsn5ytmb {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M28.182 24.016a3.8 3.8 0 0 1-1.773-.438");
}

.g101ufbyh {
  stop-color: var(--svg-color--8f5d66, #8F5D66);
}

.g3wgqm9be {
  fill-rule: evenodd;
  d: path("M25.182 24.172c-.14.17-.272.303-.101.443a5.8 5.8 0 0 0 1.193.783l.072.037a.4.4 0 0 0 .367-.711l-.074-.038a5 5 0 0 1-1.051-.69c-.17-.14-.266.005-.406.176");
}

.g43k_w9lo {
  stop-color: var(--svg-color--c59b85, #C59B85);
}

.g9z9sr5ky {
  stop-color: var(--svg-color--4f2b3c, #4F2B3C);
  stop-opacity: 0;
}

.gafrz43pc {
  stop-color: var(--svg-color--cea58c, #CEA58C);
  stop-opacity: 0;
}

.gb7af0bvz {
  stop-color: var(--svg-color--cea58c, #CEA58C);
}

.gl-yj8bin {
  stop-color: var(--svg-color--63413d, #63413D);
}

.gloxgqa0p {
  fill: var(--svg-color--462d2b, #462D2B);
  d: path("M13.875 5.845a1.74 1.74 0 0 1 1.093-.226a.174.174 0 0 1-.042.346a1.4 1.4 0 0 0-.92.209l-.01.007l-.002.002a.174.174 0 0 1-.213-.276z");
}

.gqrdhsbjl {
  d: path("M13.83 21.323H7.814v2.692c2.531.352 6.016.297 6.016.297z");
}

.gsv8efolz {
  stop-color: var(--svg-color--6e6773, #6E6773);
}

.gvb-xxmau {
  stop-color: var(--svg-color--9e6a5c, #9E6A5C);
}

.gzjm9absi {
  stop-color: var(--svg-color--604946, #604946);
}

.h09cq_pwq {
  stop-color: var(--svg-color--472438, #472438);
}

.h5ql4kb6g {
  fill: var(--svg-color--a97e62, #A97E62);
  d: path("M9.755 16.08c.22-1.858 1.605-3.58 2.152-4.041l.332.315v7.276c-.25.652-.719 1.33-1.125 1.652c0 0-.867.814-4.171 3.304c-1.325-.185-2.095-1.094-2.074-1.703c.875-.5 3.37-2.969 4.011-3.606c.537-.535.64-1.215.875-3.197");
}

.h7u2u22up {
  stroke: var(--svg-color--553f3f, #553F3F);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M13.898 6.02c.162-.116.564-.32 1.04-.24");
}

.h9o--2dhj {
  stop-color: var(--svg-color--88594b, #88594B);
  stop-opacity: 0;
}

.ha61p4glz {
  d: path("m13.447 24.312l-1.578-2.99h8.301l-1.551 2.99z");
}

.hb-rh6b9c {
  stop-color: var(--svg-color--493b3b, #493B3B);
}

.hdsgirtov {
  stop-color: var(--svg-color--c89980, #C89980);
}

.hekp_gbnf {
  stop-color: var(--svg-color--f74d05, #F74D05);
}

.i_5kuqxuv {
  stop-color: var(--svg-color--87014e, #87014E);
}

.i19nx45cf {
  fill: var(--svg-color--b18970, #B18970);
  fill-rule: evenodd;
  d: path("M5.697 23.047a.4.4 0 0 1-.266.5c-.536.163-1.099.145-1.367.136q-.082-.003-.124-.002a.4.4 0 0 1-.018-.8q.104-.002.23.003c.286.007.656.017 1.045-.103a.4.4 0 0 1 .5.266");
}

.iazz9lb4s {
  stop-color: var(--svg-color--87004d, #87004D);
}

.ickdwm8yu {
  stop-color: var(--svg-color--87463e, #87463E);
}

.idtmk0bzs {
  stop-color: var(--svg-color--ba9783, #BA9783);
}

.ifoj0vbnx {
  stop-color: var(--svg-color--c59a8a, #C59A8A);
}

.ifq7qxk0q {
  d: path("M19.076 8.573a1.04 1.04 0 0 0 .569-.194v.585c0 .561-.335 1.062-.843 1.27q.161-.344.217-.743z");
}

.irp1--mlr {
  stop-color: var(--svg-color--68413d, #68413D);
}

.itcx93bci {
  stop-color: var(--svg-color--ab817b, #AB817B);
  stop-opacity: 0;
}

.j213y8b_z {
  stop-color: var(--svg-color--926763, #926763);
}

.j22t6enpy {
  stop-color: var(--svg-color--945e5f, #945E5F);
}

.j51x2pblc {
  fill: var(--svg-color--b18970, #B18970);
  fill-rule: evenodd;
  d: path("M6.099 23.947a.4.4 0 0 1-.044.564c-.34.29-.628.456-.903.549c-.254.086-.478.101-.655.114l-.037.002a.4.4 0 0 1-.057-.798l.018-.001c.19-.014.32-.023.475-.075s.356-.158.639-.4a.4.4 0 0 1 .564.045");
}

.j8b6y4byx {
  stop-color: var(--svg-color--9a676a, #9A676A);
}

.j9p73hbtq {
  stop-color: var(--svg-color--ac7b77, #AC7B77);
  stop-opacity: 0;
}

.jmmx0hb4k {
  stop-color: var(--svg-color--bc8f81, #BC8F81);
  stop-opacity: 0;
}

.jon81gnkc {
  stop-color: var(--svg-color--af887b, #AF887B);
  stop-opacity: 0;
}

.k-8l2bbtm {
  stop-color: var(--svg-color--9a676a, #9A676A);
  stop-opacity: 0;
}

.k0b-y7b8g {
  stop-color: var(--svg-color--7a544e, #7A544E);
  stop-opacity: 0;
}

.k5is8qewn {
  fill-rule: evenodd;
  d: path("M26.175 23.525a.4.4 0 0 0 .18.536c.754.375 1.51.448 1.823.448a.4.4 0 0 0 0-.8a3.6 3.6 0 0 1-1.466-.364a.4.4 0 0 0-.537.18");
}

.kd9kwmb5m {
  stop-color: var(--svg-color--b99880, #B99880);
}

.kecs7acmm {
  d: path("M19.072 3.61c.323.111.613.337.797.66a1.49 1.49 0 0 1-.067 1.59a1 1 0 0 0-.17.549v.747a1.1 1.1 0 0 0-.42-.169l.05-1.01a.91.91 0 0 0-.867-.9h-.88c-.6 0-1.144-.354-1.391-.907a.42.42 0 0 0-.387-.264h-.8c-1.161 0-2.101.952-2.101 2.125l.019.967c-.16.023-.327.077-.453.166v-.755a1 1 0 0 0-.17-.55a1.5 1.5 0 0 1-.09-1.538c.183-.347.48-.59.817-.708c.36-.128.667-.37.87-.698a1.46 1.46 0 0 1 1.818-.573a.94.94 0 0 0 .75 0a1.46 1.46 0 0 1 1.824.594c.194.32.497.552.85.674");
}

.kjhv6n3zi {
  stop-color: var(--svg-color--8b5c4d, #8B5C4D);
  stop-opacity: 0;
}

.koh73ykov {
  stop-color: var(--svg-color--855c4f, #855C4F);
  stop-opacity: 0;
}

.ksocwfbza {
  stop-color: var(--svg-color--ee5422, #EE5422);
  stop-opacity: 0;
}

.kud2-ccnc {
  stop-color: var(--svg-color--ab7872, #AB7872);
}

.kx-uu3bcv {
  stop-color: var(--svg-color--694137, #694137);
}

.l6ffphqdg {
  stop-color: var(--svg-color--744a4a, #744A4A);
}

.l7-d3obpj {
  stop-color: var(--svg-color--bf9785, #BF9785);
}

.lctmjjbod {
  d: path("M12.822 7.033a.601.601 0 0 0 .052 1.182q-.034-.591-.052-1.182");
}

.louj_4_he {
  stop-color: var(--svg-color--8d6d58, #8D6D58);
  stop-opacity: 0;
}

.ly19gqbcr {
  stop-color: var(--svg-color--a17c62, #A17C62);
}

.m-asxm1xk {
  stop-color: var(--svg-color--a15f4d, #A15F4D);
}

.m4mios-ri {
  stop-color: var(--svg-color--ac8270, #AC8270);
  stop-opacity: 0;
}

.m5zbi1oey {
  fill: var(--svg-color--a97760, #A97760);
  fill-rule: evenodd;
  d: path("M26.175 23.525a.4.4 0 0 0 .18.536c.754.375 1.51.448 1.823.448a.4.4 0 0 0 0-.8a3.6 3.6 0 0 1-1.466-.364a.4.4 0 0 0-.537.18");
}

.m8zsuwtqz {
  d: path("M18.517 21.323h6.016v2.692c-2.532.352-6.016.297-6.016.297z");
}

.mbv-embne {
  fill: var(--svg-color--a7785f, #A7785F);
  d: path("M22.32 16.08c-.22-1.858-1.605-3.58-2.152-4.041l-.332.315v7.276c.25.652.719 1.33 1.125 1.652c0 0 .867.814 4.172 3.304c1.325-.185 2.094-1.094 2.073-1.703c-.874-.5-3.37-2.969-4.01-3.606c-.538-.535-.641-1.215-.876-3.197");
}

.mchm9tbqp {
  stop-color: var(--svg-color--a47f62, #A47F62);
}

.md5c6jb0j {
  fill-rule: evenodd;
  d: path("M26.304 23.047a.4.4 0 0 0 .265.5c.536.163 1.099.145 1.367.136q.082-.003.124-.002a.4.4 0 0 0 .018-.8a5 5 0 0 0-.23.003c-.286.007-.656.017-1.045-.103a.4.4 0 0 0-.5.266");
}

.mjvnc1bex {
  stop-color: var(--svg-color--916e5e, #916E5E);
}

.mquf7nbny {
  d: path("M19.115 8.63q.063-1.004.116-2.007a1.012 1.012 0 0 1-.116 2.007");
}

.mriigjb_g {
  fill-rule: evenodd;
  d: path("M6.099 23.947a.4.4 0 0 1-.044.564c-.34.29-.628.456-.903.549c-.254.086-.478.101-.655.114l-.037.002a.4.4 0 0 1-.057-.798l.018-.001c.19-.014.32-.023.475-.075s.356-.158.639-.4a.4.4 0 0 1 .564.045");
}

.mtikk0bwo {
  stop-color: var(--svg-color--9d7667, #9D7667);
}

.mw5vlrbvk {
  stop-color: var(--svg-color--685351, #685351);
}

.mxe5l-b8x {
  d: path("M17.627 27.937h4.244c2.93 0 4.28-1.916 4.484-2.828l-2.531-2.328l-3.62 1.422l-2.578.11z");
}

.n_iu3kb_q {
  stop-color: var(--svg-color--b38b73, #B38B73);
  stop-opacity: 0;
}

.n3riwubet {
  stop-color: var(--svg-color--c39684, #C39684);
}

.n64jnw11q {
  stop-color: var(--svg-color--bf9980, #BF9980);
  stop-opacity: 0;
}

.ndxr44g2h {
  d: path("M9.755 16.08c.22-1.858 1.605-3.58 2.152-4.041l.332.315v7.276c-.25.652-.719 1.33-1.125 1.652c0 0-.867.814-4.171 3.304c-1.325-.185-2.095-1.094-2.074-1.703c.875-.5 3.37-2.969 4.011-3.606c.537-.535.64-1.215.875-3.197");
}

.nq1cvobrk {
  stop-color: var(--svg-color--7e5b4b, #7E5B4B);
  stop-opacity: 0;
}

.nv0opqb4i {
  stop-color: var(--svg-color--a4786e, #A4786E);
  stop-opacity: 0;
}

.nx86noq5t {
  stop-color: var(--svg-color--a47f62, #A47F62);
  stop-opacity: 0;
}

.o0n2z3bef {
  stop-color: var(--svg-color--765a55, #765A55);
  stop-opacity: 0;
}

.o4k-cfqdc {
  stroke: var(--svg-color--c0998a, #C0998A);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M5.576 25.055a15 15 0 0 0 1.234-.805");
}

.o4ygf5iaf {
  d: path("M12.963 8.573a1.03 1.03 0 0 1-.569-.194v.585c0 .561.335 1.062.843 1.27a2.6 2.6 0 0 1-.217-.743z");
}

.o5jc2cxps {
  stop-color: var(--svg-color--311f2c, #311F2C);
}

.o8077h_4a {
  stop-color: var(--svg-color--b08175, #B08175);
}

.ob_jzvllb {
  fill: var(--svg-color--a97760, #A97760);
  fill-rule: evenodd;
  d: path("M26.304 23.047a.4.4 0 0 0 .265.5c.536.163 1.099.145 1.367.136q.082-.003.124-.002a.4.4 0 0 0 .018-.8a5 5 0 0 0-.23.003c-.286.007-.656.017-1.045-.103a.4.4 0 0 0-.5.266");
}

.obgxu4wfp {
  fill: var(--svg-color--a97760, #A97760);
  fill-rule: evenodd;
  d: path("M25.902 23.947a.4.4 0 0 0 .043.564c.34.29.628.456.903.549c.254.086.478.101.655.114l.037.002a.4.4 0 0 0 .057-.798l-.018-.001a1.8 1.8 0 0 1-.474-.075c-.156-.052-.357-.158-.64-.4a.4.4 0 0 0-.564.045");
}

.ofu8odbdi {
  stop-color: var(--svg-color--8f5d66, #8F5D66);
  stop-opacity: 0;
}

.oij_789sb {
  stop-color: var(--svg-color--a66d7a, #A66D7A);
}

.ok_b4wzpx {
  stop-color: var(--svg-color--9d7667, #9D7667);
  stop-opacity: 0;
}

.omwhmkb4w {
  stop-color: var(--svg-color--7a544e, #7A544E);
}

.op0wkpb0r {
  fill-rule: evenodd;
  d: path("M6.818 24.172c.14.17.272.303.101.443a5.8 5.8 0 0 1-1.193.783l-.072.037a.4.4 0 0 1-.367-.711l.074-.038a5 5 0 0 0 1.051-.69c.17-.14.266.005.406.176");
}

.or-gk9zdk {
  stop-color: var(--svg-color--bc8f81, #BC8F81);
}

.oxzu0y4el {
  stop-color: var(--svg-color--37192c, #37192C);
}

.oywlam1jg {
  stop-color: var(--svg-color--532c3f, #532C3F);
  stop-opacity: 0;
}

.p1ciocb0r {
  fill: var(--svg-color--6f3f46, #6F3F46);
  d: path("m15.767 7.46l-.371 1.156c-.064.238.089.476.304.476h.46c.216 0 .369-.242.305-.476l-.31-1.156c-.067-.256-.318-.256-.388 0");
}

.p1klu8b2k {
  stop-color: var(--svg-color--a6786a, #A6786A);
}

.p4phvc14w {
  d: path("M12.985 9.525a2.46 2.46 0 0 0 2.444 2.142h1.186a2.46 2.46 0 0 0 2.443-2.142c.074-1.184.149-2.364.204-3.548a.91.91 0 0 0-.867-.9h-.88a1.52 1.52 0 0 1-1.391-.907a.42.42 0 0 0-.387-.264h-.8a2.114 2.114 0 0 0-2.102 2.125c0 1.17.073 2.321.15 3.494");
}

.pdh31bxtz {
  stroke: var(--svg-color--c0998a, #C0998A);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M3.818 24.016c.398 0 1.015-.055 1.773-.438");
}

.plwjkgbcu {
  fill: var(--svg-color--b18970, #B18970);
  fill-rule: evenodd;
  d: path("M5.825 23.525a.4.4 0 0 1-.18.536a4.4 4.4 0 0 1-1.823.448a.4.4 0 0 1 0-.8a3.6 3.6 0 0 0 1.466-.364a.4.4 0 0 1 .537.18");
}

.psz9wvbgc {
  stop-color: var(--svg-color--8b5c4d, #8B5C4D);
}

.q3tga2buk {
  d: path("m15.779 7.337l-.334 1.156c-.068.238.095.476.327.476h.495c.232 0 .395-.242.327-.476l-.334-1.156c-.072-.256-.406-.256-.481 0");
}

.q4oz8ebqu {
  stop-color: var(--svg-color--987064, #987064);
}

.q7066kb0m {
  stop-color: var(--svg-color--9c6376, #9C6376);
}

.q91o75bcf {
  stop-color: var(--svg-color--a97760, #A97760);
}

.qdrbxzb6i {
  stroke: var(--svg-color--523b3e, #523B3E);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M13.97 7.303a.81.81 0 0 0 .672.344c.297 0 .591-.23.656-.344");
}

.qgtuxkg0g {
  stroke: var(--svg-color--553f3f, #553F3F);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M18.282 5.986a1.46 1.46 0 0 0-1.041-.24");
}

.qjdbe6bhy {
  stop-color: var(--svg-color--ab7872, #AB7872);
  stop-opacity: 0;
}

.qkgshibem {
  stop-color: var(--svg-color--714b4d, #714B4D);
}

.ql13ux9_l {
  stop-color: var(--svg-color--b58b6f, #B58B6F);
  stop-opacity: 0;
}

.qlzah1wzj {
  stop-color: var(--svg-color--754b41, #754B41);
}

.qqa4ton8x {
  d: path("m19.297 6.31l-.019-.397a.924.924 0 0 0-.883-.897h-.88a1.52 1.52 0 0 1-1.336-.792s.453-1.307 1.204-1.138c.549.124 1.137.318 1.586.612c1.097.715.905 2.004.328 2.612");
}

.qqq97ebkd {
  d: path("M10.236 27.937c-2.93 0-4.281-1.916-4.485-2.828l2.532-2.328l3.453 1.445l8.18.086a1 1 0 0 1 .944.67c.407 1.171.96 2.765 1.032 3.002c.11.36.25 1.453-.875 1.766c-.78.216-1.523-.938-2.11-1.813z");
}

.qwmps2bvc {
  d: path("M13.22 24.312h-1.429a1 1 0 0 0-.943.67c-.408 1.171-.96 2.765-1.032 3.002c-.11.36-.25 1.453.875 1.766c.757.21 1.48-.871 2.057-1.735l.052-.078h.42z");
}

.r-5q5hb6k {
  stop-color: var(--svg-color--a68064, #A68064);
}

.r-tgpdb_v {
  stop-color: var(--svg-color--c9a188, #C9A188);
}

.r2m9e8bad {
  stop-color: var(--svg-color--b57f6f, #B57F6F);
  stop-opacity: 0;
}

.rgd-j9bsm {
  stop-color: var(--svg-color--8a3e31, #8A3E31);
}

.riqghpb6w {
  d: path("m16.166 4.256l-.042-.086a.42.42 0 0 0-.387-.264h-.8c-1.16 0-2.101.952-2.101 2.125v.173c-.214-.162-.483-.506-.483-1.061c0-.674.492-1.015.805-1.232a1.4 1.4 0 0 0 .208-.16q.03-.029.063-.065c.22-.233.611-.649 1.295-.83c.22-.058.442-.088.647-.1c.472-.025.808.386.808.859v.632z");
}

.rlwq00h2l {
  stop-color: var(--svg-color--9e7765, #9E7765);
}

.rmafx6bat {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M27.538 24.746c-.41-.066-1.204-.313-1.59-.645");
}

.rxg51vbwm {
  stop-color: var(--svg-color--4f2b3c, #4F2B3C);
}

.s9hud2bil {
  fill: var(--svg-color--b2886c, #B2886C);
  d: path("M10.236 27.937c-2.93 0-4.281-1.916-4.485-2.828l2.532-2.328l3.453 1.445l8.18.086a1 1 0 0 1 .944.67c.407 1.171.96 2.765 1.032 3.002c.11.36.25 1.453-.875 1.766c-.78.216-1.523-.938-2.11-1.813z");
}

.se5f_fbvx {
  stop-color: var(--svg-color--9c6376, #9C6376);
  stop-opacity: 0;
}

.sg1foi1wu {
  stop-color: var(--svg-color--ae8574, #AE8574);
}

.sgshpgb8b {
  stop-color: var(--svg-color--b99884, #B99884);
  stop-opacity: 0;
}

.sjwz8ccmm {
  stop-color: var(--svg-color--ab817b, #AB817B);
}

.smnuntbvl {
  fill: var(--svg-color--462d2b, #462D2B);
  d: path("M18.367 5.913a1.2 1.2 0 0 0-.432-.259c-.192-.06-.431-.076-.763-.035a.174.174 0 0 0 .043.346c.302-.037.488-.018.615.022c.125.04.209.103.308.189a.174.174 0 1 0 .229-.263");
}

.t2t46ho0j {
  stop-color: var(--svg-color--a46680, #A46680);
  stop-opacity: 0;
}

.t3ovgp71x {
  fill: var(--svg-color--a3776d, #A3776D);
  d: path("m15.779 7.337l-.334 1.156c-.068.238.095.476.327.476h.495c.232 0 .395-.242.327-.476l-.334-1.156c-.072-.256-.406-.256-.481 0");
}

.u95ub1zpg {
  stop-color: var(--svg-color--b99884, #B99884);
}

.uhv9b32lc {
  stop-color: var(--svg-color--9e7765, #9E7765);
  stop-opacity: 0;
}

.ur78mwbxs {
  stop-color: var(--svg-color--654647, #654647);
}

.ut-a4zo6y {
  stop-color: var(--svg-color--685351, #685351);
  stop-opacity: 0;
}

.v_2gjcb5l {
  stop-color: var(--svg-color--4c3c39, #4C3C39);
}

.v-3y1-x4r {
  stop-color: var(--svg-color--ab7d71, #AB7D71);
  stop-opacity: 0;
}

.v-p5omnxm {
  fill-rule: evenodd;
  d: path("M6.76 22.957a.5.5 0 0 1-.5.5c-.632 0-1.257-.193-1.501-.268l-.04-.012a.5.5 0 0 1 .293-.957l.029.01c.246.075.743.227 1.219.227a.5.5 0 0 1 .5.5");
}

.v3vg2fbhx {
  stop-color: var(--svg-color--af887b, #AF887B);
}

.v5op15mpp {
  stop-color: var(--svg-color--a46680, #A46680);
}

.v6zgqtd0r {
  d: path("m19.195 8.172l.059-1.105c.252.034.448.268.448.55c0 .305-.227.553-.507.555");
}

.vj4yuc0qg {
  stop-color: var(--svg-color--614440, #614440);
}

.vjrb8p1-v {
  stop-color: var(--svg-color--754437, #754437);
  stop-opacity: 0;
}

.vkakb-b8o {
  stroke: var(--svg-color--523b3e, #523B3E);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M16.76 7.303a.81.81 0 0 0 .671.344c.297 0 .591-.23.656-.344");
}

.vm3i05jbz {
  stop-color: var(--svg-color--765a55, #765A55);
}

.vvb767b_n {
  d: path("M22.32 16.08c-.22-1.858-1.605-3.58-2.152-4.041l-.332.315v7.276c.25.652.719 1.33 1.125 1.652c0 0 .867.814 4.172 3.304c1.325-.185 2.094-1.094 2.073-1.703c-.874-.5-3.37-2.969-4.01-3.606c-.538-.535-.641-1.215-.876-3.197");
}

.vzzhqfd0u {
  stop-color: var(--svg-color--2e1c2e, #2E1C2E);
}

.w_0c54bla {
  stop-color: var(--svg-color--965b4a, #965B4A);
  stop-opacity: 0;
}

.w--l981bs {
  fill-rule: evenodd;
  d: path("M5.825 23.525a.4.4 0 0 1-.18.536a4.4 4.4 0 0 1-1.823.448a.4.4 0 0 1 0-.8a3.6 3.6 0 0 0 1.466-.364a.4.4 0 0 1 .537.18");
}

.wbdnw-owo {
  stop-color: var(--svg-color--9e6a5c, #9E6A5C);
  stop-opacity: 0;
}

.ws2mhob-h {
  stop-color: var(--svg-color--af896e, #AF896E);
}

.wv5n4khjs {
  stop-color: var(--svg-color--532c3f, #532C3F);
}

.x54l16cbw {
  stop-color: var(--svg-color--613c31, #613C31);
}

.xm_vkhc8e {
  d: path("M18.892 11.153v.722a2.5 2.5 0 0 1-2.5 2.5h-.734a2.5 2.5 0 0 1-2.5-2.5v-.724c.763-.416 1.77-.784 2.914-.784c1.05 0 2.055.375 2.82.786");
}

.xqbp6db-u {
  stop-color: var(--svg-color--8a5f5c, #8A5F5C);
  stop-opacity: 0;
}

.xs1inpkme {
  fill: var(--svg-color--533634, #533634);
  d: path("m16.166 4.256l-.042-.086a.42.42 0 0 0-.387-.264h-.8c-1.16 0-2.101.952-2.101 2.125v.173c-.214-.162-.483-.506-.483-1.061c0-.674.492-1.015.805-1.232a1.4 1.4 0 0 0 .208-.16q.03-.029.063-.065c.22-.233.611-.649 1.295-.83c.22-.058.442-.088.647-.1c.472-.025.808.386.808.859v.632z");
}

.xxn4m8bxd {
  stop-color: var(--svg-color--654647, #654647);
  stop-opacity: 0;
}

.xys9jruze {
  stop-color: var(--svg-color--604946, #604946);
  stop-opacity: 0;
}

.y-yhajzcm {
  fill-rule: evenodd;
  d: path("M5.697 23.047a.4.4 0 0 1-.266.5c-.536.163-1.099.145-1.367.136q-.082-.003-.124-.002a.4.4 0 0 1-.018-.8q.104-.002.23.003c.286.007.656.017 1.045-.103a.4.4 0 0 1 .5.266");
}

.y4noiz6ri {
  stop-color: var(--svg-color--bf9980, #BF9980);
}

.y6wicp1sh {
  d: path("M16.02 9.608c-.32 0-.62-.075-.872-.207c-.086-.043-.179.054-.124.132c.21.319.577.532.995.532s.785-.213.996-.532c.054-.082-.039-.175-.125-.132a1.9 1.9 0 0 1-.87.207");
}

.yd6vs-kvu {
  stop-color: var(--svg-color--543f3c, #543F3C);
}

.ydcxvabaw {
  stop-color: var(--svg-color--ff7d3c, #FF7D3C);
}

.ytty6sbwb {
  stop-color: var(--svg-color--7d5644, #7D5644);
}

.z321yabtz {
  stop-color: var(--svg-color--d3612e, #D3612E);
  stop-opacity: 0;
}

.zhncmkv5o {
  fill: var(--svg-color--b18970, #B18970);
  fill-rule: evenodd;
  d: path("M6.818 24.172c.14.17.272.303.101.443a5.8 5.8 0 0 1-1.193.783l-.072.037a.4.4 0 0 1-.367-.711l.074-.038a5 5 0 0 0 1.051-.69c.17-.14.266.005.406.176");
}

.zsh0_03kt {
  stop-color: var(--svg-color--c59b85, #C59B85);
  stop-opacity: 0;
}

.zvhz6qbam {
  stop-color: var(--svg-color--c2987e, #C2987E);
  stop-opacity: 0;
}

.zvm05wbin {
  stop-color: var(--svg-color--7d4d5b, #7D4D5B);
}

</style>
