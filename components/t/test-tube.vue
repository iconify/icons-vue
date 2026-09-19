<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iF7NiPc)"><path class="nfau9vpic"/></g><g filter="url(#iilqMvB)"><path class="mbzugbcbo"/></g><g filter="url(#iNBVvjd)"><path class="kqh1j02ds"/><path fill="url(#iHBy8Fb)" class="w8jvisbej"/></g><path fill="url(#iaKhvxe)" class="vzrccqb9e"/><path fill="url(#igP20vd)" class="b45_j6gjf"/><path fill="url(#ixWi2Vb)" class="vm_ik72is"/><g filter="url(#iOZvjBb)"><path class="hghih95-e"/><path fill="url(#iVTrdIe)" class="p1x-e4bnp"/></g><g filter="url(#i6Xtqjb)"><path class="wzmic9brb"/></g><defs><linearGradient id="iHBy8Fb" x1="25.761" x2="17.074" y1="13.875" y2="16.875" gradientUnits="userSpaceOnUse"><stop offset=".203" class="lk6wfbbia"/><stop offset="1" class="o52-446mg"/></linearGradient><linearGradient id="iaKhvxe" x1="16.761" x2="14.011" y1="14.063" y2="11.469" gradientUnits="userSpaceOnUse"><stop class="gg66diwtu"/><stop offset="1" class="td6ip8xap"/></linearGradient><linearGradient id="igP20vd" x1="12.252" x2="9.508" y1="18.557" y2="15.969" gradientUnits="userSpaceOnUse"><stop class="gg66diwtu"/><stop offset="1" class="td6ip8xap"/></linearGradient><linearGradient id="ixWi2Vb" x1="7.743" x2="5" y1="23.065" y2="20.477" gradientUnits="userSpaceOnUse"><stop class="gg66diwtu"/><stop offset="1" class="td6ip8xap"/></linearGradient><linearGradient id="iVTrdIe" x1="28.786" x2="28.656" y1="13.521" y2="11.86" gradientUnits="userSpaceOnUse"><stop class="p3m6t9b7r"/><stop offset="1" class="s7sp33bog"/></linearGradient><filter id="iF7NiPc" width="25.366" height="25.366" x="2.692" y="4.43" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.745098 0 0 0 0 0.85098 0 0 0 0 0.964706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_24902"/></filter><filter id="iilqMvB" width="13.675" height="13.675" x="13.347" y="5.524" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_24902" stdDeviation="1"/></filter><filter id="iNBVvjd" width="26.42" height="17.178" x="2.692" y="12.618" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="4" dy="-.75"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.505882 0 0 0 0 0.811765 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_24902"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.4"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.788235 0 0 0 0 0.843137 0 0 0 0 0.898039 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_24902" result="effect2_innerShadow_18_24902"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.4"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.67451 0 0 0 0 0.839216 0 0 0 0 0.623529 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_24902" result="effect3_innerShadow_18_24902"/></filter><filter id="iOZvjBb" width="11.181" height="11.181" x="19.12" y="2.187" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.658824 0 0 0 0 0.776471 0 0 0 0 0.937255 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_24902"/></filter><filter id="i6Xtqjb" width="10.986" height="10.986" x="19.166" y="2.14" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_24902" stdDeviation=".375"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:test-tube" /></template>
<style>
.b45_j6gjf {
  d: path("m9.097 16.398l1.162-1.162l2.085 2.085a.822.822 0 1 1-1.162 1.162z");
}

.ft5dv1b6b {
  fill: none;
}

.gg66diwtu {
  stop-color: var(--svg-color--138979, #138979);
}

.hghih95-e {
  fill: var(--svg-color--a9d8ff, #A9D8FF);
  d: path("M19.55 2.617a1.47 1.47 0 0 0 0 2.079l8.242 8.242a1.47 1.47 0 0 0 2.078-2.079l-8.242-8.242a1.47 1.47 0 0 0-2.078 0");
}

.kqh1j02ds {
  fill: var(--svg-color--d1f884, #D1F884);
  d: path("m26.112 13.368l-14.98 14.98a4.944 4.944 0 1 1-6.992-6.992l7.988-7.988z");
}

.lk6wfbbia {
  stop-color: var(--svg-color--e9eb7e, #E9EB7E);
}

.mbzugbcbo {
  fill: var(--svg-color--c6efff, #C6EFFF);
  d: path("m23.37 7.524l1.653 1.653L17 17.199l-1.653-1.652z");
}

.nfau9vpic {
  fill: var(--svg-color--a5d9ff, #A5D9FF);
  d: path("m21.066 4.43l6.992 6.992l-16.926 16.926a4.944 4.944 0 1 1-6.992-6.992z");
}

.o52-446mg {
  stop-color: var(--svg-color--e9eb7e, #E9EB7E);
  stop-opacity: 0;
}

.p1x-e4bnp {
  d: path("M19.55 2.617a1.47 1.47 0 0 0 0 2.079l8.242 8.242a1.47 1.47 0 0 0 2.078-2.079l-8.242-8.242a1.47 1.47 0 0 0-2.078 0");
}

.p3m6t9b7r {
  stop-color: var(--svg-color--a8c3ff, #A8C3FF);
}

.s7sp33bog {
  stop-color: var(--svg-color--a8c3ff, #A8C3FF);
  stop-opacity: 0;
}

.td6ip8xap {
  stop-color: var(--svg-color--2e7b65, #2E7B65);
}

.vm_ik72is {
  d: path("m4.589 20.907l1.162-1.162l2.084 2.084a.822.822 0 0 1-1.163 1.162z");
}

.vzrccqb9e {
  d: path("M14.761 10.735L13.6 11.897l2.093 2.092a.822.822 0 0 0 1.162-1.162z");
}

.w8jvisbej {
  d: path("m26.112 13.368l-14.98 14.98a4.944 4.944 0 1 1-6.992-6.992l7.988-7.988z");
}

.wzmic9brb {
  fill: var(--svg-color--c4ecff, #C4ECFF);
  d: path("m19.916 4.001l1.11-1.11l8.376 8.374l-1.111 1.111z");
}

</style>
