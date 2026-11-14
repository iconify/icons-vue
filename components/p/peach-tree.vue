<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j8_ki0ubq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:peach-tree" /></template>
<style>
.j8_ki0ubq {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.742 13.452q.689 3.443 4.183 3.794q.037.004.075.004h3.25v4.25q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146v-4.25H16q.038 0 .075-.004q3.494-.351 4.183-3.794q.645-3.224-2.022-4.891q-.143-2.307-1.817-3.98Q14.589 2.75 12 2.75T7.581 4.581q-1.674 1.673-1.817 3.98q-2.667 1.667-2.022 4.891M12.25 8.5q0-2.25 2.25-2.25t2.25 2.25t-2.25 2.25t-2.25-2.25m-2.75.75q2.25 0 2.25 2.25T9.5 13.75T7.25 11.5T9.5 9.25");
}

</style>
