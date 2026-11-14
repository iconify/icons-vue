<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="euofwwbki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:ph-neutral" /></template>
<style>
.euofwwbki {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11.488 1.952q-.019.017-.036.036Q4.25 9.704 4.25 14.5q0 3.21 2.27 5.48T12 22.25t5.48-2.27t2.27-5.48q0-4.796-7.202-12.512q-.102-.109-.237-.171q-.136-.061-.285-.067q-.149-.005-.289.048q-.14.052-.249.154M16 13.75q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014H8q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146t.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043T8 13.75z");
}

</style>
