<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ddpg_4byg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:person-voice-32-filled" /></template>
<style>
.ddpg_4byg {
  fill: currentColor;
  d: path("M22.5 18a3.5 3.5 0 0 1 3.5 3.5v.5c0 2.393-1.523 4.417-3.685 5.793C20.141 29.177 17.198 30 14 30s-6.141-.823-8.315-2.207C3.523 26.417 2 24.393 2 22v-.5A3.5 3.5 0 0 1 5.5 18zM14 2a7 7 0 1 1 0 14a7 7 0 0 1 0-14m13.355.092a1 1 0 0 1 1.316.517A15.95 15.95 0 0 1 30 9c0 2.27-.475 4.432-1.33 6.39a1 1 0 0 1-1.833-.798A13.95 13.95 0 0 0 28 9c0-1.99-.416-3.88-1.163-5.592a1 1 0 0 1 .518-1.316m-3.217 2.52a1 1 0 0 1 1.262.637c.389 1.18.6 2.442.6 3.751c0 1.31-.212 2.57-.6 3.75a1 1 0 0 1-1.9-.625c.323-.983.5-2.033.5-3.125a10 10 0 0 0-.5-3.126a1 1 0 0 1 .638-1.263");
}

</style>
