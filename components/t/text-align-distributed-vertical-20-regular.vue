<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="o8a3xbzbf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-align-distributed-vertical-20-regular" /></template>
<style>
.o8a3xbzbf {
  fill: currentColor;
  d: path("M17.854 4.854a.5.5 0 0 1-.708 0L16 3.707V17.5a.5.5 0 1 1-1 0V3.707l-1.146 1.147a.5.5 0 0 1-.708-.708l2-2a.5.5 0 0 1 .708 0l2 2a.5.5 0 0 1 0 .708m-15 10.293a.5.5 0 1 0-.708.707l2 2a.5.5 0 0 0 .708 0l2-2a.5.5 0 1 0-.708-.707L5 16.293V2.5a.5.5 0 0 0-1 0v13.793zM10 18a.5.5 0 0 1-.5-.5v-15a.5.5 0 0 1 1 0v15a.5.5 0 0 1-.5.5");
}

</style>
