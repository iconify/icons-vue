<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jmuqwbb6y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:phone-iphone-outline" /></template>
<style>
.jmuqwbb6y {
  fill: currentColor;
  d: path("M7 23q-.825 0-1.412-.587T5 21V3q0-.825.588-1.412T7 1h10q.825 0 1.413.588T19 3v18q0 .825-.587 1.413T17 23zm0-5v3h10v-3zm5 2.5q.425 0 .713-.288T13 19.5t-.288-.712T12 18.5t-.712.288T11 19.5t.288.713t.712.287M7 16h10V6H7zM7 4h10V3H7zm0 14v3zM7 4V3z");
}

</style>
