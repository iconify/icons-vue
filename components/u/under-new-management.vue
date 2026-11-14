<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ud9x5e-9d"/><path class="u5ffw2b3u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:under-new-management" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.u5ffw2b3u {
  d: path("M3 9a3 3 0 0 0 6 0a3 3 0 0 0 6 0a3 3 0 0 0 6 0M6.5 20.5v-5h4v5m7.192-4.692l.204.49a1.5 1.5 0 0 0 .806.806l.49.204a.479.479 0 0 1 0 .884l-.49.204a1.5 1.5 0 0 0-.806.806l-.204.49a.479.479 0 0 1-.884 0l-.204-.49a1.5 1.5 0 0 0-.806-.806l-.49-.204a.479.479 0 0 1 0-.884l.49-.204a1.5 1.5 0 0 0 .806-.806l.204-.49a.479.479 0 0 1 .884 0M21 14v2m-1-1h2");
}

.ud9x5e-9d {
  d: path("m3 9l1.5-5h15L21 9m-1.5 2v.6m-15-.6v9.5H12");
}

</style>
