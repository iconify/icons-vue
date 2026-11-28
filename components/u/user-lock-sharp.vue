<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="plqif9-su"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:user-lock-sharp" /></template>
<style>
.plqif9-su {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 3C10.6569 3 12 4.3431 12 6C12 7.6569 10.6569 9 9 9C7.3432 9 6 7.6569 6 6C6 4.3431 7.3432 3 9 3ZM12 21L2 21L2 19C2 15.6863 4.6863 13 8 13L12 13M15 16L22 16L22 21L15 21ZM16.5 16L16.5 14C16.5 12.8954 17.3954 12 18.5 12C19.6046 12 20.5 12.8954 20.5 14L20.5 16");
}

</style>
