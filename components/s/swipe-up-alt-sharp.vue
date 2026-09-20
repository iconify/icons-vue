<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w4s6o1bds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:swipe-up-alt-sharp" /></template>
<style>
.w4s6o1bds {
  fill: currentColor;
  d: path("M8.463 18.538Q7 17.075 7 15q0-1.825 1.138-3.187T11 10.1V5.825L9.4 7.4L8 6l4-4l4 4l-1.4 1.425l-1.6-1.6V10.1q1.725.35 2.863 1.713T17 15q0 2.075-1.463 3.538T12 20t-3.537-1.463");
}

</style>
