<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="ttdo8acwz"/><path class="vf4d7ebea"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-monotone:o-button" /></template>
<style>
.ttdo8acwz {
  fill: currentColor;
  d: path("M32 21.053c-6.036 0-10.947 4.91-10.947 10.947c0 6.035 4.911 10.947 10.947 10.947S42.947 38.035 42.947 32c0-6.037-4.911-10.947-10.947-10.947");
}

.vf4d7ebea {
  fill: currentColor;
  d: path("M52 2H12C6.477 2 2 6.477 2 12v40c0 5.523 4.477 10 10 10h40c5.523 0 10-4.477 10-10V12c0-5.523-4.477-10-10-10M32 48c-8.822 0-16-7.178-16-16c0-8.82 7.178-16 16-16s16 7.18 16 16c0 8.822-7.178 16-16 16");
}

</style>
