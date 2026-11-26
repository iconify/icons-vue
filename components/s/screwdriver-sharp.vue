<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r60-u_znp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:screwdriver-sharp" /></template>
<style>
.r60-u_znp {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12.4394 11.5607L13.9381 13.6819L7.1214 21.1213C5.9498 22.2929 4.0503 22.2929 2.8787 21.1213C1.7071 19.9497 1.7071 18.0503 2.8787 16.8787L10.3181 10.0618ZM12.4394 11.5607L17 7M17 7L17 4L21 2L22 3L20 7Z");
}

</style>
