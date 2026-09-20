<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n26j2r8gq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:park-sharp" /></template>
<style>
.n26j2r8gq {
  fill: currentColor;
  d: path("M13.95 22h-3.9v-4H3l4-6H5l7-10l7 10h-2l4 6h-7.05z");
}

</style>
