<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yfzajhbku"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:signpost" /></template>
<style>
.yfzajhbku {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12.75 4.25V2.5q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043Q12.074 1.75 12 1.75t-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146v1.75h-4.5q-2.5 0-2.5 2.5v1.5q0 2.5 2.5 2.5h4.5v1H7.225q-1.036 0-1.769.733l-.749.75Q2.941 15 4.706 16.767l.751.75q.732.733 1.768.733h4.025v3.25q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146v-3.25h4.5q2.5 0 2.5-2.5v-1.5q0-2.5-2.5-2.5h-4.5v-1h4.025q1.036 0 1.768-.733l.751-.75q1.765-1.767-.001-3.534l-.749-.75q-.733-.733-1.769-.733z");
}

</style>
