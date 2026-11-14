<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kpwxgabby"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:visual-programming" /></template>
<style>
.kpwxgabby {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.875 1.75h-2.75q-3.375 0-3.375 3.375v1.75q0 3.375 3.375 3.375h2.75q3.375 0 3.375-3.375V6.75h4.25q1.25 0 1.25 1.25v4.689l-1.22-1.219q-.052-.053-.113-.094t-.13-.069t-.141-.043T15 11.25t-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146t.014.146q.015.073.043.141t.069.13t.094.113l1.233 1.234q-2.953.204-2.953 3.361v1.75q0 3.375 3.375 3.375h2.75q3.375 0 3.375-3.375v-1.75q0-3.157-2.953-3.361l1.233-1.234q.106-.105.163-.243T20.75 12t-.057-.287t-.163-.243q-.052-.053-.113-.094t-.13-.069t-.141-.043T20 11.25t-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094l-1.22 1.219V8q0-2.75-2.75-2.75h-4.25v-.125q0-3.375-3.375-3.375");
}

</style>
