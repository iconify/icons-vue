<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b2_lpllhx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:map-pin-clock" /></template>
<style>
.b2_lpllhx {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.75 9.5q0 5.842 7.759 12.567q.051.044.108.078q.058.034.121.058q.063.023.129.035t.133.012t.133-.012t.129-.035q.063-.024.121-.058t.108-.078Q20.25 15.342 20.25 9.5q0-3.417-2.416-5.834T12 1.25T6.166 3.666Q3.75 6.083 3.75 9.5m9-.416l1.647 1.03q.063.039.117.09t.097.111t.073.127t.047.139t.019.146t-.01.147t-.039.142t-.065.131q-.039.063-.09.117t-.111.097t-.127.073t-.139.047t-.146.019t-.147-.01t-.142-.039t-.131-.065l-2-1.25q-.081-.051-.147-.12t-.112-.152t-.07-.176t-.024-.188V7q0-.074.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043T12 6.25t.146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146z");
}

</style>
