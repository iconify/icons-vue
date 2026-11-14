<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cxd4qab6s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:rainfall-light" /></template>
<style>
.cxd4qab6s {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11.516 2.427q-.048.041-.089.089Q5.75 9.225 5.75 13q0 2.589 1.831 4.419Q9.411 19.25 12 19.25t4.419-1.831T18.25 13q0-3.775-5.677-10.484q-.097-.114-.229-.183q-.133-.068-.282-.08q-.148-.013-.29.033q-.143.045-.256.141M17 20.75q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014H7q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146q0-.074.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043T7 20.75z");
}

</style>
