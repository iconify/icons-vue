<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i7y1jabpt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:phone-incoming-sharp" /></template>
<style>
.i7y1jabpt {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M2 4L2 2L9 2L9 8L7.0953 9.4285C8.5144 12.802 11.198 15.4856 14.5715 16.9047L16 15L22 15L22 22L20 22C10.0589 22 2 13.9411 2 4ZM16.1464 7.8536L21.2929 2.7071M16 1L16 8L23 8");
}

</style>
