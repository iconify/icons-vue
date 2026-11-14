<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="y8k_t7b7m"/><path class="kycmb-b1g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:repo-actions" /></template>
<style>
.kycmb-b1g {
  d: path("m15.5 14l6.5 4l-6.5 4Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y8k_t7b7m {
  d: path("m3 8.5l2.5-5h11l2.5 5M12.7 19H3V8.5h16v4.4m-8-9.4v5");
}

</style>
