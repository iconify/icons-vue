<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h9ud6ihra"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:speed-3-rounded" /></template>
<style>
.h9ud6ihra {
  fill: currentColor;
  d: path("M12.825 15.8q.75-.35 1.113-1.2t-.163-1.6q-1.1-1.575-2.212-3.062T9.3 6.95q-.275-.35-.687-.162t-.313.637q.4 1.825.85 3.625t1 3.65q.25.875 1.038 1.163t1.637-.063m-7.7 4.2q-.55 0-1.012-.238t-.738-.712q-.7-1.2-1.05-2.512t-.35-2.688q.025-2 .85-3.787t2.2-3.138T8.2 4.788T12 4q2.075 0 3.888.788t3.174 2.15t2.15 3.175T22 14q0 1.35-.35 2.625t-1 2.425q-.275.475-.75.713t-1 .237z");
}

</style>
