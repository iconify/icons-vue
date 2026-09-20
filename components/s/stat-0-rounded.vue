<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s2_yuab3c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:stat-0-rounded" /></template>
<style>
.s2_yuab3c {
  fill: currentColor;
  d: path("m10.867 16.444l-3.31-3.31q-.24-.24-.351-.538q-.112-.298-.112-.596t.112-.596t.35-.537l3.31-3.31q.24-.24.538-.351q.298-.112.596-.112t.596.112t.538.35l3.31 3.31q.239.24.35.538q.112.298.112.596t-.112.596t-.35.537l-3.31 3.31q-.24.24-.538.351q-.298.112-.596.112t-.596-.112t-.537-.35");
}

</style>
