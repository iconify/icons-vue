<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="y1paqob_g"/><path class="y8xknhx_a"/><path class="bxmaetxyp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:pound-line-duotone" /></template>
<style>
.bxmaetxyp {
  d: path("M8.75 12.5H13.25");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y1paqob_g {
  d: path("M22 12C22 17.5228 17.5228 22 12 22C6.4772 22 2 17.5228 2 12C2 6.4772 6.4772 2 12 2C17.5228 2 22 6.4772 22 12Z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.y8xknhx_a {
  d: path("M15 9.25C15 8.0074 13.9926 7 12.75 7C11.5074 7 10.5 8.0074 10.5 9.25V14.5C10.5 16 9.8 17 8.75 17H15.25");
}

</style>
