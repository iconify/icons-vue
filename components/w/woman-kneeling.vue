<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#izG0ind)"><path class="t-gr46jfz"/></g><g filter="url(#iPusLIc)"><path stroke="url(#iC5KYHe)" class="aqha79btm"/></g><path fill="url(#ifGBdCd)" class="gxq3zhbma"/><g filter="url(#ioKhQXi)"><path class="kuoei6j8q"/></g><path fill="url(#i4qdsKb)" class="timippiwa"/><path fill="url(#i74bWAY)" class="timippiwa"/><path fill="url(#ianbGjc)" class="yf5p-quaq"/><g filter="url(#i14EWud)"><path class="bpyc0obok"/><path fill="url(#ipEANKe)" class="yd3o8ib5t"/><path fill="url(#iJ7Gh3c)" class="yd3o8ib5t"/></g><g filter="url(#iS5Anoe)"><path class="ngplhmc7s"/><path fill="url(#iPxNiSZ)" class="aim8cdzcs"/><path fill="url(#izq6fBe)" class="aim8cdzcs"/></g><path fill="url(#iQa6qFe)" transform="rotate(-14.867 13.886 11.198)" class="xrq5zyb0y"/><path fill="url(#iSlN50n)" class="agujbdcbc"/><path fill="url(#iXzQSac)" class="agujbdcbc"/><path fill="url(#i2JH5cd)" class="agujbdcbc"/><path fill="url(#ipF76le)" class="agujbdcbc"/><g filter="url(#iHermHc)"><path class="ph71j9bnq"/><path fill="url(#iHoyrRb)" class="jq9gl67am"/></g><g filter="url(#i3xDijd)"><path class="rwhiabc9d"/></g><g filter="url(#iynKfsb)"><path class="au6h05bvl"/></g><path fill="url(#iFppb9b)" class="ypc2-1b3e"/><path fill="url(#imYQwWb)" class="ypc2-1b3e"/><path fill="url(#iyQCZae)" class="ypc2-1b3e"/><g filter="url(#icJ5zob)"><path fill="url(#iMTWKve)" class="sl3r8jb2e"/></g><path fill="url(#iA5CnAe)" class="uvtu-jvhf"/><g filter="url(#i3R6rce)"><path fill="url(#inasSTd)" class="a3js4bbsc"/><path fill="url(#igjFrog)" class="a3js4bbsc"/></g><g filter="url(#iCGokSb)"><path class="o90q-tngv"/></g><path fill="url(#i5o6FeG)" class="etpljybuf"/><path fill="url(#iU33hyb)" class="e1go0nbgx"/><path clip-rule="evenodd" class="xpbk6rb2s"/><g filter="url(#i3nAcQe)"><path clip-rule="evenodd" class="dqsi5fv5h"/></g><path class="xzuqivqdl"/><path class="ce6_7yb3e"/><path fill="url(#iW54vQc)" class="dmv6zzkrh"/><path fill="url(#iVmH4Rd)" class="foo7_4lzm"/><ellipse fill="url(#ignr5Sy)" transform="rotate(24.61 12.71 9.14)" class="qyoa61e9q"/><defs><radialGradient id="iC5KYHe" cx="0" cy="0" r="1" gradientTransform="matrix(3.48437 -4.05522 3.01176 2.5878 16.13 28.354)" gradientUnits="userSpaceOnUse"><stop class="lt2_2ybqi"/><stop offset="1" class="bils69brp"/></radialGradient><radialGradient id="ifGBdCd" cx="0" cy="0" r="1" gradientTransform="matrix(-.53125 3.29646 -1.78135 -.28708 16.224 22.002)" gradientUnits="userSpaceOnUse"><stop offset=".189" class="bmj_fbbea"/><stop offset="1" class="q_g8mnbhc"/></radialGradient><radialGradient id="i74bWAY" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.03125 -5.37969 0 12.849 19.674)" gradientUnits="userSpaceOnUse"><stop offset=".167" class="nu9hhfe4u"/><stop offset="1" class="t_vl9fbku"/></radialGradient><radialGradient id="ianbGjc" cx="0" cy="0" r="1" gradientTransform="matrix(-.10938 3.14063 -8.2876 -.28863 14.443 19.783)" gradientUnits="userSpaceOnUse"><stop offset=".558" class="gwwxm_bpq"/><stop offset=".971" class="xv9roqx4c"/></radialGradient><radialGradient id="iQa6qFe" cx="0" cy="0" r="1" gradientTransform="rotate(-28.776 33.185 -20.252)scale(2.02961 1.85514)" gradientUnits="userSpaceOnUse"><stop offset=".397" class="pc2bqsb8g"/><stop offset="1" class="l4bg9bbjp"/></radialGradient><radialGradient id="iSlN50n" cx="0" cy="0" r="1" gradientTransform="matrix(-3.4531 4.00002 -4.9949 -4.31194 17.677 15.299)" gradientUnits="userSpaceOnUse"><stop offset=".317" class="ai9smcbyp"/><stop offset=".849" class="j-pea3b4d"/></radialGradient><radialGradient id="iXzQSac" cx="0" cy="0" r="1" gradientTransform="rotate(120.981 4.118 11.906)scale(2.40218 1.79199)" gradientUnits="userSpaceOnUse"><stop class="svuvwyb0s"/><stop offset="1" class="dlkt90brn"/></radialGradient><radialGradient id="i2JH5cd" cx="0" cy="0" r="1" gradientTransform="matrix(-3.73437 .23436 -.4261 -6.78981 17.161 17.049)" gradientUnits="userSpaceOnUse"><stop offset=".723" class="z_p65vbje"/><stop offset="1" class="ql1m53bju"/></radialGradient><radialGradient id="ipF76le" cx="0" cy="0" r="1" gradientTransform="matrix(-.9902 -7.21551 5.43138 -.74536 16.153 19.207)" gradientUnits="userSpaceOnUse"><stop offset=".792" class="qrku0gb0w"/><stop offset=".968" class="p7c3g0b3k"/></radialGradient><radialGradient id="iHoyrRb" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.04687 -1.5625 0 16.395 17.425)" gradientUnits="userSpaceOnUse"><stop class="m8h2-hfui"/><stop offset="1" class="q2n0f68xb"/></radialGradient><radialGradient id="imYQwWb" cx="0" cy="0" r="1" gradientTransform="matrix(-.83488 1.0625 -1.21448 -.9543 16.448 13.408)" gradientUnits="userSpaceOnUse"><stop class="ove-epbrr"/><stop offset="1" class="h87azyork"/></radialGradient><radialGradient id="iyQCZae" cx="0" cy="0" r="1" gradientTransform="matrix(-2.71876 .54686 -1.0229 -5.08537 16.744 16.642)" gradientUnits="userSpaceOnUse"><stop offset=".756" class="bd3uesbch"/><stop offset=".909" class="f-z_jdbvz"/></radialGradient><radialGradient id="iA5CnAe" cx="0" cy="0" r="1" gradientTransform="matrix(.3125 .60583 -.77155 .39799 11.638 9.81)" gradientUnits="userSpaceOnUse"><stop offset=".332" class="cd4r3acma"/><stop offset="1" class="x767s0bmd"/></radialGradient><radialGradient id="igjFrog" cx="0" cy="0" r="1" gradientTransform="matrix(-.84375 -.04688 .05715 -1.0287 15.176 9.396)" gradientUnits="userSpaceOnUse"><stop offset=".156" class="d7kch3t0q"/><stop offset="1" class="admd7db0k"/></radialGradient><radialGradient id="i5o6FeG" cx="0" cy="0" r="1" gradientTransform="matrix(.84375 5.57813 -4.53655 .6862 15.869 7.218)" gradientUnits="userSpaceOnUse"><stop offset=".718" class="rmg76y8bk"/><stop offset="1" class="dgcxumb4u"/></radialGradient><radialGradient id="iU33hyb" cx="0" cy="0" r="1" gradientTransform="rotate(115.703 4.796 9.442)scale(1.04478 1.69772)" gradientUnits="userSpaceOnUse"><stop offset=".04" class="bervkqbmz"/><stop offset="1" class="c479w-bpn"/></radialGradient><radialGradient id="iW54vQc" cx="0" cy="0" r="1" gradientTransform="matrix(.27344 0 0 .53125 12.813 9.47)" gradientUnits="userSpaceOnUse"><stop offset=".895" class="l0aricxam"/><stop offset="1" class="n9r91ylyy"/></radialGradient><radialGradient id="iVmH4Rd" cx="0" cy="0" r="1" gradientTransform="matrix(.25 0 0 .54102 12.645 9.491)" gradientUnits="userSpaceOnUse"><stop class="gv3iwdbvq"/><stop offset=".813" class="ubyl24bdb"/></radialGradient><filter id="izG0ind" width="7.28" height="8.609" x="14.724" y="20.869" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.517647 0 0 0 0 0.384314 0 0 0 0 0.635294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_241"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.494118 0 0 0 0 0.466667 0 0 0 0 0.521569 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_241" result="effect2_innerShadow_4002_241"/></filter><filter id="iPusLIc" width="5.734" height="7.279" x="15.195" y="21.825" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_241" stdDeviation=".25"/></filter><filter id="ioKhQXi" width="11.64" height="10.135" x="7.83" y="19.674" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75" dy=".1"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.517647 0 0 0 0 0.490196 0 0 0 0 0.545098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_241"/></filter><filter id="i14EWud" width="4.352" height="2.364" x="7.83" y="27.644" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy=".3"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.254902 0 0 0 0 0.443137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_241"/></filter><filter id="iS5Anoe" width="3.579" height="3.542" x="20.591" y="26.223" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.247059 0 0 0 0 0.168627 0 0 0 0 0.486275 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_241"/></filter><filter id="iHermHc" width="6.876" height="3.179" x="9.905" y="16.739" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.878431 0 0 0 0 0.576471 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_241"/></filter><filter id="i3xDijd" width="1.171" height="1.539" x="9.571" y="18.716" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.862745 0 0 0 0 0.6 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_241"/></filter><filter id="iynKfsb" width="1.196" height="1.065" x="9.926" y="19.413" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.862745 0 0 0 0 0.6 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_241"/></filter><filter id="icJ5zob" width="8.168" height="8.42" x="9.556" y="20.16" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_241" stdDeviation=".375"/></filter><filter id="i3R6rce" width="4.493" height="5.449" x="11.752" y="6.997" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy="-.4"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.85098 0 0 0 0 0.54902 0 0 0 0 0.227451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_241"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy="-.05"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.737255 0 0 0 0 0.4 0 0 0 0 0.0470588 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_241" result="effect2_innerShadow_4002_241"/></filter><filter id="iCGokSb" width="7.013" height="7.503" x="11.44" y="5.436" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.843137 0 0 0 0 0.207843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_241"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.3"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.607843 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_241" result="effect2_innerShadow_4002_241"/></filter><filter id="i3nAcQe" width="1.013" height=".568" x="12.563" y="8.141" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.682353 0 0 0 0 0.219608 0 0 0 0 0.133333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_241"/></filter><linearGradient id="i4qdsKb" x1="16.786" x2="16.786" y1="19.58" y2="20.111" gradientUnits="userSpaceOnUse"><stop class="fy99v1bac"/><stop offset="1" class="l0bg_dlbj"/></linearGradient><linearGradient id="ipEANKe" x1="11.911" x2="10.927" y1="28.846" y2="28.846" gradientUnits="userSpaceOnUse"><stop class="jje8gccwz"/><stop offset="1" class="ifze1vbqw"/></linearGradient><linearGradient id="iJ7Gh3c" x1="10.474" x2="10.474" y1="29.709" y2="29.338" gradientUnits="userSpaceOnUse"><stop class="k1dl65w8i"/><stop offset="1" class="pqpq_lljy"/></linearGradient><linearGradient id="iPxNiSZ" x1="20.936" x2="21.622" y1="26.799" y2="27.463" gradientUnits="userSpaceOnUse"><stop class="olt5ljabw"/><stop offset="1" class="xgk77dt3o"/></linearGradient><linearGradient id="izq6fBe" x1="23.083" x2="22.868" y1="28.002" y2="28.174" gradientUnits="userSpaceOnUse"><stop offset=".098" class="fwheo7gdw"/><stop offset="1" class="oy9f4cbur"/></linearGradient><linearGradient id="iFppb9b" x1="16.95" x2="14.885" y1="15.877" y2="15.97" gradientUnits="userSpaceOnUse"><stop class="d30p-0b3w"/><stop offset="1" class="cm74u7bos"/></linearGradient><linearGradient id="iMTWKve" x1="10.306" x2="16.786" y1="26.596" y2="20.658" gradientUnits="userSpaceOnUse"><stop offset=".552" class="cl3ijcbld"/><stop offset="1" class="v224y-b0w"/></linearGradient><linearGradient id="inasSTd" x1="14.864" x2="12.002" y1="10.138" y2="10.31" gradientUnits="userSpaceOnUse"><stop class="sedutetcs"/><stop offset="1" class="yazmswbww"/></linearGradient><linearGradient id="ignr5Sy" x1="12.638" x2="12.825" y1="9.102" y2="9.162" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="stui2mbih"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-kneeling" /></template>
<style>
.a3js4bbsc {
  d: path("M12.03 8.698c.038-.802.297-1.188.42-1.3h3.732l.062 3.163c-.866 2.122-3.511 2.213-3.906 1.445c-.395-.767-.353-2.38-.309-3.308");
}

