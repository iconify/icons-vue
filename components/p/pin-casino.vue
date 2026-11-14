<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ybmpp08xl"/><path class="d6r8vbbwp"/><path class="rocnkmbpf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pin-casino" /></template>
<style>
.d6r8vbbwp {
  fill: currentColor;
  d: path("m6.48 12.555l2.232 2.081l-1.192 2.809l-2.232-2.081Z");
}

.rocnkmbpf {
  d: path("M15.75 4.5h.01M19 7.75h.01M19 22l-2.25-2.75a2.75 2.75 0 1 1 4.5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ybmpp08xl {
  d: path("m1.247 9.578l8.803-1.872l2.703 12.716l-8.803 1.872ZM13.75 2.5H21v7.25h-7.25Z");
}

</style>
