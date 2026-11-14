<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="or2w3lbjj"/><path class="l_y-qwucx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:repotting" /></template>
<style>
.l_y-qwucx {
  d: path("M7.5 10h9L15 18H9Zm4.5 0V5m0 2.25C12 5.25 10.5 4 8 4c0 2 1.5 3.25 4 3.25M12 6c0-2 1.5-3.25 4-3.25c0 2-1.5 3.25-4 3.25");
}

.or2w3lbjj {
  d: path("m4 12l2 9.5h12l2-9.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
