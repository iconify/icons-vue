<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zzdqscb8m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:moon-z-sharp" /></template>
<style>
.zzdqscb8m {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M20 13C20 17.9706 15.9706 22 11 22C6.0294 22 2 17.9706 2 13C2 8.0294 6.0294 4 11 4C8.9618 6.5477 9.1652 10.2206 11.4723 12.5277C13.7794 14.8348 17.4523 15.0382 20 13ZM23 9L22 9L16 9L21.9975 2L16.5 2L15.5 2");
}

</style>
