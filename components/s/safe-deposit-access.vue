<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="mwhvccbkj"/><path class="rgjz0zhyh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:safe-deposit-access" /></template>
<style>
.mwhvccbkj {
  d: path("M12.4 21.5H2.5v-19h19v9.9");
}

.rgjz0zhyh {
  d: path("M4.75 5h6v4.5h-6Zm8.5 0h6v4.5h-6Zm-8.5 9h6v4.5h-6ZM6.5 7.25H9m6 0h2.5m-11 9H9m6.25-1h.01m2.74 0h3.25m-6 2.75h.01M18 18h3.25m-6 2.75h.01m2.74 0h3.25");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
