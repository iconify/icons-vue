<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u7hht_iwm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:speed-bag" /></template>
<style>
.u7hht_iwm {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4 2.75h16q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043T20 4.25h-7.25v2h.75q.132 0 .255.045q.124.045.225.129q4.77 3.975 4.77 8.576q0 2.796-1.977 4.773T12 21.75t-4.773-1.977T5.25 15q0-4.601 4.77-8.576q.101-.084.225-.129q.123-.045.255-.045h.75v-2H4q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141Q3.25 3.574 3.25 3.5t.014-.146t.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043Q3.926 2.75 4 2.75");
}

</style>
