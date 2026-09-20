<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xks3l7bzg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:speed-2" /></template>
<style>
.xks3l7bzg {
  fill: currentColor;
  d: path("M13.4 15.425q.65-.65.6-1.5t-.75-1.4q-1.975-1.55-4.1-2.875t-4.175-2.7q1.35 2.075 2.675 4.188t2.8 4.187q.5.725 1.4.738t1.55-.638M5.125 20q-.55 0-1.012-.238t-.738-.712q-.7-1.2-1.05-2.512t-.35-2.688q.025-1.9.838-3.725T4.975 6.95q1.4-1.4 3.238-2.175T12 4q2.075 0 3.888.788t3.174 2.15t2.15 3.175T22 14q0 1.35-.35 2.625t-1 2.425q-.275.475-.75.713t-1 .237z");
}

</style>
