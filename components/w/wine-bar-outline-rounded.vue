<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ryzm5zkqi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:wine-bar-outline-rounded" /></template>
<style>
.ryzm5zkqi {
  fill: currentColor;
  d: path("M11 19v-4.1q-2.15-.35-3.575-2T6 9V4q0-.425.288-.712T7 3h10q.425 0 .713.288T18 4v5q0 2.25-1.425 3.9T13 14.9V19h2q.425 0 .713.288T16 20t-.288.713T15 21H9q-.425 0-.712-.288T8 20t.288-.712T9 19zm3.45-6.85q1.05-.85 1.4-2.15h-7.7q.35 1.3 1.4 2.15T12 13t2.45-.85M8 8h8V5H8zm4 5");
}

</style>
