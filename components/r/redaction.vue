<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lwitb5b1p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:redaction" /></template>
<style>
.lwitb5b1p {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M15.125 1.75h-6.25q-2.123 0-3.624 1.501T3.75 6.875v10.25q0 2.123 1.501 3.624t3.624 1.501h6.25q2.123 0 3.624-1.501t1.501-3.624V6.875q0-2.123-1.501-3.624T15.125 1.75m.875 4q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043T16 7.25H8q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T7.25 6.5t.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043T8 5.75zM14.75 9q2 0 2 2t-2 2h-5.5q-2 0-2-2t2-2zm-5.5 5.25h2.5q.828 0 1.414.586t.586 1.414t-.586 1.414t-1.414.586h-2.5q-2 0-2-2t2-2");
}

</style>
