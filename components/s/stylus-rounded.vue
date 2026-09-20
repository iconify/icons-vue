<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q-01mnbyz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:stylus-rounded" /></template>
<style>
.q-01mnbyz {
  fill: currentColor;
  d: path("M4.2 20.975q-.525.125-.913-.262t-.262-.913l.875-4.25l4.55 4.55zm5.875-2.1l-4.95-4.95L15.45 3.6q.575-.575 1.425-.575T18.3 3.6l2.1 2.1q.575.575.575 1.425T20.4 8.55z");
}

</style>
