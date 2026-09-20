<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ynmu9iyer"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:vertical-distribute-outline-rounded" /></template>
<style>
.ynmu9iyer {
  fill: currentColor;
  d: path("M3 22q-.425 0-.712-.288T2 21t.288-.712T3 20h18q.425 0 .713.288T22 21t-.288.713T21 22zm5.5-8.5q-.625 0-1.062-.437T7 12t.438-1.062T8.5 10.5h7q.625 0 1.063.438T17 12t-.437 1.063t-1.063.437zM3 4q-.425 0-.712-.288T2 3t.288-.712T3 2h18q.425 0 .713.288T22 3t-.288.713T21 4z");
}

</style>
