<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path clip-rule="evenodd" class="fsumcib-j"/><path class="t00ook01h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:person-standing-fill" /></template>
<style>
.fsumcib-j {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M14.8284 7.8284C14.1057 8.5512 13.1043 9 12 9C9.7908 9 8 7.2092 8 5C8 2.7908 9.7908 1 12 1C14.2092 1 16 2.7908 16 5C16 6.1043 15.5512 7.1057 14.8284 7.8284Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.t00ook01h {
  d: path("M7 12H17M12 12V17M8 22L12 17L16 22");
}

</style>
