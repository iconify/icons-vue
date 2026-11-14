<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cjqq6pb4o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:trajectory" /></template>
<style>
.cjqq6pb4o {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.5 20.75h19q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014H4.856Q6.278 9.129 10.541 6.849q1.666-.891 3.308-.036q1.48.772 2.566 2.71q-1.165.781-1.165 2.727q0 3.25 3.25 3.25q1.346 0 2.298-.952t.952-2.298t-.952-2.298T18.5 9q-.339 0-.643.035q-1.342-2.523-3.315-3.552q-2.344-1.222-4.708.043Q4.857 8.188 3.342 19.25H2.5q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141T1.75 20t.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014");
}

</style>
