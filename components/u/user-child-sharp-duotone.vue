<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="lxa420bgg"/><path class="jvcnu76mf"/><path clip-rule="evenodd" class="h-q3l7nwu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:user-child-sharp-duotone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.h-q3l7nwu {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.172 8.828C5.449 8.106 5 7.104 5 6C5 3.791 6.791 2 9 2C11.209 2 13 3.791 13 6C13 8.209 11.209 10 9 10C7.896 10 6.894 9.551 6.172 8.828Z");
  stroke: none;
}

.jvcnu76mf {
  d: path("M11 21H2V19C2 15.686 4.686 13 8 13H10C10.895 13 11.778 13.2 12.585 13.586L13.155 13.857");
}

.lxa420bgg {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M15.879 13.121C15.337 12.579 15 11.828 15 11C15 9.343 16.343 8 18 8C19.657 8 21 9.343 21 11C21 12.657 19.657 14 18 14C17.172 14 16.421 13.663 15.879 13.121ZM18 22H14C13.448 22 13 21.552 13 21V20C13 17.791 14.791 16 17 16H19C21.209 16 23 17.791 23 20V21C23 21.552 22.552 22 22 22H18Z");
  stroke: none;
}

</style>
