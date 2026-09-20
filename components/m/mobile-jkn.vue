<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="pj4j9jlmd"/><circle class="qabjhhyzj"/><path class="vg5i33s-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mobile-jkn" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.pj4j9jlmd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M6.465 16.769c-2.063 4.526-2.065 9.944 0 14.468m35.07-14.468c2.064 4.526 2.065 9.944 0 14.468M8.605 18.813c-1.173 3.321-1.16 7.05 0 10.375m30.79-10.375c1.173 3.321 1.16 7.05 0 10.375M21.85 18.65v8.1m0-1.7l3.6-3.7m-2.4 2.5l2.8 2.8m-7.65-5.3v6c0 1.1-.9 2-2 2c-.5 0-1-.2-1.4-.6");
}

.qabjhhyzj {
  cx: 18.2px;
  cy: 19.05px;
  r: 0.75px;
  fill: currentColor;
}

.vg5i33s-s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.2 26.75v-3.3c0-1.1-.9-2-2-2s-2 .9-2 2m0 3.3v-5.4");
}

</style>
