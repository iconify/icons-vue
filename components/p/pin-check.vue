<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ckr3oy4hv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:pin-check" /></template>
<style>
.ckr3oy4hv {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.495 19.555Q2.75 14.332 2.75 8.5q0-2.589 1.831-4.419Q6.411 2.25 9 2.25t4.419 1.831T15.25 8.5q0 5.832-5.745 11.055q-.052.047-.111.083t-.124.062t-.132.037q-.069.013-.138.013t-.138-.013q-.068-.012-.132-.037q-.065-.025-.124-.062q-.059-.036-.111-.083M9 5.75q-2.75 0-2.75 2.75T9 11.25t2.75-2.75T9 5.75m7.75 13.189l-1.47-1.469q-.105-.106-.243-.163t-.287-.057t-.287.057t-.243.163q-.053.052-.094.113t-.069.13t-.043.141T14 18t.014.146q.015.073.043.141t.069.13q.041.061.094.113l2 2q.052.053.113.094t.13.069t.141.043t.146.014q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094l4.25-4.25q.106-.105.163-.243t.057-.287t-.057-.287t-.163-.243q-.052-.053-.113-.094t-.13-.069t-.141-.043T21 15t-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094z");
}

</style>
