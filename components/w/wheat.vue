<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z1bypac1h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:wheat" /></template>
<style>
.z1bypac1h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 21.25V7.5m0 0q2.6-2.38 0-4.75q-2.6 2.37 0 4.75m0 4q-.06-3.19-3.25-3q.06 3.19 3.25 3m0 0q3.19.19 3.25-3q-3.19-.19-3.25 3m0 5.75q-.06-3.19-3.25-3q.06 3.19 3.25 3m0 0q3.19.19 3.25-3q-3.19-.19-3.25 3");
}

</style>
