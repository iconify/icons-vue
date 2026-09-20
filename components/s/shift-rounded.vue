<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g4dui5yyy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:shift-rounded" /></template>
<style>
.g4dui5yyy {
  fill: currentColor;
  d: path("M8 20v-7H5.1q-.65 0-.912-.562t.137-1.063l6.9-8.425q.3-.375.775-.375t.775.375l6.9 8.425q.4.5.138 1.063T18.9 13H16v7q0 .425-.288.713T15 21H9q-.425 0-.712-.288T8 20");
}

</style>
