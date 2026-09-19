<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iG4jaEd)"><path fill="url(#i3Krkbd)" class="uknyphb7w"/></g><g filter="url(#iPO6uXb)"><path fill="url(#i5Jrp4c)" class="yy6bf-bes"/></g><path fill="url(#iPzio7b)" class="fscg_1pdt"/><circle fill="url(#ikEqwKe)" class="yul8oeaxx"/><g filter="url(#irSYtqd)"><circle class="qiugn8bbv"/></g><path fill="url(#ir4ryfd)" class="yy6bf-bes"/><g filter="url(#iUcEqUq)"><path fill="url(#iqVQqhJ)" class="ouzjvgb7w"/></g><path fill="url(#ir5Yrwb)" class="ojl8vybfb"/><circle fill="url(#i7tuYfd)" transform="matrix(0 -1 -1 0 27.5 25.5)" class="cozuc-3vc"/><g filter="url(#iMswUee)"><circle transform="matrix(0 -1 -1 0 25.75 27.25)" class="ad4hwbbrx"/></g><g filter="url(#iB8i52c)"><path fill="url(#i8bptgc)" class="itqojpbfn"/></g><g filter="url(#iRRaTNc)"><path class="kjpomubzg"/></g><path fill="url(#iQCIt9c)" class="itqojpbfn"/><g filter="url(#icVxTbd)"><path fill="url(#iXYnOzb)" class="nyt5iebsw"/></g><path fill="url(#iruMFMc)" class="nyt5iebsw"/><path fill="url(#izgrRrV)" clip-rule="evenodd" class="z6tdbb0nx"/><g filter="url(#iSiIiXd)" class="mc2zb0bvp"><rect class="ng-7n1bze"/></g><g filter="url(#iOk4YKt)" class="mc2zb0bvp"><rect class="u5flebc-u"/></g><g filter="url(#i9QNYHR)" class="q-q44lbln"><rect class="sxdbl4dzh"/></g><path fill="url(#i2HwtBB)" clip-rule="evenodd" class="tdxb60u0y"/><path fill="url(#iiHzstL)" class="z2xi_dygu"/><path fill="url(#iv6gwlQ)" class="qzcm7zb3n"/><path fill="url(#ieeFone)" class="mllthmb5n"/><g filter="url(#iONAcDc)"><ellipse class="exhut8bfe"/></g><g filter="url(#iK0yzpW)"><circle class="s539gbb-l"/></g><defs><filter id="iG4jaEd" width="9.75" height="10.25" x="20.5" y="1.75" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.748624 0 0 0 0 0.67744 0 0 0 0 0.811898 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_31_1457"/></filter><filter id="iPO6uXb" width="9.75" height="10.25" x="2" y="1.75" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.778564 0 0 0 0 0.701532 0 0 0 0 0.771562 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_31_1457"/></filter><filter id="irSYtqd" width="4.5" height="4.5" x="2.5" y="4" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_31_1457" stdDeviation=".5"/></filter><filter id="iUcEqUq" width="10.25" height="9.75" x="20" y="20.25" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.798011 0 0 0 0 0.68505 0 0 0 0 0.882731 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_31_1457"/></filter><filter id="iMswUee" width="4.5" height="4.5" x="23.5" y="25" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_31_1457" stdDeviation=".5"/></filter><filter id="iB8i52c" width="11.25" height="11.25" x="2" y="18.75" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.789604 0 0 0 0 0.632853 0 0 0 0 0.886898 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_31_1457"/></filter><filter id="iRRaTNc" width="5.707" height="5.707" x="21.146" y="5.646" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_31_1457" stdDeviation=".5"/></filter><filter id="icVxTbd" width="21" height="20.96" x="6" y="5.04" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-1"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.801456 0 0 0 0 0.658291 0 0 0 0 0.911898 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_31_1457"/></filter><filter id="iSiIiXd" width="3" height="5" x="11.5" y="21.5" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_31_1457" stdDeviation=".5"/></filter><filter id="iOk4YKt" width="3" height="6" x="14.5" y="20.5" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_31_1457" stdDeviation=".5"/></filter><filter id="i9QNYHR" width="3.75" height="7" x="18" y="19.5" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_31_1457" stdDeviation=".5"/></filter><filter id="iONAcDc" width="4.5" height="5.5" x="24" y="1.5" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_31_1457" stdDeviation=".5"/></filter><filter id="iK0yzpW" width="4" height="4" x="26.5" y="4" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_31_1457" stdDeviation=".5"/></filter><radialGradient id="i3Krkbd" cx="0" cy="0" r="1" gradientTransform="matrix(7.02133 0 0 7.44313 27.325 4.778)" gradientUnits="userSpaceOnUse"><stop class="zef1df6sm"/><stop offset=".64" class="al4rvobhd"/><stop offset=".989" class="f2hqs_bjw"/></radialGradient><radialGradient id="ikEqwKe" cx="0" cy="0" r="1" gradientTransform="matrix(-2 1.5 -1.5 -2 8 3.5)" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="x0pyvtb0x"/></radialGradient><radialGradient id="i7tuYfd" cx="0" cy="0" r="1" gradientTransform="matrix(-2 1.5 -1.5 -2 4 1.5)" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="x0pyvtb0x"/></radialGradient><radialGradient id="i8bptgc" cx="0" cy="0" r="1" gradientTransform="matrix(4.94852 -4.9009 4.9733 5.02163 5.052 26.9)" gradientUnits="userSpaceOnUse"><stop class="so-4y0bbu"/><stop offset=".989" class="d7i7lkb7g"/></radialGradient><radialGradient id="iXYnOzb" cx="0" cy="0" r="1" gradientTransform="rotate(125.602 6.865 10.273)scale(18.4048 18.4188)" gradientUnits="userSpaceOnUse"><stop offset=".213" class="x2urj1m9s"/><stop offset=".743" class="fskayccxp"/></radialGradient><radialGradient id="izgrRrV" cx="0" cy="0" r="1" gradientTransform="matrix(0 2 -.96019 0 14.5 24)" gradientUnits="userSpaceOnUse"><stop class="ddi0stb3y"/><stop offset="1" class="a5qghibku"/></radialGradient><radialGradient id="i2HwtBB" cx="0" cy="0" r="1" gradientTransform="matrix(0 2 -.96019 0 17.5 24)" gradientUnits="userSpaceOnUse"><stop class="ddi0stb3y"/><stop offset="1" class="a5qghibku"/></radialGradient><radialGradient id="iiHzstL" cx="0" cy="0" r="1" gradientTransform="matrix(2.90825 -3.29563 3.91973 3.45899 9.762 16.935)" gradientUnits="userSpaceOnUse"><stop offset=".445" class="vu5gmnbri"/><stop offset="1" class="j0k00598e"/></radialGradient><radialGradient id="iv6gwlQ" cx="0" cy="0" r="1" gradientTransform="rotate(-49.102 28.646 -13.664)scale(4.36001 5.17278)" gradientUnits="userSpaceOnUse"><stop offset=".445" class="vu5gmnbri"/><stop offset="1" class="j0k00598e"/></radialGradient><radialGradient id="ieeFone" cx="0" cy="0" r="1" gradientTransform="matrix(.89486 -1.1984 1.37733 1.02846 15.696 19.249)" gradientUnits="userSpaceOnUse"><stop offset=".445" class="vu5gmnbri"/><stop offset="1" class="j0k00598e"/></radialGradient><linearGradient id="i5Jrp4c" x1="9" x2="3.5" y1="2" y2="10" gradientUnits="userSpaceOnUse"><stop class="xihay-lnh"/><stop offset=".566" class="unbfywqjz"/><stop offset=".988" class="czmti4bbd"/></linearGradient><linearGradient id="iPzio7b" x1="9.5" x2="8.5" y1="8" y2="9" gradientUnits="userSpaceOnUse"><stop class="besy-t6nf"/><stop offset="1" class="usor18bls"/></linearGradient><linearGradient id="ir4ryfd" x1="4.205" x2=".912" y1="6.643" y2="4.996" gradientUnits="userSpaceOnUse"><stop class="wapap0w9p"/><stop offset="1" class="ghiw4qs2h"/></linearGradient><linearGradient id="iqVQqhJ" x1="30" x2="22" y1="23" y2="28.5" gradientUnits="userSpaceOnUse"><stop class="xihay-lnh"/><stop offset=".566" class="fecy02f3z"/><stop offset=".988" class="i8n6zfb-n"/></linearGradient><linearGradient id="ir5Yrwb" x1="24" x2="23" y1="22.5" y2="23.5" gradientUnits="userSpaceOnUse"><stop class="besy-t6nf"/><stop offset="1" class="usor18bls"/></linearGradient><linearGradient id="iQCIt9c" x1="6.5" x2="3" y1="25.5" y2="21" gradientUnits="userSpaceOnUse"><stop class="wapap0w9p"/><stop offset="1" class="ghiw4qs2h"/></linearGradient><linearGradient id="iruMFMc" x1="10.643" x2="3.863" y1="15.307" y2="11.732" gradientUnits="userSpaceOnUse"><stop class="wapap0w9p"/><stop offset="1" class="ghiw4qs2h"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:skull-and-crossbones" /></template>
<style>
.a5qghibku {
  stop-color: var(--svg-color--b29ec2, #B29EC2);
  stop-opacity: 0;
}

.ad4hwbbrx {
  r: 1.25px;
  fill: var(--svg-color--eae0e7, #EAE0E7);
}

.al4rvobhd {
  stop-color: var(--svg-color--e2dce3, #E2DCE3);
}

.besy-t6nf {
  stop-color: var(--svg-color--f0eeef, #F0EEEF);
}

.cozuc-3vc {
  r: 2.5px;
}

.czmti4bbd {
  stop-color: var(--svg-color--cfb4cd, #CFB4CD);
}

.d7i7lkb7g {
  stop-color: var(--svg-color--bda1cb, #BDA1CB);
}

.ddi0stb3y {
  stop-color: var(--svg-color--7a6e85, #7A6E85);
}

.exhut8bfe {
  cx: 26.25px;
  cy: 4.25px;
  fill: var(--svg-color--f7f5f8, #F7F5F8);
  rx: 1.25px;
  ry: 1.75px;
}

.f2hqs_bjw {
  stop-color: var(--svg-color--dad1d1, #DAD1D1);
}

.fecy02f3z {
  stop-color: var(--svg-color--e0d1ee, #E0D1EE);
}

.fscg_1pdt {
  d: path("M6 6.5c.5-.5 2.706-.81 2.706-.81L11.5 8.5l1.5 5s-5.794-5.611-7-7");
}

.fskayccxp {
  stop-color: var(--svg-color--d1bbe0, #D1BBE0);
}

.ft5dv1b6b {
  fill: none;
}

.ghiw4qs2h {
  stop-color: var(--svg-color--ffd099, #FFD099);
}

.i8n6zfb-n {
  stop-color: var(--svg-color--ceb6e1, #CEB6E1);
}

.itqojpbfn {
  d: path("M4.356 27.668c-1.3 0-2.356-1.031-2.356-2.312s1.056-2.322 2.356-2.322c.498 0 .955.15 1.341.41L10.126 19L13 21.833l-4.428 4.444c.304.39.487.87.487 1.4C9.06 28.96 8.003 30 6.703 30a2.34 2.34 0 0 1-2.347-2.332");
}

.j0k00598e {
  stop-color: var(--svg-color--1a1016, #1A1016);
}

.kjpomubzg {
  stroke: var(--svg-color--f1ecf2, #F1ECF2);
  d: path("m25.5 7l-3 3");
}

.mc2zb0bvp {
  opacity: var(--svg-opacity--0-5, 0.5);
}

.mllthmb5n {
  d: path("M16.575 20h-1.15c-.287 0-.499-.33-.4-.642l.211-.726c.107-.377.417-.632.76-.632c.342 0 .644.255.759.623l.22.726c.098.311-.106.651-.4.651");
}

.ng-7n1bze {
  width: 1px;
  height: 3px;
  x: 12.5px;
  y: 22.5px;
  fill: var(--svg-color--fff, #fff);
  rx: 0.5px;
}

.nyt5iebsw {
  d: path("M16 6.04c-5.52 0-10 4.48-10 10c0 3.7 2.01 4.69 5 4.95v3.51a1.5 1.5 0 0 0 1.5 1.5h.06A1.44 1.44 0 0 0 14 24.56V23.5a.5.5 0 0 1 1 0V25a1 1 0 1 0 2 0v-1.5a.5.5 0 0 1 1 0v1.06c0 .795.645 1.44 1.44 1.44h.06a1.5 1.5 0 0 0 1.5-1.5v-3.51c2.99-.25 5-1.25 5-4.95c0-5.53-4.48-10-10-10");
}

.ojl8vybfb {
  d: path("M25.5 26c.5-.5.81-2.706.81-2.706L23.5 20.5l-5-1.5s5.611 5.794 7 7");
}

.ouzjvgb7w {
  d: path("M26.304 23.304L23.5 20.5H20V23l3.304 3.304a2.5 2.5 0 1 0 4.654 1.654a2.5 2.5 0 1 0-1.654-4.654");
}

.q-q44lbln {
  opacity: var(--svg-opacity--0-64, 0.64);
}

.qiugn8bbv {
  cx: 4.75px;
  cy: 6.25px;
  r: 1.25px;
  fill: var(--svg-color--eae0e7, #EAE0E7);
}

.qzcm7zb3n {
  d: path("M24.38 16.773c0 1.806-1.43 2.227-3.19 2.227S18 18.58 18 16.773s1.43-3.273 3.19-3.273c1.76-.01 3.19 1.457 3.19 3.273");
}

.s539gbb-l {
  cx: 28.5px;
  cy: 6px;
  r: 1px;
  fill: var(--svg-color--f6f4f7, #F6F4F7);
}

.so-4y0bbu {
  stop-color: var(--svg-color--d8c5de, #D8C5DE);
}

.sxdbl4dzh {
  width: 1.75px;
  height: 5px;
  x: 19px;
  y: 20.5px;
  fill: var(--svg-color--fff, #fff);
  rx: 0.875px;
}

.tdxb60u0y {
  fill-rule: evenodd;
  d: path("M18.701 25.796c.188-.5.299-1.122.299-1.796c0-1.657-.672-3-1.5-3S16 22.343 16 24c0 .738.133 1.413.354 1.936A1 1 0 0 0 17 25v-1.5a.5.5 0 1 1 1 0v1.06c0 .525.281.985.701 1.236");
}

.u5flebc-u {
  width: 1px;
  height: 4px;
  x: 15.5px;
  y: 21.5px;
  fill: var(--svg-color--fff, #fff);
  rx: 0.5px;
}

.uknyphb7w {
  d: path("M23.304 5.696L20.5 8.5V12H23l3.304-3.304a2.5 2.5 0 1 0 1.654-4.654a2.5 2.5 0 1 0-4.654 1.654");
}

.unbfywqjz {
  stop-color: var(--svg-color--e4d8e0, #E4D8E0);
}

.usor18bls {
  stop-color: var(--svg-color--f3eef0, #F3EEF0);
  stop-opacity: 0;
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.vu5gmnbri {
  stop-color: var(--svg-color--3d2c36, #3D2C36);
}

.wapap0w9p {
  stop-color: var(--svg-color--e5c9c5, #E5C9C5);
  stop-opacity: 0;
}

.x0pyvtb0x {
  stop-color: var(--svg-color--f7f4f6, #F7F4F6);
  stop-opacity: 0;
}

.x2urj1m9s {
  stop-color: var(--svg-color--f2f0f4, #F2F0F4);
}

.xihay-lnh {
  stop-color: var(--svg-color--ece5e6, #ECE5E6);
}

.yul8oeaxx {
  cx: 6.5px;
  cy: 4.5px;
  r: 2.5px;
}

.yy6bf-bes {
  d: path("M8.696 5.696L11.5 8.5V12H9L5.696 8.696a2.5 2.5 0 1 1-1.654-4.654a2.5 2.5 0 1 1 4.654 1.654");
}

.z2xi_dygu {
  d: path("M14 16.778C14 18.58 12.545 19 10.755 19S7.5 18.58 7.5 16.778S8.955 13.5 10.755 13.5S14 14.965 14 16.778");
}

.z6tdbb0nx {
  fill-rule: evenodd;
  d: path("M15.646 25.936c.22-.523.354-1.198.354-1.936c0-1.657-.672-3-1.5-3S13 22.343 13 24c0 .674.111 1.296.299 1.796A1.44 1.44 0 0 0 14 24.56V23.5a.5.5 0 0 1 1 0V25a1 1 0 0 0 .646.936");
}

.zef1df6sm {
  stop-color: var(--svg-color--eae6ec, #EAE6EC);
}

</style>
