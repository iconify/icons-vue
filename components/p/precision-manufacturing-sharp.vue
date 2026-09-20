<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z5p4embii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:precision-manufacturing-sharp" /></template>
<style>
.z5p4embii {
  fill: currentColor;
  d: path("M4.764 19.462v-1.616h3.022L5.199 9.381q-.656-.317-1.045-.908q-.39-.59-.39-1.357q0-1.039.731-1.77t1.77-.73q.917 0 1.574.562t.88 1.438h3.66v-2h.88l.075.63l2.263-2.08l4.758 2.238l-.37.78l-4.217-1.968l-2.388 2.2v1.4l2.388 2.15l4.23-1.97l.368.781l-4.769 2.25l-2.263-2.042l-.093.63h-.861v-2H8.717q-.075.335-.249.664t-.382.548l4.847 9.02h3.83v1.614zM7.321 8.174q.442-.441.442-1.059t-.442-1.058t-1.058-.442t-1.06.442q-.44.441-.44 1.058q0 .618.44 1.059q.442.442 1.06.442t1.058-.442");
}

</style>
