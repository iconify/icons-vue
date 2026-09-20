<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x15oacctf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:upload-2-rounded" /></template>
<style>
.x15oacctf {
  fill: currentColor;
  d: path("M5 20h14q.425 0 .713.288T20 21t-.288.713T19 22H5q-.425 0-.712-.288T4 21t.288-.712T5 20m5-2q-.425 0-.712-.288T9 17v-6H7.05q-.625 0-.9-.562t.1-1.063l4.95-6.35q.15-.2.363-.3t.437-.1t.438.1t.362.3l4.95 6.35q.375.5.1 1.063t-.9.562H15v6q0 .425-.288.713T14 18z");
}

</style>
