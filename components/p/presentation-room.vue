<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="txq52_bjr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:presentation-room" /></template>
<style>
.txq52_bjr {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M20 2H4q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141q-.014.072-.014.146t.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043Q3.926 3.5 4 3.5h16q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T20 2m-8 4.25q4 0 4 4v8q0 1.657-1.172 2.828Q13.657 22.25 12 22.25t-2.828-1.172Q8 19.907 8 18.25v-8q0-4 4-4m-5.25 4q0-2-2-2q-.828 0-1.414.586T2.75 10.25v.5q0 2 2 2t2-2zm12.5-2q-2 0-2 2v.5q0 2 2 2t2-2v-.5q0-2-2-2m-14.5 6q2 0 2 2v.5q0 2-2 2t-2-2v-.5q0-.828.586-1.414t1.414-.586m12.5 2q0-2 2-2t2 2v.5q0 2-2 2t-2-2z");
}

</style>
