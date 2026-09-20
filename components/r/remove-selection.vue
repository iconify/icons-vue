<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sozr0hbzb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:remove-selection" /></template>
<style>
.sozr0hbzb {
  fill: currentColor;
  d: path("m12.5 21l-1.4-1.4l3.55-3.55l-3.55-3.55l1.4-1.4l3.55 3.55l3.55-3.55l1.4 1.4l-3.55 3.55L21 19.6L19.6 21l-3.55-3.55zM7 21v-2h2v2zM5 5H3q0-.825.588-1.412T5 3zm2 0V3h2v2zm4 0V3h2v2zm4 0V3h2v2zm4 0V3q.825 0 1.413.588T21 5zM5 19v2q-.825 0-1.412-.587T3 19zm-2-2v-2h2v2zm0-4v-2h2v2zm0-4V7h2v2zm16 0V7h2v2z");
}

</style>
