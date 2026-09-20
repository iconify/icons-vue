<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t1xd6ub5b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:picture-in-picture-large-outline-rounded" /></template>
<style>
.t1xd6ub5b {
  fill: currentColor;
  d: path("M7 16q-.425 0-.712-.288T6 15V7q0-.425.288-.712T7 6h10q.425 0 .713.288T18 7v8q0 .425-.288.713T17 16zm-4 4q-.425 0-.712-.288T2 19t.288-.712T3 18h17V5q0-.425.288-.712T21 4t.713.288T22 5v13q0 .825-.587 1.413T20 20z");
}

</style>
