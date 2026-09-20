<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="kxsvacmoa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:pydroid3" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.kxsvacmoa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34 5v5a4.5 4.5 0 0 0 4 4h5M11.5 29.5v-16h5.2a5.4 5.4 0 1 1 0 10.8h-5.2m16.7 5.2L24 18.9m8 0l-5 14.4a2.34 2.34 0 0 1-2.2 1.6h-.6m7.3-4.7a3.4 3.4 0 0 1 2.5-.7h.8m0 8a2.006 2.006 0 0 0 2-2a2.006 2.006 0 0 0-2-2a2.006 2.006 0 0 0 2-2a2.006 2.006 0 0 0-2-2m-3.3 7.4a3.25 3.25 0 0 0 2.5.7h.8");
}

</style>
