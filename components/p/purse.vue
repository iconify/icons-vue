<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#i4ptOnb)"><path fill="url(#iXEykLc)" class="kv9n7itgc"/><path fill="url(#ibVfggd)" class="kv9n7itgc"/></g><path fill="url(#i5fLIKd)" class="kv9n7itgc"/><g filter="url(#iAG5bre)"><circle fill="url(#iJruSde)" class="amn11acqo"/></g><g filter="url(#if7sWCd)"><circle fill="url(#ivOq7Fb)" class="yhifpwx8y"/></g><g filter="url(#iipaS6d)"><path fill="url(#i7KThcb)" class="vgvf_01ty"/></g><path fill="url(#iYYbABe)" class="vgvf_01ty"/><g filter="url(#iyQZXCd)"><path stroke="url(#ilwbsOd)" class="h2pfe3b4n"/></g><defs><radialGradient id="iXEykLc" cx="0" cy="0" r="1" gradientTransform="matrix(-12.37497 9.8125 -8.75571 -11.04221 26.372 13.563)" gradientUnits="userSpaceOnUse"><stop offset=".272" class="gpp9z4ewr"/><stop offset="1" class="ijztiybne"/></radialGradient><radialGradient id="ibVfggd" cx="0" cy="0" r="1" gradientTransform="matrix(-4.00013 -14.25 29.96393 -8.4112 18.06 24.375)" gradientUnits="userSpaceOnUse"><stop offset=".799" class="yy6lt-b2x"/><stop offset="1" class="cbuh60b8c"/></radialGradient><radialGradient id="i5fLIKd" cx="0" cy="0" r="1" gradientTransform="matrix(0 14.625 -22.0657 0 16 15.813)" gradientUnits="userSpaceOnUse"><stop offset=".906" class="htu7wis9o"/><stop offset="1" class="t3clzmowb"/></radialGradient><radialGradient id="iJruSde" cx="0" cy="0" r="1" gradientTransform="rotate(129.92 6.214 6.9)scale(2.31328)" gradientUnits="userSpaceOnUse"><stop offset=".188" class="asoeneb6f"/><stop offset="1" class="l17mbbclx"/></radialGradient><radialGradient id="ivOq7Fb" cx="0" cy="0" r="1" gradientTransform="rotate(129.92 7.678 7.585)scale(2.31328)" gradientUnits="userSpaceOnUse"><stop offset=".188" class="asoeneb6f"/><stop offset="1" class="l17mbbclx"/></radialGradient><radialGradient id="i7KThcb" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.6875 -11.0657 0 16 9.125)" gradientUnits="userSpaceOnUse"><stop offset=".271" class="wvw_iccfb"/><stop offset="1" class="tamqwwb5j"/></radialGradient><radialGradient id="iYYbABe" cx="0" cy="0" r="1" gradientTransform="rotate(140.425 12.762 10.68)scale(3.97318 20.8132)" gradientUnits="userSpaceOnUse"><stop offset=".479" class="rd3950ktc"/><stop offset="1" class="wbgapqfpp"/></radialGradient><filter id="i4ptOnb" width="29.744" height="21.571" x="2.128" y="8.313" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="2" dy="-.5"/><feGaussianBlur stdDeviation="2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.737255 0 0 0 0 0.25098 0 0 0 0 0.396078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_17026"/></filter><filter id="iAG5bre" width="2.93" height="3.03" x="13.067" y="5.869" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.996078 0 0 0 0 0.541176 0 0 0 0 0.0941176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_17026"/></filter><filter id="if7sWCd" width="3.03" height="3.03" x="15.997" y="5.869" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.996078 0 0 0 0 0.541176 0 0 0 0 0.0941176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_17026"/></filter><filter id="iipaS6d" width="25.99" height="8.3" x="3.055" y="8.613" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.960784 0 0 0 0 0.678431 0 0 0 0 0.282353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_17026"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.498039 0 0 0 0 0.101961 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_17026" result="effect2_innerShadow_18_17026"/></filter><filter id="iyQZXCd" width="6.562" height="7.814" x="22.577" y="9.084" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_17026" stdDeviation=".2"/></filter><linearGradient id="ilwbsOd" x1="27.93" x2="23.459" y1="15.923" y2="9.442" gradientUnits="userSpaceOnUse"><stop offset=".801" class="g3zgppf7k"/><stop offset="1" class="lx5sk7b9n"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:purse" /></template>
<style>
.amn11acqo {
  cx: 14.532px;
  cy: 7.434px;
  r: 1.465px;
}

