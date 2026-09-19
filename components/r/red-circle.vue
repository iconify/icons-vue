<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#ixdL3qP)" class="vi_4d-bfd"/><path fill="url(#iNDFp1p)" class="vi_4d-bfd"/><path fill="url(#iATDPfc)" class="vi_4d-bfd"/><path fill="url(#igdxbye)" class="vi_4d-bfd"/><path fill="url(#iclb7Pt)" class="vi_4d-bfd"/><defs><radialGradient id="ixdL3qP" cx="0" cy="0" r="1" gradientTransform="rotate(130.168 9.936 9.935)scale(27.8086)" gradientUnits="userSpaceOnUse"><stop offset=".232" class="i0zc3hccw"/><stop offset="1" class="v8wq6nkkt"/></radialGradient><radialGradient id="iATDPfc" cx="0" cy="0" r="1" gradientTransform="rotate(136.38 10.067 10.264)scale(14.6767 15.816)" gradientUnits="userSpaceOnUse"><stop offset=".179" class="duap8dbut"/><stop offset="1" class="jl-v-pc5r"/></radialGradient><radialGradient id="igdxbye" cx="0" cy="0" r="1" gradientTransform="matrix(-19.25 0 0 -20 20.249 16)" gradientUnits="userSpaceOnUse"><stop offset=".62" class="f0ncnzx2v"/><stop offset=".951" class="fa7ci1b-y"/></radialGradient><radialGradient id="iclb7Pt" cx="0" cy="0" r="1" gradientTransform="matrix(0 21 -23.3208 0 15.757 9)" gradientUnits="userSpaceOnUse"><stop offset=".863" class="ajq4m8bjr"/><stop offset="1" class="jis_d-bbj"/><stop offset="1" class="s33myrbay"/></radialGradient><linearGradient id="iNDFp1p" x1="15.757" x2="15.757" y1="2" y2="8.5" gradientUnits="userSpaceOnUse"><stop class="s--dzvufl"/><stop offset="1" class="g7o0d0bbp"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:red-circle" /></template>
<style>
.ajq4m8bjr {
  stop-color: var(--svg-color--b83c5a, #B83C5A);
  stop-opacity: 0;
}

.duap8dbut {
  stop-color: var(--svg-color--ff6180, #FF6180);
}

.f0ncnzx2v {
  stop-color: var(--svg-color--b73e4b, #B73E4B);
  stop-opacity: 0;
}

.fa7ci1b-y {
  stop-color: var(--svg-color--d48387, #D48387);
}

.ft5dv1b6b {
  fill: none;
}

.g7o0d0bbp {
  stop-color: var(--svg-color--ef4b5e, #EF4B5E);
  stop-opacity: 0;
}

.i0zc3hccw {
  stop-color: var(--svg-color--f24756, #F24756);
}

.jis_d-bbj {
  stop-color: var(--svg-color--b83c5a, #B83C5A);
}

.jl-v-pc5r {
  stop-color: var(--svg-color--e5364a, #E5364A);
  stop-opacity: 0;
}

.s--dzvufl {
  stop-color: var(--svg-color--dd4577, #DD4577);
}

.s33myrbay {
  stop-color: var(--svg-color--ac4064, #AC4064);
}

.v8wq6nkkt {
  stop-color: var(--svg-color--b22945, #B22945);
}

.vi_4d-bfd {
  d: path("M29.757 16c0 7.732-6.268 14-14 14s-14-6.268-14-14s6.268-14 14-14s14 6.268 14 14");
}

</style>
