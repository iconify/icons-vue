<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="hrerymbpr"/><path class="w7kufcb8h"/><path class="w7yq6qg8d"/><path class="jf-uovv_h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:washing-machine-duotone" /></template>
<style>
.hrerymbpr {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M7 1L17 1C19.2092 1 21 2.7908 21 5L21 19C21 21.2092 19.2092 23 17 23L7 23C4.7908 23 3 21.2092 3 19L3 5C3 2.7908 4.7908 1 7 1Z");
  stroke: none;
}

.jf-uovv_h {
  fill: currentColor;
  d: path("M9 6C9 6.5523 8.5523 7 8 7C7.4477 7 7 6.5523 7 6C7 5.4477 7.4477 5 8 5C8.5523 5 9 5.4477 9 6Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.w7kufcb8h {
  fill: currentColor;
  d: path("M17 14C17 16.7614 14.7614 19 12 19C9.2386 19 7 16.7614 7 14C7 11.2386 9.2386 9 12 9C14.7614 9 17 11.2386 17 14Z");
  stroke: none;
}

.w7yq6qg8d {
  d: path("M12 6L16 6");
}

</style>
