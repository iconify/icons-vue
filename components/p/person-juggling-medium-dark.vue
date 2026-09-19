<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#i5uwaJe)"><path fill="url(#iPYYWhe)" class="swka_j87x"/><path fill="url(#iT07jwd)" class="swka_j87x"/><path fill="url(#il5eVUq)" class="swka_j87x"/><path fill="url(#iY3yYtd)" class="swka_j87x"/><path fill="url(#iv8FoOX)" class="swka_j87x"/></g><circle fill="url(#iBZ0RUd)" class="hpfqe6rjh"/><circle fill="url(#itKlKTd)" class="hpfqe6rjh"/><circle fill="url(#ihlr5IT)" class="duyhuibwk"/><circle fill="url(#iGUmgWd)" class="duyhuibwk"/><circle fill="url(#iXhqZHd)" class="iwbygtbvw"/><circle fill="url(#iOHvRJe)" class="iwbygtbvw"/><circle fill="url(#issuNue)" class="zdcorrl9x"/><circle fill="url(#iMaLBhb)" class="zdcorrl9x"/><circle fill="url(#iAhrvZc)" class="zdcorrl9x"/><g filter="url(#iRQvmcc)"><circle fill="url(#iMk8UMb)" class="t-5nldk3g"/></g><g filter="url(#iIj7mSb)"><circle fill="url(#iR23Gge)" class="don2wdpjw"/></g><path fill="url(#i5YvaPc)" class="j70rp9pis"/><path fill="url(#iK84mBb)" class="j70rp9pis"/><path fill="url(#iWCiqKd)" class="j70rp9pis"/><path fill="url(#ieol8Me)" class="qy4rrcb8b"/><path fill="url(#iDbbcbc)" class="qy4rrcb8b"/><path fill="url(#iOe2zrd)" class="qy4rrcb8b"/><path fill="url(#iV71Rbc)" class="qy4rrcb8b"/><g filter="url(#iiHTpeZ)"><path fill="url(#ih8Nxde)" class="kzmu-rrsy"/><path fill="url(#iQpTAtb)" class="kzmu-rrsy"/></g><path fill="url(#ipodSkc)" class="f21vmbcik"/><path fill="url(#iXPTZOc)" class="f21vmbcik"/><path fill="url(#itP1zjc)" class="wp2p6dbcv"/><path fill="url(#i33ZCUz)" class="wp2p6dbcv"/><g filter="url(#i0U4Hzd)"><path clip-rule="evenodd" class="byn6wubog"/></g><g filter="url(#i7cx0lb)"><path fill="url(#iSAsI1d)" class="ctsppjbax"/><path fill="url(#iwtPTOo)" class="ctsppjbax"/><path fill="url(#isAdhHe)" class="ctsppjbax"/></g><g filter="url(#ipV8A2d)"><path fill="url(#ivLP6Gc)" class="ht6lpfbpp"/><path fill="url(#iXetYud)" class="ht6lpfbpp"/></g><g filter="url(#isMmhBc)"><path fill="url(#i8tJXGc)" class="ld_83jb7a"/><path fill="url(#iw9bnJb)" class="ld_83jb7a"/></g><g filter="url(#iPVaW4b)"><path class="d8vr2qabd"/></g><g filter="url(#iVVK8ob)"><path class="fe5_67d9h"/></g><g filter="url(#izWLVUd)"><path class="lu7irnbsv"/></g><g filter="url(#il5SMWc)"><path class="a2erpabfq"/></g><g filter="url(#idXZgFd)"><path class="r_g462bwu"/></g><path fill="url(#iy5yhkB)" class="hw860-bkw"/><path fill="url(#iLYPeid)" class="hw860-bkw"/><path fill="url(#igEWuTd)" class="hw860-bkw"/><g filter="url(#ibQ8fYc)"><path fill="url(#iUsDf3b)" class="u5bjt8cdp"/></g><path fill="url(#iya7JRb)" clip-rule="evenodd" class="wfgw5ub6b"/><path fill="url(#ixz6Bfl)" clip-rule="evenodd" class="wfgw5ub6b"/><path fill="url(#iomTwyb)" clip-rule="evenodd" class="d5_x4xk7i"/><path fill="url(#il5DzUH)" clip-rule="evenodd" class="d5_x4xk7i"/><path fill="url(#iXmA6MA)" clip-rule="evenodd" class="ctupw6b3d"/><path fill="url(#ifjLIpe)" clip-rule="evenodd" class="ctupw6b3d"/><path fill="url(#iy5Lb5d)" clip-rule="evenodd" class="vdngsab5t"/><path fill="url(#iMyswRb)" clip-rule="evenodd" class="vdngsab5t"/><path fill="url(#izQ0wGc)" class="twba206ho"/><path fill="url(#iBECMpb)" class="twba206ho"/><path fill="url(#iEy58Nd)" class="k1soseb1u"/><g filter="url(#ibVpH0b)"><path class="rt394ibmb"/></g><g filter="url(#iotkPsd)"><path class="nuqjb3b3u"/></g><g filter="url(#iJyl8lb)"><path class="iinlnft3b"/></g><g filter="url(#iGH25bb)"><path class="vv0hkr84h"/></g><g filter="url(#iGkO5Xd)"><path stroke="url(#imI15oe)" class="bdk4dmb5b"/></g><g filter="url(#iFnk1Hc)"><path stroke="url(#iamKure)" class="gwm_2mjil"/></g><g filter="url(#iORhdwe)"><path stroke="url(#iGhB53d)" class="y2ly1lryk"/></g><g filter="url(#iFwMwve)"><path stroke="url(#ixXGBre)" class="am6k_ubte"/></g><g filter="url(#ic2APOe)"><path stroke="url(#iVKoQ5f)" class="c549xi8ae"/></g><g filter="url(#ixVXrye)"><path class="vcz9qnm9q"/></g><path fill="url(#ixeGorc)" class="sgymfgtlq"/><path fill="url(#ipIgdwd)" class="b4t1anbzn"/><g filter="url(#i4PSZuc)"><path fill="url(#iV9DoUc)" class="y9wvnhcxo"/><path fill="url(#iKOQDLb)" class="y9wvnhcxo"/></g><path fill="url(#ihoYEoS)" class="y9wvnhcxo"/><path fill="url(#iCjtprd)" class="y9wvnhcxo"/><path fill="url(#imCobLr)" class="y9wvnhcxo"/><path fill="url(#iyiSkLc)" class="y9wvnhcxo"/><path fill="url(#ixGqnPb)" class="y9wvnhcxo"/><path fill="url(#iQ2qpje)" class="y9wvnhcxo"/><path fill="url(#iWSGBLc)" class="y9wvnhcxo"/><path fill="url(#iqZlzZb)" class="y9wvnhcxo"/><g filter="url(#i8aiWKb)"><path class="wyxslbc9u"/></g><g filter="url(#iiC04Cb)"><path class="g8v8_wora"/><path fill="url(#iNPE4Kb)" class="c9k4y9jbh"/><path fill="url(#ip1rEfb)" class="c9k4y9jbh"/><path fill="url(#i1imeKe)" class="c9k4y9jbh"/><path fill="url(#iGhYhxs)" class="c9k4y9jbh"/><path fill="url(#iUtIiNc)" class="c9k4y9jbh"/></g><g filter="url(#iQzZKNe)"><path stroke="url(#iIPzNFe)" class="y4etjzfdh"/></g><path fill="url(#iUoWcOc)" class="mg5fqfjeo"/><g filter="url(#i0EeDpc)"><path fill="url(#i3qD2Oe)" class="jdk14lblf"/><path fill="url(#iNP6icb)" class="jdk14lblf"/><path fill="url(#iV1Y6nc)" class="jdk14lblf"/><path fill="url(#iFvIhuc)" class="jdk14lblf"/><path fill="url(#ihvhPdd)" class="jdk14lblf"/></g><g filter="url(#i3JdxPe)"><path class="wdtd_wboj"/></g><g filter="url(#iOCacdc)"><path class="h8m-46byo"/></g><path class="x2-vgab7k"/><path fill="url(#iSHrPZb)" class="x7nw9pbfq"/><path class="es232s36q"/><g filter="url(#ia3wjPZ)"><path class="l87c5y_dq"/><path fill="url(#iGqolVd)" class="v2j_a512e"/></g><g filter="url(#ipC5QBc)"><path fill="url(#iQkSN0d)" class="tmfmwacik"/></g><path class="ni991bcqt"/><path fill="url(#iVMj7Qc)" class="rl77jgbwx"/><path class="k513pqbyg"/><g filter="url(#iORTMMd)"><path fill="url(#iuYf2mc)" class="fd7j9wbmj"/></g><g filter="url(#iGeuYKb)"><ellipse transform="rotate(-27.914 14.26 13.265)" class="zgkl_ebsg"/><ellipse fill="url(#iR1rU4e)" transform="rotate(-27.914 14.26 13.265)" class="g2jhldb2e"/></g><path fill="url(#igdU3xb)" class="l4n0j6b7f"/><path fill="url(#iRI3aLb)" class="l4n0j6b7f"/><path fill="url(#iikLlpd)" class="l4n0j6b7f"/><path fill="url(#i26l8Cc)" class="l4n0j6b7f"/><path fill="url(#iIPPblc)" class="usrti_bee"/><path fill="url(#ivPW2mc)" class="usrti_bee"/><g filter="url(#iEenkQc)"><path fill="url(#iehsrOd)" class="p6kjyabmr"/></g><g filter="url(#iN0Yvmb)"><path fill="url(#iZp8ehD)" class="c1ucaijqv"/></g><g filter="url(#i0lcKUc)"><path class="lh9rvyx3m"/></g><g filter="url(#iwcXVlc)"><path class="maotw61mt"/></g><g filter="url(#i54RIAc)"><path class="hzaq54bmy"/></g><path fill="url(#iMwhdrV)" class="qzd219blo"/><path fill="url(#i3dSYhb)" class="qzd219blo"/><path fill="url(#inl9J2c)" class="qzd219blo"/><path fill="url(#iCE2gke)" class="wozepxbaa"/><path fill="url(#izP9Z9c)" class="wozepxbaa"/><rect fill="url(#ixSAAAe)" class="okwd93kys"/><rect fill="url(#iy7tjOa)" class="okwd93kys"/><rect fill="url(#iYE2hsb)" class="okwd93kys"/><defs><radialGradient id="iPYYWhe" cx="0" cy="0" r="1" gradientTransform="rotate(135.22 8.643 15.887)scale(12.9545 12.5552)" gradientUnits="userSpaceOnUse"><stop offset=".195" class="m-1-e5bla"/><stop offset=".794" class="b057dp4eh"/></radialGradient><radialGradient id="iT07jwd" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.09375 -3.28125 0 20.219 20.139)" gradientUnits="userSpaceOnUse"><stop class="m9gf32bwp"/><stop offset="1" class="n297mkbnr"/></radialGradient><radialGradient id="il5eVUq" cx="0" cy="0" r="1" gradientTransform="matrix(-1.75 0 0 -11.7187 21 25.92)" gradientUnits="userSpaceOnUse"><stop offset=".214" class="demkpcl0k"/><stop offset="1" class="ym-b_m9fy"/></radialGradient><radialGradient id="iY3yYtd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.15625 0 0 -5.75902 11.656 25.326)" gradientUnits="userSpaceOnUse"><stop class="ujrq6ixuu"/><stop offset="1" class="h4mko5b9o"/></radialGradient><radialGradient id="iv8FoOX" cx="0" cy="0" r="1" gradientTransform="matrix(2.12502 5.34374 -11.023 4.38346 13.099 18.733)" gradientUnits="userSpaceOnUse"><stop class="nl0wbpawx"/><stop offset="1" class="jm40s5baz"/></radialGradient><radialGradient id="iBZ0RUd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.34375 2.4375 -2.36069 -1.3014 7.187 11.826)" gradientUnits="userSpaceOnUse"><stop offset=".077" class="l-r9gxb9g"/><stop offset="1" class="hcmh5c50b"/></radialGradient><radialGradient id="itKlKTd" cx="0" cy="0" r="1" gradientTransform="rotate(115.145 -.151 8.247)scale(3.38309 2.95533)" gradientUnits="userSpaceOnUse"><stop offset=".452" class="y-1rsmdul"/><stop offset=".826" class="af8mzdbwl"/></radialGradient><radialGradient id="ihlr5IT" cx="0" cy="0" r="1" gradientTransform="matrix(-1.34375 2.4375 -2.36069 -1.3014 10.101 2.846)" gradientUnits="userSpaceOnUse"><stop offset=".077" class="mpwbs5b3u"/><stop offset="1" class="fzq016boz"/></radialGradient><radialGradient id="iGUmgWd" cx="0" cy="0" r="1" gradientTransform="rotate(115.145 4.158 4.683)scale(3.38309 2.95533)" gradientUnits="userSpaceOnUse"><stop offset=".452" class="x1l7xqbyw"/><stop offset=".826" class="ng1cexbhj"/></radialGradient><radialGradient id="iXhqZHd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.34375 2.4375 -2.36069 -1.3014 26.066 3.861)" gradientUnits="userSpaceOnUse"><stop offset=".077" class="lelj2r8dg"/><stop offset="1" class="fde_fwzpt"/></radialGradient><radialGradient id="iOHvRJe" cx="0" cy="0" r="1" gradientTransform="rotate(105.03 11.36 11.751)scale(3.49455 3.40391)" gradientUnits="userSpaceOnUse"><stop offset=".375" class="ppr920emc"/><stop offset=".826" class="y_auwli2s"/></radialGradient><radialGradient id="issuNue" cx="0" cy="0" r="1" gradientTransform="matrix(-1.34375 2.4375 -2.36069 -1.3014 27.09 13.818)" gradientUnits="userSpaceOnUse"><stop offset=".077" class="y05rrkbkk"/><stop offset="1" class="a5zzorbzd"/></radialGradient><radialGradient id="iMaLBhb" cx="0" cy="0" r="1" gradientTransform="matrix(1 1.07812 -1.5877 1.47265 24.969 13.357)" gradientUnits="userSpaceOnUse"><stop class="i8j0jyb4u"/><stop offset="1" class="d7caiobkz"/></radialGradient><radialGradient id="iAhrvZc" cx="0" cy="0" r="1" gradientTransform="rotate(109.11 8.51 16.52)scale(3.46022 3.37046)" gradientUnits="userSpaceOnUse"><stop offset=".347" class="tn_97qkdc"/><stop offset=".829" class="mmq2utbuk"/></radialGradient><radialGradient id="iMk8UMb" cx="0" cy="0" r="1" gradientTransform="matrix(-.7578 1.14063 -.96756 -.64282 17.25 27.855)" gradientUnits="userSpaceOnUse"><stop offset=".212" class="u6lph46no"/><stop offset="1" class="bq5dgsbba"/></radialGradient><radialGradient id="iR23Gge" cx="0" cy="0" r="1" gradientTransform="matrix(-.7578 1.14063 -.96756 -.64282 17.25 25.842)" gradientUnits="userSpaceOnUse"><stop offset=".212" class="u6lph46no"/><stop offset="1" class="bq5dgsbba"/></radialGradient><radialGradient id="i5YvaPc" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.03125 -2.40212 0 22.222 20.983)" gradientUnits="userSpaceOnUse"><stop class="koq0r9bvu"/><stop offset="1" class="dpmuo-biy"/></radialGradient><radialGradient id="ieol8Me" cx="0" cy="0" r="1" gradientTransform="scale(1.38818 6.1875)rotate(90 2.761 6.5)" gradientUnits="userSpaceOnUse"><stop class="xntzq-4ho"/><stop offset="1" class="pt8frltpn"/></radialGradient><radialGradient id="iDbbcbc" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.25 -.60938 0 13.062 24.108)" gradientUnits="userSpaceOnUse"><stop class="wshx69b-y"/><stop offset="1" class="aqzyd8bsb"/></radialGradient><radialGradient id="iOe2zrd" cx="0" cy="0" r="1" gradientTransform="matrix(2.9375 -7.98881 7.06186 2.59666 10.312 28.264)" gradientUnits="userSpaceOnUse"><stop offset=".724" class="lgi0lwbjz"/><stop offset="1" class="tvoyviyhj"/></radialGradient><radialGradient id="iV71Rbc" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.42188 -.18506 0 12.857 21.717)" gradientUnits="userSpaceOnUse"><stop class="m5avsc_ef"/><stop offset="1" class="ci3gi1b_k"/></radialGradient><radialGradient id="ih8Nxde" cx="0" cy="0" r="1" gradientTransform="matrix(-3.90624 2.42972 -4.28692 -6.89204 19.265 20.795)" gradientUnits="userSpaceOnUse"><stop class="ku63lg_wt"/><stop offset="1" class="i1-orb7ke"/></radialGradient><radialGradient id="iQpTAtb" cx="0" cy="0" r="1" gradientTransform="matrix(-.46875 -.125 .54686 -2.05079 19.188 22.482)" gradientUnits="userSpaceOnUse"><stop offset=".108" class="qsu4qbckq"/><stop offset="1" class="gr0wzobbs"/></radialGradient><radialGradient id="iSAsI1d" cx="0" cy="0" r="1" gradientTransform="matrix(1.73878 1.3451 -1.47727 1.90964 13.775 23.358)" gradientUnits="userSpaceOnUse"><stop class="ab6i82btp"/><stop offset="1" class="pb6efmson"/></radialGradient><radialGradient id="iwtPTOo" cx="0" cy="0" r="1" gradientTransform="matrix(-1.68958 -.4774 .79459 -2.81214 15.416 23.836)" gradientUnits="userSpaceOnUse"><stop offset=".69" class="sawf8hb2n"/><stop offset="1" class="o415o878f"/></radialGradient><radialGradient id="isAdhHe" cx="0" cy="0" r="1" gradientTransform="matrix(-.5 1.58457 -.75053 -.23683 16.11 23.836)" gradientUnits="userSpaceOnUse"><stop class="btor07b8q"/><stop offset="1" class="jjf293xlz"/></radialGradient><radialGradient id="ivLP6Gc" cx="0" cy="0" r="1" gradientTransform="rotate(142.275 5.895 15.056)scale(2.19833 2.41434)" gradientUnits="userSpaceOnUse"><stop class="auvn9fbbk"/><stop offset="1" class="h2li0wblg"/></radialGradient><radialGradient id="iXetYud" cx="0" cy="0" r="1" gradientTransform="matrix(1.68958 -.4774 .79459 2.81214 18.13 23.836)" gradientUnits="userSpaceOnUse"><stop offset=".69" class="sawf8hb2n"/><stop offset="1" class="o415o878f"/></radialGradient><radialGradient id="iw9bnJb" cx="0" cy="0" r="1" gradientTransform="matrix(-.39136 0 0 -2.59279 17.54 23.592)" gradientUnits="userSpaceOnUse"><stop class="scbqttb8d"/><stop offset="1" class="u1gl_1zha"/></radialGradient><radialGradient id="iy5yhkB" cx="0" cy="0" r="1" gradientTransform="matrix(-4.375 1.44046 -1.3893 -4.21963 28.098 22.456)" gradientUnits="userSpaceOnUse"><stop offset=".241" class="ykzqhbcyt"/><stop offset=".899" class="j20i63bee"/></radialGradient><radialGradient id="iLYPeid" cx="0" cy="0" r="1" gradientTransform="rotate(163.091 11.838 12.97)scale(3.90165 13.4872)" gradientUnits="userSpaceOnUse"><stop offset=".699" class="b9-qm444s"/><stop offset="1" class="lk_cbyb-c"/></radialGradient><radialGradient id="igEWuTd" cx="0" cy="0" r="1" gradientTransform="rotate(77.276 -.052 26.27)scale(.74486 4.08592)" gradientUnits="userSpaceOnUse"><stop class="xkn2wzmus"/><stop offset="1" class="ammr1_bix"/></radialGradient><radialGradient id="iUsDf3b" cx="0" cy="0" r="1" gradientTransform="rotate(139.97 1.2 10.48)scale(1.53045 3.638)" gradientUnits="userSpaceOnUse"><stop offset=".129" class="emrugab1j"/><stop offset="1" class="lc7su-9ui"/></radialGradient><radialGradient id="iya7JRb" cx="0" cy="0" r="1" gradientTransform="matrix(-.79386 1.27188 -2.4349 -1.51978 6.442 17.553)" gradientUnits="userSpaceOnUse"><stop class="swmlbjbuq"/><stop offset="1" class="ksmxe9b1k"/></radialGradient><radialGradient id="ixz6Bfl" cx="0" cy="0" r="1" gradientTransform="matrix(-.73037 2.48832 -3.82658 -1.12318 6.977 17.288)" gradientUnits="userSpaceOnUse"><stop offset=".585" class="p22s-zbfq"/><stop offset=".954" class="rq7piitrs"/></radialGradient><radialGradient id="iomTwyb" cx="0" cy="0" r="1" gradientTransform="rotate(116.602 -3.017 10.55)scale(1.58621 2.70684)" gradientUnits="userSpaceOnUse"><stop class="swmlbjbuq"/><stop offset="1" class="ksmxe9b1k"/></radialGradient><radialGradient id="il5DzUH" cx="0" cy="0" r="1" gradientTransform="matrix(-.65347 2.77477 -3.52334 -.82977 5.545 17.677)" gradientUnits="userSpaceOnUse"><stop offset=".585" class="p22s-zbfq"/><stop offset=".954" class="rq7piitrs"/></radialGradient><radialGradient id="iXmA6MA" cx="0" cy="0" r="1" gradientTransform="matrix(-.68468 1.22288 -2.2217 -1.2439 4.939 18.947)" gradientUnits="userSpaceOnUse"><stop class="swmlbjbuq"/><stop offset="1" class="ksmxe9b1k"/></radialGradient><radialGradient id="ifjLIpe" cx="0" cy="0" r="1" gradientTransform="rotate(104.751 -4.503 11.427)scale(2.474 3.46652)" gradientUnits="userSpaceOnUse"><stop offset=".585" class="p22s-zbfq"/><stop offset=".954" class="rq7piitrs"/></radialGradient><radialGradient id="iy5Lb5d" cx="0" cy="0" r="1" gradientTransform="rotate(122.692 -2.834 11.406)scale(1.24393 2.40994)" gradientUnits="userSpaceOnUse"><stop class="swmlbjbuq"/><stop offset="1" class="ksmxe9b1k"/></radialGradient><radialGradient id="iMyswRb" cx="0" cy="0" r="1" gradientTransform="matrix(-.61813 2.04813 -3.22394 -.973 5.687 19.733)" gradientUnits="userSpaceOnUse"><stop offset=".585" class="p22s-zbfq"/><stop offset=".954" class="rq7piitrs"/></radialGradient><radialGradient id="izQ0wGc" cx="0" cy="0" r="1" gradientTransform="rotate(-162.011 6.48 10.137)scale(3.69324 5.10277)" gradientUnits="userSpaceOnUse"><stop class="qjbq_nb5a"/><stop offset=".482" class="qr8h38bcf"/></radialGradient><radialGradient id="iBECMpb" cx="0" cy="0" r="1" gradientTransform="matrix(.07812 -.82813 3.88844 .36683 6.156 21.78)" gradientUnits="userSpaceOnUse"><stop class="sirm6td-l"/><stop offset="1" class="faah7i3zw"/></radialGradient><radialGradient id="iEy58Nd" cx="0" cy="0" r="1" gradientTransform="matrix(1.65625 2.09375 -2.38774 1.88881 15.815 20.443)" gradientUnits="userSpaceOnUse"><stop offset=".229" class="bo6_cwbgw"/><stop offset="1" class="uqr6xg6is"/></radialGradient><radialGradient id="ixeGorc" cx="0" cy="0" r="1" gradientTransform="matrix(.78763 2.12432 -2.52353 .93564 21.841 15.32)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="cbylncbjf"/><stop offset="1" class="hj2nkngkt"/></radialGradient><radialGradient id="ipIgdwd" cx="0" cy="0" r="1" gradientTransform="rotate(17.447 -46.364 42.036)scale(1.62797 5.02238)" gradientUnits="userSpaceOnUse"><stop class="i4otoyosx"/><stop offset=".746" class="zqff1532o"/></radialGradient><radialGradient id="iV9DoUc" cx="0" cy="0" r="1" gradientTransform="matrix(-5.4991 0 0 -9.72785 19.795 14.33)" gradientUnits="userSpaceOnUse"><stop class="e4t6-lb6y"/><stop offset="1" class="hhi9hubjb"/><stop offset="1" class="hhi9hubjb"/></radialGradient><radialGradient id="iKOQDLb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.8336 3.03254 -2.5036 -1.51379 19.394 9.092)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="fajfg00jo"/><stop offset="1" class="wpa_x2uhd"/></radialGradient><radialGradient id="iCjtprd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.3909 7.75155 0 16.822 21.051)" gradientUnits="userSpaceOnUse"><stop offset=".168" class="hjvcixbup"/><stop offset=".432" class="jg-b8c5-y"/><stop offset="1" class="y7x-29baz"/></radialGradient><radialGradient id="imCobLr" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.20793 1.49482 0 19.415 12.948)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="o847wybrn"/><stop offset="1" class="z-0dlhbai"/></radialGradient><radialGradient id="iyiSkLc" cx="0" cy="0" r="1" gradientTransform="matrix(.00413 -1.15105 1.25262 .0045 14.422 12.997)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="pxeuj6buu"/><stop offset="1" class="lg98p_5je"/></radialGradient><radialGradient id="ixGqnPb" cx="0" cy="0" r="1" gradientTransform="matrix(-8.9368 .56414 -1.44108 -22.82906 20.452 15.369)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="sim-rnb6d"/><stop offset="1" class="vx5g9qbgu"/></radialGradient><radialGradient id="iQ2qpje" cx="0" cy="0" r="1" gradientTransform="matrix(3.56146 -3.0678 .90618 1.052 9.697 11.455)" gradientUnits="userSpaceOnUse"><stop offset=".539" class="sf65_-b_u"/><stop offset="1" class="n9ebefe8q"/></radialGradient><radialGradient id="iWSGBLc" cx="0" cy="0" r="1" gradientTransform="matrix(-.24683 2.62702 -1.05012 -.09867 22.674 11.26)" gradientUnits="userSpaceOnUse"><stop offset=".245" class="p54kb3bjj"/><stop offset="1" class="rm9y2hb6m"/></radialGradient><radialGradient id="ip1rEfb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .25677 -.80699 0 17.331 15.76)" gradientUnits="userSpaceOnUse"><stop class="eqmylox_y"/><stop offset="1" class="sicchzd0u"/></radialGradient><radialGradient id="iGhYhxs" cx="0" cy="0" r="1" gradientTransform="matrix(-1.60007 .73362 -1.17898 -2.57145 17.454 15.162)" gradientUnits="userSpaceOnUse"><stop offset=".714" class="cjboikbop"/><stop offset="1" class="l6ffphqdg"/></radialGradient><radialGradient id="iUoWcOc" cx="0" cy="0" r="1" gradientTransform="rotate(-26.18 47.17 -26.033)scale(2.55757 10.2898)" gradientUnits="userSpaceOnUse"><stop offset=".562" class="etju2kb3q"/><stop offset="1" class="iazz9lb4s"/></radialGradient><radialGradient id="iNP6icb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.68299 9.31386 0 11.34 11.287)" gradientUnits="userSpaceOnUse"><stop offset=".536" class="ibt06e6rm"/><stop offset="1" class="k45xjwbmq"/></radialGradient><radialGradient id="iV1Y6nc" cx="0" cy="0" r="1" gradientTransform="matrix(.11996 -2.6429 4.6827 .21254 21.954 12.665)" gradientUnits="userSpaceOnUse"><stop class="c98z413ze"/><stop offset="1" class="ovvtmacpn"/></radialGradient><radialGradient id="iFvIhuc" cx="0" cy="0" r="1" gradientTransform="rotate(-146.667 11.488 -.136)scale(2.96977 2.17997)" gradientUnits="userSpaceOnUse"><stop class="jx9hffbwe"/><stop offset="1" class="mzj8iibqz"/></radialGradient><radialGradient id="ihvhPdd" cx="0" cy="0" r="1" gradientTransform="rotate(60.727 4.2 15.755)scale(1.44491 3.34574)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="e8ajgab-k"/><stop offset="1" class="gxf7b0v7y"/></radialGradient><radialGradient id="iSHrPZb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .85342 -1.35745 0 19.136 13.366)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="iGqolVd" cx="0" cy="0" r="1" gradientTransform="rotate(-127.811 12.743 2.1)scale(.39792 .54783)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iVMj7Qc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .85346 -1.35752 0 14.546 13.366)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="iR1rU4e" cx="0" cy="0" r="1" gradientTransform="matrix(-.00814 -.51972 .62472 -.00978 14.245 13.596)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iRI3aLb" cx="0" cy="0" r="1" gradientTransform="matrix(.66116 2.35966 -2.2513 .6308 21.698 13.38)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="xron-kbnx"/><stop offset="1" class="bzyp_ibbo"/></radialGradient><radialGradient id="iikLlpd" cx="0" cy="0" r="1" gradientTransform="matrix(.82866 -1.1372 .9532 .69458 22.078 13.953)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="w_o-5kbak"/><stop offset="1" class="mb4bnzbbk"/></radialGradient><radialGradient id="i26l8Cc" cx="0" cy="0" r="1" gradientTransform="matrix(.61745 -1.63087 2.17906 .825 22.198 14.134)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="sxoyafbbn"/><stop offset="1" class="tri7bg95c"/></radialGradient><radialGradient id="ivPW2mc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.74429 0 0 -1.94775 11.67 14.055)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="srn41o2oz"/><stop offset="1" class="dfc36bbxx"/></radialGradient><radialGradient id="iehsrOd" cx="0" cy="0" r="1" gradientTransform="matrix(-.96403 .16548 -.16967 -.98843 11.672 14.057)" gradientUnits="userSpaceOnUse"><stop class="m_eaw6bxg"/><stop offset="1" class="nk_trfbso"/></radialGradient><radialGradient id="iMwhdrV" cx="0" cy="0" r="1" gradientTransform="matrix(-5.5 4.12501 -3.615 -4.82 20.719 4.576)" gradientUnits="userSpaceOnUse"><stop offset=".179" class="tg07-ljnl"/><stop offset="1" class="c6833cb9x"/></radialGradient><radialGradient id="i3dSYhb" cx="0" cy="0" r="1" gradientTransform="matrix(2.875 .375 -.58342 4.4729 10.781 7.701)" gradientUnits="userSpaceOnUse"><stop class="j8k1fac_p"/><stop offset="1" class="g8uem1b5g"/></radialGradient><radialGradient id="inl9J2c" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.875 8.03906 0 16.773 8.326)" gradientUnits="userSpaceOnUse"><stop offset=".761" class="km6q7kb1a"/><stop offset="1" class="i8skpb2jz"/></radialGradient><radialGradient id="iCE2gke" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.47656 -8.28125 0 18.406 7.912)" gradientUnits="userSpaceOnUse"><stop class="kzuil_5zu"/><stop offset="1" class="ok2r3obil"/></radialGradient><radialGradient id="ixSAAAe" cx="0" cy="0" r="1" gradientTransform="matrix(-7.1875 0 0 -.63281 21.269 9.87)" gradientUnits="userSpaceOnUse"><stop class="w63qn2bkh"/><stop offset="1" class="vvfum-_fa"/></radialGradient><radialGradient id="iy7tjOa" cx="0" cy="0" r="1" gradientTransform="matrix(3.48438 0 0 2.01172 9.003 10.109)" gradientUnits="userSpaceOnUse"><stop class="gfrsedb9v"/><stop offset="1" class="vke6kh8bt"/></radialGradient><filter id="i5uwaJe" width="21.247" height="10.303" x="6.25" y="19.623" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.615686 0 0 0 0 0.607843 0 0 0 0 0.619608 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23849"/></filter><filter id="iRQvmcc" width="2.078" height="2.078" x="15.622" y="27.457" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.792157 0 0 0 0 0.717647 0 0 0 0 0.788235 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_3987_23849"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_3987_23849" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.831373 0 0 0 0 0.745098 0 0 0 0 0.803922 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_3987_23849"/></filter><filter id="iIj7mSb" width="2.078" height="2.078" x="15.622" y="25.444" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.792157 0 0 0 0 0.717647 0 0 0 0 0.788235 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_3987_23849"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_3987_23849" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.831373 0 0 0 0 0.745098 0 0 0 0 0.803922 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_3987_23849"/></filter><filter id="iiHTpeZ" width="6.554" height="3.702" x="13.38" y="19.523" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.721569 0 0 0 0 0.682353 0 0 0 0 0.74902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23849"/></filter><filter id="i0U4Hzd" width="7.432" height="4.46" x="12.567" y="22.084" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23849" stdDeviation=".5"/></filter><filter id="i7cx0lb" width="2.672" height="2.865" x="13.611" y="22.403" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.780392 0 0 0 0 0.270588 0 0 0 0 0.396078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23849"/></filter><filter id="ipV8A2d" width="2.672" height="2.865" x="17.264" y="22.403" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.780392 0 0 0 0 0.270588 0 0 0 0 0.396078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23849"/></filter><filter id="isMmhBc" width="1.554" height="1.999" x="15.986" y="22.812" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.827451 0 0 0 0 0.137255 0 0 0 0 0.317647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23849"/></filter><filter id="iPVaW4b" width="4.764" height="4.766" x="24.75" y="19.349" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.1"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.462745 0 0 0 0 0.282353 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23849"/></filter><filter id="iVVK8ob" width="2.077" height="3.844" x="25.907" y="17.448" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.431373 0 0 0 0 0.282353 0 0 0 0 0.247059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23849"/></filter><filter id="izWLVUd" width="2.401" height="4.052" x="24.436" y="17.107" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.431373 0 0 0 0 0.282353 0 0 0 0 0.247059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23849"/></filter><filter id="il5SMWc" width="2.312" height="4.044" x="23.386" y="17.96" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.431373 0 0 0 0 0.282353 0 0 0 0 0.247059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23849"/></filter><filter id="idXZgFd" width="2.123" height="3.114" x="22.394" y="19.041" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.431373 0 0 0 0 0.282353 0 0 0 0 0.247059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23849"/></filter><filter id="ibQ8fYc" width="3.002" height="3.147" x="6.649" y="16.347" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.431373 0 0 0 0 0.262745 0 0 0 0 0.219608 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23849"/></filter><filter id="ibVpH0b" width="1.264" height="2.491" x="22.908" y="19.19" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23849" stdDeviation=".125"/></filter><filter id="iotkPsd" width="1.286" height="2.978" x="23.933" y="18.124" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23849" stdDeviation=".125"/></filter><filter id="iJyl8lb" width="1.444" height="3.775" x="24.963" y="17.226" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23849" stdDeviation=".125"/></filter><filter id="iGH25bb" width="1.17" height="3.014" x="26.424" y="17.706" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23849" stdDeviation=".125"/></filter><filter id="iGkO5Xd" width="1.788" height="2.6" x="27.33" y="19.87" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23849" stdDeviation=".125"/></filter><filter id="iFnk1Hc" width="2.323" height="1.69" x="3.752" y="19.44" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23849" stdDeviation=".125"/></filter><filter id="iORhdwe" width="2.342" height="2.022" x="3.291" y="18.151" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23849" stdDeviation=".125"/></filter><filter id="iFwMwve" width="2.131" height="2.124" x="4.556" y="16.714" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23849" stdDeviation=".125"/></filter><filter id="ic2APOe" width="2.569" height="2.444" x="3.345" y="17.042" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23849" stdDeviation=".125"/></filter><filter id="ixVXrye" width="5.441" height="3.076" x="17.747" y="6.733" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23849" stdDeviation=".375"/></filter><filter id="i4PSZuc" width="11.751" height="13.182" x="11.515" y="7.838" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".7"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.494118 0 0 0 0 0.352941 0 0 0 0 0.32549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23849"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.396078 0 0 0 0 0.215686 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23849" result="effect2_innerShadow_3987_23849"/></filter><filter id="i8aiWKb" width="3.837" height="5.051" x="14.773" y="12.462" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23849" stdDeviation=".5"/></filter><filter id="iiC04Cb" width="2.375" height="3.451" x="15.654" y="13.056" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23849" stdDeviation=".1"/></filter><filter id="iQzZKNe" width="3.885" height="1.628" x="14.898" y="16.762" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23849" stdDeviation=".05"/></filter><filter id="i0EeDpc" width="12.895" height="8.764" x="10.402" y="4.523" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.137255 0 0 0 0 0.0901961 0 0 0 0 0.145098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23849"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0784314 0 0 0 0 0.0352941 0 0 0 0 0.0470588 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23849" result="effect2_innerShadow_3987_23849"/></filter><filter id="i3JdxPe" width="2.455" height="1.242" x="18.513" y="10.959" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.172549 0 0 0 0 0.0862745 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23849"/></filter><filter id="iOCacdc" width="2.455" height="1.226" x="12.983" y="10.975" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.172549 0 0 0 0 0.0862745 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23849"/></filter><filter id="ia3wjPZ" width=".817" height=".722" x="18.369" y="12.908" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23849" stdDeviation=".05"/></filter><filter id="ipC5QBc" width=".917" height=".94" x="19.258" y="12.992" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23849" stdDeviation=".1"/></filter><filter id="iORTMMd" width="1.017" height="1.073" x="14.585" y="12.925" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23849" stdDeviation=".1"/></filter><filter id="iGeuYKb" width=".95" height=".731" x="13.786" y="12.899" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23849" stdDeviation=".05"/></filter><filter id="iEenkQc" width="1.372" height="2.477" x="10.458" y="12.819" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23849" stdDeviation=".125"/></filter><filter id="iN0Yvmb" width="1.996" height="3.002" x="21.541" y="12.549" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23849" stdDeviation=".25"/></filter><filter id="i0lcKUc" width="2.491" height="1.181" x="12.918" y="11.062" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23849" stdDeviation=".125"/></filter><filter id="iwcXVlc" width="2.491" height="1.181" x="18.471" y="11.014" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23849" stdDeviation=".125"/></filter><filter id="i54RIAc" width="5.461" height="3.084" x="17.805" y="6.608" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23849" stdDeviation=".375"/></filter><linearGradient id="iK84mBb" x1="22.562" x2="21.812" y1="29.826" y2="29.826" gradientUnits="userSpaceOnUse"><stop class="fr__qmhjc"/><stop offset="1" class="gypp10kih"/></linearGradient><linearGradient id="iWCiqKd" x1="20.644" x2="21.062" y1="29.014" y2="29.014" gradientUnits="userSpaceOnUse"><stop class="hj-s-zboe"/><stop offset="1" class="s0umluqbl"/></linearGradient><linearGradient id="ipodSkc" x1="9.531" x2="4.906" y1="27.451" y2="27.451" gradientUnits="userSpaceOnUse"><stop class="sb-ednb_a"/><stop offset="1" class="v0501vbqa"/></linearGradient><linearGradient id="iXPTZOc" x1="9.75" x2="8.828" y1="27.076" y2="27.076" gradientUnits="userSpaceOnUse"><stop class="o_30au2yc"/><stop offset="1" class="c60cvac3k"/></linearGradient><linearGradient id="itP1zjc" x1="27.871" x2="22.844" y1="28.142" y2="28.142" gradientUnits="userSpaceOnUse"><stop class="i7zyuv8vr"/><stop offset=".907" class="qzhltkbuo"/></linearGradient><linearGradient id="i33ZCUz" x1="28.09" x2="27.168" y1="27.876" y2="27.876" gradientUnits="userSpaceOnUse"><stop class="tub8lbbfx"/><stop offset="1" class="bd09vtb_c"/></linearGradient><linearGradient id="i8tJXGc" x1="16.763" x2="16.763" y1="22.812" y2="24.81" gradientUnits="userSpaceOnUse"><stop offset=".351" class="gzsz7evmk"/><stop offset="1" class="smgiue0gi"/></linearGradient><linearGradient id="imI15oe" x1="29.13" x2="28.38" y1="20.034" y2="21.659" gradientUnits="userSpaceOnUse"><stop class="au5hixbak"/><stop offset="1" class="mcp_a12ev"/><stop offset="1" class="i4lia-rzw"/></linearGradient><linearGradient id="iamKure" x1="4.76" x2="5.331" y1="20.169" y2="21.223" gradientUnits="userSpaceOnUse"><stop class="a86-seumw"/><stop offset="1" class="u5lbkrb_x"/></linearGradient><linearGradient id="iGhB53d" x1="4.307" x2="5.218" y1="19" y2="20.223" gradientUnits="userSpaceOnUse"><stop class="a86-seumw"/><stop offset="1" class="u5lbkrb_x"/></linearGradient><linearGradient id="ixXGBre" x1="5.489" x2="6.52" y1="17.6" y2="18.693" gradientUnits="userSpaceOnUse"><stop class="a86-seumw"/><stop offset="1" class="u5lbkrb_x"/></linearGradient><linearGradient id="iVKoQ5f" x1="4.452" x2="5.734" y1="18.044" y2="19.502" gradientUnits="userSpaceOnUse"><stop class="a86-seumw"/><stop offset="1" class="u5lbkrb_x"/></linearGradient><linearGradient id="ihoYEoS" x1="22.266" x2="19.606" y1="16.102" y2="16.102" gradientUnits="userSpaceOnUse"><stop class="agilw2byy"/><stop offset="1" class="h3kh2yb2k"/></linearGradient><linearGradient id="iqZlzZb" x1="16.891" x2="16.891" y1="9.784" y2="11.909" gradientUnits="userSpaceOnUse"><stop offset=".471" class="u9e5rgnkp"/><stop offset="1" class="vcrfrnsjt"/></linearGradient><linearGradient id="iNPE4Kb" x1="17.723" x2="16.841" y1="15.039" y2="15.076" gradientUnits="userSpaceOnUse"><stop offset=".36" class="eqmylox_y"/><stop offset="1" class="sicchzd0u"/></linearGradient><linearGradient id="i1imeKe" x1="16.841" x2="16.841" y1="16.238" y2="15.748" gradientUnits="userSpaceOnUse"><stop class="qsncw6btn"/><stop offset="1" class="v7xhdx32s"/></linearGradient><linearGradient id="iUtIiNc" x1="16.841" x2="16.841" y1="13.392" y2="13.967" gradientUnits="userSpaceOnUse"><stop class="fok393bvn"/><stop offset="1" class="y4umwkb_f"/></linearGradient><linearGradient id="iIPzNFe" x1="15.577" x2="15.912" y1="17.89" y2="17.012" gradientUnits="userSpaceOnUse"><stop class="t_m5csgaz"/><stop offset="1" class="ln8xouyxx"/></linearGradient><linearGradient id="i3qD2Oe" x1="24.049" x2="11.834" y1="8.373" y2="8.373" gradientUnits="userSpaceOnUse"><stop class="s5pji6bqr"/><stop offset="1" class="c7qpv738k"/></linearGradient><linearGradient id="iQkSN0d" x1="19.955" x2="19.625" y1="13.422" y2="13.626" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iuYf2mc" x1="15.328" x2="14.998" y1="13.422" y2="13.626" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="igdU3xb" x1="23.611" x2="22.342" y1="13.45" y2="15.74" gradientUnits="userSpaceOnUse"><stop class="pkjt6qfem"/><stop offset="1" class="qw3t0fbxr"/></linearGradient><linearGradient id="iIPPblc" x1="10.688" x2="12.222" y1="14.191" y2="14.057" gradientUnits="userSpaceOnUse"><stop class="lsjj5yb-k"/><stop offset="1" class="ac3zxpbrp"/></linearGradient><linearGradient id="iZp8ehD" x1="22.538" x2="22.538" y1="13.049" y2="15.051" gradientUnits="userSpaceOnUse"><stop class="x9ttejxmc"/><stop offset="1" class="nal-rljch"/></linearGradient><linearGradient id="izP9Z9c" x1="16.773" x2="16.773" y1="7.912" y2="8.1" gradientUnits="userSpaceOnUse"><stop class="jhlen960d"/><stop offset="1" class="wjchuwb6a"/></linearGradient><linearGradient id="iYE2hsb" x1="17.956" x2="17.956" y1="10.98" y2="10.214" gradientUnits="userSpaceOnUse"><stop class="bl3fq0x9z"/><stop offset="1" class="lxo7c2i6k"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-juggling-medium-dark" /></template>
<style>
.a2erpabfq {
  fill: var(--svg-color--7e595a, #7E595A);
  d: path("M23.407 18.803a.679.679 0 1 1 1.323-.298l.555 2.766a.613.613 0 0 1-1.195.27z");
}

.a5zzorbzd {
  stop-color: var(--svg-color--e1ac3a, #E1AC3A);
}

.a86-seumw {
  stop-color: var(--svg-color--977872, #977872);
}

.ab6i82btp {
  stop-color: var(--svg-color--e7377c, #E7377C);
}

.ac3zxpbrp {
  stop-color: var(--svg-color--623549, #623549);
}

.af8mzdbwl {
  stop-color: var(--svg-color--5f679a, #5F679A);
}

.agilw2byy {
  stop-color: var(--svg-color--936b5d, #936B5D);
}

.am6k_ubte {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-35px, 0.35px);
  d: path("M4.981 17.139c.11.172.625 1.078 1.282 1.273");
}

.ammr1_bix {
  stop-color: var(--svg-color--7e595a, #7E595A);
  stop-opacity: 0;
}

.aqzyd8bsb {
  stop-color: var(--svg-color--896bb4, #896BB4);
  stop-opacity: 0;
}

.au5hixbak {
  stop-color: var(--svg-color--9b7b72, #9B7B72);
}

.auvn9fbbk {
  stop-color: var(--svg-color--e9387a, #E9387A);
}

.b057dp4eh {
  stop-color: var(--svg-color--ccbdde, #CCBDDE);
}

.b4t1anbzn {
  d: path("M11.728 15.644a1.73 1.73 0 0 1-.952-.325v.98c0 .94.56 1.776 1.41 2.123a4.3 4.3 0 0 1-.363-1.24z");
}

.b9-qm444s {
  stop-color: var(--svg-color--784b52, #784B52);
  stop-opacity: 0;
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

.bl3fq0x9z {
  stop-color: var(--svg-color--543459, #543459);
}

.bo6_cwbgw {
  stop-color: var(--svg-color--693443, #693443);
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

.bzyp_ibbo {
  stop-color: var(--svg-color--71404f, #71404F);
}

.c1ucaijqv {
  d: path("M22.04 15.05q.061-1 .117-2.001a1.005 1.005 0 0 1-.116 2.002");
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

.c7qpv738k {
  stop-color: var(--svg-color--362c2e, #362C2E);
}

.c98z413ze {
  stop-color: var(--svg-color--4f4d4d, #4F4D4D);
}

.c9k4y9jbh {
  d: path("m16.439 13.578l-.56 1.933c-.113.398.16.796.548.796h.828c.387 0 .661-.404.547-.796l-.559-1.933c-.12-.429-.679-.429-.804 0");
}

.cbylncbjf {
  stop-color: var(--svg-color--332f31, #332F31);
}

.ci3gi1b_k {
  stop-color: var(--svg-color--784b89, #784B89);
  stop-opacity: 0;
}

.cjboikbop {
  stop-color: var(--svg-color--744a4a, #744A4A);
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

.d5_x4xk7i {
  fill-rule: evenodd;
  d: path("M3.16 17.066a.75.75 0 0 1 1.042.197q.055.08.116.173c.17.259.379.576.676.877c.36.363.768.614 1.246.64a.75.75 0 0 1-.08 1.497c-.99-.052-1.73-.575-2.232-1.083c-.416-.42-.725-.893-.888-1.143l-.076-.115a.75.75 0 0 1 .196-1.043");
}

.d7caiobkz {
  stop-color: var(--svg-color--e4cc30, #E4CC30);
  stop-opacity: 0;
}

.d8vr2qabd {
  fill: var(--svg-color--8d665f, #8D665F);
  d: path("m27.85 19.83l-.447.824l-1.172 1.422l-1.481 1.992l3.099.047c.099-.172.218-.566.38-1.327c.164-.66.326-1.114.471-1.376l.443-.924a.726.726 0 0 0-1.292-.659");
}

.demkpcl0k {
  stop-color: var(--svg-color--b1a0b8, #B1A0B8);
}

.dfc36bbxx {
  stop-color: var(--svg-color--836158, #836158);
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

.e4t6-lb6y {
  stop-color: var(--svg-color--9a6e61, #9A6E61);
}

.e8ajgab-k {
  stop-color: var(--svg-color--392f31, #392F31);
}

.emrugab1j {
  stop-color: var(--svg-color--84665d, #84665D);
}

.eqmylox_y {
  stop-color: var(--svg-color--a17c72, #A17C72);
}

.es232s36q {
  fill: var(--svg-color--000, #000);
  d: path("M18.601 13.802c0-.298.239-.537.538-.537a.535.535 0 0 1 .477.785h-.951a.5.5 0 0 1-.064-.248");
}

.etju2kb3q {
  stop-color: var(--svg-color--87004e, #87004E);
}

.f21vmbcik {
  d: path("M5.437 21.764h4.094v8.063H5.437z");
}

.faah7i3zw {
  stop-color: var(--svg-color--846252, #846252);
  stop-opacity: 0;
}

.fajfg00jo {
  stop-color: var(--svg-color--855e5a, #855E5A);
}

.fd7j9wbmj {
  d: path("M15.402 13.692c0-.303-.247-.505-.314-.566l-.303.293l.187.38z");
}

.fde_fwzpt {
  stop-color: var(--svg-color--5c9946, #5C9946);
}

.fe5_67d9h {
  fill: var(--svg-color--7e595a, #7E595A);
  d: path("M25.92 18.247a.668.668 0 1 1 1.316-.232l.34 2.222q.012.082.005.164l-.015.163c-.005.055-.002.11 0 .165c.016.295-.146.515-.454.557a.61.61 0 0 1-.68-.483z");
}

.fok393bvn {
  stop-color: var(--svg-color--865c56, #865C56);
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

.g2jhldb2e {
  cx: 14.261px;
  cy: 13.265px;
  rx: 0.41px;
  ry: 0.207px;
}

.g8uem1b5g {
  stop-color: var(--svg-color--38303e, #38303E);
  stop-opacity: 0;
}

.g8v8_wora {
  fill: var(--svg-color--845b55, #845B55);
  d: path("m16.439 13.578l-.56 1.933c-.113.398.16.796.548.796h.828c.387 0 .661-.404.547-.796l-.559-1.933c-.12-.429-.679-.429-.804 0");
}

.gfrsedb9v {
  stop-color: var(--svg-color--5b595e, #5B595E);
}

.gr0wzobbs {
  stop-color: var(--svg-color--dbcdd4, #DBCDD4);
  stop-opacity: 0;
}

.gwm_2mjil {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-35px, 0.35px);
  d: path("M4.177 19.865c.177.245.832.742 1.472.84");
}

.gxf7b0v7y {
  stop-color: var(--svg-color--392f31, #392F31);
  stop-opacity: 0;
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

.h3kh2yb2k {
  stop-color: var(--svg-color--936b5d, #936B5D);
  stop-opacity: 0;
}

.h4mko5b9o {
  stop-color: var(--svg-color--beb4c6, #BEB4C6);
  stop-opacity: 0;
}

.h8m-46byo {
  fill: var(--svg-color--2e201f, #2E201F);
  d: path("M13.253 11.575a2.92 2.92 0 0 1 1.83-.378a.292.292 0 0 1-.072.579a2.33 2.33 0 0 0-1.458.3l-.097.062l-.003.002a.292.292 0 0 1-.357-.46z");
}

.hcmh5c50b {
  stop-color: var(--svg-color--357ace, #357ACE);
}

.hhi9hubjb {
  stop-color: var(--svg-color--754c4c, #754C4C);
}

.hj-s-zboe {
  stop-color: var(--svg-color--6d5096, #6D5096);
}

.hj2nkngkt {
  stop-color: var(--svg-color--221925, #221925);
}

.hjvcixbup {
  stop-color: var(--svg-color--7b3a46, #7B3A46);
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

.hzaq54bmy {
  fill: var(--svg-color--49373d, #49373D);
  d: path("M21.252 8.376h-2.19a.508.508 0 1 1 .082-1.011c.568.09 1.322.216 1.827.341c1.142.284 1.457.84 1.545 1.236a1.6 1.6 0 0 0-1.264-.566");
}

.i1-orb7ke {
  stop-color: var(--svg-color--c3b7c1, #C3B7C1);
}

.i4lia-rzw {
  stop-color: var(--svg-color--9b7b72, #9B7B72);
  stop-opacity: 0;
}

.i4otoyosx {
  stop-color: var(--svg-color--3e3330, #3E3330);
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

.ibt06e6rm {
  stop-color: var(--svg-color--3e3433, #3E3433);
}

.iinlnft3b {
  stroke: var(--svg-color--997971, #997971);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-35px, 0.35px);
  d: path("m25.388 17.65l.593 2.926");
}

.iwbygtbvw {
  cx: 25.211px;
  cy: 4.873px;
  r: 1.684px;
}

.j20i63bee {
  stop-color: var(--svg-color--835a55, #835A55);
}

.j70rp9pis {
  d: path("M22.222 29.826h-1.578v-9.568q.826.307 1.578.746z");
}

.j8k1fac_p {
  stop-color: var(--svg-color--5b5a5d, #5B5A5D);
}

.jdk14lblf {
  d: path("M21.948 7.342c.541.186-.307 1.494 0 2.036c.491.863 1.752.965 1.222 1.727a1.64 1.64 0 0 0-.285.92v1.25a1.8 1.8 0 0 0-.702-.283l.083-1.69a1.525 1.525 0 0 0-1.45-1.506h-1.473a2.55 2.55 0 0 1-2.327-1.518a.7.7 0 0 0-.647-.44H15.03c-1.941 0-3.515 1.591-3.515 3.555l.033 1.617a1.8 1.8 0 0 0-.758.277v-1.262c0-.328-.1-.65-.284-.92c-.502-.74.964-.886 1.405-1.727c.307-.581-.753-1.833-.19-2.03a2.82 2.82 0 0 0 1.457-1.168a2.446 2.446 0 0 1 3.04-.96c.402.175.854.175 1.256 0c.295-.124.619-.197.96-.197c.886 0 1.662.48 2.091 1.19c.324.536.832.926 1.423 1.129");
}

.jg-b8c5-y {
  stop-color: var(--svg-color--794057, #794057);
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

.jx9hffbwe {
  stop-color: var(--svg-color--402c32, #402C32);
}

.k1soseb1u {
  d: path("M14.545 18.417c0-.99.9-1.794 2.012-1.794c1.11 0 2.012.803 2.012 1.794v2.326c0 .99-.901 1.794-2.012 1.794s-2.012-.803-2.012-1.794z");
}

.k45xjwbmq {
  stop-color: var(--svg-color--3e3433, #3E3433);
  stop-opacity: 0;
}

.k513pqbyg {
  fill: var(--svg-color--000, #000);
  d: path("M15.082 13.802a.535.535 0 0 0-.538-.537a.535.535 0 0 0-.478.785h.952a.5.5 0 0 0 .064-.248");
}

.km6q7kb1a {
  stop-color: var(--svg-color--5d5565, #5D5565);
  stop-opacity: 0;
}

.koq0r9bvu {
  stop-color: var(--svg-color--9e78c9, #9E78C9);
}

.ksmxe9b1k {
  stop-color: var(--svg-color--7a5349, #7A5349);
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

.l4n0j6b7f {
  d: path("M22.018 15.74q.106-1.68.195-3.357a1.693 1.693 0 0 1-.195 3.357");
}

.l6ffphqdg {
  stop-color: var(--svg-color--744a4a, #744A4A);
}

.l87c5y_dq {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M19.07 13.062c.067.09-.073.199-.232.318c-.16.118-.277.202-.344.112c-.067-.089.008-.258.167-.377s.342-.142.409-.053");
}

.lc7su-9ui {
  stop-color: var(--svg-color--7f5a4b, #7F5A4B);
}

.ld_83jb7a {
  d: path("M16.018 23.224a.41.41 0 0 1 .328-.37a2.1 2.1 0 0 1 .834 0a.41.41 0 0 1 .328.37c.042.395.042.778 0 1.174a.41.41 0 0 1-.328.37c-.29.056-.544.056-.834 0a.41.41 0 0 1-.328-.37a5.5 5.5 0 0 1 0-1.174");
}

.lelj2r8dg {
  stop-color: var(--svg-color--9ae453, #9AE453);
}

.lg98p_5je {
  stop-color: var(--svg-color--70424e, #70424E);
  stop-opacity: 0;
}

.lgi0lwbjz {
  stop-color: var(--svg-color--775184, #775184);
  stop-opacity: 0;
}

.lh9rvyx3m {
  stroke: var(--svg-color--433739, #433739);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M13.293 11.869c.27-.194.944-.536 1.741-.402");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lk_cbyb-c {
  stop-color: var(--svg-color--784b52, #784B52);
}

.ln8xouyxx {
  stop-color: var(--svg-color--866163, #866163);
  stop-opacity: 0;
}

.lsjj5yb-k {
  stop-color: var(--svg-color--6a4544, #6A4544);
}

.lu7irnbsv {
  fill: var(--svg-color--7e595a, #7E595A);
  d: path("M24.458 17.959a.68.68 0 0 1 .568-.843l.023-.003a.68.68 0 0 1 .756.54l.622 3.039c.071.355-.246.42-.606.458c-.303.032-.553-.005-.629-.3z");
}

.lxo7c2i6k {
  stop-color: var(--svg-color--462f5a, #462F5A);
  stop-opacity: 0;
}

.m_eaw6bxg {
  stop-color: var(--svg-color--57353c, #57353C);
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

.maotw61mt {
  stroke: var(--svg-color--433739, #433739);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M20.587 11.82c-.27-.194-.944-.535-1.741-.4");
}

.mb4bnzbbk {
  stop-color: var(--svg-color--7c4c46, #7C4C46);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mcp_a12ev {
  stop-color: var(--svg-color--997971, #997971);
  stop-opacity: 0;
}

.mg5fqfjeo {
  d: path("M16.841 17.376a3.16 3.16 0 0 1-1.457-.345c-.144-.073-.3.089-.208.22c.352.534.966.89 1.665.89s1.313-.356 1.666-.89c.09-.136-.064-.293-.209-.22a3.14 3.14 0 0 1-1.457.345");
}

.mmq2utbuk {
  stop-color: var(--svg-color--cf8b51, #CF8B51);
}

.mpwbs5b3u {
  stop-color: var(--svg-color--ff894e, #FF894E);
}

.mzj8iibqz {
  stop-color: var(--svg-color--402c32, #402C32);
  stop-opacity: 0;
}

.n297mkbnr {
  stop-color: var(--svg-color--d6d3d7, #D6D3D7);
  stop-opacity: 0;
}

.n9ebefe8q {
  stop-color: var(--svg-color--4f2c2a, #4F2C2A);
  stop-opacity: 0;
}

.nal-rljch {
  stop-color: var(--svg-color--7d5449, #7D5449);
}

.ng1cexbhj {
  stop-color: var(--svg-color--b6424c, #B6424C);
}

.ni991bcqt {
  fill: var(--svg-color--fff, #fff);
  d: path("M14.326 12.578a1.47 1.47 0 0 0-1.425 1.113a.288.288 0 0 0 .281.359h2.348a.242.242 0 0 0 .238-.286a1.474 1.474 0 0 0-1.442-1.186");
}

.nk_trfbso {
  stop-color: var(--svg-color--5b3336, #5B3336);
}

.nl0wbpawx {
  stop-color: var(--svg-color--968f9c, #968F9C);
}

.nuqjb3b3u {
  stroke: var(--svg-color--997971, #997971);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-35px, 0.35px);
  d: path("m24.358 18.55l.436 2.127");
}

.o_30au2yc {
  stop-color: var(--svg-color--decfd8, #DECFD8);
}

.o415o878f {
  stop-color: var(--svg-color--ef4c8b, #EF4C8B);
}

.o847wybrn {
  stop-color: var(--svg-color--875455, #875455);
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

.ovvtmacpn {
  stop-color: var(--svg-color--4f4d4d, #4F4D4D);
  stop-opacity: 0;
}

.p22s-zbfq {
  stop-color: var(--svg-color--77455b, #77455B);
  stop-opacity: 0;
}

.p54kb3bjj {
  stop-color: var(--svg-color--98786d, #98786D);
}

.p6kjyabmr {
  d: path("M11.492 13.069a1.005 1.005 0 0 0 .088 1.977a82 82 0 0 1-.088-1.977");
}

.pb6efmson {
  stop-color: var(--svg-color--d72c5e, #D72C5E);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pkjt6qfem {
  stop-color: var(--svg-color--9c7b71, #9C7B71);
}

.ppr920emc {
  stop-color: var(--svg-color--61a150, #61A150);
  stop-opacity: 0;
}

.pt8frltpn {
  stop-color: var(--svg-color--7060a5, #7060A5);
}

.pxeuj6buu {
  stop-color: var(--svg-color--70424e, #70424E);
}

.qjbq_nb5a {
  stop-color: var(--svg-color--9e7c73, #9E7C73);
}

.qr8h38bcf {
  stop-color: var(--svg-color--826052, #826052);
}

.qsncw6btn {
  stop-color: var(--svg-color--7d465b, #7D465B);
}

.qsu4qbckq {
  stop-color: var(--svg-color--dbcdd4, #DBCDD4);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qw3t0fbxr {
  stop-color: var(--svg-color--815758, #815758);
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

.r_g462bwu {
  fill: var(--svg-color--7e595a, #7E595A);
  d: path("M22.414 19.88a.68.68 0 1 1 1.33-.293l.36 1.793a.645.645 0 0 1-1.26.28z");
}

.rl77jgbwx {
  d: path("M14.544 12.864a.94.94 0 0 0-.905 1.186h1.814a1 1 0 0 0 .034-.247a.945.945 0 0 0-.943-.94");
}

.rm9y2hb6m {
  stop-color: var(--svg-color--98786d, #98786D);
  stop-opacity: 0;
}

.rq7piitrs {
  stop-color: var(--svg-color--77455b, #77455B);
}

.rt394ibmb {
  stroke: var(--svg-color--997971, #997971);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-35px, 0.35px);
  d: path("m23.333 19.615l.414 1.64");
}

.s0umluqbl {
  stop-color: var(--svg-color--7160a4, #7160A4);
  stop-opacity: 0;
}

.s5pji6bqr {
  stop-color: var(--svg-color--443237, #443237);
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

.sf65_-b_u {
  stop-color: var(--svg-color--4f2c2a, #4F2C2A);
}

.sgymfgtlq {
  d: path("M21.955 15.644c.352-.011.683-.131.951-.325v.98c0 .94-.56 1.776-1.41 2.123c.179-.381.302-.797.364-1.24z");
}

.sicchzd0u {
  stop-color: var(--svg-color--a17c72, #A17C72);
  stop-opacity: 0;
}

.sim-rnb6d {
  stop-color: var(--svg-color--815f58, #815F58);
  stop-opacity: 0;
}

.sirm6td-l {
  stop-color: var(--svg-color--784759, #784759);
}

.smgiue0gi {
  stop-color: var(--svg-color--c93857, #C93857);
}

.srn41o2oz {
  stop-color: var(--svg-color--836158, #836158);
  stop-opacity: 0;
}

.swka_j87x {
  d: path("M6.25 29.826c0-5.635 4.568-10.203 10.203-10.203h.64c5.636 0 10.204 4.568 10.204 10.203z");
}

.swmlbjbuq {
  stop-color: var(--svg-color--836153, #836153);
}

.sxoyafbbn {
  stop-color: var(--svg-color--805d4c, #805D4C);
  stop-opacity: 0;
}

.t_m5csgaz {
  stop-color: var(--svg-color--866163, #866163);
}

.t-5nldk3g {
  cx: 16.761px;
  cy: 28.296px;
  r: 0.739px;
}

.tg07-ljnl {
  stop-color: var(--svg-color--5e5764, #5E5764);
}

.tmfmwacik {
  d: path("M19.975 13.68a.9.9 0 0 0-.244-.488l-.273.3l.123.24z");
}

.tn_97qkdc {
  stop-color: var(--svg-color--f2c341, #F2C341);
  stop-opacity: 0;
}

.tri7bg95c {
  stop-color: var(--svg-color--805d4c, #805D4C);
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

.u5bjt8cdp {
  d: path("M6.803 17.694a.782.782 0 0 1 1.249-.941l.93 1.214c.337.438.519.975.519 1.527l-1.5-.18z");
}

.u5lbkrb_x {
  stop-color: var(--svg-color--977872, #977872);
  stop-opacity: 0;
}

.u6lph46no {
  stop-color: var(--svg-color--f0dff0, #F0DFF0);
}

.u9e5rgnkp {
  stop-color: var(--svg-color--6f4044, #6F4044);
}

.ujrq6ixuu {
  stop-color: var(--svg-color--beb4c6, #BEB4C6);
}

.uqr6xg6is {
  stop-color: var(--svg-color--7f5552, #7F5552);
}

.usrti_bee {
  d: path("M11.535 12.37a1.71 1.71 0 0 0-1.464 1.68c0 .904.708 1.642 1.6 1.69a82 82 0 0 1-.136-3.37");
}

.v0501vbqa {
  stop-color: var(--svg-color--c0b5cd, #C0B5CD);
}

.v2j_a512e {
  d: path("M19.07 13.062c.067.09-.073.199-.232.318c-.16.118-.277.202-.344.112c-.067-.089.008-.258.167-.377s.342-.142.409-.053");
}

.v7xhdx32s {
  stop-color: var(--svg-color--7d465b, #7D465B);
  stop-opacity: 0;
}

.vcrfrnsjt {
  stop-color: var(--svg-color--6f4044, #6F4044);
  stop-opacity: 0;
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

.vv0hkr84h {
  stroke: var(--svg-color--997971, #997971);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-35px, 0.35px);
  d: path("m26.849 18.13l.32 2.165");
}

.vvfum-_fa {
  stop-color: var(--svg-color--392f42, #392F42);
}

.vx5g9qbgu {
  stop-color: var(--svg-color--815f58, #815F58);
}

.w_o-5kbak {
  stop-color: var(--svg-color--7c4c46, #7C4C46);
}

.w63qn2bkh {
  stop-color: var(--svg-color--605966, #605966);
}

.wdtd_wboj {
  fill: var(--svg-color--2e201f, #2E201F);
  d: path("M20.768 11.69c-.185-.161-.399-.331-.724-.433c-.32-.101-.72-.128-1.275-.06a.292.292 0 1 0 .071.579c.506-.062.816-.03 1.03.037c.208.066.349.172.514.316a.292.292 0 0 0 .384-.44");
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

.wpa_x2uhd {
  stop-color: var(--svg-color--855e5a, #855E5A);
  stop-opacity: 0;
}

.wshx69b-y {
  stop-color: var(--svg-color--896bb4, #896BB4);
}

.wyxslbc9u {
  fill: var(--svg-color--6f3f46, #6F3F46);
  d: path("m16.419 13.784l-.622 1.933c-.106.398.149.796.51.796h.77c.36 0 .615-.404.51-.796l-.521-1.933c-.111-.429-.53-.429-.647 0");
}

.x1l7xqbyw {
  stop-color: var(--svg-color--de5534, #DE5534);
  stop-opacity: 0;
}

.x2-vgab7k {
  fill: var(--svg-color--fff, #fff);
  d: path("M19.356 12.578a1.47 1.47 0 0 1 1.425 1.114a.288.288 0 0 1-.281.358h-2.347a.242.242 0 0 1-.24-.286a1.47 1.47 0 0 1 1.443-1.186");
}

.x7nw9pbfq {
  d: path("M19.139 12.864a.94.94 0 0 1 .904 1.186H18.23a.942.942 0 0 1 .909-1.186");
}

.x9ttejxmc {
  stop-color: var(--svg-color--825d56, #825D56);
}

.xkn2wzmus {
  stop-color: var(--svg-color--7e595a, #7E595A);
}

.xntzq-4ho {
  stop-color: var(--svg-color--8566b5, #8566B5);
}

.xron-kbnx {
  stop-color: var(--svg-color--71404f, #71404F);
  stop-opacity: 0;
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

.y4etjzfdh {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M15.419 16.964c.41.214.9.337 1.422.337a3.1 3.1 0 0 0 1.423-.337a.24.24 0 0 1 .28.046c.067.07.092.181.025.282m-3.15-.328l3.088.287m-3.089-.287a.24.24 0 0 0-.28.049a.22.22 0 0 0-.024.28m.304-.329l-.242.287m3.393.041l-.062-.041m.062.041l-.062-.041m.062.041a2.07 2.07 0 0 1-1.728.924a2.07 2.07 0 0 1-1.728-.923m3.394-.042c-.353.534-.967.89-1.666.89a1.99 1.99 0 0 1-1.665-.89m-.062.042l.062-.042m-.062.042l-.001-.001l.063-.041");
}

.y4umwkb_f {
  stop-color: var(--svg-color--865c56, #865C56);
  stop-opacity: 0;
}

.y7x-29baz {
  stop-color: var(--svg-color--794057, #794057);
  stop-opacity: 0;
}

.y9wvnhcxo {
  d: path("M11.766 17.238a4.12 4.12 0 0 0 4.087 3.582h1.985a4.12 4.12 0 0 0 4.087-3.582c.124-1.982.249-3.955.34-5.935a1.525 1.525 0 0 0-1.45-1.507h-1.472a2.55 2.55 0 0 1-2.327-1.518a.7.7 0 0 0-.647-.44H15.03c-1.941 0-3.515 1.591-3.515 3.555c0 1.957.122 3.883.25 5.845");
}

.ykzqhbcyt {
  stop-color: var(--svg-color--997067, #997067);
}

.ym-b_m9fy {
  stop-color: var(--svg-color--d1bed4, #D1BED4);
  stop-opacity: 0;
}

.z-0dlhbai {
  stop-color: var(--svg-color--875455, #875455);
  stop-opacity: 0;
}

.zdcorrl9x {
  cx: 26.234px;
  cy: 14.83px;
  r: 1.684px;
}

.zgkl_ebsg {
  cx: 14.261px;
  cy: 13.265px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.41px;
  ry: 0.207px;
}

.zqff1532o {
  stop-color: var(--svg-color--201524, #201524);
}

</style>
