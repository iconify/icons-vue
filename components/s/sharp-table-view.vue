<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dvsm-yyak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-table-view" /></template>
<style>
.dvsm-yyak {
  fill: currentColor;
  d: path("M21 7H7v14h14zm-2 2v2H9V9zm-6 6v-2h2v2zm2 2v2h-2v-2zm-4-2H9v-2h2zm6-2h2v2h-2zm-8 4h2v2H9zm8 2v-2h2v2zM6 17H3V3h14v3h-2V5H5v10h1z");
}

</style>
