<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m925t9vbs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:wb-twilight-2-outline-rounded" /></template>
<style>
.m925t9vbs {
  fill: currentColor;
  d: path("M3 20q-.425 0-.712-.288T2 19t.288-.712T3 18h18q.425 0 .713.288T22 19t-.288.713T21 20zm4.425-6h9.15q-.575-1.35-1.8-2.175T12 11t-2.775.825T7.425 14M5 16q0-2.925 2.037-4.962T12 9t4.963 2.038T19 16zm7-2");
}

</style>
