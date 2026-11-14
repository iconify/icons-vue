<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t4lmcjb_w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:plan-30-60-90" /></template>
<style>
.t4lmcjb_w {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M20 8.25h-1V6.674q.337.076.75.076h.742q.769 0 1.154-.665q.386-.664.005-1.333l-.075-.13q-.212-.372 0-.743l.075-.132q.381-.668-.005-1.332q-.385-.665-1.154-.665h-.742q-.599 0-1.038.159q-.099-.077-.218-.118q-.118-.041-.244-.041q-.074 0-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146v5.75h-1q-2.25 0-2.25 2.25v1q0 .75-.75.75h-3.25Q8 12.25 8 14.5v1q0 .75-.75.75H4q-2.25 0-2.25 2.25v1q0 2.25 2.25 2.25h16q2.25 0 2.25-2.25v-9q0-2.25-2.25-2.25");
}

</style>
