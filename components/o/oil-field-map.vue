<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kwdjadcqo"/><path class="l2zb4i5sv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:oil-field-map" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kwdjadcqo {
  d: path("M12 14.05V16m4.74-4.247l3.286-1.095q.084-.028.171-.046t.176-.025t.177-.005t.176.016t.174.037q.085.024.168.058q.082.033.159.076q.078.043.15.095t.138.112q.065.06.123.128q.058.067.107.141q.05.074.09.153q.041.079.072.162t.051.17q.021.086.032.174t.01.177v6.838q0 .117-.018.233q-.019.116-.055.228t-.089.216t-.121.2t-.152.179q-.082.083-.177.153t-.198.123q-.105.054-.216.091l-4.56 1.52q-.203.068-.417.076t-.421-.044l-7.152-1.788q-.208-.052-.421-.044q-.214.008-.417.076l-3.612 1.204q-.084.028-.171.046t-.176.025q-.088.008-.177.005t-.176-.016q-.088-.014-.174-.037q-.085-.024-.168-.058q-.082-.033-.159-.076q-.078-.043-.15-.095t-.138-.112t-.123-.128q-.058-.067-.107-.141q-.05-.074-.09-.153q-.041-.079-.072-.162t-.051-.17q-.021-.086-.032-.174T2 19.919v-6.838q0-.117.018-.233q.019-.116.055-.228t.089-.216q.053-.105.121-.2q.069-.095.152-.179t.177-.153t.198-.123t.216-.091l3.415-1.138M8 12.5V20m8-7.5V22");
}

.l2zb4i5sv {
  fill: currentColor;
  d: path("M12 2S8.75 6 8.75 8a3.25 3.25 0 0 0 6.5 0c0-2-3.25-6-3.25-6");
}

</style>
