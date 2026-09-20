<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bzeq_uclt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:rectangle" /></template>
<style>
.bzeq_uclt {
  fill: currentColor;
  d: path("M2 20V4h20v16z");
}

</style>
