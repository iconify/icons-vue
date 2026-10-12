<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iasqw8bhm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:shuffle-2-sharp-fill" /></template>
<style>
.iasqw8bhm {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M2.7071 2.7071L9.8787 9.8787M14.1213 14.1213L20.8243 20.8243M14 21L21 21L21 14M2.7071 21.2929L20.8243 3.1757M14 3L21 3L21 10");
}

</style>
