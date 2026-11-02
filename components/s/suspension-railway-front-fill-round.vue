<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u23dut4-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:suspension-railway-front-fill-round" /></template>
<style>
.u23dut4-f {
  fill: currentColor;
  d: path("M21 3a1 1 0 0 1 0 2h-5v3.099A5.01 5.01 0 0 1 20 13v5a3 3 0 0 1-3 3H7a3 3 0 0 1-3-3v-5a5.01 5.01 0 0 1 4-4.901V5H3a1 1 0 0 1 0-2Zm-7 2h-4v3h4Zm-8 8h12a3 3 0 0 0-3-3H9a3 3 0 0 0-3 3m3.01 3H9a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2M15 16a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2Z");
}

</style>
