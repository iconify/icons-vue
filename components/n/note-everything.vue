<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="rkey3t-zs"/><path class="w4l4vnbqt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:note-everything" /></template>
<style>
.rkey3t-zs {
  d: path("m30.31 14.787l-7.413 8.88l2.933 5.295l-4.237-3.503l-8.472 6.517l7.169-8.146l-3.748-6.355l5.133 4.807zM29.048 42.5c.98-2.057 1.762-4.28 3.992-5.295c-.835-2.175-.598-4.043.082-5.785c2.957-7.552 4.532-16.486 6.191-25.336c-.465-.536-1.01-.913-2.118-.163c-2.54 7.229-5.478 14.127-6.762 22.404l.245 2.28l-1.956 6.192zm4.074-11.08l-2.444-.814");
}

.w4l4vnbqt {
  d: path("M34.283 7.207H8.687V39.07H26.48h-.042");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
