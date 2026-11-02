<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s2r9fgk-l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:ruler-fill" /></template>
<style>
.s2r9fgk-l {
  fill: currentColor;
  d: path("M13.707 4.293L13 3.586l.293-.293a2.414 2.414 0 0 1 3.414 0l4 4a2.414 2.414 0 0 1 0 3.414l-10 10a2.414 2.414 0 0 1-3.414 0l-4-4a2.414 2.414 0 0 1 0-3.414L3.586 13l2.707 2.707a.999.999 0 1 0 1.414-1.414l-.586-.586l-.001-.001L5 11.586L7.586 9l2.707 2.707a.999.999 0 1 0 1.414-1.414L9 7.586L11.586 5l2.707 2.707a.999.999 0 1 0 1.414-1.414Z");
}

</style>
