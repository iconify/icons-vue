<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z7wo566qp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-sigma-duotone" /></template>
<style>
.z7wo566qp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 6C3 4.3431 4.3431 3 6 3L18 3C19.6569 3 21 4.3431 21 6L21 18C21 19.6569 19.6569 21 18 21L6 21C4.3431 21 3 19.6569 3 18ZM15.3282 7.0077L9.2276 7.0077C8.765 7.0077 8.5057 7.5404 8.7909 7.9045L11.7319 11.6579C11.8893 11.8588 11.8893 12.1412 11.7319 12.3421L8.7909 16.0955C8.5057 16.4596 8.765 16.9923 9.2276 16.9923L15.3282 16.9923");
}

</style>
