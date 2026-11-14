<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fju5kwpgo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:village" /></template>
<style>
.fju5kwpgo {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9.25 11.689V10q0-.145.054-.28q.054-.134.155-.239l5.75-6q.051-.053.111-.096q.061-.042.128-.072q.068-.029.14-.045t.146-.018t.147.011t.141.04t.131.067t.116.091l.022.022l5.75 6q.101.105.155.239q.054.135.054.28v10.5q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014H16q2.25 0 2.25-2.25v-2.5q0-2.25-2.25-2.25h-.5q-2.25 0-2.25 2.25V19q0 2.25 2.25 2.25h-13q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146v-7q0-.149.057-.287t.163-.243l3.75-3.75q.105-.106.243-.163T6.25 9t.287.057t.243.163zm0 2.122l-3-3l-3 3v5.939h6z");
}

</style>
