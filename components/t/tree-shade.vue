<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c-j2jrbic"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:tree-shade" /></template>
<style>
.c-j2jrbic {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.581 3.081Q2.75 4.911 2.75 7.5t1.831 4.419q1.559 1.56 3.669 1.791v4.54H3.5q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141T2.75 19t.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014h4.923q.889 1.75 6.327 1.75q6.5 0 6.5-2.5t-6.5-2.5q-3.377 0-5 .675V13.71q2.11-.231 3.669-1.791q1.831-1.83 1.831-4.419t-1.831-4.419T9 1.25T4.581 3.081");
}

</style>
