<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yetinqbus"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:print-landscape-long" /></template>
<style>
.yetinqbus {
  fill: currentColor;
  d: path("M4 14q-1.125 0-1.713-.925T2.175 11.2q.65-1.35 1.088-2.662T3.875 6.5q.175-.675.713-1.088T5.825 5H7V4h3v1h4V4h3v1h2q.85 0 1.425.563T21 7q0 .675-.337 1.438t-.613 1.387q-.225.525-.537 1.113t-.888 1.837q-.275.55-.775.888T16.775 14zm0 2h12.775q1.15 0 2.138-.65t1.487-1.7l.6-1.175V17q0 .825-.587 1.413T19 19H6q-.825 0-1.412-.587T4 17z");
}

</style>
