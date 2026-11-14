<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wqczv5byo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:triangle" /></template>
<style>
.wqczv5byo {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m14.919 7.533l4.44 7.647q.979 1.688.006 3.379q-.974 1.691-2.925 1.691H7.56q-1.951 0-2.925-1.691t.006-3.379l4.44-7.647q.976-1.68 2.919-1.68t2.919 1.68");
}

</style>
