<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="irxjehbbg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:remove-outline-rounded" /></template>
<style>
.irxjehbbg {
  fill: currentColor;
  d: path("M6.5 12.5q-.213 0-.356-.144T6 11.999t.144-.356t.356-.143h11q.213 0 .356.144t.144.357t-.144.356t-.356.143z");
}

</style>
