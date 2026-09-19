<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e-e5mtbss"/><path class="s3tpthb5w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-fact-check" /></template>
<style>
.e-e5mtbss {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M20 3H4c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h16c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2m0 16H4V5h16z");
}

.s3tpthb5w {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M19.41 10.42L17.99 9l-3.17 3.17l-1.41-1.42L12 12.16L14.82 15zM5 7h5v2H5zm0 4h5v2H5zm0 4h5v2H5z");
}

</style>
