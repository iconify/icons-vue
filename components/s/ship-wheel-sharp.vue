<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d0_-r_dum"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:ship-wheel-sharp" /></template>
<style>
.d0_-r_dum {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M19 12C19 15.866 15.866 19 12 19C8.134 19 5 15.866 5 12C5 8.134 8.134 5 12 5C15.866 5 19 8.134 19 12ZM12 1L12 2L12 22L12 23M21.5 6.5151L21 6.8038L3 17.1962L2.5 17.4849M21.5 17.4849L21 17.1962L3 6.8038L2.5 6.5151");
}

</style>
