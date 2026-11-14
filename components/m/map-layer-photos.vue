<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r7mr_3byx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:map-layer-photos" /></template>
<style>
.r7mr_3byx {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.875 2.75h10.25q2.123 0 3.624 1.501t1.501 3.624v8.25q0 .732-.178 1.39q-.02-.024-.042-.045l-5-5q-.105-.106-.243-.163t-.287-.057t-.287.057t-.243.163L13 15.439L8.53 10.97q-.105-.106-.243-.163T8 10.75t-.287.057t-.243.163l-5.5 5.5q-.128.128-.184.3q-.036-.315-.036-.645v-8.25q0-2.123 1.501-3.624T6.875 2.75M13.5 8q0 2.5 2.5 2.5T18.5 8T16 5.5T13.5 8m7.47 10.53q.113.113.262.171q.15.057.309.048q-.322.53-.792 1q-1.501 1.501-3.624 1.501H6.875q-2.123 0-3.624-1.501q-1-1.001-1.334-2.277q.025.03.053.058q.105.106.243.163t.287.057t.287-.057t.243-.163L8 12.561l4.47 4.469q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094l2.97-2.969z");
}

</style>
