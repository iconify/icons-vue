<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#inYhs0y)"><path fill="url(#iPYYWhe)" class="swka_j87x"/><path fill="url(#iT07jwd)" class="swka_j87x"/><path fill="url(#il5eVUq)" class="swka_j87x"/><path fill="url(#iY3yYtd)" class="swka_j87x"/><path fill="url(#iv8FoOX)" class="swka_j87x"/></g><circle fill="url(#iBZ0RUd)" class="hpfqe6rjh"/><circle fill="url(#itKlKTd)" class="hpfqe6rjh"/><circle fill="url(#ihlr5IT)" class="duyhuibwk"/><circle fill="url(#iGUmgWd)" class="duyhuibwk"/><circle fill="url(#iXhqZHd)" class="iwbygtbvw"/><circle fill="url(#iOHvRJe)" class="iwbygtbvw"/><circle fill="url(#issuNue)" class="zdcorrl9x"/><circle fill="url(#iMaLBhb)" class="zdcorrl9x"/><circle fill="url(#iAhrvZc)" class="zdcorrl9x"/><g filter="url(#iCkqeTb)"><circle fill="url(#iMk8UMb)" class="t-5nldk3g"/></g><g filter="url(#ivrmaPW)"><circle fill="url(#iR23Gge)" class="don2wdpjw"/></g><path fill="url(#i5YvaPc)" class="j70rp9pis"/><path fill="url(#iK84mBb)" class="j70rp9pis"/><path fill="url(#iWCiqKd)" class="j70rp9pis"/><path fill="url(#ieol8Me)" class="qy4rrcb8b"/><path fill="url(#iDbbcbc)" class="qy4rrcb8b"/><path fill="url(#iOe2zrd)" class="qy4rrcb8b"/><path fill="url(#iV71Rbc)" class="qy4rrcb8b"/><g filter="url(#iHpQAro)"><path fill="url(#iObplQb)" class="ggm3_setj"/><path fill="url(#iQpTAtb)" class="ggm3_setj"/></g><path fill="url(#ipodSkc)" class="f21vmbcik"/><path fill="url(#iXPTZOc)" class="f21vmbcik"/><path fill="url(#itP1zjc)" class="wp2p6dbcv"/><path fill="url(#i33ZCUz)" class="wp2p6dbcv"/><g filter="url(#islfX8c)"><path clip-rule="evenodd" class="byn6wubog"/></g><g filter="url(#imWTPpG)"><path fill="url(#iSAsI1d)" class="ctsppjbax"/><path fill="url(#iwtPTOo)" class="ctsppjbax"/><path fill="url(#isAdhHe)" class="ctsppjbax"/></g><g filter="url(#ikeaEsc)"><path fill="url(#ivLP6Gc)" class="ht6lpfbpp"/><path fill="url(#iXetYud)" class="ht6lpfbpp"/></g><g filter="url(#izq6v6b)"><path fill="url(#i8tJXGc)" class="ld_83jb7a"/><path fill="url(#iw9bnJb)" class="ld_83jb7a"/></g><g filter="url(#iNyA7td)"><path class="p4atghb8h"/></g><g filter="url(#i8WEgue)"><path class="ucq3z1bcr"/></g><g filter="url(#iTGdb4v)"><path class="sbbt-6b7n"/></g><g filter="url(#icJBrcd)"><path class="ay_tpr1ro"/></g><g filter="url(#iu8vAue)"><path class="xnf9zsbcq"/></g><path fill="url(#ilez79L)" class="hw860-bkw"/><path fill="url(#iSXBdIb)" class="hw860-bkw"/><path fill="url(#ib914xd)" class="hw860-bkw"/><g filter="url(#iFf0noc)"><path fill="url(#iq39nHd)" class="u5bjt8cdp"/></g><path fill="url(#iELdlqb)" clip-rule="evenodd" class="wfgw5ub6b"/><path fill="url(#iBqD1Xb)" clip-rule="evenodd" class="wfgw5ub6b"/><path fill="url(#iiItqld)" clip-rule="evenodd" class="d5_x4xk7i"/><path fill="url(#iGVyd2d)" clip-rule="evenodd" class="d5_x4xk7i"/><path fill="url(#i5nc0Sc)" clip-rule="evenodd" class="ctupw6b3d"/><path fill="url(#iQodSWd)" clip-rule="evenodd" class="ctupw6b3d"/><path fill="url(#iUzJ9JS)" clip-rule="evenodd" class="vdngsab5t"/><path fill="url(#iYRVChc)" clip-rule="evenodd" class="vdngsab5t"/><path fill="url(#iHc2wiw)" class="twba206ho"/><path fill="url(#idQamRc)" class="twba206ho"/><path fill="url(#ieGY6Vb)" class="lucypabyc"/><g filter="url(#i5ccbjd)"><path class="jgab0yb4f"/></g><g filter="url(#i2dZmcP)"><path class="fbmg84ypw"/></g><g filter="url(#i5F4WZd)"><path class="akrf-l3yi"/></g><g filter="url(#iISsHJe)"><path class="wzn2a8b8n"/></g><g filter="url(#iXK9R5d)"><path stroke="url(#ioZXgLe)" class="bdk4dmb5b"/></g><g filter="url(#itXh1ue)"><path stroke="url(#i4O2smb)" class="gwm_2mjil"/></g><g filter="url(#iZmhb0c)"><path stroke="url(#iz0d3ff)" class="y2ly1lryk"/></g><g filter="url(#iKbJZab)"><path stroke="url(#iJwKJNb)" class="am6k_ubte"/></g><g filter="url(#iqJlGAe)"><path stroke="url(#ivFlTre)" class="c549xi8ae"/></g><g filter="url(#iPzugRZ)"><circle fill="url(#igwpqvR)" class="bgzbsl_fh"/></g><circle fill="url(#ivJOcxs)" class="bgzbsl_fh"/><g filter="url(#igKFI3b)"><circle fill="url(#iYbsuEe)" class="u3v34c8wo"/></g><g filter="url(#idALyEe)"><circle fill="url(#i9u1XPb)" class="f295nnb9k"/><circle fill="url(#iCdlRNc)" class="f295nnb9k"/></g><g filter="url(#i9GovgN)"><circle class="lfw2icb2v"/><circle fill="url(#iM3qyOe)" class="t9eszom7h"/><circle fill="url(#itq2dOd)" class="t9eszom7h"/></g><g filter="url(#i0pLEyd)"><path fill="url(#iC7s22N)" class="kr900d0yh"/><path fill="url(#iTZClFb)" class="kr900d0yh"/><path fill="url(#ilIZEKe)" class="kr900d0yh"/></g><path fill="url(#inZAoie)" class="o3862mwmv"/><path fill="url(#izoJzdl)" class="o3862mwmv"/><path fill="url(#iFCncTk)" class="o3862mwmv"/><path fill="url(#icL2Avc)" class="o3862mwmv"/><g filter="url(#i8vsuVd)"><path class="bmf23ccsf"/><path fill="url(#iaK8adc)" class="ffsbscbfl"/><path fill="url(#iNWk5pd)" class="ffsbscbfl"/><path fill="url(#i3fDK8d)" class="ffsbscbfl"/><path fill="url(#i36RiCs)" class="ffsbscbfl"/></g><g filter="url(#ivcwPMd)"><path class="hochth35i"/></g><g filter="url(#iNknm3b)"><path class="f-at1e-1v"/><path fill="url(#i3szrEb)" class="ocqp4lspe"/><path fill="url(#iHEIc1c)" class="ocqp4lspe"/><path fill="url(#i8YUEfT)" class="ocqp4lspe"/><path fill="url(#iumzDnb)" class="ocqp4lspe"/></g><path fill="url(#iKRjoEd)" class="ocqp4lspe"/><path stroke="url(#iRtFkxf)" class="dhqq56zrt"/><g filter="url(#ipHG5Ad)"><path class="kalg6bc5c"/><path fill="url(#i1RLuwc)" class="m5_n77b4k"/></g><g filter="url(#iOYrq6b)"><path class="q6l4_694w"/><path fill="url(#iqIguJc)" class="bnnfsow1i"/></g><path class="iqrjx-_ld"/><path fill="url(#i5qCuze)" class="gkxlqf77y"/><path class="guua1rtkt"/><g filter="url(#iqj2mub)"><path class="gc5faqg1q"/><path fill="url(#iildUdd)" class="palsozbti"/></g><g filter="url(#iHr3AHb)"><path fill="url(#iStxL3J)" class="i4vnxm0ia"/></g><path class="v20j2nbso"/><path fill="url(#iuRDque)" class="dfayxa0qz"/><path class="lz4rb992v"/><g filter="url(#iphSYHb)"><path fill="url(#io5bt4c)" class="v-s78bb2b"/></g><g filter="url(#ibHr4zb)"><ellipse transform="rotate(-27.914 14.176 13.546)" class="th6oxbbzk"/><ellipse fill="url(#i4IqLYc)" transform="rotate(-27.914 14.176 13.546)" class="szi8mbi3d"/></g><g filter="url(#iMc6xVY)"><path stroke="url(#itNFNnJ)" class="tiqausb5g"/></g><g filter="url(#i8fymod)"><path stroke="url(#izK9fwe)" class="hc-r960kz"/></g><g filter="url(#i2hJMlR)"><path stroke="url(#iEi4K5c)" class="dznl_ubra"/></g><path fill="url(#iMwhdrV)" class="qzd219blo"/><path fill="url(#i3dSYhb)" class="qzd219blo"/><path fill="url(#inl9J2c)" class="qzd219blo"/><path fill="url(#iCE2gke)" class="wozepxbaa"/><path fill="url(#izP9Z9c)" class="wozepxbaa"/><rect fill="url(#iK2GSbd)" class="okwd93kys"/><rect fill="url(#iy7tjOa)" class="okwd93kys"/><rect fill="url(#iYE2hsb)" class="okwd93kys"/><defs><radialGradient id="iPYYWhe" cx="0" cy="0" r="1" gradientTransform="rotate(135.22 8.643 15.887)scale(12.9545 12.5552)" gradientUnits="userSpaceOnUse"><stop offset=".195" class="m-1-e5bla"/><stop offset=".794" class="b057dp4eh"/></radialGradient><radialGradient id="iT07jwd" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.09375 -3.28125 0 20.219 20.139)" gradientUnits="userSpaceOnUse"><stop class="m9gf32bwp"/><stop offset="1" class="n297mkbnr"/></radialGradient><radialGradient id="il5eVUq" cx="0" cy="0" r="1" gradientTransform="matrix(-1.75 0 0 -11.7187 21 25.92)" gradientUnits="userSpaceOnUse"><stop offset=".214" class="demkpcl0k"/><stop offset="1" class="ym-b_m9fy"/></radialGradient><radialGradient id="iY3yYtd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.15625 0 0 -5.75902 11.656 25.326)" gradientUnits="userSpaceOnUse"><stop class="ujrq6ixuu"/><stop offset="1" class="h4mko5b9o"/></radialGradient><radialGradient id="iv8FoOX" cx="0" cy="0" r="1" gradientTransform="matrix(2.12502 5.34374 -11.023 4.38346 13.099 18.733)" gradientUnits="userSpaceOnUse"><stop class="nl0wbpawx"/><stop offset="1" class="jm40s5baz"/></radialGradient><radialGradient id="iBZ0RUd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.34375 2.4375 -2.36069 -1.3014 7.187 11.826)" gradientUnits="userSpaceOnUse"><stop offset=".077" class="l-r9gxb9g"/><stop offset="1" class="hcmh5c50b"/></radialGradient><radialGradient id="itKlKTd" cx="0" cy="0" r="1" gradientTransform="rotate(115.145 -.151 8.247)scale(3.38309 2.95533)" gradientUnits="userSpaceOnUse"><stop offset=".452" class="y-1rsmdul"/><stop offset=".826" class="af8mzdbwl"/></radialGradient><radialGradient id="ihlr5IT" cx="0" cy="0" r="1" gradientTransform="matrix(-1.34375 2.4375 -2.36069 -1.3014 10.101 2.846)" gradientUnits="userSpaceOnUse"><stop offset=".077" class="mpwbs5b3u"/><stop offset="1" class="fzq016boz"/></radialGradient><radialGradient id="iGUmgWd" cx="0" cy="0" r="1" gradientTransform="rotate(115.145 4.158 4.683)scale(3.38309 2.95533)" gradientUnits="userSpaceOnUse"><stop offset=".452" class="x1l7xqbyw"/><stop offset=".826" class="ng1cexbhj"/></radialGradient><radialGradient id="iXhqZHd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.34375 2.4375 -2.36069 -1.3014 26.066 3.861)" gradientUnits="userSpaceOnUse"><stop offset=".077" class="lelj2r8dg"/><stop offset="1" class="fde_fwzpt"/></radialGradient><radialGradient id="iOHvRJe" cx="0" cy="0" r="1" gradientTransform="rotate(105.03 11.36 11.751)scale(3.49455 3.40391)" gradientUnits="userSpaceOnUse"><stop offset=".375" class="ppr920emc"/><stop offset=".826" class="y_auwli2s"/></radialGradient><radialGradient id="issuNue" cx="0" cy="0" r="1" gradientTransform="matrix(-1.34375 2.4375 -2.36069 -1.3014 27.09 13.818)" gradientUnits="userSpaceOnUse"><stop offset=".077" class="y05rrkbkk"/><stop offset="1" class="a5zzorbzd"/></radialGradient><radialGradient id="iMaLBhb" cx="0" cy="0" r="1" gradientTransform="matrix(1 1.07812 -1.5877 1.47265 24.969 13.357)" gradientUnits="userSpaceOnUse"><stop class="i8j0jyb4u"/><stop offset="1" class="d7caiobkz"/></radialGradient><radialGradient id="iAhrvZc" cx="0" cy="0" r="1" gradientTransform="rotate(109.11 8.51 16.52)scale(3.46022 3.37046)" gradientUnits="userSpaceOnUse"><stop offset=".347" class="tn_97qkdc"/><stop offset=".829" class="mmq2utbuk"/></radialGradient><radialGradient id="iMk8UMb" cx="0" cy="0" r="1" gradientTransform="matrix(-.7578 1.14063 -.96756 -.64282 17.25 27.855)" gradientUnits="userSpaceOnUse"><stop offset=".212" class="u6lph46no"/><stop offset="1" class="bq5dgsbba"/></radialGradient><radialGradient id="iR23Gge" cx="0" cy="0" r="1" gradientTransform="matrix(-.7578 1.14063 -.96756 -.64282 17.25 25.842)" gradientUnits="userSpaceOnUse"><stop offset=".212" class="u6lph46no"/><stop offset="1" class="bq5dgsbba"/></radialGradient><radialGradient id="i5YvaPc" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.03125 -2.40212 0 22.222 20.983)" gradientUnits="userSpaceOnUse"><stop class="koq0r9bvu"/><stop offset="1" class="dpmuo-biy"/></radialGradient><radialGradient id="ieol8Me" cx="0" cy="0" r="1" gradientTransform="scale(1.38818 6.1875)rotate(90 2.761 6.5)" gradientUnits="userSpaceOnUse"><stop class="xntzq-4ho"/><stop offset="1" class="pt8frltpn"/></radialGradient><radialGradient id="iDbbcbc" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.25 -.60938 0 13.062 24.108)" gradientUnits="userSpaceOnUse"><stop class="wshx69b-y"/><stop offset="1" class="aqzyd8bsb"/></radialGradient><radialGradient id="iOe2zrd" cx="0" cy="0" r="1" gradientTransform="matrix(2.9375 -7.98881 7.06186 2.59666 10.312 28.264)" gradientUnits="userSpaceOnUse"><stop offset=".724" class="lgi0lwbjz"/><stop offset="1" class="tvoyviyhj"/></radialGradient><radialGradient id="iV71Rbc" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.42188 -.18506 0 12.857 21.717)" gradientUnits="userSpaceOnUse"><stop class="m5avsc_ef"/><stop offset="1" class="ci3gi1b_k"/></radialGradient><radialGradient id="iObplQb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.90624 2.42972 -4.28692 -6.89204 19.266 20.795)" gradientUnits="userSpaceOnUse"><stop class="ku63lg_wt"/><stop offset="1" class="i1-orb7ke"/></radialGradient><radialGradient id="iQpTAtb" cx="0" cy="0" r="1" gradientTransform="matrix(-.46875 -.125 .54686 -2.05079 19.188 22.482)" gradientUnits="userSpaceOnUse"><stop offset=".108" class="qsu4qbckq"/><stop offset="1" class="gr0wzobbs"/></radialGradient><radialGradient id="iSAsI1d" cx="0" cy="0" r="1" gradientTransform="matrix(1.73878 1.3451 -1.47727 1.90964 13.775 23.358)" gradientUnits="userSpaceOnUse"><stop class="ab6i82btp"/><stop offset="1" class="pb6efmson"/></radialGradient><radialGradient id="iwtPTOo" cx="0" cy="0" r="1" gradientTransform="matrix(-1.68958 -.4774 .79459 -2.81214 15.416 23.836)" gradientUnits="userSpaceOnUse"><stop offset=".69" class="sawf8hb2n"/><stop offset="1" class="o415o878f"/></radialGradient><radialGradient id="isAdhHe" cx="0" cy="0" r="1" gradientTransform="matrix(-.5 1.58457 -.75053 -.23683 16.11 23.836)" gradientUnits="userSpaceOnUse"><stop class="btor07b8q"/><stop offset="1" class="jjf293xlz"/></radialGradient><radialGradient id="ivLP6Gc" cx="0" cy="0" r="1" gradientTransform="rotate(142.275 5.895 15.056)scale(2.19833 2.41434)" gradientUnits="userSpaceOnUse"><stop class="auvn9fbbk"/><stop offset="1" class="h2li0wblg"/></radialGradient><radialGradient id="iXetYud" cx="0" cy="0" r="1" gradientTransform="matrix(1.68958 -.4774 .79459 2.81214 18.13 23.836)" gradientUnits="userSpaceOnUse"><stop offset=".69" class="sawf8hb2n"/><stop offset="1" class="o415o878f"/></radialGradient><radialGradient id="iw9bnJb" cx="0" cy="0" r="1" gradientTransform="matrix(-.39136 0 0 -2.59279 17.54 23.592)" gradientUnits="userSpaceOnUse"><stop class="scbqttb8d"/><stop offset="1" class="u1gl_1zha"/></radialGradient><radialGradient id="ilez79L" cx="0" cy="0" r="1" gradientTransform="matrix(-4.375 1.44046 -1.3893 -4.21963 28.098 22.456)" gradientUnits="userSpaceOnUse"><stop offset=".241" class="va-8to-0f"/><stop offset="1" class="ljv0l9wbv"/></radialGradient><radialGradient id="iSXBdIb" cx="0" cy="0" r="1" gradientTransform="rotate(163.091 11.838 12.97)scale(3.90165 13.4872)" gradientUnits="userSpaceOnUse"><stop offset=".699" class="smnqffnel"/><stop offset="1" class="jknxnjb8w"/></radialGradient><radialGradient id="ib914xd" cx="0" cy="0" r="1" gradientTransform="rotate(77.963 .104 26.074)scale(1.04894 5.75403)" gradientUnits="userSpaceOnUse"><stop offset=".134" class="s3rfzh4ga"/><stop offset="1" class="aewjbccqi"/></radialGradient><radialGradient id="iq39nHd" cx="0" cy="0" r="1" gradientTransform="rotate(139.97 1.2 10.48)scale(1.53045 3.638)" gradientUnits="userSpaceOnUse"><stop offset=".129" class="b1xnaurjw"/><stop offset="1" class="xvexp0bjq"/></radialGradient><radialGradient id="iELdlqb" cx="0" cy="0" r="1" gradientTransform="matrix(-.79386 1.27188 -2.4349 -1.51978 6.442 17.553)" gradientUnits="userSpaceOnUse"><stop class="mug1r-bxu"/><stop offset="1" class="uck8wqbzl"/></radialGradient><radialGradient id="iBqD1Xb" cx="0" cy="0" r="1" gradientTransform="matrix(-.73037 2.48832 -3.82658 -1.12318 6.977 17.288)" gradientUnits="userSpaceOnUse"><stop offset=".579" class="qpmxtnavh"/><stop offset=".954" class="sjxmvib4j"/></radialGradient><radialGradient id="iiItqld" cx="0" cy="0" r="1" gradientTransform="rotate(116.602 -3.017 10.55)scale(1.58621 2.70684)" gradientUnits="userSpaceOnUse"><stop class="mug1r-bxu"/><stop offset="1" class="uck8wqbzl"/></radialGradient><radialGradient id="iGVyd2d" cx="0" cy="0" r="1" gradientTransform="matrix(-.65347 2.77477 -3.52334 -.82977 5.545 17.677)" gradientUnits="userSpaceOnUse"><stop offset=".579" class="qpmxtnavh"/><stop offset=".954" class="sjxmvib4j"/></radialGradient><radialGradient id="i5nc0Sc" cx="0" cy="0" r="1" gradientTransform="matrix(-.68468 1.22288 -2.2217 -1.2439 4.939 18.947)" gradientUnits="userSpaceOnUse"><stop class="mug1r-bxu"/><stop offset="1" class="uck8wqbzl"/></radialGradient><radialGradient id="iQodSWd" cx="0" cy="0" r="1" gradientTransform="rotate(104.751 -4.503 11.427)scale(2.474 3.46652)" gradientUnits="userSpaceOnUse"><stop offset=".579" class="qpmxtnavh"/><stop offset=".954" class="sjxmvib4j"/></radialGradient><radialGradient id="iUzJ9JS" cx="0" cy="0" r="1" gradientTransform="rotate(122.692 -2.834 11.406)scale(1.24393 2.40994)" gradientUnits="userSpaceOnUse"><stop class="mug1r-bxu"/><stop offset="1" class="uck8wqbzl"/></radialGradient><radialGradient id="iYRVChc" cx="0" cy="0" r="1" gradientTransform="matrix(-.61813 2.04813 -3.22394 -.973 5.687 19.733)" gradientUnits="userSpaceOnUse"><stop offset=".579" class="qpmxtnavh"/><stop offset=".954" class="sjxmvib4j"/></radialGradient><radialGradient id="iHc2wiw" cx="0" cy="0" r="1" gradientTransform="rotate(-162.011 6.48 10.137)scale(3.69324 5.10277)" gradientUnits="userSpaceOnUse"><stop class="qq8pp_7zq"/><stop offset=".482" class="blko_hazg"/></radialGradient><radialGradient id="idQamRc" cx="0" cy="0" r="1" gradientTransform="matrix(.07812 -.82813 3.88844 .36683 6.156 21.78)" gradientUnits="userSpaceOnUse"><stop class="jwq5cabxr"/><stop offset="1" class="yt9en_n3k"/></radialGradient><radialGradient id="ieGY6Vb" cx="0" cy="0" r="1" gradientTransform="rotate(53.51 -11.908 25.833)scale(3.1004 3.53574)" gradientUnits="userSpaceOnUse"><stop offset=".438" class="exfuzbt0n"/><stop offset="1" class="w4ky7s-1q"/></radialGradient><radialGradient id="igwpqvR" cx="0" cy="0" r="1" gradientTransform="matrix(1.84203 0 0 3.22357 10.018 14.363)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="n91c-gs8j"/><stop offset="1" class="qo7u-3bcf"/></radialGradient><radialGradient id="ivJOcxs" cx="0" cy="0" r="1" gradientTransform="rotate(-124.98 10.081 4.993)scale(1.73903)" gradientUnits="userSpaceOnUse"><stop offset=".34" class="ev4-2pfvs"/><stop offset="1" class="w_j-6pbpp"/></radialGradient><radialGradient id="iCdlRNc" cx="0" cy="0" r="1" gradientTransform="matrix(.86777 -.63187 .7212 .99044 22.146 14.085)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="cu-ecjbbc"/><stop offset="1" class="a1ftncccj"/></radialGradient><radialGradient id="iM3qyOe" cx="0" cy="0" r="1" gradientTransform="matrix(.86205 -1.58556 .92803 .50456 21.712 15.224)" gradientUnits="userSpaceOnUse"><stop offset=".755" class="d66ufbbtl"/><stop offset=".916" class="f7hwkw-sq"/></radialGradient><radialGradient id="itq2dOd" cx="0" cy="0" r="1" gradientTransform="matrix(.27217 .2694 -.3473 .35086 21.756 14.362)" gradientUnits="userSpaceOnUse"><stop class="suj-pjbhk"/><stop offset="1" class="dg9o8ubcl"/></radialGradient><radialGradient id="iTZClFb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.372 1.68862 0 19.216 13.028)" gradientUnits="userSpaceOnUse"><stop class="e6v6vrbif"/><stop offset="1" class="qmnjff_ag"/></radialGradient><radialGradient id="ilIZEKe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.44236 1.79371 0 14.432 13.168)" gradientUnits="userSpaceOnUse"><stop class="c02-eqbxv"/><stop offset="1" class="mmmkqcbgq"/></radialGradient><radialGradient id="iFCncTk" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.74212 -10.8353 0 16.619 12.753)" gradientUnits="userSpaceOnUse"><stop offset=".608" class="jdb29wbxt"/><stop offset=".954" class="v-g8l9b4g"/></radialGradient><radialGradient id="iaK8adc" cx="0" cy="0" r="1" gradientTransform="matrix(.83744 -3.10348 1.15087 .31055 21.315 10.053)" gradientUnits="userSpaceOnUse"><stop class="ki2rd4v4k"/><stop offset="1" class="tp9jx5j2y"/></radialGradient><radialGradient id="iNWk5pd" cx="0" cy="0" r="1" gradientTransform="matrix(4.01482 .36946 -.19866 2.15874 19.59 8.205)" gradientUnits="userSpaceOnUse"><stop offset=".392" class="je_aabb8l"/><stop offset="1" class="ivhsfvmdg"/></radialGradient><radialGradient id="i3fDK8d" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.76258 -2.72974 0 16.754 5.334)" gradientUnits="userSpaceOnUse"><stop class="n7o-m0b5s"/><stop offset="1" class="xp-9f0bqu"/></radialGradient><radialGradient id="i36RiCs" cx="0" cy="0" r="1" gradientTransform="rotate(-36.235 24.08 -9.013)scale(4.00028 6.26713)" gradientUnits="userSpaceOnUse"><stop class="ux7-g74jy"/><stop offset="1" class="dd8hfetks"/></radialGradient><radialGradient id="iumzDnb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .20668 -.66401 0 17.097 16.049)" gradientUnits="userSpaceOnUse"><stop class="mifq-tdon"/><stop offset="1" class="n-ko-_w7d"/></radialGradient><radialGradient id="i1RLuwc" cx="0" cy="0" r="1" gradientTransform="matrix(.10937 -.63323 1.87336 .32356 19.318 12.175)" gradientUnits="userSpaceOnUse"><stop class="fr4wpbo2m"/><stop offset="1" class="xo-sv8bhm"/></radialGradient><radialGradient id="iqIguJc" cx="0" cy="0" r="1" gradientTransform="rotate(-80.2 14.186 -2.175)scale(.64261 1.9012)" gradientUnits="userSpaceOnUse"><stop class="fr4wpbo2m"/><stop offset="1" class="xo-sv8bhm"/></radialGradient><radialGradient id="i5qCuze" cx="0" cy="0" r="1" gradientTransform="matrix(0 .85142 -1.35428 0 19.04 13.647)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iildUdd" cx="0" cy="0" r="1" gradientTransform="matrix(-.24338 -.31363 .4318 -.33508 18.801 13.735)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iuRDque" cx="0" cy="0" r="1" gradientTransform="matrix(0 .85146 -1.35435 0 14.461 13.647)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="i4IqLYc" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 13.91 -.032)scale(.51857 .62334)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iMwhdrV" cx="0" cy="0" r="1" gradientTransform="matrix(-5.5 4.12501 -3.615 -4.82 20.719 4.576)" gradientUnits="userSpaceOnUse"><stop offset=".179" class="tg07-ljnl"/><stop offset="1" class="c6833cb9x"/></radialGradient><radialGradient id="i3dSYhb" cx="0" cy="0" r="1" gradientTransform="matrix(2.875 .375 -.58342 4.4729 10.781 7.701)" gradientUnits="userSpaceOnUse"><stop class="j8k1fac_p"/><stop offset="1" class="g8uem1b5g"/></radialGradient><radialGradient id="inl9J2c" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.875 8.03906 0 16.773 8.326)" gradientUnits="userSpaceOnUse"><stop offset=".761" class="km6q7kb1a"/><stop offset="1" class="i8skpb2jz"/></radialGradient><radialGradient id="iCE2gke" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.47656 -8.28125 0 18.406 7.912)" gradientUnits="userSpaceOnUse"><stop class="kzuil_5zu"/><stop offset="1" class="ok2r3obil"/></radialGradient><radialGradient id="iK2GSbd" cx="0" cy="0" r="1" gradientTransform="matrix(-7.1875 0 0 -.63281 21.268 9.87)" gradientUnits="userSpaceOnUse"><stop class="w63qn2bkh"/><stop offset="1" class="vvfum-_fa"/></radialGradient><radialGradient id="iy7tjOa" cx="0" cy="0" r="1" gradientTransform="matrix(3.48438 0 0 2.01172 9.003 10.109)" gradientUnits="userSpaceOnUse"><stop class="gfrsedb9v"/><stop offset="1" class="vke6kh8bt"/></radialGradient><filter id="inYhs0y" width="21.247" height="10.303" x="6.25" y="19.623" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.615686 0 0 0 0 0.607843 0 0 0 0 0.619608 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23854"/></filter><filter id="iCkqeTb" width="2.078" height="2.078" x="15.622" y="27.457" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.792157 0 0 0 0 0.717647 0 0 0 0 0.788235 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_3987_23854"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_3987_23854" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.831373 0 0 0 0 0.745098 0 0 0 0 0.803922 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_3987_23854"/></filter><filter id="ivrmaPW" width="2.078" height="2.078" x="15.622" y="25.444" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.792157 0 0 0 0 0.717647 0 0 0 0 0.788235 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_3987_23854"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_3987_23854" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.831373 0 0 0 0 0.745098 0 0 0 0 0.803922 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_3987_23854"/></filter><filter id="iHpQAro" width="6.554" height="3.702" x="13.38" y="19.523" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.721569 0 0 0 0 0.682353 0 0 0 0 0.74902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23854"/></filter><filter id="islfX8c" width="7.432" height="4.46" x="12.567" y="22.084" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23854" stdDeviation=".5"/></filter><filter id="imWTPpG" width="2.672" height="2.865" x="13.611" y="22.403" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.780392 0 0 0 0 0.270588 0 0 0 0 0.396078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23854"/></filter><filter id="ikeaEsc" width="2.672" height="2.865" x="17.264" y="22.403" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.780392 0 0 0 0 0.270588 0 0 0 0 0.396078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23854"/></filter><filter id="izq6v6b" width="1.554" height="1.999" x="15.986" y="22.812" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.827451 0 0 0 0 0.137255 0 0 0 0 0.317647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23854"/></filter><filter id="iNyA7td" width="4.764" height="4.766" x="24.75" y="19.349" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.1"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.552941 0 0 0 0 0.364706 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23854"/></filter><filter id="i8WEgue" width="2.077" height="3.844" x="25.907" y="17.448" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.588235 0 0 0 0 0.403922 0 0 0 0 0.403922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23854"/></filter><filter id="iTGdb4v" width="2.401" height="4.052" x="24.436" y="17.107" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.588235 0 0 0 0 0.403922 0 0 0 0 0.403922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23854"/></filter><filter id="icJBrcd" width="2.312" height="4.044" x="23.386" y="17.96" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.588235 0 0 0 0 0.403922 0 0 0 0 0.403922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23854"/></filter><filter id="iu8vAue" width="2.123" height="3.114" x="22.394" y="19.041" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.588235 0 0 0 0 0.403922 0 0 0 0 0.403922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23854"/></filter><filter id="iFf0noc" width="3.002" height="3.147" x="6.649" y="16.347" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.537255 0 0 0 0 0.360784 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23854"/></filter><filter id="i5ccbjd" width="1.264" height="2.491" x="22.908" y="19.19" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23854" stdDeviation=".125"/></filter><filter id="i2dZmcP" width="1.286" height="2.978" x="23.932" y="18.124" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23854" stdDeviation=".125"/></filter><filter id="i5F4WZd" width="1.444" height="3.775" x="24.962" y="17.226" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23854" stdDeviation=".125"/></filter><filter id="iISsHJe" width="1.17" height="3.014" x="26.424" y="17.706" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23854" stdDeviation=".125"/></filter><filter id="iXK9R5d" width="1.788" height="2.6" x="27.33" y="19.87" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23854" stdDeviation=".125"/></filter><filter id="itXh1ue" width="2.323" height="1.69" x="3.752" y="19.44" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23854" stdDeviation=".125"/></filter><filter id="iZmhb0c" width="2.342" height="2.022" x="3.291" y="18.151" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23854" stdDeviation=".125"/></filter><filter id="iKbJZab" width="2.131" height="2.124" x="4.556" y="16.714" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23854" stdDeviation=".125"/></filter><filter id="iqJlGAe" width="2.569" height="2.444" x="3.345" y="17.042" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23854" stdDeviation=".125"/></filter><filter id="iPzugRZ" width="3.705" height="3.505" x="10.018" y="12.61" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.619608 0 0 0 0 0.470588 0 0 0 0 0.407843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23854"/></filter><filter id="igKFI3b" width="3.089" height="3.089" x="10.226" y="12.818" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23854" stdDeviation=".25"/></filter><filter id="idALyEe" width="3.755" height="3.755" x="20.003" y="12.36" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.584314 0 0 0 0 0.368627 0 0 0 0 0.470588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23854"/></filter><filter id="i9GovgN" width="3.089" height="3.089" x="20.211" y="12.818" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23854" stdDeviation=".25"/></filter><filter id="i0pLEyd" width="10.889" height="12.775" x="11.339" y="8.459" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.305882 0 0 0 0 0.2 0 0 0 0 0.172549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23854"/></filter><filter id="i8vsuVd" width="13.21" height="8.943" x="10.143" y="4.834" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.207843 0 0 0 0 0.109804 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23854"/></filter><filter id="ivcwPMd" width="3.347" height="4.314" x="14.829" y="13.188" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23854" stdDeviation=".375"/></filter><filter id="iNknm3b" width="2.47" height="3.314" x="15.518" y="13.517" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23854" stdDeviation=".125"/></filter><filter id="ipHG5Ad" width="3.115" height="1.946" x="17.994" y="10.552" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.156863 0 0 0 0 0.152941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23854"/></filter><filter id="iOYrq6b" width="3.115" height="1.946" x="12.591" y="10.552" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.156863 0 0 0 0 0.152941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23854"/></filter><filter id="iqj2mub" width=".816" height=".721" x="18.275" y="13.19" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23854" stdDeviation=".05"/></filter><filter id="iHr3AHb" width=".916" height=".939" x="19.162" y="13.274" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23854" stdDeviation=".1"/></filter><filter id="iphSYHb" width="1.015" height="1.072" x="14.499" y="13.207" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23854" stdDeviation=".1"/></filter><filter id="ibHr4zb" width=".948" height=".729" x="13.702" y="13.181" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23854" stdDeviation=".05"/></filter><filter id="iMc6xVY" width="3.191" height="1.702" x="17.871" y="10.696" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23854" stdDeviation=".25"/></filter><filter id="i8fymod" width="3.273" height="1.762" x="12.393" y="10.762" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23854" stdDeviation=".25"/></filter><filter id="i2hJMlR" width="1.021" height="2.345" x="11.35" y="8.937" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23854" stdDeviation=".125"/></filter><linearGradient id="iK84mBb" x1="22.562" x2="21.812" y1="29.826" y2="29.826" gradientUnits="userSpaceOnUse"><stop class="fr__qmhjc"/><stop offset="1" class="gypp10kih"/></linearGradient><linearGradient id="iWCiqKd" x1="20.644" x2="21.062" y1="29.014" y2="29.014" gradientUnits="userSpaceOnUse"><stop class="hj-s-zboe"/><stop offset="1" class="s0umluqbl"/></linearGradient><linearGradient id="ipodSkc" x1="9.531" x2="4.906" y1="27.451" y2="27.451" gradientUnits="userSpaceOnUse"><stop class="sb-ednb_a"/><stop offset="1" class="v0501vbqa"/></linearGradient><linearGradient id="iXPTZOc" x1="9.75" x2="8.828" y1="27.076" y2="27.076" gradientUnits="userSpaceOnUse"><stop class="o_30au2yc"/><stop offset="1" class="c60cvac3k"/></linearGradient><linearGradient id="itP1zjc" x1="27.871" x2="22.844" y1="28.142" y2="28.142" gradientUnits="userSpaceOnUse"><stop class="i7zyuv8vr"/><stop offset=".907" class="qzhltkbuo"/></linearGradient><linearGradient id="i33ZCUz" x1="28.09" x2="27.168" y1="27.876" y2="27.876" gradientUnits="userSpaceOnUse"><stop class="tub8lbbfx"/><stop offset="1" class="bd09vtb_c"/></linearGradient><linearGradient id="i8tJXGc" x1="16.763" x2="16.763" y1="22.812" y2="24.81" gradientUnits="userSpaceOnUse"><stop offset=".351" class="gzsz7evmk"/><stop offset="1" class="smgiue0gi"/></linearGradient><linearGradient id="ioZXgLe" x1="29.13" x2="28.38" y1="20.034" y2="21.659" gradientUnits="userSpaceOnUse"><stop class="zrsmq2u6o"/><stop offset="1" class="mcp_a12ev"/><stop offset="1" class="qg7eszk4c"/></linearGradient><linearGradient id="i4O2smb" x1="4.76" x2="5.331" y1="20.169" y2="21.223" gradientUnits="userSpaceOnUse"><stop class="m0zt7_pbu"/><stop offset="1" class="s9u0fjbul"/></linearGradient><linearGradient id="iz0d3ff" x1="4.307" x2="5.218" y1="19" y2="20.223" gradientUnits="userSpaceOnUse"><stop class="m0zt7_pbu"/><stop offset="1" class="s9u0fjbul"/></linearGradient><linearGradient id="iJwKJNb" x1="5.489" x2="6.52" y1="17.6" y2="18.693" gradientUnits="userSpaceOnUse"><stop class="m0zt7_pbu"/><stop offset="1" class="s9u0fjbul"/></linearGradient><linearGradient id="ivFlTre" x1="4.452" x2="5.734" y1="18.044" y2="19.502" gradientUnits="userSpaceOnUse"><stop class="m0zt7_pbu"/><stop offset="1" class="s9u0fjbul"/></linearGradient><linearGradient id="iYbsuEe" x1="11.77" x2="11.098" y1="14.655" y2="14.655" gradientUnits="userSpaceOnUse"><stop class="vo9agqbnp"/><stop offset="1" class="fwwugibmc"/></linearGradient><linearGradient id="i9u1XPb" x1="22.896" x2="22.037" y1="13.217" y2="15.879" gradientUnits="userSpaceOnUse"><stop class="ix2ytv1nc"/><stop offset="1" class="sla6kib8v"/></linearGradient><linearGradient id="iC7s22N" x1="20.99" x2="12.974" y1="14.771" y2="15.966" gradientUnits="userSpaceOnUse"><stop class="f43nfdclv"/><stop offset="1" class="ixdockwro"/></linearGradient><linearGradient id="inZAoie" x1="11.09" x2="13.065" y1="17.601" y2="17.531" gradientUnits="userSpaceOnUse"><stop class="xaj4s_mqh"/><stop offset="1" class="nzdq87b8k"/></linearGradient><linearGradient id="izoJzdl" x1="21.919" x2="20.751" y1="16.718" y2="16.616" gradientUnits="userSpaceOnUse"><stop class="mxfqo-b2y"/><stop offset="1" class="z8_150olp"/></linearGradient><linearGradient id="icL2Avc" x1="16.784" x2="16.784" y1="10.373" y2="12.115" gradientUnits="userSpaceOnUse"><stop offset=".256" class="t4hztoa1h"/><stop offset="1" class="rg60sduho"/></linearGradient><linearGradient id="i3szrEb" x1="15.846" x2="16.831" y1="15.463" y2="15.463" gradientUnits="userSpaceOnUse"><stop class="brzpz-p3w"/><stop offset="1" class="qxphtrj0e"/></linearGradient><linearGradient id="iHEIc1c" x1="17.738" x2="16.662" y1="15.802" y2="15.786" gradientUnits="userSpaceOnUse"><stop class="hcuo1obkg"/><stop offset="1" class="soj01hbui"/></linearGradient><linearGradient id="i8YUEfT" x1="16.958" x2="16.958" y1="16.581" y2="15.979" gradientUnits="userSpaceOnUse"><stop class="xk94moblk"/><stop offset="1" class="v1vf9kb3x"/></linearGradient><linearGradient id="iKRjoEd" x1="16.885" x2="16.885" y1="16.625" y2="16.449" gradientUnits="userSpaceOnUse"><stop class="kpt7nxbeg"/><stop offset="1" class="c70lx944e"/></linearGradient><linearGradient id="iRtFkxf" x1="15.665" x2="16.122" y1="18.276" y2="17.555" gradientUnits="userSpaceOnUse"><stop class="ssfga94sp"/><stop offset=".663" class="t-wcrfbaw"/></linearGradient><linearGradient id="iStxL3J" x1="19.857" x2="19.528" y1="13.703" y2="13.906" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="io5bt4c" x1="15.242" x2="14.912" y1="13.703" y2="13.906" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="itNFNnJ" x1="19.873" x2="19.432" y1="11.457" y2="10.556" gradientUnits="userSpaceOnUse"><stop class="bac636b7w"/><stop offset="1" class="eqzjb1bwj"/></linearGradient><linearGradient id="izK9fwe" x1="14.306" x2="13.057" y1="11.323" y2="10.8" gradientUnits="userSpaceOnUse"><stop class="bac636b7w"/><stop offset="1" class="eqzjb1bwj"/></linearGradient><linearGradient id="iEi4K5c" x1="11.86" x2="11.86" y1="9.208" y2="11.473" gradientUnits="userSpaceOnUse"><stop offset=".228" class="zw2ljvb-t"/><stop offset="1" class="ohs50t_5m"/></linearGradient><linearGradient id="izP9Z9c" x1="16.773" x2="16.773" y1="7.912" y2="8.1" gradientUnits="userSpaceOnUse"><stop class="jhlen960d"/><stop offset="1" class="wjchuwb6a"/></linearGradient><linearGradient id="iYE2hsb" x1="17.956" x2="17.956" y1="10.98" y2="10.214" gradientUnits="userSpaceOnUse"><stop class="bl3fq0x9z"/><stop offset="1" class="lxo7c2i6k"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-juggling-medium" /></template>
<style>
.a1ftncccj {
  stop-color: var(--svg-color--8f6459, #8F6459);
  stop-opacity: 0;
}

.a5zzorbzd {
  stop-color: var(--svg-color--e1ac3a, #E1AC3A);
}

.ab6i82btp {
  stop-color: var(--svg-color--e7377c, #E7377C);
}

.aewjbccqi {
  stop-color: var(--svg-color--a27671, #A27671);
  stop-opacity: 0;
}

.af8mzdbwl {
  stop-color: var(--svg-color--5f679a, #5F679A);
}

.akrf-l3yi {
  stroke: var(--svg-color--b69386, #B69386);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-35px, 0.35px);
  d: path("m25.388 17.65l.593 2.926");
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

.ay_tpr1ro {
  fill: var(--svg-color--ab8178, #AB8178);
  d: path("M23.407 18.803a.679.679 0 1 1 1.323-.298l.555 2.766a.613.613 0 0 1-1.195.27z");
}

.b057dp4eh {
  stop-color: var(--svg-color--ccbdde, #CCBDDE);
}

.b1xnaurjw {
  stop-color: var(--svg-color--b38f7a, #B38F7A);
}

.bac636b7w {
  stop-color: var(--svg-color--5b4545, #5B4545);
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

.bgzbsl_fh {
  cx: 11.77px;
  cy: 14.363px;
  r: 1.752px;
}

.bl3fq0x9z {
  stop-color: var(--svg-color--543459, #543459);
}

.blko_hazg {
  stop-color: var(--svg-color--a6846b, #A6846B);
}

.bmf23ccsf {
  fill: var(--svg-color--4f3332, #4F3332);
  d: path("M21.812 7.563V9.3c.788.392 1.69-.227 1.52.725l-.62 3.191c-.054.33-.272.552-.6.56h-.018s.056-.952.112-1.511c.046-.455-.033-.594-.45-1.008c-.225-.224-.394-.56-.394-.896v-.896c0-.28-.226-.503-.45-.56c-.676-.167-2.084-.447-4.111-.447s-3.434.28-4.11.448a.546.546 0 0 0-.45.56v.895c0 .336-.113.672-.395.896l-.169.168c-.225.168-.337.504-.337.784c.056.615.112 1.511.112 1.511l-.051-.002a.665.665 0 0 1-.624-.558l-.62-3.19c-.112-.897.455-.113 1.244-.505l.333-1.903a8 8 0 0 0 .844-.616l1.014-1.064c.62-.56 1.52-.727 2.308-.335a3.1 3.1 0 0 0 1.746 0c.844-.28 1.801-.056 2.477.56l.845.84c.225.279.506.447.844.615");
}

.bnnfsow1i {
  d: path("M12.793 11.508h.002l.001-.002l.005-.004l.013-.01a2 2 0 0 1 .162-.113c.105-.066.253-.147.44-.221a3 3 0 0 1 1.568-.166a.56.56 0 1 1-.175 1.106a1.85 1.85 0 0 0-.98.102a1.6 1.6 0 0 0-.324.173a.56.56 0 0 1-.712-.864");
}

.bq5dgsbba {
  stop-color: var(--svg-color--dcc8ec, #DCC8EC);
}

.brzpz-p3w {
  stop-color: var(--svg-color--8b6455, #8B6455);
}

.btor07b8q {
  stop-color: var(--svg-color--d61f4d, #D61F4D);
}

.byn6wubog {
  fill: var(--svg-color--bc9ebb, #BC9EBB);
  fill-rule: evenodd;
  d: path("M16.899 24.871a.35.35 0 0 1-.266.244c-.25.048-.467.048-.717 0a.35.35 0 0 1-.262-.23c-.18.2-.49.432-1.009.607c-.31.106-.668.058-.833-.23a1.86 1.86 0 0 1-.245-.948c0-.431.124-.74.245-.95c.165-.287.523-.334.833-.23c.503.171.81.418.993.63a.35.35 0 0 1 .278-.293c.25-.048.467-.048.717 0a.35.35 0 0 1 .28.31c.18-.215.49-.47 1.008-.646c.31-.105.668-.058.834.23c.12.208.244.513.244.949s-.124.74-.244.949c-.166.287-.524.335-.834.23c-.531-.18-.844-.42-1.022-.622");
}

.c02-eqbxv {
  stop-color: var(--svg-color--8f5d65, #8F5D65);
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

.c70lx944e {
  stop-color: var(--svg-color--8e5263, #8E5263);
  stop-opacity: 0;
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

.cu-ecjbbc {
  stop-color: var(--svg-color--8f6459, #8F6459);
}

.d5_x4xk7i {
  fill-rule: evenodd;
  d: path("M3.16 17.066a.75.75 0 0 1 1.042.197q.055.08.116.173c.17.259.379.576.676.877c.36.363.768.614 1.246.64a.75.75 0 0 1-.08 1.497c-.99-.052-1.73-.575-2.232-1.083c-.416-.42-.725-.893-.888-1.143l-.076-.115a.75.75 0 0 1 .196-1.043");
}

.d66ufbbtl {
  stop-color: var(--svg-color--8a5d55, #8A5D55);
  stop-opacity: 0;
}

.d7caiobkz {
  stop-color: var(--svg-color--e4cc30, #E4CC30);
  stop-opacity: 0;
}

.dd8hfetks {
  stop-color: var(--svg-color--4e3c3a, #4E3C3A);
  stop-opacity: 0;
}

.demkpcl0k {
  stop-color: var(--svg-color--b1a0b8, #B1A0B8);
}

.dfayxa0qz {
  d: path("M14.459 13.146a.937.937 0 0 0-.903 1.183h1.81a1 1 0 0 0 .034-.246a.943.943 0 0 0-.941-.937");
}

.dg9o8ubcl {
  stop-color: var(--svg-color--895f52, #895F52);
  stop-opacity: 0;
}

.dhqq56zrt {
  fill: var(--svg-color--88024e, #88024E);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M15.323 17.259c.413.215.906.339 1.43.339c.53 0 1.018-.124 1.431-.34a.21.21 0 0 1 .251.042c.06.062.081.16.022.25m-3.134-.291l3.092.264m-3.092-.264a.21.21 0 0 0-.252.043a.194.194 0 0 0-.02.249m.272-.292l-.231.264m3.365.027l-.042-.027m.042.027l-.042-.027m.042.027c-.36.546-.989.91-1.704.91a2.04 2.04 0 0 1-1.703-.91m3.365-.027a1.99 1.99 0 0 1-1.662.887c-.697 0-1.31-.355-1.661-.887m-.042.028l.042-.028m-.042.028l.042-.028");
}

.don2wdpjw {
  cx: 16.761px;
  cy: 26.282px;
  r: 0.739px;
}

.dpmuo-biy {
  stop-color: var(--svg-color--6f5ea2, #6F5EA2);
}

.duyhuibwk {
  cx: 9.246px;
  cy: 3.857px;
  r: 1.684px;
}

.dznl_ubra {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M11.995 9.312v.942c-.008.156-.073.505-.27.653");
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e6v6vrbif {
  stop-color: var(--svg-color--ab7773, #AB7773);
}

.eqzjb1bwj {
  stop-color: var(--svg-color--5b4545, #5B4545);
  stop-opacity: 0;
}

.ev4-2pfvs {
  stop-color: var(--svg-color--834e63, #834E63);
}

.exfuzbt0n {
  stop-color: var(--svg-color--8a4d60, #8A4D60);
}

.f-at1e-1v {
  fill: var(--svg-color--b7877d, #B7877D);
  d: path("m16.352 14.063l-.558 1.784a.566.566 0 0 0 .547.734h.825c.387 0 .66-.373.546-.734l-.557-1.784c-.12-.395-.678-.395-.803 0");
}

.f21vmbcik {
  d: path("M5.437 21.764h4.094v8.063H5.437z");
}

.f295nnb9k {
  cx: 21.756px;
  cy: 14.363px;
  r: 1.752px;
}

.f43nfdclv {
  stop-color: var(--svg-color--c69980, #C69980);
}

.f7hwkw-sq {
  stop-color: var(--svg-color--8a5d55, #8A5D55);
}

.fbmg84ypw {
  stroke: var(--svg-color--b69386, #B69386);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-35px, 0.35px);
  d: path("m24.357 18.55l.437 2.127");
}

.fde_fwzpt {
  stop-color: var(--svg-color--5c9946, #5C9946);
}

.ffsbscbfl {
  d: path("M21.812 7.563V9.3c.788.392 1.69-.227 1.52.725l-.62 3.191c-.054.33-.272.552-.6.56h-.018s.056-.952.112-1.511c.046-.455-.033-.594-.45-1.008c-.225-.224-.394-.56-.394-.896v-.896c0-.28-.226-.503-.45-.56c-.676-.167-2.084-.447-4.111-.447s-3.434.28-4.11.448a.546.546 0 0 0-.45.56v.895c0 .336-.113.672-.395.896l-.169.168c-.225.168-.337.504-.337.784c.056.615.112 1.511.112 1.511l-.051-.002a.665.665 0 0 1-.624-.558l-.62-3.19c-.112-.897.455-.113 1.244-.505l.333-1.903a8 8 0 0 0 .844-.616l1.014-1.064c.62-.56 1.52-.727 2.308-.335a3.1 3.1 0 0 0 1.746 0c.844-.28 1.801-.056 2.477.56l.845.84c.225.279.506.447.844.615");
}

.fr__qmhjc {
  stop-color: var(--svg-color--7a6cad, #7A6CAD);
}

.fr4wpbo2m {
  stop-color: var(--svg-color--422235, #422235);
}

.ft5dv1b6b {
  fill: none;
}

.fwwugibmc {
  stop-color: var(--svg-color--6e464d, #6E464D);
}

.fzq016boz {
  stop-color: var(--svg-color--e35838, #E35838);
}

.g8uem1b5g {
  stop-color: var(--svg-color--38303e, #38303E);
  stop-opacity: 0;
}

.gc5faqg1q {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.974 13.344c.067.09-.073.198-.232.317c-.158.118-.276.202-.343.112c-.066-.089.008-.257.167-.376c.158-.118.341-.142.408-.053");
}

.gfrsedb9v {
  stop-color: var(--svg-color--5b595e, #5B595E);
}

.ggm3_setj {
  d: path("m13.38 20.005l.612 3.22h4.946l.796-3.173a10.2 10.2 0 0 0-2.937-.429h-.64c-.963 0-1.894.133-2.777.382");
}

.gkxlqf77y {
  d: path("M19.043 13.146a.937.937 0 0 1 .902 1.183h-1.809a.94.94 0 0 1 .907-1.183");
}

.gr0wzobbs {
  stop-color: var(--svg-color--dbcdd4, #DBCDD4);
  stop-opacity: 0;
}

.guua1rtkt {
  fill: var(--svg-color--000, #000);
  d: path("M18.506 14.083c0-.298.239-.537.537-.537a.534.534 0 0 1 .476.784h-.949a.5.5 0 0 1-.064-.247");
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

.h2li0wblg {
  stop-color: var(--svg-color--d02759, #D02759);
}

.h4mko5b9o {
  stop-color: var(--svg-color--beb4c6, #BEB4C6);
  stop-opacity: 0;
}

.hc-r960kz {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M13.018 11.9c.343-.304 1.093-.623 2.023-.475");
}

.hcmh5c50b {
  stop-color: var(--svg-color--357ace, #357ACE);
}

.hcuo1obkg {
  stop-color: var(--svg-color--cda186, #CDA186);
}

.hj-s-zboe {
  stop-color: var(--svg-color--6d5096, #6D5096);
}

.hochth35i {
  fill: var(--svg-color--87565c, #87565C);
  d: path("m16.465 14.234l-.862 1.784c-.106.367.15.734.513.734h.774c.363 0 .619-.372.512-.734l-.523-1.784c-.112-.395-.297-.395-.415 0");
}

.hpfqe6rjh {
  cx: 6.332px;
  cy: 12.838px;
  r: 1.684px;
}

.ht6lpfbpp {
  d: path("M18.68 22.463c-.909.308-1.267.83-1.388 1.082l-.028.29l.028.359c.12.25.48.706 1.388 1.014c.362.123.778.068.971-.267c.14-.243.284-.599.284-1.105c0-.507-.144-.862-.284-1.106c-.193-.335-.61-.39-.97-.267");
}

.hw860-bkw {
  d: path("M22.993 22.213c.119.463.586 1.456.805 1.894h4.047l-.258-3.789l-4.836.924c.031.13.123.507.242.97");
}

.i1-orb7ke {
  stop-color: var(--svg-color--c3b7c1, #C3B7C1);
}

.i4vnxm0ia {
  d: path("M19.877 13.96a.9.9 0 0 0-.243-.486l-.272.299l.123.24z");
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

.iqrjx-_ld {
  fill: var(--svg-color--fff, #fff);
  d: path("M19.26 12.86c.685 0 1.264.473 1.422 1.112a.288.288 0 0 1-.281.357h-2.342a.242.242 0 0 1-.238-.285a1.47 1.47 0 0 1 1.439-1.183");
}

.ivhsfvmdg {
  stop-color: var(--svg-color--644949, #644949);
  stop-opacity: 0;
}

.iwbygtbvw {
  cx: 25.211px;
  cy: 4.873px;
  r: 1.684px;
}

.ix2ytv1nc {
  stop-color: var(--svg-color--cca68c, #CCA68C);
}

.ixdockwro {
  stop-color: var(--svg-color--916762, #916762);
}

.j70rp9pis {
  d: path("M22.222 29.826h-1.578v-9.568q.826.307 1.578.746z");
}

.j8k1fac_p {
  stop-color: var(--svg-color--5b5a5d, #5B5A5D);
}

.jdb29wbxt {
  stop-color: var(--svg-color--9f6a74, #9F6A74);
  stop-opacity: 0;
}

.je_aabb8l {
  stop-color: var(--svg-color--644949, #644949);
}

.jgab0yb4f {
  stroke: var(--svg-color--b69386, #B69386);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-35px, 0.35px);
  d: path("m23.333 19.615l.414 1.64");
}

.jhlen960d {
  stop-color: var(--svg-color--745ba5, #745BA5);
}

.jjf293xlz {
  stop-color: var(--svg-color--d61f4d, #D61F4D);
  stop-opacity: 0;
}

.jknxnjb8w {
  stop-color: var(--svg-color--95646c, #95646C);
}

.jm40s5baz {
  stop-color: var(--svg-color--968f9c, #968F9C);
  stop-opacity: 0;
}

.jwq5cabxr {
  stop-color: var(--svg-color--765443, #765443);
}

.kalg6bc5c {
  fill: var(--svg-color--4c3230, #4C3230);
  d: path("M20.658 11.507h-.001l-.002-.002l-.005-.004l-.013-.01a2 2 0 0 0-.162-.113a2.7 2.7 0 0 0-.44-.221a3 3 0 0 0-1.568-.166a.56.56 0 0 0 .175 1.106c.418-.066.752.011.98.102a1.6 1.6 0 0 1 .324.173a.56.56 0 0 0 .712-.865");
}

.ki2rd4v4k {
  stop-color: var(--svg-color--554042, #554042);
}

.km6q7kb1a {
  stop-color: var(--svg-color--5d5565, #5D5565);
  stop-opacity: 0;
}

.koq0r9bvu {
  stop-color: var(--svg-color--9e78c9, #9E78C9);
}

.kpt7nxbeg {
  stop-color: var(--svg-color--8e5263, #8E5263);
}

.kr900d0yh {
  d: path("M11.4 13.72h.052s-.056-.895-.113-1.51c0-.28.113-.616.338-.784l.169-.168c.281-.224.394-.56.394-.896v-.896c0-.28.169-.504.45-.56c.676-.168 2.084-.447 4.11-.447c2.028 0 3.435.28 4.11.447c.226.056.451.28.451.56v.896c0 .336.17.672.394.896c.527.369.495.572.45 1.007c-.055.56-.112 1.512-.112 1.512h.02l-.28 4.155c-.168 1.857-1.629 3.152-3.37 3.152h-3.37c-1.797 0-3.2-1.295-3.37-3.152z");
}

.ku63lg_wt {
  stop-color: var(--svg-color--e8e2ec, #E8E2EC);
}

.kzuil_5zu {
  stop-color: var(--svg-color--9072ca, #9072CA);
}

.l-r9gxb9g {
  stop-color: var(--svg-color--4bb8fb, #4BB8FB);
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.ld_83jb7a {
  d: path("M16.018 23.224a.41.41 0 0 1 .328-.37a2.1 2.1 0 0 1 .834 0a.41.41 0 0 1 .328.37c.042.395.042.778 0 1.174a.41.41 0 0 1-.328.37c-.29.056-.544.056-.834 0a.41.41 0 0 1-.328-.37a5.5 5.5 0 0 1 0-1.174");
}

.lelj2r8dg {
  stop-color: var(--svg-color--9ae453, #9AE453);
}

.lfw2icb2v {
  cx: 21.756px;
  cy: 14.362px;
  r: 1.044px;
  fill: var(--svg-color--a57c70, #A57C70);
}

.lgi0lwbjz {
  stop-color: var(--svg-color--775184, #775184);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.ljv0l9wbv {
  stop-color: var(--svg-color--a87b73, #A87B73);
}

.lucypabyc {
  d: path("M14.545 18.417c0-.99.9-1.794 2.011-1.794s2.012.803 2.012 1.794v2.326c0 .99-.9 1.794-2.012 1.794c-1.11 0-2.011-.803-2.011-1.794z");
}

.lxo7c2i6k {
  stop-color: var(--svg-color--462f5a, #462F5A);
  stop-opacity: 0;
}

.lz4rb992v {
  fill: var(--svg-color--000, #000);
  d: path("M14.995 14.083a.534.534 0 0 0-.536-.537a.534.534 0 0 0-.477.784h.95a.5.5 0 0 0 .063-.247");
}

.m-1-e5bla {
  stop-color: var(--svg-color--fbf2f7, #FBF2F7);
}

.m0zt7_pbu {
  stop-color: var(--svg-color--c7a08f, #C7A08F);
}

.m5_n77b4k {
  d: path("M20.658 11.507h-.001l-.002-.002l-.005-.004l-.013-.01a2 2 0 0 0-.162-.113a2.7 2.7 0 0 0-.44-.221a3 3 0 0 0-1.568-.166a.56.56 0 0 0 .175 1.106c.418-.066.752.011.98.102a1.6 1.6 0 0 1 .324.173a.56.56 0 0 0 .712-.865");
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

.mcp_a12ev {
  stop-color: var(--svg-color--997971, #997971);
  stop-opacity: 0;
}

.mifq-tdon {
  stop-color: var(--svg-color--c39787, #C39787);
}

.mmmkqcbgq {
  stop-color: var(--svg-color--8f5d65, #8F5D65);
  stop-opacity: 0;
}

.mmq2utbuk {
  stop-color: var(--svg-color--cf8b51, #CF8B51);
}

.mpwbs5b3u {
  stop-color: var(--svg-color--ff894e, #FF894E);
}

.mug1r-bxu {
  stop-color: var(--svg-color--b58f71, #B58F71);
}

.mxfqo-b2y {
  stop-color: var(--svg-color--c1987f, #C1987F);
}

.n-ko-_w7d {
  stop-color: var(--svg-color--c39787, #C39787);
  stop-opacity: 0;
}

.n297mkbnr {
  stop-color: var(--svg-color--d6d3d7, #D6D3D7);
  stop-opacity: 0;
}

.n7o-m0b5s {
  stop-color: var(--svg-color--624c49, #624C49);
}

.n91c-gs8j {
  stop-color: var(--svg-color--865d5f, #865D5F);
}

.ng1cexbhj {
  stop-color: var(--svg-color--b6424c, #B6424C);
}

.nl0wbpawx {
  stop-color: var(--svg-color--968f9c, #968F9C);
}

.nzdq87b8k {
  stop-color: var(--svg-color--9b7569, #9B7569);
  stop-opacity: 0;
}

.o_30au2yc {
  stop-color: var(--svg-color--decfd8, #DECFD8);
}

.o3862mwmv {
  d: path("M11.34 12.21c0-.28.112-.616.337-.784l.169-.168c.281-.224.394-.56.394-.896v-.896c0-.28.169-.504.45-.56c.676-.168 2.084-.447 4.11-.447c2.028 0 3.435.28 4.11.447c.226.056.451.28.451.56v.896c0 .336.17.672.394.896c.527.369.495.572.45 1.007c-.055.56-.112 1.512-.112 1.512h.02l-.28 4.155c-.168 1.857-1.629 3.152-3.37 3.152h-3.37c-1.797 0-3.2-1.295-3.37-3.152c-.146-1.907-.21-3.82-.384-5.723");
}

.o415o878f {
  stop-color: var(--svg-color--ef4c8b, #EF4C8B);
}

.ocqp4lspe {
  d: path("m16.352 14.063l-.558 1.784a.566.566 0 0 0 .547.734h.825c.387 0 .66-.373.546-.734l-.557-1.784c-.12-.395-.678-.395-.803 0");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ohs50t_5m {
  stop-color: var(--svg-color--4a3236, #4A3236);
  stop-opacity: 0;
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

.p4atghb8h {
  fill: var(--svg-color--c59883, #C59883);
  d: path("m27.85 19.83l-.447.824l-1.172 1.422l-1.481 1.992l3.099.047c.099-.172.218-.566.38-1.327c.164-.66.326-1.114.471-1.376l.443-.924a.726.726 0 0 0-1.292-.659");
}

.palsozbti {
  d: path("M18.974 13.344c.067.09-.073.198-.232.317c-.158.118-.276.202-.343.112c-.066-.089.008-.257.167-.376c.158-.118.341-.142.408-.053");
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

.q6l4_694w {
  fill: var(--svg-color--4c3230, #4C3230);
  d: path("M12.793 11.508h.002l.001-.002l.005-.004l.013-.01a2 2 0 0 1 .162-.113c.105-.066.253-.147.44-.221a3 3 0 0 1 1.568-.166a.56.56 0 1 1-.175 1.106a1.85 1.85 0 0 0-.98.102a1.6 1.6 0 0 0-.324.173a.56.56 0 0 1-.712-.864");
}

.qg7eszk4c {
  stop-color: var(--svg-color--caa48f, #CAA48F);
  stop-opacity: 0;
}

.qmnjff_ag {
  stop-color: var(--svg-color--ab7773, #AB7773);
  stop-opacity: 0;
}

.qo7u-3bcf {
  stop-color: var(--svg-color--76594a, #76594A);
}

.qpmxtnavh {
  stop-color: var(--svg-color--82604e, #82604E);
  stop-opacity: 0;
}

.qq8pp_7zq {
  stop-color: var(--svg-color--cca490, #CCA490);
}

.qsu4qbckq {
  stop-color: var(--svg-color--dbcdd4, #DBCDD4);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qxphtrj0e {
  stop-color: var(--svg-color--8b6455, #8B6455);
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

.rg60sduho {
  stop-color: var(--svg-color--815356, #815356);
  stop-opacity: 0;
}

.s0umluqbl {
  stop-color: var(--svg-color--7160a4, #7160A4);
  stop-opacity: 0;
}

.s3rfzh4ga {
  stop-color: var(--svg-color--a27671, #A27671);
}

.s9u0fjbul {
  stop-color: var(--svg-color--c7a08f, #C7A08F);
  stop-opacity: 0;
}

.sawf8hb2n {
  stop-color: var(--svg-color--ef4c8b, #EF4C8B);
  stop-opacity: 0;
}

.sb-ednb_a {
  stop-color: var(--svg-color--ece4f4, #ECE4F4);
}

.sbbt-6b7n {
  fill: var(--svg-color--ab8178, #AB8178);
  d: path("M24.458 17.959a.68.68 0 0 1 .568-.843l.023-.003a.68.68 0 0 1 .756.54l.622 3.039c.071.355-.246.42-.606.458c-.303.032-.553-.005-.629-.3z");
}

.scbqttb8d {
  stop-color: var(--svg-color--ec4182, #EC4182);
}

.sjxmvib4j {
  stop-color: var(--svg-color--82604e, #82604E);
}

.sla6kib8v {
  stop-color: var(--svg-color--ae7f75, #AE7F75);
}

.smgiue0gi {
  stop-color: var(--svg-color--c93857, #C93857);
}

.smnqffnel {
  stop-color: var(--svg-color--95646c, #95646C);
  stop-opacity: 0;
}

.soj01hbui {
  stop-color: var(--svg-color--cda186, #CDA186);
  stop-opacity: 0;
}

.ssfga94sp {
  stop-color: var(--svg-color--a87d7b, #A87D7B);
}

.suj-pjbhk {
  stop-color: var(--svg-color--895f52, #895F52);
}

.swka_j87x {
  d: path("M6.25 29.826c0-5.635 4.568-10.203 10.203-10.203h.64c5.636 0 10.204 4.568 10.204 10.203z");
}

.szi8mbi3d {
  cx: 14.176px;
  cy: 13.546px;
  rx: 0.409px;
  ry: 0.207px;
}

.t-5nldk3g {
  cx: 16.761px;
  cy: 28.296px;
  r: 0.739px;
}

.t-wcrfbaw {
  stop-color: var(--svg-color--a87d7b, #A87D7B);
  stop-opacity: 0;
}

.t4hztoa1h {
  stop-color: var(--svg-color--815356, #815356);
}

.t9eszom7h {
  cx: 21.756px;
  cy: 14.362px;
  r: 1.044px;
}

.tg07-ljnl {
  stop-color: var(--svg-color--5e5764, #5E5764);
}

.th6oxbbzk {
  cx: 14.176px;
  cy: 13.546px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.409px;
  ry: 0.207px;
}

.tiqausb5g {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M18.497 11.356c.45-.08 1.331-.057 1.94.417");
}

.tn_97qkdc {
  stop-color: var(--svg-color--f2c341, #F2C341);
  stop-opacity: 0;
}

.tp9jx5j2y {
  stop-color: var(--svg-color--554042, #554042);
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

.u1gl_1zha {
  stop-color: var(--svg-color--ec4182, #EC4182);
  stop-opacity: 0;
}

.u3v34c8wo {
  cx: 11.77px;
  cy: 14.362px;
  r: 1.044px;
}

.u5bjt8cdp {
  d: path("M6.803 17.694a.782.782 0 0 1 1.249-.941l.93 1.214c.337.438.519.975.519 1.527l-1.5-.18z");
}

.u6lph46no {
  stop-color: var(--svg-color--f0dff0, #F0DFF0);
}

.uck8wqbzl {
  stop-color: var(--svg-color--9f6f71, #9F6F71);
}

.ucq3z1bcr {
  fill: var(--svg-color--ab8178, #AB8178);
  d: path("M25.92 18.247a.668.668 0 1 1 1.316-.232l.34 2.222q.012.082.005.164l-.015.163c-.005.055-.002.11 0 .165c.016.295-.146.515-.454.557a.61.61 0 0 1-.68-.483z");
}

.ujrq6ixuu {
  stop-color: var(--svg-color--beb4c6, #BEB4C6);
}

.ux7-g74jy {
  stop-color: var(--svg-color--4e3c3a, #4E3C3A);
}

.v-g8l9b4g {
  stop-color: var(--svg-color--94576d, #94576D);
}

.v-s78bb2b {
  d: path("M15.314 13.973c0-.303-.246-.505-.312-.566l-.303.293l.186.38z");
}

.v0501vbqa {
  stop-color: var(--svg-color--c0b5cd, #C0B5CD);
}

.v1vf9kb3x {
  stop-color: var(--svg-color--9c6073, #9C6073);
  stop-opacity: 0;
}

.v20j2nbso {
  fill: var(--svg-color--fff, #fff);
  d: path("M14.241 12.86c-.685 0-1.264.473-1.421 1.112a.288.288 0 0 0 .28.358h2.342a.242.242 0 0 0 .238-.286a1.47 1.47 0 0 0-1.439-1.183");
}

.va-8to-0f {
  stop-color: var(--svg-color--c69985, #C69985);
}

.vdngsab5t {
  fill-rule: evenodd;
  d: path("M3.416 19.34a.75.75 0 0 1 1.051.14c.244.317.833.881 1.8.881a.75.75 0 0 1 .75.75c0 .415-.336.67-.75.67c-1.683 0-2.593-.87-2.99-1.39a.75.75 0 0 1 .139-1.05");
}

.vke6kh8bt {
  stop-color: var(--svg-color--3e3843, #3E3843);
  stop-opacity: 0;
}

.vo9agqbnp {
  stop-color: var(--svg-color--694448, #694448);
}

.vvfum-_fa {
  stop-color: var(--svg-color--392f42, #392F42);
}

.w_j-6pbpp {
  stop-color: var(--svg-color--834e63, #834E63);
  stop-opacity: 0;
}

.w4ky7s-1q {
  stop-color: var(--svg-color--ac7b71, #AC7B71);
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

.wshx69b-y {
  stop-color: var(--svg-color--896bb4, #896BB4);
}

.wzn2a8b8n {
  stroke: var(--svg-color--b69386, #B69386);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-35px, 0.35px);
  d: path("m26.849 18.13l.32 2.165");
}

.x1l7xqbyw {
  stop-color: var(--svg-color--de5534, #DE5534);
  stop-opacity: 0;
}

.xaj4s_mqh {
  stop-color: var(--svg-color--9b7569, #9B7569);
}

.xk94moblk {
  stop-color: var(--svg-color--9c6073, #9C6073);
}

.xnf9zsbcq {
  fill: var(--svg-color--ab8178, #AB8178);
  d: path("M22.414 19.881a.681.681 0 1 1 1.33-.294l.36 1.794a.645.645 0 0 1-1.26.279z");
}

.xntzq-4ho {
  stop-color: var(--svg-color--8566b5, #8566B5);
}

.xo-sv8bhm {
  stop-color: var(--svg-color--422235, #422235);
  stop-opacity: 0;
}

.xp-9f0bqu {
  stop-color: var(--svg-color--624c49, #624C49);
  stop-opacity: 0;
}

.xvexp0bjq {
  stop-color: var(--svg-color--895e4d, #895E4D);
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

.ym-b_m9fy {
  stop-color: var(--svg-color--d1bed4, #D1BED4);
  stop-opacity: 0;
}

.yt9en_n3k {
  stop-color: var(--svg-color--9b7368, #9B7368);
  stop-opacity: 0;
}

.z8_150olp {
  stop-color: var(--svg-color--c1987f, #C1987F);
  stop-opacity: 0;
}

.zdcorrl9x {
  cx: 26.234px;
  cy: 14.83px;
  r: 1.684px;
}

.zrsmq2u6o {
  stop-color: var(--svg-color--caa48f, #CAA48F);
}

.zw2ljvb-t {
  stop-color: var(--svg-color--4a3236, #4A3236);
}

</style>
