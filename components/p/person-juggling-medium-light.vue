<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#i3HEF7c)"><path fill="url(#iPYYWhe)" class="swka_j87x"/><path fill="url(#iT07jwd)" class="swka_j87x"/><path fill="url(#il5eVUq)" class="swka_j87x"/><path fill="url(#iY3yYtd)" class="swka_j87x"/><path fill="url(#iv8FoOX)" class="swka_j87x"/></g><circle fill="url(#iBZ0RUd)" class="hpfqe6rjh"/><circle fill="url(#itKlKTd)" class="hpfqe6rjh"/><circle fill="url(#ihlr5IT)" class="duyhuibwk"/><circle fill="url(#iGUmgWd)" class="duyhuibwk"/><circle fill="url(#iXhqZHd)" class="iwbygtbvw"/><circle fill="url(#iOHvRJe)" class="iwbygtbvw"/><circle fill="url(#issuNue)" class="zdcorrl9x"/><circle fill="url(#iMaLBhb)" class="zdcorrl9x"/><circle fill="url(#iAhrvZc)" class="zdcorrl9x"/><g filter="url(#imcZNTc)"><circle fill="url(#iMk8UMb)" class="t-5nldk3g"/></g><g filter="url(#iDpSrcd)"><circle fill="url(#iR23Gge)" class="don2wdpjw"/></g><path fill="url(#i5YvaPc)" class="j70rp9pis"/><path fill="url(#iK84mBb)" class="j70rp9pis"/><path fill="url(#iWCiqKd)" class="j70rp9pis"/><path fill="url(#ieol8Me)" class="qy4rrcb8b"/><path fill="url(#iDbbcbc)" class="qy4rrcb8b"/><path fill="url(#iOe2zrd)" class="qy4rrcb8b"/><path fill="url(#iV71Rbc)" class="qy4rrcb8b"/><g filter="url(#iUTOU2c)"><path fill="url(#ih8Nxde)" class="kzmu-rrsy"/><path fill="url(#iQpTAtb)" class="kzmu-rrsy"/></g><path fill="url(#ipodSkc)" class="f21vmbcik"/><path fill="url(#iXPTZOc)" class="f21vmbcik"/><path fill="url(#itP1zjc)" class="wp2p6dbcv"/><path fill="url(#i33ZCUz)" class="wp2p6dbcv"/><g filter="url(#icryIbZ)"><path clip-rule="evenodd" class="byn6wubog"/></g><g filter="url(#i79l56d)"><path fill="url(#iSAsI1d)" class="ctsppjbax"/><path fill="url(#iwtPTOo)" class="ctsppjbax"/><path fill="url(#isAdhHe)" class="ctsppjbax"/></g><g filter="url(#ijpLIJX)"><path fill="url(#ivLP6Gc)" class="ht6lpfbpp"/><path fill="url(#iXetYud)" class="ht6lpfbpp"/></g><g filter="url(#iT8RStd)"><path fill="url(#i8tJXGc)" class="ld_83jb7a"/><path fill="url(#iw9bnJb)" class="ld_83jb7a"/></g><g filter="url(#iwRGFMd)"><path class="t5ih6_hjp"/></g><g filter="url(#ipUuTbb)"><path class="mdzzfhz-x"/></g><g filter="url(#irIWLmd)"><path class="znvzi0b9x"/></g><g filter="url(#isyFsjb)"><path class="z9b4pwbpg"/></g><g filter="url(#ieTIx5d)"><path class="sty1w-bnq"/></g><path fill="url(#i9aB4nd)" class="hw860-bkw"/><path fill="url(#i1P2OKg)" class="hw860-bkw"/><path fill="url(#iQvGmfb)" class="hw860-bkw"/><g filter="url(#irDuBkb)"><path fill="url(#iH4w94w)" class="k-ikuabgd"/></g><path fill="url(#icc9pKv)" clip-rule="evenodd" class="wfgw5ub6b"/><path fill="url(#iWgnezd)" clip-rule="evenodd" class="wfgw5ub6b"/><path fill="url(#ivI3iyH)" clip-rule="evenodd" class="d5_x4xk7i"/><path fill="url(#inrNF9c)" clip-rule="evenodd" class="d5_x4xk7i"/><path fill="url(#iBFjJkb)" clip-rule="evenodd" class="ctupw6b3d"/><path fill="url(#iGp04ob)" clip-rule="evenodd" class="ctupw6b3d"/><path fill="url(#i64UBtb)" clip-rule="evenodd" class="vdngsab5t"/><path fill="url(#ioxxPTd)" clip-rule="evenodd" class="vdngsab5t"/><path fill="url(#ixRckpe)" class="twba206ho"/><path fill="url(#i7tW1rc)" class="twba206ho"/><path fill="url(#iU8PPyb)" class="k1soseb1u"/><g filter="url(#iq9YsHc)"><path class="dukixxuqk"/></g><g filter="url(#inbCgCe)"><path class="rwc5yskns"/></g><g filter="url(#i7Y4Fmc)"><path class="mra09yb-m"/></g><g filter="url(#i769qrc)"><path class="u47ww4b8k"/></g><g filter="url(#iYTt9lc)"><path stroke="url(#iPWzvjj)" class="bdk4dmb5b"/></g><g filter="url(#iNcdGUc)"><path stroke="url(#i0gZ48c)" class="gwm_2mjil"/></g><g filter="url(#ipUi5nd)"><path stroke="url(#iF8fKMd)" class="y2ly1lryk"/></g><g filter="url(#ivwjvhd)"><path stroke="url(#impiaed)" class="am6k_ubte"/></g><g filter="url(#iTOSvme)"><path stroke="url(#iVWluoc)" class="c549xi8ae"/></g><path fill="url(#iYUQPDe)" class="du90idbgf"/><path fill="url(#i9iLj3K)" class="e-7ijsrnh"/><path fill="url(#iUMaHle)" class="e-7ijsrnh"/><path fill="url(#i9iLj3K)" class="e-7ijsrnh"/><path fill="url(#iUMaHle)" class="e-7ijsrnh"/><g filter="url(#iH4smzd)"><path fill="url(#iGnxQgc)" class="derevsb3o"/></g><path fill="url(#iehsJjb)" class="derevsb3o"/><path fill="url(#ipSuSFb)" class="derevsb3o"/><path fill="url(#iJ8XMja)" class="derevsb3o"/><path fill="url(#iVKJwGe)" class="derevsb3o"/><path fill="url(#idzwV5b)" class="derevsb3o"/><path fill="url(#iPOEWkd)" class="derevsb3o"/><path fill="url(#iuAsfmb)" class="derevsb3o"/><path fill="url(#iQqLQ7b)" class="derevsb3o"/><path fill="url(#ixxjdgd)" class="derevsb3o"/><g filter="url(#iJMUa3d)"><path class="wo_5cacau"/></g><g filter="url(#ijWKwZb)"><path fill="url(#iJo6mAc)" class="h4idlt2gd"/><path fill="url(#ikgchhY)" class="h4idlt2gd"/><path fill="url(#i1MO9II)" class="h4idlt2gd"/><path fill="url(#iTIu5ed)" class="h4idlt2gd"/></g><path fill="url(#i00dDJb)" class="h4idlt2gd"/><path fill="url(#izU4rgb)" class="h4idlt2gd"/><g filter="url(#im4E2Rc)"><path stroke="url(#iXDBSFd)" class="kmbhmlbpq"/></g><path fill="url(#i4A0yIq)" class="h1eb-9w6a"/><g filter="url(#in3VXsc)"><path fill="url(#i0GZDsc)" class="zjlswjibr"/><path fill="url(#iNb7W8c)" class="zjlswjibr"/><path fill="url(#ixKY07c)" class="zjlswjibr"/><path fill="url(#i2rySDe)" class="zjlswjibr"/><path fill="url(#ieDoGGc)" class="zjlswjibr"/></g><g filter="url(#iWAXSnq)"><path class="y96ok7g9l"/></g><g filter="url(#i9NYfwe)"><path class="uvn2r8etf"/></g><path class="dgzu5db3n"/><path fill="url(#id5KnVd)" class="oho74r4oa"/><path class="s41w2e12o"/><g filter="url(#i6N961b)"><path class="htxt4vb0r"/><path fill="url(#isyQvBc)" class="f9v3rqbpn"/></g><g filter="url(#ihgaPIe)"><path fill="url(#ik5EWMx)" class="z07pf-z8p"/></g><path class="uvus49ufr"/><path fill="url(#ikza4sd)" class="b1di2kckx"/><path class="jbgwdcjxl"/><g filter="url(#iVwLZUc)"><path fill="url(#ipvIrjd)" class="mjpr9nbsy"/></g><g filter="url(#ik7jZid)"><ellipse transform="rotate(-27.914 14.17 13.253)" class="aowey9psm"/><ellipse fill="url(#iRFS3ub)" transform="rotate(-27.914 14.17 13.253)" class="f2ij-hb4f"/></g><path fill="url(#ig2rDbe)" class="pg10zvsnt"/><path fill="url(#iOJj3Dd)" class="pg10zvsnt"/><path fill="url(#iagbZRc)" class="pg10zvsnt"/><path fill="url(#i0qgP0S)" class="jfld74b3f"/><path fill="url(#iicq4Nc)" class="jfld74b3f"/><g filter="url(#ikIgMCc)"><path class="o8dampt4k"/></g><g filter="url(#iY8bSKV)"><path class="ibjeao4zu"/></g><g filter="url(#i7xsfZc)"><path class="iew71gb4d"/></g><g filter="url(#iPGSEsO)"><path class="cm6u1gkbw"/></g><path fill="url(#iMwhdrV)" class="qzd219blo"/><path fill="url(#i3dSYhb)" class="qzd219blo"/><path fill="url(#inl9J2c)" class="qzd219blo"/><path fill="url(#iCE2gke)" class="wozepxbaa"/><path fill="url(#izP9Z9c)" class="wozepxbaa"/><rect fill="url(#ixSAAAe)" class="okwd93kys"/><rect fill="url(#iy7tjOa)" class="okwd93kys"/><rect fill="url(#iYE2hsb)" class="okwd93kys"/><defs><radialGradient id="iPYYWhe" cx="0" cy="0" r="1" gradientTransform="rotate(135.22 8.643 15.887)scale(12.9545 12.5552)" gradientUnits="userSpaceOnUse"><stop offset=".195" class="m-1-e5bla"/><stop offset=".794" class="b057dp4eh"/></radialGradient><radialGradient id="iT07jwd" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.09375 -3.28125 0 20.219 20.139)" gradientUnits="userSpaceOnUse"><stop class="m9gf32bwp"/><stop offset="1" class="n297mkbnr"/></radialGradient><radialGradient id="il5eVUq" cx="0" cy="0" r="1" gradientTransform="matrix(-1.75 0 0 -11.7187 21 25.92)" gradientUnits="userSpaceOnUse"><stop offset=".214" class="demkpcl0k"/><stop offset="1" class="ym-b_m9fy"/></radialGradient><radialGradient id="iY3yYtd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.15625 0 0 -5.75902 11.656 25.326)" gradientUnits="userSpaceOnUse"><stop class="ujrq6ixuu"/><stop offset="1" class="h4mko5b9o"/></radialGradient><radialGradient id="iv8FoOX" cx="0" cy="0" r="1" gradientTransform="matrix(2.12502 5.34374 -11.023 4.38346 13.099 18.733)" gradientUnits="userSpaceOnUse"><stop class="nl0wbpawx"/><stop offset="1" class="jm40s5baz"/></radialGradient><radialGradient id="iBZ0RUd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.34375 2.4375 -2.36069 -1.3014 7.187 11.826)" gradientUnits="userSpaceOnUse"><stop offset=".077" class="l-r9gxb9g"/><stop offset="1" class="hcmh5c50b"/></radialGradient><radialGradient id="itKlKTd" cx="0" cy="0" r="1" gradientTransform="rotate(115.145 -.151 8.247)scale(3.38309 2.95533)" gradientUnits="userSpaceOnUse"><stop offset=".452" class="y-1rsmdul"/><stop offset=".826" class="af8mzdbwl"/></radialGradient><radialGradient id="ihlr5IT" cx="0" cy="0" r="1" gradientTransform="matrix(-1.34375 2.4375 -2.36069 -1.3014 10.101 2.846)" gradientUnits="userSpaceOnUse"><stop offset=".077" class="mpwbs5b3u"/><stop offset="1" class="fzq016boz"/></radialGradient><radialGradient id="iGUmgWd" cx="0" cy="0" r="1" gradientTransform="rotate(115.145 4.158 4.683)scale(3.38309 2.95533)" gradientUnits="userSpaceOnUse"><stop offset=".452" class="x1l7xqbyw"/><stop offset=".826" class="ng1cexbhj"/></radialGradient><radialGradient id="iXhqZHd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.34375 2.4375 -2.36069 -1.3014 26.066 3.861)" gradientUnits="userSpaceOnUse"><stop offset=".077" class="lelj2r8dg"/><stop offset="1" class="fde_fwzpt"/></radialGradient><radialGradient id="iOHvRJe" cx="0" cy="0" r="1" gradientTransform="rotate(105.03 11.36 11.751)scale(3.49455 3.40391)" gradientUnits="userSpaceOnUse"><stop offset=".375" class="ppr920emc"/><stop offset=".826" class="y_auwli2s"/></radialGradient><radialGradient id="issuNue" cx="0" cy="0" r="1" gradientTransform="matrix(-1.34375 2.4375 -2.36069 -1.3014 27.09 13.818)" gradientUnits="userSpaceOnUse"><stop offset=".077" class="y05rrkbkk"/><stop offset="1" class="a5zzorbzd"/></radialGradient><radialGradient id="iMaLBhb" cx="0" cy="0" r="1" gradientTransform="matrix(1 1.07812 -1.5877 1.47265 24.969 13.357)" gradientUnits="userSpaceOnUse"><stop class="i8j0jyb4u"/><stop offset="1" class="d7caiobkz"/></radialGradient><radialGradient id="iAhrvZc" cx="0" cy="0" r="1" gradientTransform="rotate(109.11 8.51 16.52)scale(3.46022 3.37046)" gradientUnits="userSpaceOnUse"><stop offset=".347" class="tn_97qkdc"/><stop offset=".829" class="mmq2utbuk"/></radialGradient><radialGradient id="iMk8UMb" cx="0" cy="0" r="1" gradientTransform="matrix(-.7578 1.14063 -.96756 -.64282 17.25 27.855)" gradientUnits="userSpaceOnUse"><stop offset=".212" class="u6lph46no"/><stop offset="1" class="bq5dgsbba"/></radialGradient><radialGradient id="iR23Gge" cx="0" cy="0" r="1" gradientTransform="matrix(-.7578 1.14063 -.96756 -.64282 17.25 25.842)" gradientUnits="userSpaceOnUse"><stop offset=".212" class="u6lph46no"/><stop offset="1" class="bq5dgsbba"/></radialGradient><radialGradient id="i5YvaPc" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.03125 -2.40212 0 22.222 20.983)" gradientUnits="userSpaceOnUse"><stop class="koq0r9bvu"/><stop offset="1" class="dpmuo-biy"/></radialGradient><radialGradient id="ieol8Me" cx="0" cy="0" r="1" gradientTransform="scale(1.38818 6.1875)rotate(90 2.761 6.5)" gradientUnits="userSpaceOnUse"><stop class="xntzq-4ho"/><stop offset="1" class="pt8frltpn"/></radialGradient><radialGradient id="iDbbcbc" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.25 -.60938 0 13.062 24.108)" gradientUnits="userSpaceOnUse"><stop class="wshx69b-y"/><stop offset="1" class="aqzyd8bsb"/></radialGradient><radialGradient id="iOe2zrd" cx="0" cy="0" r="1" gradientTransform="matrix(2.9375 -7.98881 7.06186 2.59666 10.312 28.264)" gradientUnits="userSpaceOnUse"><stop offset=".724" class="lgi0lwbjz"/><stop offset="1" class="tvoyviyhj"/></radialGradient><radialGradient id="iV71Rbc" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.42188 -.18506 0 12.857 21.717)" gradientUnits="userSpaceOnUse"><stop class="m5avsc_ef"/><stop offset="1" class="ci3gi1b_k"/></radialGradient><radialGradient id="ih8Nxde" cx="0" cy="0" r="1" gradientTransform="matrix(-3.90624 2.42972 -4.28692 -6.89204 19.265 20.795)" gradientUnits="userSpaceOnUse"><stop class="ku63lg_wt"/><stop offset="1" class="i1-orb7ke"/></radialGradient><radialGradient id="iQpTAtb" cx="0" cy="0" r="1" gradientTransform="matrix(-.46875 -.125 .54686 -2.05079 19.188 22.482)" gradientUnits="userSpaceOnUse"><stop offset=".108" class="qsu4qbckq"/><stop offset="1" class="gr0wzobbs"/></radialGradient><radialGradient id="iSAsI1d" cx="0" cy="0" r="1" gradientTransform="matrix(1.73878 1.3451 -1.47727 1.90964 13.775 23.358)" gradientUnits="userSpaceOnUse"><stop class="ab6i82btp"/><stop offset="1" class="pb6efmson"/></radialGradient><radialGradient id="iwtPTOo" cx="0" cy="0" r="1" gradientTransform="matrix(-1.68958 -.4774 .79459 -2.81214 15.416 23.836)" gradientUnits="userSpaceOnUse"><stop offset=".69" class="sawf8hb2n"/><stop offset="1" class="o415o878f"/></radialGradient><radialGradient id="isAdhHe" cx="0" cy="0" r="1" gradientTransform="matrix(-.5 1.58457 -.75053 -.23683 16.11 23.836)" gradientUnits="userSpaceOnUse"><stop class="btor07b8q"/><stop offset="1" class="jjf293xlz"/></radialGradient><radialGradient id="ivLP6Gc" cx="0" cy="0" r="1" gradientTransform="rotate(142.275 5.895 15.056)scale(2.19833 2.41434)" gradientUnits="userSpaceOnUse"><stop class="auvn9fbbk"/><stop offset="1" class="h2li0wblg"/></radialGradient><radialGradient id="iXetYud" cx="0" cy="0" r="1" gradientTransform="matrix(1.68958 -.4774 .79459 2.81214 18.13 23.836)" gradientUnits="userSpaceOnUse"><stop offset=".69" class="sawf8hb2n"/><stop offset="1" class="o415o878f"/></radialGradient><radialGradient id="iw9bnJb" cx="0" cy="0" r="1" gradientTransform="matrix(-.39136 0 0 -2.59279 17.54 23.592)" gradientUnits="userSpaceOnUse"><stop class="scbqttb8d"/><stop offset="1" class="u1gl_1zha"/></radialGradient><radialGradient id="i9aB4nd" cx="0" cy="0" r="1" gradientTransform="matrix(-4.375 1.44046 -1.3893 -4.21963 28.098 22.456)" gradientUnits="userSpaceOnUse"><stop offset=".241" class="sqw7shfwy"/><stop offset="1" class="t-r3m-b0n"/></radialGradient><radialGradient id="i1P2OKg" cx="0" cy="0" r="1" gradientTransform="rotate(163.091 11.838 12.97)scale(3.90165 13.4872)" gradientUnits="userSpaceOnUse"><stop offset=".699" class="fxbge344d"/><stop offset="1" class="i9u4tf5-i"/></radialGradient><radialGradient id="iQvGmfb" cx="0" cy="0" r="1" gradientTransform="rotate(77.963 .104 26.074)scale(1.04894 5.75403)" gradientUnits="userSpaceOnUse"><stop offset=".134" class="te2y3cbdr"/><stop offset="1" class="pdm4p_b5q"/><stop offset="1" class="kmrvduh9f"/></radialGradient><radialGradient id="iH4w94w" cx="0" cy="0" r="1" gradientTransform="rotate(139.97 1.2 10.48)scale(1.53045 3.638)" gradientUnits="userSpaceOnUse"><stop offset=".129" class="vxe5hyz_v"/><stop offset="1" class="k9e4-bb7j"/></radialGradient><radialGradient id="icc9pKv" cx="0" cy="0" r="1" gradientTransform="matrix(-.79386 1.27188 -2.4349 -1.51978 6.442 17.553)" gradientUnits="userSpaceOnUse"><stop class="hjrsfpbzk"/><stop offset="1" class="vfp25y1ae"/></radialGradient><radialGradient id="iWgnezd" cx="0" cy="0" r="1" gradientTransform="matrix(-.73037 2.48832 -3.82658 -1.12318 6.977 17.288)" gradientUnits="userSpaceOnUse"><stop offset=".579" class="lxw2rgt3i"/><stop offset=".954" class="nke1727fd"/></radialGradient><radialGradient id="ivI3iyH" cx="0" cy="0" r="1" gradientTransform="rotate(116.602 -3.017 10.55)scale(1.58621 2.70684)" gradientUnits="userSpaceOnUse"><stop class="hjrsfpbzk"/><stop offset="1" class="vfp25y1ae"/></radialGradient><radialGradient id="inrNF9c" cx="0" cy="0" r="1" gradientTransform="matrix(-.65347 2.77477 -3.52334 -.82977 5.545 17.677)" gradientUnits="userSpaceOnUse"><stop offset=".579" class="lxw2rgt3i"/><stop offset=".954" class="nke1727fd"/></radialGradient><radialGradient id="iBFjJkb" cx="0" cy="0" r="1" gradientTransform="matrix(-.68468 1.22288 -2.2217 -1.2439 4.939 18.947)" gradientUnits="userSpaceOnUse"><stop class="hjrsfpbzk"/><stop offset="1" class="vfp25y1ae"/></radialGradient><radialGradient id="iGp04ob" cx="0" cy="0" r="1" gradientTransform="rotate(104.751 -4.503 11.427)scale(2.474 3.46652)" gradientUnits="userSpaceOnUse"><stop offset=".579" class="lxw2rgt3i"/><stop offset=".954" class="nke1727fd"/></radialGradient><radialGradient id="i64UBtb" cx="0" cy="0" r="1" gradientTransform="rotate(122.692 -2.834 11.406)scale(1.24393 2.40994)" gradientUnits="userSpaceOnUse"><stop class="hjrsfpbzk"/><stop offset="1" class="vfp25y1ae"/></radialGradient><radialGradient id="ioxxPTd" cx="0" cy="0" r="1" gradientTransform="matrix(-.61813 2.04813 -3.22394 -.973 5.687 19.733)" gradientUnits="userSpaceOnUse"><stop offset=".579" class="lxw2rgt3i"/><stop offset=".954" class="nke1727fd"/></radialGradient><radialGradient id="ixRckpe" cx="0" cy="0" r="1" gradientTransform="rotate(-162.011 6.48 10.137)scale(3.69324 5.10277)" gradientUnits="userSpaceOnUse"><stop class="w3oseebkq"/><stop offset=".644" class="cy8y9p-pn"/></radialGradient><radialGradient id="i7tW1rc" cx="0" cy="0" r="1" gradientTransform="matrix(.07812 -.82813 3.88844 .36683 6.156 21.78)" gradientUnits="userSpaceOnUse"><stop class="axsenyy_b"/><stop offset="1" class="j471ep9dt"/></radialGradient><radialGradient id="iU8PPyb" cx="0" cy="0" r="1" gradientTransform="matrix(1.6875 2.24809 -2.56376 1.92445 16.099 20.289)" gradientUnits="userSpaceOnUse"><stop offset=".252" class="s0pz40q7h"/><stop offset="1" class="lvd5l1bfv"/></radialGradient><radialGradient id="iYUQPDe" cx="0" cy="0" r="1" gradientTransform="rotate(99.782 4.886 17.058)scale(3.78784 4.49966)" gradientUnits="userSpaceOnUse"><stop offset=".28" class="uhnyo9buy"/><stop offset="1" class="e1m_j1-ji"/></radialGradient><radialGradient id="i9iLj3K" cx="0" cy="0" r="1" gradientTransform="matrix(1.34533 2.83228 -1.2874 .61151 10.901 15.44)" gradientUnits="userSpaceOnUse"><stop class="dk-6ihb5y"/><stop offset="1" class="rp1-yvvbr"/></radialGradient><radialGradient id="iUMaHle" cx="0" cy="0" r="1" gradientTransform="matrix(.18936 1.2606 -1.1058 .1661 11.748 15.223)" gradientUnits="userSpaceOnUse"><stop offset=".263" class="oscuplh_u"/><stop offset="1" class="q-uhenb9x"/></radialGradient><radialGradient id="iGnxQgc" cx="0" cy="0" r="1" gradientTransform="matrix(-5.52117 0 0 -9.76689 19.726 14.321)" gradientUnits="userSpaceOnUse"><stop class="c8rk37lbz"/><stop offset="1" class="yl6fh-g8k"/></radialGradient><radialGradient id="ipSuSFb" cx="0" cy="0" r="1" gradientTransform="matrix(0 13 -10.7656 0 17.411 8.101)" gradientUnits="userSpaceOnUse"><stop offset=".738" class="dqi7sbofo"/><stop offset="1" class="z6i58eb9r"/></radialGradient><radialGradient id="iJ8XMja" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.41614 1.75247 0 19.345 13.138)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="aqc0pptzr"/><stop offset="1" class="z_smlmblg"/></radialGradient><radialGradient id="iVKJwGe" cx="0" cy="0" r="1" gradientTransform="matrix(-.06132 -1.1653 1.26813 -.06673 14.397 12.993)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="kgvcakboi"/><stop offset="1" class="gubsnccaz"/></radialGradient><radialGradient id="idzwV5b" cx="0" cy="0" r="1" gradientTransform="matrix(1.27452 0 0 6.47812 11.606 14.727)" gradientUnits="userSpaceOnUse"><stop class="ijumd0ryg"/><stop offset="1" class="oa_7ckp0d"/></radialGradient><radialGradient id="iPOEWkd" cx="0" cy="0" r="1" gradientTransform="matrix(2.76144 -3.859 .87407 .62547 10.58 11.152)" gradientUnits="userSpaceOnUse"><stop offset=".451" class="u_gcnab-s"/><stop offset="1" class="v09_-gbcb"/></radialGradient><radialGradient id="iuAsfmb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.549 -10.81764 11.91596 -2.80781 16.598 18.622)" gradientUnits="userSpaceOnUse"><stop offset=".924" class="noikzrben"/><stop offset="1" class="xx6a4jo2h"/></radialGradient><radialGradient id="iQqLQ7b" cx="0" cy="0" r="1" gradientTransform="matrix(2.15961 .76118 -.45662 1.29553 18.829 8.638)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="xx6a4jo2h"/><stop offset="1" class="noikzrben"/></radialGradient><radialGradient id="izU4rgb" cx="0" cy="0" r="1" gradientTransform="rotate(135.131 5.979 10.803)scale(2.74123 1.74234)" gradientUnits="userSpaceOnUse"><stop offset=".94" class="a860wwbce"/><stop offset="1" class="dm6t8mbjz"/></radialGradient><radialGradient id="iXDBSFd" cx="0" cy="0" r="1" gradientTransform="rotate(-60.732 22.972 -4.39)scale(.74994 2.18233)" gradientUnits="userSpaceOnUse"><stop class="slil38b7x"/><stop offset="1" class="fk4041bff"/></radialGradient><radialGradient id="i4A0yIq" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.76118 3.0624 0 16.761 18.06)" gradientUnits="userSpaceOnUse"><stop class="hwx_eib-x"/><stop offset="1" class="iazz9lb4s"/></radialGradient><radialGradient id="iNb7W8c" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.83647 6.79746 0 11.238 12.651)" gradientUnits="userSpaceOnUse"><stop class="ytx-8cb1b"/><stop offset="1" class="y3fq4efvh"/></radialGradient><radialGradient id="ixKY07c" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.83647 6.79747 0 21.894 12.651)" gradientUnits="userSpaceOnUse"><stop class="ugkkbdcpr"/><stop offset="1" class="lty0cjbuw"/></radialGradient><radialGradient id="i2rySDe" cx="0" cy="0" r="1" gradientTransform="matrix(-3.43414 -1.30993 .69762 -1.8289 21.098 6.022)" gradientUnits="userSpaceOnUse"><stop class="ofjdtziny"/><stop offset="1" class="znwnmpxvd"/></radialGradient><radialGradient id="ieDoGGc" cx="0" cy="0" r="1" gradientTransform="matrix(.9559 1.55776 -3.60702 2.2134 15.805 4.34)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="mvigw0raw"/><stop offset="1" class="tmhk4ybst"/></radialGradient><radialGradient id="id5KnVd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .85684 -1.3629 0 19.065 13.354)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="isyQvBc" cx="0" cy="0" r="1" gradientTransform="matrix(-.24493 -.31563 .43454 -.33721 18.824 13.443)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ikza4sd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .85688 -1.36297 0 14.456 13.354)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iRFS3ub" cx="0" cy="0" r="1" gradientTransform="matrix(-.00817 -.5218 .62723 -.00982 14.154 13.585)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iOJj3Dd" cx="0" cy="0" r="1" gradientTransform="matrix(.66382 2.36914 -2.26034 .63333 21.638 13.368)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="mjrn6wykw"/><stop offset="1" class="l68saw0rr"/></radialGradient><radialGradient id="iagbZRc" cx="0" cy="0" r="1" gradientTransform="matrix(.83198 -1.14176 .95702 .69737 22.018 13.944)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="wvh6w6olb"/><stop offset="1" class="hw3g0j7tn"/></radialGradient><radialGradient id="iicq4Nc" cx="0" cy="0" r="1" gradientTransform="rotate(-171.68 6.296 6.603)scale(1.78781 1.75758)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="qbxa2xbde"/><stop offset="1" class="g54wl109l"/><stop offset="1" class="umfyx2bzt"/></radialGradient><radialGradient id="iMwhdrV" cx="0" cy="0" r="1" gradientTransform="matrix(-5.5 4.12501 -3.615 -4.82 20.719 4.576)" gradientUnits="userSpaceOnUse"><stop offset=".179" class="tg07-ljnl"/><stop offset="1" class="c6833cb9x"/></radialGradient><radialGradient id="i3dSYhb" cx="0" cy="0" r="1" gradientTransform="matrix(2.875 .375 -.58342 4.4729 10.781 7.701)" gradientUnits="userSpaceOnUse"><stop class="j8k1fac_p"/><stop offset="1" class="g8uem1b5g"/></radialGradient><radialGradient id="inl9J2c" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.875 8.03906 0 16.773 8.326)" gradientUnits="userSpaceOnUse"><stop offset=".761" class="km6q7kb1a"/><stop offset="1" class="i8skpb2jz"/></radialGradient><radialGradient id="iCE2gke" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.47656 -8.28125 0 18.406 7.912)" gradientUnits="userSpaceOnUse"><stop class="kzuil_5zu"/><stop offset="1" class="ok2r3obil"/></radialGradient><radialGradient id="ixSAAAe" cx="0" cy="0" r="1" gradientTransform="matrix(-7.1875 0 0 -.63281 21.269 9.87)" gradientUnits="userSpaceOnUse"><stop class="w63qn2bkh"/><stop offset="1" class="vvfum-_fa"/></radialGradient><radialGradient id="iy7tjOa" cx="0" cy="0" r="1" gradientTransform="matrix(3.48438 0 0 2.01172 9.003 10.109)" gradientUnits="userSpaceOnUse"><stop class="gfrsedb9v"/><stop offset="1" class="vke6kh8bt"/></radialGradient><filter id="i3HEF7c" width="21.247" height="10.303" x="6.25" y="19.623" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.615686 0 0 0 0 0.607843 0 0 0 0 0.619608 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23855"/></filter><filter id="imcZNTc" width="2.078" height="2.078" x="15.622" y="27.457" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.792157 0 0 0 0 0.717647 0 0 0 0 0.788235 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_3987_23855"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_3987_23855" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.831373 0 0 0 0 0.745098 0 0 0 0 0.803922 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_3987_23855"/></filter><filter id="iDpSrcd" width="2.078" height="2.078" x="15.622" y="25.444" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.792157 0 0 0 0 0.717647 0 0 0 0 0.788235 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_3987_23855"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_3987_23855" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.831373 0 0 0 0 0.745098 0 0 0 0 0.803922 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_3987_23855"/></filter><filter id="iUTOU2c" width="6.554" height="3.702" x="13.38" y="19.523" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.721569 0 0 0 0 0.682353 0 0 0 0 0.74902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23855"/></filter><filter id="icryIbZ" width="7.432" height="4.46" x="12.567" y="22.084" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23855" stdDeviation=".5"/></filter><filter id="i79l56d" width="2.672" height="2.865" x="13.611" y="22.403" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.780392 0 0 0 0 0.270588 0 0 0 0 0.396078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23855"/></filter><filter id="ijpLIJX" width="2.672" height="2.865" x="17.264" y="22.403" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.780392 0 0 0 0 0.270588 0 0 0 0 0.396078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23855"/></filter><filter id="iT8RStd" width="1.554" height="1.999" x="15.986" y="22.812" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.827451 0 0 0 0 0.137255 0 0 0 0 0.317647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23855"/></filter><filter id="iwRGFMd" width="4.764" height="4.766" x="24.75" y="19.349" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.1"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.827451 0 0 0 0 0.592157 0 0 0 0 0.419608 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23855"/></filter><filter id="ipUuTbb" width="2.077" height="3.844" x="25.907" y="17.448" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.803922 0 0 0 0 0.564706 0 0 0 0 0.517647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23855"/></filter><filter id="irIWLmd" width="2.401" height="4.052" x="24.436" y="17.107" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.803922 0 0 0 0 0.564706 0 0 0 0 0.517647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23855"/></filter><filter id="isyFsjb" width="2.312" height="4.044" x="23.386" y="17.96" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.803922 0 0 0 0 0.564706 0 0 0 0 0.517647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23855"/></filter><filter id="ieTIx5d" width="2.123" height="3.114" x="22.394" y="19.041" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.803922 0 0 0 0 0.564706 0 0 0 0 0.517647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23855"/></filter><filter id="irDuBkb" width="3.002" height="3.147" x="6.649" y="16.347" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.85098 0 0 0 0 0.607843 0 0 0 0 0.47451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23855"/></filter><filter id="iq9YsHc" width="1.264" height="2.491" x="22.908" y="19.19" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23855" stdDeviation=".125"/></filter><filter id="inbCgCe" width="1.286" height="2.978" x="23.933" y="18.125" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23855" stdDeviation=".125"/></filter><filter id="i7Y4Fmc" width="1.444" height="3.775" x="24.963" y="17.226" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23855" stdDeviation=".125"/></filter><filter id="i769qrc" width="1.17" height="3.014" x="26.424" y="17.706" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23855" stdDeviation=".125"/></filter><filter id="iYTt9lc" width="1.788" height="2.6" x="27.33" y="19.87" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23855" stdDeviation=".125"/></filter><filter id="iNcdGUc" width="2.323" height="1.69" x="3.752" y="19.44" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23855" stdDeviation=".125"/></filter><filter id="ipUi5nd" width="2.342" height="2.022" x="3.291" y="18.151" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23855" stdDeviation=".125"/></filter><filter id="ivwjvhd" width="2.131" height="2.124" x="4.556" y="16.714" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23855" stdDeviation=".125"/></filter><filter id="iTOSvme" width="2.569" height="2.444" x="3.345" y="17.042" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23855" stdDeviation=".125"/></filter><filter id="iH4smzd" width="11.544" height="13.234" x="11.414" y="7.804" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75"/><feGaussianBlur stdDeviation=".6"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.843137 0 0 0 0 0.611765 0 0 0 0 0.498039 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23855"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.776471 0 0 0 0 0.54902 0 0 0 0 0.423529 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23855" result="effect2_innerShadow_3987_23855"/></filter><filter id="iJMUa3d" width="3.853" height="4.982" x="14.551" y="12.532" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23855" stdDeviation=".5"/></filter><filter id="ijWKwZb" width="2.183" height="3.263" x="15.669" y="13.144" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23855" stdDeviation=".05"/></filter><filter id="im4E2Rc" width="3.899" height="1.633" x="14.812" y="16.765" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23855" stdDeviation=".05"/></filter><filter id="in3VXsc" width="12.998" height="8.797" x="10.245" y="4.478" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.913725 0 0 0 0 0.733333 0 0 0 0 0.592157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23855"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.87451 0 0 0 0 0.678431 0 0 0 0 0.556863 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23855" result="effect2_innerShadow_3987_23855"/></filter><filter id="iWAXSnq" width="2.464" height="1.246" x="18.439" y="11.049" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.470588 0 0 0 0 0.270588 0 0 0 0 0.160784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23855"/></filter><filter id="i9NYfwe" width="2.464" height="1.231" x="12.888" y="11.064" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.470588 0 0 0 0 0.270588 0 0 0 0 0.160784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23855"/></filter><filter id="i6N961b" width=".82" height=".724" x="18.296" y="12.895" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23855" stdDeviation=".05"/></filter><filter id="ihgaPIe" width=".919" height=".942" x="19.188" y="12.98" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23855" stdDeviation=".1"/></filter><filter id="iVwLZUc" width="1.019" height="1.076" x="14.496" y="12.913" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23855" stdDeviation=".1"/></filter><filter id="ik7jZid" width=".953" height=".733" x="13.693" y="12.886" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23855" stdDeviation=".05"/></filter><filter id="ikIgMCc" width="1.375" height="2.485" x="10.403" y="12.807" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23855" stdDeviation=".125"/></filter><filter id="iY8bSKV" width="1.5" height="2.51" x="21.751" y="12.79" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23855" stdDeviation=".125"/></filter><filter id="i7xsfZc" width="2.498" height="1.183" x="12.823" y="11.153" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23855" stdDeviation=".125"/></filter><filter id="iPGSEsO" width="2.498" height="1.183" x="18.398" y="11.104" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23855" stdDeviation=".125"/></filter><linearGradient id="iK84mBb" x1="22.562" x2="21.812" y1="29.826" y2="29.826" gradientUnits="userSpaceOnUse"><stop class="fr__qmhjc"/><stop offset="1" class="gypp10kih"/></linearGradient><linearGradient id="iWCiqKd" x1="20.644" x2="21.062" y1="29.014" y2="29.014" gradientUnits="userSpaceOnUse"><stop class="hj-s-zboe"/><stop offset="1" class="s0umluqbl"/></linearGradient><linearGradient id="ipodSkc" x1="9.531" x2="4.906" y1="27.451" y2="27.451" gradientUnits="userSpaceOnUse"><stop class="sb-ednb_a"/><stop offset="1" class="v0501vbqa"/></linearGradient><linearGradient id="iXPTZOc" x1="9.75" x2="8.828" y1="27.076" y2="27.076" gradientUnits="userSpaceOnUse"><stop class="o_30au2yc"/><stop offset="1" class="c60cvac3k"/></linearGradient><linearGradient id="itP1zjc" x1="27.871" x2="22.844" y1="28.142" y2="28.142" gradientUnits="userSpaceOnUse"><stop class="i7zyuv8vr"/><stop offset=".907" class="qzhltkbuo"/></linearGradient><linearGradient id="i33ZCUz" x1="28.09" x2="27.168" y1="27.876" y2="27.876" gradientUnits="userSpaceOnUse"><stop class="tub8lbbfx"/><stop offset="1" class="bd09vtb_c"/></linearGradient><linearGradient id="i8tJXGc" x1="16.763" x2="16.763" y1="22.812" y2="24.81" gradientUnits="userSpaceOnUse"><stop offset=".351" class="gzsz7evmk"/><stop offset="1" class="smgiue0gi"/></linearGradient><linearGradient id="iPWzvjj" x1="29.13" x2="28.38" y1="20.034" y2="21.659" gradientUnits="userSpaceOnUse"><stop class="nisiqibvr"/><stop offset="1" class="nntb9stew"/></linearGradient><linearGradient id="i0gZ48c" x1="4.76" x2="5.331" y1="20.169" y2="21.223" gradientUnits="userSpaceOnUse"><stop class="efwa18n2a"/><stop offset="1" class="tsmwdfbse"/></linearGradient><linearGradient id="iF8fKMd" x1="4.307" x2="5.218" y1="19" y2="20.223" gradientUnits="userSpaceOnUse"><stop class="efwa18n2a"/><stop offset="1" class="tsmwdfbse"/></linearGradient><linearGradient id="impiaed" x1="5.489" x2="6.52" y1="17.6" y2="18.693" gradientUnits="userSpaceOnUse"><stop class="efwa18n2a"/><stop offset="1" class="tsmwdfbse"/></linearGradient><linearGradient id="iVWluoc" x1="4.452" x2="5.734" y1="18.044" y2="19.502" gradientUnits="userSpaceOnUse"><stop class="efwa18n2a"/><stop offset="1" class="tsmwdfbse"/></linearGradient><linearGradient id="iehsJjb" x1="22.207" x2="17.611" y1="16.101" y2="16.101" gradientUnits="userSpaceOnUse"><stop class="u0hok99ej"/><stop offset="1" class="tq4h8zb2j"/></linearGradient><linearGradient id="ixxjdgd" x1="16.811" x2="16.811" y1="10.726" y2="11.914" gradientUnits="userSpaceOnUse"><stop class="iaaybeb2f"/><stop offset="1" class="kr-nx4xib"/></linearGradient><linearGradient id="iJo6mAc" x1="16.761" x2="17.663" y1="15.197" y2="15.197" gradientUnits="userSpaceOnUse"><stop class="f6og14bdq"/><stop offset="1" class="hk633lr2o"/></linearGradient><linearGradient id="ikgchhY" x1="15.628" x2="16.762" y1="15.032" y2="15.095" gradientUnits="userSpaceOnUse"><stop class="z_vmdubsa"/><stop offset=".203" class="umam-bfga"/><stop offset="1" class="oanih0n0r"/></linearGradient><linearGradient id="i1MO9II" x1="16.761" x2="16.761" y1="15.618" y2="16.517" gradientUnits="userSpaceOnUse"><stop class="y-mxywbmo"/><stop offset=".845" class="ed0uty_4k"/></linearGradient><linearGradient id="iTIu5ed" x1="16.761" x2="16.761" y1="13.244" y2="13.687" gradientUnits="userSpaceOnUse"><stop class="f6ma3ccql"/><stop offset="1" class="donh02dkd"/></linearGradient><linearGradient id="i00dDJb" x1="16.899" x2="16.899" y1="16.33" y2="16.268" gradientUnits="userSpaceOnUse"><stop class="dm6t8mbjz"/><stop offset="1" class="a860wwbce"/></linearGradient><linearGradient id="i0GZDsc" x1="22.425" x2="11.733" y1="8.341" y2="8.341" gradientUnits="userSpaceOnUse"><stop class="wbaoi1vzd"/><stop offset="1" class="q37q-zblj"/></linearGradient><linearGradient id="ik5EWMx" x1="19.887" x2="19.555" y1="13.411" y2="13.615" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ipvIrjd" x1="15.242" x2="14.911" y1="13.411" y2="13.615" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ig2rDbe" x1="23.558" x2="22.284" y1="13.439" y2="15.738" gradientUnits="userSpaceOnUse"><stop class="zlaemgbzs"/><stop offset="1" class="hye7ay5ht"/></linearGradient><linearGradient id="i0qgP0S" x1="10.583" x2="12.123" y1="14.183" y2="14.048" gradientUnits="userSpaceOnUse"><stop class="dp9jyhbkn"/><stop offset="1" class="a0uazvbjh"/></linearGradient><linearGradient id="izP9Z9c" x1="16.773" x2="16.773" y1="7.912" y2="8.1" gradientUnits="userSpaceOnUse"><stop class="jhlen960d"/><stop offset="1" class="wjchuwb6a"/></linearGradient><linearGradient id="iYE2hsb" x1="17.956" x2="17.956" y1="10.98" y2="10.214" gradientUnits="userSpaceOnUse"><stop class="bl3fq0x9z"/><stop offset="1" class="lxo7c2i6k"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-juggling-medium-light" /></template>
<style>
.a0uazvbjh {
  stop-color: var(--svg-color--bd776c, #BD776C);
}

.a5zzorbzd {
  stop-color: var(--svg-color--e1ac3a, #E1AC3A);
}

.a860wwbce {
  stop-color: var(--svg-color--c27b78, #C27B78);
  stop-opacity: 0;
}

.ab6i82btp {
  stop-color: var(--svg-color--e7377c, #E7377C);
}

.af8mzdbwl {
  stop-color: var(--svg-color--5f679a, #5F679A);
}

.am6k_ubte {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-35px, 0.35px);
  d: path("M4.981 17.139c.11.172.625 1.078 1.282 1.273");
}

.aowey9psm {
  cx: 14.17px;
  cy: 13.253px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.411px;
  ry: 0.208px;
}

.aqc0pptzr {
  stop-color: var(--svg-color--e4a38d, #E4A38D);
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

.b1di2kckx {
  d: path("M14.454 12.85a.943.943 0 0 0-.908 1.191h1.82a1 1 0 0 0 .035-.248a.95.95 0 0 0-.947-.943");
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

.byn6wubog {
  fill: var(--svg-color--bc9ebb, #BC9EBB);
  fill-rule: evenodd;
  d: path("M16.899 24.871a.35.35 0 0 1-.266.244c-.25.048-.467.048-.717 0a.35.35 0 0 1-.262-.23c-.18.2-.49.432-1.009.607c-.31.106-.668.058-.833-.23a1.86 1.86 0 0 1-.245-.948c0-.431.124-.74.245-.95c.165-.287.523-.334.833-.23c.503.171.81.418.993.63a.35.35 0 0 1 .278-.293c.25-.048.467-.048.717 0a.35.35 0 0 1 .28.31c.18-.215.49-.47 1.008-.646c.31-.105.668-.058.834.23c.12.208.244.513.244.949s-.124.74-.244.949c-.166.287-.524.335-.834.23c-.531-.18-.844-.42-1.022-.622");
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

.c8rk37lbz {
  stop-color: var(--svg-color--ffc59f, #FFC59F);
}

.ci3gi1b_k {
  stop-color: var(--svg-color--784b89, #784B89);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cm6u1gkbw {
  stroke: var(--svg-color--b17847, #B17847);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M20.522 11.912c-.272-.195-.948-.537-1.748-.403");
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

.derevsb3o {
  d: path("M11.665 17.241a4.136 4.136 0 0 0 4.104 3.597h1.993a4.136 4.136 0 0 0 4.103-3.597c.125-1.989.25-3.97.343-5.959A1.53 1.53 0 0 0 20.75 9.77h-1.479a2.56 2.56 0 0 1-2.335-1.524a.7.7 0 0 0-.65-.442h-1.344c-1.95 0-3.53 1.598-3.53 3.569c0 1.965.123 3.898.252 5.868");
}

.dgzu5db3n {
  fill: var(--svg-color--fff, #fff);
  d: path("M19.286 12.563c.69 0 1.272.476 1.431 1.118a.29.29 0 0 1-.283.36h-2.356a.243.243 0 0 1-.24-.287a1.476 1.476 0 0 1 1.448-1.191");
}

.dk-6ihb5y {
  stop-color: var(--svg-color--f8bf95, #F8BF95);
}

.dm6t8mbjz {
  stop-color: var(--svg-color--c27b78, #C27B78);
}

.don2wdpjw {
  cx: 16.761px;
  cy: 26.282px;
  r: 0.739px;
}

.donh02dkd {
  stop-color: var(--svg-color--e0a78c, #E0A78C);
  stop-opacity: 0;
}

.dp9jyhbkn {
  stop-color: var(--svg-color--c48874, #C48874);
}

.dpmuo-biy {
  stop-color: var(--svg-color--6f5ea2, #6F5EA2);
}

.dqi7sbofo {
  stop-color: var(--svg-color--c9937f, #C9937F);
  stop-opacity: 0;
}

.du90idbgf {
  d: path("M21.895 15.641c.354-.011.685-.131.955-.326v.984c0 .943-.562 1.783-1.416 2.132q.271-.576.365-1.246z");
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

.e-7ijsrnh {
  d: path("M11.627 15.641a1.73 1.73 0 0 1-.956-.326v.984c0 .943.562 1.783 1.416 2.132q-.271-.576-.365-1.246z");
}

.e1m_j1-ji {
  stop-color: var(--svg-color--da8f78, #DA8F78);
}

.ed0uty_4k {
  stop-color: var(--svg-color--cb8685, #CB8685);
}

.efwa18n2a {
  stop-color: var(--svg-color--efbea6, #EFBEA6);
}

.f21vmbcik {
  d: path("M5.437 21.764h4.094v8.063H5.437z");
}

.f2ij-hb4f {
  cx: 14.17px;
  cy: 13.253px;
  rx: 0.411px;
  ry: 0.208px;
}

.f6ma3ccql {
  stop-color: var(--svg-color--e0a78c, #E0A78C);
}

.f6og14bdq {
  stop-color: var(--svg-color--e1aa8c, #E1AA8C);
}

.f9v3rqbpn {
  d: path("M18.998 13.05c.067.09-.073.199-.233.318c-.16.12-.278.203-.345.114s.008-.26.168-.38c.16-.119.343-.143.41-.053");
}

.fde_fwzpt {
  stop-color: var(--svg-color--5c9946, #5C9946);
}

.fk4041bff {
  stop-color: var(--svg-color--d0978e, #D0978E);
  stop-opacity: 0;
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

.g54wl109l {
  stop-color: var(--svg-color--c77937, #C77937);
}

.g8uem1b5g {
  stop-color: var(--svg-color--38303e, #38303E);
  stop-opacity: 0;
}

.gfrsedb9v {
  stop-color: var(--svg-color--5b595e, #5B595E);
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.gr0wzobbs {
  stop-color: var(--svg-color--dbcdd4, #DBCDD4);
  stop-opacity: 0;
}

.gubsnccaz {
  stop-color: var(--svg-color--c2847c, #C2847C);
  stop-opacity: 0;
}

.gwm_2mjil {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-35px, 0.35px);
  d: path("M4.177 19.865c.177.245.832.742 1.472.84");
}

.gypp10kih {
  stop-color: var(--svg-color--7a6cad, #7A6CAD);
  stop-opacity: 0;
}

.gzsz7evmk {
  stop-color: var(--svg-color--eb3782, #EB3782);
}

.h1eb-9w6a {
  d: path("M16.761 17.38c-.536 0-1.04-.125-1.463-.346c-.145-.074-.3.09-.21.22a2 2 0 0 0 1.673.894a2 2 0 0 0 1.672-.893c.091-.137-.064-.295-.209-.221c-.423.22-.922.347-1.463.347");
}

.h2li0wblg {
  stop-color: var(--svg-color--d02759, #D02759);
}

.h4idlt2gd {
  d: path("m16.357 13.567l-.561 1.941c-.115.4.16.799.55.799h.83c.39 0 .664-.406.55-.799l-.561-1.941c-.12-.43-.682-.43-.808 0");
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

.hk633lr2o {
  stop-color: var(--svg-color--fecaa8, #FECAA8);
}

.hpfqe6rjh {
  cx: 6.332px;
  cy: 12.838px;
  r: 1.684px;
}

.ht6lpfbpp {
  d: path("M18.68 22.463c-.909.308-1.267.83-1.388 1.082l-.028.29l.028.359c.12.25.48.706 1.388 1.014c.362.123.778.068.971-.267c.14-.243.284-.599.284-1.105c0-.507-.144-.862-.284-1.106c-.193-.335-.61-.39-.97-.267");
}

.htxt4vb0r {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.998 13.05c.067.09-.073.199-.233.318c-.16.12-.278.203-.345.114s.008-.26.168-.38c.16-.119.343-.143.41-.053");
}

.hw3g0j7tn {
  stop-color: var(--svg-color--e3a17b, #E3A17B);
  stop-opacity: 0;
}

.hw860-bkw {
  d: path("M22.993 22.213c.119.463.586 1.456.805 1.894h4.047l-.258-3.789l-4.836.924c.031.13.123.507.242.97");
}

.hwx_eib-x {
  stop-color: var(--svg-color--89024e, #89024E);
}

.hye7ay5ht {
  stop-color: var(--svg-color--e0a48c, #E0A48C);
}

.i1-orb7ke {
  stop-color: var(--svg-color--c3b7c1, #C3B7C1);
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

.iaaybeb2f {
  stop-color: var(--svg-color--c08372, #C08372);
}

.iazz9lb4s {
  stop-color: var(--svg-color--87004d, #87004D);
}

.ibjeao4zu {
  fill: var(--svg-color--e6aa8b, #E6AA8B);
  d: path("M22 15.05q.062-1.005.118-2.01A1.01 1.01 0 0 1 22 15.05");
}

.iew71gb4d {
  stroke: var(--svg-color--b17847, #B17847);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M13.198 11.961c.272-.195.948-.537 1.748-.403");
}

.ijumd0ryg {
  stop-color: var(--svg-color--dba085, #DBA085);
}

.iwbygtbvw {
  cx: 25.211px;
  cy: 4.873px;
  r: 1.684px;
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

.jbgwdcjxl {
  fill: var(--svg-color--000, #000);
  d: path("M14.994 13.793c0-.3-.24-.54-.54-.54a.538.538 0 0 0-.48.788h.956a.54.54 0 0 0 .064-.248");
}

.jfld74b3f {
  d: path("M11.423 12.358a1.7 1.7 0 0 0 .146 3.38a83 83 0 0 1-.146-3.38");
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

.k-ikuabgd {
  d: path("M6.803 17.694a.782.782 0 0 1 1.249-.94l.93 1.213c.337.438.519.975.519 1.527l-1.5-.18z");
}

.k1soseb1u {
  d: path("M14.545 18.417c0-.99.9-1.794 2.012-1.794c1.11 0 2.012.803 2.012 1.794v2.326c0 .99-.901 1.794-2.012 1.794s-2.012-.803-2.012-1.794z");
}

.k9e4-bb7j {
  stop-color: var(--svg-color--d49a78, #D49A78);
}

.kgvcakboi {
  stop-color: var(--svg-color--c2847c, #C2847C);
}

.km6q7kb1a {
  stop-color: var(--svg-color--5d5565, #5D5565);
  stop-opacity: 0;
}

.kmbhmlbpq {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M15.333 16.967a3.1 3.1 0 0 0 1.428.339c.53 0 1.016-.124 1.428-.339h.001a.24.24 0 0 1 .281.046c.067.07.092.182.025.283m-3.163-.329l3.1.288m-3.1-.288h-.001a.24.24 0 0 0-.282.049a.22.22 0 0 0-.023.28m.306-.329l-.244.288m3.407.041l-.063-.041m.063.041l-.063-.041m.063.041a2.07 2.07 0 0 1-1.735.927c-.728 0-1.367-.37-1.734-.926m3.406-.042a2 2 0 0 1-1.672.893a2 2 0 0 1-1.672-.893m-.062.042l.062-.042m-.062.042v-.001l.062-.041");
}

.kmrvduh9f {
  stop-color: var(--svg-color--ce9487, #CE9487);
  stop-opacity: 0;
}

.koq0r9bvu {
  stop-color: var(--svg-color--9e78c9, #9E78C9);
}

.kr-nx4xib {
  stop-color: var(--svg-color--c08372, #C08372);
  stop-opacity: 0;
}

.ku63lg_wt {
  stop-color: var(--svg-color--e8e2ec, #E8E2EC);
}

.kzmu-rrsy {
  d: path("m13.38 20.005l.612 3.22h4.945l.797-3.173a10.2 10.2 0 0 0-2.937-.429h-.64c-.963 0-1.895.133-2.777.382");
}

.kzuil_5zu {
  stop-color: var(--svg-color--9072ca, #9072CA);
}

.l-r9gxb9g {
  stop-color: var(--svg-color--4bb8fb, #4BB8FB);
}

.l68saw0rr {
  stop-color: var(--svg-color--ce8d79, #CE8D79);
}

.ld_83jb7a {
  d: path("M16.018 23.224a.41.41 0 0 1 .328-.37a2.1 2.1 0 0 1 .834 0a.41.41 0 0 1 .328.37c.042.395.042.778 0 1.174a.41.41 0 0 1-.328.37c-.29.056-.544.056-.834 0a.41.41 0 0 1-.328-.37a5.5 5.5 0 0 1 0-1.174");
}

.lelj2r8dg {
  stop-color: var(--svg-color--9ae453, #9AE453);
}

.lgi0lwbjz {
  stop-color: var(--svg-color--775184, #775184);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lty0cjbuw {
  stop-color: var(--svg-color--f6cb9c, #F6CB9C);
  stop-opacity: 0;
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

.mjpr9nbsy {
  d: path("M15.315 13.682c0-.305-.247-.508-.314-.57l-.305.295l.188.382z");
}

.mjrn6wykw {
  stop-color: var(--svg-color--ce8d79, #CE8D79);
  stop-opacity: 0;
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

.mvigw0raw {
  stop-color: var(--svg-color--ddca94, #DDCA94);
}

.n297mkbnr {
  stop-color: var(--svg-color--d6d3d7, #D6D3D7);
  stop-opacity: 0;
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

.noikzrben {
  stop-color: var(--svg-color--c17f5f, #C17F5F);
  stop-opacity: 0;
}

.o_30au2yc {
  stop-color: var(--svg-color--decfd8, #DECFD8);
}

.o415o878f {
  stop-color: var(--svg-color--ef4c8b, #EF4C8B);
}

.o8dampt4k {
  fill: var(--svg-color--b57562, #B57562);
  d: path("M11.44 13.057a1.01 1.01 0 0 0 .089 1.984a82 82 0 0 1-.088-1.984");
}

.oa_7ckp0d {
  stop-color: var(--svg-color--dba085, #DBA085);
  stop-opacity: 0;
}

.oanih0n0r {
  stop-color: var(--svg-color--d29879, #D29879);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ofjdtziny {
  stop-color: var(--svg-color--ffffc1, #FFFFC1);
}

.oho74r4oa {
  d: path("M19.068 12.85a.943.943 0 0 1 .908 1.191h-1.821a.946.946 0 0 1 .912-1.191");
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

.oscuplh_u {
  stop-color: var(--svg-color--d79b77, #D79B77);
}

.pb6efmson {
  stop-color: var(--svg-color--d72c5e, #D72C5E);
}

.pdm4p_b5q {
  stop-color: var(--svg-color--e6b298, #E6B298);
  stop-opacity: 0;
}

.pg10zvsnt {
  d: path("M21.959 15.738q.106-1.686.195-3.37a1.7 1.7 0 0 1-.195 3.37");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.ppr920emc {
  stop-color: var(--svg-color--61a150, #61A150);
  stop-opacity: 0;
}

.pt8frltpn {
  stop-color: var(--svg-color--7060a5, #7060A5);
}

.q-uhenb9x {
  stop-color: var(--svg-color--d79b77, #D79B77);
  stop-opacity: 0;
}

.q37q-zblj {
  stop-color: var(--svg-color--e7c991, #E7C991);
}

.qbxa2xbde {
  stop-color: var(--svg-color--dca187, #DCA187);
  stop-opacity: 0;
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

.qzd219blo {
  d: path("M11 8.662a5.773 5.773 0 1 1 11.547 0v1.648H11z");
}

.qzhltkbuo {
  stop-color: var(--svg-color--b9aac8, #B9AAC8);
}

.rp1-yvvbr {
  stop-color: var(--svg-color--dc998e, #DC998E);
}

.rwc5yskns {
  stroke: var(--svg-color--ddac99, #DDAC99);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-35px, 0.35px);
  d: path("m24.358 18.55l.436 2.128");
}

.s0pz40q7h {
  stop-color: var(--svg-color--b76d71, #B76D71);
}

.s0umluqbl {
  stop-color: var(--svg-color--7160a4, #7160A4);
  stop-opacity: 0;
}

.s41w2e12o {
  fill: var(--svg-color--000, #000);
  d: path("M18.528 13.793c0-.3.24-.54.54-.54a.538.538 0 0 1 .48.788h-.956a.5.5 0 0 1-.064-.248");
}

.sawf8hb2n {
  stop-color: var(--svg-color--ef4c8b, #EF4C8B);
  stop-opacity: 0;
}

.sb-ednb_a {
  stop-color: var(--svg-color--ece4f4, #ECE4F4);
}

.scbqttb8d {
  stop-color: var(--svg-color--ec4182, #EC4182);
}

.slil38b7x {
  stop-color: var(--svg-color--d0978e, #D0978E);
}

.smgiue0gi {
  stop-color: var(--svg-color--c93857, #C93857);
}

.sqw7shfwy {
  stop-color: var(--svg-color--f1bea0, #F1BEA0);
}

.sty1w-bnq {
  fill: var(--svg-color--d59f8d, #D59F8D);
  d: path("M22.414 19.881a.681.681 0 1 1 1.33-.294l.36 1.794a.645.645 0 0 1-1.26.279z");
}

.swka_j87x {
  d: path("M6.25 29.826c0-5.635 4.568-10.203 10.203-10.203h.64c5.636 0 10.204 4.568 10.204 10.203z");
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

.te2y3cbdr {
  stop-color: var(--svg-color--ce9487, #CE9487);
}

.tg07-ljnl {
  stop-color: var(--svg-color--5e5764, #5E5764);
}

.tmhk4ybst {
  stop-color: var(--svg-color--ddca94, #DDCA94);
  stop-opacity: 0;
}

.tn_97qkdc {
  stop-color: var(--svg-color--f2c341, #F2C341);
  stop-opacity: 0;
}

.tq4h8zb2j {
  stop-color: var(--svg-color--f7c29d, #F7C29D);
  stop-opacity: 0;
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

.u_gcnab-s {
  stop-color: var(--svg-color--b67459, #B67459);
}

.u0hok99ej {
  stop-color: var(--svg-color--f7c29d, #F7C29D);
}

.u1gl_1zha {
  stop-color: var(--svg-color--ec4182, #EC4182);
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

.ugkkbdcpr {
  stop-color: var(--svg-color--f6cb9c, #F6CB9C);
}

.uhnyo9buy {
  stop-color: var(--svg-color--f7bf94, #F7BF94);
}

.ujrq6ixuu {
  stop-color: var(--svg-color--beb4c6, #BEB4C6);
}

.umam-bfga {
  stop-color: var(--svg-color--d29879, #D29879);
}

.umfyx2bzt {
  stop-color: var(--svg-color--dca187, #DCA187);
}

.uvn2r8etf {
  fill: var(--svg-color--a06937, #A06937);
  d: path("M13.159 11.666a2.93 2.93 0 0 1 1.836-.38a.293.293 0 0 1-.071.582a2.34 2.34 0 0 0-1.465.3a1 1 0 0 0-.096.064l-.003.002a.293.293 0 0 1-.36-.463z");
}

.uvus49ufr {
  fill: var(--svg-color--fff, #fff);
  d: path("M14.236 12.563c-.69 0-1.273.476-1.431 1.118a.29.29 0 0 0 .282.36h2.357c.15 0 .27-.137.24-.287a1.48 1.48 0 0 0-1.448-1.191");
}

.v0501vbqa {
  stop-color: var(--svg-color--c0b5cd, #C0B5CD);
}

.v09_-gbcb {
  stop-color: var(--svg-color--b67459, #B67459);
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

.vvfum-_fa {
  stop-color: var(--svg-color--392f42, #392F42);
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

.wbaoi1vzd {
  stop-color: var(--svg-color--fff6b9, #FFF6B9);
}

.wfgw5ub6b {
  fill-rule: evenodd;
  d: path("M4.273 16.754a.75.75 0 0 1 1.042.196q.091.134.166.258c.141.228.267.432.519.637c.292.238.794.485 1.747.42a.75.75 0 1 1 .102 1.497c-1.29.088-2.178-.25-2.796-.754c-.478-.389-.78-.89-.917-1.116l-.059-.096a.75.75 0 0 1 .196-1.042");
}

.wjchuwb6a {
  stop-color: var(--svg-color--745ba5, #745BA5);
  stop-opacity: 0;
}

.wo_5cacau {
  fill: var(--svg-color--c48377, #C48377);
  d: path("m16.306 13.967l-.73 1.748c-.108.4.149.799.513.799h.776c.364 0 .621-.406.514-.799l-.525-1.941c-.112-.43-.43-.237-.548.193");
}

.wozepxbaa {
  d: path("M11.048 7.912a6 6 0 0 0-.048.75v1.648h11.547V8.663q0-.381-.049-.75z");
}

.wp2p6dbcv {
  d: path("M23.777 24.107h4.094v5.719h-4.094z");
}

.wshx69b-y {
  stop-color: var(--svg-color--896bb4, #896BB4);
}

.wvh6w6olb {
  stop-color: var(--svg-color--e3a17b, #E3A17B);
}

.x1l7xqbyw {
  stop-color: var(--svg-color--de5534, #DE5534);
  stop-opacity: 0;
}

.xntzq-4ho {
  stop-color: var(--svg-color--8566b5, #8566B5);
}

.xx6a4jo2h {
  stop-color: var(--svg-color--c17f5f, #C17F5F);
}

.y_auwli2s {
  stop-color: var(--svg-color--415e58, #415E58);
}

.y-1rsmdul {
  stop-color: var(--svg-color--3a7ab4, #3A7AB4);
  stop-opacity: 0;
}

.y-mxywbmo {
  stop-color: var(--svg-color--cb8685, #CB8685);
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

.y3fq4efvh {
  stop-color: var(--svg-color--e7b286, #E7B286);
  stop-opacity: 0;
}

.y96ok7g9l {
  fill: var(--svg-color--a06937, #A06937);
  d: path("M20.703 11.78c-.185-.16-.4-.331-.726-.434c-.321-.1-.724-.128-1.28-.06a.293.293 0 1 0 .07.582c.509-.063.82-.03 1.034.037c.21.066.351.173.517.318a.293.293 0 1 0 .385-.442");
}

.yl6fh-g8k {
  stop-color: var(--svg-color--c8917d, #C8917D);
}

.ym-b_m9fy {
  stop-color: var(--svg-color--d1bed4, #D1BED4);
  stop-opacity: 0;
}

.ytx-8cb1b {
  stop-color: var(--svg-color--e7b286, #E7B286);
}

.z_smlmblg {
  stop-color: var(--svg-color--e4a38d, #E4A38D);
  stop-opacity: 0;
}

.z_vmdubsa {
  stop-color: var(--svg-color--d29879, #D29879);
  stop-opacity: 0.915;
}

.z07pf-z8p {
  d: path("M19.907 13.668a.9.9 0 0 0-.244-.488l-.275.3l.124.242z");
}

.z6i58eb9r {
  stop-color: var(--svg-color--b26c78, #B26C78);
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

.zjlswjibr {
  d: path("M21.888 7.306c.543.187-.308 1.283 0 1.827c.493.867 1.759 1.187 1.226 1.951a1.65 1.65 0 0 0-.285.924v1.254a1.8 1.8 0 0 0-.705-.283l.083-1.696a1.53 1.53 0 0 0-1.456-1.513h-1.48a2.56 2.56 0 0 1-2.335-1.524a.7.7 0 0 0-.65-.441h-1.344c-1.95 0-3.529 1.597-3.529 3.568l.032 1.624c-.268.04-.548.129-.76.278v-1.267c0-.329-.1-.652-.286-.924c-.504-.742.35-.763.793-1.607c.308-.584-.137-1.967.428-2.165a2.83 2.83 0 0 0 1.462-1.173a2.456 2.456 0 0 1 3.053-.963a1.57 1.57 0 0 0 1.26 0c.297-.124.622-.198.964-.198c.89 0 1.67.482 2.1 1.195c.325.538.835.93 1.429 1.133");
}

.zlaemgbzs {
  stop-color: var(--svg-color--f8c5a2, #F8C5A2);
}

.znvzi0b9x {
  fill: var(--svg-color--d59f8d, #D59F8D);
  d: path("M24.458 17.959a.68.68 0 0 1 .568-.843l.023-.003a.68.68 0 0 1 .756.54l.622 3.039c.071.355-.246.42-.606.458c-.303.032-.553-.005-.629-.3z");
}

.znwnmpxvd {
  stop-color: var(--svg-color--ffffc1, #FFFFC1);
  stop-opacity: 0;
}

</style>
