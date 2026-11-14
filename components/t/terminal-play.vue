<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wrsp_5ydz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:terminal-play" /></template>
<style>
.wrsp_5ydz {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.875 2.25h10.25q2.123 0 3.624 1.501t1.501 3.624v9.25q0 2.123-1.501 3.624t-3.624 1.501H6.875q-2.123 0-3.624-1.501T1.75 16.625v-9.25q0-2.123 1.501-3.624T6.875 2.25M6.53 6.47q-.052-.053-.113-.094t-.13-.069t-.141-.043T6 6.25t-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.053.052-.094.113t-.069.13t-.043.141T5.25 7t.014.146q.015.073.043.141t.069.13q.041.061.094.113L7.439 9.5L5.47 11.47q-.106.105-.163.243T5.25 12t.057.287t.163.243q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094l2.5-2.5q.106-.105.163-.243T9.25 9.5t-.057-.287t-.163-.243zm8.149 4.298q-1.124-.691-2.276-.048q-1.152.644-1.153 1.964v2.632q.001 1.32 1.153 1.964t2.276-.048l2.138-1.316q1.07-.66 1.07-1.916t-1.07-1.916z");
}

</style>
