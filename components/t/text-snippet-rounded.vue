<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uipa2yb6v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:text-snippet-rounded" /></template>
<style>
.uipa2yb6v {
  fill: currentColor;
  d: path("M5 21q-.825 0-1.412-.587T3 19V5q0-.825.588-1.412T5 3h9.175q.4 0 .763.15t.637.425l4.85 4.85q.275.275.425.638t.15.762V19q0 .825-.587 1.413T19 21zm3-4h8q.425 0 .713-.288T17 16t-.288-.712T16 15H8q-.425 0-.712.288T7 16t.288.713T8 17m0-4h8q.425 0 .713-.288T17 12t-.288-.712T16 11H8q-.425 0-.712.288T7 12t.288.713T8 13m0-4h5q.425 0 .713-.288T14 8t-.288-.712T13 7H8q-.425 0-.712.288T7 8t.288.713T8 9");
}

</style>
