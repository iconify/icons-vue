<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="qzbtm22qd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:threat-actor-16-regular" /></template>
<style>
.qzbtm22qd {
  fill: currentColor;
  d: path("M8 1a7 7 0 0 1 6.344 4.041A1.5 1.5 0 0 1 15.5 6.5v1c0 .444-.194.84-.5 1.115v1.822a3.563 3.563 0 0 1-6.035 2.565l-.618-.596a.5.5 0 0 0-.694 0l-.618.596A3.563 3.563 0 0 1 1 10.437V8.616A1.5 1.5 0 0 1 .5 7.5v-1a1.5 1.5 0 0 1 1.155-1.459A7 7 0 0 1 8 1M2.984 9.63a1.75 1.75 0 0 0 3.032 1.75zm7 1.75a1.75 1.75 0 0 0 3.032-1.75zM2 6a.5.5 0 0 0-.5.5v1A.5.5 0 0 0 2 8h12a.5.5 0 0 0 .5-.5v-1A.5.5 0 0 0 14 6zm6-4a5.99 5.99 0 0 0-5.192 3h10.384A5.99 5.99 0 0 0 8 2");
}

</style>
