<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ie2bwtaqz"/><path class="xui4u5txw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:parallelogram-two-tone" /></template>
<style>
.ie2bwtaqz {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M13.5623 3L18.9977 3C21.696 3 23.6201 5.6173 22.8152 8.1931L19.6906 18.1931C19.1687 19.8631 17.6224 21 15.8731 21L5.0023 21C2.304 21 0.3799 18.3827 1.1848 15.8069L4.3094 5.8069C4.8313 4.1369 6.3776 3 8.1269 3Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.xui4u5txw {
  d: path("M5.2631 6.1052C5.6545 4.8527 6.8144 4 8.1265 4L18.9985 4C21.0224 4 22.4656 5.963 21.8619 7.8948L18.7369 17.8948C18.3455 19.1473 17.1856 20 15.8735 20L5.0015 20C2.9776 20 1.5344 18.037 2.1381 16.1052Z");
}

</style>
