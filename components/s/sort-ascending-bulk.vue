<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ye8mq4bhh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:sort-ascending-bulk" /></template>
<style>
.ye8mq4bhh {
  fill: currentColor;
  d: path("m17.293 13.707l-3-3a.999.999 0 1 1 1.414-1.414L17 10.586V5a1 1 0 0 1 2 0v5.586l1.293-1.293a.999.999 0 1 1 1.414 1.414l-3 3a1 1 0 0 1-1.414 0M4 8h6a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2m0 5h9a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2m12 5a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2Z");
}

</style>
