<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vjsjtgysa"/><path class="ydm2ixbjb"/><path class="zgfzc99ql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:penfed" /></template>
<style>
.vjsjtgysa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.825 41.499a2.75 2.75 0 0 0 2.615-1.9l5.925-18.231a2.75 2.75 0 0 0-.999-3.076L25.859 7.025a2.75 2.75 0 0 0-3.233 0L5.5 19.468L12.66 41.5z");
}

.ydm2ixbjb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m15.201 12.421l15.287 11.107l-5.84 17.971h1.727a2.75 2.75 0 0 0 2.615-1.898l7.348-22.611a2.75 2.75 0 0 0-.999-3.076l3.014 2.19a2.75 2.75 0 0 1 .999 3.075L32.716 39.6a2.75 2.75 0 0 1-2.616 1.9");
}

.zgfzc99ql {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m32.791 16.443l-9.966-7.24a2.75 2.75 0 0 0-3.233 0l-3.013 2.189a2.75 2.75 0 0 1 3.233 0l11.828 8.593m-7.399-.996l-6.247 4.539l2.386 7.343h7.722");
}

</style>
