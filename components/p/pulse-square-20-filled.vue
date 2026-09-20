<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xg2lc5bvj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:pulse-square-20-filled" /></template>
<style>
.xg2lc5bvj {
  fill: currentColor;
  d: path("M14 3a3 3 0 0 1 3 3v8a3 3 0 0 1-3 3H6a3 3 0 0 1-3-3V6a3 3 0 0 1 3-3zM8.504 6a.5.5 0 0 0-.472.324L6.653 10H5.5a.5.5 0 0 0 0 1H7a.5.5 0 0 0 .468-.324l1.02-2.722l2.041 5.714a.5.5 0 0 0 .918.056L12.81 11h1.69a.5.5 0 0 0 0-1h-2a.5.5 0 0 0-.447.276l-.976 1.953l-2.106-5.897A.5.5 0 0 0 8.504 6");
}

</style>
