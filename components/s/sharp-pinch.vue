<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mh5rrv2tq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-pinch" /></template>
<style>
.mh5rrv2tq {
  fill: currentColor;
  d: path("M23.18 15.4L22.1 23h-9L8 17.62l1.22-1.23l3.78.85V6.5c0-.83.67-1.5 1.5-1.5s1.5.67 1.5 1.5v6h1.38zM6 2.5V1h5v5H9.5V3.56L3.56 9.5H6V11H1V6h1.5v2.44L8.44 2.5z");
}

</style>
