<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="uyn_52biu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:window-new-rotate-180-20-regular" /></template>
<style>
.uyn_52biu {
  fill: currentColor;
  d: path("M6 17a3 3 0 0 1-3-3V8a3 3 0 0 1 2.13-2.871A3 3 0 0 1 8 3h4.5A4.5 4.5 0 0 1 17 7.5V12a3 3 0 0 1-2.129 2.871A3 3 0 0 1 12 17zm9-3.27c.598-.346 1-.99 1-1.73V7.5A3.5 3.5 0 0 0 12.5 4H8c-.74 0-1.383.403-1.729 1H12a3 3 0 0 1 3 3zM12 16a2 2 0 0 0 2-2V8a2 2 0 0 0-2-2H6a2 2 0 0 0-2 2v6a2 2 0 0 0 2 2zm-5.5-2a.5.5 0 0 1-.5-.5v-4a.5.5 0 0 1 1 0v2.793l4.147-4.147a.5.5 0 1 1 .707.708L7.707 13H10.5a.5.5 0 0 1 0 1z");
}

</style>
