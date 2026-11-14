<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z__i_n74h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:toggle-on" /></template>
<style>
.z__i_n74h {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8 5.75h8q2.589 0 4.419 1.831Q22.25 9.411 22.25 12t-1.831 4.419T16 18.25H8q-2.589 0-4.419-1.831Q1.75 14.589 1.75 12t1.831-4.419Q5.411 5.75 8 5.75M12.25 12q0-3.75 3.75-3.75T19.75 12T16 15.75T12.25 12M7.5 14.5q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146v-3.5q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T7.5 9.5t-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146v3.5q0 .074.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014m6.25-2.5q0 2.25 2.25 2.25T18.25 12T16 9.75T13.75 12");
}

</style>
