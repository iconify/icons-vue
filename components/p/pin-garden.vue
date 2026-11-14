<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="l7hk0t9tq"/><path class="u96rjlarj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pin-garden" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l7hk0t9tq {
  d: path("M7.5 3.5L9.75 6L12 3l2.25 3l2.25-2.5v5a4.5 4.5 0 0 1-9 0ZM12 13v8.5m0-2c-3.5 0-6-2.25-6-5.5c3.5 0 6 2.25 6 5.5");
}

.u96rjlarj {
  d: path("M12 17.5c0-3.25 2.5-5.5 6-5.5c0 3.25-2.5 5.5-6 5.5");
}

</style>
