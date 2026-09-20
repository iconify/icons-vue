<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="etb2r5bmm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:wb-twilight-2" /></template>
<style>
.etb2r5bmm {
  fill: currentColor;
  d: path("M2 20v-2h20v2zm3-4q0-2.925 2.038-4.962T12 9t4.963 2.038T19 16z");
}

</style>
