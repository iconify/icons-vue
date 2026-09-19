<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l42o6d3xm"/><path class="v4_nrzlpr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-view-sidebar" /></template>
<style>
.l42o6d3xm {
  fill: currentColor;
  d: path("M20 8.67h-2.5V6H20zm-2.5 2H20v2.67h-2.5zM4 6h11.5v12H4zm13.5 12v-2.67H20V18z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.v4_nrzlpr {
  fill: currentColor;
  d: path("M2 4v16h20V4zm18 4.67h-2.5V6H20zm-2.5 2H20v2.67h-2.5zM4 6h11.5v12H4zm13.5 12v-2.67H20V18z");
}

</style>
