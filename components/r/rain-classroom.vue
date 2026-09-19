<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="v6remmhei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:rain-classroom" /></template>
<style>
.v6remmhei {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 30.5v7m0-32v19m7.4-3.5v19m0-32v7m7.4 14.5v13m0-32v13m22.2 14v-32l-14.8 5v32z");
}

</style>
