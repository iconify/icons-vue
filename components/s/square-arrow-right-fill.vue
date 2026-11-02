<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jllsec-tx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-arrow-right-fill" /></template>
<style>
.jllsec-tx {
  fill: currentColor;
  d: path("M2 5a3 3 0 0 1 3-3h14a3 3 0 0 1 3 3v14a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3Zm10.293 9.293a.999.999 0 1 0 1.414 1.414l3-3a1 1 0 0 0 0-1.414l-3-3a.999.999 0 1 0-1.414 1.414L13.586 11H8a1 1 0 0 0 0 2h5.586Z");
}

</style>
