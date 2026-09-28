<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jn3zg_3ju"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-arrow-in-up-left-sharp" /></template>
<style>
.jn3zg_3ju {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10 17L3 17L3 3L17 3L17 10M21.2929 21.2929L13.1464 13.1464M22 13L13 13L13 22");
}

</style>
