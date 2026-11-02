<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="kwnr84g-f"/><path class="w6nkk--nh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:octagon-plus-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.kwnr84g-f {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M15 3c.763 0 1.479.48 2 1l3 3c.52.521 1 1.237 1 2v6c0 .763-.48 1.479-1 2l-3 3c-.521.52-1.237 1-2 1H9c-.763 0-1.479-.48-2-1l-3-3c-.52-.521-1-1.237-1-2V9c0-.763.48-1.479 1-2l3-3c.521-.52 1.237-1 2-1Z");
}

.w6nkk--nh {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 3h3c.64 0 1.36.36 2 1l3 3c.64.64 1 1.36 1 2v6c0 .64-.36 1.36-1 2l-3 3c-.64.64-1.36 1-2 1H9c-.64 0-1.36-.36-2-1l-3-3c-.64-.64-1-1.36-1-2V9c0-.64.36-1.36 1-2l3-3c.64-.64 1.36-1 2-1zm-4 9h8m-4-4v8");
}

</style>
