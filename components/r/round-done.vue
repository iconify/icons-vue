<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q7va9vb3y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-done" /></template>
<style>
.q7va9vb3y {
  fill: currentColor;
  d: path("m9 16.2l-3.5-3.5a.984.984 0 0 0-1.4 0a.984.984 0 0 0 0 1.4l4.19 4.19c.39.39 1.02.39 1.41 0L20.3 7.7a.984.984 0 0 0 0-1.4a.984.984 0 0 0-1.4 0z");
}

</style>
