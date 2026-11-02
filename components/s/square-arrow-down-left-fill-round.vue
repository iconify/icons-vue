<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iqsvpyspo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-arrow-down-left-fill-round" /></template>
<style>
.iqsvpyspo {
  fill: currentColor;
  d: path("M2 7a5 5 0 0 1 5-5h10a5 5 0 0 1 5 5v10a5 5 0 0 1-1.464 3.536A5 5 0 0 1 17 22H7a5 5 0 0 1-5-5Zm7 9h4a1 1 0 0 0 0-2h-1.586l4.293-4.293a.999.999 0 1 0-1.414-1.414L10 12.586V11a1 1 0 0 0-2 0v4a1 1 0 0 0 1 1");
}

</style>
