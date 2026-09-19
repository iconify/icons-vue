<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="rpxe9ibnu"/><path class="ca0gilwts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-priority-high" /></template>
<style>
.ca0gilwts {
  fill: currentColor;
  d: path("M12 3c-1.1 0-2 .9-2 2v8c0 1.1.9 2 2 2s2-.9 2-2V5c0-1.1-.9-2-2-2");
}

.rpxe9ibnu {
  cx: 12px;
  cy: 19px;
  r: 2px;
  fill: currentColor;
}

</style>
