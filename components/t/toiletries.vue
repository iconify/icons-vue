<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e3dwpkbgp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:toiletries" /></template>
<style>
.e3dwpkbgp {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7 4.75h1q2.25 0 2.25 2.25v.5q0 .921-.377 1.465q.331.229.632.53Q11.75 10.74 11.75 12.5v5q0 1.76-1.245 3.005T7.5 21.75t-3.005-1.245T3.25 17.5v-5q0-1.76 1.245-3.005q.301-.301.632-.53Q4.75 8.421 4.75 7.5V7q0-2.25 2.25-2.25m10.5 6.539q3.25.355 3.25 3.961v2.5q0 1.657-1.172 2.828q-1.171 1.172-2.828 1.172t-2.828-1.172q-1.172-1.171-1.172-2.828v-2.5q0-3.606 3.25-3.961V9q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014h2.75q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-2z");
}

</style>
