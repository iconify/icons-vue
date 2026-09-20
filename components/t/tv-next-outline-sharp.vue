<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fh89u6b_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:tv-next-outline-sharp" /></template>
<style>
.fh89u6b_a {
  fill: currentColor;
  d: path("M19.5 22.5L18 21l3-3l-3-3l1.5-1.5L24 18zM8 21v-2H2V3h20v9h-2V5H4v12h13v2h-2v2zm-4-4V5z");
}

</style>
