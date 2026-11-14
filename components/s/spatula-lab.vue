<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xfiu50bkq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:spatula-lab" /></template>
<style>
.xfiu50bkq {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m12.177 7.227l2.475-2.475q.952-.952 2.298-.952t2.298.952t.952 2.298t-.952 2.298l-2.475 2.475q-.952.952-2.298.952q-.955 0-1.711-.478L9.471 15.59q.822 1.299-.477 2.597l-1.059 1.061q-.66.66-1.592.66t-1.591-.66q-.66-.659-.66-1.591t.66-1.591v-.001l1.061-1.06q1.299-1.298 2.597-.476l3.293-3.293q-.478-.756-.478-1.711q0-1.346.952-2.298");
}

</style>
