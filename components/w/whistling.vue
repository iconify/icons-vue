<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pbta-0bpa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:whistling" /></template>
<style>
.pbta-0bpa {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M19.5 2.5v3.7q-.459-.2-1-.2Q16 6 16 8.5t2.5 2.5q1.036 0 1.768-.732T21 8.5V4.142q.25.614.25 1.608q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043T22 6.5q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146q0-3.316-2.294-3.971q-.101-.029-.206-.029q-.074 0-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146M3.635 10.461Q1.75 12.285 1.75 15.5q0 2.89 2.149 4.865Q5.95 22.25 8.75 22.25t4.851-1.885Q15.75 18.39 15.75 15.5q0-3.215-1.885-5.039q-1.947-1.884-4.17-.896q-.088.039-.164.099l-.781.626l-.781-.626q-.076-.06-.164-.099q-2.223-.988-4.17.896M5.75 16q0-2.25 3-2.25t3 2.25t-3 2.25t-3-2.25");
}

</style>
