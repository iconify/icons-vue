<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="z-b9wm1xz"/><path class="wyhuuqbmc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:yahoo-mail" /></template>
<style>
.wyhuuqbmc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.5 14.981L24 24L4.5 14.981");
}

.z-b9wm1xz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.5 35.5v-23a2 2 0 0 0-2-2h-35a2 2 0 0 0-2 2v23a2 2 0 0 0 2 2h35a2 2 0 0 0 2-2");
}

</style>
