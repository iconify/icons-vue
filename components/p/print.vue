<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="clectkblg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:print" /></template>
<style>
.clectkblg {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M18.5 7.25h-.75V4.5q0-1.75-1.75-1.75H8q-1.75 0-1.75 1.75v2.75H5.5q-1.139 0-1.945.805Q2.75 8.861 2.75 10v5q0 2.75 2.75 2.75h.75v1q0 2.5 2.5 2.5h6.5q2.5 0 2.5-2.5v-1h.75q2.75 0 2.75-2.75v-5q0-2.75-2.75-2.75M7.75 4.5v2.75h8.5V4.5q0-.25-.25-.25H8q-.25 0-.25.25m9.26 5.75q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141q.014.072.014.146t-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014H17q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T16.25 11t.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014z");
}

</style>
