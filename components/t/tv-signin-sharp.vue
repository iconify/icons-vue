<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bcso85zhm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:tv-signin-sharp" /></template>
<style>
.bcso85zhm {
  fill: currentColor;
  d: path("M8 15h8v-.55q0-1.125-1.1-1.787T12 12t-2.9.663T8 14.45zm5.413-4.587Q14 9.825 14 9t-.587-1.412T12 7t-1.412.588T10 9t.588 1.413T12 11t1.413-.587M8 21v-2H2V3h20v16h-6v2z");
}

</style>
