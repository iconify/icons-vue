<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zcklx6bxn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:player-tracking" /></template>
<style>
.zcklx6bxn {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.641 3.641Q6.25 5.032 6.25 7t1.391 3.359T11 11.75t3.359-1.391T15.75 7t-1.391-3.359T11 2.25T7.641 3.641M11 14.75q1.709 0 3.086.456q.285-.703.812-1.305q-1.732-.651-3.898-.651q-3.71 0-6.15 1.909q-2.6 2.035-2.6 5.341q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146q0-2.575 2.025-4.159Q7.807 14.75 11 14.75m6.97 7.53Q15 19.311 15 17q0-3.5 3.5-3.5T22 17q0 2.311-2.97 5.28q-.052.053-.113.094t-.13.069t-.141.043t-.146.014q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094M20.5 17q0 1.502-2 3.669q-2-2.167-2-3.669q0-2 2-2t2 2m-1.363.589q-.332-.705-.841-1.323q-.546.094-.546.734q0 .69.75 1.723q.458-.631.637-1.134");
}

</style>
