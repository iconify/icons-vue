<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lxz2ywb7q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:pipe-wrench" /></template>
<style>
.lxz2ywb7q {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M17.481 2.985h-.001q-.659-.66-1.591-.66t-1.591.66L12 5.283q-.586.585-.586 1.414T12 8.111l.042.041q-.21.127-.395.313q-.264.263-.409.577q-.305-.103-.652-.103q-.829 0-1.414.586q-.586.585-.586 1.414q0 .421.151.779q-.578.235-1.156.813l-2.829 2.828q-.806.805-.806 1.944q0 1.14.806 1.945q.805.806 1.944.806q1.14 0 1.945-.806l2.828-2.829q.578-.578.813-1.156q.358.151.779.151q.829 0 1.414-.586q.202-.202.335-.432q.475.311 1.079.311q.829 0 1.414-.586q.586-.585.586-1.414t-.586-1.414l-2.828-2.828l-.042-.042q.21-.126.396-.312l.529-.531q.22-.22.531-.22t.531.22l.884.885q1.414 1.412 2.827-.001q.586-.585.586-1.414t-.586-1.414z");
}

</style>
