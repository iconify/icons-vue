<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hku331uys"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:pen" /></template>
<style>
.hku331uys {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11.25 3.059q-.989.211-1.724 1.003l-3.56 3.834q-1.306 1.406-.765 3.249l1.526 5.183q.712 2.422 3.237 2.422h4.072q2.525 0 3.238-2.422l1.525-5.183q.541-1.843-.765-3.249l-3.56-3.834q-.735-.792-1.724-1.003V9.06q2 .345 2 2.69q0 2.75-2.75 2.75t-2.75-2.75q0-2.345 2-2.69zM16.75 21q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T16 20.25H8q-.074 0-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.053.052-.094.113t-.069.13t-.043.141T7.25 21q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014h8q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146");
}

</style>
