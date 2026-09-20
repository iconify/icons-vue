<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qm8_yibvw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:transit-ticket-sharp" /></template>
<style>
.qm8_yibvw {
  fill: currentColor;
  d: path("M9 17h6v-1l-1-.5q.825 0 1.413-.587T16 13.5V9q0-1.075-.925-1.537T12 7q-2.075 0-3.037.475T8 9v4.5q0 .825.588 1.413T10 15.5L9 16zm.713-2.713q-.213-.212-.213-.537t.213-.537t.537-.213t.538.213t.212.537t-.213.538t-.537.212t-.537-.213m3.5 0Q13 14.076 13 13.75t.213-.537t.537-.213t.538.213t.212.537t-.213.538t-.537.212t-.537-.213M9.5 12V9h5v3zM2 20v-6q.825 0 1.413-.587T4 12t-.587-1.412T2 10V4h20v6q-.825 0-1.412.588T20 12t.588 1.413T22 14v6z");
}

</style>
