<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tef4orlbs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:window-awning-open" /></template>
<style>
.tef4orlbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 3H4.8417C4.3553 3 3.9394 3.35 3.8564 3.829L3.0477 8.5L2.3106 12.757C2.1528 13.389 2.6302 14 3.2808 14H4M4 14V21M4 14H12M3.0477 8.5H12M20 14H20.7192C21.3698 14 21.8472 13.389 21.6894 12.757L20.9523 8.5L20.1436 3.829C20.0606 3.35 19.6447 3 19.1583 3H12M12 3V8.5M20 14V21M20 14H12M20.9523 8.5H12M12 8.5V14M2 21H4M4 21H20M20 21H22");
}

</style>
