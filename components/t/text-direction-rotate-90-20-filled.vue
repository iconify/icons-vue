<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="ft5dv1b6b"><path class="zkr5akqpu"/><path class="o9iwmhb5z"/><path class="b2rewi6ww"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-direction-rotate-90-20-filled" /></template>
<style>
.b2rewi6ww {
  d: path("M13 10.75a.75.75 0 0 1 1.5 0v3.69l.72-.72a.75.75 0 1 1 1.06 1.06l-2 2a.748.748 0 0 1-1.06 0l-2-2a.75.75 0 1 1 1.06-1.06l.72.72v-3.69z");
  fill: currentColor;
}

.ft5dv1b6b {
  fill: none;
}

.o9iwmhb5z {
  d: path("M5 3.75a.75.75 0 0 1 1.5 0v10.69l.72-.72a.75.75 0 0 1 1.06 1.06l-2 2a.75.75 0 0 1-1.06 0l-2-2a.75.75 0 1 1 1.06-1.06l.72.72V3.75z");
  fill: currentColor;
}

.zkr5akqpu {
  d: path("M17 6.5a.75.75 0 0 0-.471-.696l-7.5-3a.75.75 0 0 0-.557 1.393l2.028.811v2.984l-2.028.812a.75.75 0 0 0 .557 1.393l7.5-3A.75.75 0 0 0 17 6.5zm-2.77 0L12 7.392V5.608l2.23.892z");
  fill: currentColor;
}

</style>
