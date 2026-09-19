<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="uyhh_acmr"/><path class="rucf6bb8v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:zoho-sheet" /></template>
<style>
.rucf6bb8v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m33.5 42.5l9-9l-13-4z");
}

.uyhh_acmr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.5 36.5h-19c-1.662 0-3-1.338-3-3v-25c0-1.662 1.338-3 3-3h26c1.662 0 3 1.338 3 3v19m-20 9v-27m20 7.5h-28");
}

</style>
