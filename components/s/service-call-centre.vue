<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ipyjbhbpt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:service-call-centre" /></template>
<style>
.ipyjbhbpt {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.75 12v.438q-1.5.531-1.5 2.562v2q0 2.75 2.75 2.75T7.75 17v-2q0-2.622-2.5-2.744V12q0-2.796 1.977-4.773T12 5.25t4.773 1.977T18.75 12v.256q-2.5.122-2.5 2.744v2q0 2.234 1.815 2.653Q17.364 20.75 14 20.75q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146t.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014q5.091 0 5.674-2.547Q21.75 19.389 21.75 17v-2q0-2.031-1.5-2.562V12q0-3.417-2.416-5.834T12 3.75T6.166 6.166Q3.75 8.583 3.75 12");
}

</style>
