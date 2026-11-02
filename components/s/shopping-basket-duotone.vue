<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="nfnl2e3nl"/><path class="fiqgz4b1c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:shopping-basket-duotone" /></template>
<style>
.fiqgz4b1c {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 10h18M4 10l2 8c.294 1.175 1.118 2 2 2h8c.882 0 1.706-.825 2-2l2-8m-10 0v10m4-10v10M5 10l4-6m10 6l-4-6");
}

.ft5dv1b6b {
  fill: none;
}

.nfnl2e3nl {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M4 9h16a.998.998 0 0 1 .97 1.243l-2 8c-.178.713-.52 1.382-1.043 1.905c-.511.511-1.195.852-1.927.852H8c-.732 0-1.416-.341-1.927-.852c-.523-.523-.865-1.192-1.043-1.905l-2-8A.998.998 0 0 1 4 9");
}

</style>
