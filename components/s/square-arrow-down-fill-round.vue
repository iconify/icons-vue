<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d2-d67nmy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-arrow-down-fill-round" /></template>
<style>
.d2-d67nmy {
  fill: currentColor;
  d: path("M2 7a5 5 0 0 1 5-5h10a5 5 0 0 1 5 5v10a5 5 0 0 1-1.464 3.536A5 5 0 0 1 17 22H7a5 5 0 0 1-5-5Zm6.293 6.707l3 3a1 1 0 0 0 1.414 0l3-3a.999.999 0 1 0-1.414-1.414L13 13.586V8a1 1 0 0 0-2 0v5.586l-1.293-1.293a.999.999 0 1 0-1.414 1.414");
}

</style>
