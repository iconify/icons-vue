<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="utr-zkbad"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-person-off" /></template>
<style>
.utr-zkbad {
  fill: currentColor;
  d: path("M8.65 5.82a3.999 3.999 0 1 1 5.53 5.53zM20 17.17c-.02-1.1-.63-2.11-1.61-2.62c-.54-.28-1.13-.54-1.77-.76zm1.19 4.02L2.81 2.81L1.39 4.22l8.89 8.89c-1.81.23-3.39.79-4.67 1.45A2.97 2.97 0 0 0 4 17.22V20h13.17l2.61 2.61z");
}

</style>
