<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oqsfp-dcl"/><path class="j3avj9arr"/><path class="w0i40obbd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-content-paste-search" /></template>
<style>
.j3avj9arr {
  fill: currentColor;
  d: path("M10.5 19H5V5h2v3h10V5h2v5.5c.75.31 1.42.76 2 1.32V5c0-1.1-.9-2-2-2h-4.18C14.4 1.84 13.3 1 12 1s-2.4.84-2.82 2H5c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h6.82a6.6 6.6 0 0 1-1.32-2M12 3c.55 0 1 .45 1 1s-.45 1-1 1s-1-.45-1-1s.45-1 1-1");
}

.oqsfp-dcl {
  fill: currentColor;
  d: path("M10 16.5c0-3.58 2.92-6.5 6.5-6.5c.89 0 1.73.18 2.5.5V5h-2v3H7V5H5v14h5.5c-.32-.77-.5-1.61-.5-2.5");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.w0i40obbd {
  fill: currentColor;
  d: path("M20.3 18.9c.4-.7.7-1.5.7-2.4c0-2.5-2-4.5-4.5-4.5S12 14 12 16.5s2 4.5 4.5 4.5c.9 0 1.7-.3 2.4-.7l2.7 2.7l1.4-1.4zm-3.8.1c-1.4 0-2.5-1.1-2.5-2.5s1.1-2.5 2.5-2.5s2.5 1.1 2.5 2.5s-1.1 2.5-2.5 2.5");
}

</style>
