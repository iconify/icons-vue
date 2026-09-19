<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iHhsQec)"><path fill="url(#iCWg3yz)" class="swka_j87x"/><path fill="url(#iTFB9Bb)" class="swka_j87x"/><path fill="url(#iw5sInd)" class="swka_j87x"/><path fill="url(#il5eVUq)" class="swka_j87x"/><path fill="url(#iY3yYtd)" class="swka_j87x"/></g><circle fill="url(#iBZ0RUd)" class="hpfqe6rjh"/><circle fill="url(#itKlKTd)" class="hpfqe6rjh"/><circle fill="url(#ihlr5IT)" class="duyhuibwk"/><circle fill="url(#iGUmgWd)" class="duyhuibwk"/><circle fill="url(#iXhqZHd)" class="iwbygtbvw"/><circle fill="url(#iOHvRJe)" class="iwbygtbvw"/><circle fill="url(#issuNue)" class="zdcorrl9x"/><circle fill="url(#iMaLBhb)" class="zdcorrl9x"/><circle fill="url(#iAhrvZc)" class="zdcorrl9x"/><g filter="url(#iXUX2Mu)"><circle fill="url(#iMk8UMb)" class="t-5nldk3g"/></g><g filter="url(#i6D4Q7b)"><circle fill="url(#iR23Gge)" class="don2wdpjw"/></g><path fill="url(#i5YvaPc)" class="j70rp9pis"/><path fill="url(#iK84mBb)" class="j70rp9pis"/><path fill="url(#iWCiqKd)" class="j70rp9pis"/><path fill="url(#ieol8Me)" class="qy4rrcb8b"/><path fill="url(#iDbbcbc)" class="qy4rrcb8b"/><path fill="url(#iOe2zrd)" class="qy4rrcb8b"/><path fill="url(#iV71Rbc)" class="qy4rrcb8b"/><g filter="url(#iR7lOpc)"><path fill="url(#i5S4ipb)" class="cyi-b68yu"/><path fill="url(#ix2mzrc)" class="cyi-b68yu"/></g><path fill="url(#ipodSkc)" class="f21vmbcik"/><path fill="url(#iXPTZOc)" class="f21vmbcik"/><path fill="url(#itP1zjc)" class="wp2p6dbcv"/><path fill="url(#i33ZCUz)" class="wp2p6dbcv"/><g filter="url(#ieGS5Vc)"><path clip-rule="evenodd" class="fgpnfrb_u"/></g><g filter="url(#iecPnWb)"><path fill="url(#iSAsI1d)" class="ctsppjbax"/><path fill="url(#iwtPTOo)" class="ctsppjbax"/><path fill="url(#isAdhHe)" class="ctsppjbax"/></g><g filter="url(#iSo54bd)"><path fill="url(#ivLP6Gc)" class="ht6lpfbpp"/><path fill="url(#iXetYud)" class="ht6lpfbpp"/></g><g filter="url(#iqQr4qV)"><path fill="url(#i8tJXGc)" class="ld_83jb7a"/><path fill="url(#iw9bnJb)" class="ld_83jb7a"/></g><g filter="url(#iss6Pvd)"><path class="bsid3ncbw"/></g><g filter="url(#iVeku9U)"><path class="j4x55bbau"/></g><g filter="url(#iue1kme)"><path class="hwyai6h-t"/></g><g filter="url(#i9Lm63q)"><path class="ddpez5d9u"/></g><g filter="url(#i9yuSEb)"><path class="cfziuz30v"/></g><path fill="url(#ipMueJd)" class="gvcddab8z"/><path fill="url(#i3JaYLp)" class="gvcddab8z"/><g filter="url(#i9V7hSb)"><path fill="url(#iTna7Kc)" class="u5bjt8cdp"/></g><path fill="url(#ih4s9ac)" clip-rule="evenodd" class="wfgw5ub6b"/><path fill="url(#ikJdwNc)" clip-rule="evenodd" class="wfgw5ub6b"/><path fill="url(#i40zLFb)" clip-rule="evenodd" class="d5_x4xk7i"/><path fill="url(#il9qrHe)" clip-rule="evenodd" class="d5_x4xk7i"/><path fill="url(#imjV17b)" clip-rule="evenodd" class="ctupw6b3d"/><path fill="url(#iD8Aurb)" clip-rule="evenodd" class="ctupw6b3d"/><path fill="url(#i2Iv6ab)" clip-rule="evenodd" class="vdngsab5t"/><path fill="url(#ihNB5dd)" clip-rule="evenodd" class="vdngsab5t"/><path fill="url(#ilhtGxd)" class="twba206ho"/><path fill="url(#itEg77z)" class="twba206ho"/><path fill="url(#i8FqvGc)" class="fpq5frbny"/><path fill="url(#iBEqkLe)" class="fpq5frbny"/><g filter="url(#icGKBic)"><ellipse fill="url(#iKwJqgb)" transform="rotate(-11.027 25.353 20.78)" class="w6tinjvyq"/></g><path fill="url(#i1Vefld)" class="y6vse6_qo"/><path fill="url(#iyY4azJ)" class="y6vse6_qo"/><path fill="url(#iFhrhPb)" class="a7xqagbcb"/><path fill="url(#iMinkib)" class="a7xqagbcb"/><g filter="url(#iHO4xMb)"><path fill="url(#iSR03fd)" class="i4_9z4_vp"/></g><path fill="url(#i0fgNLe)" class="i4_9z4_vp"/><path fill="url(#ibln6Sc)" class="i4_9z4_vp"/><path fill="url(#iDqMLQc)" class="i4_9z4_vp"/><path fill="url(#i5Ryunc)" class="i4_9z4_vp"/><path fill="url(#iosHfeb)" class="i4_9z4_vp"/><g filter="url(#izD1wze)"><path class="fjgbgxbbd"/></g><g filter="url(#ionUJae)"><path fill="url(#iIKRyTb)" class="miwt9fbcd"/><path fill="url(#i2tY9De)" class="miwt9fbcd"/><path fill="url(#i2nQh7d)" class="miwt9fbcd"/><path fill="url(#iUVwrIc)" class="miwt9fbcd"/></g><g filter="url(#iCWn9Zd)"><path stroke="url(#igChQVc)" class="ibuznhb7a"/></g><path fill="url(#iPcyP6b)" class="irk66op0u"/><g filter="url(#iRGe5xd)"><path fill="url(#ixdP1uA)" class="vq-kd0zaf"/><path fill="url(#i8LoVXd)" class="vq-kd0zaf"/><path fill="url(#ivRpDLc)" class="vq-kd0zaf"/><path fill="url(#iNvOWdb)" class="vq-kd0zaf"/><path fill="url(#iYpAaRb)" class="vq-kd0zaf"/></g><g filter="url(#ivxCIDw)"><path class="wrz017bzp"/></g><g filter="url(#iO05ZFb)"><path class="l3d0520td"/></g><path class="rupv3qobh"/><path fill="url(#iFVlAJd)" class="tzo02q1al"/><path class="z7d6tabwf"/><g filter="url(#iF2R3bb)"><path class="z93ygib1c"/><path fill="url(#i9qdvye)" class="npskz24gn"/></g><g filter="url(#iaSfA7b)"><path fill="url(#iq0dcad)" class="wlq6ufb3a"/></g><path class="xe9265amt"/><path fill="url(#iBVa7oc)" class="uhdec2fht"/><path class="donv6bcww"/><g filter="url(#ictHIse)"><path fill="url(#iAZOZld)" class="m0-m1fdur"/></g><g filter="url(#ikkd0kd)"><ellipse transform="rotate(-27.914 14.213 13.315)" class="zvbtjsb5l"/><ellipse fill="url(#iA3K1fe)" transform="rotate(-27.914 14.213 13.315)" class="n_uwwia7r"/></g><path fill="url(#it6KCqb)" class="m3r-0t5fu"/><path fill="url(#iibb9Sd)" class="m3r-0t5fu"/><path fill="url(#ioLYiHB)" class="m3r-0t5fu"/><path fill="url(#ivQSrCe)" class="nugpx2cgg"/><path fill="url(#i40HCse)" class="nugpx2cgg"/><g filter="url(#irKkSub)"><path class="slg6r6crg"/></g><g filter="url(#iskkgUb)"><path class="t0gi-gb8u"/></g><g filter="url(#itDs7he)"><path stroke="url(#iEtS1ge)" class="h1373oqiz"/></g><g filter="url(#icWPJ1c)"><path stroke="url(#il15Eqd)" class="pyl-ckr1z"/></g><path fill="url(#iMwhdrV)" class="qzd219blo"/><path fill="url(#i3dSYhb)" class="qzd219blo"/><path fill="url(#inl9J2c)" class="qzd219blo"/><path fill="url(#iCE2gke)" class="wozepxbaa"/><path fill="url(#izP9Z9c)" class="wozepxbaa"/><rect fill="url(#ixSAAAe)" class="okwd93kys"/><rect fill="url(#iy7tjOa)" class="okwd93kys"/><rect fill="url(#iYE2hsb)" class="okwd93kys"/><defs><radialGradient id="iCWg3yz" cx="0" cy="0" r="1" gradientTransform="rotate(135.22 8.643 15.887)scale(12.9545 12.5552)" gradientUnits="userSpaceOnUse"><stop offset=".195" class="m-1-e5bla"/><stop offset=".655" class="x92j_kb4w"/></radialGradient><radialGradient id="iTFB9Bb" cx="0" cy="0" r="1" gradientTransform="matrix(2.75 0 0 6.1875 8.969 25.389)" gradientUnits="userSpaceOnUse"><stop class="nmqo35b7x"/><stop offset="1" class="gzcpsebza"/></radialGradient><radialGradient id="iw5sInd" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.09375 -3.28125 0 20.219 20.139)" gradientUnits="userSpaceOnUse"><stop class="dpkv3e8bt"/><stop offset="1" class="w4ea2bbjv"/></radialGradient><radialGradient id="il5eVUq" cx="0" cy="0" r="1" gradientTransform="matrix(-1.75 0 0 -11.7187 21 25.92)" gradientUnits="userSpaceOnUse"><stop offset=".214" class="demkpcl0k"/><stop offset="1" class="ym-b_m9fy"/></radialGradient><radialGradient id="iY3yYtd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.15625 0 0 -5.75902 11.656 25.326)" gradientUnits="userSpaceOnUse"><stop class="ujrq6ixuu"/><stop offset="1" class="h4mko5b9o"/></radialGradient><radialGradient id="iBZ0RUd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.34375 2.4375 -2.36069 -1.3014 7.187 11.826)" gradientUnits="userSpaceOnUse"><stop offset=".077" class="l-r9gxb9g"/><stop offset="1" class="hcmh5c50b"/></radialGradient><radialGradient id="itKlKTd" cx="0" cy="0" r="1" gradientTransform="rotate(115.145 -.151 8.247)scale(3.38309 2.95533)" gradientUnits="userSpaceOnUse"><stop offset=".452" class="y-1rsmdul"/><stop offset=".826" class="af8mzdbwl"/></radialGradient><radialGradient id="ihlr5IT" cx="0" cy="0" r="1" gradientTransform="matrix(-1.34375 2.4375 -2.36069 -1.3014 10.101 2.846)" gradientUnits="userSpaceOnUse"><stop offset=".077" class="mpwbs5b3u"/><stop offset="1" class="fzq016boz"/></radialGradient><radialGradient id="iGUmgWd" cx="0" cy="0" r="1" gradientTransform="rotate(115.145 4.158 4.683)scale(3.38309 2.95533)" gradientUnits="userSpaceOnUse"><stop offset=".452" class="x1l7xqbyw"/><stop offset=".826" class="ng1cexbhj"/></radialGradient><radialGradient id="iXhqZHd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.34375 2.4375 -2.36069 -1.3014 26.066 3.861)" gradientUnits="userSpaceOnUse"><stop offset=".077" class="lelj2r8dg"/><stop offset="1" class="fde_fwzpt"/></radialGradient><radialGradient id="iOHvRJe" cx="0" cy="0" r="1" gradientTransform="rotate(105.03 11.36 11.751)scale(3.49455 3.40391)" gradientUnits="userSpaceOnUse"><stop offset=".375" class="ppr920emc"/><stop offset=".826" class="y_auwli2s"/></radialGradient><radialGradient id="issuNue" cx="0" cy="0" r="1" gradientTransform="matrix(-1.34375 2.4375 -2.36069 -1.3014 27.09 13.818)" gradientUnits="userSpaceOnUse"><stop offset=".077" class="y05rrkbkk"/><stop offset="1" class="a5zzorbzd"/></radialGradient><radialGradient id="iMaLBhb" cx="0" cy="0" r="1" gradientTransform="matrix(1 1.07812 -1.5877 1.47265 24.969 13.357)" gradientUnits="userSpaceOnUse"><stop class="i8j0jyb4u"/><stop offset="1" class="d7caiobkz"/></radialGradient><radialGradient id="iAhrvZc" cx="0" cy="0" r="1" gradientTransform="rotate(109.11 8.51 16.52)scale(3.46022 3.37046)" gradientUnits="userSpaceOnUse"><stop offset=".347" class="tn_97qkdc"/><stop offset=".829" class="mmq2utbuk"/></radialGradient><radialGradient id="iMk8UMb" cx="0" cy="0" r="1" gradientTransform="matrix(-.7578 1.14063 -.96756 -.64282 17.25 27.855)" gradientUnits="userSpaceOnUse"><stop offset=".212" class="u6lph46no"/><stop offset="1" class="bq5dgsbba"/></radialGradient><radialGradient id="iR23Gge" cx="0" cy="0" r="1" gradientTransform="matrix(-.7578 1.14063 -.96756 -.64282 17.25 25.842)" gradientUnits="userSpaceOnUse"><stop offset=".212" class="u6lph46no"/><stop offset="1" class="bq5dgsbba"/></radialGradient><radialGradient id="i5YvaPc" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.03125 -2.40212 0 22.222 20.983)" gradientUnits="userSpaceOnUse"><stop class="koq0r9bvu"/><stop offset="1" class="dpmuo-biy"/></radialGradient><radialGradient id="ieol8Me" cx="0" cy="0" r="1" gradientTransform="scale(1.38818 6.1875)rotate(90 2.761 6.5)" gradientUnits="userSpaceOnUse"><stop class="xntzq-4ho"/><stop offset="1" class="pt8frltpn"/></radialGradient><radialGradient id="iDbbcbc" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.25 -.60938 0 13.062 24.108)" gradientUnits="userSpaceOnUse"><stop class="wshx69b-y"/><stop offset="1" class="aqzyd8bsb"/></radialGradient><radialGradient id="iOe2zrd" cx="0" cy="0" r="1" gradientTransform="matrix(2.9375 -7.98881 7.06186 2.59666 10.312 28.264)" gradientUnits="userSpaceOnUse"><stop offset=".724" class="lgi0lwbjz"/><stop offset="1" class="tvoyviyhj"/></radialGradient><radialGradient id="iV71Rbc" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.42188 -.18506 0 12.857 21.717)" gradientUnits="userSpaceOnUse"><stop class="m5avsc_ef"/><stop offset="1" class="ci3gi1b_k"/></radialGradient><radialGradient id="i5S4ipb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.90624 2.42972 -4.28692 -6.89204 19.562 20.795)" gradientUnits="userSpaceOnUse"><stop class="sqf03_p-t"/><stop offset="1" class="kdv9gpb4z"/></radialGradient><radialGradient id="ix2mzrc" cx="0" cy="0" r="1" gradientTransform="matrix(-.46875 -.125 .54686 -2.05079 19.484 22.483)" gradientUnits="userSpaceOnUse"><stop offset=".108" class="qsu4qbckq"/><stop offset="1" class="gr0wzobbs"/></radialGradient><radialGradient id="iSAsI1d" cx="0" cy="0" r="1" gradientTransform="matrix(1.73878 1.3451 -1.47727 1.90964 13.775 23.358)" gradientUnits="userSpaceOnUse"><stop class="ab6i82btp"/><stop offset="1" class="pb6efmson"/></radialGradient><radialGradient id="iwtPTOo" cx="0" cy="0" r="1" gradientTransform="matrix(-1.68958 -.4774 .79459 -2.81214 15.416 23.836)" gradientUnits="userSpaceOnUse"><stop offset=".69" class="sawf8hb2n"/><stop offset="1" class="o415o878f"/></radialGradient><radialGradient id="isAdhHe" cx="0" cy="0" r="1" gradientTransform="matrix(-.5 1.58457 -.75053 -.23683 16.11 23.836)" gradientUnits="userSpaceOnUse"><stop class="btor07b8q"/><stop offset="1" class="jjf293xlz"/></radialGradient><radialGradient id="ivLP6Gc" cx="0" cy="0" r="1" gradientTransform="rotate(142.275 5.895 15.056)scale(2.19833 2.41434)" gradientUnits="userSpaceOnUse"><stop class="auvn9fbbk"/><stop offset="1" class="h2li0wblg"/></radialGradient><radialGradient id="iXetYud" cx="0" cy="0" r="1" gradientTransform="matrix(1.68958 -.4774 .79459 2.81214 18.13 23.836)" gradientUnits="userSpaceOnUse"><stop offset=".69" class="sawf8hb2n"/><stop offset="1" class="o415o878f"/></radialGradient><radialGradient id="iw9bnJb" cx="0" cy="0" r="1" gradientTransform="matrix(-.39136 0 0 -2.59279 17.54 23.592)" gradientUnits="userSpaceOnUse"><stop class="scbqttb8d"/><stop offset="1" class="u1gl_1zha"/></radialGradient><radialGradient id="ipMueJd" cx="0" cy="0" r="1" gradientTransform="matrix(-4.375 1.44046 -1.3893 -4.21963 28.094 22.456)" gradientUnits="userSpaceOnUse"><stop offset=".241" class="l3ydtt4ya"/><stop offset=".899" class="vgk5w_bmg"/></radialGradient><radialGradient id="i3JaYLp" cx="0" cy="0" r="1" gradientTransform="rotate(163.091 11.836 12.97)scale(3.90165 13.4872)" gradientUnits="userSpaceOnUse"><stop offset=".699" class="w5vup9bwr"/><stop offset="1" class="mu0q52a8h"/></radialGradient><radialGradient id="iTna7Kc" cx="0" cy="0" r="1" gradientTransform="rotate(139.97 1.2 10.48)scale(1.53045 3.638)" gradientUnits="userSpaceOnUse"><stop offset=".129" class="lelniimio"/><stop offset="1" class="zeffp9bvk"/></radialGradient><radialGradient id="ih4s9ac" cx="0" cy="0" r="1" gradientTransform="matrix(-.79386 1.27188 -2.4349 -1.51978 6.442 17.553)" gradientUnits="userSpaceOnUse"><stop class="wef8zac8b"/><stop offset="1" class="hoarz6bum"/></radialGradient><radialGradient id="ikJdwNc" cx="0" cy="0" r="1" gradientTransform="matrix(-.73037 2.48832 -3.82658 -1.12318 6.977 17.288)" gradientUnits="userSpaceOnUse"><stop offset=".63" class="e8-v49b1g"/><stop offset="1" class="y6ze32mia"/></radialGradient><radialGradient id="i40zLFb" cx="0" cy="0" r="1" gradientTransform="rotate(116.602 -3.017 10.55)scale(1.58621 2.70684)" gradientUnits="userSpaceOnUse"><stop class="wef8zac8b"/><stop offset="1" class="hoarz6bum"/></radialGradient><radialGradient id="il9qrHe" cx="0" cy="0" r="1" gradientTransform="matrix(-.65347 2.77477 -3.52334 -.82977 5.545 17.677)" gradientUnits="userSpaceOnUse"><stop offset=".63" class="e8-v49b1g"/><stop offset="1" class="y6ze32mia"/></radialGradient><radialGradient id="imjV17b" cx="0" cy="0" r="1" gradientTransform="matrix(-.68468 1.22288 -2.2217 -1.2439 4.939 18.947)" gradientUnits="userSpaceOnUse"><stop class="wef8zac8b"/><stop offset="1" class="hoarz6bum"/></radialGradient><radialGradient id="iD8Aurb" cx="0" cy="0" r="1" gradientTransform="rotate(104.751 -4.503 11.427)scale(2.474 3.46652)" gradientUnits="userSpaceOnUse"><stop offset=".63" class="e8-v49b1g"/><stop offset="1" class="y6ze32mia"/></radialGradient><radialGradient id="i2Iv6ab" cx="0" cy="0" r="1" gradientTransform="rotate(122.692 -2.834 11.406)scale(1.24393 2.40994)" gradientUnits="userSpaceOnUse"><stop class="wef8zac8b"/><stop offset="1" class="hoarz6bum"/></radialGradient><radialGradient id="ihNB5dd" cx="0" cy="0" r="1" gradientTransform="matrix(-.61813 2.04813 -3.22394 -.973 5.687 19.733)" gradientUnits="userSpaceOnUse"><stop offset=".63" class="e8-v49b1g"/><stop offset="1" class="y6ze32mia"/></radialGradient><radialGradient id="ilhtGxd" cx="0" cy="0" r="1" gradientTransform="rotate(-162.011 6.48 10.137)scale(3.69324 5.10277)" gradientUnits="userSpaceOnUse"><stop class="dwn54oxgo"/><stop offset="1" class="v0i04x6vh"/></radialGradient><radialGradient id="itEg77z" cx="0" cy="0" r="1" gradientTransform="matrix(.07812 -.82813 3.88844 .36683 6.156 21.78)" gradientUnits="userSpaceOnUse"><stop class="hq864_b1v"/><stop offset="1" class="e-tdchb2h"/></radialGradient><radialGradient id="i8FqvGc" cx="0" cy="0" r="1" gradientTransform="matrix(1.65625 2.09375 -2.38774 1.88881 16.031 20.389)" gradientUnits="userSpaceOnUse"><stop offset=".229" class="padl1sbsh"/><stop offset="1" class="w4y1jwbmd"/></radialGradient><radialGradient id="iBEqkLe" cx="0" cy="0" r="1" gradientTransform="matrix(-.8164 -.53126 1.47794 -2.27122 18.786 21.576)" gradientUnits="userSpaceOnUse"><stop class="wpyfqw4vs"/><stop offset="1" class="tja28sbvb"/></radialGradient><radialGradient id="iKwJqgb" cx="0" cy="0" r="1" gradientTransform="rotate(178.447 13.441 10.55)scale(2.70045 29.1455)" gradientUnits="userSpaceOnUse"><stop class="zmosas2ke"/><stop offset="1" class="cpfhw8b0c"/></radialGradient><radialGradient id="i1Vefld" cx="0" cy="0" r="1" gradientTransform="matrix(-.91033 3.89066 -4.6218 -1.0814 22.563 15.354)" gradientUnits="userSpaceOnUse"><stop offset=".043" class="xitcw8bap"/><stop offset="1" class="by5wrxbms"/></radialGradient><radialGradient id="iyY4azJ" cx="0" cy="0" r="1" gradientTransform="matrix(.3061 .4198 -.35662 .26004 21.784 15.633)" gradientUnits="userSpaceOnUse"><stop class="ke8n9wjsm"/><stop offset="1" class="iav904f4q"/></radialGradient><radialGradient id="iFhrhPb" cx="0" cy="0" r="1" gradientTransform="matrix(1.39112 4.09434 -1.86106 .63233 10.983 15.476)" gradientUnits="userSpaceOnUse"><stop class="b9qaylb2c"/><stop offset="1" class="gz8haxb3i"/></radialGradient><radialGradient id="iMinkib" cx="0" cy="0" r="1" gradientTransform="matrix(.33234 1.04073 -.91294 .29153 11.675 15.466)" gradientUnits="userSpaceOnUse"><stop offset=".263" class="n8euy9vjg"/><stop offset=".977" class="z8auuww1t"/></radialGradient><radialGradient id="iSR03fd" cx="0" cy="0" r="1" gradientTransform="matrix(-5.45555 0 0 -9.65081 19.703 14.371)" gradientUnits="userSpaceOnUse"><stop class="wbf-2ib5u"/><stop offset="1" class="r2t9jab3e"/></radialGradient><radialGradient id="i0fgNLe" cx="0" cy="0" r="1" gradientTransform="matrix(-.4201 6.36769 -2.34103 -.15444 22.155 14.13)" gradientUnits="userSpaceOnUse"><stop offset=".39" class="swgfs-c3o"/><stop offset="1" class="lppsh4wvc"/></radialGradient><radialGradient id="ibln6Sc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.47544 1.77635 0 14.59 13.14)" gradientUnits="userSpaceOnUse"><stop offset=".276" class="u7o3559vd"/><stop offset="1" class="kbjuoc3rc"/></radialGradient><radialGradient id="iDqMLQc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.60211 2.07798 0 19.37 12.71)" gradientUnits="userSpaceOnUse"><stop offset=".178" class="bija72usz"/><stop offset="1" class="wwr7m_5oe"/></radialGradient><radialGradient id="i5Ryunc" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.4221 -9.61736 0 16.83 12.38)" gradientUnits="userSpaceOnUse"><stop offset=".757" class="f8ri2qd6n"/><stop offset="1" class="kgsnu7bwr"/></radialGradient><radialGradient id="igChQVc" cx="0" cy="0" r="1" gradientTransform="rotate(-60.732 22.992 -4.409)scale(.74102 2.15641)" gradientUnits="userSpaceOnUse"><stop class="ninpi-65y"/><stop offset="1" class="bjbw-ir7e"/></radialGradient><radialGradient id="iPcyP6b" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.75213 3.026 0 16.773 18.065)" gradientUnits="userSpaceOnUse"><stop class="g3hjbil2k"/><stop offset="1" class="iazz9lb4s"/></radialGradient><radialGradient id="i8LoVXd" cx="0" cy="0" r="1" gradientTransform="scale(10.5742 5.96806)rotate(-90 1.6 .53)" gradientUnits="userSpaceOnUse"><stop offset=".315" class="ven54yrxx"/><stop offset="1" class="wrlksbcrj"/></radialGradient><radialGradient id="ivRpDLc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.79087 6.71668 0 21.846 12.72)" gradientUnits="userSpaceOnUse"><stop class="hlw3e_blf"/><stop offset="1" class="wxscdbbqi"/></radialGradient><radialGradient id="iNvOWdb" cx="0" cy="0" r="1" gradientTransform="matrix(-4.28537 -1.50357 .80075 -2.28225 21.059 6.17)" gradientUnits="userSpaceOnUse"><stop offset=".347" class="c6y_tcclg"/><stop offset="1" class="bn4a00sgu"/></radialGradient><radialGradient id="iYpAaRb" cx="0" cy="0" r="1" gradientTransform="rotate(58.465 3.886 16.397)scale(1.80593 4.18169)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="iadv6taec"/><stop offset="1" class="m3om6jjzt"/></radialGradient><radialGradient id="iFVlAJd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .84666 -1.3467 0 19.05 13.415)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="i9qdvye" cx="0" cy="0" r="1" gradientTransform="matrix(-.24202 -.31187 .42938 -.3332 18.812 13.503)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iBVa7oc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8467 -1.34677 0 14.496 13.415)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iA3K1fe" cx="0" cy="0" r="1" gradientTransform="matrix(-.00807 -.5156 .61978 -.0097 14.197 13.644)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iibb9Sd" cx="0" cy="0" r="1" gradientTransform="matrix(.6559 2.34099 -2.23348 .62578 21.591 13.43)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="vr5749b_g"/><stop offset="1" class="r9kx25b9b"/></radialGradient><radialGradient id="ioLYiHB" cx="0" cy="0" r="1" gradientTransform="matrix(.8221 -1.12819 .94565 .68908 21.968 13.998)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="a8tdckb6o"/><stop offset="1" class="mfa5gim3o"/></radialGradient><radialGradient id="i40HCse" cx="0" cy="0" r="1" gradientTransform="matrix(-.43085 2.16644 -2.12981 -.42357 11.28 13.604)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="bqhcerb-b"/><stop offset="1" class="g54wl109l"/></radialGradient><radialGradient id="iMwhdrV" cx="0" cy="0" r="1" gradientTransform="matrix(-5.5 4.12501 -3.615 -4.82 20.719 4.576)" gradientUnits="userSpaceOnUse"><stop offset=".179" class="tg07-ljnl"/><stop offset="1" class="c6833cb9x"/></radialGradient><radialGradient id="i3dSYhb" cx="0" cy="0" r="1" gradientTransform="matrix(2.875 .375 -.58342 4.4729 10.781 7.701)" gradientUnits="userSpaceOnUse"><stop class="j8k1fac_p"/><stop offset="1" class="g8uem1b5g"/></radialGradient><radialGradient id="inl9J2c" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.875 8.03906 0 16.773 8.326)" gradientUnits="userSpaceOnUse"><stop offset=".761" class="km6q7kb1a"/><stop offset="1" class="i8skpb2jz"/></radialGradient><radialGradient id="iCE2gke" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.47656 -8.28125 0 18.406 7.912)" gradientUnits="userSpaceOnUse"><stop class="kzuil_5zu"/><stop offset="1" class="ok2r3obil"/></radialGradient><radialGradient id="ixSAAAe" cx="0" cy="0" r="1" gradientTransform="matrix(-7.1875 0 0 -.63281 21.269 9.87)" gradientUnits="userSpaceOnUse"><stop class="w63qn2bkh"/><stop offset="1" class="vvfum-_fa"/></radialGradient><radialGradient id="iy7tjOa" cx="0" cy="0" r="1" gradientTransform="matrix(3.48438 0 0 2.01172 9.003 10.109)" gradientUnits="userSpaceOnUse"><stop class="gfrsedb9v"/><stop offset="1" class="vke6kh8bt"/></radialGradient><filter id="iHhsQec" width="21.247" height="10.303" x="6.25" y="19.623" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.776471 0 0 0 0 0.745098 0 0 0 0 0.741176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23843"/></filter><filter id="iXUX2Mu" width="2.078" height="2.078" x="15.622" y="27.457" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.792157 0 0 0 0 0.717647 0 0 0 0 0.788235 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_3987_23843"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_3987_23843" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.831373 0 0 0 0 0.745098 0 0 0 0 0.803922 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_3987_23843"/></filter><filter id="i6D4Q7b" width="2.078" height="2.078" x="15.622" y="25.444" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.792157 0 0 0 0 0.717647 0 0 0 0 0.788235 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_3987_23843"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_3987_23843" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.831373 0 0 0 0 0.745098 0 0 0 0 0.803922 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_3987_23843"/></filter><filter id="iR7lOpc" width="6.554" height="3.702" x="13.676" y="19.523" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.741176 0 0 0 0 0.666667 0 0 0 0 0.701961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23843"/></filter><filter id="ieGS5Vc" width="8.324" height="4.864" x="12.611" y="21.931" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23843" stdDeviation=".5"/></filter><filter id="iecPnWb" width="2.672" height="2.865" x="13.611" y="22.403" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.780392 0 0 0 0 0.270588 0 0 0 0 0.396078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23843"/></filter><filter id="iSo54bd" width="2.672" height="2.865" x="17.264" y="22.403" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.780392 0 0 0 0 0.270588 0 0 0 0 0.396078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23843"/></filter><filter id="iqQr4qV" width="1.554" height="1.999" x="15.986" y="22.812" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.827451 0 0 0 0 0.137255 0 0 0 0 0.317647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23843"/></filter><filter id="iss6Pvd" width="4.764" height="4.766" x="24.75" y="19.349" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.1"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.909804 0 0 0 0 0.658824 0 0 0 0 0.14902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23843"/></filter><filter id="iVeku9U" width="2.277" height="3.844" x="25.907" y="17.448" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".6"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.996078 0 0 0 0 0.713726 0 0 0 0 0.0862745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23843"/></filter><filter id="iue1kme" width="2.436" height="4.046" x="24.436" y="17.107" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.92549 0 0 0 0 0.643137 0 0 0 0 0.101961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23843"/></filter><filter id="i9Lm63q" width="2.312" height="4.044" x="23.386" y="17.96" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.917647 0 0 0 0 0.631373 0 0 0 0 0.129412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23843"/></filter><filter id="i9yuSEb" width="2.123" height="3.114" x="22.394" y="19.041" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.870588 0 0 0 0 0.619608 0 0 0 0 0.219608 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23843"/></filter><filter id="i9V7hSb" width="3.002" height="3.147" x="6.649" y="16.347" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.811765 0 0 0 0 0.588235 0 0 0 0 0.294118 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23843"/></filter><filter id="icGKBic" width="4.665" height="1.737" x="23.02" y="19.912" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23843" stdDeviation=".125"/></filter><filter id="iHO4xMb" width="11.165" height="13.079" x="11.489" y="7.932" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.823529 0 0 0 0 0.623529 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23843"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.980392 0 0 0 0 0.54902 0 0 0 0 0.0941176 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23843" result="effect2_innerShadow_3987_23843"/></filter><filter id="izD1wze" width="3.959" height="5.026" x="14.577" y="12.511" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23843" stdDeviation=".5"/></filter><filter id="ionUJae" width="2.159" height="3.226" x="15.694" y="13.207" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23843" stdDeviation=".05"/></filter><filter id="iCWn9Zd" width="3.859" height="1.62" x="14.844" y="16.783" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23843" stdDeviation=".05"/></filter><filter id="iRGe5xd" width="12.866" height="8.699" x="10.332" y="4.639" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.945098 0 0 0 0 0.509804 0 0 0 0 0.0627451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23843"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.862745 0 0 0 0 0.486275 0 0 0 0 0.0470588 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23843" result="effect2_innerShadow_3987_23843"/></filter><filter id="ivxCIDw" width="2.436" height="1.234" x="18.397" y="11.068" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.603922 0 0 0 0 0.243137 0 0 0 0 0.152941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23843"/></filter><filter id="iO05ZFb" width="2.436" height="1.218" x="12.912" y="11.083" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.603922 0 0 0 0 0.243137 0 0 0 0 0.152941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23843"/></filter><filter id="iF2R3bb" width=".812" height=".718" x="18.288" y="12.96" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23843" stdDeviation=".05"/></filter><filter id="iaSfA7b" width=".913" height=".936" x="19.169" y="13.043" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23843" stdDeviation=".1"/></filter><filter id="ictHIse" width="1.012" height="1.068" x="14.533" y="12.977" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23843" stdDeviation=".1"/></filter><filter id="ikkd0kd" width=".944" height=".726" x="13.741" y="12.952" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23843" stdDeviation=".05"/></filter><filter id="irKkSub" width="1.365" height="2.461" x="10.489" y="12.871" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23843" stdDeviation=".125"/></filter><filter id="iskkgUb" width="1.488" height="2.486" x="21.701" y="12.855" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23843" stdDeviation=".125"/></filter><filter id="itDs7he" width="2.277" height=".978" x="12.943" y="11.269" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23843" stdDeviation=".075"/></filter><filter id="icWPJ1c" width="2.347" height="1.025" x="18.452" y="11.217" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23843" stdDeviation=".075"/></filter><linearGradient id="iK84mBb" x1="22.562" x2="21.812" y1="29.826" y2="29.826" gradientUnits="userSpaceOnUse"><stop class="fr__qmhjc"/><stop offset="1" class="gypp10kih"/></linearGradient><linearGradient id="iWCiqKd" x1="20.644" x2="21.062" y1="29.014" y2="29.014" gradientUnits="userSpaceOnUse"><stop class="hj-s-zboe"/><stop offset="1" class="s0umluqbl"/></linearGradient><linearGradient id="ipodSkc" x1="9.531" x2="4.906" y1="27.451" y2="27.451" gradientUnits="userSpaceOnUse"><stop class="sb-ednb_a"/><stop offset="1" class="v0501vbqa"/></linearGradient><linearGradient id="iXPTZOc" x1="9.75" x2="8.828" y1="27.076" y2="27.076" gradientUnits="userSpaceOnUse"><stop class="o_30au2yc"/><stop offset="1" class="c60cvac3k"/></linearGradient><linearGradient id="itP1zjc" x1="27.871" x2="22.844" y1="28.142" y2="28.142" gradientUnits="userSpaceOnUse"><stop class="i7zyuv8vr"/><stop offset=".907" class="qzhltkbuo"/></linearGradient><linearGradient id="i33ZCUz" x1="28.09" x2="27.168" y1="27.876" y2="27.876" gradientUnits="userSpaceOnUse"><stop class="tub8lbbfx"/><stop offset="1" class="bd09vtb_c"/></linearGradient><linearGradient id="i8tJXGc" x1="16.763" x2="16.763" y1="22.812" y2="24.81" gradientUnits="userSpaceOnUse"><stop offset=".351" class="gzsz7evmk"/><stop offset="1" class="smgiue0gi"/></linearGradient><linearGradient id="iosHfeb" x1="16.822" x2="16.822" y1="10.576" y2="12.451" gradientUnits="userSpaceOnUse"><stop offset=".16" class="xebfowbpy"/><stop offset="1" class="lzx7yzb_s"/></linearGradient><linearGradient id="iIKRyTb" x1="16.773" x2="17.665" y1="15.236" y2="15.236" gradientUnits="userSpaceOnUse"><stop class="kc3wm8i6w"/><stop offset="1" class="st3dxnbfu"/></linearGradient><linearGradient id="i2tY9De" x1="15.654" x2="16.775" y1="15.074" y2="15.136" gradientUnits="userSpaceOnUse"><stop class="abomb1boi"/><stop offset="1" class="pvsu__x5y"/><stop offset="1" class="ig7uz4g5n"/></linearGradient><linearGradient id="i2nQh7d" x1="16.773" x2="16.773" y1="15.652" y2="16.541" gradientUnits="userSpaceOnUse"><stop class="pvsu__x5y"/><stop offset=".845" class="ag8lyyc-n"/></linearGradient><linearGradient id="iUVwrIc" x1="16.773" x2="16.773" y1="13.307" y2="13.744" gradientUnits="userSpaceOnUse"><stop class="zav_leb7s"/><stop offset="1" class="l5m23db_l"/></linearGradient><linearGradient id="ixdP1uA" x1="22.37" x2="11.806" y1="8.462" y2="8.462" gradientUnits="userSpaceOnUse"><stop class="r37rgng3f"/><stop offset="1" class="gcsbsh2mh"/></linearGradient><linearGradient id="iq0dcad" x1="19.862" x2="19.535" y1="13.471" y2="13.673" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iAZOZld" x1="15.272" x2="14.945" y1="13.471" y2="13.673" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="it6KCqb" x1="23.49" x2="22.231" y1="13.499" y2="15.77" gradientUnits="userSpaceOnUse"><stop class="dxsnshbck"/><stop offset="1" class="eihs-teph"/></linearGradient><linearGradient id="ivQSrCe" x1="10.669" x2="12.191" y1="14.234" y2="14.101" gradientUnits="userSpaceOnUse"><stop class="a9f7swmqb"/><stop offset="1" class="jr2wmk3hc"/></linearGradient><linearGradient id="iEtS1ge" x1="12.765" x2="16.558" y1="11.972" y2="11.41" gradientUnits="userSpaceOnUse"><stop class="fci8p2biu"/><stop offset="1" class="nsrylabov"/></linearGradient><linearGradient id="il15Eqd" x1="20.454" x2="18.727" y1="11.924" y2="11.404" gradientUnits="userSpaceOnUse"><stop class="fci8p2biu"/><stop offset="1" class="nsrylabov"/></linearGradient><linearGradient id="izP9Z9c" x1="16.773" x2="16.773" y1="7.912" y2="8.1" gradientUnits="userSpaceOnUse"><stop class="jhlen960d"/><stop offset="1" class="wjchuwb6a"/></linearGradient><linearGradient id="iYE2hsb" x1="17.956" x2="17.956" y1="10.98" y2="10.214" gradientUnits="userSpaceOnUse"><stop class="bl3fq0x9z"/><stop offset="1" class="lxo7c2i6k"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-juggling" /></template>
<style>
.a5zzorbzd {
  stop-color: var(--svg-color--e1ac3a, #E1AC3A);
}

.a7xqagbcb {
  d: path("M11.7 15.676a1.7 1.7 0 0 1-.944-.322v.971c0 .932.556 1.762 1.4 2.107q-.268-.568-.361-1.231z");
}

.a8tdckb6o {
  stop-color: var(--svg-color--ffbd22, #FFBD22);
}

.a9f7swmqb {
  stop-color: var(--svg-color--e39726, #E39726);
}

.ab6i82btp {
  stop-color: var(--svg-color--e7377c, #E7377C);
}

.abomb1boi {
  stop-color: var(--svg-color--f49f22, #F49F22);
}

.af8mzdbwl {
  stop-color: var(--svg-color--5f679a, #5F679A);
}

.ag8lyyc-n {
  stop-color: var(--svg-color--e88830, #E88830);
}

.aqzyd8bsb {
  stop-color: var(--svg-color--896bb4, #896BB4);
  stop-opacity: 0;
}

.auvn9fbbk {
  stop-color: var(--svg-color--e9387a, #E9387A);
}

.b9qaylb2c {
  stop-color: var(--svg-color--d57a26, #D57A26);
}

.bd09vtb_c {
  stop-color: var(--svg-color--e0dde3, #E0DDE3);
  stop-opacity: 0;
}

.bija72usz {
  stop-color: var(--svg-color--ffbe3a, #FFBE3A);
}

.bjbw-ir7e {
  stop-color: var(--svg-color--ffb534, #FFB534);
  stop-opacity: 0;
}

.bl3fq0x9z {
  stop-color: var(--svg-color--543459, #543459);
}

.bn4a00sgu {
  stop-color: var(--svg-color--ffe639, #FFE639);
  stop-opacity: 0;
}

.bq5dgsbba {
  stop-color: var(--svg-color--dcc8ec, #DCC8EC);
}

.bqhcerb-b {
  stop-color: var(--svg-color--c77937, #C77937);
  stop-opacity: 0;
}

.bsid3ncbw {
  fill: var(--svg-color--ffd942, #FFD942);
  d: path("m27.85 19.83l-.447.824l-1.172 1.422l-1.481 1.992l3.099.047c.099-.172.218-.566.38-1.327c.164-.66.326-1.114.471-1.376l.443-.924a.726.726 0 0 0-1.292-.659");
}

.btor07b8q {
  stop-color: var(--svg-color--d61f4d, #D61F4D);
}

.by5wrxbms {
  stop-color: var(--svg-color--e26839, #E26839);
}

.c60cvac3k {
  stop-color: var(--svg-color--e5ddee, #E5DDEE);
  stop-opacity: 0;
}

.c6833cb9x {
  stop-color: var(--svg-color--372f3c, #372F3C);
}

.c6y_tcclg {
  stop-color: var(--svg-color--ffe639, #FFE639);
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

.cyi-b68yu {
  d: path("m13.676 20.005l.613 3.22h4.945l.797-3.173a10.2 10.2 0 0 0-2.937-.429h-.641c-.962 0-1.894.133-2.777.382");
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

.don2wdpjw {
  cx: 16.761px;
  cy: 26.282px;
  r: 0.739px;
}

.donv6bcww {
  fill: var(--svg-color--000, #000);
  d: path("M15.027 13.848a.53.53 0 0 0-.533-.533a.53.53 0 0 0-.474.779h.944a.5.5 0 0 0 .063-.246");
}

.dpkv3e8bt {
  stop-color: var(--svg-color--efd8d5, #EFD8D5);
}

.dpmuo-biy {
  stop-color: var(--svg-color--6f5ea2, #6F5EA2);
}

.duyhuibwk {
  cx: 9.246px;
  cy: 3.857px;
  r: 1.684px;
}

.dwn54oxgo {
  stop-color: var(--svg-color--ffe23d, #FFE23D);
}

.dxsnshbck {
  stop-color: var(--svg-color--ffe343, #FFE343);
}

.e-tdchb2h {
  stop-color: var(--svg-color--f7b528, #F7B528);
  stop-opacity: 0;
}

.e8-v49b1g {
  stop-color: var(--svg-color--efa929, #EFA929);
  stop-opacity: 0;
}

.eihs-teph {
  stop-color: var(--svg-color--ffc136, #FFC136);
}

.f21vmbcik {
  d: path("M5.437 21.764h4.094v8.063H5.437z");
}

.f8ri2qd6n {
  stop-color: var(--svg-color--fc9f3f, #FC9F3F);
  stop-opacity: 0;
}

.fci8p2biu {
  stop-color: var(--svg-color--b66255, #B66255);
}

.fde_fwzpt {
  stop-color: var(--svg-color--5c9946, #5C9946);
}

.fgpnfrb_u {
  fill: var(--svg-color--bc9ebb, #BC9EBB);
  fill-rule: evenodd;
  d: path("M16.022 23.723c-.213-.246-.57-.534-1.156-.733c-.36-.122-.777-.067-.97.268c-.14.243-.285.604-.285 1.105s.144.862.285 1.105c.193.335.61.39.97.267c.604-.204.965-.474 1.175-.706c.048.135.159.24.305.268c.29.055.544.055.834 0a.41.41 0 0 0 .31-.285c.208.236.572.514 1.19.723c.362.123.778.068.971-.267c.14-.243.284-.598.284-1.105s-.144-.862-.284-1.105c-.193-.335-.61-.39-.97-.268c-.603.205-.964.503-1.174.754a.41.41 0 0 0-.327-.363a2.1 2.1 0 0 0-.834 0a.41.41 0 0 0-.324.342");
}

.fjgbgxbbd {
  fill: var(--svg-color--ee9020, #EE9020);
  d: path("m16.266 13.83l-.663 1.918c-.113.394.159.79.543.79h.821c.385 0 .657-.402.543-.79l-.554-1.918c-.12-.425-.566-.425-.69 0");
}

.fpq5frbny {
  d: path("M14.762 18.363c0-.991.9-1.795 2.011-1.795s2.012.804 2.012 1.794v2.326c0 .991-.9 1.794-2.012 1.794c-1.11 0-2.011-.803-2.011-1.794z");
}

.fr__qmhjc {
  stop-color: var(--svg-color--7a6cad, #7A6CAD);
}

.ft5dv1b6b {
  fill: none;
}

.fzq016boz {
  stop-color: var(--svg-color--e35838, #E35838);
}

.g3hjbil2k {
  stop-color: var(--svg-color--89014e, #89014E);
}

.g54wl109l {
  stop-color: var(--svg-color--c77937, #C77937);
}

.g8uem1b5g {
  stop-color: var(--svg-color--38303e, #38303E);
  stop-opacity: 0;
}

.gcsbsh2mh {
  stop-color: var(--svg-color--d29935, #D29935);
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

.gvcddab8z {
  d: path("M22.99 22.213c.118.463.585 1.456.804 1.894h4.047l-.258-3.789l-4.836.924c.031.13.123.507.242.97");
}

.gypp10kih {
  stop-color: var(--svg-color--7a6cad, #7A6CAD);
  stop-opacity: 0;
}

.gz8haxb3i {
  stop-color: var(--svg-color--d06a3c, #D06A3C);
}

.gzcpsebza {
  stop-color: var(--svg-color--ded4e0, #DED4E0);
  stop-opacity: 0;
}

.gzsz7evmk {
  stop-color: var(--svg-color--eb3782, #EB3782);
}

.h1373oqiz {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M13.218 11.972c.268-.192.937-.53 1.727-.398");
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

.hlw3e_blf {
  stop-color: var(--svg-color--ffb52a, #FFB52A);
}

.hoarz6bum {
  stop-color: var(--svg-color--fab32c, #FAB32C);
}

.hpfqe6rjh {
  cx: 6.332px;
  cy: 12.838px;
  r: 1.684px;
}

.hq864_b1v {
  stop-color: var(--svg-color--d2991f, #D2991F);
}

.ht6lpfbpp {
  d: path("M18.68 22.463c-.909.308-1.267.83-1.388 1.082l-.028.29l.028.359c.12.25.48.706 1.388 1.014c.362.123.778.068.971-.267c.14-.243.284-.599.284-1.105c0-.507-.144-.862-.284-1.106c-.193-.335-.61-.39-.97-.267");
}

.hwyai6h-t {
  fill: var(--svg-color--ffd343, #FFD343);
  d: path("M24.458 17.959a.68.68 0 0 1 .568-.843l.023-.003a.68.68 0 0 1 .756.54l.555 2.764a.615.615 0 0 1-1.198.275z");
}

.i4_9z4_vp {
  d: path("M11.738 17.257a4.09 4.09 0 0 0 4.055 3.554h1.969a4.09 4.09 0 0 0 4.055-3.554c.123-1.966.247-3.924.338-5.889a1.51 1.51 0 0 0-1.44-1.494h-1.46a2.53 2.53 0 0 1-2.308-1.506a.69.69 0 0 0-.642-.436h-1.329c-1.926 0-3.487 1.578-3.487 3.526c0 1.942.122 3.852.249 5.799");
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

.iadv6taec {
  stop-color: var(--svg-color--f3c130, #F3C130);
}

.iav904f4q {
  stop-color: var(--svg-color--e18c2a, #E18C2A);
  stop-opacity: 0;
}

.iazz9lb4s {
  stop-color: var(--svg-color--87004d, #87004D);
}

.ibuznhb7a {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M15.362 16.985a.234.234 0 0 0-.28.048a.22.22 0 0 0-.023.278c.363.55.995.916 1.714.916a2.05 2.05 0 0 0 1.715-.916a.22.22 0 0 0-.024-.28a.235.235 0 0 0-.28-.047a3.05 3.05 0 0 1-1.411.335a3.06 3.06 0 0 1-1.411-.334Z");
}

.ig7uz4g5n {
  stop-color: var(--svg-color--f49f22, #F49F22);
  stop-opacity: 0;
}

.irk66op0u {
  d: path("M16.773 17.394c-.53 0-1.027-.125-1.446-.343c-.143-.072-.296.089-.206.218c.35.53.958.883 1.652.883s1.303-.353 1.652-.883c.09-.135-.063-.29-.206-.218a3.1 3.1 0 0 1-1.446.343");
}

.iwbygtbvw {
  cx: 25.211px;
  cy: 4.873px;
  r: 1.684px;
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

.jhlen960d {
  stop-color: var(--svg-color--745ba5, #745BA5);
}

.jjf293xlz {
  stop-color: var(--svg-color--d61f4d, #D61F4D);
  stop-opacity: 0;
}

.jr2wmk3hc {
  stop-color: var(--svg-color--d9851d, #D9851D);
}

.kbjuoc3rc {
  stop-color: var(--svg-color--f59632, #F59632);
  stop-opacity: 0;
}

.kc3wm8i6w {
  stop-color: var(--svg-color--ffc92f, #FFC92F);
}

.kdv9gpb4z {
  stop-color: var(--svg-color--dabdc3, #DABDC3);
}

.ke8n9wjsm {
  stop-color: var(--svg-color--e18c2a, #E18C2A);
}

.kgsnu7bwr {
  stop-color: var(--svg-color--de7942, #DE7942);
}

.km6q7kb1a {
  stop-color: var(--svg-color--5d5565, #5D5565);
  stop-opacity: 0;
}

.koq0r9bvu {
  stop-color: var(--svg-color--9e78c9, #9E78C9);
}

.kzuil_5zu {
  stop-color: var(--svg-color--9072ca, #9072CA);
}

.l-r9gxb9g {
  stop-color: var(--svg-color--4bb8fb, #4BB8FB);
}

.l3d0520td {
  fill: var(--svg-color--922817, #922817);
  d: path("M13.179 11.68a2.9 2.9 0 0 1 1.815-.375a.29.29 0 0 1-.07.575a2.3 2.3 0 0 0-1.448.297l-.096.062l-.002.002a.29.29 0 0 1-.355-.457z");
}

.l3ydtt4ya {
  stop-color: var(--svg-color--ffda02, #FFDA02);
}

.l5m23db_l {
  stop-color: var(--svg-color--fac137, #FAC137);
  stop-opacity: 0;
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

.lgi0lwbjz {
  stop-color: var(--svg-color--775184, #775184);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lppsh4wvc {
  stop-color: var(--svg-color--ffd930, #FFD930);
  stop-opacity: 0;
}

.lxo7c2i6k {
  stop-color: var(--svg-color--462f5a, #462F5A);
  stop-opacity: 0;
}

.lzx7yzb_s {
  stop-color: var(--svg-color--f8ad31, #F8AD31);
  stop-opacity: 0;
}

.m-1-e5bla {
  stop-color: var(--svg-color--fbf2f7, #FBF2F7);
}

.m0-m1fdur {
  d: path("M15.345 13.739c0-.301-.245-.502-.311-.562l-.301.29l.185.378z");
}

.m3om6jjzt {
  stop-color: var(--svg-color--f3c130, #F3C130);
  stop-opacity: 0;
}

.m3r-0t5fu {
  d: path("M21.91 15.77q.104-1.665.192-3.33a1.68 1.68 0 0 1-.192 3.33");
}

.m5avsc_ef {
  stop-color: var(--svg-color--784b89, #784B89);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mfa5gim3o {
  stop-color: var(--svg-color--ffbd22, #FFBD22);
  stop-opacity: 0;
}

.miwt9fbcd {
  d: path("m16.374 13.625l-.554 1.919c-.114.394.158.789.543.789h.82c.386 0 .657-.4.544-.79l-.555-1.918c-.119-.425-.673-.425-.798 0");
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

.n_uwwia7r {
  cx: 14.213px;
  cy: 13.315px;
  rx: 0.407px;
  ry: 0.206px;
}

.n8euy9vjg {
  stop-color: var(--svg-color--be691e, #BE691E);
}

.ng1cexbhj {
  stop-color: var(--svg-color--b6424c, #B6424C);
}

.ninpi-65y {
  stop-color: var(--svg-color--ffb534, #FFB534);
}

.nmqo35b7x {
  stop-color: var(--svg-color--ded4e0, #DED4E0);
}

.npskz24gn {
  d: path("M18.984 13.114c.066.089-.073.197-.23.315s-.275.2-.341.112c-.067-.089.007-.256.165-.374s.34-.142.406-.053");
}

.nsrylabov {
  stop-color: var(--svg-color--b66255, #B66255);
  stop-opacity: 0;
}

.nugpx2cgg {
  d: path("M11.5 12.432a1.68 1.68 0 0 0 .144 3.339a81 81 0 0 1-.145-3.34");
}

.o_30au2yc {
  stop-color: var(--svg-color--decfd8, #DECFD8);
}

.o415o878f {
  stop-color: var(--svg-color--ef4c8b, #EF4C8B);
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

.padl1sbsh {
  stop-color: var(--svg-color--e68016, #E68016);
}

.pb6efmson {
  stop-color: var(--svg-color--d72c5e, #D72C5E);
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

.pvsu__x5y {
  stop-color: var(--svg-color--e88830, #E88830);
  stop-opacity: 0;
}

.pyl-ckr1z {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M20.523 11.967c-.277-.29-1.006-.574-1.796-.441");
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

.r2t9jab3e {
  stop-color: var(--svg-color--f5a129, #F5A129);
}

.r37rgng3f {
  stop-color: var(--svg-color--ffe235, #FFE235);
}

.r9kx25b9b {
  stop-color: var(--svg-color--e08f2e, #E08F2E);
}

.rupv3qobh {
  fill: var(--svg-color--fff, #fff);
  d: path("M19.268 12.634c.682 0 1.258.47 1.414 1.105a.286.286 0 0 1-.28.355h-2.328a.24.24 0 0 1-.237-.283a1.46 1.46 0 0 1 1.431-1.177");
}

.s0umluqbl {
  stop-color: var(--svg-color--7160a4, #7160A4);
  stop-opacity: 0;
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

.slg6r6crg {
  fill: var(--svg-color--dd8224, #DD8224);
  d: path("M11.517 13.121a.997.997 0 0 0 .087 1.961a81 81 0 0 1-.087-1.96");
}

.smgiue0gi {
  stop-color: var(--svg-color--c93857, #C93857);
}

.sqf03_p-t {
  stop-color: var(--svg-color--f8e6e8, #F8E6E8);
}

.st3dxnbfu {
  stop-color: var(--svg-color--ffea47, #FFEA47);
}

.swgfs-c3o {
  stop-color: var(--svg-color--ffd930, #FFD930);
}

.swka_j87x {
  d: path("M6.25 29.826c0-5.635 4.568-10.203 10.203-10.203h.64c5.636 0 10.204 4.568 10.204 10.203z");
}

.t-5nldk3g {
  cx: 16.761px;
  cy: 28.296px;
  r: 0.739px;
}

.t0gi-gb8u {
  fill: var(--svg-color--ffc837, #FFC837);
  d: path("M21.951 15.091q.061-.993.116-1.986a.997.997 0 0 1-.116 1.986");
}

.tg07-ljnl {
  stop-color: var(--svg-color--5e5764, #5E5764);
}

.tja28sbvb {
  stop-color: var(--svg-color--fdb836, #FDB836);
  stop-opacity: 0;
}

.tn_97qkdc {
  stop-color: var(--svg-color--f2c341, #F2C341);
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

.tzo02q1al {
  d: path("M19.052 12.917a.93.93 0 0 1 .898 1.177h-1.8a.935.935 0 0 1 .902-1.177");
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

.u7o3559vd {
  stop-color: var(--svg-color--f59632, #F59632);
}

.uhdec2fht {
  d: path("M14.494 12.917a.93.93 0 0 0-.898 1.177h1.8a1 1 0 0 0 .033-.246a.94.94 0 0 0-.935-.931");
}

.ujrq6ixuu {
  stop-color: var(--svg-color--beb4c6, #BEB4C6);
}

.v0501vbqa {
  stop-color: var(--svg-color--c0b5cd, #C0B5CD);
}

.v0i04x6vh {
  stop-color: var(--svg-color--ffbd23, #FFBD23);
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.vdngsab5t {
  fill-rule: evenodd;
  d: path("M3.416 19.34a.75.75 0 0 1 1.051.14c.244.317.833.881 1.8.881a.75.75 0 0 1 .75.75c0 .415-.336.67-.75.67c-1.683 0-2.593-.87-2.99-1.39a.75.75 0 0 1 .139-1.05");
}

.ven54yrxx {
  stop-color: var(--svg-color--c98537, #C98537);
}

.vgk5w_bmg {
  stop-color: var(--svg-color--ffc12e, #FFC12E);
}

.vke6kh8bt {
  stop-color: var(--svg-color--3e3843, #3E3843);
  stop-opacity: 0;
}

.vq-kd0zaf {
  d: path("M21.84 7.44c.536.184-.072 1.427.233 1.964c.487.857 1.504 1.013.978 1.768a1.63 1.63 0 0 0-.282.913v1.24a1.8 1.8 0 0 0-.696-.28l.082-1.677a1.513 1.513 0 0 0-1.44-1.494h-1.46a2.53 2.53 0 0 1-2.308-1.506a.69.69 0 0 0-.642-.436h-1.329c-1.926 0-3.487 1.578-3.487 3.526l.032 1.604a1.8 1.8 0 0 0-.751.275v-1.252c0-.325-.1-.644-.282-.913c-.499-.733.325-.934.762-1.768c.304-.576-.115-1.763.444-1.96a2.8 2.8 0 0 0 1.445-1.158a2.43 2.43 0 0 1 3.016-.951c.399.173.847.173 1.245 0c.294-.124.615-.196.952-.196c.88 0 1.65.475 2.076 1.18a2.63 2.63 0 0 0 1.411 1.12");
}

.vr5749b_g {
  stop-color: var(--svg-color--e1943d, #E1943D);
  stop-opacity: 0;
}

.vvfum-_fa {
  stop-color: var(--svg-color--392f42, #392F42);
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

.wbf-2ib5u {
  stop-color: var(--svg-color--ffe846, #FFE846);
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

.wlq6ufb3a {
  d: path("M19.882 13.726a.9.9 0 0 0-.241-.483l-.271.298l.122.238z");
}

.wozepxbaa {
  d: path("M11.048 7.912a6 6 0 0 0-.048.75v1.648h11.547V8.663q0-.381-.049-.75z");
}

.wp2p6dbcv {
  d: path("M23.777 24.107h4.094v5.719h-4.094z");
}

.wpyfqw4vs {
  stop-color: var(--svg-color--fdb836, #FDB836);
}

.wrlksbcrj {
  stop-color: var(--svg-color--c98537, #C98537);
  stop-opacity: 0;
}

.wrz017bzp {
  fill: var(--svg-color--922817, #922817);
  d: path("M20.634 11.794a1.9 1.9 0 0 0-.718-.43c-.317-.1-.715-.127-1.265-.06a.29.29 0 0 0 .07.575c.503-.061.81-.03 1.022.037c.207.065.347.171.51.314a.29.29 0 0 0 .38-.437");
}

.wshx69b-y {
  stop-color: var(--svg-color--896bb4, #896BB4);
}

.wwr7m_5oe {
  stop-color: var(--svg-color--ffbe3a, #FFBE3A);
  stop-opacity: 0;
}

.wxscdbbqi {
  stop-color: var(--svg-color--ffb52a, #FFB52A);
  stop-opacity: 0;
}

.x1l7xqbyw {
  stop-color: var(--svg-color--de5534, #DE5534);
  stop-opacity: 0;
}

.x92j_kb4w {
  stop-color: var(--svg-color--d4c4da, #D4C4DA);
}

.xe9265amt {
  fill: var(--svg-color--fff, #fff);
  d: path("M14.278 12.633c-.681 0-1.257.47-1.414 1.105a.286.286 0 0 0 .28.356h2.328a.24.24 0 0 0 .237-.284a1.46 1.46 0 0 0-1.43-1.177");
}

.xebfowbpy {
  stop-color: var(--svg-color--e5842b, #E5842B);
}

.xitcw8bap {
  stop-color: var(--svg-color--ffc135, #FFC135);
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

.y6vse6_qo {
  d: path("M21.846 15.676c.35-.012.677-.13.944-.322v.971c0 .932-.555 1.762-1.4 2.107q.268-.568.361-1.231z");
}

.y6ze32mia {
  stop-color: var(--svg-color--c3863f, #C3863F);
}

.ym-b_m9fy {
  stop-color: var(--svg-color--d1bed4, #D1BED4);
  stop-opacity: 0;
}

.z7d6tabwf {
  fill: var(--svg-color--000, #000);
  d: path("M18.519 13.848a.53.53 0 0 1 .533-.533a.53.53 0 0 1 .474.779h-.944a.5.5 0 0 1-.063-.246");
}

.z8auuww1t {
  stop-color: var(--svg-color--be691e, #BE691E);
  stop-opacity: 0;
}

.z93ygib1c {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.984 13.114c.066.089-.073.197-.23.315s-.275.2-.341.112c-.067-.089.007-.256.165-.374s.34-.142.406-.053");
}

.zav_leb7s {
  stop-color: var(--svg-color--fac137, #FAC137);
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

.zvbtjsb5l {
  cx: 14.213px;
  cy: 13.315px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.407px;
  ry: 0.206px;
}

</style>
