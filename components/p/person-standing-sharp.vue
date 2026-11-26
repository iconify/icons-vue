<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n-l02fbok"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:person-standing-sharp" /></template>
<style>
.n-l02fbok {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M15 5C15 6.6569 13.6569 8 12 8C10.3431 8 9 6.6569 9 5C9 3.3431 10.3431 2 12 2C13.6569 2 15 3.3431 15 5ZM6 12L18 12M12 12L12 17M7.6998 22.3753L12 17L16.3002 22.3753");
}

</style>
