<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y2-bsccqn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:zap-flame-alt-fill-sharp" /></template>
<style>
.y2-bsccqn {
  fill: currentColor;
  d: path("M5.667 2h4.666a1 1 0 0 1 .869 1.496L9.39 6.667H11a1 1 0 0 1 .707 1.707l-7.333 7.333a1.002 1.002 0 0 1-1.684-.924L3.753 10H3a1 1 0 0 1-.914-1.406l2.667-6A1 1 0 0 1 5.667 2m12.948 19.788l-.001.001A1 1 0 0 1 18 22h-2a1 1 0 0 1-.614-.211h-.001a8 8 0 0 1-.837-.745c-1.778-1.724-2.845-3.828-2.265-6.337c.253-1.091.779-2.105 1.391-3.035c.765-1.161 1.678-2.213 2.545-3.297a1 1 0 0 1 1.562 0q.29.36.584.72c.335.41.67.821.995 1.24c1.013 1.305 1.979 2.743 2.357 4.372c.58 2.509-.487 4.613-2.265 6.337a8 8 0 0 1-.837.744M16.355 20h1.29c.366-.313.727-.675.932-1.118c.376-.814-.138-1.596-.647-2.216a11 11 0 0 0-.93-.981c-.326.31-.644.632-.93.981c-.509.62-1.023 1.402-.647 2.216c.205.443.566.805.932 1.118");
}

</style>
