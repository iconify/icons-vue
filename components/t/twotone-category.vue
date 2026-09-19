<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="m5gn77coh"/><path class="wtz_r3x1x"/><path class="jo2uq8b5p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-category" /></template>
<style>
.jo2uq8b5p {
  fill: currentColor;
  d: path("m12 2l-5.5 9h11zm0 3.84L13.93 9h-3.87zM17.5 13c-2.49 0-4.5 2.01-4.5 4.5s2.01 4.5 4.5 4.5s4.5-2.01 4.5-4.5s-2.01-4.5-4.5-4.5m0 7a2.5 2.5 0 0 1 0-5a2.5 2.5 0 0 1 0 5M11 13.5H3v8h8zm-2 6H5v-4h4z");
}

.m5gn77coh {
  cx: 17.5px;
  cy: 17.5px;
  r: 2.5px;
  fill: currentColor;
  opacity: var(--svg-opacity--0-3, 0.3);
}

.wtz_r3x1x {
  fill: currentColor;
  d: path("M5 15.5h4v4H5zm7-9.66L10.07 9h3.86z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
