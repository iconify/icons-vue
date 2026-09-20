<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="g2nlpvbhr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:pulse-square-20-regular" /></template>
<style>
.g2nlpvbhr {
  fill: currentColor;
  d: path("M14 3a3 3 0 0 1 3 3v8a3 3 0 0 1-3 3H6a3 3 0 0 1-3-3V6a3 3 0 0 1 3-3zM6 4a2 2 0 0 0-2 2v8a2 2 0 0 0 2 2h8a2 2 0 0 0 2-2V6a2 2 0 0 0-2-2zm2.504 2a.5.5 0 0 1 .467.332l2.106 5.897l.976-1.953A.5.5 0 0 1 12.5 10h2a.5.5 0 0 1 0 1h-1.691l-1.362 2.724a.5.5 0 0 1-.918-.056L8.49 7.954l-1.021 2.722A.5.5 0 0 1 7 11H5.5a.5.5 0 0 1 0-1h1.153l1.38-3.676A.5.5 0 0 1 8.502 6");
}

</style>
