<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="l6cd208_p"/><circle class="rr907xbun"/><path class="pb_3h3b6c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:watchcheck" /></template>
<style>
.l6cd208_p {
  cx: 24px;
  cy: 24px;
  r: 18.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.pb_3h3b6c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  d: path("M24 5.5c.52-.235.973-1.013 1.29-1.49a3.1 3.1 0 0 0 .51-1.51M42.5 24c.235.52 1.013.973 1.49 1.29a3.1 3.1 0 0 0 1.51.51M24 42.5c-.52.235-.973 1.013-1.29 1.49a3.1 3.1 0 0 0-.51 1.51M5.5 24c-.235-.52-1.013-.973-1.49-1.29a3.1 3.1 0 0 0-1.51-.51M14.75 7.979a4.2 4.2 0 0 0 .373-1.935a3.1 3.1 0 0 0-.314-1.563M40.022 14.75a4.2 4.2 0 0 0 1.934.373a3.1 3.1 0 0 0 1.563-.314M33.25 40.022a4.2 4.2 0 0 0-.373 1.934a3.1 3.1 0 0 0 .314 1.563M7.979 33.25a4.2 4.2 0 0 0-1.935-.373a3.1 3.1 0 0 0-1.563.314M7.979 14.75a4.2 4.2 0 0 0-.645-1.862a3.1 3.1 0 0 0-1.053-1.197M33.25 7.979a4.2 4.2 0 0 0 1.862-.645a3.1 3.1 0 0 0 1.197-1.053m3.713 26.969a4.2 4.2 0 0 0 .644 1.862a3.1 3.1 0 0 0 1.054 1.197m-26.97 3.713a4.2 4.2 0 0 0-1.862.644a3.1 3.1 0 0 0-1.197 1.054M24 19.506v-14M28.51 24h14m-18.491 4.512v14M19.51 24h-14");
}

.rr907xbun {
  cx: 24.019px;
  cy: 24.012px;
  r: 4.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
