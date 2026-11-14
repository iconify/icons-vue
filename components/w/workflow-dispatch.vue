<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iaj09ewsg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:workflow-dispatch" /></template>
<style>
.iaj09ewsg {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.125 1.75h1.75q3.375 0 3.375 3.375v.125h3.06q.214-1.284 1.185-2.255Q15.74 1.75 17.5 1.75t3.005 1.245T21.75 6t-1.245 3.005T17.5 10.25t-3.005-1.245q-.971-.971-1.185-2.255h-3.06v.125q0 3.375-3.375 3.375H6.75v3.5h.125q3.375 0 3.375 3.375v1.75q0 3.375-3.375 3.375h-1.75q-3.375 0-3.375-3.375v-1.75q0-1.398.989-2.386q.988-.989 2.386-.989h.125v-3.5h-.125q-3.375 0-3.375-3.375v-1.75q0-3.375 3.375-3.375m12.389 12.648l2.04 1.195q1.236.724 1.236 2.157t-1.236 2.157l-2.04 1.195q-1.249.733-2.506.013t-1.258-2.169v-2.392q.001-1.449 1.258-2.169t2.506.013m-.758 1.294q-.5-.293-1.003-.005t-.503.867v2.392q0 .579.503.867t1.003-.005l2.04-1.195q.494-.29.494-.863t-.494-.863z");
}

</style>
