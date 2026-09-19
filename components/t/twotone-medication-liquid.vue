<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tf2p33bvy"/><path class="hvb0wkb-d"/><path class="oqf93jb-q"/><path class="svj3245ie"/><path class="sk-qk1h3h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-medication-liquid" /></template>
<style>
.hvb0wkb-d {
  fill: currentColor;
  d: path("M7.5 17.5h3V15H13v-3h-2.5V9.5h-3V12H5v3h2.5z");
}

.oqf93jb-q {
  fill: currentColor;
  d: path("M20 12c.552 0 1-.895 1-2s-.448-2-1-2s-1 .895-1 2s.448 2 1 2");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.sk-qk1h3h {
  fill: currentColor;
  d: path("M4 19h10V8H4zm1-7h2.5V9.5h3V12H13v3h-2.5v2.5h-3V15H5z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.svj3245ie {
  fill: currentColor;
  d: path("M20 6c-1.68 0-3 1.76-3 4c0 1.77.83 3.22 2 3.76V20c0 .55.45 1 1 1s1-.45 1-1v-6.24c1.17-.54 2-1.99 2-3.76c0-2.24-1.32-4-3-4m0 6c-.41 0-1-.78-1-2s.59-2 1-2s1 .78 1 2s-.59 2-1 2");
}

.tf2p33bvy {
  fill: currentColor;
  d: path("M3 3h12v2H3zm11 3H4c-1.1 0-2 .9-2 2v11c0 1.1.9 2 2 2h10c1.1 0 2-.9 2-2V8c0-1.1-.9-2-2-2m0 13H4V8h10z");
}

</style>
