<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c0gb_ccfm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:triangle-right" /></template>
<style>
.c0gb_ccfm {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m8.82 4.641l7.647 4.44q1.68.976 1.68 2.919t-1.68 2.919l-7.647 4.44q-1.688.979-3.379.006q-1.691-.974-1.691-2.925V7.56q0-1.951 1.691-2.925t3.379.006");
}

</style>
