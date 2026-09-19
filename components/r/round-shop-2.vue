<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xsic6nmpw"/><path class="l50s1ebuu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-shop-2" /></template>
<style>
.l50s1ebuu {
  fill: currentColor;
  d: path("M18 5V3c0-1.11-.89-2-2-2h-4c-1.11 0-2 .89-2 2v2H5v11c0 1.11.89 2 2 2h14c1.11 0 2-.89 2-2V5zm-6-2h4v2h-4zm0 11.09V8.91c0-.39.44-.63.77-.42l4.07 2.59c.31.2.31.65 0 .84l-4.07 2.59a.503.503 0 0 1-.77-.42");
}

.xsic6nmpw {
  fill: currentColor;
  d: path("M2 9c-.55 0-1 .45-1 1v10c0 1.1.9 2 2 2h15c.55 0 1-.45 1-1s-.45-1-1-1H3V10c0-.55-.45-1-1-1");
}

</style>
