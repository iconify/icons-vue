<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iMrCPHc)"><path fill="url(#iCWg3yz)" class="swka_j87x"/><path fill="url(#iTFB9Bb)" class="swka_j87x"/><path fill="url(#iw5sInd)" class="swka_j87x"/><path fill="url(#il5eVUq)" class="swka_j87x"/><path fill="url(#iY3yYtd)" class="swka_j87x"/></g><circle fill="url(#iBZ0RUd)" class="hpfqe6rjh"/><circle fill="url(#itKlKTd)" class="hpfqe6rjh"/><circle fill="url(#ihlr5IT)" class="duyhuibwk"/><circle fill="url(#iGUmgWd)" class="duyhuibwk"/><circle fill="url(#iXhqZHd)" class="iwbygtbvw"/><circle fill="url(#iOHvRJe)" class="iwbygtbvw"/><circle fill="url(#issuNue)" class="zdcorrl9x"/><circle fill="url(#iMaLBhb)" class="zdcorrl9x"/><circle fill="url(#iAhrvZc)" class="zdcorrl9x"/><g filter="url(#ixfZlgc)"><circle fill="url(#iMk8UMb)" class="t-5nldk3g"/></g><g filter="url(#ii0Rzsd)"><circle fill="url(#iR23Gge)" class="don2wdpjw"/></g><path fill="url(#i5YvaPc)" class="j70rp9pis"/><path fill="url(#iK84mBb)" class="j70rp9pis"/><path fill="url(#iWCiqKd)" class="j70rp9pis"/><path fill="url(#ieol8Me)" class="qy4rrcb8b"/><path fill="url(#iDbbcbc)" class="qy4rrcb8b"/><path fill="url(#iOe2zrd)" class="qy4rrcb8b"/><path fill="url(#iV71Rbc)" class="qy4rrcb8b"/><g filter="url(#iOo264d)"><path fill="url(#iJ1cHHU)" class="ta93jn_me"/><path fill="url(#ix2mzrc)" class="ta93jn_me"/></g><path fill="url(#ipodSkc)" class="f21vmbcik"/><path fill="url(#iXPTZOc)" class="f21vmbcik"/><path fill="url(#itP1zjc)" class="wp2p6dbcv"/><path fill="url(#i33ZCUz)" class="wp2p6dbcv"/><g filter="url(#iuAefgb)"><path clip-rule="evenodd" class="fgpnfrb_u"/></g><g filter="url(#inBlbCN)"><path fill="url(#iSAsI1d)" class="ctsppjbax"/><path fill="url(#iwtPTOo)" class="ctsppjbax"/><path fill="url(#isAdhHe)" class="ctsppjbax"/></g><g filter="url(#iVr1UgR)"><path fill="url(#ivLP6Gc)" class="ht6lpfbpp"/><path fill="url(#iXetYud)" class="ht6lpfbpp"/></g><g filter="url(#isp3xlb)"><path fill="url(#i8tJXGc)" class="ld_83jb7a"/><path fill="url(#iw9bnJb)" class="ld_83jb7a"/></g><g filter="url(#iJ4OXKc)"><path class="bsid3ncbw"/></g><g filter="url(#iMvtzQe)"><path class="j4x55bbau"/></g><g filter="url(#i4J64ed)"><path class="hwyai6h-t"/></g><g filter="url(#iuSzUwM)"><path class="ddpez5d9u"/></g><g filter="url(#iOE9K4d)"><path class="cfziuz30v"/></g><path fill="url(#ipMueJd)" class="gvcddab8z"/><path fill="url(#i3JaYLp)" class="gvcddab8z"/><g filter="url(#iRdXnIe)"><path fill="url(#iTna7Kc)" class="u5bjt8cdp"/></g><path fill="url(#ih4s9ac)" clip-rule="evenodd" class="wfgw5ub6b"/><path fill="url(#ikJdwNc)" clip-rule="evenodd" class="wfgw5ub6b"/><path fill="url(#i40zLFb)" clip-rule="evenodd" class="d5_x4xk7i"/><path fill="url(#il9qrHe)" clip-rule="evenodd" class="d5_x4xk7i"/><path fill="url(#imjV17b)" clip-rule="evenodd" class="ctupw6b3d"/><path fill="url(#iD8Aurb)" clip-rule="evenodd" class="ctupw6b3d"/><path fill="url(#i2Iv6ab)" clip-rule="evenodd" class="vdngsab5t"/><path fill="url(#ihNB5dd)" clip-rule="evenodd" class="vdngsab5t"/><path fill="url(#ilhtGxd)" class="twba206ho"/><path fill="url(#itEg77z)" class="twba206ho"/><path fill="url(#ilHp1He)" class="fpq5frbny"/><g filter="url(#iJuswmc)"><ellipse fill="url(#iKwJqgb)" transform="rotate(-11.027 25.353 20.78)" class="w6tinjvyq"/></g><circle fill="url(#iHopaXc)" class="bq-3inb5p"/><g filter="url(#iu5CvOe)"><circle fill="url(#ib7wIKe)" class="qubidabul"/></g><g filter="url(#iW81uhz)"><circle fill="url(#iRVGrLb)" class="iw6qprblb"/><circle fill="url(#iNTFjAx)" class="iw6qprblb"/></g><g filter="url(#ikmJWWd)"><circle class="ewajonw4w"/><circle fill="url(#iSjhqwG)" class="xvg5w_x2s"/><circle fill="url(#id0jZvd)" class="xvg5w_x2s"/></g><path fill="url(#iQNbWGd)" class="sl0q4acir"/><path fill="url(#iK76Qpd)" class="sl0q4acir"/><path fill="url(#iedrnKy)" class="sl0q4acir"/><path fill="url(#iVufHyU)" class="sl0q4acir"/><path fill="url(#iJ2wNtd)" class="sl0q4acir"/><path fill="url(#icL5zKb)" class="sl0q4acir"/><path class="ifie1jl_u"/><path fill="url(#iXpBHzS)" class="u86eruqic"/><path fill="url(#i9f88zc)" class="u86eruqic"/><path fill="url(#icmKGxd)" class="u86eruqic"/><path fill="url(#iCIolwe)" class="u86eruqic"/><path fill="url(#iQxs4Td)" class="u86eruqic"/><path fill="url(#izC3nvd)" class="u86eruqic"/><g filter="url(#icK5J3c)"><path class="crnv2vbtk"/></g><g filter="url(#iiiGsPb)"><path class="ggx6mbb3s"/><path fill="url(#iEhEBmd)" class="ugynyo-0t"/><path fill="url(#iH1qLAc)" class="ugynyo-0t"/><path fill="url(#it1tIvd)" class="ugynyo-0t"/></g><g filter="url(#is79gac)"><path stroke="url(#igio5bc)" class="z9_ub4btj"/></g><path class="sp8j17bpa"/><path class="ukqqiac9d"/><path fill="url(#ikaYcCe)" class="c90ph3ygb"/><path class="stb_0w47k"/><g filter="url(#i4pJyre)"><path class="u2_b7w1wq"/><path fill="url(#ibAYMvd)" class="ei9-ouyfz"/></g><g filter="url(#iB0PSQc)"><path fill="url(#imA5vLb)" class="t6q5npbfe"/></g><path class="yap8h-69j"/><path fill="url(#iefetzc)" class="rl6o24rpa"/><path class="edu356h8a"/><g filter="url(#ih7fxzb)"><path fill="url(#iruq5pc)" class="ck8aob5yl"/></g><g filter="url(#itwmHfb)"><ellipse transform="rotate(-27.914 14.199 13.826)" class="jcwji135y"/><ellipse fill="url(#iMMAmWd)" transform="rotate(-27.914 14.199 13.826)" class="j3af3t0lk"/></g><g filter="url(#ixhX7Jb)"><path fill="url(#itaGfHV)" clip-rule="evenodd" class="az3i9e_0y"/></g><g filter="url(#ipX2NKb)"><path class="p01d23b1i"/></g><g filter="url(#if8vRHc)"><path fill="url(#iwHRX3D)" clip-rule="evenodd" class="zkyr435ek"/></g><g filter="url(#ijbGnqe)"><path class="dvl1qccly"/></g><path fill="url(#iMwhdrV)" class="qzd219blo"/><path fill="url(#i3dSYhb)" class="qzd219blo"/><path fill="url(#inl9J2c)" class="qzd219blo"/><path fill="url(#iCE2gke)" class="wozepxbaa"/><path fill="url(#izP9Z9c)" class="wozepxbaa"/><rect fill="url(#iK2GSbd)" class="okwd93kys"/><rect fill="url(#iy7tjOa)" class="okwd93kys"/><rect fill="url(#iYE2hsb)" class="okwd93kys"/><defs><radialGradient id="iCWg3yz" cx="0" cy="0" r="1" gradientTransform="rotate(135.22 8.643 15.887)scale(12.9545 12.5552)" gradientUnits="userSpaceOnUse"><stop offset=".195" class="m-1-e5bla"/><stop offset=".655" class="x92j_kb4w"/></radialGradient><radialGradient id="iTFB9Bb" cx="0" cy="0" r="1" gradientTransform="matrix(2.75 0 0 6.1875 8.969 25.389)" gradientUnits="userSpaceOnUse"><stop class="nmqo35b7x"/><stop offset="1" class="gzcpsebza"/></radialGradient><radialGradient id="iw5sInd" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.09375 -3.28125 0 20.219 20.139)" gradientUnits="userSpaceOnUse"><stop class="dpkv3e8bt"/><stop offset="1" class="w4ea2bbjv"/></radialGradient><radialGradient id="il5eVUq" cx="0" cy="0" r="1" gradientTransform="matrix(-1.75 0 0 -11.7187 21 25.92)" gradientUnits="userSpaceOnUse"><stop offset=".214" class="demkpcl0k"/><stop offset="1" class="ym-b_m9fy"/></radialGradient><radialGradient id="iY3yYtd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.15625 0 0 -5.75902 11.656 25.326)" gradientUnits="userSpaceOnUse"><stop class="ujrq6ixuu"/><stop offset="1" class="h4mko5b9o"/></radialGradient><radialGradient id="iBZ0RUd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.34375 2.4375 -2.36069 -1.3014 7.187 11.826)" gradientUnits="userSpaceOnUse"><stop offset=".077" class="l-r9gxb9g"/><stop offset="1" class="hcmh5c50b"/></radialGradient><radialGradient id="itKlKTd" cx="0" cy="0" r="1" gradientTransform="rotate(115.145 -.151 8.247)scale(3.38309 2.95533)" gradientUnits="userSpaceOnUse"><stop offset=".452" class="y-1rsmdul"/><stop offset=".826" class="af8mzdbwl"/></radialGradient><radialGradient id="ihlr5IT" cx="0" cy="0" r="1" gradientTransform="matrix(-1.34375 2.4375 -2.36069 -1.3014 10.101 2.846)" gradientUnits="userSpaceOnUse"><stop offset=".077" class="mpwbs5b3u"/><stop offset="1" class="fzq016boz"/></radialGradient><radialGradient id="iGUmgWd" cx="0" cy="0" r="1" gradientTransform="rotate(115.145 4.158 4.683)scale(3.38309 2.95533)" gradientUnits="userSpaceOnUse"><stop offset=".452" class="x1l7xqbyw"/><stop offset=".826" class="ng1cexbhj"/></radialGradient><radialGradient id="iXhqZHd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.34375 2.4375 -2.36069 -1.3014 26.066 3.861)" gradientUnits="userSpaceOnUse"><stop offset=".077" class="lelj2r8dg"/><stop offset="1" class="fde_fwzpt"/></radialGradient><radialGradient id="iOHvRJe" cx="0" cy="0" r="1" gradientTransform="rotate(105.03 11.36 11.751)scale(3.49455 3.40391)" gradientUnits="userSpaceOnUse"><stop offset=".375" class="ppr920emc"/><stop offset=".826" class="y_auwli2s"/></radialGradient><radialGradient id="issuNue" cx="0" cy="0" r="1" gradientTransform="matrix(-1.34375 2.4375 -2.36069 -1.3014 27.09 13.818)" gradientUnits="userSpaceOnUse"><stop offset=".077" class="y05rrkbkk"/><stop offset="1" class="a5zzorbzd"/></radialGradient><radialGradient id="iMaLBhb" cx="0" cy="0" r="1" gradientTransform="matrix(1 1.07812 -1.5877 1.47265 24.969 13.357)" gradientUnits="userSpaceOnUse"><stop class="i8j0jyb4u"/><stop offset="1" class="d7caiobkz"/></radialGradient><radialGradient id="iAhrvZc" cx="0" cy="0" r="1" gradientTransform="rotate(109.11 8.51 16.52)scale(3.46022 3.37046)" gradientUnits="userSpaceOnUse"><stop offset=".347" class="tn_97qkdc"/><stop offset=".829" class="mmq2utbuk"/></radialGradient><radialGradient id="iMk8UMb" cx="0" cy="0" r="1" gradientTransform="matrix(-.7578 1.14063 -.96756 -.64282 17.25 27.855)" gradientUnits="userSpaceOnUse"><stop offset=".212" class="u6lph46no"/><stop offset="1" class="bq5dgsbba"/></radialGradient><radialGradient id="iR23Gge" cx="0" cy="0" r="1" gradientTransform="matrix(-.7578 1.14063 -.96756 -.64282 17.25 25.842)" gradientUnits="userSpaceOnUse"><stop offset=".212" class="u6lph46no"/><stop offset="1" class="bq5dgsbba"/></radialGradient><radialGradient id="i5YvaPc" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.03125 -2.40212 0 22.222 20.983)" gradientUnits="userSpaceOnUse"><stop class="koq0r9bvu"/><stop offset="1" class="dpmuo-biy"/></radialGradient><radialGradient id="ieol8Me" cx="0" cy="0" r="1" gradientTransform="scale(1.38818 6.1875)rotate(90 2.761 6.5)" gradientUnits="userSpaceOnUse"><stop class="xntzq-4ho"/><stop offset="1" class="pt8frltpn"/></radialGradient><radialGradient id="iDbbcbc" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.25 -.60938 0 13.062 24.108)" gradientUnits="userSpaceOnUse"><stop class="wshx69b-y"/><stop offset="1" class="aqzyd8bsb"/></radialGradient><radialGradient id="iOe2zrd" cx="0" cy="0" r="1" gradientTransform="matrix(2.9375 -7.98881 7.06186 2.59666 10.312 28.264)" gradientUnits="userSpaceOnUse"><stop offset=".724" class="lgi0lwbjz"/><stop offset="1" class="tvoyviyhj"/></radialGradient><radialGradient id="iV71Rbc" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.42188 -.18506 0 12.857 21.717)" gradientUnits="userSpaceOnUse"><stop class="m5avsc_ef"/><stop offset="1" class="ci3gi1b_k"/></radialGradient><radialGradient id="iJ1cHHU" cx="0" cy="0" r="1" gradientTransform="matrix(-3.90624 2.42972 -4.28692 -6.89204 19.563 20.795)" gradientUnits="userSpaceOnUse"><stop class="sqf03_p-t"/><stop offset="1" class="kdv9gpb4z"/></radialGradient><radialGradient id="ix2mzrc" cx="0" cy="0" r="1" gradientTransform="matrix(-.46875 -.125 .54686 -2.05079 19.484 22.483)" gradientUnits="userSpaceOnUse"><stop offset=".108" class="qsu4qbckq"/><stop offset="1" class="gr0wzobbs"/></radialGradient><radialGradient id="iSAsI1d" cx="0" cy="0" r="1" gradientTransform="matrix(1.73878 1.3451 -1.47727 1.90964 13.775 23.358)" gradientUnits="userSpaceOnUse"><stop class="ab6i82btp"/><stop offset="1" class="pb6efmson"/></radialGradient><radialGradient id="iwtPTOo" cx="0" cy="0" r="1" gradientTransform="matrix(-1.68958 -.4774 .79459 -2.81214 15.416 23.836)" gradientUnits="userSpaceOnUse"><stop offset=".69" class="sawf8hb2n"/><stop offset="1" class="o415o878f"/></radialGradient><radialGradient id="isAdhHe" cx="0" cy="0" r="1" gradientTransform="matrix(-.5 1.58457 -.75053 -.23683 16.11 23.836)" gradientUnits="userSpaceOnUse"><stop class="btor07b8q"/><stop offset="1" class="jjf293xlz"/></radialGradient><radialGradient id="ivLP6Gc" cx="0" cy="0" r="1" gradientTransform="rotate(142.275 5.895 15.056)scale(2.19833 2.41434)" gradientUnits="userSpaceOnUse"><stop class="auvn9fbbk"/><stop offset="1" class="h2li0wblg"/></radialGradient><radialGradient id="iXetYud" cx="0" cy="0" r="1" gradientTransform="matrix(1.68958 -.4774 .79459 2.81214 18.13 23.836)" gradientUnits="userSpaceOnUse"><stop offset=".69" class="sawf8hb2n"/><stop offset="1" class="o415o878f"/></radialGradient><radialGradient id="iw9bnJb" cx="0" cy="0" r="1" gradientTransform="matrix(-.39136 0 0 -2.59279 17.54 23.592)" gradientUnits="userSpaceOnUse"><stop class="scbqttb8d"/><stop offset="1" class="u1gl_1zha"/></radialGradient><radialGradient id="ipMueJd" cx="0" cy="0" r="1" gradientTransform="matrix(-4.375 1.44046 -1.3893 -4.21963 28.094 22.456)" gradientUnits="userSpaceOnUse"><stop offset=".241" class="l3ydtt4ya"/><stop offset=".899" class="vgk5w_bmg"/></radialGradient><radialGradient id="i3JaYLp" cx="0" cy="0" r="1" gradientTransform="rotate(163.091 11.836 12.97)scale(3.90165 13.4872)" gradientUnits="userSpaceOnUse"><stop offset=".699" class="w5vup9bwr"/><stop offset="1" class="mu0q52a8h"/></radialGradient><radialGradient id="iTna7Kc" cx="0" cy="0" r="1" gradientTransform="rotate(139.97 1.2 10.48)scale(1.53045 3.638)" gradientUnits="userSpaceOnUse"><stop offset=".129" class="lelniimio"/><stop offset="1" class="zeffp9bvk"/></radialGradient><radialGradient id="ih4s9ac" cx="0" cy="0" r="1" gradientTransform="matrix(-.79386 1.27188 -2.4349 -1.51978 6.442 17.553)" gradientUnits="userSpaceOnUse"><stop class="wef8zac8b"/><stop offset="1" class="hoarz6bum"/></radialGradient><radialGradient id="ikJdwNc" cx="0" cy="0" r="1" gradientTransform="matrix(-.73037 2.48832 -3.82658 -1.12318 6.977 17.288)" gradientUnits="userSpaceOnUse"><stop offset=".63" class="e8-v49b1g"/><stop offset="1" class="y6ze32mia"/></radialGradient><radialGradient id="i40zLFb" cx="0" cy="0" r="1" gradientTransform="rotate(116.602 -3.017 10.55)scale(1.58621 2.70684)" gradientUnits="userSpaceOnUse"><stop class="wef8zac8b"/><stop offset="1" class="hoarz6bum"/></radialGradient><radialGradient id="il9qrHe" cx="0" cy="0" r="1" gradientTransform="matrix(-.65347 2.77477 -3.52334 -.82977 5.545 17.677)" gradientUnits="userSpaceOnUse"><stop offset=".63" class="e8-v49b1g"/><stop offset="1" class="y6ze32mia"/></radialGradient><radialGradient id="imjV17b" cx="0" cy="0" r="1" gradientTransform="matrix(-.68468 1.22288 -2.2217 -1.2439 4.939 18.947)" gradientUnits="userSpaceOnUse"><stop class="wef8zac8b"/><stop offset="1" class="hoarz6bum"/></radialGradient><radialGradient id="iD8Aurb" cx="0" cy="0" r="1" gradientTransform="rotate(104.751 -4.503 11.427)scale(2.474 3.46652)" gradientUnits="userSpaceOnUse"><stop offset=".63" class="e8-v49b1g"/><stop offset="1" class="y6ze32mia"/></radialGradient><radialGradient id="i2Iv6ab" cx="0" cy="0" r="1" gradientTransform="rotate(122.692 -2.834 11.406)scale(1.24393 2.40994)" gradientUnits="userSpaceOnUse"><stop class="wef8zac8b"/><stop offset="1" class="hoarz6bum"/></radialGradient><radialGradient id="ihNB5dd" cx="0" cy="0" r="1" gradientTransform="matrix(-.61813 2.04813 -3.22394 -.973 5.687 19.733)" gradientUnits="userSpaceOnUse"><stop offset=".63" class="e8-v49b1g"/><stop offset="1" class="y6ze32mia"/></radialGradient><radialGradient id="ilhtGxd" cx="0" cy="0" r="1" gradientTransform="rotate(-162.011 6.48 10.137)scale(3.69324 5.10277)" gradientUnits="userSpaceOnUse"><stop class="dwn54oxgo"/><stop offset="1" class="v0i04x6vh"/></radialGradient><radialGradient id="itEg77z" cx="0" cy="0" r="1" gradientTransform="matrix(.07812 -.82813 3.88844 .36683 6.156 21.78)" gradientUnits="userSpaceOnUse"><stop class="hq864_b1v"/><stop offset="1" class="e-tdchb2h"/></radialGradient><radialGradient id="ilHp1He" cx="0" cy="0" r="1" gradientTransform="matrix(1.65625 2.09375 -2.38774 1.88881 16.031 20.389)" gradientUnits="userSpaceOnUse"><stop offset=".229" class="gzw3vzb1j"/><stop offset="1" class="pwx273btt"/></radialGradient><radialGradient id="iKwJqgb" cx="0" cy="0" r="1" gradientTransform="rotate(178.447 13.441 10.55)scale(2.70045 29.1455)" gradientUnits="userSpaceOnUse"><stop class="zmosas2ke"/><stop offset="1" class="cpfhw8b0c"/></radialGradient><radialGradient id="iHopaXc" cx="0" cy="0" r="1" gradientTransform="matrix(1.82448 0 0 3.19286 10.08 14.635)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="p8hteacus"/><stop offset="1" class="ez11m_bio"/></radialGradient><radialGradient id="iNTFjAx" cx="0" cy="0" r="1" gradientTransform="matrix(.8595 -.62585 .71432 .981 22.093 14.36)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="ykvv4rhnl"/><stop offset="1" class="rixtyr4np"/></radialGradient><radialGradient id="iSjhqwG" cx="0" cy="0" r="1" gradientTransform="matrix(.85355 -1.56992 .91888 .49959 21.662 15.488)" gradientUnits="userSpaceOnUse"><stop offset=".69" class="mrmfxebtr"/><stop offset="1" class="avncbf64d"/></radialGradient><radialGradient id="id0jZvd" cx="0" cy="0" r="1" gradientTransform="rotate(44.708 -6.94 33.708)scale(.37918 .48881)" gradientUnits="userSpaceOnUse"><stop class="q8bsowbrp"/><stop offset="1" class="p-73vab8n"/></radialGradient><radialGradient id="iedrnKy" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.92625 -10.1921 0 17.262 12.98)" gradientUnits="userSpaceOnUse"><stop offset=".526" class="tpaawnlif"/><stop offset=".925" class="iy2p59b9j"/></radialGradient><radialGradient id="iVufHyU" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.35894 1.67254 0 19.19 13.313)" gradientUnits="userSpaceOnUse"><stop class="qvori65vn"/><stop offset="1" class="l_2mr6b5e"/></radialGradient><radialGradient id="iJ2wNtd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.44605 1.79829 0 14.452 13.278)" gradientUnits="userSpaceOnUse"><stop class="waf9s5hfu"/><stop offset="1" class="qibk7dfmm"/></radialGradient><radialGradient id="iXpBHzS" cx="0" cy="0" r="1" gradientTransform="rotate(127.807 8.675 8.35)scale(5.82859 9.91204)" gradientUnits="userSpaceOnUse"><stop class="ck410xb1o"/><stop offset="1" class="qeh0r4bjq"/></radialGradient><radialGradient id="icmKGxd" cx="0" cy="0" r="1" gradientTransform="matrix(-.19181 -2.07156 1.01739 -.0942 12.451 10.852)" gradientUnits="userSpaceOnUse"><stop offset=".222" class="euj6xpbnj"/><stop offset="1" class="hchnd0bsx"/></radialGradient><radialGradient id="iCIolwe" cx="0" cy="0" r="1" gradientTransform="matrix(.89323 -2.0445 1.66745 .7285 21.146 12.828)" gradientUnits="userSpaceOnUse"><stop offset=".479" class="ghdrqrbfe"/><stop offset="1" class="d7zypgbet"/></radialGradient><radialGradient id="iQxs4Td" cx="0" cy="0" r="1" gradientTransform="matrix(1.03217 1.28074 -1.1308 .91133 15.945 5.692)" gradientUnits="userSpaceOnUse"><stop class="wn92vfpti"/><stop offset="1" class="t4clght5m"/></radialGradient><radialGradient id="izC3nvd" cx="0" cy="0" r="1" gradientTransform="rotate(-64.453 18.681 -11.617)scale(3.49808 1.20863)" gradientUnits="userSpaceOnUse"><stop class="hye_w5bmk"/><stop offset="1" class="f2dz70yyi"/></radialGradient><radialGradient id="igio5bc" cx="0" cy="0" r="1" gradientTransform="matrix(.02557 -.65216 1.95647 .07672 16.663 18.806)" gradientUnits="userSpaceOnUse"><stop class="zjmwko4fr"/><stop offset="1" class="md9bsbc9k"/></radialGradient><radialGradient id="ikaYcCe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .93866 -1.11068 0 19.017 14.272)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="ibAYMvd" cx="0" cy="0" r="1" gradientTransform="matrix(-.24098 -.31054 .42753 -.33177 18.779 14.013)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iefetzc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .93871 -1.11074 0 14.48 14.272)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iMMAmWd" cx="0" cy="0" r="1" gradientTransform="matrix(-.00804 -.5134 .61712 -.00966 14.183 14.153)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="itaGfHV" cx="0" cy="0" r="1" gradientTransform="matrix(.20453 -.84368 1.8509 .4487 19.3 11.979)" gradientUnits="userSpaceOnUse"><stop offset=".657" class="mrt-5h0hn"/><stop offset="1" class="xaad_wcir"/></radialGradient><radialGradient id="iwHRX3D" cx="0" cy="0" r="1" gradientTransform="rotate(-103.627 11.812 .404)scale(.86812 1.9045)" gradientUnits="userSpaceOnUse"><stop offset=".657" class="mrt-5h0hn"/><stop offset="1" class="xaad_wcir"/></radialGradient><radialGradient id="iMwhdrV" cx="0" cy="0" r="1" gradientTransform="matrix(-5.5 4.12501 -3.615 -4.82 20.719 4.576)" gradientUnits="userSpaceOnUse"><stop offset=".179" class="tg07-ljnl"/><stop offset="1" class="c6833cb9x"/></radialGradient><radialGradient id="i3dSYhb" cx="0" cy="0" r="1" gradientTransform="matrix(2.875 .375 -.58342 4.4729 10.781 7.701)" gradientUnits="userSpaceOnUse"><stop class="j8k1fac_p"/><stop offset="1" class="g8uem1b5g"/></radialGradient><radialGradient id="inl9J2c" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.875 8.03906 0 16.773 8.326)" gradientUnits="userSpaceOnUse"><stop offset=".761" class="km6q7kb1a"/><stop offset="1" class="i8skpb2jz"/></radialGradient><radialGradient id="iCE2gke" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.47656 -8.28125 0 18.406 7.912)" gradientUnits="userSpaceOnUse"><stop class="kzuil_5zu"/><stop offset="1" class="ok2r3obil"/></radialGradient><radialGradient id="iK2GSbd" cx="0" cy="0" r="1" gradientTransform="matrix(-7.1875 0 0 -.63281 21.268 9.87)" gradientUnits="userSpaceOnUse"><stop class="w63qn2bkh"/><stop offset="1" class="vvfum-_fa"/></radialGradient><radialGradient id="iy7tjOa" cx="0" cy="0" r="1" gradientTransform="matrix(3.48438 0 0 2.01172 9.003 10.109)" gradientUnits="userSpaceOnUse"><stop class="gfrsedb9v"/><stop offset="1" class="vke6kh8bt"/></radialGradient><filter id="iMrCPHc" width="21.247" height="10.303" x="6.25" y="19.623" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.776471 0 0 0 0 0.745098 0 0 0 0 0.741176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23845"/></filter><filter id="ixfZlgc" width="2.078" height="2.078" x="15.622" y="27.457" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.792157 0 0 0 0 0.717647 0 0 0 0 0.788235 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_3987_23845"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_3987_23845" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.831373 0 0 0 0 0.745098 0 0 0 0 0.803922 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_3987_23845"/></filter><filter id="ii0Rzsd" width="2.078" height="2.078" x="15.622" y="25.444" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.792157 0 0 0 0 0.717647 0 0 0 0 0.788235 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_3987_23845"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_3987_23845" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.831373 0 0 0 0 0.745098 0 0 0 0 0.803922 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_3987_23845"/></filter><filter id="iOo264d" width="6.554" height="3.702" x="13.677" y="19.523" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.741176 0 0 0 0 0.666667 0 0 0 0 0.701961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23845"/></filter><filter id="iuAefgb" width="8.324" height="4.864" x="12.611" y="21.931" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23845" stdDeviation=".5"/></filter><filter id="inBlbCN" width="2.672" height="2.865" x="13.611" y="22.403" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.780392 0 0 0 0 0.270588 0 0 0 0 0.396078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23845"/></filter><filter id="iVr1UgR" width="2.672" height="2.865" x="17.264" y="22.403" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.780392 0 0 0 0 0.270588 0 0 0 0 0.396078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23845"/></filter><filter id="isp3xlb" width="1.554" height="1.999" x="15.986" y="22.812" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.827451 0 0 0 0 0.137255 0 0 0 0 0.317647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23845"/></filter><filter id="iJ4OXKc" width="4.764" height="4.766" x="24.75" y="19.349" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.1"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.909804 0 0 0 0 0.658824 0 0 0 0 0.14902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23845"/></filter><filter id="iMvtzQe" width="2.277" height="3.844" x="25.907" y="17.448" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".6"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.996078 0 0 0 0 0.713726 0 0 0 0 0.0862745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23845"/></filter><filter id="i4J64ed" width="2.436" height="4.046" x="24.436" y="17.107" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.92549 0 0 0 0 0.643137 0 0 0 0 0.101961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23845"/></filter><filter id="iuSzUwM" width="2.312" height="4.044" x="23.386" y="17.96" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.917647 0 0 0 0 0.631373 0 0 0 0 0.129412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23845"/></filter><filter id="iOE9K4d" width="2.123" height="3.114" x="22.394" y="19.041" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.870588 0 0 0 0 0.619608 0 0 0 0 0.219608 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23845"/></filter><filter id="iRdXnIe" width="3.002" height="3.147" x="6.649" y="16.347" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.811765 0 0 0 0 0.588235 0 0 0 0 0.294118 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23845"/></filter><filter id="iJuswmc" width="4.665" height="1.737" x="23.02" y="19.912" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23845" stdDeviation=".125"/></filter><filter id="iu5CvOe" width="3.068" height="3.068" x="10.281" y="13.1" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23845" stdDeviation=".25"/></filter><filter id="iW81uhz" width="3.721" height="3.721" x="19.971" y="12.649" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.85098 0 0 0 0 0.560784 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23845"/></filter><filter id="ikmJWWd" width="3.068" height="3.068" x="20.171" y="13.1" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23845" stdDeviation=".25"/></filter><filter id="icK5J3c" width="3.329" height="4.287" x="14.838" y="13.464" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23845" stdDeviation=".375"/></filter><filter id="iiiGsPb" width="2.451" height="3.287" x="15.526" y="13.794" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23845" stdDeviation=".125"/></filter><filter id="is79gac" width="3.745" height="1.515" x="14.879" y="17.329" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23845" stdDeviation=".05"/></filter><filter id="i4pJyre" width=".81" height=".716" x="18.258" y="13.473" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23845" stdDeviation=".05"/></filter><filter id="iB0PSQc" width=".91" height=".933" x="19.134" y="13.554" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23845" stdDeviation=".1"/></filter><filter id="ih7fxzb" width="1.009" height="1.065" x="14.517" y="13.489" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23845" stdDeviation=".1"/></filter><filter id="itwmHfb" width=".941" height=".724" x="13.728" y="13.464" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23845" stdDeviation=".05"/></filter><filter id="ixhX7Jb" width="2.704" height="1.702" x="18.066" y="10.73" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.698039 0 0 0 0 0.25098 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23845"/></filter><filter id="ipX2NKb" width="2.772" height="1.52" x="18.032" y="10.831" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23845" stdDeviation=".2"/></filter><filter id="if8vRHc" width="2.704" height="1.702" x="12.733" y="10.73" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.698039 0 0 0 0 0.25098 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23845"/></filter><filter id="ijbGnqe" width="2.772" height="1.52" x="12.699" y="10.831" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23845" stdDeviation=".2"/></filter><linearGradient id="iK84mBb" x1="22.562" x2="21.812" y1="29.826" y2="29.826" gradientUnits="userSpaceOnUse"><stop class="fr__qmhjc"/><stop offset="1" class="gypp10kih"/></linearGradient><linearGradient id="iWCiqKd" x1="20.644" x2="21.062" y1="29.014" y2="29.014" gradientUnits="userSpaceOnUse"><stop class="hj-s-zboe"/><stop offset="1" class="s0umluqbl"/></linearGradient><linearGradient id="ipodSkc" x1="9.531" x2="4.906" y1="27.451" y2="27.451" gradientUnits="userSpaceOnUse"><stop class="sb-ednb_a"/><stop offset="1" class="v0501vbqa"/></linearGradient><linearGradient id="iXPTZOc" x1="9.75" x2="8.828" y1="27.076" y2="27.076" gradientUnits="userSpaceOnUse"><stop class="o_30au2yc"/><stop offset="1" class="c60cvac3k"/></linearGradient><linearGradient id="itP1zjc" x1="27.871" x2="22.844" y1="28.142" y2="28.142" gradientUnits="userSpaceOnUse"><stop class="i7zyuv8vr"/><stop offset=".907" class="qzhltkbuo"/></linearGradient><linearGradient id="i33ZCUz" x1="28.09" x2="27.168" y1="27.876" y2="27.876" gradientUnits="userSpaceOnUse"><stop class="tub8lbbfx"/><stop offset="1" class="bd09vtb_c"/></linearGradient><linearGradient id="i8tJXGc" x1="16.763" x2="16.763" y1="22.812" y2="24.81" gradientUnits="userSpaceOnUse"><stop offset=".351" class="gzsz7evmk"/><stop offset="1" class="smgiue0gi"/></linearGradient><linearGradient id="ib7wIKe" x1="11.815" x2="11.149" y1="14.924" y2="14.924" gradientUnits="userSpaceOnUse"><stop class="k94wnob3w"/><stop offset="1" class="pxzrjgb8y"/></linearGradient><linearGradient id="iRVGrLb" x1="22.836" x2="21.985" y1="13.5" y2="16.137" gradientUnits="userSpaceOnUse"><stop class="s5fwd11en"/><stop offset="1" class="tsum8q2zl"/></linearGradient><linearGradient id="iQNbWGd" x1="20.948" x2="13.008" y1="15.04" y2="16.223" gradientUnits="userSpaceOnUse"><stop class="mbmro29rs"/><stop offset=".916" class="as9qb1byz"/></linearGradient><linearGradient id="iK76Qpd" x1="11.142" x2="13.546" y1="17.843" y2="17.529" gradientUnits="userSpaceOnUse"><stop class="a99w59rao"/><stop offset="1" class="x2u305zwp"/></linearGradient><linearGradient id="icL5zKb" x1="16.782" x2="16.782" y1="10.139" y2="12.389" gradientUnits="userSpaceOnUse"><stop offset=".236" class="pjfyjvbdl"/><stop offset="1" class="ae8mesboz"/></linearGradient><linearGradient id="i9f88zc" x1="11.697" x2="14.715" y1="14.357" y2="8.997" gradientUnits="userSpaceOnUse"><stop class="kyzs66gfi"/><stop offset="1" class="zsx4vmb0f"/></linearGradient><linearGradient id="iEhEBmd" x1="15.853" x2="16.828" y1="15.724" y2="15.724" gradientUnits="userSpaceOnUse"><stop class="vrar8hnmh"/><stop offset="1" class="ry_l2ebgl"/></linearGradient><linearGradient id="iH1qLAc" x1="17.727" x2="16.661" y1="16.059" y2="16.044" gradientUnits="userSpaceOnUse"><stop class="hmiraywql"/><stop offset="1" class="l99c_58cs"/></linearGradient><linearGradient id="it1tIvd" x1="16.954" x2="16.954" y1="16.831" y2="16.235" gradientUnits="userSpaceOnUse"><stop class="wno2x162j"/><stop offset="1" class="hog28xbdu"/></linearGradient><linearGradient id="imA5vLb" x1="19.825" x2="19.499" y1="13.982" y2="14.182" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iruq5pc" x1="15.254" x2="14.928" y1="13.982" y2="14.182" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="izP9Z9c" x1="16.773" x2="16.773" y1="7.912" y2="8.1" gradientUnits="userSpaceOnUse"><stop class="jhlen960d"/><stop offset="1" class="wjchuwb6a"/></linearGradient><linearGradient id="iYE2hsb" x1="17.956" x2="17.956" y1="10.98" y2="10.214" gradientUnits="userSpaceOnUse"><stop class="bl3fq0x9z"/><stop offset="1" class="lxo7c2i6k"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-juggling" /></template>
<style>
.a5zzorbzd {
  stop-color: var(--svg-color--e1ac3a, #E1AC3A);
}

.a99w59rao {
  stop-color: var(--svg-color--d19c3a, #D19C3A);
}

.ab6i82btp {
  stop-color: var(--svg-color--e7377c, #E7377C);
}

.ae8mesboz {
  stop-color: var(--svg-color--f5a624, #F5A624);
  stop-opacity: 0;
}

.af8mzdbwl {
  stop-color: var(--svg-color--5f679a, #5F679A);
}

.aqzyd8bsb {
  stop-color: var(--svg-color--896bb4, #896BB4);
  stop-opacity: 0;
}

.as9qb1byz {
  stop-color: var(--svg-color--f9a528, #F9A528);
}

.auvn9fbbk {
  stop-color: var(--svg-color--e9387a, #E9387A);
}

.avncbf64d {
  stop-color: var(--svg-color--f4a51a, #F4A51A);
}

.az3i9e_0y {
  fill-rule: evenodd;
  d: path("M18.602 11.972c.748-.07 1.228.222 1.344.33a.49.49 0 1 0 .666-.722c-.319-.294-1.072-.681-2.101-.585a.49.49 0 1 0 .091.977");
}

.bd09vtb_c {
  stop-color: var(--svg-color--e0dde3, #E0DDE3);
  stop-opacity: 0;
}

.bl3fq0x9z {
  stop-color: var(--svg-color--543459, #543459);
}

.bq-3inb5p {
  cx: 11.815px;
  cy: 14.635px;
  r: 1.736px;
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

.c60cvac3k {
  stop-color: var(--svg-color--e5ddee, #E5DDEE);
  stop-opacity: 0;
}

.c6833cb9x {
  stop-color: var(--svg-color--372f3c, #372F3C);
}

.c90ph3ygb {
  d: path("M19.019 13.43a.927.927 0 0 1 .893 1.172h-1.791a.93.93 0 0 1 .898-1.172");
}

.cfziuz30v {
  fill: var(--svg-color--ffc239, #FFC239);
  d: path("M22.414 19.88a.68.68 0 1 1 1.33-.293l.36 1.793a.645.645 0 0 1-1.26.28z");
}

.ci3gi1b_k {
  stop-color: var(--svg-color--784b89, #784B89);
  stop-opacity: 0;
}

.ck410xb1o {
  stop-color: var(--svg-color--ffe336, #FFE336);
}

.ck8aob5yl {
  d: path("M15.326 14.248c0-.3-.244-.5-.31-.56l-.3.29l.185.376z");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cpfhw8b0c {
  stop-color: var(--svg-color--ffc32b, #FFC32B);
}

.crnv2vbtk {
  fill: var(--svg-color--f1901c, #F1901C);
  d: path("m16.465 14.507l-.853 1.767c-.106.363.148.726.507.726h.767c.359 0 .612-.369.507-.726l-.518-1.767c-.111-.391-.294-.391-.41 0");
}

.ctsppjbax {
  d: path("M14.866 22.463c.91.308 1.268.83 1.389 1.082l.028.29l-.028.359c-.12.25-.48.706-1.389 1.014c-.36.123-.777.068-.97-.267a2.17 2.17 0 0 1-.285-1.105c0-.502.144-.862.285-1.106c.193-.335.61-.39.97-.267");
}

.ctupw6b3d {
  fill-rule: evenodd;
  d: path("M3.113 18.184a.75.75 0 0 1 1.042.196c.312.455.974 1.204 1.85 1.204a.75.75 0 1 1 0 1.5c-1.702 0-2.759-1.376-3.088-1.858a.75.75 0 0 1 .196-1.042");
}

.d5_x4xk7i {
  fill-rule: evenodd;
  d: path("M3.16 17.066a.75.75 0 0 1 1.042.197q.055.08.116.173c.17.259.379.576.676.877c.36.363.768.614 1.246.64a.75.75 0 0 1-.08 1.497c-.99-.052-1.73-.575-2.232-1.083c-.416-.42-.725-.893-.888-1.143l-.076-.115a.75.75 0 0 1 .196-1.043");
}

.d7caiobkz {
  stop-color: var(--svg-color--e4cc30, #E4CC30);
  stop-opacity: 0;
}

.d7zypgbet {
  stop-color: var(--svg-color--e57d1c, #E57D1C);
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

.dvl1qccly {
  stroke: var(--svg-color--d76d5b, #D76D5B);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M13.224 11.826c.217-.2.834-.54 1.723-.457");
}

.dwn54oxgo {
  stop-color: var(--svg-color--ffe23d, #FFE23D);
}

.e-tdchb2h {
  stop-color: var(--svg-color--f7b528, #F7B528);
  stop-opacity: 0;
}

.e8-v49b1g {
  stop-color: var(--svg-color--efa929, #EFA929);
  stop-opacity: 0;
}

.edu356h8a {
  fill: var(--svg-color--000, #000);
  d: path("M15.01 14.357a.53.53 0 0 0-.532-.53a.53.53 0 0 0-.472.775h.94a.5.5 0 0 0 .063-.245");
}

.ei9-ouyfz {
  d: path("M18.95 13.626c.067.088-.071.196-.228.314s-.274.2-.34.111c-.066-.088.008-.255.165-.373s.338-.14.404-.052");
}

.euj6xpbnj {
  stop-color: var(--svg-color--ffb42c, #FFB42C);
}

.ewajonw4w {
  cx: 21.705px;
  cy: 14.634px;
  r: 1.034px;
  fill: var(--svg-color--ffbf34, #FFBF34);
}

.ez11m_bio {
  stop-color: var(--svg-color--ca8f29, #CA8F29);
}

.f21vmbcik {
  d: path("M5.437 21.764h4.094v8.063H5.437z");
}

.f2dz70yyi {
  stop-color: var(--svg-color--ffd93a, #FFD93A);
  stop-opacity: 0;
}

.fde_fwzpt {
  stop-color: var(--svg-color--5c9946, #5C9946);
}

.fgpnfrb_u {
  fill: var(--svg-color--bc9ebb, #BC9EBB);
  fill-rule: evenodd;
  d: path("M16.022 23.723c-.213-.246-.57-.534-1.156-.733c-.36-.122-.777-.067-.97.268c-.14.243-.285.604-.285 1.105s.144.862.285 1.105c.193.335.61.39.97.267c.604-.204.965-.474 1.175-.706c.048.135.159.24.305.268c.29.055.544.055.834 0a.41.41 0 0 0 .31-.285c.208.236.572.514 1.19.723c.362.123.778.068.971-.267c.14-.243.284-.598.284-1.105s-.144-.862-.284-1.105c-.193-.335-.61-.39-.97-.268c-.603.205-.964.503-1.174.754a.41.41 0 0 0-.327-.363a2.1 2.1 0 0 0-.834 0a.41.41 0 0 0-.324.342");
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

.g8uem1b5g {
  stop-color: var(--svg-color--38303e, #38303E);
  stop-opacity: 0;
}

.gfrsedb9v {
  stop-color: var(--svg-color--5b595e, #5B595E);
}

.ggx6mbb3s {
  fill: var(--svg-color--ffcc28, #FFCC28);
  d: path("m16.354 14.338l-.552 1.766a.56.56 0 0 0 .541.727h.817a.562.562 0 0 0 .541-.727l-.552-1.766c-.119-.391-.67-.391-.795 0");
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.ghdrqrbfe {
  stop-color: var(--svg-color--e57d1c, #E57D1C);
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

.gzcpsebza {
  stop-color: var(--svg-color--ded4e0, #DED4E0);
  stop-opacity: 0;
}

.gzsz7evmk {
  stop-color: var(--svg-color--eb3782, #EB3782);
}

.gzw3vzb1j {
  stop-color: var(--svg-color--d27429, #D27429);
}

.h2li0wblg {
  stop-color: var(--svg-color--d02759, #D02759);
}

.h4mko5b9o {
  stop-color: var(--svg-color--beb4c6, #BEB4C6);
  stop-opacity: 0;
}

.hchnd0bsx {
  stop-color: var(--svg-color--ffb42c, #FFB42C);
  stop-opacity: 0;
}

.hcmh5c50b {
  stop-color: var(--svg-color--357ace, #357ACE);
}

.hj-s-zboe {
  stop-color: var(--svg-color--6d5096, #6D5096);
}

.hmiraywql {
  stop-color: var(--svg-color--ffe721, #FFE721);
}

.hoarz6bum {
  stop-color: var(--svg-color--fab32c, #FAB32C);
}

.hog28xbdu {
  stop-color: var(--svg-color--eb8a1c, #EB8A1C);
  stop-opacity: 0;
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

.hye_w5bmk {
  stop-color: var(--svg-color--ffd93a, #FFD93A);
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

.ifie1jl_u {
  fill: var(--svg-color--ffa91b, #FFA91B);
  d: path("m21.761 7.9l-.056 1.33c.781.389 1.73.167 1.562 1.11l-.614 3.16c-.054.326-.27.546-.594.554c.037-.523.071-1.368.085-1.501c.045-.45-.026-.583-.439-.994c-.223-.221-.39-.554-.39-.887v-.887c0-.277-.223-.5-.446-.555c-.67-.166-2.064-.443-4.071-.443c-2.008 0-3.402.277-4.071.443a.54.54 0 0 0-.446.555v.887c0 .333-.112.665-.39.887l-.168.167c-.223.166-.336.513-.336.79c.015.162.037 1.094.062 1.481a.66.66 0 0 1-.618-.552l-.614-3.161c-.111-.887.199-.386.98-.774c1.054-.462 1.574-2.552 2.422-3.274c.614-.554 1.506-.72 2.287-.333a3.06 3.06 0 0 0 1.728 0c.837-.277 1.785-.055 2.454.555l.837.832c.223.277.502.443.836.61");
}

.iw6qprblb {
  cx: 21.706px;
  cy: 14.635px;
  r: 1.736px;
}

.iwbygtbvw {
  cx: 25.211px;
  cy: 4.873px;
  r: 1.684px;
}

.iy2p59b9j {
  stop-color: var(--svg-color--d4783e, #D4783E);
}

.j3af3t0lk {
  cx: 14.199px;
  cy: 13.826px;
  rx: 0.405px;
  ry: 0.205px;
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

.jcwji135y {
  cx: 14.199px;
  cy: 13.826px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.405px;
  ry: 0.205px;
}

.jhlen960d {
  stop-color: var(--svg-color--745ba5, #745BA5);
}

.jjf293xlz {
  stop-color: var(--svg-color--d61f4d, #D61F4D);
  stop-opacity: 0;
}

.k94wnob3w {
  stop-color: var(--svg-color--bd6a1e, #BD6A1E);
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

.kyzs66gfi {
  stop-color: var(--svg-color--e07027, #E07027);
}

.kzuil_5zu {
  stop-color: var(--svg-color--9072ca, #9072CA);
}

.l_2mr6b5e {
  stop-color: var(--svg-color--ffba0d, #FFBA0D);
  stop-opacity: 0;
}

.l-r9gxb9g {
  stop-color: var(--svg-color--4bb8fb, #4BB8FB);
}

.l3ydtt4ya {
  stop-color: var(--svg-color--ffda02, #FFDA02);
}

.l99c_58cs {
  stop-color: var(--svg-color--ffe721, #FFE721);
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

.lxo7c2i6k {
  stop-color: var(--svg-color--462f5a, #462F5A);
  stop-opacity: 0;
}

.m-1-e5bla {
  stop-color: var(--svg-color--fbf2f7, #FBF2F7);
}

.m5avsc_ef {
  stop-color: var(--svg-color--784b89, #784B89);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mbmro29rs {
  stop-color: var(--svg-color--ffe833, #FFE833);
}

.md9bsbc9k {
  stop-color: var(--svg-color--ffbe30, #FFBE30);
  stop-opacity: 0;
}

.mmq2utbuk {
  stop-color: var(--svg-color--cf8b51, #CF8B51);
}

.mpwbs5b3u {
  stop-color: var(--svg-color--ff894e, #FF894E);
}

.mrmfxebtr {
  stop-color: var(--svg-color--f4a51a, #F4A51A);
  stop-opacity: 0;
}

.mrt-5h0hn {
  stop-color: var(--svg-color--c64f38, #C64F38);
}

.mu0q52a8h {
  stop-color: var(--svg-color--d1923d, #D1923D);
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

.p-73vab8n {
  stop-color: var(--svg-color--e59b1f, #E59B1F);
  stop-opacity: 0;
}

.p01d23b1i {
  stroke: var(--svg-color--d76d5b, #D76D5B);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M20.28 11.826c-.218-.2-.835-.54-1.723-.457");
}

.p8hteacus {
  stop-color: var(--svg-color--e6962b, #E6962B);
}

.pb6efmson {
  stop-color: var(--svg-color--d72c5e, #D72C5E);
}

.pjfyjvbdl {
  stop-color: var(--svg-color--d98827, #D98827);
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

.pwx273btt {
  stop-color: var(--svg-color--e69530, #E69530);
}

.pxzrjgb8y {
  stop-color: var(--svg-color--d77a1c, #D77A1C);
}

.q8bsowbrp {
  stop-color: var(--svg-color--e59b1f, #E59B1F);
}

.qeh0r4bjq {
  stop-color: var(--svg-color--ffe336, #FFE336);
  stop-opacity: 0;
}

.qibk7dfmm {
  stop-color: var(--svg-color--ee911a, #EE911A);
  stop-opacity: 0;
}

.qsu4qbckq {
  stop-color: var(--svg-color--dbcdd4, #DBCDD4);
}

.qubidabul {
  cx: 11.815px;
  cy: 14.634px;
  r: 1.034px;
}

.qvori65vn {
  stop-color: var(--svg-color--ffba0d, #FFBA0D);
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

.rixtyr4np {
  stop-color: var(--svg-color--ffc532, #FFC532);
  stop-opacity: 0;
}

.rl6o24rpa {
  d: path("M14.478 13.43a.927.927 0 0 0-.894 1.172h1.792a1 1 0 0 0 .034-.245a.934.934 0 0 0-.932-.927");
}

.ry_l2ebgl {
  stop-color: var(--svg-color--faa416, #FAA416);
  stop-opacity: 0;
}

.s0umluqbl {
  stop-color: var(--svg-color--7160a4, #7160A4);
  stop-opacity: 0;
}

.s5fwd11en {
  stop-color: var(--svg-color--ffe446, #FFE446);
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

.sl0q4acir {
  d: path("M11.45 13.998a31 31 0 0 1-.061-1.496c0-.277.112-.61.335-.776l.167-.166c.279-.222.39-.555.39-.888v-.887a.54.54 0 0 1 .446-.554c.67-.167 2.064-.444 4.072-.444s3.401.277 4.07.444c.224.055.447.277.447.554v.887c0 .333.167.666.39.888c.522.365.49.567.446.998c-.013.133-.056 1.242-.093 1.497l-.276 4.115c-.167 1.84-1.613 3.122-3.338 3.122h-3.337c-1.78 0-3.171-1.282-3.338-3.122z");
}

.smgiue0gi {
  stop-color: var(--svg-color--c93857, #C93857);
}

.sp8j17bpa {
  fill: var(--svg-color--8a004f, #8A004F);
  d: path("M16.752 17.889a3.1 3.1 0 0 1-1.44-.342c-.143-.072-.296.088-.206.218a1.97 1.97 0 0 0 1.646.879c.69 0 1.297-.352 1.645-.88c.09-.134-.063-.29-.205-.217a3.1 3.1 0 0 1-1.44.342");
}

.sqf03_p-t {
  stop-color: var(--svg-color--f8e6e8, #F8E6E8);
}

.stb_0w47k {
  fill: var(--svg-color--000, #000);
  d: path("M18.488 14.357c0-.295.236-.53.53-.53a.53.53 0 0 1 .473.775h-.94a.5.5 0 0 1-.063-.245");
}

.swka_j87x {
  d: path("M6.25 29.826c0-5.635 4.568-10.203 10.203-10.203h.64c5.636 0 10.204 4.568 10.204 10.203z");
}

.t-5nldk3g {
  cx: 16.761px;
  cy: 28.296px;
  r: 0.739px;
}

.t4clght5m {
  stop-color: var(--svg-color--ffce2c, #FFCE2C);
  stop-opacity: 0;
}

.t6q5npbfe {
  d: path("M19.845 14.235a.87.87 0 0 0-.24-.48l-.27.296l.121.237z");
}

.ta93jn_me {
  d: path("m13.677 20.005l.612 3.22h4.946l.796-3.173a10.2 10.2 0 0 0-2.937-.429h-.64c-.963 0-1.895.133-2.777.382");
}

.tg07-ljnl {
  stop-color: var(--svg-color--5e5764, #5E5764);
}

.tn_97qkdc {
  stop-color: var(--svg-color--f2c341, #F2C341);
  stop-opacity: 0;
}

.tpaawnlif {
  stop-color: var(--svg-color--ffa63f, #FFA63F);
  stop-opacity: 0;
}

.tsum8q2zl {
  stop-color: var(--svg-color--ffc339, #FFC339);
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

.u1gl_1zha {
  stop-color: var(--svg-color--ec4182, #EC4182);
  stop-opacity: 0;
}

.u2_b7w1wq {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.95 13.626c.067.088-.071.196-.228.314s-.274.2-.34.111c-.066-.088.008-.255.165-.373s.338-.14.404-.052");
}

.u5bjt8cdp {
  d: path("M6.803 17.694a.782.782 0 0 1 1.249-.941l.93 1.214c.337.438.519.975.519 1.527l-1.5-.18z");
}

.u6lph46no {
  stop-color: var(--svg-color--f0dff0, #F0DFF0);
}

.u86eruqic {
  d: path("m21.761 7.9l-.056 1.33c.781.389 1.73.167 1.562 1.11l-.614 3.16c-.054.326-.27.546-.594.554c.037-.523.071-1.368.085-1.501c.045-.45-.026-.583-.439-.994c-.223-.221-.39-.554-.39-.887v-.887c0-.277-.223-.5-.446-.555c-.67-.166-2.064-.443-4.071-.443c-2.008 0-3.402.277-4.071.443a.54.54 0 0 0-.446.555v.887c0 .333-.112.665-.39.887l-.168.167c-.223.166-.336.513-.336.79c.015.162.037 1.094.062 1.481a.66.66 0 0 1-.618-.552l-.614-3.161c-.111-.887.199-.386.98-.774c1.054-.462 1.574-2.552 2.422-3.274c.614-.554 1.506-.72 2.287-.333a3.06 3.06 0 0 0 1.728 0c.837-.277 1.785-.055 2.454.555l.837.832c.223.277.502.443.836.61");
}

.ugynyo-0t {
  d: path("m16.354 14.338l-.552 1.766a.56.56 0 0 0 .541.727h.817a.562.562 0 0 0 .541-.727l-.552-1.766c-.119-.391-.67-.391-.795 0");
}

.ujrq6ixuu {
  stop-color: var(--svg-color--beb4c6, #BEB4C6);
}

.ukqqiac9d {
  fill: var(--svg-color--fff, #fff);
  d: path("M19.233 13.147c.679 0 1.252.468 1.408 1.1a.285.285 0 0 1-.278.354h-2.318a.24.24 0 0 1-.236-.282a1.45 1.45 0 0 1 1.424-1.172");
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

.vgk5w_bmg {
  stop-color: var(--svg-color--ffc12e, #FFC12E);
}

.vke6kh8bt {
  stop-color: var(--svg-color--3e3843, #3E3843);
  stop-opacity: 0;
}

.vrar8hnmh {
  stop-color: var(--svg-color--faa416, #FAA416);
}

.vvfum-_fa {
  stop-color: var(--svg-color--392f42, #392F42);
}

.w4ea2bbjv {
  stop-color: var(--svg-color--efd8d5, #EFD8D5);
  stop-opacity: 0;
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

.waf9s5hfu {
  stop-color: var(--svg-color--ee911a, #EE911A);
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

.wn92vfpti {
  stop-color: var(--svg-color--ffce2c, #FFCE2C);
}

.wno2x162j {
  stop-color: var(--svg-color--eb8a1c, #EB8A1C);
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

.x1l7xqbyw {
  stop-color: var(--svg-color--de5534, #DE5534);
  stop-opacity: 0;
}

.x2u305zwp {
  stop-color: var(--svg-color--d19c3a, #D19C3A);
  stop-opacity: 0;
}

.x92j_kb4w {
  stop-color: var(--svg-color--d4c4da, #D4C4DA);
}

.xaad_wcir {
  stop-color: var(--svg-color--bb4f29, #BB4F29);
}

.xntzq-4ho {
  stop-color: var(--svg-color--8566b5, #8566B5);
}

.xvg5w_x2s {
  cx: 21.705px;
  cy: 14.634px;
  r: 1.034px;
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

.yap8h-69j {
  fill: var(--svg-color--fff, #fff);
  d: path("M14.263 13.147c-.679 0-1.252.468-1.408 1.1a.285.285 0 0 0 .278.354h2.319a.24.24 0 0 0 .236-.282a1.456 1.456 0 0 0-1.425-1.172");
}

.ykvv4rhnl {
  stop-color: var(--svg-color--ffc532, #FFC532);
}

.ym-b_m9fy {
  stop-color: var(--svg-color--d1bed4, #D1BED4);
  stop-opacity: 0;
}

.z9_ub4btj {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M16.752 17.889a3.1 3.1 0 0 1-1.44-.342c-.143-.072-.296.088-.206.218a1.97 1.97 0 0 0 1.646.879c.69 0 1.297-.352 1.645-.88c.09-.134-.063-.29-.205-.217a3.1 3.1 0 0 1-1.44.342Z");
}

.zdcorrl9x {
  cx: 26.234px;
  cy: 14.83px;
  r: 1.684px;
}

.zeffp9bvk {
  stop-color: var(--svg-color--f5a913, #F5A913);
}

.zjmwko4fr {
  stop-color: var(--svg-color--ffd069, #FFD069);
}

.zkyr435ek {
  fill-rule: evenodd;
  d: path("M14.9 11.972c-.748-.07-1.227.222-1.344.33a.49.49 0 1 1-.665-.722c.318-.294 1.072-.681 2.1-.585a.49.49 0 0 1-.09.977");
}

.zmosas2ke {
  stop-color: var(--svg-color--ffd709, #FFD709);
}

.zsx4vmb0f {
  stop-color: var(--svg-color--e07027, #E07027);
  stop-opacity: 0;
}

</style>
