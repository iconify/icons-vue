<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="xvjk-cbox"/><path class="u_u9u_b6m"/><path class="p7exz8bqd"/><path class="zwiw2-bkv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:streets-map-point-linear" /></template>
<style>
.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.p7exz8bqd {
  d: path("M14.0004 13.9998L20.5004 20.4998M21.6072 6.39307L14.0004 13.9998L6.39453 21.6057");
}

.u_u9u_b6m {
  d: path("M5.5 8.7572C5.5 6.95823 7.067 5.49988 9 5.49988C10.933 5.49988 12.5 6.95823 12.5 8.7572C12.5 10.5421 11.3829 12.6248 9.64003 13.3697C9.23374 13.5433 8.76626 13.5433 8.35997 13.3697C6.61708 12.6248 5.5 10.5421 5.5 8.7572Z");
}

.xvjk-cbox {
  d: path("M12 22C7.28595 22 4.92893 22 3.46447 20.5355C2 19.0711 2 16.714 2 12C2 7.28595 2 4.92893 3.46447 3.46447C4.92893 2 7.28595 2 12 2C16.714 2 19.0711 2 20.5355 3.46447C22 4.92893 22 7.28595 22 12C22 16.714 22 19.0711 20.5355 20.5355C19.0711 22 16.714 22 12 22Z");
}

.zwiw2-bkv {
  stroke-linejoin: round;
  d: path("M9 9H9.0001");
}

</style>
