<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m5-e1hs_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:wb-twilight-2-outline-sharp" /></template>
<style>
.m5-e1hs_q {
  fill: currentColor;
  d: path("M2 20v-2h20v2zm5.425-6h9.15q-.575-1.35-1.8-2.175T12 11t-2.775.825T7.425 14M5 16q0-2.925 2.038-4.962T12 9t4.963 2.038T19 16zm7-2");
}

</style>
