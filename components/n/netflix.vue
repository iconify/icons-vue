<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hf2r7eb6e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:netflix" /></template>
<style>
.hf2r7eb6e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29 25.75V5l8.4-.5v39L29 43M19 22.25V43l-8.4.5v-39h0L19 5m-.02 0l18.44 38.5m-26.84-39L29.02 43");
}

</style>
