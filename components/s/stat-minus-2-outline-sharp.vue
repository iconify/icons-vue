<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mthupbbfs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:stat-minus-2-outline-sharp" /></template>
<style>
.mthupbbfs {
  fill: currentColor;
  d: path("m12 19l-6-6l1.4-1.4l4.6 4.575l4.6-4.575L18 13zm0-6L6 7l1.4-1.4l4.6 4.575L16.6 5.6L18 7z");
}

</style>
