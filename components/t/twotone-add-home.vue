<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vb_5uw28p"/><path class="jph8w2vmo"/><path class="a4tj93cqy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-add-home" /></template>
<style>
.a4tj93cqy {
  fill: currentColor;
  d: path("M18 13c-2.76 0-5 2.24-5 5s2.24 5 5 5s5-2.24 5-5s-2.24-5-5-5m3 5.5h-2.5V21h-1v-2.5H15v-1h2.5V15h1v2.5H21z");
}

.jph8w2vmo {
  fill: currentColor;
  d: path("M6 19v-9l6-4.5l6 4.5v1c.7 0 1.37.1 2 .29V9l-8-6l-8 6v12h7.68c-.3-.62-.5-1.29-.6-2z");
}

.vb_5uw28p {
  fill: currentColor;
  d: path("M12 5.5L6 10v9h5.08c-.62-4.3 2.72-8 6.92-8v-1z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
