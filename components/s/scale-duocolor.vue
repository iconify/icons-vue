<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="gd5ygyb4r"/><path class="ht_kdnlyp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:scale-duocolor" /></template>
<style>
.gd5ygyb4r {
  stroke-opacity: 0.4;
  d: path("m6 6l3 7a3.25 3.25 0 0 1-6 0Zm12 0l3 7a3.25 3.25 0 0 1-6 0Z");
}

.ht_kdnlyp {
  d: path("M12 3v18m-4 0h8M6 6h12");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
