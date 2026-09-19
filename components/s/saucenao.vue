<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="flkb2ebyg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:saucenao" /></template>
<style>
.flkb2ebyg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 10.74V9.5c0-2.216 1.784-4 4-4h29c2.216 0 4 1.784 4 4v1.24m0 26.52v1.24c0 2.216-1.784 4-4 4h-29c-2.216 0-4-1.784-4-4v-1.24m4 1.24l29-29m-29 0l29 29");
}

</style>
