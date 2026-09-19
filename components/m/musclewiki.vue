<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vjti1abtg"/><path class="lm53s9biy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:musclewiki" /></template>
<style>
.lm53s9biy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.808 20.181V42.5L24 29.293l-9.808 13.172v-22.31");
}

.vjti1abtg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.449 29.994V5.5L24 25.116L40.551 5.537V30.02");
}

</style>
