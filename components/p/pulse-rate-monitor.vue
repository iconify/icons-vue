<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="j9a1d4b2x"/><path class="sfs8-9bwv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:pulse-rate-monitor" /></template>
<style>
.j9a1d4b2x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.236 26.4h9.31l3.417-8.437l2.982 12.074l4.582-10.328l3.128 8.728l3.054-7.2l1.746 5.163h9.31");
}

.sfs8-9bwv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43 17.077c0-5.654-4.583-10.238-10.237-10.238c-3.723 0-6.971 1.993-8.763 4.964c-1.792-2.97-5.04-4.964-8.763-4.964C9.583 6.84 5 11.423 5 17.077c0 1.292.25 2.524.687 3.662C9.072 30.476 24 41.161 24 41.161s14.928-10.685 18.314-20.422c.437-1.138.686-2.37.686-3.662m-19-5.274v29.358");
}

</style>
