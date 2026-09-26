<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zl5ni9bgm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:sparkle-sharp-duotone" /></template>
<style>
.zl5ni9bgm {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 3L14.7896 9.2104L21 12L14.7896 14.7896L12 21L9.2104 14.7896L3 12L9.2104 9.2104L12 3Z");
}

</style>