.asoeneb6f {
  stop-color: var(--svg-color--fff453, #FFF453);
}

.cbuh60b8c {
  stop-color: var(--svg-color--ec2d8a, #EC2D8A);
}

.ft5dv1b6b {
  fill: none;
}

.g3zgppf7k {
  stop-color: var(--svg-color--ffde5f, #FFDE5F);
}

.gpp9z4ewr {
  stop-color: var(--svg-color--ff68a5, #FF68A5);
}

.h2pfe3b4n {
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M23.006 9.605c1.298.314 4.084 1.676 4.924 4.617c.218.724.562 1.756.688 2.244");
}

.htu7wis9o {
  stop-color: var(--svg-color--de66a6, #DE66A6);
  stop-opacity: 0;
}

.ijztiybne {
  stop-color: var(--svg-color--fb2b66, #FB2B66);
}

.kv9n7itgc {
  d: path("M11.371 8.813c-3.663 0-6.916 2.299-7.852 5.8q-.098.364-.194.735c.386.58.689 1.16.469 1.27c-.19.094-.425.152-.632.186a.32.32 0 0 0-.262.234c-.23.949-.442 1.89-.62 2.774c-.79 4.782 1.185 10.375 13.72 10.06c12.535.316 14.51-5.278 13.72-10.06a74 74 0 0 0-.62-2.775a.32.32 0 0 0-.262-.233a2.3 2.3 0 0 1-.63-.187c-.22-.11.081-.689.467-1.267l-.194-.737c-.936-3.501-4.189-5.8-7.852-5.8z");
}

.l17mbbclx {
  stop-color: var(--svg-color--ffa424, #FFA424);
}

.lx5sk7b9n {
  stop-color: var(--svg-color--ffde5f, #FFDE5F);
  stop-opacity: 0;
}

.rd3950ktc {
  stop-color: var(--svg-color--ffe05f, #FFE05F);
}

.t3clzmowb {
  stop-color: var(--svg-color--de66a6, #DE66A6);
}

.tamqwwb5j {
  stop-color: var(--svg-color--ffc046, #FFC046);
}

.vgvf_01ty {
  d: path("M11.371 8.813c-3.663 0-6.916 2.299-7.852 5.8c-.154.575-.306 1.163-.453 1.751a.36.36 0 0 0 .35.448c.578 0 1.081-.39 1.232-.947l.163-.592c.839-3.012 3.023-4.99 7.04-4.99h8.299c4.04 0 6.2 1.978 7.039 4.99l.163.592a1.28 1.28 0 0 0 1.231.947a.36.36 0 0 0 .35-.448a99 99 0 0 0-.452-1.751c-.936-3.501-4.189-5.8-7.852-5.8z");
}

.wbgapqfpp {
  stop-color: var(--svg-color--ffe05f, #FFE05F);
  stop-opacity: 0;
}

.wvw_iccfb {
  stop-color: var(--svg-color--ffd544, #FFD544);
}

.yhifpwx8y {
  cx: 17.462px;
  cy: 7.434px;
  r: 1.465px;
}

.yy6lt-b2x {
  stop-color: var(--svg-color--ec2d8a, #EC2D8A);
  stop-opacity: 0;
}

</style>
