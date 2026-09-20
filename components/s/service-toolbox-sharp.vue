<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bmc8_5grw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:service-toolbox-sharp" /></template>
<style>
.bmc8_5grw {
  fill: currentColor;
  d: path("M2 20v-6h5v1h2v-1h6v1h2v-1h5v6zm.425-8l2.6-6H7V5q0-.825.588-1.412T9 3h6q.825 0 1.413.588T17 5v1h1.975l2.6 6H17v-1h-2v1H9v-1H7v1zM9 6h6V5H9z");
}

</style>
