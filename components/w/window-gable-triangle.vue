<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jumqp_gid"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:window-gable-triangle" /></template>
<style>
.jumqp_gid {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11.388 3.066L2.943 14.989q-1.193.534-1.193 2.261v2q0 1.036.732 1.768t1.768.732h15.5q1.036 0 1.768-.732t.732-1.768v-2q0-1.036-.732-1.768q-.158-.158-.331-.282q-.03-.071-.075-.134l-8.5-12q-.074-.104-.178-.178q-.183-.129-.406-.137L12 2.75q-.09 0-.177.021q-.088.022-.168.063q-.079.041-.147.1t-.12.132m-3.25 7.184l3.112-4.394v4.394zm-1.063 1.5h4.175v3h-6.3zm5.675 0h4.175l2.125 3h-6.3zm3.112-1.5H12.75V5.856z");
}

</style>
