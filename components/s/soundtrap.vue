<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ap8jminyn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:soundtrap" /></template>
<style>
.ap8jminyn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.429 24h21.142M10.786 10.588S5.5 16.595 5.5 24s5.286 13.413 5.286 13.413m26.428-26.825S42.5 16.595 42.5 24s-5.286 13.413-5.286 13.413");
}

</style>
