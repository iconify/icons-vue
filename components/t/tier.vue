<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gwodxdakz"/><path class="uqkdx24ws"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:tier" /></template>
<style>
.gwodxdakz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 42.5h-29c-2.2 0-4-1.8-4-4v-29c0-2.2 1.8-4 4-4h29c2.2 0 4 1.8 4 4v29c0 2.2-1.8 4-4 4M19.717 18.15v10m3.566 0h5m-5-10h5m-5 5h3.26m-3.26-5v10");
}

.uqkdx24ws {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.849 28.15v-10h3.274c1.85 0 3.35 1.504 3.35 3.358s-1.5 3.359-3.35 3.359h-3.274m3.274 0l3.273 3.281M9.526 18.15h6.625m-3.312 10v-10");
}

</style>
