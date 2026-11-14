<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tln5lbcsc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:pill-bell" /></template>
<style>
.tln5lbcsc {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.97 13.97Q4.75 12.189 4.75 8q0-2.382 1.684-4.066T10.5 2.25t4.066 1.684T16.25 8q0 4.189 1.78 5.97q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.105.106-.243.163t-.287.057h-4.31q-.345 2-2.69 2t-2.69-2H3.5q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141q-.014-.072-.014-.146q0-.149.057-.287t.163-.243m6.449 1.28q.29.5 1.081.5t1.081-.5zm6.956 1.5h3.75q2.625 0 2.625 2.625q0 1.087-.769 1.856T20.125 22h-3.75q-1.087 0-1.856-.769t-.769-1.856q0-2.625 2.625-2.625m0 1.5q-1.125 0-1.125 1.125q0 .466.33.795q.329.33.795.33h3.75q.466 0 .795-.33q.33-.329.33-.795q0-1.125-1.125-1.125z");
}

</style>
