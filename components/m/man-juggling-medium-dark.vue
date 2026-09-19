<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#ieCjqAc)"><path fill="url(#iPYYWhe)" class="swka_j87x"/><path fill="url(#iT07jwd)" class="swka_j87x"/><path fill="url(#il5eVUq)" class="swka_j87x"/><path fill="url(#iY3yYtd)" class="swka_j87x"/><path fill="url(#iv8FoOX)" class="swka_j87x"/></g><circle fill="url(#iBZ0RUd)" class="hpfqe6rjh"/><circle fill="url(#itKlKTd)" class="hpfqe6rjh"/><circle fill="url(#ihlr5IT)" class="duyhuibwk"/><circle fill="url(#iGUmgWd)" class="duyhuibwk"/><circle fill="url(#iXhqZHd)" class="iwbygtbvw"/><circle fill="url(#iOHvRJe)" class="iwbygtbvw"/><circle fill="url(#issuNue)" class="zdcorrl9x"/><circle fill="url(#iMaLBhb)" class="zdcorrl9x"/><circle fill="url(#iAhrvZc)" class="zdcorrl9x"/><g filter="url(#iv9lMRj)"><circle fill="url(#iMk8UMb)" class="t-5nldk3g"/></g><g filter="url(#i0VYF9c)"><circle fill="url(#iR23Gge)" class="don2wdpjw"/></g><path fill="url(#i5YvaPc)" class="j70rp9pis"/><path fill="url(#iK84mBb)" class="j70rp9pis"/><path fill="url(#iWCiqKd)" class="j70rp9pis"/><path fill="url(#ieol8Me)" class="qy4rrcb8b"/><path fill="url(#iDbbcbc)" class="qy4rrcb8b"/><path fill="url(#iOe2zrd)" class="qy4rrcb8b"/><path fill="url(#iV71Rbc)" class="qy4rrcb8b"/><g filter="url(#ifZnVtb)"><path fill="url(#iObplQb)" class="ggm3_setj"/><path fill="url(#iQpTAtb)" class="ggm3_setj"/></g><path fill="url(#ipodSkc)" class="f21vmbcik"/><path fill="url(#iXPTZOc)" class="f21vmbcik"/><path fill="url(#itP1zjc)" class="wp2p6dbcv"/><path fill="url(#i33ZCUz)" class="wp2p6dbcv"/><g filter="url(#iOxdC1N)"><path clip-rule="evenodd" class="byn6wubog"/></g><g filter="url(#iUdr0Kd)"><path fill="url(#iSAsI1d)" class="ctsppjbax"/><path fill="url(#iwtPTOo)" class="ctsppjbax"/><path fill="url(#isAdhHe)" class="ctsppjbax"/></g><g filter="url(#iJ07zAb)"><path fill="url(#ivLP6Gc)" class="ht6lpfbpp"/><path fill="url(#iXetYud)" class="ht6lpfbpp"/></g><g filter="url(#i5vOXRd)"><path fill="url(#i8tJXGc)" class="ld_83jb7a"/><path fill="url(#iw9bnJb)" class="ld_83jb7a"/></g><g filter="url(#iPOf2Fb)"><path class="d8vr2qabd"/></g><g filter="url(#iRStZ0o)"><path class="fe5_67d9h"/></g><g filter="url(#iHqUdwo)"><path class="lu7irnbsv"/></g><g filter="url(#iCyKjzc)"><path class="a2erpabfq"/></g><g filter="url(#iWTGbtc)"><path class="r_g462bwu"/></g><path fill="url(#iy5yhkB)" class="hw860-bkw"/><path fill="url(#iLYPeid)" class="hw860-bkw"/><path fill="url(#igEWuTd)" class="hw860-bkw"/><g filter="url(#iJajync)"><path fill="url(#iUsDf3b)" class="u5bjt8cdp"/></g><path fill="url(#iya7JRb)" clip-rule="evenodd" class="wfgw5ub6b"/><path fill="url(#ixz6Bfl)" clip-rule="evenodd" class="wfgw5ub6b"/><path fill="url(#iomTwyb)" clip-rule="evenodd" class="d5_x4xk7i"/><path fill="url(#il5DzUH)" clip-rule="evenodd" class="d5_x4xk7i"/><path fill="url(#iXmA6MA)" clip-rule="evenodd" class="ctupw6b3d"/><path fill="url(#ifjLIpe)" clip-rule="evenodd" class="ctupw6b3d"/><path fill="url(#iy5Lb5d)" clip-rule="evenodd" class="vdngsab5t"/><path fill="url(#iMyswRb)" clip-rule="evenodd" class="vdngsab5t"/><path fill="url(#izQ0wGc)" class="twba206ho"/><path fill="url(#iBECMpb)" class="twba206ho"/><path fill="url(#i0pxh3d)" class="lucypabyc"/><g filter="url(#iEBzT2c)"><path class="rt394ibmb"/></g><g filter="url(#ikTYhnb)"><path class="znup_d9es"/></g><g filter="url(#icv5W7b)"><path class="iinlnft3b"/></g><g filter="url(#iPsFncb)"><path class="vv0hkr84h"/></g><g filter="url(#iPasnxe)"><path stroke="url(#imI15oe)" class="bdk4dmb5b"/></g><g filter="url(#iLuDrWd)"><path stroke="url(#iamKure)" class="gwm_2mjil"/></g><g filter="url(#ibxCS5b)"><path stroke="url(#iGhB53d)" class="y2ly1lryk"/></g><g filter="url(#iQWP35d)"><path stroke="url(#ixXGBre)" class="am6k_ubte"/></g><g filter="url(#ihtosLb)"><path stroke="url(#iVKoQ5f)" class="c549xi8ae"/></g><g filter="url(#iVGW3Ud)"><circle fill="url(#idUWQBe)" class="jhbcwjouc"/></g><g filter="url(#iAaNH9d)"><circle fill="url(#iqD3oIz)" class="pshp3gbyy"/></g><g filter="url(#i9y6SXd)"><circle fill="url(#iOW2Csd)" class="bd4yam5lz"/><circle fill="url(#iVJhwpb)" class="bd4yam5lz"/></g><g filter="url(#icTBQTc)"><circle class="i6deo3edg"/><circle fill="url(#ievZBXb)" class="q63ojm9za"/><circle fill="url(#iBwpeXd)" class="q63ojm9za"/></g><g filter="url(#iTHhOsd)"><path fill="url(#ieSd4zs)" class="kb4brky7h"/><path fill="url(#iRWaFld)" class="kb4brky7h"/><path fill="url(#ifTvvud)" class="kb4brky7h"/></g><path fill="url(#iKQU1Db)" class="p2_a-vgnp"/><path fill="url(#iI4rfUd)" class="p2_a-vgnp"/><path fill="url(#iZerEHy)" class="p2_a-vgnp"/><path fill="url(#iAn8ERJ)" class="p2_a-vgnp"/><path fill="url(#iqgLKfd)" class="p2_a-vgnp"/><path fill="url(#ia7TxKE)" class="p2_a-vgnp"/><g filter="url(#iVyvsib)"><path class="y-darzb-m"/><path fill="url(#ioDqMMb)" class="zocay_btp"/><path fill="url(#iB8EQQb)" class="zocay_btp"/><path fill="url(#iZfYnUd)" class="zocay_btp"/><path fill="url(#iTB1Veb)" class="zocay_btp"/></g><g filter="url(#iqFn0Rc)"><path class="uwilonrnh"/></g><g filter="url(#iPVMeac)"><path class="sr2acebhk"/><path fill="url(#ir0ybGe)" class="k9derdbxj"/><path fill="url(#iPyCbkc)" class="k9derdbxj"/><path fill="url(#iJqnWqc)" class="k9derdbxj"/><path fill="url(#idzmrLc)" class="k9derdbxj"/></g><path stroke="url(#iba3Gae)" class="jeg__ccjl"/><g filter="url(#iEx92ve)"><path class="m8y3hpmcv"/><path fill="url(#iSu38FC)" class="brk2w9bsn"/></g><g filter="url(#iJpvtVc)"><path class="ugcc8sbhb"/><path fill="url(#iYLoY1b)" class="h2l0yub-m"/></g><path class="qu0fk82sg"/><path fill="url(#iv4WXid)" class="zwyp76bpi"/><path class="jy5_zcb8f"/><g filter="url(#ii9sO5d)"><path class="axv337-vt"/><path fill="url(#iJAy6CA)" class="kk2f_dbcn"/></g><g filter="url(#i0Aunge)"><path fill="url(#ixgKIPd)" class="y3zk80bfr"/></g><path class="yk1hdeydu"/><path fill="url(#igAQgHe)" class="py_-fb9_p"/><path class="mhenm65eu"/><g filter="url(#imXh74d)"><path fill="url(#iEOREJb)" class="pfrjt3bzl"/></g><g filter="url(#iuhp9pe)"><ellipse transform="rotate(-27.914 14.054 13.632)" class="eau-icrly"/><ellipse fill="url(#ilssdgc)" transform="rotate(-27.914 14.054 13.632)" class="l04ioccmf"/></g><g filter="url(#iwrLgjd)"><path stroke="url(#irt3zgd)" class="hcb81nbzm"/></g><g filter="url(#iqr8iMd)"><path stroke="url(#iuQvUad)" class="qoz4txb4k"/></g><g filter="url(#i8xTAcc)"><path stroke="url(#ihukOYd)" class="c-7n2ksmg"/></g><path fill="url(#iMwhdrV)" class="qzd219blo"/><path fill="url(#i3dSYhb)" class="qzd219blo"/><path fill="url(#inl9J2c)" class="qzd219blo"/><path fill="url(#iCE2gke)" class="wozepxbaa"/><path fill="url(#izP9Z9c)" class="wozepxbaa"/><rect fill="url(#iK2GSbd)" class="okwd93kys"/><rect fill="url(#iy7tjOa)" class="okwd93kys"/><rect fill="url(#iYE2hsb)" class="okwd93kys"/><defs><radialGradient id="iPYYWhe" cx="0" cy="0" r="1" gradientTransform="rotate(135.22 8.643 15.887)scale(12.9545 12.5552)" gradientUnits="userSpaceOnUse"><stop offset=".195" class="m-1-e5bla"/><stop offset=".794" class="b057dp4eh"/></radialGradient><radialGradient id="iT07jwd" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.09375 -3.28125 0 20.219 20.139)" gradientUnits="userSpaceOnUse"><stop class="m9gf32bwp"/><stop offset="1" class="n297mkbnr"/></radialGradient><radialGradient id="il5eVUq" cx="0" cy="0" r="1" gradientTransform="matrix(-1.75 0 0 -11.7187 21 25.92)" gradientUnits="userSpaceOnUse"><stop offset=".214" class="demkpcl0k"/><stop offset="1" class="ym-b_m9fy"/></radialGradient><radialGradient id="iY3yYtd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.15625 0 0 -5.75902 11.656 25.326)" gradientUnits="userSpaceOnUse"><stop class="ujrq6ixuu"/><stop offset="1" class="h4mko5b9o"/></radialGradient><radialGradient id="iv8FoOX" cx="0" cy="0" r="1" gradientTransform="matrix(2.12502 5.34374 -11.023 4.38346 13.099 18.733)" gradientUnits="userSpaceOnUse"><stop class="nl0wbpawx"/><stop offset="1" class="jm40s5baz"/></radialGradient><radialGradient id="iBZ0RUd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.34375 2.4375 -2.36069 -1.3014 7.187 11.826)" gradientUnits="userSpaceOnUse"><stop offset=".077" class="l-r9gxb9g"/><stop offset="1" class="hcmh5c50b"/></radialGradient><radialGradient id="itKlKTd" cx="0" cy="0" r="1" gradientTransform="rotate(115.145 -.151 8.247)scale(3.38309 2.95533)" gradientUnits="userSpaceOnUse"><stop offset=".452" class="y-1rsmdul"/><stop offset=".826" class="af8mzdbwl"/></radialGradient><radialGradient id="ihlr5IT" cx="0" cy="0" r="1" gradientTransform="matrix(-1.34375 2.4375 -2.36069 -1.3014 10.101 2.846)" gradientUnits="userSpaceOnUse"><stop offset=".077" class="mpwbs5b3u"/><stop offset="1" class="fzq016boz"/></radialGradient><radialGradient id="iGUmgWd" cx="0" cy="0" r="1" gradientTransform="rotate(115.145 4.158 4.683)scale(3.38309 2.95533)" gradientUnits="userSpaceOnUse"><stop offset=".452" class="x1l7xqbyw"/><stop offset=".826" class="ng1cexbhj"/></radialGradient><radialGradient id="iXhqZHd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.34375 2.4375 -2.36069 -1.3014 26.066 3.861)" gradientUnits="userSpaceOnUse"><stop offset=".077" class="lelj2r8dg"/><stop offset="1" class="fde_fwzpt"/></radialGradient><radialGradient id="iOHvRJe" cx="0" cy="0" r="1" gradientTransform="rotate(105.03 11.36 11.751)scale(3.49455 3.40391)" gradientUnits="userSpaceOnUse"><stop offset=".375" class="ppr920emc"/><stop offset=".826" class="y_auwli2s"/></radialGradient><radialGradient id="issuNue" cx="0" cy="0" r="1" gradientTransform="matrix(-1.34375 2.4375 -2.36069 -1.3014 27.09 13.818)" gradientUnits="userSpaceOnUse"><stop offset=".077" class="y05rrkbkk"/><stop offset="1" class="a5zzorbzd"/></radialGradient><radialGradient id="iMaLBhb" cx="0" cy="0" r="1" gradientTransform="matrix(1 1.07812 -1.5877 1.47265 24.969 13.357)" gradientUnits="userSpaceOnUse"><stop class="i8j0jyb4u"/><stop offset="1" class="d7caiobkz"/></radialGradient><radialGradient id="iAhrvZc" cx="0" cy="0" r="1" gradientTransform="rotate(109.11 8.51 16.52)scale(3.46022 3.37046)" gradientUnits="userSpaceOnUse"><stop offset=".347" class="tn_97qkdc"/><stop offset=".829" class="mmq2utbuk"/></radialGradient><radialGradient id="iMk8UMb" cx="0" cy="0" r="1" gradientTransform="matrix(-.7578 1.14063 -.96756 -.64282 17.25 27.855)" gradientUnits="userSpaceOnUse"><stop offset=".212" class="u6lph46no"/><stop offset="1" class="bq5dgsbba"/></radialGradient><radialGradient id="iR23Gge" cx="0" cy="0" r="1" gradientTransform="matrix(-.7578 1.14063 -.96756 -.64282 17.25 25.842)" gradientUnits="userSpaceOnUse"><stop offset=".212" class="u6lph46no"/><stop offset="1" class="bq5dgsbba"/></radialGradient><radialGradient id="i5YvaPc" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.03125 -2.40212 0 22.222 20.983)" gradientUnits="userSpaceOnUse"><stop class="koq0r9bvu"/><stop offset="1" class="dpmuo-biy"/></radialGradient><radialGradient id="ieol8Me" cx="0" cy="0" r="1" gradientTransform="scale(1.38818 6.1875)rotate(90 2.761 6.5)" gradientUnits="userSpaceOnUse"><stop class="xntzq-4ho"/><stop offset="1" class="pt8frltpn"/></radialGradient><radialGradient id="iDbbcbc" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.25 -.60938 0 13.062 24.108)" gradientUnits="userSpaceOnUse"><stop class="wshx69b-y"/><stop offset="1" class="aqzyd8bsb"/></radialGradient><radialGradient id="iOe2zrd" cx="0" cy="0" r="1" gradientTransform="matrix(2.9375 -7.98881 7.06186 2.59666 10.312 28.264)" gradientUnits="userSpaceOnUse"><stop offset=".724" class="lgi0lwbjz"/><stop offset="1" class="tvoyviyhj"/></radialGradient><radialGradient id="iV71Rbc" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.42188 -.18506 0 12.857 21.717)" gradientUnits="userSpaceOnUse"><stop class="m5avsc_ef"/><stop offset="1" class="ci3gi1b_k"/></radialGradient><radialGradient id="iObplQb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.90624 2.42972 -4.28692 -6.89204 19.266 20.795)" gradientUnits="userSpaceOnUse"><stop class="ku63lg_wt"/><stop offset="1" class="i1-orb7ke"/></radialGradient><radialGradient id="iQpTAtb" cx="0" cy="0" r="1" gradientTransform="matrix(-.46875 -.125 .54686 -2.05079 19.188 22.482)" gradientUnits="userSpaceOnUse"><stop offset=".108" class="qsu4qbckq"/><stop offset="1" class="gr0wzobbs"/></radialGradient><radialGradient id="iSAsI1d" cx="0" cy="0" r="1" gradientTransform="matrix(1.73878 1.3451 -1.47727 1.90964 13.775 23.358)" gradientUnits="userSpaceOnUse"><stop class="ab6i82btp"/><stop offset="1" class="pb6efmson"/></radialGradient><radialGradient id="iwtPTOo" cx="0" cy="0" r="1" gradientTransform="matrix(-1.68958 -.4774 .79459 -2.81214 15.416 23.836)" gradientUnits="userSpaceOnUse"><stop offset=".69" class="sawf8hb2n"/><stop offset="1" class="o415o878f"/></radialGradient><radialGradient id="isAdhHe" cx="0" cy="0" r="1" gradientTransform="matrix(-.5 1.58457 -.75053 -.23683 16.11 23.836)" gradientUnits="userSpaceOnUse"><stop class="btor07b8q"/><stop offset="1" class="jjf293xlz"/></radialGradient><radialGradient id="ivLP6Gc" cx="0" cy="0" r="1" gradientTransform="rotate(142.275 5.895 15.056)scale(2.19833 2.41434)" gradientUnits="userSpaceOnUse"><stop class="auvn9fbbk"/><stop offset="1" class="h2li0wblg"/></radialGradient><radialGradient id="iXetYud" cx="0" cy="0" r="1" gradientTransform="matrix(1.68958 -.4774 .79459 2.81214 18.13 23.836)" gradientUnits="userSpaceOnUse"><stop offset=".69" class="sawf8hb2n"/><stop offset="1" class="o415o878f"/></radialGradient><radialGradient id="iw9bnJb" cx="0" cy="0" r="1" gradientTransform="matrix(-.39136 0 0 -2.59279 17.54 23.592)" gradientUnits="userSpaceOnUse"><stop class="scbqttb8d"/><stop offset="1" class="u1gl_1zha"/></radialGradient><radialGradient id="iy5yhkB" cx="0" cy="0" r="1" gradientTransform="matrix(-4.375 1.44046 -1.3893 -4.21963 28.098 22.456)" gradientUnits="userSpaceOnUse"><stop offset=".241" class="ykzqhbcyt"/><stop offset=".899" class="j20i63bee"/></radialGradient><radialGradient id="iLYPeid" cx="0" cy="0" r="1" gradientTransform="rotate(163.091 11.838 12.97)scale(3.90165 13.4872)" gradientUnits="userSpaceOnUse"><stop offset=".699" class="b9-qm444s"/><stop offset="1" class="lk_cbyb-c"/></radialGradient><radialGradient id="igEWuTd" cx="0" cy="0" r="1" gradientTransform="rotate(77.276 -.052 26.27)scale(.74486 4.08592)" gradientUnits="userSpaceOnUse"><stop class="xkn2wzmus"/><stop offset="1" class="ammr1_bix"/></radialGradient><radialGradient id="iUsDf3b" cx="0" cy="0" r="1" gradientTransform="rotate(139.97 1.2 10.48)scale(1.53045 3.638)" gradientUnits="userSpaceOnUse"><stop offset=".129" class="emrugab1j"/><stop offset="1" class="lc7su-9ui"/></radialGradient><radialGradient id="iya7JRb" cx="0" cy="0" r="1" gradientTransform="matrix(-.79386 1.27188 -2.4349 -1.51978 6.442 17.553)" gradientUnits="userSpaceOnUse"><stop class="swmlbjbuq"/><stop offset="1" class="ksmxe9b1k"/></radialGradient><radialGradient id="ixz6Bfl" cx="0" cy="0" r="1" gradientTransform="matrix(-.73037 2.48832 -3.82658 -1.12318 6.977 17.288)" gradientUnits="userSpaceOnUse"><stop offset=".585" class="p22s-zbfq"/><stop offset=".954" class="rq7piitrs"/></radialGradient><radialGradient id="iomTwyb" cx="0" cy="0" r="1" gradientTransform="rotate(116.602 -3.017 10.55)scale(1.58621 2.70684)" gradientUnits="userSpaceOnUse"><stop class="swmlbjbuq"/><stop offset="1" class="ksmxe9b1k"/></radialGradient><radialGradient id="il5DzUH" cx="0" cy="0" r="1" gradientTransform="matrix(-.65347 2.77477 -3.52334 -.82977 5.545 17.677)" gradientUnits="userSpaceOnUse"><stop offset=".585" class="p22s-zbfq"/><stop offset=".954" class="rq7piitrs"/></radialGradient><radialGradient id="iXmA6MA" cx="0" cy="0" r="1" gradientTransform="matrix(-.68468 1.22288 -2.2217 -1.2439 4.939 18.947)" gradientUnits="userSpaceOnUse"><stop class="swmlbjbuq"/><stop offset="1" class="ksmxe9b1k"/></radialGradient><radialGradient id="ifjLIpe" cx="0" cy="0" r="1" gradientTransform="rotate(104.751 -4.503 11.427)scale(2.474 3.46652)" gradientUnits="userSpaceOnUse"><stop offset=".585" class="p22s-zbfq"/><stop offset=".954" class="rq7piitrs"/></radialGradient><radialGradient id="iy5Lb5d" cx="0" cy="0" r="1" gradientTransform="rotate(122.692 -2.834 11.406)scale(1.24393 2.40994)" gradientUnits="userSpaceOnUse"><stop class="swmlbjbuq"/><stop offset="1" class="ksmxe9b1k"/></radialGradient><radialGradient id="iMyswRb" cx="0" cy="0" r="1" gradientTransform="matrix(-.61813 2.04813 -3.22394 -.973 5.687 19.733)" gradientUnits="userSpaceOnUse"><stop offset=".585" class="p22s-zbfq"/><stop offset=".954" class="rq7piitrs"/></radialGradient><radialGradient id="izQ0wGc" cx="0" cy="0" r="1" gradientTransform="rotate(-162.011 6.48 10.137)scale(3.69324 5.10277)" gradientUnits="userSpaceOnUse"><stop class="qjbq_nb5a"/><stop offset=".482" class="qr8h38bcf"/></radialGradient><radialGradient id="iBECMpb" cx="0" cy="0" r="1" gradientTransform="matrix(.07812 -.82813 3.88844 .36683 6.156 21.78)" gradientUnits="userSpaceOnUse"><stop class="sirm6td-l"/><stop offset="1" class="faah7i3zw"/></radialGradient><radialGradient id="i0pxh3d" cx="0" cy="0" r="1" gradientTransform="matrix(1.65625 2.09375 -2.38774 1.88881 15.814 20.443)" gradientUnits="userSpaceOnUse"><stop offset=".229" class="bo6_cwbgw"/><stop offset="1" class="uqr6xg6is"/></radialGradient><radialGradient id="idUWQBe" cx="0" cy="0" r="1" gradientTransform="matrix(1.84203 0 0 3.22357 9.895 14.449)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="gsgzrwbpm"/><stop offset="1" class="nhrtbwabt"/></radialGradient><radialGradient id="iVJhwpb" cx="0" cy="0" r="1" gradientTransform="matrix(.86777 -.63187 .7212 .99044 22.024 14.17)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="ywu0pr7ii"/><stop offset="1" class="pw1h71b2a"/></radialGradient><radialGradient id="ievZBXb" cx="0" cy="0" r="1" gradientTransform="matrix(.86205 -1.58556 .92803 .50456 21.59 15.31)" gradientUnits="userSpaceOnUse"><stop offset=".755" class="evklql54e"/><stop offset=".916" class="ppo67rb9b"/></radialGradient><radialGradient id="iBwpeXd" cx="0" cy="0" r="1" gradientTransform="matrix(.27217 .2694 -.3473 .35086 21.634 14.448)" gradientUnits="userSpaceOnUse"><stop class="o45oetbxg"/><stop offset="1" class="mfyy4ibhn"/></radialGradient><radialGradient id="iRWaFld" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.372 1.68862 0 19.095 13.114)" gradientUnits="userSpaceOnUse"><stop class="q3kvcibxc"/><stop offset="1" class="kz100sbcz"/></radialGradient><radialGradient id="ifTvvud" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.44236 1.79371 0 14.31 13.254)" gradientUnits="userSpaceOnUse"><stop class="z_g0j449a"/><stop offset="1" class="s5xtkwbhw"/></radialGradient><radialGradient id="iZerEHy" cx="0" cy="0" r="1" gradientTransform="matrix(0 9.28595 -12.6052 0 16.315 12.586)" gradientUnits="userSpaceOnUse"><stop offset=".619" class="rko8b-bmk"/><stop offset="1" class="whxihzpaf"/></radialGradient><radialGradient id="iAn8ERJ" cx="0" cy="0" r="1" gradientTransform="matrix(-1.8024 -1.21254 .69016 -1.0259 21.107 20.66)" gradientUnits="userSpaceOnUse"><stop class="m13zyzbuk"/><stop offset="1" class="kzk-_ccou"/></radialGradient><radialGradient id="iqgLKfd" cx="0" cy="0" r="1" gradientTransform="matrix(2.72001 -.57105 .3617 1.72286 12.816 21.74)" gradientUnits="userSpaceOnUse"><stop class="m13zyzbuk"/><stop offset="1" class="kzk-_ccou"/></radialGradient><radialGradient id="ioDqMMb" cx="0" cy="0" r="1" gradientTransform="matrix(.83745 -3.10348 1.49432 .40323 21.193 10.138)" gradientUnits="userSpaceOnUse"><stop offset=".372" class="v4bc9u3un"/><stop offset="1" class="o90gcpqxu"/></radialGradient><radialGradient id="iB8EQQb" cx="0" cy="0" r="1" gradientTransform="matrix(4.01482 .36946 -.19866 2.15874 19.468 8.29)" gradientUnits="userSpaceOnUse"><stop offset=".32" class="tti32obdt"/><stop offset="1" class="cpvxurbrw"/></radialGradient><radialGradient id="iZfYnUd" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.76258 -2.72974 0 16.632 5.42)" gradientUnits="userSpaceOnUse"><stop class="vpyj0s_ar"/><stop offset="1" class="lkn2u3bae"/></radialGradient><radialGradient id="iTB1Veb" cx="0" cy="0" r="1" gradientTransform="rotate(-36.235 24.15 -8.783)scale(4.00028 6.26713)" gradientUnits="userSpaceOnUse"><stop class="zk3m83b4g"/><stop offset="1" class="gey-evbzc"/></radialGradient><radialGradient id="idzmrLc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .20668 -.66401 0 16.975 16.135)" gradientUnits="userSpaceOnUse"><stop class="w-44tpbkk"/><stop offset="1" class="d52rddbnb"/></radialGradient><radialGradient id="iSu38FC" cx="0" cy="0" r="1" gradientTransform="matrix(.10937 -.63323 1.87336 .32356 19.196 12.26)" gradientUnits="userSpaceOnUse"><stop class="ne4llzbvb"/><stop offset="1" class="vgfjqtbdb"/></radialGradient><radialGradient id="iYLoY1b" cx="0" cy="0" r="1" gradientTransform="matrix(.10938 -.63323 1.87347 .3236 13.792 12.26)" gradientUnits="userSpaceOnUse"><stop class="ne4llzbvb"/><stop offset="1" class="vgfjqtbdb"/></radialGradient><radialGradient id="iv4WXid" cx="0" cy="0" r="1" gradientTransform="matrix(0 .85142 -1.35428 0 18.919 13.732)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iJAy6CA" cx="0" cy="0" r="1" gradientTransform="matrix(-.24338 -.31363 .4318 -.33508 18.679 13.82)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="igAQgHe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .85146 -1.35435 0 14.339 13.733)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="ilssdgc" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 13.892 .071)scale(.51857 .62334)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iMwhdrV" cx="0" cy="0" r="1" gradientTransform="matrix(-5.5 4.12501 -3.615 -4.82 20.719 4.576)" gradientUnits="userSpaceOnUse"><stop offset=".179" class="tg07-ljnl"/><stop offset="1" class="c6833cb9x"/></radialGradient><radialGradient id="i3dSYhb" cx="0" cy="0" r="1" gradientTransform="matrix(2.875 .375 -.58342 4.4729 10.781 7.701)" gradientUnits="userSpaceOnUse"><stop class="j8k1fac_p"/><stop offset="1" class="g8uem1b5g"/></radialGradient><radialGradient id="inl9J2c" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.875 8.03906 0 16.773 8.326)" gradientUnits="userSpaceOnUse"><stop offset=".761" class="km6q7kb1a"/><stop offset="1" class="i8skpb2jz"/></radialGradient><radialGradient id="iCE2gke" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.47656 -8.28125 0 18.406 7.912)" gradientUnits="userSpaceOnUse"><stop class="kzuil_5zu"/><stop offset="1" class="ok2r3obil"/></radialGradient><radialGradient id="iK2GSbd" cx="0" cy="0" r="1" gradientTransform="matrix(-7.1875 0 0 -.63281 21.268 9.87)" gradientUnits="userSpaceOnUse"><stop class="w63qn2bkh"/><stop offset="1" class="vvfum-_fa"/></radialGradient><radialGradient id="iy7tjOa" cx="0" cy="0" r="1" gradientTransform="matrix(3.48438 0 0 2.01172 9.003 10.109)" gradientUnits="userSpaceOnUse"><stop class="gfrsedb9v"/><stop offset="1" class="vke6kh8bt"/></radialGradient><filter id="ieCjqAc" width="21.247" height="10.303" x="6.25" y="19.623" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.615686 0 0 0 0 0.607843 0 0 0 0 0.619608 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23851"/></filter><filter id="iv9lMRj" width="2.078" height="2.078" x="15.622" y="27.457" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.792157 0 0 0 0 0.717647 0 0 0 0 0.788235 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_3987_23851"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_3987_23851" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.831373 0 0 0 0 0.745098 0 0 0 0 0.803922 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_3987_23851"/></filter><filter id="i0VYF9c" width="2.078" height="2.078" x="15.622" y="25.444" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.792157 0 0 0 0 0.717647 0 0 0 0 0.788235 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_3987_23851"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_3987_23851" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.831373 0 0 0 0 0.745098 0 0 0 0 0.803922 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_3987_23851"/></filter><filter id="ifZnVtb" width="6.554" height="3.702" x="13.38" y="19.523" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.721569 0 0 0 0 0.682353 0 0 0 0 0.74902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23851"/></filter><filter id="iOxdC1N" width="7.432" height="4.46" x="12.567" y="22.084" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23851" stdDeviation=".5"/></filter><filter id="iUdr0Kd" width="2.672" height="2.865" x="13.611" y="22.403" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.780392 0 0 0 0 0.270588 0 0 0 0 0.396078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23851"/></filter><filter id="iJ07zAb" width="2.672" height="2.865" x="17.264" y="22.403" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.780392 0 0 0 0 0.270588 0 0 0 0 0.396078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23851"/></filter><filter id="i5vOXRd" width="1.554" height="1.999" x="15.986" y="22.812" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.827451 0 0 0 0 0.137255 0 0 0 0 0.317647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23851"/></filter><filter id="iPOf2Fb" width="4.764" height="4.766" x="24.75" y="19.349" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.1"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.462745 0 0 0 0 0.282353 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23851"/></filter><filter id="iRStZ0o" width="2.077" height="3.844" x="25.907" y="17.448" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.431373 0 0 0 0 0.282353 0 0 0 0 0.247059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23851"/></filter><filter id="iHqUdwo" width="2.401" height="4.052" x="24.436" y="17.107" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.431373 0 0 0 0 0.282353 0 0 0 0 0.247059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23851"/></filter><filter id="iCyKjzc" width="2.312" height="4.044" x="23.386" y="17.96" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.431373 0 0 0 0 0.282353 0 0 0 0 0.247059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23851"/></filter><filter id="iWTGbtc" width="2.123" height="3.114" x="22.394" y="19.041" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.431373 0 0 0 0 0.282353 0 0 0 0 0.247059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23851"/></filter><filter id="iJajync" width="3.002" height="3.147" x="6.649" y="16.347" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.431373 0 0 0 0 0.262745 0 0 0 0 0.219608 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23851"/></filter><filter id="iEBzT2c" width="1.264" height="2.491" x="22.908" y="19.19" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23851" stdDeviation=".125"/></filter><filter id="ikTYhnb" width="1.286" height="2.978" x="23.932" y="18.124" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23851" stdDeviation=".125"/></filter><filter id="icv5W7b" width="1.444" height="3.775" x="24.962" y="17.226" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23851" stdDeviation=".125"/></filter><filter id="iPsFncb" width="1.17" height="3.014" x="26.424" y="17.706" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23851" stdDeviation=".125"/></filter><filter id="iPasnxe" width="1.788" height="2.6" x="27.33" y="19.87" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23851" stdDeviation=".125"/></filter><filter id="iLuDrWd" width="2.323" height="1.69" x="3.752" y="19.44" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23851" stdDeviation=".125"/></filter><filter id="ibxCS5b" width="2.342" height="2.022" x="3.291" y="18.151" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23851" stdDeviation=".125"/></filter><filter id="iQWP35d" width="2.131" height="2.124" x="4.556" y="16.714" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23851" stdDeviation=".125"/></filter><filter id="ihtosLb" width="2.569" height="2.444" x="3.345" y="17.042" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23851" stdDeviation=".125"/></filter><filter id="iVGW3Ud" width="3.705" height="3.505" x="9.895" y="12.696" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.517647 0 0 0 0 0.384314 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23851"/></filter><filter id="iAaNH9d" width="3.089" height="3.089" x="10.103" y="12.904" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23851" stdDeviation=".25"/></filter><filter id="i9y6SXd" width="3.755" height="3.755" x="19.881" y="12.446" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.482353 0 0 0 0 0.278431 0 0 0 0 0.372549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23851"/></filter><filter id="icTBQTc" width="3.089" height="3.089" x="20.089" y="12.904" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23851" stdDeviation=".25"/></filter><filter id="iTHhOsd" width="10.889" height="12.775" x="11.218" y="8.544" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.137255 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23851"/></filter><filter id="iVyvsib" width="13.216" height="8.943" x="10.014" y="4.92" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0392157 0 0 0 0 0.00784314 0 0 0 0 0.0196078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23851"/></filter><filter id="iqFn0Rc" width="3.347" height="4.314" x="14.707" y="13.274" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23851" stdDeviation=".375"/></filter><filter id="iPVMeac" width="2.47" height="3.314" x="15.397" y="13.602" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23851" stdDeviation=".125"/></filter><filter id="iEx92ve" width="3.115" height="1.946" x="17.872" y="10.638" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.156863 0 0 0 0 0.0784314 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23851"/></filter><filter id="iJpvtVc" width="3.115" height="1.946" x="12.469" y="10.638" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.156863 0 0 0 0 0.0784314 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23851"/></filter><filter id="ii9sO5d" width=".816" height=".721" x="18.153" y="13.276" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23851" stdDeviation=".05"/></filter><filter id="i0Aunge" width=".916" height=".939" x="19.039" y="13.36" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23851" stdDeviation=".1"/></filter><filter id="imXh74d" width="1.015" height="1.072" x="14.377" y="13.293" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23851" stdDeviation=".1"/></filter><filter id="iuhp9pe" width=".948" height=".729" x="13.58" y="13.267" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23851" stdDeviation=".05"/></filter><filter id="iwrLgjd" width="3.191" height="1.702" x="17.749" y="10.782" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23851" stdDeviation=".25"/></filter><filter id="iqr8iMd" width="3.273" height="1.762" x="12.271" y="10.848" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23851" stdDeviation=".25"/></filter><filter id="i8xTAcc" width="1.021" height="2.345" x="11.227" y="9.023" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23851" stdDeviation=".125"/></filter><linearGradient id="iK84mBb" x1="22.562" x2="21.812" y1="29.826" y2="29.826" gradientUnits="userSpaceOnUse"><stop class="fr__qmhjc"/><stop offset="1" class="gypp10kih"/></linearGradient><linearGradient id="iWCiqKd" x1="20.644" x2="21.062" y1="29.014" y2="29.014" gradientUnits="userSpaceOnUse"><stop class="hj-s-zboe"/><stop offset="1" class="s0umluqbl"/></linearGradient><linearGradient id="ipodSkc" x1="9.531" x2="4.906" y1="27.451" y2="27.451" gradientUnits="userSpaceOnUse"><stop class="sb-ednb_a"/><stop offset="1" class="v0501vbqa"/></linearGradient><linearGradient id="iXPTZOc" x1="9.75" x2="8.828" y1="27.076" y2="27.076" gradientUnits="userSpaceOnUse"><stop class="o_30au2yc"/><stop offset="1" class="c60cvac3k"/></linearGradient><linearGradient id="itP1zjc" x1="27.871" x2="22.844" y1="28.142" y2="28.142" gradientUnits="userSpaceOnUse"><stop class="i7zyuv8vr"/><stop offset=".907" class="qzhltkbuo"/></linearGradient><linearGradient id="i33ZCUz" x1="28.09" x2="27.168" y1="27.876" y2="27.876" gradientUnits="userSpaceOnUse"><stop class="tub8lbbfx"/><stop offset="1" class="bd09vtb_c"/></linearGradient><linearGradient id="i8tJXGc" x1="16.763" x2="16.763" y1="22.812" y2="24.81" gradientUnits="userSpaceOnUse"><stop offset=".351" class="gzsz7evmk"/><stop offset="1" class="smgiue0gi"/></linearGradient><linearGradient id="imI15oe" x1="29.13" x2="28.38" y1="20.034" y2="21.659" gradientUnits="userSpaceOnUse"><stop class="au5hixbak"/><stop offset="1" class="mcp_a12ev"/><stop offset="1" class="i4lia-rzw"/></linearGradient><linearGradient id="iamKure" x1="4.76" x2="5.331" y1="20.169" y2="21.223" gradientUnits="userSpaceOnUse"><stop class="a86-seumw"/><stop offset="1" class="u5lbkrb_x"/></linearGradient><linearGradient id="iGhB53d" x1="4.307" x2="5.218" y1="19" y2="20.223" gradientUnits="userSpaceOnUse"><stop class="a86-seumw"/><stop offset="1" class="u5lbkrb_x"/></linearGradient><linearGradient id="ixXGBre" x1="5.489" x2="6.52" y1="17.6" y2="18.693" gradientUnits="userSpaceOnUse"><stop class="a86-seumw"/><stop offset="1" class="u5lbkrb_x"/></linearGradient><linearGradient id="iVKoQ5f" x1="4.452" x2="5.734" y1="18.044" y2="19.502" gradientUnits="userSpaceOnUse"><stop class="a86-seumw"/><stop offset="1" class="u5lbkrb_x"/></linearGradient><linearGradient id="iqD3oIz" x1="11.648" x2="10.975" y1="14.741" y2="14.741" gradientUnits="userSpaceOnUse"><stop class="jrtbzwbyo"/><stop offset="1" class="xh6agdcni"/></linearGradient><linearGradient id="iOW2Csd" x1="22.774" x2="21.915" y1="13.303" y2="15.965" gradientUnits="userSpaceOnUse"><stop class="z3o7w4-ew"/><stop offset="1" class="uddso4bed"/></linearGradient><linearGradient id="ieSd4zs" x1="20.868" x2="12.852" y1="14.857" y2="16.052" gradientUnits="userSpaceOnUse"><stop class="ah-u2v6vh"/><stop offset="1" class="hp2sktbkw"/></linearGradient><linearGradient id="iKQU1Db" x1="10.968" x2="12.943" y1="17.687" y2="17.617" gradientUnits="userSpaceOnUse"><stop class="wgn2-qn3r"/><stop offset="1" class="cyilnmbju"/></linearGradient><linearGradient id="iI4rfUd" x1="21.738" x2="20.63" y1="16.808" y2="16.702" gradientUnits="userSpaceOnUse"><stop class="y91wuhb_y"/><stop offset="1" class="dfnybco8z"/></linearGradient><linearGradient id="ia7TxKE" x1="16.662" x2="16.662" y1="10.605" y2="11.878" gradientUnits="userSpaceOnUse"><stop class="dg7qenbli"/><stop offset="1" class="lcni0o4zg"/></linearGradient><linearGradient id="ir0ybGe" x1="15.725" x2="16.71" y1="15.549" y2="15.549" gradientUnits="userSpaceOnUse"><stop class="tye5yqhfq"/><stop offset="1" class="rb8odhbtu"/></linearGradient><linearGradient id="iPyCbkc" x1="17.617" x2="16.54" y1="15.888" y2="15.872" gradientUnits="userSpaceOnUse"><stop class="w6mxzsbgv"/><stop offset="1" class="ylom6naui"/></linearGradient><linearGradient id="iJqnWqc" x1="16.836" x2="16.836" y1="16.667" y2="16.065" gradientUnits="userSpaceOnUse"><stop class="hlulkvo5l"/><stop offset="1" class="y_z4ite8v"/></linearGradient><linearGradient id="iba3Gae" x1="15.543" x2="15.999" y1="18.362" y2="17.641" gradientUnits="userSpaceOnUse"><stop class="lwz87437z"/><stop offset=".663" class="c7jfumw-i"/></linearGradient><linearGradient id="ixgKIPd" x1="19.735" x2="19.405" y1="13.789" y2="13.992" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iEOREJb" x1="15.119" x2="14.79" y1="13.789" y2="13.992" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="irt3zgd" x1="19.751" x2="19.31" y1="11.543" y2="10.642" gradientUnits="userSpaceOnUse"><stop class="v9-6-sbuc"/><stop offset="1" class="q8x82vmoe"/></linearGradient><linearGradient id="iuQvUad" x1="14.184" x2="12.935" y1="11.409" y2="10.885" gradientUnits="userSpaceOnUse"><stop class="v9-6-sbuc"/><stop offset="1" class="q8x82vmoe"/></linearGradient><linearGradient id="ihukOYd" x1="11.738" x2="11.738" y1="9.294" y2="11.559" gradientUnits="userSpaceOnUse"><stop offset=".228" class="tkijdf1cs"/><stop offset="1" class="wg8zzjbli"/></linearGradient><linearGradient id="izP9Z9c" x1="16.773" x2="16.773" y1="7.912" y2="8.1" gradientUnits="userSpaceOnUse"><stop class="jhlen960d"/><stop offset="1" class="wjchuwb6a"/></linearGradient><linearGradient id="iYE2hsb" x1="17.956" x2="17.956" y1="10.98" y2="10.214" gradientUnits="userSpaceOnUse"><stop class="bl3fq0x9z"/><stop offset="1" class="lxo7c2i6k"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-juggling-medium-dark" /></template>
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

