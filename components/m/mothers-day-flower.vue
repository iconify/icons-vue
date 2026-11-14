<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iykvdrbyi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:mothers-day-flower" /></template>
<style>
.iykvdrbyi {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.25 5q0-2.5 2.5-2.5q1.131 0 1.75.511q.619-.511 1.75-.511q.946 0 1.639.611q.625-.611 1.861-.611q.946 0 1.639.611q.625-.611 1.861-.611q2.5 0 2.5 2.5q0 6.415-7 6.733v2.698q.511-.501 1.187-.893q2.091-1.21 4.686-.778q.073.012.142.038q.069.027.132.066t.117.089q.053.051.096.111t.074.128q.03.067.047.139q.016.072.019.146q.002.073-.01.146q-.422 2.533-2.677 3.839q-1.733 1.003-3.813.878v2.16q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146v-8.767q-7-.318-7-6.733");
}

</style>
