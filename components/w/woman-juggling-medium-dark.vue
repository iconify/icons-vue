<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><path id="iSEC7Bg" class="be39v8b_v"/></defs><g class="ft5dv1b6b"><g filter="url(#i6TXXde)"><path fill="url(#iMgry4c)" clip-rule="evenodd" class="uw0_1wnpi"/><path fill="url(#idvyg3c)" clip-rule="evenodd" class="uw0_1wnpi"/><path fill="url(#iEjZY7u)" clip-rule="evenodd" class="uw0_1wnpi"/><path fill="url(#iKLcCDb)" clip-rule="evenodd" class="uw0_1wnpi"/><path fill="url(#imUXDyd)" clip-rule="evenodd" class="uw0_1wnpi"/><path fill="url(#iH074hO)" clip-rule="evenodd" class="uw0_1wnpi"/><path fill="url(#irVZPnG)" clip-rule="evenodd" class="uw0_1wnpi"/><path fill="url(#ih7BEbc)" clip-rule="evenodd" class="uw0_1wnpi"/><path fill="url(#i6ZJJlc)" clip-rule="evenodd" class="uw0_1wnpi"/><path fill="url(#iANQqXg)" clip-rule="evenodd" class="uw0_1wnpi"/><path fill="url(#ic7Idsc)" clip-rule="evenodd" class="uw0_1wnpi"/></g><g filter="url(#iPpnG1c)"><path fill="url(#iPYYWhe)" class="swka_j87x"/><path fill="url(#iT07jwd)" class="swka_j87x"/><path fill="url(#il5eVUq)" class="swka_j87x"/><path fill="url(#iY3yYtd)" class="swka_j87x"/><path fill="url(#iv8FoOX)" class="swka_j87x"/></g><circle fill="url(#iBZ0RUd)" class="hpfqe6rjh"/><circle fill="url(#itKlKTd)" class="hpfqe6rjh"/><circle fill="url(#ihlr5IT)" class="duyhuibwk"/><circle fill="url(#iGUmgWd)" class="duyhuibwk"/><circle fill="url(#iXhqZHd)" class="iwbygtbvw"/><circle fill="url(#iOHvRJe)" class="iwbygtbvw"/><circle fill="url(#issuNue)" class="zdcorrl9x"/><circle fill="url(#iMaLBhb)" class="zdcorrl9x"/><circle fill="url(#iAhrvZc)" class="zdcorrl9x"/><g filter="url(#i4ahPBd)"><circle fill="url(#iMk8UMb)" class="t-5nldk3g"/></g><g filter="url(#iLm34Bc)"><circle fill="url(#iR23Gge)" class="don2wdpjw"/></g><path fill="url(#i5YvaPc)" class="j70rp9pis"/><path fill="url(#iK84mBb)" class="j70rp9pis"/><path fill="url(#iWCiqKd)" class="j70rp9pis"/><path fill="url(#ieol8Me)" class="qy4rrcb8b"/><path fill="url(#iDbbcbc)" class="qy4rrcb8b"/><path fill="url(#iOe2zrd)" class="qy4rrcb8b"/><path fill="url(#iV71Rbc)" class="qy4rrcb8b"/><g filter="url(#ioS9k1B)"><path fill="url(#iGnWdQb)" class="hirfvzj6c"/><path fill="url(#ihX9LUc)" class="hirfvzj6c"/></g><path fill="url(#ipodSkc)" class="f21vmbcik"/><path fill="url(#iXPTZOc)" class="f21vmbcik"/><path fill="url(#itP1zjc)" class="wp2p6dbcv"/><path fill="url(#i33ZCUz)" class="wp2p6dbcv"/><g filter="url(#iXkUIDd)"><path clip-rule="evenodd" class="byn6wubog"/></g><g filter="url(#iEdTYLd)"><path fill="url(#iSAsI1d)" class="ctsppjbax"/><path fill="url(#iwtPTOo)" class="ctsppjbax"/><path fill="url(#isAdhHe)" class="ctsppjbax"/></g><g filter="url(#iRytQJb)"><path fill="url(#ivLP6Gc)" class="ht6lpfbpp"/><path fill="url(#iXetYud)" class="ht6lpfbpp"/></g><g filter="url(#iVbsgBe)"><path fill="url(#i8tJXGc)" class="ld_83jb7a"/><path fill="url(#iw9bnJb)" class="ld_83jb7a"/></g><g filter="url(#iPJZ6bc)"><path class="d8vr2qabd"/></g><g filter="url(#ilMkEFq)"><path class="fe5_67d9h"/></g><g filter="url(#iGWJPWc)"><path class="lu7irnbsv"/></g><g filter="url(#iAi37ic)"><path class="a2erpabfq"/></g><g filter="url(#iSAGrbe)"><path class="r_g462bwu"/></g><path fill="url(#iy5yhkB)" class="hw860-bkw"/><path fill="url(#iLYPeid)" class="hw860-bkw"/><path fill="url(#igEWuTd)" class="hw860-bkw"/><g filter="url(#iHShkKc)"><path fill="url(#iUsDf3b)" class="u5bjt8cdp"/></g><path fill="url(#iya7JRb)" clip-rule="evenodd" class="wfgw5ub6b"/><path fill="url(#ixz6Bfl)" clip-rule="evenodd" class="wfgw5ub6b"/><path fill="url(#iomTwyb)" clip-rule="evenodd" class="d5_x4xk7i"/><path fill="url(#il5DzUH)" clip-rule="evenodd" class="d5_x4xk7i"/><path fill="url(#iXmA6MA)" clip-rule="evenodd" class="ctupw6b3d"/><path fill="url(#ifjLIpe)" clip-rule="evenodd" class="ctupw6b3d"/><path fill="url(#iy5Lb5d)" clip-rule="evenodd" class="vdngsab5t"/><path fill="url(#iMyswRb)" clip-rule="evenodd" class="vdngsab5t"/><path fill="url(#izQ0wGc)" class="twba206ho"/><path fill="url(#iBECMpb)" class="twba206ho"/><path fill="url(#iR7ZGtd)" class="vwf3t2b2u"/><g filter="url(#i75yEkb)"><path class="rt394ibmb"/></g><g filter="url(#imTnI4d)"><path class="nuqjb3b3u"/></g><g filter="url(#iWWyMTb)"><path class="phhy_ubqp"/></g><g filter="url(#iGbRvDl)"><path class="vv0hkr84h"/></g><g filter="url(#iQYzp7b)"><path stroke="url(#imI15oe)" class="bdk4dmb5b"/></g><g filter="url(#irfvnPe)"><path stroke="url(#iamKure)" class="gwm_2mjil"/></g><g filter="url(#iCbvYbS)"><path stroke="url(#iGhB53d)" class="y2ly1lryk"/></g><g filter="url(#iQeDutc)"><path stroke="url(#ixXGBre)" class="am6k_ubte"/></g><g filter="url(#iR87did)"><path stroke="url(#iVKoQ5f)" class="c549xi8ae"/></g><g filter="url(#iPijCCe)"><path class="vcz9qnm9q"/></g><g filter="url(#iDQjIYd)"><path class="hzaq54bmy"/></g><g filter="url(#iZ21R8d)"><path fill="url(#iOHqgze)" class="ccf6axbtk"/></g><g filter="url(#ica6vKq)"><path fill="url(#iaptchb)" class="osnazwkth"/><path fill="url(#ikkYZ8c)" class="osnazwkth"/></g><g filter="url(#iD5A4de)"><path class="fi7wz1bec"/><path fill="url(#iRAhcoC)" class="uaba6iq6u"/></g><g filter="url(#itQTwLQ)"><path class="vpo725bhk"/><path fill="url(#iE3Lc9b)" class="tl2m9zb9f"/></g><g filter="url(#iHhgXDc)"><path fill="url(#igKhlYi)" class="sbauxibsu"/><path fill="url(#ifhq5Kd)" class="sbauxibsu"/><path fill="url(#iDSMHsb)" class="sbauxibsu"/><path fill="url(#iciCm2b)" class="sbauxibsu"/><path fill="url(#if9Itpc)" class="sbauxibsu"/><path fill="url(#iTyEpdc)" class="sbauxibsu"/><path fill="url(#iFasDQb)" class="sbauxibsu"/><path fill="url(#iB3SbtO)" class="sbauxibsu"/></g><path fill="url(#iEnifqe)" class="sbauxibsu"/><path fill="url(#igJE5bd)" class="sbauxibsu"/><path fill="url(#iTx2zgd)" class="sbauxibsu"/><path fill="url(#iILntki)" class="sbauxibsu"/><g filter="url(#ijb1bXb)"><path class="umfbmkqyq"/></g><g filter="url(#iwfjMiE)"><path class="lm_8kobga"/><path fill="url(#i2CAQEe)" class="hvtb3cbit"/><path fill="url(#iBHYztc)" class="hvtb3cbit"/><path fill="url(#iUkk53H)" class="hvtb3cbit"/><path fill="url(#i5zICgd)" class="hvtb3cbit"/></g><g filter="url(#i1XCKKe)"><use href="#iSEC7Bg"/><path stroke="url(#iVRqHob)" class="bxaqvnd6d"/></g><use href="#iSEC7Bg"/><g filter="url(#iHxbfZd)"><path class="xuioilrmd"/></g><g filter="url(#idE1IGc)"><path class="ninyoac7q"/></g><g filter="url(#i2A3Psb)"><path class="h1ngowbkc"/></g><g filter="url(#iPo63db)"><path clip-rule="evenodd" class="rv0ymrbfc"/></g><path class="mm17qbboc"/><path fill="url(#iaxiavb)" class="gz5tj9apj"/><path class="pwun67v-k"/><g filter="url(#i5OmKkb)"><path class="zd45hpjnr"/><path fill="url(#ikGZJQd)" class="y0z9-1vnj"/></g><g filter="url(#iIXDGpO)"><path fill="url(#iEwUv5t)" class="to0rgu7go"/></g><path class="zr5faibop"/><path fill="url(#i6YWBKc)" class="g4d0dvb3l"/><path class="pdv9cyg6v"/><g filter="url(#iUFAmcc)"><path fill="url(#iMr32Vb)" class="zjwhzkbez"/></g><g filter="url(#i9jjJMe)"><ellipse transform="rotate(-27.914 14.277 13.311)" class="txvhrnh2c"/><ellipse fill="url(#iwBScIe)" transform="rotate(-27.914 14.277 13.311)" class="mrj68fbtn"/></g><g filter="url(#iz1EVvc)"><path class="s1xedwb9e"/></g><g filter="url(#iSr1ZAb)"><path class="pfu0f9xgl"/></g><g filter="url(#ik2mr4b)"><path stroke="url(#iIMpJGb)" class="xojd46bcr"/></g><g filter="url(#iFhQS9d)"><path class="v6yq82b7v"/></g><path fill="url(#iMwhdrV)" class="qzd219blo"/><path fill="url(#i3dSYhb)" class="qzd219blo"/><path fill="url(#inl9J2c)" class="qzd219blo"/><path fill="url(#iCE2gke)" class="wozepxbaa"/><path fill="url(#izP9Z9c)" class="wozepxbaa"/><rect fill="url(#ixSAAAe)" class="okwd93kys"/><rect fill="url(#iy7tjOa)" class="okwd93kys"/><rect fill="url(#iYE2hsb)" class="okwd93kys"/><defs><radialGradient id="idvyg3c" cx="0" cy="0" r="1" gradientTransform="rotate(97.539 .967 15.566)scale(4.80763 6.00571)" gradientUnits="userSpaceOnUse"><stop offset=".591" class="xdn388byj"/><stop offset="1" class="qwp4ni-tf"/></radialGradient><radialGradient id="iEjZY7u" cx="0" cy="0" r="1" gradientTransform="rotate(146.004 4.203 10.541)scale(3.63527 4.77645)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="bl7uysvvb"/><stop offset="1" class="r_v2kebuk"/></radialGradient><radialGradient id="iKLcCDb" cx="0" cy="0" r="1" gradientTransform="rotate(127.405 2.363 10.043)scale(2.24996 1.72766)" gradientUnits="userSpaceOnUse"><stop offset=".334" class="l0xg-rbdf"/><stop offset="1" class="chj8m5e2t"/></radialGradient><radialGradient id="imUXDyd" cx="0" cy="0" r="1" gradientTransform="rotate(121.43 2.719 9.508)scale(2.58744 1.82262)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="kbl3igr5c"/><stop offset="1" class="glo437b-m"/></radialGradient><radialGradient id="iH074hO" cx="0" cy="0" r="1" gradientTransform="rotate(62.272 1.937 13.699)scale(3.08811 4.28676)" gradientUnits="userSpaceOnUse"><stop class="paonnib9g"/><stop offset="1" class="g0r7omboq"/></radialGradient><radialGradient id="irVZPnG" cx="0" cy="0" r="1" gradientTransform="matrix(-1.50683 1.50693 -2.1059 -2.10576 22.939 7.784)" gradientUnits="userSpaceOnUse"><stop class="hx66smwtj"/><stop offset="1" class="c9_6uxbfa"/></radialGradient><radialGradient id="ih7BEbc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.92737 .56072 -1.16934 -4.01938 24.691 13.145)" gradientUnits="userSpaceOnUse"><stop class="cj4rfmfkx"/><stop offset="1" class="silozpblh"/></radialGradient><radialGradient id="i6ZJJlc" cx="0" cy="0" r="1" gradientTransform="rotate(165.963 11 9.841)scale(3.03427 3.8652)" gradientUnits="userSpaceOnUse"><stop class="mxnnm4bur"/><stop offset="1" class="jk5udqbyz"/></radialGradient><radialGradient id="iANQqXg" cx="0" cy="0" r="1" gradientTransform="matrix(-.9455 -2.77059 2.19138 -.74784 21.789 10.6)" gradientUnits="userSpaceOnUse"><stop class="hkormb2xp"/><stop offset="1" class="e-twaac7b"/></radialGradient><radialGradient id="ic7Idsc" cx="0" cy="0" r="1" gradientTransform="matrix(1.5722 .16491 -.26721 2.54742 10.42 13.108)" gradientUnits="userSpaceOnUse"><stop class="lgjudcrkd"/><stop offset="1" class="tr7czpf3k"/></radialGradient><radialGradient id="iPYYWhe" cx="0" cy="0" r="1" gradientTransform="rotate(135.22 8.643 15.887)scale(12.9545 12.5552)" gradientUnits="userSpaceOnUse"><stop offset=".195" class="m-1-e5bla"/><stop offset=".794" class="b057dp4eh"/></radialGradient><radialGradient id="iT07jwd" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.09375 -3.28125 0 20.219 20.139)" gradientUnits="userSpaceOnUse"><stop class="m9gf32bwp"/><stop offset="1" class="n297mkbnr"/></radialGradient><radialGradient id="il5eVUq" cx="0" cy="0" r="1" gradientTransform="matrix(-1.75 0 0 -11.7187 21 25.92)" gradientUnits="userSpaceOnUse"><stop offset=".214" class="demkpcl0k"/><stop offset="1" class="ym-b_m9fy"/></radialGradient><radialGradient id="iY3yYtd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.15625 0 0 -5.75902 11.656 25.326)" gradientUnits="userSpaceOnUse"><stop class="ujrq6ixuu"/><stop offset="1" class="h4mko5b9o"/></radialGradient><radialGradient id="iv8FoOX" cx="0" cy="0" r="1" gradientTransform="matrix(2.12502 5.34374 -11.023 4.38346 13.099 18.733)" gradientUnits="userSpaceOnUse"><stop class="nl0wbpawx"/><stop offset="1" class="jm40s5baz"/></radialGradient><radialGradient id="iBZ0RUd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.34375 2.4375 -2.36069 -1.3014 7.187 11.826)" gradientUnits="userSpaceOnUse"><stop offset=".077" class="l-r9gxb9g"/><stop offset="1" class="hcmh5c50b"/></radialGradient><radialGradient id="itKlKTd" cx="0" cy="0" r="1" gradientTransform="rotate(115.145 -.151 8.247)scale(3.38309 2.95533)" gradientUnits="userSpaceOnUse"><stop offset=".452" class="y-1rsmdul"/><stop offset=".826" class="af8mzdbwl"/></radialGradient><radialGradient id="ihlr5IT" cx="0" cy="0" r="1" gradientTransform="matrix(-1.34375 2.4375 -2.36069 -1.3014 10.101 2.846)" gradientUnits="userSpaceOnUse"><stop offset=".077" class="mpwbs5b3u"/><stop offset="1" class="fzq016boz"/></radialGradient><radialGradient id="iGUmgWd" cx="0" cy="0" r="1" gradientTransform="rotate(115.145 4.158 4.683)scale(3.38309 2.95533)" gradientUnits="userSpaceOnUse"><stop offset=".452" class="x1l7xqbyw"/><stop offset=".826" class="ng1cexbhj"/></radialGradient><radialGradient id="iXhqZHd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.34375 2.4375 -2.36069 -1.3014 26.066 3.861)" gradientUnits="userSpaceOnUse"><stop offset=".077" class="lelj2r8dg"/><stop offset="1" class="fde_fwzpt"/></radialGradient><radialGradient id="iOHvRJe" cx="0" cy="0" r="1" gradientTransform="rotate(105.03 11.36 11.751)scale(3.49455 3.40391)" gradientUnits="userSpaceOnUse"><stop offset=".375" class="ppr920emc"/><stop offset=".826" class="y_auwli2s"/></radialGradient><radialGradient id="issuNue" cx="0" cy="0" r="1" gradientTransform="matrix(-1.34375 2.4375 -2.36069 -1.3014 27.09 13.818)" gradientUnits="userSpaceOnUse"><stop offset=".077" class="y05rrkbkk"/><stop offset="1" class="a5zzorbzd"/></radialGradient><radialGradient id="iMaLBhb" cx="0" cy="0" r="1" gradientTransform="matrix(1 1.07812 -1.5877 1.47265 24.969 13.357)" gradientUnits="userSpaceOnUse"><stop class="i8j0jyb4u"/><stop offset="1" class="d7caiobkz"/></radialGradient><radialGradient id="iAhrvZc" cx="0" cy="0" r="1" gradientTransform="rotate(109.11 8.51 16.52)scale(3.46022 3.37046)" gradientUnits="userSpaceOnUse"><stop offset=".347" class="tn_97qkdc"/><stop offset=".829" class="mmq2utbuk"/></radialGradient><radialGradient id="iMk8UMb" cx="0" cy="0" r="1" gradientTransform="matrix(-.7578 1.14063 -.96756 -.64282 17.25 27.855)" gradientUnits="userSpaceOnUse"><stop offset=".212" class="u6lph46no"/><stop offset="1" class="bq5dgsbba"/></radialGradient><radialGradient id="iR23Gge" cx="0" cy="0" r="1" gradientTransform="matrix(-.7578 1.14063 -.96756 -.64282 17.25 25.842)" gradientUnits="userSpaceOnUse"><stop offset=".212" class="u6lph46no"/><stop offset="1" class="bq5dgsbba"/></radialGradient><radialGradient id="i5YvaPc" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.03125 -2.40212 0 22.222 20.983)" gradientUnits="userSpaceOnUse"><stop class="koq0r9bvu"/><stop offset="1" class="dpmuo-biy"/></radialGradient><radialGradient id="ieol8Me" cx="0" cy="0" r="1" gradientTransform="scale(1.38818 6.1875)rotate(90 2.761 6.5)" gradientUnits="userSpaceOnUse"><stop class="xntzq-4ho"/><stop offset="1" class="pt8frltpn"/></radialGradient><radialGradient id="iDbbcbc" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.25 -.60938 0 13.062 24.108)" gradientUnits="userSpaceOnUse"><stop class="wshx69b-y"/><stop offset="1" class="aqzyd8bsb"/></radialGradient><radialGradient id="iOe2zrd" cx="0" cy="0" r="1" gradientTransform="matrix(2.9375 -7.98881 7.06186 2.59666 10.312 28.264)" gradientUnits="userSpaceOnUse"><stop offset=".724" class="lgi0lwbjz"/><stop offset="1" class="tvoyviyhj"/></radialGradient><radialGradient id="iV71Rbc" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.42188 -.18506 0 12.857 21.717)" gradientUnits="userSpaceOnUse"><stop class="m5avsc_ef"/><stop offset="1" class="ci3gi1b_k"/></radialGradient><radialGradient id="iGnWdQb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.90624 2.42972 -4.28692 -6.89204 19.55 20.74)" gradientUnits="userSpaceOnUse"><stop class="ku63lg_wt"/><stop offset="1" class="i1-orb7ke"/></radialGradient><radialGradient id="ihX9LUc" cx="0" cy="0" r="1" gradientTransform="matrix(-.46875 -.125 .54686 -2.05079 19.471 22.427)" gradientUnits="userSpaceOnUse"><stop offset=".108" class="qsu4qbckq"/><stop offset="1" class="gr0wzobbs"/></radialGradient><radialGradient id="iSAsI1d" cx="0" cy="0" r="1" gradientTransform="matrix(1.73878 1.3451 -1.47727 1.90964 13.775 23.358)" gradientUnits="userSpaceOnUse"><stop class="ab6i82btp"/><stop offset="1" class="pb6efmson"/></radialGradient><radialGradient id="iwtPTOo" cx="0" cy="0" r="1" gradientTransform="matrix(-1.68958 -.4774 .79459 -2.81214 15.416 23.836)" gradientUnits="userSpaceOnUse"><stop offset=".69" class="sawf8hb2n"/><stop offset="1" class="o415o878f"/></radialGradient><radialGradient id="isAdhHe" cx="0" cy="0" r="1" gradientTransform="matrix(-.5 1.58457 -.75053 -.23683 16.11 23.836)" gradientUnits="userSpaceOnUse"><stop class="btor07b8q"/><stop offset="1" class="jjf293xlz"/></radialGradient><radialGradient id="ivLP6Gc" cx="0" cy="0" r="1" gradientTransform="rotate(142.275 5.895 15.056)scale(2.19833 2.41434)" gradientUnits="userSpaceOnUse"><stop class="auvn9fbbk"/><stop offset="1" class="h2li0wblg"/></radialGradient><radialGradient id="iXetYud" cx="0" cy="0" r="1" gradientTransform="matrix(1.68958 -.4774 .79459 2.81214 18.13 23.836)" gradientUnits="userSpaceOnUse"><stop offset=".69" class="sawf8hb2n"/><stop offset="1" class="o415o878f"/></radialGradient><radialGradient id="iw9bnJb" cx="0" cy="0" r="1" gradientTransform="matrix(-.39136 0 0 -2.59279 17.54 23.592)" gradientUnits="userSpaceOnUse"><stop class="scbqttb8d"/><stop offset="1" class="u1gl_1zha"/></radialGradient><radialGradient id="iy5yhkB" cx="0" cy="0" r="1" gradientTransform="matrix(-4.375 1.44046 -1.3893 -4.21963 28.098 22.456)" gradientUnits="userSpaceOnUse"><stop offset=".241" class="ykzqhbcyt"/><stop offset=".899" class="j20i63bee"/></radialGradient><radialGradient id="iLYPeid" cx="0" cy="0" r="1" gradientTransform="rotate(163.091 11.838 12.97)scale(3.90165 13.4872)" gradientUnits="userSpaceOnUse"><stop offset=".699" class="b9-qm444s"/><stop offset="1" class="lk_cbyb-c"/></radialGradient><radialGradient id="igEWuTd" cx="0" cy="0" r="1" gradientTransform="rotate(77.276 -.052 26.27)scale(.74486 4.08592)" gradientUnits="userSpaceOnUse"><stop class="xkn2wzmus"/><stop offset="1" class="ammr1_bix"/></radialGradient><radialGradient id="iUsDf3b" cx="0" cy="0" r="1" gradientTransform="rotate(139.97 1.2 10.48)scale(1.53045 3.638)" gradientUnits="userSpaceOnUse"><stop offset=".129" class="emrugab1j"/><stop offset="1" class="lc7su-9ui"/></radialGradient><radialGradient id="iya7JRb" cx="0" cy="0" r="1" gradientTransform="matrix(-.79386 1.27188 -2.4349 -1.51978 6.442 17.553)" gradientUnits="userSpaceOnUse"><stop class="swmlbjbuq"/><stop offset="1" class="ksmxe9b1k"/></radialGradient><radialGradient id="ixz6Bfl" cx="0" cy="0" r="1" gradientTransform="matrix(-.73037 2.48832 -3.82658 -1.12318 6.977 17.288)" gradientUnits="userSpaceOnUse"><stop offset=".585" class="p22s-zbfq"/><stop offset=".954" class="rq7piitrs"/></radialGradient><radialGradient id="iomTwyb" cx="0" cy="0" r="1" gradientTransform="rotate(116.602 -3.017 10.55)scale(1.58621 2.70684)" gradientUnits="userSpaceOnUse"><stop class="swmlbjbuq"/><stop offset="1" class="ksmxe9b1k"/></radialGradient><radialGradient id="il5DzUH" cx="0" cy="0" r="1" gradientTransform="matrix(-.65347 2.77477 -3.52334 -.82977 5.545 17.677)" gradientUnits="userSpaceOnUse"><stop offset=".585" class="p22s-zbfq"/><stop offset=".954" class="rq7piitrs"/></radialGradient><radialGradient id="iXmA6MA" cx="0" cy="0" r="1" gradientTransform="matrix(-.68468 1.22288 -2.2217 -1.2439 4.939 18.947)" gradientUnits="userSpaceOnUse"><stop class="swmlbjbuq"/><stop offset="1" class="ksmxe9b1k"/></radialGradient><radialGradient id="ifjLIpe" cx="0" cy="0" r="1" gradientTransform="rotate(104.751 -4.503 11.427)scale(2.474 3.46652)" gradientUnits="userSpaceOnUse"><stop offset=".585" class="p22s-zbfq"/><stop offset=".954" class="rq7piitrs"/></radialGradient><radialGradient id="iy5Lb5d" cx="0" cy="0" r="1" gradientTransform="rotate(122.692 -2.834 11.406)scale(1.24393 2.40994)" gradientUnits="userSpaceOnUse"><stop class="swmlbjbuq"/><stop offset="1" class="ksmxe9b1k"/></radialGradient><radialGradient id="iMyswRb" cx="0" cy="0" r="1" gradientTransform="matrix(-.61813 2.04813 -3.22394 -.973 5.687 19.733)" gradientUnits="userSpaceOnUse"><stop offset=".585" class="p22s-zbfq"/><stop offset=".954" class="rq7piitrs"/></radialGradient><radialGradient id="izQ0wGc" cx="0" cy="0" r="1" gradientTransform="rotate(-162.011 6.48 10.137)scale(3.69324 5.10277)" gradientUnits="userSpaceOnUse"><stop class="qjbq_nb5a"/><stop offset=".482" class="qr8h38bcf"/></radialGradient><radialGradient id="iBECMpb" cx="0" cy="0" r="1" gradientTransform="matrix(.07812 -.82813 3.88844 .36683 6.156 21.78)" gradientUnits="userSpaceOnUse"><stop class="sirm6td-l"/><stop offset="1" class="faah7i3zw"/></radialGradient><radialGradient id="iR7ZGtd" cx="0" cy="0" r="1" gradientTransform="matrix(1.65625 2.09375 -2.38774 1.88881 16.099 20.357)" gradientUnits="userSpaceOnUse"><stop offset=".229" class="bo6_cwbgw"/><stop offset="1" class="uqr6xg6is"/></radialGradient><radialGradient id="iaptchb" cx="0" cy="0" r="1" gradientTransform="rotate(-24.444 43.99 -41.374)scale(2.85826 3.4898)" gradientUnits="userSpaceOnUse"><stop offset=".64" class="olqyf7fmb"/><stop offset=".944" class="hpeo8yzih"/></radialGradient><radialGradient id="ikkYZ8c" cx="0" cy="0" r="1" gradientTransform="matrix(1.3755 .77098 -.21797 .38888 22.141 12.278)" gradientUnits="userSpaceOnUse"><stop class="mt9k2qzvi"/><stop offset="1" class="fx1tjiblm"/></radialGradient><radialGradient id="iRAhcoC" cx="0" cy="0" r="1" gradientTransform="matrix(1.57845 -.11741 .09178 1.2339 21.432 14.153)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="l__dw9bpv"/><stop offset="1" class="wrh2b4bbx"/></radialGradient><radialGradient id="iE3Lc9b" cx="0" cy="0" r="1" gradientTransform="rotate(-180 6.015 7.018)scale(1.10391)" gradientUnits="userSpaceOnUse"><stop offset=".722" class="o3wo53bzp"/><stop offset="1" class="eo_7g0bzd"/></radialGradient><radialGradient id="igKhlYi" cx="0" cy="0" r="1" gradientTransform="matrix(-6.79886 3.13518 -4.19638 -9.10015 19.83 13.474)" gradientUnits="userSpaceOnUse"><stop class="crj44uotj"/><stop offset="1" class="yamoh3dov"/></radialGradient><radialGradient id="ifhq5Kd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.27927 1.00295 -.69844 -1.58725 18.901 14.367)" gradientUnits="userSpaceOnUse"><stop class="up8l18w-p"/><stop offset="1" class="ai95fabuh"/></radialGradient><radialGradient id="iDSMHsb" cx="0" cy="0" r="1" gradientTransform="rotate(-71.832 21.288 .073)scale(4.3222 5.48407)" gradientUnits="userSpaceOnUse"><stop class="osxg47drp"/><stop offset="1" class="da7h3oe0u"/></radialGradient><radialGradient id="iciCm2b" cx="0" cy="0" r="1" gradientTransform="matrix(-1.343 7.70795 -9.63484 -1.67874 17.91 13.039)" gradientUnits="userSpaceOnUse"><stop offset=".637" class="mg10me7tz"/><stop offset="1" class="kitn3twkh"/></radialGradient><radialGradient id="if9Itpc" cx="0" cy="0" r="1" gradientTransform="matrix(-7.2192 1.41674 -2.4392 -12.42922 18.733 15.284)" gradientUnits="userSpaceOnUse"><stop offset=".795" class="opgioqbtx"/><stop offset="1" class="wg3eepbwp"/></radialGradient><radialGradient id="iTyEpdc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.20302 1.47643 0 19.247 13.037)" gradientUnits="userSpaceOnUse"><stop class="t9k87pm2r"/><stop offset="1" class="ax9af2vtk"/></radialGradient><radialGradient id="iFasDQb" cx="0" cy="0" r="1" gradientTransform="scale(1.57252 1.37211)rotate(-90 9.328 0)" gradientUnits="userSpaceOnUse"><stop class="x_ik4kbfh"/><stop offset="1" class="gcfqr7bfg"/></radialGradient><radialGradient id="iB3SbtO" cx="0" cy="0" r="1" gradientTransform="rotate(105.092 5.077 12.312)scale(3.49375 2.79558)" gradientUnits="userSpaceOnUse"><stop class="uj7hgsb3u"/><stop offset="1" class="p88c31myn"/></radialGradient><radialGradient id="iEnifqe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.34364 0 0 -6.73822 22.168 14.592)" gradientUnits="userSpaceOnUse"><stop class="zoq8fuaif"/><stop offset="1" class="ycrcotb4u"/></radialGradient><radialGradient id="igJE5bd" cx="0" cy="0" r="1" gradientTransform="rotate(-121.569 15.768 3.968)scale(1.59124 1.69084)" gradientUnits="userSpaceOnUse"><stop class="ni-4se4rm"/><stop offset="1" class="wsh5tsbcf"/></radialGradient><radialGradient id="iTx2zgd" cx="0" cy="0" r="1" gradientTransform="matrix(1.82947 -1.63343 1.93949 2.17225 12.622 19.463)" gradientUnits="userSpaceOnUse"><stop class="z26rrllgi"/><stop offset="1" class="fs9pa7bci"/></radialGradient><radialGradient id="i2CAQEe" cx="0" cy="0" r="1" gradientTransform="matrix(-.47623 -2.13682 .65854 -.14677 17.662 15.35)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="bof3uzbpf"/><stop offset="1" class="jaf6nfbfs"/></radialGradient><radialGradient id="i5zICgd" cx="0" cy="0" r="1" gradientTransform="matrix(-.81479 0 0 -.22779 17.41 15.572)" gradientUnits="userSpaceOnUse"><stop class="bof3uzbpf"/><stop offset="1" class="jaf6nfbfs"/></radialGradient><radialGradient id="iaxiavb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .84815 -1.34908 0 19.122 13.411)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="ikGZJQd" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 12.748 2.125)scale(.39546 .54446)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i6YWBKc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .84816 -1.34909 0 14.56 13.411)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iwBScIe" cx="0" cy="0" r="1" gradientTransform="matrix(-.00809 -.51649 .62084 -.00972 14.262 13.64)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iMwhdrV" cx="0" cy="0" r="1" gradientTransform="matrix(-5.5 4.12501 -3.615 -4.82 20.719 4.576)" gradientUnits="userSpaceOnUse"><stop offset=".179" class="tg07-ljnl"/><stop offset="1" class="c6833cb9x"/></radialGradient><radialGradient id="i3dSYhb" cx="0" cy="0" r="1" gradientTransform="matrix(2.875 .375 -.58342 4.4729 10.781 7.701)" gradientUnits="userSpaceOnUse"><stop class="j8k1fac_p"/><stop offset="1" class="g8uem1b5g"/></radialGradient><radialGradient id="inl9J2c" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.875 8.03906 0 16.773 8.326)" gradientUnits="userSpaceOnUse"><stop offset=".761" class="km6q7kb1a"/><stop offset="1" class="i8skpb2jz"/></radialGradient><radialGradient id="iCE2gke" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.47656 -8.28125 0 18.406 7.912)" gradientUnits="userSpaceOnUse"><stop class="kzuil_5zu"/><stop offset="1" class="ok2r3obil"/></radialGradient><radialGradient id="ixSAAAe" cx="0" cy="0" r="1" gradientTransform="matrix(-7.1875 0 0 -.63281 21.269 9.87)" gradientUnits="userSpaceOnUse"><stop class="w63qn2bkh"/><stop offset="1" class="vvfum-_fa"/></radialGradient><radialGradient id="iy7tjOa" cx="0" cy="0" r="1" gradientTransform="matrix(3.48438 0 0 2.01172 9.003 10.109)" gradientUnits="userSpaceOnUse"><stop class="gfrsedb9v"/><stop offset="1" class="vke6kh8bt"/></radialGradient><filter id="i6TXXde" width="15.95" height="16.45" x="8.991" y="4.37" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.121569 0 0 0 0 0.0705882 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23850"/></filter><filter id="iPpnG1c" width="21.247" height="10.303" x="6.25" y="19.623" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.615686 0 0 0 0 0.607843 0 0 0 0 0.619608 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23850"/></filter><filter id="i4ahPBd" width="2.078" height="2.078" x="15.622" y="27.457" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.792157 0 0 0 0 0.717647 0 0 0 0 0.788235 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_3987_23850"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_3987_23850" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.831373 0 0 0 0 0.745098 0 0 0 0 0.803922 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_3987_23850"/></filter><filter id="iLm34Bc" width="2.078" height="2.078" x="15.622" y="25.444" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.792157 0 0 0 0 0.717647 0 0 0 0 0.788235 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_3987_23850"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_3987_23850" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.831373 0 0 0 0 0.745098 0 0 0 0 0.803922 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_3987_23850"/></filter><filter id="ioS9k1B" width="6.532" height="3.647" x="13.675" y="19.523" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.721569 0 0 0 0 0.682353 0 0 0 0 0.74902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23850"/></filter><filter id="iXkUIDd" width="7.432" height="4.46" x="12.567" y="22.084" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23850" stdDeviation=".5"/></filter><filter id="iEdTYLd" width="2.672" height="2.865" x="13.611" y="22.403" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.780392 0 0 0 0 0.270588 0 0 0 0 0.396078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23850"/></filter><filter id="iRytQJb" width="2.672" height="2.865" x="17.264" y="22.403" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.780392 0 0 0 0 0.270588 0 0 0 0 0.396078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23850"/></filter><filter id="iVbsgBe" width="1.554" height="1.999" x="15.986" y="22.812" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.827451 0 0 0 0 0.137255 0 0 0 0 0.317647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23850"/></filter><filter id="iPJZ6bc" width="4.764" height="4.766" x="24.75" y="19.349" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.1"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.462745 0 0 0 0 0.282353 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23850"/></filter><filter id="ilMkEFq" width="2.077" height="3.844" x="25.907" y="17.448" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.431373 0 0 0 0 0.282353 0 0 0 0 0.247059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23850"/></filter><filter id="iGWJPWc" width="2.401" height="4.052" x="24.436" y="17.107" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.431373 0 0 0 0 0.282353 0 0 0 0 0.247059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23850"/></filter><filter id="iAi37ic" width="2.312" height="4.044" x="23.386" y="17.96" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.431373 0 0 0 0 0.282353 0 0 0 0 0.247059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23850"/></filter><filter id="iSAGrbe" width="2.123" height="3.114" x="22.394" y="19.041" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.431373 0 0 0 0 0.282353 0 0 0 0 0.247059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23850"/></filter><filter id="iHShkKc" width="3.002" height="3.147" x="6.649" y="16.347" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.431373 0 0 0 0 0.262745 0 0 0 0 0.219608 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23850"/></filter><filter id="i75yEkb" width="1.264" height="2.491" x="22.908" y="19.19" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23850" stdDeviation=".125"/></filter><filter id="imTnI4d" width="1.286" height="2.978" x="23.933" y="18.124" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23850" stdDeviation=".125"/></filter><filter id="iWWyMTb" width="1.444" height="3.775" x="24.963" y="17.226" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23850" stdDeviation=".125"/></filter><filter id="iGbRvDl" width="1.17" height="3.014" x="26.424" y="17.706" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23850" stdDeviation=".125"/></filter><filter id="iQYzp7b" width="1.788" height="2.6" x="27.33" y="19.87" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23850" stdDeviation=".125"/></filter><filter id="irfvnPe" width="2.323" height="1.69" x="3.752" y="19.44" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23850" stdDeviation=".125"/></filter><filter id="iCbvYbS" width="2.342" height="2.022" x="3.291" y="18.151" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23850" stdDeviation=".125"/></filter><filter id="iQeDutc" width="2.131" height="2.124" x="4.556" y="16.714" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23850" stdDeviation=".125"/></filter><filter id="iR87did" width="2.569" height="2.444" x="3.345" y="17.042" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23850" stdDeviation=".125"/></filter><filter id="iPijCCe" width="5.441" height="3.076" x="17.747" y="6.733" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23850" stdDeviation=".375"/></filter><filter id="iDQjIYd" width="5.461" height="3.084" x="17.805" y="6.608" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23850" stdDeviation=".375"/></filter><filter id="iZ21R8d" width="3.514" height="3.364" x="10.261" y="12.354" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.509804 0 0 0 0 0.376471 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23850"/></filter><filter id="ica6vKq" width="3.364" height="3.614" x="20.205" y="12.104" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.431373 0 0 0 0 0.243137 0 0 0 0 0.282353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23850"/></filter><filter id="iD5A4de" width="3.246" height="3.246" x="20.265" y="12.413" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23850" stdDeviation=".25"/></filter><filter id="itQTwLQ" width="2.746" height="2.746" x="10.59" y="12.663" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23850" stdDeviation=".125"/></filter><filter id="iHhgXDc" width="10.654" height="11.621" x="11.514" y="8.906" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".175"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.407843 0 0 0 0 0.223529 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23850"/></filter><filter id="ijb1bXb" width="2.962" height="3.803" x="15.19" y="13.008" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23850" stdDeviation=".25"/></filter><filter id="iwfjMiE" width="2.462" height="3.303" x="15.61" y="13.113" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23850" stdDeviation=".125"/></filter><filter id="i1XCKKe" width="3.852" height="1.577" x="14.915" y="16.5" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23850" stdDeviation=".05"/></filter><filter id="iHxbfZd" width="3.129" height="1.344" x="17.835" y="12.567" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0941176 0 0 0 0 0.0666667 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23850"/></filter><filter id="idE1IGc" width="3.129" height="1.344" x="12.719" y="12.567" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0862745 0 0 0 0 0.054902 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23850"/></filter><filter id="i2A3Psb" width="2.555" height="1.131" x="12.86" y="11.088" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.164706 0 0 0 0 0.0901961 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23850"/></filter><filter id="iPo63db" width="2.555" height="1.132" x="18.523" y="11.088" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.164706 0 0 0 0 0.0901961 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23850"/></filter><filter id="i5OmKkb" width=".813" height=".719" x="18.36" y="12.956" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23850" stdDeviation=".05"/></filter><filter id="iIXDGpO" width=".914" height=".937" x="19.242" y="13.039" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23850" stdDeviation=".1"/></filter><filter id="iUFAmcc" width="1.013" height="1.069" x="14.597" y="12.973" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23850" stdDeviation=".1"/></filter><filter id="i9jjJMe" width=".945" height=".727" x="13.804" y="12.948" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23850" stdDeviation=".05"/></filter><filter id="iz1EVvc" width="2.336" height=".995" x="18.569" y="11.22" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23850" stdDeviation=".1"/></filter><filter id="iSr1ZAb" width="2.336" height=".995" x="12.87" y="11.22" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23850" stdDeviation=".1"/></filter><filter id="ik2mr4b" width="1.169" height="2.387" x="13.518" y="6.897" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23850" stdDeviation=".1"/></filter><filter id="iFhQS9d" width="7.151" height="3.957" x="16.017" y="7.512" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23850" stdDeviation=".5"/></filter><linearGradient id="iMgry4c" x1="21.747" x2="14.633" y1="6.767" y2="19.944" gradientUnits="userSpaceOnUse"><stop class="c1nwhtznm"/><stop offset="1" class="ogqxd-bue"/></linearGradient><linearGradient id="iK84mBb" x1="22.562" x2="21.812" y1="29.826" y2="29.826" gradientUnits="userSpaceOnUse"><stop class="fr__qmhjc"/><stop offset="1" class="gypp10kih"/></linearGradient><linearGradient id="iWCiqKd" x1="20.644" x2="21.062" y1="29.014" y2="29.014" gradientUnits="userSpaceOnUse"><stop class="hj-s-zboe"/><stop offset="1" class="s0umluqbl"/></linearGradient><linearGradient id="ipodSkc" x1="9.531" x2="4.906" y1="27.451" y2="27.451" gradientUnits="userSpaceOnUse"><stop class="sb-ednb_a"/><stop offset="1" class="v0501vbqa"/></linearGradient><linearGradient id="iXPTZOc" x1="9.75" x2="8.828" y1="27.076" y2="27.076" gradientUnits="userSpaceOnUse"><stop class="o_30au2yc"/><stop offset="1" class="c60cvac3k"/></linearGradient><linearGradient id="itP1zjc" x1="27.871" x2="22.844" y1="28.142" y2="28.142" gradientUnits="userSpaceOnUse"><stop class="i7zyuv8vr"/><stop offset=".907" class="qzhltkbuo"/></linearGradient><linearGradient id="i33ZCUz" x1="28.09" x2="27.168" y1="27.876" y2="27.876" gradientUnits="userSpaceOnUse"><stop class="tub8lbbfx"/><stop offset="1" class="bd09vtb_c"/></linearGradient><linearGradient id="i8tJXGc" x1="16.763" x2="16.763" y1="22.812" y2="24.81" gradientUnits="userSpaceOnUse"><stop offset=".351" class="gzsz7evmk"/><stop offset="1" class="smgiue0gi"/></linearGradient><linearGradient id="imI15oe" x1="29.13" x2="28.38" y1="20.034" y2="21.659" gradientUnits="userSpaceOnUse"><stop class="au5hixbak"/><stop offset="1" class="mcp_a12ev"/><stop offset="1" class="i4lia-rzw"/></linearGradient><linearGradient id="iamKure" x1="4.76" x2="5.331" y1="20.169" y2="21.223" gradientUnits="userSpaceOnUse"><stop class="a86-seumw"/><stop offset="1" class="u5lbkrb_x"/></linearGradient><linearGradient id="iGhB53d" x1="4.307" x2="5.218" y1="19" y2="20.223" gradientUnits="userSpaceOnUse"><stop class="a86-seumw"/><stop offset="1" class="u5lbkrb_x"/></linearGradient><linearGradient id="ixXGBre" x1="5.489" x2="6.52" y1="17.6" y2="18.693" gradientUnits="userSpaceOnUse"><stop class="a86-seumw"/><stop offset="1" class="u5lbkrb_x"/></linearGradient><linearGradient id="iVKoQ5f" x1="4.452" x2="5.734" y1="18.044" y2="19.502" gradientUnits="userSpaceOnUse"><stop class="a86-seumw"/><stop offset="1" class="u5lbkrb_x"/></linearGradient><linearGradient id="iOHqgze" x1="10.314" x2="11.611" y1="14.127" y2="14.127" gradientUnits="userSpaceOnUse"><stop class="b9k-3ybvb"/><stop offset="1" class="vbw-bobru"/></linearGradient><linearGradient id="iILntki" x1="16.841" x2="16.841" y1="10.472" y2="12.159" gradientUnits="userSpaceOnUse"><stop class="fncfq6bkz"/><stop offset="1" class="ab-x4ir6t"/></linearGradient><linearGradient id="iBHYztc" x1="15.86" x2="16.841" y1="15.427" y2="15.427" gradientUnits="userSpaceOnUse"><stop class="rby1z7ber"/><stop offset="1" class="dl0nwov2w"/></linearGradient><linearGradient id="iUkk53H" x1="16.841" x2="16.841" y1="16.263" y2="15.625" gradientUnits="userSpaceOnUse"><stop class="cyl8wapbv"/><stop offset="1" class="jplc2lvem"/></linearGradient><linearGradient id="iVRqHob" x1="15.729" x2="16.21" y1="17.736" y2="16.992" gradientUnits="userSpaceOnUse"><stop class="lwz87437z"/><stop offset=".663" class="c7jfumw-i"/></linearGradient><linearGradient id="iEwUv5t" x1="19.936" x2="19.608" y1="13.468" y2="13.67" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iMr32Vb" x1="15.338" x2="15.009" y1="13.468" y2="13.67" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iIMpJGb" x1="13.818" x2="14.388" y1="7.556" y2="8.888" gradientUnits="userSpaceOnUse"><stop class="z66p5h_5k"/><stop offset="1" class="ll4sw0vun"/></linearGradient><linearGradient id="izP9Z9c" x1="16.773" x2="16.773" y1="7.912" y2="8.1" gradientUnits="userSpaceOnUse"><stop class="jhlen960d"/><stop offset="1" class="wjchuwb6a"/></linearGradient><linearGradient id="iYE2hsb" x1="17.956" x2="17.956" y1="10.98" y2="10.214" gradientUnits="userSpaceOnUse"><stop class="bl3fq0x9z"/><stop offset="1" class="lxo7c2i6k"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-juggling-medium-dark" /></template>
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

