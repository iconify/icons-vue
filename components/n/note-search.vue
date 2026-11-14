<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rs_77yjoy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:note-search" /></template>
<style>
.rs_77yjoy {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6 3.25Q3.25 3.25 3.25 6v12q0 2.75 2.75 2.75h8q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T13.25 20v-4q0-.915.305-1.526q-.194-.052-.335-.194l-.706-.705Q11.72 14 10.5 14Q7 14 7 10.5T10.5 7t3.5 3.5q0 1.22-.425 2.014l.705.706q.142.141.194.335q.611-.305 1.526-.305h4q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146V6q0-2.75-2.75-2.75zm14.53 11.28q-.105.106-.243.163T20 14.75h-4q-1.25 0-1.25 1.25v4q0 .149-.057.287t-.163.243z");
}

</style>
