<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q3hl67rpo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:nfc-off" /></template>
<style>
.q3hl67rpo {
  fill: currentColor;
  d: path("M5.616 20q-.691 0-1.153-.462T4 18.384V5.422L1.887 3.308l.713-.714l19.223 19.223l-.713.714L18.579 20zM8 9.421V16h6.579l-1-1H9v-4.579zM15 9v3.208l-2.5-2.5V9zm5-3.384v11.592l-4-4V8h-3.5q-.362 0-.621.196q-.26.196-.35.54L6.792 4h11.593q.69 0 1.152.463T20 5.616");
}

</style>
