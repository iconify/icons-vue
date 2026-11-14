<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p6tj8ulmw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:workstation-setup" /></template>
<style>
.p6tj8ulmw {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.125 1.75h11.75q3.375 0 3.375 3.375v5.75q0 3.375-3.375 3.375H12.75v.5h1.75q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-5q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146t.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014h1.75v-.5H6.125q-3.375 0-3.375-3.375v-5.75q0-3.375 3.375-3.375m13.125 15q1.036 0 1.768.732t.732 1.768v.5q0 1.036-.732 1.768t-1.768.732t-1.768-.732t-.732-1.768v-.5q0-1.036.732-1.768t1.768-.732m-5.25.5H4q-2.25 0-2.25 2.25v.5q0 2.25 2.25 2.25h10q.932 0 1.591-.659T16.25 20v-.5q0-.932-.659-1.591T14 17.25");
}

</style>
