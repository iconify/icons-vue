<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bgt9v_bhz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:server-check-corner-fill-round" /></template>
<style>
.bgt9v_bhz {
  fill: currentColor;
  d: path("M6 3h12a4 4 0 0 1 0 8H6a4 4 0 0 1 0-8m1.01 3H7a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2M9 21H6a4 4 0 0 1 0-8h3a1 1 0 0 1 1 1v6a1 1 0 0 1-1 1m4.707-4.707l2.226 2.226l4.299-5.159a1 1 0 1 1 1.536 1.28l-5 6a1 1 0 0 1-1.475.067l-3-3a.999.999 0 1 1 1.414-1.414M7.01 16H7a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2");
}

</style>
