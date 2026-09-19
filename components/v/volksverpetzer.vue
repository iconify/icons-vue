<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vp6eec1lb"/><path class="kwkt8cbtv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:volksverpetzer" /></template>
<style>
.kwkt8cbtv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.945 39.348L7.389 8.652H42.5z");
}

.vp6eec1lb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m5.5 11.892l15.896 27.456L37.29 11.892z");
}

</style>
