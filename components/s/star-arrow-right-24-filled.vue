<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="pbg9bj9vi"/><path class="c6x5-eb_x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:star-arrow-right-24-filled" /></template>
<style>
.c6x5-eb_x {
  d: path("M23 17.5a5.5 5.5 0 1 1-11 0a5.5 5.5 0 0 1 11 0zm-8.5-.5a.5.5 0 0 0 0 1h4.793l-1.647 1.646a.5.5 0 0 0 .708.708l2.5-2.5a.5.5 0 0 0 0-.708l-2.5-2.5a.5.5 0 0 0-.708.708L19.293 17H14.5z");
  fill: currentColor;
}

.ft5dv1b6b {
  fill: none;
}

.pbg9bj9vi {
  d: path("M10.79 3.103c.495-1.004 1.926-1.004 2.421 0l2.358 4.777l5.272.766c1.108.161 1.55 1.522.749 2.303l-.906.883a6.5 6.5 0 0 0-9.442 7.43l-3.958 2.08c-.99.521-2.147-.32-1.958-1.423l.9-5.25l-3.815-3.72c-.801-.78-.359-2.142.748-2.303l5.273-.766l2.358-4.777z");
  fill: currentColor;
}

</style>
