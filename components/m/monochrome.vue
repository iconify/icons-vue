<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="f5-mnfltt"/><path class="iluc3esas"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:monochrome" /></template>
<style>
.f5-mnfltt {
  d: path("M4.5 21.809c0-3.54 2.621-6.411 5.854-6.411h27.292c3.233 0 5.854 2.87 5.854 6.41l-11.917 7.715z");
}

.iluc3esas {
  d: path("M10.354 9.602h27.292c3.233 0 5.854 2.63 5.854 5.875v17.046c0 3.245-2.621 5.875-5.854 5.875H10.354c-3.233 0-5.854-2.63-5.854-5.875V15.477c0-3.245 2.621-5.875 5.854-5.875");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
