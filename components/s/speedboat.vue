<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jqggjmb8p"/><path class="lnd1a260v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:speedboat" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jqggjmb8p {
  d: path("M2.75 12.75h12.5l6-2.25l-1.95 5.2a2 2 0 0 1-1.87 1.3H7.4a3 3 0 0 1-2.6-1.5Z");
}

.lnd1a260v {
  d: path("m9.09 12.26l2.82-4.02q.34-.49.94-.49h.8q.6 0 .48.59l-.76 3.82q-.12.59-.72.59h-3.3q-.6 0-.26-.49M2.75 20h5m2.75 0h8.25M5 17.25H2.75");
}

</style>
