<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="w5kufji0i"/><path class="vkw41wbkd"/><path class="p-3e8ccvy"/><path class="qxlqd4byz"/><path class="dfx_3jruf"/><path class="c4jetlbgt"/><path class="ko6o-6b9b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:target-broken" /></template>
<style>
.c4jetlbgt {
  stroke-linejoin: round;
  d: path("M12 14L12 12L12 10");
}

.dfx_3jruf {
  stroke-linejoin: round;
  d: path("M10 12H12H14");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ko6o-6b9b {
  d: path("M7 3.33782C8.47087 2.48697 10.1786 2 12 2C17.5228 2 22 6.47715 22 12C22 17.5228 17.5228 22 12 22C6.47715 22 2 17.5228 2 12C2 10.1786 2.48697 8.47087 3.33782 7");
}

.p-3e8ccvy {
  d: path("M12 22L12 19");
}

.qxlqd4byz {
  d: path("M12 5L12 2");
}

.vkw41wbkd {
  d: path("M19 12L22 12");
}

.w5kufji0i {
  d: path("M2 12L5 12");
}

</style>
