<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j9g6h7dml"/><path class="b_08bu7ae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-monitor" /></template>
<style>
.b_08bu7ae {
  fill: currentColor;
  d: path("M4 5h16v11H4z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.j9g6h7dml {
  fill: currentColor;
  d: path("M20 3H4c-1.1 0-2 .9-2 2v11c0 1.1.9 2 2 2h3l-1 1v2h12v-2l-1-1h3c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2m0 13H4V5h16z");
}

</style>
