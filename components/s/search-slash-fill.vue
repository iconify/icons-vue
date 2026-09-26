<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="puvdzn6rg"/><path class="xexl16bfr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:search-slash-fill" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.puvdzn6rg {
  fill: currentColor;
  d: path("M18 10C18 14.4183 14.4183 18 10 18C5.5817 18 2 14.4183 2 10C2 5.5817 5.5817 2 10 2C14.4183 2 18 5.5817 18 10ZM12.8284 8.5858C13.0159 8.3983 13.1213 8.1439 13.1213 7.8787C13.1213 7.3264 12.6736 6.8787 12.1213 6.8787C11.8561 6.8787 11.6017 6.9841 11.4142 7.1716L7.1716 11.4142C6.9841 11.6017 6.8787 11.8561 6.8787 12.1213C6.8787 12.6736 7.3264 13.1213 7.8787 13.1213C8.1439 13.1213 8.3983 13.0159 8.5858 12.8284L12.8284 8.5858Z");
  stroke: none;
}

.xexl16bfr {
  d: path("M15 15L21 21");
}

</style>
