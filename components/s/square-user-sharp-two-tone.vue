<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="cmnquvbgz"/><path class="o0ubd-spe"/><path clip-rule="evenodd" class="fg1ylussd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-user-sharp-two-tone" /></template>
<style>
.cmnquvbgz {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12 2H21C21.552 2 22 2.4477 22 3V21C22 21.5523 21.552 22 21 22H3C2.448 22 2 21.5523 2 21V3C2 2.4477 2.448 2 3 2H12Z");
  stroke: none;
}

.fg1ylussd {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M14.121 11.1213C13.579 11.6631 12.828 12 12 12C10.343 12 9 10.6569 9 9C9 7.3431 10.343 6 12 6C13.657 6 15 7.3431 15 9C15 9.8282 14.663 10.5795 14.121 11.1213ZM6 20V19C6 16.2386 8.239 14 11 14H13C15.761 14 18 16.2386 18 19V20H6Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.o0ubd-spe {
  d: path("M3 3H21V21H3V3Z");
}

</style>
