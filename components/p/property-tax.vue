<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s7tohmbwu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:property-tax" /></template>
<style>
.s7tohmbwu {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.25 5.25q0-1.243.878-2.122q.879-.879 2.122-.879t2.122.879t.878 2.122t-.878 2.122q-.879.879-2.122.879t-2.122-.879T2.25 5.25m.22 9.22l12-12q.105-.106.243-.163T15 2.25t.287.057t.243.163q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13t-.094.113l-12 12q-.052.053-.113.094t-.13.069t-.141.043T3 15.75t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.106-.105-.163-.243T2.25 15t.057-.287t.163-.243M12.5 9.75q-2.75 0-2.75 2.75t2.75 2.75t2.75-2.75t-2.75-2.75m1.715 7.257v-.001l2.25-2.099q1.535-1.431 3.07-.001l2.25 2.101q.715.667.715 1.645v1.598q0 2.25-2.25 2.25h-4.5q-2.25 0-2.25-2.25v-1.598q0-.978.715-1.645m1.024 1.097q-.239.222-.239.548v1.598q0 .75.75.75h4.5q.75 0 .75-.75v-1.598q0-.326-.239-.549l-2.25-2.099q-.511-.477-1.022-.001z");
}

</style>
