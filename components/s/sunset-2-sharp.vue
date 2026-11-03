<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ut3lb8bjs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:sunset-2-sharp" /></template>
<style>
.ut3lb8bjs {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M1.7241 14.7897L2 14.5C2.9123 13.5421 4.1772 13 5.5 13C6.8228 13 8.0877 13.5421 9 14.5C9.9123 15.4579 11.1772 16 12.5 16C13.8228 16 15.0877 15.4579 16 14.5C16.9123 13.5421 18.1772 13 19.5 13C20.4 13 21.3 13.25 22 13.7L22.4592 13.9952M1.7241 19.7897L2 19.5C2.9123 18.5421 4.1772 18 5.5 18C6.8228 18 8.0877 18.5421 9 19.5C9.9123 20.4579 11.1772 21 12.5 21C13.8228 21 15.0877 20.4579 16 19.5C16.9123 18.5421 18.1772 18 19.5 18C20.4 18 21.3 18.25 22 18.7L22.4592 18.9952M4.295 13.1526C4.0993 12.4518 4 11.7276 4 11C4 6.5817 7.5817 3 12 3C16.4183 3 20 6.5817 20 11C20 11.6768 19.9141 12.3509 19.7444 13.0061");
}

</style>
