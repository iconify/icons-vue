<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xj0g_hu2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:vr-sim-racing" /></template>
<style>
.xj0g_hu2m {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.5 2.25h15q2.75 0 2.75 2.75v6.25q0 2.75-2.75 2.75H15q-.097 0-.191-.025q-.094-.024-.179-.072t-.154-.116t-.119-.151L13.075 11.5h-2.15l-1.282 2.136q-.05.083-.119.151q-.07.068-.154.116q-.085.048-.179.072Q9.097 14 9 14H4.5q-2.75 0-2.75-2.75V5q0-1.139.805-1.945q.806-.805 1.945-.805M14.75 19q0-3.5 3.5-3.5t3.5 3.5t-3.5 3.5t-3.5-3.5m5.412-.75Q19.831 17 18.25 17t-1.912 1.25zM17.5 20.912V19.75h-1.162q.243.919 1.162 1.162m2.662-1.162H19v1.162q.919-.243 1.162-1.162");
}

</style>
