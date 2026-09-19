<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mnumfnbbo"/><path class="eol4_l0on"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-signal-cellular-3-bar" /></template>
<style>
.eol4_l0on {
  fill: currentColor;
  d: path("M17 7L2 22h15z");
}

.mnumfnbbo {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-3, 0.3);
  d: path("M2 22h20V2z");
}

</style>
