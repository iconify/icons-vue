<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e5-vtvbdy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:press-accreditation" /></template>
<style>
.e5-vtvbdy {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8 5.5q0-4 4-4q1.657 0 2.828 1.172Q16 3.843 16 5.5q0 4-4 4t-4-4M2.75 19v2.5q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146V19q0-4.886 4.737-5.952l1.202 1.202H9.5q-2.5 0-2.5 2.5v2q0 2.5 2.5 2.5h5q1.036 0 1.768-.732T17 18.75v-2q0-1.036-.732-1.768T14.5 14.25h-.689l1.202-1.202Q19.75 14.114 19.75 19v2.5q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146V19q0-3.67-2.659-5.776Q16.096 11.25 12 11.25t-6.591 1.974Q2.75 15.33 2.75 19m10.402-6.213L12 13.939l-1.152-1.152q.553-.037 1.152-.037t1.152.037");
}

</style>
