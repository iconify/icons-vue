<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gz0qc-bjw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:priority-medium" /></template>
<style>
.gz0qc-bjw {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M16.25 6.25q0-3 3-3t3 3v11.5q0 3-3 3q-1.243 0-2.121-.879q-.879-.878-.879-2.121zM15 17.75v-6.5q0-3-3-3t-3 3v6.5q0 1.243.879 2.121q.878.879 2.121.879t2.121-.879Q15 18.993 15 17.75M2.629 14.129q.878-.879 2.121-.879q3 0 3 3v1.5q0 1.243-.879 2.121q-.878.879-2.121.879t-2.121-.879q-.879-.878-.879-2.121v-1.5q0-1.243.879-2.121");
}

</style>
