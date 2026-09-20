<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ogk7tibkl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:table-cells-split-16-regular" /></template>
<style>
.ogk7tibkl {
  fill: currentColor;
  d: path("M2 4.5A2.5 2.5 0 0 1 4.5 2h7A2.5 2.5 0 0 1 14 4.5v7a2.5 2.5 0 0 1-2.5 2.5h-7A2.5 2.5 0 0 1 2 11.5zM3.085 4H7V3H4.5a1.5 1.5 0 0 0-1.415 1M8 3v1h4.915A1.5 1.5 0 0 0 11.5 3zm5 2H3v6h10zm-.085 7H8v1h3.5a1.5 1.5 0 0 0 1.415-1M7 13v-1H3.085A1.5 1.5 0 0 0 4.5 13zm0-3V6h1v4z");
}

</style>
