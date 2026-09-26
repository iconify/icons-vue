<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="usyatnmym"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:message-square-sparkle-sharp" /></template>
<style>
.usyatnmym {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 3L21 3L21 17L7 17L3 21L3 3ZM12 7.0093L13.128 8.872L14.9907 10L13.128 11.128L12 12.9907L10.872 11.128L9.0093 10L10.872 8.872L12 7.0093Z");
}

</style>
