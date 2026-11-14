<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jwaw2hb2o"/><path class="lbbooz00z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:spelling-bee" /></template>
<style>
.jwaw2hb2o {
  d: path("M12 7c3.5 0 5.5 2.5 5.5 6c0 4-2.5 7-5.5 7s-5.5-3-5.5-7c0-3.5 2-6 5.5-6Zm-5.25 4.5h10.5m-10.75 4h11");
}

.lbbooz00z {
  d: path("M9.5 7.5C8 5 6 4.5 4.5 5.5c.5 2.5 2.5 3 5 2Zm5 0c1.5-2.5 3.5-3 5-2c-.5 2.5-2.5 3-5 2Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
