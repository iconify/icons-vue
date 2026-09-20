<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bc45hbcqa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:shopping-basket" /></template>
<style>
.bc45hbcqa {
  fill: currentColor;
  d: path("M5.525 21q-.675 0-1.2-.413T3.6 19.525l-2.55-9.25Q.925 9.8 1.213 9.4T2 9h4.75l4.4-6.55q.125-.2.35-.325T11.975 2t.475.125t.35.325L17.2 9H22q.5 0 .788.4t.162.875l-2.55 9.25q-.2.65-.725 1.063t-1.2.412zm7.888-4.587Q14 15.825 14 15t-.587-1.412T12 13t-1.412.588T10 15t.588 1.413T12 17t1.413-.587M9.174 9H14.8l-2.825-4.2z");
}

</style>
