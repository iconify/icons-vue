<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="u766dnb9d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:window-multiple-off-20-regular" /></template>
<style>
.u766dnb9d {
  fill: currentColor;
  d: path("M2.146 2.146a.5.5 0 0 1 .708 0l15 15a.5.5 0 0 1-.707.707l-.696-.695A3.98 3.98 0 0 1 14 18H7.5a2.5 2.5 0 0 1-2.45-2h1.035A1.5 1.5 0 0 0 7.5 17H14a3 3 0 0 0 1.735-.558l-1.857-1.857A2.5 2.5 0 0 1 12.5 15h-8A2.5 2.5 0 0 1 2 12.5v-8c0-.51.152-.984.414-1.379l-.268-.267a.5.5 0 0 1 0-.708M16 5.05a2.5 2.5 0 0 1 2 2.45V14c0 .554-.114 1.082-.317 1.562l-.788-.789A3 3 0 0 0 17 14V7.5a1.5 1.5 0 0 0-1-1.415zM3 6v6.5A1.5 1.5 0 0 0 4.5 14h8a1.5 1.5 0 0 0 .645-.148L5.293 6zm9.5-4A2.5 2.5 0 0 1 15 4.5v8c0 .12-.012.236-.028.35L14 11.88V6H8.121l-1-1H14v-.5A1.5 1.5 0 0 0 12.5 3H5.121l-.973-.973Q4.321 2.001 4.5 2zM3.147 3.854A1.5 1.5 0 0 0 3 4.5V5h1.293z");
}

</style>
