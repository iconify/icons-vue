<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wdvk7ydwc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:reply" /></template>
<style>
.wdvk7ydwc {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m10.03 6.53l-3.719 3.72H14q2.589 0 4.419 1.831q1.831 1.83 1.831 4.419V19q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T18.75 19v-2.5q0-1.968-1.391-3.359T14 11.75H6.311l3.719 3.72q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.105.106-.243.163t-.287.057t-.287-.057t-.243-.163l-5-5q-.106-.105-.163-.243T3.75 11t.057-.287t.163-.243v-.001l5-4.999q.105-.106.243-.163T9.5 5.25t.287.057t.243.163q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113");
}

</style>
