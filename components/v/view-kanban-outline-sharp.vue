<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vva4sfbzb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:view-kanban-outline-sharp" /></template>
<style>
.vva4sfbzb {
  fill: currentColor;
  d: path("M7 17h2V7H7zm4-5h2V7h-2zm4 3h2V7h-2zM3 21V3h18v18zm2-2h14V5H5zm0 0V5z");
}

</style>
