<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="gjra1kb6g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:work-iq-20-regular" /></template>
<style>
.gjra1kb6g {
  fill: currentColor;
  d: path("M11.5 13a.5.5 0 0 1 .5.5v5a.5.5 0 0 1-1 0v-5a.5.5 0 0 1 .5-.5m4.5 0a3 3 0 0 1 3 3c0 .648-.209 1.245-.558 1.736l.412.41a.5.5 0 0 1-.707.708l-.41-.41A3 3 0 0 1 16 19a3 3 0 0 1 0-6M8.5 1.63a3 3 0 0 1 3 0l5 2.886A3 3 0 0 1 18 7.114V11.5a.5.5 0 0 1-1 0V7.114c0-.715-.381-1.375-1-1.733l-1.25-.721a2 2 0 0 0-2 0L7.996 7.405c-.618.357-1 1.018-1 1.732v6.057c0 .714.382 1.375 1 1.732l1.254.724a.5.5 0 0 1-.5.866l-1.254-.724l-.003-.002L3.5 15.486A3 3 0 0 1 2 12.887V7.114a3 3 0 0 1 1.5-2.598zM16 14a2 2 0 1 0 0 4c.37 0 .716-.103 1.014-.279l-.867-.867a.5.5 0 0 1 .707-.707l.867.867A2 2 0 0 0 16 14M11 2.495a2 2 0 0 0-2 0L4 5.38c-.619.36-1 1.02-1 1.734v5.773c0 .714.381 1.375 1 1.733l2.06 1.189a3 3 0 0 1-.064-.615V9.137c0-1.072.572-2.063 1.5-2.599l4.754-2.744q.272-.156.565-.253z");
}

</style>
