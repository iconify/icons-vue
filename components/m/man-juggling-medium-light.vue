<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iHVdxme)"><path fill="url(#iPYYWhe)" class="swka_j87x"/><path fill="url(#iT07jwd)" class="swka_j87x"/><path fill="url(#il5eVUq)" class="swka_j87x"/><path fill="url(#iY3yYtd)" class="swka_j87x"/><path fill="url(#iv8FoOX)" class="swka_j87x"/></g><circle fill="url(#iBZ0RUd)" class="hpfqe6rjh"/><circle fill="url(#itKlKTd)" class="hpfqe6rjh"/><circle fill="url(#ihlr5IT)" class="duyhuibwk"/><circle fill="url(#iGUmgWd)" class="duyhuibwk"/><circle fill="url(#iXhqZHd)" class="iwbygtbvw"/><circle fill="url(#iOHvRJe)" class="iwbygtbvw"/><circle fill="url(#issuNue)" class="zdcorrl9x"/><circle fill="url(#iMaLBhb)" class="zdcorrl9x"/><circle fill="url(#iAhrvZc)" class="zdcorrl9x"/><g filter="url(#ieBIGMd)"><circle fill="url(#iMk8UMb)" class="t-5nldk3g"/></g><g filter="url(#i2DFhNd)"><circle fill="url(#iR23Gge)" class="don2wdpjw"/></g><path fill="url(#i5YvaPc)" class="j70rp9pis"/><path fill="url(#iK84mBb)" class="j70rp9pis"/><path fill="url(#iWCiqKd)" class="j70rp9pis"/><path fill="url(#ieol8Me)" class="qy4rrcb8b"/><path fill="url(#iDbbcbc)" class="qy4rrcb8b"/><path fill="url(#iOe2zrd)" class="qy4rrcb8b"/><path fill="url(#iV71Rbc)" class="qy4rrcb8b"/><g filter="url(#iX7E1Nd)"><path fill="url(#iObplQb)" class="ggm3_setj"/><path fill="url(#iQpTAtb)" class="ggm3_setj"/></g><path fill="url(#ipodSkc)" class="f21vmbcik"/><path fill="url(#iXPTZOc)" class="f21vmbcik"/><path fill="url(#itP1zjc)" class="wp2p6dbcv"/><path fill="url(#i33ZCUz)" class="wp2p6dbcv"/><g filter="url(#i1WNX7d)"><path clip-rule="evenodd" class="byn6wubog"/></g><g filter="url(#isnRlYc)"><path fill="url(#iSAsI1d)" class="ctsppjbax"/><path fill="url(#iwtPTOo)" class="ctsppjbax"/><path fill="url(#isAdhHe)" class="ctsppjbax"/></g><g filter="url(#irlXTbe)"><path fill="url(#ivLP6Gc)" class="ht6lpfbpp"/><path fill="url(#iXetYud)" class="ht6lpfbpp"/></g><g filter="url(#ipGCYje)"><path fill="url(#i8tJXGc)" class="ld_83jb7a"/><path fill="url(#iw9bnJb)" class="ld_83jb7a"/></g><g filter="url(#ihk1Wde)"><path class="t5ih6_hjp"/></g><g filter="url(#iuUsbKd)"><path class="mdzzfhz-x"/></g><g filter="url(#icj7Jdd)"><path class="znvzi0b9x"/></g><g filter="url(#iCv5qtc)"><path class="z9b4pwbpg"/></g><g filter="url(#i2Go94v)"><path class="sty1w-bnq"/></g><path fill="url(#i9aB4nd)" class="hw860-bkw"/><path fill="url(#i1P2OKg)" class="hw860-bkw"/><path fill="url(#iQvGmfb)" class="hw860-bkw"/><g filter="url(#iAElzwe)"><path fill="url(#iH4w94w)" class="k-ikuabgd"/></g><path fill="url(#icc9pKv)" clip-rule="evenodd" class="wfgw5ub6b"/><path fill="url(#iWgnezd)" clip-rule="evenodd" class="wfgw5ub6b"/><path fill="url(#ivI3iyH)" clip-rule="evenodd" class="d5_x4xk7i"/><path fill="url(#inrNF9c)" clip-rule="evenodd" class="d5_x4xk7i"/><path fill="url(#iBFjJkb)" clip-rule="evenodd" class="ctupw6b3d"/><path fill="url(#iGp04ob)" clip-rule="evenodd" class="ctupw6b3d"/><path fill="url(#i64UBtb)" clip-rule="evenodd" class="vdngsab5t"/><path fill="url(#ioxxPTd)" clip-rule="evenodd" class="vdngsab5t"/><path fill="url(#ixRckpe)" class="twba206ho"/><path fill="url(#i7tW1rc)" class="twba206ho"/><path fill="url(#ihEGbme)" class="lucypabyc"/><g filter="url(#igyynSb)"><path class="dukixxuqk"/></g><g filter="url(#iHNCX4d)"><path class="tx50jtscj"/></g><g filter="url(#iAERgOO)"><path class="mra09yb-m"/></g><g filter="url(#i0O2qdc)"><path class="u47ww4b8k"/></g><g filter="url(#il7bZzb)"><path stroke="url(#iPWzvjj)" class="bdk4dmb5b"/></g><g filter="url(#is1eBoR)"><path stroke="url(#i0gZ48c)" class="gwm_2mjil"/></g><g filter="url(#ifoFGve)"><path stroke="url(#iF8fKMd)" class="y2ly1lryk"/></g><g filter="url(#iWZLRrf)"><path stroke="url(#impiaed)" class="am6k_ubte"/></g><g filter="url(#i07dZ8c)"><path stroke="url(#iVWluoc)" class="c549xi8ae"/></g><g filter="url(#iJqSyRb)"><circle fill="url(#i1TqxEb)" class="i-duydtwp"/></g><g filter="url(#igPI4lc)"><circle fill="url(#iHVEK9d)" class="vwohnyejo"/></g><g filter="url(#imUfcOl)"><circle fill="url(#ib5rLZU)" class="qaglwccub"/><circle fill="url(#i4sRx9d)" class="qaglwccub"/></g><g filter="url(#iG8sQwx)"><circle class="x0-6qkygn"/><circle fill="url(#ilY2PKe)" class="i6dlqjbae"/><circle fill="url(#iZ2ZTHd)" class="i6dlqjbae"/></g><g filter="url(#iQQtIrd)"><path fill="url(#i7muuXV)" class="l90-jebsc"/><path fill="url(#iAiV5Tb)" class="l90-jebsc"/><path fill="url(#i4x8brd)" class="l90-jebsc"/><path fill="url(#iak0sLc)" class="l90-jebsc"/><path fill="url(#iawlDmd)" class="l90-jebsc"/><path fill="url(#iZ3cL1c)" class="l90-jebsc"/></g><g filter="url(#ilcTZKz)"><path class="o1l1clgsm"/><path fill="url(#imXWpNe)" class="nafyo8b5t"/><path fill="url(#ifhmc1d)" class="nafyo8b5t"/><path fill="url(#ilRRL6c)" class="nafyo8b5t"/><path fill="url(#i2igzGe)" class="nafyo8b5t"/><path fill="url(#iwIBKII)" class="nafyo8b5t"/></g><g filter="url(#iDqQTOo)"><path class="c532_ht3q"/></g><g filter="url(#iw8X1ee)"><path class="ivad9acsp"/><path fill="url(#iGjcxHd)" class="wy1rn8btp"/><path fill="url(#iHgScsc)" class="wy1rn8btp"/><path fill="url(#iZsWzAo)" class="wy1rn8btp"/></g><path fill="url(#ilXDw6c)" class="wy1rn8btp"/><path stroke="url(#iLkIHAe)" class="pdpzp9ejr"/><g filter="url(#iXCAkwb)"><path class="tr5270bph"/></g><g filter="url(#ib5R8Sd)"><path class="xrxxjybof"/></g><path class="d2yfm4wlm"/><path fill="url(#i7bP5rc)" class="ivmi_zbqk"/><path class="qr4y5_b5k"/><g filter="url(#inLSeJb)"><path class="unksyib4v"/><path fill="url(#ipQhr1c)" class="bube3wtxx"/></g><g filter="url(#imfgWtb)"><path fill="url(#iwtw2Sc)" class="ltklaoqtr"/></g><path class="wpznbn7xg"/><path fill="url(#ikhImrd)" class="ocnjw0b9f"/><path class="jrc-__bwk"/><g filter="url(#iwq9IZd)"><path fill="url(#iYc8ehI)" class="xmtjwwq5j"/></g><g filter="url(#iNcXKyb)"><ellipse transform="rotate(-27.914 14.227 13.377)" class="tbh7zobro"/><ellipse fill="url(#icGVsAd)" transform="rotate(-27.914 14.227 13.377)" class="pgmlwohvs"/></g><g filter="url(#iQL9Wpd)"><path stroke="url(#iUxBSLe)" class="xwse_esww"/></g><g filter="url(#iC1WR9b)"><path stroke="url(#iOTbDce)" class="jtrn8vb0v"/></g><path fill="url(#iMwhdrV)" class="qzd219blo"/><path fill="url(#i3dSYhb)" class="qzd219blo"/><path fill="url(#inl9J2c)" class="qzd219blo"/><path fill="url(#iCE2gke)" class="wozepxbaa"/><path fill="url(#izP9Z9c)" class="wozepxbaa"/><rect fill="url(#iK2GSbd)" class="okwd93kys"/><rect fill="url(#iy7tjOa)" class="okwd93kys"/><rect fill="url(#iYE2hsb)" class="okwd93kys"/><defs><radialGradient id="iPYYWhe" cx="0" cy="0" r="1" gradientTransform="rotate(135.22 8.643 15.887)scale(12.9545 12.5552)" gradientUnits="userSpaceOnUse"><stop offset=".195" class="m-1-e5bla"/><stop offset=".794" class="b057dp4eh"/></radialGradient><radialGradient id="iT07jwd" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.09375 -3.28125 0 20.219 20.139)" gradientUnits="userSpaceOnUse"><stop class="m9gf32bwp"/><stop offset="1" class="n297mkbnr"/></radialGradient><radialGradient id="il5eVUq" cx="0" cy="0" r="1" gradientTransform="matrix(-1.75 0 0 -11.7187 21 25.92)" gradientUnits="userSpaceOnUse"><stop offset=".214" class="demkpcl0k"/><stop offset="1" class="ym-b_m9fy"/></radialGradient><radialGradient id="iY3yYtd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.15625 0 0 -5.75902 11.656 25.326)" gradientUnits="userSpaceOnUse"><stop class="ujrq6ixuu"/><stop offset="1" class="h4mko5b9o"/></radialGradient><radialGradient id="iv8FoOX" cx="0" cy="0" r="1" gradientTransform="matrix(2.12502 5.34374 -11.023 4.38346 13.099 18.733)" gradientUnits="userSpaceOnUse"><stop class="nl0wbpawx"/><stop offset="1" class="jm40s5baz"/></radialGradient><radialGradient id="iBZ0RUd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.34375 2.4375 -2.36069 -1.3014 7.187 11.826)" gradientUnits="userSpaceOnUse"><stop offset=".077" class="l-r9gxb9g"/><stop offset="1" class="hcmh5c50b"/></radialGradient><radialGradient id="itKlKTd" cx="0" cy="0" r="1" gradientTransform="rotate(115.145 -.151 8.247)scale(3.38309 2.95533)" gradientUnits="userSpaceOnUse"><stop offset=".452" class="y-1rsmdul"/><stop offset=".826" class="af8mzdbwl"/></radialGradient><radialGradient id="ihlr5IT" cx="0" cy="0" r="1" gradientTransform="matrix(-1.34375 2.4375 -2.36069 -1.3014 10.101 2.846)" gradientUnits="userSpaceOnUse"><stop offset=".077" class="mpwbs5b3u"/><stop offset="1" class="fzq016boz"/></radialGradient><radialGradient id="iGUmgWd" cx="0" cy="0" r="1" gradientTransform="rotate(115.145 4.158 4.683)scale(3.38309 2.95533)" gradientUnits="userSpaceOnUse"><stop offset=".452" class="x1l7xqbyw"/><stop offset=".826" class="ng1cexbhj"/></radialGradient><radialGradient id="iXhqZHd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.34375 2.4375 -2.36069 -1.3014 26.066 3.861)" gradientUnits="userSpaceOnUse"><stop offset=".077" class="lelj2r8dg"/><stop offset="1" class="fde_fwzpt"/></radialGradient><radialGradient id="iOHvRJe" cx="0" cy="0" r="1" gradientTransform="rotate(105.03 11.36 11.751)scale(3.49455 3.40391)" gradientUnits="userSpaceOnUse"><stop offset=".375" class="ppr920emc"/><stop offset=".826" class="y_auwli2s"/></radialGradient><radialGradient id="issuNue" cx="0" cy="0" r="1" gradientTransform="matrix(-1.34375 2.4375 -2.36069 -1.3014 27.09 13.818)" gradientUnits="userSpaceOnUse"><stop offset=".077" class="y05rrkbkk"/><stop offset="1" class="a5zzorbzd"/></radialGradient><radialGradient id="iMaLBhb" cx="0" cy="0" r="1" gradientTransform="matrix(1 1.07812 -1.5877 1.47265 24.969 13.357)" gradientUnits="userSpaceOnUse"><stop class="i8j0jyb4u"/><stop offset="1" class="d7caiobkz"/></radialGradient><radialGradient id="iAhrvZc" cx="0" cy="0" r="1" gradientTransform="rotate(109.11 8.51 16.52)scale(3.46022 3.37046)" gradientUnits="userSpaceOnUse"><stop offset=".347" class="tn_97qkdc"/><stop offset=".829" class="mmq2utbuk"/></radialGradient><radialGradient id="iMk8UMb" cx="0" cy="0" r="1" gradientTransform="matrix(-.7578 1.14063 -.96756 -.64282 17.25 27.855)" gradientUnits="userSpaceOnUse"><stop offset=".212" class="u6lph46no"/><stop offset="1" class="bq5dgsbba"/></radialGradient><radialGradient id="iR23Gge" cx="0" cy="0" r="1" gradientTransform="matrix(-.7578 1.14063 -.96756 -.64282 17.25 25.842)" gradientUnits="userSpaceOnUse"><stop offset=".212" class="u6lph46no"/><stop offset="1" class="bq5dgsbba"/></radialGradient><radialGradient id="i5YvaPc" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.03125 -2.40212 0 22.222 20.983)" gradientUnits="userSpaceOnUse"><stop class="koq0r9bvu"/><stop offset="1" class="dpmuo-biy"/></radialGradient><radialGradient id="ieol8Me" cx="0" cy="0" r="1" gradientTransform="scale(1.38818 6.1875)rotate(90 2.761 6.5)" gradientUnits="userSpaceOnUse"><stop class="xntzq-4ho"/><stop offset="1" class="pt8frltpn"/></radialGradient><radialGradient id="iDbbcbc" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.25 -.60938 0 13.062 24.108)" gradientUnits="userSpaceOnUse"><stop class="wshx69b-y"/><stop offset="1" class="aqzyd8bsb"/></radialGradient><radialGradient id="iOe2zrd" cx="0" cy="0" r="1" gradientTransform="matrix(2.9375 -7.98881 7.06186 2.59666 10.312 28.264)" gradientUnits="userSpaceOnUse"><stop offset=".724" class="lgi0lwbjz"/><stop offset="1" class="tvoyviyhj"/></radialGradient><radialGradient id="iV71Rbc" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.42188 -.18506 0 12.857 21.717)" gradientUnits="userSpaceOnUse"><stop class="m5avsc_ef"/><stop offset="1" class="ci3gi1b_k"/></radialGradient><radialGradient id="iObplQb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.90624 2.42972 -4.28692 -6.89204 19.266 20.795)" gradientUnits="userSpaceOnUse"><stop class="ku63lg_wt"/><stop offset="1" class="i1-orb7ke"/></radialGradient><radialGradient id="iQpTAtb" cx="0" cy="0" r="1" gradientTransform="matrix(-.46875 -.125 .54686 -2.05079 19.188 22.482)" gradientUnits="userSpaceOnUse"><stop offset=".108" class="qsu4qbckq"/><stop offset="1" class="gr0wzobbs"/></radialGradient><radialGradient id="iSAsI1d" cx="0" cy="0" r="1" gradientTransform="matrix(1.73878 1.3451 -1.47727 1.90964 13.775 23.358)" gradientUnits="userSpaceOnUse"><stop class="ab6i82btp"/><stop offset="1" class="pb6efmson"/></radialGradient><radialGradient id="iwtPTOo" cx="0" cy="0" r="1" gradientTransform="matrix(-1.68958 -.4774 .79459 -2.81214 15.416 23.836)" gradientUnits="userSpaceOnUse"><stop offset=".69" class="sawf8hb2n"/><stop offset="1" class="o415o878f"/></radialGradient><radialGradient id="isAdhHe" cx="0" cy="0" r="1" gradientTransform="matrix(-.5 1.58457 -.75053 -.23683 16.11 23.836)" gradientUnits="userSpaceOnUse"><stop class="btor07b8q"/><stop offset="1" class="jjf293xlz"/></radialGradient><radialGradient id="ivLP6Gc" cx="0" cy="0" r="1" gradientTransform="rotate(142.275 5.895 15.056)scale(2.19833 2.41434)" gradientUnits="userSpaceOnUse"><stop class="auvn9fbbk"/><stop offset="1" class="h2li0wblg"/></radialGradient><radialGradient id="iXetYud" cx="0" cy="0" r="1" gradientTransform="matrix(1.68958 -.4774 .79459 2.81214 18.13 23.836)" gradientUnits="userSpaceOnUse"><stop offset=".69" class="sawf8hb2n"/><stop offset="1" class="o415o878f"/></radialGradient><radialGradient id="iw9bnJb" cx="0" cy="0" r="1" gradientTransform="matrix(-.39136 0 0 -2.59279 17.54 23.592)" gradientUnits="userSpaceOnUse"><stop class="scbqttb8d"/><stop offset="1" class="u1gl_1zha"/></radialGradient><radialGradient id="i9aB4nd" cx="0" cy="0" r="1" gradientTransform="matrix(-4.375 1.44046 -1.3893 -4.21963 28.098 22.456)" gradientUnits="userSpaceOnUse"><stop offset=".241" class="sqw7shfwy"/><stop offset="1" class="t-r3m-b0n"/></radialGradient><radialGradient id="i1P2OKg" cx="0" cy="0" r="1" gradientTransform="rotate(163.091 11.838 12.97)scale(3.90165 13.4872)" gradientUnits="userSpaceOnUse"><stop offset=".699" class="fxbge344d"/><stop offset="1" class="i9u4tf5-i"/></radialGradient><radialGradient id="iQvGmfb" cx="0" cy="0" r="1" gradientTransform="rotate(77.963 .104 26.074)scale(1.04894 5.75403)" gradientUnits="userSpaceOnUse"><stop offset=".134" class="te2y3cbdr"/><stop offset="1" class="pdm4p_b5q"/><stop offset="1" class="kmrvduh9f"/></radialGradient><radialGradient id="iH4w94w" cx="0" cy="0" r="1" gradientTransform="rotate(139.97 1.2 10.48)scale(1.53045 3.638)" gradientUnits="userSpaceOnUse"><stop offset=".129" class="vxe5hyz_v"/><stop offset="1" class="k9e4-bb7j"/></radialGradient><radialGradient id="icc9pKv" cx="0" cy="0" r="1" gradientTransform="matrix(-.79386 1.27188 -2.4349 -1.51978 6.442 17.553)" gradientUnits="userSpaceOnUse"><stop class="hjrsfpbzk"/><stop offset="1" class="vfp25y1ae"/></radialGradient><radialGradient id="iWgnezd" cx="0" cy="0" r="1" gradientTransform="matrix(-.73037 2.48832 -3.82658 -1.12318 6.977 17.288)" gradientUnits="userSpaceOnUse"><stop offset=".579" class="lxw2rgt3i"/><stop offset=".954" class="nke1727fd"/></radialGradient><radialGradient id="ivI3iyH" cx="0" cy="0" r="1" gradientTransform="rotate(116.602 -3.017 10.55)scale(1.58621 2.70684)" gradientUnits="userSpaceOnUse"><stop class="hjrsfpbzk"/><stop offset="1" class="vfp25y1ae"/></radialGradient><radialGradient id="inrNF9c" cx="0" cy="0" r="1" gradientTransform="matrix(-.65347 2.77477 -3.52334 -.82977 5.545 17.677)" gradientUnits="userSpaceOnUse"><stop offset=".579" class="lxw2rgt3i"/><stop offset=".954" class="nke1727fd"/></radialGradient><radialGradient id="iBFjJkb" cx="0" cy="0" r="1" gradientTransform="matrix(-.68468 1.22288 -2.2217 -1.2439 4.939 18.947)" gradientUnits="userSpaceOnUse"><stop class="hjrsfpbzk"/><stop offset="1" class="vfp25y1ae"/></radialGradient><radialGradient id="iGp04ob" cx="0" cy="0" r="1" gradientTransform="rotate(104.751 -4.503 11.427)scale(2.474 3.46652)" gradientUnits="userSpaceOnUse"><stop offset=".579" class="lxw2rgt3i"/><stop offset=".954" class="nke1727fd"/></radialGradient><radialGradient id="i64UBtb" cx="0" cy="0" r="1" gradientTransform="rotate(122.692 -2.834 11.406)scale(1.24393 2.40994)" gradientUnits="userSpaceOnUse"><stop class="hjrsfpbzk"/><stop offset="1" class="vfp25y1ae"/></radialGradient><radialGradient id="ioxxPTd" cx="0" cy="0" r="1" gradientTransform="matrix(-.61813 2.04813 -3.22394 -.973 5.687 19.733)" gradientUnits="userSpaceOnUse"><stop offset=".579" class="lxw2rgt3i"/><stop offset=".954" class="nke1727fd"/></radialGradient><radialGradient id="ixRckpe" cx="0" cy="0" r="1" gradientTransform="rotate(-162.011 6.48 10.137)scale(3.69324 5.10277)" gradientUnits="userSpaceOnUse"><stop class="w3oseebkq"/><stop offset=".644" class="cy8y9p-pn"/></radialGradient><radialGradient id="i7tW1rc" cx="0" cy="0" r="1" gradientTransform="matrix(.07812 -.82813 3.88844 .36683 6.156 21.78)" gradientUnits="userSpaceOnUse"><stop class="axsenyy_b"/><stop offset="1" class="j471ep9dt"/></radialGradient><radialGradient id="ihEGbme" cx="0" cy="0" r="1" gradientTransform="matrix(1.6875 2.24809 -2.56376 1.92445 16.098 20.289)" gradientUnits="userSpaceOnUse"><stop offset=".252" class="s0pz40q7h"/><stop offset="1" class="lvd5l1bfv"/></radialGradient><radialGradient id="i1TqxEb" cx="0" cy="0" r="1" gradientTransform="matrix(1.84203 0 0 3.22356 10.068 14.193)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="aik_z9b6i"/><stop offset="1" class="k1mq2zvhc"/></radialGradient><radialGradient id="i4sRx9d" cx="0" cy="0" r="1" gradientTransform="matrix(.86777 -.63187 .7212 .99044 22.197 13.915)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="g7lt91bhf"/><stop offset="1" class="ze1cb0iau"/></radialGradient><radialGradient id="ilY2PKe" cx="0" cy="0" r="1" gradientTransform="matrix(.86205 -1.58556 .92803 .50456 21.763 15.055)" gradientUnits="userSpaceOnUse"><stop offset=".69" class="ezktjkbgg"/><stop offset="1" class="j3anadbkm"/></radialGradient><radialGradient id="iZ2ZTHd" cx="0" cy="0" r="1" gradientTransform="matrix(.27217 .2694 -.3473 .35086 21.806 14.193)" gradientUnits="userSpaceOnUse"><stop class="i4pfhbczn"/><stop offset="1" class="xjk10obil"/></radialGradient><radialGradient id="iAiV5Tb" cx="0" cy="0" r="1" gradientTransform="matrix(0 11.2002 -10.7007 0 17.298 10.686)" gradientUnits="userSpaceOnUse"><stop offset=".618" class="admloybui"/><stop offset=".951" class="ss_mx3bgz"/></radialGradient><radialGradient id="iak0sLc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.372 1.68862 0 19.266 12.859)" gradientUnits="userSpaceOnUse"><stop class="op2kwubyv"/><stop offset="1" class="wvivicznw"/></radialGradient><radialGradient id="iawlDmd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.45995 1.81558 0 14.482 12.824)" gradientUnits="userSpaceOnUse"><stop class="y7nn5tbfc"/><stop offset="1" class="uylyaxbnq"/></radialGradient><radialGradient id="imXWpNe" cx="0" cy="0" r="1" gradientTransform="rotate(127.807 8.847 8.113)scale(5.88464 10.0073)" gradientUnits="userSpaceOnUse"><stop class="qyobb4hvj"/><stop offset="1" class="szm1jtb2t"/></radialGradient><radialGradient id="ilRRL6c" cx="0" cy="0" r="1" gradientTransform="matrix(-.07014 -1.95393 .95962 -.03445 12.403 10.566)" gradientUnits="userSpaceOnUse"><stop offset=".227" class="u7v6tactn"/><stop offset="1" class="hpjuubccm"/></radialGradient><radialGradient id="i2igzGe" cx="0" cy="0" r="1" gradientTransform="matrix(.90182 -2.06416 1.68347 .7355 21.24 12.37)" gradientUnits="userSpaceOnUse"><stop offset=".479" class="ls62f1bvq"/><stop offset="1" class="gx0o3oiqw"/></radialGradient><radialGradient id="iwIBKII" cx="0" cy="0" r="1" gradientTransform="matrix(1.0421 1.29305 -1.14167 .9201 15.99 5.165)" gradientUnits="userSpaceOnUse"><stop class="kxzxrmw_u"/><stop offset="1" class="vs8934bpj"/></radialGradient><radialGradient id="i7bP5rc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .94801 -1.12175 0 19.09 13.828)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="ipQhr1c" cx="0" cy="0" r="1" gradientTransform="matrix(-.24338 -.31363 .4318 -.33508 18.851 13.566)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ikhImrd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .94806 -1.1218 0 14.511 13.828)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="icGVsAd" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 13.853 -.141)scale(.51857 .62334)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iMwhdrV" cx="0" cy="0" r="1" gradientTransform="matrix(-5.5 4.12501 -3.615 -4.82 20.719 4.576)" gradientUnits="userSpaceOnUse"><stop offset=".179" class="tg07-ljnl"/><stop offset="1" class="c6833cb9x"/></radialGradient><radialGradient id="i3dSYhb" cx="0" cy="0" r="1" gradientTransform="matrix(2.875 .375 -.58342 4.4729 10.781 7.701)" gradientUnits="userSpaceOnUse"><stop class="j8k1fac_p"/><stop offset="1" class="g8uem1b5g"/></radialGradient><radialGradient id="inl9J2c" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.875 8.03906 0 16.773 8.326)" gradientUnits="userSpaceOnUse"><stop offset=".761" class="km6q7kb1a"/><stop offset="1" class="i8skpb2jz"/></radialGradient><radialGradient id="iCE2gke" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.47656 -8.28125 0 18.406 7.912)" gradientUnits="userSpaceOnUse"><stop class="kzuil_5zu"/><stop offset="1" class="ok2r3obil"/></radialGradient><radialGradient id="iK2GSbd" cx="0" cy="0" r="1" gradientTransform="matrix(-7.1875 0 0 -.63281 21.268 9.87)" gradientUnits="userSpaceOnUse"><stop class="w63qn2bkh"/><stop offset="1" class="vvfum-_fa"/></radialGradient><radialGradient id="iy7tjOa" cx="0" cy="0" r="1" gradientTransform="matrix(3.48438 0 0 2.01172 9.003 10.109)" gradientUnits="userSpaceOnUse"><stop class="gfrsedb9v"/><stop offset="1" class="vke6kh8bt"/></radialGradient><filter id="iHVdxme" width="21.247" height="10.303" x="6.25" y="19.623" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.615686 0 0 0 0 0.607843 0 0 0 0 0.619608 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23857"/></filter><filter id="ieBIGMd" width="2.078" height="2.078" x="15.622" y="27.457" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.792157 0 0 0 0 0.717647 0 0 0 0 0.788235 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_3987_23857"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_3987_23857" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.831373 0 0 0 0 0.745098 0 0 0 0 0.803922 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_3987_23857"/></filter><filter id="i2DFhNd" width="2.078" height="2.078" x="15.622" y="25.444" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.792157 0 0 0 0 0.717647 0 0 0 0 0.788235 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_3987_23857"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_3987_23857" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.831373 0 0 0 0 0.745098 0 0 0 0 0.803922 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_3987_23857"/></filter><filter id="iX7E1Nd" width="6.554" height="3.702" x="13.38" y="19.523" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.721569 0 0 0 0 0.682353 0 0 0 0 0.74902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23857"/></filter><filter id="i1WNX7d" width="7.432" height="4.46" x="12.567" y="22.084" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23857" stdDeviation=".5"/></filter><filter id="isnRlYc" width="2.672" height="2.865" x="13.611" y="22.403" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.780392 0 0 0 0 0.270588 0 0 0 0 0.396078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23857"/></filter><filter id="irlXTbe" width="2.672" height="2.865" x="17.264" y="22.403" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.780392 0 0 0 0 0.270588 0 0 0 0 0.396078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23857"/></filter><filter id="ipGCYje" width="1.554" height="1.999" x="15.986" y="22.812" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.827451 0 0 0 0 0.137255 0 0 0 0 0.317647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23857"/></filter><filter id="ihk1Wde" width="4.764" height="4.766" x="24.75" y="19.349" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.1"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.827451 0 0 0 0 0.592157 0 0 0 0 0.419608 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23857"/></filter><filter id="iuUsbKd" width="2.077" height="3.844" x="25.907" y="17.448" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.803922 0 0 0 0 0.564706 0 0 0 0 0.517647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23857"/></filter><filter id="icj7Jdd" width="2.401" height="4.052" x="24.436" y="17.107" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.803922 0 0 0 0 0.564706 0 0 0 0 0.517647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23857"/></filter><filter id="iCv5qtc" width="2.312" height="4.044" x="23.386" y="17.96" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.803922 0 0 0 0 0.564706 0 0 0 0 0.517647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23857"/></filter><filter id="i2Go94v" width="2.123" height="3.114" x="22.394" y="19.041" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.803922 0 0 0 0 0.564706 0 0 0 0 0.517647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23857"/></filter><filter id="iAElzwe" width="3.002" height="3.147" x="6.649" y="16.347" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.85098 0 0 0 0 0.607843 0 0 0 0 0.47451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23857"/></filter><filter id="igyynSb" width="1.264" height="2.491" x="22.908" y="19.19" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23857" stdDeviation=".125"/></filter><filter id="iHNCX4d" width="1.286" height="2.978" x="23.932" y="18.125" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23857" stdDeviation=".125"/></filter><filter id="iAERgOO" width="1.444" height="3.775" x="24.962" y="17.226" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23857" stdDeviation=".125"/></filter><filter id="i0O2qdc" width="1.17" height="3.014" x="26.424" y="17.706" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23857" stdDeviation=".125"/></filter><filter id="il7bZzb" width="1.788" height="2.6" x="27.33" y="19.87" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23857" stdDeviation=".125"/></filter><filter id="is1eBoR" width="2.323" height="1.69" x="3.752" y="19.44" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23857" stdDeviation=".125"/></filter><filter id="ifoFGve" width="2.342" height="2.022" x="3.291" y="18.151" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23857" stdDeviation=".125"/></filter><filter id="iWZLRrf" width="2.131" height="2.124" x="4.556" y="16.714" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23857" stdDeviation=".125"/></filter><filter id="i07dZ8c" width="2.569" height="2.444" x="3.345" y="17.042" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23857" stdDeviation=".125"/></filter><filter id="iJqSyRb" width="3.705" height="3.505" x="10.068" y="12.441" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.866667 0 0 0 0 0.643137 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23857"/></filter><filter id="igPI4lc" width="3.089" height="3.089" x="10.276" y="12.649" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23857" stdDeviation=".25"/></filter><filter id="imUfcOl" width="3.755" height="3.755" x="20.054" y="12.191" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.768627 0 0 0 0 0.529412 0 0 0 0 0.505882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23857"/></filter><filter id="iG8sQwx" width="3.089" height="3.089" x="20.262" y="12.649" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23857" stdDeviation=".25"/></filter><filter id="iQQtIrd" width="10.889" height="12.775" x="11.389" y="8.29" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.752941 0 0 0 0 0.501961 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23857"/></filter><filter id="ilcTZKz" width="13.21" height="8.943" x="10.192" y="4.665" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.858824 0 0 0 0 0.690196 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23857"/></filter><filter id="iDqQTOo" width="3.347" height="4.314" x="14.879" y="13.019" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23857" stdDeviation=".375"/></filter><filter id="iw8X1ee" width="2.47" height="3.314" x="15.569" y="13.348" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23857" stdDeviation=".125"/></filter><filter id="iXCAkwb" width="3.115" height="1.946" x="18.045" y="10.383" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.262745 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23857"/></filter><filter id="ib5R8Sd" width="3.115" height="1.946" x="12.642" y="10.383" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.262745 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23857"/></filter><filter id="inLSeJb" width=".816" height=".721" x="18.325" y="13.021" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23857" stdDeviation=".05"/></filter><filter id="imfgWtb" width=".916" height=".939" x="19.212" y="13.105" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23857" stdDeviation=".1"/></filter><filter id="iwq9IZd" width="1.015" height="1.072" x="14.55" y="13.038" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23857" stdDeviation=".1"/></filter><filter id="iNcXKyb" width=".948" height=".729" x="13.752" y="13.012" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23857" stdDeviation=".05"/></filter><filter id="iQL9Wpd" width="3.191" height="1.702" x="17.922" y="10.527" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23857" stdDeviation=".25"/></filter><filter id="iC1WR9b" width="3.273" height="1.762" x="12.443" y="10.594" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23857" stdDeviation=".25"/></filter><linearGradient id="iK84mBb" x1="22.562" x2="21.812" y1="29.826" y2="29.826" gradientUnits="userSpaceOnUse"><stop class="fr__qmhjc"/><stop offset="1" class="gypp10kih"/></linearGradient><linearGradient id="iWCiqKd" x1="20.644" x2="21.062" y1="29.014" y2="29.014" gradientUnits="userSpaceOnUse"><stop class="hj-s-zboe"/><stop offset="1" class="s0umluqbl"/></linearGradient><linearGradient id="ipodSkc" x1="9.531" x2="4.906" y1="27.451" y2="27.451" gradientUnits="userSpaceOnUse"><stop class="sb-ednb_a"/><stop offset="1" class="v0501vbqa"/></linearGradient><linearGradient id="iXPTZOc" x1="9.75" x2="8.828" y1="27.076" y2="27.076" gradientUnits="userSpaceOnUse"><stop class="o_30au2yc"/><stop offset="1" class="c60cvac3k"/></linearGradient><linearGradient id="itP1zjc" x1="27.871" x2="22.844" y1="28.142" y2="28.142" gradientUnits="userSpaceOnUse"><stop class="i7zyuv8vr"/><stop offset=".907" class="qzhltkbuo"/></linearGradient><linearGradient id="i33ZCUz" x1="28.09" x2="27.168" y1="27.876" y2="27.876" gradientUnits="userSpaceOnUse"><stop class="tub8lbbfx"/><stop offset="1" class="bd09vtb_c"/></linearGradient><linearGradient id="i8tJXGc" x1="16.763" x2="16.763" y1="22.812" y2="24.81" gradientUnits="userSpaceOnUse"><stop offset=".351" class="gzsz7evmk"/><stop offset="1" class="smgiue0gi"/></linearGradient><linearGradient id="iPWzvjj" x1="29.13" x2="28.38" y1="20.034" y2="21.659" gradientUnits="userSpaceOnUse"><stop class="nisiqibvr"/><stop offset="1" class="nntb9stew"/></linearGradient><linearGradient id="i0gZ48c" x1="4.76" x2="5.331" y1="20.169" y2="21.223" gradientUnits="userSpaceOnUse"><stop class="efwa18n2a"/><stop offset="1" class="tsmwdfbse"/></linearGradient><linearGradient id="iF8fKMd" x1="4.307" x2="5.218" y1="19" y2="20.223" gradientUnits="userSpaceOnUse"><stop class="efwa18n2a"/><stop offset="1" class="tsmwdfbse"/></linearGradient><linearGradient id="impiaed" x1="5.489" x2="6.52" y1="17.6" y2="18.693" gradientUnits="userSpaceOnUse"><stop class="efwa18n2a"/><stop offset="1" class="tsmwdfbse"/></linearGradient><linearGradient id="iVWluoc" x1="4.452" x2="5.734" y1="18.044" y2="19.502" gradientUnits="userSpaceOnUse"><stop class="efwa18n2a"/><stop offset="1" class="tsmwdfbse"/></linearGradient><linearGradient id="iHVEK9d" x1="11.82" x2="11.148" y1="14.486" y2="14.486" gradientUnits="userSpaceOnUse"><stop class="s236rjbsc"/><stop offset="1" class="o6sle6pni"/></linearGradient><linearGradient id="ib5rLZU" x1="22.946" x2="22.087" y1="13.047" y2="15.71" gradientUnits="userSpaceOnUse"><stop class="kwz3apblc"/><stop offset="1" class="gx0xrfbie"/></linearGradient><linearGradient id="i7muuXV" x1="21.04" x2="13.024" y1="14.602" y2="15.797" gradientUnits="userSpaceOnUse"><stop class="b941pszbd"/><stop offset="1" class="jtnk9gb3a"/></linearGradient><linearGradient id="i4x8brd" x1="11.14" x2="13.567" y1="17.432" y2="17.116" gradientUnits="userSpaceOnUse"><stop class="ls27mhbfe"/><stop offset="1" class="ys1ri2qqc"/></linearGradient><linearGradient id="iZ3cL1c" x1="16.834" x2="16.834" y1="10.437" y2="12.001" gradientUnits="userSpaceOnUse"><stop offset=".229" class="u9kljibmk"/><stop offset="1" class="u3jpphbne"/></linearGradient><linearGradient id="ifhmc1d" x1="11.702" x2="14.748" y1="13.913" y2="8.502" gradientUnits="userSpaceOnUse"><stop class="ts8ii3fly"/><stop offset="1" class="zlpmx2b9v"/></linearGradient><linearGradient id="iGjcxHd" x1="15.897" x2="16.881" y1="15.294" y2="15.294" gradientUnits="userSpaceOnUse"><stop class="gs643vbjw"/><stop offset="1" class="v4v-qb7kx"/></linearGradient><linearGradient id="iHgScsc" x1="17.789" x2="16.712" y1="15.633" y2="15.617" gradientUnits="userSpaceOnUse"><stop class="sbp9bz1ap"/><stop offset="1" class="xrkexibub"/></linearGradient><linearGradient id="iZsWzAo" x1="17.008" x2="17.008" y1="16.412" y2="15.81" gradientUnits="userSpaceOnUse"><stop class="rxh459f4v"/><stop offset="1" class="lemuo5beu"/></linearGradient><linearGradient id="ilXDw6c" x1="16.936" x2="16.936" y1="16.456" y2="16.28" gradientUnits="userSpaceOnUse"><stop class="e14d05bbo"/><stop offset="1" class="jt8p4rb1c"/></linearGradient><linearGradient id="iLkIHAe" x1="15.715" x2="16.172" y1="18.107" y2="17.386" gradientUnits="userSpaceOnUse"><stop class="pn2_jabhi"/><stop offset=".663" class="z9945l-5h"/></linearGradient><linearGradient id="iwtw2Sc" x1="19.907" x2="19.578" y1="13.534" y2="13.737" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iYc8ehI" x1="15.292" x2="14.963" y1="13.534" y2="13.737" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iUxBSLe" x1="19.924" x2="19.483" y1="11.288" y2="10.387" gradientUnits="userSpaceOnUse"><stop class="pqf0u3bgb"/><stop offset="1" class="xogpiobqs"/></linearGradient><linearGradient id="iOTbDce" x1="14.356" x2="13.108" y1="11.154" y2="10.63" gradientUnits="userSpaceOnUse"><stop class="pqf0u3bgb"/><stop offset="1" class="xogpiobqs"/></linearGradient><linearGradient id="izP9Z9c" x1="16.773" x2="16.773" y1="7.912" y2="8.1" gradientUnits="userSpaceOnUse"><stop class="jhlen960d"/><stop offset="1" class="wjchuwb6a"/></linearGradient><linearGradient id="iYE2hsb" x1="17.956" x2="17.956" y1="10.98" y2="10.214" gradientUnits="userSpaceOnUse"><stop class="bl3fq0x9z"/><stop offset="1" class="lxo7c2i6k"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-juggling-medium-light" /></template>
<style>
.a5zzorbzd {
  stop-color: var(--svg-color--e1ac3a, #E1AC3A);
}

.ab6i82btp {
  stop-color: var(--svg-color--e7377c, #E7377C);
}

.admloybui {
  stop-color: var(--svg-color--d1938d, #D1938D);
  stop-opacity: 0;
}

.af8mzdbwl {
  stop-color: var(--svg-color--5f679a, #5F679A);
}

.aik_z9b6i {
  stop-color: var(--svg-color--c28775, #C28775);
}

.am6k_ubte {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-35px, 0.35px);
  d: path("M4.981 17.139c.11.172.625 1.078 1.282 1.273");
}

.aqzyd8bsb {
  stop-color: var(--svg-color--896bb4, #896BB4);
  stop-opacity: 0;
}

.auvn9fbbk {
  stop-color: var(--svg-color--e9387a, #E9387A);
}

.axsenyy_b {
  stop-color: var(--svg-color--c28d66, #C28D66);
}

.b057dp4eh {
  stop-color: var(--svg-color--ccbdde, #CCBDDE);
}

.b941pszbd {
  stop-color: var(--svg-color--fac39e, #FAC39E);
}

.bd09vtb_c {
  stop-color: var(--svg-color--e0dde3, #E0DDE3);
  stop-opacity: 0;
}

.bdk4dmb5b {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-35px, 0.35px);
  d: path("m28.692 20.295l-.937 1.75");
}

.bl3fq0x9z {
  stop-color: var(--svg-color--543459, #543459);
}

.bq5dgsbba {
  stop-color: var(--svg-color--dcc8ec, #DCC8EC);
}

.btor07b8q {
  stop-color: var(--svg-color--d61f4d, #D61F4D);
}

.bube3wtxx {
  d: path("M19.024 13.175c.067.09-.073.198-.231.317c-.159.118-.276.202-.343.112c-.067-.089.008-.257.166-.376c.159-.118.341-.142.408-.053");
}

.byn6wubog {
  fill: var(--svg-color--bc9ebb, #BC9EBB);
  fill-rule: evenodd;
  d: path("M16.899 24.871a.35.35 0 0 1-.266.244c-.25.048-.467.048-.717 0a.35.35 0 0 1-.262-.23c-.18.2-.49.432-1.009.607c-.31.106-.668.058-.833-.23a1.86 1.86 0 0 1-.245-.948c0-.431.124-.74.245-.95c.165-.287.523-.334.833-.23c.503.171.81.418.993.63a.35.35 0 0 1 .278-.293c.25-.048.467-.048.717 0a.35.35 0 0 1 .28.31c.18-.215.49-.47 1.008-.646c.31-.105.668-.058.834.23c.12.208.244.513.244.949s-.124.74-.244.949c-.166.287-.524.335-.834.23c-.531-.18-.844-.42-1.022-.622");
}

.c532_ht3q {
  fill: var(--svg-color--c68378, #C68378);
  d: path("m16.515 14.065l-.861 1.784c-.107.367.15.734.512.734h.774c.363 0 .619-.373.512-.734l-.523-1.784c-.112-.395-.297-.395-.414 0");
}

.c549xi8ae {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-35px, 0.35px);
  d: path("M3.77 17.467c.177.245.618 1.078 1.72 1.594");
}

.c60cvac3k {
  stop-color: var(--svg-color--e5ddee, #E5DDEE);
  stop-opacity: 0;
}

.c6833cb9x {
  stop-color: var(--svg-color--372f3c, #372F3C);
}

.ci3gi1b_k {
  stop-color: var(--svg-color--784b89, #784B89);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.ctsppjbax {
  d: path("M14.866 22.463c.91.308 1.268.83 1.389 1.082l.028.29l-.028.359c-.12.25-.48.706-1.389 1.014c-.36.123-.777.068-.97-.267a2.17 2.17 0 0 1-.285-1.105c0-.502.144-.862.285-1.106c.193-.335.61-.39.97-.267");
}

.ctupw6b3d {
  fill-rule: evenodd;
  d: path("M3.113 18.184a.75.75 0 0 1 1.042.196c.312.455.974 1.204 1.85 1.204a.75.75 0 1 1 0 1.5c-1.702 0-2.759-1.376-3.088-1.858a.75.75 0 0 1 .196-1.042");
}

.cy8y9p-pn {
  stop-color: var(--svg-color--daa781, #DAA781);
}

.d2yfm4wlm {
  fill: var(--svg-color--fff, #fff);
  d: path("M19.31 12.692c.686 0 1.264.472 1.422 1.111a.288.288 0 0 1-.281.358H18.11a.242.242 0 0 1-.239-.286a1.47 1.47 0 0 1 1.44-1.183");
}

.d5_x4xk7i {
  fill-rule: evenodd;
  d: path("M3.16 17.066a.75.75 0 0 1 1.042.197q.055.08.116.173c.17.259.379.576.676.877c.36.363.768.614 1.246.64a.75.75 0 0 1-.08 1.497c-.99-.052-1.73-.575-2.232-1.083c-.416-.42-.725-.893-.888-1.143l-.076-.115a.75.75 0 0 1 .196-1.043");
}

.d7caiobkz {
  stop-color: var(--svg-color--e4cc30, #E4CC30);
  stop-opacity: 0;
}

.demkpcl0k {
  stop-color: var(--svg-color--b1a0b8, #B1A0B8);
}

.don2wdpjw {
  cx: 16.761px;
  cy: 26.282px;
  r: 0.739px;
}

.dpmuo-biy {
  stop-color: var(--svg-color--6f5ea2, #6F5EA2);
}

.dukixxuqk {
  stroke: var(--svg-color--ddac99, #DDAC99);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-35px, 0.35px);
  d: path("m23.333 19.615l.414 1.64");
}

.duyhuibwk {
  cx: 9.246px;
  cy: 3.857px;
  r: 1.684px;
}

.e14d05bbo {
  stop-color: var(--svg-color--c27b77, #C27B77);
}

.efwa18n2a {
  stop-color: var(--svg-color--efbea6, #EFBEA6);
}

.ezktjkbgg {
  stop-color: var(--svg-color--d79a76, #D79A76);
  stop-opacity: 0;
}

.f21vmbcik {
  d: path("M5.437 21.764h4.094v8.063H5.437z");
}

.fde_fwzpt {
  stop-color: var(--svg-color--5c9946, #5C9946);
}

.fr__qmhjc {
  stop-color: var(--svg-color--7a6cad, #7A6CAD);
}

.ft5dv1b6b {
  fill: none;
}

.fxbge344d {
  stop-color: var(--svg-color--cb8d82, #CB8D82);
  stop-opacity: 0;
}

.fzq016boz {
  stop-color: var(--svg-color--e35838, #E35838);
}

.g7lt91bhf {
  stop-color: var(--svg-color--e3ab88, #E3AB88);
}

.g8uem1b5g {
  stop-color: var(--svg-color--38303e, #38303E);
  stop-opacity: 0;
}

.gfrsedb9v {
  stop-color: var(--svg-color--5b595e, #5B595E);
}

.ggm3_setj {
  d: path("m13.38 20.005l.612 3.22h4.946l.796-3.173a10.2 10.2 0 0 0-2.937-.429h-.64c-.963 0-1.894.133-2.777.382");
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.gr0wzobbs {
  stop-color: var(--svg-color--dbcdd4, #DBCDD4);
  stop-opacity: 0;
}

.gs643vbjw {
  stop-color: var(--svg-color--cb9173, #CB9173);
}

.gwm_2mjil {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-35px, 0.35px);
  d: path("M4.177 19.865c.177.245.832.742 1.472.84");
}

.gx0o3oiqw {
  stop-color: var(--svg-color--e3ab85, #E3AB85);
  stop-opacity: 0;
}

.gx0xrfbie {
  stop-color: var(--svg-color--dca189, #DCA189);
}

.gypp10kih {
  stop-color: var(--svg-color--7a6cad, #7A6CAD);
  stop-opacity: 0;
}

.gzsz7evmk {
  stop-color: var(--svg-color--eb3782, #EB3782);
}

.h2li0wblg {
  stop-color: var(--svg-color--d02759, #D02759);
}

.h4mko5b9o {
  stop-color: var(--svg-color--beb4c6, #BEB4C6);
  stop-opacity: 0;
}

.hcmh5c50b {
  stop-color: var(--svg-color--357ace, #357ACE);
}

.hj-s-zboe {
  stop-color: var(--svg-color--6d5096, #6D5096);
}

.hjrsfpbzk {
  stop-color: var(--svg-color--e7b594, #E7B594);
}

.hpfqe6rjh {
  cx: 6.332px;
  cy: 12.838px;
  r: 1.684px;
}

.hpjuubccm {
  stop-color: var(--svg-color--eec19c, #EEC19C);
  stop-opacity: 0;
}

.ht6lpfbpp {
  d: path("M18.68 22.463c-.909.308-1.267.83-1.388 1.082l-.028.29l.028.359c.12.25.48.706 1.388 1.014c.362.123.778.068.971-.267c.14-.243.284-.599.284-1.105c0-.507-.144-.862-.284-1.106c-.193-.335-.61-.39-.97-.267");
}

.hw860-bkw {
  d: path("M22.993 22.213c.119.463.586 1.456.805 1.894h4.047l-.258-3.789l-4.836.924c.031.13.123.507.242.97");
}

.i-duydtwp {
  cx: 11.82px;
  cy: 14.193px;
  r: 1.752px;
}

.i1-orb7ke {
  stop-color: var(--svg-color--c3b7c1, #C3B7C1);
}

.i4pfhbczn {
  stop-color: var(--svg-color--cb8e6d, #CB8E6D);
}

.i6dlqjbae {
  cx: 21.806px;
  cy: 14.193px;
  r: 1.044px;
}

.i7zyuv8vr {
  stop-color: var(--svg-color--ede7f3, #EDE7F3);
}

.i8j0jyb4u {
  stop-color: var(--svg-color--b8a734, #B8A734);
}

.i8skpb2jz {
  stop-color: var(--svg-color--5d5565, #5D5565);
}

.i9u4tf5-i {
  stop-color: var(--svg-color--cb8d82, #CB8D82);
}

.ivad9acsp {
  fill: var(--svg-color--e4ac8f, #E4AC8F);
  d: path("m16.403 13.894l-.558 1.784a.566.566 0 0 0 .546.734h.825c.387 0 .66-.373.547-.734l-.558-1.784c-.12-.395-.677-.395-.802 0");
}

.ivmi_zbqk {
  d: path("M19.093 12.977a.937.937 0 0 1 .902 1.184h-1.809a.94.94 0 0 1 .907-1.183");
}

.iwbygtbvw {
  cx: 25.211px;
  cy: 4.873px;
  r: 1.684px;
}

.j3anadbkm {
  stop-color: var(--svg-color--d79a76, #D79A76);
}

.j471ep9dt {
  stop-color: var(--svg-color--d5a186, #D5A186);
  stop-opacity: 0;
}

.j70rp9pis {
  d: path("M22.222 29.826h-1.578v-9.568q.826.307 1.578.746z");
}

.j8k1fac_p {
  stop-color: var(--svg-color--5b5a5d, #5B5A5D);
}

.jhlen960d {
  stop-color: var(--svg-color--745ba5, #745BA5);
}

.jjf293xlz {
  stop-color: var(--svg-color--d61f4d, #D61F4D);
  stop-opacity: 0;
}

.jm40s5baz {
  stop-color: var(--svg-color--968f9c, #968F9C);
  stop-opacity: 0;
}

.jrc-__bwk {
  fill: var(--svg-color--000, #000);
  d: path("M15.045 13.913a.534.534 0 0 0-.536-.536a.534.534 0 0 0-.477.783h.95a.5.5 0 0 0 .063-.247");
}

.jt8p4rb1c {
  stop-color: var(--svg-color--c27b77, #C27B77);
  stop-opacity: 0;
}

.jtnk9gb3a {
  stop-color: var(--svg-color--c9917c, #C9917C);
}

.jtrn8vb0v {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M13.068 11.73c.344-.303 1.094-.622 2.023-.474");
}

.k-ikuabgd {
  d: path("M6.803 17.694a.782.782 0 0 1 1.249-.94l.93 1.213c.337.438.519.975.519 1.527l-1.5-.18z");
}

.k1mq2zvhc {
  stop-color: var(--svg-color--ba7867, #BA7867);
}

.k9e4-bb7j {
  stop-color: var(--svg-color--d49a78, #D49A78);
}

.km6q7kb1a {
  stop-color: var(--svg-color--5d5565, #5D5565);
  stop-opacity: 0;
}

.kmrvduh9f {
  stop-color: var(--svg-color--ce9487, #CE9487);
  stop-opacity: 0;
}

.koq0r9bvu {
  stop-color: var(--svg-color--9e78c9, #9E78C9);
}

.ku63lg_wt {
  stop-color: var(--svg-color--e8e2ec, #E8E2EC);
}

.kwz3apblc {
  stop-color: var(--svg-color--f5c8a5, #F5C8A5);
}

.kxzxrmw_u {
  stop-color: var(--svg-color--fbecaf, #FBECAF);
}

.kzuil_5zu {
  stop-color: var(--svg-color--9072ca, #9072CA);
}

.l-r9gxb9g {
  stop-color: var(--svg-color--4bb8fb, #4BB8FB);
}

.l90-jebsc {
  d: path("m11.45 13.55l.052.002s-.056-.896-.113-1.512c0-.28.113-.615.338-.783l.17-.168c.28-.224.393-.56.393-.896v-.896c0-.28.17-.504.45-.56c.676-.168 2.084-.447 4.111-.447s3.435.28 4.11.447c.225.056.45.28.45.56v.896c0 .336.17.672.395.896c.527.369.494.572.45 1.007c-.056.56-.113 1.512-.113 1.512h.02l-.28 4.155c-.168 1.857-1.628 3.152-3.37 3.152h-3.37c-1.796 0-3.2-1.295-3.369-3.152z");
}

.ld_83jb7a {
  d: path("M16.018 23.224a.41.41 0 0 1 .328-.37a2.1 2.1 0 0 1 .834 0a.41.41 0 0 1 .328.37c.042.395.042.778 0 1.174a.41.41 0 0 1-.328.37c-.29.056-.544.056-.834 0a.41.41 0 0 1-.328-.37a5.5 5.5 0 0 1 0-1.174");
}

.lelj2r8dg {
  stop-color: var(--svg-color--9ae453, #9AE453);
}

.lemuo5beu {
  stop-color: var(--svg-color--c98583, #C98583);
  stop-opacity: 0;
}

.lgi0lwbjz {
  stop-color: var(--svg-color--775184, #775184);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.ls27mhbfe {
  stop-color: var(--svg-color--d99e84, #D99E84);
}

.ls62f1bvq {
  stop-color: var(--svg-color--e3ab85, #E3AB85);
}

.ltklaoqtr {
  d: path("M19.928 13.79a.9.9 0 0 0-.243-.485l-.273.299l.123.24z");
}

.lucypabyc {
  d: path("M14.545 18.417c0-.99.9-1.794 2.011-1.794s2.012.803 2.012 1.794v2.326c0 .99-.9 1.794-2.012 1.794c-1.11 0-2.011-.803-2.011-1.794z");
}

.lvd5l1bfv {
  stop-color: var(--svg-color--d29a87, #D29A87);
}

.lxo7c2i6k {
  stop-color: var(--svg-color--462f5a, #462F5A);
  stop-opacity: 0;
}

.lxw2rgt3i {
  stop-color: var(--svg-color--c7877f, #C7877F);
  stop-opacity: 0;
}

.m-1-e5bla {
  stop-color: var(--svg-color--fbf2f7, #FBF2F7);
}

.m5avsc_ef {
  stop-color: var(--svg-color--784b89, #784B89);
}

.m9gf32bwp {
  stop-color: var(--svg-color--d6d3d7, #D6D3D7);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mdzzfhz-x {
  fill: var(--svg-color--d59f8d, #D59F8D);
  d: path("M25.92 18.247a.668.668 0 1 1 1.316-.232l.34 2.222q.012.082.005.164l-.015.163c-.005.055-.002.11 0 .165c.016.295-.146.515-.454.557a.61.61 0 0 1-.68-.483z");
}

.mmq2utbuk {
  stop-color: var(--svg-color--cf8b51, #CF8B51);
}

.mpwbs5b3u {
  stop-color: var(--svg-color--ff894e, #FF894E);
}

.mra09yb-m {
  stroke: var(--svg-color--ddac99, #DDAC99);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-35px, 0.35px);
  d: path("m25.388 17.651l.593 2.925");
}

.n297mkbnr {
  stop-color: var(--svg-color--d6d3d7, #D6D3D7);
  stop-opacity: 0;
}

.nafyo8b5t {
  d: path("m21.862 7.394l-.056 2.15c.788.392 1.745-.638 1.576.313l-.619 3.191c-.055.33-.273.552-.6.56h-.02s.057-.952.113-1.511c.046-.455-.033-.594-.45-1.008c-.225-.224-.394-.56-.394-.896v-.896c0-.28-.225-.503-.45-.56c-.676-.167-2.084-.447-4.11-.447c-2.028 0-3.435.28-4.11.448a.546.546 0 0 0-.451.56v.895c0 .336-.113.672-.395.896l-.168.168c-.226.168-.338.504-.338.784c.056.615.112 1.511.112 1.511q-.026 0-.051-.002a.665.665 0 0 1-.624-.558l-.62-3.19c-.112-.896.395.134 1.183-.258l.394-2.15c.281-.168.563-.392.845-.616l1.013-1.063c.62-.56 1.52-.728 2.308-.336a3.1 3.1 0 0 0 1.746 0c.844-.28 1.801-.056 2.477.56l.845.84c.225.28.506.447.844.615");
}

.ng1cexbhj {
  stop-color: var(--svg-color--b6424c, #B6424C);
}

.nisiqibvr {
  stop-color: var(--svg-color--efc0a4, #EFC0A4);
}

.nke1727fd {
  stop-color: var(--svg-color--c7877f, #C7877F);
}

.nl0wbpawx {
  stop-color: var(--svg-color--968f9c, #968F9C);
}

.nntb9stew {
  stop-color: var(--svg-color--efc0a4, #EFC0A4);
  stop-opacity: 0;
}

.o_30au2yc {
  stop-color: var(--svg-color--decfd8, #DECFD8);
}

.o1l1clgsm {
  fill: var(--svg-color--ebcc94, #EBCC94);
  d: path("m21.862 7.394l-.056 2.15c.788.392 1.745-.638 1.576.313l-.619 3.191c-.055.33-.273.552-.6.56h-.02s.057-.952.113-1.511c.046-.455-.033-.594-.45-1.008c-.225-.224-.394-.56-.394-.896v-.896c0-.28-.225-.503-.45-.56c-.676-.167-2.084-.447-4.11-.447c-2.028 0-3.435.28-4.11.448a.546.546 0 0 0-.451.56v.895c0 .336-.113.672-.395.896l-.168.168c-.226.168-.338.504-.338.784c.056.615.112 1.511.112 1.511q-.026 0-.051-.002a.665.665 0 0 1-.624-.558l-.62-3.19c-.112-.896.395.134 1.183-.258l.394-2.15c.281-.168.563-.392.845-.616l1.013-1.063c.62-.56 1.52-.728 2.308-.336a3.1 3.1 0 0 0 1.746 0c.844-.28 1.801-.056 2.477.56l.845.84c.225.28.506.447.844.615");
}

.o415o878f {
  stop-color: var(--svg-color--ef4c8b, #EF4C8B);
}

.o6sle6pni {
  stop-color: var(--svg-color--b87862, #B87862);
}

.ocnjw0b9f {
  d: path("M14.51 12.977a.937.937 0 0 0-.903 1.184h1.81a1 1 0 0 0 .033-.247a.943.943 0 0 0-.94-.937");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ok2r3obil {
  stop-color: var(--svg-color--634d93, #634D93);
}

.okwd93kys {
  width: 15.516px;
  height: 1.742px;
  x: 9.003px;
  y: 9.238px;
  rx: 0.871px;
}

.op2kwubyv {
  stop-color: var(--svg-color--e2a18c, #E2A18C);
}

.pb6efmson {
  stop-color: var(--svg-color--d72c5e, #D72C5E);
}

.pdm4p_b5q {
  stop-color: var(--svg-color--e6b298, #E6B298);
  stop-opacity: 0;
}

.pdpzp9ejr {
  fill: var(--svg-color--88024e, #88024E);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M15.373 17.09a.21.21 0 0 0-.251.043a.194.194 0 0 0-.021.249c.36.546.988.91 1.703.91s1.343-.365 1.703-.91a.196.196 0 0 0-.022-.251a.21.21 0 0 0-.25-.041a3.1 3.1 0 0 1-1.431.339a3.1 3.1 0 0 1-1.431-.339Z");
}

.pgmlwohvs {
  cx: 14.227px;
  cy: 13.377px;
  rx: 0.409px;
  ry: 0.207px;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pn2_jabhi {
  stop-color: var(--svg-color--d79e8e, #D79E8E);
}

.ppr920emc {
  stop-color: var(--svg-color--61a150, #61A150);
  stop-opacity: 0;
}

.pqf0u3bgb {
  stop-color: var(--svg-color--a57146, #A57146);
}

.pt8frltpn {
  stop-color: var(--svg-color--7060a5, #7060A5);
}

.qaglwccub {
  cx: 21.806px;
  cy: 14.193px;
  r: 1.752px;
}

.qr4y5_b5k {
  fill: var(--svg-color--000, #000);
  d: path("M18.557 13.913c0-.298.238-.536.536-.536a.534.534 0 0 1 .477.783h-.95a.5.5 0 0 1-.064-.247");
}

.qsu4qbckq {
  stop-color: var(--svg-color--dbcdd4, #DBCDD4);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qy4rrcb8b {
  d: path("M12.857 29.826h-1.578v-8.795a10 10 0 0 1 1.578-.756z");
}

.qyobb4hvj {
  stop-color: var(--svg-color--ffffc2, #FFFFC2);
}

.qzd219blo {
  d: path("M11 8.662a5.773 5.773 0 1 1 11.547 0v1.648H11z");
}

.qzhltkbuo {
  stop-color: var(--svg-color--b9aac8, #B9AAC8);
}

.rxh459f4v {
  stop-color: var(--svg-color--c98583, #C98583);
}

.s0pz40q7h {
  stop-color: var(--svg-color--b76d71, #B76D71);
}

.s0umluqbl {
  stop-color: var(--svg-color--7160a4, #7160A4);
  stop-opacity: 0;
}

.s236rjbsc {
  stop-color: var(--svg-color--af6f5d, #AF6F5D);
}

.sawf8hb2n {
  stop-color: var(--svg-color--ef4c8b, #EF4C8B);
  stop-opacity: 0;
}

.sb-ednb_a {
  stop-color: var(--svg-color--ece4f4, #ECE4F4);
}

.sbp9bz1ap {
  stop-color: var(--svg-color--fec8a4, #FEC8A4);
}

.scbqttb8d {
  stop-color: var(--svg-color--ec4182, #EC4182);
}

.smgiue0gi {
  stop-color: var(--svg-color--c93857, #C93857);
}

.sqw7shfwy {
  stop-color: var(--svg-color--f1bea0, #F1BEA0);
}

.ss_mx3bgz {
  stop-color: var(--svg-color--b56f7c, #B56F7C);
}

.sty1w-bnq {
  fill: var(--svg-color--d59f8d, #D59F8D);
  d: path("M22.414 19.881a.681.681 0 1 1 1.33-.294l.36 1.794a.645.645 0 0 1-1.26.279z");
}

.swka_j87x {
  d: path("M6.25 29.826c0-5.635 4.568-10.203 10.203-10.203h.64c5.636 0 10.204 4.568 10.204 10.203z");
}

.szm1jtb2t {
  stop-color: var(--svg-color--ffffc2, #FFFFC2);
  stop-opacity: 0;
}

.t-5nldk3g {
  cx: 16.761px;
  cy: 28.296px;
  r: 0.739px;
}

.t-r3m-b0n {
  stop-color: var(--svg-color--d69f8b, #D69F8B);
}

.t5ih6_hjp {
  fill: var(--svg-color--f2bfa1, #F2BFA1);
  d: path("m27.85 19.83l-.447.824l-1.172 1.422l-1.481 1.992l3.099.047c.099-.172.218-.566.38-1.327c.164-.66.326-1.114.471-1.376l.443-.924a.726.726 0 0 0-1.292-.659");
}

.tbh7zobro {
  cx: 14.227px;
  cy: 13.377px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.409px;
  ry: 0.207px;
}

.te2y3cbdr {
  stop-color: var(--svg-color--ce9487, #CE9487);
}

.tg07-ljnl {
  stop-color: var(--svg-color--5e5764, #5E5764);
}

.tn_97qkdc {
  stop-color: var(--svg-color--f2c341, #F2C341);
  stop-opacity: 0;
}

.tr5270bph {
  fill: var(--svg-color--9a6634, #9A6634);
  d: path("M20.708 11.338h-.001l-.002-.002l-.005-.004l-.012-.01a2 2 0 0 0-.163-.113a2.7 2.7 0 0 0-.44-.221a3 3 0 0 0-1.567-.166a.56.56 0 1 0 .174 1.106c.418-.066.752.011.98.102a1.6 1.6 0 0 1 .316.167l.008.006a.56.56 0 0 0 .712-.865");
}

.ts8ii3fly {
  stop-color: var(--svg-color--e8ad8e, #E8AD8E);
}

.tsmwdfbse {
  stop-color: var(--svg-color--efbea6, #EFBEA6);
  stop-opacity: 0;
}

.tub8lbbfx {
  stop-color: var(--svg-color--e0dde3, #E0DDE3);
}

.tvoyviyhj {
  stop-color: var(--svg-color--775184, #775184);
}

.twba206ho {
  d: path("M5.963 18.892a.88.88 0 0 0-.37.74v2.108l.618.04h3.302v-2.33c0-.836-.805-1.25-1.97-1.148c-.655.057-1.208.34-1.58.589");
}

.tx50jtscj {
  stroke: var(--svg-color--ddac99, #DDAC99);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-35px, 0.35px);
  d: path("m24.357 18.55l.437 2.128");
}

.u1gl_1zha {
  stop-color: var(--svg-color--ec4182, #EC4182);
  stop-opacity: 0;
}

.u3jpphbne {
  stop-color: var(--svg-color--ba7e6e, #BA7E6E);
  stop-opacity: 0;
}

.u47ww4b8k {
  stroke: var(--svg-color--ddac99, #DDAC99);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-35px, 0.35px);
  d: path("m26.849 18.13l.32 2.165");
}

.u6lph46no {
  stop-color: var(--svg-color--f0dff0, #F0DFF0);
}

.u7v6tactn {
  stop-color: var(--svg-color--eec19c, #EEC19C);
}

.u9kljibmk {
  stop-color: var(--svg-color--ba7e6e, #BA7E6E);
}

.ujrq6ixuu {
  stop-color: var(--svg-color--beb4c6, #BEB4C6);
}

.unksyib4v {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M19.024 13.175c.067.09-.073.198-.231.317c-.159.118-.276.202-.343.112c-.067-.089.008-.257.166-.376c.159-.118.341-.142.408-.053");
}

.uylyaxbnq {
  stop-color: var(--svg-color--c2837a, #C2837A);
  stop-opacity: 0;
}

.v0501vbqa {
  stop-color: var(--svg-color--c0b5cd, #C0B5CD);
}

.v4v-qb7kx {
  stop-color: var(--svg-color--cb9173, #CB9173);
  stop-opacity: 0;
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.vdngsab5t {
  fill-rule: evenodd;
  d: path("M3.416 19.34a.75.75 0 0 1 1.051.14c.244.317.833.881 1.8.881a.75.75 0 0 1 .75.75c0 .415-.336.67-.75.67c-1.683 0-2.593-.87-2.99-1.39a.75.75 0 0 1 .139-1.05");
}

.vfp25y1ae {
  stop-color: var(--svg-color--cf9080, #CF9080);
}

.vke6kh8bt {
  stop-color: var(--svg-color--3e3843, #3E3843);
  stop-opacity: 0;
}

.vs8934bpj {
  stop-color: var(--svg-color--fbecaf, #FBECAF);
  stop-opacity: 0;
}

.vvfum-_fa {
  stop-color: var(--svg-color--392f42, #392F42);
}

.vwohnyejo {
  cx: 11.82px;
  cy: 14.193px;
  r: 1.044px;
}

.vxe5hyz_v {
  stop-color: var(--svg-color--dfad8b, #DFAD8B);
}

.w3oseebkq {
  stop-color: var(--svg-color--f5c5a6, #F5C5A6);
}

.w63qn2bkh {
  stop-color: var(--svg-color--605966, #605966);
}

.wfgw5ub6b {
  fill-rule: evenodd;
  d: path("M4.273 16.754a.75.75 0 0 1 1.042.196q.091.134.166.258c.141.228.267.432.519.637c.292.238.794.485 1.747.42a.75.75 0 1 1 .102 1.497c-1.29.088-2.178-.25-2.796-.754c-.478-.389-.78-.89-.917-1.116l-.059-.096a.75.75 0 0 1 .196-1.042");
}

.wjchuwb6a {
  stop-color: var(--svg-color--745ba5, #745BA5);
  stop-opacity: 0;
}

.wozepxbaa {
  d: path("M11.048 7.912a6 6 0 0 0-.048.75v1.648h11.547V8.663q0-.381-.049-.75z");
}

.wp2p6dbcv {
  d: path("M23.777 24.107h4.094v5.719h-4.094z");
}

.wpznbn7xg {
  fill: var(--svg-color--fff, #fff);
  d: path("M14.292 12.692c-.686 0-1.265.473-1.422 1.111a.288.288 0 0 0 .28.358h2.342a.242.242 0 0 0 .239-.286a1.47 1.47 0 0 0-1.44-1.183");
}

.wshx69b-y {
  stop-color: var(--svg-color--896bb4, #896BB4);
}

.wvivicznw {
  stop-color: var(--svg-color--e2a18c, #E2A18C);
  stop-opacity: 0;
}

.wy1rn8btp {
  d: path("m16.403 13.894l-.558 1.784a.566.566 0 0 0 .546.734h.825c.387 0 .66-.373.547-.734l-.558-1.784c-.12-.395-.677-.395-.802 0");
}

.x0-6qkygn {
  cx: 21.806px;
  cy: 14.193px;
  r: 1.044px;
  fill: var(--svg-color--d79e81, #D79E81);
}

.x1l7xqbyw {
  stop-color: var(--svg-color--de5534, #DE5534);
  stop-opacity: 0;
}

.xjk10obil {
  stop-color: var(--svg-color--cb8e6d, #CB8E6D);
  stop-opacity: 0;
}

.xmtjwwq5j {
  d: path("M15.365 13.804c0-.303-.246-.505-.312-.566l-.303.293l.186.38z");
}

.xntzq-4ho {
  stop-color: var(--svg-color--8566b5, #8566B5);
}

.xogpiobqs {
  stop-color: var(--svg-color--a57146, #A57146);
  stop-opacity: 0;
}

.xrkexibub {
  stop-color: var(--svg-color--fec8a4, #FEC8A4);
  stop-opacity: 0;
}

.xrxxjybof {
  fill: var(--svg-color--9a6634, #9A6634);
  d: path("M12.843 11.339h.002l.002-.002l.004-.004l.013-.01a2 2 0 0 1 .163-.113c.104-.066.252-.147.44-.221a3 3 0 0 1 1.567-.166a.56.56 0 1 1-.175 1.106a1.85 1.85 0 0 0-.98.102a1.6 1.6 0 0 0-.323.173a.56.56 0 0 1-.713-.864");
}

.xwse_esww {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M18.547 11.187c.451-.08 1.331-.057 1.941.417");
}

.y_auwli2s {
  stop-color: var(--svg-color--415e58, #415E58);
}

.y-1rsmdul {
  stop-color: var(--svg-color--3a7ab4, #3A7AB4);
  stop-opacity: 0;
}

.y05rrkbkk {
  stop-color: var(--svg-color--ffff54, #FFFF54);
}

.y2ly1lryk {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-35px, 0.35px);
  d: path("M3.716 18.576c.177.245.672.953 1.492 1.172");
}

.y7nn5tbfc {
  stop-color: var(--svg-color--c2837a, #C2837A);
}

.ym-b_m9fy {
  stop-color: var(--svg-color--d1bed4, #D1BED4);
  stop-opacity: 0;
}

.ys1ri2qqc {
  stop-color: var(--svg-color--d99e84, #D99E84);
  stop-opacity: 0;
}

.z9945l-5h {
  stop-color: var(--svg-color--d79e8e, #D79E8E);
  stop-opacity: 0;
}

.z9b4pwbpg {
  fill: var(--svg-color--d59f8d, #D59F8D);
  d: path("M23.407 18.803a.679.679 0 1 1 1.323-.298l.555 2.766a.613.613 0 0 1-1.195.27z");
}

.zdcorrl9x {
  cx: 26.234px;
  cy: 14.83px;
  r: 1.684px;
}

.ze1cb0iau {
  stop-color: var(--svg-color--e3ab88, #E3AB88);
  stop-opacity: 0;
}

.zlpmx2b9v {
  stop-color: var(--svg-color--e8ad8e, #E8AD8E);
  stop-opacity: 0;
}

.znvzi0b9x {
  fill: var(--svg-color--d59f8d, #D59F8D);
  d: path("M24.458 17.959a.68.68 0 0 1 .568-.843l.023-.003a.68.68 0 0 1 .756.54l.622 3.039c.071.355-.246.42-.606.458c-.303.032-.553-.005-.629-.3z");
}

</style>
