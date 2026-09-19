<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vlq1icc7o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:zalando" /></template>
<style>
.vlq1icc7o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.368 5.765c9.867-2.32 30.508 11.19 32.038 17.726c1.482 6.332-22.66 21.338-31.713 18.701c-6.262-1.824-7.361-34.774-.325-36.428Z");
}

</style>
