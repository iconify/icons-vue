<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z-3zatnzq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:tooth-abscess" /></template>
<style>
.z-3zatnzq {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M10.279 2.304Q8.894 1.75 8 1.75q-4.75 0-4.75 5.5q0 1.785 1.275 4.249q.581 1.123.746 1.68l.406 2.032q-.442.251-.829.637Q3.75 16.947 3.75 18.5q0 3.75 3.75 3.75t3.75-3.75q0-2.594-1.795-3.394l.977-2.541q.2-.315 1.568-.315t1.568.315l1.217 3.165q.34 1.27 1.59 1.27q1.264 0 1.598-1.3l.745-2.484q.162-.566.757-1.717Q20.75 9.035 20.75 7.25q0-5.5-4.75-5.5q-.894 0-2.279.554q-1.115.446-1.721.446t-1.721-.446");
}

</style>
