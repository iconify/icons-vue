<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="rwigyl-gn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:sound-wave-circle-20-regular" /></template>
<style>
.rwigyl-gn {
  fill: currentColor;
  d: path("M9.996 2.999a7 7 0 1 0 0 14a7 7 0 0 0 0-14m-8 7a8 8 0 1 1 16 0a8 8 0 0 1-16 0M6 8.5a.5.5 0 0 1 .5.5v2a.5.5 0 0 1-1 0V9a.5.5 0 0 1 .5-.5m5.5 0a.5.5 0 0 0-1 0v3a.5.5 0 0 0 1 0zM8.5 7a.5.5 0 0 1 .5.5v5a.5.5 0 0 1-1 0v-5a.5.5 0 0 1 .5-.5m5.5.5a.5.5 0 0 0-1 0v5a.5.5 0 0 0 1 0z");
}

</style>
