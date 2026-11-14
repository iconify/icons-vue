<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mkjr1dbma"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:residents-only-sign" /></template>
<style>
.mkjr1dbma {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.375 1.75h9.25q2.123 0 3.624 1.501t1.501 3.624v4.75q0 2.123-1.501 3.624t-3.624 1.501H12.75v4.75q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146v-4.75H7.375q-2.123 0-3.624-1.501T2.25 11.625v-4.75q0-2.123 1.501-3.624T7.375 1.75M6.25 11.5q0 2.25 2.25 2.25h7q2.25 0 2.25-2.25V9.314q0-1.222-1.024-1.887l-3.5-2.275q-1.226-.796-2.452 0l-3.5 2.275Q6.25 8.092 6.25 9.314z");
}

</style>
