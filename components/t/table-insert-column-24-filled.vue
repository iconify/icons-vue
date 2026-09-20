<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ari2u1yrp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:table-insert-column-24-filled" /></template>
<style>
.ari2u1yrp {
  fill: currentColor;
  d: path("M4.5 3.75v16.5a.75.75 0 0 1-1.5 0V3.75a.75.75 0 0 1 1.5 0M16 5.25C16 4.007 15.105 3 14 3h-4C8.895 3 8 4.007 8 5.25V8h8zM8 14.5v-5h8v5zM8 16v2.75c0 1.243.895 2.25 2 2.25h4c1.105 0 2-1.007 2-2.25V16zm13 4.25V3.75a.75.75 0 0 0-1.5 0v16.5a.75.75 0 0 0 1.5 0");
}

</style>
