<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="c-0yq4b9y"/><path class="d790fjbkx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:medical-cross-duotone-sharp" /></template>
<style>
.c-0yq4b9y {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m14 8.536l4.794-2.768l2 3.464L16 12l4.794 2.768l-2 3.464L14 15.464V21h-4v-5.536l-4.794 2.768l-2-3.464L8 12L3.206 9.232l2-3.464L10 8.536V3h4Z");
}

.d790fjbkx {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m14 8.536l4.794-2.768l2 3.464L16 12l4.794 2.768l-2 3.464L14 15.464V21h-4v-5.536l-4.794 2.768l-2-3.464L8 12L3.206 9.232l2-3.464L10 8.536V3h4z");
}

.ft5dv1b6b {
  fill: none;
}

</style>
