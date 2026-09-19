<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ktoz6ibps"/><path class="lkxnyuoeg"/><path class="ib4i46yge"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-data-thresholding" /></template>
<style>
.ib4i46yge {
  fill: currentColor;
  d: path("m10.67 11l2 2l5.08-5.09l-1.41-1.41l-3.67 3.67l-2-2l-4.42 4.42L7.66 14z");
}

.ktoz6ibps {
  fill: currentColor;
  d: path("M19 19v-1.73L17.27 19zM5 17.72L6.72 16h2.12l-3 3h1.83l3-3h2.12l-3 3h1.62l3-3h2.12l-3 3h1.62l3-3H19V5H5zm5.67-9.55l2 2l3.67-3.67l1.41 1.41L12.67 13l-2-2l-3 3l-1.41-1.41z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.lkxnyuoeg {
  fill: currentColor;
  d: path("M19 3H5c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h14c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2m0 16h-1.73L19 17.27zm0-3h-.85l-3 3h-1.62l3-3h-2.12l-3 3H9.8l3-3h-2.12l-3 3H5.84l3-3H6.72L5 17.72V5h14z");
}

</style>
