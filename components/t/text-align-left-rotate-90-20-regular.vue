<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="o4bm0ddrp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-align-left-rotate-90-20-regular" /></template>
<style>
.o4bm0ddrp {
  fill: currentColor;
  d: path("M15.5 2a.5.5 0 0 1 .5.5v11a.5.5 0 0 1-1 0v-11a.5.5 0 0 1 .5-.5m-5 0a.5.5 0 0 1 .5.5v15a.5.5 0 0 1-1 0v-15a.5.5 0 0 1 .5-.5M6 2.5a.5.5 0 0 0-1 0v9a.5.5 0 0 0 1 0z");
}

</style>
