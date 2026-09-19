<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="mme4iukjt"/><path class="iqltf5e1r"/><path class="rgti7u20g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:wggesucht" /></template>
<style>
.iqltf5e1r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m31.783 42.173l3.53-6.33M5.5 15.694l27.236-9.867l9.764 7.811");
}

.mme4iukjt {
  cx: 37.666px;
  cy: 31.887px;
  r: 4.625px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.rgti7u20g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.25 13.844v5.344l4.111 2.878v-5.344Zm-5.86 19.238a3.83 3.83 0 0 0-3.954-3.813a3.98 3.98 0 0 0-3.53 3.954v3.53a3.797 3.797 0 0 0 3.812 3.814h0a3.797 3.797 0 0 0 3.812-3.813h-3.813M6.014 29.26L8.84 40.567l2.826-11.305l2.827 11.305l2.827-11.305");
}

</style>
