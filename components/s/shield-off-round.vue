<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m_3dwbc1d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:shield-off-round" /></template>
<style>
.m_3dwbc1d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10 3h6a4 4 0 0 1 4 4v3c0 .958-.106 1.855-.305 2.695m-1.952 4.048C16.3 18.59 14.279 19.987 12 21c-4.5-2-8-5.5-8-11V7c0-1.105.448-2.105 1.172-2.828M3 2l19 19");
}

</style>
