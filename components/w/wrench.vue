<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iOwEFUc)"><path fill="url(#id98fUb)" class="l96_6ebjf"/><path fill="url(#iPUojfd)" class="l96_6ebjf"/></g><g filter="url(#iO5iQed)"><path fill="url(#i1hhkzd)" class="yp1cs5bre"/><path fill="url(#iwdRwub)" class="yp1cs5bre"/><path fill="url(#imfHGlc)" class="yp1cs5bre"/></g><g filter="url(#i3r5V2c)"><path fill="url(#iQ4t3ld)" class="yhoh8lbsj"/><path fill="url(#ixeQyfe)" class="yhoh8lbsj"/></g><g filter="url(#iM7f7fd)"><path class="gr6e1icgc"/></g><g filter="url(#ijZlsYc)"><path class="y5uqhmbyd"/></g><g filter="url(#i6EBsPE)"><path class="s4m1_3f3j"/></g><defs><filter id="iOwEFUc" width="25.7" height="25.453" x="3.363" y="2.837" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.701961 0 0 0 0 0.686275 0 0 0 0 0.733333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_24325"/></filter><filter id="iO5iQed" width="10.462" height="10.487" x="3.14" y="2.651" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_24325" stdDeviation=".25"/></filter><filter id="i3r5V2c" width="10.462" height="10.462" x="18.636" y="17.975" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_24325" stdDeviation=".25"/></filter><filter id="iM7f7fd" width="13.356" height="13.527" x="8.828" y="9.237" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_24325" stdDeviation=".75"/></filter><filter id="ijZlsYc" width="12.564" height="12.735" x="10.529" y="8.354" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_24325" stdDeviation=".75"/></filter><filter id="i6EBsPE" width="3.765" height="3.62" x="9.485" y="9.204" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_24325" stdDeviation=".25"/></filter><radialGradient id="iPUojfd" cx="0" cy="0" r="1" gradientTransform="matrix(.8125 -.90625 7.36639 6.60435 14.758 17.014)" gradientUnits="userSpaceOnUse"><stop class="kfvqegxsb"/><stop offset="1" class="h3dyzvbdx"/></radialGradient><radialGradient id="i1hhkzd" cx="0" cy="0" r="1" gradientTransform="rotate(-94.749 9.59 2.02)scale(5.92465 8.69968)" gradientUnits="userSpaceOnUse"><stop class="ndyz_te8w"/><stop offset="1" class="yz_0e2o9z"/></radialGradient><radialGradient id="imfHGlc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.31248 2.06252 -3.19873 -3.5864 12.664 4.295)" gradientUnits="userSpaceOnUse"><stop offset=".202" class="fruy4pbmk"/><stop offset="1" class="o35eepbhn"/></radialGradient><radialGradient id="ixeQyfe" cx="0" cy="0" r="1" gradientTransform="matrix(-4.375 -.375 .36793 -4.29257 24.883 25.483)" gradientUnits="userSpaceOnUse"><stop offset=".26" class="gwuzddmyd"/><stop offset="1" class="y31ee37qp"/></radialGradient><linearGradient id="id98fUb" x1="13.396" x2="19.492" y1="22.244" y2="16.018" gradientUnits="userSpaceOnUse"><stop class="lse0qd2kj"/><stop offset="1" class="ubn8dccbe"/></linearGradient><linearGradient id="iwdRwub" x1="2.914" x2="5.945" y1="7.639" y2="7.483" gradientUnits="userSpaceOnUse"><stop class="hnqsnrb6n"/><stop offset="1" class="s6utpvcoq"/></linearGradient><linearGradient id="iQ4t3ld" x1="19.867" x2="23.211" y1="20.217" y2="23.811" gradientUnits="userSpaceOnUse"><stop class="hc7ov8b7z"/><stop offset="1" class="c9x1bccrw"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:wrench" /></template>
<style>
.c9x1bccrw {
  stop-color: var(--svg-color--b8b0c5, #B8B0C5);
  stop-opacity: 0;
}

.fruy4pbmk {
  stop-color: var(--svg-color--e4e1eb, #E4E1EB);
}

.ft5dv1b6b {
  fill: none;
}

.gr6e1icgc {
  fill: var(--svg-color--ccbce1, #CCBCE1);
  d: path("m11.519 10.737l9.164 9.36l-1.191 1.166l-9.164-9.36z");
}

.gwuzddmyd {
  stop-color: var(--svg-color--cebde5, #CEBDE5);
}

.h3dyzvbdx {
  stop-color: var(--svg-color--c6b7db, #C6B7DB);
  stop-opacity: 0;
}

.hc7ov8b7z {
  stop-color: var(--svg-color--b8b0c5, #B8B0C5);
}

.hnqsnrb6n {
  stop-color: var(--svg-color--a8a6b0, #A8A6B0);
}

.kfvqegxsb {
  stop-color: var(--svg-color--c6b7db, #C6B7DB);
}

.l96_6ebjf {
  d: path("M7.09 3.003c-.342.09-.425.511-.175.761l2.424 2.424a.75.75 0 0 1 0 1.06l-1.55 1.55a.75.75 0 0 1-1.06 0L4.297 6.364c-.25-.25-.67-.168-.762.173a5.014 5.014 0 0 0 4.836 6.315a5 5 0 0 0 1.258-.16a.65.65 0 0 1 .622.158l8.589 8.588c.16.161.214.398.158.618a5.008 5.008 0 0 0 6.138 6.068c.342-.09.425-.512.175-.762l-2.424-2.423a.75.75 0 0 1 0-1.06l1.549-1.55a.75.75 0 0 1 1.06 0l2.433 2.433c.25.25.67.167.762-.173a5.008 5.008 0 0 0-6.083-6.159a.65.65 0 0 1-.621-.157l-8.598-8.598a.65.65 0 0 1-.159-.616q.147-.586.149-1.215a5.008 5.008 0 0 0-6.29-4.842");
}

.lse0qd2kj {
  stop-color: var(--svg-color--bab6c1, #BAB6C1);
}

.ndyz_te8w {
  stop-color: var(--svg-color--d5c6eb, #D5C6EB);
}

.o35eepbhn {
  stop-color: var(--svg-color--e4e1eb, #E4E1EB);
  stop-opacity: 0;
}

.s4m1_3f3j {
  stroke: var(--svg-color--cbbae2, #CBBAE2);
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("m10.07 12.233l2.594-2.438");
}

.s6utpvcoq {
  stop-color: var(--svg-color--a8a6b0, #A8A6B0);
  stop-opacity: 0;
}

.ubn8dccbe {
  stop-color: var(--svg-color--e0dbe7, #E0DBE7);
}

.y31ee37qp {
  stop-color: var(--svg-color--cebde5, #CEBDE5);
  stop-opacity: 0;
}

.y5uqhmbyd {
  fill: var(--svg-color--e6e2f1, #E6E2F1);
  d: path("m12.029 10.61l8.791 8.98l.772-.757l-8.79-8.979z");
}

.yhoh8lbsj {
  d: path("M19.213 21.589a.63.63 0 0 1 .063.47a4.73 4.73 0 0 0 4.59 5.878c.24 0 1.703.044.923-.736l-2.294-2.367a.71.71 0 0 1 0-1.002l1.922-1.935a.71.71 0 0 1 1.002 0L27.9 24.35c.236.235.447.413.534.091a4.737 4.737 0 0 0-5.757-5.815a.64.64 0 0 1-.403-.025z");
}

.yp1cs5bre {
  d: path("M13.025 9.525a.63.63 0 0 1-.064-.47q.139-.553.14-1.147a4.73 4.73 0 0 0-4.73-4.731c-.24 0-1.69-.209-.91.571L9.742 6.28a.71.71 0 0 1 0 1.002L7.82 9.217a.71.71 0 0 1-1.002 0L4.336 6.764c-.236-.236-.447-.413-.533-.092a4.737 4.737 0 0 0 4.568 5.966q.617-.002 1.189-.15a.64.64 0 0 1 .402.025z");
}

.yz_0e2o9z {
  stop-color: var(--svg-color--d5c6eb, #D5C6EB);
  stop-opacity: 0;
}

</style>
