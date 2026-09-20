<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cfrcb2brf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:travel-luggage-and-bags-outline-sharp" /></template>
<style>
.cfrcb2brf {
  fill: currentColor;
  d: path("M7.616 21v-1H6V7h3.904V3.808h4.192V7H18v13h-1.616v1h-1v-1H8.616v1zm3.288-14h2.192V4.808h-2.192zm3.684 5.047Q15.85 11.71 17 11.035V8H7v3.035q1.15.674 2.413 1.012t2.587.337t2.588-.337M11.5 14.385v-1.012q-1.184-.086-2.31-.375T7 12.169V19h10v-6.83q-1.065.54-2.19.828t-2.31.375v1.012zm.5-2.216");
}

</style>
