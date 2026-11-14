<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x44vnkb6q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:robotics" /></template>
<style>
.x44vnkb6q {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12.75 3.5v3.25h2q2.485 0 4.243 1.757q1.757 1.758 1.757 4.243v2.5q0 2.485-1.757 4.243q-1.758 1.757-4.243 1.757h-5.5q-2.485 0-4.243-1.757Q3.25 17.735 3.25 15.25v-2.5q0-2.485 1.757-4.243Q6.765 6.75 9.25 6.75h2V3.5q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043q.072-.014.146-.014t.146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146M9 11.25q-2.25 0-2.25 2.25T9 15.75t2.25-2.25T9 11.25m3.75 2.25q0 2.25 2.25 2.25t2.25-2.25T15 11.25t-2.25 2.25");
}

</style>
