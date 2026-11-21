<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ahihb4qon"/><path class="o9905acwr"/><path class="uaqsiob9y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:postcard-duotone" /></template>
<style>
.ahihb4qon {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12 3L19 3C21.2092 3 23 4.7908 23 7L23 17C23 19.2092 21.2092 21 19 21L5 21C2.7908 21 1 19.2092 1 17L1 7C1 4.7908 2.7908 3 5 3Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.o9905acwr {
  fill: currentColor;
  d: path("M16 7L17 7C18.1046 7 19 7.8954 19 9L19 11C19 12.1046 18.1046 13 17 13L15 13C13.8954 13 13 12.1046 13 11L13 9C13 7.8954 13.8954 7 15 7Z");
  stroke: none;
}

.uaqsiob9y {
  d: path("M6 12H10M6 16H14");
}

</style>
