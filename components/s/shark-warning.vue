<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j5ybxabli"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:shark-warning" /></template>
<style>
.j5ybxabli {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m19.972 15.728l-5.026-8.993Q13.979 5.007 12 5.007T9.054 6.735l-5.026 8.993q-.943 1.687.035 3.355t2.911 1.667h10.052q1.933 0 2.911-1.667t.035-3.355M7.4 16.05q.323-.431 1.012-1.505q2.874-4.484 5.793-5.734q.067-.029.14-.045q.072-.015.146-.016t.146.013t.142.041q.068.027.13.067t.115.092t.094.113t.071.129q.061.141.061.295v7q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014H8q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146q0-.122.038-.237q.039-.116.112-.213");
}

</style>
