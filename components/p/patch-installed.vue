<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fkx91yxel"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:patch-installed" /></template>
<style>
.fkx91yxel {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m3.874 8.824l4.95-4.95q2.651-2.651 5.302 0t0 5.302l-4.95 4.95q-2.651 2.651-5.302 0t0-5.302m2.121-1.415q-.66.659-.66 1.591t.66 1.591l1.414 1.414q.659.66 1.591.66t1.591-.66l1.414-1.414q.66-.659.66-1.591t-.66-1.591l-1.414-1.414q-.659-.66-1.591-.66t-1.591.66zm10.755 11.53l-1.47-1.469q-.105-.106-.243-.163t-.287-.057t-.287.057t-.243.163q-.053.052-.094.113t-.069.13t-.043.141T14 18t.014.146q.015.073.043.141t.069.13q.041.061.094.113l2 2q.052.053.113.094t.13.069t.141.043t.146.014q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094l4.25-4.25q.106-.105.163-.243t.057-.287t-.057-.287t-.163-.243q-.052-.053-.113-.094t-.13-.069t-.141-.043T21 15t-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094z");
}

</style>
