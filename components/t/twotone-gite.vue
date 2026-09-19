<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iwaq0ccvx"/><path class="g585j3bhz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-gite" /></template>
<style>
.g585j3bhz {
  fill: currentColor;
  d: path("M18 6H9V4H7v2H6l-4 4v9h20v-9zM4 12h10v5H4zm16 5h-4v-6.17l2-2l2 2z");
}

.iwaq0ccvx {
  fill: currentColor;
  d: path("M4 12h10v5H4zm16 5h-4v-6.17l2-2l2 2z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
