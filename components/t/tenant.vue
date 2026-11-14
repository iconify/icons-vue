<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ppbdokbvi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:tenant" /></template>
<style>
.ppbdokbvi {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12.75 22.25h8.75q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014h-2.106l.441-.177q1.415-.565 1.415-2.089V5.516q0-1.524-1.414-2.089l-2-.8h-.001q-1.027-.411-1.952.134q-.125-.185-.292-.352Q14.932 1.75 14 1.75H5Q2.75 1.75 2.75 4v16.75H2.5q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146t.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014zm.738-1.5Q13.28 14.5 9.5 14.5t-3.988 6.25H4.25V4q0-.75.75-.75h9q.75 0 .75.75v16.75zm-6.476 0Q7.177 16 9.5 16t2.488 4.75zM9.5 5.25q-3.25 0-3.25 3.25t3.25 3.25t3.25-3.25T9.5 5.25");
}

</style>
