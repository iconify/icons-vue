<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bhe_6bk_w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:safe-deposit-key" /></template>
<style>
.bhe_6bk_w {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.641 8.641Q3.25 10.032 3.25 12t1.391 3.359T8 16.75t3.359-1.391q1.118-1.118 1.337-2.609h4.554V15q0 .074.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146v-2.25h1.5v1.75q0 .074.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146V12q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T21 11.25h-8.304q-.219-1.491-1.337-2.609Q9.968 7.25 8 7.25T4.641 8.641");
}

</style>
