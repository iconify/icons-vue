<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hog-73bvc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:sprint-assigned" /></template>
<style>
.hog-73bvc {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.975 5.045q.803-.992 1.94-.414t.81 1.812l-.413 1.549q-.127.476.173.867t.793.391h.472q1.334.001 1.969 1.173t-.093 2.29l-3.613 5.541q-.696 1.063-1.864.563t-.879-1.739l.494-2.099q.111-.471-.19-.85q-.3-.379-.784-.379H5.75q-1.452.001-2.077-1.31t.289-2.438zM15.5 15.25q0-2.5 2.5-2.5q1.036 0 1.768.732t.732 1.768t-.732 1.768T18 17.75q-2.5 0-2.5-2.5m1.5 0q0 1 1 1q.414 0 .707-.293T19 15.25t-.293-.707T18 14.25q-1 0-1 1M18 18q-4.25 0-4.25 3.25q0 1.25 1.25 1.25h6q1.25 0 1.25-1.25Q22.25 18 18 18m2.735 3h-5.47q.189-1.5 2.735-1.5t2.735 1.5");
}

</style>
