<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f27gp2bkp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:tablet-mac-outline" /></template>
<style>
.f27gp2bkp {
  fill: currentColor;
  d: path("M12.713 20.213Q13 19.925 13 19.5t-.288-.712T12 18.5t-.712.288T11 19.5t.288.713t.712.287t.713-.288M5 23q-.825 0-1.412-.587T3 21V3q0-.825.588-1.412T5 1h14q.825 0 1.413.588T21 3v18q0 .825-.587 1.413T19 23zm0-5v3h14v-3zm0-2h14V6H5zM5 4h14V3H5zm0 0V3zm0 14v3z");
}

</style>
