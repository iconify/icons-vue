<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="jlrxn6bdq"/><path class="n85wj0l0g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:phone-arrow-u-turn-up-right-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.jlrxn6bdq {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 5V3a1 1 0 0 1 1-1h6c.409 0 .777.249.928.629l2 5a1 1 0 0 1-.221 1.078L9.414 11L13 14.586l2.293-2.293a1 1 0 0 1 1.078-.221l5 2c.38.151.629.519.629.928v6a1 1 0 0 1-1 1h-2C9.611 22 2 14.389 2 5");
}

.n85wj0l0g {
  d: path("m18.707 2.293l3 3a1 1 0 0 1 0 1.414l-3 3a1 1 0 0 1-1.414-1.414L18.586 7H15v2a1 1 0 0 1-2 0V6a1 1 0 0 1 1-1h4.586l-1.293-1.293a1 1 0 0 1 1.414-1.414");
}

</style>
