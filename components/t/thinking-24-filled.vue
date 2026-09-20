<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g2ianobii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:thinking-24-filled" /></template>
<style>
.g2ianobii {
  fill: currentColor;
  d: path("M4 18a2 2 0 1 1 0 4a2 2 0 0 1 0-4m5.5-3a2.5 2.5 0 1 1 0 5a2.5 2.5 0 0 1 0-5M12 2a5.414 5.414 0 0 1 5.33 4.47h.082a3.765 3.765 0 1 1 0 7.53H6.588a3.765 3.765 0 1 1 0-7.53h.082A5.414 5.414 0 0 1 12 2");
}

</style>
