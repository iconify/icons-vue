<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gna_m8xeg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:water-refill-fountain" /></template>
<style>
.gna_m8xeg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M14.426 12.402q-.14.142-.304.254q-.165.112-.349.189t-.379.116T13 13H5q-.098 0-.196-.01q-.098-.009-.194-.028q-.097-.02-.191-.048q-.094-.029-.184-.066q-.091-.038-.178-.084q-.086-.046-.168-.101t-.158-.117t-.145-.132t-.132-.145t-.117-.158t-.101-.168q-.046-.087-.084-.178q-.037-.09-.066-.184q-.028-.094-.048-.191q-.019-.096-.028-.194T3 11V9.5h12V11q0 .102-.01.204M9 13v7.5m-3 0h6m-6.5-11c0-6.5 6.5-7 7-2.75M16 21.5h5V17l-1.25-1.25V14h-2.5v1.75L16 17Z");
}

</style>
