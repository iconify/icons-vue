<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a8z0xkb7g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:media-bluetooth-on" /></template>
<style>
.a8z0xkb7g {
  fill: currentColor;
  d: path("M4.175 19.825Q3 18.65 3 17t1.175-2.825T7 13q.575 0 1.063.138T9 13.55V3h6v4h-4v10q0 1.65-1.175 2.825T7 21t-2.825-1.175M17 21v-4.55l-2.75 2.75l-.85-.85L16.75 15l-3.4-3.35l.85-.85l2.75 2.75V9h.6L21 12.45L18.4 15l2.6 2.55L17.6 21zm1.15-2.3l1.15-1.15l-1.15-1.1zm0-5.15l1.15-1.1l-1.15-1.15z");
}

</style>
