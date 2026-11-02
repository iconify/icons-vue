<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="az6u_vgrl"/><path class="k8bbaobrq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:plane-landing-duotone-sharp" /></template>
<style>
.az6u_vgrl {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m13.293 15.707l-1.636-1.636l-5.493.915a1 1 0 0 1-.871-.279l-1-1A.998.998 0 0 1 4.4 12.2l3.332-2.499L7.382 9H6a1 1 0 0 1-.707-.293l-1-1a1 1 0 0 1 0-1.414l4-4a1 1 0 0 1 1.414 0l1 1A1 1 0 0 1 11 4v1.382l.701.35L14.2 2.4a.998.998 0 0 1 1.507-.107l1 1a1 1 0 0 1 .279.871l-.915 5.493l1.636 1.636c1.536 1.536 2.951 3.462 1 5.414c-.692.692-1.538 1.096-2.528.899c-1.102-.221-2.116-1.128-2.886-1.899");
}

.ft5dv1b6b {
  fill: none;
}

.k8bbaobrq {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m17 12l-2-2l1-6l-1-1l-3 4l-2-1V4L9 3L5 7l1 1h2l1 2l-4 3l1 1l6-1l2 2c2 2 3 2 4 1s1-2-1-4M3 21h18");
}

</style>
