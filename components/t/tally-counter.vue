<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="d1mbm7oaz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:tally-counter" /></template>
<style>
.d1mbm7oaz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.3 8.5v31m7.8-31v31m7.8-31v31m7.8-31v31M4.5 26.667l39-8.367");
}

</style>
