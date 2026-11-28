<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tyasve7-q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:ruler-sharp" /></template>
<style>
.tyasve7-q {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4.929 13.414L8.465 16.95M7.757 10.586L10.232 13.061M10.586 7.757L14.121 11.293M13.414 4.929L15.889 7.404M2 16.343L16.343 2L22 7.657L7.657 22L2 16.343Z");
}

</style>
