<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g48junbwk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:volume-fill-sharp" /></template>
<style>
.g48junbwk {
  fill: currentColor;
  d: path("M12 20a1.002 1.002 0 0 1-1.707.707L6.586 17H3a1 1 0 0 1-1-1V8a1 1 0 0 1 1-1h3.586l3.707-3.707A1 1 0 0 1 12 4Z");
}

</style>
