<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ebrn-67ov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:memory-alt-outline-sharp" /></template>
<style>
.ebrn-67ov {
  fill: currentColor;
  d: path("M6 15h2V9H6zm5 0h2V9h-2zm5 0h2V9h-2zM4 17h16V7H4zm0 0V7zm1 4v-2H2V5h3V3h2v2h4V3h2v2h4V3h2v2h3v14h-3v2h-2v-2h-4v2h-2v-2H7v2z");
}

</style>
