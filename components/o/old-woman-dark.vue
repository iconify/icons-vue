<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#i8Yfxmc)" class="estahhywh"/><g filter="url(#ikMO96c)"><path class="gqg8xzo3g"/><path fill="url(#i9hEG8b)" class="axrc_wsrb"/></g><path fill="url(#iY1L1Nd)" class="btm1a2bhh"/><path fill="url(#ivF7Ubb)" class="btm1a2bhh"/><g filter="url(#i5DIjqd)"><path fill="url(#i1XtxAb)" class="vtynmbbzd"/></g><g filter="url(#imS4zYG)"><path class="buxgdcbal"/><path fill="url(#iFLQCob)" class="t-t5e7bov"/></g><g filter="url(#iSq1lFb)"><path fill="url(#icLHaGo)" class="h-s1ac-oh"/><path fill="url(#i3AZxji)" class="h-s1ac-oh"/></g><g filter="url(#iw6bwAb)"><path class="nmap8bczm"/><path fill="url(#i5Xtr4c)" class="ei5heabxh"/></g><g filter="url(#i7i59hb)"><path fill="url(#iQJaR9c)" class="spxz5vbis"/><path fill="url(#iCLkhpc)" class="spxz5vbis"/><path fill="url(#iF4HWEe)" class="spxz5vbis"/><path fill="url(#i9FZcKb)" class="spxz5vbis"/><path fill="url(#ifV8rLe)" class="spxz5vbis"/><path fill="url(#iZoKfZb)" class="spxz5vbis"/></g><path fill="url(#iNK7NML)" class="spxz5vbis"/><path fill="url(#iWVrpIc)" class="spxz5vbis"/><path fill="url(#iVP8lXb)" class="spxz5vbis"/><path fill="url(#iWwMjae)" class="spxz5vbis"/><g filter="url(#iM1oh8d)"><path class="ktbp48b3z"/></g><g filter="url(#iOCtycb)"><path class="m8t636bcz"/><path fill="url(#iJ9sMoe)" class="j1t9k-s0o"/><path fill="url(#iOinzFe)" class="j1t9k-s0o"/><path fill="url(#iCoU8xc)" class="j1t9k-s0o"/><path fill="url(#iI1EGFe)" class="j1t9k-s0o"/></g><path fill="url(#iN6cYDd)" class="j1t9k-s0o"/><path fill="url(#iAWmSle)" class="j1t9k-s0o"/><path stroke="url(#isW0F5d)" class="mqfwqob3e"/><g filter="url(#iaiPMMd)"><path class="yjdpsuykb"/></g><g filter="url(#iVDZNib)"><path class="dz24a9bdx"/></g><g filter="url(#iDVwvsb)"><path class="ckmwos09j"/></g><g filter="url(#iPk7c1b)"><path class="aef08ybhj"/></g><path class="z5hcufbzz"/><path fill="url(#iRsUyNu)" class="bn9_xfr7t"/><path class="unb3robxh"/><g filter="url(#iyMobsX)"><path fill="url(#ieNq3od)" class="vzcmxob8j"/></g><g filter="url(#ipz7Lcc)"><ellipse transform="rotate(-27.914 11.432 18.201)" class="bv_oasbmn"/><ellipse fill="url(#i4BeKMb)" transform="rotate(-27.914 11.432 18.201)" class="akdceqbho"/></g><path class="xzhu5kb8a"/><path fill="url(#iBJZF7h)" class="v8b4zib9a"/><path class="rg7dtccaw"/><g filter="url(#iXrPMIe)"><path class="m5u6hrbbe"/><path fill="url(#if7rqoc)" class="aoi4rrb-h"/></g><g filter="url(#iAk10Ie)"><path fill="url(#iNKGTMd)" class="mo-xo_0ef"/></g><g filter="url(#iAhNxCc)"><path stroke="url(#ipNbFoN)" class="hrsq7eket"/></g><g filter="url(#ivrIeto)"><path stroke="url(#iiVwdqe)" class="r7is_wb0l"/></g><g filter="url(#iPMmKZb)"><path fill="url(#i5wZpJb)" class="rrkbucuoy"/></g><g filter="url(#iWEKkEb)"><path fill="url(#icuNDec)" class="c9h0wxb7i"/></g><path clip-rule="evenodd" class="k-jgyeioh"/><path clip-rule="evenodd" class="c77l-utpr"/><defs><radialGradient id="i8Yfxmc" cx="0" cy="0" r="1" gradientTransform="rotate(159.45 8.832 4.39)scale(8.16232 6.90297)" gradientUnits="userSpaceOnUse"><stop offset=".096" class="jpk3lwb9k"/><stop offset=".879" class="mzsejxbhe"/></radialGradient><radialGradient id="i9hEG8b" cx="0" cy="0" r="1" gradientTransform="matrix(7.70897 -9.00929 11.38856 9.74484 6.164 15.722)" gradientUnits="userSpaceOnUse"><stop class="jwo0h5dbt"/><stop offset="1" class="igxv_jb3j"/></radialGradient><radialGradient id="iY1L1Nd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.73002 0 0 -3.69719 8.345 14.645)" gradientUnits="userSpaceOnUse"><stop offset=".223" class="lxwev9kth"/><stop offset="1" class="dbmm3wbls"/></radialGradient><radialGradient id="ivF7Ubb" cx="0" cy="0" r="1" gradientTransform="rotate(-109.573 9.186 .903)scale(1.93641 .96821)" gradientUnits="userSpaceOnUse"><stop offset=".167" class="edx7bubmp"/><stop offset="1" class="m2s_72ssr"/></radialGradient><radialGradient id="iFLQCob" cx="0" cy="0" r="1" gradientTransform="matrix(-2.23544 0 0 -1.76349 7.429 19.475)" gradientUnits="userSpaceOnUse"><stop offset=".667" class="pj2ff5nxp"/><stop offset="1" class="sdufqstmc"/></radialGradient><radialGradient id="icLHaGo" cx="0" cy="0" r="1" gradientTransform="rotate(-24.444 58.383 -44.239)scale(5.09754 6.22385)" gradientUnits="userSpaceOnUse"><stop offset=".64" class="ayiod_bfg"/><stop offset=".944" class="wb78_hxsc"/></radialGradient><radialGradient id="i3AZxji" cx="0" cy="0" r="1" gradientTransform="matrix(2.45313 1.375 -.38873 .69354 25.46 16.24)" gradientUnits="userSpaceOnUse"><stop class="s9u3_wbrp"/><stop offset="1" class="crde6o_5i"/></radialGradient><radialGradient id="i5Xtr4c" cx="0" cy="0" r="1" gradientTransform="matrix(2.79684 -.20804 .16263 2.18635 24.225 19.683)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="rmmi4abgs"/><stop offset="1" class="xuyenabum"/></radialGradient><radialGradient id="iQJaR9c" cx="0" cy="0" r="1" gradientTransform="matrix(-10.06253 11.24998 -11.00901 -9.847 22.462 17.563)" gradientUnits="userSpaceOnUse"><stop offset=".239" class="ts8y9ypsy"/><stop offset="1" class="t18jwhbnk"/></radialGradient><radialGradient id="iCLkhpc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.1875 3.14012 0 20.4 17.656)" gradientUnits="userSpaceOnUse"><stop offset=".129" class="onedav9lq"/><stop offset="1" class="df0whbb4f"/></radialGradient><radialGradient id="iF4HWEe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.4375 2.75 0 11.994 17.656)" gradientUnits="userSpaceOnUse"><stop offset=".295" class="mzbtew81d"/><stop offset="1" class="fq1j44b5k"/></radialGradient><radialGradient id="i9FZcKb" cx="0" cy="0" r="1" gradientTransform="matrix(.6875 1.78125 -1.94444 .75048 11.588 19.031)" gradientUnits="userSpaceOnUse"><stop class="g680_juih"/><stop offset="1" class="doddtsdma"/></radialGradient><radialGradient id="ifV8rLe" cx="0" cy="0" r="1" gradientTransform="matrix(-2.72442 5.81787 -4.91398 -2.30114 19.9 12.653)" gradientUnits="userSpaceOnUse"><stop class="yctuay0tg"/><stop offset="1" class="ev1lf1bpu"/></radialGradient><radialGradient id="iZoKfZb" cx="0" cy="0" r="1" gradientTransform="matrix(1.91564 -.45407 .5613 2.36803 16.807 20.77)" gradientUnits="userSpaceOnUse"><stop class="mzkqj9diq"/><stop offset="1" class="r797m1bua"/></radialGradient><radialGradient id="iNK7NML" cx="0" cy="0" r="1" gradientTransform="matrix(-3.99991 13.56256 -19.47614 -5.74396 17.275 17.125)" gradientUnits="userSpaceOnUse"><stop offset=".605" class="vmz5qubbv"/><stop offset="1" class="x3yus_bxo"/></radialGradient><radialGradient id="iWVrpIc" cx="0" cy="0" r="1" gradientTransform="rotate(100.183 4.783 20.723)scale(11.3126 2.49146)" gradientUnits="userSpaceOnUse"><stop class="le0y6ubvn"/><stop offset="1" class="hcwj8tbcz"/></radialGradient><radialGradient id="iVP8lXb" cx="0" cy="0" r="1" gradientTransform="rotate(62.199 -1.628 12.88)scale(1.94304 1.49899)" gradientUnits="userSpaceOnUse"><stop class="eacoktb6y"/><stop offset="1" class="hx3m61btj"/></radialGradient><radialGradient id="iWwMjae" cx="0" cy="0" r="1" gradientTransform="matrix(3.3125 -3.125 2.10639 2.23277 6.806 10.875)" gradientUnits="userSpaceOnUse"><stop offset=".204" class="pjc2mbc0w"/><stop offset="1" class="ew2lz0bbx"/></radialGradient><radialGradient id="iJ9sMoe" cx="0" cy="0" r="1" gradientTransform="matrix(-.84932 -3.81088 1.17448 -.26175 17.462 22.139)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="x_sue_b_g"/><stop offset="1" class="gl9okfban"/></radialGradient><radialGradient id="iI1EGFe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.45312 0 0 -.40625 17.016 22.533)" gradientUnits="userSpaceOnUse"><stop class="t5djkhb4t"/><stop offset="1" class="qm132ccsa"/></radialGradient><radialGradient id="iAWmSle" cx="0" cy="0" r="1" gradientTransform="rotate(143.931 4.89 13.482)scale(3.13156 3.97775)" gradientUnits="userSpaceOnUse"><stop offset=".851" class="i669rlbzr"/><stop offset=".949" class="yt9sv1b9n"/></radialGradient><radialGradient id="iRsUyNu" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.51264 -2.40602 0 11.938 18.38)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="i4BeKMb" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 14.95 3.78)scale(.92124 1.10737)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iBJZF7h" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.51263 -2.406 0 19.968 18.434)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="if7rqoc" cx="0" cy="0" r="1" gradientTransform="matrix(-.43239 -.5572 .76712 -.5953 19.543 18.591)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><filter id="ikMO96c" width="22.676" height="13.787" x="4.837" y="4.595" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75" dy="-.75"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.45098 0 0 0 0 0.486275 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19559"/></filter><filter id="i5DIjqd" width="6.15" height="6" x="4.308" y="16.475" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.337255 0 0 0 0 0.266667 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19559"/></filter><filter id="imS4zYG" width="4.479" height="4.479" x="5.068" y="17.235" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19559" stdDeviation=".125"/></filter><filter id="iSq1lFb" width="6" height="6.25" x="22.008" y="16.125" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.184314 0 0 0 0 0.0901961 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19559"/></filter><filter id="iw6bwAb" width="4.979" height="4.979" x="22.543" y="16.985" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19559" stdDeviation=".25"/></filter><filter id="i7i59hb" width="20" height="21.833" x="6.5" y="9.012" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.333333 0 0 0 0 0.262745 0 0 0 0 0.247059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19559"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".5"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.176471 0 0 0 0 0.101961 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_19559" result="effect2_innerShadow_3987_19559"/></filter><filter id="iM1oh8d" width="4.5" height="6" x="13.438" y="18.323" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19559" stdDeviation=".25"/></filter><filter id="iOCtycb" width="4" height="5.5" x="14" y="18.343" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19559" stdDeviation=".125"/></filter><filter id="iaiPMMd" width="4.35" height="1.811" x="18.9" y="14.282" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.345098 0 0 0 0 0.305882 0 0 0 0 0.368627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19559"/></filter><filter id="iVDZNib" width="4.35" height="1.811" x="8.9" y="14.282" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.345098 0 0 0 0 0.305882 0 0 0 0 0.368627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19559"/></filter><filter id="iDVwvsb" width="5.419" height="2.462" x="8.604" y="16.998" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.133333 0 0 0 0 0.0784314 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19559"/></filter><filter id="iPk7c1b" width="5.419" height="2.462" x="18.104" y="16.998" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.133333 0 0 0 0 0.0784314 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19559"/></filter><filter id="iyMobsX" width="1.493" height="1.594" x="12.162" y="17.754" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19559" stdDeviation=".1"/></filter><filter id="ipz7Lcc" width="1.529" height="1.141" x="10.668" y="17.631" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19559" stdDeviation=".05"/></filter><filter id="iXrPMIe" width="1.294" height="1.125" x="18.686" y="17.701" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19559" stdDeviation=".05"/></filter><filter id="iAk10Ie" width="1.316" height="1.357" x="20.338" y="17.927" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19559" stdDeviation=".1"/></filter><filter id="iAhNxCc" width="3.891" height="1.401" x="9.088" y="14.505" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19559" stdDeviation=".125"/></filter><filter id="ivrIeto" width="3.891" height="1.401" x="19.219" y="14.456" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19559" stdDeviation=".125"/></filter><filter id="iPMmKZb" width="17.593" height="9.464" x="9.558" y="4.536" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19559" stdDeviation=".625"/></filter><filter id="iWEKkEb" width="6.633" height="6.958" x="5.287" y="6.155" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19559" stdDeviation=".625"/></filter><linearGradient id="i1XtxAb" x1="4.308" x2="9.825" y1="19.638" y2="19.638" gradientUnits="userSpaceOnUse"><stop class="z_wfxjr5n"/><stop offset="1" class="qenr6bbwz"/></linearGradient><linearGradient id="iOinzFe" x1="14.25" x2="16" y1="22.275" y2="22.275" gradientUnits="userSpaceOnUse"><stop class="o6hm6qxaj"/><stop offset="1" class="mg63gccek"/></linearGradient><linearGradient id="iCoU8xc" x1="16" x2="16" y1="23.764" y2="22.627" gradientUnits="userSpaceOnUse"><stop class="cctx1cb1y"/><stop offset="1" class="xfmbn4_bb"/></linearGradient><linearGradient id="iN6cYDd" x1="16.146" x2="16.146" y1="23.716" y2="23.456" gradientUnits="userSpaceOnUse"><stop class="kos78---c"/><stop offset="1" class="wq1w-qb8s"/></linearGradient><linearGradient id="isW0F5d" x1="14.066" x2="14.877" y1="26.105" y2="24.822" gradientUnits="userSpaceOnUse"><stop class="w1_1yhbve"/><stop offset=".663" class="zbexf6jod"/></linearGradient><linearGradient id="ieNq3od" x1="13.325" x2="12.74" y1="18.48" y2="18.841" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iNKGTMd" x1="21.418" x2="20.834" y1="18.535" y2="18.895" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ipNbFoN" x1="9.74" x2="12.771" y1="15.776" y2="14.88" gradientUnits="userSpaceOnUse"><stop class="wgmwydz1w"/><stop offset="1" class="jxtrqmq9q"/></linearGradient><linearGradient id="iiVwdqe" x1="18.236" x2="22.439" y1="14.716" y2="15.357" gradientUnits="userSpaceOnUse"><stop class="wgmwydz1w"/><stop offset="1" class="jxtrqmq9q"/></linearGradient><linearGradient id="i5wZpJb" x1="22.557" x2="12.479" y1="9.87" y2="5.366" gradientUnits="userSpaceOnUse"><stop class="ft_qk78lm"/><stop offset="1" class="eu_5adeum"/></linearGradient><linearGradient id="icuNDec" x1="10.32" x2="10.044" y1="7.827" y2="10.67" gradientUnits="userSpaceOnUse"><stop class="ft_qk78lm"/><stop offset="1" class="eu_5adeum"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:old-woman-dark" /></template>
<style>
.aef08ybhj {
  fill: var(--svg-color--28262a, #28262A);
  d: path("M18.104 18.6c.494-.87.987-1.592 2.606-1.592c.969-.067 1.652.232 2.26.723c.501.405.42.835.06 1.148l-.793.582c-1.215-.393-2.817-.467-4.133-.86");
}

.akdceqbho {
  cx: 11.432px;
  cy: 18.201px;
  rx: 0.726px;
  ry: 0.368px;
}

.aoi4rrb-h {
  d: path("M19.85 17.897c.118.158-.13.352-.412.562s-.49.36-.609.2c-.119-.158.014-.457.296-.668c.281-.21.606-.253.724-.094");
}

.axrc_wsrb {
  d: path("M26.69 13.358c-.715-4.45-3.06-8.013-10.69-8.013c-7.635 0-10.201 3.568-11.064 8.023c-.377 1.95.345 3.737 1.66 5.014L6.5 14.741c.038-1.77 1.07-2.454 1.51-2.682q.046-.016.096-.038q.051-.023.096-.039a4.3 4.3 0 0 0 2.217-2.301l.153-.362a.492.492 0 0 1 .86-.095a7.2 7.2 0 0 0 5.947 3.12h6.003c.336 0 2.018.163 2.118 2.484l-.1 3.045c1.027-1.223 1.566-2.804 1.29-4.515");
}

.ayiod_bfg {
  stop-color: var(--svg-color--493033, #493033);
}

.bn9_xfr7t {
  d: path("M11.935 17.49a1.664 1.664 0 0 0-1.604 2.103h3.215c.037-.144.06-.288.06-.439a1.675 1.675 0 0 0-1.671-1.664");
}

.btm1a2bhh {
  d: path("M26.69 13.358c-.715-4.45-3.06-8.013-10.69-8.013c-7.635 0-10.201 3.568-11.064 8.023c-.377 1.95.345 3.737 1.66 5.014l-.058-2.576l-.019-.495l-.019-.57c.038-1.77 1.07-2.454 1.51-2.682q.046-.016.096-.038q.051-.023.096-.039a4.3 4.3 0 0 0 2.217-2.301l.153-.362a.492.492 0 0 1 .86-.095a7.2 7.2 0 0 0 5.947 3.12h6.003c.336 0 2.018.163 2.118 2.484l-.1 3.045c1.027-1.223 1.566-2.804 1.29-4.515");
}

.buxgdcbal {
  fill: var(--svg-color--35252b, #35252B);
  d: path("M9.297 19.475a1.99 1.99 0 1 1-3.979 0a1.99 1.99 0 0 1 3.98 0");
}

.bv_oasbmn {
  cx: 11.432px;
  cy: 18.201px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.726px;
  ry: 0.368px;
}

.c77l-utpr {
  fill: var(--svg-color--362322, #362322);
  fill-rule: evenodd;
  d: path("M13.48 20.461a.45.45 0 0 0-.636.031c-.196.217-.842.684-1.672.657a.45.45 0 1 0-.03.9c1.159.037 2.043-.593 2.369-.952a.45.45 0 0 0-.031-.636");
}

.c9h0wxb7i {
  d: path("M10.67 7.405c-.116 1.076-.929 3.994-4.133 4.458c.03-1.176 1.045-4.156 4.133-4.458");
}

.cctx1cb1y {
  stop-color: var(--svg-color--3a1f30, #3A1F30);
}

.ckmwos09j {
  fill: var(--svg-color--28262a, #28262A);
  d: path("M13.823 18.6c-.495-.87-.987-1.592-2.607-1.592c-.968-.067-1.652.232-2.26.723c-.5.405-.42.835-.06 1.148l.793.582c1.215-.393 2.817-.467 4.134-.86");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.crde6o_5i {
  stop-color: var(--svg-color--402824, #402824);
  stop-opacity: 0;
}

.dbmm3wbls {
  stop-color: var(--svg-color--6f524d, #6F524D);
  stop-opacity: 0;
}

.df0whbb4f {
  stop-color: var(--svg-color--412529, #412529);
  stop-opacity: 0;
}

.doddtsdma {
  stop-color: var(--svg-color--412b29, #412B29);
  stop-opacity: 0;
}

.dz24a9bdx {
  fill: var(--svg-color--7e7c7f, #7E7C7F);
  d: path("m9.666 16.017l-.009.005a.5.5 0 0 1-.514-.858h.001l.002-.002l.006-.003l.017-.01a3 3 0 0 1 .277-.143c.184-.088.445-.2.765-.302c.633-.202 1.52-.372 2.476-.203a.5.5 0 0 1-.174.984c-.743-.13-1.457-.001-1.998.172a5 5 0 0 0-.85.36");
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.eacoktb6y {
  stop-color: var(--svg-color--16090c, #16090C);
}

.edx7bubmp {
  stop-color: var(--svg-color--776169, #776169);
}

.ei5heabxh {
  d: path("M27.022 19.475a1.99 1.99 0 1 1-3.979 0a1.99 1.99 0 0 1 3.98 0");
}

.estahhywh {
  d: path("M21 7.438a5 5 0 1 1-10 0a5 5 0 0 1 10 0");
}

.eu_5adeum {
  stop-color: var(--svg-color--bbb9bc, #BBB9BC);
  stop-opacity: 0;
}

.ev1lf1bpu {
  stop-color: var(--svg-color--594a49, #594A49);
  stop-opacity: 0;
}

.ew2lz0bbx {
  stop-color: var(--svg-color--231318, #231318);
  stop-opacity: 0;
}

.fq1j44b5k {
  stop-color: var(--svg-color--371e28, #371E28);
  stop-opacity: 0;
}

.ft_qk78lm {
  stop-color: var(--svg-color--bbb9bc, #BBB9BC);
}

.ft5dv1b6b {
  fill: none;
}

.g680_juih {
  stop-color: var(--svg-color--412b29, #412B29);
}

.gl9okfban {
  stop-color: var(--svg-color--634d4b, #634D4B);
  stop-opacity: 0;
}

.gqg8xzo3g {
  fill: var(--svg-color--a5a5a5, #A5A5A5);
  d: path("M26.69 13.358c-.715-4.45-3.06-8.013-10.69-8.013c-7.635 0-10.201 3.568-11.064 8.023c-.377 1.95.345 3.737 1.66 5.014L6.5 14.741c.038-1.77 1.07-2.454 1.51-2.682q.046-.016.096-.038q.051-.023.096-.039a4.3 4.3 0 0 0 2.217-2.301l.153-.362a.492.492 0 0 1 .86-.095a7.2 7.2 0 0 0 5.947 3.12h6.003c.336 0 2.018.163 2.118 2.484l-.1 3.045c1.027-1.223 1.566-2.804 1.29-4.515");
}

.h-s1ac-oh {
  d: path("M28.008 19.375a3 3 0 1 1-6 0a3 3 0 0 1 6 0");
}

.hcwj8tbcz {
  stop-color: var(--svg-color--5e4a47, #5E4A47);
  stop-opacity: 0;
}

.hrsq7eket {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M9.463 15.531c.343-.245 1.553-.775 3.14-.625");
}

.hx3m61btj {
  stop-color: var(--svg-color--16090c, #16090C);
  stop-opacity: 0;
}

.i669rlbzr {
  stop-color: var(--svg-color--2d151c, #2D151C);
  stop-opacity: 0;
}

.igxv_jb3j {
  stop-color: var(--svg-color--82747b, #82747B);
  stop-opacity: 0;
}

.j1t9k-s0o {
  d: path("m15.287 19.12l-.99 3.169a1.005 1.005 0 0 0 .97 1.304h1.466c.688 0 1.173-.662.97-1.304l-.99-3.17c-.213-.702-1.203-.702-1.426 0");
}

.jpk3lwb9k {
  stop-color: var(--svg-color--c3c3c3, #C3C3C3);
}

.jwo0h5dbt {
  stop-color: var(--svg-color--82747b, #82747B);
}

.jxtrqmq9q {
  stop-color: var(--svg-color--a3a2a4, #A3A2A4);
}

.k-jgyeioh {
  fill: var(--svg-color--452c2a, #452C2A);
  fill-rule: evenodd;
  d: path("M18.602 20.461a.45.45 0 0 1 .636.031c.196.217.841.684 1.672.657a.45.45 0 1 1 .03.9c-1.16.037-2.043-.593-2.37-.952a.45.45 0 0 1 .032-.636");
}

.kos78---c {
  stop-color: var(--svg-color--311620, #311620);
}

.ktbp48b3z {
  fill: var(--svg-color--331b25, #331B25);
  d: path("m15.25 19.35l-1.266 3.17a1.005 1.005 0 0 0 .97 1.303h1.467c.688 0 1.173-.662.97-1.304l-.99-3.17c-.213-.701-.929-.701-1.151 0");
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.le0y6ubvn {
  stop-color: var(--svg-color--5e4a47, #5E4A47);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lxwev9kth {
  stop-color: var(--svg-color--6f524d, #6F524D);
}

.m2s_72ssr {
  stop-color: var(--svg-color--776169, #776169);
  stop-opacity: 0;
}

.m5u6hrbbe {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M19.85 17.897c.118.158-.13.352-.412.562s-.49.36-.609.2c-.119-.158.014-.457.296-.668c.281-.21.606-.253.724-.094");
}

.m8t636bcz {
  fill: var(--svg-color--4a302d, #4A302D);
  d: path("m15.287 19.12l-.99 3.169a1.005 1.005 0 0 0 .97 1.304h1.466c.688 0 1.173-.662.97-1.304l-.99-3.17c-.213-.702-1.203-.702-1.426 0");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mg63gccek {
  stop-color: var(--svg-color--3d2928, #3D2928);
  stop-opacity: 0;
}

.mo-xo_0ef {
  d: path("M21.454 18.99a1.57 1.57 0 0 0-.431-.863l-.485.532l.219.425z");
}

.mqfwqob3e {
  fill: var(--svg-color--2a0219, #2A0219);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M13.44 24.332a.335.335 0 0 0-.4.069a.305.305 0 0 0-.033.393A3.58 3.58 0 0 0 16 26.393a3.58 3.58 0 0 0 2.994-1.6a.31.31 0 0 0-.034-.396a.34.34 0 0 0-.4-.066a5.5 5.5 0 0 1-2.56.607a5.54 5.54 0 0 1-2.56-.607Z");
}

.mzbtew81d {
  stop-color: var(--svg-color--371e28, #371E28);
}

.mzkqj9diq {
  stop-color: var(--svg-color--5b4341, #5B4341);
}

.mzsejxbhe {
  stop-color: var(--svg-color--868381, #868381);
}

.nmap8bczm {
  fill: var(--svg-color--4c3637, #4C3637);
  d: path("M27.022 19.475a1.99 1.99 0 1 1-3.979 0a1.99 1.99 0 0 1 3.98 0");
}

.o6hm6qxaj {
  stop-color: var(--svg-color--3d2928, #3D2928);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.onedav9lq {
  stop-color: var(--svg-color--412529, #412529);
}

.pj2ff5nxp {
  stop-color: var(--svg-color--2d181a, #2D181A);
  stop-opacity: 0;
}

.pjc2mbc0w {
  stop-color: var(--svg-color--231318, #231318);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.qenr6bbwz {
  stop-color: var(--svg-color--2a1c1f, #2A1C1F);
}

.qm132ccsa {
  stop-color: var(--svg-color--655251, #655251);
  stop-opacity: 0;
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r797m1bua {
  stop-color: var(--svg-color--5b4341, #5B4341);
  stop-opacity: 0;
}

.r7is_wb0l {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M22.734 15.482c-.344-.245-1.553-.775-3.14-.625");
}

.rg7dtccaw {
  fill: var(--svg-color--000, #000);
  d: path("M19.019 19.21c0-.53.423-.954.953-.954s.953.424.953.953a.94.94 0 0 1-.106.439h-1.687a.86.86 0 0 1-.113-.439");
}

.rmmi4abgs {
  stop-color: var(--svg-color--371d1f, #371D1F);
  stop-opacity: 0;
}

.rrkbucuoy {
  d: path("M17.634 11.542c-4.272 0-6.27-3.127-6.826-4.55c0-.512 2.554-1.417 6.826-1.162c6.23.373 8.111 4.613 8.266 6.92c-.371-1.078-1.393-1.13-1.857-1.208z");
}

.s9u3_wbrp {
  stop-color: var(--svg-color--402824, #402824);
}

.sdufqstmc {
  stop-color: var(--svg-color--2d181a, #2D181A);
}

.spxz5vbis {
  d: path("M6.5 14.74c.038-1.768 1.07-2.453 1.51-2.681a1 1 0 0 0 .096-.039q.051-.022.096-.038a4.3 4.3 0 0 0 2.217-2.301l.153-.362a.492.492 0 0 1 .86-.095a7.2 7.2 0 0 0 5.947 3.12h6.003c.336 0 2.018.163 2.118 2.484l-.222 6.783c-.23 5.225-4.31 8.734-9.29 8.734c-4.981 0-9.061-3.509-9.291-8.734z");
}

.t-t5e7bov {
  d: path("M9.297 19.475a1.99 1.99 0 1 1-3.979 0a1.99 1.99 0 0 1 3.98 0");
}

.t18jwhbnk {
  stop-color: var(--svg-color--402a2a, #402A2A);
}

.t5djkhb4t {
  stop-color: var(--svg-color--655251, #655251);
}

.ts8y9ypsy {
  stop-color: var(--svg-color--563a37, #563A37);
}

.unb3robxh {
  fill: var(--svg-color--000, #000);
  d: path("M12.888 19.154a.95.95 0 0 0-.953-.953a.95.95 0 0 0-.953.953c0 .159.037.31.106.439h1.686a.94.94 0 0 0 .114-.439");
}

.v8b4zib9a {
  d: path("M19.972 17.545a1.664 1.664 0 0 1 1.603 2.103h-3.214a1.7 1.7 0 0 1-.06-.439a1.67 1.67 0 0 1 1.67-1.664");
}

.vmz5qubbv {
  stop-color: var(--svg-color--41283f, #41283F);
  stop-opacity: 0;
}

.vtynmbbzd {
  d: path("M10.308 19.475a3 3 0 1 1-6 0a3 3 0 0 1 6 0");
}

.vzcmxob8j {
  d: path("M13.455 18.959c0-.538-.438-.896-.556-1.005l-.537.52l.33.674z");
}

.w1_1yhbve {
  stop-color: var(--svg-color--564848, #564848);
}

.wb78_hxsc {
  stop-color: var(--svg-color--6a5956, #6A5956);
}

.wgmwydz1w {
  stop-color: var(--svg-color--a3a2a4, #A3A2A4);
  stop-opacity: 0;
}

.wq1w-qb8s {
  stop-color: var(--svg-color--311620, #311620);
  stop-opacity: 0;
}

.x_sue_b_g {
  stop-color: var(--svg-color--634d4b, #634D4B);
}

.x3yus_bxo {
  stop-color: var(--svg-color--41283f, #41283F);
}

.xfmbn4_bb {
  stop-color: var(--svg-color--3a1f30, #3A1F30);
  stop-opacity: 0;
}

.xuyenabum {
  stop-color: var(--svg-color--371d1f, #371D1F);
}

.xzhu5kb8a {
  fill: var(--svg-color--fff, #fff);
  d: path("M20.358 17.038c1.217 0 2.246.84 2.526 1.974a.51.51 0 0 1-.5.636h-4.16a.43.43 0 0 1-.423-.507a2.606 2.606 0 0 1 2.557-2.103");
}

.yctuay0tg {
  stop-color: var(--svg-color--594a49, #594A49);
}

.yjdpsuykb {
  fill: var(--svg-color--7e7c7f, #7E7C7F);
  d: path("m22.857 15.164l-.002-.002l-.005-.003l-.018-.01l-.06-.034a6 6 0 0 0-.98-.411c-.635-.202-1.521-.372-2.478-.203a.5.5 0 0 0 .174.984c.743-.13 1.457-.001 1.999.172a5 5 0 0 1 .849.36l.008.005a.5.5 0 0 0 .514-.858");
}

.yt9sv1b9n {
  stop-color: var(--svg-color--2d151c, #2D151C);
}

.z_wfxjr5n {
  stop-color: var(--svg-color--392526, #392526);
}

.z5hcufbzz {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.549 16.984c-1.218 0-2.246.84-2.526 1.974a.51.51 0 0 0 .499.635h4.16a.43.43 0 0 0 .423-.507a2.61 2.61 0 0 0-2.556-2.102");
}

.zbexf6jod {
  stop-color: var(--svg-color--564848, #564848);
  stop-opacity: 0;
}

</style>
