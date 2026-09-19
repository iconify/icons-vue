<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mkzujueaz"/><path class="j5n0flbcv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mercantil-banco" /></template>
<style>
.j5n0flbcv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.41 43.622c-1.378-6.142-5.83-8.595-10.91-10.294c8.393-.75 19.021-2.57 27.026-8.388c4.9-3.562 8.13-10.331 1.372-15.51");
}

.mkzujueaz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.613 4.529c18.876-1.457 28.95 7.943 30.66 16.992c1.711 9.052-6.149 19.977-25.862 22.1c8.808-4.724 11.902-13.856 10.768-21.915c-1.077-7.65-6.18-14.373-15.566-17.177");
}

</style>
