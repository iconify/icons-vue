<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zu1tbsbmq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:route-start" /></template>
<style>
.zu1tbsbmq {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.5 22.5q3.606 0 3.961-3.25H15q3.75 0 3.75-3.75T15 11.75H9q-1.139 0-1.945-.805Q6.25 10.139 6.25 9q0-2.75 2.75-2.75h10.5q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014H9q-1.76 0-3.005 1.245T4.75 9t1.245 3.005T9 13.25h6q2.25 0 2.25 2.25T15 17.75H9.461Q9.106 14.5 5.5 14.5q-4 0-4 4t4 4");
}

</style>
