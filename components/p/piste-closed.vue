<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u-blkwosa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:piste-closed" /></template>
<style>
.u-blkwosa {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M18.695 15.866L8.134 5.305l1.48-1.479q2.386-2.386 4.772 0l5.788 5.788q2.386 2.386 0 4.772zM4.03 2.97l17 17q.053.052.094.113t.069.13t.043.141t.014.146q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094l-17-17q-.053-.052-.094-.113t-.069-.13t-.043-.141T2.75 3.5t.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043q.072-.014.146-.014t.146.014q.073.015.141.043t.13.069t.113.094m10.356 17.204l1.48-1.479L5.305 8.134l-1.479 1.48q-2.386 2.386 0 4.772l5.788 5.788q2.386 2.386 4.772 0");
}

</style>
