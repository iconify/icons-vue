<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pf0pa3_-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:mansard-roof" /></template>
<style>
.pf0pa3_-t {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m5.882 4.424l-2.275 6.5q-.427 1.219.321 2.273q.351.494.822.757V21q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014h13q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146v-7.046q.471-.263.822-.757q.748-1.054.321-2.273l-2.275-6.5q-.586-1.674-2.36-1.674H8.242q-1.774 0-2.36 1.674M17.75 14.25v6H6.25v-6z");
}

</style>
