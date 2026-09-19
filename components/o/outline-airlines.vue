<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ubjs4q5ge"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-airlines" /></template>
<style>
.ubjs4q5ge {
  fill: currentColor;
  d: path("M17.34 18H5.8l8.25-12h5.54zM13 4L2 20h17l3-16zm1.5 5a2.5 2.5 0 0 0 0 5a2.5 2.5 0 0 0 0-5");
}

</style>
