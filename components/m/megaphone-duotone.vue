<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="a83sk_bez"/><path class="ye9frhb-l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:megaphone-duotone" /></template>
<style>
.a83sk_bez {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M18.553 3.106c.356-.181.75-.274 1.149-.273C20.924 2.836 22 3.735 22 5v12c0 1.265-1.076 2.164-2.298 2.167a2.5 2.5 0 0 1-1.149-.273l-8-4A1 1 0 0 1 10 14V8c0-.379.214-.725.553-.894Z");
}

.ft5dv1b6b {
  fill: none;
}

.ye9frhb-l {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m11 8l8-4c.919-.46 2 .081 2 1v12c0 .919-1.081 1.46-2 1l-8-4zm0 0H5a2 2 0 0 0-2 2v2a2 2 0 0 0 2 2h6m-6 0v5a2 2 0 1 0 4 0v-5");
}

</style>
