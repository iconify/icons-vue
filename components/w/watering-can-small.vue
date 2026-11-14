<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x605vabdd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:watering-can-small" /></template>
<style>
.x605vabdd {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.254 10.268Q2 10.507 2 14q0 3.491 3.25 3.732V20q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014h10q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146v-3.254l5.355-7.302q.088-.121.123-.266t.013-.292t-.1-.275t-.197-.216q-.121-.088-.266-.123t-.292-.013t-.275.1t-.216.197l-4.145 5.653V10.5q0-2.382-1.684-4.066T11 4.75T6.934 6.434q-1.601 1.602-1.68 3.834m-.004 1.513v4.438Q3.5 15.984 3.5 14t1.75-2.219");
}

</style>
