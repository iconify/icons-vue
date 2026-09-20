<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o8750-_fk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:maximize-rounded" /></template>
<style>
.o8750-_fk {
  fill: currentColor;
  d: path("M5 5q-.425 0-.712-.288T4 4t.288-.712T5 3h14q.425 0 .713.288T20 4t-.288.713T19 5z");
}

</style>
