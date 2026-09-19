<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#i86sG1b)"><path fill="url(#igL0Bud)" clip-rule="evenodd" class="gwyjgcc6d"/><path fill="url(#iLJN2Cd)" clip-rule="evenodd" class="gwyjgcc6d"/><path fill="url(#iD0VbJY)" clip-rule="evenodd" class="gwyjgcc6d"/><path fill="url(#ibBfa4c)" clip-rule="evenodd" class="gwyjgcc6d"/><path fill="url(#iijQ0Uc)" clip-rule="evenodd" class="gwyjgcc6d"/><path fill="url(#iHsFNMd)" clip-rule="evenodd" class="gwyjgcc6d"/><path fill="url(#i0xjQUd)" clip-rule="evenodd" class="gwyjgcc6d"/><path fill="url(#iTvX4pb)" clip-rule="evenodd" class="gwyjgcc6d"/><path fill="url(#idr8buc)" clip-rule="evenodd" class="gwyjgcc6d"/><path fill="url(#ihyEkkd)" clip-rule="evenodd" class="gwyjgcc6d"/><path fill="url(#iFGRsxe)" clip-rule="evenodd" class="gwyjgcc6d"/><path fill="url(#iapLTzT)" clip-rule="evenodd" class="gwyjgcc6d"/></g><path fill="url(#iJ0Nzyc)" class="xzot6tb3a"/><path fill="url(#iQ3Jo1d)" class="xzot6tb3a"/><path fill="url(#iu4BL0y)" class="xzot6tb3a"/><path fill="url(#i6kQckA)" class="xzot6tb3a"/><path fill="url(#iEbtPxb)" class="h83slyb1a"/><path fill="url(#imxslwc)" class="h83slyb1a"/><path fill="url(#iAPRHYd)" class="sllpz02jo"/><path fill="url(#iegNxyc)" class="sllpz02jo"/><g filter="url(#ir3azmc)"><path fill="url(#i6aJFZY)" class="i8us91y_g"/><path fill="url(#izDA0dI)" class="i8us91y_g"/></g><g filter="url(#ivknJvd)"><path class="a7obdqv4r"/><path fill="url(#iDMsGJb)" class="e4qvstbaw"/><path fill="url(#izjH7xz)" class="e4qvstbaw"/></g><g filter="url(#iKzJrad)"><ellipse transform="rotate(-40.534 9.937 22.243)" class="si-u7d6wp"/></g><ellipse fill="url(#iuxxmBb)" transform="rotate(-40.534 9.886 22.154)" class="fvifkjh5i"/><g filter="url(#isZwa0X)"><ellipse transform="scale(-1 1)rotate(-35.343 23.848 45.555)" class="n11xmqb_x"/></g><ellipse fill="url(#imtwsXc)" transform="scale(-1 1)rotate(-40.534 18.954 40.982)" class="tto44ccna"/><g filter="url(#i0pcMoC)"><rect fill="url(#icTwalH)" class="qyeoy6a8h"/><rect fill="url(#iFB7LRc)" class="qyeoy6a8h"/><rect fill="url(#i7g7vQc)" class="qyeoy6a8h"/></g><rect fill="url(#iNsLlse)" class="kav9ef57d"/><path fill="url(#iYKVIWb)" class="g4mvl20po"/><path fill="url(#iDWpPDG)" class="g4mvl20po"/><g filter="url(#ig0ccud)"><circle class="d0e6vrb_a"/></g><g filter="url(#i1LlF4b)"><circle class="b4n-hsbxm"/></g><circle fill="url(#itFpnJb)" class="sx6q1cbyi"/><circle fill="url(#iOrZVKb)" class="cad66eb8i"/><path fill="url(#icGpVve)" class="if6aw8aev"/><path fill="url(#isLpFne)" class="yk-5cub9i"/><g filter="url(#iETJxqb)"><path fill="url(#i5DGjTb)" class="gvxstr-td"/></g><g filter="url(#iKACenb)"><path fill="url(#irCMJ4r)" class="x-k_p1dly"/><path fill="url(#i4gZ4kd)" class="x-k_p1dly"/></g><g filter="url(#ifcteic)"><path class="l_96kr3kr"/><path fill="url(#ic5idHb)" class="o91iu5btx"/></g><g filter="url(#i5YbI4Y)"><path class="xolko2_ao"/><path fill="url(#inOgopx)" class="n2jxlwzra"/></g><g filter="url(#issdSJc)"><path fill="url(#iMFRwLL)" class="e2h-54bmv"/><path fill="url(#iD3Jf8b)" class="e2h-54bmv"/><path fill="url(#i4SXE6b)" class="e2h-54bmv"/><path fill="url(#ig8nRLW)" class="e2h-54bmv"/><path fill="url(#iMx4VSd)" class="e2h-54bmv"/><path fill="url(#i0U9FNc)" class="e2h-54bmv"/><path fill="url(#i4IxQjb)" class="e2h-54bmv"/><path fill="url(#i8bd7ye)" class="e2h-54bmv"/></g><path fill="url(#ihZRuTc)" class="e2h-54bmv"/><path fill="url(#iEyHjAr)" class="e2h-54bmv"/><path fill="url(#it2w3Cc)" class="e2h-54bmv"/><path fill="url(#ivm4Kle)" class="e2h-54bmv"/><g filter="url(#iDydXKc)"><path class="kviyf7blg"/></g><g filter="url(#iZqlpPc)"><path class="u70snkboj"/><path fill="url(#ieLitUd)" class="jy-abr9zo"/><path fill="url(#iZGA7Ne)" class="jy-abr9zo"/><path fill="url(#iA2vqjc)" class="jy-abr9zo"/><path fill="url(#id2bzZc)" class="jy-abr9zo"/></g><g filter="url(#i1zX9Xd)"><path fill="url(#iSbzHye)" class="k0sl1tber"/></g><g filter="url(#icver2O)"><path stroke="url(#iquHSpb)" class="i16488b3m"/></g><path class="zobftskva"/><g filter="url(#iKHBE7d)"><path class="bc53okb3o"/></g><g filter="url(#idxOpjo)"><path class="qhplrx0mg"/></g><path class="b7gs5bban"/><path fill="url(#io3EaRb)" class="nesqdcchf"/><path class="yt3n_ccvh"/><g filter="url(#iLOVfJd)"><path class="h8qkcsbic"/><path fill="url(#i9Nolwb)" class="eikz_kwmc"/></g><g filter="url(#iuLVkKN)"><path fill="url(#iE9NuWE)" class="hrbrxdb4k"/></g><path class="f2pe0nb3d"/><path fill="url(#iLG3rXc)" class="bx1dz9qpc"/><path class="c_x9vzbvj"/><g filter="url(#ijsDHeH)"><path fill="url(#i6fdTud)" class="nz9di63yp"/></g><g filter="url(#ipUJdLx)"><ellipse transform="rotate(-27.914 13.515 14.869)" class="rot26fbzl"/><ellipse fill="url(#iNXynfc)" transform="rotate(-27.914 13.515 14.869)" class="jpermjesn"/></g><g filter="url(#iWzG3cb)"><path fill="url(#iyKRZUc)" class="vim75kb4b"/><path fill="url(#iC5hH6b)" class="vim75kb4b"/></g><path fill="url(#iWLVOVc)" class="vim75kb4b"/><path fill="url(#i2pBBLt)" class="vim75kb4b"/><path fill="url(#isYcgqc)" class="vim75kb4b"/><g filter="url(#icLiyue)"><path fill="url(#iU1wwRb)" class="ygyxlcb5n"/><path fill="url(#i7n11Wc)" class="ygyxlcb5n"/><path fill="url(#iyBJvOb)" class="ygyxlcb5n"/></g><defs><radialGradient id="iLJN2Cd" cx="0" cy="0" r="1" gradientTransform="matrix(-.60337 4.55908 -5.69522 -.75373 15.667 18.062)" gradientUnits="userSpaceOnUse"><stop offset=".591" class="xdn388byj"/><stop offset="1" class="qwp4ni-tf"/></radialGradient><radialGradient id="iD0VbJY" cx="0" cy="0" r="1" gradientTransform="matrix(-2.88301 1.94432 -2.5547 -3.78806 12.851 18.33)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="bl7uysvvb"/><stop offset="1" class="r_v2kebuk"/></radialGradient><radialGradient id="ibBfa4c" cx="0" cy="0" r="1" gradientTransform="rotate(127.405 1.663 10.64)scale(2.15225 1.65263)" gradientUnits="userSpaceOnUse"><stop offset=".334" class="l0xg-rbdf"/><stop offset="1" class="chj8m5e2t"/></radialGradient><radialGradient id="iijQ0Uc" cx="0" cy="0" r="1" gradientTransform="rotate(121.43 1.932 10.124)scale(2.47506 1.74346)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="kbl3igr5c"/><stop offset="1" class="glo437b-m"/></radialGradient><radialGradient id="iHsFNMd" cx="0" cy="0" r="1" gradientTransform="rotate(62.272 .014 14.055)scale(2.95399 4.10059)" gradientUnits="userSpaceOnUse"><stop class="paonnib9g"/><stop offset="1" class="g0r7omboq"/></radialGradient><radialGradient id="i0xjQUd" cx="0" cy="0" r="1" gradientTransform="rotate(134.998 8.916 9.306)scale(2.03849 2.84876)" gradientUnits="userSpaceOnUse"><stop class="hx66smwtj"/><stop offset="1" class="c9_6uxbfa"/></radialGradient><radialGradient id="iTvX4pb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.84366 .53637 -1.11855 -3.84482 23.478 14.71)" gradientUnits="userSpaceOnUse"><stop class="cj4rfmfkx"/><stop offset="1" class="silozpblh"/></radialGradient><radialGradient id="idr8buc" cx="0" cy="0" r="1" gradientTransform="rotate(161.565 10.203 10.854)scale(2.22348 3.17216)" gradientUnits="userSpaceOnUse"><stop class="mxnnm4bur"/><stop offset=".629" class="jk5udqbyz"/></radialGradient><radialGradient id="ihyEkkd" cx="0" cy="0" r="1" gradientTransform="rotate(-108.843 14.742 -1.266)scale(2.80034 2.21491)" gradientUnits="userSpaceOnUse"><stop class="hkormb2xp"/><stop offset="1" class="e-twaac7b"/></radialGradient><radialGradient id="iFGRsxe" cx="0" cy="0" r="1" gradientTransform="matrix(1.50392 .15775 -.2556 2.43678 9.827 14.674)" gradientUnits="userSpaceOnUse"><stop class="lgjudcrkd"/><stop offset="1" class="tr7czpf3k"/></radialGradient><radialGradient id="iapLTzT" cx="0" cy="0" r="1" gradientTransform="rotate(107.382 .912 9.59)scale(2.91973 2.69143)" gradientUnits="userSpaceOnUse"><stop offset=".243" class="gcrmpdfop"/><stop offset="1" class="nd--cppfl"/></radialGradient><radialGradient id="iJ0Nzyc" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.71875 -19.3424 0 16 26.989)" gradientUnits="userSpaceOnUse"><stop offset=".315" class="u2-vnsrzx"/><stop offset="1" class="u25v0cb4e"/></radialGradient><radialGradient id="iQ3Jo1d" cx="0" cy="0" r="1" gradientTransform="matrix(-2.6875 0 0 -8.81836 22.928 27.145)" gradientUnits="userSpaceOnUse"><stop offset=".24" class="hztqsacfn"/><stop offset="1" class="g15tcgc_e"/></radialGradient><radialGradient id="iEbtPxb" cx="0" cy="0" r="1" gradientTransform="matrix(1.96876 -8.07812 2.82155 .68765 6.74 29.91)" gradientUnits="userSpaceOnUse"><stop offset=".232" class="y6ictpbdv"/><stop offset="1" class="exer9ybqp"/></radialGradient><radialGradient id="iAPRHYd" cx="0" cy="0" r="1" gradientTransform="rotate(-101.449 24.978 4.726)scale(7.55662 1.96679)" gradientUnits="userSpaceOnUse"><stop class="z2ubpb-up"/><stop offset="1" class="icppbwd3b"/></radialGradient><radialGradient id="iegNxyc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -11.366 .65507 0 22.942 29.91)" gradientUnits="userSpaceOnUse"><stop offset=".443" class="p9dhe0cfb"/><stop offset="1" class="m7r_2tbtp"/></radialGradient><radialGradient id="i6aJFZY" cx="0" cy="0" r="1" gradientTransform="matrix(1.35937 1.64062 -3.29137 2.72714 9.71 21.208)" gradientUnits="userSpaceOnUse"><stop class="tuvqdtb4j"/><stop offset="1" class="mw-6yhbvl"/></radialGradient><radialGradient id="izDA0dI" cx="0" cy="0" r="1" gradientTransform="matrix(1.78125 1.85937 -.47826 .45816 8.381 22.458)" gradientUnits="userSpaceOnUse"><stop offset=".435" class="aok9j0bwd"/><stop offset="1" class="ul3ws4blr"/></radialGradient><radialGradient id="iDMsGJb" cx="0" cy="0" r="1" gradientTransform="matrix(1.3125 .25 -.73637 3.86594 19.569 21.145)" gradientUnits="userSpaceOnUse"><stop offset=".032" class="wcylmi-4x"/><stop offset="1" class="lcybi9bke"/></radialGradient><radialGradient id="izjH7xz" cx="0" cy="0" r="1" gradientTransform="matrix(-1.21875 1.09375 -.16383 -.18256 23.498 22.2)" gradientUnits="userSpaceOnUse"><stop class="dwh48tz1p"/><stop offset="1" class="b5_53rm9x"/></radialGradient><radialGradient id="iuxxmBb" cx="0" cy="0" r="1" gradientTransform="rotate(-169.136 6.388 10.772)scale(1.64141 .91814)" gradientUnits="userSpaceOnUse"><stop offset=".525" class="k5s0mt74t"/><stop offset="1" class="hfobxebps"/></radialGradient><radialGradient id="imtwsXc" cx="0" cy="0" r="1" gradientTransform="matrix(.678 .80592 -1.4278 1.20118 .1 .257)" gradientUnits="userSpaceOnUse"><stop class="w_-x-cc4i"/><stop offset="1" class="xbkp5vbln"/></radialGradient><radialGradient id="icTwalH" cx="0" cy="0" r="1" gradientTransform="matrix(-2.68749 -3.76563 4.9287 -3.51755 18.1 23.91)" gradientUnits="userSpaceOnUse"><stop class="mg6vw6bqp"/><stop offset="1" class="f_x1tcb5s"/></radialGradient><radialGradient id="iFB7LRc" cx="0" cy="0" r="1" gradientTransform="matrix(-.39844 0 0 -.91123 15.538 23.762)" gradientUnits="userSpaceOnUse"><stop offset=".244" class="w_5lucbuv"/><stop offset="1" class="x_olikxjr"/></radialGradient><radialGradient id="i7g7vQc" cx="0" cy="0" r="1" gradientTransform="rotate(74.046 -5.836 21.01)scale(2.11262 4.94248)" gradientUnits="userSpaceOnUse"><stop offset=".417" class="ay981bbmw"/><stop offset="1" class="co8373ibr"/></radialGradient><radialGradient id="iNsLlse" cx="0" cy="0" r="1" gradientTransform="rotate(51.989 -14.74 27.087)scale(1.72534 2.83656)" gradientUnits="userSpaceOnUse"><stop class="t47nmfbtz"/><stop offset="1" class="wu9sp8brv"/></radialGradient><radialGradient id="itFpnJb" cx="0" cy="0" r="1" gradientTransform="matrix(-.71875 .59375 -.75915 -.91896 17.85 25.16)" gradientUnits="userSpaceOnUse"><stop class="x2r0w67qw"/><stop offset="1" class="e2y-fbcxj"/></radialGradient><radialGradient id="iOrZVKb" cx="0" cy="0" r="1" gradientTransform="matrix(-.71875 .59375 -.75915 -.91896 17.85 28.16)" gradientUnits="userSpaceOnUse"><stop class="x2r0w67qw"/><stop offset="1" class="e2y-fbcxj"/></radialGradient><radialGradient id="irCMJ4r" cx="0" cy="0" r="1" gradientTransform="matrix(2.48905 -1.13139 1.38138 3.03902 20.008 16)" gradientUnits="userSpaceOnUse"><stop offset=".64" class="ayiod_bfg"/><stop offset=".944" class="wb78_hxsc"/></radialGradient><radialGradient id="i4gZ4kd" cx="0" cy="0" r="1" gradientTransform="matrix(1.31577 .7375 -.2085 .37199 21.039 13.88)" gradientUnits="userSpaceOnUse"><stop class="s9u3_wbrp"/><stop offset="1" class="crde6o_5i"/></radialGradient><radialGradient id="ic5idHb" cx="0" cy="0" r="1" gradientTransform="matrix(1.50989 -.11231 .0878 1.18032 20.36 15.674)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="rmmi4abgs"/><stop offset="1" class="xuyenabum"/></radialGradient><radialGradient id="inOgopx" cx="0" cy="0" r="1" gradientTransform="matrix(-1.20681 0 0 -.95203 11.22 15.562)" gradientUnits="userSpaceOnUse"><stop offset=".667" class="pj2ff5nxp"/><stop offset="1" class="sdufqstmc"/></radialGradient><radialGradient id="iMFRwLL" cx="0" cy="0" r="1" gradientTransform="matrix(-6.50358 2.99902 -4.01413 -8.70492 18.828 15.024)" gradientUnits="userSpaceOnUse"><stop class="aj61gebdf"/><stop offset="1" class="v2xpqhbrh"/></radialGradient><radialGradient id="iD3Jf8b" cx="0" cy="0" r="1" gradientTransform="rotate(154.513 7.104 9.946)scale(2.25599 1.57104)" gradientUnits="userSpaceOnUse"><stop class="o3k0towjz"/><stop offset="1" class="x7h3p2bdy"/></radialGradient><radialGradient id="i4SXE6b" cx="0" cy="0" r="1" gradientTransform="matrix(1.0735 -3.47607 4.41049 1.36207 13.788 21.807)" gradientUnits="userSpaceOnUse"><stop class="cctx1cb1y"/><stop offset="1" class="xfmbn4_bb"/></radialGradient><radialGradient id="ig8nRLW" cx="0" cy="0" r="1" gradientTransform="rotate(96.727 1.507 14.929)scale(6.84714 6.88381)" gradientUnits="userSpaceOnUse"><stop offset=".727" class="m6mmhsf1n"/><stop offset="1" class="do3fwrbgr"/></radialGradient><radialGradient id="iMx4VSd" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.56691 -6.60207 0 15.707 15.414)" gradientUnits="userSpaceOnUse"><stop offset=".794" class="d0fyzsbqc"/><stop offset="1" class="n8ysctycz"/></radialGradient><radialGradient id="i0U9FNc" cx="0" cy="0" r="1" gradientTransform="rotate(168.897 8.075 9.242)scale(7.03739 12.1162)" gradientUnits="userSpaceOnUse"><stop offset=".795" class="f6uv1pf_h"/><stop offset="1" class="fp6zmm73k"/></radialGradient><radialGradient id="i4IxQjb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.15077 1.41231 0 18.27 14.606)" gradientUnits="userSpaceOnUse"><stop class="yv4uycbmh"/><stop offset="1" class="wgpm0ibqw"/></radialGradient><radialGradient id="i8bd7ye" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.31251 1.50423 0 13.892 14.377)" gradientUnits="userSpaceOnUse"><stop class="f82mfcbsw"/><stop offset="1" class="xkhh7vb2n"/></radialGradient><radialGradient id="ihZRuTc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.28528 0 0 -6.44557 21.064 16.093)" gradientUnits="userSpaceOnUse"><stop class="jids0zpwm"/><stop offset="1" class="zz4mcgrzh"/></radialGradient><radialGradient id="iEyHjAr" cx="0" cy="0" r="1" gradientTransform="matrix(-1.829 1.57435 -1.05517 -1.22584 19.89 20.14)" gradientUnits="userSpaceOnUse"><stop class="ybvm9tprh"/><stop offset=".694" class="yxwqgvbem"/></radialGradient><radialGradient id="it2w3Cc" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.03177 -7.03807 0 15.969 13.737)" gradientUnits="userSpaceOnUse"><stop offset=".255" class="gel4aubhu"/><stop offset="1" class="m62_f2b8o"/></radialGradient><radialGradient id="ivm4Kle" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.14878 -7.03697 0 15.969 16.093)" gradientUnits="userSpaceOnUse"><stop offset=".804" class="w75ubxqjn"/><stop offset="1" class="i8o1bfbix"/></radialGradient><radialGradient id="ieLitUd" cx="0" cy="0" r="1" gradientTransform="matrix(-.45554 -2.04401 .62995 -.1404 16.753 16.82)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="x_sue_b_g"/><stop offset="1" class="gl9okfban"/></radialGradient><radialGradient id="id2bzZc" cx="0" cy="0" r="1" gradientTransform="matrix(-.7794 0 0 -.2179 16.514 17.032)" gradientUnits="userSpaceOnUse"><stop class="t5djkhb4t"/><stop offset="1" class="qm132ccsa"/></radialGradient><radialGradient id="io3EaRb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.29049 0 18.15 14.965)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="i9Nolwb" cx="0" cy="0" r="1" gradientTransform="matrix(-.23192 -.29886 .41145 -.3193 17.923 15.049)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iLG3rXc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.2905 0 13.787 14.965)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iNXynfc" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 14.224 .947)scale(.49412 .59395)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iWLVOVc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -12.3535 18.2706 0 15.953 14.155)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="guwslmx9m"/><stop offset="1" class="csva0fh9x"/></radialGradient><radialGradient id="i2pBBLt" cx="0" cy="0" r="1" gradientTransform="rotate(-179.736 10.798 2.33)scale(6.78132 1.9151)" gradientUnits="userSpaceOnUse"><stop class="ak4i8vy1v"/><stop offset="1" class="d0nv29baz"/></radialGradient><radialGradient id="iyBJvOb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.46875 -.51569 0 21.381 16.27)" gradientUnits="userSpaceOnUse"><stop class="qqll8tbvj"/><stop offset="1" class="i1pxvjzop"/></radialGradient><filter id="i86sG1b" width="15.268" height="15.768" x="8.46" y="6.283" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.121569 0 0 0 0 0.0705882 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2838"/></filter><filter id="ir3azmc" width="4.755" height="3.491" x="8.464" y="20.061" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy="-.1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.262745 0 0 0 0 0.172549 0 0 0 0 0.309804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2838"/></filter><filter id="ivknJvd" width="4.705" height="3.591" x="18.753" y="19.961" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.270588 0 0 0 0 0.172549 0 0 0 0 0.309804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2838"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.266667 0 0 0 0 0.0666667 0 0 0 0 0.219608 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2838" result="effect2_innerShadow_4002_2838"/></filter><filter id="iKzJrad" width="2.189" height="2.153" x="8.842" y="21.167" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2838" stdDeviation=".25"/></filter><filter id="isZwa0X" width="1.692" height="1.595" x="21.111" y="21.394" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2838" stdDeviation=".125"/></filter><filter id="i0pcMoC" width="7.744" height="9.694" x="12.072" y="14.826" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.384314 0 0 0 0 0.47451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2838"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.384314 0 0 0 0 0.47451 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2838" result="effect2_innerShadow_4002_2838"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.172549 0 0 0 0 0.372549 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_2838" result="effect3_innerShadow_4002_2838"/></filter><filter id="ig0ccud" width="2.09" height="2.09" x="16.395" y="24.399" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2838" stdDeviation=".25"/></filter><filter id="i1LlF4b" width="2.09" height="2.09" x="16.395" y="27.399" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2838" stdDeviation=".25"/></filter><filter id="iETJxqb" width="3.368" height="3.218" x="9.526" y="13.952" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.337255 0 0 0 0 0.266667 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2838"/></filter><filter id="iKACenb" width="3.218" height="3.468" x="19.187" y="13.702" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.184314 0 0 0 0 0.0901961 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2838"/></filter><filter id="ifcteic" width="3.148" height="3.148" x="19.222" y="13.988" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2838" stdDeviation=".25"/></filter><filter id="i5YbI4Y" width="2.648" height="2.648" x="9.83" y="14.238" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2838" stdDeviation=".125"/></filter><filter id="issdSJc" width="10.691" height="11.327" x="10.373" y="10.455" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.14902 0 0 0 0 0.0901961 0 0 0 0 0.0941176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2838"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.75" dy="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.188235 0 0 0 0 0.109804 0 0 0 0 0.141176 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2838" result="effect2_innerShadow_4002_2838"/></filter><filter id="iDydXKc" width="2.877" height="3.682" x="14.368" y="14.556" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2838" stdDeviation=".25"/></filter><filter id="iZqlpPc" width="2.377" height="3.182" x="14.78" y="14.668" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2838" stdDeviation=".125"/></filter><filter id="i1zX9Xd" width="2.377" height="3.182" x="14.78" y="14.487" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2838" stdDeviation=".125"/></filter><filter id="icver2O" width="3.702" height="1.526" x="14.117" y="17.91" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2838" stdDeviation=".05"/></filter><filter id="iKHBE7d" width="3.001" height="1.285" x="16.911" y="14.157" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0941176 0 0 0 0 0.0666667 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2838"/></filter><filter id="idxOpjo" width="3.001" height="1.285" x="12.025" y="14.157" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0862745 0 0 0 0 0.054902 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2838"/></filter><filter id="iLOVfJd" width=".787" height=".696" x="17.417" y="14.525" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2838" stdDeviation=".05"/></filter><filter id="iuLVkKN" width=".891" height=".913" x="18.256" y="14.6" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2838" stdDeviation=".1"/></filter><filter id="ijsDHeH" width=".986" height="1.04" x="13.814" y="14.537" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2838" stdDeviation=".1"/></filter><filter id="ipUJdLx" width=".913" height=".705" x="13.059" y="14.517" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2838" stdDeviation=".05"/></filter><filter id="iWzG3cb" width="13.655" height="12.317" x="9.076" y="1.839" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.282353 0 0 0 0 0.203922 0 0 0 0 0.364706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2838"/></filter><filter id="icLiyue" width="10.882" height="7.996" x="10.499" y="14.055" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.803922 0 0 0 0 0.635294 0 0 0 0 0.886275 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2838"/></filter><linearGradient id="igL0Bud" x1="20.662" x2="13.857" y1="8.609" y2="21.213" gradientUnits="userSpaceOnUse"><stop class="hjtn79bml"/><stop offset="1" class="a4-v90a8k"/></linearGradient><linearGradient id="iu4BL0y" x1="9.026" x2="9.233" y1="29.911" y2="29.911" gradientUnits="userSpaceOnUse"><stop class="g-00mbcgn"/><stop offset="1" class="tvzw53atw"/></linearGradient><linearGradient id="i6kQckA" x1="22.975" x2="22.827" y1="29.911" y2="29.911" gradientUnits="userSpaceOnUse"><stop offset=".118" class="yacpd-mqw"/><stop offset="1" class="m2jbcqdpu"/></linearGradient><linearGradient id="imxslwc" x1="9.397" x2="8.084" y1="29.739" y2="29.739" gradientUnits="userSpaceOnUse"><stop class="s2ol_bbam"/><stop offset="1" class="hm-si4p_s"/></linearGradient><linearGradient id="iYKVIWb" x1="15.984" x2="15.984" y1="23.197" y2="29.911" gradientUnits="userSpaceOnUse"><stop class="ty59qw5cn"/><stop offset="1" class="jwfvhhlnv"/></linearGradient><linearGradient id="iDWpPDG" x1="16.479" x2="16.147" y1="27.271" y2="27.271" gradientUnits="userSpaceOnUse"><stop class="z_332kbzw"/><stop offset="1" class="v6fzn4zbl"/></linearGradient><linearGradient id="icGpVve" x1="8.784" x2="23.16" y1="20.371" y2="20.371" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="isLpFne" x1="8.784" x2="23.16" y1="20.341" y2="20.341" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="i5DGjTb" x1="9.526" x2="12.485" y1="15.649" y2="15.649" gradientUnits="userSpaceOnUse"><stop class="z_wfxjr5n"/><stop offset="1" class="qenr6bbwz"/></linearGradient><linearGradient id="iZGA7Ne" x1="15.03" x2="15.969" y1="16.893" y2="16.893" gradientUnits="userSpaceOnUse"><stop class="o6hm6qxaj"/><stop offset="1" class="mg63gccek"/></linearGradient><linearGradient id="iA2vqjc" x1="15.969" x2="15.969" y1="17.692" y2="17.082" gradientUnits="userSpaceOnUse"><stop class="cctx1cb1y"/><stop offset="1" class="xfmbn4_bb"/></linearGradient><linearGradient id="iSbzHye" x1="15.969" x2="15.969" y1="14.737" y2="15.972" gradientUnits="userSpaceOnUse"><stop class="w8z128b_w"/><stop offset="1" class="y9j9od0au"/></linearGradient><linearGradient id="iquHSpb" x1="14.904" x2="15.365" y1="19.102" y2="18.39" gradientUnits="userSpaceOnUse"><stop class="xt1sudijz"/><stop offset=".663" class="zsqh37b9g"/></linearGradient><linearGradient id="iE9NuWE" x1="18.929" x2="18.615" y1="15.019" y2="15.212" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i6fdTud" x1="14.53" x2="14.217" y1="15.019" y2="15.212" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iyKRZUc" x1="19.866" x2="12.585" y1="11.708" y2="11.708" gradientUnits="userSpaceOnUse"><stop class="j8rdzr3lb"/><stop offset=".554" class="h5foydtlz"/><stop offset="1" class="roy3-sbpo"/></linearGradient><linearGradient id="iC5hH6b" x1="9.71" x2="12.428" y1="11.989" y2="11.989" gradientUnits="userSpaceOnUse"><stop class="bamb_e30h"/><stop offset="1" class="szoje-bkc"/></linearGradient><linearGradient id="isYcgqc" x1="16.538" x2="16.538" y1="14.155" y2="13.88" gradientUnits="userSpaceOnUse"><stop class="ip1t-iw4f"/><stop offset="1" class="l0ic_xblz"/></linearGradient><linearGradient id="iU1wwRb" x1="21.116" x2="15.022" y1="18.489" y2="18.489" gradientUnits="userSpaceOnUse"><stop class="it4bksbcb"/><stop offset="1" class="twe7w31pl"/></linearGradient><linearGradient id="i7n11Wc" x1="15.94" x2="15.94" y1="13.927" y2="16.029" gradientUnits="userSpaceOnUse"><stop class="x-67tmbrg"/><stop offset="1" class="bkz397hyg"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-guard-dark" /></template>
<style>
.a4-v90a8k {
  stop-color: var(--svg-color--1a1718, #1A1718);
}

.a7obdqv4r {
  fill: var(--svg-color--554b59, #554B59);
  d: path("M20.046 20.16c1.364.419 2.538 1.308 3.179 1.936a.46.46 0 0 1-.011.659l-.65.65a.523.523 0 0 1-.704.02a12.3 12.3 0 0 0-3.107-1.858z");
}

.aj61gebdf {
  stop-color: var(--svg-color--4f322e, #4F322E);
}

.ak4i8vy1v {
  stop-color: var(--svg-color--686070, #686070);
}

.aok9j0bwd {
  stop-color: var(--svg-color--4b4551, #4B4551);
}

.ay981bbmw {
  stop-color: var(--svg-color--452139, #452139);
}

.ayiod_bfg {
  stop-color: var(--svg-color--493033, #493033);
}

.b4n-hsbxm {
  cx: 17.439px;
  cy: 28.444px;
  r: 0.545px;
  fill: var(--svg-color--f6265e, #F6265E);
}

.b5_53rm9x {
  stop-color: var(--svg-color--5e5864, #5E5864);
  stop-opacity: 0;
}

.b7gs5bban {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.36 14.216c.653 0 1.205.45 1.355 1.058a.274.274 0 0 1-.268.341h-2.231a.23.23 0 0 1-.227-.272c.125-.64.69-1.127 1.37-1.127");
}

.bamb_e30h {
  stop-color: var(--svg-color--4d4c50, #4D4C50);
}

.bc53okb3o {
  fill: var(--svg-color--4c4b4d, #4C4B4D);
  d: path("M17.11 14.993c.266-.467.67-.836 1.538-.836c.38 0 .747.105 1.073.369c.269.217.233.495.025.599l-.556.317c-.652-.21-1.373-.239-2.08-.45");
}

.bkz397hyg {
  stop-color: var(--svg-color--c7aed9, #C7AED9);
  stop-opacity: 0;
}

.bl7uysvvb {
  stop-color: var(--svg-color--181518, #181518);
}

.bx1dz9qpc {
  d: path("M13.785 14.488a.893.893 0 0 0-.86 1.127h1.724a1 1 0 0 0 .032-.235a.9.9 0 0 0-.896-.893");
}

.c_x9vzbvj {
  fill: var(--svg-color--000, #000);
  d: path("M14.296 15.38a.51.51 0 0 0-.511-.511a.51.51 0 0 0-.455.746h.905a.5.5 0 0 0 .06-.235");
}

.c9_6uxbfa {
  stop-color: var(--svg-color--4a4446, #4A4446);
  stop-opacity: 0;
}

.cad66eb8i {
  cx: 17.494px;
  cy: 28.374px;
  r: 0.545px;
}

.cctx1cb1y {
  stop-color: var(--svg-color--3a1f30, #3A1F30);
}

.chj8m5e2t {
  stop-color: var(--svg-color--040101, #040101);
  stop-opacity: 0;
}

.cj4rfmfkx {
  stop-color: var(--svg-color--3b3638, #3B3638);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.co8373ibr {
  stop-color: var(--svg-color--452139, #452139);
  stop-opacity: 0;
}

.crde6o_5i {
  stop-color: var(--svg-color--402824, #402824);
  stop-opacity: 0;
}

.csva0fh9x {
  stop-color: var(--svg-color--403947, #403947);
}

.d0e6vrb_a {
  cx: 17.439px;
  cy: 25.444px;
  r: 0.545px;
  fill: var(--svg-color--f6265e, #F6265E);
}

.d0fyzsbqc {
  stop-color: var(--svg-color--3b232b, #3B232B);
  stop-opacity: 0;
}

.d0nv29baz {
  stop-color: var(--svg-color--686070, #686070);
  stop-opacity: 0;
}

.do3fwrbgr {
  stop-color: var(--svg-color--3f243b, #3F243B);
}

.dwh48tz1p {
  stop-color: var(--svg-color--5e5864, #5E5864);
}

.e-twaac7b {
  stop-color: var(--svg-color--575455, #575455);
  stop-opacity: 0;
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e2h-54bmv {
  d: path("M10.882 14.3h.012l-.01-.266l-.01-.306c.02-.95.574-1.316.81-1.439l.05-.02l.052-.02a2.3 2.3 0 0 0 1.19-1.235l.082-.194a.264.264 0 0 1 .461-.051a3.86 3.86 0 0 0 3.19 1.673h3.22c.18 0 1.082.088 1.135 1.332l-.119 3.074c-.123 2.802-2.311 4.684-4.983 4.684s-4.86-1.882-4.983-4.684z");
}

.e2y-fbcxj {
  stop-color: var(--svg-color--fca239, #FCA239);
}

.e4qvstbaw {
  d: path("M20.046 20.16c1.364.419 2.538 1.308 3.179 1.936a.46.46 0 0 1-.011.659l-.65.65a.523.523 0 0 1-.704.02a12.3 12.3 0 0 0-3.107-1.858z");
}

.eikz_kwmc {
  d: path("M18.087 14.676c.064.085-.07.189-.22.302c-.151.113-.264.192-.327.107c-.064-.085.007-.245.158-.358s.326-.136.39-.05");
}

.exer9ybqp {
  stop-color: var(--svg-color--b13b50, #B13B50);
}

.f_x1tcb5s {
  stop-color: var(--svg-color--482949, #482949);
}

.f2pe0nb3d {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.578 14.216c-.653 0-1.205.45-1.355 1.058a.274.274 0 0 0 .268.341h2.23a.23.23 0 0 0 .228-.272a1.4 1.4 0 0 0-1.371-1.127");
}

.f6uv1pf_h {
  stop-color: var(--svg-color--5e4543, #5E4543);
  stop-opacity: 0;
}

.f82mfcbsw {
  stop-color: var(--svg-color--371e27, #371E27);
}

.fp6zmm73k {
  stop-color: var(--svg-color--5e4543, #5E4543);
}

.ft5dv1b6b {
  fill: none;
}

.fvifkjh5i {
  cx: 9.886px;
  cy: 22.154px;
  rx: 0.641px;
  ry: 0.524px;
}

.g-00mbcgn {
  stop-color: var(--svg-color--c2254a, #C2254A);
}

.g0r7omboq {
  stop-color: var(--svg-color--474445, #474445);
  stop-opacity: 0;
}

.g15tcgc_e {
  stop-color: var(--svg-color--ff6085, #FF6085);
  stop-opacity: 0;
}

.g4mvl20po {
  d: path("M15.49 23.203v6.708h.989v-6.714a2 2 0 0 1-.409.042h-.203q-.194 0-.377-.036");
}

.gcrmpdfop {
  stop-color: var(--svg-color--585352, #585352);
}

.gel4aubhu {
  stop-color: var(--svg-color--331b27, #331B27);
}

.gl9okfban {
  stop-color: var(--svg-color--634d4b, #634D4B);
  stop-opacity: 0;
}

.glo437b-m {
  stop-color: var(--svg-color--040002, #040002);
  stop-opacity: 0;
}

.guwslmx9m {
  stop-color: var(--svg-color--403947, #403947);
  stop-opacity: 0;
}

.gvxstr-td {
  d: path("M11.135 17.17a1.61 1.61 0 1 0 0-3.218a1.61 1.61 0 0 0 0 3.219");
}

.gwyjgcc6d {
  fill-rule: evenodd;
  d: path("M23.154 16.971c.212-.435.324-.92.324-1.427c0-.467-.096-.905-.269-1.305h.006a3 3 0 0 0-.282-.513l-.002-.003a3.24 3.24 0 0 1-.526-1.771v-.01a3.3 3.3 0 0 0-3.299-3.3a.54.54 0 0 1-.455-.232a3.3 3.3 0 0 0-2.682-1.377a3.3 3.3 0 0 0-2.682 1.377a.56.56 0 0 1-.456.233h-.085a3.3 3.3 0 0 0-3.214 3.299v.01a3.24 3.24 0 0 1-.526 1.77l-.002.005a3.3 3.3 0 0 0-.22 3.244c.07.142.07.314 0 .456a3.213 3.213 0 0 0 2.894 4.625h8.582a3.213 3.213 0 0 0 2.894-4.625a.52.52 0 0 1 0-.456M10.894 14.3h-.012l1.198 2.355c.123 2.803 1.217 0 3.889 0s3.836 3.12 3.96.317l1.135-3.197c-.053-1.245-.956-1.332-1.136-1.332h-3.22a3.86 3.86 0 0 1-3.189-1.673a.264.264 0 0 0-.461.05l-.082.195c-.226.56-.657.99-1.19 1.234l-.051.02l-.051.02c-.236.123-.79.49-.81 1.44l.01.306z");
}

.h_j9u0wvt {
  stop-color: var(--svg-color--e6e6e6, #E6E6E6);
}

.h5foydtlz {
  stop-color: var(--svg-color--4b3c5b, #4B3C5B);
}

.h83slyb1a {
  d: path("M9.058 29.91h-3.63a9.98 9.98 0 0 1 3.63-7.354z");
}

.h8qkcsbic {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.087 14.676c.064.085-.07.189-.22.302c-.151.113-.264.192-.327.107c-.064-.085.007-.245.158-.358s.326-.136.39-.05");
}

.hfobxebps {
  stop-color: var(--svg-color--dcb144, #DCB144);
}

.hjtn79bml {
  stop-color: var(--svg-color--393134, #393134);
}

.hkormb2xp {
  stop-color: var(--svg-color--575455, #575455);
}

.hm-si4p_s {
  stop-color: var(--svg-color--c9345b, #C9345B);
  stop-opacity: 0;
}

.hrbrxdb4k {
  d: path("M18.948 15.263a.84.84 0 0 0-.232-.463l-.26.285l.118.228z");
}

.hx66smwtj {
  stop-color: var(--svg-color--4a4446, #4A4446);
}

.hztqsacfn {
  stop-color: var(--svg-color--ff6085, #FF6085);
}

.i16488b3m {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M15.969 18.473c-.521 0-1.01-.125-1.422-.344c-.14-.073-.292.088-.203.22a1.932 1.932 0 0 0 3.25 0c.088-.137-.063-.293-.204-.22a3 3 0 0 1-1.421.344Z");
}

.i1pxvjzop {
  stop-color: var(--svg-color--f6dcf7, #F6DCF7);
  stop-opacity: 0;
}

.i8o1bfbix {
  stop-color: var(--svg-color--55233a, #55233A);
}

.i8us91y_g {
  d: path("M11.926 20.16c-1.363.419-2.538 1.308-3.179 1.936a.46.46 0 0 0 .011.659l.65.65a.523.523 0 0 0 .705.02a12.3 12.3 0 0 1 3.106-1.858z");
}

.icppbwd3b {
  stop-color: var(--svg-color--e34c67, #E34C67);
}

.if6aw8aev {
  d: path("M16.324 20.342c.25.01.51.03.77.05c-.26-.02-.51-.04-.77-.05");
}

.ip1t-iw4f {
  stop-color: var(--svg-color--462659, #462659);
}

.it4bksbcb {
  stop-color: var(--svg-color--dfc6ed, #DFC6ED);
}

.j8rdzr3lb {
  stop-color: var(--svg-color--5d536a, #5D536A);
}

.jids0zpwm {
  stop-color: var(--svg-color--59403d, #59403D);
}

.jk5udqbyz {
  stop-color: var(--svg-color--464444, #464444);
  stop-opacity: 0;
}

.jpermjesn {
  cx: 13.515px;
  cy: 14.869px;
  rx: 0.39px;
  ry: 0.197px;
}

.jwfvhhlnv {
  stop-color: var(--svg-color--d8bbeb, #D8BBEB);
}

.jy-abr9zo {
  d: path("m15.586 15.2l-.531 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.53-1.7c-.115-.376-.646-.376-.766 0");
}

.k0sl1tber {
  d: path("m15.586 15.019l-.531 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.53-1.7c-.115-.377-.646-.377-.766 0");
}

.k5s0mt74t {
  stop-color: var(--svg-color--cc981a, #CC981A);
}

.kav9ef57d {
  width: 4.141px;
  height: 5.141px;
  x: 13.898px;
  y: 18.098px;
  rx: 1.969px;
}

.kbl3igr5c {
  stop-color: var(--svg-color--040002, #040002);
}

.kt__1405u {
  stop-color: var(--svg-color--ccc, #CCC);
}

.kviyf7blg {
  fill: var(--svg-color--331b25, #331B25);
  d: path("m15.576 15.339l-.683 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.531-1.7c-.114-.377-.494-.377-.613 0");
}

.l_96kr3kr {
  fill: var(--svg-color--4c3637, #4C3637);
  d: path("M20.796 16.636a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.l0ic_xblz {
  stop-color: var(--svg-color--462659, #462659);
  stop-opacity: 0;
}

.l0xg-rbdf {
  stop-color: var(--svg-color--040101, #040101);
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.lcybi9bke {
  stop-color: var(--svg-color--513f4e, #513F4E);
  stop-opacity: 0;
}

.lgjudcrkd {
  stop-color: var(--svg-color--413733, #413733);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.m2jbcqdpu {
  stop-color: var(--svg-color--fc356b, #FC356B);
  stop-opacity: 0;
}

.m62_f2b8o {
  stop-color: var(--svg-color--331b27, #331B27);
  stop-opacity: 0;
}

.m6mmhsf1n {
  stop-color: var(--svg-color--3f243b, #3F243B);
  stop-opacity: 0;
}

.m7r_2tbtp {
  stop-color: var(--svg-color--ee5076, #EE5076);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mg63gccek {
  stop-color: var(--svg-color--3d2928, #3D2928);
  stop-opacity: 0;
}

.mg6vw6bqp {
  stop-color: var(--svg-color--5d4364, #5D4364);
}

.mw-6yhbvl {
  stop-color: var(--svg-color--382834, #382834);
}

.mxnnm4bur {
  stop-color: var(--svg-color--464444, #464444);
}

.n11xmqb_x {
  fill: var(--svg-color--3e3138, #3E3138);
  rx: 0.641px;
  ry: 0.494px;
}

.n2jxlwzra {
  d: path("M11.154 16.636a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.n8ysctycz {
  stop-color: var(--svg-color--2b151b, #2B151B);
}

.nd--cppfl {
  stop-color: var(--svg-color--585352, #585352);
  stop-opacity: 0;
}

.nesqdcchf {
  d: path("M18.153 14.488a.892.892 0 0 1 .86 1.127h-1.724a.896.896 0 0 1 .864-1.128");
}

.nz9di63yp {
  d: path("M14.6 15.275c0-.288-.234-.48-.298-.538l-.288.278l.177.362z");
}

.o3k0towjz {
  stop-color: var(--svg-color--533632, #533632);
}

.o6hm6qxaj {
  stop-color: var(--svg-color--3d2928, #3D2928);
}

.o91iu5btx {
  d: path("M20.796 16.636a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.p9dhe0cfb {
  stop-color: var(--svg-color--e11c59, #E11C59);
}

.paonnib9g {
  stop-color: var(--svg-color--474445, #474445);
}

.pj2ff5nxp {
  stop-color: var(--svg-color--2d181a, #2D181A);
  stop-opacity: 0;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.qenr6bbwz {
  stop-color: var(--svg-color--2a1c1f, #2A1C1F);
}

.qhplrx0mg {
  fill: var(--svg-color--5a595b, #5A595B);
  d: path("M14.827 14.993c-.266-.467-.67-.836-1.538-.836c-.38 0-.746.105-1.072.369c-.27.217-.233.495-.025.599l.556.317c.652-.21 1.373-.239 2.079-.45");
}

.qm132ccsa {
  stop-color: var(--svg-color--655251, #655251);
  stop-opacity: 0;
}

.qqll8tbvj {
  stop-color: var(--svg-color--f6dcf7, #F6DCF7);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qwp4ni-tf {
  stop-color: var(--svg-color--171418, #171418);
  stop-opacity: 0;
}

.qyeoy6a8h {
  width: 7.594px;
  height: 9.594px;
  x: 12.172px;
  y: 14.927px;
  rx: 3.797px;
}

.r_v2kebuk {
  stop-color: var(--svg-color--181518, #181518);
  stop-opacity: 0;
}

.rmmi4abgs {
  stop-color: var(--svg-color--371d1f, #371D1F);
  stop-opacity: 0;
}

.rot26fbzl {
  cx: 13.515px;
  cy: 14.869px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.roy3-sbpo {
  stop-color: var(--svg-color--393341, #393341);
}

.s2ol_bbam {
  stop-color: var(--svg-color--ac394e, #AC394E);
}

.s9u3_wbrp {
  stop-color: var(--svg-color--402824, #402824);
}

.sdufqstmc {
  stop-color: var(--svg-color--2d181a, #2D181A);
}

.si-u7d6wp {
  cx: 9.937px;
  cy: 22.243px;
  fill: var(--svg-color--321f22, #321F22);
  rx: 0.641px;
  ry: 0.524px;
}

.silozpblh {
  stop-color: var(--svg-color--3b3638, #3B3638);
  stop-opacity: 0;
}

.sllpz02jo {
  d: path("M22.942 29.91h3.63a9.98 9.98 0 0 0-3.63-7.354z");
}

.sx6q1cbyi {
  cx: 17.494px;
  cy: 25.374px;
  r: 0.545px;
}

.szoje-bkc {
  stop-color: var(--svg-color--393341, #393341);
  stop-opacity: 0;
}

.t47nmfbtz {
  stop-color: var(--svg-color--351720, #351720);
}

.t5djkhb4t {
  stop-color: var(--svg-color--655251, #655251);
}

.tr7czpf3k {
  stop-color: var(--svg-color--413733, #413733);
  stop-opacity: 0;
}

.tto44ccna {
  rx: 0.641px;
  ry: 0.524px;
}

.tuvqdtb4j {
  stop-color: var(--svg-color--454048, #454048);
}

.tvzw53atw {
  stop-color: var(--svg-color--c2254a, #C2254A);
  stop-opacity: 0;
}

.twe7w31pl {
  stop-color: var(--svg-color--c9b0d8, #C9B0D8);
}

.ty59qw5cn {
  stop-color: var(--svg-color--dbb8dd, #DBB8DD);
}

.u2-vnsrzx {
  stop-color: var(--svg-color--f73c71, #F73C71);
}

.u25v0cb4e {
  stop-color: var(--svg-color--d6274f, #D6274F);
}

.u70snkboj {
  fill: var(--svg-color--4a302d, #4A302D);
  d: path("m15.586 15.2l-.531 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.53-1.7c-.115-.376-.646-.376-.766 0");
}

.ul3ws4blr {
  stop-color: var(--svg-color--4b4551, #4B4551);
  stop-opacity: 0;
}

.v2xpqhbrh {
  stop-color: var(--svg-color--402a29, #402A29);
}

.v6fzn4zbl {
  stop-color: var(--svg-color--eacceb, #EACCEB);
  stop-opacity: 0;
}

.vim75kb4b {
  d: path("M10.31 14.155c-.278-.016-.842-.08-1.054-.728c-.11-.37.082-.779.143-.91l.024-.049c.062-.12.152-.297-.02-.577c-.193-.313-.374-.615-.045-1.257c.207-.405.093-.652-.032-.875c-.183-.327-.166-.604 0-.938c.071-.143.173-.275.173-.472c0-.198-.07-.335-.141-.474c-.074-.143-.148-.289-.148-.504c0-.23.084-.398.161-.554c.067-.133.128-.257.128-.402c0-.129-.06-.24-.125-.364c-.094-.178-.201-.38-.164-.69c.071-.59.537-.787.756-.879l.02-.008c.21-.089.364-.163.453-.58c.045-.215.131-.502.292-.663a1.06 1.06 0 0 1 .792-.3c.257.007.534-.03.75-.254c.218-.225.46-.413.7-.453s.472.014.725.144c.281.145.567.07.705-.035c.34-.262.718-.32 1.158-.141c.18.072.295.112.394.112s.214-.04.393-.112c.44-.18.819-.12 1.159.141a.68.68 0 0 0 .704.035c.254-.13.485-.184.725-.144c.241.04.483.228.7.453s.494.261.75.253a1.06 1.06 0 0 1 .793.301c.16.161.247.448.292.663c.088.417.243.491.452.58l.02.008c.22.092.685.288.756.878c.038.31-.07.513-.164.69c-.065.124-.125.236-.125.365c0 .145.062.269.128.402c.078.156.161.324.161.554c0 .215-.074.36-.147.504a.94.94 0 0 0-.105.466c0 .528.496.742.176 1.422c-.125.223-.324.455-.116.86c.329.641.192.955 0 1.268c-.172.28-.082.457-.02.577l.02.041l.004.009c.06.13.252.54.142.909c-.212.649-.775.712-1.054.728z");
}

.w_-x-cc4i {
  stop-color: var(--svg-color--ffff50, #FFFF50);
}

.w_5lucbuv {
  stop-color: var(--svg-color--4a2e4f, #4A2E4F);
}

.w75ubxqjn {
  stop-color: var(--svg-color--55233a, #55233A);
  stop-opacity: 0;
}

.w8z128b_w {
  stop-color: var(--svg-color--381f28, #381F28);
}

.wb78_hxsc {
  stop-color: var(--svg-color--6a5956, #6A5956);
}

.wcylmi-4x {
  stop-color: var(--svg-color--513f4e, #513F4E);
}

.wgpm0ibqw {
  stop-color: var(--svg-color--43272a, #43272A);
  stop-opacity: 0;
}

.wu9sp8brv {
  stop-color: var(--svg-color--492934, #492934);
}

.x_olikxjr {
  stop-color: var(--svg-color--4a2e4f, #4A2E4F);
  stop-opacity: 0;
}

.x_sue_b_g {
  stop-color: var(--svg-color--634d4b, #634D4B);
}

.x-67tmbrg {
  stop-color: var(--svg-color--b593cf, #B593CF);
}

.x-k_p1dly {
  d: path("M20.796 17.17a1.61 1.61 0 1 0 0-3.218a1.61 1.61 0 0 0 0 3.219");
}

.x2r0w67qw {
  stop-color: var(--svg-color--fff153, #FFF153);
}

.x7h3p2bdy {
  stop-color: var(--svg-color--533632, #533632);
  stop-opacity: 0;
}

.xbkp5vbln {
  stop-color: var(--svg-color--f6cf1c, #F6CF1C);
}

.xdn388byj {
  stop-color: var(--svg-color--171418, #171418);
}

.xfmbn4_bb {
  stop-color: var(--svg-color--3a1f30, #3A1F30);
  stop-opacity: 0;
}

.xkhh7vb2n {
  stop-color: var(--svg-color--371e27, #371E27);
  stop-opacity: 0;
}

.xolko2_ao {
  fill: var(--svg-color--35252b, #35252B);
  d: path("M11.154 16.636a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.xt1sudijz {
  stop-color: var(--svg-color--574a4c, #574A4C);
}

.xuyenabum {
  stop-color: var(--svg-color--371d1f, #371D1F);
}

.xzot6tb3a {
  d: path("M5.428 29.91h21.144c-.19-5.355-4.591-9.64-9.994-9.64h-1.156c-5.403 0-9.805 4.285-9.994 9.64");
}

.y6ictpbdv {
  stop-color: var(--svg-color--e43669, #E43669);
}

.y9j9od0au {
  stop-color: var(--svg-color--381f28, #381F28);
  stop-opacity: 0;
}

.yacpd-mqw {
  stop-color: var(--svg-color--fc356b, #FC356B);
}

.ybvm9tprh {
  stop-color: var(--svg-color--594d4d, #594D4D);
}

.ygyxlcb5n {
  d: path("m10.5 14.155l.12 3.518c.082 2.425 2.07 4.379 4.497 4.379h1.677c2.44 0 4.435-1.977 4.498-4.416l.09-3.481h-.909l-.12 3.48c-.049 1.898-1.662 3.487-3.56 3.487h-1.676c-1.887 0-3.489-1.597-3.553-3.483l-.09-3.484z");
}

.yk-5cub9i {
  d: path("M15.994 20.342h-.04c.1 0 .19 0 .29.01c-.08-.01-.17-.01-.25-.01");
}

.yt3n_ccvh {
  fill: var(--svg-color--000, #000);
  d: path("M17.642 15.38a.51.51 0 0 1 .51-.511a.51.51 0 0 1 .455.746h-.904a.46.46 0 0 1-.061-.235");
}

.yv4uycbmh {
  stop-color: var(--svg-color--43272a, #43272A);
}

.yxwqgvbem {
  stop-color: var(--svg-color--594d4d, #594D4D);
  stop-opacity: 0;
}

.z_332kbzw {
  stop-color: var(--svg-color--eacceb, #EACCEB);
}

.z_wfxjr5n {
  stop-color: var(--svg-color--392526, #392526);
}

.z2ubpb-up {
  stop-color: var(--svg-color--ff5c85, #FF5C85);
}

.zobftskva {
  fill: var(--svg-color--2a0219, #2A0219);
  d: path("M15.969 18.473c-.521 0-1.01-.125-1.422-.344c-.14-.073-.292.088-.203.22a1.932 1.932 0 0 0 3.25 0c.088-.137-.063-.293-.204-.22a3 3 0 0 1-1.421.344");
}

.zsqh37b9g {
  stop-color: var(--svg-color--574a4c, #574A4C);
  stop-opacity: 0;
}

.zz4mcgrzh {
  stop-color: var(--svg-color--59403d, #59403D);
  stop-opacity: 0;
}

</style>
