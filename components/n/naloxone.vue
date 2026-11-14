<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kwgervbrl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:naloxone" /></template>
<style>
.kwgervbrl {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M17 9.25h-3.052l-.45-6.303l-.005-.046Q13.332 1.688 12 1.688t-1.493 1.213l-.005.046l-.45 6.303H7q-1.75 0-1.75 1.75T7 12.75h1.757q-.507.872-.507 2.25v3.5q0 3.75 3.75 3.75t3.75-3.75V15q0-1.378-.507-2.25H17q1.75 0 1.75-1.75T17 9.25m-4.994-6.141l.439 6.141h-.89l.439-6.141l.006.079zM14.25 16q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-3q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T9.75 16t.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014h3q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146");
}

</style>
