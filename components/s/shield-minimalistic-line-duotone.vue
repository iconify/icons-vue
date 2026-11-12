<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="k_9yvrb1q"/><path class="jtnup6gsa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:shield-minimalistic-line-duotone" /></template>
<style>
.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jtnup6gsa {
  d: path("M12 2C12.8114 2 13.595 2.26824 15.1623 2.80472L15.7351 3.00079C18.7417 4.02996 20.245 4.54465 20.6226 5.08252C21.0001 5.62039 21.0001 7.21918 21.0001 10.4168V11.9914C21.0001 17.6294 16.7611 20.3655 14.1015 21.5273C13.3801 21.8424 13.0193 22 12.0001 22");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.k_9yvrb1q {
  d: path("M11.9999 2C11.1885 2 10.4049 2.26824 8.83765 2.80472L8.26484 3.00079C5.25825 4.02996 3.75503 4.54465 3.37752 5.08252C3 5.62039 3 7.21918 3 10.4168V11.9914C3 17.6294 7.23896 20.3655 9.89856 21.5273C10.62 21.8424 10.9808 22 12 22");
}

</style>
