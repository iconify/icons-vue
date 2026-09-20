<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rmjqs45hg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:shopping-basket-sharp" /></template>
<style>
.rmjqs45hg {
  fill: currentColor;
  d: path("M4.025 21L.675 9H6.75l5.225-7.775L17.2 9h6.125l-3.35 12zm9.388-4.587Q14 15.825 14 15t-.587-1.412T12 13t-1.412.588T10 15t.588 1.413T12 17t1.413-.587M9.174 9H14.8l-2.825-4.2z");
}

</style>
