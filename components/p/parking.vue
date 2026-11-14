<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ykr2q0skr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:parking" /></template>
<style>
.ykr2q0skr {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M10.875 2.25h2.25q3.573 0 6.099 2.526t2.526 6.099v2.25q0 3.573-2.526 6.099t-6.099 2.526h-2.25q-3.573 0-6.099-2.526T2.25 13.125v-2.25q0-3.573 2.526-6.099t6.099-2.526M8.5 13.5v4q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141T10 17.5v-3.25h3.25q1.76 0 3.005-1.245T17.5 10t-1.245-3.005T13.25 5.75h-4q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141T8.5 6.5zm1.5-.75h3.25Q16 12.75 16 10t-2.75-2.75H10z");
}

</style>
