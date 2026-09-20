<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="tq87tgb2i"/><path class="hgd9f6bdx"/><path class="aljlkceyh"/><path class="cex855aua"/><path class="d41o03b5c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:shuffle" /></template>
<style>
.aljlkceyh {
  d: path("M16.46 14.778a.75.75 0 0 1-1.053-.133l-1.5-1.936a.75.75 0 0 1 1.186-.918l1.5 1.935a.75.75 0 0 1-.134 1.052");
}

.cex855aua {
  d: path("M14.05 16.786a.75.75 0 0 1-.15-1.05l1.5-2a.75.75 0 1 1 1.2.9l-1.5 2a.75.75 0 0 1-1.05.15m2.41-11.564a.75.75 0 0 0-1.053.133l-1.5 1.936a.75.75 0 0 0 1.186.918l1.5-1.935a.75.75 0 0 0-.134-1.052");
}

.d41o03b5c {
  d: path("M14.05 3.15a.75.75 0 0 0-.15 1.05l1.5 2a.75.75 0 1 0 1.2-.9l-1.5-2a.75.75 0 0 0-1.05-.15");
}

.hgd9f6bdx {
  d: path("M16 5.75a1 1 0 0 0-1-1c-3.335 0-6.5 2.126-6.5 5.25s3.165 5.25 6.5 5.25a1 1 0 1 0 0-2c-2.74 0-4.5-1.68-4.5-3.25s1.76-3.25 4.5-3.25a1 1 0 0 0 1-1");
}

.n1lsf0bnc {
  fill: currentColor;
  fill-rule: evenodd;
}

.tq87tgb2i {
  d: path("M3 5.75a1 1 0 0 1 1-1c3.335 0 6.5 2.126 6.5 5.25S7.335 15.25 4 15.25a1 1 0 1 1 0-2c2.74 0 4.5-1.68 4.5-3.25S6.74 6.75 4 6.75a1 1 0 0 1-1-1");
}

</style>
