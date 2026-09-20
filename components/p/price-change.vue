<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xtf5hmbky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:price-change" /></template>
<style>
.xtf5hmbky {
  fill: currentColor;
  d: path("M2 20V4h20v16zm6-3h2v-1h1q.425 0 .713-.288T12 15v-3q0-.425-.288-.712T11 11H8v-1h4V8h-2V7H8v1H7q-.425 0-.712.288T6 9v3q0 .425.288.713T7 13h3v1H6v2h2zm8-.75l2-2h-4zM14 10h4l-2-2z");
}

</style>
