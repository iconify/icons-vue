<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kuzq45flh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:ointment-jar-sharp" /></template>
<style>
.kuzq45flh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 7h2.5v10h-2.5zm3.5.75h8.25l.74.67l1.02.91l.74.67v4l-.74.67l-1.02.91l-.74.67H5.25v-8.5zM8 12h4.5m4.5-1.75h4.25v3.5H17z");
}

</style>
