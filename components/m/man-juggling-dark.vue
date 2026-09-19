<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#ivjWlxQ)"><path fill="url(#iPYYWhe)" class="swka_j87x"/><path fill="url(#iT07jwd)" class="swka_j87x"/><path fill="url(#il5eVUq)" class="swka_j87x"/><path fill="url(#iY3yYtd)" class="swka_j87x"/><path fill="url(#iv8FoOX)" class="swka_j87x"/></g><circle fill="url(#iBZ0RUd)" class="hpfqe6rjh"/><circle fill="url(#itKlKTd)" class="hpfqe6rjh"/><circle fill="url(#ihlr5IT)" class="duyhuibwk"/><circle fill="url(#iGUmgWd)" class="duyhuibwk"/><circle fill="url(#iXhqZHd)" class="iwbygtbvw"/><circle fill="url(#iOHvRJe)" class="iwbygtbvw"/><circle fill="url(#issuNue)" class="zdcorrl9x"/><circle fill="url(#iMaLBhb)" class="zdcorrl9x"/><circle fill="url(#iAhrvZc)" class="zdcorrl9x"/><g filter="url(#ikFtPJc)"><circle fill="url(#iMk8UMb)" class="t-5nldk3g"/></g><g filter="url(#iQI5HQe)"><circle fill="url(#iR23Gge)" class="don2wdpjw"/></g><path fill="url(#i5YvaPc)" class="j70rp9pis"/><path fill="url(#iK84mBb)" class="j70rp9pis"/><path fill="url(#iWCiqKd)" class="j70rp9pis"/><path fill="url(#ieol8Me)" class="qy4rrcb8b"/><path fill="url(#iDbbcbc)" class="qy4rrcb8b"/><path fill="url(#iOe2zrd)" class="qy4rrcb8b"/><path fill="url(#iV71Rbc)" class="qy4rrcb8b"/><g filter="url(#imykPwt)"><path fill="url(#iObplQb)" class="ggm3_setj"/><path fill="url(#iQpTAtb)" class="ggm3_setj"/></g><path fill="url(#ipodSkc)" class="f21vmbcik"/><path fill="url(#iXPTZOc)" class="f21vmbcik"/><path fill="url(#itP1zjc)" class="wp2p6dbcv"/><path fill="url(#i33ZCUz)" class="wp2p6dbcv"/><g filter="url(#i0Hwnod)"><path clip-rule="evenodd" class="byn6wubog"/></g><g filter="url(#iDf870c)"><path fill="url(#iSAsI1d)" class="ctsppjbax"/><path fill="url(#iwtPTOo)" class="ctsppjbax"/><path fill="url(#isAdhHe)" class="ctsppjbax"/></g><g filter="url(#ilnfgHe)"><path fill="url(#ivLP6Gc)" class="ht6lpfbpp"/><path fill="url(#iXetYud)" class="ht6lpfbpp"/></g><g filter="url(#iM3qzqd)"><path fill="url(#i8tJXGc)" class="ld_83jb7a"/><path fill="url(#iw9bnJb)" class="ld_83jb7a"/></g><g filter="url(#iAH8nTf)"><path class="wr17kemdy"/></g><g filter="url(#iK3gnrs)"><path class="y2f_cuplr"/></g><g filter="url(#id8LBbb)"><path class="t62nyv9ws"/></g><g filter="url(#iO0pEyW)"><path class="j5vd_ebrq"/></g><g filter="url(#iGNrBic)"><path class="fazjy714p"/></g><path fill="url(#ihpEqzz)" class="gvcddab8z"/><path fill="url(#ipszqNd)" class="gvcddab8z"/><g filter="url(#ixLBnFe)"><path fill="url(#in92hEc)" class="u5bjt8cdp"/></g><path fill="url(#iB68NCe)" clip-rule="evenodd" class="wfgw5ub6b"/><path fill="url(#iOsKiYd)" clip-rule="evenodd" class="wfgw5ub6b"/><path fill="url(#ihXy2HX)" clip-rule="evenodd" class="d5_x4xk7i"/><path fill="url(#ioj66mb)" clip-rule="evenodd" class="d5_x4xk7i"/><path fill="url(#i9hrt8d)" clip-rule="evenodd" class="ctupw6b3d"/><path fill="url(#isuPSHd)" clip-rule="evenodd" class="ctupw6b3d"/><path fill="url(#iHX20tM)" clip-rule="evenodd" class="vdngsab5t"/><path fill="url(#i2wuAyS)" clip-rule="evenodd" class="vdngsab5t"/><path fill="url(#iKBLSqc)" class="twba206ho"/><path fill="url(#iyqAagc)" class="twba206ho"/><path fill="url(#iLzvubs)" class="lucypabyc"/><g filter="url(#iN0HTNb)"><path class="adnyuxbuz"/></g><g filter="url(#i6RVKSQ)"><path class="ti33upbvq"/></g><g filter="url(#iEr4xNe)"><path class="tq3uhwb-v"/></g><g filter="url(#ibTT5hb)"><path class="zlrx7kbjx"/></g><g filter="url(#ifEHZty)"><path stroke="url(#iwmtN9c)" class="bdk4dmb5b"/></g><g filter="url(#iA9PNtb)"><path stroke="url(#iD202ve)" class="gwm_2mjil"/></g><g filter="url(#i7U8f5d)"><path stroke="url(#idzA6dc)" class="y2ly1lryk"/></g><g filter="url(#ivDGtrb)"><path stroke="url(#iVuU7Md)" class="am6k_ubte"/></g><g filter="url(#iEhL65d)"><path stroke="url(#iAeOdqd)" class="c549xi8ae"/></g><g filter="url(#ij3rzNc)"><circle fill="url(#iU8mCjd)" class="tzzfewb5d"/></g><g filter="url(#iJyjjiX)"><circle fill="url(#icWvYTb)" class="kl3z7gbld"/></g><g filter="url(#iKVXBde)"><circle fill="url(#iPbrODe)" class="pexm_sqtu"/><circle fill="url(#iL2zFOd)" class="pexm_sqtu"/></g><g filter="url(#iAWuRyc)"><circle class="fx6d6qbgd"/><circle fill="url(#iCrfwTK)" class="sgsgpoblf"/><circle fill="url(#iKVv2ql)" class="sgsgpoblf"/></g><g filter="url(#iySs8iZ)"><path fill="url(#iFrw67G)" class="tvtny1bdz"/><path fill="url(#ixD7SMc)" class="tvtny1bdz"/><path fill="url(#iiBZrQc)" class="tvtny1bdz"/><path fill="url(#inMIB9R)" class="tvtny1bdz"/><path fill="url(#iso9zAb)" class="tvtny1bdz"/><path fill="url(#i5aDC8r)" class="tvtny1bdz"/><path fill="url(#i65yv5d)" class="tvtny1bdz"/></g><g filter="url(#icuhuMc)"><path class="bg-b1rbld"/><path fill="url(#iQOxlQp)" class="ntnex-y5x"/><path fill="url(#iUYo8Da)" class="ntnex-y5x"/><path fill="url(#ir9UL7u)" class="ntnex-y5x"/><path fill="url(#iGQ7AqT)" class="ntnex-y5x"/></g><g filter="url(#ig4ldVc)"><path class="khhwu5bdo"/></g><g filter="url(#iVha9Ke)"><path class="gprbt2b6a"/><path fill="url(#iX0P38Q)" class="xfnas2msm"/><path fill="url(#iFUZNHc)" class="xfnas2msm"/><path fill="url(#iIZTBUb)" class="xfnas2msm"/><path fill="url(#iFfzlwb)" class="xfnas2msm"/></g><path fill="url(#iXXi66d)" class="xfnas2msm"/><path stroke="url(#iglNIjb)" class="eu5r48x5o"/><g filter="url(#iYUxSVb)"><path class="c2zo4jnmk"/></g><g filter="url(#iQ5hFtd)"><path class="yr2jbccoa"/></g><path class="atkbn2b1o"/><path fill="url(#iRFvGpe)" class="d8qtl-bzx"/><path class="u7a-dxbac"/><g filter="url(#ilMJZ5d)"><path class="uciwgyi0j"/><path fill="url(#i7j1lOe)" class="drt0g1bin"/></g><g filter="url(#iOlN5vc)"><path fill="url(#iJ5zNwo)" class="hc91e0myr"/></g><path class="ufczfdozl"/><path fill="url(#iE8PiMe)" class="pnfq2gqwd"/><path class="t96os-b7n"/><g filter="url(#i9Nztud)"><path fill="url(#iFLT9pc)" class="agpicebtj"/></g><g filter="url(#i9bsxkb)"><ellipse transform="rotate(-27.914 13.97 13.754)" class="nfq5w_rcl"/><ellipse fill="url(#iTqG7Ac)" transform="rotate(-27.914 13.97 13.754)" class="w6vq7lbjf"/></g><g filter="url(#iRXdHDb)"><path stroke="url(#iPWrHTd)" class="s9rscdb5x"/></g><g filter="url(#ig2EFxb)"><path stroke="url(#iXDE7sS)" class="x438pabwn"/></g><g filter="url(#i1RTpxc)"><path stroke="url(#ioPhFCe)" class="ab6py490d"/></g><g filter="url(#iOuX91E)"><path class="vcz9qnm9q"/></g><path fill="url(#iMwhdrV)" class="qzd219blo"/><path fill="url(#i3dSYhb)" class="qzd219blo"/><path fill="url(#inl9J2c)" class="qzd219blo"/><path fill="url(#iCE2gke)" class="wozepxbaa"/><path fill="url(#izP9Z9c)" class="wozepxbaa"/><rect fill="url(#iK2GSbd)" class="okwd93kys"/><rect fill="url(#iy7tjOa)" class="okwd93kys"/><rect fill="url(#iYE2hsb)" class="okwd93kys"/><defs><radialGradient id="iPYYWhe" cx="0" cy="0" r="1" gradientTransform="rotate(135.22 8.643 15.887)scale(12.9545 12.5552)" gradientUnits="userSpaceOnUse"><stop offset=".195" class="m-1-e5bla"/><stop offset=".794" class="b057dp4eh"/></radialGradient><radialGradient id="iT07jwd" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.09375 -3.28125 0 20.219 20.139)" gradientUnits="userSpaceOnUse"><stop class="m9gf32bwp"/><stop offset="1" class="n297mkbnr"/></radialGradient><radialGradient id="il5eVUq" cx="0" cy="0" r="1" gradientTransform="matrix(-1.75 0 0 -11.7187 21 25.92)" gradientUnits="userSpaceOnUse"><stop offset=".214" class="demkpcl0k"/><stop offset="1" class="ym-b_m9fy"/></radialGradient><radialGradient id="iY3yYtd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.15625 0 0 -5.75902 11.656 25.326)" gradientUnits="userSpaceOnUse"><stop class="ujrq6ixuu"/><stop offset="1" class="h4mko5b9o"/></radialGradient><radialGradient id="iv8FoOX" cx="0" cy="0" r="1" gradientTransform="matrix(2.12502 5.34374 -11.023 4.38346 13.099 18.733)" gradientUnits="userSpaceOnUse"><stop class="nl0wbpawx"/><stop offset="1" class="jm40s5baz"/></radialGradient><radialGradient id="iBZ0RUd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.34375 2.4375 -2.36069 -1.3014 7.187 11.826)" gradientUnits="userSpaceOnUse"><stop offset=".077" class="l-r9gxb9g"/><stop offset="1" class="hcmh5c50b"/></radialGradient><radialGradient id="itKlKTd" cx="0" cy="0" r="1" gradientTransform="rotate(115.145 -.151 8.247)scale(3.38309 2.95533)" gradientUnits="userSpaceOnUse"><stop offset=".452" class="y-1rsmdul"/><stop offset=".826" class="af8mzdbwl"/></radialGradient><radialGradient id="ihlr5IT" cx="0" cy="0" r="1" gradientTransform="matrix(-1.34375 2.4375 -2.36069 -1.3014 10.101 2.846)" gradientUnits="userSpaceOnUse"><stop offset=".077" class="mpwbs5b3u"/><stop offset="1" class="fzq016boz"/></radialGradient><radialGradient id="iGUmgWd" cx="0" cy="0" r="1" gradientTransform="rotate(115.145 4.158 4.683)scale(3.38309 2.95533)" gradientUnits="userSpaceOnUse"><stop offset=".452" class="x1l7xqbyw"/><stop offset=".826" class="ng1cexbhj"/></radialGradient><radialGradient id="iXhqZHd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.34375 2.4375 -2.36069 -1.3014 26.066 3.861)" gradientUnits="userSpaceOnUse"><stop offset=".077" class="lelj2r8dg"/><stop offset="1" class="fde_fwzpt"/></radialGradient><radialGradient id="iOHvRJe" cx="0" cy="0" r="1" gradientTransform="rotate(105.03 11.36 11.751)scale(3.49455 3.40391)" gradientUnits="userSpaceOnUse"><stop offset=".375" class="ppr920emc"/><stop offset=".826" class="y_auwli2s"/></radialGradient><radialGradient id="issuNue" cx="0" cy="0" r="1" gradientTransform="matrix(-1.34375 2.4375 -2.36069 -1.3014 27.09 13.818)" gradientUnits="userSpaceOnUse"><stop offset=".077" class="y05rrkbkk"/><stop offset="1" class="a5zzorbzd"/></radialGradient><radialGradient id="iMaLBhb" cx="0" cy="0" r="1" gradientTransform="matrix(1 1.07812 -1.5877 1.47265 24.969 13.357)" gradientUnits="userSpaceOnUse"><stop class="i8j0jyb4u"/><stop offset="1" class="d7caiobkz"/></radialGradient><radialGradient id="iAhrvZc" cx="0" cy="0" r="1" gradientTransform="rotate(109.11 8.51 16.52)scale(3.46022 3.37046)" gradientUnits="userSpaceOnUse"><stop offset=".347" class="tn_97qkdc"/><stop offset=".829" class="mmq2utbuk"/></radialGradient><radialGradient id="iMk8UMb" cx="0" cy="0" r="1" gradientTransform="matrix(-.7578 1.14063 -.96756 -.64282 17.25 27.855)" gradientUnits="userSpaceOnUse"><stop offset=".212" class="u6lph46no"/><stop offset="1" class="bq5dgsbba"/></radialGradient><radialGradient id="iR23Gge" cx="0" cy="0" r="1" gradientTransform="matrix(-.7578 1.14063 -.96756 -.64282 17.25 25.842)" gradientUnits="userSpaceOnUse"><stop offset=".212" class="u6lph46no"/><stop offset="1" class="bq5dgsbba"/></radialGradient><radialGradient id="i5YvaPc" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.03125 -2.40212 0 22.222 20.983)" gradientUnits="userSpaceOnUse"><stop class="koq0r9bvu"/><stop offset="1" class="dpmuo-biy"/></radialGradient><radialGradient id="ieol8Me" cx="0" cy="0" r="1" gradientTransform="scale(1.38818 6.1875)rotate(90 2.761 6.5)" gradientUnits="userSpaceOnUse"><stop class="xntzq-4ho"/><stop offset="1" class="pt8frltpn"/></radialGradient><radialGradient id="iDbbcbc" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.25 -.60938 0 13.062 24.108)" gradientUnits="userSpaceOnUse"><stop class="wshx69b-y"/><stop offset="1" class="aqzyd8bsb"/></radialGradient><radialGradient id="iOe2zrd" cx="0" cy="0" r="1" gradientTransform="matrix(2.9375 -7.98881 7.06186 2.59666 10.312 28.264)" gradientUnits="userSpaceOnUse"><stop offset=".724" class="lgi0lwbjz"/><stop offset="1" class="tvoyviyhj"/></radialGradient><radialGradient id="iV71Rbc" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.42188 -.18506 0 12.857 21.717)" gradientUnits="userSpaceOnUse"><stop class="m5avsc_ef"/><stop offset="1" class="ci3gi1b_k"/></radialGradient><radialGradient id="iObplQb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.90624 2.42972 -4.28692 -6.89204 19.266 20.795)" gradientUnits="userSpaceOnUse"><stop class="ku63lg_wt"/><stop offset="1" class="i1-orb7ke"/></radialGradient><radialGradient id="iQpTAtb" cx="0" cy="0" r="1" gradientTransform="matrix(-.46875 -.125 .54686 -2.05079 19.188 22.482)" gradientUnits="userSpaceOnUse"><stop offset=".108" class="qsu4qbckq"/><stop offset="1" class="gr0wzobbs"/></radialGradient><radialGradient id="iSAsI1d" cx="0" cy="0" r="1" gradientTransform="matrix(1.73878 1.3451 -1.47727 1.90964 13.775 23.358)" gradientUnits="userSpaceOnUse"><stop class="ab6i82btp"/><stop offset="1" class="pb6efmson"/></radialGradient><radialGradient id="iwtPTOo" cx="0" cy="0" r="1" gradientTransform="matrix(-1.68958 -.4774 .79459 -2.81214 15.416 23.836)" gradientUnits="userSpaceOnUse"><stop offset=".69" class="sawf8hb2n"/><stop offset="1" class="o415o878f"/></radialGradient><radialGradient id="isAdhHe" cx="0" cy="0" r="1" gradientTransform="matrix(-.5 1.58457 -.75053 -.23683 16.11 23.836)" gradientUnits="userSpaceOnUse"><stop class="btor07b8q"/><stop offset="1" class="jjf293xlz"/></radialGradient><radialGradient id="ivLP6Gc" cx="0" cy="0" r="1" gradientTransform="rotate(142.275 5.895 15.056)scale(2.19833 2.41434)" gradientUnits="userSpaceOnUse"><stop class="auvn9fbbk"/><stop offset="1" class="h2li0wblg"/></radialGradient><radialGradient id="iXetYud" cx="0" cy="0" r="1" gradientTransform="matrix(1.68958 -.4774 .79459 2.81214 18.13 23.836)" gradientUnits="userSpaceOnUse"><stop offset=".69" class="sawf8hb2n"/><stop offset="1" class="o415o878f"/></radialGradient><radialGradient id="iw9bnJb" cx="0" cy="0" r="1" gradientTransform="matrix(-.39136 0 0 -2.59279 17.54 23.592)" gradientUnits="userSpaceOnUse"><stop class="scbqttb8d"/><stop offset="1" class="u1gl_1zha"/></radialGradient><radialGradient id="ihpEqzz" cx="0" cy="0" r="1" gradientTransform="matrix(-4.375 1.44046 -1.3893 -4.21963 28.094 22.456)" gradientUnits="userSpaceOnUse"><stop offset=".241" class="n0weh-4ic"/><stop offset=".899" class="ocrikough"/></radialGradient><radialGradient id="ipszqNd" cx="0" cy="0" r="1" gradientTransform="rotate(163.091 11.836 12.97)scale(3.90165 13.4872)" gradientUnits="userSpaceOnUse"><stop offset=".699" class="b0r23cb7j"/><stop offset="1" class="tck-t1b9f"/></radialGradient><radialGradient id="in92hEc" cx="0" cy="0" r="1" gradientTransform="rotate(139.97 1.2 10.48)scale(1.53045 3.638)" gradientUnits="userSpaceOnUse"><stop offset=".129" class="xft8gg3_m"/><stop offset="1" class="p3h7bebar"/></radialGradient><radialGradient id="iB68NCe" cx="0" cy="0" r="1" gradientTransform="matrix(-.79386 1.27188 -2.4349 -1.51978 6.442 17.553)" gradientUnits="userSpaceOnUse"><stop class="x1gqtkb2l"/><stop offset="1" class="utdnmlbmp"/><stop offset="1" class="f30_pcbll"/></radialGradient><radialGradient id="iOsKiYd" cx="0" cy="0" r="1" gradientTransform="matrix(-.73037 2.48832 -3.82658 -1.12318 6.977 17.288)" gradientUnits="userSpaceOnUse"><stop offset=".582" class="odagoac9w"/><stop offset=".823" class="vx50bbb3x"/></radialGradient><radialGradient id="ihXy2HX" cx="0" cy="0" r="1" gradientTransform="rotate(116.602 -3.017 10.55)scale(1.58621 2.70684)" gradientUnits="userSpaceOnUse"><stop class="x1gqtkb2l"/><stop offset="1" class="utdnmlbmp"/><stop offset="1" class="f30_pcbll"/></radialGradient><radialGradient id="ioj66mb" cx="0" cy="0" r="1" gradientTransform="matrix(-.65347 2.77477 -3.52334 -.82977 5.545 17.677)" gradientUnits="userSpaceOnUse"><stop offset=".511" class="odagoac9w"/><stop offset=".833" class="vx50bbb3x"/></radialGradient><radialGradient id="i9hrt8d" cx="0" cy="0" r="1" gradientTransform="matrix(-.68468 1.22288 -2.2217 -1.2439 4.939 18.947)" gradientUnits="userSpaceOnUse"><stop class="x1gqtkb2l"/><stop offset="1" class="utdnmlbmp"/><stop offset="1" class="f30_pcbll"/></radialGradient><radialGradient id="isuPSHd" cx="0" cy="0" r="1" gradientTransform="rotate(104.751 -4.503 11.427)scale(2.474 3.46652)" gradientUnits="userSpaceOnUse"><stop offset=".508" class="odagoac9w"/><stop offset=".862" class="vx50bbb3x"/></radialGradient><radialGradient id="iHX20tM" cx="0" cy="0" r="1" gradientTransform="rotate(122.692 -2.834 11.406)scale(1.24393 2.40994)" gradientUnits="userSpaceOnUse"><stop class="x1gqtkb2l"/><stop offset="1" class="utdnmlbmp"/><stop offset="1" class="f30_pcbll"/></radialGradient><radialGradient id="i2wuAyS" cx="0" cy="0" r="1" gradientTransform="matrix(-.61813 2.04813 -3.22394 -.973 5.687 19.733)" gradientUnits="userSpaceOnUse"><stop offset=".585" class="odagoac9w"/><stop offset=".954" class="vx50bbb3x"/></radialGradient><radialGradient id="iKBLSqc" cx="0" cy="0" r="1" gradientTransform="rotate(-162.011 6.48 10.137)scale(3.69324 5.10277)" gradientUnits="userSpaceOnUse"><stop class="kibsqob-j"/><stop offset=".482" class="ikr704p2a"/></radialGradient><radialGradient id="iyqAagc" cx="0" cy="0" r="1" gradientTransform="matrix(.07812 -.82813 3.88844 .36683 6.156 21.78)" gradientUnits="userSpaceOnUse"><stop class="d8qlssbpw"/><stop offset="1" class="g7e6fzidn"/></radialGradient><radialGradient id="iLzvubs" cx="0" cy="0" r="1" gradientTransform="matrix(1.65625 2.09375 -2.38774 1.88881 15.814 20.443)" gradientUnits="userSpaceOnUse"><stop offset=".229" class="bgjnq7nzl"/><stop offset="1" class="z6jr4yb7o"/></radialGradient><radialGradient id="iU8mCjd" cx="0" cy="0" r="1" gradientTransform="matrix(1.84203 0 0 3.22357 9.811 14.57)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="x3sd7rf5r"/><stop offset="1" class="dsm4f-bda"/></radialGradient><radialGradient id="iL2zFOd" cx="0" cy="0" r="1" gradientTransform="matrix(.86777 -.63187 .7212 .99044 21.94 14.293)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="ytssyfa7a"/><stop offset="1" class="fnfe_1psv"/></radialGradient><radialGradient id="iCrfwTK" cx="0" cy="0" r="1" gradientTransform="matrix(.86205 -1.58556 .92803 .50456 21.506 15.433)" gradientUnits="userSpaceOnUse"><stop offset=".755" class="lvos55blo"/><stop offset=".916" class="bvmj8ubsx"/></radialGradient><radialGradient id="iKVv2ql" cx="0" cy="0" r="1" gradientTransform="matrix(.27217 .2694 -.3473 .35086 21.55 14.57)" gradientUnits="userSpaceOnUse"><stop class="iqm2531qk"/><stop offset="1" class="n3g96cceg"/></radialGradient><radialGradient id="iiBZrQc" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.45807 -10.1239 0 16.23 14.361)" gradientUnits="userSpaceOnUse"><stop offset=".561" class="g0r5sc7jj"/><stop offset="1" class="i5c5eto6f"/></radialGradient><radialGradient id="inMIB9R" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.372 1.68862 0 19.01 13.236)" gradientUnits="userSpaceOnUse"><stop class="kb28pwbin"/><stop offset="1" class="uck_nmbag"/></radialGradient><radialGradient id="iso9zAb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.45995 1.81558 0 14.226 13.2)" gradientUnits="userSpaceOnUse"><stop class="j7sc31byj"/><stop offset="1" class="e9zt2gbxt"/></radialGradient><radialGradient id="i5aDC8r" cx="0" cy="0" r="1" gradientTransform="matrix(-2.98218 -.72097 .42362 -1.75222 21.028 21.036)" gradientUnits="userSpaceOnUse"><stop offset=".136" class="ph-yb3bws"/><stop offset="1" class="az2la2bjr"/></radialGradient><radialGradient id="iQOxlQp" cx="0" cy="0" r="1" gradientTransform="matrix(.83744 -3.10348 1.15087 .31055 21.109 10.26)" gradientUnits="userSpaceOnUse"><stop class="ui2kgq2tt"/><stop offset="1" class="bumyo9b5s"/></radialGradient><radialGradient id="iUYo8Da" cx="0" cy="0" r="1" gradientTransform="matrix(4.01482 .36946 -.19866 2.15874 19.384 8.413)" gradientUnits="userSpaceOnUse"><stop offset=".122" class="d4d293bim"/><stop offset="1" class="yf9erdbmk"/></radialGradient><radialGradient id="ir9UL7u" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.76258 -2.72974 0 16.547 5.542)" gradientUnits="userSpaceOnUse"><stop class="qc5tyzrav"/><stop offset="1" class="m_1e2qbpe"/></radialGradient><radialGradient id="iGQ7AqT" cx="0" cy="0" r="1" gradientTransform="rotate(-36.235 24.295 -8.593)scale(4.00028 6.26713)" gradientUnits="userSpaceOnUse"><stop class="gg1n47rtb"/><stop offset="1" class="uk24qccae"/></radialGradient><radialGradient id="iFfzlwb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .20668 -.66401 0 16.89 16.257)" gradientUnits="userSpaceOnUse"><stop class="ldpzz4bsg"/><stop offset="1" class="xtaxaigve"/></radialGradient><radialGradient id="iRFvGpe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .85142 -1.35428 0 18.835 13.855)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="i7j1lOe" cx="0" cy="0" r="1" gradientTransform="matrix(-.24308 -.31325 .43127 -.33467 18.595 13.943)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iE8PiMe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .85146 -1.35436 0 14.255 13.855)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iTqG7Ac" cx="0" cy="0" r="1" gradientTransform="matrix(-.0081 -.51787 .6225 -.00975 13.954 14.084)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iMwhdrV" cx="0" cy="0" r="1" gradientTransform="matrix(-5.5 4.12501 -3.615 -4.82 20.719 4.576)" gradientUnits="userSpaceOnUse"><stop offset=".179" class="tg07-ljnl"/><stop offset="1" class="c6833cb9x"/></radialGradient><radialGradient id="i3dSYhb" cx="0" cy="0" r="1" gradientTransform="matrix(2.875 .375 -.58342 4.4729 10.781 7.701)" gradientUnits="userSpaceOnUse"><stop class="j8k1fac_p"/><stop offset="1" class="g8uem1b5g"/></radialGradient><radialGradient id="inl9J2c" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.875 8.03906 0 16.773 8.326)" gradientUnits="userSpaceOnUse"><stop offset=".761" class="km6q7kb1a"/><stop offset="1" class="i8skpb2jz"/></radialGradient><radialGradient id="iCE2gke" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.47656 -8.28125 0 18.406 7.912)" gradientUnits="userSpaceOnUse"><stop class="kzuil_5zu"/><stop offset="1" class="ok2r3obil"/></radialGradient><radialGradient id="iK2GSbd" cx="0" cy="0" r="1" gradientTransform="matrix(-7.1875 0 0 -.63281 21.268 9.87)" gradientUnits="userSpaceOnUse"><stop class="w63qn2bkh"/><stop offset="1" class="vvfum-_fa"/></radialGradient><radialGradient id="iy7tjOa" cx="0" cy="0" r="1" gradientTransform="matrix(3.48438 0 0 2.01172 9.003 10.109)" gradientUnits="userSpaceOnUse"><stop class="gfrsedb9v"/><stop offset="1" class="vke6kh8bt"/></radialGradient><filter id="ivjWlxQ" width="21.247" height="10.303" x="6.25" y="19.623" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.615686 0 0 0 0 0.607843 0 0 0 0 0.619608 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23848"/></filter><filter id="ikFtPJc" width="2.078" height="2.078" x="15.622" y="27.457" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.792157 0 0 0 0 0.717647 0 0 0 0 0.788235 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_3987_23848"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_3987_23848" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.831373 0 0 0 0 0.745098 0 0 0 0 0.803922 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_3987_23848"/></filter><filter id="iQI5HQe" width="2.078" height="2.078" x="15.622" y="25.444" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.792157 0 0 0 0 0.717647 0 0 0 0 0.788235 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_3987_23848"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_3987_23848" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.831373 0 0 0 0 0.745098 0 0 0 0 0.803922 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_3987_23848"/></filter><filter id="imykPwt" width="6.554" height="3.702" x="13.38" y="19.523" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.721569 0 0 0 0 0.682353 0 0 0 0 0.74902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23848"/></filter><filter id="i0Hwnod" width="7.432" height="4.46" x="12.567" y="22.084" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23848" stdDeviation=".5"/></filter><filter id="iDf870c" width="2.672" height="2.865" x="13.611" y="22.403" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.780392 0 0 0 0 0.270588 0 0 0 0 0.396078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23848"/></filter><filter id="ilnfgHe" width="2.672" height="2.865" x="17.264" y="22.403" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.780392 0 0 0 0 0.270588 0 0 0 0 0.396078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23848"/></filter><filter id="iM3qzqd" width="1.554" height="1.999" x="15.986" y="22.812" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.827451 0 0 0 0 0.137255 0 0 0 0 0.317647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23848"/></filter><filter id="iAH8nTf" width="4.764" height="4.766" x="24.75" y="19.349" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.1"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.192157 0 0 0 0 0.0980392 0 0 0 0 0.0862745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23848"/></filter><filter id="iK3gnrs" width="2.077" height="3.844" x="25.907" y="17.448" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.239216 0 0 0 0 0.156863 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23848"/></filter><filter id="id8LBbb" width="2.401" height="4.052" x="24.436" y="17.107" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.220016 0 0 0 0 0.12951 0 0 0 0 0.12951 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23848"/></filter><filter id="iO0pEyW" width="2.312" height="4.044" x="23.386" y="17.96" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.239216 0 0 0 0 0.156863 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23848"/></filter><filter id="iGNrBic" width="2.123" height="3.114" x="22.394" y="19.041" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.239216 0 0 0 0 0.156863 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23848"/></filter><filter id="ixLBnFe" width="3.002" height="3.147" x="6.649" y="16.347" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.207843 0 0 0 0 0.137255 0 0 0 0 0.141176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23848"/></filter><filter id="iN0HTNb" width="1.264" height="2.491" x="22.908" y="19.19" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23848" stdDeviation=".125"/></filter><filter id="i6RVKSQ" width="1.286" height="2.978" x="23.932" y="18.124" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23848" stdDeviation=".125"/></filter><filter id="iEr4xNe" width="1.444" height="3.775" x="24.962" y="17.226" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23848" stdDeviation=".125"/></filter><filter id="ibTT5hb" width="1.17" height="3.014" x="26.424" y="17.706" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23848" stdDeviation=".125"/></filter><filter id="ifEHZty" width="1.788" height="2.6" x="27.33" y="19.87" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23848" stdDeviation=".125"/></filter><filter id="iA9PNtb" width="2.323" height="1.69" x="3.752" y="19.44" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23848" stdDeviation=".125"/></filter><filter id="i7U8f5d" width="2.342" height="2.022" x="3.291" y="18.151" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23848" stdDeviation=".125"/></filter><filter id="ivDGtrb" width="2.131" height="2.124" x="4.556" y="16.714" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23848" stdDeviation=".125"/></filter><filter id="iEhL65d" width="2.569" height="2.444" x="3.345" y="17.042" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23848" stdDeviation=".125"/></filter><filter id="ij3rzNc" width="3.705" height="3.505" x="9.811" y="12.818" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.341176 0 0 0 0 0.270588 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23848"/></filter><filter id="iJyjjiX" width="3.089" height="3.089" x="10.02" y="13.026" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23848" stdDeviation=".25"/></filter><filter id="iKVXBde" width="3.755" height="3.755" x="19.797" y="12.568" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.243137 0 0 0 0 0.141176 0 0 0 0 0.223529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23848"/></filter><filter id="iAWuRyc" width="3.089" height="3.089" x="20.005" y="13.026" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23848" stdDeviation=".25"/></filter><filter id="iySs8iZ" width="10.889" height="12.775" x="11.133" y="8.666" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.109804 0 0 0 0 0.0509804 0 0 0 0 0.0509804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23848"/></filter><filter id="icuhuMc" width="13.209" height="8.943" x="9.936" y="5.042" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0392157 0 0 0 0 0.00784314 0 0 0 0 0.0196078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23848"/></filter><filter id="ig4ldVc" width="3.347" height="4.314" x="14.623" y="13.396" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23848" stdDeviation=".375"/></filter><filter id="iVha9Ke" width="2.47" height="3.314" x="15.312" y="13.725" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23848" stdDeviation=".125"/></filter><filter id="iYUxSVb" width="3.115" height="1.946" x="17.788" y="10.76" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0196078 0 0 0 0 0.027451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23848"/></filter><filter id="iQ5hFtd" width="3.115" height="1.946" x="12.385" y="10.76" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0196078 0 0 0 0 0.027451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23848"/></filter><filter id="ilMJZ5d" width=".815" height=".72" x="18.069" y="13.398" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23848" stdDeviation=".05"/></filter><filter id="iOlN5vc" width=".915" height=".938" x="18.955" y="13.482" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23848" stdDeviation=".1"/></filter><filter id="i9Nztud" width="1.015" height="1.071" x="14.293" y="13.415" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23848" stdDeviation=".1"/></filter><filter id="i9bsxkb" width=".947" height=".729" x="13.496" y="13.39" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23848" stdDeviation=".05"/></filter><filter id="iRXdHDb" width="2.791" height="1.302" x="17.865" y="11.104" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23848" stdDeviation=".15"/></filter><filter id="ig2EFxb" width="2.873" height="1.362" x="12.387" y="11.171" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23848" stdDeviation=".15"/></filter><filter id="i1RTpxc" width="1.021" height="2.345" x="11.143" y="9.146" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23848" stdDeviation=".125"/></filter><filter id="iOuX91E" width="5.441" height="3.076" x="17.747" y="6.733" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23848" stdDeviation=".375"/></filter><linearGradient id="iK84mBb" x1="22.562" x2="21.812" y1="29.826" y2="29.826" gradientUnits="userSpaceOnUse"><stop class="fr__qmhjc"/><stop offset="1" class="gypp10kih"/></linearGradient><linearGradient id="iWCiqKd" x1="20.644" x2="21.062" y1="29.014" y2="29.014" gradientUnits="userSpaceOnUse"><stop class="hj-s-zboe"/><stop offset="1" class="s0umluqbl"/></linearGradient><linearGradient id="ipodSkc" x1="9.531" x2="4.906" y1="27.451" y2="27.451" gradientUnits="userSpaceOnUse"><stop class="sb-ednb_a"/><stop offset="1" class="v0501vbqa"/></linearGradient><linearGradient id="iXPTZOc" x1="9.75" x2="8.828" y1="27.076" y2="27.076" gradientUnits="userSpaceOnUse"><stop class="o_30au2yc"/><stop offset="1" class="c60cvac3k"/></linearGradient><linearGradient id="itP1zjc" x1="27.871" x2="22.844" y1="28.142" y2="28.142" gradientUnits="userSpaceOnUse"><stop class="i7zyuv8vr"/><stop offset=".907" class="qzhltkbuo"/></linearGradient><linearGradient id="i33ZCUz" x1="28.09" x2="27.168" y1="27.876" y2="27.876" gradientUnits="userSpaceOnUse"><stop class="tub8lbbfx"/><stop offset="1" class="bd09vtb_c"/></linearGradient><linearGradient id="i8tJXGc" x1="16.763" x2="16.763" y1="22.812" y2="24.81" gradientUnits="userSpaceOnUse"><stop offset=".351" class="gzsz7evmk"/><stop offset="1" class="smgiue0gi"/></linearGradient><linearGradient id="iwmtN9c" x1="28.747" x2="27.817" y1="20.365" y2="22.154" gradientUnits="userSpaceOnUse"><stop class="hyyljzbsz"/><stop offset="1" class="s92p9gs-v"/></linearGradient><linearGradient id="iD202ve" x1="4.76" x2="5.331" y1="20.169" y2="21.223" gradientUnits="userSpaceOnUse"><stop class="hyyljzbsz"/><stop offset="1" class="s92p9gs-v"/></linearGradient><linearGradient id="idzA6dc" x1="4.307" x2="5.218" y1="19" y2="20.223" gradientUnits="userSpaceOnUse"><stop class="hyyljzbsz"/><stop offset="1" class="s92p9gs-v"/></linearGradient><linearGradient id="iVuU7Md" x1="5.489" x2="6.52" y1="17.6" y2="18.693" gradientUnits="userSpaceOnUse"><stop class="hyyljzbsz"/><stop offset="1" class="s92p9gs-v"/></linearGradient><linearGradient id="iAeOdqd" x1="4.452" x2="5.734" y1="18.044" y2="19.502" gradientUnits="userSpaceOnUse"><stop class="hyyljzbsz"/><stop offset="1" class="s92p9gs-v"/></linearGradient><linearGradient id="icWvYTb" x1="11.564" x2="10.892" y1="14.863" y2="14.863" gradientUnits="userSpaceOnUse"><stop class="fbs6uccsw"/><stop offset="1" class="np-b1wbds"/></linearGradient><linearGradient id="iPbrODe" x1="22.69" x2="21.831" y1="13.425" y2="16.087" gradientUnits="userSpaceOnUse"><stop class="o1rzobcjq"/><stop offset="1" class="acjykw8xe"/></linearGradient><linearGradient id="iFrw67G" x1="20.784" x2="12.768" y1="14.979" y2="16.174" gradientUnits="userSpaceOnUse"><stop class="cdm_o50ho"/><stop offset="1" class="ahguepbtf"/></linearGradient><linearGradient id="ixD7SMc" x1="10.883" x2="13.261" y1="17.809" y2="17.66" gradientUnits="userSpaceOnUse"><stop offset=".283" class="j-n0q842a"/><stop offset="1" class="o-j_7gbpq"/></linearGradient><linearGradient id="i65yv5d" x1="16.799" x2="16.799" y1="10.442" y2="12.294" gradientUnits="userSpaceOnUse"><stop class="ue2euobvm"/><stop offset="1" class="kngkfdbba"/></linearGradient><linearGradient id="iX0P38Q" x1="15.64" x2="16.625" y1="15.671" y2="15.671" gradientUnits="userSpaceOnUse"><stop class="o6hm6qxaj"/><stop offset="1" class="mg63gccek"/></linearGradient><linearGradient id="iFUZNHc" x1="17.532" x2="16.456" y1="16.01" y2="15.994" gradientUnits="userSpaceOnUse"><stop class="yww6tz8di"/><stop offset="1" class="n-4z7qb5o"/></linearGradient><linearGradient id="iIZTBUb" x1="16.752" x2="16.752" y1="16.789" y2="16.188" gradientUnits="userSpaceOnUse"><stop class="xtiplndwl"/><stop offset="1" class="h8-lntwqp"/></linearGradient><linearGradient id="iXXi66d" x1="16.679" x2="16.679" y1="16.833" y2="16.657" gradientUnits="userSpaceOnUse"><stop class="zoxadnjxe"/><stop offset="1" class="gnvm67mtb"/></linearGradient><linearGradient id="iglNIjb" x1="15.459" x2="15.915" y1="18.484" y2="17.763" gradientUnits="userSpaceOnUse"><stop class="w1_1yhbve"/><stop offset=".663" class="zbexf6jod"/></linearGradient><linearGradient id="iJ5zNwo" x1="19.65" x2="19.321" y1="13.911" y2="14.114" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iFLT9pc" x1="15.035" x2="14.706" y1="13.911" y2="14.114" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iPWrHTd" x1="19.667" x2="19.226" y1="11.665" y2="10.764" gradientUnits="userSpaceOnUse"><stop class="wi8di0b_n"/><stop offset="1" class="zx1idre_k"/></linearGradient><linearGradient id="iXDE7sS" x1="14.1" x2="12.851" y1="11.531" y2="11.008" gradientUnits="userSpaceOnUse"><stop class="wi8di0b_n"/><stop offset="1" class="zx1idre_k"/></linearGradient><linearGradient id="ioPhFCe" x1="11.654" x2="11.654" y1="9.417" y2="11.681" gradientUnits="userSpaceOnUse"><stop class="nc1ak66ax"/><stop offset="1" class="vpvekld5v"/></linearGradient><linearGradient id="izP9Z9c" x1="16.773" x2="16.773" y1="7.912" y2="8.1" gradientUnits="userSpaceOnUse"><stop class="jhlen960d"/><stop offset="1" class="wjchuwb6a"/></linearGradient><linearGradient id="iYE2hsb" x1="17.956" x2="17.956" y1="10.98" y2="10.214" gradientUnits="userSpaceOnUse"><stop class="bl3fq0x9z"/><stop offset="1" class="lxo7c2i6k"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-juggling-dark" /></template>
<style>
.a5zzorbzd {
  stop-color: var(--svg-color--e1ac3a, #E1AC3A);
}

.ab6i82btp {
  stop-color: var(--svg-color--e7377c, #E7377C);
}

.ab6py490d {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M11.79 9.52v.943c-.009.156-.074.505-.272.652");
}

.acjykw8xe {
  stop-color: var(--svg-color--452a31, #452A31);
}

.adnyuxbuz {
  stroke: var(--svg-color--5e4e4d, #5E4E4D);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-35px, 0.35px);
  d: path("m23.333 19.615l.414 1.64");
}

.af8mzdbwl {
  stop-color: var(--svg-color--5f679a, #5F679A);
}

.agpicebtj {
  d: path("M15.108 14.18c0-.302-.246-.504-.313-.565l-.302.293l.186.378z");
}

.ahguepbtf {
  stop-color: var(--svg-color--3c2828, #3C2828);
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

.atkbn2b1o {
  fill: var(--svg-color--fff, #fff);
  d: path("M19.054 13.069c.686 0 1.265.472 1.422 1.111a.288.288 0 0 1-.28.357h-2.342a.242.242 0 0 1-.239-.285a1.47 1.47 0 0 1 1.44-1.183");
}

.auvn9fbbk {
  stop-color: var(--svg-color--e9387a, #E9387A);
}

.az2la2bjr {
  stop-color: var(--svg-color--5b4b4d, #5B4B4D);
  stop-opacity: 0;
}

.b057dp4eh {
  stop-color: var(--svg-color--ccbdde, #CCBDDE);
}

.b0r23cb7j {
  stop-color: var(--svg-color--432b2c, #432B2C);
  stop-opacity: 0;
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

.bg-b1rbld {
  fill: var(--svg-color--21181b, #21181B);
  d: path("m21.606 7.771l-.057 1.586c.788.392 1.746-.074 1.577.877l-.62 3.191c-.055.33-.273.552-.6.56h-.019s.056-.952.113-1.511c.045-.455-.034-.594-.45-1.008c-.226-.224-.395-.56-.395-.896v-.896c0-.28-.225-.503-.45-.56c-.676-.167-2.084-.447-4.11-.447s-3.435.28-4.11.448a.546.546 0 0 0-.451.56v.895c0 .336-.113.672-.394.896l-.17.168c-.224.168-.337.504-.337.784c.056.615.113 1.511.113 1.511q-.027 0-.052-.002a.665.665 0 0 1-.624-.558l-.62-3.19c-.112-.896.456-.113 1.244-.505l.333-1.903c.282-.168.563-.392.845-.616l1.013-1.064c.62-.56 1.52-.727 2.309-.335a3.1 3.1 0 0 0 1.745 0c.845-.28 1.802-.056 2.477.56l.845.84c.225.28.507.447.845.615");
}

.bgjnq7nzl {
  stop-color: var(--svg-color--2d141b, #2D141B);
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

.bumyo9b5s {
  stop-color: var(--svg-color--464344, #464344);
  stop-opacity: 0;
}

.bvmj8ubsx {
  stop-color: var(--svg-color--31191a, #31191A);
}

.byn6wubog {
  fill: var(--svg-color--bc9ebb, #BC9EBB);
  fill-rule: evenodd;
  d: path("M16.899 24.871a.35.35 0 0 1-.266.244c-.25.048-.467.048-.717 0a.35.35 0 0 1-.262-.23c-.18.2-.49.432-1.009.607c-.31.106-.668.058-.833-.23a1.86 1.86 0 0 1-.245-.948c0-.431.124-.74.245-.95c.165-.287.523-.334.833-.23c.503.171.81.418.993.63a.35.35 0 0 1 .278-.293c.25-.048.467-.048.717 0a.35.35 0 0 1 .28.31c.18-.215.49-.47 1.008-.646c.31-.105.668-.058.834.23c.12.208.244.513.244.949s-.124.74-.244.949c-.166.287-.524.335-.834.23c-.531-.18-.844-.42-1.022-.622");
}

.c2zo4jnmk {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("M20.452 11.715h-.001l-.002-.002l-.005-.004l-.013-.01a2 2 0 0 0-.162-.113a2.7 2.7 0 0 0-.44-.221a3 3 0 0 0-1.568-.166a.56.56 0 0 0 .175 1.106c.418-.066.752.011.98.102a1.6 1.6 0 0 1 .316.167l.008.006a.56.56 0 0 0 .712-.865");
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

.cdm_o50ho {
  stop-color: var(--svg-color--533531, #533531);
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

.d4d293bim {
  stop-color: var(--svg-color--4a4648, #4A4648);
}

.d5_x4xk7i {
  fill-rule: evenodd;
  d: path("M3.16 17.066a.75.75 0 0 1 1.042.197q.055.08.116.173c.17.259.379.576.676.877c.36.363.768.614 1.246.64a.75.75 0 0 1-.08 1.497c-.99-.052-1.73-.575-2.232-1.083c-.416-.42-.725-.893-.888-1.143l-.076-.115a.75.75 0 0 1 .196-1.043");
}

.d7caiobkz {
  stop-color: var(--svg-color--e4cc30, #E4CC30);
  stop-opacity: 0;
}

.d8qlssbpw {
  stop-color: var(--svg-color--362625, #362625);
}

.d8qtl-bzx {
  d: path("M18.837 13.354a.937.937 0 0 1 .902 1.184h-1.81a.94.94 0 0 1 .907-1.184");
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

.drt0g1bin {
  d: path("M18.767 13.552c.067.09-.072.198-.23.317c-.16.118-.277.201-.343.112c-.067-.089.008-.257.166-.376c.158-.118.34-.142.407-.053");
}

.dsm4f-bda {
  stop-color: var(--svg-color--332423, #332423);
}

.duyhuibwk {
  cx: 9.246px;
  cy: 3.857px;
  r: 1.684px;
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e9zt2gbxt {
  stop-color: var(--svg-color--351d26, #351D26);
  stop-opacity: 0;
}

.eu5r48x5o {
  fill: var(--svg-color--2a0219, #2A0219);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M15.117 17.467a.21.21 0 0 0-.252.043a.194.194 0 0 0-.02.249c.36.546.988.91 1.702.91a2.04 2.04 0 0 0 1.704-.91a.196.196 0 0 0-.022-.251a.21.21 0 0 0-.25-.041a3.1 3.1 0 0 1-1.432.339a3.1 3.1 0 0 1-1.43-.339Z");
}

.f21vmbcik {
  d: path("M5.437 21.764h4.094v8.063H5.437z");
}

.f30_pcbll {
  stop-color: var(--svg-color--472e2d, #472E2D);
}

.fazjy714p {
  fill: var(--svg-color--483032, #483032);
  d: path("M22.414 19.88a.68.68 0 1 1 1.33-.293l.36 1.793a.645.645 0 0 1-1.26.28z");
}

.fbs6uccsw {
  stop-color: var(--svg-color--281920, #281920);
}

.fde_fwzpt {
  stop-color: var(--svg-color--5c9946, #5C9946);
}

.fnfe_1psv {
  stop-color: var(--svg-color--40272a, #40272A);
  stop-opacity: 0;
}

.fr__qmhjc {
  stop-color: var(--svg-color--7a6cad, #7A6CAD);
}

.ft5dv1b6b {
  fill: none;
}

.fx6d6qbgd {
  cx: 21.55px;
  cy: 14.571px;
  r: 1.044px;
  fill: var(--svg-color--463133, #463133);
}

.fzq016boz {
  stop-color: var(--svg-color--e35838, #E35838);
}

.g0r5sc7jj {
  stop-color: var(--svg-color--3d2138, #3D2138);
  stop-opacity: 0;
}

.g7e6fzidn {
  stop-color: var(--svg-color--362625, #362625);
  stop-opacity: 0;
}

.g8uem1b5g {
  stop-color: var(--svg-color--38303e, #38303E);
  stop-opacity: 0;
}

.gfrsedb9v {
  stop-color: var(--svg-color--5b595e, #5B595E);
}

.gg1n47rtb {
  stop-color: var(--svg-color--463c39, #463C39);
}

.ggm3_setj {
  d: path("m13.38 20.005l.612 3.22h4.946l.796-3.173a10.2 10.2 0 0 0-2.937-.429h-.64c-.963 0-1.894.133-2.777.382");
}

.gnvm67mtb {
  stop-color: var(--svg-color--31171f, #31171F);
  stop-opacity: 0;
}

.gprbt2b6a {
  fill: var(--svg-color--4b3034, #4B3034);
  d: path("m16.146 14.271l-.558 1.784a.566.566 0 0 0 .547.734h.825c.387 0 .66-.373.546-.734l-.557-1.784c-.12-.395-.678-.395-.803 0");
}

.gr0wzobbs {
  stop-color: var(--svg-color--dbcdd4, #DBCDD4);
  stop-opacity: 0;
}

.gvcddab8z {
  d: path("M22.99 22.213c.118.463.585 1.456.804 1.894h4.047l-.258-3.789l-4.836.924c.031.13.123.507.242.97");
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

.h8-lntwqp {
  stop-color: var(--svg-color--3f222f, #3F222F);
  stop-opacity: 0;
}

.hc91e0myr {
  d: path("M19.67 14.167a.9.9 0 0 0-.243-.485l-.272.299l.123.239z");
}

.hcmh5c50b {
  stop-color: var(--svg-color--357ace, #357ACE);
}

.hj-s-zboe {
  stop-color: var(--svg-color--6d5096, #6D5096);
}

.hpfqe6rjh {
  cx: 6.332px;
  cy: 12.838px;
  r: 1.684px;
}

.ht6lpfbpp {
  d: path("M18.68 22.463c-.909.308-1.267.83-1.388 1.082l-.028.29l.028.359c.12.25.48.706 1.388 1.014c.362.123.778.068.971-.267c.14-.243.284-.599.284-1.105c0-.507-.144-.862-.284-1.106c-.193-.335-.61-.39-.97-.267");
}

.hyyljzbsz {
  stop-color: var(--svg-color--5e4e4d, #5E4E4D);
}

.i1-orb7ke {
  stop-color: var(--svg-color--c3b7c1, #C3B7C1);
}

.i5c5eto6f {
  stop-color: var(--svg-color--3d2138, #3D2138);
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

.ikr704p2a {
  stop-color: var(--svg-color--4b3633, #4B3633);
}

.iqm2531qk {
  stop-color: var(--svg-color--352123, #352123);
}

.iwbygtbvw {
  cx: 25.211px;
  cy: 4.873px;
  r: 1.684px;
}

.j-n0q842a {
  stop-color: var(--svg-color--564440, #564440);
}

.j5vd_ebrq {
  fill: var(--svg-color--483032, #483032);
  d: path("M23.407 18.803a.679.679 0 1 1 1.323-.298l.555 2.766a.613.613 0 0 1-1.195.27z");
}

.j70rp9pis {
  d: path("M22.222 29.826h-1.578v-9.568q.826.307 1.578.746z");
}

.j7sc31byj {
  stop-color: var(--svg-color--351d26, #351D26);
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

.kb28pwbin {
  stop-color: var(--svg-color--412628, #412628);
}

.khhwu5bdo {
  fill: var(--svg-color--332024, #332024);
  d: path("m16.259 14.442l-.862 1.784c-.106.367.15.734.513.734h.773c.363 0 .62-.372.513-.734l-.523-1.784c-.112-.395-.297-.395-.414 0");
}

.kibsqob-j {
  stop-color: var(--svg-color--6a5654, #6A5654);
}

.kl3z7gbld {
  cx: 11.564px;
  cy: 14.571px;
  r: 1.044px;
}

.km6q7kb1a {
  stop-color: var(--svg-color--5d5565, #5D5565);
  stop-opacity: 0;
}

.kngkfdbba {
  stop-color: var(--svg-color--2e181f, #2E181F);
  stop-opacity: 0;
}

.koq0r9bvu {
  stop-color: var(--svg-color--9e78c9, #9E78C9);
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

.ldpzz4bsg {
  stop-color: var(--svg-color--624e4d, #624E4D);
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

.lucypabyc {
  d: path("M14.545 18.417c0-.99.9-1.794 2.011-1.794s2.012.803 2.012 1.794v2.326c0 .99-.9 1.794-2.012 1.794c-1.11 0-2.011-.803-2.011-1.794z");
}

.lvos55blo {
  stop-color: var(--svg-color--31191a, #31191A);
  stop-opacity: 0;
}

.lxo7c2i6k {
  stop-color: var(--svg-color--462f5a, #462F5A);
  stop-opacity: 0;
}

.m_1e2qbpe {
  stop-color: var(--svg-color--423d3f, #423D3F);
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

.mg63gccek {
  stop-color: var(--svg-color--3d2928, #3D2928);
  stop-opacity: 0;
}

.mmq2utbuk {
  stop-color: var(--svg-color--cf8b51, #CF8B51);
}

.mpwbs5b3u {
  stop-color: var(--svg-color--ff894e, #FF894E);
}

.n-4z7qb5o {
  stop-color: var(--svg-color--624d4b, #624D4B);
  stop-opacity: 0;
}

.n0weh-4ic {
  stop-color: var(--svg-color--4c2f2c, #4C2F2C);
}

.n297mkbnr {
  stop-color: var(--svg-color--d6d3d7, #D6D3D7);
  stop-opacity: 0;
}

.n3g96cceg {
  stop-color: var(--svg-color--352123, #352123);
  stop-opacity: 0;
}

.nc1ak66ax {
  stop-color: var(--svg-color--3c393a, #3C393A);
}

.nfq5w_rcl {
  cx: 13.97px;
  cy: 13.754px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.408px;
  ry: 0.207px;
}

.ng1cexbhj {
  stop-color: var(--svg-color--b6424c, #B6424C);
}

.nl0wbpawx {
  stop-color: var(--svg-color--968f9c, #968F9C);
}

.np-b1wbds {
  stop-color: var(--svg-color--27161d, #27161D);
}

.ntnex-y5x {
  d: path("m21.606 7.771l-.057 1.586c.788.392 1.746-.074 1.577.877l-.62 3.191c-.055.33-.273.552-.6.56h-.019s.056-.952.113-1.511c.045-.455-.034-.594-.45-1.008c-.226-.224-.395-.56-.395-.896v-.896c0-.28-.225-.503-.45-.56c-.676-.167-2.084-.447-4.11-.447s-3.435.28-4.11.448a.546.546 0 0 0-.451.56v.895c0 .336-.113.672-.394.896l-.17.168c-.224.168-.337.504-.337.784c.056.615.113 1.511.113 1.511q-.027 0-.052-.002a.665.665 0 0 1-.624-.558l-.62-3.19c-.112-.896.456-.113 1.244-.505l.333-1.903c.282-.168.563-.392.845-.616l1.013-1.064c.62-.56 1.52-.727 2.309-.335a3.1 3.1 0 0 0 1.745 0c.845-.28 1.802-.056 2.477.56l.845.84c.225.28.507.447.845.615");
}

.o_30au2yc {
  stop-color: var(--svg-color--decfd8, #DECFD8);
}

.o-j_7gbpq {
  stop-color: var(--svg-color--564440, #564440);
  stop-opacity: 0;
}

.o1rzobcjq {
  stop-color: var(--svg-color--635251, #635251);
}

.o415o878f {
  stop-color: var(--svg-color--ef4c8b, #EF4C8B);
}

.o6hm6qxaj {
  stop-color: var(--svg-color--3d2928, #3D2928);
}

.ocrikough {
  stop-color: var(--svg-color--41282f, #41282F);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.odagoac9w {
  stop-color: var(--svg-color--3a2130, #3A2130);
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

.p3h7bebar {
  stop-color: var(--svg-color--412824, #412824);
}

.pb6efmson {
  stop-color: var(--svg-color--d72c5e, #D72C5E);
}

.pexm_sqtu {
  cx: 21.55px;
  cy: 14.571px;
  r: 1.752px;
}

.ph-yb3bws {
  stop-color: var(--svg-color--5b4b4d, #5B4B4D);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pnfq2gqwd {
  d: path("M14.253 13.354a.937.937 0 0 0-.903 1.184h1.81a1 1 0 0 0 .034-.247a.943.943 0 0 0-.941-.937");
}

.ppr920emc {
  stop-color: var(--svg-color--61a150, #61A150);
  stop-opacity: 0;
}

.pt8frltpn {
  stop-color: var(--svg-color--7060a5, #7060A5);
}

.qc5tyzrav {
  stop-color: var(--svg-color--423d3f, #423D3F);
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

.s0umluqbl {
  stop-color: var(--svg-color--7160a4, #7160A4);
  stop-opacity: 0;
}

.s92p9gs-v {
  stop-color: var(--svg-color--5e4e4d, #5E4E4D);
  stop-opacity: 0;
}

.s9rscdb5x {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M18.29 11.564c.452-.08 1.332-.057 1.942.417");
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

.sgsgpoblf {
  cx: 21.55px;
  cy: 14.571px;
  r: 1.044px;
}

.smgiue0gi {
  stop-color: var(--svg-color--c93857, #C93857);
}

.swka_j87x {
  d: path("M6.25 29.826c0-5.635 4.568-10.203 10.203-10.203h.64c5.636 0 10.204 4.568 10.204 10.203z");
}

.t-5nldk3g {
  cx: 16.761px;
  cy: 28.296px;
  r: 0.739px;
}

.t62nyv9ws {
  fill: var(--svg-color--483032, #483032);
  d: path("M24.458 17.959a.68.68 0 0 1 .568-.843l.023-.003a.68.68 0 0 1 .756.54l.622 3.039c.071.355-.246.42-.606.458c-.303.032-.553-.005-.629-.3z");
}

.t96os-b7n {
  fill: var(--svg-color--000, #000);
  d: path("M14.789 14.29a.534.534 0 0 0-.536-.536a.534.534 0 0 0-.477.784h.95a.5.5 0 0 0 .063-.247");
}

.tck-t1b9f {
  stop-color: var(--svg-color--473238, #473238);
}

.tg07-ljnl {
  stop-color: var(--svg-color--5e5764, #5E5764);
}

.ti33upbvq {
  stroke: var(--svg-color--5e4e4d, #5E4E4D);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-35px, 0.35px);
  d: path("m24.357 18.55l.437 2.127");
}

.tn_97qkdc {
  stop-color: var(--svg-color--f2c341, #F2C341);
  stop-opacity: 0;
}

.tq3uhwb-v {
  stroke: var(--svg-color--5e4e4d, #5E4E4D);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-35px, 0.35px);
  d: path("m25.388 17.65l.593 2.926");
}

.tub8lbbfx {
  stop-color: var(--svg-color--e0dde3, #E0DDE3);
}

.tvoyviyhj {
  stop-color: var(--svg-color--775184, #775184);
}

.tvtny1bdz {
  d: path("m11.194 13.927l.052.002s-.056-.896-.113-1.512c0-.28.113-.615.338-.783l.169-.168c.281-.224.394-.56.394-.896v-.896c0-.28.169-.504.45-.56c.676-.168 2.084-.448 4.11-.448c2.028 0 3.435.28 4.11.448c.226.056.451.28.451.56v.896c0 .336.17.672.394.896c.527.369.495.572.45 1.007c-.055.56-.112 1.512-.112 1.512h.02l-.28 4.155c-.168 1.857-1.629 3.152-3.37 3.152h-3.37c-1.797 0-3.2-1.295-3.37-3.152z");
}

.twba206ho {
  d: path("M5.963 18.892a.88.88 0 0 0-.37.74v2.108l.618.04h3.302v-2.33c0-.836-.805-1.25-1.97-1.148c-.655.057-1.208.34-1.58.589");
}

.tzzfewb5d {
  cx: 11.564px;
  cy: 14.571px;
  r: 1.752px;
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

.u7a-dxbac {
  fill: var(--svg-color--000, #000);
  d: path("M18.3 14.29c0-.297.239-.536.537-.536a.534.534 0 0 1 .476.784h-.949a.5.5 0 0 1-.064-.247");
}

.uciwgyi0j {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.767 13.552c.067.09-.072.198-.23.317c-.16.118-.277.201-.343.112c-.067-.089.008-.257.166-.376c.158-.118.34-.142.407-.053");
}

.uck_nmbag {
  stop-color: var(--svg-color--412628, #412628);
  stop-opacity: 0;
}

.ue2euobvm {
  stop-color: var(--svg-color--2e181f, #2E181F);
}

.ufczfdozl {
  fill: var(--svg-color--fff, #fff);
  d: path("M14.036 13.069c-.685 0-1.264.472-1.422 1.111a.288.288 0 0 0 .28.358h2.342c.15 0 .269-.137.239-.286a1.47 1.47 0 0 0-1.44-1.183");
}

.ui2kgq2tt {
  stop-color: var(--svg-color--464344, #464344);
}

.ujrq6ixuu {
  stop-color: var(--svg-color--beb4c6, #BEB4C6);
}

.uk24qccae {
  stop-color: var(--svg-color--463c39, #463C39);
  stop-opacity: 0;
}

.utdnmlbmp {
  stop-color: var(--svg-color--503736, #503736);
}

.v0501vbqa {
  stop-color: var(--svg-color--c0b5cd, #C0B5CD);
}

.vcz9qnm9q {
  fill: var(--svg-color--504a4c, #504A4C);
  d: path("M21.18 8.495h-2.178a.505.505 0 1 1 .08-1.005c.566.09 1.316.215 1.818.34c1.136.281 1.45.834 1.538 1.229a1.58 1.58 0 0 0-1.258-.564");
}

.vdngsab5t {
  fill-rule: evenodd;
  d: path("M3.416 19.34a.75.75 0 0 1 1.051.14c.244.317.833.881 1.8.881a.75.75 0 0 1 .75.75c0 .415-.336.67-.75.67c-1.683 0-2.593-.87-2.99-1.39a.75.75 0 0 1 .139-1.05");
}

.vke6kh8bt {
  stop-color: var(--svg-color--3e3843, #3E3843);
  stop-opacity: 0;
}

.vpvekld5v {
  stop-color: var(--svg-color--3c393a, #3C393A);
  stop-opacity: 0;
}

.vvfum-_fa {
  stop-color: var(--svg-color--392f42, #392F42);
}

.vx50bbb3x {
  stop-color: var(--svg-color--3a2130, #3A2130);
}

.w1_1yhbve {
  stop-color: var(--svg-color--564848, #564848);
}

.w63qn2bkh {
  stop-color: var(--svg-color--605966, #605966);
}

.w6vq7lbjf {
  cx: 13.97px;
  cy: 13.754px;
  rx: 0.408px;
  ry: 0.207px;
}

.wfgw5ub6b {
  fill-rule: evenodd;
  d: path("M4.273 16.754a.75.75 0 0 1 1.042.196q.091.134.166.258c.141.228.267.432.519.637c.292.238.794.485 1.747.42a.75.75 0 1 1 .102 1.497c-1.29.088-2.178-.25-2.796-.754c-.478-.389-.78-.89-.917-1.116l-.059-.096a.75.75 0 0 1 .196-1.042");
}

.wi8di0b_n {
  stop-color: var(--svg-color--353435, #353435);
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

.wr17kemdy {
  fill: var(--svg-color--533837, #533837);
  d: path("m27.85 19.83l-.447.824l-1.172 1.422l-1.481 1.992l3.099.047c.099-.172.218-.566.38-1.327c.164-.66.326-1.114.471-1.376l.443-.924a.726.726 0 0 0-1.292-.659");
}

.wshx69b-y {
  stop-color: var(--svg-color--896bb4, #896BB4);
}

.x1gqtkb2l {
  stop-color: var(--svg-color--4e322d, #4E322D);
}

.x1l7xqbyw {
  stop-color: var(--svg-color--de5534, #DE5534);
  stop-opacity: 0;
}

.x3sd7rf5r {
  stop-color: var(--svg-color--362324, #362324);
}

.x438pabwn {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M12.812 12.108c.343-.304 1.093-.623 2.023-.475");
}

.xfnas2msm {
  d: path("m16.146 14.271l-.558 1.784a.566.566 0 0 0 .547.734h.825c.387 0 .66-.373.546-.734l-.557-1.784c-.12-.395-.678-.395-.803 0");
}

.xft8gg3_m {
  stop-color: var(--svg-color--533e3c, #533E3C);
}

.xntzq-4ho {
  stop-color: var(--svg-color--8566b5, #8566B5);
}

.xtaxaigve {
  stop-color: var(--svg-color--624e4d, #624E4D);
  stop-opacity: 0;
}

.xtiplndwl {
  stop-color: var(--svg-color--3f222f, #3F222F);
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

.y2f_cuplr {
  fill: var(--svg-color--483032, #483032);
  d: path("M25.92 18.247a.668.668 0 1 1 1.316-.232l.34 2.222q.012.082.005.164l-.015.163c-.005.055-.002.11 0 .165c.016.295-.146.515-.454.557a.61.61 0 0 1-.68-.483z");
}

.y2ly1lryk {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-35px, 0.35px);
  d: path("M3.716 18.576c.177.245.672.953 1.492 1.172");
}

.yf9erdbmk {
  stop-color: var(--svg-color--4a4648, #4A4648);
  stop-opacity: 0;
}

.ym-b_m9fy {
  stop-color: var(--svg-color--d1bed4, #D1BED4);
  stop-opacity: 0;
}

.yr2jbccoa {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("m12.586 11.716l.003-.002l.005-.004l.012-.01a2 2 0 0 1 .163-.113c.104-.066.253-.147.44-.221a3 3 0 0 1 1.567-.166a.56.56 0 0 1-.175 1.106a1.86 1.86 0 0 0-.98.102a1.6 1.6 0 0 0-.315.167l-.008.006a.56.56 0 0 1-.713-.864");
}

.ytssyfa7a {
  stop-color: var(--svg-color--40272a, #40272A);
}

.yww6tz8di {
  stop-color: var(--svg-color--624d4b, #624D4B);
}

.z6jr4yb7o {
  stop-color: var(--svg-color--452a2d, #452A2D);
}

.zbexf6jod {
  stop-color: var(--svg-color--564848, #564848);
  stop-opacity: 0;
}

.zdcorrl9x {
  cx: 26.234px;
  cy: 14.83px;
  r: 1.684px;
}

.zlrx7kbjx {
  stroke: var(--svg-color--5e4e4d, #5E4E4D);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-35px, 0.35px);
  d: path("m26.849 18.13l.32 2.165");
}

.zoxadnjxe {
  stop-color: var(--svg-color--31171f, #31171F);
}

.zx1idre_k {
  stop-color: var(--svg-color--353435, #353435);
  stop-opacity: 0;
}

</style>
