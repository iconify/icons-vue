<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ia6g_4_yd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:vertical-split-sharp" /></template>
<style>
.ia6g_4_yd {
  fill: currentColor;
  d: path("M3 15v-2h8v2zm0 4v-2h8v2zm0-8V9h8v2zm0-4V5h8v2zm10 12V5h8v14z");
}

</style>
