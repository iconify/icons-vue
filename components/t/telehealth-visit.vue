<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p54zzeb6e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:telehealth-visit" /></template>
<style>
.p54zzeb6e {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.25 4.25h-.125q-3.375 0-3.375 3.375v5.75q0 3.375 3.375 3.375h11.75q3.375 0 3.375-3.375v-5.75q0-3.375-3.375-3.375H13.25V7q0 3.324-2.75 3.702v.798q0 1.25 1.5 1.25q1.25 0 1.25-1q0-.038.004-.077q-.004-.084-.004-.173q0-2 2-2t2 2t-2 2q-.545 0-.941-.148q-.66.898-2.309.898q-3 0-3-2.75v-.798Q6.25 10.324 6.25 7zM11.75 7q0 2.25-2 2.25T7.75 7V4.25h4zM2 18.25q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141T1.25 19t.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069q.068.028.141.043T2 19.75h20q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T22 18.25z");
}

</style>
