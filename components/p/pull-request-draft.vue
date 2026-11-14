<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cetoqjbkf"/><path class="s9les-b-f"/><path class="sqynocblz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pull-request-draft" /></template>
<style>
.cetoqjbkf {
  d: path("M4 5.75V5a2.5 2.5 0 0 1 2.5-2.5h.75m9.5 0h.75A2.5 2.5 0 0 1 20 5v.75m0 12.5V19a2.5 2.5 0 0 1-2.5 2.5h-.75m-9.5 0H6.5A2.5 2.5 0 0 1 4 19v-.75M10.5 2.5h3m-3 19h3M4 9.25v5.5m16-5.5v5.5M9 6v12m4-2a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.s9les-b-f {
  d: path("M15 14v-4a2.5 2.5 0 0 0-2.5-2.5H12");
}

.sqynocblz {
  d: path("M13.5 6L12 7.5L13.5 9");
}

</style>
