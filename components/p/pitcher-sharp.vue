<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="grluslo_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:pitcher-sharp" /></template>
<style>
.grluslo_q {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M2.0005 4L18 4L16 20L8 20L6.5 8ZM17.5 8L18 8C20.2091 8 22 9.7909 22 12C22 14.2091 20.2091 16 18 16L16.5 16M7 12L17 12");
}

</style>
