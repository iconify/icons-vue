<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d2ac16b7a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:minus-forward-slash-plus-sharp-fill" /></template>
<style>
.d2ac16b7a {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M13 18H17.999M17.999 18H23M17.999 18L17.997 23M17.999 18L18 13M1 6H11M4.703 22.43L19.3 1.57");
}

</style>
