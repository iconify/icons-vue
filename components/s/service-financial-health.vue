<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="pqc1gibky"/><path class="zibzysaae"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:service-financial-health" /></template>
<style>
.pqc1gibky {
  d: path("M12 20.5s-8.5-5-8.5-11a4.5 4.5 0 0 1 8.5-2a4.5 4.5 0 0 1 8.5 2c0 6-8.5 11-8.5 11Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zibzysaae {
  d: path("M7 12h2.5L11 9l2 6l1.5-3H17");
}

</style>
