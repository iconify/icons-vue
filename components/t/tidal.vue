<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="h6_wom11w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:tidal" /></template>
<style>
.h6_wom11w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m10.333 12.333l6.834 6.834L24 12.333l6.833 6.834l6.834-6.834l6.833 6.834L37.667 26l-6.834-6.833L24 26l6.833 6.833L24 39.667l-6.833-6.834L24 26l-6.833-6.833L10.333 26L3.5 19.167Z");
}

</style>
