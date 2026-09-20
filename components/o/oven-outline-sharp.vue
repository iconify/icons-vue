<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cyclawmcs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:oven-outline-sharp" /></template>
<style>
.cyclawmcs {
  fill: currentColor;
  d: path("M16.713 7.097Q17 6.809 17 6.385t-.287-.713T16 5.384t-.712.288t-.288.713t.288.712t.712.288t.713-.288m-4 0Q13 6.809 13 6.385t-.287-.713T12 5.384t-.712.288t-.288.713t.288.712t.712.288t.713-.288m-4 0Q9 6.809 9 6.385t-.287-.713T8 5.384t-.712.288T7 6.385t.288.712t.712.288t.713-.288M5 9.616V19h14V9.616zm5.385 3.615h3.23V12h-3.23zM4 20V4h16v16zm8-10.385");
}

</style>
