<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k5-8cdcye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-border-outer" /></template>
<style>
.k5-8cdcye {
  fill: currentColor;
  d: path("M11 11h2v2h-2zm0-4h2v2h-2zm10-4H3v18h18zm-2 16H5V5h14zm-4-8h2v2h-2zm-8 0h2v2H7zm4 4h2v2h-2z");
}

</style>
