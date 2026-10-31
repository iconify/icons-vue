<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="i5h8q2-fz"/><path clip-rule="evenodd" class="j-4jyqbyy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:shower-head-sharp" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.i5h8q2-fz {
  d: path("M4 23L4 7C4 4.2386 6.2386 2 9 2C11.7614 2 14 4.2386 14 7M8 13C8 9.6863 10.6863 7 14 7C17.3137 7 20 9.6863 20 13Z");
}

.j-4jyqbyy {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11 17C11 17.5523 10.5523 18 10 18C9.4477 18 9 17.5523 9 17C9 16.4477 9.4477 16 10 16C10.5523 16 11 16.4477 11 17ZM15 17C15 17.5523 14.5523 18 14 18C13.4477 18 13 17.5523 13 17C13 16.4477 13.4477 16 14 16C14.5523 16 15 16.4477 15 17ZM19 17C19 17.5523 18.5523 18 18 18C17.4477 18 17 17.5523 17 17C17 16.4477 17.4477 16 18 16C18.5523 16 19 16.4477 19 17ZM13 21C13 21.5523 12.5523 22 12 22C11.4477 22 11 21.5523 11 21C11 20.4477 11.4477 20 12 20C12.5523 20 13 20.4477 13 21ZM17 21C17 21.5523 16.5523 22 16 22C15.4477 22 15 21.5523 15 21C15 20.4477 15.4477 20 16 20C16.5523 20 17 20.4477 17 21Z");
  stroke: none;
}

</style>
