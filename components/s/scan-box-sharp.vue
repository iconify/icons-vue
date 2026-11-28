<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wtzx0ccci"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:scan-box-sharp" /></template>
<style>
.wtzx0ccci {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 9L3 3L9 3M15 3L21 3L21 9M21 15L21 21L15 21M9 21L3 21L3 15M7 9.4239L12 12M12 12L17 9.4239M12 12L12 17M12 7L17 9.4239L17 14.5761L12 17L7 14.5761L7 9.4239L12 7Z");
}

</style>
