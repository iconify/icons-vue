<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="fknjydbia"/><path class="p4u579bld"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:studio-backdrop" /></template>
<style>
.fknjydbia {
  d: path("M3 3a1.5 1.5 0 0 1 1.5-1.5h11A1.5 1.5 0 0 1 17 3v7a1.5 1.5 0 0 1-1.5 1.5h-11A1.5 1.5 0 0 1 3 10zm2 .5v6h10v-6z");
}

.n1lsf0bnc {
  fill: currentColor;
  fill-rule: evenodd;
}

.p4u579bld {
  d: path("M1.75 2.5a1 1 0 0 1 1-1h14.5a1 1 0 1 1 0 2H2.75a1 1 0 0 1-1-1m1.97 14l1.26-6.304l-1.96-.392l-1.381 6.902a1.5 1.5 0 0 0 1.47 1.794H16.89a1.5 1.5 0 0 0 1.471-1.794l-1.38-6.902l-1.962.392L16.28 16.5z");
}

</style>
