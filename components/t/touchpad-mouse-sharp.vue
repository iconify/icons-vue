<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lmne4f_ud"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:touchpad-mouse-sharp" /></template>
<style>
.lmne4f_ud {
  fill: currentColor;
  d: path("M16.5 21q-1.871 0-3.185-1.314T12 16.5v-2h9v2q0 1.871-1.311 3.186Q18.377 21 16.5 21M3 19V5h18v3.304q-.94-.823-2.096-1.256q-1.156-.432-2.404-.432q-2.875 0-4.88 2.004T9.616 13.5v3q0 .656.116 1.284T10.1 19zm9-5.5q.017-1.74 1.158-3.016Q14.298 9.208 16 9.017V13.5zm5 0V9.017q1.702.19 2.842 1.467Q20.982 11.76 21 13.5z");
}

</style>
