<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="kph2kmbun"/><path class="ykd2c7b6c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:tax-evasion" /></template>
<style>
.kph2kmbun {
  d: path("M6.672 3.5H9.5l3 3v8.129M9.299 20.5H5.5q-.098 0-.196-.01q-.098-.009-.194-.028q-.097-.02-.191-.048q-.094-.029-.184-.066q-.091-.038-.178-.084q-.086-.046-.168-.101t-.158-.117t-.145-.132q-.07-.069-.132-.145t-.117-.158t-.101-.168t-.084-.178q-.037-.09-.066-.184q-.028-.094-.048-.191q-.019-.096-.028-.194T3.5 18.5V9.428m12 3.072h6v3h-6Zm0 3h6v3h-6Zm0 4.8v-1.8h6v3h-5.3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ykd2c7b6c {
  d: path("M9.5 3.5v3h3M3 2.5l10 19");
}

</style>
