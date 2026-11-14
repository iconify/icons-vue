<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bj49zivak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:phone-check" /></template>
<style>
.bj49zivak {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M10.725 4.557Q10.243 2.75 8.5 2.75h-3q-2.75 0-2.75 2.75q0 6.311 4.72 11.03q4.719 4.72 11.03 4.72q2.75 0 2.75-2.75v-3q0-1.743-1.818-2.228l-3-.75l-.035-.007q-1.595-.32-2.521 1.069l-.633.949q-2.398-1.299-3.77-3.781l.943-.628q1.389-.926 1.069-2.521l-.007-.035zM16.5 7.439L15.03 5.97q-.105-.106-.243-.163T14.5 5.75t-.287.057t-.243.163q-.053.052-.094.113t-.069.13t-.043.141t-.014.146t.014.146q.015.073.043.141t.069.13q.041.061.094.113l2 2q.105.106.243.163t.287.057t.287-.057t.243-.163l4-4q.106-.105.163-.243t.057-.287t-.057-.287t-.163-.243q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014t-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094z");
}

</style>
