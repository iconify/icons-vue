<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#itOF6Pd)"><path fill="url(#iM3TIFd)" clip-rule="evenodd" class="is1a69b4d"/><path fill="url(#iH8yMxD)" clip-rule="evenodd" class="is1a69b4d"/><path fill="url(#iTVJxZW)" clip-rule="evenodd" class="is1a69b4d"/><path fill="url(#ihWpvWb)" clip-rule="evenodd" class="is1a69b4d"/><path fill="url(#iHYek6b)" clip-rule="evenodd" class="is1a69b4d"/><path fill="url(#i8JLjie)" clip-rule="evenodd" class="is1a69b4d"/><path fill="url(#igXo0Yb)" clip-rule="evenodd" class="is1a69b4d"/><path fill="url(#i7Dsqne)" clip-rule="evenodd" class="is1a69b4d"/><path fill="url(#iB3r9Fc)" clip-rule="evenodd" class="is1a69b4d"/><path fill="url(#iXDjsld)" clip-rule="evenodd" class="is1a69b4d"/><path fill="url(#ibc0vCd)" clip-rule="evenodd" class="is1a69b4d"/></g><path fill="url(#ipxqfNb)" class="c5pyn6kwp"/><path fill="url(#ixtGmqe)" class="c5pyn6kwp"/><path fill="url(#iu4BL0y)" class="c5pyn6kwp"/><path fill="url(#i6kQckA)" class="c5pyn6kwp"/><path fill="url(#ivcbSbu)" class="d42a8nbyx"/><path fill="url(#imxslwc)" class="d42a8nbyx"/><path fill="url(#iCIPAvc)" class="sy7gbya4q"/><path fill="url(#ib2sn4d)" class="sy7gbya4q"/><g filter="url(#iqwA4Wd)"><path fill="url(#i6aJFZY)" class="cd8uxyblt"/><path fill="url(#izDA0dI)" class="cd8uxyblt"/></g><g filter="url(#iSsYCmd)"><path class="v7lobvb0w"/><path fill="url(#i4dkT0d)" class="blsopp2mg"/><path fill="url(#izjH7xz)" class="blsopp2mg"/></g><g filter="url(#iPVtkmd)"><ellipse transform="rotate(-40.534 9.937 22.243)" class="si-u7d6wp"/></g><ellipse fill="url(#iuxxmBb)" transform="rotate(-40.534 9.886 22.154)" class="fvifkjh5i"/><g filter="url(#iBE6GFb)"><ellipse transform="scale(-1 1)rotate(-35.343 23.849 45.555)" class="n11xmqb_x"/></g><ellipse fill="url(#imtwsXc)" transform="scale(-1 1)rotate(-40.534 18.954 40.982)" class="tto44ccna"/><g filter="url(#iBAslYH)"><rect fill="url(#i1U54LR)" class="qyeoy6a8h"/><rect fill="url(#iZgh3lf)" class="qyeoy6a8h"/><rect fill="url(#i7g7vQc)" class="qyeoy6a8h"/></g><rect fill="url(#i55Moxc)" class="gx_0zqbtq"/><path fill="url(#iYKVIWb)" class="g4mvl20po"/><path fill="url(#iDWpPDG)" class="g4mvl20po"/><g filter="url(#ijDAfEF)"><circle class="wfn54lnxd"/></g><g filter="url(#i2obbmB)"><circle class="a1tpsrb8u"/></g><circle fill="url(#iYFehJc)" class="sx6q1cbyi"/><circle fill="url(#iO6rBqd)" class="cad66eb8i"/><path fill="url(#iGfMeIc)" class="if6aw8aev"/><path fill="url(#isLpFne)" class="yk-5cub9i"/><g filter="url(#iaARfac)"><path fill="url(#i6RqZje)" class="h4xnajbet"/></g><g filter="url(#iyuPKJe)"><path fill="url(#iaynVMb)" class="srsu-zbqf"/><path fill="url(#iUqaM0J)" class="srsu-zbqf"/></g><g filter="url(#iyxtb3b)"><path class="czp_i4iyf"/><path fill="url(#iDoFx1d)" class="qynwwbc5y"/></g><g filter="url(#ijaC7Uc)"><path class="rc_bk898j"/><path fill="url(#i95uo9c)" class="tnyz6pflp"/></g><g filter="url(#iMPkzve)"><path fill="url(#iiOVkUb)" class="d3oi1zbdr"/><path fill="url(#iAt8ald)" class="d3oi1zbdr"/><path fill="url(#ihuw8ec)" class="d3oi1zbdr"/><path fill="url(#i9iNlzd)" class="d3oi1zbdr"/><path fill="url(#i3UHdUd)" class="d3oi1zbdr"/><path fill="url(#iKhLsGd)" class="d3oi1zbdr"/><path fill="url(#iBIpH5d)" class="d3oi1zbdr"/><path fill="url(#iwaLrCb)" class="d3oi1zbdr"/></g><g filter="url(#ikmGrgd)"><path class="bhu-9-bus"/></g><g filter="url(#ijNkQme)"><path class="v-z8r6b-c"/><path fill="url(#ik9QKoe)" class="z4th17bal"/><path fill="url(#iGKObhX)" class="z4th17bal"/><path fill="url(#igfDoue)" class="z4th17bal"/><path fill="url(#izTxUtd)" class="z4th17bal"/></g><g filter="url(#ifEgtfc)"><path fill="url(#i3vUYib)" class="v35_ndupb"/></g><g filter="url(#iOwxYgu)"><path stroke="url(#i63IHQe)" class="ot4iumb_e"/></g><path class="rd66zrbmz"/><g filter="url(#ioWxieZ)"><path class="gqqtwubim"/></g><g filter="url(#i4uQT6c)"><path class="l7l5hpb1w"/></g><path class="oamhc07tx"/><path fill="url(#i1iFRxG)" class="tyeec335h"/><path class="l59yayqpc"/><g filter="url(#iFHldDb)"><path class="mjk1u9lsv"/><path fill="url(#igtFGud)" class="is9c70bqb"/></g><g filter="url(#ikTnWVc)"><path fill="url(#iAiKprb)" class="y5cc9h9kl"/></g><path class="qg_d8ubct"/><path fill="url(#id76juc)" class="az8rbc7bc"/><path class="xrlcxenmf"/><g filter="url(#iuI8PGe)"><path fill="url(#ilvCFle)" class="m_vwkvi0t"/></g><g filter="url(#i3JzX4d)"><ellipse transform="rotate(-27.914 13.547 14.869)" class="yk2k5ii1q"/><ellipse fill="url(#iOprDnb)" transform="rotate(-27.914 13.547 14.869)" class="ssttjvbga"/></g><g filter="url(#it2pRjb)"><path fill="url(#iyKRZUc)" class="vim75kb4b"/><path fill="url(#iC5hH6b)" class="vim75kb4b"/></g><path fill="url(#iWLVOVc)" class="vim75kb4b"/><path fill="url(#i2pBBLt)" class="vim75kb4b"/><path fill="url(#isYcgqc)" class="vim75kb4b"/><g filter="url(#ieTtOof)"><path fill="url(#iU1wwRb)" class="u17l1bw1n"/><path fill="url(#i7n11Wc)" class="u17l1bw1n"/><path fill="url(#iyBJvOb)" class="u17l1bw1n"/></g><defs><radialGradient id="iH8yMxD" cx="0" cy="0" r="1" gradientTransform="matrix(-.6034 4.55907 -5.6952 -.75377 15.698 18.063)" gradientUnits="userSpaceOnUse"><stop offset=".591" class="xdn388byj"/><stop offset="1" class="qwp4ni-tf"/></radialGradient><radialGradient id="iTVJxZW" cx="0" cy="0" r="1" gradientTransform="matrix(-2.88301 1.94432 -2.5547 -3.78806 12.883 18.331)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="bl7uysvvb"/><stop offset="1" class="r_v2kebuk"/></radialGradient><radialGradient id="ihWpvWb" cx="0" cy="0" r="1" gradientTransform="rotate(127.405 1.678 10.648)scale(2.15225 1.65263)" gradientUnits="userSpaceOnUse"><stop offset=".334" class="l0xg-rbdf"/><stop offset="1" class="chj8m5e2t"/></radialGradient><radialGradient id="iHYek6b" cx="0" cy="0" r="1" gradientTransform="rotate(121.43 1.947 10.133)scale(2.47506 1.74346)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="kbl3igr5c"/><stop offset="1" class="glo437b-m"/></radialGradient><radialGradient id="i8JLjie" cx="0" cy="0" r="1" gradientTransform="matrix(1.37443 2.61477 -3.62969 1.90792 12.48 7.503)" gradientUnits="userSpaceOnUse"><stop class="paonnib9g"/><stop offset="1" class="g0r7omboq"/></radialGradient><radialGradient id="igXo0Yb" cx="0" cy="0" r="1" gradientTransform="rotate(134.998 8.932 9.313)scale(2.03849 2.84876)" gradientUnits="userSpaceOnUse"><stop class="hx66smwtj"/><stop offset="1" class="c9_6uxbfa"/></radialGradient><radialGradient id="i7Dsqne" cx="0" cy="0" r="1" gradientTransform="matrix(-1.84366 .53637 -1.11855 -3.8448 23.51 14.71)" gradientUnits="userSpaceOnUse"><stop class="cj4rfmfkx"/><stop offset="1" class="silozpblh"/></radialGradient><radialGradient id="iB3r9Fc" cx="0" cy="0" r="1" gradientTransform="rotate(165.963 10.337 10.475)scale(2.90248 3.69733)" gradientUnits="userSpaceOnUse"><stop class="mxnnm4bur"/><stop offset="1" class="jk5udqbyz"/></radialGradient><radialGradient id="iXDjsld" cx="0" cy="0" r="1" gradientTransform="rotate(-108.843 14.757 -1.277)scale(2.80034 2.21491)" gradientUnits="userSpaceOnUse"><stop class="hkormb2xp"/><stop offset="1" class="e-twaac7b"/></radialGradient><radialGradient id="ibc0vCd" cx="0" cy="0" r="1" gradientTransform="matrix(1.50392 .15775 -.2556 2.43678 9.858 14.675)" gradientUnits="userSpaceOnUse"><stop class="lgjudcrkd"/><stop offset="1" class="tr7czpf3k"/></radialGradient><radialGradient id="ipxqfNb" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.71875 -19.3424 0 16 26.99)" gradientUnits="userSpaceOnUse"><stop offset=".315" class="u2-vnsrzx"/><stop offset="1" class="u25v0cb4e"/></radialGradient><radialGradient id="ixtGmqe" cx="0" cy="0" r="1" gradientTransform="matrix(-2.6875 0 0 -8.81836 22.928 27.146)" gradientUnits="userSpaceOnUse"><stop offset=".24" class="hztqsacfn"/><stop offset="1" class="g15tcgc_e"/></radialGradient><radialGradient id="ivcbSbu" cx="0" cy="0" r="1" gradientTransform="matrix(1.96876 -8.07812 2.82155 .68765 6.74 29.911)" gradientUnits="userSpaceOnUse"><stop offset=".232" class="y6ictpbdv"/><stop offset="1" class="exer9ybqp"/></radialGradient><radialGradient id="iCIPAvc" cx="0" cy="0" r="1" gradientTransform="rotate(-101.449 24.978 4.727)scale(7.55662 1.96679)" gradientUnits="userSpaceOnUse"><stop class="z2ubpb-up"/><stop offset="1" class="icppbwd3b"/></radialGradient><radialGradient id="ib2sn4d" cx="0" cy="0" r="1" gradientTransform="matrix(0 -11.366 .65507 0 22.942 29.911)" gradientUnits="userSpaceOnUse"><stop offset=".443" class="p9dhe0cfb"/><stop offset="1" class="m7r_2tbtp"/></radialGradient><radialGradient id="i6aJFZY" cx="0" cy="0" r="1" gradientTransform="matrix(1.35937 1.64062 -3.29137 2.72714 9.71 21.208)" gradientUnits="userSpaceOnUse"><stop class="tuvqdtb4j"/><stop offset="1" class="mw-6yhbvl"/></radialGradient><radialGradient id="izDA0dI" cx="0" cy="0" r="1" gradientTransform="matrix(1.78125 1.85937 -.47826 .45816 8.381 22.458)" gradientUnits="userSpaceOnUse"><stop offset=".435" class="aok9j0bwd"/><stop offset="1" class="ul3ws4blr"/></radialGradient><radialGradient id="i4dkT0d" cx="0" cy="0" r="1" gradientTransform="matrix(1.3125 .25 -.73637 3.86594 19.569 21.146)" gradientUnits="userSpaceOnUse"><stop offset=".032" class="wcylmi-4x"/><stop offset="1" class="lcybi9bke"/></radialGradient><radialGradient id="izjH7xz" cx="0" cy="0" r="1" gradientTransform="matrix(-1.21875 1.09375 -.16383 -.18256 23.498 22.2)" gradientUnits="userSpaceOnUse"><stop class="dwh48tz1p"/><stop offset="1" class="b5_53rm9x"/></radialGradient><radialGradient id="iuxxmBb" cx="0" cy="0" r="1" gradientTransform="rotate(-169.136 6.388 10.772)scale(1.64141 .91814)" gradientUnits="userSpaceOnUse"><stop offset=".525" class="k5s0mt74t"/><stop offset="1" class="hfobxebps"/></radialGradient><radialGradient id="imtwsXc" cx="0" cy="0" r="1" gradientTransform="matrix(.678 .80592 -1.4278 1.20118 .1 .257)" gradientUnits="userSpaceOnUse"><stop class="w_-x-cc4i"/><stop offset="1" class="xbkp5vbln"/></radialGradient><radialGradient id="i1U54LR" cx="0" cy="0" r="1" gradientTransform="matrix(-2.68749 -3.76563 4.9287 -3.51755 18.1 23.911)" gradientUnits="userSpaceOnUse"><stop class="mg6vw6bqp"/><stop offset="1" class="f_x1tcb5s"/></radialGradient><radialGradient id="iZgh3lf" cx="0" cy="0" r="1" gradientTransform="matrix(-.39844 0 0 -.91123 15.538 23.763)" gradientUnits="userSpaceOnUse"><stop offset=".244" class="w_5lucbuv"/><stop offset="1" class="x_olikxjr"/></radialGradient><radialGradient id="i7g7vQc" cx="0" cy="0" r="1" gradientTransform="rotate(74.046 -5.836 21.01)scale(2.11262 4.94248)" gradientUnits="userSpaceOnUse"><stop offset=".417" class="ay981bbmw"/><stop offset="1" class="co8373ibr"/></radialGradient><radialGradient id="i55Moxc" cx="0" cy="0" r="1" gradientTransform="rotate(51.989 -14.741 27.087)scale(1.72534 2.83656)" gradientUnits="userSpaceOnUse"><stop class="gohadn3wh"/><stop offset="1" class="mj-ttbc0m"/></radialGradient><radialGradient id="iYFehJc" cx="0" cy="0" r="1" gradientTransform="matrix(-.71875 .59375 -.75915 -.91896 17.85 25.161)" gradientUnits="userSpaceOnUse"><stop class="x2r0w67qw"/><stop offset="1" class="e2y-fbcxj"/></radialGradient><radialGradient id="iO6rBqd" cx="0" cy="0" r="1" gradientTransform="matrix(-.71875 .59375 -.75915 -.91896 17.85 28.161)" gradientUnits="userSpaceOnUse"><stop class="x2r0w67qw"/><stop offset="1" class="e2y-fbcxj"/></radialGradient><radialGradient id="iaynVMb" cx="0" cy="0" r="1" gradientTransform="rotate(-48.104 28.781 -14.707)scale(2.73591 3.34042)" gradientUnits="userSpaceOnUse"><stop offset=".444" class="w--6bgeqj"/><stop offset=".944" class="sheftacio"/></radialGradient><radialGradient id="iUqaM0J" cx="0" cy="0" r="1" gradientTransform="matrix(1.31576 .7375 -.2085 .37199 21.07 13.88)" gradientUnits="userSpaceOnUse"><stop class="ynae43ovp"/><stop offset="1" class="v-9tn59hb"/></radialGradient><radialGradient id="iDoFx1d" cx="0" cy="0" r="1" gradientTransform="matrix(1.50989 -.11231 .0878 1.18032 20.392 15.674)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="k2oqpgb0o"/><stop offset="1" class="dkw8bsvxv"/></radialGradient><radialGradient id="i95uo9c" cx="0" cy="0" r="1" gradientTransform="matrix(-1.20681 0 0 -.95203 11.203 15.562)" gradientUnits="userSpaceOnUse"><stop offset=".667" class="b55qklbsj"/><stop offset="1" class="uaoaczbhz"/></radialGradient><radialGradient id="iiOVkUb" cx="0" cy="0" r="1" gradientTransform="matrix(-6.50357 2.99901 -3.23936 -7.02477 18.86 15.024)" gradientUnits="userSpaceOnUse"><stop class="zw1wivbgv"/><stop offset=".798" class="pjy1og4qu"/></radialGradient><radialGradient id="iAt8ald" cx="0" cy="0" r="1" gradientTransform="matrix(-3.46116 .45112 -.49796 -3.82051 19.252 16.387)" gradientUnits="userSpaceOnUse"><stop class="z-rzt8b_f"/><stop offset="1" class="tk20gvbnd"/></radialGradient><radialGradient id="ihuw8ec" cx="0" cy="0" r="1" gradientTransform="matrix(1.30737 -3.78806 4.80634 1.6588 13.62 22.353)" gradientUnits="userSpaceOnUse"><stop class="fvm07vbkd"/><stop offset="1" class="n1w64orcn"/></radialGradient><radialGradient id="i9iNlzd" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.72467 -7.78405 0 16 14.807)" gradientUnits="userSpaceOnUse"><stop offset=".668" class="y1lgprrzn"/><stop offset="1" class="by20mjbph"/></radialGradient><radialGradient id="i3UHdUd" cx="0" cy="0" r="1" gradientTransform="rotate(168.897 8.09 9.243)scale(7.03738 12.1162)" gradientUnits="userSpaceOnUse"><stop offset=".795" class="brg8dbpny"/><stop offset="1" class="d_t8kfbgb"/></radialGradient><radialGradient id="iKhLsGd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.15077 1.41231 0 18.301 14.606)" gradientUnits="userSpaceOnUse"><stop class="e2earo80w"/><stop offset="1" class="xl9xm7bnj"/></radialGradient><radialGradient id="iBIpH5d" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.31251 1.50423 0 13.924 14.377)" gradientUnits="userSpaceOnUse"><stop class="suybu51ug"/><stop offset="1" class="intda8ekf"/></radialGradient><radialGradient id="ik9QKoe" cx="0" cy="0" r="1" gradientTransform="matrix(-.45554 -2.04401 .62995 -.1404 16.784 16.82)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="xbgj88f0b"/><stop offset="1" class="y_9l2i5ww"/></radialGradient><radialGradient id="izTxUtd" cx="0" cy="0" r="1" gradientTransform="matrix(-.7794 0 0 -.2179 16.545 17.032)" gradientUnits="userSpaceOnUse"><stop class="qpkqxibzk"/><stop offset="1" class="nwt8glb0m"/></radialGradient><radialGradient id="i1iFRxG" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.29049 0 18.182 14.965)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="igtFGud" cx="0" cy="0" r="1" gradientTransform="matrix(-.23192 -.29886 .41145 -.3193 17.954 15.049)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="id76juc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.2905 0 13.818 14.965)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iOprDnb" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 14.24 .931)scale(.49412 .59395)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iWLVOVc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -12.3535 18.2706 0 15.953 14.155)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="guwslmx9m"/><stop offset="1" class="csva0fh9x"/></radialGradient><radialGradient id="i2pBBLt" cx="0" cy="0" r="1" gradientTransform="rotate(-179.736 10.798 2.33)scale(6.78132 1.9151)" gradientUnits="userSpaceOnUse"><stop class="ak4i8vy1v"/><stop offset="1" class="d0nv29baz"/></radialGradient><radialGradient id="iyBJvOb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.46875 -.51569 0 21.381 16.27)" gradientUnits="userSpaceOnUse"><stop class="qqll8tbvj"/><stop offset="1" class="i1pxvjzop"/></radialGradient><filter id="itOF6Pd" width="15.268" height="15.768" x="8.491" y="6.284" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.121569 0 0 0 0 0.0705882 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2850"/></filter><filter id="iqwA4Wd" width="4.755" height="3.491" x="8.464" y="20.061" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy="-.1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.262745 0 0 0 0 0.172549 0 0 0 0 0.309804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2850"/></filter><filter id="iSsYCmd" width="4.705" height="3.591" x="18.753" y="19.961" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.270588 0 0 0 0 0.172549 0 0 0 0 0.309804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2850"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.266667 0 0 0 0 0.0666667 0 0 0 0 0.219608 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2850" result="effect2_innerShadow_4002_2850"/></filter><filter id="iPVtkmd" width="2.189" height="2.153" x="8.842" y="21.167" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2850" stdDeviation=".25"/></filter><filter id="iBE6GFb" width="1.692" height="1.595" x="21.111" y="21.394" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2850" stdDeviation=".125"/></filter><filter id="iBAslYH" width="7.744" height="9.694" x="12.072" y="14.827" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.384314 0 0 0 0 0.47451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2850"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.384314 0 0 0 0 0.47451 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2850" result="effect2_innerShadow_4002_2850"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.172549 0 0 0 0 0.372549 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_2850" result="effect3_innerShadow_4002_2850"/></filter><filter id="ijDAfEF" width="2.09" height="2.09" x="16.395" y="24.4" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2850" stdDeviation=".25"/></filter><filter id="i2obbmB" width="2.09" height="2.09" x="16.395" y="27.4" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2850" stdDeviation=".25"/></filter><filter id="iaARfac" width="3.368" height="3.218" x="9.509" y="13.953" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.894118 0 0 0 0 0.682353 0 0 0 0 0.6 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2850"/></filter><filter id="iyuPKJe" width="3.218" height="3.468" x="19.218" y="13.703" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.784314 0 0 0 0 0.572549 0 0 0 0 0.513726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2850"/></filter><filter id="iyxtb3b" width="3.148" height="3.148" x="19.253" y="13.988" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2850" stdDeviation=".25"/></filter><filter id="ijaC7Uc" width="2.948" height="2.948" x="9.663" y="14.088" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2850" stdDeviation=".2"/></filter><filter id="iMPkzve" width="10.691" height="11.777" x="10.405" y="10.155" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.807843 0 0 0 0 0.592157 0 0 0 0 0.52549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2850"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.75" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.815686 0 0 0 0 0.541176 0 0 0 0 0.541176 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2850" result="effect2_innerShadow_4002_2850"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.811765 0 0 0 0 0.486275 0 0 0 0 0.568627 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_2850" result="effect3_innerShadow_4002_2850"/></filter><filter id="ikmGrgd" width="2.877" height="3.682" x="14.399" y="14.557" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2850" stdDeviation=".25"/></filter><filter id="ijNkQme" width="2.377" height="3.182" x="14.811" y="14.668" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2850" stdDeviation=".125"/></filter><filter id="ifEgtfc" width="2.377" height="3.182" x="14.811" y="14.487" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2850" stdDeviation=".125"/></filter><filter id="iOwxYgu" width="3.702" height="1.526" x="14.149" y="17.91" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2850" stdDeviation=".05"/></filter><filter id="ioWxieZ" width="3.001" height="1.285" x="16.942" y="14.158" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0941176 0 0 0 0 0.0666667 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2850"/></filter><filter id="i4uQT6c" width="3.001" height="1.285" x="12.057" y="14.158" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0862745 0 0 0 0 0.054902 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2850"/></filter><filter id="iFHldDb" width=".787" height=".696" x="17.448" y="14.525" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2850" stdDeviation=".05"/></filter><filter id="ikTnWVc" width=".891" height=".913" x="18.288" y="14.6" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2850" stdDeviation=".1"/></filter><filter id="iuI8PGe" width=".986" height="1.04" x="13.845" y="14.537" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2850" stdDeviation=".1"/></filter><filter id="i3JzX4d" width=".913" height=".705" x="13.09" y="14.517" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2850" stdDeviation=".05"/></filter><filter id="it2pRjb" width="13.655" height="12.317" x="9.076" y="1.839" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.282353 0 0 0 0 0.203922 0 0 0 0 0.364706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2850"/></filter><filter id="ieTtOof" width="10.882" height="7.996" x="10.499" y="14.056" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.803922 0 0 0 0 0.635294 0 0 0 0 0.886275 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2850"/></filter><linearGradient id="iM3TIFd" x1="20.693" x2="13.888" y1="8.61" y2="21.214" gradientUnits="userSpaceOnUse"><stop class="hjtn79bml"/><stop offset="1" class="a4-v90a8k"/></linearGradient><linearGradient id="iu4BL0y" x1="9.026" x2="9.233" y1="29.911" y2="29.911" gradientUnits="userSpaceOnUse"><stop class="g-00mbcgn"/><stop offset="1" class="tvzw53atw"/></linearGradient><linearGradient id="i6kQckA" x1="22.975" x2="22.827" y1="29.911" y2="29.911" gradientUnits="userSpaceOnUse"><stop offset=".118" class="yacpd-mqw"/><stop offset="1" class="m2jbcqdpu"/></linearGradient><linearGradient id="imxslwc" x1="9.397" x2="8.084" y1="29.739" y2="29.739" gradientUnits="userSpaceOnUse"><stop class="s2ol_bbam"/><stop offset="1" class="hm-si4p_s"/></linearGradient><linearGradient id="iYKVIWb" x1="15.984" x2="15.984" y1="23.197" y2="29.911" gradientUnits="userSpaceOnUse"><stop class="ty59qw5cn"/><stop offset="1" class="jwfvhhlnv"/></linearGradient><linearGradient id="iDWpPDG" x1="16.479" x2="16.147" y1="27.271" y2="27.271" gradientUnits="userSpaceOnUse"><stop class="z_332kbzw"/><stop offset="1" class="v6fzn4zbl"/></linearGradient><linearGradient id="iGfMeIc" x1="8.784" x2="23.16" y1="20.372" y2="20.372" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="isLpFne" x1="8.784" x2="23.16" y1="20.341" y2="20.341" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="i6RqZje" x1="9.509" x2="12.469" y1="15.649" y2="15.649" gradientUnits="userSpaceOnUse"><stop class="ixw8njbyx"/><stop offset="1" class="me4c4fyoe"/></linearGradient><linearGradient id="iwaLrCb" x1="16" x2="16" y1="14.042" y2="15.667" gradientUnits="userSpaceOnUse"><stop class="lk8oqpz4p"/><stop offset="1" class="jpnkebn1w"/></linearGradient><linearGradient id="iGKObhX" x1="15.061" x2="16" y1="16.893" y2="16.893" gradientUnits="userSpaceOnUse"><stop class="l38p1-72g"/><stop offset="1" class="njp0-cbrk"/></linearGradient><linearGradient id="igfDoue" x1="16" x2="16" y1="17.692" y2="17.082" gradientUnits="userSpaceOnUse"><stop class="vdvey0c5l"/><stop offset="1" class="tddz0-g7t"/></linearGradient><linearGradient id="i3vUYib" x1="16" x2="16.253" y1="14.737" y2="16.423" gradientUnits="userSpaceOnUse"><stop class="uj2q-ob9n"/><stop offset="1" class="s60zdccbu"/></linearGradient><linearGradient id="i63IHQe" x1="14.936" x2="15.397" y1="19.102" y2="18.39" gradientUnits="userSpaceOnUse"><stop class="crzn0et_w"/><stop offset=".663" class="of5h8snug"/></linearGradient><linearGradient id="iAiKprb" x1="18.96" x2="18.646" y1="15.019" y2="15.212" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ilvCFle" x1="14.562" x2="14.248" y1="15.019" y2="15.212" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iyKRZUc" x1="19.866" x2="12.585" y1="11.708" y2="11.708" gradientUnits="userSpaceOnUse"><stop class="j8rdzr3lb"/><stop offset=".554" class="h5foydtlz"/><stop offset="1" class="roy3-sbpo"/></linearGradient><linearGradient id="iC5hH6b" x1="9.71" x2="12.428" y1="11.989" y2="11.989" gradientUnits="userSpaceOnUse"><stop class="bamb_e30h"/><stop offset="1" class="szoje-bkc"/></linearGradient><linearGradient id="isYcgqc" x1="16.538" x2="16.538" y1="14.155" y2="13.88" gradientUnits="userSpaceOnUse"><stop class="ip1t-iw4f"/><stop offset="1" class="l0ic_xblz"/></linearGradient><linearGradient id="iU1wwRb" x1="21.116" x2="15.022" y1="18.489" y2="18.489" gradientUnits="userSpaceOnUse"><stop class="it4bksbcb"/><stop offset="1" class="twe7w31pl"/></linearGradient><linearGradient id="i7n11Wc" x1="15.94" x2="15.94" y1="13.927" y2="16.029" gradientUnits="userSpaceOnUse"><stop class="x-67tmbrg"/><stop offset="1" class="bkz397hyg"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-guard-light" /></template>
<style>
.a1tpsrb8u {
  cx: 17.439px;
  cy: 28.445px;
  r: 0.545px;
  fill: var(--svg-color--f6265e, #F6265E);
}

.a4-v90a8k {
  stop-color: var(--svg-color--1a1718, #1A1718);
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

.az8rbc7bc {
  d: path("M13.816 14.488a.892.892 0 0 0-.86 1.127h1.724a1 1 0 0 0 .032-.235a.9.9 0 0 0-.896-.893");
}

.b5_53rm9x {
  stop-color: var(--svg-color--5e5864, #5E5864);
  stop-opacity: 0;
}

.b55qklbsj {
  stop-color: var(--svg-color--bc8272, #BC8272);
  stop-opacity: 0;
}

.bamb_e30h {
  stop-color: var(--svg-color--4d4c50, #4D4C50);
}

.bhu-9-bus {
  fill: var(--svg-color--d19590, #D19590);
  d: path("m15.607 15.34l-.683 1.7a.54.54 0 0 0 .52.699h.787a.54.54 0 0 0 .52-.7l-.531-1.7c-.114-.376-.493-.376-.613 0");
}

.bkz397hyg {
  stop-color: var(--svg-color--c7aed9, #C7AED9);
  stop-opacity: 0;
}

.bl7uysvvb {
  stop-color: var(--svg-color--181518, #181518);
}

.blsopp2mg {
  d: path("M20.046 20.161c1.364.418 2.538 1.308 3.179 1.936a.46.46 0 0 1-.011.659l-.65.649a.523.523 0 0 1-.704.02a12.3 12.3 0 0 0-3.107-1.857z");
}

.brg8dbpny {
  stop-color: var(--svg-color--e2a895, #E2A895);
  stop-opacity: 0;
}

.by20mjbph {
  stop-color: var(--svg-color--d993a0, #D993A0);
}

.c5pyn6kwp {
  d: path("M5.428 29.911h21.144c-.19-5.356-4.591-9.64-9.994-9.64h-1.156c-5.403 0-9.805 4.284-9.994 9.64");
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

.cd8uxyblt {
  d: path("M11.926 20.161c-1.363.418-2.538 1.308-3.179 1.936a.46.46 0 0 0 .011.659l.65.649a.523.523 0 0 0 .705.02a12.3 12.3 0 0 1 3.106-1.857z");
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

.crzn0et_w {
  stop-color: var(--svg-color--e7b4b2, #E7B4B2);
}

.csva0fh9x {
  stop-color: var(--svg-color--403947, #403947);
}

.czp_i4iyf {
  fill: var(--svg-color--f6bca5, #F6BCA5);
  d: path("M20.827 16.636a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.d_t8kfbgb {
  stop-color: var(--svg-color--e2a895, #E2A895);
}

.d0nv29baz {
  stop-color: var(--svg-color--686070, #686070);
  stop-opacity: 0;
}

.d3oi1zbdr {
  d: path("M10.913 14.3h.012l-.01-.266l-.01-.306c.02-.95.574-1.316.81-1.439l.05-.02l.052-.02a2.3 2.3 0 0 0 1.19-1.235l.082-.194a.264.264 0 0 1 .461-.051a3.86 3.86 0 0 0 3.19 1.673h3.22c.18 0 1.082.088 1.135 1.332l-.118 3.074c-.124 2.802-2.312 4.684-4.984 4.684c-2.671 0-4.86-1.882-4.983-4.684z");
}

.d42a8nbyx {
  d: path("M9.058 29.911h-3.63a9.98 9.98 0 0 1 3.63-7.355z");
}

.dkw8bsvxv {
  stop-color: var(--svg-color--f5b99d, #F5B99D);
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

.e2earo80w {
  stop-color: var(--svg-color--f6baa9, #F6BAA9);
}

.e2y-fbcxj {
  stop-color: var(--svg-color--fca239, #FCA239);
}

.exer9ybqp {
  stop-color: var(--svg-color--b13b50, #B13B50);
}

.f_x1tcb5s {
  stop-color: var(--svg-color--482949, #482949);
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

.fvm07vbkd {
  stop-color: var(--svg-color--b87c92, #B87C92);
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

.glo437b-m {
  stop-color: var(--svg-color--040002, #040002);
  stop-opacity: 0;
}

.gohadn3wh {
  stop-color: var(--svg-color--d38893, #D38893);
}

.gqqtwubim {
  fill: var(--svg-color--2d2b2e, #2D2B2E);
  d: path("M17.142 14.993c.265-.467.669-.835 1.537-.835c.38 0 .747.105 1.073.368c.27.217.233.495.025.6l-.556.317c-.652-.21-1.373-.24-2.079-.45");
}

.guwslmx9m {
  stop-color: var(--svg-color--403947, #403947);
  stop-opacity: 0;
}

.gx_0zqbtq {
  width: 4.141px;
  height: 5.141px;
  x: 13.898px;
  y: 18.099px;
  rx: 1.969px;
}

.h_j9u0wvt {
  stop-color: var(--svg-color--e6e6e6, #E6E6E6);
}

.h4xnajbet {
  d: path("M11.118 17.171a1.61 1.61 0 1 0 0-3.218a1.61 1.61 0 0 0 0 3.218");
}

.h5foydtlz {
  stop-color: var(--svg-color--4b3c5b, #4B3C5B);
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

.hx66smwtj {
  stop-color: var(--svg-color--4a4446, #4A4446);
}

.hztqsacfn {
  stop-color: var(--svg-color--ff6085, #FF6085);
}

.i1pxvjzop {
  stop-color: var(--svg-color--f6dcf7, #F6DCF7);
  stop-opacity: 0;
}

.icppbwd3b {
  stop-color: var(--svg-color--e34c67, #E34C67);
}

.if6aw8aev {
  d: path("M16.324 20.342c.25.01.51.03.77.05c-.26-.02-.51-.04-.77-.05");
}

.intda8ekf {
  stop-color: var(--svg-color--d09790, #D09790);
  stop-opacity: 0;
}

.ip1t-iw4f {
  stop-color: var(--svg-color--462659, #462659);
}

.is1a69b4d {
  fill-rule: evenodd;
  d: path("M23.185 16.972c.213-.435.324-.921.324-1.427a3.3 3.3 0 0 0-.268-1.306h.005a3 3 0 0 0-.281-.513l-.002-.003c-.344-.526-.71-1.143-.71-1.77l.183-.01a3.3 3.3 0 0 0-3.299-3.3a.54.54 0 0 1-.455-.233A3.3 3.3 0 0 0 16 7.034a3.3 3.3 0 0 0-2.682 1.376a.56.56 0 0 1-.455.233l-.085.001a3.3 3.3 0 0 0-3.214 3.298v.01a3.24 3.24 0 0 1-.527 1.771l-.002.004a3.3 3.3 0 0 0-.22 3.245a.52.52 0 0 1 0 .455a3.213 3.213 0 0 0 2.894 4.625h8.582a3.213 3.213 0 0 0 3.218-3.218c0-.506-.121-.982-.324-1.407a.51.51 0 0 1 0-.455m-12.26-2.673h-.012l1.198 2.356c.124 2.802 1.217 0 3.889 0s3.836 3.12 3.96.317l1.136-3.197c-.054-1.245-.956-1.332-1.136-1.332h-3.22a3.86 3.86 0 0 1-3.19-1.674a.264.264 0 0 0-.461.051l-.082.194c-.226.561-.656.99-1.19 1.235l-.051.02l-.051.02c-.236.123-.79.49-.81 1.439l.01.306z");
}

.is9c70bqb {
  d: path("M18.118 14.676c.064.085-.069.189-.22.302s-.263.192-.327.107c-.063-.085.008-.245.159-.358c.15-.113.325-.136.388-.05");
}

.it4bksbcb {
  stop-color: var(--svg-color--dfc6ed, #DFC6ED);
}

.ixw8njbyx {
  stop-color: var(--svg-color--cc9987, #CC9987);
}

.j8rdzr3lb {
  stop-color: var(--svg-color--5d536a, #5D536A);
}

.jk5udqbyz {
  stop-color: var(--svg-color--464444, #464444);
  stop-opacity: 0;
}

.jpnkebn1w {
  stop-color: var(--svg-color--d58e95, #D58E95);
  stop-opacity: 0;
}

.jwfvhhlnv {
  stop-color: var(--svg-color--d8bbeb, #D8BBEB);
}

.k2oqpgb0o {
  stop-color: var(--svg-color--f4b89e, #F4B89E);
  stop-opacity: 0;
}

.k5s0mt74t {
  stop-color: var(--svg-color--cc981a, #CC981A);
}

.kbl3igr5c {
  stop-color: var(--svg-color--040002, #040002);
}

.kt__1405u {
  stop-color: var(--svg-color--ccc, #CCC);
}

.l0ic_xblz {
  stop-color: var(--svg-color--462659, #462659);
  stop-opacity: 0;
}

.l0xg-rbdf {
  stop-color: var(--svg-color--040101, #040101);
}

.l38p1-72g {
  stop-color: var(--svg-color--dfa791, #DFA791);
}

.l59yayqpc {
  fill: var(--svg-color--000, #000);
  d: path("M17.673 15.38c0-.284.227-.511.511-.511a.51.51 0 0 1 .454.746h-.904a.46.46 0 0 1-.061-.235");
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.l7l5hpb1w {
  fill: var(--svg-color--272528, #272528);
  d: path("M14.858 14.993c-.265-.467-.669-.835-1.537-.835c-.38 0-.747.105-1.073.368c-.269.217-.233.495-.025.6l.556.317c.652-.21 1.373-.24 2.079-.45");
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

.lk8oqpz4p {
  stop-color: var(--svg-color--d58e95, #D58E95);
}

.m_vwkvi0t {
  d: path("M14.631 15.275c0-.288-.234-.48-.298-.538l-.288.278l.177.362z");
}

.m2jbcqdpu {
  stop-color: var(--svg-color--fc356b, #FC356B);
  stop-opacity: 0;
}

.m7r_2tbtp {
  stop-color: var(--svg-color--ee5076, #EE5076);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.me4c4fyoe {
  stop-color: var(--svg-color--ac7864, #AC7864);
}

.mg6vw6bqp {
  stop-color: var(--svg-color--5d4364, #5D4364);
}

.mj-ttbc0m {
  stop-color: var(--svg-color--e8aca8, #E8ACA8);
}

.mjk1u9lsv {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.118 14.676c.064.085-.069.189-.22.302s-.263.192-.327.107c-.063-.085.008-.245.159-.358c.15-.113.325-.136.388-.05");
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

.n1w64orcn {
  stop-color: var(--svg-color--b87c92, #B87C92);
  stop-opacity: 0;
}

.njp0-cbrk {
  stop-color: var(--svg-color--dfa791, #DFA791);
  stop-opacity: 0;
}

.nwt8glb0m {
  stop-color: var(--svg-color--ffd6c2, #FFD6C2);
  stop-opacity: 0;
}

.oamhc07tx {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.391 14.216c.653 0 1.205.45 1.355 1.059a.274.274 0 0 1-.268.34h-2.23a.23.23 0 0 1-.228-.271a1.4 1.4 0 0 1 1.371-1.128");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.of5h8snug {
  stop-color: var(--svg-color--e7b4b2, #E7B4B2);
  stop-opacity: 0;
}

.ot4iumb_e {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M16 18.473c-.52 0-1.01-.125-1.422-.344c-.14-.073-.291.088-.203.22a1.932 1.932 0 0 0 3.25 0c.088-.137-.063-.293-.203-.22c-.412.22-.896.344-1.422.344Z");
}

.p9dhe0cfb {
  stop-color: var(--svg-color--e11c59, #E11C59);
}

.paonnib9g {
  stop-color: var(--svg-color--474445, #474445);
}

.pjy1og4qu {
  stop-color: var(--svg-color--d6a094, #D6A094);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.qg_d8ubct {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.609 14.216c-.653 0-1.205.45-1.355 1.059c-.044.174.09.34.268.34h2.231a.23.23 0 0 0 .227-.271a1.4 1.4 0 0 0-1.371-1.128");
}

.qpkqxibzk {
  stop-color: var(--svg-color--ffd6c2, #FFD6C2);
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

.qynwwbc5y {
  d: path("M20.827 16.636a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.r_v2kebuk {
  stop-color: var(--svg-color--181518, #181518);
  stop-opacity: 0;
}

.rc_bk898j {
  fill: var(--svg-color--c58c80, #C58C80);
  d: path("M11.138 16.636a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.rd66zrbmz {
  fill: var(--svg-color--88024e, #88024E);
  d: path("M16 18.473c-.52 0-1.01-.125-1.422-.344c-.14-.073-.291.088-.203.22a1.932 1.932 0 0 0 3.25 0c.088-.137-.063-.293-.203-.22c-.412.22-.896.344-1.422.344");
}

.roy3-sbpo {
  stop-color: var(--svg-color--393341, #393341);
}

.s2ol_bbam {
  stop-color: var(--svg-color--ac394e, #AC394E);
}

.s60zdccbu {
  stop-color: var(--svg-color--de9f9d, #DE9F9D);
  stop-opacity: 0;
}

.sheftacio {
  stop-color: var(--svg-color--ffd8c1, #FFD8C1);
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

.srsu-zbqf {
  d: path("M20.827 17.171a1.61 1.61 0 1 0 0-3.218a1.61 1.61 0 0 0 0 3.218");
}

.ssttjvbga {
  cx: 13.547px;
  cy: 14.869px;
  rx: 0.39px;
  ry: 0.197px;
}

.suybu51ug {
  stop-color: var(--svg-color--d09790, #D09790);
}

.sx6q1cbyi {
  cx: 17.494px;
  cy: 25.374px;
  r: 0.545px;
}

.sy7gbya4q {
  d: path("M22.942 29.911h3.63a9.98 9.98 0 0 0-3.63-7.355z");
}

.szoje-bkc {
  stop-color: var(--svg-color--393341, #393341);
  stop-opacity: 0;
}

.tddz0-g7t {
  stop-color: var(--svg-color--d29394, #D29394);
  stop-opacity: 0;
}

.tk20gvbnd {
  stop-color: var(--svg-color--ffdebf, #FFDEBF);
  stop-opacity: 0;
}

.tnyz6pflp {
  d: path("M11.138 16.636a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
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

.tyeec335h {
  d: path("M18.184 14.488a.892.892 0 0 1 .86 1.127H17.32a.896.896 0 0 1 .864-1.128");
}

.u17l1bw1n {
  d: path("m10.5 14.156l.12 3.518c.082 2.424 2.07 4.378 4.497 4.378h1.677c2.44 0 4.435-1.976 4.498-4.416l.09-3.48h-.909l-.12 3.48c-.049 1.898-1.662 3.486-3.56 3.486h-1.676c-1.887 0-3.489-1.597-3.553-3.482l-.09-3.485z");
}

.u2-vnsrzx {
  stop-color: var(--svg-color--f73c71, #F73C71);
}

.u25v0cb4e {
  stop-color: var(--svg-color--d6274f, #D6274F);
}

.uaoaczbhz {
  stop-color: var(--svg-color--bc8272, #BC8272);
}

.uj2q-ob9n {
  stop-color: var(--svg-color--de9f9d, #DE9F9D);
}

.ul3ws4blr {
  stop-color: var(--svg-color--4b4551, #4B4551);
  stop-opacity: 0;
}

.v-9tn59hb {
  stop-color: var(--svg-color--dba98b, #DBA98B);
  stop-opacity: 0;
}

.v-z8r6b-c {
  fill: var(--svg-color--dea99c, #DEA99C);
  d: path("m15.618 15.2l-.532 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.53-1.7c-.114-.376-.646-.376-.765 0");
}

.v35_ndupb {
  d: path("m15.618 15.019l-.532 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.53-1.7c-.114-.377-.646-.377-.765 0");
}

.v6fzn4zbl {
  stop-color: var(--svg-color--eacceb, #EACCEB);
  stop-opacity: 0;
}

.v7lobvb0w {
  fill: var(--svg-color--554b59, #554B59);
  d: path("M20.046 20.161c1.364.418 2.538 1.308 3.179 1.936a.46.46 0 0 1-.011.659l-.65.649a.523.523 0 0 1-.704.02a12.3 12.3 0 0 0-3.107-1.857z");
}

.vdvey0c5l {
  stop-color: var(--svg-color--d29394, #D29394);
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

.w--6bgeqj {
  stop-color: var(--svg-color--e5b1a5, #E5B1A5);
}

.wcylmi-4x {
  stop-color: var(--svg-color--513f4e, #513F4E);
}

.wfn54lnxd {
  cx: 17.439px;
  cy: 25.445px;
  r: 0.545px;
  fill: var(--svg-color--f6265e, #F6265E);
}

.x_olikxjr {
  stop-color: var(--svg-color--4a2e4f, #4A2E4F);
  stop-opacity: 0;
}

.x-67tmbrg {
  stop-color: var(--svg-color--b593cf, #B593CF);
}

.x2r0w67qw {
  stop-color: var(--svg-color--fff153, #FFF153);
}

.xbgj88f0b {
  stop-color: var(--svg-color--ffdcc5, #FFDCC5);
}

.xbkp5vbln {
  stop-color: var(--svg-color--f6cf1c, #F6CF1C);
}

.xdn388byj {
  stop-color: var(--svg-color--171418, #171418);
}

.xl9xm7bnj {
  stop-color: var(--svg-color--f6baa9, #F6BAA9);
  stop-opacity: 0;
}

.xrlcxenmf {
  fill: var(--svg-color--000, #000);
  d: path("M14.327 15.38a.51.51 0 0 0-.511-.511a.51.51 0 0 0-.454.746h.904a.5.5 0 0 0 .061-.235");
}

.y_9l2i5ww {
  stop-color: var(--svg-color--ffdcc5, #FFDCC5);
  stop-opacity: 0;
}

.y1lgprrzn {
  stop-color: var(--svg-color--d993a0, #D993A0);
  stop-opacity: 0;
}

.y5cc9h9kl {
  d: path("M18.979 15.263a.84.84 0 0 0-.231-.463l-.26.285l.117.228z");
}

.y6ictpbdv {
  stop-color: var(--svg-color--e43669, #E43669);
}

.yacpd-mqw {
  stop-color: var(--svg-color--fc356b, #FC356B);
}

.yk-5cub9i {
  d: path("M15.994 20.342h-.04c.1 0 .19 0 .29.01c-.08-.01-.17-.01-.25-.01");
}

.yk2k5ii1q {
  cx: 13.547px;
  cy: 14.869px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.ynae43ovp {
  stop-color: var(--svg-color--dba98b, #DBA98B);
}

.z_332kbzw {
  stop-color: var(--svg-color--eacceb, #EACCEB);
}

.z-rzt8b_f {
  stop-color: var(--svg-color--ffdebf, #FFDEBF);
}

.z2ubpb-up {
  stop-color: var(--svg-color--ff5c85, #FF5C85);
}

.z4th17bal {
  d: path("m15.618 15.2l-.532 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.53-1.7c-.114-.376-.646-.376-.765 0");
}

.zw1wivbgv {
  stop-color: var(--svg-color--ffcfbb, #FFCFBB);
}

</style>
