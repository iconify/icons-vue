<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x1r7vabzb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:mobile-speaker-outline-sharp" /></template>
<style>
.x1r7vabzb {
  fill: currentColor;
  d: path("M5 20V4zm-1 1V3h11.077v4.944l-1 1V4H5v16h5.79l1 1zm5.577-3.384v-3h2.212l2.788-2.789v8.577l-2.788-2.788zm7.385.838V13.77q.682.3 1.11.931q.428.63.428 1.414q0 .782-.428 1.41t-1.11.928m0 3.49v-1.038q1.73-.356 2.827-1.702q1.095-1.346 1.095-3.089t-1.096-3.088t-2.827-1.677V10.31q2.139.35 3.531 1.996t1.393 3.808t-1.393 3.819t-3.53 2.01M10.088 7.088q.22-.22.22-.55q0-.329-.22-.549t-.55-.22t-.548.22t-.22.55t.22.549t.549.22t.549-.22");
}

</style>
