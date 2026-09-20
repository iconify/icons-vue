<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gdao3pbir"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:text-select-move-forward-character" /></template>
<style>
.gdao3pbir {
  fill: currentColor;
  d: path("M11 21v-2h2v2zm0-16V3h2v2zm4 16v-2h2v2zm0-16V3h2v2zm4 16v-2h2v2zm0-16V3h2v2zM3 21v-2h2V5H3V3h6v2H7v14h2v2zm14-5l-1.4-1.4l1.575-1.6H10v-2h7.175L15.6 9.4L17 8l4 4z");
}

</style>
