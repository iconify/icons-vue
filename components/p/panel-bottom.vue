<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qh2ji3bzd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:panel-bottom" /></template>
<style>
.qh2ji3bzd {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.875 2.75h10.25q2.123 0 3.624 1.501t1.501 3.624v8.25q0 2.123-1.501 3.624t-3.624 1.501H6.875q-2.123 0-3.624-1.501T1.75 16.125v-8.25q0-2.123 1.501-3.624T6.875 2.75M12 9.189L9.53 6.72q-.105-.106-.243-.163T9 6.5t-.287.057t-.243.163q-.053.052-.094.113t-.069.13t-.043.141t-.014.146t.014.146q.015.073.043.141t.069.13q.041.061.094.113l3 3q.105.106.243.163T12 11t.287-.057t.243-.163l3-3q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.105-.106-.243-.163T15 6.5t-.287.057t-.243.163z");
}

</style>
