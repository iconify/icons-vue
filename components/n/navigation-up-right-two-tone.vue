<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="p-zpxcbuj"/><path class="u2jyj3rvz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:navigation-up-right-two-tone" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.p-zpxcbuj {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M18.9791 3.07C20.1718 2.76 21.3214 3.89 20.922 5.08L15.9757 19.92C15.5439 21.21 13.7733 21.32 13.0919 20.18L9.9992 14.01L3.8781 10.94C2.6182 10.31 2.7488 8.48 4.0851 8.03L18.9791 3.07Z");
  stroke: none;
}

.u2jyj3rvz {
  d: path("M4.3977 8.98L19.2337 4.03C19.6883 3.88 20.1207 4.31 19.9691 4.77L15.0229 19.6C14.859 20.09 14.1828 20.14 13.951 19.68L10.8281 13.43C10.7718 13.32 10.6806 13.23 10.5681 13.17L4.3214 10.05C3.8581 9.82 3.9062 9.14 4.3977 8.98Z");
}

</style>
