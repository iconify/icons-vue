<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="tw6ixq57g"/><path class="uf48zac5e"/><path class="bk2je2bwb"/><path class="dh3op-jbw"/><path class="i6bg3fnyb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:move-x" /></template>
<style>
.bk2je2bwb {
  d: path("M16 10a1 1 0 0 1-1 1H7a1 1 0 1 1 0-2h8a1 1 0 0 1 1 1m-9.026 4.768a1 1 0 0 1-1.409-.128l-3.333-4a1 1 0 1 1 1.536-1.28l3.334 4a1 1 0 0 1-.128 1.408");
}

.dh3op-jbw {
  d: path("M6.974 5.232a1 1 0 0 1 .128 1.408l-3.334 4a1 1 0 1 1-1.536-1.28l3.333-4a1 1 0 0 1 1.409-.128");
}

.i6bg3fnyb {
  d: path("M4 10a1 1 0 0 1 1-1h8a1 1 0 0 1 0 2H5a1 1 0 0 1-1-1");
}

.n1lsf0bnc {
  fill: currentColor;
  fill-rule: evenodd;
}

.tw6ixq57g {
  d: path("M13.027 5.232a1 1 0 0 1 1.408.128l3.333 4a1 1 0 1 1-1.536 1.28l-3.334-4a1 1 0 0 1 .129-1.408");
}

.uf48zac5e {
  d: path("M13.027 14.768a1 1 0 0 1-.129-1.408l3.334-4a1 1 0 1 1 1.536 1.28l-3.333 4a1 1 0 0 1-1.408.128");
}

</style>
