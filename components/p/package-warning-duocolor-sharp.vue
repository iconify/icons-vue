<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="i8lrfn7rs"/><path class="s7e_ee__v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:package-warning-duocolor-sharp" /></template>
<style>
.i8lrfn7rs {
  stroke-opacity: 0.4;
  d: path("M12 11v3m0 3h.01");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.s7e_ee__v {
  d: path("m5 6l1-2h12l2 4v12H4V8zM4 8h16");
}

</style>
