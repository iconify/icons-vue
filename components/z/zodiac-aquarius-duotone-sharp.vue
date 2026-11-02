<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lj_v8nkfm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:zodiac-aquarius-duotone-sharp" /></template>
<style>
.lj_v8nkfm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m3 10l3-3l3 3l3-3l3 3l3-3l3 3M3 17l3-3l3 3l3-3l3 3l3-3l3 3");
}

</style>
