<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wkly5ubxe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:real-estate-agent" /></template>
<style>
.wkly5ubxe {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.641 4.141Q7.25 5.532 7.25 7.5t1.391 3.359T12 12.25t3.359-1.391T16.75 7.5t-1.391-3.359T12 2.75T8.641 4.141M12 15.25q1.1 0 2.063.189l1.306-1.219q-1.528-.47-3.369-.47q-3.71 0-6.15 1.909q-2.6 2.035-2.6 5.341q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141T4.75 21q0-2.575 2.025-4.159Q8.807 15.25 12 15.25m2.215 1.757v-.001l2.25-2.099q1.535-1.431 3.07-.001l2.25 2.101q.715.667.715 1.645v1.598q0 2.25-2.25 2.25h-4.5q-2.25 0-2.25-2.25v-1.598q0-.978.715-1.645m1.024 1.097q-.239.222-.239.548v1.598q0 .75.75.75h4.5q.75 0 .75-.75v-1.598q0-.326-.239-.549l-2.25-2.099q-.511-.477-1.022-.001zm2.597-.715q.982 1.014 1.282 2.361h.632v-.881L18 17.236z");
}

</style>
