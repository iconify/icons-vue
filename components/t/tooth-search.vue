<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t3yj_1vpo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:tooth-search" /></template>
<style>
.t3yj_1vpo {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.5 2.75q1.205 0 2.842.599q1.095.401 1.658.401t1.658-.401q1.637-.599 2.842-.599q4.25 0 4.25 5.25q0 1.66-.825 4.183q-.283.865-.465 1.532q-.884-.465-1.96-.465q-1.76 0-3.005 1.245q-.408.407-.682.871l-.043-.193q-.238-.923-1.77-.923t-1.77.923l-.995 4.474q-.308 1.541-1.735 1.541t-1.735-1.541l-1-5q-.184-.916-.69-2.464Q3.25 9.66 3.25 8q0-5.25 4.25-5.25m10 11.75q-3 0-3 3t3 3q.97 0 1.626-.313l1.344 1.343q.052.053.113.094t.13.069t.141.043t.146.014q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113l-1.343-1.344q.313-.656.313-1.626q0-3-3-3m0 4.5Q16 19 16 17.5t1.5-1.5t1.5 1.5t-1.5 1.5m-.25-1.5q0 .25.25.25t.25-.25t-.25-.25t-.25.25");
}

</style>
