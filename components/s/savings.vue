<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oicmwuhnb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:savings" /></template>
<style>
.oicmwuhnb {
  fill: currentColor;
  d: path("M16.713 10.713Q17 10.425 17 10t-.288-.712T16 9t-.712.288T15 10t.288.713T16 11t.713-.288M8 9h5V7H8zM4.5 21q-.85-2.85-1.675-5.687T2 9.5q0-2.3 1.6-3.9T7.5 4h5q.725-.95 1.763-1.475T16.5 2q.625 0 1.063.438T18 3.5q0 .125-.125.575q-.1.275-.187.563t-.138.587L19.825 7.5H22v6.975l-2.825.925L17.5 21H12v-2h-2v2z");
}

</style>
