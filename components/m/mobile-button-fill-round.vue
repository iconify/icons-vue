<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f2oqqhw1r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:mobile-button-fill-round" /></template>
<style>
.f2oqqhw1r {
  fill: currentColor;
  d: path("M6 7a5 5 0 0 1 5-5h2a5 5 0 0 1 5 5v10a5 5 0 0 1-5 5h-2a5 5 0 0 1-5-5Zm6.01 10H12a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2");
}

</style>
