<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tr3rb1bvm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:phone-off-fill" /></template>
<style>
.tr3rb1bvm {
  fill: currentColor;
  d: path("M10.5 12.086L21.293 1.293a.999.999 0 1 1 1.414 1.414L11.914 13.5l.793.793a.414.414 0 0 0 .586 0l1-1c.737-.737 1.922-1.608 3.023-1.242l3 1c.586.196 1.031.66 1.302 1.203c.271.541.382 1.145.382 1.746v3c0 .797-.314 1.558-.879 2.121A3 3 0 0 1 19 22a16.8 16.8 0 0 1-6.617-1.336a16.8 16.8 0 0 1-4.677-2.956l-4.999 4.999a.999.999 0 1 1-1.414-1.414Zm1.447-4.275l-6.904 6.903a17 17 0 0 1-1.707-3.097A16.8 16.8 0 0 1 2 5c0-.797.314-1.558.879-2.121A3 3 0 0 1 5 2h3c.601 0 1.205.111 1.746.382c.543.271 1.007.716 1.203 1.302l1 3c.122.366.104.759-.002 1.127");
}

</style>
