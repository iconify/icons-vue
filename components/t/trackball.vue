<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iuM5hsb)"><path fill="url(#iQUFcqc)" class="vj-pibb9d"/><path fill="url(#iFAvZrc)" class="vj-pibb9d"/><path fill="url(#iX0Wtue)" class="vj-pibb9d"/></g><g filter="url(#iGNFe3b)"><path stroke="url(#iL14QRb)" class="lgv079bte"/></g><g filter="url(#iKNJYUd)"><path class="iyi573kve"/></g><circle fill="url(#iZILHre)" class="zppfvb5wr"/><circle fill="url(#iUlf7xK)" class="zppfvb5wr"/><ellipse fill="url(#irQNiGK)" transform="rotate(-33.162 17.49 9.643)" class="bbru-yb1c"/><defs><radialGradient id="iQUFcqc" cx="0" cy="0" r="1" gradientTransform="scale(14.8125 15.5)rotate(90 .39 .918)" gradientUnits="userSpaceOnUse"><stop class="qd1k2gbkt"/><stop offset="1" class="fm8rduitx"/></radialGradient><radialGradient id="iFAvZrc" cx="0" cy="0" r="1" gradientTransform="matrix(2.5625 -9.125 11.4883 3.22617 13.438 31)" gradientUnits="userSpaceOnUse"><stop class="pt32f1e5e"/><stop offset="1" class="kydbc-bpq"/></radialGradient><radialGradient id="iX0Wtue" cx="0" cy="0" r="1" gradientTransform="rotate(60.971 1.609 9.775)scale(13.6526 27.2717)" gradientUnits="userSpaceOnUse"><stop class="wie6no-en"/><stop offset="1" class="vmamq97pn"/></radialGradient><radialGradient id="iZILHre" cx="0" cy="0" r="1" gradientTransform="matrix(-5.3437 6.75004 -7.06062 -5.58956 18.906 8.406)" gradientUnits="userSpaceOnUse"><stop offset=".175" class="fq87jib8s"/><stop offset="1" class="oy9qi0pgb"/></radialGradient><radialGradient id="iUlf7xK" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.6875 -7.77422 0 16 9.313)" gradientUnits="userSpaceOnUse"><stop offset=".897" class="py-gbmb8x"/><stop offset="1" class="qj_imlb6b"/></radialGradient><filter id="iuM5hsb" width="18.252" height="28.275" x="6.874" y="1.863" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.4 0 0 0 0 0.4 0 0 0 0 0.498039 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_19755"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.521569 0 0 0 0 0.52549 0 0 0 0 0.709804 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_19755" result="effect2_innerShadow_18_19755"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.478431 0 0 0 0 0.380392 0 0 0 0 0.619608 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_19755" result="effect3_innerShadow_18_19755"/></filter><filter id="iGNFe3b" width="12.875" height="17.594" x="9.563" y="1.688" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_19755" stdDeviation=".125"/></filter><filter id="iKNJYUd" width="12.525" height="16.844" x="9.688" y="2.063" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.239216 0 0 0 0 0.141176 0 0 0 0 0.333333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_19755"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.4 0 0 0 0 0.321569 0 0 0 0 0.466667 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_19755" result="effect2_innerShadow_18_19755"/></filter><linearGradient id="iL14QRb" x1="16.219" x2="16.219" y1="16.875" y2="3.094" gradientUnits="userSpaceOnUse"><stop class="t1ggw7b5w"/><stop offset="1" class="pr-hks25y"/></linearGradient><linearGradient id="irQNiGK" x1="18.009" x2="16.436" y1="8.468" y2="10.874" gradientUnits="userSpaceOnUse"><stop offset=".391" class="vc--wpv5i"/><stop offset="1" class="stui2mbih"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:trackball" /></template>
<style>
.bbru-yb1c {
  cx: 17.489px;
  cy: 9.643px;
  rx: 1.377px;
  ry: 1.753px;
}

.fm8rduitx {
  stop-color: var(--svg-color--50437f, #50437F);
}

.fq87jib8s {
  stop-color: var(--svg-color--ff4471, #FF4471);
}

.ft5dv1b6b {
  fill: none;
}

.iyi573kve {
  fill: var(--svg-color--543a65, #543A65);
  d: path("M16.54 2.063h-1.08V4.96a6.063 6.063 0 0 0 0 12.078v1.328a.54.54 0 0 0 1.08 0V17.04a6.063 6.063 0 0 0 0-12.078z");
}

.kydbc-bpq {
  stop-color: var(--svg-color--4b367a, #4B367A);
  stop-opacity: 0;
}

.lgv079bte {
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M16.54 2.063h-1.08V4.96a6.063 6.063 0 0 0 0 12.078v1.328a.54.54 0 0 0 1.08 0V17.04a6.063 6.063 0 0 0 0-12.078z");
}

.oy9qi0pgb {
  stop-color: var(--svg-color--c9274f, #C9274F);
}

.pr-hks25y {
  stop-color: var(--svg-color--625b87, #625B87);
  stop-opacity: 0;
}

.pt32f1e5e {
  stop-color: var(--svg-color--4b367a, #4B367A);
}

.py-gbmb8x {
  stop-color: var(--svg-color--c72361, #C72361);
  stop-opacity: 0;
}

.qd1k2gbkt {
  stop-color: var(--svg-color--7f7da4, #7F7DA4);
}

.qj_imlb6b {
  stop-color: var(--svg-color--c72361, #C72361);
}

.stui2mbih {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0;
}

.t1ggw7b5w {
  stop-color: var(--svg-color--625b87, #625B87);
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.vj-pibb9d {
  d: path("M7.074 6.763a4.7 4.7 0 0 1 4.7-4.7h8.452a4.7 4.7 0 0 1 4.7 4.7v18.675a4.5 4.5 0 0 1-4.5 4.5h-8.852a4.5 4.5 0 0 1-4.5-4.5z");
}

.vmamq97pn {
  stop-color: var(--svg-color--616293, #616293);
  stop-opacity: 0;
}

.wie6no-en {
  stop-color: var(--svg-color--616293, #616293);
}

.zppfvb5wr {
  cx: 16px;
  cy: 11px;
  r: 5px;
}

</style>
