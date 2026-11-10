<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wb99c8e4b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:pants-sharp" /></template>
<style>
.wb99c8e4b {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M18.602 7.06L20.995 21.08L15.902 22L12.049 10.27L8.003 22L3.004 20.99L5.397 7.06L5.594 6.05L6.382 2H17.617L18.405 6.05L18.602 7.06ZM5.397 7.06H18.602");
}

</style>
