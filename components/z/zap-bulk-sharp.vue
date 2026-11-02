<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="taaxwiuza"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:zap-bulk-sharp" /></template>
<style>
.taaxwiuza {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M13.293 2.293A1 1 0 0 1 15 3v7h5a1.002 1.002 0 0 1 .707 1.707l-10 10A1 1 0 0 1 9 21v-7H4a1.002 1.002 0 0 1-.707-1.707Z");
}

</style>
