<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qeb149kkw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:picture-in-picture-small-outline-rounded" /></template>
<style>
.qeb149kkw {
  fill: currentColor;
  d: path("M3 20q-.425 0-.712-.288T2 19t.288-.712T3 18h17V5q0-.425.288-.712T21 4t.713.288T22 5v13q0 .825-.587 1.413T20 20zm8-4q-.425 0-.712-.288T10 15v-4q0-.425.288-.712T11 10h6q.425 0 .713.288T18 11v4q0 .425-.288.713T17 16z");
}

</style>
