<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tv7-0-0na"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:testing-centre" /></template>
<style>
.tv7-0-0na {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M17 1.75H7q-.074 0-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146t.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043q.072.014.146.014h.75V17.5q0 1.76 1.245 3.005T12 21.75t3.005-1.245T16.25 17.5V3.25H17q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T17 1.75m-2.25 9.5h-5.5v-8h5.5zm-5.5 1.5h5.5v4.75q0 1.139-.805 1.945q-.806.805-1.945.805q-2.75 0-2.75-2.75z");
}

</style>
