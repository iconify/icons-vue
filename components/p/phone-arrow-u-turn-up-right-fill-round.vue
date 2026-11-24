<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g92-0qb8d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:phone-arrow-u-turn-up-right-fill-round" /></template>
<style>
.g92-0qb8d {
  fill: currentColor;
  d: path("M21.707 5.293a1 1 0 0 1 0 1.414l-3 3a1 1 0 0 1-1.414-1.414L18.586 7H17a1.997 1.997 0 0 0-2 2a1 1 0 0 1-2 0c0-1.064.418-2.078 1.172-2.828A3.98 3.98 0 0 1 17 5h1.586l-1.293-1.293a1 1 0 0 1 1.414-1.414ZM5 2h1c2.253 0 4.118 1.603 4.928 3.629c.351.877.592 1.812.592 2.761c0 .419-.05.84-.177 1.24a2.65 2.65 0 0 1-.636 1.077a1.123 1.123 0 0 0 0 1.586l2 2a1.123 1.123 0 0 0 1.586 0c.459-.459 1.038-.777 1.651-.982A6.5 6.5 0 0 1 18 13h1c.53 0 1.023.211 1.424.551C21.61 14.555 22 16.522 22 18v1c0 .797-.314 1.558-.879 2.121A3 3 0 0 1 19 22a16.8 16.8 0 0 1-6.617-1.336a16.9 16.9 0 0 1-5.404-3.643a16.9 16.9 0 0 1-3.643-5.404A16.8 16.8 0 0 1 2 5c0-.797.314-1.558.879-2.121A3 3 0 0 1 5 2");
}

</style>
