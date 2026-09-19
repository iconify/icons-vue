<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#i3TeBAC)"><path fill="url(#i6Cgjvd)" class="ope7cobmx"/></g><g filter="url(#icBI3Eb)"><path class="jqg64warz"/></g><path fill="url(#iAiG9Yc)" class="g3ih2vbkp"/><path fill="url(#ixQFgWb)" class="g3ih2vbkp"/><path fill="url(#ie4geXd)" class="g3ih2vbkp"/><path fill="url(#iyNzT5R)" class="u14mdwben"/><path fill="url(#invX9Fb)" class="e4_2xomki"/><circle fill="url(#inj7Zec)" class="b23ua5sqw"/><g filter="url(#ilmGyrd)"><circle fill="url(#isr4NXb)" class="ta2cj8d_l"/></g><circle class="e0r0hkiyh"/><g filter="url(#it5F30d)"><circle class="e0mbnabxe"/></g><path class="bu_gth2kq"/><path fill="url(#iXvfN1d)" class="ms6s56bri"/><g filter="url(#iuoKf2d)"><path fill="url(#iD6nSZc)" class="m0epjrpdy"/><path fill="url(#i1AatND)" class="m0epjrpdy"/><path fill="url(#idjR9bb)" class="m0epjrpdy"/><path fill="url(#i4bQJpd)" class="m0epjrpdy"/></g><g filter="url(#isTd9oe)"><path fill="url(#iKFZiJa)" class="nspd-bc_q"/></g><g filter="url(#iZjhpVp)"><circle stroke="url(#i1bo8mc)" class="opm-362jl"/></g><circle class="thq4f0b3u"/><g filter="url(#iLn2qRU)"><path class="mzglr-0os"/></g><g filter="url(#iDIsNbc)"><path class="d_a34bbeu"/><path fill="url(#i7fim1d)" class="rloq5acco"/></g><path fill="url(#iug5pLb)" transform="rotate(45.489 14.576 13.545)" class="w1o1dzcrs"/><path fill="url(#iLdIhgb)" transform="rotate(45.489 14.576 13.545)" class="w1o1dzcrs"/><path fill="url(#iOfnHsc)" class="p20j9l8ys"/><path fill="url(#iADQXOd)" class="p20j9l8ys"/><path fill="url(#ijBsEib)" class="p20j9l8ys"/><path class="rhvql9b0j"/><path fill="url(#izONlad)" class="gzjmc0u7h"/><path fill="url(#iyr1j1I)" class="gzjmc0u7h"/><path fill="url(#izm1xec)" class="gzjmc0u7h"/><path fill="url(#iAIuQKe)" stroke="url(#ibkkqee)" class="klcwxoikl"/><path clip-rule="evenodd" class="j3k_ndnzw"/><g filter="url(#ikBeBBd)"><path clip-rule="evenodd" class="kfu10dbey"/></g><path fill="url(#iw4nSBd)" stroke="url(#iLIMP7C)" class="b8s9lnb_d"/><path clip-rule="evenodd" class="inr2dgbyr"/><g filter="url(#iUYsHHd)"><path stroke="url(#imygZBb)" clip-rule="evenodd" class="kyazxmlwb"/></g><path fill="url(#igqKAbb)" class="kt0ivv6sc"/><path fill="url(#iQLdV7T)" class="kt0ivv6sc"/><path fill="url(#id4JLlb)" class="kt0ivv6sc"/><path fill="url(#iyAx18c)" class="kt0ivv6sc"/><path fill="url(#i1rIGMc)" clip-rule="evenodd" class="pdh9-7nqt"/><path clip-rule="evenodd" class="t0wdhhb-y"/><path fill="url(#iM9jWZb)" clip-rule="evenodd" class="ia-93s17c"/><path clip-rule="evenodd" class="r9e661rhr"/><path fill="url(#iDGXLDA)" clip-rule="evenodd" class="seg3d7bcj"/><path clip-rule="evenodd" class="p9nkt0b_d"/><path fill="url(#iiOkb9n)" clip-rule="evenodd" class="o7ubd0c6z"/><g filter="url(#ifAXFRd)"><path clip-rule="evenodd" class="e5q7yr13h"/></g><path fill="url(#iH2t6Zb)" class="qhalwxbwc"/><g filter="url(#iXwqnqb)"><path class="ybzktlmqs"/></g><defs><radialGradient id="iAiG9Yc" cx="0" cy="0" r="1" gradientTransform="rotate(-127.875 18.597 4.411)scale(6.23829 9.65927)" gradientUnits="userSpaceOnUse"><stop class="l1d8gzbpr"/><stop offset="1" class="hfjpw3r3n"/></radialGradient><radialGradient id="ixQFgWb" cx="0" cy="0" r="1" gradientTransform="matrix(5.40625 1.9375 -3.91835 10.93347 16.64 17.743)" gradientUnits="userSpaceOnUse"><stop class="n8x10_yyu"/><stop offset="1" class="hf6gjo7so"/></radialGradient><radialGradient id="ie4geXd" cx="0" cy="0" r="1" gradientTransform="matrix(-.20312 .59375 -4.82693 -1.65131 22.031 14.962)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="e53cpys3y"/><stop offset="1" class="izl0csmmw"/></radialGradient><radialGradient id="iyNzT5R" cx="0" cy="0" r="1" gradientTransform="matrix(-.53125 .61718 -2.20347 -1.8967 13.602 18.884)" gradientUnits="userSpaceOnUse"><stop offset=".324" class="ly84fytvy"/><stop offset="1" class="g6sdywbtn"/></radialGradient><radialGradient id="invX9Fb" cx="0" cy="0" r="1" gradientTransform="rotate(-42.975 26.47 -17.62)scale(.63033 .94222)" gradientUnits="userSpaceOnUse"><stop offset=".311" class="u8qeolr3f"/><stop offset="1" class="m4wkn0hmo"/></radialGradient><radialGradient id="inj7Zec" cx="0" cy="0" r="1" gradientTransform="matrix(-1.01562 .92188 -.5107 -.56264 18.653 11.325)" gradientUnits="userSpaceOnUse"><stop offset=".011" class="uh4sajbra"/><stop offset="1" class="n5u671d-u"/></radialGradient><radialGradient id="isr4NXb" cx="0" cy="0" r="1" gradientTransform="matrix(.32031 -.30469 .39566 .41595 17.912 11.913)" gradientUnits="userSpaceOnUse"><stop class="qkzq6ngxm"/><stop offset="1" class="qsbfs9brs"/></radialGradient><radialGradient id="i1AatND" cx="0" cy="0" r="1" gradientTransform="matrix(1.84375 5.88499 -6.78343 2.12523 15.36 14.118)" gradientUnits="userSpaceOnUse"><stop offset=".545" class="dz0jipb-b"/><stop offset="1" class="gb6fkji1r"/></radialGradient><radialGradient id="idjR9bb" cx="0" cy="0" r="1" gradientTransform="matrix(1.43751 1.34374 -1.37698 1.47307 15.888 13.308)" gradientUnits="userSpaceOnUse"><stop offset=".228" class="lelh2xe6v"/><stop offset="1" class="nea38by1j"/></radialGradient><radialGradient id="i4bQJpd" cx="0" cy="0" r="1" gradientTransform="matrix(1.27128 1.07818 -.89068 1.0502 13.433 15.462)" gradientUnits="userSpaceOnUse"><stop offset=".422" class="bruh6vbyh"/><stop offset="1" class="rmf6m6b3y"/></radialGradient><radialGradient id="i7fim1d" cx="0" cy="0" r="1" gradientTransform="rotate(135.14 5.02 11.005)scale(.85969 .22297)" gradientUnits="userSpaceOnUse"><stop offset=".254" class="hxo-hsbpj"/><stop offset="1" class="pdslbmrwt"/></radialGradient><radialGradient id="iLdIhgb" cx="0" cy="0" r="1" gradientTransform="rotate(90.613 .789 14.136)scale(.28732 .60402)" gradientUnits="userSpaceOnUse"><stop offset=".649" class="wjyjhxryd"/><stop offset="1" class="y01zyrbyt"/></radialGradient><radialGradient id="izONlad" cx="0" cy="0" r="1" gradientTransform="matrix(-.46094 .29687 -.34413 -.53431 11.951 16.3)" gradientUnits="userSpaceOnUse"><stop offset=".214" class="y84i3jbqp"/><stop offset="1" class="mn36x_bue"/></radialGradient><radialGradient id="ibkkqee" cx="0" cy="0" r="1" gradientTransform="rotate(133.409 5.76 9.632)scale(1.9895 1.30599)" gradientUnits="userSpaceOnUse"><stop class="y_4rzacqk"/><stop offset=".96" class="td_1nybnc"/></radialGradient><radialGradient id="iLIMP7C" cx="0" cy="0" r="1" gradientTransform="matrix(-1.0078 1.59375 -1.27162 -.8041 13.74 14.925)" gradientUnits="userSpaceOnUse"><stop class="y_4rzacqk"/><stop offset="1" class="psw8g7_uy"/></radialGradient><radialGradient id="igqKAbb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.75 -2.62501 3.8318 -4.01424 14.203 11.837)" gradientUnits="userSpaceOnUse"><stop class="taiuw254n"/><stop offset="1" class="wk7-7rb8w"/></radialGradient><radialGradient id="iQLdV7T" cx="0" cy="0" r="1" gradientTransform="rotate(-157.729 8.553 4.821)scale(6.59658 10.6884)" gradientUnits="userSpaceOnUse"><stop offset=".546" class="g4b5macvs"/><stop offset="1" class="s4_cj8byh"/></radialGradient><radialGradient id="id4JLlb" cx="0" cy="0" r="1" gradientTransform="matrix(.20313 -1.98437 .81115 .08303 8.766 13.68)" gradientUnits="userSpaceOnUse"><stop class="mo87chbhx"/><stop offset="1" class="bbj4eu2oj"/></radialGradient><radialGradient id="iM9jWZb" cx="0" cy="0" r="1" gradientTransform="rotate(146.787 3.532 4.3)scale(3.43755 1.60167)" gradientUnits="userSpaceOnUse"><stop offset=".402" class="hofau5bhk"/><stop offset="1" class="t54rujbrr"/></radialGradient><radialGradient id="iDGXLDA" cx="0" cy="0" r="1" gradientTransform="matrix(-3.21274 2.13195 -.99864 -1.5049 8.962 7.084)" gradientUnits="userSpaceOnUse"><stop offset=".402" class="hofau5bhk"/><stop offset="1" class="t54rujbrr"/></radialGradient><radialGradient id="iiOkb9n" cx="0" cy="0" r="1" gradientTransform="rotate(144.615 3.35 5.24)scale(3.29193 1.58011)" gradientUnits="userSpaceOnUse"><stop offset=".402" class="hofau5bhk"/><stop offset="1" class="t54rujbrr"/></radialGradient><radialGradient id="iH2t6Zb" cx="0" cy="0" r="1" gradientTransform="rotate(4.852 -43.738 127.665)scale(6.3945 3.71258)" gradientUnits="userSpaceOnUse"><stop offset=".344" class="dvwb7ebev"/><stop offset="1" class="h-knxwkhr"/></radialGradient><linearGradient id="i6Cgjvd" x1="26.833" x2="2.047" y1="16.612" y2="16.612" gradientUnits="userSpaceOnUse"><stop class="q8sgc5k5k"/><stop offset="1" class="o5v952b3t"/></linearGradient><linearGradient id="iXvfN1d" x1="16.656" x2="16.93" y1="10.352" y2="10.884" gradientUnits="userSpaceOnUse"><stop offset=".18" class="pv3974bmp"/><stop offset=".592" class="db8r1b6ef"/></linearGradient><linearGradient id="iD6nSZc" x1="19.016" x2="14.391" y1="13.868" y2="19.368" gradientUnits="userSpaceOnUse"><stop class="d0zw7oq6w"/><stop offset=".886" class="cs1vkybxa"/></linearGradient><linearGradient id="iKFZiJa" x1="26.833" x2="2.047" y1="23.675" y2="23.675" gradientUnits="userSpaceOnUse"><stop class="t8k4gwbbc"/><stop offset="1" class="kpw0uhrkg"/></linearGradient><linearGradient id="i1bo8mc" x1="17.219" x2="17.188" y1="17.681" y2="15.774" gradientUnits="userSpaceOnUse"><stop class="rzorcbc7r"/><stop offset="1" class="lt8zy5hkm"/></linearGradient><linearGradient id="iug5pLb" x1="14.945" x2="14.954" y1="13.719" y2="14.669" gradientUnits="userSpaceOnUse"><stop class="uhfoyqb3x"/><stop offset="1" class="eb0haibji"/></linearGradient><linearGradient id="iOfnHsc" x1="16.334" x2="17.49" y1="11.441" y2="11.23" gradientUnits="userSpaceOnUse"><stop class="nd7thpbgb"/><stop offset="1" class="fs5c4ebko"/></linearGradient><linearGradient id="iADQXOd" x1="16.734" x2="16.848" y1="10.743" y2="10.821" gradientUnits="userSpaceOnUse"><stop offset=".354" class="r7rn_bcmx"/><stop offset="1" class="ht-1xqb8g"/></linearGradient><linearGradient id="ijBsEib" x1="17.383" x2="17.301" y1="11.161" y2="11.106" gradientUnits="userSpaceOnUse"><stop class="hb9tx9b6i"/><stop offset="1" class="ppgh7wbyg"/></linearGradient><linearGradient id="iyr1j1I" x1="11.422" x2="11.305" y1="17.087" y2="16.903" gradientUnits="userSpaceOnUse"><stop offset=".145" class="u8ol5ho1k"/><stop offset="1" class="bbcrpz64i"/></linearGradient><linearGradient id="izm1xec" x1="10.984" x2="11.027" y1="16.458" y2="16.528" gradientUnits="userSpaceOnUse"><stop class="bwf4x3cld"/><stop offset="1" class="a5orf1efs"/></linearGradient><linearGradient id="iAIuQKe" x1="16.467" x2="15.279" y1="12.168" y2="13.402" gradientUnits="userSpaceOnUse"><stop class="z1dq245it"/><stop offset="1" class="jzcp_rb0i"/></linearGradient><linearGradient id="iw4nSBd" x1="13.678" x2="12.49" y1="14.925" y2="16.16" gradientUnits="userSpaceOnUse"><stop class="z1dq245it"/><stop offset="1" class="jzcp_rb0i"/></linearGradient><linearGradient id="imygZBb" x1="14.269" x2="12.127" y1="14.672" y2="16.718" gradientUnits="userSpaceOnUse"><stop offset=".096" class="qi1y9bzby"/><stop offset=".322" class="f-nlkoezi"/><stop offset=".768" class="qi1y9bzby"/></linearGradient><linearGradient id="iyAx18c" x1="13.703" x2="13.641" y1="12.466" y2="12.407" gradientUnits="userSpaceOnUse"><stop class="d1-v2bc1s"/><stop offset="1" class="lt8u35u8x"/></linearGradient><linearGradient id="i1rIGMc" x1="8.172" x2="10.923" y1="3.89" y2="3.632" gradientUnits="userSpaceOnUse"><stop class="l2jvne_2k"/><stop offset="1" class="gw4pa76xg"/></linearGradient><filter id="i3TeBAC" width="28.306" height="9.762" x="1.847" y="12.196" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.32549 0 0 0 0 0.729412 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23159"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.247059 0 0 0 0 0.584314 0 0 0 0 0.854902 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23159" result="effect2_innerShadow_3987_23159"/></filter><filter id="icBI3Eb" width="19.969" height="19.969" x="10.642" y="1.845" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1.25" dy="-1.25"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.819608 0 0 0 0 0.568627 0 0 0 0 0.478431 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23159"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.776471 0 0 0 0 0.505882 0 0 0 0 0.388235 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23159" result="effect2_innerShadow_3987_23159"/></filter><filter id="ilmGyrd" width="2.053" height="2.053" x="16.759" y="10.956" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23159" stdDeviation=".075"/></filter><filter id="it5F30d" width="2.044" height="2.044" x="11.179" y="16.549" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23159" stdDeviation=".1"/></filter><filter id="iuoKf2d" width="11.327" height="11.381" x="8.984" y="8.622" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.686275 0 0 0 0 0.462745 0 0 0 0 0.560784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23159"/></filter><filter id="isTd9oe" width="28.306" height="9.762" x="1.847" y="19.259" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.301961 0 0 0 0 0.580392 0 0 0 0 0.87451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23159"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.207843 0 0 0 0 0.482353 0 0 0 0 0.772549 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23159" result="effect2_innerShadow_3987_23159"/></filter><filter id="iZjhpVp" width="2.217" height="2.217" x="15.887" y="15.642" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23159" stdDeviation=".1"/></filter><filter id="iLn2qRU" width="3.106" height="3.164" x="13.726" y="13.908" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23159" stdDeviation=".25"/></filter><filter id="iDIsNbc" width="2.203" height="2.458" x="14.338" y="13.935" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.72549 0 0 0 0 0.482353 0 0 0 0 0.498039 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23159"/><feGaussianBlur result="effect2_foregroundBlur_3987_23159" stdDeviation=".05"/></filter><filter id="ikBeBBd" width="2.872" height="2.874" x="14.46" y="11.367" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23159" stdDeviation=".075"/></filter><filter id="iUYsHHd" width="2.872" height="2.874" x="11.68" y="14.162" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23159" stdDeviation=".075"/></filter><filter id="ifAXFRd" width="4.333" height="3.319" x="7.677" y="5.396" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.4"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.784314 0 0 0 0 0.517647 0 0 0 0 0.403922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23159"/></filter><filter id="iXwqnqb" width="10.371" height="13.323" x="17.499" y="4.779" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23159" stdDeviation=".35"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-swimming-medium-light" /></template>
<style>
.a5orf1efs {
  stop-color: var(--svg-color--504b5b, #504B5B);
  stop-opacity: 0;
}

.b23ua5sqw {
  cx: 17.785px;
  cy: 11.983px;
  r: 1.296px;
}

.b8s9lnb_d {
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("m13.805 15.86l-.488.475a.696.696 0 0 1-.973-.996l.488-.476a.696.696 0 1 1 .973.996Z");
}

.bbcrpz64i {
  stop-color: var(--svg-color--443873, #443873);
  stop-opacity: 0;
}

.bbj4eu2oj {
  stop-color: var(--svg-color--dd617e, #DD617E);
  stop-opacity: 0;
}

.bruh6vbyh {
  stop-color: var(--svg-color--ab717c, #AB717C);
}

.bu_gth2kq {
  fill: var(--svg-color--c28d96, #C28D96);
  d: path("m10.762 16.79l-.84-.715l.293-.554l1.137.886z");
}

.bwf4x3cld {
  stop-color: var(--svg-color--504b5b, #504B5B);
}

.cs1vkybxa {
  stop-color: var(--svg-color--b37783, #B37783);
}

.d_a34bbeu {
  fill: var(--svg-color--ddac8e, #DDAC8E);
  d: path("m15.22 16.072l-.782-1.555l.29-.282l1.51.853a.4.4 0 0 1 .084.633l-.465.457a.4.4 0 0 1-.638-.106");
}

.d0zw7oq6w {
  stop-color: var(--svg-color--fdc9a7, #FDC9A7);
}

.d1-v2bc1s {
  stop-color: var(--svg-color--f64a6a, #F64A6A);
}

.db8r1b6ef {
  stop-color: var(--svg-color--c6a06f, #C6A06F);
}

.dvwb7ebev {
  stop-color: var(--svg-color--c99878, #C99878);
}

.dz0jipb-b {
  stop-color: var(--svg-color--d59e95, #D59E95);
  stop-opacity: 0;
}

.e0mbnabxe {
  cx: 12.201px;
  cy: 17.571px;
  r: 0.822px;
  fill: var(--svg-color--a76669, #A76669);
}

.e0r0hkiyh {
  cx: 12.201px;
  cy: 17.571px;
  r: 1.296px;
  fill: var(--svg-color--ae6e7f, #AE6E7F);
}

.e4_2xomki {
  d: path("m19.598 12.782l-.614-.668l-.785.73l1.664 1.91c.375-.843.047-1.632-.265-1.972");
}

.e53cpys3y {
  stop-color: var(--svg-color--bc7e5b, #BC7E5B);
}

.e5q7yr13h {
  fill: var(--svg-color--cd9881, #CD9881);
  fill-rule: evenodd;
  d: path("M11.348 7.095c-.585 0-1.22.253-1.659.551c-.31.21-.668.603-.82.805a.662.662 0 1 1-1.058-.799c.202-.266.661-.78 1.133-1.101c.63-.428 1.52-.755 2.404-.755c.366 0 .662.296.662.662s-.296.637-.662.637");
}

.eb0haibji {
  stop-color: var(--svg-color--413251, #413251);
}

.f-nlkoezi {
  stop-color: var(--svg-color--5f5669, #5F5669);
  stop-opacity: 0;
}

.fs5c4ebko {
  stop-color: var(--svg-color--4c4055, #4C4055);
}

.ft5dv1b6b {
  fill: none;
}

.g3ih2vbkp {
  d: path("M17.313 16.618c-1.688 1.15-3.224 3.25-3.782 4.156c3.25 2.163 7.927 2.172 9.86 1.907l6.53-2.266c-.765-1.305-2.036-2.52-2.53-3l-5.407-2.375c-.937 0-2.562.14-4.672 1.578");
}

.g4b5macvs {
  stop-color: var(--svg-color--ad525e, #AD525E);
  stop-opacity: 0;
}

.g6sdywbtn {
  stop-color: var(--svg-color--d49d9b, #D49D9B);
}

.gb6fkji1r {
  stop-color: var(--svg-color--a46379, #A46379);
}

.gw4pa76xg {
  stop-color: var(--svg-color--c69976, #C69976);
}

.gzjmc0u7h {
  d: path("M10.925 17.376a.1.1 0 0 1-.138-.029l-.29-.445a.1.1 0 0 1 .03-.138l1.253-.818l.4.612z");
}

.h-knxwkhr {
  stop-color: var(--svg-color--e1ac8c, #E1AC8C);
  stop-opacity: 0;
}

.hb9tx9b6i {
  stop-color: var(--svg-color--574e60, #574E60);
}

.hf6gjo7so {
  stop-color: var(--svg-color--e0a580, #E0A580);
  stop-opacity: 0;
}

.hfjpw3r3n {
  stop-color: var(--svg-color--dfa67f, #DFA67F);
}

.hofau5bhk {
  stop-color: var(--svg-color--bc8665, #BC8665);
}

.ht-1xqb8g {
  stop-color: var(--svg-color--403044, #403044);
  stop-opacity: 0;
}

.hxo-hsbpj {
  stop-color: var(--svg-color--f3c4a7, #F3C4A7);
}

.ia-93s17c {
  fill-rule: evenodd;
  d: path("M11.266 4.003a.663.663 0 0 1-.608.713c-1.395.111-2.487 1.077-3.036 1.863a.663.663 0 0 1-1.087-.758c.678-.971 2.085-2.271 4.018-2.426a.663.663 0 0 1 .713.608");
}

.inr2dgbyr {
  fill: var(--svg-color--412e4c, #412E4C);
  fill-rule: evenodd;
  d: path("m14.144 16.206l-.488.476a1.182 1.182 0 0 1-1.65-1.69l.487-.476a1.181 1.181 0 0 1 1.65 1.69m-.238-1.419a.82.82 0 0 0-1.162-.014l-.487.476a.821.821 0 1 0 1.148 1.176l.487-.476a.82.82 0 0 0 .014-1.162");
}

.izl0csmmw {
  stop-color: var(--svg-color--c6916f, #C6916F);
  stop-opacity: 0;
}

.j3k_ndnzw {
  fill: var(--svg-color--412e4c, #412E4C);
  fill-rule: evenodd;
  d: path("m16.933 13.448l-.488.476a1.181 1.181 0 1 1-1.65-1.69l.487-.476a1.181 1.181 0 0 1 1.65 1.69m-.238-1.419a.82.82 0 0 0-1.162-.014l-.487.476a.821.821 0 0 0 1.148 1.176l.487-.476a.82.82 0 0 0 .014-1.162");
}

.jqg64warz {
  fill: var(--svg-color--ebb793, #EBB793);
  d: path("M10.642 7.095h4.828a4 4 0 0 1 3.602 2.26l6.164 12.459l4.125-.594l-6.687-13.604a8 8 0 0 0-7.204-4.521h-4.43z");
}

.jzcp_rb0i {
  stop-color: var(--svg-color--4893e1, #4893E1);
}

.kfu10dbey {
  stroke: var(--svg-color--5c4c6d, #5C4C6D);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M16.857 11.867c-.364-.373-1-.41-1.373-.046l-.559.546c-.373.364-.34.99.024 1.363c.363.372.976.43 1.348.067l.56-.546c.372-.364.364-1.012 0-1.384Z");
}

.klcwxoikl {
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("m16.594 13.101l-.488.476a.696.696 0 0 1-.973-.996l.488-.476a.696.696 0 1 1 .973.996Z");
}

.kpw0uhrkg {
  stop-color: var(--svg-color--4184e7, #4184E7);
}

.kt0ivv6sc {
  d: path("M9.475 15.78c-1.367-1.366-1.202-3.537.236-5.17l1.21-1.203c1.556-1.414 3.79-1.595 5.156-.228l.317.317a.2.2 0 0 1 0 .283l-6.319 6.319a.2.2 0 0 1-.282 0z");
}

.kyazxmlwb {
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.077 14.661c-.364-.372-1-.409-1.373-.045l-.56.546c-.372.364-.34.99.024 1.362s.977.431 1.35.068l.559-.546c.372-.364.363-1.012 0-1.385Z");
}

.l1d8gzbpr {
  stop-color: var(--svg-color--eab8a0, #EAB8A0);
}

.l2jvne_2k {
  stop-color: var(--svg-color--d59d7b, #D59D7B);
}

.lelh2xe6v {
  stop-color: var(--svg-color--b27a68, #B27A68);
}

.lt8u35u8x {
  stop-color: var(--svg-color--f64a6a, #F64A6A);
  stop-opacity: 0;
}

.lt8zy5hkm {
  stop-color: var(--svg-color--e3a695, #E3A695);
}

.ly84fytvy {
  stop-color: var(--svg-color--c68785, #C68785);
}

.m0epjrpdy {
  d: path("m8.984 14.873l6.11-6.1l4.26 4.74a3.15 3.15 0 0 1-.079 4.296l-1.195 1.235a3.15 3.15 0 0 1-4.39.134z");
}

.m4wkn0hmo {
  stop-color: var(--svg-color--eab78b, #EAB78B);
}

.mn36x_bue {
  stop-color: var(--svg-color--483e5b, #483E5B);
  stop-opacity: 0;
}

.mo87chbhx {
  stop-color: var(--svg-color--dd617e, #DD617E);
}

.ms6s56bri {
  d: path("m17.133 10.458l-.758-.742l-.844.3c.401.428 1.206 1.277 1.215 1.258z");
}

.mzglr-0os {
  fill: var(--svg-color--b97b7c, #B97B7C);
  d: path("m15.047 16.34l-.821-1.637l.304-.295l1.588.896a.42.42 0 0 1 .088.666l-.488.48a.42.42 0 0 1-.67-.11");
}

.n5u671d-u {
  stop-color: var(--svg-color--e7ad85, #E7AD85);
}

.n8x10_yyu {
  stop-color: var(--svg-color--a86d65, #A86D65);
}

.nd7thpbgb {
  stop-color: var(--svg-color--574c62, #574C62);
}

.nea38by1j {
  stop-color: var(--svg-color--b27a68, #B27A68);
  stop-opacity: 0;
}

.nspd-bc_q {
  d: path("M3.922 19.259c-.975 0-1.656.49-1.875.734v9.028h27.906v-8.872l-.003-.003c-.623-.545-1.015-.887-2.2-.887c-.906 0-1.67.67-2.05 1.003c-.261.225-.94.637-1.864.637s-1.469-.406-2.07-.906c-.27-.223-.952-.734-1.914-.734c-.963 0-1.857.666-2.165 1c-.244.224-.718.64-1.87.64c-.794 0-1.396-.35-1.614-.562c-.37-.36-1.133-1.078-2.312-1.078c-.975 0-1.54.468-1.907.781s-1.006.89-2.093.89c-.985 0-1.585-.5-1.915-.774l-.007-.007c-.276-.297-1.072-.89-2.047-.89");
}

.o5v952b3t {
  stop-color: var(--svg-color--3ea5fe, #3EA5FE);
}

.o7ubd0c6z {
  fill-rule: evenodd;
  d: path("M11.379 5.607a.663.663 0 0 1-.635.69c-1.183.05-2.097.941-2.665 1.87a.663.663 0 0 1-1.131-.69c.651-1.066 1.893-2.426 3.74-2.504a.663.663 0 0 1 .69.634");
}

.ope7cobmx {
  d: path("M3.922 12.196c-.975 0-1.656.49-1.875.735v9.027h27.906v-8.871l-.003-.003c-.623-.545-1.015-.888-2.2-.888c-.906 0-1.67.67-2.05 1.004c-.261.224-.94.637-1.864.637s-1.469-.406-2.07-.906c-.27-.224-.952-.735-1.914-.735c-.963 0-1.857.667-2.165 1c-.244.224-.718.64-1.87.64c-.794 0-1.396-.35-1.614-.562c-.37-.359-1.133-1.078-2.312-1.078c-.975 0-1.54.469-1.907.781s-1.006.891-2.093.891c-.985 0-1.585-.5-1.915-.775l-.007-.006c-.276-.297-1.072-.89-2.047-.89");
}

.opm-362jl {
  cx: 16.996px;
  cy: 16.751px;
  r: 0.809px;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
}

.p20j9l8ys {
  d: path("M17.065 10.303a.1.1 0 0 1 .139-.026l.439.297a.1.1 0 0 1 .027.14l-.84 1.239l-.605-.41z");
}

.p9nkt0b_d {
  fill: var(--svg-color--ca997a, #CA997A);
  fill-rule: evenodd;
  d: path("M11.379 5.607a.663.663 0 0 1-.635.69c-1.183.05-2.097.941-2.665 1.87a.663.663 0 0 1-1.131-.69c.651-1.066 1.893-2.426 3.74-2.504a.663.663 0 0 1 .69.634");
}

.pdh9-7nqt {
  fill-rule: evenodd;
  d: path("M9.936 4.505c-.557.044-1.037.103-1.262.16a.66.66 0 0 1-.804-.488a.673.673 0 0 1 .48-.816c.836-.214 1.78-.266 2.642-.266c.366 0 .647.287.647.658s.106.687-.26.687c-.345 0-.9.023-1.443.065");
}

.pdslbmrwt {
  stop-color: var(--svg-color--f3c4a7, #F3C4A7);
  stop-opacity: 0;
}

.ppgh7wbyg {
  stop-color: var(--svg-color--574e60, #574E60);
  stop-opacity: 0;
}

.psw8g7_uy {
  stop-color: var(--svg-color--2c6fb5, #2C6FB5);
}

.pv3974bmp {
  stop-color: var(--svg-color--fad7a6, #FAD7A6);
}

.q8sgc5k5k {
  stop-color: var(--svg-color--40aafe, #40AAFE);
}

.qhalwxbwc {
  d: path("M10.642 7.095h4.828a4 4 0 0 1 3.602 2.26l6.164 12.459l4.125-.594l-6.687-13.604a8 8 0 0 0-7.204-4.521h-4.457z");
}

.qi1y9bzby {
  stop-color: var(--svg-color--5f5669, #5F5669);
}

.qkzq6ngxm {
  stop-color: var(--svg-color--e7b18d, #E7B18D);
}

.qsbfs9brs {
  stop-color: var(--svg-color--dea076, #DEA076);
}

.r7rn_bcmx {
  stop-color: var(--svg-color--403044, #403044);
}

.r9e661rhr {
  fill: var(--svg-color--ca997a, #CA997A);
  fill-rule: evenodd;
  d: path("M11.67 4.784a.663.663 0 0 1-.607.713c-.639.051-1.95.36-2.427.804c-.482.447-.861 1.004-1.156 1.487a.662.662 0 1 1-1.131-.69c.314-.516.769-1.196 1.385-1.768c.62-.576 1.5-1.153 3.223-1.153c.366 0 .684.242.713.607");
}

.rhvql9b0j {
  fill: var(--svg-color--4e496a, #4E496A);
  d: path("M10.925 17.376a.1.1 0 0 1-.138-.029l-.29-.445a.1.1 0 0 1 .03-.138l1.253-.818l.4.612z");
}

.rloq5acco {
  d: path("m15.22 16.072l-.782-1.555l.29-.282l1.51.853a.4.4 0 0 1 .084.633l-.465.457a.4.4 0 0 1-.638-.106");
}

.rmf6m6b3y {
  stop-color: var(--svg-color--ab717c, #AB717C);
  stop-opacity: 0;
}

.rzorcbc7r {
  stop-color: var(--svg-color--dbab9f, #DBAB9F);
}

.s4_cj8byh {
  stop-color: var(--svg-color--ad525e, #AD525E);
}

.seg3d7bcj {
  fill-rule: evenodd;
  d: path("M11.67 4.784a.663.663 0 0 1-.607.713c-.639.051-1.95.36-2.427.804c-.482.447-.861 1.004-1.156 1.487a.662.662 0 1 1-1.131-.69c.314-.516.769-1.196 1.385-1.768c.62-.576 1.5-1.153 3.223-1.153c.366 0 .684.242.713.607");
}

.t0wdhhb-y {
  fill: var(--svg-color--ca997a, #CA997A);
  fill-rule: evenodd;
  d: path("M11.266 4.003a.663.663 0 0 1-.608.713c-1.395.111-2.487 1.077-3.036 1.863a.663.663 0 0 1-1.087-.758c.678-.971 2.085-2.271 4.018-2.426a.663.663 0 0 1 .713.608");
}

.t54rujbrr {
  stop-color: var(--svg-color--bc8665, #BC8665);
  stop-opacity: 0;
}

.t8k4gwbbc {
  stop-color: var(--svg-color--3f90f0, #3F90F0);
}

.ta2cj8d_l {
  cx: 17.785px;
  cy: 11.983px;
  r: 0.877px;
}

.taiuw254n {
  stop-color: var(--svg-color--fb5684, #FB5684);
}

.td_1nybnc {
  stop-color: var(--svg-color--1f64c4, #1F64C4);
}

.thq4f0b3u {
  cx: 16.996px;
  cy: 16.751px;
  r: 0.809px;
  fill: var(--svg-color--87014e, #87014E);
}

.u14mdwben {
  d: path("m12.973 19.337l-.614-.57l.235-.938l2.14 1.871c-.937.266-1.493-.131-1.761-.363");
}

.u8ol5ho1k {
  stop-color: var(--svg-color--443873, #443873);
}

.u8qeolr3f {
  stop-color: var(--svg-color--ffd6a4, #FFD6A4);
}

.uh4sajbra {
  stop-color: var(--svg-color--f2c2a2, #F2C2A2);
}

.uhfoyqb3x {
  stop-color: var(--svg-color--52475d, #52475D);
}

.w1o1dzcrs {
  d: path("M14.576 13.545h.758v1.123h-.758z");
}

.wjyjhxryd {
  stop-color: var(--svg-color--453b50, #453B50);
}

.wk7-7rb8w {
  stop-color: var(--svg-color--e12e6e, #E12E6E);
}

.y_4rzacqk {
  stop-color: var(--svg-color--54abec, #54ABEC);
}

.y01zyrbyt {
  stop-color: var(--svg-color--453b50, #453B50);
  stop-opacity: 0;
}

.y84i3jbqp {
  stop-color: var(--svg-color--483e5b, #483E5B);
}

.ybzktlmqs {
  fill: var(--svg-color--f3c0a3, #F3C0A3);
  d: path("M20.637 7.527c-.675-1.475-1.907-1.969-2.438-2.031c1.469-.157 2.672.789 3.156 1.656l5.815 10.25l-2.533-1.281c-1.052-2.25-3.325-7.12-4-8.594");
}

.z1dq245it {
  stop-color: var(--svg-color--479ded, #479DED);
}

</style>
