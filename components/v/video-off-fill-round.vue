<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m9p1--bar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:video-off-fill-round" /></template>
<style>
.m9p1--bar {
  fill: currentColor;
  d: path("m2.707 2.293l19 19a.999.999 0 1 1-1.414 1.414l-4.899-4.898A3 3 0 0 1 13 19H7a5 5 0 0 1-5-5V8c0-.942.439-1.827 1.191-2.394L1.293 3.707a.999.999 0 1 1 1.414-1.414m16.732 13.903L8.243 5H11a5.01 5.01 0 0 1 4.77 3.497l.783-.391c1.12-.56 2.457-.597 3.583-.034c.534.267.996.658 1.328 1.154c.352.527.536 1.141.536 1.774v2c0 1.562-1.093 2.793-2.561 3.196");
}

</style>
