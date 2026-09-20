<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="w_tw_5b8q"/><path class="oikwbacyn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:pocket-mathematics" /></template>
<style>
.oikwbacyn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24 16.932l9.965-9.965a5 5 0 0 1 7.07 7.07l-9.965 9.965M24 31.072l-9.965 9.964a5 5 0 0 1-7.07-7.07l9.965-9.965");
}

.w_tw_5b8q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.5 5.5a5 5 0 0 0-3.535 8.535l27 27a5 5 0 0 0 7.07-7.07l-27-27A5 5 0 0 0 10.5 5.5");
}

</style>
