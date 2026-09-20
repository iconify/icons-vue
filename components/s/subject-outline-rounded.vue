<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a50cyy-tq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:subject-outline-rounded" /></template>
<style>
.a50cyy-tq {
  fill: currentColor;
  d: path("M5 19q-.425 0-.712-.288T4 18t.288-.712T5 17h8q.425 0 .713.288T14 18t-.288.713T13 19zm0-4q-.425 0-.712-.288T4 14t.288-.712T5 13h14q.425 0 .713.288T20 14t-.288.713T19 15zm0-4q-.425 0-.712-.288T4 10t.288-.712T5 9h14q.425 0 .713.288T20 10t-.288.713T19 11zm0-4q-.425 0-.712-.288T4 6t.288-.712T5 5h14q.425 0 .713.288T20 6t-.288.713T19 7z");
}

</style>
