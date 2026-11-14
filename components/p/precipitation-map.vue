<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ihjl_81jn"/><path class="snipgzq-n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:precipitation-map" /></template>
<style>
.ihjl_81jn {
  d: path("M12.073 19.874L8.5 18.5l-6 2.5V5.5l6-2.5L15 5.5L21 3v9.936M8.5 3v15.5m6.5-13v7.4");
}

.snipgzq-n {
  d: path("m18 13.5l2.5 3.5a3 3 0 1 1-5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
