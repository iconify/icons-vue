<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="zxtoqfw6h"/><path class="w41sfpb9b"/><ellipse class="vbq8j0yjo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-monotone:warning" /></template>
<style>
.vbq8j0yjo {
  cx: 32px;
  cy: 49.605px;
  fill: currentColor;
  rx: 4.219px;
  ry: 4.207px;
}

.w41sfpb9b {
  fill: currentColor;
  d: path("M30.551 42.051c.275 1.84 2.623 1.84 2.898 0l2.748-18.464c.506-7.199-8.904-7.199-8.396 0z");
}

.zxtoqfw6h {
  fill: currentColor;
  d: path("M61.428 56.709L34.693 4.182C33.953 2.727 32.977 2 32 2s-1.953.728-2.693 2.183L2.572 56.709C1.09 59.621 2.588 62 5.9 62h52.197c3.313 0 4.813-2.379 3.331-5.291m-1.555 2.664c-.24.393-.904.627-1.775.627H5.9c-.87 0-1.534-.232-1.774-.625c-.228-.373-.143-1.029.229-1.758L31.089 5.089c.431-.845.828-1.075.911-1.089c.083.015.48.244.911 1.09l26.734 52.528c.371.728.457 1.384.228 1.755");
}

</style>
