<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="g3oqoesuk"/><path class="b2hgpb6-p"/><path class="e23tkxb7t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:tiendamia" /></template>
<style>
.b2hgpb6-p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.51 20c0-2.529 1.95-4.532 4.333-4.532s4.332 2.003 4.332 4.533v7.389M4.51 15.785v11.594");
}

.e23tkxb7t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.143 20c0-2.529 1.95-4.532 4.332-4.532s4.333 2.003 4.333 4.533v7.389m6.514-11.605v11.594M43.5 23.268c0 2.53-1.95 4.533-4.332 4.533s-4.332-2.003-4.332-4.533v-2.951c0-2.53 1.95-4.533 4.332-4.533s4.332 2.003 4.332 4.533m0 7.168V15.89m-39 16.548h16.865v2.53l5.27-2.53H43.5");
}

.g3oqoesuk {
  fill: currentColor;
  d: path("M29.102 13.782a.75.75 0 0 1-1.5 0a.75.75 0 0 1 1.5 0");
}

</style>
