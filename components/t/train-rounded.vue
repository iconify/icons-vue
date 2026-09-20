<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ansf4-bda"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:train-rounded" /></template>
<style>
.ansf4-bda {
  fill: currentColor;
  d: path("M4 15.5V6q0-1.325.688-2.113t1.812-1.2t2.563-.55T12 2q1.65 0 3.113.138t2.55.55t1.712 1.2T20 6v9.5q0 1.475-1.012 2.488T16.5 19l.5.5q.425.425.2.963t-.825.537q-.175 0-.337-.062t-.288-.188L14 19h-4l-1.75 1.75q-.125.125-.288.188T7.626 21q-.575 0-.812-.537T7 19.5l.5-.5q-1.475 0-2.488-1.012T4 15.5M6 10h5V7H6zm7 0h5V7h-5zm-3.425 5.575Q10 15.15 10 14.5t-.425-1.075T8.5 13t-1.075.425T7 14.5t.425 1.075T8.5 16t1.075-.425m7 0Q17 15.15 17 14.5t-.425-1.075T15.5 13t-1.075.425T14 14.5t.425 1.075T15.5 16t1.075-.425");
}

</style>
