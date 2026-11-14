<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wppsv9ute"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:runway-condition" /></template>
<style>
.wppsv9ute {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.596 21.5H5.713q-.099 0-.197-.011t-.194-.033t-.189-.055q-.094-.033-.182-.076q-.089-.043-.173-.096q-.083-.052-.16-.114t-.147-.132q-.069-.07-.131-.147q-.061-.078-.113-.162q-.052-.083-.094-.173t-.075-.182t-.053-.19q-.022-.096-.032-.194t-.01-.197t.012-.197t.035-.194l3.671-15.5q.034-.143.091-.278t.136-.259t.177-.233t.213-.2t.244-.161t.267-.119t.284-.073t.291-.024h1.696q.149 0 .297.025q.147.026.288.075q.141.05.271.123q.131.074.247.168t.214.206q.099.113.177.24q.078.128.133.267t.086.285l2.204 10.469M10.25 6v3M10 12.5v3m8.5 0v6M16 17l5 3m-5 0l5-3");
}

</style>
