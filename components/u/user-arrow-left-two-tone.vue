<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="lj5jgub7q"/><path class="b8qyyibai"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:user-arrow-left-two-tone" /></template>
<style>
.b8qyyibai {
  d: path("M22 7H16M19 4L16 7L19 10M8 14H10C13.3137 14 16 16.6863 16 20C16 20.5523 15.5523 21 15 21H3C2.44772 21 2 20.5523 2 20C2 16.6863 4.68629 14 8 14ZM9 4C10.6569 4 12 5.34315 12 7C12 8.65685 10.6569 10 9 10C7.34315 10 6 8.65685 6 7C6 5.34315 7.34315 4 9 4Z");
}

.lj5jgub7q {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M8 13L10 13C13.866 13 17 16.134 17 20C17 21.1046 16.1046 22 15 22L3 22C1.8954 22 1 21.1046 1 20C1 16.134 4.134 13 8 13ZM13 7C13 9.2091 11.2091 11 9 11C6.7909 11 5 9.2091 5 7C5 4.7909 6.7909 3 9 3C11.2091 3 13 4.7909 13 7Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
