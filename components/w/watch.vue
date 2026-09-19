<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><rect fill="url(#ikKv1ad)" class="gzwrwobio"/><rect fill="url(#i2E1e9b)" class="gzwrwobio"/><rect fill="url(#iY6j04c)" class="gzwrwobio"/><rect fill="url(#ivH0YSJ)" class="t7mp9ibha"/><rect fill="url(#ioKoSRc)" class="t7mp9ibha"/><rect fill="url(#iio5I8d)" class="t7mp9ibha"/><rect fill="url(#iGSHN9d)" class="t7mp9ibha"/><rect fill="url(#iRp42II)" class="t7mp9ibha"/><rect fill="url(#ie2LvTr)" class="t7mp9ibha"/><circle fill="url(#i3Ksbld)" class="lt6otgbmt"/><g filter="url(#iNvDOyc)"><path fill="url(#iVoWsud)" class="e8cy20bpp"/></g><g filter="url(#iL5ySAN)"><path fill="url(#i2jQPFe)" clip-rule="evenodd" class="n1u1r7bpm"/></g><rect fill="url(#if6cybb)" class="wnh7aucmw"/><rect fill="url(#ieRjgLK)" transform="rotate(50.006 16 15.054)" class="unrff_b6a"/><circle fill="url(#iQ7p6Gb)" class="dp3d86xgt"/><defs><linearGradient id="iY6j04c" x1="27.406" x2="28.453" y1="13.72" y2="14.453" gradientUnits="userSpaceOnUse"><stop class="r85bjxb0b"/><stop offset="1" class="bz1fp8bhr"/></linearGradient><linearGradient id="ivH0YSJ" x1="16" x2="16" y1="2" y2="30" gradientUnits="userSpaceOnUse"><stop class="f40usxuqg"/><stop offset="1" class="li092tb4r"/></linearGradient><linearGradient id="ioKoSRc" x1="23.563" x2="20.75" y1="14.546" y2="14.546" gradientUnits="userSpaceOnUse"><stop class="fxhifpt1m"/><stop offset="1" class="d3wgnobhu"/></linearGradient><linearGradient id="iio5I8d" x1="9.313" x2="14.688" y1=".672" y2="5.797" gradientUnits="userSpaceOnUse"><stop class="jfugm0nof"/><stop offset="1" class="avgrnibdp"/></linearGradient><linearGradient id="iGSHN9d" x1="9" x2="10.625" y1="18.422" y2="18.422" gradientUnits="userSpaceOnUse"><stop class="t46jnubjk"/><stop offset="1" class="f1pm-xb_w"/></linearGradient><linearGradient id="iRp42II" x1="9.938" x2="11.625" y1="31.422" y2="25.859" gradientUnits="userSpaceOnUse"><stop class="hgpmq5b1t"/><stop offset="1" class="qq1wiwb0e"/></linearGradient><linearGradient id="ie2LvTr" x1="17.049" x2="17.049" y1="30.275" y2="29.358" gradientUnits="userSpaceOnUse"><stop class="o4ggfxbgt"/><stop offset="1" class="zhp2y247o"/></linearGradient><linearGradient id="iVoWsud" x1="16.976" x2="12.274" y1="8.835" y2="19.589" gradientUnits="userSpaceOnUse"><stop class="rct4yvbrn"/><stop offset="1" class="wwvqhy92m"/></linearGradient><linearGradient id="i2jQPFe" x1="23.75" x2="10.375" y1="6.797" y2="22.234" gradientUnits="userSpaceOnUse"><stop class="upqrgacwi"/><stop offset="1" class="ddyjb6bzi"/></linearGradient><linearGradient id="if6cybb" x1="15.323" x2="16.881" y1="12.034" y2="12.034" gradientUnits="userSpaceOnUse"><stop class="q5pauvbow"/><stop offset="1" class="zniha4b1z"/></linearGradient><linearGradient id="ieRjgLK" x1="16.85" x2="16.806" y1="16.832" y2="21.605" gradientUnits="userSpaceOnUse"><stop class="q5pauvbow"/><stop offset="1" class="zniha4b1z"/></linearGradient><radialGradient id="ikKv1ad" cx="0" cy="0" r="1" gradientTransform="matrix(-2.17807 2.57932 -3.57188 -3.01623 29.62 14.952)" gradientUnits="userSpaceOnUse"><stop class="yqq6yhb_s"/><stop offset="1" class="hdjg581xz"/></radialGradient><radialGradient id="i2E1e9b" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.21629 -.38212 0 29.105 14.818)" gradientUnits="userSpaceOnUse"><stop class="n-6r3v2rv"/><stop offset="1" class="baviybb9z"/></radialGradient><radialGradient id="i3Ksbld" cx="0" cy="0" r="1" gradientTransform="matrix(0 9 -9 0 16 16)" gradientUnits="userSpaceOnUse"><stop offset=".901" class="duaow_uvo"/><stop offset="1" class="welyum_dn"/></radialGradient><radialGradient id="iQ7p6Gb" cx="0" cy="0" r="1" gradientTransform="rotate(111.124 3.325 13.364)scale(2.7455)" gradientUnits="userSpaceOnUse"><stop offset=".701" class="u5hgzoblm"/><stop offset="1" class="dstyr73px"/></radialGradient><filter id="iNvDOyc" width="7.789" height="13.03" x="9.937" y="8.085" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_13286" stdDeviation=".375"/></filter><filter id="iL5ySAN" width="24.35" height="24.15" x="3.85" y="4" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.607843 0 0 0 0 0.615686 0 0 0 0 0.729412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_13286"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.894118 0 0 0 0 0.898039 0 0 0 0 0.968627 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_13286" result="effect2_innerShadow_18_13286"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:watch" /></template>
<style>
.avgrnibdp {
  stop-color: var(--svg-color--596fc7, #596FC7);
  stop-opacity: 0;
}

.baviybb9z {
  stop-color: var(--svg-color--5cc2ff, #5CC2FF);
  stop-opacity: 0;
}

.bz1fp8bhr {
  stop-color: var(--svg-color--5190d7, #5190D7);
  stop-opacity: 0;
}

.d3wgnobhu {
  stop-color: var(--svg-color--4cb2ff, #4CB2FF);
  stop-opacity: 0;
}

.ddyjb6bzi {
  stop-color: var(--svg-color--bdc2ff, #BDC2FF);
}

.dp3d86xgt {
  cx: 16px;
  cy: 16px;
  r: 1.639px;
}

.dstyr73px {
  stop-color: var(--svg-color--caa742, #CAA742);
}

.duaow_uvo {
  stop-color: var(--svg-color--50369c, #50369C);
}

.e8cy20bpp {
  d: path("M14.66 9.512a.677.677 0 1 1 1.354 0v5.412a1.64 1.64 0 1 1-1.433 2.949L11.8 20.207a.677.677 0 0 1-.87-1.038l2.815-2.362a1.64 1.64 0 0 1 .915-1.883z");
}

.f1pm-xb_w {
  stop-color: var(--svg-color--444a9e, #444A9E);
  stop-opacity: 0;
}

.f40usxuqg {
  stop-color: var(--svg-color--3b96e6, #3B96E6);
}

.ft5dv1b6b {
  fill: none;
}

.fxhifpt1m {
  stop-color: var(--svg-color--4cb2ff, #4CB2FF);
}

.gzwrwobio {
  width: 2.866px;
  height: 3.812px;
  x: 26.335px;
  y: 13.72px;
  rx: 0.6px;
}

.hdjg581xz {
  stop-color: var(--svg-color--1f6dff, #1F6DFF);
}

.hgpmq5b1t {
  stop-color: var(--svg-color--2845ff, #2845FF);
}

.jfugm0nof {
  stop-color: var(--svg-color--596fc7, #596FC7);
}

.li092tb4r {
  stop-color: var(--svg-color--256aff, #256AFF);
}

.lt6otgbmt {
  cx: 16px;
  cy: 16px;
  r: 9px;
}

.n-6r3v2rv {
  stop-color: var(--svg-color--5cc2ff, #5CC2FF);
}

.n1u1r7bpm {
  fill-rule: evenodd;
  d: path("M16 28c6.627 0 12-5.373 12-12S22.627 4 16 4S4 9.373 4 16s5.373 12 12 12m0-3a9 9 0 1 0 0-18a9 9 0 0 0 0 18");
}

.o4ggfxbgt {
  stop-color: var(--svg-color--5d7aff, #5D7AFF);
}

.q5pauvbow {
  stop-color: var(--svg-color--d6d8ff, #D6D8FF);
}

.qq1wiwb0e {
  stop-color: var(--svg-color--2845ff, #2845FF);
  stop-opacity: 0;
}

.r85bjxb0b {
  stop-color: var(--svg-color--5190d7, #5190D7);
}

.rct4yvbrn {
  stop-color: var(--svg-color--352260, #352260);
}

.t46jnubjk {
  stop-color: var(--svg-color--444a9e, #444A9E);
}

.t7mp9ibha {
  width: 14px;
  height: 28px;
  x: 9px;
  y: 2px;
  rx: 1px;
}

.u5hgzoblm {
  stop-color: var(--svg-color--ddbd3d, #DDBD3D);
}

.unrff_b6a {
  width: 1.354px;
  height: 6.431px;
  x: 16px;
  y: 15.054px;
  rx: 0.677px;
}

.upqrgacwi {
  stop-color: var(--svg-color--cccff7, #CCCFF7);
}

.welyum_dn {
  stop-color: var(--svg-color--3b2862, #3B2862);
}

.wnh7aucmw {
  width: 1.354px;
  height: 7.233px;
  x: 15.323px;
  y: 8.417px;
  rx: 0.677px;
}

.wwvqhy92m {
  stop-color: var(--svg-color--39268e, #39268E);
}

.yqq6yhb_s {
  stop-color: var(--svg-color--28a1fa, #28A1FA);
}

.zhp2y247o {
  stop-color: var(--svg-color--5d7aff, #5D7AFF);
  stop-opacity: 0;
}

.zniha4b1z {
  stop-color: var(--svg-color--e7eaff, #E7EAFF);
}

</style>
