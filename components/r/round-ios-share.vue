<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zrmizccuy"/><path class="yxub4sbfq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-ios-share" /></template>
<style>
.yxub4sbfq {
  fill: currentColor;
  d: path("M12 16c.55 0 1-.45 1-1V5h1.79c.45 0 .67-.54.35-.85l-2.79-2.79c-.2-.2-.51-.2-.71 0L8.85 4.15a.5.5 0 0 0 .36.85H11v10c0 .55.45 1 1 1");
}

.zrmizccuy {
  fill: currentColor;
  d: path("M18 8h-2c-.55 0-1 .45-1 1s.45 1 1 1h2v11H6V10h2c.55 0 1-.45 1-1s-.45-1-1-1H6c-1.1 0-2 .9-2 2v11c0 1.1.9 2 2 2h12c1.1 0 2-.9 2-2V10c0-1.1-.9-2-2-2");
}

</style>
