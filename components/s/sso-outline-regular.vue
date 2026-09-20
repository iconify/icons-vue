<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="hvxngl_cs"/><path class="bfl7ipbld"/><path class="e1-kupvjo"/><path class="b0jxq8rov"/><path class="fiap06mao"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:sso-outline-regular" /></template>
<style>
.b0jxq8rov {
  d: path("M15 4a2 2 0 0 1 2 -2h3a2 2 0 0 1 2 2v4a2 2 0 0 1 -2 2h-3a2 2 0 0 1 -2 -2Z");
}

.bfl7ipbld {
  d: path("M8 12h4V6h3");
}

.e1-kupvjo {
  d: path("M12 12v6h3");
}

.fiap06mao {
  d: path("M15 16a2 2 0 0 1 2 -2h3a2 2 0 0 1 2 2v4a2 2 0 0 1 -2 2h-3a2 2 0 0 1 -2 -2Z");
}

.hvxngl_cs {
  d: path("M2 12a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
