<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="g0othl66k"/><circle class="v0v8ezffz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:petal-sharp" /></template>
<style>
.g0othl66k {
  d: path("m12.56 9.05l1.08-1.35l.56-.7l-.16-.89l-.28-1.57l-.16-.89l-.76.48l-.08.04l-.76.48l-.76-.48l-.08-.04l-.76-.48l-.16.89l-.28 1.57L9.8 7l.56.7l1.08 1.35l.56.7zm2.66 2.74l1.61.61l.84.32l.8-.42l1.41-.76l.79-.43l-.69-.57l-.06-.06l-.69-.58l.22-.87l.02-.09l.21-.87l-.89.12l-1.59.22l-.89.13l-.49.75l-.95 1.44l-.49.75zm-1.79 3.38l-.08 1.72l-.04.9l.65.62l1.15 1.11l.65.63l.34-.84l.03-.08l.34-.83l.89-.06l.09-.01l.9-.06l-.39-.81l-.7-1.45l-.39-.81l-.87-.23l-1.66-.46l-.87-.24zm-3.77-.66L8 14.97l-.87.23l-.39.81l-.7 1.45l-.39.81l.9.06l.09.01l.89.06l.34.83l.03.08l.34.84l.65-.63l1.15-1.11l.65-.62l-.04-.9l-.08-1.72l-.04-.9zm-.53-3.78l-.95-1.44l-.49-.75l-.89-.13l-1.59-.22l-.89-.12l.21.87l.02.09l.22.87l-.69.58l-.06.06l-.69.57l.79.43l1.41.76l.8.42l.84-.32l1.61-.61l.84-.31zM12 8.75v-1.5m3.33 3.92l1.43-.47m-2.7 4.38l.88 1.22m-5-1.22l-.88 1.22m-.39-5.13l-1.43-.47");
}

.v0v8ezffz {
  cx: 12px;
  cy: 12.25px;
  r: 1.25px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
