<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k7dic6q-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:towel-stack" /></template>
<style>
.k7dic6q-w {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.75 2.25h8.5q1.243 0 2.121.879q.879.878.879 2.121q0 3-3 3h-8.5q-3 0-3-3q0-1.243.879-2.121q.878-.879 2.121-.879m9.5 6.5H6.75q-1.243 0-2.121.879q-.879.878-.879 2.121q0 3 3 3h10.5q3 0 3-3q0-1.243-.879-2.121q-.878-.879-2.121-.879m-11.5 6.5h12.5q3 0 3 3q0 1.243-.879 2.121q-.878.879-2.121.879H5.75q-1.243 0-2.121-.879q-.879-.878-.879-2.121q0-3 3-3");
}

</style>
