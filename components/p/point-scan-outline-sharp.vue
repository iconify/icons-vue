<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ufekslbsa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:point-scan-outline-sharp" /></template>
<style>
.ufekslbsa {
  fill: currentColor;
  d: path("M10.588 13.413Q10 12.825 10 12t.588-1.412T12 10t1.413.588T14 12t-.587 1.413T12 14t-1.412-.587M11 8V3h2v5zm0 13v-5h2v5zm5-8v-2h5v2zM3 13v-2h5v2z");
}

</style>
