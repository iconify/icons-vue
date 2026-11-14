<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g-hljveee"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:print-queue" /></template>
<style>
.g-hljveee {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.25 3v2.5H6q-.074 0-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146v3.01q-.979.08-1.695.795q-.805.806-.805 1.945v3q0 2.75 2.75 2.75h.75v1.5q0 1.036.732 1.768t1.768.732h6.5q1.036 0 1.768-.732t.732-1.768v-1.5h.75q2.75 0 2.75-2.75v-3q0-2.345-2-2.69V3q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014H9q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141T8.25 3m9.5 6.25v-5.5h-8V5.5h5.75q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146v3zm-3-2.25v2.25h-8V7z");
}

</style>
