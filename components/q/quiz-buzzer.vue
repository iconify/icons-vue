<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k65deibfa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:quiz-buzzer" /></template>
<style>
.k65deibfa {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M10.75 8.341q.606-.091 1.25-.091t1.25.091V6.25h-2.5zm4 .388q1.503.563 2.73 1.791q2.007 2.007 2.24 4.75q2.53.225 2.53 2.98q0 1.243-.879 2.121q-.878.879-2.121.879H4.75q-1.243 0-2.121-.879q-.879-.878-.879-2.121q0-2.755 2.53-2.98q.233-2.743 2.24-4.75q1.227-1.228 2.73-1.791V5.5q0-.074.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043T10 4.75h4q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146zM5.79 15.25h12.42q-.231-2.11-1.791-3.669Q14.589 9.75 12 9.75t-4.419 1.831Q6.021 13.14 5.79 15.25");
}

</style>
