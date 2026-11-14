<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gfs6b3s9t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:visited-places" /></template>
<style>
.gfs6b3s9t {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.75 9.5q0 5.842 7.759 12.567q.051.044.108.078q.058.034.121.058q.063.023.129.035t.133.012t.133-.012t.129-.035q.063-.024.121-.058t.108-.078Q20.25 15.342 20.25 9.5q0-3.417-2.416-5.834T12 1.25T6.166 3.666Q3.75 6.083 3.75 9.5m7.484 1.173l3.47-3.687q.05-.054.111-.097q.06-.043.127-.073t.139-.047t.146-.019t.147.01t.142.039t.132.065t.116.09t.097.111t.073.127t.047.139q.016.072.019.146t-.01.147t-.039.142t-.065.132t-.09.116l-4 4.25l-.016.016q-.105.106-.243.163t-.287.057t-.287-.057t-.243-.163l-2.25-2.25q-.106-.105-.163-.243T8.25 9.5t.057-.287t.163-.243q.052-.053.113-.094t.13-.069t.141-.043T9 8.75t.146.014q.073.015.141.043t.13.069t.113.094z");
}

</style>
