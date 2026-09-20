<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n9pkm-9bs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:settings-system-daydream-sharp" /></template>
<style>
.n9pkm-9bs {
  fill: currentColor;
  d: path("M9.154 14.904h6.5q.627 0 1.063-.437t.437-1.063t-.437-1.063t-1.063-.437h-.512q-.046-1.217-.814-2.109t-1.947-.891q-.973 0-1.748.544t-1.014 1.456h-.528q-.83 0-1.383.582q-.554.583-.554 1.418q0 .846.577 1.423t1.423.577M3 19V5h18v14z");
}

</style>
