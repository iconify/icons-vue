<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="uh-6pmc_e"/><path class="kdyns6but"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:undo-dot-sharp-duotone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.kdyns6but {
  fill: currentColor;
  d: path("M12.5 17C12.5 18.1046 11.6046 19 10.5 19C9.3954 19 8.5 18.1046 8.5 17C8.5 15.8954 9.3954 15 10.5 15C11.6046 15 12.5 15.8954 12.5 17Z");
  stroke: none;
}

.uh-6pmc_e {
  stroke-opacity: 0.4;
  d: path("M22 19L22 18C22 11.6487 16.8513 6.5 10.5 6.5C7.45 6.5 4.5249 7.7116 2.3683 9.8683L2 10.2365M2 5L2 10.2365L7.2365 10.2365");
}

</style>
