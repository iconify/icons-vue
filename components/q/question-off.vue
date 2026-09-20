<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="v7ae3ac4g"/><path clip-rule="evenodd" class="y2lzfynak"/><path clip-rule="evenodd" class="ryzr0xr3a"/><path clip-rule="evenodd" class="e4pe5pz5m"/><path class="xedf9ccsf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:question-off" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.e4pe5pz5m {
  fill-rule: evenodd;
  d: path("M13.239 7.966a1.45 1.45 0 0 1-.5 1.99l-2.284 1.367a1.45 1.45 0 0 1-1.49-2.488l2.285-1.368a1.45 1.45 0 0 1 1.989.5");
}

.ryzr0xr3a {
  fill-rule: evenodd;
  d: path("M9.71 8.63c.8 0 1.45.648 1.45 1.45v1.502a1.45 1.45 0 1 1-2.9 0V10.08c0-.8.649-1.45 1.45-1.45");
}

.v7ae3ac4g {
  d: path("M11.739 16.213a2 2 0 1 1-4 0a2 2 0 0 1 4 0");
}

.xedf9ccsf {
  d: path("M1.293 2.707a1 1 0 0 1 1.414-1.414l16 16a1 1 0 0 1-1.414 1.414z");
}

.y2lzfynak {
  fill-rule: evenodd;
  d: path("M9.71 4.765c-.67 0-1.245.2-1.65.486c-.39.276-.583.597-.639.874a1.45 1.45 0 0 1-2.842-.574c.227-1.126.925-2.045 1.809-2.67c.92-.65 2.086-1.016 3.322-1.016c2.557 0 5.208 1.71 5.208 4.456c0 1.59-.945 2.876-2.169 3.626a1.45 1.45 0 0 1-1.514-2.474c.57-.349.783-.794.783-1.152c0-.574-.715-1.556-2.308-1.556");
}

</style>
