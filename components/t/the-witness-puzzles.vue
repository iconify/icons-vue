<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dxep43bkk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:the-witness-puzzles" /></template>
<style>
.dxep43bkk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.995 9.504L24 3.5l6.004 6.004m-20.5 20.501L3.5 24l6.004-6.004m20.5 20.5L24 44.5l-6.005-6.004m20.501-20.5l6.004 6.005l-6.004 6.004M9.504 17.995v-8.49h8.491m0 28.991H9.504v-8.491m28.991 0v8.491h-8.49m0-28.992h8.49v8.492");
}

</style>
