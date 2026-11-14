<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ng2un1k8j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:pipeline-inspection" /></template>
<style>
.ng2un1k8j {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.75 4.75q0-2-2-2q-.828 0-1.414.586T1.75 4.75v7.5q0 2 2 2t2-2h12.5q0 .66.218 1.103q.982.217 1.773.897h.009q2 0 2-2v-7.5q0-2-2-2t-2 2zm12.5 6H5.75v-4.5h12.5zm-.75 3.75q-3 0-3 3t3 3q.97 0 1.626-.313l1.344 1.343q.052.053.113.094t.13.069t.141.043t.146.014q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113l-1.343-1.344q.313-.656.313-1.626q0-3-3-3m0 4.5Q16 19 16 17.5t1.5-1.5t1.5 1.5t-1.5 1.5");
}

</style>
