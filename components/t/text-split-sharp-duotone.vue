<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xc7aorpfn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:text-split-sharp-duotone" /></template>
<style>
.xc7aorpfn {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M1 7L12 7M3 12L12 12M5 17L12 17M12 3L12 21M15 7L19 7M15 12L21 12M15 17L23 17");
}

</style>
