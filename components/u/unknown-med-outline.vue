<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cflyrvc9a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:unknown-med-outline" /></template>
<style>
.cflyrvc9a {
  fill: currentColor;
  d: path("M3.5 13q-.625 0-1.062-.437T2 11.5t.438-1.062T3.5 10h6q.625 0 1.063.438T11 11.5t-.437 1.063T9.5 13zm11 0q-.625 0-1.062-.437T13 11.5t.438-1.062T14.5 10h6q.625 0 1.063.438T22 11.5t-.437 1.063T20.5 13z");
}

</style>
