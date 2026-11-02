<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nwdbjr99o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:pen-tool-fill-sharp" /></template>
<style>
.nwdbjr99o {
  fill: currentColor;
  d: path("M14.287 6.042a1 1 0 0 1 .607.511l2.928 5.855l2.885 2.885a1 1 0 0 1 0 1.414l-4 4a1 1 0 0 1-1.414 0l-2.885-2.885l-5.855-2.928a1 1 0 0 1-.511-.607l-3-10a1 1 0 0 1 1.245-1.245ZM6.121 7.535l1.172 1.172a.999.999 0 1 0 1.414-1.414L7.535 6.121a.999.999 0 1 0-1.414 1.414M11.01 10H11a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2M17 14.414L14.414 17L16 18.586L18.586 16Z");
}

</style>
