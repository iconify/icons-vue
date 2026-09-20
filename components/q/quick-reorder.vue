<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jip00ptnt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:quick-reorder" /></template>
<style>
.jip00ptnt {
  fill: currentColor;
  d: path("M2.327 19v-1h4.346v-2.5H3.327v-1h3.346V12H4.377v-1h2.296V8.089L4.916 4.235l.915-.427L7.758 8h11.83l-1.872-3.958l.915-.427L20.673 8v11zm9.346-6.5h4q.213 0 .356-.144t.144-.357t-.144-.356t-.356-.143h-4q-.212 0-.356.144t-.144.357t.144.356t.356.143");
}

</style>
