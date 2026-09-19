<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="fykpg24rv"/><circle class="x1c0mrbmc"/><path class="um4ux7b_z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:tranzy" /></template>
<style>
.fykpg24rv {
  d: path("M17.83 5.5v12.33H7.5a2 2 0 0 1-2-2V7.5a2 2 0 0 1 2-2z");
}

.um4ux7b_z {
  d: path("M42.5 7.5v8.33a2 2 0 0 1-2 2h-8.33a2 2 0 0 0-2 2v8.34a2 2 0 0 1-2 2h-8.34a2 2 0 0 1-2-2V5.5H40.5a2 2 0 0 1 2 2");
}

.x1c0mrbmc {
  cx: 24px;
  cy: 36.33px;
  r: 6.17px;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
