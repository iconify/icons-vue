<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="e_awiut7n"/><path class="ynnhdwb4e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:monitor-loop" /></template>
<style>
.e_awiut7n {
  d: path("M1.5 4.5A2.5 2.5 0 0 1 4 2h11.748a2.5 2.5 0 0 1 2.5 2.5v7.651a2.5 2.5 0 0 1-2.5 2.5h-4.874v2.278a1 1 0 1 1-2 0V14.43a1 1 0 0 1 .626-1.78h6.248a.5.5 0 0 0 .5-.5V4.5a.5.5 0 0 0-.5-.5H4a.5.5 0 0 0-.5.5V6a1 1 0 0 1-2 0z");
}

.n1lsf0bnc {
  fill: currentColor;
  fill-rule: evenodd;
}

.ynnhdwb4e {
  d: path("M5.187 17.59a1 1 0 0 1 1-1h7.374a1 1 0 1 1 0 2H6.187a1 1 0 0 1-1-1m.25-8.208a2.193 2.193 0 1 0-2.058 3.872a2.193 2.193 0 0 0 2.058-3.872M.705 9.35a4.193 4.193 0 1 1 2.674 6.034l-1.677 3.155A1 1 0 1 1-.064 17.6l1.677-3.155A4.194 4.194 0 0 1 .705 9.35");
}

</style>
