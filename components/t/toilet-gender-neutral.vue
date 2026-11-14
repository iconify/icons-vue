<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ts_ecgbhk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:toilet-gender-neutral" /></template>
<style>
.ts_ecgbhk {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M14.121 2.379Q13.243 1.5 12 1.5q-3 0-3 3t3 3t3-3q0-1.243-.879-2.121M12.75 17.25H14v4.25q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146v-4.25h2q.166 0 .317-.07q.067-.032.127-.075q.059-.044.109-.098t.088-.118q.039-.063.064-.133q.025-.069.036-.142q.012-.073.008-.147q-.003-.074-.021-.145q-.017-.072-.048-.139l-3.5-7.5q-.046-.097-.116-.178t-.161-.138t-.193-.087t-.21-.03H9.5q-2.25 0-2.25 2.25v11q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014h4q.074 0 .146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146zm0-1.5v-6h.772l2.8 6z");
}

</style>
