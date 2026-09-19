<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ijklq_2vl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:yatse" /></template>
<style>
.ijklq_2vl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m12.46 5.5l9.9 5.5v10.69l9.4-5.43l10.08 5.61l-19.48 11.26l-5 2.9l-4.9 2.83l-6.3 3.64V31.06l6.3-3.64z");
}

</style>
