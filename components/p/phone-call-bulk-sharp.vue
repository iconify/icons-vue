<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="jlrxn6bdq"/><path class="z-6ep7b4i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:phone-call-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.jlrxn6bdq {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 5V3a1 1 0 0 1 1-1h6c.409 0 .777.249.928.629l2 5a1 1 0 0 1-.221 1.078L9.414 11L13 14.586l2.293-2.293a1 1 0 0 1 1.078-.221l5 2c.38.151.629.519.629.928v6a1 1 0 0 1-1 1h-2C9.611 22 2 14.389 2 5");
}

.z-6ep7b4i {
  d: path("M15 2c1.862 0 3.636.731 4.95 2.05a6.9 6.9 0 0 1 1.499 2.225c.366.862.554 1.789.551 2.725a1 1 0 0 1-2 0a4.9 4.9 0 0 0-.393-1.946a5 5 0 0 0-1.071-1.59A4.97 4.97 0 0 0 15 4a1 1 0 0 1 0-2m0 3c1.064 0 2.078.418 2.828 1.172A3.98 3.98 0 0 1 19 9a1 1 0 0 1-2 0c0-.533-.207-1.039-.586-1.414A1.98 1.98 0 0 0 15 7a1 1 0 0 1 0-2");
}

</style>
