<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="t5o1uw7zv"/><path class="ydl9pabhu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ny-rangers" /></template>
<style>
.t5o1uw7zv {
  d: path("M24 42.5s1.922-1.898 3.545-1.932l9.92-.056s2.617.468 3.071-2.459l.078-29.508l1.903-2.97l-7.022-.022l-2.149 2.032l-2.316-2.069l-7.622-.016m.592 37s-1.922-1.898-3.545-1.932l-9.92-.056s-2.617.468-3.071-2.459L7.386 8.546L5.483 5.575l7.022-.022l2.149 2.032l2.316-2.069l6.438-.016M7.52 16.244l32.916-.026");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ydl9pabhu {
  d: path("M7.43 20.792c.398.13 27.006 19.598 27.006 19.598M16.722 16.247l23.583 17.005");
}

</style>
