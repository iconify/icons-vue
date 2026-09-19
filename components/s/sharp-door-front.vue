<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ik3ck5bam"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-door-front" /></template>
<style>
.ik3ck5bam {
  fill: currentColor;
  d: path("M19 19V3H5v16H3v2h18v-2zm-4-6h-2v-2h2z");
}

</style>
