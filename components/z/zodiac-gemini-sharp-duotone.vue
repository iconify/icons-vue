<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jjqaada3c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:zodiac-gemini-sharp-duotone" /></template>
<style>
.jjqaada3c {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M1 4L2 4C5.1686 5.3203 8.5673 6 12 6C15.4327 6 18.8314 5.3203 22 4L23 4M1 20L2 20C5.1686 18.6797 8.5673 18 12 18C15.4327 18 18.8314 18.6797 22 20L23 20M8.5 5.7633L8.5 18.2367M15.5 5.7633L15.5 18.2367");
}

</style>
