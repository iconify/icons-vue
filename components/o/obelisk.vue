<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jlg9hvbcy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:obelisk" /></template>
<style>
.jlg9hvbcy {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M10 21.75H7q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T6.25 21q0-.074.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043T7 20.25h2.278l.473-12.279q.004-.121.047-.234l1.5-4q.052-.14.154-.249t.238-.171t.285-.067t.288.048q.152.057.267.172t.172.267l1.5 4q.043.113.047.234l.473 12.279H17q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014z");
}

</style>
