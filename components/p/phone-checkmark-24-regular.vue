<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oy2_olpvq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:phone-checkmark-24-regular" /></template>
<style>
.oy2_olpvq {
  fill: currentColor;
  d: path("M12.348 2a6.5 6.5 0 0 0-1.324 1.5H8.25a.75.75 0 0 0-.75.75v15.5c0 .414.336.75.75.75h7.5a.75.75 0 0 0 .75-.75V13.5a6.5 6.5 0 0 0 1.5-.177v6.427A2.25 2.25 0 0 1 15.75 22h-7.5A2.25 2.25 0 0 1 6 19.75V4.25A2.25 2.25 0 0 1 8.25 2zm.901 15.5a.75.75 0 0 1 .002 1.5l-2.5.004a.75.75 0 0 1-.002-1.5zm3.251-16a5.5 5.5 0 1 1 0 11a5.5 5.5 0 0 1 0-11m3.354 3.146a.5.5 0 0 0-.707 0L15.5 8.293l-1.646-1.647a.5.5 0 1 0-.707.708l2 2a.5.5 0 0 0 .707 0l4-4a.5.5 0 0 0 0-.708");
}

</style>
