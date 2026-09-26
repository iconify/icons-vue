<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="shc-s7oyr"/><path class="qq128bzey"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:plug-two-tone" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qq128bzey {
  d: path("M8 7L16 7C17.6569 7 19 8.3431 19 10L19 11C19 14.866 15.866 18 12 18C8.134 18 5 14.866 5 11L5 10C5 8.3431 6.3431 7 8 7ZM9 2L9 7M15 2L15 7M12 18L12 22");
}

.shc-s7oyr {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M8 6L16 6C18.2092 6 20 7.7908 20 10L20 11C20 15.4183 16.4183 19 12 19C7.5817 19 4 15.4183 4 11L4 10C4 7.7908 5.7908 6 8 6Z");
  stroke: none;
}

</style>
