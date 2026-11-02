<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="z8mk4x2rh"/><path class="mn39akbeo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:shopping-cart-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.mn39akbeo {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 4c.752 0 1.549.797 2 2l3 8c.451 1.203 1.248 2 2 2h7c.882 0 1.706-.825 2-2l1-4c.254-1.016-.238-2-1-2H6m2 12a1 1 0 1 0 2 0a1 1 0 0 0-2 0m9 0a1 1 0 1 0 2 0a1 1 0 0 0-2 0");
}

.z8mk4x2rh {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M5.75 7H19c.397 0 .779.127 1.1.36c.885.641 1.123 1.869.87 2.883l-1 4c-.178.713-.52 1.382-1.043 1.905c-.511.511-1.195.852-1.927.852h-7c-.699 0-1.336-.358-1.82-.842c-.506-.506-.866-1.14-1.116-1.807l-2.25-6A1 1 0 0 1 5.75 7");
}

</style>