.af8mzdbwl {
  stop-color: var(--svg-color--5f679a, #5F679A);
}

.ah-u2v6vh {
  stop-color: var(--svg-color--9b6c5e, #9B6C5E);
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

.axv337-vt {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.852 13.43c.066.09-.073.198-.232.317c-.158.118-.276.202-.343.112c-.066-.089.008-.257.167-.376c.158-.119.341-.142.408-.053");
}

.b057dp4eh {
  stop-color: var(--svg-color--ccbdde, #CCBDDE);
}

.b9-qm444s {
  stop-color: var(--svg-color--784b52, #784B52);
  stop-opacity: 0;
}

.bd09vtb_c {
  stop-color: var(--svg-color--e0dde3, #E0DDE3);
  stop-opacity: 0;
}

.bd4yam5lz {
  cx: 21.634px;
  cy: 14.449px;
  r: 1.752px;
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

.brk2w9bsn {
  d: path("M20.536 11.593h-.001l-.002-.002l-.005-.004l-.013-.01l-.037-.029a2.7 2.7 0 0 0-.565-.306a3 3 0 0 0-1.568-.165a.56.56 0 1 0 .175 1.106c.418-.066.752.011.98.102a1.6 1.6 0 0 1 .324.173a.56.56 0 0 0 .712-.865");
}

.btor07b8q {
  stop-color: var(--svg-color--d61f4d, #D61F4D);
}

.byn6wubog {
  fill: var(--svg-color--bc9ebb, #BC9EBB);
  fill-rule: evenodd;
  d: path("M16.899 24.871a.35.35 0 0 1-.266.244c-.25.048-.467.048-.717 0a.35.35 0 0 1-.262-.23c-.18.2-.49.432-1.009.607c-.31.106-.668.058-.833-.23a1.86 1.86 0 0 1-.245-.948c0-.431.124-.74.245-.95c.165-.287.523-.334.833-.23c.503.171.81.418.993.63a.35.35 0 0 1 .278-.293c.25-.048.467-.048.717 0a.35.35 0 0 1 .28.31c.18-.215.49-.47 1.008-.646c.31-.105.668-.058.834.23c.12.208.244.513.244.949s-.124.74-.244.949c-.166.287-.524.335-.834.23c-.531-.18-.844-.42-1.022-.622");
}

.c-7n2ksmg {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M11.873 9.398v.942c-.008.156-.073.505-.27.653");
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

.c7jfumw-i {
  stop-color: var(--svg-color--865e63, #865E63);
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

.cpvxurbrw {
  stop-color: var(--svg-color--46383d, #46383D);
  stop-opacity: 0;
}

.ctsppjbax {
  d: path("M14.866 22.463c.91.308 1.268.83 1.389 1.082l.028.29l-.028.359c-.12.25-.48.706-1.389 1.014c-.36.123-.777.068-.97-.267a2.17 2.17 0 0 1-.285-1.105c0-.502.144-.862.285-1.106c.193-.335.61-.39.97-.267");
}

.ctupw6b3d {
  fill-rule: evenodd;
  d: path("M3.113 18.184a.75.75 0 0 1 1.042.196c.312.455.974 1.204 1.85 1.204a.75.75 0 1 1 0 1.5c-1.702 0-2.759-1.376-3.088-1.858a.75.75 0 0 1 .196-1.042");
}

.cyilnmbju {
  stop-color: var(--svg-color--84615a, #84615A);
  stop-opacity: 0;
}

.d5_x4xk7i {
  fill-rule: evenodd;
  d: path("M3.16 17.066a.75.75 0 0 1 1.042.197q.055.08.116.173c.17.259.379.576.676.877c.36.363.768.614 1.246.64a.75.75 0 0 1-.08 1.497c-.99-.052-1.73-.575-2.232-1.083c-.416-.42-.725-.893-.888-1.143l-.076-.115a.75.75 0 0 1 .196-1.043");
}

.d52rddbnb {
  stop-color: var(--svg-color--976f6a, #976F6A);
  stop-opacity: 0;
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

.dfnybco8z {
  stop-color: var(--svg-color--966d5f, #966D5F);
  stop-opacity: 0;
}

.dg7qenbli {
  stop-color: var(--svg-color--6b3d41, #6B3D41);
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

.eau-icrly {
  cx: 14.054px;
  cy: 13.632px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.409px;
  ry: 0.207px;
}

.emrugab1j {
  stop-color: var(--svg-color--84665d, #84665D);
}

.evklql54e {
  stop-color: var(--svg-color--73443e, #73443E);
  stop-opacity: 0;
}

.f21vmbcik {
  d: path("M5.437 21.764h4.094v8.063H5.437z");
}

.faah7i3zw {
  stop-color: var(--svg-color--846252, #846252);
  stop-opacity: 0;
}

.fde_fwzpt {
  stop-color: var(--svg-color--5c9946, #5C9946);
}

.fe5_67d9h {
  fill: var(--svg-color--7e595a, #7E595A);
  d: path("M25.92 18.247a.668.668 0 1 1 1.316-.232l.34 2.222q.012.082.005.164l-.015.163c-.005.055-.002.11 0 .165c.016.295-.146.515-.454.557a.61.61 0 0 1-.68-.483z");
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

.gey-evbzc {
  stop-color: var(--svg-color--453938, #453938);
  stop-opacity: 0;
}

.gfrsedb9v {
  stop-color: var(--svg-color--5b595e, #5B595E);
}

.ggm3_setj {
  d: path("m13.38 20.005l.612 3.22h4.946l.796-3.173a10.2 10.2 0 0 0-2.937-.429h-.64c-.963 0-1.894.133-2.777.382");
}

.gr0wzobbs {
  stop-color: var(--svg-color--dbcdd4, #DBCDD4);
  stop-opacity: 0;
}

.gsgzrwbpm {
  stop-color: var(--svg-color--664249, #664249);
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

.h2l0yub-m {
  d: path("m12.67 11.594l.002-.001l.002-.002l.005-.004l.013-.01l.037-.029q.047-.034.125-.084c.105-.066.253-.147.44-.221a3 3 0 0 1 1.568-.166a.56.56 0 0 1-.175 1.106a1.85 1.85 0 0 0-.98.102a1.6 1.6 0 0 0-.324.173a.56.56 0 0 1-.712-.864");
}

.h2li0wblg {
  stop-color: var(--svg-color--d02759, #D02759);
}

.h4mko5b9o {
  stop-color: var(--svg-color--beb4c6, #BEB4C6);
  stop-opacity: 0;
}

.hcb81nbzm {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M18.374 11.442c.452-.08 1.332-.057 1.942.417");
}

.hcmh5c50b {
  stop-color: var(--svg-color--357ace, #357ACE);
}

.hj-s-zboe {
  stop-color: var(--svg-color--6d5096, #6D5096);
}

.hlulkvo5l {
  stop-color: var(--svg-color--7c4559, #7C4559);
}

.hp2sktbkw {
  stop-color: var(--svg-color--744d4a, #744D4A);
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

.i4lia-rzw {
  stop-color: var(--svg-color--9b7b72, #9B7B72);
  stop-opacity: 0;
}

.i6deo3edg {
  cx: 21.634px;
  cy: 14.448px;
  r: 1.044px;
  fill: var(--svg-color--7a5654, #7A5654);
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

.jeg__ccjl {
  fill: var(--svg-color--88014f, #88014F);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M15.2 17.345a.21.21 0 0 0-.25.043a.194.194 0 0 0-.022.249c.36.546.989.91 1.703.91s1.343-.365 1.704-.91a.196.196 0 0 0-.022-.251a.21.21 0 0 0-.25-.041a3.1 3.1 0 0 1-1.432.339a3.1 3.1 0 0 1-1.43-.34Z");
}

.jhbcwjouc {
  cx: 11.648px;
  cy: 14.449px;
  r: 1.752px;
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

.jrtbzwbyo {
  stop-color: var(--svg-color--553038, #553038);
}

.jy5_zcb8f {
  fill: var(--svg-color--000, #000);
  d: path("M18.384 14.169c0-.298.239-.537.537-.537a.534.534 0 0 1 .476.784h-.949a.5.5 0 0 1-.064-.247");
}

.k9derdbxj {
  d: path("m16.23 14.149l-.557 1.784a.566.566 0 0 0 .546.734h.825c.387 0 .66-.373.547-.734l-.558-1.784c-.12-.395-.677-.395-.802 0");
}

.kb4brky7h {
  d: path("m11.279 13.805l.051.002s-.056-.896-.112-1.512c0-.28.112-.615.338-.784l.168-.167c.282-.224.394-.56.394-.896v-.896c0-.28.17-.504.45-.56c.677-.168 2.084-.448 4.111-.448s3.435.28 4.11.448c.226.056.45.28.45.56v.896c0 .336.17.672.395.896c.527.369.494.572.45 1.007c-.056.56-.112 1.512-.112 1.512h.019l-.28 4.155c-.168 1.857-1.628 3.152-3.37 3.152h-3.37c-1.796 0-3.2-1.295-3.369-3.152z");
}

.kk2f_dbcn {
  d: path("M18.852 13.43c.066.09-.073.198-.232.317c-.158.118-.276.202-.343.112c-.066-.089.008-.257.167-.376c.158-.119.341-.142.408-.053");
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

.kz100sbcz {
  stop-color: var(--svg-color--855354, #855354);
  stop-opacity: 0;
}

.kzk-_ccou {
  stop-color: var(--svg-color--8b6a6b, #8B6A6B);
  stop-opacity: 0;
}

.kzuil_5zu {
  stop-color: var(--svg-color--9072ca, #9072CA);
}

.l-r9gxb9g {
  stop-color: var(--svg-color--4bb8fb, #4BB8FB);
}

.l04ioccmf {
  cx: 14.054px;
  cy: 13.632px;
  rx: 0.409px;
  ry: 0.207px;
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.lc7su-9ui {
  stop-color: var(--svg-color--7f5a4b, #7F5A4B);
}

.lcni0o4zg {
  stop-color: var(--svg-color--6b3d41, #6B3D41);
  stop-opacity: 0;
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

.lk_cbyb-c {
  stop-color: var(--svg-color--784b52, #784B52);
}

.lkn2u3bae {
  stop-color: var(--svg-color--3e3034, #3E3034);
  stop-opacity: 0;
}

.lu7irnbsv {
  fill: var(--svg-color--7e595a, #7E595A);
  d: path("M24.458 17.959a.68.68 0 0 1 .568-.843l.023-.003a.68.68 0 0 1 .756.54l.622 3.039c.071.355-.246.42-.606.458c-.303.032-.553-.005-.629-.3z");
}

.lucypabyc {
  d: path("M14.545 18.417c0-.99.9-1.794 2.011-1.794s2.012.803 2.012 1.794v2.326c0 .99-.9 1.794-2.012 1.794c-1.11 0-2.011-.803-2.011-1.794z");
}

.lwz87437z {
  stop-color: var(--svg-color--865e63, #865E63);
}

.lxo7c2i6k {
  stop-color: var(--svg-color--462f5a, #462F5A);
  stop-opacity: 0;
}

.m-1-e5bla {
  stop-color: var(--svg-color--fbf2f7, #FBF2F7);
}

.m13zyzbuk {
  stop-color: var(--svg-color--8b6a6b, #8B6A6B);
}

.m5avsc_ef {
  stop-color: var(--svg-color--784b89, #784B89);
}

.m8y3hpmcv {
  fill: var(--svg-color--352827, #352827);
  d: path("M20.536 11.593h-.001l-.002-.002l-.005-.004l-.013-.01l-.037-.029a2.7 2.7 0 0 0-.565-.306a3 3 0 0 0-1.568-.165a.56.56 0 1 0 .175 1.106c.418-.066.752.011.98.102a1.6 1.6 0 0 1 .324.173a.56.56 0 0 0 .712-.865");
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

.mfyy4ibhn {
  stop-color: var(--svg-color--6c443e, #6C443E);
  stop-opacity: 0;
}

.mhenm65eu {
  fill: var(--svg-color--000, #000);
  d: path("M14.873 14.169a.534.534 0 0 0-.536-.537a.534.534 0 0 0-.477.784h.95a.5.5 0 0 0 .063-.247");
}

.mmq2utbuk {
  stop-color: var(--svg-color--cf8b51, #CF8B51);
}

.mpwbs5b3u {
  stop-color: var(--svg-color--ff894e, #FF894E);
}

.n297mkbnr {
  stop-color: var(--svg-color--d6d3d7, #D6D3D7);
  stop-opacity: 0;
}

.ne4llzbvb {
  stop-color: var(--svg-color--301a2d, #301A2D);
}

.ng1cexbhj {
  stop-color: var(--svg-color--b6424c, #B6424C);
}

.nhrtbwabt {
  stop-color: var(--svg-color--613641, #613641);
}

.nl0wbpawx {
  stop-color: var(--svg-color--968f9c, #968F9C);
}

.o_30au2yc {
  stop-color: var(--svg-color--decfd8, #DECFD8);
}

.o415o878f {
  stop-color: var(--svg-color--ef4c8b, #EF4C8B);
}

.o45oetbxg {
  stop-color: var(--svg-color--6c443e, #6C443E);
}

.o90gcpqxu {
  stop-color: var(--svg-color--3d3437, #3D3437);
  stop-opacity: 0;
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

.p2_a-vgnp {
  d: path("M11.218 12.295c0-.28.112-.615.338-.784l.168-.167c.282-.224.394-.56.394-.896v-.896c0-.28.17-.504.45-.56c.677-.168 2.084-.448 4.111-.448s3.435.28 4.11.448c.226.056.45.28.45.56v.896c0 .336.17.672.395.896c.527.369.494.572.45 1.007c-.056.56-.112 1.512-.112 1.512h.019l-.28 4.155c-.168 1.857-1.628 3.152-3.37 3.152h-3.37c-1.796 0-3.2-1.295-3.369-3.152c-.146-1.907-.21-3.82-.384-5.723");
}

.p22s-zbfq {
  stop-color: var(--svg-color--77455b, #77455B);
  stop-opacity: 0;
}

.pb6efmson {
  stop-color: var(--svg-color--d72c5e, #D72C5E);
}

.pfrjt3bzl {
  d: path("M15.192 14.059c0-.303-.246-.505-.312-.566l-.303.293l.186.379z");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.ppo67rb9b {
  stop-color: var(--svg-color--73443e, #73443E);
}

.ppr920emc {
  stop-color: var(--svg-color--61a150, #61A150);
  stop-opacity: 0;
}

.pshp3gbyy {
  cx: 11.648px;
  cy: 14.448px;
  r: 1.044px;
}

.pt8frltpn {
  stop-color: var(--svg-color--7060a5, #7060A5);
}

.pw1h71b2a {
  stop-color: var(--svg-color--7c524c, #7C524C);
  stop-opacity: 0;
}

.py_-fb9_p {
  d: path("M14.337 13.232a.937.937 0 0 0-.903 1.184h1.81a1 1 0 0 0 .034-.248a.943.943 0 0 0-.941-.936");
}

.q3kvcibxc {
  stop-color: var(--svg-color--855354, #855354);
}

.q63ojm9za {
  cx: 21.634px;
  cy: 14.448px;
  r: 1.044px;
}

.q8x82vmoe {
  stop-color: var(--svg-color--483e3e, #483E3E);
  stop-opacity: 0;
}

.qjbq_nb5a {
  stop-color: var(--svg-color--9e7c73, #9E7C73);
}

.qoz4txb4k {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M12.896 11.986c.343-.304 1.093-.623 2.023-.475");
}

.qr8h38bcf {
  stop-color: var(--svg-color--826052, #826052);
}

.qsu4qbckq {
  stop-color: var(--svg-color--dbcdd4, #DBCDD4);
}

.qu0fk82sg {
  fill: var(--svg-color--fff, #fff);
  d: path("M19.138 12.947c.685 0 1.264.472 1.422 1.11a.288.288 0 0 1-.281.358h-2.342a.242.242 0 0 1-.238-.285a1.47 1.47 0 0 1 1.439-1.183");
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

.r_g462bwu {
  fill: var(--svg-color--7e595a, #7E595A);
  d: path("M22.414 19.88a.68.68 0 1 1 1.33-.293l.36 1.793a.645.645 0 0 1-1.26.28z");
}

.rb8odhbtu {
  stop-color: var(--svg-color--754e46, #754E46);
  stop-opacity: 0;
}

.rko8b-bmk {
  stop-color: var(--svg-color--714250, #714250);
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

.s5xtkwbhw {
  stop-color: var(--svg-color--6f414d, #6F414D);
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

.sirm6td-l {
  stop-color: var(--svg-color--784759, #784759);
}

.smgiue0gi {
  stop-color: var(--svg-color--c93857, #C93857);
}

.sr2acebhk {
  fill: var(--svg-color--8c5f5e, #8C5F5E);
  d: path("m16.23 14.149l-.557 1.784a.566.566 0 0 0 .546.734h.825c.387 0 .66-.373.547-.734l-.558-1.784c-.12-.395-.677-.395-.802 0");
}

.swka_j87x {
  d: path("M6.25 29.826c0-5.635 4.568-10.203 10.203-10.203h.64c5.636 0 10.204 4.568 10.204 10.203z");
}

.swmlbjbuq {
  stop-color: var(--svg-color--836153, #836153);
}

.t-5nldk3g {
  cx: 16.761px;
  cy: 28.296px;
  r: 0.739px;
}

.tg07-ljnl {
  stop-color: var(--svg-color--5e5764, #5E5764);
}

.tkijdf1cs {
  stop-color: var(--svg-color--32272d, #32272D);
}

.tn_97qkdc {
  stop-color: var(--svg-color--f2c341, #F2C341);
  stop-opacity: 0;
}

.tti32obdt {
  stop-color: var(--svg-color--46383d, #46383D);
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

.tye5yqhfq {
  stop-color: var(--svg-color--754e46, #754E46);
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

.uddso4bed {
  stop-color: var(--svg-color--855a5b, #855A5B);
}

.ugcc8sbhb {
  fill: var(--svg-color--352827, #352827);
  d: path("m12.67 11.594l.002-.001l.002-.002l.005-.004l.013-.01l.037-.029q.047-.034.125-.084c.105-.066.253-.147.44-.221a3 3 0 0 1 1.568-.166a.56.56 0 0 1-.175 1.106a1.85 1.85 0 0 0-.98.102a1.6 1.6 0 0 0-.324.173a.56.56 0 0 1-.712-.864");
}

.ujrq6ixuu {
  stop-color: var(--svg-color--beb4c6, #BEB4C6);
}

.uqr6xg6is {
  stop-color: var(--svg-color--7f5552, #7F5552);
}

.uwilonrnh {
  fill: var(--svg-color--71404a, #71404A);
  d: path("m16.342 14.32l-.86 1.784c-.107.367.149.734.512.734h.773c.363 0 .62-.372.513-.734l-.523-1.784c-.112-.395-.297-.395-.415 0");
}

.v0501vbqa {
  stop-color: var(--svg-color--c0b5cd, #C0B5CD);
}

.v4bc9u3un {
  stop-color: var(--svg-color--3d3437, #3D3437);
}

.v9-6-sbuc {
  stop-color: var(--svg-color--483e3e, #483E3E);
}

.vdngsab5t {
  fill-rule: evenodd;
  d: path("M3.416 19.34a.75.75 0 0 1 1.051.14c.244.317.833.881 1.8.881a.75.75 0 0 1 .75.75c0 .415-.336.67-.75.67c-1.683 0-2.593-.87-2.99-1.39a.75.75 0 0 1 .139-1.05");
}

.vgfjqtbdb {
  stop-color: var(--svg-color--301a2d, #301A2D);
  stop-opacity: 0;
}

.vke6kh8bt {
  stop-color: var(--svg-color--3e3843, #3E3843);
  stop-opacity: 0;
}

.vpyj0s_ar {
  stop-color: var(--svg-color--3e3034, #3E3034);
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

.w-44tpbkk {
  stop-color: var(--svg-color--976f6a, #976F6A);
}

.w63qn2bkh {
  stop-color: var(--svg-color--605966, #605966);
}

.w6mxzsbgv {
  stop-color: var(--svg-color--9d766b, #9D766B);
}

.wfgw5ub6b {
  fill-rule: evenodd;
  d: path("M4.273 16.754a.75.75 0 0 1 1.042.196q.091.134.166.258c.141.228.267.432.519.637c.292.238.794.485 1.747.42a.75.75 0 1 1 .102 1.497c-1.29.088-2.178-.25-2.796-.754c-.478-.389-.78-.89-.917-1.116l-.059-.096a.75.75 0 0 1 .196-1.042");
}

.wg8zzjbli {
  stop-color: var(--svg-color--32272d, #32272D);
  stop-opacity: 0;
}

.wgn2-qn3r {
  stop-color: var(--svg-color--84615a, #84615A);
}

.whxihzpaf {
  stop-color: var(--svg-color--5f3e52, #5F3E52);
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

.x1l7xqbyw {
  stop-color: var(--svg-color--de5534, #DE5534);
  stop-opacity: 0;
}

.xh6agdcni {
  stop-color: var(--svg-color--59323c, #59323C);
}

.xkn2wzmus {
  stop-color: var(--svg-color--7e595a, #7E595A);
}

.xntzq-4ho {
  stop-color: var(--svg-color--8566b5, #8566B5);
}

.y_auwli2s {
  stop-color: var(--svg-color--415e58, #415E58);
}

.y_z4ite8v {
  stop-color: var(--svg-color--7c4559, #7C4559);
  stop-opacity: 0;
}

.y-1rsmdul {
  stop-color: var(--svg-color--3a7ab4, #3A7AB4);
  stop-opacity: 0;
}

.y-darzb-m {
  fill: var(--svg-color--27151c, #27151C);
  d: path("m21.69 7.649l-.056 1.808c.788.391 1.745-.297 1.576.655l-.62 3.191c-.055.33-.272.551-.6.56h-.019s.057-.952.113-1.512c.046-.454-.034-.593-.45-1.007c-.226-.224-.395-.56-.395-.896v-.896c0-.28-.225-.504-.45-.56c-.676-.168-2.083-.447-4.11-.447s-3.435.28-4.11.447a.546.546 0 0 0-.45.56v.896c0 .336-.114.672-.395.896l-.169.168c-.225.168-.338.503-.338.784c.057.615.113 1.511.113 1.511l-.052-.002a.665.665 0 0 1-.624-.558l-.62-3.19c-.112-.897.232-.113 1.02-.505l.557-1.903c.282-.168.563-.392.845-.616l1.013-1.064c.62-.56 1.52-.727 2.309-.336a3.1 3.1 0 0 0 1.745 0c.845-.28 1.802-.055 2.478.56l.844.84c.225.28.507.448.845.616");
}

.y05rrkbkk {
  stop-color: var(--svg-color--ffff54, #FFFF54);
}

.y2ly1lryk {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-35px, 0.35px);
  d: path("M3.716 18.576c.177.245.672.953 1.492 1.172");
}

.y3zk80bfr {
  d: path("M19.755 14.045a.9.9 0 0 0-.243-.485l-.273.299l.123.24z");
}

.y91wuhb_y {
  stop-color: var(--svg-color--966d5f, #966D5F);
}

.yk1hdeydu {
  fill: var(--svg-color--fff, #fff);
  d: path("M14.12 12.947c-.686 0-1.265.472-1.422 1.11a.288.288 0 0 0 .28.359h2.342a.242.242 0 0 0 .239-.286a1.47 1.47 0 0 0-1.44-1.183");
}

.ykzqhbcyt {
  stop-color: var(--svg-color--997067, #997067);
}

.ylom6naui {
  stop-color: var(--svg-color--9d766b, #9D766B);
  stop-opacity: 0;
}

.ym-b_m9fy {
  stop-color: var(--svg-color--d1bed4, #D1BED4);
  stop-opacity: 0;
}

.ywu0pr7ii {
  stop-color: var(--svg-color--7c524c, #7C524C);
}

.z_g0j449a {
  stop-color: var(--svg-color--6f414d, #6F414D);
}

.z3o7w4-ew {
  stop-color: var(--svg-color--96776b, #96776B);
}

.zdcorrl9x {
  cx: 26.234px;
  cy: 14.83px;
  r: 1.684px;
}

.zk3m83b4g {
  stop-color: var(--svg-color--453938, #453938);
}

.znup_d9es {
  stroke: var(--svg-color--997971, #997971);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-35px, 0.35px);
  d: path("m24.357 18.55l.437 2.127");
}

.zocay_btp {
  d: path("m21.69 7.649l-.056 1.808c.788.391 1.745-.297 1.576.655l-.62 3.191c-.055.33-.272.551-.6.56h-.019s.057-.952.113-1.512c.046-.454-.034-.593-.45-1.007c-.226-.224-.395-.56-.395-.896v-.896c0-.28-.225-.504-.45-.56c-.676-.168-2.083-.447-4.11-.447s-3.435.28-4.11.447a.546.546 0 0 0-.45.56v.896c0 .336-.114.672-.395.896l-.169.168c-.225.168-.338.503-.338.784c.057.615.113 1.511.113 1.511l-.052-.002a.665.665 0 0 1-.624-.558l-.62-3.19c-.112-.897.232-.113 1.02-.505l.557-1.903c.282-.168.563-.392.845-.616l1.013-1.064c.62-.56 1.52-.727 2.309-.336a3.1 3.1 0 0 0 1.745 0c.845-.28 1.802-.055 2.478.56l.844.84c.225.28.507.448.845.616");
}

.zwyp76bpi {
  d: path("M18.921 13.232a.937.937 0 0 1 .903 1.183h-1.81a.94.94 0 0 1 .907-1.184");
}

</style>
