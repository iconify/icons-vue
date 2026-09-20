<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="cif-3rbax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:vehicle-trailer-arrow-down-20-filled" /></template>
<style>
.cif-3rbax {
  fill: currentColor;
  d: path("M6.5 12a.5.5 0 0 1 .5.5v4.793l1.146-1.146a.5.5 0 1 1 .708.707l-2 2a.5.5 0 0 1-.708 0l-2-2a.5.5 0 1 1 .708-.707L6 17.293V12.5a.5.5 0 0 1 .5-.5m6.654-8.996A3 3 0 0 1 16 6v8h2v-1.5a.5.5 0 0 1 1 0v4a.5.5 0 0 1-1 0V15H8v-2.5a1.5 1.5 0 0 0-3 0V15H4a3 3 0 0 1-3-3a9 9 0 0 1 9-9h3zM10 6a1 1 0 0 0-1 1v2l.005.103A1 1 0 0 0 10 10h2a1 1 0 0 0 1-1V7a1 1 0 0 0-.898-.995L12 6z");
}

</style>
