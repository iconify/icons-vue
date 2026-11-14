<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w5zz7cbss"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:pin-paint" /></template>
<style>
.w5zz7cbss {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.125 1.75h9.25q3.182 0 3.364 3H20.5q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146v6q0 .074-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-7.75v1.076q1.5.337 1.5 2.174V20q0 2.25-2.25 2.25T9.75 20v-4.5q0-1.837 1.5-2.174V11.5q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014h7.75v-4.5h-1.011q-.182 3-3.364 3h-9.25q-3.375 0-3.375-3.375v-.75q0-3.375 3.375-3.375");
}

</style>
