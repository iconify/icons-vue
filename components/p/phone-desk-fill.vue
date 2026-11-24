<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hq6cw-bpe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:phone-desk-fill" /></template>
<style>
.hq6cw-bpe {
  fill: currentColor;
  d: path("M16 21.829V2.171A3 3 0 0 1 17 2h2a3 3 0 0 1 3 3v14a3 3 0 0 1-3 3h-2a3 3 0 0 1-1-.171M13.5 4v16H5a3 3 0 0 1-3-3V7a3 3 0 0 1 3-3ZM5 8a1 1 0 0 0 0 2h6a1 1 0 0 0 0-2Zm0 6h.01a1 1 0 0 0 0-2H5a1 1 0 0 0 0 2m3.01-2H8a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2M11 12a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2Zm-6 5h.01a1 1 0 0 0 0-2H5a1 1 0 0 0 0 2m3-2a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2Zm3.01 0H11a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2");
}

</style>
