<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nzq1i_bcl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-align-left-24-filled" /></template>
<style>
.nzq1i_bcl {
  fill: currentColor;
  d: path("M2 6a1 1 0 0 1 1-1h15a1 1 0 1 1 0 2H3a1 1 0 0 1-1-1m0 12a1 1 0 0 1 1-1h11a1 1 0 1 1 0 2H3a1 1 0 0 1-1-1m1-7a1 1 0 1 0 0 2h18a1 1 0 1 0 0-2z");
}

</style>
