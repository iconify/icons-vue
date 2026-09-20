<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qtb2tn7sz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:mobile-speaker-sharp" /></template>
<style>
.qtb2tn7sz {
  fill: currentColor;
  d: path("M4 21V3h11.077v4.944l-4.286 4.287H7.192V20h3.599l1 1zm6.088-13.913q.22-.22.22-.549t-.22-.549t-.55-.22t-.548.22t-.22.55t.22.548t.549.22t.549-.22m4.489 13.317l-2.788-2.788H9.577v-3h2.212l2.788-2.789zm2.385 1.54v-1.038q1.73-.356 2.827-1.702q1.095-1.346 1.095-3.089t-1.096-3.088t-2.827-1.677v-1.039q2.139.35 3.531 1.996t1.393 3.808t-1.393 3.819t-3.53 2.01m0-3.49V13.77q.682.3 1.11.931q.428.63.428 1.414q0 .782-.428 1.41t-1.11.928");
}

</style>
