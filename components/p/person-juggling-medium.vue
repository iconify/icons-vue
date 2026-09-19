<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#i13oPwc)"><path fill="url(#iPYYWhe)" class="swka_j87x"/><path fill="url(#iT07jwd)" class="swka_j87x"/><path fill="url(#il5eVUq)" class="swka_j87x"/><path fill="url(#iY3yYtd)" class="swka_j87x"/><path fill="url(#iv8FoOX)" class="swka_j87x"/></g><circle fill="url(#iBZ0RUd)" class="hpfqe6rjh"/><circle fill="url(#itKlKTd)" class="hpfqe6rjh"/><circle fill="url(#ihlr5IT)" class="duyhuibwk"/><circle fill="url(#iGUmgWd)" class="duyhuibwk"/><circle fill="url(#iXhqZHd)" class="iwbygtbvw"/><circle fill="url(#iOHvRJe)" class="iwbygtbvw"/><circle fill="url(#issuNue)" class="zdcorrl9x"/><circle fill="url(#iMaLBhb)" class="zdcorrl9x"/><circle fill="url(#iAhrvZc)" class="zdcorrl9x"/><g filter="url(#iDDl5Eb)"><circle fill="url(#iMk8UMb)" class="t-5nldk3g"/></g><g filter="url(#i2aIaNd)"><circle fill="url(#iR23Gge)" class="don2wdpjw"/></g><path fill="url(#i5YvaPc)" class="j70rp9pis"/><path fill="url(#iK84mBb)" class="j70rp9pis"/><path fill="url(#iWCiqKd)" class="j70rp9pis"/><path fill="url(#ieol8Me)" class="qy4rrcb8b"/><path fill="url(#iDbbcbc)" class="qy4rrcb8b"/><path fill="url(#iOe2zrd)" class="qy4rrcb8b"/><path fill="url(#iV71Rbc)" class="qy4rrcb8b"/><g filter="url(#i6NrRAb)"><path fill="url(#ih8Nxde)" class="kzmu-rrsy"/><path fill="url(#iQpTAtb)" class="kzmu-rrsy"/></g><path fill="url(#ipodSkc)" class="f21vmbcik"/><path fill="url(#iXPTZOc)" class="f21vmbcik"/><path fill="url(#itP1zjc)" class="wp2p6dbcv"/><path fill="url(#i33ZCUz)" class="wp2p6dbcv"/><g filter="url(#isn51ud)"><path clip-rule="evenodd" class="byn6wubog"/></g><g filter="url(#iBGWFae)"><path fill="url(#iSAsI1d)" class="ctsppjbax"/><path fill="url(#iwtPTOo)" class="ctsppjbax"/><path fill="url(#isAdhHe)" class="ctsppjbax"/></g><g filter="url(#i1FaHbn)"><path fill="url(#ivLP6Gc)" class="ht6lpfbpp"/><path fill="url(#iXetYud)" class="ht6lpfbpp"/></g><g filter="url(#ikO3Ilc)"><path fill="url(#i8tJXGc)" class="ld_83jb7a"/><path fill="url(#iw9bnJb)" class="ld_83jb7a"/></g><g filter="url(#ikW2CXI)"><path class="p4atghb8h"/></g><g filter="url(#iBblwwe)"><path class="ucq3z1bcr"/></g><g filter="url(#iLIBlOI)"><path class="sbbt-6b7n"/></g><g filter="url(#iLCPe0c)"><path class="ay_tpr1ro"/></g><g filter="url(#ifSo5Yb)"><path class="xnf9zsbcq"/></g><path fill="url(#ilez79L)" class="hw860-bkw"/><path fill="url(#iSXBdIb)" class="hw860-bkw"/><path fill="url(#ib914xd)" class="hw860-bkw"/><g filter="url(#i84rtgc)"><path fill="url(#iq39nHd)" class="u5bjt8cdp"/></g><path fill="url(#iELdlqb)" clip-rule="evenodd" class="wfgw5ub6b"/><path fill="url(#iBqD1Xb)" clip-rule="evenodd" class="wfgw5ub6b"/><path fill="url(#iiItqld)" clip-rule="evenodd" class="d5_x4xk7i"/><path fill="url(#iGVyd2d)" clip-rule="evenodd" class="d5_x4xk7i"/><path fill="url(#i5nc0Sc)" clip-rule="evenodd" class="ctupw6b3d"/><path fill="url(#iQodSWd)" clip-rule="evenodd" class="ctupw6b3d"/><path fill="url(#iUzJ9JS)" clip-rule="evenodd" class="vdngsab5t"/><path fill="url(#iYRVChc)" clip-rule="evenodd" class="vdngsab5t"/><path fill="url(#iHc2wiw)" class="twba206ho"/><path fill="url(#idQamRc)" class="twba206ho"/><path fill="url(#ieGY6Vb)" class="k1soseb1u"/><g filter="url(#i31mfrc)"><path class="jgab0yb4f"/></g><g filter="url(#iM3pRHq)"><path class="a65rs5a6h"/></g><g filter="url(#iPgKdub)"><path class="akrf-l3yi"/></g><g filter="url(#itAdVic)"><path class="wzn2a8b8n"/></g><g filter="url(#iZDnoMl)"><path stroke="url(#ioZXgLe)" class="bdk4dmb5b"/></g><g filter="url(#i29dLze)"><path stroke="url(#i4O2smb)" class="gwm_2mjil"/></g><g filter="url(#i6Q3C9b)"><path stroke="url(#iz0d3ff)" class="y2ly1lryk"/></g><g filter="url(#iEAAnQd)"><path stroke="url(#iJwKJNb)" class="am6k_ubte"/></g><g filter="url(#igdwpBb)"><path stroke="url(#ivFlTre)" class="c549xi8ae"/></g><g filter="url(#i1FBRNc)"><path class="vcz9qnm9q"/></g><g filter="url(#iPTVr7d)"><path class="hzaq54bmy"/></g><path fill="url(#ikzTdze)" class="c2gpet42m"/><path fill="url(#i7NM8uw)" class="c3gr2ccfh"/><g filter="url(#iqfTife)"><path fill="url(#iiLJxzb)" class="nuzlzbt9j"/><path fill="url(#izdJfKT)" class="nuzlzbt9j"/></g><path fill="url(#i569ddd)" class="nuzlzbt9j"/><path fill="url(#iS64bJc)" class="nuzlzbt9j"/><path fill="url(#i3fBZGb)" class="nuzlzbt9j"/><path fill="url(#idmITCe)" class="nuzlzbt9j"/><path fill="url(#iiOeZwd)" class="nuzlzbt9j"/><path fill="url(#iZDYxgc)" class="nuzlzbt9j"/><path fill="url(#iHpB06c)" class="nuzlzbt9j"/><path fill="url(#iSz2hDb)" class="nuzlzbt9j"/><path fill="url(#iK8OnYd)" class="nuzlzbt9j"/><g filter="url(#isySrbb)"><path class="zueu3mftc"/></g><g filter="url(#iM7gwgb)"><path class="eyqrsfcva"/><path fill="url(#iv1RleS)" class="tuxkwlbzf"/><path fill="url(#iVRPk8b)" class="tuxkwlbzf"/><path fill="url(#iq1Y8se)" class="tuxkwlbzf"/><path fill="url(#iDJxVDb)" class="tuxkwlbzf"/><path fill="url(#izNgxkc)" class="tuxkwlbzf"/></g><g filter="url(#iVdXK6E)"><path stroke="url(#iSr2O9S)" class="j5-qsy2fi"/></g><path fill="url(#iG3Ax6b)" class="dklp1oekh"/><g filter="url(#iZSiK9b)"><path fill="url(#ilkbyyb)" class="lwi963zwv"/></g><g filter="url(#iC0aShd)"><path class="ep9ttx4ds"/></g><g filter="url(#id5fyeb)"><path class="f-dh8j4tm"/></g><path class="lnmij5brh"/><path fill="url(#iSAdiyd)" class="v71pqg4ed"/><path class="gt8hc6nxf"/><g filter="url(#iItBPQd)"><path class="prlk-hzei"/><path fill="url(#i8l3rMt)" class="jsxbyvb_p"/></g><g filter="url(#ij3fSCe)"><path fill="url(#iZfDgPd)" class="hs7yh0bot"/></g><path class="ghjd91i9b"/><path fill="url(#iMgEHwb)" class="fvjz8xbso"/><path class="y-ob1pbsd"/><g filter="url(#iFVAF6c)"><path fill="url(#iONlpjd)" class="ckv4qxbrn"/></g><g filter="url(#iE2Ajxb)"><ellipse transform="rotate(-27.914 14.17 13.235)" class="zdzom5a9w"/><ellipse fill="url(#ibu7EZQ)" transform="rotate(-27.914 14.17 13.235)" class="if4bi9b9w"/></g><path fill="url(#ipdnd0m)" class="uh87n4b_i"/><path fill="url(#iOp3uDb)" class="uh87n4b_i"/><path fill="url(#iHGACfc)" class="uh87n4b_i"/><path fill="url(#iLuRz4b)" class="uh87n4b_i"/><path fill="url(#idHz03h)" class="t1yb008wo"/><path fill="url(#iFyxouJ)" class="t1yb008wo"/><g filter="url(#iHwHtge)"><path fill="url(#iUuTBYc)" class="jk__z2bxx"/></g><g filter="url(#iHHqmgc)"><path fill="url(#isf4a1d)" class="nvnpqub-x"/></g><g filter="url(#ik5PE3O)"><path class="g9e006slv"/></g><g filter="url(#izzG3ee)"><path class="b-hh4tbue"/></g><path fill="url(#iMwhdrV)" class="qzd219blo"/><path fill="url(#i3dSYhb)" class="qzd219blo"/><path fill="url(#inl9J2c)" class="qzd219blo"/><path fill="url(#iCE2gke)" class="wozepxbaa"/><path fill="url(#izP9Z9c)" class="wozepxbaa"/><rect fill="url(#ixSAAAe)" class="okwd93kys"/><rect fill="url(#iy7tjOa)" class="okwd93kys"/><rect fill="url(#iYE2hsb)" class="okwd93kys"/><defs><radialGradient id="iPYYWhe" cx="0" cy="0" r="1" gradientTransform="rotate(135.22 8.643 15.887)scale(12.9545 12.5552)" gradientUnits="userSpaceOnUse"><stop offset=".195" class="m-1-e5bla"/><stop offset=".794" class="b057dp4eh"/></radialGradient><radialGradient id="iT07jwd" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.09375 -3.28125 0 20.219 20.139)" gradientUnits="userSpaceOnUse"><stop class="m9gf32bwp"/><stop offset="1" class="n297mkbnr"/></radialGradient><radialGradient id="il5eVUq" cx="0" cy="0" r="1" gradientTransform="matrix(-1.75 0 0 -11.7187 21 25.92)" gradientUnits="userSpaceOnUse"><stop offset=".214" class="demkpcl0k"/><stop offset="1" class="ym-b_m9fy"/></radialGradient><radialGradient id="iY3yYtd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.15625 0 0 -5.75902 11.656 25.326)" gradientUnits="userSpaceOnUse"><stop class="ujrq6ixuu"/><stop offset="1" class="h4mko5b9o"/></radialGradient><radialGradient id="iv8FoOX" cx="0" cy="0" r="1" gradientTransform="matrix(2.12502 5.34374 -11.023 4.38346 13.099 18.733)" gradientUnits="userSpaceOnUse"><stop class="nl0wbpawx"/><stop offset="1" class="jm40s5baz"/></radialGradient><radialGradient id="iBZ0RUd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.34375 2.4375 -2.36069 -1.3014 7.187 11.826)" gradientUnits="userSpaceOnUse"><stop offset=".077" class="l-r9gxb9g"/><stop offset="1" class="hcmh5c50b"/></radialGradient><radialGradient id="itKlKTd" cx="0" cy="0" r="1" gradientTransform="rotate(115.145 -.151 8.247)scale(3.38309 2.95533)" gradientUnits="userSpaceOnUse"><stop offset=".452" class="y-1rsmdul"/><stop offset=".826" class="af8mzdbwl"/></radialGradient><radialGradient id="ihlr5IT" cx="0" cy="0" r="1" gradientTransform="matrix(-1.34375 2.4375 -2.36069 -1.3014 10.101 2.846)" gradientUnits="userSpaceOnUse"><stop offset=".077" class="mpwbs5b3u"/><stop offset="1" class="fzq016boz"/></radialGradient><radialGradient id="iGUmgWd" cx="0" cy="0" r="1" gradientTransform="rotate(115.145 4.158 4.683)scale(3.38309 2.95533)" gradientUnits="userSpaceOnUse"><stop offset=".452" class="x1l7xqbyw"/><stop offset=".826" class="ng1cexbhj"/></radialGradient><radialGradient id="iXhqZHd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.34375 2.4375 -2.36069 -1.3014 26.066 3.861)" gradientUnits="userSpaceOnUse"><stop offset=".077" class="lelj2r8dg"/><stop offset="1" class="fde_fwzpt"/></radialGradient><radialGradient id="iOHvRJe" cx="0" cy="0" r="1" gradientTransform="rotate(105.03 11.36 11.751)scale(3.49455 3.40391)" gradientUnits="userSpaceOnUse"><stop offset=".375" class="ppr920emc"/><stop offset=".826" class="y_auwli2s"/></radialGradient><radialGradient id="issuNue" cx="0" cy="0" r="1" gradientTransform="matrix(-1.34375 2.4375 -2.36069 -1.3014 27.09 13.818)" gradientUnits="userSpaceOnUse"><stop offset=".077" class="y05rrkbkk"/><stop offset="1" class="a5zzorbzd"/></radialGradient><radialGradient id="iMaLBhb" cx="0" cy="0" r="1" gradientTransform="matrix(1 1.07812 -1.5877 1.47265 24.969 13.357)" gradientUnits="userSpaceOnUse"><stop class="i8j0jyb4u"/><stop offset="1" class="d7caiobkz"/></radialGradient><radialGradient id="iAhrvZc" cx="0" cy="0" r="1" gradientTransform="rotate(109.11 8.51 16.52)scale(3.46022 3.37046)" gradientUnits="userSpaceOnUse"><stop offset=".347" class="tn_97qkdc"/><stop offset=".829" class="mmq2utbuk"/></radialGradient><radialGradient id="iMk8UMb" cx="0" cy="0" r="1" gradientTransform="matrix(-.7578 1.14063 -.96756 -.64282 17.25 27.855)" gradientUnits="userSpaceOnUse"><stop offset=".212" class="u6lph46no"/><stop offset="1" class="bq5dgsbba"/></radialGradient><radialGradient id="iR23Gge" cx="0" cy="0" r="1" gradientTransform="matrix(-.7578 1.14063 -.96756 -.64282 17.25 25.842)" gradientUnits="userSpaceOnUse"><stop offset=".212" class="u6lph46no"/><stop offset="1" class="bq5dgsbba"/></radialGradient><radialGradient id="i5YvaPc" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.03125 -2.40212 0 22.222 20.983)" gradientUnits="userSpaceOnUse"><stop class="koq0r9bvu"/><stop offset="1" class="dpmuo-biy"/></radialGradient><radialGradient id="ieol8Me" cx="0" cy="0" r="1" gradientTransform="scale(1.38818 6.1875)rotate(90 2.761 6.5)" gradientUnits="userSpaceOnUse"><stop class="xntzq-4ho"/><stop offset="1" class="pt8frltpn"/></radialGradient><radialGradient id="iDbbcbc" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.25 -.60938 0 13.062 24.108)" gradientUnits="userSpaceOnUse"><stop class="wshx69b-y"/><stop offset="1" class="aqzyd8bsb"/></radialGradient><radialGradient id="iOe2zrd" cx="0" cy="0" r="1" gradientTransform="matrix(2.9375 -7.98881 7.06186 2.59666 10.312 28.264)" gradientUnits="userSpaceOnUse"><stop offset=".724" class="lgi0lwbjz"/><stop offset="1" class="tvoyviyhj"/></radialGradient><radialGradient id="iV71Rbc" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.42188 -.18506 0 12.857 21.717)" gradientUnits="userSpaceOnUse"><stop class="m5avsc_ef"/><stop offset="1" class="ci3gi1b_k"/></radialGradient><radialGradient id="ih8Nxde" cx="0" cy="0" r="1" gradientTransform="matrix(-3.90624 2.42972 -4.28692 -6.89204 19.265 20.795)" gradientUnits="userSpaceOnUse"><stop class="ku63lg_wt"/><stop offset="1" class="i1-orb7ke"/></radialGradient><radialGradient id="iQpTAtb" cx="0" cy="0" r="1" gradientTransform="matrix(-.46875 -.125 .54686 -2.05079 19.188 22.482)" gradientUnits="userSpaceOnUse"><stop offset=".108" class="qsu4qbckq"/><stop offset="1" class="gr0wzobbs"/></radialGradient><radialGradient id="iSAsI1d" cx="0" cy="0" r="1" gradientTransform="matrix(1.73878 1.3451 -1.47727 1.90964 13.775 23.358)" gradientUnits="userSpaceOnUse"><stop class="ab6i82btp"/><stop offset="1" class="pb6efmson"/></radialGradient><radialGradient id="iwtPTOo" cx="0" cy="0" r="1" gradientTransform="matrix(-1.68958 -.4774 .79459 -2.81214 15.416 23.836)" gradientUnits="userSpaceOnUse"><stop offset=".69" class="sawf8hb2n"/><stop offset="1" class="o415o878f"/></radialGradient><radialGradient id="isAdhHe" cx="0" cy="0" r="1" gradientTransform="matrix(-.5 1.58457 -.75053 -.23683 16.11 23.836)" gradientUnits="userSpaceOnUse"><stop class="btor07b8q"/><stop offset="1" class="jjf293xlz"/></radialGradient><radialGradient id="ivLP6Gc" cx="0" cy="0" r="1" gradientTransform="rotate(142.275 5.895 15.056)scale(2.19833 2.41434)" gradientUnits="userSpaceOnUse"><stop class="auvn9fbbk"/><stop offset="1" class="h2li0wblg"/></radialGradient><radialGradient id="iXetYud" cx="0" cy="0" r="1" gradientTransform="matrix(1.68958 -.4774 .79459 2.81214 18.13 23.836)" gradientUnits="userSpaceOnUse"><stop offset=".69" class="sawf8hb2n"/><stop offset="1" class="o415o878f"/></radialGradient><radialGradient id="iw9bnJb" cx="0" cy="0" r="1" gradientTransform="matrix(-.39136 0 0 -2.59279 17.54 23.592)" gradientUnits="userSpaceOnUse"><stop class="scbqttb8d"/><stop offset="1" class="u1gl_1zha"/></radialGradient><radialGradient id="ilez79L" cx="0" cy="0" r="1" gradientTransform="matrix(-4.375 1.44046 -1.3893 -4.21963 28.098 22.456)" gradientUnits="userSpaceOnUse"><stop offset=".241" class="va-8to-0f"/><stop offset="1" class="ljv0l9wbv"/></radialGradient><radialGradient id="iSXBdIb" cx="0" cy="0" r="1" gradientTransform="rotate(163.091 11.838 12.97)scale(3.90165 13.4872)" gradientUnits="userSpaceOnUse"><stop offset=".699" class="smnqffnel"/><stop offset="1" class="jknxnjb8w"/></radialGradient><radialGradient id="ib914xd" cx="0" cy="0" r="1" gradientTransform="rotate(77.963 .104 26.074)scale(1.04894 5.75403)" gradientUnits="userSpaceOnUse"><stop offset=".134" class="s3rfzh4ga"/><stop offset="1" class="aewjbccqi"/></radialGradient><radialGradient id="iq39nHd" cx="0" cy="0" r="1" gradientTransform="rotate(139.97 1.2 10.48)scale(1.53045 3.638)" gradientUnits="userSpaceOnUse"><stop offset=".129" class="b1xnaurjw"/><stop offset="1" class="xvexp0bjq"/></radialGradient><radialGradient id="iELdlqb" cx="0" cy="0" r="1" gradientTransform="matrix(-.79386 1.27188 -2.4349 -1.51978 6.442 17.553)" gradientUnits="userSpaceOnUse"><stop class="mug1r-bxu"/><stop offset="1" class="uck8wqbzl"/></radialGradient><radialGradient id="iBqD1Xb" cx="0" cy="0" r="1" gradientTransform="matrix(-.73037 2.48832 -3.82658 -1.12318 6.977 17.288)" gradientUnits="userSpaceOnUse"><stop offset=".579" class="qpmxtnavh"/><stop offset=".954" class="sjxmvib4j"/></radialGradient><radialGradient id="iiItqld" cx="0" cy="0" r="1" gradientTransform="rotate(116.602 -3.017 10.55)scale(1.58621 2.70684)" gradientUnits="userSpaceOnUse"><stop class="mug1r-bxu"/><stop offset="1" class="uck8wqbzl"/></radialGradient><radialGradient id="iGVyd2d" cx="0" cy="0" r="1" gradientTransform="matrix(-.65347 2.77477 -3.52334 -.82977 5.545 17.677)" gradientUnits="userSpaceOnUse"><stop offset=".579" class="qpmxtnavh"/><stop offset=".954" class="sjxmvib4j"/></radialGradient><radialGradient id="i5nc0Sc" cx="0" cy="0" r="1" gradientTransform="matrix(-.68468 1.22288 -2.2217 -1.2439 4.939 18.947)" gradientUnits="userSpaceOnUse"><stop class="mug1r-bxu"/><stop offset="1" class="uck8wqbzl"/></radialGradient><radialGradient id="iQodSWd" cx="0" cy="0" r="1" gradientTransform="rotate(104.751 -4.503 11.427)scale(2.474 3.46652)" gradientUnits="userSpaceOnUse"><stop offset=".579" class="qpmxtnavh"/><stop offset=".954" class="sjxmvib4j"/></radialGradient><radialGradient id="iUzJ9JS" cx="0" cy="0" r="1" gradientTransform="rotate(122.692 -2.834 11.406)scale(1.24393 2.40994)" gradientUnits="userSpaceOnUse"><stop class="mug1r-bxu"/><stop offset="1" class="uck8wqbzl"/></radialGradient><radialGradient id="iYRVChc" cx="0" cy="0" r="1" gradientTransform="matrix(-.61813 2.04813 -3.22394 -.973 5.687 19.733)" gradientUnits="userSpaceOnUse"><stop offset=".579" class="qpmxtnavh"/><stop offset=".954" class="sjxmvib4j"/></radialGradient><radialGradient id="iHc2wiw" cx="0" cy="0" r="1" gradientTransform="rotate(-162.011 6.48 10.137)scale(3.69324 5.10277)" gradientUnits="userSpaceOnUse"><stop class="qq8pp_7zq"/><stop offset=".482" class="blko_hazg"/></radialGradient><radialGradient id="idQamRc" cx="0" cy="0" r="1" gradientTransform="matrix(.07812 -.82813 3.88844 .36683 6.156 21.78)" gradientUnits="userSpaceOnUse"><stop class="jwq5cabxr"/><stop offset="1" class="yt9en_n3k"/></radialGradient><radialGradient id="ieGY6Vb" cx="0" cy="0" r="1" gradientTransform="rotate(53.51 -11.908 25.833)scale(3.1004 3.53574)" gradientUnits="userSpaceOnUse"><stop offset=".438" class="exfuzbt0n"/><stop offset="1" class="w4ky7s-1q"/></radialGradient><radialGradient id="ikzTdze" cx="0" cy="0" r="1" gradientTransform="rotate(69.657 -.103 23.302)scale(2.27477 2.70225)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="hb-rh6b9c"/><stop offset="1" class="o5jc2cxps"/></radialGradient><radialGradient id="i7NM8uw" cx="0" cy="0" r="1" gradientTransform="rotate(17.447 -46.352 41.68)scale(1.63453 5.04264)" gradientUnits="userSpaceOnUse"><stop class="v_2gjcb5l"/><stop offset=".746" class="vzzhqfd0u"/></radialGradient><radialGradient id="iiLJxzb" cx="0" cy="0" r="1" gradientTransform="matrix(-4.96912 0 0 -8.79032 19.726 14.303)" gradientUnits="userSpaceOnUse"><stop class="hdsgirtov"/><stop offset="1" class="j213y8b_z"/></radialGradient><radialGradient id="izdJfKT" cx="0" cy="0" r="1" gradientTransform="rotate(121.159 7.112 9.971)scale(3.55808 2.93748)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="v3vg2fbhx"/><stop offset="1" class="jon81gnkc"/></radialGradient><radialGradient id="iS64bJc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.0796 13.12076 -10.86558 -.89404 18.431 8.058)" gradientUnits="userSpaceOnUse"><stop offset=".767" class="f0o-9fbtc"/><stop offset="1" class="otf1mnoto"/></radialGradient><radialGradient id="i3fBZGb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.2128 1.50085 0 19.345 12.917)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="kud2-ccnc"/><stop offset="1" class="qjdbe6bhy"/></radialGradient><radialGradient id="idmITCe" cx="0" cy="0" r="1" gradientTransform="matrix(.00415 -1.1557 1.25767 .00452 14.332 12.966)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="g101ufbyh"/><stop offset="1" class="ofu8odbdi"/></radialGradient><radialGradient id="iiOeZwd" cx="0" cy="0" r="1" gradientTransform="rotate(176.388 9.951 7.995)scale(8.9907 22.9667)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="c-0f6obbw"/><stop offset="1" class="q4oz8ebqu"/></radialGradient><radialGradient id="iZDYxgc" cx="0" cy="0" r="1" gradientTransform="rotate(-40.741 20.168 -7.203)scale(4.71952 1.39407)" gradientUnits="userSpaceOnUse"><stop offset=".539" class="gl-yj8bin"/><stop offset="1" class="b1x_r2coy"/></radialGradient><radialGradient id="iHpB06c" cx="0" cy="0" r="1" gradientTransform="matrix(-.24783 2.63761 -1.05437 -.09907 22.617 11.222)" gradientUnits="userSpaceOnUse"><stop offset=".245" class="y4noiz6ri"/><stop offset="1" class="n64jnw11q"/></radialGradient><radialGradient id="iSz2hDb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .9205 -1.76711 0 14.42 13.78)" gradientUnits="userSpaceOnUse"><stop class="rlwq00h2l"/><stop offset="1" class="uhv9b32lc"/></radialGradient><radialGradient id="iVRPk8b" cx="0" cy="0" r="1" gradientTransform="matrix(0 .2578 -.81024 0 17.253 15.74)" gradientUnits="userSpaceOnUse"><stop class="ifoj0vbnx"/><stop offset="1" class="fd01o6-ig"/></radialGradient><radialGradient id="iDJxVDb" cx="0" cy="0" r="1" gradientTransform="rotate(156.092 7.085 9.409)scale(1.95475 3.14145)" gradientUnits="userSpaceOnUse"><stop offset=".702" class="xqbp6db-u"/><stop offset="1" class="l6ffphqdg"/><stop offset="1" class="bi0efq_rm"/></radialGradient><radialGradient id="iG3Ax6b" cx="0" cy="0" r="1" gradientTransform="matrix(2.30445 -1.13293 4.55811 9.27143 16.242 18.13)" gradientUnits="userSpaceOnUse"><stop offset=".562" class="i_5kuqxuv"/><stop offset="1" class="iazz9lb4s"/></radialGradient><radialGradient id="iSAdiyd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .85686 -1.36293 0 19.065 13.335)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="i8l3rMt" cx="0" cy="0" r="1" gradientTransform="matrix(-.24493 -.31563 .43455 -.33721 18.825 13.424)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iMgEHwb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8569 -1.363 0 14.456 13.335)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="ibu7EZQ" cx="0" cy="0" r="1" gradientTransform="matrix(-.00817 -.52182 .62724 -.00982 14.154 13.567)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iOp3uDb" cx="0" cy="0" r="1" gradientTransform="matrix(.66383 2.36919 -2.26039 .63334 21.638 13.35)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="k-8l2bbtm"/><stop offset="1" class="j8b6y4byx"/></radialGradient><radialGradient id="iHGACfc" cx="0" cy="0" r="1" gradientTransform="matrix(.832 -1.14178 .95704 .69738 22.018 13.925)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="gvb-xxmau"/><stop offset="1" class="wbdnw-owo"/></radialGradient><radialGradient id="iLuRz4b" cx="0" cy="0" r="1" gradientTransform="rotate(-69.263 21.282 -8.973)scale(1.75087 2.33941)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="nx86noq5t"/><stop offset="1" class="mchm9tbqp"/></radialGradient><radialGradient id="iFyxouJ" cx="0" cy="0" r="1" gradientTransform="matrix(-1.75133 0 0 -1.95561 11.57 14.027)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="ok_b4wzpx"/><stop offset="1" class="mtikk0bwo"/></radialGradient><radialGradient id="iUuTBYc" cx="0" cy="0" r="1" gradientTransform="rotate(170.258 5.188 7.508)scale(.98208 1.00692)" gradientUnits="userSpaceOnUse"><stop class="qkgshibem"/><stop offset="1" class="b89ok8b-l"/></radialGradient><radialGradient id="iMwhdrV" cx="0" cy="0" r="1" gradientTransform="matrix(-5.5 4.12501 -3.615 -4.82 20.719 4.576)" gradientUnits="userSpaceOnUse"><stop offset=".179" class="tg07-ljnl"/><stop offset="1" class="c6833cb9x"/></radialGradient><radialGradient id="i3dSYhb" cx="0" cy="0" r="1" gradientTransform="matrix(2.875 .375 -.58342 4.4729 10.781 7.701)" gradientUnits="userSpaceOnUse"><stop class="j8k1fac_p"/><stop offset="1" class="g8uem1b5g"/></radialGradient><radialGradient id="inl9J2c" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.875 8.03906 0 16.773 8.326)" gradientUnits="userSpaceOnUse"><stop offset=".761" class="km6q7kb1a"/><stop offset="1" class="i8skpb2jz"/></radialGradient><radialGradient id="iCE2gke" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.47656 -8.28125 0 18.406 7.912)" gradientUnits="userSpaceOnUse"><stop class="kzuil_5zu"/><stop offset="1" class="ok2r3obil"/></radialGradient><radialGradient id="ixSAAAe" cx="0" cy="0" r="1" gradientTransform="matrix(-7.1875 0 0 -.63281 21.269 9.87)" gradientUnits="userSpaceOnUse"><stop class="w63qn2bkh"/><stop offset="1" class="vvfum-_fa"/></radialGradient><radialGradient id="iy7tjOa" cx="0" cy="0" r="1" gradientTransform="matrix(3.48438 0 0 2.01172 9.003 10.109)" gradientUnits="userSpaceOnUse"><stop class="gfrsedb9v"/><stop offset="1" class="vke6kh8bt"/></radialGradient><filter id="i13oPwc" width="21.247" height="10.303" x="6.25" y="19.623" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.615686 0 0 0 0 0.607843 0 0 0 0 0.619608 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23852"/></filter><filter id="iDDl5Eb" width="2.078" height="2.078" x="15.622" y="27.457" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.792157 0 0 0 0 0.717647 0 0 0 0 0.788235 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_3987_23852"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_3987_23852" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.831373 0 0 0 0 0.745098 0 0 0 0 0.803922 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_3987_23852"/></filter><filter id="i2aIaNd" width="2.078" height="2.078" x="15.622" y="25.444" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.792157 0 0 0 0 0.717647 0 0 0 0 0.788235 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_3987_23852"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_3987_23852" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.831373 0 0 0 0 0.745098 0 0 0 0 0.803922 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_3987_23852"/></filter><filter id="i6NrRAb" width="6.554" height="3.702" x="13.38" y="19.523" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.721569 0 0 0 0 0.682353 0 0 0 0 0.74902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23852"/></filter><filter id="isn51ud" width="7.432" height="4.46" x="12.567" y="22.084" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23852" stdDeviation=".5"/></filter><filter id="iBGWFae" width="2.672" height="2.865" x="13.611" y="22.403" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.780392 0 0 0 0 0.270588 0 0 0 0 0.396078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23852"/></filter><filter id="i1FaHbn" width="2.672" height="2.865" x="17.264" y="22.403" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.780392 0 0 0 0 0.270588 0 0 0 0 0.396078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23852"/></filter><filter id="ikO3Ilc" width="1.554" height="1.999" x="15.986" y="22.812" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.827451 0 0 0 0 0.137255 0 0 0 0 0.317647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23852"/></filter><filter id="ikW2CXI" width="4.764" height="4.766" x="24.75" y="19.349" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.1"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.552941 0 0 0 0 0.364706 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23852"/></filter><filter id="iBblwwe" width="2.077" height="3.844" x="25.907" y="17.448" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.588235 0 0 0 0 0.403922 0 0 0 0 0.403922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23852"/></filter><filter id="iLIBlOI" width="2.401" height="4.052" x="24.436" y="17.107" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.588235 0 0 0 0 0.403922 0 0 0 0 0.403922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23852"/></filter><filter id="iLCPe0c" width="2.312" height="4.044" x="23.386" y="17.96" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.588235 0 0 0 0 0.403922 0 0 0 0 0.403922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23852"/></filter><filter id="ifSo5Yb" width="2.123" height="3.114" x="22.394" y="19.041" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.588235 0 0 0 0 0.403922 0 0 0 0 0.403922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23852"/></filter><filter id="i84rtgc" width="3.002" height="3.147" x="6.649" y="16.347" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.537255 0 0 0 0 0.360784 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23852"/></filter><filter id="i31mfrc" width="1.264" height="2.491" x="22.908" y="19.19" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23852" stdDeviation=".125"/></filter><filter id="iM3pRHq" width="1.286" height="2.978" x="23.933" y="18.124" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23852" stdDeviation=".125"/></filter><filter id="iPgKdub" width="1.444" height="3.775" x="24.963" y="17.226" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23852" stdDeviation=".125"/></filter><filter id="itAdVic" width="1.17" height="3.014" x="26.424" y="17.706" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23852" stdDeviation=".125"/></filter><filter id="iZDnoMl" width="1.788" height="2.6" x="27.33" y="19.87" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23852" stdDeviation=".125"/></filter><filter id="i29dLze" width="2.323" height="1.69" x="3.752" y="19.44" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23852" stdDeviation=".125"/></filter><filter id="i6Q3C9b" width="2.342" height="2.022" x="3.291" y="18.151" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23852" stdDeviation=".125"/></filter><filter id="iEAAnQd" width="2.131" height="2.124" x="4.556" y="16.714" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23852" stdDeviation=".125"/></filter><filter id="igdwpBb" width="2.569" height="2.444" x="3.345" y="17.042" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23852" stdDeviation=".125"/></filter><filter id="i1FBRNc" width="5.441" height="3.076" x="17.747" y="6.733" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23852" stdDeviation=".375"/></filter><filter id="iPTVr7d" width="5.461" height="3.084" x="17.805" y="6.608" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23852" stdDeviation=".375"/></filter><filter id="iqfTife" width="11.794" height="13.134" x="11.414" y="7.786" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".7"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.584314 0 0 0 0 0.427451 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23852"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.419608 0 0 0 0 0.25098 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23852" result="effect2_innerShadow_3987_23852"/></filter><filter id="isySrbb" width="3.845" height="5.063" x="14.688" y="12.433" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23852" stdDeviation=".5"/></filter><filter id="iM7gwgb" width="2.383" height="3.463" x="15.569" y="13.026" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23852" stdDeviation=".1"/></filter><filter id="iVdXK6E" width="3.899" height="1.633" x="14.811" y="16.746" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23852" stdDeviation=".05"/></filter><filter id="iZSiK9b" width="12.975" height="8.798" x="10.268" y="4.459" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.266667 0 0 0 0 0.152941 0 0 0 0 0.184314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23852"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.258824 0 0 0 0 0.133333 0 0 0 0 0.172549 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23852" result="effect2_innerShadow_3987_23852"/></filter><filter id="iC0aShd" width="2.465" height="1.246" x="18.439" y="10.959" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.243137 0 0 0 0 0.121569 0 0 0 0 0.2 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23852"/></filter><filter id="id5fyeb" width="2.465" height="1.231" x="12.888" y="10.975" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.243137 0 0 0 0 0.121569 0 0 0 0 0.2 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23852"/></filter><filter id="iItBPQd" width=".82" height=".724" x="18.296" y="12.876" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23852" stdDeviation=".05"/></filter><filter id="ij3fSCe" width=".919" height=".942" x="19.188" y="12.962" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23852" stdDeviation=".1"/></filter><filter id="iFVAF6c" width="1.019" height="1.076" x="14.496" y="12.894" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23852" stdDeviation=".1"/></filter><filter id="iE2Ajxb" width=".953" height=".733" x="13.693" y="12.868" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23852" stdDeviation=".05"/></filter><filter id="iHwHtge" width="1.375" height="2.485" x="10.353" y="12.788" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23852" stdDeviation=".125"/></filter><filter id="iHHqmgc" width="1.851" height="2.856" x="21.595" y="12.594" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23852" stdDeviation=".25"/></filter><filter id="ik5PE3O" width="2.498" height="1.183" x="12.824" y="11.063" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23852" stdDeviation=".125"/></filter><filter id="izzG3ee" width="2.498" height="1.183" x="18.438" y="11.005" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23852" stdDeviation=".125"/></filter><linearGradient id="iK84mBb" x1="22.562" x2="21.812" y1="29.826" y2="29.826" gradientUnits="userSpaceOnUse"><stop class="fr__qmhjc"/><stop offset="1" class="gypp10kih"/></linearGradient><linearGradient id="iWCiqKd" x1="20.644" x2="21.062" y1="29.014" y2="29.014" gradientUnits="userSpaceOnUse"><stop class="hj-s-zboe"/><stop offset="1" class="s0umluqbl"/></linearGradient><linearGradient id="ipodSkc" x1="9.531" x2="4.906" y1="27.451" y2="27.451" gradientUnits="userSpaceOnUse"><stop class="sb-ednb_a"/><stop offset="1" class="v0501vbqa"/></linearGradient><linearGradient id="iXPTZOc" x1="9.75" x2="8.828" y1="27.076" y2="27.076" gradientUnits="userSpaceOnUse"><stop class="o_30au2yc"/><stop offset="1" class="c60cvac3k"/></linearGradient><linearGradient id="itP1zjc" x1="27.871" x2="22.844" y1="28.142" y2="28.142" gradientUnits="userSpaceOnUse"><stop class="i7zyuv8vr"/><stop offset=".907" class="qzhltkbuo"/></linearGradient><linearGradient id="i33ZCUz" x1="28.09" x2="27.168" y1="27.876" y2="27.876" gradientUnits="userSpaceOnUse"><stop class="tub8lbbfx"/><stop offset="1" class="bd09vtb_c"/></linearGradient><linearGradient id="i8tJXGc" x1="16.763" x2="16.763" y1="22.812" y2="24.81" gradientUnits="userSpaceOnUse"><stop offset=".351" class="gzsz7evmk"/><stop offset="1" class="smgiue0gi"/></linearGradient><linearGradient id="ioZXgLe" x1="29.13" x2="28.38" y1="20.034" y2="21.659" gradientUnits="userSpaceOnUse"><stop class="zrsmq2u6o"/><stop offset="1" class="mcp_a12ev"/><stop offset="1" class="qg7eszk4c"/></linearGradient><linearGradient id="i4O2smb" x1="4.76" x2="5.331" y1="20.169" y2="21.223" gradientUnits="userSpaceOnUse"><stop class="m0zt7_pbu"/><stop offset="1" class="s9u0fjbul"/></linearGradient><linearGradient id="iz0d3ff" x1="4.307" x2="5.218" y1="19" y2="20.223" gradientUnits="userSpaceOnUse"><stop class="m0zt7_pbu"/><stop offset="1" class="s9u0fjbul"/></linearGradient><linearGradient id="iJwKJNb" x1="5.489" x2="6.52" y1="17.6" y2="18.693" gradientUnits="userSpaceOnUse"><stop class="m0zt7_pbu"/><stop offset="1" class="s9u0fjbul"/></linearGradient><linearGradient id="ivFlTre" x1="4.452" x2="5.734" y1="18.044" y2="19.502" gradientUnits="userSpaceOnUse"><stop class="m0zt7_pbu"/><stop offset="1" class="s9u0fjbul"/></linearGradient><linearGradient id="i569ddd" x1="22.207" x2="19.537" y1="16.083" y2="16.083" gradientUnits="userSpaceOnUse"><stop class="cgoojyxdz"/><stop offset="1" class="zvhz6qbam"/></linearGradient><linearGradient id="iK8OnYd" x1="16.811" x2="16.811" y1="10.732" y2="11.888" gradientUnits="userSpaceOnUse"><stop offset=".14" class="oj0uzzlvl"/><stop offset="1" class="qy5yuhbvq"/></linearGradient><linearGradient id="iv1RleS" x1="17.646" x2="16.761" y1="15.016" y2="15.053" gradientUnits="userSpaceOnUse"><stop offset=".36" class="gb7af0bvz"/><stop offset="1" class="gafrz43pc"/></linearGradient><linearGradient id="iq1Y8se" x1="16.761" x2="16.761" y1="16.219" y2="15.728" gradientUnits="userSpaceOnUse"><stop class="q7066kb0m"/><stop offset="1" class="se5f_fbvx"/></linearGradient><linearGradient id="izNgxkc" x1="16.761" x2="16.761" y1="13.362" y2="13.939" gradientUnits="userSpaceOnUse"><stop class="bl4x47bvc"/><stop offset="1" class="nv0opqb4i"/></linearGradient><linearGradient id="iSr2O9S" x1="15.492" x2="15.828" y1="17.878" y2="16.997" gradientUnits="userSpaceOnUse"><stop class="sjwz8ccmm"/><stop offset="1" class="itcx93bci"/></linearGradient><linearGradient id="ilkbyyb" x1="23.997" x2="11.733" y1="8.323" y2="8.323" gradientUnits="userSpaceOnUse"><stop offset=".471" class="vj4yuc0qg"/><stop offset="1" class="yd6vs-kvu"/></linearGradient><linearGradient id="iZfDgPd" x1="19.887" x2="19.555" y1="13.393" y2="13.597" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iONlpjd" x1="15.242" x2="14.911" y1="13.392" y2="13.596" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ipdnd0m" x1="23.558" x2="22.284" y1="13.421" y2="15.719" gradientUnits="userSpaceOnUse"><stop class="r-tgpdb_v"/><stop offset="1" class="o8077h_4a"/></linearGradient><linearGradient id="idHz03h" x1="10.583" x2="12.123" y1="14.164" y2="14.03" gradientUnits="userSpaceOnUse"><stop class="d7c3jfbwh"/><stop offset="1" class="zvm05wbin"/></linearGradient><linearGradient id="isf4a1d" x1="22.52" x2="22.52" y1="13.094" y2="14.951" gradientUnits="userSpaceOnUse"><stop class="aj8ithlra"/><stop offset="1" class="a9_46dbsd"/></linearGradient><linearGradient id="izP9Z9c" x1="16.773" x2="16.773" y1="7.912" y2="8.1" gradientUnits="userSpaceOnUse"><stop class="jhlen960d"/><stop offset="1" class="wjchuwb6a"/></linearGradient><linearGradient id="iYE2hsb" x1="17.956" x2="17.956" y1="10.98" y2="10.214" gradientUnits="userSpaceOnUse"><stop class="bl3fq0x9z"/><stop offset="1" class="lxo7c2i6k"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-juggling-medium" /></template>
<style>
.a5zzorbzd {
  stop-color: var(--svg-color--e1ac3a, #E1AC3A);
}

.a65rs5a6h {
  stroke: var(--svg-color--b69386, #B69386);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-35px, 0.35px);
  d: path("m24.358 18.55l.436 2.127");
}

.a9_46dbsd {
  stop-color: var(--svg-color--ad806f, #AD806F);
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

.aj8ithlra {
  stop-color: var(--svg-color--ac7f6f, #AC7F6F);
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

.b-hh4tbue {
  stroke: var(--svg-color--553f3f, #553F3F);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M20.56 11.813c-.27-.195-.947-.537-1.747-.403");
}

.b057dp4eh {
  stop-color: var(--svg-color--ccbdde, #CCBDDE);
}

.b1x_r2coy {
  stop-color: var(--svg-color--63413d, #63413D);
  stop-opacity: 0;
}

.b1xnaurjw {
  stop-color: var(--svg-color--b38f7a, #B38F7A);
}

.b89ok8b-l {
  stop-color: var(--svg-color--784e52, #784E52);
}

.bbyb_mbsk {
  stop-color: var(--svg-color--664842, #664842);
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

.bi0efq_rm {
  stop-color: var(--svg-color--8a5f5c, #8A5F5C);
}

.bl3fq0x9z {
  stop-color: var(--svg-color--543459, #543459);
}

.bl4x47bvc {
  stop-color: var(--svg-color--a4786e, #A4786E);
}

.blko_hazg {
  stop-color: var(--svg-color--a6846b, #A6846B);
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

.c-0f6obbw {
  stop-color: var(--svg-color--987064, #987064);
  stop-opacity: 0;
}

.c2gpet42m {
  d: path("M21.895 15.623c.354-.011.686-.131.956-.326v.984c0 .943-.562 1.783-1.417 2.132q.271-.576.366-1.246z");
}

.c3gr2ccfh {
  d: path("M11.627 15.623a1.73 1.73 0 0 1-.956-.326v.984c0 .943.562 1.783 1.416 2.132q-.271-.576-.365-1.246z");
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

.cgoojyxdz {
  stop-color: var(--svg-color--c2987e, #C2987E);
}

.ci3gi1b_k {
  stop-color: var(--svg-color--784b89, #784B89);
  stop-opacity: 0;
}

.ckv4qxbrn {
  d: path("M15.315 13.663c0-.304-.247-.507-.314-.569l-.305.295l.188.381z");
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

.d5_x4xk7i {
  fill-rule: evenodd;
  d: path("M3.16 17.066a.75.75 0 0 1 1.042.197q.055.08.116.173c.17.259.379.576.676.877c.36.363.768.614 1.246.64a.75.75 0 0 1-.08 1.497c-.99-.052-1.73-.575-2.232-1.083c-.416-.42-.725-.893-.888-1.143l-.076-.115a.75.75 0 0 1 .196-1.043");
}

.d7c3jfbwh {
  stop-color: var(--svg-color--855d5a, #855D5A);
}

.d7caiobkz {
  stop-color: var(--svg-color--e4cc30, #E4CC30);
  stop-opacity: 0;
}

.demkpcl0k {
  stop-color: var(--svg-color--b1a0b8, #B1A0B8);
}

.dklp1oekh {
  d: path("M16.76 17.362a3.2 3.2 0 0 1-1.462-.347c-.145-.073-.3.09-.21.221a2 2 0 0 0 1.673.893a2 2 0 0 0 1.672-.893c.091-.137-.064-.294-.209-.22c-.423.22-.922.346-1.463.346");
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

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.ep9ttx4ds {
  fill: var(--svg-color--462d2b, #462D2B);
  d: path("M20.703 11.691c-.185-.16-.4-.332-.726-.434c-.322-.101-.724-.128-1.28-.06a.293.293 0 0 0 .07.581c.509-.062.82-.03 1.034.038c.21.066.35.172.517.317a.293.293 0 1 0 .385-.442");
}

.exfuzbt0n {
  stop-color: var(--svg-color--8a4d60, #8A4D60);
}

.eyqrsfcva {
  fill: var(--svg-color--a3776d, #A3776D);
  d: path("m16.357 13.548l-.561 1.942c-.115.399.16.798.55.798h.83c.39 0 .664-.405.55-.798l-.561-1.942c-.12-.43-.682-.43-.808 0");
}

.f-dh8j4tm {
  fill: var(--svg-color--462d2b, #462D2B);
  d: path("M13.158 11.576a2.93 2.93 0 0 1 1.837-.38a.293.293 0 1 1-.071.582a2.34 2.34 0 0 0-1.465.301l-.097.063l-.003.002a.293.293 0 0 1-.358-.463z");
}

.f0o-9fbtc {
  stop-color: var(--svg-color--985682, #985682);
  stop-opacity: 0;
}

.f21vmbcik {
  d: path("M5.437 21.764h4.094v8.063H5.437z");
}

.fd01o6-ig {
  stop-color: var(--svg-color--c59a8a, #C59A8A);
  stop-opacity: 0;
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

.fvjz8xbso {
  d: path("M14.454 12.832a.943.943 0 0 0-.908 1.19h1.82a1 1 0 0 0 .035-.248a.95.95 0 0 0-.947-.942");
}

.fzq016boz {
  stop-color: var(--svg-color--e35838, #E35838);
}

.g101ufbyh {
  stop-color: var(--svg-color--8f5d66, #8F5D66);
}

.g8uem1b5g {
  stop-color: var(--svg-color--38303e, #38303E);
  stop-opacity: 0;
}

.g9e006slv {
  stroke: var(--svg-color--553f3f, #553F3F);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M13.199 11.872c.271-.195.948-.538 1.748-.403");
}

.gafrz43pc {
  stop-color: var(--svg-color--cea58c, #CEA58C);
  stop-opacity: 0;
}

.gb7af0bvz {
  stop-color: var(--svg-color--cea58c, #CEA58C);
}

.gfrsedb9v {
  stop-color: var(--svg-color--5b595e, #5B595E);
}

.ghjd91i9b {
  fill: var(--svg-color--fff, #fff);
  d: path("M14.236 12.544c-.69 0-1.273.476-1.431 1.119a.29.29 0 0 0 .283.36h2.356c.15 0 .27-.137.24-.287a1.48 1.48 0 0 0-1.448-1.192");
}

.gl-yj8bin {
  stop-color: var(--svg-color--63413d, #63413D);
}

.gr0wzobbs {
  stop-color: var(--svg-color--dbcdd4, #DBCDD4);
  stop-opacity: 0;
}

.gt8hc6nxf {
  fill: var(--svg-color--000, #000);
  d: path("M18.528 13.774c0-.3.24-.54.54-.54a.538.538 0 0 1 .48.789h-.956a.5.5 0 0 1-.064-.249");
}

.gvb-xxmau {
  stop-color: var(--svg-color--9e6a5c, #9E6A5C);
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

.hb-rh6b9c {
  stop-color: var(--svg-color--493b3b, #493B3B);
}

.hcmh5c50b {
  stop-color: var(--svg-color--357ace, #357ACE);
}

.hdsgirtov {
  stop-color: var(--svg-color--c89980, #C89980);
}

.hj-s-zboe {
  stop-color: var(--svg-color--6d5096, #6D5096);
}

.hpfqe6rjh {
  cx: 6.332px;
  cy: 12.838px;
  r: 1.684px;
}

.hs7yh0bot {
  d: path("M19.907 13.65a.9.9 0 0 0-.244-.488l-.275.3l.124.242z");
}

.ht6lpfbpp {
  d: path("M18.68 22.463c-.909.308-1.267.83-1.388 1.082l-.028.29l.028.359c.12.25.48.706 1.388 1.014c.362.123.778.068.971-.267c.14-.243.284-.599.284-1.105c0-.507-.144-.862-.284-1.106c-.193-.335-.61-.39-.97-.267");
}

.hw860-bkw {
  d: path("M22.993 22.213c.119.463.586 1.456.805 1.894h4.047l-.258-3.789l-4.836.924c.031.13.123.507.242.97");
}

.hzaq54bmy {
  fill: var(--svg-color--49373d, #49373D);
  d: path("M21.252 8.376h-2.19a.508.508 0 1 1 .082-1.011c.568.09 1.322.216 1.827.341c1.142.284 1.457.84 1.545 1.236a1.6 1.6 0 0 0-1.264-.566");
}

.i_5kuqxuv {
  stop-color: var(--svg-color--87014e, #87014E);
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

.iazz9lb4s {
  stop-color: var(--svg-color--87004d, #87004D);
}

.if4bi9b9w {
  cx: 14.17px;
  cy: 13.235px;
  rx: 0.411px;
  ry: 0.208px;
}

.ifoj0vbnx {
  stop-color: var(--svg-color--c59a8a, #C59A8A);
}

.itcx93bci {
  stop-color: var(--svg-color--ab817b, #AB817B);
  stop-opacity: 0;
}

.iwbygtbvw {
  cx: 25.211px;
  cy: 4.873px;
  r: 1.684px;
}

.j213y8b_z {
  stop-color: var(--svg-color--926763, #926763);
}

.j5-qsy2fi {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M15.332 16.949a.236.236 0 0 0-.282.048a.22.22 0 0 0-.024.281a2.08 2.08 0 0 0 1.735.927c.728 0 1.367-.371 1.735-.927a.22.22 0 0 0-.025-.283a.24.24 0 0 0-.281-.047a3.1 3.1 0 0 1-1.43.34a3.1 3.1 0 0 1-1.428-.34Z");
}

.j70rp9pis {
  d: path("M22.222 29.826h-1.578v-9.568q.826.307 1.578.746z");
}

.j8b6y4byx {
  stop-color: var(--svg-color--9a676a, #9A676A);
}

.j8k1fac_p {
  stop-color: var(--svg-color--5b5a5d, #5B5A5D);
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

.jk__z2bxx {
  d: path("M11.39 13.038a1.01 1.01 0 0 0 .088 1.984a82 82 0 0 1-.088-1.984");
}

.jknxnjb8w {
  stop-color: var(--svg-color--95646c, #95646C);
}

.jm40s5baz {
  stop-color: var(--svg-color--968f9c, #968F9C);
  stop-opacity: 0;
}

.jon81gnkc {
  stop-color: var(--svg-color--af887b, #AF887B);
  stop-opacity: 0;
}

.jsxbyvb_p {
  d: path("M18.998 13.03c.067.09-.073.2-.233.32c-.16.119-.278.203-.345.113s.008-.26.168-.379c.16-.12.343-.143.41-.053");
}

.jwq5cabxr {
  stop-color: var(--svg-color--765443, #765443);
}

.k-8l2bbtm {
  stop-color: var(--svg-color--9a676a, #9A676A);
  stop-opacity: 0;
}

.k1soseb1u {
  d: path("M14.545 18.417c0-.99.9-1.794 2.012-1.794c1.11 0 2.012.803 2.012 1.794v2.326c0 .99-.901 1.794-2.012 1.794s-2.012-.803-2.012-1.794z");
}

.km6q7kb1a {
  stop-color: var(--svg-color--5d5565, #5D5565);
  stop-opacity: 0;
}

.koq0r9bvu {
  stop-color: var(--svg-color--9e78c9, #9E78C9);
}

.ku63lg_wt {
  stop-color: var(--svg-color--e8e2ec, #E8E2EC);
}

.kud2-ccnc {
  stop-color: var(--svg-color--ab7872, #AB7872);
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

.l6ffphqdg {
  stop-color: var(--svg-color--744a4a, #744A4A);
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

.ljv0l9wbv {
  stop-color: var(--svg-color--a87b73, #A87B73);
}

.lnmij5brh {
  fill: var(--svg-color--fff, #fff);
  d: path("M19.286 12.544c.69 0 1.272.476 1.431 1.119a.29.29 0 0 1-.283.36h-2.356a.243.243 0 0 1-.24-.287a1.476 1.476 0 0 1 1.448-1.192");
}

.lwi963zwv {
  d: path("M21.888 7.288c.543.187-.308 1.385 0 1.929c.493.866 1.759 1.084 1.227 1.849a1.65 1.65 0 0 0-.286.923v1.255a1.8 1.8 0 0 0-.704-.283l.082-1.697a1.53 1.53 0 0 0-1.456-1.512h-1.479a2.56 2.56 0 0 1-2.335-1.524a.7.7 0 0 0-.65-.442h-1.345c-1.949 0-3.529 1.598-3.529 3.569l.033 1.624a1.8 1.8 0 0 0-.76.278v-1.268c0-.328-.102-.651-.286-.923c-.505-.742.57-.912 1.014-1.756c.308-.583-.36-1.818.207-2.017a2.83 2.83 0 0 0 1.462-1.172a2.456 2.456 0 0 1 3.053-.963c.403.175.857.175 1.26 0c.297-.125.622-.199.963-.199c.89 0 1.67.482 2.1 1.196c.326.538.835.929 1.43 1.133");
}

.lxo7c2i6k {
  stop-color: var(--svg-color--462f5a, #462F5A);
  stop-opacity: 0;
}

.m-1-e5bla {
  stop-color: var(--svg-color--fbf2f7, #FBF2F7);
}

.m0zt7_pbu {
  stop-color: var(--svg-color--c7a08f, #C7A08F);
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

.mchm9tbqp {
  stop-color: var(--svg-color--a47f62, #A47F62);
}

.mcp_a12ev {
  stop-color: var(--svg-color--997971, #997971);
  stop-opacity: 0;
}

.mmq2utbuk {
  stop-color: var(--svg-color--cf8b51, #CF8B51);
}

.mpwbs5b3u {
  stop-color: var(--svg-color--ff894e, #FF894E);
}

.mtikk0bwo {
  stop-color: var(--svg-color--9d7667, #9D7667);
}

.mug1r-bxu {
  stop-color: var(--svg-color--b58f71, #B58F71);
}

.n297mkbnr {
  stop-color: var(--svg-color--d6d3d7, #D6D3D7);
  stop-opacity: 0;
}

.n64jnw11q {
  stop-color: var(--svg-color--bf9980, #BF9980);
  stop-opacity: 0;
}

.ng1cexbhj {
  stop-color: var(--svg-color--b6424c, #B6424C);
}

.nl0wbpawx {
  stop-color: var(--svg-color--968f9c, #968F9C);
}

.nuzlzbt9j {
  d: path("M11.665 17.224a4.136 4.136 0 0 0 4.104 3.596h1.992a4.136 4.136 0 0 0 4.104-3.596c.125-1.99.25-3.971.343-5.96a1.53 1.53 0 0 0-1.457-1.512h-1.479a2.56 2.56 0 0 1-2.335-1.524a.7.7 0 0 0-.65-.442h-1.345c-1.949 0-3.528 1.598-3.528 3.569c0 1.965.122 3.898.251 5.869");
}

.nv0opqb4i {
  stop-color: var(--svg-color--a4786e, #A4786E);
  stop-opacity: 0;
}

.nvnpqub-x {
  d: path("M22.095 14.95q.051-.927.1-1.856c.423.058.75.45.75.925c0 .512-.38.927-.85.932");
}

.nx86noq5t {
  stop-color: var(--svg-color--a47f62, #A47F62);
  stop-opacity: 0;
}

.o_30au2yc {
  stop-color: var(--svg-color--decfd8, #DECFD8);
}

.o415o878f {
  stop-color: var(--svg-color--ef4c8b, #EF4C8B);
}

.o5jc2cxps {
  stop-color: var(--svg-color--311f2c, #311F2C);
}

.o8077h_4a {
  stop-color: var(--svg-color--b08175, #B08175);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ofu8odbdi {
  stop-color: var(--svg-color--8f5d66, #8F5D66);
  stop-opacity: 0;
}

.oj0uzzlvl {
  stop-color: var(--svg-color--815257, #815257);
}

.ok_b4wzpx {
  stop-color: var(--svg-color--9d7667, #9D7667);
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

.otf1mnoto {
  stop-color: var(--svg-color--985682, #985682);
}

.p4atghb8h {
  fill: var(--svg-color--c59883, #C59883);
  d: path("m27.85 19.83l-.447.824l-1.172 1.422l-1.481 1.992l3.099.047c.099-.172.218-.566.38-1.327c.164-.66.326-1.114.471-1.376l.443-.924a.726.726 0 0 0-1.292-.659");
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

.prlk-hzei {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.998 13.03c.067.09-.073.2-.233.32c-.16.119-.278.203-.345.113s.008-.26.168-.379c.16-.12.343-.143.41-.053");
}

.pt8frltpn {
  stop-color: var(--svg-color--7060a5, #7060A5);
}

.q4oz8ebqu {
  stop-color: var(--svg-color--987064, #987064);
}

.q7066kb0m {
  stop-color: var(--svg-color--9c6376, #9C6376);
}

.qg7eszk4c {
  stop-color: var(--svg-color--caa48f, #CAA48F);
  stop-opacity: 0;
}

.qjdbe6bhy {
  stop-color: var(--svg-color--ab7872, #AB7872);
  stop-opacity: 0;
}

.qkgshibem {
  stop-color: var(--svg-color--714b4d, #714B4D);
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

.qy4rrcb8b {
  d: path("M12.857 29.826h-1.578v-8.795a10 10 0 0 1 1.578-.756z");
}

.qy5yuhbvq {
  stop-color: var(--svg-color--9a6f68, #9A6F68);
  stop-opacity: 0;
}

.qzd219blo {
  d: path("M11 8.662a5.773 5.773 0 1 1 11.547 0v1.648H11z");
}

.qzhltkbuo {
  stop-color: var(--svg-color--b9aac8, #B9AAC8);
}

.r-tgpdb_v {
  stop-color: var(--svg-color--c9a188, #C9A188);
}

.rlwq00h2l {
  stop-color: var(--svg-color--9e7765, #9E7765);
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

.se5f_fbvx {
  stop-color: var(--svg-color--9c6376, #9C6376);
  stop-opacity: 0;
}

.sjwz8ccmm {
  stop-color: var(--svg-color--ab817b, #AB817B);
}

.sjxmvib4j {
  stop-color: var(--svg-color--82604e, #82604E);
}

.smgiue0gi {
  stop-color: var(--svg-color--c93857, #C93857);
}

.smnqffnel {
  stop-color: var(--svg-color--95646c, #95646C);
  stop-opacity: 0;
}

.swka_j87x {
  d: path("M6.25 29.826c0-5.635 4.568-10.203 10.203-10.203h.64c5.636 0 10.204 4.568 10.204 10.203z");
}

.t-5nldk3g {
  cx: 16.761px;
  cy: 28.296px;
  r: 0.739px;
}

.t1yb008wo {
  d: path("M11.434 12.335c-.826.116-1.47.83-1.47 1.688a1.7 1.7 0 0 0 1.605 1.697a83 83 0 0 1-.136-3.385");
}

.tg07-ljnl {
  stop-color: var(--svg-color--5e5764, #5E5764);
}

.tn_97qkdc {
  stop-color: var(--svg-color--f2c341, #F2C341);
  stop-opacity: 0;
}

.tub8lbbfx {
  stop-color: var(--svg-color--e0dde3, #E0DDE3);
}

.tuxkwlbzf {
  d: path("m16.357 13.548l-.561 1.942c-.115.399.16.798.55.798h.83c.39 0 .664-.405.55-.798l-.561-1.942c-.12-.43-.682-.43-.808 0");
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

.uh87n4b_i {
  d: path("M21.959 15.719q.106-1.685.195-3.37a1.7 1.7 0 0 1-.195 3.37");
}

.uhv9b32lc {
  stop-color: var(--svg-color--9e7765, #9E7765);
  stop-opacity: 0;
}

.ujrq6ixuu {
  stop-color: var(--svg-color--beb4c6, #BEB4C6);
}

.v_2gjcb5l {
  stop-color: var(--svg-color--4c3c39, #4C3C39);
}

.v0501vbqa {
  stop-color: var(--svg-color--c0b5cd, #C0B5CD);
}

.v3vg2fbhx {
  stop-color: var(--svg-color--af887b, #AF887B);
}

.v71pqg4ed {
  d: path("M19.067 12.832a.943.943 0 0 1 .909 1.19h-1.821a.946.946 0 0 1 .912-1.191");
}

.va-8to-0f {
  stop-color: var(--svg-color--c69985, #C69985);
}

.vcz9qnm9q {
  fill: var(--svg-color--504a4c, #504A4C);
  d: path("M21.18 8.495h-2.178a.505.505 0 1 1 .08-1.005c.566.09 1.316.215 1.818.34c1.136.281 1.45.834 1.538 1.229a1.58 1.58 0 0 0-1.258-.564");
}

.vdngsab5t {
  fill-rule: evenodd;
  d: path("M3.416 19.34a.75.75 0 0 1 1.051.14c.244.317.833.881 1.8.881a.75.75 0 0 1 .75.75c0 .415-.336.67-.75.67c-1.683 0-2.593-.87-2.99-1.39a.75.75 0 0 1 .139-1.05");
}

.vj4yuc0qg {
  stop-color: var(--svg-color--614440, #614440);
}

.vke6kh8bt {
  stop-color: var(--svg-color--3e3843, #3E3843);
  stop-opacity: 0;
}

.vvfum-_fa {
  stop-color: var(--svg-color--392f42, #392F42);
}

.vzzhqfd0u {
  stop-color: var(--svg-color--2e1c2e, #2E1C2E);
}

.w4ky7s-1q {
  stop-color: var(--svg-color--ac7b71, #AC7B71);
}

.w63qn2bkh {
  stop-color: var(--svg-color--605966, #605966);
}

.wbdnw-owo {
  stop-color: var(--svg-color--9e6a5c, #9E6A5C);
  stop-opacity: 0;
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

.xnf9zsbcq {
  fill: var(--svg-color--ab8178, #AB8178);
  d: path("M22.414 19.881a.681.681 0 1 1 1.33-.294l.36 1.794a.645.645 0 0 1-1.26.279z");
}

.xntzq-4ho {
  stop-color: var(--svg-color--8566b5, #8566B5);
}

.xqbp6db-u {
  stop-color: var(--svg-color--8a5f5c, #8A5F5C);
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

.y-ob1pbsd {
  fill: var(--svg-color--000, #000);
  d: path("M14.994 13.774c0-.3-.24-.54-.54-.54a.538.538 0 0 0-.48.789h.956a.54.54 0 0 0 .064-.249");
}

.y05rrkbkk {
  stop-color: var(--svg-color--ffff54, #FFFF54);
}

.y2ly1lryk {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-35px, 0.35px);
  d: path("M3.716 18.576c.177.245.672.953 1.492 1.172");
}

.y4noiz6ri {
  stop-color: var(--svg-color--bf9980, #BF9980);
}

.yd6vs-kvu {
  stop-color: var(--svg-color--543f3c, #543F3C);
}

.ym-b_m9fy {
  stop-color: var(--svg-color--d1bed4, #D1BED4);
  stop-opacity: 0;
}

.yt9en_n3k {
  stop-color: var(--svg-color--9b7368, #9B7368);
  stop-opacity: 0;
}

.zdcorrl9x {
  cx: 26.234px;
  cy: 14.83px;
  r: 1.684px;
}

.zdzom5a9w {
  cx: 14.17px;
  cy: 13.235px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.411px;
  ry: 0.208px;
}

.zrsmq2u6o {
  stop-color: var(--svg-color--caa48f, #CAA48F);
}

.zueu3mftc {
  fill: var(--svg-color--6f3f46, #6F3F46);
  d: path("m16.337 13.755l-.624 1.942c-.107.4.149.798.511.798h.773c.363 0 .618-.405.512-.798l-.523-1.942c-.111-.43-.532-.43-.65 0");
}

.zvhz6qbam {
  stop-color: var(--svg-color--c2987e, #C2987E);
  stop-opacity: 0;
}

.zvm05wbin {
  stop-color: var(--svg-color--7d4d5b, #7D4D5B);
}

</style>
