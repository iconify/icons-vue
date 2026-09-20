<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGShQ4bbjL)" class="iip_x3xmm"/><defs><linearGradient id="SVGShQ4bbjL" x1="12" x2="12" y1="3" y2="21" gradientUnits="userSpaceOnUse"><stop class="p4q25z16a"/><stop offset="1" class="jcsppz9dw"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:zap" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.iip_x3xmm {
  d: path("M13.152 9.188V3.71c.027-.135-.024-.456-.444-.653c-.366-.172-.765.083-.885.247c-1.825 2.917-5.233 9.051-5.366 9.36c-.169.389-.054.631.106.81c.119.134.403.214.555.214h3.705l-.79 6.7c.01.155.14.49.564.592c.425.101.717-.205.81-.37l6.057-10.25c.088-.135.27-.494.076-.81a.78.78 0 0 0-.7-.362z");
}

.jcsppz9dw {
  stop-color: var(--svg-color--50c0fe, #50c0fe);
}

.p4q25z16a {
  stop-color: var(--svg-color--087ffe, #087ffe);
}

</style>
