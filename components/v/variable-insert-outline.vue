<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dr49a8boz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:variable-insert-outline" /></template>
<style>
.dr49a8boz {
  fill: currentColor;
  d: path("M3 17V7h18v4h-2V9H5v6h9v2zm2-2V9zm16.6 5L18 16.425V19.5h-2V13h6.5v2h-3.1l3.6 3.6z");
}

</style>
