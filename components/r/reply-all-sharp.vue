<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pxh_3sbpn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:reply-all-sharp" /></template>
<style>
.pxh_3sbpn {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8.2929 3.7071L2 10L8.2929 16.2929M14.2929 3.7071L8 10L14.2929 16.2929M8 10L22 10L22 21");
}

</style>