.ab-x4ir6t {
  stop-color: var(--svg-color--683a42, #683A42);
  stop-opacity: 0;
}

.ab6i82btp {
  stop-color: var(--svg-color--e7377c, #E7377C);
}

.af8mzdbwl {
  stop-color: var(--svg-color--5f679a, #5F679A);
}

.ai95fabuh {
  stop-color: var(--svg-color--986b5a, #986B5A);
  stop-opacity: 0;
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

.ax9af2vtk {
  stop-color: var(--svg-color--875555, #875555);
  stop-opacity: 0;
}

.b057dp4eh {
  stop-color: var(--svg-color--ccbdde, #CCBDDE);
}

.b9-qm444s {
  stop-color: var(--svg-color--784b52, #784B52);
  stop-opacity: 0;
}

.b9k-3ybvb {
  stop-color: var(--svg-color--6a4745, #6A4745);
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

.be39v8b_v {
  fill: var(--svg-color--88014f, #88014F);
  d: path("M16.841 17.08a3.2 3.2 0 0 1-1.486-.36c-.147-.077-.305.092-.212.229a2.02 2.02 0 0 0 3.397 0c.092-.143-.066-.306-.213-.23c-.43.23-.936.36-1.486.36");
}

.bl3fq0x9z {
  stop-color: var(--svg-color--543459, #543459);
}

.bl7uysvvb {
  stop-color: var(--svg-color--181518, #181518);
}

.bo6_cwbgw {
  stop-color: var(--svg-color--693443, #693443);
}

.bof3uzbpf {
  stop-color: var(--svg-color--a07a6f, #A07A6F);
}

.bq5dgsbba {
  stop-color: var(--svg-color--dcc8ec, #DCC8EC);
}

.btor07b8q {
  stop-color: var(--svg-color--d61f4d, #D61F4D);
}

.bxaqvnd6d {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M16.841 17.08a3.2 3.2 0 0 1-1.486-.36c-.147-.077-.305.092-.212.229a2.02 2.02 0 0 0 3.397 0c.092-.143-.066-.306-.213-.23c-.43.23-.936.36-1.486.36Z");
}

.byn6wubog {
  fill: var(--svg-color--bc9ebb, #BC9EBB);
  fill-rule: evenodd;
  d: path("M16.899 24.871a.35.35 0 0 1-.266.244c-.25.048-.467.048-.717 0a.35.35 0 0 1-.262-.23c-.18.2-.49.432-1.009.607c-.31.106-.668.058-.833-.23a1.86 1.86 0 0 1-.245-.948c0-.431.124-.74.245-.95c.165-.287.523-.334.833-.23c.503.171.81.418.993.63a.35.35 0 0 1 .278-.293c.25-.048.467-.048.717 0a.35.35 0 0 1 .28.31c.18-.215.49-.47 1.008-.646c.31-.105.668-.058.834.23c.12.208.244.513.244.949s-.124.74-.244.949c-.166.287-.524.335-.834.23c-.531-.18-.844-.42-1.022-.622");
}

.c1nwhtznm {
  stop-color: var(--svg-color--45363a, #45363A);
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

.c9_6uxbfa {
  stop-color: var(--svg-color--4a4446, #4A4446);
  stop-opacity: 0;
}

.ccf6axbtk {
  d: path("M11.943 15.718a1.682 1.682 0 1 0 0-3.364a1.682 1.682 0 0 0 0 3.364");
}

.chj8m5e2t {
  stop-color: var(--svg-color--040101, #040101);
  stop-opacity: 0;
}

.ci3gi1b_k {
  stop-color: var(--svg-color--784b89, #784B89);
  stop-opacity: 0;
}

.cj4rfmfkx {
  stop-color: var(--svg-color--3b3638, #3B3638);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.crj44uotj {
  stop-color: var(--svg-color--996b5e, #996B5E);
}

.ctsppjbax {
  d: path("M14.866 22.463c.91.308 1.268.83 1.389 1.082l.028.29l-.028.359c-.12.25-.48.706-1.389 1.014c-.36.123-.777.068-.97-.267a2.17 2.17 0 0 1-.285-1.105c0-.502.144-.862.285-1.106c.193-.335.61-.39.97-.267");
}

.ctupw6b3d {
  fill-rule: evenodd;
  d: path("M3.113 18.184a.75.75 0 0 1 1.042.196c.312.455.974 1.204 1.85 1.204a.75.75 0 1 1 0 1.5c-1.702 0-2.759-1.376-3.088-1.858a.75.75 0 0 1 .196-1.042");
}

.cyl8wapbv {
  stop-color: var(--svg-color--7c455c, #7C455C);
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

.da7h3oe0u {
  stop-color: var(--svg-color--743f5a, #743F5A);
  stop-opacity: 0;
}

.demkpcl0k {
  stop-color: var(--svg-color--b1a0b8, #B1A0B8);
}

.dl0nwov2w {
  stop-color: var(--svg-color--744c45, #744C45);
  stop-opacity: 0;
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

.e-twaac7b {
  stop-color: var(--svg-color--575455, #575455);
  stop-opacity: 0;
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.emrugab1j {
  stop-color: var(--svg-color--84665d, #84665D);
}

.eo_7g0bzd {
  stop-color: var(--svg-color--5a3638, #5A3638);
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

.fi7wz1bec {
  fill: var(--svg-color--845f59, #845F59);
  d: path("M21.887 15.158a1.123 1.123 0 1 0 0-2.245a1.123 1.123 0 0 0 0 2.245");
}

.fncfq6bkz {
  stop-color: var(--svg-color--683a42, #683A42);
}

.fr__qmhjc {
  stop-color: var(--svg-color--7a6cad, #7A6CAD);
}

.fs9pa7bci {
  stop-color: var(--svg-color--6e494b, #6E494B);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fx1tjiblm {
  stop-color: var(--svg-color--755041, #755041);
  stop-opacity: 0;
}

.fzq016boz {
  stop-color: var(--svg-color--e35838, #E35838);
}

.g0r7omboq {
  stop-color: var(--svg-color--474445, #474445);
  stop-opacity: 0;
}

.g4d0dvb3l {
  d: path("M14.558 12.913a.933.933 0 0 0-.9 1.178h1.803a1 1 0 0 0 .034-.245a.94.94 0 0 0-.937-.933");
}

.g8uem1b5g {
  stop-color: var(--svg-color--38303e, #38303E);
  stop-opacity: 0;
}

.gcfqr7bfg {
  stop-color: var(--svg-color--714350, #714350);
  stop-opacity: 0;
}

.gfrsedb9v {
  stop-color: var(--svg-color--5b595e, #5B595E);
}

.glo437b-m {
  stop-color: var(--svg-color--040002, #040002);
  stop-opacity: 0;
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

.gypp10kih {
  stop-color: var(--svg-color--7a6cad, #7A6CAD);
  stop-opacity: 0;
}

.gz5tj9apj {
  d: path("M19.125 12.913a.933.933 0 0 1 .899 1.178H18.22a.937.937 0 0 1 .903-1.179");
}

.gzsz7evmk {
  stop-color: var(--svg-color--eb3782, #EB3782);
}

.h1ngowbkc {
  fill: var(--svg-color--352827, #352827);
  d: path("m13.289 12.177l-.005.003a.28.28 0 0 1-.288-.481l.002-.001l.003-.002l.01-.006l.034-.019q.044-.024.12-.061c.104-.05.25-.112.43-.17a2.9 2.9 0 0 1 1.388-.113a.28.28 0 1 1-.097.552a2.4 2.4 0 0 0-1.121.096a3 3 0 0 0-.476.202");
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

.hirfvzj6c {
  d: path("M20.007 20.045a10.2 10.2 0 0 0-2.913-.422h-.641c-.963 0-1.895.133-2.778.383l.602 3.164h4.945z");
}

.hj-s-zboe {
  stop-color: var(--svg-color--6d5096, #6D5096);
}

.hkormb2xp {
  stop-color: var(--svg-color--575455, #575455);
}

.hpeo8yzih {
  stop-color: var(--svg-color--9d7e72, #9D7E72);
}

.hpfqe6rjh {
  cx: 6.332px;
  cy: 12.838px;
  r: 1.684px;
}

.ht6lpfbpp {
  d: path("M18.68 22.463c-.909.308-1.267.83-1.388 1.082l-.028.29l.028.359c.12.25.48.706 1.388 1.014c.362.123.778.068.971-.267c.14-.243.284-.599.284-1.105c0-.507-.144-.862-.284-1.106c-.193-.335-.61-.39-.97-.267");
}

.hvtb3cbit {
  d: path("m16.441 13.658l-.555 1.777a.564.564 0 0 0 .544.731h.822a.566.566 0 0 0 .544-.73l-.555-1.778c-.12-.394-.675-.394-.8 0");
}

.hw860-bkw {
  d: path("M22.993 22.213c.119.463.586 1.456.805 1.894h4.047l-.258-3.789l-4.836.924c.031.13.123.507.242.97");
}

.hx66smwtj {
  stop-color: var(--svg-color--4a4446, #4A4446);
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

.i7zyuv8vr {
  stop-color: var(--svg-color--ede7f3, #EDE7F3);
}

.i8j0jyb4u {
  stop-color: var(--svg-color--b8a734, #B8A734);
}

.i8skpb2jz {
  stop-color: var(--svg-color--5d5565, #5D5565);
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

.jaf6nfbfs {
  stop-color: var(--svg-color--a07a6f, #A07A6F);
  stop-opacity: 0;
}

.jhlen960d {
  stop-color: var(--svg-color--745ba5, #745BA5);
}

.jjf293xlz {
  stop-color: var(--svg-color--d61f4d, #D61F4D);
  stop-opacity: 0;
}

.jk5udqbyz {
  stop-color: var(--svg-color--464444, #464444);
  stop-opacity: 0;
}

.jm40s5baz {
  stop-color: var(--svg-color--968f9c, #968F9C);
  stop-opacity: 0;
}

.jplc2lvem {
  stop-color: var(--svg-color--7c455c, #7C455C);
  stop-opacity: 0;
}

.kbl3igr5c {
  stop-color: var(--svg-color--040002, #040002);
}

.kitn3twkh {
  stop-color: var(--svg-color--5f363f, #5F363F);
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

.kzuil_5zu {
  stop-color: var(--svg-color--9072ca, #9072CA);
}

.l__dw9bpv {
  stop-color: var(--svg-color--7d4d48, #7D4D48);
  stop-opacity: 0;
}

.l-r9gxb9g {
  stop-color: var(--svg-color--4bb8fb, #4BB8FB);
}

.l0xg-rbdf {
  stop-color: var(--svg-color--040101, #040101);
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
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

.lgi0lwbjz {
  stop-color: var(--svg-color--775184, #775184);
  stop-opacity: 0;
}

.lgjudcrkd {
  stop-color: var(--svg-color--413733, #413733);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lk_cbyb-c {
  stop-color: var(--svg-color--784b52, #784B52);
}

.ll4sw0vun {
  stop-color: var(--svg-color--24182d, #24182D);
}

.lm_8kobga {
  fill: var(--svg-color--8a6058, #8A6058);
  d: path("m16.441 13.658l-.555 1.777a.564.564 0 0 0 .544.731h.822a.566.566 0 0 0 .544-.73l-.555-1.778c-.12-.394-.675-.394-.8 0");
}

.lu7irnbsv {
  fill: var(--svg-color--7e595a, #7E595A);
  d: path("M24.458 17.959a.68.68 0 0 1 .568-.843l.023-.003a.68.68 0 0 1 .756.54l.622 3.039c.071.355-.246.42-.606.458c-.303.032-.553-.005-.629-.3z");
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

.mg10me7tz {
  stop-color: var(--svg-color--794958, #794958);
  stop-opacity: 0;
}

.mm17qbboc {
  fill: var(--svg-color--fff, #fff);
  d: path("M19.34 12.629c.683 0 1.26.47 1.417 1.107a.287.287 0 0 1-.28.356h-2.332a.24.24 0 0 1-.238-.284c.132-.67.721-1.18 1.434-1.18");
}

.mmq2utbuk {
  stop-color: var(--svg-color--cf8b51, #CF8B51);
}

.mpwbs5b3u {
  stop-color: var(--svg-color--ff894e, #FF894E);
}

.mrj68fbtn {
  cx: 14.277px;
  cy: 13.311px;
  rx: 0.407px;
  ry: 0.206px;
}

.mt9k2qzvi {
  stop-color: var(--svg-color--755041, #755041);
}

.mxnnm4bur {
  stop-color: var(--svg-color--464444, #464444);
}

.n297mkbnr {
  stop-color: var(--svg-color--d6d3d7, #D6D3D7);
  stop-opacity: 0;
}

.ng1cexbhj {
  stop-color: var(--svg-color--b6424c, #B6424C);
}

.ni-4se4rm {
  stop-color: var(--svg-color--836462, #836462);
}

.ninyoac7q {
  fill: var(--svg-color--272528, #272528);
  d: path("M15.648 13.44c-.278-.487-.7-.873-1.607-.873c-.398 0-.781.11-1.122.386c-.281.227-.243.518-.026.626l.582.332c.681-.22 1.435-.25 2.173-.47");
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

.o3wo53bzp {
  stop-color: var(--svg-color--5a3638, #5A3638);
  stop-opacity: 0;
}

.o415o878f {
  stop-color: var(--svg-color--ef4c8b, #EF4C8B);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ogqxd-bue {
  stop-color: var(--svg-color--1c151f, #1C151F);
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

.olqyf7fmb {
  stop-color: var(--svg-color--875e5e, #875E5E);
}

.opgioqbtx {
  stop-color: var(--svg-color--805c54, #805C54);
  stop-opacity: 0;
}

.osnazwkth {
  d: path("M21.887 15.718a1.682 1.682 0 1 0 0-3.364a1.682 1.682 0 0 0 0 3.364");
}

.osxg47drp {
  stop-color: var(--svg-color--743f5a, #743F5A);
}

.p22s-zbfq {
  stop-color: var(--svg-color--77455b, #77455B);
  stop-opacity: 0;
}

.p88c31myn {
  stop-color: var(--svg-color--815a5b, #815A5B);
  stop-opacity: 0;
}

.paonnib9g {
  stop-color: var(--svg-color--474445, #474445);
}

.pb6efmson {
  stop-color: var(--svg-color--d72c5e, #D72C5E);
}

.pdv9cyg6v {
  fill: var(--svg-color--000, #000);
  d: path("M15.093 13.846a.53.53 0 0 0-.535-.534a.532.532 0 0 0-.475.78h.946a.5.5 0 0 0 .063-.246");
}

.pfu0f9xgl {
  stroke: var(--svg-color--473c3c, #473C3C);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M14.906 11.555c-.338-.082-1.176-.04-1.737.36");
}

.phhy_ubqp {
  stroke: var(--svg-color--997971, #997971);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-35px, 0.35px);
  d: path("m25.388 17.65l.594 2.926");
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

.pwun67v-k {
  fill: var(--svg-color--000, #000);
  d: path("M18.59 13.846c0-.297.238-.534.535-.534a.532.532 0 0 1 .474.78h-.945a.5.5 0 0 1-.064-.246");
}

.qjbq_nb5a {
  stop-color: var(--svg-color--9e7c73, #9E7C73);
}

.qr8h38bcf {
  stop-color: var(--svg-color--826052, #826052);
}

.qsu4qbckq {
  stop-color: var(--svg-color--dbcdd4, #DBCDD4);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qwp4ni-tf {
  stop-color: var(--svg-color--171418, #171418);
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

.r_g462bwu {
  fill: var(--svg-color--7e595a, #7E595A);
  d: path("M22.414 19.88a.68.68 0 1 1 1.33-.293l.36 1.793a.645.645 0 0 1-1.26.28z");
}

.r_v2kebuk {
  stop-color: var(--svg-color--181518, #181518);
  stop-opacity: 0;
}

.rby1z7ber {
  stop-color: var(--svg-color--744c45, #744C45);
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

.rv0ymrbfc {
  fill: var(--svg-color--352827, #352827);
  fill-rule: evenodd;
  d: path("m20.742 11.699l-.144.24za.28.28 0 0 1-.288.48l-.005-.002l-.023-.013l-.095-.048a3 3 0 0 0-.358-.141a2.4 2.4 0 0 0-1.12-.096a.28.28 0 0 1-.098-.552c.536-.095 1.033 0 1.389.114a3.4 3.4 0 0 1 .584.25l.01.005l.002.002z");
}

.s0umluqbl {
  stop-color: var(--svg-color--7160a4, #7160A4);
  stop-opacity: 0;
}

.s1xedwb9e {
  stroke: var(--svg-color--473c3c, #473C3C);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M18.869 11.555c.337-.082 1.176-.04 1.736.36");
}

.sawf8hb2n {
  stop-color: var(--svg-color--ef4c8b, #EF4C8B);
  stop-opacity: 0;
}

.sb-ednb_a {
  stop-color: var(--svg-color--ece4f4, #ECE4F4);
}

.sbauxibsu {
  d: path("M11.523 12.716h.013l-.011-.277l-.011-.32c.022-.992.6-1.376.847-1.504l.054-.022l.053-.021a2.4 2.4 0 0 0 1.244-1.29l.085-.203a.276.276 0 0 1 .483-.054a4.04 4.04 0 0 0 3.334 1.75h3.366c.188 0 1.131.091 1.188 1.392l-.124 3.213c-.13 2.93-2.417 4.897-5.21 4.897s-5.08-1.967-5.21-4.897z");
}

.scbqttb8d {
  stop-color: var(--svg-color--ec4182, #EC4182);
}

.silozpblh {
  stop-color: var(--svg-color--3b3638, #3B3638);
  stop-opacity: 0;
}

.sirm6td-l {
  stop-color: var(--svg-color--784759, #784759);
}

.smgiue0gi {
  stop-color: var(--svg-color--c93857, #C93857);
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

.t9k87pm2r {
  stop-color: var(--svg-color--875555, #875555);
}

.tg07-ljnl {
  stop-color: var(--svg-color--5e5764, #5E5764);
}

.tl2m9zb9f {
  d: path("M11.963 15.158a1.123 1.123 0 1 0 0-2.246a1.123 1.123 0 0 0 0 2.246");
}

.tn_97qkdc {
  stop-color: var(--svg-color--f2c341, #F2C341);
  stop-opacity: 0;
}

.to0rgu7go {
  d: path("M19.956 13.723a.9.9 0 0 0-.242-.484l-.272.298l.123.239z");
}

.tr7czpf3k {
  stop-color: var(--svg-color--413733, #413733);
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

.txvhrnh2c {
  cx: 14.277px;
  cy: 13.311px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.407px;
  ry: 0.206px;
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

.uaba6iq6u {
  d: path("M21.887 15.158a1.123 1.123 0 1 0 0-2.245a1.123 1.123 0 0 0 0 2.245");
}

.uj7hgsb3u {
  stop-color: var(--svg-color--815a5b, #815A5B);
}

.ujrq6ixuu {
  stop-color: var(--svg-color--beb4c6, #BEB4C6);
}

.umfbmkqyq {
  fill: var(--svg-color--70404a, #70404A);
  d: path("m16.43 13.803l-.714 1.777a.564.564 0 0 0 .545.731h.822a.566.566 0 0 0 .544-.73l-.556-1.778c-.119-.394-.515-.394-.64 0");
}

.up8l18w-p {
  stop-color: var(--svg-color--986b5a, #986B5A);
}

.uqr6xg6is {
  stop-color: var(--svg-color--7f5552, #7F5552);
}

.uw0_1wnpi {
  fill-rule: evenodd;
  d: path("M24.353 15.51a3.4 3.4 0 0 0 .338-1.492c0-.489-.1-.947-.28-1.365h.005a3.3 3.3 0 0 0-.294-.537l-.002-.003a3.4 3.4 0 0 1-.55-1.851v-.01c0-.805-1.781-.256-2.243-.843c-.632-.802-.106-2.607-1.206-2.607a.56.56 0 0 1-.476-.243A3.46 3.46 0 0 0 16.84 5.12c-1.153 0-2.18.571-2.804 1.439a.59.59 0 0 1-.476.243l-.089.001c-1.226.031-1.125 2.054-1.712 3.043c-.305.515-1.648-.236-1.648.405v.01c0 .657-.19 1.302-.55 1.852l-.002.004a3.45 3.45 0 0 0-.23 3.392a.54.54 0 0 1 0 .476a3.4 3.4 0 0 0-.339 1.47a3.36 3.36 0 0 0 3.364 3.365h8.972a3.36 3.36 0 0 0 3.364-3.364c0-.53-.127-1.026-.338-1.47a.54.54 0 0 1 0-.477m-12.817-2.794h-.013l1.253 2.462c.129 2.93 1.272 0 4.065 0s4.01 3.261 4.14.331l1.187-3.342c-.056-1.301-1-1.393-1.188-1.393h-3.366c-1.33 0-2.583-.65-3.334-1.749a.276.276 0 0 0-.482.053l-.086.203a2.4 2.4 0 0 1-1.244 1.29l-.053.022l-.054.021c-.246.128-.825.512-.847 1.504l.011.32z");
}

.v0501vbqa {
  stop-color: var(--svg-color--c0b5cd, #C0B5CD);
}

.v6yq82b7v {
  fill: var(--svg-color--47383d, #47383D);
  d: path("m19.357 9.665l-1.49.274a.72.72 0 1 1-.131-1.427h2.447c1.447 0 1.926 1.459 1.985 1.957a3.29 3.29 0 0 0-2.811-.804");
}

.vbw-bobru {
  stop-color: var(--svg-color--533335, #533335);
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

.vpo725bhk {
  fill: var(--svg-color--5f3c45, #5F3C45);
  d: path("M11.963 15.158a1.123 1.123 0 1 0 0-2.246a1.123 1.123 0 0 0 0 2.246");
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

.vwf3t2b2u {
  d: path("M14.83 18.331c0-.99.9-1.794 2.011-1.794s2.012.803 2.012 1.794v2.326c0 .99-.9 1.794-2.012 1.794c-1.11 0-2.012-.803-2.012-1.794z");
}

.w63qn2bkh {
  stop-color: var(--svg-color--605966, #605966);
}

.wfgw5ub6b {
  fill-rule: evenodd;
  d: path("M4.273 16.754a.75.75 0 0 1 1.042.196q.091.134.166.258c.141.228.267.432.519.637c.292.238.794.485 1.747.42a.75.75 0 1 1 .102 1.497c-1.29.088-2.178-.25-2.796-.754c-.478-.389-.78-.89-.917-1.116l-.059-.096a.75.75 0 0 1 .196-1.042");
}

.wg3eepbwp {
  stop-color: var(--svg-color--805c54, #805C54);
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

.wrh2b4bbx {
  stop-color: var(--svg-color--7d4d48, #7D4D48);
}

.wsh5tsbcf {
  stop-color: var(--svg-color--836462, #836462);
  stop-opacity: 0;
}

.wshx69b-y {
  stop-color: var(--svg-color--896bb4, #896BB4);
}

.x_ik4kbfh {
  stop-color: var(--svg-color--714350, #714350);
}

.x1l7xqbyw {
  stop-color: var(--svg-color--de5534, #DE5534);
  stop-opacity: 0;
}

.xdn388byj {
  stop-color: var(--svg-color--171418, #171418);
}

.xkn2wzmus {
  stop-color: var(--svg-color--7e595a, #7E595A);
}

.xntzq-4ho {
  stop-color: var(--svg-color--8566b5, #8566B5);
}

.xojd46bcr {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M13.818 7.197c.025.254.245 1.209.57 1.787");
}

.xuioilrmd {
  fill: var(--svg-color--2d2b2e, #2D2B2E);
  d: path("M18.035 13.44c.278-.487.7-.873 1.607-.873c.398 0 .781.11 1.122.386c.28.227.243.518.026.626l-.582.332c-.681-.22-1.435-.25-2.173-.47");
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

.y0z9-1vnj {
  d: path("M19.056 13.11c.066.09-.072.197-.23.316c-.158.118-.276.2-.342.112c-.067-.089.008-.257.166-.375s.34-.142.406-.053");
}

.y2ly1lryk {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-35px, 0.35px);
  d: path("M3.716 18.576c.177.245.672.953 1.492 1.172");
}

.yamoh3dov {
  stop-color: var(--svg-color--764e4c, #764E4C);
}

.ycrcotb4u {
  stop-color: var(--svg-color--986f60, #986F60);
  stop-opacity: 0;
}

.ykzqhbcyt {
  stop-color: var(--svg-color--997067, #997067);
}

.ym-b_m9fy {
  stop-color: var(--svg-color--d1bed4, #D1BED4);
  stop-opacity: 0;
}

.z26rrllgi {
  stop-color: var(--svg-color--6e494b, #6E494B);
}

.z66p5h_5k {
  stop-color: var(--svg-color--1a1316, #1A1316);
}

.zd45hpjnr {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M19.056 13.11c.066.09-.072.197-.23.316c-.158.118-.276.2-.342.112c-.067-.089.008-.257.166-.375s.34-.142.406-.053");
}

.zdcorrl9x {
  cx: 26.234px;
  cy: 14.83px;
  r: 1.684px;
}

.zjwhzkbez {
  d: path("M15.41 13.736c0-.301-.245-.502-.311-.563l-.302.291l.186.378z");
}

.zoq8fuaif {
  stop-color: var(--svg-color--986f60, #986F60);
}

.zr5faibop {
  fill: var(--svg-color--fff, #fff);
  d: path("M14.341 12.629c-.682 0-1.26.47-1.416 1.107a.287.287 0 0 0 .28.356h2.332a.24.24 0 0 0 .238-.284a1.465 1.465 0 0 0-1.434-1.18");
}

</style>
