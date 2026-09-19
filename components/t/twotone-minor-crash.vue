<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ei1-02ord"/><path class="fj3bhphly"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-minor-crash" /></template>
<style>
.ei1-02ord {
  fill: currentColor;
  d: path("M5 15v5h14v-5zm2.5 4c-.83 0-1.5-.67-1.5-1.5S6.67 16 7.5 16s1.5.67 1.5 1.5S8.33 19 7.5 19m9 0c-.83 0-1.5-.67-1.5-1.5s.67-1.5 1.5-1.5s1.5.67 1.5 1.5s-.67 1.5-1.5 1.5");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.fj3bhphly {
  fill: currentColor;
  d: path("M9.41 5L8 6.41l-3-3L6.41 2zM19 3.41L17.59 2l-3 3L16 6.41zM13 0h-2v5h2zm8 15v8c0 .55-.45 1-1 1h-1c-.55 0-1-.45-1-1v-1H6v1c0 .55-.45 1-1 1H4c-.55 0-1-.45-1-1v-8l2.08-5.99C5.29 8.42 5.84 8 6.5 8h11c.66 0 1.22.42 1.42 1.01zM5.81 13h12.38l-1.04-3H6.85zM19 15H5v5h14zM7.5 19c.83 0 1.5-.67 1.5-1.5S8.33 16 7.5 16S6 16.67 6 17.5S6.67 19 7.5 19m9 0c.83 0 1.5-.67 1.5-1.5s-.67-1.5-1.5-1.5s-1.5.67-1.5 1.5s.67 1.5 1.5 1.5");
}

</style>
