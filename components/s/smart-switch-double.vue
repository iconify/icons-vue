<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="kb6_hbjfr"/><path class="mq_i3sbyh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:smart-switch-double" /></template>
<style>
.kb6_hbjfr {
  d: path("M11.1 16.5H2.5v-14h19v11.2");
}

.mq_i3sbyh {
  d: path("M6 6h4.5v7H6Zm11 7h-3.5V6H18v6.9m-3.75 4.35a5.3 5.3 0 0 1 7.5 0M16 19a2.83 2.83 0 0 1 4 0m-2 2h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
