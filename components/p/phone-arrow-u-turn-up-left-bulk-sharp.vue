<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="jlrxn6bdq"/><path class="e91t2_m0o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:phone-arrow-u-turn-up-left-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.e91t2_m0o {
  d: path("M17.707 3.707L16.414 5H21a1 1 0 0 1 1 1v3a1 1 0 0 1-2 0V7h-3.586l1.293 1.293a.999.999 0 1 1-1.414 1.414l-3-3a1 1 0 0 1 0-1.414v-.001l3-2.999a.999.999 0 1 1 1.414 1.414");
}

.jlrxn6bdq {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 5V3a1 1 0 0 1 1-1h6c.409 0 .777.249.928.629l2 5a1 1 0 0 1-.221 1.078L9.414 11L13 14.586l2.293-2.293a1 1 0 0 1 1.078-.221l5 2c.38.151.629.519.629.928v6a1 1 0 0 1-1 1h-2C9.611 22 2 14.389 2 5");
}

</style>
