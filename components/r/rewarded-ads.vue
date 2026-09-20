<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wqfud-b3r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:rewarded-ads" /></template>
<style>
.wqfud-b3r {
  fill: currentColor;
  d: path("M13.413 10.413Q14 9.825 14 9t-.587-1.412T12 7t-1.412.588T10 9t.588 1.413T12 11t1.413-.587M8.385 20v-1H11.5v-3.754q-1.321-.236-2.312-1.105T7.823 11.99q-1.586-.187-2.705-1.301T4 8V7q0-.402.299-.701T5 6h2.654V4h8.692v2H19q.402 0 .701.299T20 7v1q0 1.573-1.118 2.688t-2.705 1.3q-.373 1.285-1.364 2.153T12.5 15.246V19h3.115v1zm-.731-9.084V7H5v1q0 1.142.762 1.963t1.892.953m8.692 0q1.131-.133 1.893-.954T19 8V7h-2.654z");
}

</style>
