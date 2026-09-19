<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x0vdqy99x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:school" /></template>
<style>
.x0vdqy99x {
  fill: currentColor;
  d: path("M5 13.18v4L12 21l7-3.82v-4L12 17zM12 3L1 9l11 6l9-4.91V17h2V9z");
}

</style>
