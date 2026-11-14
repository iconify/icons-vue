<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="px_r196kc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:music-heart" /></template>
<style>
.px_r196kc {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.5 21.25q3.75 0 3.75-3.75V4.714l3.915 1.957q.066.033.137.052q.071.02.145.025t.147-.004t.143-.032q.07-.024.134-.06q.065-.037.12-.085q.056-.049.101-.107q.046-.059.079-.125t.052-.137t.025-.145t-.004-.147t-.032-.143q-.024-.07-.06-.134q-.037-.065-.085-.12q-.049-.056-.107-.101q-.059-.046-.125-.079l-5-2.5Q9.677 2.75 9.5 2.75q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146v10.757q-.872-.507-2.25-.507q-1.553 0-2.652 1.098Q2.75 15.947 2.75 17.5q0 3.75 3.75 3.75m11.107.389Q14 19.419 14 16.75q0-2.5 2.5-2.5q.89 0 1.5.523q.61-.523 1.5-.523q2.5 0 2.5 2.5q0 2.669-3.607 4.889q-.089.054-.189.083q-.1.028-.204.028t-.204-.028q-.1-.029-.189-.083");
}

</style>
