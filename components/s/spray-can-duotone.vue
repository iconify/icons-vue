<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="p8_i9sbkw"/><path class="u92u0ougy"/><path clip-rule="evenodd" class="tjkdd-bjz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:spray-can-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.p8_i9sbkw {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M15 8L19 8C21.2092 8 23 9.7908 23 12L23 19C23 21.2092 21.2092 23 19 23L15 23C12.7908 23 11 21.2092 11 19L11 12C11 9.7908 12.7908 8 15 8Z");
}

.tjkdd-bjz {
  fill-rule: evenodd;
  d: path("M3 2C3 2.5523 2.5523 3 2 3C1.4477 3 1 2.5523 1 2C1 1.4477 1.4477 1 2 1C2.5523 1 3 1.4477 3 2ZM3 6C3 6.5523 2.5523 7 2 7C1.4477 7 1 6.5523 1 6C1 5.4477 1.4477 5 2 5C2.5523 5 3 5.4477 3 6ZM3 10C3 10.5523 2.5523 11 2 11C1.4477 11 1 10.5523 1 10C1 9.4477 1.4477 9 2 9C2.5523 9 3 9.4477 3 10ZM7 4C7 4.5523 6.5523 5 6 5C5.4477 5 5 4.5523 5 4C5 3.4477 5.4477 3 6 3C6.5523 3 7 3.4477 7 4ZM7 8C7 8.5523 6.5523 9 6 9C5.4477 9 5 8.5523 5 8C5 7.4477 5.4477 7 6 7C6.5523 7 7 7.4477 7 8ZM11 6C11 6.5523 10.5523 7 10 7C9.4477 7 9 6.5523 9 6C9 5.4477 9.4477 5 10 5C10.5523 5 11 5.4477 11 6Z");
}

.u92u0ougy {
  d: path("M14 9L14 4.6404C14 3.812 14.6716 3.1404 15.5 3.1404C15.6227 3.1404 15.7449 3.1554 15.8638 3.1852L18.485 3.8405C19.3754 4.063 20 4.863 20 5.7808L20 9C20 9.5523 19.5523 10 19 10L15 10C14.4477 10 14 9.5523 14 9Z");
}

</style>
