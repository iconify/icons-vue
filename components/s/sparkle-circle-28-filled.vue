<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="qtx2ulb6o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:sparkle-circle-28-filled" /></template>
<style>
.qtx2ulb6o {
  fill: currentColor;
  d: path("M14 2C7.373 2 2 7.373 2 14s5.373 12 12 12s12-5.373 12-12S20.627 2 14 2m-3.56 5.75c.353-1 1.767-1 2.12 0l.516 1.455c.12.336.384.6.72.72l1.455.515c.999.353.999 1.767 0 2.12l-1.455.515c-.336.119-.6.383-.72.72l-.515 1.456c-.354 1-1.768.999-2.121-.001l-.514-1.455a1.18 1.18 0 0 0-.72-.72L7.75 12.56c-1-.353-1-1.767 0-2.12l1.456-.516c.336-.119.6-.383.72-.72zm7.885 6.833l.401 1.132a.92.92 0 0 0 .56.56l1.131.4c.777.275.777 1.375 0 1.65l-1.131.4a.92.92 0 0 0-.56.56l-.401 1.132c-.275.777-1.375.777-1.65 0l-.4-1.132a.92.92 0 0 0-.56-.56l-1.132-.4c-.777-.275-.777-1.375 0-1.65l1.133-.4a.92.92 0 0 0 .56-.56l.4-1.132c.274-.777 1.374-.777 1.649 0");
}

</style>
