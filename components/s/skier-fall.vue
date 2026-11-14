<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nbktzbrhv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:skier-fall" /></template>
<style>
.nbktzbrhv {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.934 4.399q-.732-.733-1.768-.733q-1.035 0-1.767.733q-.733.732-.733 1.768q0 1.035.733 1.767L8.464 12l-4.065 4.066q-.733.732-.733 1.768q0 1.035.733 1.767q.732.733 1.768.733q1.035 0 1.767-.733L12 15.536l4.066 4.065q.732.733 1.768.733q1.035 0 1.767-.733q.733-.732.733-1.767q0-1.036-.733-1.768L15.536 12l4.065-4.066q.733-.732.733-1.768q0-1.035-.733-1.767q-.732-.733-1.767-.733q-1.036 0-1.768.733L12 8.464z");
}

</style>
