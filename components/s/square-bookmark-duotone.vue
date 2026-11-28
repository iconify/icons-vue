<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="g7r9u8b5f"/><path class="euycknhiy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-bookmark-duotone" /></template>
<style>
.euycknhiy {
  d: path("M8.129 8.613C8.129 7.812 8.779 7.162 9.581 7.162H14.419C15.221 7.162 15.871 7.812 15.871 8.613V16.354C15.871 16.737 15.447 16.968 15.125 16.761L12.392 15.315C12.153 15.161 11.847 15.161 11.608 15.315L8.875 16.761C8.553 16.968 8.129 16.737 8.129 16.354V8.613Z");
}

.g7r9u8b5f {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 6C2 3.791 3.791 2 6 2H18C20.209 2 22 3.791 22 6V18C22 20.209 20.209 22 18 22H6C3.791 22 2 20.209 2 18V6Z");
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
