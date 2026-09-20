<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="viy_a72mh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:road-outline-rounded" /></template>
<style>
.viy_a72mh {
  fill: currentColor;
  d: path("M4.288 19.713Q4 19.425 4 19V5q0-.425.288-.712T5 4t.713.288T6 5v14q0 .425-.288.713T5 20t-.712-.288m7 0Q11 19.426 11 19v-2q0-.425.288-.712T12 16t.713.288T13 17v2q0 .425-.288.713T12 20t-.712-.288m7 0Q18 19.426 18 19V5q0-.425.288-.712T19 4t.713.288T20 5v14q0 .425-.288.713T19 20t-.712-.288m-7-6Q11 13.425 11 13v-2q0-.425.288-.712T12 10t.713.288T13 11v2q0 .425-.288.713T12 14t-.712-.288m0-6Q11 7.426 11 7V5q0-.425.288-.712T12 4t.713.288T13 5v2q0 .425-.288.713T12 8t-.712-.288");
}

</style>
