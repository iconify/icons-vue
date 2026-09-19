<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ehsi7sbcv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:myfidelidade" /></template>
<style>
.ehsi7sbcv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.553 15.573L17.548 5.5l3.949 6.692l7.31 3.162l.943 3.666l10.697 6.285l-3.184 6.273l-3.421 1.83l-16.467.047l-7.44 9.034l-2.293.011z");
}

</style>
