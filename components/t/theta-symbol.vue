<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jt6lbhb_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:theta-symbol" /></template>
<style>
.jt6lbhb_c {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.123 4.882Q5.25 7.848 5.25 12t1.873 7.118Q9.101 22.25 12 22.25t4.877-3.132Q18.75 16.152 18.75 12t-1.873-7.118Q14.899 1.75 12 1.75T7.123 4.882M18.75 12q0 .074-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014H6q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T5.25 12t.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043T6 11.25h12q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146");
}

</style>
