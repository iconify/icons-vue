<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="af7iv3n-p"/><path class="iiquwwbvb"/><path class="jnf_2db5t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:stock-outline-thin" /></template>
<style>
.af7iv3n-p {
  d: path("M12 2v2.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.iiquwwbvb {
  d: path("M5 6.5a2 2 0 0 1 2 -2h10a2 2 0 0 1 2 2V16a2 2 0 0 1 -2 2H7a2 2 0 0 1 -2 -2Z");
}

.jnf_2db5t {
  d: path("M12 18v3");
}

</style>
