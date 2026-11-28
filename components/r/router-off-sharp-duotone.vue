<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="eqkyffb6j"/><path class="tslw_dbxz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:router-off-sharp-duotone" /></template>
<style>
.eqkyffb6j {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M20.88 21H2C1.448 21 1 20.5523 1 20V12C1 11.4477 1.448 11 2 11H5.719L4.363 5.5758L5.237 5.3573L6.748 6.8676L7.781 11H10.88L20.88 21ZM9 16C9 15.4477 8.552 15 8 15C7.448 15 7 15.4477 7 16C7 16.5523 7.448 17 8 17C8.552 17 9 16.5523 9 16ZM18.281 11H22C22.552 11 23 11.4477 23 12V19.3431L14.657 11H16.219L18.219 3L20.16 3.485L18.281 11Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.tslw_dbxz {
  d: path("M1.707 1.7071L22.293 22.293");
}

</style>
