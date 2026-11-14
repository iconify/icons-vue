<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k6rddnb6z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:map-layer-poi" /></template>
<style>
.k6rddnb6z {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.75 10q0 4.955 7.743 12.053q.052.047.111.084t.124.062t.134.038t.138.013t.138-.013t.134-.038t.124-.062t.111-.084Q20.25 14.955 20.25 10q0-3.417-2.416-5.834T12 1.75T6.166 4.166Q3.75 6.583 3.75 10m4.75 0q0-3.5 3.5-3.5t3.5 3.5t-3.5 3.5T8.5 10");
}

</style>
