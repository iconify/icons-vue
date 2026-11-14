<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jzgsjfb-y"/><path class="ccb2ft52c"/><path class="nh2v95bix"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:stock-expiry-check" /></template>
<style>
.ccb2ft52c {
  d: path("m3 7l9 4.5L21 7m-9 4.5v10M7.5 4.75l9 4.5M15 14.5h6m-6 7h6m-5-7v1l4 5v1");
}

.jzgsjfb-y {
  d: path("m12.201 21.4l-.201.1L3 17V7l9-4.5L21 7v4.738");
}

.nh2v95bix {
  d: path("M20 14.5v1l-4 5v1");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
