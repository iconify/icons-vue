<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="gp3g00bpb"/><path class="ismw9z0vz"/><path class="c_vectb4r"/><path class="auyjsv2-l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:rewind-time" /></template>
<style>
.auyjsv2-l {
  d: path("M14 10.5a1 1 0 0 1-1 1h-3a1 1 0 1 1 0-2h3a1 1 0 0 1 1 1");
}

.c_vectb4r {
  d: path("M2.42 11.6a1 1 0 0 0 1.4.2l2-1.5a1 1 0 0 0-1.2-1.6l-2 1.5a1 1 0 0 0-.2 1.4M10 6a1 1 0 0 1 1 1v3.5a1 1 0 1 1-2 0V7a1 1 0 0 1 1-1");
}

.gp3g00bpb {
  d: path("M5.955 5.805a5.94 5.94 0 0 0-1.736 4.87a1 1 0 0 1-1.99.21a7.94 7.94 0 0 1 2.322-6.504c3.136-3.092 8.19-3.04 11.289.102s3.081 8.198-.054 11.29a7.92 7.92 0 0 1-5.44 2.286a8 8 0 0 1-2.283-.29a1 1 0 1 1 .533-1.927a6 6 0 0 0 1.714.217a5.92 5.92 0 0 0 4.071-1.71c2.343-2.31 2.365-6.099.035-8.461s-6.118-2.393-8.46-.083");
}

.ismw9z0vz {
  d: path("M3.967 11.695a1 1 0 0 1-1.412.082l-1.72-1.53a1 1 0 0 1 1.33-1.494l1.72 1.53a1 1 0 0 1 .082 1.412");
}

.n1lsf0bnc {
  fill: currentColor;
  fill-rule: evenodd;
}

</style>
