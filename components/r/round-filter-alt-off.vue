<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nx-1kz4eh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-filter-alt-off" /></template>
<style>
.nx-1kz4eh {
  fill: currentColor;
  d: path("M19.79 5.61A.998.998 0 0 0 19 4H6.83l7.97 7.97zm.7 14.88L3.51 3.51A.996.996 0 1 0 2.1 4.92L10 13v5c0 1.1.9 2 2 2s2-.9 2-2v-1.17l5.07 5.07c.39.39 1.02.39 1.41 0s.4-1.02.01-1.41");
}

</style>
