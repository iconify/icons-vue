<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="d_1vu593t"/><path class="ub1jg5_1h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:widget-remove" /></template>
<style>
.d_1vu593t {
  d: path("M12.8 21.5H2.5v-19h19v10.3m-19-4.3h19M10 4.5h.01m1.99 0h.01m1.99 0h.01M10 6.5h.01m1.99 0h.01m1.99 0h.01");
}

.ub1jg5_1h {
  d: path("M14.5 18a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0Zm1.75 0h3.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
