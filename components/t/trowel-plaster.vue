<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wgge2gb9e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:trowel-plaster" /></template>
<style>
.wgge2gb9e {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M16.442 4.248q1.577-.716 2.801.509q1.225 1.224.509 2.801l-2.024 4.453q-.542 1.192-1.83 1.426t-2.214-.693L13 12.061l-1.988 1.988q.822 1.299-.477 2.597l-3.889 3.889q-1.59 1.591-3.181 0t0-3.181l3.889-3.889q1.299-1.299 2.597-.477L11.939 11l-.683-.684q-.926-.925-.693-2.214t1.426-1.83z");
}

</style>
