<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u8md9dkyh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:shield-lock-sharp" /></template>
<style>
.u8md9dkyh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 3h8v7c0 5.5-3.5 9-8 11c-4.5-2-8-5.5-8-11V3zm-3 7h6v4H9Zm1 0V9a2 2 0 1 1 4 0v1");
}

</style>
