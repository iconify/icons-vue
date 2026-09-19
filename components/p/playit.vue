<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wi7u77bnp"/><path class="x_3o3herz"/><path class="ebwpprb3p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:playit" /></template>
<style>
.ebwpprb3p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m29.188 18.467l-9.145-5.265a1.233 1.233 0 0 0-1.848 1.068V24.8a1.233 1.233 0 0 0 1.848 1.07l9.145-5.266a1.233 1.233 0 0 0 0-2.137");
}

.wi7u77bnp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17 32.5v5a5 5 0 0 1-5 5h0a5 5 0 0 1-5-5");
}

.x_3o3herz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7 37.5a5 5 0 0 1 5-5h25c2.2 0 4-1.8 4-4v-19c0-2.2-1.8-4-4-4H11c-2.2 0-4 1.8-4 4z");
}

</style>
