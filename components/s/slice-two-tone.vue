<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ur_189nwm"/><path class="jyagbvbyx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:slice-two-tone" /></template>
<style>
.jyagbvbyx {
  d: path("M6.8465 12.5088L12.8418 6.2161C15.8394 3.0697 19.2363 2.3044 22 3.6037L10.3424 15.8395ZM7.1961 12.8419L2.533 17.7362C1.7972 18.5086 1.8268 19.7311 2.5991 20.4669C3.3715 21.2027 4.594 21.1732 5.3298 20.4008L9.9928 15.5065");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ur_189nwm {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M16.8952 10.4114L22.724 4.2935C22.9012 4.1075 23 3.8605 23 3.6037C23 3.2162 22.7761 2.8636 22.4255 2.6987C20.8212 1.9445 19.0376 1.7959 17.2488 2.2771C15.4686 2.756 13.7167 3.8481 12.1178 5.5263L6.1225 11.819C5.9453 12.005 5.8465 12.252 5.8465 12.5088C5.8465 12.5985 5.8585 12.6868 5.8817 12.7718L1.809 17.0464C0.6923 18.2187 0.7371 20.0741 1.9093 21.1909C3.0815 22.3076 4.937 22.2629 6.0539 21.0905L10.1265 16.8159C10.1969 16.8315 10.2692 16.8395 10.3424 16.8395C10.616 16.8395 10.8777 16.7274 11.0664 16.5293Z");
  stroke: none;
}

</style>
