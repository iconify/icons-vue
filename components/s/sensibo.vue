<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dw1tniber"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:sensibo" /></template>
<style>
.dw1tniber {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.82 12.193L24.649 5.016a3.72 3.72 0 0 0-4.041.167l-7.354 5.201a3.72 3.72 0 0 0-1.505 3.755l2.71 13.868c.028.14.086.26.13.39l-3.61 2.553c-1.715 1.212-1.608 3.79.202 4.857l12.172 7.177a3.72 3.72 0 0 0 4.042-.167l7.353-5.201a3.72 3.72 0 0 0 1.505-3.755l-2.71-13.868c-.028-.14-.086-.26-.13-.39l3.61-2.552c1.714-1.213 1.608-3.791-.202-4.858Z");
}

</style>
