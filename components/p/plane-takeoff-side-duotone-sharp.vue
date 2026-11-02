<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="a9s5hccap"/><path class="ichncc4ym"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:plane-takeoff-side-duotone-sharp" /></template>
<style>
.a9s5hccap {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m6.764 12l.894-.447l-2.105-4.211a2 2 0 0 1-.109-1.527a2 2 0 0 1 1.003-1.157l.461-.23a2 2 0 0 1 2.309.375l3.98 3.98l5.909-2.954A2 2 0 0 1 22 7.618v1.764a2 2 0 0 1-1.106 1.789L7.658 17.789c-.277.14-.583.212-.894.211H5.618a2 2 0 0 1-1.789-1.106l-1-2A2 2 0 0 1 4.618 12Z");
}

.ft5dv1b6b {
  fill: none;
}

.ichncc4ym {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m7 13l2-1l-2.553-5.106a1 1 0 0 1 .447-1.341l.461-.23a1 1 0 0 1 1.155.187L13 10l6.553-3.276A1 1 0 0 1 21 7.618v1.764a1 1 0 0 1-.553.894L7.211 16.894a1 1 0 0 1-.447.106H5.618a1 1 0 0 1-.894-.553l-1-2A1 1 0 0 1 4.618 13zm-4 8h18");
}

</style>
