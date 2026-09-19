<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xgqwtx5yq"/><path class="rlh10ob3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-plumbing" /></template>
<style>
.rlh10ob3m {
  fill: currentColor;
  d: path("m14.33 8.46l-.71.71l-3.18-3.18a1.49 1.49 0 0 0-2.12 0a1.49 1.49 0 0 0 0 2.12l3.18 3.18l-7 7c-.7.7-.88 1.84-.29 2.65a2.005 2.005 0 0 0 3.05.26l9.19-9.2a.996.996 0 1 0 1.41-1.41l-2.12-2.12a.987.987 0 0 0-1.41-.01");
}

.xgqwtx5yq {
  fill: currentColor;
  d: path("m19.28 4.93l-2.12-2.12c-.78-.78-2.05-.78-2.83 0L11.5 5.64l2.12 2.12l2.12-2.12l3.54 3.54a3.01 3.01 0 0 0 0-4.25M5.49 13.77c.59.59 1.54.59 2.12 0l2.47-2.47l-2.12-2.13l-2.47 2.47c-.59.59-.59 1.54 0 2.13");
}

</style>
