<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t_ozkacuj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:speed-4-rounded" /></template>
<style>
.t_ozkacuj {
  fill: currentColor;
  d: path("M11.2 15.8q.85.35 1.638.063t1.037-1.163q.55-1.85 1-3.65t.85-3.625q.1-.45-.312-.637t-.688.162q-1.15 1.5-2.262 2.988T10.25 13q-.525.75-.162 1.6t1.112 1.2M5.125 20q-.55 0-1.012-.238t-.738-.712q-.7-1.2-1.05-2.512t-.35-2.688q.025-2 .85-3.787t2.2-3.138T8.2 4.788T12 4q2.075 0 3.888.788t3.174 2.15t2.15 3.175T22 14q0 1.35-.35 2.625t-1 2.425q-.275.475-.75.713t-1 .237z");
}

</style>
