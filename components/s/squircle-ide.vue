<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pwa4pmb-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:squircle-ide" /></template>
<style>
.pwa4pmb-z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.861 17.639L3.5 24L24 44.5l6.361-6.361m7.778-7.778L44.5 24L24 3.5l-6.361 6.361");
}

</style>