.admd7db0k {
  stop-color: var(--svg-color--ffab1d, #FFAB1D);
  stop-opacity: 0;
}

.agujbdcbc {
  d: path("M13.677 14.896c-.163 1.15-.094 2.637.016 3.528v1.289h5.03c-.054-2.063-.577-4.729-1.366-6.047c-.665-1.11-1.422-1.176-2.055-.957c-.606.183-1.422.75-1.625 2.187");
}

.ai9smcbyp {
  stop-color: var(--svg-color--8672be, #8672BE);
}

.aim8cdzcs {
  d: path("m21.476 26.533l-.885.75l.406 1.5c.39.198 1.35.653 2.063.89c.547.183.887.06 1.056-.083c.078-.065.066-.179 0-.257l-2.285-2.769a.25.25 0 0 0-.355-.031");
}

.aqha79btm {
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M17.208 22.361c-.138.941-.573 3.263-1.239 5.338a.5.5 0 0 0 .152.535a.55.55 0 0 0 .538.085c.689-.243 2.053-.525 3.737-.302");
}

.au6h05bvl {
  fill: var(--svg-color--f6b22f, #F6B22F);
  d: path("M10.552 19.513c.325-.003.516.179.57.27a2.2 2.2 0 0 0-.65.567c-.1.124-.278.169-.413.086a.266.266 0 0 1-.079-.39c.257-.329.48-.49.572-.533");
}

.bd3uesbch {
  stop-color: var(--svg-color--79699e, #79699E);
  stop-opacity: 0;
}

.bervkqbmz {
  stop-color: var(--svg-color--ffd040, #FFD040);
}

.bils69brp {
  stop-color: var(--svg-color--a49dac, #A49DAC);
  stop-opacity: 0;
}

.bmj_fbbea {
  stop-color: var(--svg-color--6a5a7a, #6A5A7A);
}

.bpyc0obok {
  fill: var(--svg-color--55538a, #55538A);
  d: path("M11.77 28.287a6.3 6.3 0 0 0-1.413-.643l.004.014c-.433.175-1.005.467-1.55.746l-.517.262c-.324.162-.533.495-.443.847a.26.26 0 0 0 .252.196h3.43a.25.25 0 0 0 .25-.253z");
}

.c479w-bpn {
  stop-color: var(--svg-color--fead30, #FEAD30);
}

.cd4r3acma {
  stop-color: var(--svg-color--e9b03e, #E9B03E);
}

.ce6_7yb3e {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.536 9.491h.988c0-.391-.221-.709-.494-.709s-.494.318-.494.71");
}

.cl3ijcbld {
  stop-color: var(--svg-color--a098a8, #A098A8);
}

.cm74u7bos {
  stop-color: var(--svg-color--725aaa, #725AAA);
}

.d30p-0b3w {
  stop-color: var(--svg-color--8f77c9, #8F77C9);
}

.d7kch3t0q {
  stop-color: var(--svg-color--ffab1d, #FFAB1D);
}

.dgcxumb4u {
  stop-color: var(--svg-color--a76445, #A76445);
}

.dlkt90brn {
  stop-color: var(--svg-color--9c83d3, #9C83D3);
  stop-opacity: 0;
}

.dmv6zzkrh {
  d: path("M13.141 9.491v-.003c0-.32-.137-.58-.306-.58c-.17 0-.307.26-.307.58v.003z");
}

.dqsi5fv5h {
  fill: var(--svg-color--af5247, #AF5247);
  fill-rule: evenodd;
  d: path("M13.049 8.459a.8.8 0 0 0-.217-.016a.15.15 0 1 1-.038-.298a1 1 0 0 1 .313.02c.128.025.278.076.409.173a.15.15 0 1 1-.179.24a.7.7 0 0 0-.288-.12");
}

.e1go0nbgx {
  d: path("M14.794 10.158c-.05 0-.086-.047-.08-.097l.174-1.248c.008-.056.06-.095.113-.079a.727.727 0 0 1-.207 1.424");
}

.etpljybuf {
  d: path("M11.91 7.35c-.172-.41.016-.843.113-.991c.367-.672 1.128-.717 1.566-.524c.516.227.67.347 1.504.11c.837-.239 1.868-.13 2.407.84c.539.968-.047 2.058.086 2.652c.132.593.512.652.652 1.34c.117.953-.473 1.574-.996 1.714c-.524.141-1.602 0-1.953-.875c-.575-1.431-.184-2.109-.31-2.828c-.124-.718-.554-.922-1.335-.765c-.92.184-1.506-.126-1.734-.672");
}

.f-z_jdbvz {
  stop-color: var(--svg-color--79699e, #79699E);
}

.foo7_4lzm {
  d: path("m12.946 9.491l.004-.072c0-.185-.079-.336-.176-.336s-.176.15-.176.336q0 .038.004.072z");
}

.ft5dv1b6b {
  fill: none;
}

.fwheo7gdw {
  stop-color: var(--svg-color--60608e, #60608E);
}

.fy99v1bac {
  stop-color: var(--svg-color--897694, #897694);
}

.gv3iwdbvq {
  stop-color: var(--svg-color--666361, #666361);
}

.gwwxm_bpq {
  stop-color: var(--svg-color--857297, #857297);
  stop-opacity: 0;
}

.gxq3zhbma {
  d: path("M14.73 27.385c-.05-1.838.196-4.493.32-5.57l3.485-.696c-.555 3.344-1.328 5.508-1.687 6.265c1.062-.265 2.578-.171 3.765-.117l.39 1.516c-1.233.125-3.339.522-3.843.648c-.562.141-2.371.086-2.43-2.047");
}

.h87azyork {
  stop-color: var(--svg-color--8366c0, #8366C0);
  stop-opacity: 0;
}

.ifze1vbqw {
  stop-color: var(--svg-color--605f91, #605F91);
  stop-opacity: 0;
}

.j-pea3b4d {
  stop-color: var(--svg-color--7059a7, #7059A7);
}

.jje8gccwz {
  stop-color: var(--svg-color--605f91, #605F91);
}

.jq9gl67am {
  d: path("m14.685 17.846l-.04-.782l1.891-.125c.047.664.118 1.594-.148 1.985c-.266.39-.765.858-2.2.945a42 42 0 0 1-3.269.031v-.18h-.672l-.34-.214c-.039-.192.39-.568.79-.711c1.254-.45 2.96-.82 3.988-.95");
}

.k1dl65w8i {
  stop-color: var(--svg-color--3f2d7e, #3F2D7E);
}

.kuoei6j8q {
  fill: var(--svg-color--968ba1, #968BA1);
  d: path("M9.236 22.877c.137.575.807 3.427 1.125 4.781c-.573.232-1.39.668-2.067 1.008c-.324.162-.533.495-.443.847a.26.26 0 0 0 .252.196h3.43a.25.25 0 0 0 .25-.253l-.076-7.17c1.787.443 3.937.81 5.747.263c1.2-.363 1.266-1.817 1.266-2.875l-7.61.078a2.726 2.726 0 0 0-1.874 3.125");
}

.l0aricxam {
  stop-color: var(--svg-color--916a62, #916A62);
}

.l0bg_dlbj {
  stop-color: var(--svg-color--897694, #897694);
  stop-opacity: 0;
}

.l4bg9bbjp {
  stop-color: var(--svg-color--bf6807, #BF6807);
}

.lt2_2ybqi {
  stop-color: var(--svg-color--a49dac, #A49DAC);
}

.m8h2-hfui {
  stop-color: var(--svg-color--ffc93e, #FFC93E);
}

.n9r91ylyy {
  stop-color: var(--svg-color--824d44, #824D44);
}

.ngplhmc7s {
  fill: var(--svg-color--443c7f, #443C7F);
  d: path("m21.476 26.533l-.885.75l.406 1.5c.39.198 1.35.653 2.063.89c.547.183.887.06 1.056-.083c.078-.065.066-.179 0-.257l-2.285-2.769a.25.25 0 0 0-.355-.031");
}

.nu9hhfe4u {
  stop-color: var(--svg-color--774e55, #774E55);
}

.o90q-tngv {
  fill: var(--svg-color--ffb629, #FFB629);
  d: path("M11.91 7.35c-.172-.41.016-.843.113-.991c.367-.672 1.128-.717 1.566-.524c.516.227.67.347 1.504.11c.837-.239 1.868-.13 2.407.84c.539.968-.047 2.058.086 2.652c.132.593.512.652.652 1.34c.117.953-.473 1.574-.996 1.714c-.524.141-1.602 0-1.953-.875c-.575-1.431-.184-2.109-.31-2.828c-.124-.718-.554-.922-1.335-.765c-.92.184-1.506-.126-1.734-.672");
}

.olt5ljabw {
  stop-color: var(--svg-color--3f3e62, #3F3E62);
}

.ove-epbrr {
  stop-color: var(--svg-color--9d84d5, #9D84D5);
}

.oy9f4cbur {
  stop-color: var(--svg-color--60608e, #60608E);
  stop-opacity: 0;
}

.p7c3g0b3k {
  stop-color: var(--svg-color--723b5b, #723B5B);
}

.pc2bqsb8g {
  stop-color: var(--svg-color--dc9e3c, #DC9E3C);
}

.ph71j9bnq {
  fill: var(--svg-color--ffbf36, #FFBF36);
  d: path("m14.685 17.846l-.04-.782l1.891-.125c.047.664.118 1.594-.148 1.985c-.266.39-.765.858-2.2.945a42 42 0 0 1-3.269.031v-.18h-.672l-.34-.214c-.039-.192.39-.568.79-.711c1.254-.45 2.96-.82 3.988-.95");
}

.pqpq_lljy {
  stop-color: var(--svg-color--3f2d7e, #3F2D7E);
  stop-opacity: 0;
}

.q_g8mnbhc {
  stop-color: var(--svg-color--766b81, #766B81);
  stop-opacity: 0;
}

.q2n0f68xb {
  stop-color: var(--svg-color--ffc93e, #FFC93E);
  stop-opacity: 0;
}

.ql1m53bju {
  stop-color: var(--svg-color--786c9a, #786C9A);
}

.qrku0gb0w {
  stop-color: var(--svg-color--81547e, #81547E);
  stop-opacity: 0;
}

.qyoa61e9q {
  cx: 12.71px;
  cy: 9.14px;
  rx: 0.064px;
  ry: 0.088px;
}

.rmg76y8bk {
  stop-color: var(--svg-color--fba522, #FBA522);
  stop-opacity: 0;
}

.rwhiabc9d {
  fill: var(--svg-color--eeae2f, #EEAE2F);
  d: path("m10.599 18.916l.043.633a4.3 4.3 0 0 0-.603.608a.27.27 0 0 1-.346.058a.243.243 0 0 1-.085-.338c.312-.472.795-.844.99-.961");
}

.sedutetcs {
  stop-color: var(--svg-color--ffb536, #FFB536);
}

.sl3r8jb2e {
  d: path("m10.318 22.213l.656 5.492l.312.125l-.43-5.73a.487.487 0 0 1 .482-.528c.926-.006 3.848 0 4.542 0c.812 0 1.094-.273 1.094-.648c-1.193-.01-4.677-.025-5.664 0s-1.04.862-.992 1.289");
}

.stui2mbih {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0;
}

.svuvwyb0s {
  stop-color: var(--svg-color--9c83d3, #9C83D3);
}

.t_vl9fbku {
  stop-color: var(--svg-color--8f7c7f, #8F7C7F);
  stop-opacity: 0;
}

.t-gr46jfz {
  fill: var(--svg-color--97919f, #97919F);
  d: path("M14.73 27.385c-.05-1.838.196-4.493.32-5.57l3.485-.696c-.555 3.344-1.328 5.508-1.687 6.265c1.062-.265 2.578-.171 3.765-.117l.39 1.516c-1.233.125-3.339.522-3.843.648c-.562.141-2.371.086-2.43-2.047");
}

.timippiwa {
  d: path("M9.236 22.877c.137.575.807 3.427 1.125 4.781c-.573.232-1.39.668-2.067 1.008c-.324.162-.533.495-.443.847a.26.26 0 0 0 .252.196h3.43a.25.25 0 0 0 .25-.253l-.076-7.17c1.787.443 3.937.81 5.747.263c1.2-.363 1.266-1.817 1.266-2.875l-7.61.078a2.726 2.726 0 0 0-1.874 3.125");
}

.ubyl24bdb {
  stop-color: var(--svg-color--565352, #565352);
}

.uvtu-jvhf {
  d: path("M11.792 9.635c.156-.147.23-.405.25-.497l.2.066v1.125c-.214.137-.538.08-.63-.124c-.078-.176-.015-.387.18-.57");
}

.v224y-b0w {
  stop-color: var(--svg-color--a098a8, #A098A8);
  stop-opacity: 0;
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.x767s0bmd {
  stop-color: var(--svg-color--e29e3f, #E29E3F);
}

.xgk77dt3o {
  stop-color: var(--svg-color--3f3e62, #3F3E62);
  stop-opacity: 0;
}

.xpbk6rb2s {
  fill: var(--svg-color--87014d, #87014D);
  fill-rule: evenodd;
  d: path("M13.281 10.605a.125.125 0 0 1-.002.177c-.238.233-.582.293-.691.304a.125.125 0 1 1-.026-.248c.094-.01.366-.062.542-.235a.125.125 0 0 1 .177.002");
}

.xrq5zyb0y {
  d: path("M13.886 11.198h1.976v2.198h-1.976z");
}

.xv9roqx4c {
  stop-color: var(--svg-color--7e5e9a, #7E5E9A);
}

.xzuqivqdl {
  fill: var(--svg-color--2f2c2d, #2F2C2D);
  d: path("M13.561 8.98c-.131-.13-.349-.16-.441-.16l.302.467c.147-.008.303-.143.14-.307");
}

.yazmswbww {
  stop-color: var(--svg-color--feb42f, #FEB42F);
}

.yd3o8ib5t {
  d: path("M11.77 28.287a6.3 6.3 0 0 0-1.413-.643l.004.014c-.433.175-1.005.467-1.55.746l-.517.262c-.324.162-.533.495-.443.847a.26.26 0 0 0 .252.196h3.43a.25.25 0 0 0 .25-.253z");
}

.yf5p-quaq {
  d: path("M11.707 22.29v-.003c1.787.442 3.937.808 5.747.262c1.2-.363 1.266-1.817 1.266-2.875l-7.61.078q-.4.138-.702.336z");
}

.ypc2-1b3e {
  d: path("M14.276 14.381a1.261 1.261 0 0 1 2.519-.119l.155 2.775l-2.566.152z");
}

.z_p65vbje {
  stop-color: var(--svg-color--786c9a, #786C9A);
  stop-opacity: 0;
}

</style>
