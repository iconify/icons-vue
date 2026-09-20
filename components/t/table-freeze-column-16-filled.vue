<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="hdiacfb2j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:table-freeze-column-16-filled" /></template>
<style>
.hdiacfb2j {
  fill: currentColor;
  d: path("M3 4.5A1.5 1.5 0 0 1 4.5 3H6v2h4V2H4.5A2.5 2.5 0 0 0 2 4.5v7A2.5 2.5 0 0 0 4.5 14H10v-3H6v2H4.5A1.5 1.5 0 0 1 3 11.5zM6 6v4h4V6zm5 5v3h.5a2.5 2.5 0 0 0 2.5-2.5V11zm3-1V6h-3v4zm0-5.5V5h-3V2h.5A2.5 2.5 0 0 1 14 4.5");
}

</style>
