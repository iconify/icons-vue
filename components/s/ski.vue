<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ml939hbkm"/><path class="nnx5j0bae"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:ski" /></template>
<style>
.ml939hbkm {
  d: path("M13 9L9.9056 12.0944C9.4456 12.5544 9.5404 13.3242 10.0983 13.659L12.8571 15.3143C13.4286 15.6572 13.5111 16.4527 13.022 16.9055L11 18.7778M12 10L16 12M3 17L21 21");
}

.nnx5j0bae {
  fill: currentColor;
  d: path("M17 4C17 5.1046 16.1046 6 15 6C13.8954 6 13 5.1046 13 4C13 2.8954 13.8954 2 15 2C16.1046 2 17 2.8954 17 4Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
