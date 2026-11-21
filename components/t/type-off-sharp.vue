<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i3o7etb4m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:type-off-sharp" /></template>
<style>
.i3o7etb4m {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M1.7071 1.7071L2 2L22 22L22.2929 22.2929M4 7L4 6L4 5C4 4.7065 4.0632 4.4278 4.1767 4.1767M7.6569 3L8.6569 3L20 3L20 6L20 7M12 3L12 6.3431L12 7.3431M12 21L12 12M7.6569 21L8.6569 21L15.3431 21L16.3431 21");
}

</style>
