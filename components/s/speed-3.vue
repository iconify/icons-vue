<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y2yzn0l4k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:speed-3" /></template>
<style>
.y2yzn0l4k {
  fill: currentColor;
  d: path("M12.825 15.8q.85-.375 1.15-1.225t-.2-1.575q-1.45-2.075-2.937-4.075T7.775 4.95q.475 2.475 1.063 4.9t1.312 4.85q.25.825 1.063 1.138t1.612-.038m-7.7 4.2q-.55 0-1.012-.238t-.738-.712q-.7-1.2-1.05-2.512t-.35-2.688q.025-2 .85-3.787t2.2-3.138T8.2 4.788T12 4q2.075 0 3.888.788t3.174 2.15t2.15 3.175T22 14q0 1.35-.35 2.625t-1 2.425q-.275.475-.75.713t-1 .237z");
}

</style>
