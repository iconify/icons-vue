<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k-q6n55ea"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:zap-flame-alt-round" /></template>
<style>
.k-q6n55ea {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7.333 11.333L4.61 14.057c-.274.275-.737.02-.653-.359l.827-3.722A.802.802 0 0 0 4 9a.65.65 0 0 1-.594-.914l1.909-4.294A1.33 1.33 0 0 1 6.533 3H9c.594 0 .967.642.672 1.158L8.328 6.509A.774.774 0 0 0 9 7.667h.667c.492 0 .738.595.39.942zM16 21c-5.667-4.667-1.667-8.667 1-12c2.667 3.333 6.667 7.333 1 12Zm0 0c-3-2.333-1.667-4.333 1-6.667c2.667 2.334 4 4.334 1 6.667");
}

</style>
