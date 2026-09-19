<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j_vbwb_gx"/><path class="oqskdwbyn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-highlight" /></template>
<style>
.j_vbwb_gx {
  fill: currentColor;
  d: path("M11 20h2v-3.83l3-3V11H8v2.17l3 3z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.oqskdwbyn {
  fill: currentColor;
  d: path("m6 14l3 3v5h6v-5l3-3V9H6zm2-3h8v2.17l-3 3V20h-2v-3.83l-3-3zm3-9h2v3h-2zM4.916 4.464l2.12 2.122L5.62 8L3.5 5.877zM18.372 8l-1.414-1.414l2.12-2.12l1.415 1.413z");
}

</style>
