<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s2yjeipmx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:tree-ornament" /></template>
<style>
.s2yjeipmx {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m13.893 4.057l2.697 4.195q.415.647.047 1.322q-.284.52-.806.639l2.871 4.593q.702 1.124.06 2.284q-.643 1.159-1.968 1.159H12.75v3.25q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146v-3.25H7.206q-1.325 0-1.968-1.159q-.642-1.16.06-2.283l2.871-4.594q-.522-.119-.806-.639q-.368-.675.047-1.321l2.697-4.197Q10.771 3.024 12 3.024t1.893 1.033M9.5 13.5Q9.5 16 12 16q1.036 0 1.768-.732T14.5 13.5t-.732-1.768T12 11q-2.5 0-2.5 2.5");
}

</style>
