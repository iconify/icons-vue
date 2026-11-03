<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k4qx48fws"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:repeat-off-sharp-fill" /></template>
<style>
.k4qx48fws {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 13L3 6L6 6M18 18L3 18M6.2929 21.2929L3 18L6.2929 14.7071M10.6569 6L21 6M17.7071 2.7071L21 6L17.7071 9.2929M21 11L21 16.3431M1.7071 1.7071L22.2929 22.2929");
}

</style>
