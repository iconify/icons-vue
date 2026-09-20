<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qgx2gpbea"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:replay-30-outline" /></template>
<style>
.qgx2gpbea {
  fill: currentColor;
  d: path("M8.882 20.374q-1.455-.626-2.542-1.713t-1.714-2.543T4 13h1q0 2.925 2.038 4.963T12 20t4.963-2.037T19 13t-2.037-4.962T12 6h-.38l1.626 1.627l-.708.72L9.692 5.48l2.885-2.866l.708.72L11.619 5H12q1.664 0 3.118.626T17.66 7.34t1.714 2.542T20 13t-.626 3.118t-1.714 2.543t-2.542 1.713T12 21t-3.118-.626m-1.343-4.682v-.884h2.884v-1.424H8.346v-.769h2.077v-1.423H7.539v-.884h3.077q.309 0 .5.191q.192.192.192.501v4q0 .31-.192.501q-.191.191-.5.191zm6.153 0q-.425 0-.712-.287t-.288-.713v-3.384q0-.425.288-.713t.712-.287h1.77q.424 0 .712.287t.288.713v3.384q0 .425-.288.713t-.712.287zm.116-.884h1.538q.116 0 .173-.058t.058-.173v-3.154q0-.115-.058-.173t-.173-.058h-1.538q-.116 0-.174.058t-.057.173v3.154q0 .115.057.173q.058.058.174.058");
}

</style>
