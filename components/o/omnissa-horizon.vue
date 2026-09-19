<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gpz9tj6oz"/><ellipse class="ua557fsab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:omnissa-horizon" /></template>
<style>
.gpz9tj6oz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.786 37.984c-4.562 0-8.676-2.75-10.424-6.969c-1.749-4.218-.788-9.076 2.434-12.31s8.073-4.206 12.29-2.465m16.46 6.497a7.91 7.91 0 0 1-2.947 15.247m.001 0H16.785m4.302-21.744l16.459 6.497");
}

.ua557fsab {
  cx: 24.578px;
  cy: 21.314px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 11.286px;
  ry: 11.299px;
}

</style>
