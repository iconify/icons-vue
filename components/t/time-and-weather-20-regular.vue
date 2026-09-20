<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="v81x_ri4q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:time-and-weather-20-regular" /></template>
<style>
.v81x_ri4q {
  fill: currentColor;
  d: path("M10.5 2.5a.5.5 0 0 0-1 0v1a.5.5 0 0 0 1 0zm-.5 6a.5.5 0 0 0-1 0v2a.5.5 0 0 0 .5.5H11a.5.5 0 0 0 0-1h-1zm0-3a4.5 4.5 0 1 0 0 9a4.5 4.5 0 0 0 0-9M6.5 10a3.5 3.5 0 1 1 7 0a3.5 3.5 0 0 1-7 0m3.5 6a.5.5 0 0 1 .5.5v1a.5.5 0 0 1-1 0v-1a.5.5 0 0 1 .5-.5M2.5 9.5a.5.5 0 0 0 0 1h1a.5.5 0 0 0 0-1zM16 10a.5.5 0 0 1 .5-.5h1a.5.5 0 0 1 0 1h-1a.5.5 0 0 1-.5-.5M4.146 15.146a.5.5 0 0 0 .708.708l1-1a.5.5 0 0 0-.708-.708zm10-10l1-1a.5.5 0 0 1 .708.708l-1 1a.5.5 0 0 1-.708-.708m-9.292-1a.5.5 0 1 0-.708.708l1 1a.5.5 0 1 0 .708-.708zm10 10l1 1a.5.5 0 0 1-.708.708l-1-1a.5.5 0 0 1 .708-.708");
}

</style>
