<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="va1dd-bps"/><path class="t9tohgx0q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-dns" /></template>
<style>
.t9tohgx0q {
  fill: currentColor;
  d: path("M20 13H4c-.55 0-1 .45-1 1v6c0 .55.45 1 1 1h16c.55 0 1-.45 1-1v-6c0-.55-.45-1-1-1m-1 6H5v-4h14zm-12-.5c.83 0 1.5-.67 1.5-1.5s-.67-1.5-1.5-1.5s-1.5.67-1.5 1.5s.67 1.5 1.5 1.5M20 3H4c-.55 0-1 .45-1 1v6c0 .55.45 1 1 1h16c.55 0 1-.45 1-1V4c0-.55-.45-1-1-1m-1 6H5V5h14zM7 8.5c.83 0 1.5-.67 1.5-1.5S7.83 5.5 7 5.5S5.5 6.17 5.5 7S6.17 8.5 7 8.5");
}

.va1dd-bps {
  fill: currentColor;
  d: path("M5 9h14V5H5zm2-3.5c.83 0 1.5.67 1.5 1.5S7.83 8.5 7 8.5S5.5 7.83 5.5 7S6.17 5.5 7 5.5M5 19h14v-4H5zm2-3.5c.83 0 1.5.67 1.5 1.5s-.67 1.5-1.5 1.5s-1.5-.67-1.5-1.5s.67-1.5 1.5-1.5");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
