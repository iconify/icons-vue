<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="xkmafkb6z"/><path class="tkdid9ndg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:thermometer-sharp-duotone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.tkdid9ndg {
  d: path("M5.5355 18.4645L2 22L1.7071 22.2929M15.4645 2.8787L17.8787 5.2929M12.636 5.7071L15.0503 8.1213M9.8076 8.5355L12.2218 10.9497");
}

.xkmafkb6z {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M16.1716 2.1716C16.9217 1.4214 17.9391 1 19 1C21.2091 1 23 2.7909 23 5C23 6.0609 22.5786 7.0783 21.8284 7.8284L10.4852 19.1716C9.7351 19.9218 8.7177 20.3432 7.6568 20.3432C5.4477 20.3432 3.6568 18.5523 3.6568 16.3432C3.6568 15.2823 4.0782 14.2649 4.8284 13.5148L16.1716 2.1716Z");
  stroke: none;
}

</style>
