<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#ifsTPGe)" class="y4ry21bde"/><path fill="url(#icSQTNe)" class="y4ry21bde"/><g filter="url(#i9b3twe)"><path fill="url(#i7yoO4d)" class="lvsegjpwg"/></g><path fill="url(#id7DRKd)" class="ek8raqfgw"/><path fill="url(#iBctjib)" class="ek8raqfgw"/><path fill="url(#iAfnwfc)" class="ek8raqfgw"/><path fill="url(#isN2fSc)" class="cxglzrzzy"/><g filter="url(#iAG372b)"><path stroke="url(#ii5FHCc)" class="f-32n_bpv"/></g><g filter="url(#iHRbLwd)"><path fill="url(#imx7xEd)" class="q8-bdqbzx"/></g><g filter="url(#iASUU1H)"><path fill="url(#iabFNdW)" class="pxritme5m"/><path fill="url(#iszL3Bb)" class="pxritme5m"/></g><path fill="url(#ilvPXHd)" class="e1q3dybxk"/><g filter="url(#iurnThe)"><path fill="url(#iOPLaSd)" class="f1kd3kb2t"/><path fill="url(#i1GsJNg)" class="f1kd3kb2t"/></g><g filter="url(#iaqMzsd)"><path fill="url(#ixxnayc)" class="qc6lc6bbw"/></g><g filter="url(#i4Dufxb)"><path class="bavk0kysg"/><path fill="url(#iY9kW4P)" class="v1ix08pkg"/></g><g filter="url(#iUINXpc)"><path class="msnji0o6l"/><path fill="url(#iEXk4hc)" class="vbck9_szr"/></g><g filter="url(#i9EivHb)"><path class="yxk74abun"/><path fill="url(#iz4PXrS)" class="wz1j5qbkl"/></g><g filter="url(#i62H0Px)"><path class="sv8dwrbhh"/><path fill="url(#is8Isgc)" class="cyfgrwg-g"/></g><g filter="url(#iLdXD7d)"><path class="q7xmerefi"/><path fill="url(#iTS6SVg)" class="c2s-9kb-i"/></g><g filter="url(#iV2embb)"><path class="ovt_3gb5q"/><path fill="url(#iwnho1b)" class="f0jlyxb9g"/></g><path fill="url(#iFrlLDe)" class="bgwggohbg"/><g filter="url(#ieX9MPw)"><path class="cqkglbb4g"/><path fill="url(#ih1aL6q)" class="r43ra_bzf"/></g><g filter="url(#ilU7X9P)"><path fill="url(#iH2u2hd)" class="rwvc4g-ws"/><path fill="url(#ikzn51b)" class="rwvc4g-ws"/><path fill="url(#iqFTUld)" class="rwvc4g-ws"/></g><g filter="url(#iWSpiNc)"><path stroke="url(#iiWbfxb)" class="pxndj4bbi"/></g><defs><linearGradient id="ifsTPGe" x1="13.985" x2="17.286" y1="7.85" y2="7.85" gradientUnits="userSpaceOnUse"><stop class="a5qwn1bnn"/><stop offset="1" class="q7_-rqi2h"/></linearGradient><linearGradient id="icSQTNe" x1="17.87" x2="17.227" y1="5.59" y2="6.973" gradientUnits="userSpaceOnUse"><stop class="sr3y642lz"/><stop offset="1" class="otw4c0btd"/></linearGradient><linearGradient id="i7yoO4d" x1="7.192" x2="10.62" y1="12.352" y2="9.065" gradientUnits="userSpaceOnUse"><stop class="jqmc0bbfw"/><stop offset="1" class="bdjo8s1kb"/></linearGradient><linearGradient id="id7DRKd" x1="25.345" x2="23.314" y1="9.344" y2="11.594" gradientUnits="userSpaceOnUse"><stop class="bwxo5stbh"/><stop offset="1" class="kkgk7zxaq"/></linearGradient><linearGradient id="iBctjib" x1="21.814" x2="22.657" y1="8.719" y2="9.562" gradientUnits="userSpaceOnUse"><stop class="filh8qb5f"/><stop offset="1" class="z7p1jnk9a"/></linearGradient><linearGradient id="iAfnwfc" x1="26.236" x2="25.876" y1="13.234" y2="12.89" gradientUnits="userSpaceOnUse"><stop class="phls8db-s"/><stop offset="1" class="bm1b0lbjr"/></linearGradient><linearGradient id="isN2fSc" x1="15.338" x2="15.338" y1="8" y2="30" gradientUnits="userSpaceOnUse"><stop offset=".374" class="wdh60knlv"/><stop offset="1" class="s2bbkvtfi"/></linearGradient><linearGradient id="ii5FHCc" x1="24.095" x2="10.493" y1="8.719" y2="25.726" gradientUnits="userSpaceOnUse"><stop class="tb9ed99fo"/><stop offset="1" class="inq8oc6zl"/></linearGradient><linearGradient id="imx7xEd" x1="15.421" x2="15.421" y1="9.406" y2="28.594" gradientUnits="userSpaceOnUse"><stop class="gesxvccog"/><stop offset="1" class="ml9skmb3a"/></linearGradient><linearGradient id="iabFNdW" x1="15.975" x2="15.975" y1="2" y2="6" gradientUnits="userSpaceOnUse"><stop class="gb4c4i4hl"/><stop offset="1" class="extrbq2kp"/></linearGradient><linearGradient id="iszL3Bb" x1="19.975" x2="18.649" y1="3.564" y2="3.564" gradientUnits="userSpaceOnUse"><stop class="d_gu2rbfq"/><stop offset="1" class="wnl844m3h"/></linearGradient><linearGradient id="ilvPXHd" x1="8.158" x2="24.985" y1="22.125" y2="14.313" gradientUnits="userSpaceOnUse"><stop class="o86y1gk6o"/><stop offset="1" class="ysh_mjxrm"/></linearGradient><linearGradient id="ixxnayc" x1="18.541" x2="13.699" y1="15.127" y2="19.757" gradientUnits="userSpaceOnUse"><stop class="gs8t8v7vi"/><stop offset="1" class="hrwg9wbph"/></linearGradient><linearGradient id="iz4PXrS" x1="22.485" x2="22.485" y1="17.563" y2="18.594" gradientUnits="userSpaceOnUse"><stop class="em15-gbgt"/><stop offset="1" class="ygua8lb3a"/></linearGradient><linearGradient id="iFrlLDe" x1="21.64" x2="19.518" y1="13.349" y2="15.47" gradientUnits="userSpaceOnUse"><stop class="qzooa0bqp"/><stop offset="1" class="wae-w0imf"/></linearGradient><linearGradient id="iH2u2hd" x1="16.157" x2="21.689" y1="18.781" y2="13.25" gradientUnits="userSpaceOnUse"><stop class="i9_zkoqpn"/><stop offset="1" class="vi81-ttnv"/></linearGradient><linearGradient id="ikzn51b" x1="15.427" x2="16.24" y1="19.651" y2="18.891" gradientUnits="userSpaceOnUse"><stop class="ky9jasbge"/><stop offset="1" class="c72snobbt"/></linearGradient><linearGradient id="iiWbfxb" x1="21.436" x2="15.463" y1="13.89" y2="19.987" gradientUnits="userSpaceOnUse"><stop class="mknijcccz"/><stop offset="1" class="tq3vhxbhd"/></linearGradient><filter id="i9b3twe" width="6.421" height="6.22" x="4.97" y="7.795" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.443137 0 0 0 0 0.403922 0 0 0 0 0.501961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_13360"/></filter><filter id="iAG372b" width="21.719" height="21.719" x="5.298" y="7.969" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_13360" stdDeviation=".25"/></filter><filter id="iHRbLwd" width="20.688" height="20.688" x="5.641" y="8.656" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_13360" stdDeviation=".375"/></filter><filter id="iASUU1H" width="8.5" height="4.5" x="11.975" y="1.5" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.145098 0 0 0 0 0.137255 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_13360"/></filter><filter id="iurnThe" width="18.501" height="18.501" x="6.734" y="9.749" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_13360" stdDeviation=".25"/></filter><filter id="iaqMzsd" width="8.145" height="8.145" x="13.912" y="12.652" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_13360" stdDeviation=".3"/></filter><filter id="i4Dufxb" width="3" height="3.8" x="14.485" y="10.7" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.67451 0 0 0 0 0.592157 0 0 0 0 0.729412 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_13360"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_13360" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.478431 0 0 0 0 0.443137 0 0 0 0 0.52549 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_18_13360"/></filter><filter id="iUINXpc" width="3" height="3.8" x="14.485" y="23.7" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.67451 0 0 0 0 0.592157 0 0 0 0 0.729412 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_13360"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_13360" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.478431 0 0 0 0 0.443137 0 0 0 0 0.52549 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_18_13360"/></filter><filter id="i9EivHb" width="3.8" height="3" x="20.485" y="17.5" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.67451 0 0 0 0 0.592157 0 0 0 0 0.729412 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_13360"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_13360" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.478431 0 0 0 0 0.443137 0 0 0 0 0.52549 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_18_13360"/></filter><filter id="i62H0Px" width="4" height="3" x="7.485" y="17.5" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.67451 0 0 0 0 0.592157 0 0 0 0 0.729412 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_13360"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_13360" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.478431 0 0 0 0 0.443137 0 0 0 0 0.52549 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_18_13360"/></filter><filter id="iLdXD7d" width="3.705" height="3.705" x="18.733" y="21.748" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.67451 0 0 0 0 0.592157 0 0 0 0 0.729412 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_13360"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_13360" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.478431 0 0 0 0 0.443137 0 0 0 0 0.52549 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_18_13360"/></filter><filter id="iV2embb" width="3.705" height="3.512" x="9.533" y="12.75" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.67451 0 0 0 0 0.592157 0 0 0 0 0.729412 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_13360"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_13360" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.478431 0 0 0 0 0.443137 0 0 0 0 0.52549 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_18_13360"/></filter><filter id="ieX9MPw" width="3.705" height="3.505" x="9.533" y="21.938" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.67451 0 0 0 0 0.592157 0 0 0 0 0.729412 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_13360"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_13360" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.478431 0 0 0 0 0.443137 0 0 0 0 0.52549 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_18_13360"/></filter><filter id="ilU7X9P" width="6.945" height="7.395" x="14.982" y="12.857" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.533333 0 0 0 0 0.129412 0 0 0 0 0.192157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_13360"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.717647 0 0 0 0 0.25098 0 0 0 0 0.482353 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_13360" result="effect2_innerShadow_18_13360"/></filter><filter id="iWSpiNc" width="6.607" height="6.591" x="15.199" y="13.166" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_13360" stdDeviation=".3"/></filter><radialGradient id="iOPLaSd" cx="0" cy="0" r="1" gradientTransform="matrix(8.93279 -13.12596 18.31816 12.4663 12.689 25.623)" gradientUnits="userSpaceOnUse"><stop offset=".455" class="v2dg1jb9y"/><stop offset="1" class="x_0gftmvh"/></radialGradient><radialGradient id="i1GsJNg" cx="0" cy="0" r="1" gradientTransform="rotate(-24.51 58.304 -6.246)scale(17.928)" gradientUnits="userSpaceOnUse"><stop offset=".81" class="vajvadc2i"/><stop offset="1" class="jwcs6tqgb"/></radialGradient><radialGradient id="iY9kW4P" cx="0" cy="0" r="1" gradientTransform="matrix(-1.25 -.84374 .99675 -1.4767 17.064 13.594)" gradientUnits="userSpaceOnUse"><stop class="cth-ractz"/><stop offset="1" class="h2nv5lbrv"/></radialGradient><radialGradient id="iEXk4hc" cx="0" cy="0" r="1" gradientTransform="rotate(108.452 -.349 17.979)scale(1.92721 1.24519)" gradientUnits="userSpaceOnUse"><stop class="cth-ractz"/><stop offset="1" class="h2nv5lbrv"/></radialGradient><radialGradient id="is8Isgc" cx="0" cy="0" r="1" gradientTransform="rotate(136.37 1.598 11.227)scale(1.404 .93124)" gradientUnits="userSpaceOnUse"><stop class="cth-ractz"/><stop offset="1" class="h2nv5lbrv"/></radialGradient><radialGradient id="iTS6SVg" cx="0" cy="0" r="1" gradientTransform="matrix(.33376 1.83342 -1.14355 .20817 20.251 22.063)" gradientUnits="userSpaceOnUse"><stop class="cth-ractz"/><stop offset="1" class="h2nv5lbrv"/></radialGradient><radialGradient id="iwnho1b" cx="0" cy="0" r="1" gradientTransform="rotate(178.396 6.145 7.65)scale(1.11669 1.1136)" gradientUnits="userSpaceOnUse"><stop class="uissonb5s"/><stop offset="1" class="qhr5_d-2k"/></radialGradient><radialGradient id="ih1aL6q" cx="0" cy="0" r="1" gradientTransform="rotate(143.224 2.567 13.555)scale(1.68855 1.05319)" gradientUnits="userSpaceOnUse"><stop class="cth-ractz"/><stop offset="1" class="h2nv5lbrv"/></radialGradient><radialGradient id="iqFTUld" cx="0" cy="0" r="1" gradientTransform="rotate(137.862 8.06 11.03)scale(1.00098)" gradientUnits="userSpaceOnUse"><stop class="suny1hbrp"/><stop offset="1" class="lyj96_0lh"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:stopwatch" /></template>
<style>
.a5qwn1bnn {
  stop-color: var(--svg-color--66646d, #66646D);
}

.bavk0kysg {
  fill: var(--svg-color--9b93a5, #9B93A5);
  d: path("M14.985 13v-1c0-.55.45-1 1-1s1 .45 1 1v1c0 .55-.45 1-1 1c-.56 0-1-.45-1-1");
}

.bdjo8s1kb {
  stop-color: var(--svg-color--a19da8, #A19DA8);
}

.bgwggohbg {
  d: path("m19.515 14.05l.71-.71a.996.996 0 1 1 1.41 1.41l-.71.71a.996.996 0 1 1-1.41-1.41");
}

.bm1b0lbjr {
  stop-color: var(--svg-color--918a9d, #918A9D);
  stop-opacity: 0;
}

.bwxo5stbh {
  stop-color: var(--svg-color--b7b5bd, #B7B5BD);
}

.c2s-9kb-i {
  d: path("m20.935 22.54l.71.71a.996.996 0 1 1-1.41 1.41l-.71-.71a.996.996 0 1 1 1.41-1.41");
}

.c72snobbt {
  stop-color: var(--svg-color--9f346b, #9F346B);
  stop-opacity: 0;
}

.cqkglbb4g {
  fill: var(--svg-color--9b93a5, #9B93A5);
  d: path("m10.325 23.24l.71-.71a.996.996 0 1 1 1.41 1.41l-.71.71a.996.996 0 1 1-1.41-1.41");
}

.cth-ractz {
  stop-color: var(--svg-color--aba5b3, #ABA5B3);
}

.cxglzrzzy {
  d: path("M15.985 30c6.075 0 11-4.925 11-11s-4.925-11-11-11s-11 4.925-11 11s4.925 11 11 11");
}

.cyfgrwg-g {
  d: path("M8.985 18h1c.55 0 1 .45 1 1s-.45 1-1 1h-1c-.55 0-1-.45-1-1s.44-1 1-1");
}

.d_gu2rbfq {
  stop-color: var(--svg-color--5c375f, #5C375F);
}

.e1q3dybxk {
  d: path("M15.985 28a9 9 0 1 0 0-18a9 9 0 0 0 0 18");
}

.ek8raqfgw {
  d: path("m21.345 11.19l2.45 2.45c.5.5 1.3.5 1.79 0l1.04-1.04c.5-.5.5-1.3 0-1.79l-2.45-2.45c-.5-.5-1.3-.5-1.79 0l-1.04 1.04c-.5.49-.5 1.3 0 1.79");
}

.em15-gbgt {
  stop-color: var(--svg-color--867f8d, #867F8D);
}

.extrbq2kp {
  stop-color: var(--svg-color--1c1f54, #1C1F54);
}

.f-32n_bpv {
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M16.157 28.938c5.583 0 10.11-4.527 10.11-10.11s-4.527-10.11-10.11-10.11s-10.11 4.527-10.11 10.11s4.527 10.11 10.11 10.11Z");
}

.f0jlyxb9g {
  d: path("m11.735 13.35l.71.71a.996.996 0 1 1-1.41 1.41l-.71-.71a.996.996 0 0 1 0-1.41c.39-.4 1.02-.4 1.41 0");
}

.f1kd3kb2t {
  d: path("M15.985 27.75a8.75 8.75 0 1 0 0-17.5a8.75 8.75 0 0 0 0 17.5");
}

.filh8qb5f {
  stop-color: var(--svg-color--74717d, #74717D);
}

.ft5dv1b6b {
  fill: none;
}

.gb4c4i4hl {
  stop-color: var(--svg-color--4d224f, #4D224F);
}

.gesxvccog {
  stop-color: var(--svg-color--3a1d41, #3A1D41);
}

.gs8t8v7vi {
  stop-color: var(--svg-color--b7a1ac, #B7A1AC);
}

.h2nv5lbrv {
  stop-color: var(--svg-color--aba5b3, #ABA5B3);
  stop-opacity: 0;
}

.hrwg9wbph {
  stop-color: var(--svg-color--bb9cc1, #BB9CC1);
}

.i9_zkoqpn {
  stop-color: var(--svg-color--c9287b, #C9287B);
}

.inq8oc6zl {
  stop-color: var(--svg-color--3f3e6a, #3F3E6A);
}

.jqmc0bbfw {
  stop-color: var(--svg-color--948c9d, #948C9D);
}

.jwcs6tqgb {
  stop-color: var(--svg-color--ad98b7, #AD98B7);
}

.kkgk7zxaq {
  stop-color: var(--svg-color--9993a0, #9993A0);
}

.ky9jasbge {
  stop-color: var(--svg-color--9f346b, #9F346B);
}

.lvsegjpwg {
  d: path("m10.615 11.19l-2.45 2.45c-.5.5-1.3.5-1.79 0l-1.03-1.03c-.5-.5-.5-1.3 0-1.79l2.45-2.45c.5-.5 1.3-.5 1.79 0l1.04 1.04c.49.48.49 1.29-.01 1.78");
}

.lyj96_0lh {
  stop-color: var(--svg-color--df5460, #DF5460);
  stop-opacity: 0;
}

.mknijcccz {
  stop-color: var(--svg-color--e14d5f, #E14D5F);
}

.ml9skmb3a {
  stop-color: var(--svg-color--2e2a44, #2E2A44);
}

.msnji0o6l {
  fill: var(--svg-color--9b93a5, #9B93A5);
  d: path("M14.985 26v-1c0-.55.45-1 1-1s1 .45 1 1v1c0 .55-.45 1-1 1c-.56 0-1-.45-1-1");
}

.o86y1gk6o {
  stop-color: var(--svg-color--938d9c, #938D9C);
}

.otw4c0btd {
  stop-color: var(--svg-color--686475, #686475);
  stop-opacity: 0;
}

.ovt_3gb5q {
  fill: var(--svg-color--9b93a5, #9B93A5);
  d: path("m11.735 13.35l.71.71a.996.996 0 1 1-1.41 1.41l-.71-.71a.996.996 0 0 1 0-1.41c.39-.4 1.02-.4 1.41 0");
}

.phls8db-s {
  stop-color: var(--svg-color--918a9d, #918A9D);
}

.pxndj4bbi {
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("m21.03 13.943l-5.055 5.036");
}

.pxritme5m {
  d: path("M18.715 6h-5.47c-.7 0-1.27-.57-1.27-1.27V3.27c.01-.7.57-1.27 1.27-1.27h5.46c.7 0 1.27.57 1.27 1.27v1.46c.01.7-.56 1.27-1.26 1.27");
}

.q7_-rqi2h {
  stop-color: var(--svg-color--a49fac, #A49FAC);
}

.q7xmerefi {
  fill: var(--svg-color--9b93a5, #9B93A5);
  d: path("m20.935 22.54l.71.71a.996.996 0 1 1-1.41 1.41l-.71-.71a.996.996 0 1 1 1.41-1.41");
}

.q8-bdqbzx {
  d: path("M15.985 28.594a9.594 9.594 0 1 0 0-19.188a9.594 9.594 0 0 0 0 19.188");
}

.qc6lc6bbw {
  d: path("M14.805 19.905a.996.996 0 0 1 0-1.41l4.95-4.95a.996.996 0 1 1 1.41 1.41l-4.95 4.95a.996.996 0 0 1-1.41 0");
}

.qhr5_d-2k {
  stop-color: var(--svg-color--a69faf, #A69FAF);
  stop-opacity: 0;
}

.qzooa0bqp {
  stop-color: var(--svg-color--9b9b9b, #9B9B9B);
}

.r43ra_bzf {
  d: path("m10.325 23.24l.71-.71a.996.996 0 1 1 1.41 1.41l-.71.71a.996.996 0 1 1-1.41-1.41");
}

.rwvc4g-ws {
  d: path("M15.275 19.71a.996.996 0 0 1 0-1.41l4.95-4.95a.996.996 0 1 1 1.41 1.41l-4.95 4.95a.996.996 0 0 1-1.41 0");
}

.s2bbkvtfi {
  stop-color: var(--svg-color--272e63, #272E63);
}

.sr3y642lz {
  stop-color: var(--svg-color--686475, #686475);
}

.suny1hbrp {
  stop-color: var(--svg-color--df5460, #DF5460);
}

.sv8dwrbhh {
  fill: var(--svg-color--9b93a5, #9B93A5);
  d: path("M8.985 18h1c.55 0 1 .45 1 1s-.45 1-1 1h-1c-.55 0-1-.45-1-1s.44-1 1-1");
}

.tb9ed99fo {
  stop-color: var(--svg-color--5c3760, #5C3760);
}

.tq3vhxbhd {
  stop-color: var(--svg-color--e14d5f, #E14D5F);
  stop-opacity: 0;
}

.uissonb5s {
  stop-color: var(--svg-color--a69faf, #A69FAF);
}

.v1ix08pkg {
  d: path("M14.985 13v-1c0-.55.45-1 1-1s1 .45 1 1v1c0 .55-.45 1-1 1c-.56 0-1-.45-1-1");
}

.v2dg1jb9y {
  stop-color: var(--svg-color--e4ddeb, #E4DDEB);
}

.vajvadc2i {
  stop-color: var(--svg-color--ad98b7, #AD98B7);
  stop-opacity: 0;
}

.vbck9_szr {
  d: path("M14.985 26v-1c0-.55.45-1 1-1s1 .45 1 1v1c0 .55-.45 1-1 1c-.56 0-1-.45-1-1");
}

.vi81-ttnv {
  stop-color: var(--svg-color--d82044, #D82044);
}

.wae-w0imf {
  stop-color: var(--svg-color--d3d3d3, #D3D3D3);
}

.wdh60knlv {
  stop-color: var(--svg-color--4c2250, #4C2250);
}

.wnl844m3h {
  stop-color: var(--svg-color--5c375f, #5C375F);
  stop-opacity: 0;
}

.wz1j5qbkl {
  d: path("M21.985 18h1c.55 0 1 .45 1 1s-.45 1-1 1h-1c-.55 0-1-.45-1-1s.44-1 1-1");
}

.x_0gftmvh {
  stop-color: var(--svg-color--d2c2db, #D2C2DB);
}

.y4ry21bde {
  d: path("M17.985 6h-4v3h4z");
}

.ygua8lb3a {
  stop-color: var(--svg-color--867f8d, #867F8D);
  stop-opacity: 0;
}

.ysh_mjxrm {
  stop-color: var(--svg-color--897c91, #897C91);
}

.yxk74abun {
  fill: var(--svg-color--9b93a5, #9B93A5);
  d: path("M21.985 18h1c.55 0 1 .45 1 1s-.45 1-1 1h-1c-.55 0-1-.45-1-1s.44-1 1-1");
}

.z7p1jnk9a {
  stop-color: var(--svg-color--74717d, #74717D);
  stop-opacity: 0;
}

</style>
