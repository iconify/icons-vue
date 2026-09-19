<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kz9n24bpt"/><path class="mxrwm4bmj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-desk" /></template>
<style>
.kz9n24bpt {
  fill: currentColor;
  d: path("M16 8h4v2h-4zm0 4h4v2h-4z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.mxrwm4bmj {
  fill: currentColor;
  d: path("M2 6v12h2V8h10v10h2v-2h4v2h2V6zm18 8h-4v-2h4zm0-4h-4V8h4z");
}

</style>
