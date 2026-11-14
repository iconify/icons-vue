<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c-nn5s7cp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:pin-laundry" /></template>
<style>
.c-nn5s7cp {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.5 1.75h9q1.76 0 3.005 1.245T20.75 6v12q0 1.76-1.245 3.005T16.5 22.25h-9q-1.76 0-3.005-1.245T3.25 18V6q0-1.76 1.245-3.005T7.5 1.75M7 14.25q0 2.071 1.464 3.536Q9.929 19.25 12 19.25t3.536-1.464Q17 16.321 17 14.25t-1.464-3.536T12 9.25t-3.536 1.464Q7 12.179 7 14.25");
}

</style>
