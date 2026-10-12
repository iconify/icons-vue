<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="z24r03bhq"/><rect class="hueodbcwc"/><path class="wo3vhf2ht"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:treasury" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hueodbcwc {
  width: 7px;
  height: 6px;
  x: 8.5px;
  y: 12px;
  rx: 1.5px;
}

.wo3vhf2ht {
  d: path("M8.5 15h7");
}

.z24r03bhq {
  d: path("m3.6 8.47l7.55-4.69q.85-.53 1.7 0l7.55 4.69q.85.53-.15.53H3.75q-1 0-.15-.53M4.75 12v6.5m14.5-6.5v6.5M2.75 21h18.5");
}

</style>
