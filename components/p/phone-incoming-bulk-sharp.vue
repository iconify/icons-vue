<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="jlrxn6bdq"/><path class="zvk288b7k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:phone-incoming-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.jlrxn6bdq {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 5V3a1 1 0 0 1 1-1h6c.409 0 .777.249.928.629l2 5a1 1 0 0 1-.221 1.078L9.414 11L13 14.586l2.293-2.293a1 1 0 0 1 1.078-.221l5 2c.38.151.629.519.629.928v6a1 1 0 0 1-1 1h-2C9.611 22 2 14.389 2 5");
}

.zvk288b7k {
  d: path("M14 9V5a1 1 0 0 1 2 0v1.586l4.293-4.293a.999.999 0 1 1 1.414 1.414L17.414 8H19a1 1 0 0 1 0 2h-4a1 1 0 0 1-1-1");
}

</style>
