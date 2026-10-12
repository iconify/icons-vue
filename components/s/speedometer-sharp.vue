<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t6z63nbnk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:speedometer-sharp" /></template>
<style>
.t6z63nbnk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 15a9.25 9.25 0 0 1 18.5 0v3.25H2.75v-1ZM6 15h1.5M12 8.5V10m4.5 5H18m-6 0l3.75-3.75");
}

</style>
