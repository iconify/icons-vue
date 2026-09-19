<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="y70u8xk7v"/><path class="mppw3d1om"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:miniflutt" /></template>
<style>
.mppw3d1om {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.681 25.009c0-1.387 1.135-2.522 2.522-2.522s2.522 1.135 2.522 2.522v4.035m-5.044-6.557v6.557m5.044-4.035c0-1.387 1.135-2.522 2.522-2.522s2.522 1.135 2.522 2.522v4.035m11.867-10.088h6.683m-3.278 10.088V18.956");
}

.y70u8xk7v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4M22.03 18.956h6.683m-3.279 10.088V18.956");
}

</style>
