<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xsm1_jstp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:test-tubes-sharp" /></template>
<style>
.xsm1_jstp {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 2L9 2L9 19C9 20.6569 7.6569 22 6 22C4.3431 22 3 20.6569 3 19L3 2ZM1 2L11 2M3 13L9 13M15 2L21 2L21 19C21 20.6569 19.6569 22 18 22C16.3431 22 15 20.6569 15 19L15 2ZM13 2L23 2M15 16L21 16");
}

</style>
