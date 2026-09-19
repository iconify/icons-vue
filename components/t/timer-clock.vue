<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iZoiOEe)"><path fill="url(#iv4p3Xd)" class="f8b0anb_k"/></g><g clip-rule="evenodd" filter="url(#iy3PCGe)" class="d2kvgvbvc"><path fill="url(#iwKhySc)" class="i5g0n7pow"/><path fill="url(#iGTTIeW)" class="i5g0n7pow"/></g><path fill="url(#ibqCpic)" class="lppeuey0l"/><path fill="url(#imJX7jd)" class="lppeuey0l"/><path fill="url(#iCeCVWc)" class="lppeuey0l"/><g filter="url(#iPEe0ET)"><path stroke="url(#iodqDfd)" class="bir6rubnd"/></g><g filter="url(#ialr04j)"><path class="fpar0kbvq"/></g><path fill="url(#iQTPfMc)" class="tpyd82blf"/><path fill="url(#iIpQyPc)" class="tpyd82blf"/><g filter="url(#ieaQ3Pb)"><path fill="url(#iNYvMlc)" class="jyiy93bzs"/></g><g filter="url(#ibB4brb)"><path fill="url(#iZdU1oy)" class="t-k5x9qmx"/></g><g filter="url(#iAndjzj)"><path fill="url(#itBqKbd)" class="iz2-89bii"/></g><g filter="url(#ifdSiZb)"><path fill="url(#iBB1wXb)" class="ax_o6karz"/></g><g filter="url(#imq6Nce)"><path fill="url(#i5Kutuc)" class="ddckbpc1b"/></g><g filter="url(#iWaK1gW)"><path fill="url(#i4V5Zjd)" class="y04zu5nrg"/></g><g filter="url(#iOrd6od)"><path fill="url(#ikKsQqb)" class="re--o5fgx"/></g><g filter="url(#iJfl0Nb)"><path fill="url(#iOyfz4c)" class="yd5ovcbbr"/></g><g filter="url(#idQse0F)"><path fill="url(#izSz51c)" class="kox67zzfl"/></g><g filter="url(#igxBszC)"><path fill="url(#iG4PgYb)" class="n5n_7jbbh"/></g><g filter="url(#iVLK3Xd)"><path fill="url(#iWBcjFb)" class="o3u4_xb9e"/></g><g filter="url(#i3I5YLd)"><path fill="url(#icssNpc)" class="vaem41ecl"/></g><g filter="url(#i6uku1b)"><path fill="url(#ioizdmd)" class="strjigmwy"/></g><g filter="url(#ihpwmGR)"><path fill="url(#iAosQqG)" class="k8030zdul"/></g><g filter="url(#iaHtpQb)"><path fill="url(#i5BjRwc)" class="brr8eo8iz"/></g><g filter="url(#idVA7Xc)"><path fill="url(#iDjcMbL)" class="mz842s87i"/></g><defs><linearGradient id="iv4p3Xd" x1="16.002" x2="16.002" y1="30.005" y2="2" gradientUnits="userSpaceOnUse"><stop class="rg3hy_rca"/><stop offset="1" class="px57o6k3r"/></linearGradient><linearGradient id="iwKhySc" x1="9.73" x2="22.678" y1="5.767" y2="25.099" gradientUnits="userSpaceOnUse"><stop class="oza9g4bva"/><stop offset="1" class="ld4u54b0x"/></linearGradient><linearGradient id="iCeCVWc" x1="12.588" x2="16" y1="25.819" y2="14.993" gradientUnits="userSpaceOnUse"><stop class="tl9r2ib4x"/><stop offset="1" class="q3_azm-2m"/></linearGradient><linearGradient id="iodqDfd" x1="25.502" x2="8.21" y1="6.719" y2="20.034" gradientUnits="userSpaceOnUse"><stop offset=".082" class="yspvuzbsw"/><stop offset=".355" class="d5br6mfkp"/><stop offset=".692" class="d5br6mfkp"/><stop offset="1" class="yspvuzbsw"/></linearGradient><linearGradient id="iQTPfMc" x1="13.563" x2="16" y1="13.809" y2="13.809" gradientUnits="userSpaceOnUse"><stop class="yja8-33uy"/><stop offset="1" class="ly0l786gp"/></linearGradient><linearGradient id="iIpQyPc" x1="16.28" x2="16.28" y1="19.45" y2="17.766" gradientUnits="userSpaceOnUse"><stop class="hcx26wxil"/><stop offset="1" class="r7nikhbdy"/></linearGradient><linearGradient id="iNYvMlc" x1="15.313" x2="17" y1="8.651" y2="7.526" gradientUnits="userSpaceOnUse"><stop class="g-2zwbbkx"/><stop offset="1" class="ko35a032o"/></linearGradient><linearGradient id="iZdU1oy" x1="15.196" x2="16.799" y1="21.568" y2="22.826" gradientUnits="userSpaceOnUse"><stop class="bzoqs-b7o"/><stop offset="1" class="r14f_1b3z"/></linearGradient><linearGradient id="itBqKbd" x1="20.146" x2="21.75" y1="9.628" y2="10.886" gradientUnits="userSpaceOnUse"><stop class="bzoqs-b7o"/><stop offset="1" class="r14f_1b3z"/></linearGradient><linearGradient id="iBB1wXb" x1="10.246" x2="11.85" y1="19.518" y2="20.776" gradientUnits="userSpaceOnUse"><stop class="bzoqs-b7o"/><stop offset="1" class="r14f_1b3z"/></linearGradient><linearGradient id="i5Kutuc" x1="22.084" x2="24.078" y1="14.964" y2="15.388" gradientUnits="userSpaceOnUse"><stop class="bzoqs-b7o"/><stop offset="1" class="r14f_1b3z"/></linearGradient><linearGradient id="i4V5Zjd" x1="8.085" x2="10.079" y1="14.964" y2="15.388" gradientUnits="userSpaceOnUse"><stop class="bzoqs-b7o"/><stop offset="1" class="r14f_1b3z"/></linearGradient><linearGradient id="ikKsQqb" x1="20.276" x2="21.985" y1="20.569" y2="19.459" gradientUnits="userSpaceOnUse"><stop class="bzoqs-b7o"/><stop offset="1" class="r14f_1b3z"/></linearGradient><linearGradient id="iOyfz4c" x1="10.386" x2="12.095" y1="10.673" y2="9.563" gradientUnits="userSpaceOnUse"><stop class="bzoqs-b7o"/><stop offset="1" class="r14f_1b3z"/></linearGradient><linearGradient id="izSz51c" x1="10.544" x2="11.919" y1="10.638" y2="9.722" gradientUnits="userSpaceOnUse"><stop class="xxhj4bcib"/><stop offset="1" class="k_snybcwj"/></linearGradient><linearGradient id="iG4PgYb" x1="8.489" x2="9.864" y1="15.582" y2="14.666" gradientUnits="userSpaceOnUse"><stop class="xxhj4bcib"/><stop offset="1" class="k_snybcwj"/></linearGradient><linearGradient id="iWBcjFb" x1="10.544" x2="11.919" y1="20.532" y2="19.616" gradientUnits="userSpaceOnUse"><stop class="xxhj4bcib"/><stop offset="1" class="k_snybcwj"/></linearGradient><linearGradient id="icssNpc" x1="15.494" x2="16.869" y1="22.582" y2="21.666" gradientUnits="userSpaceOnUse"><stop class="xxhj4bcib"/><stop offset="1" class="k_snybcwj"/></linearGradient><linearGradient id="ioizdmd" x1="20.434" x2="21.808" y1="20.541" y2="19.624" gradientUnits="userSpaceOnUse"><stop class="xxhj4bcib"/><stop offset="1" class="k_snybcwj"/></linearGradient><linearGradient id="iAosQqG" x1="22.489" x2="23.863" y1="15.582" y2="14.666" gradientUnits="userSpaceOnUse"><stop class="xxhj4bcib"/><stop offset="1" class="k_snybcwj"/></linearGradient><linearGradient id="i5BjRwc" x1="20.445" x2="21.819" y1="10.642" y2="9.726" gradientUnits="userSpaceOnUse"><stop class="xxhj4bcib"/><stop offset="1" class="k_snybcwj"/></linearGradient><linearGradient id="iDjcMbL" x1="15.494" x2="16.869" y1="8.582" y2="7.666" gradientUnits="userSpaceOnUse"><stop class="kz0w2ubmc"/><stop offset="1" class="rr8jg7s1l"/></linearGradient><filter id="iZoiOEe" width="27.2" height="29.2" x="2.4" y="1.4" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".6" dy="-.6"/><feGaussianBlur stdDeviation=".6"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.211765 0 0 0 0 0.478431 0 0 0 0 0.654902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_13450"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.6" dy=".6"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.490196 0 0 0 0 0.968627 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_13450" result="effect2_innerShadow_18_13450"/></filter><filter id="iy3PCGe" width="23.5" height="23.5" x="3.85" y="3.645" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy=".4"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.180392 0 0 0 0 0.392157 0 0 0 0 0.635294 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_13450"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_13450" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.25 0"/><feBlend in2="shape" result="effect2_innerShadow_18_13450"/></filter><filter id="iPEe0ET" width="21.004" height="21.004" x="5.838" y="4.176" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_13450" stdDeviation=".2"/></filter><filter id="ialr04j" width="3.2" height="9.2" x="14" y="10.795" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.501961 0 0 0 0 0.439216 0 0 0 0 0.537255 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_13450"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_13450" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.968627 0 0 0 0 0.941176 0 0 0 0 0.984314 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_18_13450"/></filter><filter id="ieaQ3Pb" width="2.4" height="2.4" x="14.7" y="6.895" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.470588 0 0 0 0 0.392157 0 0 0 0 0.509804 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_13450"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_13450" result="shape"/></filter><filter id="ibB4brb" width="2.4" height="2.4" x="14.7" y="20.895" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.403922 0 0 0 0 0.352941 0 0 0 0 0.427451 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_13450"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_13450" result="shape"/></filter><filter id="iAndjzj" width="2.4" height="2.4" x="19.65" y="8.955" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.4 0 0 0 0 0.509804 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_13450"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_13450" result="shape"/></filter><filter id="ifdSiZb" width="2.4" height="2.4" x="9.75" y="18.845" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.403922 0 0 0 0 0.352941 0 0 0 0 0.427451 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_13450"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_13450" result="shape"/></filter><filter id="imq6Nce" width="2.4" height="2.4" x="21.694" y="13.893" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.470588 0 0 0 0 0.392157 0 0 0 0 0.509804 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_13450"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_13450" result="shape"/></filter><filter id="iWaK1gW" width="2.4" height="2.4" x="7.695" y="13.893" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.403922 0 0 0 0 0.352941 0 0 0 0 0.427451 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_13450"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_13450" result="shape"/></filter><filter id="iOrd6od" width="2.4" height="2.4" x="19.64" y="18.846" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.470588 0 0 0 0 0.392157 0 0 0 0 0.509804 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_13450"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_13450" result="shape"/></filter><filter id="iJfl0Nb" width="2.4" height="2.4" x="9.75" y="8.951" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.470588 0 0 0 0 0.392157 0 0 0 0 0.509804 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_13450"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_13450" result="shape"/></filter><filter id="idQse0F" width="1.841" height="1.841" x="10.13" y="9.13" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_13450" stdDeviation=".05"/></filter><filter id="igxBszC" width="1.841" height="1.841" x="8.075" y="14.074" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_13450" stdDeviation=".05"/></filter><filter id="iVLK3Xd" width="1.841" height="1.841" x="10.13" y="19.024" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_13450" stdDeviation=".05"/></filter><filter id="i3I5YLd" width="1.841" height="1.841" x="15.08" y="21.074" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_13450" stdDeviation=".05"/></filter><filter id="i6uku1b" width="1.841" height="1.841" x="20.019" y="19.033" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_13450" stdDeviation=".05"/></filter><filter id="ihpwmGR" width="1.841" height="1.841" x="22.074" y="14.074" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_13450" stdDeviation=".05"/></filter><filter id="iaHtpQb" width="1.841" height="1.841" x="20.03" y="9.134" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_13450" stdDeviation=".05"/></filter><filter id="idVA7Xc" width="1.841" height="1.841" x="15.08" y="7.074" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_13450" stdDeviation=".05"/></filter><radialGradient id="iGTTIeW" cx="0" cy="0" r="1" gradientTransform="matrix(-14.4852 0 0 -13.0117 19.485 14.995)" gradientUnits="userSpaceOnUse"><stop offset=".91" class="vamu3krpe"/><stop offset="1" class="qgnvec3nv"/></radialGradient><radialGradient id="ibqCpic" cx="0" cy="0" r="1" gradientTransform="matrix(2.42682 13.49838 -18.70008 3.36201 13.573 10.495)" gradientUnits="userSpaceOnUse"><stop class="z_vpn5-se"/><stop offset="1" class="frwc2mbxm"/></radialGradient><radialGradient id="imJX7jd" cx="0" cy="0" r="1" gradientTransform="matrix(9.26156 -6.08047 5.81139 8.8517 14.682 16.114)" gradientUnits="userSpaceOnUse"><stop offset=".893" class="w8ocpkb8x"/><stop offset=".991" class="djutolb9y"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:timer-clock" /></template>
<style>
.ax_o6karz {
  d: path("M11.05 20.945a1 1 0 1 0 0-2a1 1 0 0 0 0 2");
}

.bir6rubnd {
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M16.34 24.656c5.51 0 9.977-4.467 9.977-9.977S21.85 4.7 16.34 4.7s-9.977 4.468-9.977 9.98c0 5.51 4.467 9.977 9.977 9.977Z");
}

.brr8eo8iz {
  d: path("M21.726 10.32a.82.82 0 1 0-1.552-.53a.82.82 0 0 0 1.552.53");
}

.bzoqs-b7o {
  stop-color: var(--svg-color--48424c, #48424C);
}

.d2kvgvbvc {
  fill-rule: evenodd;
}

.d5br6mfkp {
  stop-color: var(--svg-color--969497, #969497);
  stop-opacity: 0;
}

.ddckbpc1b {
  d: path("M23.435 15.892a1 1 0 1 0-.88-1.796a1 1 0 0 0 .88 1.796");
}

.djutolb9y {
  stop-color: var(--svg-color--796583, #796583);
}

.f8b0anb_k {
  d: path("M15.375 2.015C8.382 2.345 3 8.365 3 15.367V26.88C3 28.6 4.4 30 6.121 30H25.88c1.719 0 3.12-1.4 3.12-3.12V14.996c.01-7.381-6.162-13.332-13.625-12.982");
}

.fpar0kbvq {
  fill: var(--svg-color--d7cade, #D7CADE);
  d: path("M16 18.995c-.55 0-1-.45-1-1v-6c0-.55.45-1 1-1s1 .45 1 1v6c0 .56-.45 1-1 1");
}

.frwc2mbxm {
  stop-color: var(--svg-color--a49ba9, #A49BA9);
}

.ft5dv1b6b {
  fill: none;
}

.g-2zwbbkx {
  stop-color: var(--svg-color--b1236a, #B1236A);
}

.hcx26wxil {
  stop-color: var(--svg-color--b49fbf, #B49FBF);
}

.i5g0n7pow {
  d: path("M27 14.995c0 6.075-4.925 11-11 11s-11-4.925-11-11s4.925-11 11-11s11 4.924 11 11m-2 0a9 9 0 1 1-18 0a9 9 0 0 1 18 0");
}

.iz2-89bii {
  d: path("M20.95 11.055a1 1 0 1 0 0-2a1 1 0 0 0 0 2");
}

.jyiy93bzs {
  d: path("M16 8.995a1 1 0 1 0 0-2a1 1 0 0 0 0 2");
}

.k_snybcwj {
  stop-color: var(--svg-color--6d6670, #6D6670);
}

.k8030zdul {
  d: path("M23.77 15.26a.82.82 0 1 0-1.552-.53a.82.82 0 0 0 1.552.53");
}

.ko35a032o {
  stop-color: var(--svg-color--fc6572, #FC6572);
}

.kox67zzfl {
  d: path("M11.826 10.316a.82.82 0 1 0-1.552-.53a.82.82 0 0 0 1.552.53");
}

.kz0w2ubmc {
  stop-color: var(--svg-color--ea3786, #EA3786);
}

.ld4u54b0x {
  stop-color: var(--svg-color--6d6671, #6D6671);
}

.lppeuey0l {
  d: path("M16 23.993a9 9 0 1 0 0-18a9 9 0 0 0 0 18");
}

.ly0l786gp {
  stop-color: var(--svg-color--9c90a3, #9C90A3);
  stop-opacity: 0;
}

.mz842s87i {
  d: path("M16.776 8.26a.82.82 0 1 0-1.552-.53a.82.82 0 0 0 1.552.53");
}

.n5n_7jbbh {
  d: path("M9.77 15.26a.82.82 0 1 0-1.55-.53a.82.82 0 0 0 1.55.53");
}

.o3u4_xb9e {
  d: path("M11.826 20.21a.82.82 0 1 0-1.552-.531a.82.82 0 0 0 1.552.531");
}

.oza9g4bva {
  stop-color: var(--svg-color--6b656f, #6B656F);
}

.px57o6k3r {
  stop-color: var(--svg-color--56bfe3, #56BFE3);
}

.q3_azm-2m {
  stop-color: var(--svg-color--9e96a2, #9E96A2);
  stop-opacity: 0;
}

.qgnvec3nv {
  stop-color: var(--svg-color--4a4b54, #4A4B54);
}

.r14f_1b3z {
  stop-color: var(--svg-color--8b898d, #8B898D);
}

.r7nikhbdy {
  stop-color: var(--svg-color--b49fbf, #B49FBF);
  stop-opacity: 0;
}

.re--o5fgx {
  d: path("M21.886 20.27a1 1 0 1 0-1.892-.647a1 1 0 0 0 1.892.647");
}

.rg3hy_rca {
  stop-color: var(--svg-color--43b0f2, #43B0F2);
}

.rr8jg7s1l {
  stop-color: var(--svg-color--e73d60, #E73D60);
}

.strjigmwy {
  d: path("M21.716 20.219a.82.82 0 1 0-1.552-.531a.82.82 0 0 0 1.552.53");
}

.t-k5x9qmx {
  d: path("M16 22.995a1 1 0 1 0 0-2a1 1 0 0 0 0 2");
}

.tl9r2ib4x {
  stop-color: var(--svg-color--9e96a2, #9E96A2);
}

.tpyd82blf {
  d: path("M16 18.995c-.55 0-1-.45-1-1v-6c0-.55.45-1 1-1s1 .45 1 1v6c0 .56-.45 1-1 1");
}

.vaem41ecl {
  d: path("M16.776 22.26a.82.82 0 1 0-1.552-.53a.82.82 0 0 0 1.552.53");
}

.vamu3krpe {
  stop-color: var(--svg-color--4a4b54, #4A4B54);
  stop-opacity: 0;
}

.w8ocpkb8x {
  stop-color: var(--svg-color--796583, #796583);
  stop-opacity: 0;
}

.xxhj4bcib {
  stop-color: var(--svg-color--6c656f, #6C656F);
}

.y04zu5nrg {
  d: path("M9.435 15.891a1 1 0 1 0-.88-1.796a1 1 0 0 0 .88 1.796");
}

.yd5ovcbbr {
  d: path("M11.996 10.374a1 1 0 1 0-1.892-.647a1 1 0 0 0 1.892.647");
}

.yja8-33uy {
  stop-color: var(--svg-color--9c90a3, #9C90A3);
}

.yspvuzbsw {
  stop-color: var(--svg-color--969497, #969497);
}

.z_vpn5-se {
  stop-color: var(--svg-color--c7bdce, #C7BDCE);
}

</style>
