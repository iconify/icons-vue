<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ggur5zqld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:suitcase" /></template>
<style>
.ggur5zqld {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M19.249 8.251q-1.457-1.457-3.499-1.5V6q0-2.25-2.25-2.25h-3Q8.25 3.75 8.25 6v.751q-2.042.043-3.499 1.5Q3.25 9.752 3.25 11.875V13q0-.074.014-.147q.015-.072.043-.14q.029-.069.07-.13t.093-.113t.113-.094t.13-.069t.141-.043q.072-.014.146-.014h16q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014H4q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094t-.093-.113t-.07-.13t-.043-.14Q3.25 13.074 3.25 13v2.625q0 2.123 1.501 3.624t3.624 1.501h7.25q2.123 0 3.624-1.501t1.501-3.624v-3.75q0-2.123-1.501-3.624M14.25 6.75h-4.5V6q0-.75.75-.75h3q.75 0 .75.75z");
}

</style>
