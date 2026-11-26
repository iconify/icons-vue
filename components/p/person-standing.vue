<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a15f3lb4l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:person-standing" /></template>
<style>
.a15f3lb4l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M15 5C15 6.6569 13.6569 8 12 8C10.3431 8 9 6.6569 9 5C9 3.3431 10.3431 2 12 2C13.6569 2 15 3.3431 15 5ZM7 12H17M12 12V17M8 22L12 17L16 22");
}

</style>
