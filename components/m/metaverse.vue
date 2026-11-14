<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oknd2vb5m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:metaverse" /></template>
<style>
.oknd2vb5m {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.5 5.75h11q3.122 0 3.245 3h.755q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146v5q0 .074-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-.755q-.123 3-3.245 3h-2q-.128 0-.248-.042q-.121-.043-.221-.122l-2.294-1.836h-1.474l-2.294 1.836q-.1.079-.221.122q-.12.042-.248.042h-2q-3.122 0-3.245-3H2.5q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141q-.014-.072-.014-.146v-5q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014h.755q.123-3 3.245-3m2.25 3Q6 8.75 6 11.5t2.75 2.75t2.75-2.75t-2.75-2.75m3.75 2.75q0 2.75 2.75 2.75T18 11.5t-2.75-2.75t-2.75 2.75");
}

</style>
