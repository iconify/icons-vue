<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rkd6q0x0g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:siren-fill" /></template>
<style>
.rkd6q0x0g {
  fill: currentColor;
  d: path("M11 5V3a1 1 0 0 1 2 0v2a1 1 0 0 1-2 0M6.707 6.293a.999.999 0 1 1-1.414 1.414l-2-2a.999.999 0 1 1 1.414-1.414Zm12 1.414a1 1 0 0 1-1.414-1.414l2-2a.999.999 0 1 1 1.414 1.414ZM18 16a2 2 0 0 1 2 2v2a2 2 0 0 1-2 2H6a2 2 0 0 1-2-2v-2a2 2 0 0 1 2-2h1v-3a5 5 0 0 1 10 0v3Zm-5-1v-2a1 1 0 0 0-2 0v2a1 1 0 0 0 2 0");
}

</style>
