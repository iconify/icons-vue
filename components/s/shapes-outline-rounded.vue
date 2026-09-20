<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ysx-a6k8d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:shapes-outline-rounded" /></template>
<style>
.ysx-a6k8d {
  fill: currentColor;
  d: path("M10.385 20.77q-.667 0-1.141-.475t-.475-1.141V18.5q0-.213.144-.356Q9.057 18 9.27 18t.356.144t.143.356v.654q0 .269.173.442t.442.173h8.77q.269 0 .442-.173t.173-.442v-8.77q0-.268-.173-.442q-.173-.173-.442-.173H18.5q-.213 0-.356-.144T18 9.27t.144-.356t.356-.144h.654q.666 0 1.14.475t.475 1.14v8.77q0 .666-.474 1.14t-1.141.475zM4.98 13.485Q3.23 11.74 3.23 9.234T4.977 4.98q1.746-1.75 4.251-1.75t4.255 1.746t1.749 4.251t-1.745 4.255t-4.251 1.749t-4.255-1.745m7.788-.718q1.463-1.462 1.463-3.537t-1.463-3.538t-3.537-1.462t-3.538 1.462t-1.462 3.538t1.462 3.537t3.538 1.463t3.537-1.463M9.231 9.231");
}

</style>
