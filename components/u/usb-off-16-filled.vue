<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="g5c69jb5d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:usb-off-16-filled" /></template>
<style>
.g5c69jb5d {
  fill: currentColor;
  d: path("M1.147 1.146a.5.5 0 0 1 .707 0l13 13a.5.5 0 0 1-.707.707L9.224 9.931l-.216.188a.75.75 0 0 0-.259.566v1.517a1.5 1.5 0 1 1-1.621.077a.8.8 0 0 0-.138-.16L4.276 9.766a2.25 2.25 0 0 1-.776-1.7v-.818A1.247 1.247 0 0 1 4.25 5l.046.002l-3.15-3.15a.5.5 0 0 1 0-.707M5.5 6.251c0 .408-.197.769-.5.997v.818c0 .217.095.425.259.567l1.991 1.724v-2.4L5.497 6.204zm7-3.25a.5.5 0 0 1 .5.5V5a.5.5 0 0 1-.5.5v.565a2.26 2.26 0 0 1-.777 1.7l-.984.852l-1.063-1.063l1.064-.922a.75.75 0 0 0 .26-.567V5.5a.5.5 0 0 1-.5-.5V3.5A.5.5 0 0 1 11 3zM7.585.722a.5.5 0 0 1 .831 0l1 1.498A.5.5 0 0 1 9 2.997h-.25v3.632l-1.5-1.5V2.997h-.249a.5.5 0 0 1-.416-.777z");
}

</style>
