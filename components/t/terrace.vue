<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dt5ygobkt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:terrace" /></template>
<style>
.dt5ygobkt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 10.5h17a1 1 0 0 1 1 1a1 1 0 0 1-1 1h-17a1 1 0 0 1-1-1a1 1 0 0 1 1-1m-1 11h19M6 12.5za1.25 1.25 0 0 1 1.25 1.25v6.5A1.25 1.25 0 0 1 6 21.5a1.25 1.25 0 0 1-1.25-1.25v-6.5A1.25 1.25 0 0 1 6 12.5m6 0za1.25 1.25 0 0 1 1.25 1.25v6.5A1.25 1.25 0 0 1 12 21.5a1.25 1.25 0 0 1-1.25-1.25v-6.5A1.25 1.25 0 0 1 12 12.5m6 0za1.25 1.25 0 0 1 1.25 1.25v6.5A1.25 1.25 0 0 1 18 21.5a1.25 1.25 0 0 1-1.25-1.25v-6.5A1.25 1.25 0 0 1 18 12.5M10.82 7h2.36a1.373 1.373 0 0 1 1.32 1.75l-.189.662a1.5 1.5 0 0 1-1.442 1.088h-1.738a1.5 1.5 0 0 1-1.442-1.088L9.5 8.75A1.373 1.373 0 0 1 10.82 7M12 7c0-2.5-1.5-4-3.5-4.5c0 2 1.5 4 3.5 4.5m0 0c0-2.5 1.5-4 3.5-4.5c0 2-1.5 4-3.5 4.5");
}

</style>
