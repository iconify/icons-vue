<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="x_-55mshj"/><path class="o39ngecar"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:trophy-fill" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.o39ngecar {
  d: path("M9 2H15C16.65685 2 18 3.34315 18 5V9C18 12.31371 15.31371 15 12 15C8.68629 15 6 12.31371 6 9V5C6 3.34315 7.34315 2 9 2ZM6 5H4C2.89543 5 2 5.89543 2 7V9C2 10.10457 2.89543 11 4 11H6M18 5H20C21.10457 5 22 5.89543 22 7V9C22 10.10457 21.10457 11 20 11H18M12 15V19M9 19H15C16.65685 19 18 20.34315 18 22H6C6 20.34315 7.34315 19 9 19Z");
}

.x_-55mshj {
  fill: currentColor;
  d: path("M9 2H15C16.65685 2 18 3.34315 18 5V9C18 12.31371 15.31371 15 12 15C8.68629 15 6 12.31371 6 9V5C6 3.34315 7.34315 2 9 2ZM9 19H15C16.65685 19 18 20.34315 18 22H6C6 20.34315 7.34315 19 9 19Z");
  stroke: none;
}

</style>
