<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m2c3yqqhj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:nest-farsight-weather-outline-rounded" /></template>
<style>
.m2c3yqqhj {
  fill: currentColor;
  d: path("M9 15.5h6.25q1.15 0 1.95-.812t.8-1.938t-.763-1.912T15.35 10q-.325-1.125-1.25-1.812T12 7.5q-1.025 0-1.875.538T8.85 9.525q-1.2.05-2.025.913T6 12.5q0 1.25.875 2.125T9 15.5m0-2q-.425 0-.712-.288T8 12.5t.275-.7t.675-.3h1.2l.5-1.125q.2-.425.563-.65T12 9.5q.5 0 .9.288t.525.787l.4 1.425h1.45q.325 0 .525.213t.2.537q0 .3-.212.525t-.538.225zm3 8.5q-2.075 0-3.9-.788t-3.175-2.137T2.788 15.9T2 12t.788-3.9t2.137-3.175T8.1 2.788T12 2t3.9.788t3.175 2.137T21.213 8.1T22 12t-.788 3.9t-2.137 3.175t-3.175 2.138T12 22m0-2q3.35 0 5.675-2.325T20 12t-2.325-5.675T12 4T6.325 6.325T4 12t2.325 5.675T12 20m0-8");
}

</style>
