<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iRNiVSw)"><path fill="url(#iDKbS9T)" class="nefg4ld7i"/><path fill="url(#iHEPtad)" class="nefg4ld7i"/><path fill="url(#iQFctjb)" class="nefg4ld7i"/><path fill="url(#ib7cZiU)" class="nefg4ld7i"/><path fill="url(#i3wv0fe)" class="nefg4ld7i"/></g><g filter="url(#ivUVYGc)"><path fill="url(#iEmPwld)" clip-rule="evenodd" class="daan-bbxd"/></g><path fill="url(#iANc78b)" clip-rule="evenodd" class="daan-bbxd"/><path fill="url(#iDsWc7d)" clip-rule="evenodd" class="daan-bbxd"/><g filter="url(#iSchu6c)"><path fill="url(#i0p7Pac)" class="ur7jve8ye"/></g><g filter="url(#isoD9Ke)"><rect fill="url(#iJFv7UF)" class="eh8-k9gho"/></g><g filter="url(#iRXLgvg)"><path stroke="url(#iMceJCd)" class="el4925bpu"/></g><defs><radialGradient id="iDKbS9T" cx="0" cy="0" r="1" gradientTransform="matrix(0 -8.82558 12.8465 0 4.855 28.915)" gradientUnits="userSpaceOnUse"><stop offset=".089" class="r7fz6rbnr"/><stop offset="1" class="zd5sh0b2p"/></radialGradient><radialGradient id="ib7cZiU" cx="0" cy="0" r="1" gradientTransform="matrix(1.89063 -7.9375 12.62578 3.00733 2.758 27.597)" gradientUnits="userSpaceOnUse"><stop offset=".762" class="vbsjlvbmk"/><stop offset=".973" class="li82e5o-h"/></radialGradient><radialGradient id="i3wv0fe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -7.06253 1.71875 0 6.102 29.94)" gradientUnits="userSpaceOnUse"><stop class="esvm0qm6t"/><stop offset="1" class="uywd5h87s"/></radialGradient><radialGradient id="iANc78b" cx="0" cy="0" r="1" gradientTransform="rotate(158.199 5.492 16.097)scale(4.03887 5.98838)" gradientUnits="userSpaceOnUse"><stop offset=".198" class="go1idfbej"/><stop offset="1" class="o5wfu9s6g"/></radialGradient><radialGradient id="iDsWc7d" cx="0" cy="0" r="1" gradientTransform="rotate(143.556 10.637 18.31)scale(2.52507 .99397)" gradientUnits="userSpaceOnUse"><stop class="u5biapw5g"/><stop offset="1" class="c918gxblu"/></radialGradient><radialGradient id="iMceJCd" cx="0" cy="0" r="1" gradientTransform="rotate(125.8 1.404 13.102)scale(6.35736 10.1761)" gradientUnits="userSpaceOnUse"><stop offset=".135" class="lh8o26b8t"/><stop offset="1" class="w1olkgbsx"/></radialGradient><linearGradient id="iHEPtad" x1="1.602" x2="3.445" y1="26.128" y2="26.191" gradientUnits="userSpaceOnUse"><stop offset=".13" class="s5-i_5baa"/><stop offset="1" class="lr8-bxhca"/></linearGradient><linearGradient id="iQFctjb" x1="7.758" x2="6.602" y1="29.566" y2="29.566" gradientUnits="userSpaceOnUse"><stop class="l0v7p6b2t"/><stop offset="1" class="crwoeabne"/></linearGradient><linearGradient id="iEmPwld" x1="4.879" x2="29.476" y1="20.066" y2="29.349" gradientUnits="userSpaceOnUse"><stop offset=".372" class="sanj04bac"/><stop offset="1" class="nxyicj3ne"/></linearGradient><linearGradient id="i0p7Pac" x1="23.695" x2="20.258" y1="21.253" y2="30.222" gradientUnits="userSpaceOnUse"><stop class="hxiazpbky"/><stop offset="1" class="jby78g7pk"/></linearGradient><linearGradient id="iJFv7UF" x1="25.164" x2="25.164" y1="22.378" y2="28.91" gradientUnits="userSpaceOnUse"><stop class="zjgefedqp"/><stop offset=".849" class="lezv4obvo"/></linearGradient><filter id="iRNiVSw" width="5.031" height="11.145" x="2.133" y="18.796" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.847059 0 0 0 0 0.521569 0 0 0 0 0.584314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_17288"/></filter><filter id="ivUVYGc" width="28.234" height="12.159" x="2.133" y="17.719" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.3"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.792157 0 0 0 0 0.364706 0 0 0 0 0.423529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_17288"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.780392 0 0 0 0 0.517647 0 0 0 0 0.360784 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_17288" result="effect2_innerShadow_18_17288"/></filter><filter id="iSchu6c" width="11.155" height="11.158" x="15.249" y="19.783" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="1"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.847059 0 0 0 0 0.137255 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_17288"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.811765 0 0 0 0 0.133333 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_17288" result="effect2_innerShadow_18_17288"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.737255 0 0 0 0 0.184314 0 0 0 0 0.305882 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_17288" result="effect3_innerShadow_18_17288"/></filter><filter id="isoD9Ke" width="2.875" height="8.531" x="23.727" y="21.378" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_17288" stdDeviation=".5"/></filter><filter id="iRXLgvg" width="10.969" height="10.25" x="3.383" y="18.04" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_17288" stdDeviation=".25"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:womans-sandal" /></template>
<style>
.c918gxblu {
  stop-color: var(--svg-color--ffd78f, #FFD78F);
  stop-opacity: 0;
}

.crwoeabne {
  stop-color: var(--svg-color--e49160, #E49160);
  stop-opacity: 0;
}

.daan-bbxd {
  fill-rule: evenodd;
  d: path("M7.552 21.019H4.133a2 2 0 0 1-2-2v-.5a.5.5 0 0 1 .5-.5h4.919a6 6 0 0 1 6 6v2.01c0 .469.381.85.85.85h14.965a.5.5 0 0 1 .5.5v.75a1.75 1.75 0 0 1-1.75 1.75H13.052a2.5 2.5 0 0 1-2.5-2.5v-3.266c0-1.782-1.64-3.094-3-3.094");
}

.eh8-k9gho {
  width: 0.875px;
  height: 6.531px;
  x: 24.727px;
  y: 22.378px;
  rx: 0.438px;
}

.el4925bpu {
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M3.883 18.79h4.156c2.188 0 4.781 1.607 4.781 5.182v3.068a.5.5 0 0 0 .5.5h.532");
}

.esvm0qm6t {
  stop-color: var(--svg-color--ffd8a6, #FFD8A6);
}

.ft5dv1b6b {
  fill: none;
}

.go1idfbej {
  stop-color: var(--svg-color--d4794d, #D4794D);
}

.hxiazpbky {
  stop-color: var(--svg-color--e3346a, #E3346A);
}

.jby78g7pk {
  stop-color: var(--svg-color--d91e95, #D91E95);
}

.l0v7p6b2t {
  stop-color: var(--svg-color--da7442, #DA7442);
}

.lezv4obvo {
  stop-color: var(--svg-color--ed5381, #ED5381);
}

.lh8o26b8t {
  stop-color: var(--svg-color--ffd694, #FFD694);
}

.li82e5o-h {
  stop-color: var(--svg-color--ba4632, #BA4632);
}

.lr8-bxhca {
  stop-color: var(--svg-color--b88a66, #B88A66);
  stop-opacity: 0;
}

.nefg4ld7i {
  d: path("M2.133 18.946h5.031V29.04a.9.9 0 0 1-.9.9H3.033a.9.9 0 0 1-.9-.9z");
}

.nxyicj3ne {
  stop-color: var(--svg-color--ffc08c, #FFC08C);
}

.o5wfu9s6g {
  stop-color: var(--svg-color--d4794d, #D4794D);
  stop-opacity: 0;
}

.r7fz6rbnr {
  stop-color: var(--svg-color--f6bd90, #F6BD90);
}

.s5-i_5baa {
  stop-color: var(--svg-color--9e6845, #9E6845);
}

.sanj04bac {
  stop-color: var(--svg-color--efb383, #EFB383);
}

.u5biapw5g {
  stop-color: var(--svg-color--ffd78f, #FFD78F);
}

.ur7jve8ye {
  d: path("m19.51 20.646l-4.028 6.804a1.65 1.65 0 0 0 1.42 2.49h8.153c.69 0 1.25-.559 1.25-1.25v-5.815a1.2 1.2 0 0 0-.79-1.128l-4.501-1.639a1.25 1.25 0 0 0-1.503.538");
}

.uywd5h87s {
  stop-color: var(--svg-color--f0b88c, #F0B88C);
  stop-opacity: 0;
}

.vbsjlvbmk {
  stop-color: var(--svg-color--ba4632, #BA4632);
  stop-opacity: 0;
}

.w1olkgbsx {
  stop-color: var(--svg-color--ffd694, #FFD694);
  stop-opacity: 0;
}

.zd5sh0b2p {
  stop-color: var(--svg-color--de8452, #DE8452);
}

.zjgefedqp {
  stop-color: var(--svg-color--ec506c, #EC506C);
}

</style>
