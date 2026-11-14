<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mr3dzkfnm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:surfboard-beach" /></template>
<style>
.mr3dzkfnm {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.651 10.305q-1.563 5.804.66 10.99q.063.148.181.257t.271.16q3.912 1.304 8.443.009q.163-.046.29-.158t.193-.268q2.223-5.186.66-10.99Q15.922 5.004 12.45 2.4q-.048-.036-.102-.064t-.111-.048t-.117-.028q-.06-.01-.12-.01t-.12.01t-.117.028q-.058.02-.111.048q-.054.028-.102.064q-3.472 2.604-4.899 7.905M12.75 20.5q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146v-17q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043q.072-.014.146-.014t.146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146z");
}

</style>
