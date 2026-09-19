<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j7bjd7iyz"/><path class="fhlpeqbhg"/><path class="tirdnce-u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-doorbell" /></template>
<style>
.fhlpeqbhg {
  fill: currentColor;
  d: path("M12 3L4 9v12h16V9zm6 16H6v-9l6-4.5l6 4.5z");
}

.j7bjd7iyz {
  fill: currentColor;
  d: path("M6 10v9h12v-9l-6-4.5zm6 7.5c-.55 0-1-.45-1-1h2c0 .55-.45 1-1 1m.75-8.25v.25c1.44.34 2.25 1.62 2.25 3.16V15h1v1H8v-1h1v-2.34c0-1.54.82-2.82 2.25-3.16v-.25c0-.41.34-.75.75-.75s.75.34.75.75");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.tirdnce-u {
  fill: currentColor;
  d: path("M11.25 9.25v.25C9.82 9.84 9 11.12 9 12.66V15H8v1h8v-1h-1v-2.34c0-1.54-.81-2.82-2.25-3.16v-.25c0-.41-.34-.75-.75-.75s-.75.34-.75.75M12 17.5c.55 0 1-.45 1-1h-2c0 .55.45 1 1 1");
}

</style>
