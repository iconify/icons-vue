<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#i21fOWe)"><path fill="url(#i4C5tJe)" clip-rule="evenodd" class="bb8jc-j1w"/><path fill="url(#iFN5fGd)" clip-rule="evenodd" class="bb8jc-j1w"/><path fill="url(#i0PEvEb)" clip-rule="evenodd" class="bb8jc-j1w"/><path fill="url(#iu29iMN)" clip-rule="evenodd" class="bb8jc-j1w"/><path fill="url(#iAtOdsb)" clip-rule="evenodd" class="bb8jc-j1w"/><path fill="url(#i987Odb)" clip-rule="evenodd" class="bb8jc-j1w"/><path fill="url(#ivqMLIb)" clip-rule="evenodd" class="bb8jc-j1w"/><path fill="url(#iaV161b)" clip-rule="evenodd" class="bb8jc-j1w"/><path fill="url(#i5BO8Td)" clip-rule="evenodd" class="bb8jc-j1w"/><path fill="url(#iD73tqb)" clip-rule="evenodd" class="bb8jc-j1w"/><path fill="url(#i2EHy5X)" clip-rule="evenodd" class="bb8jc-j1w"/></g><g filter="url(#iLYb1Xb)"><path fill="url(#iPYYWhe)" class="swka_j87x"/><path fill="url(#iT07jwd)" class="swka_j87x"/><path fill="url(#il5eVUq)" class="swka_j87x"/><path fill="url(#iY3yYtd)" class="swka_j87x"/><path fill="url(#iv8FoOX)" class="swka_j87x"/></g><circle fill="url(#iBZ0RUd)" class="hpfqe6rjh"/><circle fill="url(#itKlKTd)" class="hpfqe6rjh"/><circle fill="url(#ihlr5IT)" class="duyhuibwk"/><circle fill="url(#iGUmgWd)" class="duyhuibwk"/><circle fill="url(#iXhqZHd)" class="iwbygtbvw"/><circle fill="url(#iOHvRJe)" class="iwbygtbvw"/><circle fill="url(#issuNue)" class="zdcorrl9x"/><circle fill="url(#iMaLBhb)" class="zdcorrl9x"/><circle fill="url(#iAhrvZc)" class="zdcorrl9x"/><g filter="url(#ixmnZWr)"><circle fill="url(#iMk8UMb)" class="t-5nldk3g"/></g><g filter="url(#i9LD6re)"><circle fill="url(#iR23Gge)" class="don2wdpjw"/></g><path fill="url(#i5YvaPc)" class="j70rp9pis"/><path fill="url(#iK84mBb)" class="j70rp9pis"/><path fill="url(#iWCiqKd)" class="j70rp9pis"/><path fill="url(#ieol8Me)" class="qy4rrcb8b"/><path fill="url(#iDbbcbc)" class="qy4rrcb8b"/><path fill="url(#iOe2zrd)" class="qy4rrcb8b"/><path fill="url(#iV71Rbc)" class="qy4rrcb8b"/><g filter="url(#iwGD7ud)"><path fill="url(#ih8Nxde)" class="arh302van"/><path fill="url(#iQpTAtb)" class="arh302van"/></g><path fill="url(#ipodSkc)" class="f21vmbcik"/><path fill="url(#iXPTZOc)" class="f21vmbcik"/><path fill="url(#itP1zjc)" class="wp2p6dbcv"/><path fill="url(#i33ZCUz)" class="wp2p6dbcv"/><g filter="url(#isOldVb)"><path clip-rule="evenodd" class="byn6wubog"/></g><g filter="url(#i8GJS7X)"><path fill="url(#iSAsI1d)" class="ctsppjbax"/><path fill="url(#iwtPTOo)" class="ctsppjbax"/><path fill="url(#isAdhHe)" class="ctsppjbax"/></g><g filter="url(#ic8bGfb)"><path fill="url(#ivLP6Gc)" class="ht6lpfbpp"/><path fill="url(#iXetYud)" class="ht6lpfbpp"/></g><g filter="url(#iccsWMe)"><path fill="url(#i8tJXGc)" class="ld_83jb7a"/><path fill="url(#iw9bnJb)" class="ld_83jb7a"/></g><g filter="url(#ilbhIle)"><path class="sh7m4tbex"/></g><g filter="url(#i0Fho3b)"><path class="htooq-bzz"/></g><g filter="url(#iUWNzom)"><path class="dtaunfmfd"/></g><g filter="url(#iu4zlHc)"><path class="cz19hw0vg"/></g><g filter="url(#igM6I7w)"><path class="h28q1nbvc"/></g><path fill="url(#iaWvCHb)" class="hw860-bkw"/><path fill="url(#iHqXrTb)" class="hw860-bkw"/><path fill="url(#iKOvVob)" class="hw860-bkw"/><g filter="url(#iXrzBPA)"><path fill="url(#iZRDtQc)" class="u5bjt8cdp"/></g><path fill="url(#i5T5fHd)" clip-rule="evenodd" class="wfgw5ub6b"/><path fill="url(#itdLitT)" clip-rule="evenodd" class="wfgw5ub6b"/><path fill="url(#iMq80zd)" clip-rule="evenodd" class="d5_x4xk7i"/><path fill="url(#i3YGs4L)" clip-rule="evenodd" class="d5_x4xk7i"/><path fill="url(#ihieIdl)" clip-rule="evenodd" class="ctupw6b3d"/><path fill="url(#iFQkc1c)" clip-rule="evenodd" class="ctupw6b3d"/><path fill="url(#ioOhupe)" clip-rule="evenodd" class="vdngsab5t"/><path fill="url(#ifr9kzc)" clip-rule="evenodd" class="vdngsab5t"/><path fill="url(#iTt0qwc)" class="twba206ho"/><path fill="url(#i9lIzkb)" class="twba206ho"/><path fill="url(#iwkimxQ)" class="wp2dqucie"/><g filter="url(#i9ihvZE)"><path class="ndapliy4h"/></g><g filter="url(#iMCf9pe)"><path class="arn591bff"/></g><g filter="url(#ireKNKe)"><path class="s76rkqhqi"/></g><g filter="url(#iErm7Pd)"><path class="hhnbdw1mn"/></g><g filter="url(#iIUcmeb)"><path stroke="url(#ijG10yh)" class="bdk4dmb5b"/></g><g filter="url(#iyqinHd)"><path stroke="url(#i9IIrXd)" class="gwm_2mjil"/></g><g filter="url(#iy6GIMg)"><path stroke="url(#i8TsYWd)" class="y2ly1lryk"/></g><g filter="url(#i6QO16b)"><path stroke="url(#imTyYGd)" class="am6k_ubte"/></g><g filter="url(#iRbXige)"><path stroke="url(#ikSuYlc)" class="c549xi8ae"/></g><g filter="url(#iqyKwhe)"><path fill="url(#iKNW15b)" class="ogxz6h-st"/></g><g filter="url(#ipsgJ5c)"><path fill="url(#i2hz8Me)" class="tbmfqptqo"/><path fill="url(#iarmGre)" class="tbmfqptqo"/></g><g filter="url(#iJuPptJ)"><path class="q2yo0ybkp"/><path fill="url(#it1OQFe)" class="m87o_mhtw"/></g><g filter="url(#iGHBoBe)"><path class="vjdrhubcm"/><path fill="url(#i7zaA5b)" class="lsx269bcs"/></g><g filter="url(#iRMPGPb)"><path fill="url(#i6HqOvA)" class="y2ea22zwh"/><path fill="url(#iO7mIGe)" class="y2ea22zwh"/><path fill="url(#iTG6JPD)" class="y2ea22zwh"/><path fill="url(#iLDySBc)" class="y2ea22zwh"/><path fill="url(#izvvk1b)" class="y2ea22zwh"/><path fill="url(#inyOzqc)" class="y2ea22zwh"/><path fill="url(#iZOQQNd)" class="y2ea22zwh"/></g><path fill="url(#iEtzWQc)" class="y2ea22zwh"/><path fill="url(#ij4jQ2I)" class="y2ea22zwh"/><path fill="url(#ihRBYHb)" class="y2ea22zwh"/><g filter="url(#ikxVmXe)"><path class="nnonv9b0l"/></g><g filter="url(#iEFK4Zb)"><path class="lh1q57nmq"/><path fill="url(#iH4MQNb)" class="j--0dbbee"/><path fill="url(#idUWGEc)" class="j--0dbbee"/><path fill="url(#i2xcffd)" class="j--0dbbee"/><path fill="url(#iPFaMwb)" class="j--0dbbee"/></g><g filter="url(#inMwY2d)"><path stroke="url(#ihGOajb)" class="lp_0y5ggb"/></g><path class="tou4lf01r"/><g filter="url(#idQMvte)"><path class="n302v8i1b"/></g><g filter="url(#iqIeJDd)"><path class="ped5v8nqh"/></g><g filter="url(#iKIiwnf)"><path class="mt9jhjbax"/></g><g filter="url(#iUzneAb)"><path clip-rule="evenodd" class="r6y4i1b2t"/></g><path class="ue219ybxm"/><path fill="url(#i7yHq7d)" class="obqipxbwg"/><path class="eyusp0blq"/><g filter="url(#iqurHMM)"><path class="b7w777b-n"/><path fill="url(#i3yhqYb)" class="ofoeipbcd"/></g><g filter="url(#ipzLEvb)"><path fill="url(#ikj3Tad)" class="b3bgf45aw"/></g><path class="jus1k8bhb"/><path fill="url(#iIN3vwd)" class="flu_1vdvd"/><path class="hd554kb0x"/><g filter="url(#ivo5ZAV)"><path fill="url(#ibntPCF)" class="q15yln0fl"/></g><g filter="url(#iNEIGyd)"><ellipse transform="rotate(-27.914 14.104 13.575)" class="k9fawxbmc"/><ellipse fill="url(#igHdhrA)" transform="rotate(-27.914 14.104 13.575)" class="ljv4u1xrn"/></g><g filter="url(#i0yvwMe)"><path class="oirt5lbzg"/></g><g filter="url(#iXxcZdd)"><path class="td2qu3khi"/></g><g filter="url(#iIzONlu)"><path stroke="url(#iDDSyGe)" class="o-tanhhbh"/></g><g filter="url(#iW7XHfQ)"><path class="ytdkz2bln"/></g><path fill="url(#iMwhdrV)" class="qzd219blo"/><path fill="url(#i3dSYhb)" class="qzd219blo"/><path fill="url(#inl9J2c)" class="qzd219blo"/><path fill="url(#iCE2gke)" class="wozepxbaa"/><path fill="url(#izP9Z9c)" class="wozepxbaa"/><rect fill="url(#ixSAAAe)" class="okwd93kys"/><rect fill="url(#iy7tjOa)" class="okwd93kys"/><rect fill="url(#iYE2hsb)" class="okwd93kys"/><defs><radialGradient id="iFN5fGd" cx="0" cy="0" r="1" gradientTransform="rotate(97.539 .765 15.623)scale(4.80763 6.00571)" gradientUnits="userSpaceOnUse"><stop offset=".591" class="xdn388byj"/><stop offset="1" class="qwp4ni-tf"/></radialGradient><radialGradient id="i0PEvEb" cx="0" cy="0" r="1" gradientTransform="rotate(146.004 4.077 10.647)scale(3.63527 4.77645)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="bl7uysvvb"/><stop offset="1" class="r_v2kebuk"/></radialGradient><radialGradient id="iu29iMN" cx="0" cy="0" r="1" gradientTransform="rotate(127.405 2.212 10.133)scale(2.24996 1.72766)" gradientUnits="userSpaceOnUse"><stop offset=".334" class="l0xg-rbdf"/><stop offset="1" class="chj8m5e2t"/></radialGradient><radialGradient id="iAtOdsb" cx="0" cy="0" r="1" gradientTransform="rotate(121.43 2.559 9.592)scale(2.58744 1.82262)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="kbl3igr5c"/><stop offset="1" class="glo437b-m"/></radialGradient><radialGradient id="i987Odb" cx="0" cy="0" r="1" gradientTransform="rotate(62.272 1.632 13.688)scale(3.08811 4.28676)" gradientUnits="userSpaceOnUse"><stop class="paonnib9g"/><stop offset="1" class="g0r7omboq"/></radialGradient><radialGradient id="ivqMLIb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.50683 1.50693 -2.1059 -2.10576 22.767 8.047)" gradientUnits="userSpaceOnUse"><stop class="hx66smwtj"/><stop offset="1" class="c9_6uxbfa"/></radialGradient><radialGradient id="iaV161b" cx="0" cy="0" r="1" gradientTransform="matrix(-1.92737 .56072 -1.16934 -4.01938 24.519 13.409)" gradientUnits="userSpaceOnUse"><stop class="cj4rfmfkx"/><stop offset="1" class="silozpblh"/></radialGradient><radialGradient id="i5BO8Td" cx="0" cy="0" r="1" gradientTransform="rotate(165.963 10.899 9.962)scale(3.03427 3.8652)" gradientUnits="userSpaceOnUse"><stop class="mxnnm4bur"/><stop offset="1" class="jk5udqbyz"/></radialGradient><radialGradient id="iD73tqb" cx="0" cy="0" r="1" gradientTransform="rotate(-108.843 14.694 -2.3)scale(2.92748 2.31547)" gradientUnits="userSpaceOnUse"><stop class="hkormb2xp"/><stop offset="1" class="e-twaac7b"/></radialGradient><radialGradient id="i2EHy5X" cx="0" cy="0" r="1" gradientTransform="matrix(1.5722 .16491 -.2672 2.54742 10.248 13.37)" gradientUnits="userSpaceOnUse"><stop class="lgjudcrkd"/><stop offset="1" class="tr7czpf3k"/></radialGradient><radialGradient id="iPYYWhe" cx="0" cy="0" r="1" gradientTransform="rotate(135.22 8.643 15.887)scale(12.9545 12.5552)" gradientUnits="userSpaceOnUse"><stop offset=".195" class="m-1-e5bla"/><stop offset=".794" class="b057dp4eh"/></radialGradient><radialGradient id="iT07jwd" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.09375 -3.28125 0 20.219 20.139)" gradientUnits="userSpaceOnUse"><stop class="m9gf32bwp"/><stop offset="1" class="n297mkbnr"/></radialGradient><radialGradient id="il5eVUq" cx="0" cy="0" r="1" gradientTransform="matrix(-1.75 0 0 -11.7187 21 25.92)" gradientUnits="userSpaceOnUse"><stop offset=".214" class="demkpcl0k"/><stop offset="1" class="ym-b_m9fy"/></radialGradient><radialGradient id="iY3yYtd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.15625 0 0 -5.75902 11.656 25.326)" gradientUnits="userSpaceOnUse"><stop class="ujrq6ixuu"/><stop offset="1" class="h4mko5b9o"/></radialGradient><radialGradient id="iv8FoOX" cx="0" cy="0" r="1" gradientTransform="matrix(2.12502 5.34374 -11.023 4.38346 13.099 18.733)" gradientUnits="userSpaceOnUse"><stop class="nl0wbpawx"/><stop offset="1" class="jm40s5baz"/></radialGradient><radialGradient id="iBZ0RUd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.34375 2.4375 -2.36069 -1.3014 7.187 11.826)" gradientUnits="userSpaceOnUse"><stop offset=".077" class="l-r9gxb9g"/><stop offset="1" class="hcmh5c50b"/></radialGradient><radialGradient id="itKlKTd" cx="0" cy="0" r="1" gradientTransform="rotate(115.145 -.151 8.247)scale(3.38309 2.95533)" gradientUnits="userSpaceOnUse"><stop offset=".452" class="y-1rsmdul"/><stop offset=".826" class="af8mzdbwl"/></radialGradient><radialGradient id="ihlr5IT" cx="0" cy="0" r="1" gradientTransform="matrix(-1.34375 2.4375 -2.36069 -1.3014 10.101 2.846)" gradientUnits="userSpaceOnUse"><stop offset=".077" class="mpwbs5b3u"/><stop offset="1" class="fzq016boz"/></radialGradient><radialGradient id="iGUmgWd" cx="0" cy="0" r="1" gradientTransform="rotate(115.145 4.158 4.683)scale(3.38309 2.95533)" gradientUnits="userSpaceOnUse"><stop offset=".452" class="x1l7xqbyw"/><stop offset=".826" class="ng1cexbhj"/></radialGradient><radialGradient id="iXhqZHd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.34375 2.4375 -2.36069 -1.3014 26.066 3.861)" gradientUnits="userSpaceOnUse"><stop offset=".077" class="lelj2r8dg"/><stop offset="1" class="fde_fwzpt"/></radialGradient><radialGradient id="iOHvRJe" cx="0" cy="0" r="1" gradientTransform="rotate(105.03 11.36 11.751)scale(3.49455 3.40391)" gradientUnits="userSpaceOnUse"><stop offset=".375" class="ppr920emc"/><stop offset=".826" class="y_auwli2s"/></radialGradient><radialGradient id="issuNue" cx="0" cy="0" r="1" gradientTransform="matrix(-1.34375 2.4375 -2.36069 -1.3014 27.09 13.818)" gradientUnits="userSpaceOnUse"><stop offset=".077" class="y05rrkbkk"/><stop offset="1" class="a5zzorbzd"/></radialGradient><radialGradient id="iMaLBhb" cx="0" cy="0" r="1" gradientTransform="matrix(1 1.07812 -1.5877 1.47265 24.969 13.357)" gradientUnits="userSpaceOnUse"><stop class="i8j0jyb4u"/><stop offset="1" class="d7caiobkz"/></radialGradient><radialGradient id="iAhrvZc" cx="0" cy="0" r="1" gradientTransform="rotate(109.11 8.51 16.52)scale(3.46022 3.37046)" gradientUnits="userSpaceOnUse"><stop offset=".347" class="tn_97qkdc"/><stop offset=".829" class="mmq2utbuk"/></radialGradient><radialGradient id="iMk8UMb" cx="0" cy="0" r="1" gradientTransform="matrix(-.7578 1.14063 -.96756 -.64282 17.25 27.855)" gradientUnits="userSpaceOnUse"><stop offset=".212" class="u6lph46no"/><stop offset="1" class="bq5dgsbba"/></radialGradient><radialGradient id="iR23Gge" cx="0" cy="0" r="1" gradientTransform="matrix(-.7578 1.14063 -.96756 -.64282 17.25 25.842)" gradientUnits="userSpaceOnUse"><stop offset=".212" class="u6lph46no"/><stop offset="1" class="bq5dgsbba"/></radialGradient><radialGradient id="i5YvaPc" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.03125 -2.40212 0 22.222 20.983)" gradientUnits="userSpaceOnUse"><stop class="koq0r9bvu"/><stop offset="1" class="dpmuo-biy"/></radialGradient><radialGradient id="ieol8Me" cx="0" cy="0" r="1" gradientTransform="scale(1.38818 6.1875)rotate(90 2.761 6.5)" gradientUnits="userSpaceOnUse"><stop class="xntzq-4ho"/><stop offset="1" class="pt8frltpn"/></radialGradient><radialGradient id="iDbbcbc" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.25 -.60938 0 13.062 24.108)" gradientUnits="userSpaceOnUse"><stop class="wshx69b-y"/><stop offset="1" class="aqzyd8bsb"/></radialGradient><radialGradient id="iOe2zrd" cx="0" cy="0" r="1" gradientTransform="matrix(2.9375 -7.98881 7.06186 2.59666 10.312 28.264)" gradientUnits="userSpaceOnUse"><stop offset=".724" class="lgi0lwbjz"/><stop offset="1" class="tvoyviyhj"/></radialGradient><radialGradient id="iV71Rbc" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.42188 -.18506 0 12.857 21.717)" gradientUnits="userSpaceOnUse"><stop class="m5avsc_ef"/><stop offset="1" class="ci3gi1b_k"/></radialGradient><radialGradient id="ih8Nxde" cx="0" cy="0" r="1" gradientTransform="matrix(-3.90624 2.42972 -4.28692 -6.89204 19.265 20.795)" gradientUnits="userSpaceOnUse"><stop class="ku63lg_wt"/><stop offset="1" class="i1-orb7ke"/></radialGradient><radialGradient id="iQpTAtb" cx="0" cy="0" r="1" gradientTransform="matrix(-.46875 -.125 .54686 -2.05079 19.188 22.482)" gradientUnits="userSpaceOnUse"><stop offset=".108" class="qsu4qbckq"/><stop offset="1" class="gr0wzobbs"/></radialGradient><radialGradient id="iSAsI1d" cx="0" cy="0" r="1" gradientTransform="matrix(1.73878 1.3451 -1.47727 1.90964 13.775 23.358)" gradientUnits="userSpaceOnUse"><stop class="ab6i82btp"/><stop offset="1" class="pb6efmson"/></radialGradient><radialGradient id="iwtPTOo" cx="0" cy="0" r="1" gradientTransform="matrix(-1.68958 -.4774 .79459 -2.81214 15.416 23.836)" gradientUnits="userSpaceOnUse"><stop offset=".69" class="sawf8hb2n"/><stop offset="1" class="o415o878f"/></radialGradient><radialGradient id="isAdhHe" cx="0" cy="0" r="1" gradientTransform="matrix(-.5 1.58457 -.75053 -.23683 16.11 23.836)" gradientUnits="userSpaceOnUse"><stop class="btor07b8q"/><stop offset="1" class="jjf293xlz"/></radialGradient><radialGradient id="ivLP6Gc" cx="0" cy="0" r="1" gradientTransform="rotate(142.275 5.895 15.056)scale(2.19833 2.41434)" gradientUnits="userSpaceOnUse"><stop class="auvn9fbbk"/><stop offset="1" class="h2li0wblg"/></radialGradient><radialGradient id="iXetYud" cx="0" cy="0" r="1" gradientTransform="matrix(1.68958 -.4774 .79459 2.81214 18.13 23.836)" gradientUnits="userSpaceOnUse"><stop offset=".69" class="sawf8hb2n"/><stop offset="1" class="o415o878f"/></radialGradient><radialGradient id="iw9bnJb" cx="0" cy="0" r="1" gradientTransform="matrix(-.39136 0 0 -2.59279 17.54 23.592)" gradientUnits="userSpaceOnUse"><stop class="scbqttb8d"/><stop offset="1" class="u1gl_1zha"/></radialGradient><radialGradient id="iaWvCHb" cx="0" cy="0" r="1" gradientTransform="matrix(-4.375 1.44046 -1.3893 -4.21963 28.098 22.456)" gradientUnits="userSpaceOnUse"><stop offset=".241" class="f6slf6w2m"/><stop offset="1" class="p5eexwbyw"/></radialGradient><radialGradient id="iHqXrTb" cx="0" cy="0" r="1" gradientTransform="rotate(163.091 11.838 12.97)scale(3.90165 13.4872)" gradientUnits="userSpaceOnUse"><stop offset=".699" class="byihu8b7s"/><stop offset="1" class="l1l6vcdra"/></radialGradient><radialGradient id="iKOvVob" cx="0" cy="0" r="1" gradientTransform="matrix(.21875 1.02588 -2.1162 .45124 25.583 20.534)" gradientUnits="userSpaceOnUse"><stop offset=".134" class="nqrf57zsi"/><stop offset="1" class="wrgoaxbaa"/></radialGradient><radialGradient id="iZRDtQc" cx="0" cy="0" r="1" gradientTransform="rotate(139.97 1.2 10.48)scale(1.53045 3.638)" gradientUnits="userSpaceOnUse"><stop offset=".129" class="utcasbb3u"/><stop offset="1" class="ww1jp2brw"/></radialGradient><radialGradient id="i5T5fHd" cx="0" cy="0" r="1" gradientTransform="matrix(-.79386 1.27188 -2.4349 -1.51978 6.442 17.553)" gradientUnits="userSpaceOnUse"><stop class="jzs0qy57r"/><stop offset="1" class="g9xx7math"/></radialGradient><radialGradient id="itdLitT" cx="0" cy="0" r="1" gradientTransform="matrix(-.73037 2.48832 -3.82658 -1.12318 6.977 17.288)" gradientUnits="userSpaceOnUse"><stop offset=".579" class="txbqaun0d"/><stop offset=".954" class="xm9fbaccy"/></radialGradient><radialGradient id="iMq80zd" cx="0" cy="0" r="1" gradientTransform="rotate(116.602 -3.017 10.55)scale(1.58621 2.70684)" gradientUnits="userSpaceOnUse"><stop class="jzs0qy57r"/><stop offset="1" class="g9xx7math"/></radialGradient><radialGradient id="i3YGs4L" cx="0" cy="0" r="1" gradientTransform="matrix(-.65347 2.77477 -3.52334 -.82977 5.545 17.677)" gradientUnits="userSpaceOnUse"><stop offset=".579" class="txbqaun0d"/><stop offset=".954" class="xm9fbaccy"/></radialGradient><radialGradient id="ihieIdl" cx="0" cy="0" r="1" gradientTransform="matrix(-.68468 1.22288 -2.2217 -1.2439 4.939 18.947)" gradientUnits="userSpaceOnUse"><stop class="jzs0qy57r"/><stop offset="1" class="g9xx7math"/></radialGradient><radialGradient id="iFQkc1c" cx="0" cy="0" r="1" gradientTransform="rotate(104.751 -4.503 11.427)scale(2.474 3.46652)" gradientUnits="userSpaceOnUse"><stop offset=".579" class="txbqaun0d"/><stop offset=".954" class="xm9fbaccy"/></radialGradient><radialGradient id="ioOhupe" cx="0" cy="0" r="1" gradientTransform="rotate(122.692 -2.834 11.406)scale(1.24393 2.40994)" gradientUnits="userSpaceOnUse"><stop class="jzs0qy57r"/><stop offset="1" class="g9xx7math"/></radialGradient><radialGradient id="ifr9kzc" cx="0" cy="0" r="1" gradientTransform="matrix(-.61813 2.04813 -3.22394 -.973 5.687 19.733)" gradientUnits="userSpaceOnUse"><stop offset=".579" class="txbqaun0d"/><stop offset=".954" class="xm9fbaccy"/></radialGradient><radialGradient id="iTt0qwc" cx="0" cy="0" r="1" gradientTransform="rotate(-162.011 6.48 10.137)scale(3.69324 5.10277)" gradientUnits="userSpaceOnUse"><stop class="sheftacio"/><stop offset=".644" class="vbn8f2bra"/></radialGradient><radialGradient id="i9lIzkb" cx="0" cy="0" r="1" gradientTransform="matrix(.07812 -.82813 3.88844 .36683 6.156 21.78)" gradientUnits="userSpaceOnUse"><stop class="khemg5bhx"/><stop offset="1" class="e7777ub0x"/></radialGradient><radialGradient id="iwkimxQ" cx="0" cy="0" r="1" gradientTransform="matrix(1.6875 2.24809 -2.56376 1.92445 16.099 20.289)" gradientUnits="userSpaceOnUse"><stop offset=".252" class="cg9m3ci5c"/><stop offset="1" class="ux87x8bpy"/></radialGradient><radialGradient id="i2hz8Me" cx="0" cy="0" r="1" gradientTransform="matrix(1.90994 -2.12896 2.59936 2.33194 21.382 15.32)" gradientUnits="userSpaceOnUse"><stop offset=".444" class="w--6bgeqj"/><stop offset=".944" class="sheftacio"/></radialGradient><radialGradient id="iarmGre" cx="0" cy="0" r="1" gradientTransform="matrix(1.3755 .77098 -.21797 .38888 21.969 12.542)" gradientUnits="userSpaceOnUse"><stop class="ynae43ovp"/><stop offset="1" class="v-9tn59hb"/></radialGradient><radialGradient id="it1OQFe" cx="0" cy="0" r="1" gradientTransform="matrix(1.57845 -.11741 .09178 1.2339 21.26 14.417)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="k2oqpgb0o"/><stop offset="1" class="dkw8bsvxv"/></radialGradient><radialGradient id="i7zaA5b" cx="0" cy="0" r="1" gradientTransform="matrix(-1.26161 0 0 -.99525 11.859 14.3)" gradientUnits="userSpaceOnUse"><stop offset=".667" class="b55qklbsj"/><stop offset="1" class="uaoaczbhz"/></radialGradient><radialGradient id="i6HqOvA" cx="0" cy="0" r="1" gradientTransform="matrix(-6.79886 3.13518 -4.19638 -9.10015 19.657 13.738)" gradientUnits="userSpaceOnUse"><stop class="v5rheyc4i"/><stop offset="1" class="wum9l96_j"/></radialGradient><radialGradient id="iO7mIGe" cx="0" cy="0" r="1" gradientTransform="rotate(172.574 9.542 8.232)scale(3.64892 4.02776)" gradientUnits="userSpaceOnUse"><stop class="z-rzt8b_f"/><stop offset="1" class="tk20gvbnd"/></radialGradient><radialGradient id="iTG6JPD" cx="0" cy="0" r="1" gradientTransform="matrix(1.36674 -3.96004 5.02456 1.73414 14.18 21.4)" gradientUnits="userSpaceOnUse"><stop class="fvm07vbkd"/><stop offset="1" class="n1w64orcn"/></radialGradient><radialGradient id="iLDySBc" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.02999 -8.13748 0 16.669 13.51)" gradientUnits="userSpaceOnUse"><stop offset=".567" class="vrhnsgvqh"/><stop offset="1" class="iuch0hb0l"/></radialGradient><radialGradient id="izvvk1b" cx="0" cy="0" r="1" gradientTransform="matrix(-7.2192 1.41674 -2.4392 -12.42922 18.56 15.547)" gradientUnits="userSpaceOnUse"><stop offset=".795" class="brg8dbpny"/><stop offset="1" class="d_t8kfbgb"/></radialGradient><radialGradient id="inyOzqc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.20302 1.47643 0 19.074 13.3)" gradientUnits="userSpaceOnUse"><stop class="e2earo80w"/><stop offset="1" class="xl9xm7bnj"/></radialGradient><radialGradient id="iZOQQNd" cx="0" cy="0" r="1" gradientTransform="scale(1.57252 1.37211)rotate(-90 9.37 .15)" gradientUnits="userSpaceOnUse"><stop class="suybu51ug"/><stop offset="1" class="intda8ekf"/></radialGradient><radialGradient id="iEtzWQc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.34586 0 0 -6.73822 27.12 12.8)" gradientUnits="userSpaceOnUse"><stop class="sqxrh1b6n"/><stop offset="1" class="eodwsybla"/></radialGradient><radialGradient id="ij4jQ2I" cx="0" cy="0" r="1" gradientTransform="rotate(71.806 6.01 16.172)scale(4.40168 7.67846)" gradientUnits="userSpaceOnUse"><stop class="f_q-3cc4h"/><stop offset="1" class="s44y8_wdc"/></radialGradient><radialGradient id="iH4MQNb" cx="0" cy="0" r="1" gradientTransform="matrix(-.47623 -2.13682 .65854 -.14677 17.489 15.614)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="xbgj88f0b"/><stop offset="1" class="y_9l2i5ww"/></radialGradient><radialGradient id="iPFaMwb" cx="0" cy="0" r="1" gradientTransform="matrix(-.81479 0 0 -.22779 17.238 15.836)" gradientUnits="userSpaceOnUse"><stop class="qpkqxibzk"/><stop offset="1" class="nwt8glb0m"/></radialGradient><radialGradient id="i7yHq7d" cx="0" cy="0" r="1" gradientTransform="matrix(0 .84815 -1.34908 0 18.95 13.675)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="i3yhqYb" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 12.726 2.3)scale(.39546 .54446)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iIN3vwd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .84816 -1.34909 0 14.388 13.675)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="igHdhrA" cx="0" cy="0" r="1" gradientTransform="matrix(-.00809 -.51649 .62084 -.00972 14.088 13.904)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iMwhdrV" cx="0" cy="0" r="1" gradientTransform="matrix(-5.5 4.12501 -3.615 -4.82 20.719 4.576)" gradientUnits="userSpaceOnUse"><stop offset=".179" class="tg07-ljnl"/><stop offset="1" class="c6833cb9x"/></radialGradient><radialGradient id="i3dSYhb" cx="0" cy="0" r="1" gradientTransform="matrix(2.875 .375 -.58342 4.4729 10.781 7.701)" gradientUnits="userSpaceOnUse"><stop class="j8k1fac_p"/><stop offset="1" class="g8uem1b5g"/></radialGradient><radialGradient id="inl9J2c" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.875 8.03906 0 16.773 8.326)" gradientUnits="userSpaceOnUse"><stop offset=".761" class="km6q7kb1a"/><stop offset="1" class="i8skpb2jz"/></radialGradient><radialGradient id="iCE2gke" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.47656 -8.28125 0 18.406 7.912)" gradientUnits="userSpaceOnUse"><stop class="kzuil_5zu"/><stop offset="1" class="ok2r3obil"/></radialGradient><radialGradient id="ixSAAAe" cx="0" cy="0" r="1" gradientTransform="matrix(-7.1875 0 0 -.63281 21.269 9.87)" gradientUnits="userSpaceOnUse"><stop class="w63qn2bkh"/><stop offset="1" class="vvfum-_fa"/></radialGradient><radialGradient id="iy7tjOa" cx="0" cy="0" r="1" gradientTransform="matrix(3.48438 0 0 2.01172 9.003 10.109)" gradientUnits="userSpaceOnUse"><stop class="gfrsedb9v"/><stop offset="1" class="vke6kh8bt"/></radialGradient><filter id="i21fOWe" width="15.95" height="16.45" x="8.819" y="4.634" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.121569 0 0 0 0 0.0705882 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23859"/></filter><filter id="iLYb1Xb" width="21.247" height="10.303" x="6.25" y="19.623" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.615686 0 0 0 0 0.607843 0 0 0 0 0.619608 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23859"/></filter><filter id="ixmnZWr" width="2.078" height="2.078" x="15.622" y="27.457" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.792157 0 0 0 0 0.717647 0 0 0 0 0.788235 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_3987_23859"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_3987_23859" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.831373 0 0 0 0 0.745098 0 0 0 0 0.803922 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_3987_23859"/></filter><filter id="i9LD6re" width="2.078" height="2.078" x="15.622" y="25.444" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.792157 0 0 0 0 0.717647 0 0 0 0 0.788235 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_3987_23859"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_3987_23859" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.831373 0 0 0 0 0.745098 0 0 0 0 0.803922 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_3987_23859"/></filter><filter id="iwGD7ud" width="6.563" height="3.702" x="13.395" y="19.523" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.721569 0 0 0 0 0.682353 0 0 0 0 0.74902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23859"/></filter><filter id="isOldVb" width="7.432" height="4.46" x="12.567" y="22.084" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23859" stdDeviation=".5"/></filter><filter id="i8GJS7X" width="2.672" height="2.865" x="13.611" y="22.403" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.780392 0 0 0 0 0.270588 0 0 0 0 0.396078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23859"/></filter><filter id="ic8bGfb" width="2.672" height="2.865" x="17.264" y="22.403" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.780392 0 0 0 0 0.270588 0 0 0 0 0.396078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23859"/></filter><filter id="iccsWMe" width="1.554" height="1.999" x="15.986" y="22.812" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.827451 0 0 0 0 0.137255 0 0 0 0 0.317647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23859"/></filter><filter id="ilbhIle" width="4.764" height="4.766" x="24.75" y="19.349" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.1"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.898039 0 0 0 0 0.67451 0 0 0 0 0.556863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23859"/></filter><filter id="i0Fho3b" width="2.077" height="3.844" x="25.907" y="17.448" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.866667 0 0 0 0 0.639216 0 0 0 0 0.6 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23859"/></filter><filter id="iUWNzom" width="2.401" height="4.052" x="24.436" y="17.107" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.866667 0 0 0 0 0.639216 0 0 0 0 0.6 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23859"/></filter><filter id="iu4zlHc" width="2.312" height="4.044" x="23.386" y="17.96" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.866667 0 0 0 0 0.639216 0 0 0 0 0.6 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23859"/></filter><filter id="igM6I7w" width="2.123" height="3.114" x="22.394" y="19.041" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.866667 0 0 0 0 0.639216 0 0 0 0 0.6 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23859"/></filter><filter id="iXrzBPA" width="3.002" height="3.147" x="6.649" y="16.347" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.917647 0 0 0 0 0.662745 0 0 0 0 0.54902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23859"/></filter><filter id="i9ihvZE" width="1.264" height="2.491" x="22.908" y="19.19" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23859" stdDeviation=".125"/></filter><filter id="iMCf9pe" width="1.286" height="2.978" x="23.933" y="18.124" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23859" stdDeviation=".125"/></filter><filter id="ireKNKe" width="1.444" height="3.775" x="24.963" y="17.226" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23859" stdDeviation=".125"/></filter><filter id="iErm7Pd" width="1.17" height="3.014" x="26.424" y="17.706" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23859" stdDeviation=".125"/></filter><filter id="iIUcmeb" width="1.788" height="2.6" x="27.33" y="19.87" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23859" stdDeviation=".125"/></filter><filter id="iyqinHd" width="2.323" height="1.69" x="3.752" y="19.44" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23859" stdDeviation=".125"/></filter><filter id="iy6GIMg" width="2.342" height="2.022" x="3.291" y="18.151" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23859" stdDeviation=".125"/></filter><filter id="i6QO16b" width="2.131" height="2.124" x="4.556" y="16.714" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23859" stdDeviation=".125"/></filter><filter id="iRbXige" width="2.569" height="2.444" x="3.345" y="17.042" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23859" stdDeviation=".125"/></filter><filter id="iqyKwhe" width="3.514" height="3.364" x="10.088" y="12.617" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.894118 0 0 0 0 0.682353 0 0 0 0 0.6 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23859"/></filter><filter id="ipsgJ5c" width="3.364" height="3.614" x="20.033" y="12.367" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.784314 0 0 0 0 0.572549 0 0 0 0 0.513726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23859"/></filter><filter id="iJuPptJ" width="3.246" height="3.246" x="20.092" y="12.676" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23859" stdDeviation=".25"/></filter><filter id="iGHBoBe" width="3.046" height="3.046" x="10.267" y="12.776" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23859" stdDeviation=".2"/></filter><filter id="iRMPGPb" width="10.671" height="11.771" x="11.342" y="9.17" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.807843 0 0 0 0 0.592157 0 0 0 0 0.52549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23859"/></filter><filter id="ikxVmXe" width="2.962" height="3.803" x="15.018" y="13.271" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23859" stdDeviation=".25"/></filter><filter id="iEFK4Zb" width="2.462" height="3.303" x="15.437" y="13.377" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23859" stdDeviation=".125"/></filter><filter id="inMwY2d" width="3.852" height="1.577" x="14.743" y="16.763" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23859" stdDeviation=".05"/></filter><filter id="idQMvte" width="3.129" height="1.344" x="17.663" y="12.831" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0941176 0 0 0 0 0.0666667 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23859"/></filter><filter id="iqIeJDd" width="3.129" height="1.344" x="12.547" y="12.831" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0862745 0 0 0 0 0.054902 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23859"/></filter><filter id="iKIiwnf" width="2.555" height="1.131" x="12.687" y="11.352" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0235294 0 0 0 0 0.0313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23859"/></filter><filter id="iUzneAb" width="2.555" height="1.132" x="18.351" y="11.352" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0235294 0 0 0 0 0.0313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23859"/></filter><filter id="iqurHMM" width=".813" height=".719" x="18.187" y="13.22" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23859" stdDeviation=".05"/></filter><filter id="ipzLEvb" width=".914" height=".937" x="19.069" y="13.303" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23859" stdDeviation=".1"/></filter><filter id="ivo5ZAV" width="1.013" height="1.069" x="14.425" y="13.236" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23859" stdDeviation=".1"/></filter><filter id="iNEIGyd" width=".945" height=".727" x="13.632" y="13.211" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23859" stdDeviation=".05"/></filter><filter id="i0yvwMe" width="2.336" height=".995" x="18.397" y="11.484" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23859" stdDeviation=".1"/></filter><filter id="iXxcZdd" width="2.336" height=".995" x="12.697" y="11.484" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23859" stdDeviation=".1"/></filter><filter id="iIzONlu" width="1.169" height="2.387" x="13.234" y="7.513" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23859" stdDeviation=".1"/></filter><filter id="iW7XHfQ" width="6.651" height="3.457" x="15.982" y="8.378" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23859" stdDeviation=".375"/></filter><linearGradient id="i4C5tJe" x1="21.575" x2="14.461" y1="7.031" y2="20.208" gradientUnits="userSpaceOnUse"><stop class="hjtn79bml"/><stop offset="1" class="a4-v90a8k"/></linearGradient><linearGradient id="iK84mBb" x1="22.562" x2="21.812" y1="29.826" y2="29.826" gradientUnits="userSpaceOnUse"><stop class="fr__qmhjc"/><stop offset="1" class="gypp10kih"/></linearGradient><linearGradient id="iWCiqKd" x1="20.644" x2="21.062" y1="29.014" y2="29.014" gradientUnits="userSpaceOnUse"><stop class="hj-s-zboe"/><stop offset="1" class="s0umluqbl"/></linearGradient><linearGradient id="ipodSkc" x1="9.531" x2="4.906" y1="27.451" y2="27.451" gradientUnits="userSpaceOnUse"><stop class="sb-ednb_a"/><stop offset="1" class="v0501vbqa"/></linearGradient><linearGradient id="iXPTZOc" x1="9.75" x2="8.828" y1="27.076" y2="27.076" gradientUnits="userSpaceOnUse"><stop class="o_30au2yc"/><stop offset="1" class="c60cvac3k"/></linearGradient><linearGradient id="itP1zjc" x1="27.871" x2="22.844" y1="28.142" y2="28.142" gradientUnits="userSpaceOnUse"><stop class="i7zyuv8vr"/><stop offset=".907" class="qzhltkbuo"/></linearGradient><linearGradient id="i33ZCUz" x1="28.09" x2="27.168" y1="27.876" y2="27.876" gradientUnits="userSpaceOnUse"><stop class="tub8lbbfx"/><stop offset="1" class="bd09vtb_c"/></linearGradient><linearGradient id="i8tJXGc" x1="16.763" x2="16.763" y1="22.812" y2="24.81" gradientUnits="userSpaceOnUse"><stop offset=".351" class="gzsz7evmk"/><stop offset="1" class="smgiue0gi"/></linearGradient><linearGradient id="ijG10yh" x1="29.13" x2="28.38" y1="20.034" y2="21.659" gradientUnits="userSpaceOnUse"><stop class="i3-_-w2pf"/><stop offset="1" class="nntb9stew"/><stop offset="1" class="hyql_fbqw"/></linearGradient><linearGradient id="i9IIrXd" x1="4.76" x2="5.331" y1="20.169" y2="21.223" gradientUnits="userSpaceOnUse"><stop class="w5mx_ioxz"/><stop offset="1" class="dzgp29byh"/></linearGradient><linearGradient id="i8TsYWd" x1="4.307" x2="5.218" y1="19" y2="20.223" gradientUnits="userSpaceOnUse"><stop class="w5mx_ioxz"/><stop offset="1" class="dzgp29byh"/></linearGradient><linearGradient id="imTyYGd" x1="5.489" x2="6.52" y1="17.6" y2="18.693" gradientUnits="userSpaceOnUse"><stop class="w5mx_ioxz"/><stop offset="1" class="dzgp29byh"/></linearGradient><linearGradient id="ikSuYlc" x1="4.452" x2="5.734" y1="18.044" y2="19.502" gradientUnits="userSpaceOnUse"><stop class="w5mx_ioxz"/><stop offset="1" class="dzgp29byh"/></linearGradient><linearGradient id="iKNW15b" x1="10.088" x2="13.182" y1="14.39" y2="14.39" gradientUnits="userSpaceOnUse"><stop class="ixw8njbyx"/><stop offset="1" class="me4c4fyoe"/></linearGradient><linearGradient id="ihRBYHb" x1="16.677" x2="16.677" y1="10.783" y2="11.867" gradientUnits="userSpaceOnUse"><stop class="qtsgls2tz"/><stop offset="1" class="emix6fb6l"/></linearGradient><linearGradient id="idUWGEc" x1="15.687" x2="16.669" y1="15.691" y2="15.691" gradientUnits="userSpaceOnUse"><stop class="l38p1-72g"/><stop offset="1" class="njp0-cbrk"/></linearGradient><linearGradient id="i2xcffd" x1="16.669" x2="16.669" y1="16.526" y2="15.888" gradientUnits="userSpaceOnUse"><stop class="vdvey0c5l"/><stop offset="1" class="tddz0-g7t"/></linearGradient><linearGradient id="ihGOajb" x1="15.556" x2="16.038" y1="18" y2="17.256" gradientUnits="userSpaceOnUse"><stop class="b5nknil5b"/><stop offset=".663" class="prv6psg5p"/></linearGradient><linearGradient id="ikj3Tad" x1="19.763" x2="19.435" y1="13.732" y2="13.934" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ibntPCF" x1="15.165" x2="14.837" y1="13.731" y2="13.934" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iDDSyGe" x1="13.534" x2="14.103" y1="8.172" y2="9.504" gradientUnits="userSpaceOnUse"><stop class="z66p5h_5k"/><stop offset="1" class="ll4sw0vun"/></linearGradient><linearGradient id="izP9Z9c" x1="16.773" x2="16.773" y1="7.912" y2="8.1" gradientUnits="userSpaceOnUse"><stop class="jhlen960d"/><stop offset="1" class="wjchuwb6a"/></linearGradient><linearGradient id="iYE2hsb" x1="17.956" x2="17.956" y1="10.98" y2="10.214" gradientUnits="userSpaceOnUse"><stop class="bl3fq0x9z"/><stop offset="1" class="lxo7c2i6k"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-juggling-light" /></template>
<style>
.a4-v90a8k {
  stop-color: var(--svg-color--1a1718, #1A1718);
}

.a5zzorbzd {
  stop-color: var(--svg-color--e1ac3a, #E1AC3A);
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

.aqzyd8bsb {
  stop-color: var(--svg-color--896bb4, #896BB4);
  stop-opacity: 0;
}

.arh302van {
  d: path("M16.453 19.623a10.2 10.2 0 0 0-3.058.466l.597 3.136h4.945l.821-3.25a10.2 10.2 0 0 0-2.664-.352z");
}

.arn591bff {
  stroke: var(--svg-color--ffd1bd, #FFD1BD);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-35px, 0.35px);
  d: path("m24.358 18.55l.436 2.127");
}

.auvn9fbbk {
  stop-color: var(--svg-color--e9387a, #E9387A);
}

.b057dp4eh {
  stop-color: var(--svg-color--ccbdde, #CCBDDE);
}

.b3bgf45aw {
  d: path("M19.783 13.987a.9.9 0 0 0-.242-.484l-.272.298l.123.239z");
}

.b55qklbsj {
  stop-color: var(--svg-color--bc8272, #BC8272);
  stop-opacity: 0;
}

.b5nknil5b {
  stop-color: var(--svg-color--eabbab, #EABBAB);
}

.b7w777b-n {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.884 13.374c.066.089-.073.197-.23.315c-.159.118-.276.201-.342.113c-.067-.09.007-.257.165-.375s.34-.142.407-.053");
}

.bb8jc-j1w {
  fill-rule: evenodd;
  d: path("M24.18 15.773a3.4 3.4 0 0 0 .339-1.492c0-.488-.1-.947-.281-1.365h.006a3.3 3.3 0 0 0-.294-.536l-.003-.003a3.4 3.4 0 0 1-.55-1.852v-.01c0-.81-1.431-1.251-1.9-1.84c-.632-.795-.455-1.61-1.549-1.61a.56.56 0 0 1-.476-.242a3.46 3.46 0 0 0-2.803-1.44c-1.154 0-2.18.572-2.804 1.44a.59.59 0 0 1-.476.243l-.089.001c-1.057.027-1.013 1.449-1.628 2.222c-.468.589-1.732.415-1.732 1.226v.01c0 .656-.19 1.302-.55 1.852l-.002.004a3.45 3.45 0 0 0-.23 3.392a.54.54 0 0 1 0 .476a3.4 3.4 0 0 0-.34 1.47a3.36 3.36 0 0 0 3.365 3.365h8.971a3.36 3.36 0 0 0 3.365-3.364c0-.53-.127-1.027-.339-1.471a.54.54 0 0 1 0-.476m-12.817-2.794h-.012l1.253 2.463c.129 2.93 1.272 0 4.065 0c2.792 0 4.01 3.26 4.14.33l1.186-3.341c-.056-1.302-.999-1.393-1.187-1.393h-3.366c-1.33 0-2.584-.65-3.334-1.75a.276.276 0 0 0-.483.054l-.085.203a2.4 2.4 0 0 1-1.297 1.312q-.03.013-.054.02c-.247.129-.826.513-.847 1.505l.01.32z");
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

.bl7uysvvb {
  stop-color: var(--svg-color--181518, #181518);
}

.bq5dgsbba {
  stop-color: var(--svg-color--dcc8ec, #DCC8EC);
}

.brg8dbpny {
  stop-color: var(--svg-color--e2a895, #E2A895);
  stop-opacity: 0;
}

.btor07b8q {
  stop-color: var(--svg-color--d61f4d, #D61F4D);
}

.byihu8b7s {
  stop-color: var(--svg-color--dba096, #DBA096);
  stop-opacity: 0;
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

.c9_6uxbfa {
  stop-color: var(--svg-color--4a4446, #4A4446);
  stop-opacity: 0;
}

.cg9m3ci5c {
  stop-color: var(--svg-color--c57e83, #C57E83);
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

.ctsppjbax {
  d: path("M14.866 22.463c.91.308 1.268.83 1.389 1.082l.028.29l-.028.359c-.12.25-.48.706-1.389 1.014c-.36.123-.777.068-.97-.267a2.17 2.17 0 0 1-.285-1.105c0-.502.144-.862.285-1.106c.193-.335.61-.39.97-.267");
}

.ctupw6b3d {
  fill-rule: evenodd;
  d: path("M3.113 18.184a.75.75 0 0 1 1.042.196c.312.455.974 1.204 1.85 1.204a.75.75 0 1 1 0 1.5c-1.702 0-2.759-1.376-3.088-1.858a.75.75 0 0 1 .196-1.042");
}

.cz19hw0vg {
  fill: var(--svg-color--f1bdaa, #F1BDAA);
  d: path("M23.407 18.803a.679.679 0 1 1 1.323-.298l.555 2.766a.613.613 0 0 1-1.195.27z");
}

.d_t8kfbgb {
  stop-color: var(--svg-color--e2a895, #E2A895);
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

.dkw8bsvxv {
  stop-color: var(--svg-color--f5b99d, #F5B99D);
}

.don2wdpjw {
  cx: 16.761px;
  cy: 26.282px;
  r: 0.739px;
}

.dpmuo-biy {
  stop-color: var(--svg-color--6f5ea2, #6F5EA2);
}

.dtaunfmfd {
  fill: var(--svg-color--f1bdaa, #F1BDAA);
  d: path("M24.458 17.959a.68.68 0 0 1 .568-.843l.023-.003a.68.68 0 0 1 .756.54l.622 3.039c.071.355-.246.42-.606.458c-.303.032-.553-.005-.629-.3z");
}

.duyhuibwk {
  cx: 9.246px;
  cy: 3.857px;
  r: 1.684px;
}

.dzgp29byh {
  stop-color: var(--svg-color--ffd0bd, #FFD0BD);
  stop-opacity: 0;
}

.e-twaac7b {
  stop-color: var(--svg-color--575455, #575455);
  stop-opacity: 0;
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e2earo80w {
  stop-color: var(--svg-color--f6baa9, #F6BAA9);
}

.e7777ub0x {
  stop-color: var(--svg-color--ebb8a2, #EBB8A2);
  stop-opacity: 0;
}

.emix6fb6l {
  stop-color: var(--svg-color--c78c84, #C78C84);
  stop-opacity: 0;
}

.eodwsybla {
  stop-color: var(--svg-color--ffd8bc, #FFD8BC);
  stop-opacity: 0;
}

.eyusp0blq {
  fill: var(--svg-color--000, #000);
  d: path("M18.418 14.11c0-.297.237-.535.534-.535a.532.532 0 0 1 .475.78h-.945a.5.5 0 0 1-.064-.245");
}

.f_q-3cc4h {
  stop-color: var(--svg-color--a47463, #A47463);
}

.f21vmbcik {
  d: path("M5.437 21.764h4.094v8.063H5.437z");
}

.f6slf6w2m {
  stop-color: var(--svg-color--ffd3be, #FFD3BE);
}

.fde_fwzpt {
  stop-color: var(--svg-color--5c9946, #5C9946);
}

.flu_1vdvd {
  d: path("M14.386 13.176a.933.933 0 0 0-.9 1.18h1.803a1 1 0 0 0 .034-.247a.94.94 0 0 0-.937-.933");
}

.fr__qmhjc {
  stop-color: var(--svg-color--7a6cad, #7A6CAD);
}

.ft5dv1b6b {
  fill: none;
}

.fvm07vbkd {
  stop-color: var(--svg-color--b87c92, #B87C92);
}

.fzq016boz {
  stop-color: var(--svg-color--e35838, #E35838);
}

.g0r7omboq {
  stop-color: var(--svg-color--474445, #474445);
  stop-opacity: 0;
}

.g8uem1b5g {
  stop-color: var(--svg-color--38303e, #38303E);
  stop-opacity: 0;
}

.g9xx7math {
  stop-color: var(--svg-color--e7aea1, #E7AEA1);
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

.gzsz7evmk {
  stop-color: var(--svg-color--eb3782, #EB3782);
}

.h28q1nbvc {
  fill: var(--svg-color--f1bdaa, #F1BDAA);
  d: path("M22.414 19.88a.68.68 0 1 1 1.33-.293l.36 1.793a.645.645 0 0 1-1.26.28z");
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

.hd554kb0x {
  fill: var(--svg-color--000, #000);
  d: path("M14.92 14.11a.53.53 0 0 0-.534-.535a.532.532 0 0 0-.475.78h.946a.5.5 0 0 0 .063-.245");
}

.hhnbdw1mn {
  stroke: var(--svg-color--ffd1bd, #FFD1BD);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-35px, 0.35px);
  d: path("m26.849 18.13l.32 2.165");
}

.hj-s-zboe {
  stop-color: var(--svg-color--6d5096, #6D5096);
}

.hjtn79bml {
  stop-color: var(--svg-color--393134, #393134);
}

.hkormb2xp {
  stop-color: var(--svg-color--575455, #575455);
}

.hpfqe6rjh {
  cx: 6.332px;
  cy: 12.838px;
  r: 1.684px;
}

.ht6lpfbpp {
  d: path("M18.68 22.463c-.909.308-1.267.83-1.388 1.082l-.028.29l.028.359c.12.25.48.706 1.388 1.014c.362.123.778.068.971-.267c.14-.243.284-.599.284-1.105c0-.507-.144-.862-.284-1.106c-.193-.335-.61-.39-.97-.267");
}

.htooq-bzz {
  fill: var(--svg-color--f1bdaa, #F1BDAA);
  d: path("M25.92 18.247a.668.668 0 1 1 1.316-.232l.34 2.222q.012.082.005.164l-.015.163c-.005.055-.002.11 0 .165c.016.295-.146.515-.454.557a.61.61 0 0 1-.68-.483z");
}

.hw860-bkw {
  d: path("M22.993 22.213c.119.463.586 1.456.805 1.894h4.047l-.258-3.789l-4.836.924c.031.13.123.507.242.97");
}

.hx66smwtj {
  stop-color: var(--svg-color--4a4446, #4A4446);
}

.hyql_fbqw {
  stop-color: var(--svg-color--ffd5bf, #FFD5BF);
  stop-opacity: 0;
}

.i1-orb7ke {
  stop-color: var(--svg-color--c3b7c1, #C3B7C1);
}

.i3-_-w2pf {
  stop-color: var(--svg-color--ffd5bf, #FFD5BF);
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

.intda8ekf {
  stop-color: var(--svg-color--d09790, #D09790);
  stop-opacity: 0;
}

.iuch0hb0l {
  stop-color: var(--svg-color--b4807e, #B4807E);
}

.iwbygtbvw {
  cx: 25.211px;
  cy: 4.873px;
  r: 1.684px;
}

.ixw8njbyx {
  stop-color: var(--svg-color--cc9987, #CC9987);
}

.j--0dbbee {
  d: path("m16.269 13.922l-.556 1.777a.564.564 0 0 0 .545.731h.822a.565.565 0 0 0 .544-.731l-.556-1.777c-.119-.394-.674-.394-.8 0");
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

.jk5udqbyz {
  stop-color: var(--svg-color--464444, #464444);
  stop-opacity: 0;
}

.jm40s5baz {
  stop-color: var(--svg-color--968f9c, #968F9C);
  stop-opacity: 0;
}

.jus1k8bhb {
  fill: var(--svg-color--fff, #fff);
  d: path("M14.169 12.893c-.683 0-1.26.47-1.416 1.106a.287.287 0 0 0 .28.357h2.332a.24.24 0 0 0 .237-.284a1.465 1.465 0 0 0-1.433-1.18");
}

.jzs0qy57r {
  stop-color: var(--svg-color--f9c6ac, #F9C6AC);
}

.k2oqpgb0o {
  stop-color: var(--svg-color--f4b89e, #F4B89E);
  stop-opacity: 0;
}

.k9fawxbmc {
  cx: 14.104px;
  cy: 13.575px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.407px;
  ry: 0.206px;
}

.kbl3igr5c {
  stop-color: var(--svg-color--040002, #040002);
}

.khemg5bhx {
  stop-color: var(--svg-color--dea98d, #DEA98D);
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

.kzuil_5zu {
  stop-color: var(--svg-color--9072ca, #9072CA);
}

.l-r9gxb9g {
  stop-color: var(--svg-color--4bb8fb, #4BB8FB);
}

.l0xg-rbdf {
  stop-color: var(--svg-color--040101, #040101);
}

.l1l6vcdra {
  stop-color: var(--svg-color--dba096, #DBA096);
}

.l38p1-72g {
  stop-color: var(--svg-color--dfa791, #DFA791);
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

.lgi0lwbjz {
  stop-color: var(--svg-color--775184, #775184);
  stop-opacity: 0;
}

.lgjudcrkd {
  stop-color: var(--svg-color--413733, #413733);
}

.lh1q57nmq {
  fill: var(--svg-color--f1c4b2, #F1C4B2);
  d: path("m16.269 13.922l-.556 1.777a.564.564 0 0 0 .545.731h.822a.565.565 0 0 0 .544-.731l-.556-1.777c-.119-.394-.674-.394-.8 0");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.ljv4u1xrn {
  cx: 14.104px;
  cy: 13.575px;
  rx: 0.407px;
  ry: 0.206px;
}

.ll4sw0vun {
  stop-color: var(--svg-color--24182d, #24182D);
}

.lp_0y5ggb {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M16.669 17.343a3.16 3.16 0 0 1-1.486-.36c-.147-.077-.305.093-.213.23a2.02 2.02 0 0 0 3.397 0c.093-.143-.065-.307-.212-.23c-.43.23-.936.36-1.486.36Z");
}

.lsx269bcs {
  d: path("M11.79 15.422a1.123 1.123 0 1 0 0-2.246a1.123 1.123 0 0 0 0 2.246");
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

.m87o_mhtw {
  d: path("M21.715 15.422a1.123 1.123 0 1 0 0-2.246a1.123 1.123 0 0 0 0 2.246");
}

.m9gf32bwp {
  stop-color: var(--svg-color--d6d3d7, #D6D3D7);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.me4c4fyoe {
  stop-color: var(--svg-color--ac7864, #AC7864);
}

.mmq2utbuk {
  stop-color: var(--svg-color--cf8b51, #CF8B51);
}

.mpwbs5b3u {
  stop-color: var(--svg-color--ff894e, #FF894E);
}

.mt9jhjbax {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("m13.117 12.44l-.005.003a.28.28 0 0 1-.288-.48v-.001h.001l.003-.002l.01-.006l.034-.019q.044-.024.121-.061c.103-.05.25-.112.43-.17a2.9 2.9 0 0 1 1.388-.114a.28.28 0 1 1-.098.553a2.36 2.36 0 0 0-1.12.096a3 3 0 0 0-.454.189z");
}

.mxnnm4bur {
  stop-color: var(--svg-color--464444, #464444);
}

.n1w64orcn {
  stop-color: var(--svg-color--b87c92, #B87C92);
  stop-opacity: 0;
}

.n297mkbnr {
  stop-color: var(--svg-color--d6d3d7, #D6D3D7);
  stop-opacity: 0;
}

.n302v8i1b {
  fill: var(--svg-color--2d2b2e, #2D2B2E);
  d: path("M17.863 13.705c.277-.489.7-.874 1.607-.874c.398 0 .78.11 1.122.386c.28.227.243.517.025.626l-.581.332c-.681-.22-1.435-.25-2.173-.47");
}

.ndapliy4h {
  stroke: var(--svg-color--ffd1bd, #FFD1BD);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-35px, 0.35px);
  d: path("m23.333 19.615l.414 1.64");
}

.ng1cexbhj {
  stop-color: var(--svg-color--b6424c, #B6424C);
}

.njp0-cbrk {
  stop-color: var(--svg-color--dfa791, #DFA791);
  stop-opacity: 0;
}

.nl0wbpawx {
  stop-color: var(--svg-color--968f9c, #968F9C);
}

.nnonv9b0l {
  fill: var(--svg-color--d19590, #D19590);
  d: path("m16.259 14.067l-.715 1.777a.564.564 0 0 0 .544.731h.822a.566.566 0 0 0 .544-.731l-.555-1.777c-.12-.394-.516-.394-.64 0");
}

.nntb9stew {
  stop-color: var(--svg-color--efc0a4, #EFC0A4);
  stop-opacity: 0;
}

.nqrf57zsi {
  stop-color: var(--svg-color--f2bdaa, #F2BDAA);
}

.nwt8glb0m {
  stop-color: var(--svg-color--ffd6c2, #FFD6C2);
  stop-opacity: 0;
}

.o_30au2yc {
  stop-color: var(--svg-color--decfd8, #DECFD8);
}

.o-tanhhbh {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M13.534 7.813c.024.254.245 1.209.569 1.787");
}

.o415o878f {
  stop-color: var(--svg-color--ef4c8b, #EF4C8B);
}

.obqipxbwg {
  d: path("M18.952 13.176a.933.933 0 0 1 .899 1.18h-1.802a.937.937 0 0 1 .903-1.179");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ofoeipbcd {
  d: path("M18.884 13.374c.066.089-.073.197-.23.315c-.159.118-.276.201-.342.113c-.067-.09.007-.257.165-.375s.34-.142.407-.053");
}

.ogxz6h-st {
  d: path("M11.77 15.982a1.682 1.682 0 1 0 0-3.365a1.682 1.682 0 0 0 0 3.364");
}

.oirt5lbzg {
  stroke: var(--svg-color--323233, #323233);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M18.697 11.82c.337-.083 1.175-.042 1.736.36");
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

.p5eexwbyw {
  stop-color: var(--svg-color--edb9a9, #EDB9A9);
}

.paonnib9g {
  stop-color: var(--svg-color--474445, #474445);
}

.pb6efmson {
  stop-color: var(--svg-color--d72c5e, #D72C5E);
}

.ped5v8nqh {
  fill: var(--svg-color--272528, #272528);
  d: path("M15.475 13.705c-.277-.489-.699-.874-1.607-.874c-.397 0-.78.11-1.121.386c-.281.227-.244.517-.026.626l.581.332c.682-.22 1.435-.25 2.173-.47");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.ppr920emc {
  stop-color: var(--svg-color--61a150, #61A150);
  stop-opacity: 0;
}

.prv6psg5p {
  stop-color: var(--svg-color--eabbab, #EABBAB);
  stop-opacity: 0;
}

.pt8frltpn {
  stop-color: var(--svg-color--7060a5, #7060A5);
}

.q15yln0fl {
  d: path("M15.238 14c0-.302-.245-.503-.312-.563l-.301.291l.185.378z");
}

.q2yo0ybkp {
  fill: var(--svg-color--f6bca5, #F6BCA5);
  d: path("M21.715 15.422a1.123 1.123 0 1 0 0-2.246a1.123 1.123 0 0 0 0 2.246");
}

.qpkqxibzk {
  stop-color: var(--svg-color--ffd6c2, #FFD6C2);
}

.qsu4qbckq {
  stop-color: var(--svg-color--dbcdd4, #DBCDD4);
}

.qtsgls2tz {
  stop-color: var(--svg-color--c78c84, #C78C84);
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

.r_v2kebuk {
  stop-color: var(--svg-color--181518, #181518);
  stop-opacity: 0;
}

.r6y4i1b2t {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  fill-rule: evenodd;
  d: path("m20.57 11.962l-.144.24za.28.28 0 0 1-.288.482l-.005-.003l-.023-.013l-.095-.048a3 3 0 0 0-.358-.141a2.4 2.4 0 0 0-1.12-.097a.28.28 0 1 1-.098-.552a2.94 2.94 0 0 1 1.388.114a3.4 3.4 0 0 1 .584.25l.01.006l.003.001z");
}

.s0umluqbl {
  stop-color: var(--svg-color--7160a4, #7160A4);
  stop-opacity: 0;
}

.s44y8_wdc {
  stop-color: var(--svg-color--a47463, #A47463);
  stop-opacity: 0;
}

.s76rkqhqi {
  stroke: var(--svg-color--ffd1bd, #FFD1BD);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-35px, 0.35px);
  d: path("m25.388 17.65l.594 2.926");
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

.sh7m4tbex {
  fill: var(--svg-color--ffd4bf, #FFD4BF);
  d: path("m27.85 19.83l-.447.824l-1.172 1.422l-1.481 1.992l3.099.047c.099-.172.218-.566.38-1.327c.164-.66.326-1.114.471-1.376l.443-.924a.726.726 0 0 0-1.292-.659");
}

.sheftacio {
  stop-color: var(--svg-color--ffd8c1, #FFD8C1);
}

.silozpblh {
  stop-color: var(--svg-color--3b3638, #3B3638);
  stop-opacity: 0;
}

.smgiue0gi {
  stop-color: var(--svg-color--c93857, #C93857);
}

.sqxrh1b6n {
  stop-color: var(--svg-color--ffd8bc, #FFD8BC);
}

.suybu51ug {
  stop-color: var(--svg-color--d09790, #D09790);
}

.swka_j87x {
  d: path("M6.25 29.826c0-5.635 4.568-10.203 10.203-10.203h.64c5.636 0 10.204 4.568 10.204 10.203z");
}

.t-5nldk3g {
  cx: 16.761px;
  cy: 28.296px;
  r: 0.739px;
}

.tbmfqptqo {
  d: path("M21.715 15.982a1.682 1.682 0 1 0 0-3.365a1.682 1.682 0 0 0 0 3.364");
}

.td2qu3khi {
  stroke: var(--svg-color--323233, #323233);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M14.733 11.82c-.337-.083-1.175-.042-1.736.36");
}

.tddz0-g7t {
  stop-color: var(--svg-color--d29394, #D29394);
  stop-opacity: 0;
}

.tg07-ljnl {
  stop-color: var(--svg-color--5e5764, #5E5764);
}

.tk20gvbnd {
  stop-color: var(--svg-color--ffdebf, #FFDEBF);
  stop-opacity: 0;
}

.tn_97qkdc {
  stop-color: var(--svg-color--f2c341, #F2C341);
  stop-opacity: 0;
}

.tou4lf01r {
  fill: var(--svg-color--88024e, #88024E);
  d: path("M16.669 17.343a3.16 3.16 0 0 1-1.486-.36c-.147-.077-.305.093-.213.23a2.02 2.02 0 0 0 3.397 0c.093-.143-.065-.307-.212-.23c-.43.23-.936.36-1.486.36");
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

.txbqaun0d {
  stop-color: var(--svg-color--d39891, #D39891);
  stop-opacity: 0;
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

.uaoaczbhz {
  stop-color: var(--svg-color--bc8272, #BC8272);
}

.ue219ybxm {
  fill: var(--svg-color--fff, #fff);
  d: path("M19.168 12.893c.683 0 1.26.47 1.417 1.106a.287.287 0 0 1-.28.357h-2.333a.24.24 0 0 1-.237-.284a1.46 1.46 0 0 1 1.433-1.18");
}

.ujrq6ixuu {
  stop-color: var(--svg-color--beb4c6, #BEB4C6);
}

.utcasbb3u {
  stop-color: var(--svg-color--f3c0a7, #F3C0A7);
}

.ux87x8bpy {
  stop-color: var(--svg-color--e2aa9f, #E2AA9F);
}

.v-9tn59hb {
  stop-color: var(--svg-color--dba98b, #DBA98B);
  stop-opacity: 0;
}

.v0501vbqa {
  stop-color: var(--svg-color--c0b5cd, #C0B5CD);
}

.v5rheyc4i {
  stop-color: var(--svg-color--ffd7bf, #FFD7BF);
}

.vbn8f2bra {
  stop-color: var(--svg-color--f0bea2, #F0BEA2);
}

.vdngsab5t {
  fill-rule: evenodd;
  d: path("M3.416 19.34a.75.75 0 0 1 1.051.14c.244.317.833.881 1.8.881a.75.75 0 0 1 .75.75c0 .415-.336.67-.75.67c-1.683 0-2.593-.87-2.99-1.39a.75.75 0 0 1 .139-1.05");
}

.vdvey0c5l {
  stop-color: var(--svg-color--d29394, #D29394);
}

.vjdrhubcm {
  fill: var(--svg-color--c58c80, #C58C80);
  d: path("M11.79 15.422a1.123 1.123 0 1 0 0-2.246a1.123 1.123 0 0 0 0 2.246");
}

.vke6kh8bt {
  stop-color: var(--svg-color--3e3843, #3E3843);
  stop-opacity: 0;
}

.vrhnsgvqh {
  stop-color: var(--svg-color--cd9897, #CD9897);
  stop-opacity: 0;
}

.vvfum-_fa {
  stop-color: var(--svg-color--392f42, #392F42);
}

.w--6bgeqj {
  stop-color: var(--svg-color--e5b1a5, #E5B1A5);
}

.w5mx_ioxz {
  stop-color: var(--svg-color--ffd0bd, #FFD0BD);
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

.wp2dqucie {
  d: path("M14.545 18.417c0-.99.901-1.794 2.012-1.794s2.012.803 2.012 1.794v2.326c0 .99-.901 1.794-2.012 1.794s-2.012-.803-2.012-1.794z");
}

.wp2p6dbcv {
  d: path("M23.777 24.107h4.094v5.719h-4.094z");
}

.wrgoaxbaa {
  stop-color: var(--svg-color--f2bdaa, #F2BDAA);
  stop-opacity: 0;
}

.wshx69b-y {
  stop-color: var(--svg-color--896bb4, #896BB4);
}

.wum9l96_j {
  stop-color: var(--svg-color--d59f97, #D59F97);
}

.ww1jp2brw {
  stop-color: var(--svg-color--ebae91, #EBAE91);
}

.x1l7xqbyw {
  stop-color: var(--svg-color--de5534, #DE5534);
  stop-opacity: 0;
}

.xbgj88f0b {
  stop-color: var(--svg-color--ffdcc5, #FFDCC5);
}

.xdn388byj {
  stop-color: var(--svg-color--171418, #171418);
}

.xl9xm7bnj {
  stop-color: var(--svg-color--f6baa9, #F6BAA9);
  stop-opacity: 0;
}

.xm9fbaccy {
  stop-color: var(--svg-color--d39891, #D39891);
}

.xntzq-4ho {
  stop-color: var(--svg-color--8566b5, #8566B5);
}

.y_9l2i5ww {
  stop-color: var(--svg-color--ffdcc5, #FFDCC5);
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

.y2ea22zwh {
  d: path("M11.35 12.98h.013l-.01-.278l-.011-.32c.021-.992.6-1.376.847-1.504q.024-.008.053-.021q.03-.013.054-.021a2.4 2.4 0 0 0 1.243-1.291l.086-.203a.276.276 0 0 1 .482-.053c.751 1.099 2.005 1.123 3.335 1.123h3.366c.188 0 1.362 0 1.187 2.019l-.124 3.213c-.129 2.93-2.417 4.897-5.21 4.897c-2.792 0-5.08-1.968-5.209-4.898z");
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

.ynae43ovp {
  stop-color: var(--svg-color--dba98b, #DBA98B);
}

.ytdkz2bln {
  fill: var(--svg-color--4b4648, #4B4648);
  d: path("m19.072 10.281l-1.49.274a.72.72 0 1 1-.13-1.427h2.446c1.448 0 1.927 1.459 1.985 1.957a3.29 3.29 0 0 0-2.811-.804");
}

.z-rzt8b_f {
  stop-color: var(--svg-color--ffdebf, #FFDEBF);
}

.z66p5h_5k {
  stop-color: var(--svg-color--1a1316, #1A1316);
}

.zdcorrl9x {
  cx: 26.234px;
  cy: 14.83px;
  r: 1.684px;
}

</style>
