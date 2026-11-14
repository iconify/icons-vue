<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rk097iysb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:ring-apron" /></template>
<style>
.rk097iysb {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.75 3.5V6h12.5V3.5q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043T19 2.75t.146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146v8.796q.719.138 1.268.686q.732.732.732 1.768v5q0 1.036-.732 1.768t-1.768.732H4.75q-1.036 0-1.768-.732T2.25 19.75v-5q0-2.236 2-2.472V3.5q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043Q4.926 2.75 5 2.75t.146.014t.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146m0 7.25v1.5h12.5v-1.5zm12.5-1.5V7.5H5.75v1.75z");
}

</style>
