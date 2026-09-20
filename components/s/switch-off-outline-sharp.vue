<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zgg70jx_i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:switch-off-outline-sharp" /></template>
<style>
.zgg70jx_i {
  fill: currentColor;
  d: path("M4 22V2h16v20zm2-2h12V4H6zm2-3h8V7H8zm6-8v4h-4V9zm-2 10.25q.325 0 .538-.225t.212-.525q0-.325-.213-.537T12 17.75q-.3 0-.525.213t-.225.537q0 .3.225.525t.525.225m0-13q.325 0 .538-.225t.212-.525q0-.325-.213-.537T12 4.75q-.3 0-.525.213t-.225.537q0 .3.225.525T12 6.25M12 12");
}

</style>
