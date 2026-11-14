<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p4hpbebuu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:specimen-preserved" /></template>
<style>
.p4hpbebuu {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.75 1.75h6.5q2.5 0 2.5 2.5q0 1.014-.702 1.737L19.53 8.47q.106.105.163.243T19.75 9v10q0 3.25-3.25 3.25h-9q-1.346 0-2.298-.952T4.25 19V9q0-.149.057-.287t.163-.243l2.482-2.483Q6.25 5.264 6.25 4.25q0-2.5 2.5-2.5m-.409 4.97L5.75 9.311V19q0 .725.513 1.237q.512.513 1.237.513h9q1.75 0 1.75-1.75V9.311L15.659 6.72q-.198.03-.409.03h-6.5q-.211 0-.409-.03M8.75 18q0-3.701 1.914-6.094Q12.39 9.75 14.5 9.75q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 3.792-1.713 6.075Q11.906 18.75 9.5 18.75q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T8.75 18");
}

</style>
