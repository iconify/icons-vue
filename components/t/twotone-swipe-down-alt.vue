<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="oozognl6w"/><path class="y96sitbtz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-swipe-down-alt" /></template>
<style>
.oozognl6w {
  cx: 12px;
  cy: 9px;
  r: 3px;
  fill: currentColor;
  opacity: var(--svg-opacity--0-3, 0.3);
}

.y96sitbtz {
  fill: currentColor;
  d: path("M13 13.9a5 5 0 1 0-2 0v4.27l-1.59-1.59L8 18l4 4l4-4l-1.41-1.41L13 18.17zM15 9c0 1.66-1.34 3-3 3s-3-1.34-3-3s1.34-3 3-3s3 1.34 3 3");
}

</style>
