<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iIMgSyc)"><path fill="url(#iJlNl1b)" clip-rule="evenodd" class="tqzzcj6ns"/><path fill="url(#ijnaVLc)" clip-rule="evenodd" class="tqzzcj6ns"/><path fill="url(#is16fse)" clip-rule="evenodd" class="tqzzcj6ns"/><path fill="url(#iO8U86b)" clip-rule="evenodd" class="tqzzcj6ns"/><path fill="url(#iufh3vb)" clip-rule="evenodd" class="tqzzcj6ns"/><path fill="url(#io4sTLT)" clip-rule="evenodd" class="tqzzcj6ns"/><path fill="url(#izRmjCe)" clip-rule="evenodd" class="tqzzcj6ns"/><path fill="url(#iFszQoe)" clip-rule="evenodd" class="tqzzcj6ns"/><path fill="url(#i969OtO)" clip-rule="evenodd" class="tqzzcj6ns"/><path fill="url(#ibAlkLd)" clip-rule="evenodd" class="tqzzcj6ns"/><path fill="url(#iQEGqYd)" clip-rule="evenodd" class="tqzzcj6ns"/></g><g filter="url(#iy1CE5d)"><path fill="url(#iCWg3yz)" class="swka_j87x"/><path fill="url(#iTFB9Bb)" class="swka_j87x"/><path fill="url(#iw5sInd)" class="swka_j87x"/><path fill="url(#il5eVUq)" class="swka_j87x"/><path fill="url(#iY3yYtd)" class="swka_j87x"/></g><circle fill="url(#iBZ0RUd)" class="hpfqe6rjh"/><circle fill="url(#itKlKTd)" class="hpfqe6rjh"/><circle fill="url(#ihlr5IT)" class="duyhuibwk"/><circle fill="url(#iGUmgWd)" class="duyhuibwk"/><circle fill="url(#iXhqZHd)" class="iwbygtbvw"/><circle fill="url(#iOHvRJe)" class="iwbygtbvw"/><circle fill="url(#issuNue)" class="zdcorrl9x"/><circle fill="url(#iMaLBhb)" class="zdcorrl9x"/><circle fill="url(#iAhrvZc)" class="zdcorrl9x"/><g filter="url(#itlVy6d)"><circle fill="url(#iMk8UMb)" class="t-5nldk3g"/></g><g filter="url(#i2eHrec)"><circle fill="url(#iR23Gge)" class="don2wdpjw"/></g><path fill="url(#i5YvaPc)" class="j70rp9pis"/><path fill="url(#iK84mBb)" class="j70rp9pis"/><path fill="url(#iWCiqKd)" class="j70rp9pis"/><path fill="url(#ieol8Me)" class="qy4rrcb8b"/><path fill="url(#iDbbcbc)" class="qy4rrcb8b"/><path fill="url(#iOe2zrd)" class="qy4rrcb8b"/><path fill="url(#iV71Rbc)" class="qy4rrcb8b"/><g filter="url(#i14Vgbs)"><path fill="url(#i5S4ipb)" class="lliu2abxg"/><path fill="url(#ix2mzrc)" class="lliu2abxg"/></g><path fill="url(#ipodSkc)" class="f21vmbcik"/><path fill="url(#iXPTZOc)" class="f21vmbcik"/><path fill="url(#itP1zjc)" class="wp2p6dbcv"/><path fill="url(#i33ZCUz)" class="wp2p6dbcv"/><g filter="url(#iaVd1Hd)"><path clip-rule="evenodd" class="fgpnfrb_u"/></g><g filter="url(#iGjsbUc)"><path fill="url(#iSAsI1d)" class="ctsppjbax"/><path fill="url(#iwtPTOo)" class="ctsppjbax"/><path fill="url(#isAdhHe)" class="ctsppjbax"/></g><g filter="url(#ifGYUXb)"><path fill="url(#ivLP6Gc)" class="ht6lpfbpp"/><path fill="url(#iXetYud)" class="ht6lpfbpp"/></g><g filter="url(#ithTOoq)"><path fill="url(#i8tJXGc)" class="ld_83jb7a"/><path fill="url(#iw9bnJb)" class="ld_83jb7a"/></g><g filter="url(#iVpanRb)"><path class="bsid3ncbw"/></g><g filter="url(#idOdVHd)"><path class="j4x55bbau"/></g><g filter="url(#i2DrPMc)"><path class="hwyai6h-t"/></g><g filter="url(#i72qZmc)"><path class="ddpez5d9u"/></g><g filter="url(#iETXWCe)"><path class="cfziuz30v"/></g><path fill="url(#ipMueJd)" class="gvcddab8z"/><path fill="url(#i3JaYLp)" class="gvcddab8z"/><g filter="url(#i5vVvue)"><path fill="url(#iTna7Kc)" class="u5bjt8cdp"/></g><path fill="url(#ih4s9ac)" clip-rule="evenodd" class="wfgw5ub6b"/><path fill="url(#ikJdwNc)" clip-rule="evenodd" class="wfgw5ub6b"/><path fill="url(#i40zLFb)" clip-rule="evenodd" class="d5_x4xk7i"/><path fill="url(#il9qrHe)" clip-rule="evenodd" class="d5_x4xk7i"/><path fill="url(#imjV17b)" clip-rule="evenodd" class="ctupw6b3d"/><path fill="url(#iD8Aurb)" clip-rule="evenodd" class="ctupw6b3d"/><path fill="url(#i2Iv6ab)" clip-rule="evenodd" class="vdngsab5t"/><path fill="url(#ihNB5dd)" clip-rule="evenodd" class="vdngsab5t"/><path fill="url(#ilhtGxd)" class="twba206ho"/><path fill="url(#itEg77z)" class="twba206ho"/><path fill="url(#i8FqvGc)" class="fpq5frbny"/><path fill="url(#iBEqkLe)" class="fpq5frbny"/><g filter="url(#idSDA3d)"><ellipse fill="url(#iKwJqgb)" transform="rotate(-11.027 25.353 20.78)" class="w6tinjvyq"/></g><g filter="url(#isMdERc)"><path fill="url(#i994Uzd)" class="hv2lphb6i"/></g><g filter="url(#iSPPwyN)"><path fill="url(#ixEv3LT)" class="ljh3pfo4c"/></g><g filter="url(#i9KmNnD)"><path class="v5pmfy16o"/><path fill="url(#ip6ojXb)" class="vvmlqccxo"/></g><g filter="url(#ivPiCie)"><path class="hq7_u2r_k"/><path fill="url(#iunyyYs)" class="oan4hab5a"/></g><g filter="url(#ichFdWh)"><path fill="url(#iSgns7k)" class="ohjqpb16k"/><path fill="url(#iSijRic)" class="ohjqpb16k"/><path fill="url(#iOIJw3e)" class="ohjqpb16k"/><path fill="url(#iIOM0db)" class="ohjqpb16k"/><path fill="url(#iab2Nhb)" class="ohjqpb16k"/><path fill="url(#i7y4zZc)" class="ohjqpb16k"/><path fill="url(#immo5Xb)" class="ohjqpb16k"/></g><path fill="url(#i3pLImd)" class="ohjqpb16k"/><path fill="url(#iDu27Hb)" class="ohjqpb16k"/><g filter="url(#iJVgzOd)"><path class="nfiiif6yg"/></g><g filter="url(#iCrlPrd)"><path fill="url(#i2nI9kc)" class="czcujwbjt"/><path fill="url(#izCBpcb)" class="czcujwbjt"/><path fill="url(#iuyhrAe)" class="czcujwbjt"/><path fill="url(#iOqfDdc)" class="czcujwbjt"/></g><g filter="url(#iwwUVKd)"><path stroke="url(#i1Yy7ab)" class="zncfmhvrl"/></g><path class="lr49rjb-q"/><g filter="url(#i2Zqbrd)"><path class="m-2cz-bcp"/></g><g filter="url(#i8EbOac)"><path class="djl_ovbam"/></g><g filter="url(#ifTRird)"><path class="h97a2frxj"/></g><g filter="url(#iKMWs6b)"><path clip-rule="evenodd" class="ys9yiru4r"/></g><path class="ptlpnyb1n"/><path fill="url(#iACjyRJ)" class="frq_4bb4s"/><path class="s19inuw5i"/><g filter="url(#idopKFm)"><path class="vxy77p_hq"/><path fill="url(#ijg1ase)" class="wpmv2hblc"/></g><g filter="url(#i2VN4ed)"><path fill="url(#iPtLbuc)" class="kre23obqr"/></g><path class="pp1m28b5p"/><path fill="url(#iEdMrkp)" class="t8f3iprss"/><path class="c7h5vdb0o"/><g filter="url(#iS2KwGb)"><path fill="url(#iot6ESb)" class="yh2htvgmn"/></g><g filter="url(#ipC51Cb)"><ellipse transform="rotate(-27.894 34.487 -21.975)skewX(.039)" class="r-2q1cb7n"/><ellipse fill="url(#iKN2uVD)" transform="rotate(-27.894 34.487 -21.975)skewX(.039)" class="o87v3pbeq"/></g><g filter="url(#iVsvOqe)"><path class="wwxb6rbbd"/></g><g filter="url(#isYzPld)"><path class="dg9vkvbdw"/></g><g filter="url(#iahMVue)"><path stroke="url(#iol6Ose)" class="y8mrckbab"/></g><path fill="url(#iMwhdrV)" class="qzd219blo"/><path fill="url(#i3dSYhb)" class="qzd219blo"/><path fill="url(#inl9J2c)" class="qzd219blo"/><path fill="url(#iCE2gke)" class="wozepxbaa"/><path fill="url(#izP9Z9c)" class="wozepxbaa"/><rect fill="url(#ixSAAAe)" class="okwd93kys"/><rect fill="url(#iy7tjOa)" class="okwd93kys"/><rect fill="url(#iYE2hsb)" class="okwd93kys"/><defs><radialGradient id="ijnaVLc" cx="0" cy="0" r="1" gradientTransform="matrix(2.93582 1.57952 -2.23628 4.15653 20.85 17.75)" gradientUnits="userSpaceOnUse"><stop offset=".616" class="w3-vy4c8j"/><stop offset="1" class="w72oynbwi"/></radialGradient><radialGradient id="is16fse" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.65493 -2.80677 0 12.075 16.43)" gradientUnits="userSpaceOnUse"><stop class="lcrdwk1fj"/><stop offset="1" class="denqa3bda"/></radialGradient><radialGradient id="iO8U86b" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.81911 -6.06668 0 16.853 16.526)" gradientUnits="userSpaceOnUse"><stop offset=".617" class="ag6fa4z4y"/><stop offset="1" class="qir_1cb0f"/></radialGradient><radialGradient id="iufh3vb" cx="0" cy="0" r="1" gradientTransform="rotate(127.64 2.261 10.2)scale(2.12394 2.06267)" gradientUnits="userSpaceOnUse"><stop offset=".161" class="ha2cq84sa"/><stop offset="1" class="p4wkjrbae"/></radialGradient><radialGradient id="io4sTLT" cx="0" cy="0" r="1" gradientTransform="rotate(100.546 1.143 11.174)scale(2.67084 2.78333)" gradientUnits="userSpaceOnUse"><stop offset=".365" class="tgqxysbgm"/><stop offset="1" class="p1xq25bjq"/></radialGradient><radialGradient id="izRmjCe" cx="0" cy="0" r="1" gradientTransform="matrix(1.1453 2.20809 -4.20837 2.18281 13.365 6.823)" gradientUnits="userSpaceOnUse"><stop offset=".222" class="esx41hbqq"/><stop offset=".921" class="v9rq5jjti"/></radialGradient><radialGradient id="iFszQoe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.15647 1.26057 -1.76175 -1.61627 22.6 8.303)" gradientUnits="userSpaceOnUse"><stop class="duwob45dr"/><stop offset="1" class="v61l3jbat"/></radialGradient><radialGradient id="i969OtO" cx="0" cy="0" r="1" gradientTransform="rotate(163.792 11.397 8.467)scale(2.00715 4.36423)" gradientUnits="userSpaceOnUse"><stop class="u0-djrvhx"/><stop offset="1" class="hottnizrg"/><stop offset="1" class="fj67tibom"/></radialGradient><radialGradient id="ibAlkLd" cx="0" cy="0" r="1" gradientTransform="rotate(-133.339 16.015 5.863)scale(4.87169 6.99666)" gradientUnits="userSpaceOnUse"><stop class="yqk-2gbyp"/><stop offset="1" class="oaxszm67z"/></radialGradient><radialGradient id="iQEGqYd" cx="0" cy="0" r="1" gradientTransform="rotate(-90.352 11.698 -2.256)scale(1.4356 .47108)" gradientUnits="userSpaceOnUse"><stop offset=".295" class="sufhn4bec"/><stop offset="1" class="kpf8h5ohf"/></radialGradient><radialGradient id="iCWg3yz" cx="0" cy="0" r="1" gradientTransform="rotate(135.22 8.643 15.887)scale(12.9545 12.5552)" gradientUnits="userSpaceOnUse"><stop offset=".195" class="m-1-e5bla"/><stop offset=".655" class="x92j_kb4w"/></radialGradient><radialGradient id="iTFB9Bb" cx="0" cy="0" r="1" gradientTransform="matrix(2.75 0 0 6.1875 8.969 25.389)" gradientUnits="userSpaceOnUse"><stop class="nmqo35b7x"/><stop offset="1" class="gzcpsebza"/></radialGradient><radialGradient id="iw5sInd" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.09375 -3.28125 0 20.219 20.139)" gradientUnits="userSpaceOnUse"><stop class="dpkv3e8bt"/><stop offset="1" class="w4ea2bbjv"/></radialGradient><radialGradient id="il5eVUq" cx="0" cy="0" r="1" gradientTransform="matrix(-1.75 0 0 -11.7187 21 25.92)" gradientUnits="userSpaceOnUse"><stop offset=".214" class="demkpcl0k"/><stop offset="1" class="ym-b_m9fy"/></radialGradient><radialGradient id="iY3yYtd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.15625 0 0 -5.75902 11.656 25.326)" gradientUnits="userSpaceOnUse"><stop class="ujrq6ixuu"/><stop offset="1" class="h4mko5b9o"/></radialGradient><radialGradient id="iBZ0RUd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.34375 2.4375 -2.36069 -1.3014 7.187 11.826)" gradientUnits="userSpaceOnUse"><stop offset=".077" class="l-r9gxb9g"/><stop offset="1" class="hcmh5c50b"/></radialGradient><radialGradient id="itKlKTd" cx="0" cy="0" r="1" gradientTransform="rotate(115.145 -.151 8.247)scale(3.38309 2.95533)" gradientUnits="userSpaceOnUse"><stop offset=".452" class="y-1rsmdul"/><stop offset=".826" class="af8mzdbwl"/></radialGradient><radialGradient id="ihlr5IT" cx="0" cy="0" r="1" gradientTransform="matrix(-1.34375 2.4375 -2.36069 -1.3014 10.101 2.846)" gradientUnits="userSpaceOnUse"><stop offset=".077" class="mpwbs5b3u"/><stop offset="1" class="fzq016boz"/></radialGradient><radialGradient id="iGUmgWd" cx="0" cy="0" r="1" gradientTransform="rotate(115.145 4.158 4.683)scale(3.38309 2.95533)" gradientUnits="userSpaceOnUse"><stop offset=".452" class="x1l7xqbyw"/><stop offset=".826" class="ng1cexbhj"/></radialGradient><radialGradient id="iXhqZHd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.34375 2.4375 -2.36069 -1.3014 26.066 3.861)" gradientUnits="userSpaceOnUse"><stop offset=".077" class="lelj2r8dg"/><stop offset="1" class="fde_fwzpt"/></radialGradient><radialGradient id="iOHvRJe" cx="0" cy="0" r="1" gradientTransform="rotate(105.03 11.36 11.751)scale(3.49455 3.40391)" gradientUnits="userSpaceOnUse"><stop offset=".375" class="ppr920emc"/><stop offset=".826" class="y_auwli2s"/></radialGradient><radialGradient id="issuNue" cx="0" cy="0" r="1" gradientTransform="matrix(-1.34375 2.4375 -2.36069 -1.3014 27.09 13.818)" gradientUnits="userSpaceOnUse"><stop offset=".077" class="y05rrkbkk"/><stop offset="1" class="a5zzorbzd"/></radialGradient><radialGradient id="iMaLBhb" cx="0" cy="0" r="1" gradientTransform="matrix(1 1.07812 -1.5877 1.47265 24.969 13.357)" gradientUnits="userSpaceOnUse"><stop class="i8j0jyb4u"/><stop offset="1" class="d7caiobkz"/></radialGradient><radialGradient id="iAhrvZc" cx="0" cy="0" r="1" gradientTransform="rotate(109.11 8.51 16.52)scale(3.46022 3.37046)" gradientUnits="userSpaceOnUse"><stop offset=".347" class="tn_97qkdc"/><stop offset=".829" class="mmq2utbuk"/></radialGradient><radialGradient id="iMk8UMb" cx="0" cy="0" r="1" gradientTransform="matrix(-.7578 1.14063 -.96756 -.64282 17.25 27.855)" gradientUnits="userSpaceOnUse"><stop offset=".212" class="u6lph46no"/><stop offset="1" class="bq5dgsbba"/></radialGradient><radialGradient id="iR23Gge" cx="0" cy="0" r="1" gradientTransform="matrix(-.7578 1.14063 -.96756 -.64282 17.25 25.842)" gradientUnits="userSpaceOnUse"><stop offset=".212" class="u6lph46no"/><stop offset="1" class="bq5dgsbba"/></radialGradient><radialGradient id="i5YvaPc" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.03125 -2.40212 0 22.222 20.983)" gradientUnits="userSpaceOnUse"><stop class="koq0r9bvu"/><stop offset="1" class="dpmuo-biy"/></radialGradient><radialGradient id="ieol8Me" cx="0" cy="0" r="1" gradientTransform="scale(1.38818 6.1875)rotate(90 2.761 6.5)" gradientUnits="userSpaceOnUse"><stop class="xntzq-4ho"/><stop offset="1" class="pt8frltpn"/></radialGradient><radialGradient id="iDbbcbc" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.25 -.60938 0 13.062 24.108)" gradientUnits="userSpaceOnUse"><stop class="wshx69b-y"/><stop offset="1" class="aqzyd8bsb"/></radialGradient><radialGradient id="iOe2zrd" cx="0" cy="0" r="1" gradientTransform="matrix(2.9375 -7.98881 7.06186 2.59666 10.312 28.264)" gradientUnits="userSpaceOnUse"><stop offset=".724" class="lgi0lwbjz"/><stop offset="1" class="tvoyviyhj"/></radialGradient><radialGradient id="iV71Rbc" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.42188 -.18506 0 12.857 21.717)" gradientUnits="userSpaceOnUse"><stop class="m5avsc_ef"/><stop offset="1" class="ci3gi1b_k"/></radialGradient><radialGradient id="i5S4ipb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.90624 2.42972 -4.28692 -6.89204 19.562 20.795)" gradientUnits="userSpaceOnUse"><stop class="sqf03_p-t"/><stop offset="1" class="kdv9gpb4z"/></radialGradient><radialGradient id="ix2mzrc" cx="0" cy="0" r="1" gradientTransform="matrix(-.46875 -.125 .54686 -2.05079 19.484 22.483)" gradientUnits="userSpaceOnUse"><stop offset=".108" class="qsu4qbckq"/><stop offset="1" class="gr0wzobbs"/></radialGradient><radialGradient id="iSAsI1d" cx="0" cy="0" r="1" gradientTransform="matrix(1.73878 1.3451 -1.47727 1.90964 13.775 23.358)" gradientUnits="userSpaceOnUse"><stop class="ab6i82btp"/><stop offset="1" class="pb6efmson"/></radialGradient><radialGradient id="iwtPTOo" cx="0" cy="0" r="1" gradientTransform="matrix(-1.68958 -.4774 .79459 -2.81214 15.416 23.836)" gradientUnits="userSpaceOnUse"><stop offset=".69" class="sawf8hb2n"/><stop offset="1" class="o415o878f"/></radialGradient><radialGradient id="isAdhHe" cx="0" cy="0" r="1" gradientTransform="matrix(-.5 1.58457 -.75053 -.23683 16.11 23.836)" gradientUnits="userSpaceOnUse"><stop class="btor07b8q"/><stop offset="1" class="jjf293xlz"/></radialGradient><radialGradient id="ivLP6Gc" cx="0" cy="0" r="1" gradientTransform="rotate(142.275 5.895 15.056)scale(2.19833 2.41434)" gradientUnits="userSpaceOnUse"><stop class="auvn9fbbk"/><stop offset="1" class="h2li0wblg"/></radialGradient><radialGradient id="iXetYud" cx="0" cy="0" r="1" gradientTransform="matrix(1.68958 -.4774 .79459 2.81214 18.13 23.836)" gradientUnits="userSpaceOnUse"><stop offset=".69" class="sawf8hb2n"/><stop offset="1" class="o415o878f"/></radialGradient><radialGradient id="iw9bnJb" cx="0" cy="0" r="1" gradientTransform="matrix(-.39136 0 0 -2.59279 17.54 23.592)" gradientUnits="userSpaceOnUse"><stop class="scbqttb8d"/><stop offset="1" class="u1gl_1zha"/></radialGradient><radialGradient id="ipMueJd" cx="0" cy="0" r="1" gradientTransform="matrix(-4.375 1.44046 -1.3893 -4.21963 28.094 22.456)" gradientUnits="userSpaceOnUse"><stop offset=".241" class="l3ydtt4ya"/><stop offset=".899" class="vgk5w_bmg"/></radialGradient><radialGradient id="i3JaYLp" cx="0" cy="0" r="1" gradientTransform="rotate(163.091 11.836 12.97)scale(3.90165 13.4872)" gradientUnits="userSpaceOnUse"><stop offset=".699" class="w5vup9bwr"/><stop offset="1" class="mu0q52a8h"/></radialGradient><radialGradient id="iTna7Kc" cx="0" cy="0" r="1" gradientTransform="rotate(139.97 1.2 10.48)scale(1.53045 3.638)" gradientUnits="userSpaceOnUse"><stop offset=".129" class="lelniimio"/><stop offset="1" class="zeffp9bvk"/></radialGradient><radialGradient id="ih4s9ac" cx="0" cy="0" r="1" gradientTransform="matrix(-.79386 1.27188 -2.4349 -1.51978 6.442 17.553)" gradientUnits="userSpaceOnUse"><stop class="wef8zac8b"/><stop offset="1" class="hoarz6bum"/></radialGradient><radialGradient id="ikJdwNc" cx="0" cy="0" r="1" gradientTransform="matrix(-.73037 2.48832 -3.82658 -1.12318 6.977 17.288)" gradientUnits="userSpaceOnUse"><stop offset=".63" class="e8-v49b1g"/><stop offset="1" class="y6ze32mia"/></radialGradient><radialGradient id="i40zLFb" cx="0" cy="0" r="1" gradientTransform="rotate(116.602 -3.017 10.55)scale(1.58621 2.70684)" gradientUnits="userSpaceOnUse"><stop class="wef8zac8b"/><stop offset="1" class="hoarz6bum"/></radialGradient><radialGradient id="il9qrHe" cx="0" cy="0" r="1" gradientTransform="matrix(-.65347 2.77477 -3.52334 -.82977 5.545 17.677)" gradientUnits="userSpaceOnUse"><stop offset=".63" class="e8-v49b1g"/><stop offset="1" class="y6ze32mia"/></radialGradient><radialGradient id="imjV17b" cx="0" cy="0" r="1" gradientTransform="matrix(-.68468 1.22288 -2.2217 -1.2439 4.939 18.947)" gradientUnits="userSpaceOnUse"><stop class="wef8zac8b"/><stop offset="1" class="hoarz6bum"/></radialGradient><radialGradient id="iD8Aurb" cx="0" cy="0" r="1" gradientTransform="rotate(104.751 -4.503 11.427)scale(2.474 3.46652)" gradientUnits="userSpaceOnUse"><stop offset=".63" class="e8-v49b1g"/><stop offset="1" class="y6ze32mia"/></radialGradient><radialGradient id="i2Iv6ab" cx="0" cy="0" r="1" gradientTransform="rotate(122.692 -2.834 11.406)scale(1.24393 2.40994)" gradientUnits="userSpaceOnUse"><stop class="wef8zac8b"/><stop offset="1" class="hoarz6bum"/></radialGradient><radialGradient id="ihNB5dd" cx="0" cy="0" r="1" gradientTransform="matrix(-.61813 2.04813 -3.22394 -.973 5.687 19.733)" gradientUnits="userSpaceOnUse"><stop offset=".63" class="e8-v49b1g"/><stop offset="1" class="y6ze32mia"/></radialGradient><radialGradient id="ilhtGxd" cx="0" cy="0" r="1" gradientTransform="rotate(-162.011 6.48 10.137)scale(3.69324 5.10277)" gradientUnits="userSpaceOnUse"><stop class="dwn54oxgo"/><stop offset="1" class="v0i04x6vh"/></radialGradient><radialGradient id="itEg77z" cx="0" cy="0" r="1" gradientTransform="matrix(.07812 -.82813 3.88844 .36683 6.156 21.78)" gradientUnits="userSpaceOnUse"><stop class="hq864_b1v"/><stop offset="1" class="e-tdchb2h"/></radialGradient><radialGradient id="i8FqvGc" cx="0" cy="0" r="1" gradientTransform="matrix(1.65625 2.09375 -2.38774 1.88881 16.031 20.389)" gradientUnits="userSpaceOnUse"><stop offset=".229" class="padl1sbsh"/><stop offset="1" class="w4y1jwbmd"/></radialGradient><radialGradient id="iBEqkLe" cx="0" cy="0" r="1" gradientTransform="matrix(-.8164 -.53126 1.47794 -2.27122 18.786 21.576)" gradientUnits="userSpaceOnUse"><stop class="wpyfqw4vs"/><stop offset="1" class="tja28sbvb"/></radialGradient><radialGradient id="iKwJqgb" cx="0" cy="0" r="1" gradientTransform="rotate(178.447 13.441 10.55)scale(2.70045 29.1455)" gradientUnits="userSpaceOnUse"><stop class="zmosas2ke"/><stop offset="1" class="cpfhw8b0c"/></radialGradient><radialGradient id="ixEv3LT" cx="0" cy="0" r="1" gradientTransform="matrix(2.60207 -1.18178 1.44211 3.17527 21.076 14.764)" gradientUnits="userSpaceOnUse"><stop offset=".572" class="qtr_-gj2q"/><stop offset=".905" class="yomsttbzk"/></radialGradient><radialGradient id="ip6ojXb" cx="0" cy="0" r="1" gradientTransform="rotate(-20.282 51.51 -53.255)scale(1.36368 1.36283)" gradientUnits="userSpaceOnUse"><stop offset=".71" class="iy3kcbc1e"/><stop offset="1" class="nfa0q6zfs"/></radialGradient><radialGradient id="iunyyYs" cx="0" cy="0" r="1" gradientTransform="matrix(-1.12288 0 0 -1.07322 11.975 14.305)" gradientUnits="userSpaceOnUse"><stop offset=".415" class="e3owjub-t"/><stop offset="1" class="qb0464bzj"/></radialGradient><radialGradient id="iSgns7k" cx="0" cy="0" r="1" gradientTransform="rotate(155.262 8.414 9.047)scale(7.48583 10.0143)" gradientUnits="userSpaceOnUse"><stop class="wa9cqx9pi"/><stop offset="1" class="m45oyzb-o"/></radialGradient><radialGradient id="iSijRic" cx="0" cy="0" r="1" gradientTransform="rotate(152.144 7.625 9.572)scale(2.49459 2.1155)" gradientUnits="userSpaceOnUse"><stop class="pb_rvfc5z"/><stop offset="1" class="v2k4g1b_w"/></radialGradient><radialGradient id="iOIJw3e" cx="0" cy="0" r="1" gradientTransform="rotate(-78.301 20.079 1.463)scale(4.31493 5.479)" gradientUnits="userSpaceOnUse"><stop class="wrs_9y9vq"/><stop offset="1" class="z-gb6n28y"/></radialGradient><radialGradient id="iIOM0db" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.77198 -12.3542 0 16.58 13.238)" gradientUnits="userSpaceOnUse"><stop offset=".593" class="ajxs5ri3z"/><stop offset="1" class="x05md6_2b"/></radialGradient><radialGradient id="iab2Nhb" cx="0" cy="0" r="1" gradientTransform="matrix(-5.66878 1.56623 -2.69466 -9.75299 17.509 15.474)" gradientUnits="userSpaceOnUse"><stop offset=".877" class="ud-bjxb5c"/><stop offset="1" class="a9dfe182j"/></radialGradient><radialGradient id="i7y4zZc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.20202 1.47643 0 19.259 13.306)" gradientUnits="userSpaceOnUse"><stop class="e0lgwbeaw"/><stop offset="1" class="y7n0ymbzx"/></radialGradient><radialGradient id="immo5Xb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.42057 1.62942 0 14.848 13.398)" gradientUnits="userSpaceOnUse"><stop class="w2e_edyjl"/><stop offset="1" class="gsggv-b-p"/></radialGradient><radialGradient id="i3pLImd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.40811 0 0 -4.6317 22.18 14.86)" gradientUnits="userSpaceOnUse"><stop class="f902gfhfn"/><stop offset="1" class="jh40i5bvl"/></radialGradient><radialGradient id="izCBpcb" cx="0" cy="0" r="1" gradientTransform="rotate(-105.904 14.732 1.14)scale(2.6607 1.52356)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="itt9z7bbf"/><stop offset="1" class="eh2hzabiv"/></radialGradient><radialGradient id="iACjyRJ" cx="0" cy="0" r="1" gradientTransform="matrix(0 .84745 -1.34908 0 19.135 13.681)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="ijg1ase" cx="0" cy="0" r="1" gradientTransform="matrix(-.24242 -.31213 .42972 -.33375 18.896 13.77)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iEdMrkp" cx="0" cy="0" r="1" gradientTransform="matrix(0 .84746 -1.34909 0 14.572 13.681)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iKN2uVD" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 .459 .075)scale(.51622 .62053)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iMwhdrV" cx="0" cy="0" r="1" gradientTransform="matrix(-5.5 4.12501 -3.615 -4.82 20.719 4.576)" gradientUnits="userSpaceOnUse"><stop offset=".179" class="tg07-ljnl"/><stop offset="1" class="c6833cb9x"/></radialGradient><radialGradient id="i3dSYhb" cx="0" cy="0" r="1" gradientTransform="matrix(2.875 .375 -.58342 4.4729 10.781 7.701)" gradientUnits="userSpaceOnUse"><stop class="j8k1fac_p"/><stop offset="1" class="g8uem1b5g"/></radialGradient><radialGradient id="inl9J2c" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.875 8.03906 0 16.773 8.326)" gradientUnits="userSpaceOnUse"><stop offset=".761" class="km6q7kb1a"/><stop offset="1" class="i8skpb2jz"/></radialGradient><radialGradient id="iCE2gke" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.47656 -8.28125 0 18.406 7.912)" gradientUnits="userSpaceOnUse"><stop class="kzuil_5zu"/><stop offset="1" class="ok2r3obil"/></radialGradient><radialGradient id="ixSAAAe" cx="0" cy="0" r="1" gradientTransform="matrix(-7.1875 0 0 -.63281 21.269 9.87)" gradientUnits="userSpaceOnUse"><stop class="w63qn2bkh"/><stop offset="1" class="vvfum-_fa"/></radialGradient><radialGradient id="iy7tjOa" cx="0" cy="0" r="1" gradientTransform="matrix(3.48438 0 0 2.01172 9.003 10.109)" gradientUnits="userSpaceOnUse"><stop class="gfrsedb9v"/><stop offset="1" class="vke6kh8bt"/></radialGradient><filter id="iIMgSyc" width="15.95" height="15.937" x="9.003" y="5.147" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.92549 0 0 0 0 0.537255 0 0 0 0 0.12549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23844"/></filter><filter id="iy1CE5d" width="21.247" height="10.303" x="6.25" y="19.623" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.776471 0 0 0 0 0.745098 0 0 0 0 0.741176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23844"/></filter><filter id="itlVy6d" width="2.078" height="2.078" x="15.622" y="27.457" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.792157 0 0 0 0 0.717647 0 0 0 0 0.788235 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_3987_23844"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_3987_23844" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.831373 0 0 0 0 0.745098 0 0 0 0 0.803922 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_3987_23844"/></filter><filter id="i2eHrec" width="2.078" height="2.078" x="15.622" y="25.444" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.792157 0 0 0 0 0.717647 0 0 0 0 0.788235 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_3987_23844"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_3987_23844" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.831373 0 0 0 0 0.745098 0 0 0 0 0.803922 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_3987_23844"/></filter><filter id="i14Vgbs" width="6.554" height="3.702" x="13.676" y="19.523" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.741176 0 0 0 0 0.666667 0 0 0 0 0.701961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23844"/></filter><filter id="iaVd1Hd" width="8.324" height="4.864" x="12.611" y="21.931" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23844" stdDeviation=".5"/></filter><filter id="iGjsbUc" width="2.672" height="2.865" x="13.611" y="22.403" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.780392 0 0 0 0 0.270588 0 0 0 0 0.396078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23844"/></filter><filter id="ifGYUXb" width="2.672" height="2.865" x="17.264" y="22.403" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.780392 0 0 0 0 0.270588 0 0 0 0 0.396078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23844"/></filter><filter id="ithTOoq" width="1.554" height="1.999" x="15.986" y="22.812" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.827451 0 0 0 0 0.137255 0 0 0 0 0.317647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23844"/></filter><filter id="iVpanRb" width="4.764" height="4.766" x="24.75" y="19.349" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.1"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.909804 0 0 0 0 0.658824 0 0 0 0 0.14902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23844"/></filter><filter id="idOdVHd" width="2.277" height="3.844" x="25.907" y="17.448" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".6"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.996078 0 0 0 0 0.713726 0 0 0 0 0.0862745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23844"/></filter><filter id="i2DrPMc" width="2.436" height="4.046" x="24.436" y="17.107" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.92549 0 0 0 0 0.643137 0 0 0 0 0.101961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23844"/></filter><filter id="i72qZmc" width="2.312" height="4.044" x="23.386" y="17.96" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.917647 0 0 0 0 0.631373 0 0 0 0 0.129412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23844"/></filter><filter id="iETXWCe" width="2.123" height="3.114" x="22.394" y="19.041" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.870588 0 0 0 0 0.619608 0 0 0 0 0.219608 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23844"/></filter><filter id="i5vVvue" width="3.002" height="3.147" x="6.649" y="16.347" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.811765 0 0 0 0 0.588235 0 0 0 0 0.294118 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23844"/></filter><filter id="idSDA3d" width="4.665" height="1.737" x="23.02" y="19.912" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23844" stdDeviation=".125"/></filter><filter id="isMdERc" width="3.464" height="3.362" x="10.273" y="12.624" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.768627 0 0 0 0 0.501961 0 0 0 0 0.160784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23844"/></filter><filter id="iSPPwyN" width="3.364" height="3.612" x="20.218" y="12.374" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.937255 0 0 0 0 0.576471 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23844"/></filter><filter id="i9KmNnD" width="3.246" height="3.244" x="20.277" y="12.683" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23844" stdDeviation=".25"/></filter><filter id="ivPiCie" width="2.746" height="2.744" x="10.602" y="12.933" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23844" stdDeviation=".125"/></filter><filter id="ichFdWh" width="10.654" height="11.761" x="11.526" y="9.18" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.92549 0 0 0 0 0.529412 0 0 0 0 0.137255 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23844"/></filter><filter id="iJVgzOd" width="2.962" height="3.801" x="15.203" y="13.277" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23844" stdDeviation=".25"/></filter><filter id="iCrlPrd" width="2.462" height="3.301" x="15.622" y="13.383" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23844" stdDeviation=".125"/></filter><filter id="iwwUVKd" width="3.852" height="1.576" x="14.927" y="16.767" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23844" stdDeviation=".05"/></filter><filter id="i2Zqbrd" width="3.129" height="1.343" x="17.847" y="12.838" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.141176 0 0 0 0 0.0862745 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23844"/></filter><filter id="i8EbOac" width="3.129" height="1.343" x="12.731" y="12.838" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.133333 0 0 0 0 0.0784314 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23844"/></filter><filter id="ifTRird" width="2.555" height="1.131" x="12.872" y="11.36" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.658824 0 0 0 0 0.270588 0 0 0 0 0.141176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23844"/></filter><filter id="iKMWs6b" width="2.555" height="1.131" x="18.535" y="11.36" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.658824 0 0 0 0 0.270588 0 0 0 0 0.141176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23844"/></filter><filter id="idopKFm" width=".813" height=".718" x="18.371" y="13.226" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23844" stdDeviation=".05"/></filter><filter id="i2VN4ed" width=".913" height=".936" x="19.254" y="13.309" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23844" stdDeviation=".1"/></filter><filter id="iS2KwGb" width="1.013" height="1.069" x="14.609" y="13.243" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23844" stdDeviation=".1"/></filter><filter id="ipC51Cb" width=".945" height=".727" x="13.816" y="13.218" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23844" stdDeviation=".05"/></filter><filter id="iVsvOqe" width="2.336" height=".995" x="18.581" y="11.492" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23844" stdDeviation=".1"/></filter><filter id="isYzPld" width="2.336" height=".995" x="12.882" y="11.492" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23844" stdDeviation=".1"/></filter><filter id="iahMVue" width="1.169" height="2.386" x="13.53" y="7.442" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23844" stdDeviation=".125"/></filter><linearGradient id="iJlNl1b" x1="21.76" x2="14.199" y1="7.043" y2="21.089" gradientUnits="userSpaceOnUse"><stop class="yr1vjkbzu"/><stop offset="1" class="btu9i2bec"/></linearGradient><linearGradient id="iK84mBb" x1="22.562" x2="21.812" y1="29.826" y2="29.826" gradientUnits="userSpaceOnUse"><stop class="fr__qmhjc"/><stop offset="1" class="gypp10kih"/></linearGradient><linearGradient id="iWCiqKd" x1="20.644" x2="21.062" y1="29.014" y2="29.014" gradientUnits="userSpaceOnUse"><stop class="hj-s-zboe"/><stop offset="1" class="s0umluqbl"/></linearGradient><linearGradient id="ipodSkc" x1="9.531" x2="4.906" y1="27.451" y2="27.451" gradientUnits="userSpaceOnUse"><stop class="sb-ednb_a"/><stop offset="1" class="v0501vbqa"/></linearGradient><linearGradient id="iXPTZOc" x1="9.75" x2="8.828" y1="27.076" y2="27.076" gradientUnits="userSpaceOnUse"><stop class="o_30au2yc"/><stop offset="1" class="c60cvac3k"/></linearGradient><linearGradient id="itP1zjc" x1="27.871" x2="22.844" y1="28.142" y2="28.142" gradientUnits="userSpaceOnUse"><stop class="i7zyuv8vr"/><stop offset=".907" class="qzhltkbuo"/></linearGradient><linearGradient id="i33ZCUz" x1="28.09" x2="27.168" y1="27.876" y2="27.876" gradientUnits="userSpaceOnUse"><stop class="tub8lbbfx"/><stop offset="1" class="bd09vtb_c"/></linearGradient><linearGradient id="i8tJXGc" x1="16.763" x2="16.763" y1="22.812" y2="24.81" gradientUnits="userSpaceOnUse"><stop offset=".351" class="gzsz7evmk"/><stop offset="1" class="smgiue0gi"/></linearGradient><linearGradient id="i994Uzd" x1="10.273" x2="13.367" y1="14.396" y2="14.396" gradientUnits="userSpaceOnUse"><stop class="o-5xddb6x"/><stop offset="1" class="h11_utkon"/></linearGradient><linearGradient id="iDu27Hb" x1="16.853" x2="16.853" y1="10.771" y2="11.993" gradientUnits="userSpaceOnUse"><stop class="a1bpy6bmb"/><stop offset="1" class="zowc6p8hv"/></linearGradient><linearGradient id="i2nI9kc" x1="16.854" x2="16.854" y1="16.434" y2="13.633" gradientUnits="userSpaceOnUse"><stop class="um-di3lxj"/><stop offset="1" class="fkdj3ejgt"/></linearGradient><linearGradient id="iuyhrAe" x1="15.76" x2="16.653" y1="15.638" y2="15.747" gradientUnits="userSpaceOnUse"><stop class="enxo4ub-d"/><stop offset="1" class="vsluyubzo"/></linearGradient><linearGradient id="iOqfDdc" x1="16.854" x2="16.854" y1="16.53" y2="15.893" gradientUnits="userSpaceOnUse"><stop class="kpdurub6t"/><stop offset="1" class="qwjswe-rp"/></linearGradient><linearGradient id="i1Yy7ab" x1="16.091" x2="16.563" y1="18.073" y2="17.162" gradientUnits="userSpaceOnUse"><stop class="q0k9-hbaq"/><stop offset="1" class="mhbvyzb9x"/></linearGradient><linearGradient id="iPtLbuc" x1="19.947" x2="19.619" y1="13.738" y2="13.94" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iot6ESb" x1="15.349" x2="15.022" y1="13.738" y2="13.94" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iol6Ose" x1="13.83" x2="14.399" y1="8.101" y2="9.432" gradientUnits="userSpaceOnUse"><stop class="riyyv6xjv"/><stop offset="1" class="lfjsh038a"/></linearGradient><linearGradient id="izP9Z9c" x1="16.773" x2="16.773" y1="7.912" y2="8.1" gradientUnits="userSpaceOnUse"><stop class="jhlen960d"/><stop offset="1" class="wjchuwb6a"/></linearGradient><linearGradient id="iYE2hsb" x1="17.956" x2="17.956" y1="10.98" y2="10.214" gradientUnits="userSpaceOnUse"><stop class="bl3fq0x9z"/><stop offset="1" class="lxo7c2i6k"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-juggling" /></template>
<style>
.a1bpy6bmb {
  stop-color: var(--svg-color--d9882d, #D9882D);
}

.a5zzorbzd {
  stop-color: var(--svg-color--e1ac3a, #E1AC3A);
}

.a9dfe182j {
  stop-color: var(--svg-color--d4993e, #D4993E);
}

.ab6i82btp {
  stop-color: var(--svg-color--e7377c, #E7377C);
}

.af8mzdbwl {
  stop-color: var(--svg-color--5f679a, #5F679A);
}

.ag6fa4z4y {
  stop-color: var(--svg-color--e26b25, #E26B25);
}

.ajxs5ri3z {
  stop-color: var(--svg-color--f3943b, #F3943B);
  stop-opacity: 0;
}

.aqzyd8bsb {
  stop-color: var(--svg-color--896bb4, #896BB4);
  stop-opacity: 0;
}

.auvn9fbbk {
  stop-color: var(--svg-color--e9387a, #E9387A);
}

.bd09vtb_c {
  stop-color: var(--svg-color--e0dde3, #E0DDE3);
  stop-opacity: 0;
}

.bl3fq0x9z {
  stop-color: var(--svg-color--543459, #543459);
}

.bq5dgsbba {
  stop-color: var(--svg-color--dcc8ec, #DCC8EC);
}

.bsid3ncbw {
  fill: var(--svg-color--ffd942, #FFD942);
  d: path("m27.85 19.83l-.447.824l-1.172 1.422l-1.481 1.992l3.099.047c.099-.172.218-.566.38-1.327c.164-.66.326-1.114.471-1.376l.443-.924a.726.726 0 0 0-1.292-.659");
}

.btor07b8q {
  stop-color: var(--svg-color--d61f4d, #D61F4D);
}

.btu9i2bec {
  stop-color: var(--svg-color--e37923, #E37923);
}

.c60cvac3k {
  stop-color: var(--svg-color--e5ddee, #E5DDEE);
  stop-opacity: 0;
}

.c6833cb9x {
  stop-color: var(--svg-color--372f3c, #372F3C);
}

.c7h5vdb0o {
  fill: var(--svg-color--000, #000);
  d: path("M15.104 14.115a.53.53 0 0 0-.534-.534a.532.532 0 0 0-.475.78h.945a.5.5 0 0 0 .064-.246");
}

.cfziuz30v {
  fill: var(--svg-color--ffc239, #FFC239);
  d: path("M22.414 19.88a.68.68 0 1 1 1.33-.293l.36 1.793a.645.645 0 0 1-1.26.28z");
}

.ci3gi1b_k {
  stop-color: var(--svg-color--784b89, #784B89);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cpfhw8b0c {
  stop-color: var(--svg-color--ffc32b, #FFC32B);
}

.ctsppjbax {
  d: path("M14.866 22.463c.91.308 1.268.83 1.389 1.082l.028.29l-.028.359c-.12.25-.48.706-1.389 1.014c-.36.123-.777.068-.97-.267a2.17 2.17 0 0 1-.285-1.105c0-.502.144-.862.285-1.106c.193-.335.61-.39.97-.267");
}

.ctupw6b3d {
  fill-rule: evenodd;
  d: path("M3.113 18.184a.75.75 0 0 1 1.042.196c.312.455.974 1.204 1.85 1.204a.75.75 0 1 1 0 1.5c-1.702 0-2.759-1.376-3.088-1.858a.75.75 0 0 1 .196-1.042");
}

.czcujwbjt {
  d: path("m16.454 13.928l-.556 1.775a.563.563 0 0 0 .545.731h.822c.385 0 .657-.37.544-.73l-.556-1.776c-.119-.394-.674-.394-.799 0");
}

.d5_x4xk7i {
  fill-rule: evenodd;
  d: path("M3.16 17.066a.75.75 0 0 1 1.042.197q.055.08.116.173c.17.259.379.576.676.877c.36.363.768.614 1.246.64a.75.75 0 0 1-.08 1.497c-.99-.052-1.73-.575-2.232-1.083c-.416-.42-.725-.893-.888-1.143l-.076-.115a.75.75 0 0 1 .196-1.043");
}

.d7caiobkz {
  stop-color: var(--svg-color--e4cc30, #E4CC30);
  stop-opacity: 0;
}

.ddpez5d9u {
  fill: var(--svg-color--ffc93e, #FFC93E);
  d: path("M23.407 18.803a.679.679 0 1 1 1.323-.298l.555 2.766a.613.613 0 0 1-1.195.27z");
}

.demkpcl0k {
  stop-color: var(--svg-color--b1a0b8, #B1A0B8);
}

.denqa3bda {
  stop-color: var(--svg-color--d77117, #D77117);
  stop-opacity: 0;
}

.dg9vkvbdw {
  stroke: var(--svg-color--c9725d, #C9725D);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M14.918 11.827c-.337-.082-1.176-.041-1.736.36");
}

.djl_ovbam {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M15.66 13.71c-.278-.487-.7-.872-1.608-.872c-.397 0-.78.11-1.121.385c-.281.227-.244.517-.026.626l.581.332c.682-.22 1.435-.25 2.173-.47");
}

.don2wdpjw {
  cx: 16.761px;
  cy: 26.282px;
  r: 0.739px;
}

.dpkv3e8bt {
  stop-color: var(--svg-color--efd8d5, #EFD8D5);
}

.dpmuo-biy {
  stop-color: var(--svg-color--6f5ea2, #6F5EA2);
}

.duwob45dr {
  stop-color: var(--svg-color--ffdf3c, #FFDF3C);
}

.duyhuibwk {
  cx: 9.246px;
  cy: 3.857px;
  r: 1.684px;
}

.dwn54oxgo {
  stop-color: var(--svg-color--ffe23d, #FFE23D);
}

.e-tdchb2h {
  stop-color: var(--svg-color--f7b528, #F7B528);
  stop-opacity: 0;
}

.e0lgwbeaw {
  stop-color: var(--svg-color--ffbb31, #FFBB31);
}

.e3owjub-t {
  stop-color: var(--svg-color--d67923, #D67923);
  stop-opacity: 0;
}

.e8-v49b1g {
  stop-color: var(--svg-color--efa929, #EFA929);
  stop-opacity: 0;
}

.eh2hzabiv {
  stop-color: var(--svg-color--ffe848, #FFE848);
  stop-opacity: 0;
}

.enxo4ub-d {
  stop-color: var(--svg-color--f8a322, #F8A322);
}

.esx41hbqq {
  stop-color: var(--svg-color--cba140, #CBA140);
}

.f21vmbcik {
  d: path("M5.437 21.764h4.094v8.063H5.437z");
}

.f902gfhfn {
  stop-color: var(--svg-color--ffda39, #FFDA39);
}

.fde_fwzpt {
  stop-color: var(--svg-color--5c9946, #5C9946);
}

.fgpnfrb_u {
  fill: var(--svg-color--bc9ebb, #BC9EBB);
  fill-rule: evenodd;
  d: path("M16.022 23.723c-.213-.246-.57-.534-1.156-.733c-.36-.122-.777-.067-.97.268c-.14.243-.285.604-.285 1.105s.144.862.285 1.105c.193.335.61.39.97.267c.604-.204.965-.474 1.175-.706c.048.135.159.24.305.268c.29.055.544.055.834 0a.41.41 0 0 0 .31-.285c.208.236.572.514 1.19.723c.362.123.778.068.971-.267c.14-.243.284-.598.284-1.105s-.144-.862-.284-1.105c-.193-.335-.61-.39-.97-.268c-.603.205-.964.503-1.174.754a.41.41 0 0 0-.327-.363a2.1 2.1 0 0 0-.834 0a.41.41 0 0 0-.324.342");
}

.fj67tibom {
  stop-color: var(--svg-color--ffd537, #FFD537);
  stop-opacity: 0;
}

.fkdj3ejgt {
  stop-color: var(--svg-color--f8c73f, #F8C73F);
}

.fpq5frbny {
  d: path("M14.762 18.363c0-.991.9-1.795 2.011-1.795s2.012.804 2.012 1.794v2.326c0 .991-.9 1.794-2.012 1.794c-1.11 0-2.011-.803-2.011-1.794z");
}

.fr__qmhjc {
  stop-color: var(--svg-color--7a6cad, #7A6CAD);
}

.frq_4bb4s {
  d: path("M19.137 13.183a.933.933 0 0 1 .899 1.178h-1.803a.936.936 0 0 1 .903-1.178");
}

.ft5dv1b6b {
  fill: none;
}

.fzq016boz {
  stop-color: var(--svg-color--e35838, #E35838);
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

.gsggv-b-p {
  stop-color: var(--svg-color--f09429, #F09429);
  stop-opacity: 0;
}

.gvcddab8z {
  d: path("M22.99 22.213c.118.463.585 1.456.804 1.894h4.047l-.258-3.789l-4.836.924c.031.13.123.507.242.97");
}

.gypp10kih {
  stop-color: var(--svg-color--7a6cad, #7A6CAD);
  stop-opacity: 0;
}

.gzcpsebza {
  stop-color: var(--svg-color--ded4e0, #DED4E0);
  stop-opacity: 0;
}

.gzsz7evmk {
  stop-color: var(--svg-color--eb3782, #EB3782);
}

.h11_utkon {
  stop-color: var(--svg-color--b96201, #B96201);
}

.h2li0wblg {
  stop-color: var(--svg-color--d02759, #D02759);
}

.h4mko5b9o {
  stop-color: var(--svg-color--beb4c6, #BEB4C6);
  stop-opacity: 0;
}

.h97a2frxj {
  fill: var(--svg-color--bd4f26, #BD4F26);
  d: path("m13.302 12.448l-.005.002a.28.28 0 0 1-.288-.48l.001-.001l.004-.002l.01-.006l.033-.018q.044-.024.121-.062c.103-.049.25-.112.43-.169a2.94 2.94 0 0 1 1.388-.114a.28.28 0 1 1-.098.552c-.416-.074-.817 0-1.12.096a3 3 0 0 0-.476.202");
}

.ha2cq84sa {
  stop-color: var(--svg-color--c9681c, #C9681C);
}

.hcmh5c50b {
  stop-color: var(--svg-color--357ace, #357ACE);
}

.hj-s-zboe {
  stop-color: var(--svg-color--6d5096, #6D5096);
}

.hoarz6bum {
  stop-color: var(--svg-color--fab32c, #FAB32C);
}

.hottnizrg {
  stop-color: var(--svg-color--ffd336, #FFD336);
  stop-opacity: 0;
}

.hpfqe6rjh {
  cx: 6.332px;
  cy: 12.838px;
  r: 1.684px;
}

.hq7_u2r_k {
  fill: var(--svg-color--e28527, #E28527);
  d: path("M11.975 15.427a1.122 1.122 0 1 0 0-2.245a1.122 1.122 0 0 0 0 2.245");
}

.hq864_b1v {
  stop-color: var(--svg-color--d2991f, #D2991F);
}

.ht6lpfbpp {
  d: path("M18.68 22.463c-.909.308-1.267.83-1.388 1.082l-.028.29l.028.359c.12.25.48.706 1.388 1.014c.362.123.778.068.971-.267c.14-.243.284-.599.284-1.105c0-.507-.144-.862-.284-1.106c-.193-.335-.61-.39-.97-.267");
}

.hv2lphb6i {
  d: path("M11.955 15.986a1.681 1.681 0 1 0 .001-3.363a1.681 1.681 0 0 0-.001 3.363");
}

.hwyai6h-t {
  fill: var(--svg-color--ffd343, #FFD343);
  d: path("M24.458 17.959a.68.68 0 0 1 .568-.843l.023-.003a.68.68 0 0 1 .756.54l.555 2.764a.615.615 0 0 1-1.198.275z");
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

.itt9z7bbf {
  stop-color: var(--svg-color--ffe848, #FFE848);
}

.iwbygtbvw {
  cx: 25.211px;
  cy: 4.873px;
  r: 1.684px;
}

.iy3kcbc1e {
  stop-color: var(--svg-color--ffba25, #FFBA25);
  stop-opacity: 0;
}

.j4x55bbau {
  fill: var(--svg-color--ffdd46, #FFDD46);
  d: path("M25.92 18.247a.668.668 0 1 1 1.316-.232l.34 2.222q.012.082.005.164l-.015.163c-.005.055-.002.11 0 .165c.016.295-.146.515-.454.557a.61.61 0 0 1-.68-.483z");
}

.j70rp9pis {
  d: path("M22.222 29.826h-1.578v-9.568q.826.307 1.578.746z");
}

.j8k1fac_p {
  stop-color: var(--svg-color--5b5a5d, #5B5A5D);
}

.jh40i5bvl {
  stop-color: var(--svg-color--ffda39, #FFDA39);
  stop-opacity: 0;
}

.jhlen960d {
  stop-color: var(--svg-color--745ba5, #745BA5);
}

.jjf293xlz {
  stop-color: var(--svg-color--d61f4d, #D61F4D);
  stop-opacity: 0;
}

.kdv9gpb4z {
  stop-color: var(--svg-color--dabdc3, #DABDC3);
}

.km6q7kb1a {
  stop-color: var(--svg-color--5d5565, #5D5565);
  stop-opacity: 0;
}

.koq0r9bvu {
  stop-color: var(--svg-color--9e78c9, #9E78C9);
}

.kpdurub6t {
  stop-color: var(--svg-color--e48538, #E48538);
}

.kpf8h5ohf {
  stop-color: var(--svg-color--db6009, #DB6009);
  stop-opacity: 0;
}

.kre23obqr {
  d: path("M19.967 13.993a.9.9 0 0 0-.241-.484l-.272.298l.122.239z");
}

.kzuil_5zu {
  stop-color: var(--svg-color--9072ca, #9072CA);
}

.l-r9gxb9g {
  stop-color: var(--svg-color--4bb8fb, #4BB8FB);
}

.l3ydtt4ya {
  stop-color: var(--svg-color--ffda02, #FFDA02);
}

.lcrdwk1fj {
  stop-color: var(--svg-color--c9641b, #C9641B);
}

.ld_83jb7a {
  d: path("M16.018 23.224a.41.41 0 0 1 .328-.37a2.1 2.1 0 0 1 .834 0a.41.41 0 0 1 .328.37c.042.395.042.778 0 1.174a.41.41 0 0 1-.328.37c-.29.056-.544.056-.834 0a.41.41 0 0 1-.328-.37a5.5 5.5 0 0 1 0-1.174");
}

.lelj2r8dg {
  stop-color: var(--svg-color--9ae453, #9AE453);
}

.lelniimio {
  stop-color: var(--svg-color--ffce38, #FFCE38);
}

.lfjsh038a {
  stop-color: var(--svg-color--db6008, #DB6008);
}

.lgi0lwbjz {
  stop-color: var(--svg-color--775184, #775184);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.ljh3pfo4c {
  d: path("M21.9 15.986a1.681 1.681 0 1 0 .001-3.363a1.681 1.681 0 0 0-.001 3.363");
}

.lliu2abxg {
  d: path("m13.676 20.005l.613 3.22h4.945l.797-3.173a10.2 10.2 0 0 0-2.938-.429h-.64c-.963 0-1.894.133-2.777.382");
}

.lr49rjb-q {
  fill: var(--svg-color--8a004f, #8A004F);
  d: path("M16.853 17.346c-.545 0-1.056-.13-1.486-.36c-.147-.076-.305.093-.213.23a2.02 2.02 0 0 0 3.397 0c.093-.143-.065-.306-.212-.23c-.43.23-.936.36-1.486.36");
}

.lxo7c2i6k {
  stop-color: var(--svg-color--462f5a, #462F5A);
  stop-opacity: 0;
}

.m-1-e5bla {
  stop-color: var(--svg-color--fbf2f7, #FBF2F7);
}

.m-2cz-bcp {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M18.047 13.71c.278-.487.7-.872 1.607-.872c.398 0 .781.11 1.122.385c.281.227.243.517.026.626l-.581.332c-.682-.22-1.435-.25-2.174-.47");
}

.m45oyzb-o {
  stop-color: var(--svg-color--eb9235, #EB9235);
}

.m5avsc_ef {
  stop-color: var(--svg-color--784b89, #784B89);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mhbvyzb9x {
  stop-color: var(--svg-color--feac35, #FEAC35);
  stop-opacity: 0;
}

.mmq2utbuk {
  stop-color: var(--svg-color--cf8b51, #CF8B51);
}

.mpwbs5b3u {
  stop-color: var(--svg-color--ff894e, #FF894E);
}

.mu0q52a8h {
  stop-color: var(--svg-color--d1923d, #D1923D);
}

.nfa0q6zfs {
  stop-color: var(--svg-color--ffba25, #FFBA25);
}

.nfiiif6yg {
  fill: var(--svg-color--eb8b29, #EB8B29);
  d: path("m16.443 14.072l-.715 1.776a.563.563 0 0 0 .545.73h.822c.385 0 .658-.37.544-.73l-.555-1.776c-.12-.393-.516-.393-.64 0");
}

.ng1cexbhj {
  stop-color: var(--svg-color--b6424c, #B6424C);
}

.nmqo35b7x {
  stop-color: var(--svg-color--ded4e0, #DED4E0);
}

.o_30au2yc {
  stop-color: var(--svg-color--decfd8, #DECFD8);
}

.o-5xddb6x {
  stop-color: var(--svg-color--e79b27, #E79B27);
}

.o415o878f {
  stop-color: var(--svg-color--ef4c8b, #EF4C8B);
}

.o87v3pbeq {
  rx: 0.407px;
  ry: 0.206px;
}

.oan4hab5a {
  d: path("M11.975 15.427a1.122 1.122 0 1 0 0-2.245a1.122 1.122 0 0 0 0 2.245");
}

.oaxszm67z {
  stop-color: var(--svg-color--cb6325, #CB6325);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ohjqpb16k {
  d: path("M11.535 12.986h.013l-.011-.277l-.01-.32c.02-.99.6-1.374.846-1.502l.054-.022l.053-.021a2.4 2.4 0 0 0 1.244-1.29l.086-.202a.276.276 0 0 1 .482-.053c.75 1.097 2.005 1.194 3.334 1.194h3.366c.83 0 1.132.645 1.188 1.945l-.124 3.21c-.13 2.927-2.417 4.893-5.21 4.893s-5.08-1.966-5.21-4.893z");
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

.p1xq25bjq {
  stop-color: var(--svg-color--d76a18, #D76A18);
  stop-opacity: 0;
}

.p4wkjrbae {
  stop-color: var(--svg-color--c9681c, #C9681C);
  stop-opacity: 0;
}

.padl1sbsh {
  stop-color: var(--svg-color--e68016, #E68016);
}

.pb_rvfc5z {
  stop-color: var(--svg-color--ffe842, #FFE842);
}

.pb6efmson {
  stop-color: var(--svg-color--d72c5e, #D72C5E);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pp1m28b5p {
  fill: var(--svg-color--fff, #fff);
  d: path("M14.354 12.899c-.683 0-1.26.47-1.416 1.106a.286.286 0 0 0 .28.356h2.332a.24.24 0 0 0 .237-.284a1.464 1.464 0 0 0-1.433-1.178");
}

.ppr920emc {
  stop-color: var(--svg-color--61a150, #61A150);
  stop-opacity: 0;
}

.pt8frltpn {
  stop-color: var(--svg-color--7060a5, #7060A5);
}

.ptlpnyb1n {
  fill: var(--svg-color--fff, #fff);
  d: path("M19.353 12.899c.683 0 1.26.47 1.416 1.106a.286.286 0 0 1-.28.356h-2.332a.24.24 0 0 1-.238-.284a1.46 1.46 0 0 1 1.434-1.178");
}

.q0k9-hbaq {
  stop-color: var(--svg-color--feac35, #FEAC35);
}

.qb0464bzj {
  stop-color: var(--svg-color--d67923, #D67923);
}

.qir_1cb0f {
  stop-color: var(--svg-color--e26b25, #E26B25);
  stop-opacity: 0;
}

.qsu4qbckq {
  stop-color: var(--svg-color--dbcdd4, #DBCDD4);
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

.qy4rrcb8b {
  d: path("M12.857 29.826h-1.578v-8.795a10 10 0 0 1 1.578-.756z");
}

.qzd219blo {
  d: path("M11 8.662a5.773 5.773 0 1 1 11.547 0v1.648H11z");
}

.qzhltkbuo {
  stop-color: var(--svg-color--b9aac8, #B9AAC8);
}

.r-2q1cb7n {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.407px;
  ry: 0.206px;
}

.riyyv6xjv {
  stop-color: var(--svg-color--faa719, #FAA719);
}

.s0umluqbl {
  stop-color: var(--svg-color--7160a4, #7160A4);
  stop-opacity: 0;
}

.s19inuw5i {
  fill: var(--svg-color--000, #000);
  d: path("M18.602 14.115c0-.296.237-.534.534-.534a.532.532 0 0 1 .474.78h-.944a.5.5 0 0 1-.064-.246");
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

.smgiue0gi {
  stop-color: var(--svg-color--c93857, #C93857);
}

.sqf03_p-t {
  stop-color: var(--svg-color--f8e6e8, #F8E6E8);
}

.sufhn4bec {
  stop-color: var(--svg-color--db6009, #DB6009);
}

.swka_j87x {
  d: path("M6.25 29.826c0-5.635 4.568-10.203 10.203-10.203h.64c5.636 0 10.204 4.568 10.204 10.203z");
}

.t-5nldk3g {
  cx: 16.761px;
  cy: 28.296px;
  r: 0.739px;
}

.t8f3iprss {
  d: path("M14.57 13.183a.933.933 0 0 0-.899 1.178h1.802a1 1 0 0 0 .034-.246a.94.94 0 0 0-.937-.932");
}

.tg07-ljnl {
  stop-color: var(--svg-color--5e5764, #5E5764);
}

.tgqxysbgm {
  stop-color: var(--svg-color--d76a18, #D76A18);
}

.tja28sbvb {
  stop-color: var(--svg-color--fdb836, #FDB836);
  stop-opacity: 0;
}

.tn_97qkdc {
  stop-color: var(--svg-color--f2c341, #F2C341);
  stop-opacity: 0;
}

.tqzzcj6ns {
  fill-rule: evenodd;
  d: path("M24.365 15.778c.222-.455.338-.963.338-1.491c0-.488-.1-.946-.28-1.364h.005a3.3 3.3 0 0 0-.294-.536l-.002-.003a3.4 3.4 0 0 1-.55-1.85v-.01c0-.801-1.222-.742-1.681-1.328c-.632-.805-.666-2.118-1.768-2.118a.56.56 0 0 1-.476-.243a3.46 3.46 0 0 0-2.804-1.438c-1.153 0-2.18.57-2.803 1.438a.59.59 0 0 1-.477.243h-.088c-1.107.029-1.326 1.44-1.937 2.274c-.418.57-1.423.41-1.423 1.172v.01c0 .656-.19 1.3-.55 1.85l-.003.004a3.44 3.44 0 0 0-.23 3.39a.54.54 0 0 1 0 .475a3.358 3.358 0 0 0 3.026 4.83h8.971a3.358 3.358 0 0 0 3.026-4.83a.54.54 0 0 1 0-.476m-12.817-2.792h-.013l1.253 2.46c.13 2.928 1.272 0 4.065 0s4.01 3.259 4.14.332l1.187-3.34c-.056-1.3-1-2.398-1.187-2.398h-3.367c-1.329 0-2.583.356-3.334-.741a.276.276 0 0 0-.482.053l-.086.202a2.4 2.4 0 0 1-1.243 1.29q-.025.008-.054.021l-.054.021c-.246.128-.825.512-.846 1.503l.01.32z");
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

.u0-djrvhx {
  stop-color: var(--svg-color--ffd537, #FFD537);
}

.u1gl_1zha {
  stop-color: var(--svg-color--ec4182, #EC4182);
  stop-opacity: 0;
}

.u5bjt8cdp {
  d: path("M6.803 17.694a.782.782 0 0 1 1.249-.941l.93 1.214c.337.438.519.975.519 1.527l-1.5-.18z");
}

.u6lph46no {
  stop-color: var(--svg-color--f0dff0, #F0DFF0);
}

.ud-bjxb5c {
  stop-color: var(--svg-color--d4993e, #D4993E);
  stop-opacity: 0;
}

.ujrq6ixuu {
  stop-color: var(--svg-color--beb4c6, #BEB4C6);
}

.um-di3lxj {
  stop-color: var(--svg-color--ffc134, #FFC134);
}

.v0501vbqa {
  stop-color: var(--svg-color--c0b5cd, #C0B5CD);
}

.v0i04x6vh {
  stop-color: var(--svg-color--ffbd23, #FFBD23);
}

.v2k4g1b_w {
  stop-color: var(--svg-color--ffe842, #FFE842);
  stop-opacity: 0;
}

.v5pmfy16o {
  fill: var(--svg-color--ffca38, #FFCA38);
  d: path("M21.9 15.427a1.122 1.122 0 1 0 0-2.245a1.122 1.122 0 0 0 0 2.245");
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.v61l3jbat {
  stop-color: var(--svg-color--ffdf3c, #FFDF3C);
  stop-opacity: 0;
}

.v9rq5jjti {
  stop-color: var(--svg-color--cba140, #CBA140);
  stop-opacity: 0;
}

.vdngsab5t {
  fill-rule: evenodd;
  d: path("M3.416 19.34a.75.75 0 0 1 1.051.14c.244.317.833.881 1.8.881a.75.75 0 0 1 .75.75c0 .415-.336.67-.75.67c-1.683 0-2.593-.87-2.99-1.39a.75.75 0 0 1 .139-1.05");
}

.vgk5w_bmg {
  stop-color: var(--svg-color--ffc12e, #FFC12E);
}

.vke6kh8bt {
  stop-color: var(--svg-color--3e3843, #3E3843);
  stop-opacity: 0;
}

.vsluyubzo {
  stop-color: var(--svg-color--f8a322, #F8A322);
  stop-opacity: 0;
}

.vvfum-_fa {
  stop-color: var(--svg-color--392f42, #392F42);
}

.vvmlqccxo {
  d: path("M21.9 15.427a1.122 1.122 0 1 0 0-2.245a1.122 1.122 0 0 0 0 2.245");
}

.vxy77p_hq {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M19.068 13.38c.066.089-.073.197-.23.315c-.159.118-.276.201-.342.112c-.067-.088.007-.256.165-.374s.34-.142.407-.053");
}

.w2e_edyjl {
  stop-color: var(--svg-color--f09429, #F09429);
}

.w3-vy4c8j {
  stop-color: var(--svg-color--e38923, #E38923);
}

.w4ea2bbjv {
  stop-color: var(--svg-color--efd8d5, #EFD8D5);
  stop-opacity: 0;
}

.w4y1jwbmd {
  stop-color: var(--svg-color--ffaa3a, #FFAA3A);
}

.w5vup9bwr {
  stop-color: var(--svg-color--eda628, #EDA628);
  stop-opacity: 0;
}

.w63qn2bkh {
  stop-color: var(--svg-color--605966, #605966);
}

.w6tinjvyq {
  cx: 25.353px;
  cy: 20.78px;
  rx: 2.12px;
  ry: 0.475px;
}

.w72oynbwi {
  stop-color: var(--svg-color--e38923, #E38923);
  stop-opacity: 0;
}

.wa9cqx9pi {
  stop-color: var(--svg-color--ffe644, #FFE644);
}

.wef8zac8b {
  stop-color: var(--svg-color--ffdd43, #FFDD43);
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

.wpmv2hblc {
  d: path("M19.068 13.38c.066.089-.073.197-.23.315c-.159.118-.276.201-.342.112c-.067-.088.007-.256.165-.374s.34-.142.407-.053");
}

.wpyfqw4vs {
  stop-color: var(--svg-color--fdb836, #FDB836);
}

.wrs_9y9vq {
  stop-color: var(--svg-color--e4883f, #E4883F);
}

.wshx69b-y {
  stop-color: var(--svg-color--896bb4, #896BB4);
}

.wwxb6rbbd {
  stroke: var(--svg-color--c9725d, #C9725D);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M18.88 11.827c.338-.082 1.176-.041 1.737.36");
}

.x05md6_2b {
  stop-color: var(--svg-color--d97c39, #D97C39);
}

.x1l7xqbyw {
  stop-color: var(--svg-color--de5534, #DE5534);
  stop-opacity: 0;
}

.x92j_kb4w {
  stop-color: var(--svg-color--d4c4da, #D4C4DA);
}

.xntzq-4ho {
  stop-color: var(--svg-color--8566b5, #8566B5);
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

.y6ze32mia {
  stop-color: var(--svg-color--c3863f, #C3863F);
}

.y7n0ymbzx {
  stop-color: var(--svg-color--ffbb31, #FFBB31);
  stop-opacity: 0;
}

.y8mrckbab {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M13.83 7.742c.025.254.246 1.208.57 1.786");
}

.yh2htvgmn {
  d: path("M15.422 14.006c0-.302-.245-.502-.311-.563l-.302.291l.186.378z");
}

.ym-b_m9fy {
  stop-color: var(--svg-color--d1bed4, #D1BED4);
  stop-opacity: 0;
}

.yomsttbzk {
  stop-color: var(--svg-color--ffe549, #FFE549);
}

.yqk-2gbyp {
  stop-color: var(--svg-color--cb6325, #CB6325);
}

.yr1vjkbzu {
  stop-color: var(--svg-color--ffd93c, #FFD93C);
}

.ys9yiru4r {
  fill: var(--svg-color--bd4f26, #BD4F26);
  fill-rule: evenodd;
  d: path("m20.754 11.97l-.144.24za.28.28 0 1 1-.288.48l-.005-.002a2 2 0 0 0-.118-.061a3 3 0 0 0-.358-.141a2.4 2.4 0 0 0-1.12-.096a.28.28 0 0 1-.098-.552c.537-.094 1.033 0 1.389.114a3.4 3.4 0 0 1 .55.23l.034.02l.01.005z");
}

.z-gb6n28y {
  stop-color: var(--svg-color--e4883f, #E4883F);
  stop-opacity: 0;
}

.zdcorrl9x {
  cx: 26.234px;
  cy: 14.83px;
  r: 1.684px;
}

.zeffp9bvk {
  stop-color: var(--svg-color--f5a913, #F5A913);
}

.zmosas2ke {
  stop-color: var(--svg-color--ffd709, #FFD709);
}

.zncfmhvrl {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M16.853 17.346c-.545 0-1.056-.13-1.486-.36c-.147-.076-.305.093-.213.23a2.02 2.02 0 0 0 3.397 0c.093-.143-.065-.306-.212-.23c-.43.23-.936.36-1.486.36Z");
}

.zowc6p8hv {
  stop-color: var(--svg-color--f6bd3e, #F6BD3E);
  stop-opacity: 0;
}

</style>
