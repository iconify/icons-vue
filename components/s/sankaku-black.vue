<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="l-4kcwb3x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:sankaku-black" /></template>
<style>
.l-4kcwb3x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 8.498L6.1 39.502h35.8l-3.464-6H16.492L24 20.498l7.508 13.004h6.928z");
}

</style>
