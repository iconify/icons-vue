<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uw09byb_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:rotate-cw-square-sharp" /></template>
<style>
.uw09byb_p {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9.312 1.73L12 4.25L9.284 6.8M12 4.25H4V10M9 22V11H20V22H9Z");
}

</style>
