<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pz3edcb4l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:trail-length-short-rounded" /></template>
<style>
.pz3edcb4l {
  fill: currentColor;
  d: path("M15 17q-1.825 0-3.187-1.137T10.1 13H5q-.425 0-.712-.288T4 12t.288-.712T5 11h5.1q.125-.575.338-1.075T11 9H7q-.425 0-.712-.288T6 8t.288-.712T7 7h8q2.075 0 3.538 1.463T20 12t-1.463 3.538T15 17m-7 0q-.425 0-.712-.288T7 16t.288-.712T8 15h1q.425 0 .713.288T10 16t-.288.713T9 17z");
}

</style>
