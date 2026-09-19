<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kwn8oravu"/><path class="b_tliwbzd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:valv" /></template>
<style>
.b_tliwbzd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m5.5 6.925l18.5 37l18.5-37H28.167l-4.166 9.489l-4.167-9.49z");
}

.kwn8oravu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M40.721 10.485A21.5 21.5 0 0 1 45.5 24c0 11.874-9.626 21.5-21.5 21.5S2.5 35.874 2.5 24a21.5 21.5 0 0 1 4.773-13.507m3.667-3.571a21.5 21.5 0 0 1 26.122 0");
}

</style>
