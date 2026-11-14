<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b13ldvbog"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:pet-crate" /></template>
<style>
.b13ldvbog {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M15.75 6.04q6 1.057 6 5.96v8.5q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014H3q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146V12q0-4.903 6-5.96V4q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043Q8.926 3.25 9 3.25h6q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146zm-6-.196Q10.801 5.75 12 5.75t2.25.094V4.75h-4.5zM7.5 9.75q-2.5 0-2.5 2.5v4q0 1.036.732 1.768t1.768.732h4.75q1.036 0 1.768-.732t.732-1.768v-4q0-2.5-2.5-2.5z");
}

</style>
