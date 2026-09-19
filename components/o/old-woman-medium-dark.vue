<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#igoxEXd)" class="p1t68ub2u"/><g filter="url(#iXnyANd)"><path class="rlzr21ojg"/><path fill="url(#ijYIljj)" class="r47xdwvdk"/></g><path fill="url(#i12Ftrt)" class="cx6b__bkx"/><path fill="url(#iaTm0De)" class="cx6b__bkx"/><g filter="url(#iYvulFe)"><path fill="url(#ibhlHAd)" class="u4el_pbub"/></g><g filter="url(#iwbq0vm)"><path class="kaop5nutr"/><path fill="url(#iMynSFe)" class="jit21bcof"/></g><g filter="url(#iB7WAuc)"><path fill="url(#igaGxge)" class="ecsl7pwdh"/><path fill="url(#iqsjemd)" class="ecsl7pwdh"/></g><g filter="url(#iw9q6Mb)"><path class="pik9hex1y"/><path fill="url(#iztitHd)" class="svvkrhblm"/></g><g filter="url(#i4yib9c)"><path fill="url(#imNybPb)" class="oo-z-0bdz"/><path fill="url(#iWD5Vfb)" class="oo-z-0bdz"/><path fill="url(#iMPHodb)" class="oo-z-0bdz"/><path fill="url(#i84txnc)" class="oo-z-0bdz"/><path fill="url(#iYtNREb)" class="oo-z-0bdz"/><path fill="url(#iyS3mfB)" class="oo-z-0bdz"/></g><path fill="url(#iJP05Gt)" class="oo-z-0bdz"/><path fill="url(#ilPh1vu)" class="oo-z-0bdz"/><path fill="url(#ihpaZPe)" class="oo-z-0bdz"/><path fill="url(#iBR78gL)" class="oo-z-0bdz"/><g filter="url(#ibvsioe)"><path class="ttquqrbuk"/></g><g filter="url(#i56gDWd)"><path class="x0eehlyos"/><path fill="url(#iQOjV0F)" class="wi4cdsb7r"/><path fill="url(#iduLU7d)" class="wi4cdsb7r"/><path fill="url(#ihKyVOc)" class="wi4cdsb7r"/><path fill="url(#ivpOqUx)" class="wi4cdsb7r"/></g><path fill="url(#iPgEafc)" class="wi4cdsb7r"/><path fill="url(#i902Unb)" class="wi4cdsb7r"/><path stroke="url(#iUaxwFd)" class="bnvl4qe9m"/><g filter="url(#ii76nld)"><path class="w3pv9o4ng"/></g><g filter="url(#izCNTJt)"><path class="f-wrv_bsh"/></g><g filter="url(#iMMVFzd)"><path class="ooybeuwfn"/></g><g filter="url(#ikipiGv)"><path class="blnb1hgzw"/></g><path class="kccskachc"/><path fill="url(#igpBNpd)" class="uksdmvb8v"/><path class="n5_jbqrja"/><g filter="url(#ixGk09d)"><path fill="url(#i1aWe6d)" class="foqmszbeh"/></g><g filter="url(#iUismmH)"><ellipse transform="rotate(-27.914 11.432 18.326)" class="iy8_2ibno"/><ellipse fill="url(#i4wIkIb)" transform="rotate(-27.914 11.432 18.326)" class="oxr24vbrk"/></g><path class="xdlhcqbvr"/><path fill="url(#iNCzPee)" class="qvobw0bkr"/><path class="c5i3qvmcm"/><g filter="url(#iK7bYFe)"><path class="mzpt3xpio"/><path fill="url(#i1VldGi)" class="ume_64sfv"/></g><g filter="url(#iEG9z8d)"><path fill="url(#ip9plhc)" class="fymtymbzc"/></g><g filter="url(#iExJo3i)"><path stroke="url(#iicmMkj)" class="s00jozx4n"/></g><g filter="url(#imrEPnd)"><path stroke="url(#iIrZtde)" class="rs3aw2b6w"/></g><g filter="url(#icGYw3d)"><path fill="url(#i25OLJc)" class="t-y2r113w"/></g><g filter="url(#ibWMGYb)"><path fill="url(#ibXBoTc)" class="or71rpdmj"/></g><path clip-rule="evenodd" class="w5ddscbkp"/><path clip-rule="evenodd" class="xhp1wsbhx"/><defs><radialGradient id="igoxEXd" cx="0" cy="0" r="1" gradientTransform="rotate(159.45 8.82 4.453)scale(8.16232 6.90297)" gradientUnits="userSpaceOnUse"><stop offset=".096" class="jpk3lwb9k"/><stop offset=".879" class="mzsejxbhe"/></radialGradient><radialGradient id="ijYIljj" cx="0" cy="0" r="1" gradientTransform="matrix(7.70897 -9.00929 11.38856 9.74484 6.164 15.847)" gradientUnits="userSpaceOnUse"><stop class="jwo0h5dbt"/><stop offset="1" class="igxv_jb3j"/></radialGradient><radialGradient id="i12Ftrt" cx="0" cy="0" r="1" gradientTransform="matrix(-2.73002 0 0 -3.69719 8.345 14.77)" gradientUnits="userSpaceOnUse"><stop offset=".223" class="lxwev9kth"/><stop offset="1" class="dbmm3wbls"/></radialGradient><radialGradient id="iaTm0De" cx="0" cy="0" r="1" gradientTransform="rotate(-109.573 9.23 .966)scale(1.93641 .96821)" gradientUnits="userSpaceOnUse"><stop offset=".167" class="edx7bubmp"/><stop offset="1" class="m2s_72ssr"/></radialGradient><radialGradient id="iMynSFe" cx="0" cy="0" r="1" gradientTransform="rotate(180 3.714 9.8)scale(1.95601)" gradientUnits="userSpaceOnUse"><stop offset=".722" class="o3wo53bzp"/><stop offset="1" class="eo_7g0bzd"/></radialGradient><radialGradient id="igaGxge" cx="0" cy="0" r="1" gradientTransform="rotate(-24.444 58.671 -44.176)scale(5.09754 6.22385)" gradientUnits="userSpaceOnUse"><stop offset=".64" class="olqyf7fmb"/><stop offset=".944" class="hpeo8yzih"/></radialGradient><radialGradient id="iqsjemd" cx="0" cy="0" r="1" gradientTransform="matrix(2.45313 1.375 -.38873 .69354 25.46 16.366)" gradientUnits="userSpaceOnUse"><stop class="mt9k2qzvi"/><stop offset="1" class="fx1tjiblm"/></radialGradient><radialGradient id="iztitHd" cx="0" cy="0" r="1" gradientTransform="matrix(2.79684 -.20804 .16263 2.18635 24.225 19.807)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="l__dw9bpv"/><stop offset="1" class="wrh2b4bbx"/></radialGradient><radialGradient id="imNybPb" cx="0" cy="0" r="1" gradientTransform="matrix(-9.83758 10.56244 -10.33625 -9.62691 22.462 17.688)" gradientUnits="userSpaceOnUse"><stop offset=".239" class="df3eq3qef"/><stop offset=".877" class="oabln9bvq"/></radialGradient><radialGradient id="iWD5Vfb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.1875 3.14012 0 20.4 17.781)" gradientUnits="userSpaceOnUse"><stop offset=".129" class="uvgug6b6x"/><stop offset="1" class="g-mco4ren"/></radialGradient><radialGradient id="iMPHodb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.4375 2.75 0 11.994 17.781)" gradientUnits="userSpaceOnUse"><stop offset=".167" class="ohcigrjhb"/><stop offset="1" class="sqr2ux5ew"/></radialGradient><radialGradient id="i84txnc" cx="0" cy="0" r="1" gradientTransform="matrix(.6875 1.78125 -1.94444 .75048 11.588 19.156)" gradientUnits="userSpaceOnUse"><stop class="n0nwenbpt"/><stop offset="1" class="uin3tjbzk"/></radialGradient><radialGradient id="iYtNREb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.72442 5.81787 -4.91398 -2.30114 19.9 12.778)" gradientUnits="userSpaceOnUse"><stop class="hw61ir83d"/><stop offset="1" class="zwcsjbryl"/></radialGradient><radialGradient id="iyS3mfB" cx="0" cy="0" r="1" gradientTransform="rotate(-13.335 97.775 -61.44)scale(1.96872 2.43365)" gradientUnits="userSpaceOnUse"><stop class="geq1pmdmd"/><stop offset="1" class="qxczoybxi"/></radialGradient><radialGradient id="iJP05Gt" cx="0" cy="0" r="1" gradientTransform="matrix(-3.99991 13.56256 -19.47614 -5.74396 17.275 17.25)" gradientUnits="userSpaceOnUse"><stop offset=".605" class="x889gio9s"/><stop offset="1" class="og08facuy"/></radialGradient><radialGradient id="ilPh1vu" cx="0" cy="0" r="1" gradientTransform="rotate(100.183 4.731 20.785)scale(11.3126 2.49146)" gradientUnits="userSpaceOnUse"><stop class="ebxt27bwe"/><stop offset="1" class="oohree1oj"/></radialGradient><radialGradient id="ihpaZPe" cx="0" cy="0" r="1" gradientTransform="matrix(1.06875 2.59374 -3.06547 1.26312 10.525 8.438)" gradientUnits="userSpaceOnUse"><stop class="ml5ahdbjb"/><stop offset="1" class="ws4-zpq3r"/></radialGradient><radialGradient id="iBR78gL" cx="0" cy="0" r="1" gradientTransform="matrix(4.19373 -4 2.69618 2.82676 6.806 11)" gradientUnits="userSpaceOnUse"><stop offset=".236" class="abco83byt"/><stop offset="1" class="y7x71_qft"/></radialGradient><radialGradient id="iQOjV0F" cx="0" cy="0" r="1" gradientTransform="matrix(-.84932 -3.81088 1.17448 -.26175 17.462 22.264)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="bof3uzbpf"/><stop offset="1" class="jaf6nfbfs"/></radialGradient><radialGradient id="ivpOqUx" cx="0" cy="0" r="1" gradientTransform="matrix(-1.45312 0 0 -.40625 17.016 22.658)" gradientUnits="userSpaceOnUse"><stop class="bof3uzbpf"/><stop offset="1" class="jaf6nfbfs"/></radialGradient><radialGradient id="i902Unb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.5565 1.75513 -2.1094 -3.07252 16.703 21.549)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="wln98ypvp"/><stop offset="1" class="p13423bzd"/></radialGradient><radialGradient id="igpBNpd" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.51264 -2.40602 0 11.938 18.505)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="i4wIkIb" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 15.012 3.843)scale(.92124 1.10737)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iNCzPee" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.51263 -2.406 0 19.968 18.56)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="i1VldGi" cx="0" cy="0" r="1" gradientTransform="matrix(-.43239 -.5572 .76712 -.5953 19.543 18.716)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><filter id="iXnyANd" width="22.676" height="13.787" x="4.837" y="4.72" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75" dy="-.75"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.45098 0 0 0 0 0.486275 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19565"/></filter><filter id="iYvulFe" width="6.15" height="6" x="4.308" y="16.6" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.509804 0 0 0 0 0.376471 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19565"/></filter><filter id="iwbq0vm" width="4.479" height="4.479" x="5.068" y="17.36" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19565" stdDeviation=".125"/></filter><filter id="iB7WAuc" width="6" height="6.25" x="22.008" y="16.25" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.431373 0 0 0 0 0.243137 0 0 0 0 0.282353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19565"/></filter><filter id="iw9q6Mb" width="4.979" height="4.979" x="22.543" y="17.11" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19565" stdDeviation=".25"/></filter><filter id="i4yib9c" width="20" height="21.833" x="6.5" y="9.137" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.509804 0 0 0 0 0.372549 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19565"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".5"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.407843 0 0 0 0 0.235294 0 0 0 0 0.235294 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_19565" result="effect2_innerShadow_3987_19565"/></filter><filter id="ibvsioe" width="4.5" height="6" x="13.438" y="18.448" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19565" stdDeviation=".25"/></filter><filter id="i56gDWd" width="4" height="5.5" x="14" y="18.468" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19565" stdDeviation=".125"/></filter><filter id="ii76nld" width="4.35" height="1.811" x="18.9" y="14.407" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.345098 0 0 0 0 0.305882 0 0 0 0 0.368627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19565"/></filter><filter id="izCNTJt" width="4.35" height="1.811" x="8.9" y="14.407" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.345098 0 0 0 0 0.305882 0 0 0 0 0.368627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19565"/></filter><filter id="iMMVFzd" width="5.419" height="2.462" x="8.604" y="17.123" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.133333 0 0 0 0 0.0784314 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19565"/></filter><filter id="ikipiGv" width="5.419" height="2.462" x="18.104" y="17.123" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.133333 0 0 0 0 0.0784314 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19565"/></filter><filter id="ixGk09d" width="1.493" height="1.594" x="12.162" y="17.879" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19565" stdDeviation=".1"/></filter><filter id="iUismmH" width="1.529" height="1.141" x="10.668" y="17.756" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19565" stdDeviation=".05"/></filter><filter id="iK7bYFe" width="1.294" height="1.125" x="18.686" y="17.826" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19565" stdDeviation=".05"/></filter><filter id="iEG9z8d" width="1.316" height="1.357" x="20.338" y="18.052" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19565" stdDeviation=".1"/></filter><filter id="iExJo3i" width="3.891" height="1.401" x="9.088" y="14.63" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19565" stdDeviation=".125"/></filter><filter id="imrEPnd" width="3.891" height="1.401" x="19.219" y="14.581" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19565" stdDeviation=".125"/></filter><filter id="icGYw3d" width="17.593" height="9.464" x="9.558" y="4.661" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19565" stdDeviation=".625"/></filter><filter id="ibWMGYb" width="6.633" height="6.958" x="5.287" y="6.28" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19565" stdDeviation=".625"/></filter><linearGradient id="ibhlHAd" x1="4.403" x2="6.716" y1="19.763" y2="19.763" gradientUnits="userSpaceOnUse"><stop class="b9k-3ybvb"/><stop offset="1" class="vbw-bobru"/></linearGradient><linearGradient id="iduLU7d" x1="14.25" x2="16" y1="22.4" y2="22.4" gradientUnits="userSpaceOnUse"><stop class="rby1z7ber"/><stop offset="1" class="dl0nwov2w"/></linearGradient><linearGradient id="ihKyVOc" x1="16" x2="16" y1="23.889" y2="22.752" gradientUnits="userSpaceOnUse"><stop class="cyl8wapbv"/><stop offset="1" class="jplc2lvem"/></linearGradient><linearGradient id="iPgEafc" x1="16.146" x2="16.146" y1="23.841" y2="23.581" gradientUnits="userSpaceOnUse"><stop class="p13423bzd"/><stop offset="1" class="wln98ypvp"/></linearGradient><linearGradient id="iUaxwFd" x1="14.066" x2="14.877" y1="26.23" y2="24.947" gradientUnits="userSpaceOnUse"><stop class="lwz87437z"/><stop offset=".663" class="c7jfumw-i"/></linearGradient><linearGradient id="i1aWe6d" x1="13.325" x2="12.74" y1="18.605" y2="18.966" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ip9plhc" x1="21.418" x2="20.834" y1="18.66" y2="19.02" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iicmMkj" x1="9.74" x2="12.771" y1="15.901" y2="15.005" gradientUnits="userSpaceOnUse"><stop class="wgmwydz1w"/><stop offset="1" class="jxtrqmq9q"/></linearGradient><linearGradient id="iIrZtde" x1="18.236" x2="22.439" y1="14.841" y2="15.482" gradientUnits="userSpaceOnUse"><stop class="wgmwydz1w"/><stop offset="1" class="jxtrqmq9q"/></linearGradient><linearGradient id="i25OLJc" x1="22.557" x2="12.479" y1="9.995" y2="5.491" gradientUnits="userSpaceOnUse"><stop class="ft_qk78lm"/><stop offset="1" class="eu_5adeum"/></linearGradient><linearGradient id="ibXBoTc" x1="10.32" x2="10.044" y1="7.952" y2="10.795" gradientUnits="userSpaceOnUse"><stop class="ft_qk78lm"/><stop offset="1" class="eu_5adeum"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:old-woman-medium-dark" /></template>
<style>
.abco83byt {
  stop-color: var(--svg-color--522f2f, #522F2F);
}

.b9k-3ybvb {
  stop-color: var(--svg-color--6a4745, #6A4745);
}

.blnb1hgzw {
  fill: var(--svg-color--36292e, #36292E);
  d: path("M18.104 18.726c.494-.87.987-1.593 2.606-1.593c.969-.067 1.652.232 2.26.723c.501.405.42.835.06 1.148l-.793.582c-1.215-.393-2.817-.467-4.133-.86");
}

.bnvl4qe9m {
  fill: var(--svg-color--88014f, #88014F);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M13.44 24.457a.335.335 0 0 0-.4.069a.305.305 0 0 0-.033.393A3.58 3.58 0 0 0 16 26.518a3.58 3.58 0 0 0 2.994-1.6a.31.31 0 0 0-.034-.396a.34.34 0 0 0-.4-.066a5.5 5.5 0 0 1-2.56.607a5.54 5.54 0 0 1-2.56-.607Z");
}

.bof3uzbpf {
  stop-color: var(--svg-color--a07a6f, #A07A6F);
}

.c5i3qvmcm {
  fill: var(--svg-color--000, #000);
  d: path("M19.019 19.334c0-.53.423-.953.953-.953s.953.424.953.953a.94.94 0 0 1-.106.439h-1.687a.86.86 0 0 1-.113-.439");
}

.c7jfumw-i {
  stop-color: var(--svg-color--865e63, #865E63);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cx6b__bkx {
  d: path("M26.69 13.483C25.976 9.033 23.63 5.47 16 5.47c-7.635 0-10.201 3.568-11.064 8.023c-.377 1.95.345 3.737 1.66 5.014l-.058-2.576l-.019-.495l-.019-.57c.038-1.77 1.07-2.454 1.51-2.682q.046-.016.096-.038q.051-.023.096-.039a4.3 4.3 0 0 0 2.217-2.301l.153-.362a.492.492 0 0 1 .86-.095a7.2 7.2 0 0 0 5.947 3.12h6.003c.336 0 2.018.163 2.118 2.484l-.1 3.045c1.027-1.223 1.566-2.804 1.29-4.515");
}

.cyl8wapbv {
  stop-color: var(--svg-color--7c455c, #7C455C);
}

.dbmm3wbls {
  stop-color: var(--svg-color--6f524d, #6F524D);
  stop-opacity: 0;
}

.df3eq3qef {
  stop-color: var(--svg-color--9b7063, #9B7063);
}

.dl0nwov2w {
  stop-color: var(--svg-color--744c45, #744C45);
  stop-opacity: 0;
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.ebxt27bwe {
  stop-color: var(--svg-color--976c5e, #976C5E);
}

.ecsl7pwdh {
  d: path("M28.008 19.5a3 3 0 1 1-6 0a3 3 0 0 1 6 0");
}

.edx7bubmp {
  stop-color: var(--svg-color--776169, #776169);
}

.eo_7g0bzd {
  stop-color: var(--svg-color--5a3638, #5A3638);
}

.eu_5adeum {
  stop-color: var(--svg-color--bbb9bc, #BBB9BC);
  stop-opacity: 0;
}

.f-wrv_bsh {
  fill: var(--svg-color--7e7c7f, #7E7C7F);
  d: path("m9.666 16.142l-.009.005a.5.5 0 0 1-.514-.858h.001l.002-.002l.006-.003l.017-.01a3 3 0 0 1 .277-.143c.184-.088.445-.2.765-.302c.633-.202 1.52-.372 2.476-.203a.5.5 0 0 1-.174.984c-.743-.13-1.457-.001-1.998.172a5 5 0 0 0-.85.36");
}

.foqmszbeh {
  d: path("M13.455 19.084c0-.538-.438-.896-.556-1.005l-.537.52l.33.674z");
}

.ft_qk78lm {
  stop-color: var(--svg-color--bbb9bc, #BBB9BC);
}

.ft5dv1b6b {
  fill: none;
}

.fx1tjiblm {
  stop-color: var(--svg-color--755041, #755041);
  stop-opacity: 0;
}

.fymtymbzc {
  d: path("M21.454 19.115a1.57 1.57 0 0 0-.431-.863l-.485.532l.219.425z");
}

.g-mco4ren {
  stop-color: var(--svg-color--865353, #865353);
  stop-opacity: 0;
}

.geq1pmdmd {
  stop-color: var(--svg-color--9c7265, #9C7265);
}

.hpeo8yzih {
  stop-color: var(--svg-color--9d7e72, #9D7E72);
}

.hw61ir83d {
  stop-color: var(--svg-color--8b6b65, #8B6B65);
}

.igxv_jb3j {
  stop-color: var(--svg-color--82747b, #82747B);
  stop-opacity: 0;
}

.iy8_2ibno {
  cx: 11.432px;
  cy: 18.326px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.726px;
  ry: 0.368px;
}

.jaf6nfbfs {
  stop-color: var(--svg-color--a07a6f, #A07A6F);
  stop-opacity: 0;
}

.jit21bcof {
  d: path("M9.297 19.6a1.99 1.99 0 1 1-3.979 0a1.99 1.99 0 0 1 3.98 0");
}

.jpk3lwb9k {
  stop-color: var(--svg-color--c3c3c3, #C3C3C3);
}

.jplc2lvem {
  stop-color: var(--svg-color--7c455c, #7C455C);
  stop-opacity: 0;
}

.jwo0h5dbt {
  stop-color: var(--svg-color--82747b, #82747B);
}

.jxtrqmq9q {
  stop-color: var(--svg-color--a3a2a4, #A3A2A4);
}

.kaop5nutr {
  fill: var(--svg-color--5f3c45, #5F3C45);
  d: path("M9.297 19.6a1.99 1.99 0 1 1-3.979 0a1.99 1.99 0 0 1 3.98 0");
}

.kccskachc {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.549 17.109c-1.218 0-2.246.84-2.526 1.974a.51.51 0 0 0 .499.635h4.16a.43.43 0 0 0 .423-.507a2.61 2.61 0 0 0-2.556-2.102");
}

.l__dw9bpv {
  stop-color: var(--svg-color--7d4d48, #7D4D48);
  stop-opacity: 0;
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lwz87437z {
  stop-color: var(--svg-color--865e63, #865E63);
}

.lxwev9kth {
  stop-color: var(--svg-color--6f524d, #6F524D);
}

.m2s_72ssr {
  stop-color: var(--svg-color--776169, #776169);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.ml5ahdbjb {
  stop-color: var(--svg-color--412021, #412021);
}

.mt9k2qzvi {
  stop-color: var(--svg-color--755041, #755041);
}

.mzpt3xpio {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M19.85 18.022c.118.158-.13.352-.412.562s-.49.36-.609.2c-.119-.158.014-.457.296-.668c.281-.21.606-.253.724-.094");
}

.mzsejxbhe {
  stop-color: var(--svg-color--868381, #868381);
}

.n0nwenbpt {
  stop-color: var(--svg-color--7a544c, #7A544C);
}

.n5_jbqrja {
  fill: var(--svg-color--000, #000);
  d: path("M12.888 19.28a.95.95 0 0 0-.953-.954a.95.95 0 0 0-.953.953c0 .159.037.31.106.439h1.686a.94.94 0 0 0 .114-.439");
}

.o3wo53bzp {
  stop-color: var(--svg-color--5a3638, #5A3638);
  stop-opacity: 0;
}

.oabln9bvq {
  stop-color: var(--svg-color--74494e, #74494E);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.og08facuy {
  stop-color: var(--svg-color--7a3f6a, #7A3F6A);
}

.ohcigrjhb {
  stop-color: var(--svg-color--6f3f4c, #6F3F4C);
}

.olqyf7fmb {
  stop-color: var(--svg-color--875e5e, #875E5E);
}

.oo-z-0bdz {
  d: path("M6.5 14.866c.038-1.77 1.07-2.454 1.51-2.682a1 1 0 0 0 .096-.039q.051-.022.096-.038a4.3 4.3 0 0 0 2.217-2.301l.153-.362a.492.492 0 0 1 .86-.095a7.2 7.2 0 0 0 5.947 3.12h6.003c.336 0 2.018.163 2.118 2.484l-.222 6.783c-.23 5.225-4.31 8.734-9.29 8.734c-4.981 0-9.061-3.509-9.291-8.734z");
}

.oohree1oj {
  stop-color: var(--svg-color--976c5e, #976C5E);
  stop-opacity: 0;
}

.ooybeuwfn {
  fill: var(--svg-color--36292e, #36292E);
  d: path("M13.823 18.726c-.495-.87-.987-1.593-2.607-1.593c-.968-.067-1.652.232-2.26.723c-.5.405-.42.835-.06 1.148l.793.582c1.215-.393 2.817-.467 4.134-.86");
}

.or71rpdmj {
  d: path("M10.67 7.53c-.116 1.076-.929 3.994-4.133 4.458c.03-1.176 1.045-4.156 4.133-4.458");
}

.oxr24vbrk {
  cx: 11.432px;
  cy: 18.326px;
  rx: 0.726px;
  ry: 0.368px;
}

.p13423bzd {
  stop-color: var(--svg-color--693b40, #693B40);
}

.p1t68ub2u {
  d: path("M21 7.563a5 5 0 1 1-10 0a5 5 0 0 1 10 0");
}

.pik9hex1y {
  fill: var(--svg-color--845f59, #845F59);
  d: path("M27.022 19.6a1.99 1.99 0 1 1-3.979 0a1.99 1.99 0 0 1 3.98 0");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.qvobw0bkr {
  d: path("M19.972 17.67a1.664 1.664 0 0 1 1.603 2.103h-3.214a1.7 1.7 0 0 1-.06-.439a1.67 1.67 0 0 1 1.67-1.664");
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qxczoybxi {
  stop-color: var(--svg-color--9c7265, #9C7265);
  stop-opacity: 0;
}

.r47xdwvdk {
  d: path("M26.69 13.483C25.976 9.033 23.63 5.47 16 5.47c-7.635 0-10.201 3.568-11.064 8.023c-.377 1.95.345 3.737 1.66 5.014L6.5 14.866c.038-1.77 1.07-2.454 1.51-2.682q.046-.016.096-.038q.051-.023.096-.039a4.3 4.3 0 0 0 2.217-2.301l.153-.362a.492.492 0 0 1 .86-.095a7.2 7.2 0 0 0 5.947 3.12h6.003c.336 0 2.018.163 2.118 2.484l-.1 3.045c1.027-1.223 1.566-2.804 1.29-4.515");
}

.rby1z7ber {
  stop-color: var(--svg-color--744c45, #744C45);
}

.rlzr21ojg {
  fill: var(--svg-color--a5a5a5, #A5A5A5);
  d: path("M26.69 13.483C25.976 9.033 23.63 5.47 16 5.47c-7.635 0-10.201 3.568-11.064 8.023c-.377 1.95.345 3.737 1.66 5.014L6.5 14.866c.038-1.77 1.07-2.454 1.51-2.682q.046-.016.096-.038q.051-.023.096-.039a4.3 4.3 0 0 0 2.217-2.301l.153-.362a.492.492 0 0 1 .86-.095a7.2 7.2 0 0 0 5.947 3.12h6.003c.336 0 2.018.163 2.118 2.484l-.1 3.045c1.027-1.223 1.566-2.804 1.29-4.515");
}

.rs3aw2b6w {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M22.734 15.607c-.344-.245-1.553-.775-3.14-.625");
}

.s00jozx4n {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M9.463 15.656c.343-.245 1.553-.775 3.14-.625");
}

.sqr2ux5ew {
  stop-color: var(--svg-color--6f3f4c, #6F3F4C);
  stop-opacity: 0;
}

.svvkrhblm {
  d: path("M27.022 19.6a1.99 1.99 0 1 1-3.979 0a1.99 1.99 0 0 1 3.98 0");
}

.t-y2r113w {
  d: path("M17.634 11.667c-4.272 0-6.27-3.127-6.826-4.55c0-.512 2.554-1.417 6.826-1.162c6.23.373 8.111 4.613 8.266 6.92c-.371-1.078-1.393-1.13-1.857-1.208z");
}

.ttquqrbuk {
  fill: var(--svg-color--70404a, #70404A);
  d: path("m15.25 19.475l-1.266 3.17a1.005 1.005 0 0 0 .97 1.303h1.467c.688 0 1.173-.662.97-1.304l-.99-3.17c-.213-.701-.929-.701-1.151 0");
}

.u4el_pbub {
  d: path("M10.308 19.6a3 3 0 1 1-6 0a3 3 0 0 1 6 0");
}

.uin3tjbzk {
  stop-color: var(--svg-color--7a544c, #7A544C);
  stop-opacity: 0;
}

.uksdmvb8v {
  d: path("M11.935 17.615a1.664 1.664 0 0 0-1.604 2.103h3.215c.037-.144.06-.288.06-.439a1.675 1.675 0 0 0-1.671-1.664");
}

.ume_64sfv {
  d: path("M19.85 18.022c.118.158-.13.352-.412.562s-.49.36-.609.2c-.119-.158.014-.457.296-.668c.281-.21.606-.253.724-.094");
}

.uvgug6b6x {
  stop-color: var(--svg-color--865353, #865353);
}

.vbw-bobru {
  stop-color: var(--svg-color--533335, #533335);
}

.w3pv9o4ng {
  fill: var(--svg-color--7e7c7f, #7E7C7F);
  d: path("m22.857 15.289l-.002-.002l-.005-.003l-.018-.01l-.06-.034a6 6 0 0 0-.98-.411c-.635-.202-1.521-.372-2.478-.203a.5.5 0 0 0 .174.984c.743-.13 1.457-.001 1.999.172a5 5 0 0 1 .849.36l.008.005a.5.5 0 0 0 .514-.858");
}

.w5ddscbkp {
  fill: var(--svg-color--875a53, #875A53);
  fill-rule: evenodd;
  d: path("M18.602 20.586a.45.45 0 0 1 .636.031c.196.217.841.684 1.672.657a.45.45 0 1 1 .03.9c-1.16.037-2.043-.593-2.37-.952a.45.45 0 0 1 .032-.636");
}

.wgmwydz1w {
  stop-color: var(--svg-color--a3a2a4, #A3A2A4);
  stop-opacity: 0;
}

.wi4cdsb7r {
  d: path("m15.287 19.244l-.99 3.17a1.005 1.005 0 0 0 .97 1.304h1.466c.688 0 1.173-.662.97-1.304l-.99-3.17c-.213-.702-1.203-.702-1.426 0");
}

.wln98ypvp {
  stop-color: var(--svg-color--693b40, #693B40);
  stop-opacity: 0;
}

.wrh2b4bbx {
  stop-color: var(--svg-color--7d4d48, #7D4D48);
}

.ws4-zpq3r {
  stop-color: var(--svg-color--412021, #412021);
  stop-opacity: 0;
}

.x0eehlyos {
  fill: var(--svg-color--8a6058, #8A6058);
  d: path("m15.287 19.244l-.99 3.17a1.005 1.005 0 0 0 .97 1.304h1.466c.688 0 1.173-.662.97-1.304l-.99-3.17c-.213-.702-1.203-.702-1.426 0");
}

.x889gio9s {
  stop-color: var(--svg-color--7a3f6a, #7A3F6A);
  stop-opacity: 0;
}

.xdlhcqbvr {
  fill: var(--svg-color--fff, #fff);
  d: path("M20.358 17.163c1.217 0 2.246.84 2.526 1.974a.51.51 0 0 1-.5.636h-4.16a.43.43 0 0 1-.423-.507a2.606 2.606 0 0 1 2.557-2.103");
}

.xhp1wsbhx {
  fill: var(--svg-color--6e4844, #6E4844);
  fill-rule: evenodd;
  d: path("M13.48 20.586a.45.45 0 0 0-.636.031c-.196.217-.842.684-1.672.657a.45.45 0 1 0-.03.9c1.159.037 2.043-.593 2.369-.952a.45.45 0 0 0-.031-.636");
}

.y7x71_qft {
  stop-color: var(--svg-color--522f2f, #522F2F);
  stop-opacity: 0;
}

.zwcsjbryl {
  stop-color: var(--svg-color--8b6b65, #8B6B65);
  stop-opacity: 0;
}

</style>
