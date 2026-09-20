<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s93pp7beu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:mobile-vibrate-outline" /></template>
<style>
.s93pp7beu {
  fill: currentColor;
  d: path("M8 21q-.825 0-1.412-.587T6 19V5q0-.825.588-1.412T8 3h8q.825 0 1.413.588T18 5v14q0 .825-.587 1.413T16 21zm8-2V5H8v14zM12.713 7.713Q13 7.425 13 7t-.288-.712T12 6t-.712.288T11 7t.288.713T12 8t.713-.288M0 15V9h2v6zm3 2V7h2v10zm19-2V9h2v6zm-3 2V7h2v10zM8 19V5z");
}

</style>
