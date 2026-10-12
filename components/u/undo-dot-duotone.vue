<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="le57-mato"/><path class="kdyns6but"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:undo-dot-duotone" /></template>
<style>
.kdyns6but {
  fill: currentColor;
  d: path("M12.5 17C12.5 18.1046 11.6046 19 10.5 19C9.3954 19 8.5 18.1046 8.5 17C8.5 15.8954 9.3954 15 10.5 15C11.6046 15 12.5 15.8954 12.5 17Z");
  stroke: none;
}

.le57-mato {
  stroke-opacity: 0.4;
  d: path("M22 18C22 11.6487 16.8513 6.5 10.5 6.5C7.45 6.5 4.5249 7.7116 2.3683 9.8683M2 6L2 9.7365C2 10.0127 2.2239 10.2365 2.5 10.2365L6.2365 10.2365");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
