<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ow9w0pbfq"/><path class="r2wmmibhb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:remote-team" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ow9w0pbfq {
  d: path("M5.125 3h13.75A2.625 2.625 0 0 1 21.5 5.625v8.75A2.625 2.625 0 0 1 18.875 17H5.125A2.625 2.625 0 0 1 2.5 14.375v-8.75A2.625 2.625 0 0 1 5.125 3M12 17v3.5m-4 0h8M12 3v14m-9.5-7h19");
}

.r2wmmibhb {
  d: path("M6 6.5a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0m9.5 0a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0m-9.5 7a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0m9.5 0a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0");
}

</style>
