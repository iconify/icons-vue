<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="pn45yjb-t"/><path class="s2o1_jbxy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:patient-monitor" /></template>
<style>
.pn45yjb-t {
  d: path("M3.5 3.5h17v11h-17Zm8.5 11V18m-5 3h10");
}

.s2o1_jbxy {
  d: path("M6 9h2l1.25-2.25l1.75 4.5L12 9m3-2h3m-3 4h3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
