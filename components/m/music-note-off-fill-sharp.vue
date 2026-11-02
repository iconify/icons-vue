<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uoq78rb1e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:music-note-off-fill-sharp" /></template>
<style>
.uoq78rb1e {
  fill: currentColor;
  d: path("m2.707 3.293l18 18a.999.999 0 1 1-1.414 1.414l-6.343-6.343a4.001 4.001 0 1 1-3.314-3.314L1.293 4.707a.999.999 0 1 1 1.414-1.414M11 4a1 1 0 0 1 1.447-.894l6 3a1 1 0 1 1-.894 1.788L13 5.618V8a1 1 0 0 1-2 0Z");
}

</style>
