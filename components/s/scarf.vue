<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><rect fill="url(#iJ3yHEb)" class="opi5e4blu"/><rect fill="url(#irIJuyc)" class="lfhmp4r9d"/><rect fill="url(#iT0nSPb)" class="y-u5ps6fr"/><rect fill="url(#iurGFVg)" class="jej38c2zf"/><g filter="url(#ipCvmDd)"><path fill="url(#iraUh7d)" class="zxo8yfr-q"/><path fill="url(#iijVt8b)" class="zxo8yfr-q"/></g><path fill="url(#i9d34me)" clip-rule="evenodd" class="a3yotjb2z"/><path fill="url(#iXDZcyc)" clip-rule="evenodd" class="a3yotjb2z"/><path fill="url(#intr7db)" clip-rule="evenodd" class="a3yotjb2z"/><path fill="url(#i3A4Slc)" clip-rule="evenodd" class="a3yotjb2z"/><path fill="url(#izwkKIc)" class="cifv1zbmr"/><path fill="url(#i3mTHee)" class="cifv1zbmr"/><path fill="url(#iyZk0lc)" class="cifv1zbmr"/><path fill="url(#iUYMoqd)" class="cifv1zbmr"/><path fill="url(#iMj359d)" class="cifv1zbmr"/><path fill="url(#i2T8Zrc)" class="cifv1zbmr"/><path fill="url(#ioYru9d)" class="cifv1zbmr"/><defs><radialGradient id="iJ3yHEb" cx="0" cy="0" r="1" gradientTransform="matrix(2.41015 0 0 .64889 2.081 22.779)" gradientUnits="userSpaceOnUse"><stop class="o6f9dsugp"/><stop offset="1" class="gtg11acuz"/></radialGradient><radialGradient id="irIJuyc" cx="0" cy="0" r="1" gradientTransform="matrix(2.41015 0 0 .64889 2.081 24.818)" gradientUnits="userSpaceOnUse"><stop class="o6f9dsugp"/><stop offset="1" class="gtg11acuz"/></radialGradient><radialGradient id="iT0nSPb" cx="0" cy="0" r="1" gradientTransform="matrix(2.41015 0 0 .64889 2.081 26.755)" gradientUnits="userSpaceOnUse"><stop class="o6f9dsugp"/><stop offset="1" class="gtg11acuz"/></radialGradient><radialGradient id="iurGFVg" cx="0" cy="0" r="1" gradientTransform="matrix(2.41015 0 0 .64889 2.081 28.63)" gradientUnits="userSpaceOnUse"><stop class="o6f9dsugp"/><stop offset="1" class="gtg11acuz"/></radialGradient><radialGradient id="iraUh7d" cx="0" cy="0" r="1" gradientTransform="matrix(1.7608 8.00036 -22.39072 4.92796 9.977 20.895)" gradientUnits="userSpaceOnUse"><stop class="pobhhxbow"/><stop offset="1" class="f3o1ajbao"/></radialGradient><radialGradient id="iijVt8b" cx="0" cy="0" r="1" gradientTransform="rotate(86.155 -6.628 14.6)scale(3.45587 16.2121)" gradientUnits="userSpaceOnUse"><stop offset=".276" class="m4m38ob0c"/><stop offset="1" class="b9g72cbrb"/></radialGradient><radialGradient id="i9d34me" cx="0" cy="0" r="1" gradientTransform="matrix(6.625 -9.93752 10.86151 7.24099 17.788 15.187)" gradientUnits="userSpaceOnUse"><stop offset=".254" class="hbgggmbdi"/><stop offset="1" class="e-5k_jq6j"/></radialGradient><radialGradient id="iXDZcyc" cx="0" cy="0" r="1" gradientTransform="matrix(4.73004 -3.92277 3.74607 4.51697 14.873 11.875)" gradientUnits="userSpaceOnUse"><stop offset=".653" class="n0xvj6lry"/><stop offset="1" class="xgrez327d"/></radialGradient><radialGradient id="intr7db" cx="0" cy="0" r="1" gradientTransform="matrix(5.722 -5.77618 6.87464 6.81015 17.882 11.875)" gradientUnits="userSpaceOnUse"><stop offset=".811" class="qvr0edcrn"/><stop offset=".955" class="s_-3q8sgh"/></radialGradient><radialGradient id="i3A4Slc" cx="0" cy="0" r="1" gradientTransform="rotate(-159.664 12.384 3.907)scale(12.763 8.17559)" gradientUnits="userSpaceOnUse"><stop offset=".929" class="y09u65bga"/><stop offset="1" class="xvzju5bhv"/></radialGradient><radialGradient id="i3mTHee" cx="0" cy="0" r="1" gradientTransform="rotate(-150.101 13.583 .729)scale(11.6587 13.8221)" gradientUnits="userSpaceOnUse"><stop class="smhw9mbxl"/><stop offset="1" class="p0xohyb7n"/></radialGradient><radialGradient id="iyZk0lc" cx="0" cy="0" r="1" gradientTransform="rotate(157.751 7.83 4.932)scale(6.68524 4.26619)" gradientUnits="userSpaceOnUse"><stop offset=".814" class="wrfdem4qe"/><stop offset="1" class="t1uir7drl"/></radialGradient><radialGradient id="iUYMoqd" cx="0" cy="0" r="1" gradientTransform="rotate(23.658 -9.597 16.21)scale(7.83993 46.3791)" gradientUnits="userSpaceOnUse"><stop offset=".18" class="z8g2son8j"/><stop offset="1" class="yxjpyw7lq"/></radialGradient><radialGradient id="iMj359d" cx="0" cy="0" r="1" gradientTransform="matrix(-16.79418 -15.47173 10.48383 -11.37994 23.795 21.027)" gradientUnits="userSpaceOnUse"><stop offset=".94" class="gw829ac-g"/><stop offset="1" class="t1fwi9bjc"/></radialGradient><radialGradient id="i2T8Zrc" cx="0" cy="0" r="1" gradientTransform="rotate(-88.509 23.928 1.362)scale(5.08083 18.1434)" gradientUnits="userSpaceOnUse"><stop class="jrtjj9bpr"/><stop offset="1" class="kau4zxbdw"/></radialGradient><radialGradient id="ioYru9d" cx="0" cy="0" r="1" gradientTransform="rotate(87.866 5.122 24.17)scale(5.32625 .95314)" gradientUnits="userSpaceOnUse"><stop offset=".26" class="kp81rabeu"/><stop offset="1" class="nmfn8rqzk"/></radialGradient><linearGradient id="izwkKIc" x1="17.427" x2="17.427" y1="2.319" y2="19.414" gradientUnits="userSpaceOnUse"><stop class="va4hins_k"/><stop offset="1" class="a3lcjv4ej"/></linearGradient><filter id="ipCvmDd" width="16.415" height="9.984" x="3.655" y="20.234" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.678431 0 0 0 0 0.145098 0 0 0 0 0.423529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_16482"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:scarf" /></template>
<style>
.a3lcjv4ej {
  stop-color: var(--svg-color--fe1c32, #FE1C32);
}

.a3yotjb2z {
  fill-rule: evenodd;
  d: path("M15.601 20.781c6.192 0 10.875-1.543 10.875-7.735S21.262 2.969 15.07 2.969s-8.063 3.558-8.063 9.75c0 6.191 2.402 8.062 8.594 8.062m-.555-4.36a4.617 4.617 0 1 0 0-9.234a4.617 4.617 0 0 0 0 9.235");
}

.b9g72cbrb {
  stop-color: var(--svg-color--c02474, #C02474);
  stop-opacity: 0;
}

.cifv1zbmr {
  d: path("M17.663 3.844c6.125.8 8.323 5.416 8.657 7.625c-.532-5.64-6.19-9.924-12.407-9.032C8.695 3.36 6.07 7.25 5.351 10.72c-.625 2.578-.219 8.812 6.062 11.75c5.201 2.748 13.603 2.911 17.579 2.723a.71.71 0 0 0 .68-.677c.076-1.698.071-5.128-.178-7.483c-.052-.502-.5-.863-1.005-.851C13.569 16.513 11.423 12.556 11.1 9c-.188-3.375 3.031-5.625 6.562-5.156");
}

.e-5k_jq6j {
  stop-color: var(--svg-color--dc1362, #DC1362);
}

.f3o1ajbao {
  stop-color: var(--svg-color--dd209f, #DD209F);
}

.ft5dv1b6b {
  fill: none;
}

.gtg11acuz {
  stop-color: var(--svg-color--ca3131, #CA3131);
}

.gw829ac-g {
  stop-color: var(--svg-color--af4e5a, #AF4E5A);
  stop-opacity: 0;
}

.hbgggmbdi {
  stop-color: var(--svg-color--d01b57, #D01B57);
}

.jej38c2zf {
  width: 4.133px;
  height: 1.195px;
  x: 1.851px;
  y: 27.914px;
  rx: 0.598px;
}

.jrtjj9bpr {
  stop-color: var(--svg-color--ff184e, #FF184E);
}

.kau4zxbdw {
  stop-color: var(--svg-color--ff184e, #FF184E);
  stop-opacity: 0;
}

.kp81rabeu {
  stop-color: var(--svg-color--ff5a5a, #FF5A5A);
}

.lfhmp4r9d {
  width: 4.133px;
  height: 1.195px;
  x: 1.851px;
  y: 24.102px;
  rx: 0.598px;
}

.m4m38ob0c {
  stop-color: var(--svg-color--9a3657, #9A3657);
}

.n0xvj6lry {
  stop-color: var(--svg-color--ad394b, #AD394B);
}

.nmfn8rqzk {
  stop-color: var(--svg-color--ff5a5a, #FF5A5A);
  stop-opacity: 0;
}

.o6f9dsugp {
  stop-color: var(--svg-color--de1c32, #DE1C32);
}

.opi5e4blu {
  width: 4.133px;
  height: 1.195px;
  x: 1.851px;
  y: 22.063px;
  rx: 0.598px;
}

.p0xohyb7n {
  stop-color: var(--svg-color--ff5c87, #FF5C87);
  stop-opacity: 0;
}

.pobhhxbow {
  stop-color: var(--svg-color--d52297, #D52297);
}

.qvr0edcrn {
  stop-color: var(--svg-color--ed1c75, #ED1C75);
  stop-opacity: 0;
}

.s_-3q8sgh {
  stop-color: var(--svg-color--ed1c75, #ED1C75);
}

.smhw9mbxl {
  stop-color: var(--svg-color--ff5c87, #FF5C87);
}

.t1fwi9bjc {
  stop-color: var(--svg-color--af4e5a, #AF4E5A);
}

.t1uir7drl {
  stop-color: var(--svg-color--f93768, #F93768);
  stop-opacity: 0;
}

.va4hins_k {
  stop-color: var(--svg-color--f22b61, #F22B61);
}

.wrfdem4qe {
  stop-color: var(--svg-color--f93768, #F93768);
}

.xgrez327d {
  stop-color: var(--svg-color--ad394b, #AD394B);
  stop-opacity: 0;
}

.xvzju5bhv {
  stop-color: var(--svg-color--e4345a, #E4345A);
}

.y-u5ps6fr {
  width: 4.133px;
  height: 1.195px;
  x: 1.851px;
  y: 26.039px;
  rx: 0.598px;
}

.y09u65bga {
  stop-color: var(--svg-color--e4345a, #E4345A);
  stop-opacity: 0;
}

.yxjpyw7lq {
  stop-color: var(--svg-color--be364b, #BE364B);
  stop-opacity: 0;
}

.z8g2son8j {
  stop-color: var(--svg-color--ab4550, #AB4550);
}

.zxo8yfr-q {
  d: path("M3.984 22.055c-.146 1.157-.364 3.4-.324 7.14c.004.43.353.78.784.773c7.564-.131 13.728-3.892 15.376-5.585l-9.656-4.149c-1.345.46-3.638.743-5.231.821c-.478.024-.876.418-.95 1");
}

</style>
