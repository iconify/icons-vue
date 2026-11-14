<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="y4_l21gux"/><path class="ngnowyw1l"/><path class="ptr18-b7h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:mouth-ulcer" /></template>
<style>
.ngnowyw1l {
  d: path("M2.5 12c4.5 1 14.5 1 19 0M9 15h.01");
}

.ptr18-b7h {
  fill: currentColor;
  d: path("M12.75 18.75a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y4_l21gux {
  d: path("M10.11 17.327C7.269 16.803 4.549 15.073 2.5 12C5 8.5 8 7 10.25 7.75L12 8.5l1.75-.75C16 7 19 8.5 21.5 12c-.859 1.288-1.836 2.341-2.89 3.167");
}

</style>
