<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gjbt88mbn"/><circle class="savg20ioh"/><path class="ovy7491qu"/><circle class="sbll8ubqx"/><path class="zc7cbac5v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:materialpods" /></template>
<style>
.gjbt88mbn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.7 17.056a7.35 7.35 0 0 1 3.24 5.98V40.82a1.68 1.68 0 0 0 1.678 1.679h2.439a1.68 1.68 0 0 0 1.679-1.68V19.69c0-4.4-.964-8.777-3.35-11.446a9 9 0 0 0-.727-.696C14.544 4.042 9.586 5.232 5.6 9.638a1.54 1.54 0 0 0-.336.885v6.593a1.6 1.6 0 0 0 .326.897c3.15 3.711 6.17 4.852 11.313 4.32");
}

.ovy7491qu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.736 39.15h-3.26M15.628 9.964a8.6 8.6 0 0 1 2.338 3.342m16.334 3.75a7.35 7.35 0 0 0-3.24 5.98V40.82a1.68 1.68 0 0 1-1.678 1.679h-2.439a1.68 1.68 0 0 1-1.679-1.68V19.69c0-4.4.964-8.777 3.35-11.446a9 9 0 0 1 .727-.696c4.115-3.506 9.073-2.316 13.059 2.09a1.54 1.54 0 0 1 .336.885v6.593a1.6 1.6 0 0 1-.326.897c-3.15 3.711-6.17 4.852-11.313 4.32");
}

.savg20ioh {
  cx: 9.447px;
  cy: 13.933px;
  r: 0.75px;
  fill: currentColor;
}

.sbll8ubqx {
  cx: 38.553px;
  cy: 13.933px;
  r: 0.75px;
  fill: currentColor;
}

.zc7cbac5v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.264 39.15h3.26m3.848-29.186a8.6 8.6 0 0 0-2.337 3.342");
}

</style>
