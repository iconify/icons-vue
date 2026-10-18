<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ja7jswbmn"/><path class="d6oj2_bsc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:play-pause-fill" /></template>
<style>
.d6oj2_bsc {
  d: path("M17 6L17 18M22 6L22 18");
}

.ja7jswbmn {
  fill: currentColor;
  d: path("M1 7.5C1 6.1193 2.1193 5 3.5 5C4.0018 5 4.4919 5.151 4.9067 5.4333L12.1253 10.3466C12.6725 10.7191 13 11.3381 13 12C13 12.6619 12.6725 13.2809 12.1253 13.6534L4.9067 18.5667C4.4919 18.849 4.0018 19 3.5 19C2.1193 19 1 17.8807 1 16.5L1 7.5Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
