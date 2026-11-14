<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pejo6bb2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:smart-speaker-mute" /></template>
<style>
.pejo6bb2m {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M18.75 5.5v10.422l-1.5-1.5v-6.58q-1.682.908-5.25.908q-.216 0-.425-.003L6.283 3.455Q7.891 2.25 12 2.25q6.75 0 6.75 3.25M4.03 2.97l17 17q.053.052.094.113t.069.13t.043.141t.014.146q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094l-17-17q-.053-.052-.094-.113t-.069-.13t-.043-.141T2.75 3.5t.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043q.072-.014.146-.014t.146.014q.073.015.141.043t.13.069t.113.094M12 20.25q3.479 0 4.653-.769l1.064 1.064Q16.109 21.75 12 21.75q-6.75 0-6.75-3.25V8.078l1.5 1.5V18.5q0 1.75 5.25 1.75");
}

</style>
