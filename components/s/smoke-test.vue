<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="gmm65hbdp"/><path class="dyxr40bml"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:smoke-test" /></template>
<style>
.dyxr40bml {
  d: path("M7.25 14.5a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0Zm8.25-7c-1.75-1.5 1.75-3 0-5m4.5 7c-1.75-1.5 1.75-3 0-5");
}

.gmm65hbdp {
  d: path("m8.105 9.699l.155-2.088h2.48l.155 2.088l2.066 1.192l1.886-.909l1.239 2.147l-1.73 1.178v2.386l1.73 1.178l-1.239 2.147l-1.886-.909l-2.066 1.192l-.155 2.088H8.26l-.155-2.088l-2.066-1.192l-1.886.909l-1.239-2.147l1.73-1.178v-2.386l-1.73-1.178l1.239-2.147l1.886.909Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
