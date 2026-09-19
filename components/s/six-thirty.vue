<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="tra3yd2fw"/><path class="zc8_48_5b"/><path class="hd7y_b88y"/><path class="kemv13nqi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:six-thirty" /></template>
<style>
.hd7y_b88y {
  fill: var(--svg-color--85939c, #85939c);
  d: path("M33.871 52.95c0 1.437-.848 2.603-1.89 2.603s-1.89-1.166-1.89-2.603V31.87c0-1.438.849-2.605 1.89-2.605c1.042 0 1.89 1.167 1.89 2.605z");
}

.kemv13nqi {
  fill: var(--svg-color--788288, #788288);
  d: path("M30.1 31.871c0-1.438.845-2.605 1.888-2.605s1.891 1.168 1.891 2.605l.006 15.253c0 1.437-.851 2.604-1.889 2.603c-1.043.002-1.892-1.166-1.892-2.601z");
}

.tra3yd2fw {
  fill: var(--svg-color--e0e7ec, #e0e7ec);
  d: path("M61.63 31.994c0 16.365-13.271 29.636-29.638 29.636c-16.369 0-29.637-13.271-29.637-29.636c0-16.371 13.269-29.639 29.637-29.639c16.367 0 29.638 13.269 29.638 29.639");
}

.zc8_48_5b {
  fill: var(--svg-color--98a9b4, #98a9b4);
  d: path("M31.994 0C14.353 0 0 14.353 0 31.994c0 17.642 14.353 31.994 31.994 31.994c17.643 0 31.992-14.354 31.992-31.994S49.637 0 31.994 0m0 57.76c-14.207 0-25.766-11.56-25.766-25.766c0-14.207 11.559-25.766 25.766-25.766s25.764 11.559 25.764 25.766S46.2 57.76 31.994 57.76");
}

</style>
