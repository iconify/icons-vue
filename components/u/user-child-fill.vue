<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="x94sxebue"/><path clip-rule="evenodd" class="a0jvvwj3s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:user-child-fill" /></template>
<style>
.a0jvvwj3s {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11.828 3.172C12.551 3.894 13 4.896 13 6C13 8.209 11.209 10 9 10C6.791 10 5 8.209 5 6C5 3.791 6.791 2 9 2C10.104 2 11.106 2.449 11.828 3.172ZM15.879 13.121C15.337 12.58 15 11.828 15 11C15 9.343 16.343 8 18 8C19.657 8 21 9.343 21 11C21 12.657 19.657 14 18 14C17.172 14 16.42 13.663 15.879 13.121ZM18 22H15C13.895 22 13 21.105 13 20C13 17.791 14.791 16 17 16H19C21.209 16 23 17.791 23 20C23 21.105 22.105 22 21 22H18Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.x94sxebue {
  d: path("M10.101 21H3C2.448 21 2 20.552 2 20V19C2 15.686 4.686 13 8 13H10C10.895 13 11.778 13.2 12.585 13.586");
}

</style>
