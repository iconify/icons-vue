<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="ft5dv1b6b"><path class="b8ti21bus"/><path class="nvgh4sevl"/><path class="q993dybyj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:set-top-stack-20-filled" /></template>
<style>
.b8ti21bus {
  d: path("M4 3a2 2 0 0 0-2 2v6a2 2 0 0 0 2 2h8a2 2 0 0 0 2-2V5a2 2 0 0 0-2-2H4zm4.332 2.076l.909 1.738l1.803.216a.375.375 0 0 1 .19.665L9.919 8.744l.446 1.921a.375.375 0 0 1-.557.407L8 9.992l-1.808 1.08a.375.375 0 0 1-.557-.407l.446-1.921l-1.315-1.049a.375.375 0 0 1 .19-.665l1.803-.216l.909-1.738a.375.375 0 0 1 .664 0z");
  fill: currentColor;
}

.ft5dv1b6b {
  fill: none;
}

.nvgh4sevl {
  d: path("M4.268 14A2 2 0 0 0 6 15h6a4 4 0 0 0 4-4V7a2 2 0 0 0-1-1.732V11a3 3 0 0 1-3 3H4.268z");
  fill: currentColor;
}

.q993dybyj {
  d: path("M6.268 16A2 2 0 0 0 8 17h4a6 6 0 0 0 6-6V9a2 2 0 0 0-1-1.732V11a5 5 0 0 1-5 5H6.268z");
  fill: currentColor;
}

</style>
