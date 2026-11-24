<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="npwqlgbwd"/><path class="xf4lv1b1j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:phone-record-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.npwqlgbwd {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 3a1 1 0 0 1 1-1h6c.409 0 .777.249.928.629l2 5a1 1 0 0 1-.221 1.078L9.414 11L13 14.586l2.293-2.293a1 1 0 0 1 1.078-.221l5 2c.38.151.629.519.629.928v6a1 1 0 0 1-1 1h-2C9.611 22 2 14.389 2 5Z");
}

.xf4lv1b1j {
  d: path("M14.028 5.523a4 4 0 1 1 7.942.954a4 4 0 0 1-7.942-.954M20 6.001V6a2 2 0 1 0-4-.002a2 2 0 0 0 4 .003M18 5h.01a1 1 0 0 1 0 2H18a1 1 0 0 1 0-2");
}

</style>
