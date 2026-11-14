<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kf4agybis"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:pyramid" /></template>
<style>
.kf4agybis {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11.291 3.757Q10.466 4 9.951 4.8L3.516 14.81q-.638.991-.279 2.114t1.454 1.56l7.207 2.882q.288.116.57.162q-.097-.097-.153-.223t-.064-.263zm2.326 17.669q.27-.096.533-.261l5.693-3.557q.907-.567 1.123-1.615t-.393-1.928L14.11 4.729q-.523-.755-1.317-.981l.956 17.21q.007.125-.027.245t-.105.223");
}

</style>
