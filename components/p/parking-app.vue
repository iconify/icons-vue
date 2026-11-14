<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u5h3sc6vi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:parking-app" /></template>
<style>
.u5h3sc6vi {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M10.375 1.75h3.25q2.123 0 3.624 1.501t1.501 3.624v10.25q0 2.123-1.501 3.624t-3.624 1.501h-3.25q-2.123 0-3.624-1.501T5.25 17.125V6.875q0-2.123 1.501-3.624t3.624-1.501M9.25 12.5V17q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146v-3.75h1.75q3.5 0 3.5-3.5t-3.5-3.5H10q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141T9.25 7zm1.5-.75h1.75q2 0 2-2t-2-2h-1.75z");
}

</style>
