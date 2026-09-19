<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mht-iupvy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-tv-off" /></template>
<style>
.mht-iupvy {
  fill: currentColor;
  d: path("M21 8v9.88l1.85 1.85c.1-.22.15-.47.15-.73V7a2 2 0 0 0-2-2h-7.59l2.94-2.94c.2-.2.2-.51 0-.71s-.51-.2-.71 0L12 4.99L8.36 1.35c-.2-.2-.51-.2-.71 0s-.2.51 0 .71L10.59 5H8.12l2 2H20c.55 0 1 .45 1 1M3.12 2.83a.996.996 0 1 0-1.41 1.41l.82.82C1.65 5.28 1 6.06 1 7v12c0 1.1.9 2 2 2h15.46l1.29 1.29c.39.39 1.02.39 1.41 0c.36-.36.37-.92.07-1.31h.03zM3 18V8c0-.55.45-1 1-1h.46l12 12H4c-.55 0-1-.45-1-1");
}

</style>
