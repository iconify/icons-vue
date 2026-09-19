<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#itBYKwc)" class="zfree3baf"/><path fill="url(#itAInvc)" class="zfree3baf"/><path fill="url(#i5ofdfc)" class="zfree3baf"/><path fill="url(#iqp3oac)" class="zfree3baf"/><path fill="url(#iMOOZnc)" class="zfree3baf"/><path fill="url(#iEn8unk)" class="d23y02b4l"/><path fill="url(#ixN40jb)" class="d23y02b4l"/><path fill="url(#iN4JNKe)" class="d23y02b4l"/><path fill="url(#idaHAtl)" class="d23y02b4l"/><path fill="url(#idprBUH)" class="e1oizz7_b"/><path fill="url(#ivx88gd)" class="e1oizz7_b"/><path fill="url(#iRh2eGd)" class="e1oizz7_b"/><path fill="url(#i3vocVc)" class="e1oizz7_b"/><g filter="url(#iHxYNId)"><path fill="url(#i6N0gmd)" class="g_ysjmbrf"/></g><g filter="url(#i1tFETb)"><path fill="url(#iEvCtDd)" class="owrgdvbme"/></g><g filter="url(#iiaGe0c)"><path fill="url(#i4Z3sNd)" class="jlcacfbau"/></g><path fill="url(#iQztIeJ)" class="ymz1xs6ex"/><path fill="url(#iyGkMKo)" class="y5vl6_bal"/><g filter="url(#ibJcKGe)"><path fill="url(#iY6Ilbe)" class="w61tqnb0g"/><path fill="url(#iolMo2c)" class="w61tqnb0g"/><path fill="url(#if1ViPb)" class="w61tqnb0g"/><path fill="url(#i1ZcaIe)" class="w61tqnb0g"/><path fill="url(#iCbNNMd)" class="w61tqnb0g"/><path fill="url(#ibs7cAv)" class="w61tqnb0g"/></g><g filter="url(#ioaR4Oc)"><path fill="url(#iwYx5fd)" class="vcgyh92un"/></g><g filter="url(#iDbMQLc)"><path fill="url(#iiQrphd)" class="mhdxxgbzz"/></g><g filter="url(#i5dbNCe)"><path fill="url(#i9tLJmc)" class="pijiswbcu"/><path fill="url(#i4HBfWa)" class="pijiswbcu"/></g><path fill="url(#iDSzC4c)" class="pijiswbcu"/><path fill="url(#iqe8ebb)" class="pijiswbcu"/><path fill="url(#iTZLg4b)" class="pijiswbcu"/><g filter="url(#iAPJvfb)"><path fill="url(#i9t34ed)" class="g-ae66bju"/></g><g filter="url(#ir56L5c)"><path fill="url(#iTAV31c)" class="jmnvn7nui"/><path fill="url(#ivMFoic)" class="jmnvn7nui"/><path fill="url(#iEpg4MD)" class="jmnvn7nui"/></g><path class="r_ckvab-y"/><path fill="url(#ibl1W7M)" class="z4vjykd0x"/><path class="vpkqk59tf"/><g filter="url(#icewgYd)"><path fill="url(#iL9bx4c)" class="fp27koqed"/></g><g filter="url(#i3jjXVb)"><ellipse transform="rotate(-27.914 12.849 20.448)" class="ge10hrb8f"/><ellipse fill="url(#i7KhvgG)" transform="rotate(-27.914 12.849 20.448)" class="e505wibdz"/></g><path class="nzt0dyr_i"/><path fill="url(#i3ZzJgd)" class="h0w3ehbbr"/><path class="o-css572m"/><g filter="url(#ivSVale)"><path fill="url(#i7ueWhe)" class="mrx1hybjj"/></g><g filter="url(#iFKCvPc)"><ellipse transform="rotate(-27.914 18.505 20.448)" class="d6lbdubvl"/><ellipse fill="url(#ikSm5Yc)" transform="rotate(-27.914 18.505 20.448)" class="xnds8eb0z"/></g><g filter="url(#iMYSVxd)"><path clip-rule="evenodd" class="n4odr4vnh"/></g><g filter="url(#ihK2YYc)"><path class="hgx031bkz"/></g><g filter="url(#i30TIpm)"><path clip-rule="evenodd" class="ufuzl_b_h"/></g><g filter="url(#iASfnvb)"><path class="h1n3ss2pg"/></g><g filter="url(#izSEA2c)"><path fill="url(#it7Leil)" class="hxyhiv56f"/></g><g filter="url(#i7Gksqe)"><path fill="url(#iwaQwKc)" class="cjenfq8ao"/><path fill="url(#iNN1JxF)" class="cjenfq8ao"/></g><defs><radialGradient id="itAInvc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -6.375 13.4856 0 16.73 31.5)" gradientUnits="userSpaceOnUse"><stop class="ms1i9y3sd"/><stop offset="1" class="tv3llfnnc"/></radialGradient><radialGradient id="i5ofdfc" cx="0" cy="0" r="1" gradientTransform="rotate(128.254 1.98 14.278)scale(8.27742 7.99773)" gradientUnits="userSpaceOnUse"><stop offset=".41" class="ga0t70bsk"/><stop offset="1" class="pff_xvb-o"/></radialGradient><radialGradient id="iqp3oac" cx="0" cy="0" r="1" gradientTransform="matrix(3.99999 9.24998 -3.49626 1.5119 24.855 19.938)" gradientUnits="userSpaceOnUse"><stop class="yhp94650d"/><stop offset="1" class="ntnm3dw3i"/></radialGradient><radialGradient id="iMOOZnc" cx="0" cy="0" r="1" gradientTransform="rotate(112.521 -3.532 11.153)scale(8.32213 3.45064)" gradientUnits="userSpaceOnUse"><stop class="bhtfot5lc"/><stop offset="1" class="i5vei3bfj"/></radialGradient><radialGradient id="iEn8unk" cx="0" cy="0" r="1" gradientTransform="rotate(-158.13 7.74 12.509)scale(9.7316 4.17069)" gradientUnits="userSpaceOnUse"><stop class="wx46szfra"/><stop offset="1" class="re43f_bny"/></radialGradient><radialGradient id="idaHAtl" cx="0" cy="0" r="1" gradientTransform="matrix(-.5 2.4375 -.98492 -.20203 9.262 29.281)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="v0l5en3es"/><stop offset="1" class="c4bn1nh8f"/></radialGradient><radialGradient id="idprBUH" cx="0" cy="0" r="1" gradientTransform="matrix(8.53125 -2.21874 .7924 3.04687 22.262 27.188)" gradientUnits="userSpaceOnUse"><stop offset=".212" class="u1-n55buw"/><stop offset="1" class="qkikqtb3f"/></radialGradient><radialGradient id="i3vocVc" cx="0" cy="0" r="1" gradientTransform="rotate(-25.475 69.562 -28.586)scale(3.30579 7.08094)" gradientUnits="userSpaceOnUse"><stop class="f-odvf_ry"/><stop offset="1" class="s02vtwpqx"/></radialGradient><radialGradient id="iY6Ilbe" cx="0" cy="0" r="1" gradientTransform="rotate(129.416 6.225 13.498)scale(10.8277 13.7649)" gradientUnits="userSpaceOnUse"><stop offset=".204" class="t-v22vtsk"/><stop offset=".727" class="dv4icmbqz"/></radialGradient><radialGradient id="iolMo2c" cx="0" cy="0" r="1" gradientTransform="rotate(156.371 7.167 12.548)scale(2.45591 1.61695)" gradientUnits="userSpaceOnUse"><stop offset=".045" class="y06fetb4u"/><stop offset="1" class="duzj_wbgx"/></radialGradient><radialGradient id="if1ViPb" cx="0" cy="0" r="1" gradientTransform="matrix(1.4375 6.5 -3.9318 .86953 14.2 15.688)" gradientUnits="userSpaceOnUse"><stop class="q2p7q4bac"/><stop offset="1" class="cl42-t4us"/></radialGradient><radialGradient id="i1ZcaIe" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.125 -6.80075 0 16 14.313)" gradientUnits="userSpaceOnUse"><stop offset=".441" class="bksouobxj"/><stop offset="1" class="bvdn5abpt"/></radialGradient><radialGradient id="iCbNNMd" cx="0" cy="0" r="1" gradientTransform="matrix(1.625 -.9375 .61203 1.06085 19.043 20.203)" gradientUnits="userSpaceOnUse"><stop offset=".163" class="wei4uo88h"/><stop offset="1" class="tcm8ipltk"/></radialGradient><radialGradient id="ibs7cAv" cx="0" cy="0" r="1" gradientTransform="matrix(-1.5 -1.4375 .95744 -.99907 13.012 20.219)" gradientUnits="userSpaceOnUse"><stop offset=".163" class="l4fz75bjj"/><stop offset="1" class="dh21vibgf"/></radialGradient><radialGradient id="iiQrphd" cx="0" cy="0" r="1" gradientTransform="matrix(5.6875 -4.9375 3.04319 3.50544 16.668 31.875)" gradientUnits="userSpaceOnUse"><stop offset=".827" class="e89pv8d9w"/><stop offset="1" class="fgz6lbb_q"/></radialGradient><radialGradient id="i9tLJmc" cx="0" cy="0" r="1" gradientTransform="rotate(119.023 6.056 9.205)scale(11.0787 12.8963)" gradientUnits="userSpaceOnUse"><stop offset=".229" class="ed3cdu6st"/><stop offset=".586" class="zy9alzbrq"/><stop offset="1" class="l_p06obzw"/></radialGradient><radialGradient id="i4HBfWa" cx="0" cy="0" r="1" gradientTransform="matrix(3.03124 4.78126 -7.17655 4.5498 10.48 8.812)" gradientUnits="userSpaceOnUse"><stop offset=".173" class="rxpqegslo"/><stop offset="1" class="uz747kbcx"/></radialGradient><radialGradient id="iDSzC4c" cx="0" cy="0" r="1" gradientTransform="matrix(-1.81247 -5.21877 2.28999 -.7953 9.543 18.875)" gradientUnits="userSpaceOnUse"><stop class="r497yzb9u"/><stop offset="1" class="mb_z4bcne"/></radialGradient><radialGradient id="iqe8ebb" cx="0" cy="0" r="1" gradientTransform="matrix(2.5 -4.60008 2.87236 1.56104 22.137 18.506)" gradientUnits="userSpaceOnUse"><stop class="r497yzb9u"/><stop offset="1" class="onyxmnbkr"/></radialGradient><radialGradient id="iTZLg4b" cx="0" cy="0" r="1" gradientTransform="matrix(.34375 4.625 -2.1421 .1592 16.73 6.437)" gradientUnits="userSpaceOnUse"><stop offset=".151" class="lf1my1bmo"/><stop offset="1" class="xww7r3f9e"/></radialGradient><radialGradient id="ivMFoic" cx="0" cy="0" r="1" gradientTransform="matrix(-1.39062 0 0 -1.985 16.862 23.156)" gradientUnits="userSpaceOnUse"><stop class="n0zizq_8d"/><stop offset="1" class="jnop8h4yg"/></radialGradient><radialGradient id="iEpg4MD" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.30469 -2.35811 0 16 21.828)" gradientUnits="userSpaceOnUse"><stop offset=".871" class="hh29jvbig"/><stop offset="1" class="y8xk-w_wn"/></radialGradient><radialGradient id="ibl1W7M" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.05276 -1.67453 0 13.2 20.572)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="i7KhvgG" cx="0" cy="0" r="1" gradientTransform="matrix(-.01004 -.64108 .77062 -.01207 12.829 20.855)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i3ZzJgd" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.05276 -1.67453 0 18.857 20.572)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="ikSm5Yc" cx="0" cy="0" r="1" gradientTransform="matrix(-.01004 -.64108 .77062 -.01207 18.486 20.856)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="it7Leil" cx="0" cy="0" r="1" gradientTransform="rotate(91.909 2.708 12.72)scale(3.75208 3.48905)" gradientUnits="userSpaceOnUse"><stop offset=".196" class="p_o3_x88l"/><stop offset="1" class="qzh8n_zqw"/></radialGradient><radialGradient id="iNN1JxF" cx="0" cy="0" r="1" gradientTransform="matrix(-2.37502 5.80764 -4.61772 -1.8884 18.793 8.402)" gradientUnits="userSpaceOnUse"><stop class="lf3njzbxn"/><stop offset="1" class="lfr4-msfs"/></radialGradient><filter id="iHxYNId" width="3.2" height="3.2" x="14.38" y="1.9" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.188235 0 0 0 0 0.47451 0 0 0 0 0.698039 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4035"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.286275 0 0 0 0 0.67451 0 0 0 0 0.929412 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_4035" result="effect2_innerShadow_4002_4035"/></filter><filter id="i1tFETb" width="3.323" height="3.322" x="7.76" y="2.78" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.188235 0 0 0 0 0.47451 0 0 0 0 0.698039 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4035"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.286275 0 0 0 0 0.67451 0 0 0 0 0.929412 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_4035" result="effect2_innerShadow_4002_4035"/></filter><filter id="iiaGe0c" width="3.315" height="3.322" x="20.881" y="2.778" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.188235 0 0 0 0 0.47451 0 0 0 0 0.698039 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4035"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.286275 0 0 0 0 0.67451 0 0 0 0 0.929412 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_4035" result="effect2_innerShadow_4002_4035"/></filter><filter id="ibJcKGe" width="13.751" height="17.48" x="9.374" y="8.52" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.768627 0 0 0 0 0.592157 0 0 0 0 0.239216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4035"/></filter><filter id="ioaR4Oc" width="7" height="3.5" x="8.98" y="26.5" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.835294 0 0 0 0 0.556863 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4035"/></filter><filter id="iDbMQLc" width="7" height="3.6" x="16.48" y="26.4" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.87451 0 0 0 0 0.505882 0 0 0 0 0.160784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4035"/></filter><filter id="i5dbNCe" width="16.462" height="11.633" x="7.73" y="6.846" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.933333 0 0 0 0 0.494118 0 0 0 0 0.0431373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4035"/></filter><filter id="iAPJvfb" width="4.345" height="5.433" x="13.635" y="19.845" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4035" stdDeviation=".5"/></filter><filter id="ir56L5c" width="2.545" height="3.632" x="14.727" y="20.468" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4035" stdDeviation=".05"/></filter><filter id="icewgYd" width="1.161" height="1.231" x="13.295" y="20.076" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4035" stdDeviation=".1"/></filter><filter id="i3jjXVb" width="1.125" height=".855" x="12.286" y="20.02" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4035" stdDeviation=".05"/></filter><filter id="ivSVale" width="1.161" height="1.231" x="18.952" y="20.076" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4035" stdDeviation=".1"/></filter><filter id="iFKCvPc" width="1.125" height=".855" x="17.942" y="20.02" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4035" stdDeviation=".05"/></filter><filter id="iMYSVxd" width="2.86" height="1.658" x="11.258" y="17.115" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.717647 0 0 0 0 0.231373 0 0 0 0 0.301961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4035"/></filter><filter id="ihK2YYc" width="2.559" height="1.108" x="11.408" y="17.311" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4035" stdDeviation=".125"/></filter><filter id="i30TIpm" width="2.86" height="1.658" x="17.883" y="17.115" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.717647 0 0 0 0 0.231373 0 0 0 0 0.301961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4035"/></filter><filter id="iASfnvb" width="2.559" height="1.108" x="18.115" y="17.4" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4035" stdDeviation=".125"/></filter><filter id="izSEA2c" width="4.925" height="8.899" x="11.525" y="7.038" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4035" stdDeviation=".25"/></filter><filter id="i7Gksqe" width="10.893" height="9.389" x="13.855" y="6.484" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4035" stdDeviation=".5"/></filter><linearGradient id="itBYKwc" x1="3.23" x2="27.73" y1="25.438" y2="25.438" gradientUnits="userSpaceOnUse"><stop class="g4f_hhbsk"/><stop offset="1" class="w6ry4524w"/></linearGradient><linearGradient id="ixN40jb" x1="8.699" x2="7.98" y1="24.5" y2="26.813" gradientUnits="userSpaceOnUse"><stop class="og3e4kk-e"/><stop offset="1" class="ynyfnhbha"/></linearGradient><linearGradient id="iN4JNKe" x1="7.73" x2="7.699" y1="30.156" y2="28.906" gradientUnits="userSpaceOnUse"><stop class="osrxhzfhp"/><stop offset="1" class="fu0j5nb_v"/></linearGradient><linearGradient id="ivx88gd" x1="24.73" x2="24.73" y1="30.125" y2="28.563" gradientUnits="userSpaceOnUse"><stop class="t1e217bwb"/><stop offset="1" class="zy06qjblk"/></linearGradient><linearGradient id="iRh2eGd" x1="22.637" x2="23.012" y1="24.594" y2="25.719" gradientUnits="userSpaceOnUse"><stop offset=".15" class="bxic48qwp"/><stop offset="1" class="x8a_nqnwc"/></linearGradient><linearGradient id="i6N0gmd" x1="17.48" x2="14.885" y1="2.498" y2="5" gradientUnits="userSpaceOnUse"><stop offset=".32" class="ua70ijcgb"/><stop offset="1" class="cy-darb1h"/></linearGradient><linearGradient id="iEvCtDd" x1="10.983" x2="8.282" y1="3.399" y2="6.003" gradientUnits="userSpaceOnUse"><stop offset=".32" class="ua70ijcgb"/><stop offset="1" class="cy-darb1h"/></linearGradient><linearGradient id="i4Z3sNd" x1="24.096" x2="21.395" y1="3.397" y2="5.995" gradientUnits="userSpaceOnUse"><stop offset=".32" class="ua70ijcgb"/><stop offset="1" class="cy-darb1h"/></linearGradient><linearGradient id="iQztIeJ" x1="10.531" x2="8.08" y1="18.753" y2="15.699" gradientUnits="userSpaceOnUse"><stop class="w9napxb6c"/><stop offset="1" class="m2g4nbcbq"/></linearGradient><linearGradient id="iyGkMKo" x1="20.696" x2="24.556" y1="19.288" y2="15.428" gradientUnits="userSpaceOnUse"><stop class="w9napxb6c"/><stop offset="1" class="m2g4nbcbq"/></linearGradient><linearGradient id="iwYx5fd" x1="13.385" x2="11.849" y1="27.345" y2="31.044" gradientUnits="userSpaceOnUse"><stop offset=".053" class="xhq8-uz6x"/><stop offset=".431" class="q__mu-bme"/></linearGradient><linearGradient id="i9t34ed" x1="15.309" x2="15.591" y1="24.129" y2="21.895" gradientUnits="userSpaceOnUse"><stop class="pmyro9arm"/><stop offset="1" class="m2rj-fbyn"/></linearGradient><linearGradient id="iTAV31c" x1="15.656" x2="15.656" y1="23.391" y2="21.031" gradientUnits="userSpaceOnUse"><stop class="ro6gldb5l"/><stop offset="1" class="yz9f7qbmr"/></linearGradient><linearGradient id="iL9bx4c" x1="14.166" x2="13.759" y1="20.642" y2="20.893" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i7ueWhe" x1="19.822" x2="19.415" y1="20.642" y2="20.893" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iwaQwKc" x1="22.043" x2="15.849" y1="9.914" y2="17.494" gradientUnits="userSpaceOnUse"><stop class="iel_jdbyc"/><stop offset="1" class="qzh8n_zqw"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-bowing" /></template>
<style>
.bhtfot5lc {
  stop-color: var(--svg-color--3b86ba, #3B86BA);
}

.bksouobxj {
  stop-color: var(--svg-color--ee8e1e, #EE8E1E);
}

.bvdn5abpt {
  stop-color: var(--svg-color--ee8e1e, #EE8E1E);
  stop-opacity: 0;
}

.bxic48qwp {
  stop-color: var(--svg-color--2780ad, #2780AD);
}

.c4bn1nh8f {
  stop-color: var(--svg-color--246bd5, #246BD5);
  stop-opacity: 0;
}

.cjenfq8ao {
  d: path("M14.856 14.784c3.359-1.694 3-5.485 3-7.3c.385.02 1.52.112 2.328 1.313c.671.998 1.015 1.228 1.921 1.5s1.875 1.674 1.594 2.521s-4.125 2.45-8.844 1.966");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cl42-t4us {
  stop-color: var(--svg-color--fda222, #FDA222);
  stop-opacity: 0;
}

.cy-darb1h {
  stop-color: var(--svg-color--3a91ce, #3A91CE);
}

.d23y02b4l {
  d: path("M10.955 25.59c.114.03.229.059.332.098c.987.36 1.693 1.268 1.693 2.332c0 .81-.405 1.521-1.038 1.98H5.159c-1.755 0-3.179-1.356-3.179-3.005S3.404 24 5.17 24c.27 0 .54.039.789.098c.114.029.228.058.332.097z");
}

.d6lbdubvl {
  cx: 18.505px;
  cy: 20.448px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.506px;
  ry: 0.256px;
}

.dh21vibgf {
  stop-color: var(--svg-color--d47e20, #D47E20);
  stop-opacity: 0;
}

.duzj_wbgx {
  stop-color: var(--svg-color--ffd106, #FFD106);
  stop-opacity: 0;
}

.dv4icmbqz {
  stop-color: var(--svg-color--f19626, #F19626);
}

.e1oizz7_b {
  d: path("M21.006 25.59c-.114.03-.229.059-.332.098c-.987.36-1.694 1.268-1.694 2.332c0 .81.406 1.521 1.04 1.98h6.782c1.755 0 3.178-1.356 3.178-3.005S28.557 24 26.793 24c-.27 0-.54.039-.79.098c-.114.029-.228.058-.332.097z");
}

.e505wibdz {
  cx: 12.849px;
  cy: 20.448px;
  rx: 0.506px;
  ry: 0.256px;
}

.e89pv8d9w {
  stop-color: var(--svg-color--ffc602, #FFC602);
}

.ed3cdu6st {
  stop-color: var(--svg-color--ffbf1b, #FFBF1B);
}

.f-odvf_ry {
  stop-color: var(--svg-color--146688, #146688);
}

.fgz6lbb_q {
  stop-color: var(--svg-color--ffe948, #FFE948);
}

.fp27koqed {
  d: path("M14.256 20.975c0-.374-.304-.624-.386-.7l-.375.363l.23.469z");
}

.ft5dv1b6b {
  fill: none;
}

.fu0j5nb_v {
  stop-color: var(--svg-color--5767f5, #5767F5);
  stop-opacity: 0;
}

.g_ysjmbrf {
  d: path("m15.64 4.79l-1.122-2.248a.377.377 0 0 1 .34-.542h2.244c.28 0 .46.291.34.542l-1.121 2.247a.38.38 0 0 1-.681 0");
}

.g-ae66bju {
  d: path("m14.667 23.338l.66-2.14c.14-.47.81-.47.96 0l.66 2.14a.678.678 0 0 1-.54.87c-.148.04-.35.07-.612.07c-.302 0-.507-.036-.649-.082a.674.674 0 0 1-.479-.859");
}

.g4f_hhbsk {
  stop-color: var(--svg-color--316da0, #316DA0);
}

.ga0t70bsk {
  stop-color: var(--svg-color--17447e, #17447E);
}

.ge10hrb8f {
  cx: 12.849px;
  cy: 20.448px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.506px;
  ry: 0.256px;
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.h0w3ehbbr {
  d: path("M18.854 19.953a1.158 1.158 0 0 0-1.116 1.463h2.238q.04-.149.042-.305a1.166 1.166 0 0 0-1.164-1.158");
}

.h1n3ss2pg {
  stroke: var(--svg-color--d4725f, #D4725F);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M20.324 18.158c-.203-.152-.844-.488-1.86-.39");
}

.hgx031bkz {
  stroke: var(--svg-color--d4725f, #D4725F);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M11.758 18.07c.203-.153.844-.489 1.86-.391");
}

.hh29jvbig {
  stop-color: var(--svg-color--db8330, #DB8330);
  stop-opacity: 0;
}

.hxyhiv56f {
  d: path("M13.69 7.597c.735-.199 1.678.133 2.26.62v7.22c-1.529-.83-3.24-2.88-3.622-4.052c-.897-2.758.386-3.523 1.362-3.788");
}

.i5vei3bfj {
  stop-color: var(--svg-color--2675b0, #2675B0);
  stop-opacity: 0;
}

.iel_jdbyc {
  stop-color: var(--svg-color--ffdf2d, #FFDF2D);
}

.jlcacfbau {
  d: path("m21.471 5.98l2.37-.79a.38.38 0 0 0 .15-.62l-1.58-1.58c-.2-.2-.53-.12-.62.15l-.79 2.38c-.1.28.18.56.47.46");
}

.jmnvn7nui {
  d: path("m14.86 23.06l.66-2.14c.14-.47.81-.47.96 0l.66 2.14a.678.678 0 0 1-.54.871a2.4 2.4 0 0 1-.613.069c-.301 0-.506-.035-.648-.081a.674.674 0 0 1-.479-.859");
}

.jnop8h4yg {
  stop-color: var(--svg-color--ffcf30, #FFCF30);
  stop-opacity: 0;
}

.l_p06obzw {
  stop-color: var(--svg-color--ea8627, #EA8627);
}

.l4fz75bjj {
  stop-color: var(--svg-color--d47e20, #D47E20);
}

.lf1my1bmo {
  stop-color: var(--svg-color--dcaa39, #DCAA39);
}

.lf3njzbxn {
  stop-color: var(--svg-color--ffe736, #FFE736);
}

.lfr4-msfs {
  stop-color: var(--svg-color--ffe736, #FFE736);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.m2g4nbcbq {
  stop-color: var(--svg-color--f4c222, #F4C222);
}

.m2rj-fbyn {
  stop-color: var(--svg-color--d9802c, #D9802C);
  stop-opacity: 0;
}

.mb_z4bcne {
  stop-color: var(--svg-color--e2872d, #E2872D);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mhdxxgbzz {
  d: path("M21.336 26.5a1.6 1.6 0 0 0-.69.153l-3.708 1.765a.82.82 0 0 0-.457.735c0 .449.34.847.768.847h5.722l.01-1.765c.01-.95-.73-1.725-1.645-1.735");
}

.mrx1hybjj {
  d: path("M19.912 20.975c0-.374-.304-.624-.386-.7l-.374.363l.23.469z");
}

.ms1i9y3sd {
  stop-color: var(--svg-color--305cc7, #305CC7);
}

.n0zizq_8d {
  stop-color: var(--svg-color--ffcf30, #FFCF30);
}

.n4odr4vnh {
  fill: var(--svg-color--c9572b, #C9572B);
  fill-rule: evenodd;
  d: path("M13.57 18.38c-.886-.085-1.404.212-1.512.293a.5.5 0 0 1-.6-.8c.297-.223 1.061-.598 2.207-.488a.5.5 0 0 1-.096.995");
}

.ntnm3dw3i {
  stop-color: var(--svg-color--39baff, #39BAFF);
  stop-opacity: 0;
}

.nzt0dyr_i {
  fill: var(--svg-color--fff, #fff);
  d: path("M19.055 19.6c-.848 0-1.564.585-1.758 1.374a.356.356 0 0 0 .347.442h2.895a.3.3 0 0 0 .295-.352a1.82 1.82 0 0 0-1.78-1.464");
}

.o-css572m {
  fill: var(--svg-color--000, #000);
  d: path("M19.518 21.111a.66.66 0 0 0-.664-.663a.66.66 0 0 0-.59.968h1.175a.66.66 0 0 0 .079-.305");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.og3e4kk-e {
  stop-color: var(--svg-color--2887b4, #2887B4);
}

.onyxmnbkr {
  stop-color: var(--svg-color--fe9f2d, #FE9F2D);
  stop-opacity: 0;
}

.osrxhzfhp {
  stop-color: var(--svg-color--5767f5, #5767F5);
}

.owrgdvbme {
  d: path("m10.493 5.982l-2.38-.79a.373.373 0 0 1-.14-.62l1.58-1.58c.2-.2.53-.12.62.15l.79 2.38c.1.28-.18.56-.47.46");
}

.p_o3_x88l {
  stop-color: var(--svg-color--ffe02c, #FFE02C);
}

.pff_xvb-o {
  stop-color: var(--svg-color--2a6a9d, #2A6A9D);
  stop-opacity: 0;
}

.pijiswbcu {
  d: path("M22.197 9.886c.68.23 1.29.72 1.66 1.42c.31.6.41 1.26.28 1.87l-.015.085l-.015.085l-.77 4.15a2 2 0 0 1-.096.34l-.004.01c-.117.296-.397.525-.713.617c-.144.041-.265-.088-.25-.237l.163-1.726h-.34c-.226-.047-.46-.174-.44-.614l.02-.54c.01-.2-.19-.36-.39-.3c-1.21.35-3.15.8-5.3.8c-2.13 0-4.09-.45-5.31-.81a.3.3 0 0 0-.39.3l.02.55c.02.44-.069.606-.405.606h-.336l.14 1.744c.011.146-.105.272-.247.238c-.412-.099-.776-.414-.842-.818l-.8-4.24l-.019-.086a2.98 2.98 0 0 1 .278-2.024c.37-.69.98-1.18 1.67-1.42c.73-.25 1.36-.74 1.77-1.4a2.98 2.98 0 0 1 3.69-1.15c.24.11.5.16.76.16s.52-.06.76-.16a3 3 0 0 1 3.7 1.15a3.45 3.45 0 0 0 1.77 1.4");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pmyro9arm {
  stop-color: var(--svg-color--d9802c, #D9802C);
}

.q__mu-bme {
  stop-color: var(--svg-color--fda70e, #FDA70E);
}

.q2p7q4bac {
  stop-color: var(--svg-color--fda222, #FDA222);
}

.qkikqtb3f {
  stop-color: var(--svg-color--288fff, #288FFF);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qzh8n_zqw {
  stop-color: var(--svg-color--ffdf2d, #FFDF2D);
  stop-opacity: 0;
}

.r_ckvab-y {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.93 19.6c-.848 0-1.564.585-1.758 1.374a.356.356 0 0 0 .347.442h2.895a.3.3 0 0 0 .295-.352a1.82 1.82 0 0 0-1.78-1.464");
}

.r497yzb9u {
  stop-color: var(--svg-color--c56520, #C56520);
}

.re43f_bny {
  stop-color: var(--svg-color--2e74dd, #2E74DD);
}

.ro6gldb5l {
  stop-color: var(--svg-color--f59d1d, #F59D1D);
}

.rxpqegslo {
  stop-color: var(--svg-color--cd9a3f, #CD9A3F);
}

.s02vtwpqx {
  stop-color: var(--svg-color--2e8db4, #2E8DB4);
  stop-opacity: 0;
}

.t-v22vtsk {
  stop-color: var(--svg-color--ffcd23, #FFCD23);
}

.t1e217bwb {
  stop-color: var(--svg-color--5566f6, #5566F6);
}

.tcm8ipltk {
  stop-color: var(--svg-color--e08d08, #E08D08);
  stop-opacity: 0;
}

.tv3llfnnc {
  stop-color: var(--svg-color--305cc7, #305CC7);
  stop-opacity: 0;
}

.u1-n55buw {
  stop-color: var(--svg-color--46b6ff, #46B6FF);
}

.ua70ijcgb {
  stop-color: var(--svg-color--399be2, #399BE2);
}

.ufuzl_b_h {
  fill: var(--svg-color--c9572b, #C9572B);
  fill-rule: evenodd;
  d: path("M18.43 18.38c.886-.085 1.404.212 1.512.293a.5.5 0 0 0 .6-.8c-.298-.223-1.061-.598-2.207-.488a.5.5 0 0 0 .096.995");
}

.uz747kbcx {
  stop-color: var(--svg-color--f1a124, #F1A124);
  stop-opacity: 0;
}

.v0l5en3es {
  stop-color: var(--svg-color--246bd5, #246BD5);
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.vcgyh92un {
  d: path("M10.625 26.5c.243 0 .477.051.69.153l3.708 1.765a.82.82 0 0 1 .457.735c0 .449-.34.847-.768.847H8.99l-.01-1.765c-.01-.95.73-1.725 1.645-1.735");
}

.vpkqk59tf {
  fill: var(--svg-color--000, #000);
  d: path("M13.861 21.111a.66.66 0 0 0-.663-.663a.66.66 0 0 0-.59.968h1.174a.66.66 0 0 0 .08-.305");
}

.w61tqnb0g {
  d: path("M14.58 8.52h2.82c3.16 0 5.59 2.79 5.18 5.91l-.6 7.27s-.44 4.3-5.97 4.3s-6.03-4.3-6.03-4.3l-.57-7.27c-.36-3.27 2.01-5.91 5.17-5.91");
}

.w6ry4524w {
  stop-color: var(--svg-color--329ee1, #329EE1);
}

.w9napxb6c {
  stop-color: var(--svg-color--f5891f, #F5891F);
}

.wei4uo88h {
  stop-color: var(--svg-color--e08d08, #E08D08);
}

.wx46szfra {
  stop-color: var(--svg-color--2e92db, #2E92DB);
}

.x8a_nqnwc {
  stop-color: var(--svg-color--33b6f8, #33B6F8);
  stop-opacity: 0;
}

.xhq8-uz6x {
  stop-color: var(--svg-color--ffd42a, #FFD42A);
}

.xnds8eb0z {
  cx: 18.505px;
  cy: 20.448px;
  rx: 0.506px;
  ry: 0.256px;
}

.xww7r3f9e {
  stop-color: var(--svg-color--feb91e, #FEB91E);
  stop-opacity: 0;
}

.y06fetb4u {
  stop-color: var(--svg-color--ffd106, #FFD106);
}

.y5vl6_bal {
  d: path("M22.23 19.75a2 2 0 1 0 0-4a2 2 0 0 0 0 4");
}

.y8xk-w_wn {
  stop-color: var(--svg-color--db8330, #DB8330);
}

.yhp94650d {
  stop-color: var(--svg-color--39baff, #39BAFF);
}

.ymz1xs6ex {
  d: path("M9.73 19.75a2 2 0 1 0 0-4a2 2 0 0 0 0 4");
}

.ynyfnhbha {
  stop-color: var(--svg-color--2887b4, #2887B4);
  stop-opacity: 0;
}

.yz9f7qbmr {
  stop-color: var(--svg-color--f59d1d, #F59D1D);
  stop-opacity: 0;
}

.z4vjykd0x {
  d: path("M13.198 19.953a1.158 1.158 0 0 0-1.116 1.463h2.237q.041-.149.042-.305a1.166 1.166 0 0 0-1.163-1.158");
}

.zfree3baf {
  d: path("M26.896 19.188A3.58 3.58 0 0 0 23.591 17H8.29c-1.442 0-2.744.86-3.305 2.188L2.23 25.83h4.75V30h18v-4.15l4.75-.017z");
}

.zy06qjblk {
  stop-color: var(--svg-color--2e7bfe, #2E7BFE);
  stop-opacity: 0;
}

.zy9alzbrq {
  stop-color: var(--svg-color--ffa91c, #FFA91C);
}

</style>
