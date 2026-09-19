<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mblvupw0f"/><path class="z8f16ob3z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-domain-verification" /></template>
<style>
.mblvupw0f {
  fill: currentColor;
  d: path("M10.23 15.83c.39.39 1.02.39 1.41 0l4.24-4.24c.39-.39.39-1.02 0-1.42a.996.996 0 0 0-1.41 0l-3.54 3.53l-1.41-1.41c-.39-.39-1.02-.39-1.42 0s-.39 1.02 0 1.41z");
}

.z8f16ob3z {
  fill: currentColor;
  d: path("M19 4H5a2 2 0 0 0-2 2v12a2 2 0 0 0 2 2h14c1.1 0 2-.9 2-2V6a2 2 0 0 0-2-2m0 13c0 .55-.45 1-1 1H6c-.55 0-1-.45-1-1V8h14z");
}

</style>
