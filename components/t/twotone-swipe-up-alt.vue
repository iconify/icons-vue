<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="vxyf4s5ei"/><path class="uf65xccsg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-swipe-up-alt" /></template>
<style>
.uf65xccsg {
  fill: currentColor;
  d: path("m13 5.83l1.59 1.59L16 6l-4-4l-4 4l1.41 1.41L11 5.83v4.27a5 5 0 1 0 2 0zM12 18c-1.66 0-3-1.34-3-3s1.34-3 3-3s3 1.34 3 3s-1.34 3-3 3");
}

.vxyf4s5ei {
  cx: 12px;
  cy: 15px;
  r: 3px;
  fill: currentColor;
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
