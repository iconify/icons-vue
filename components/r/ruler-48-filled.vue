<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mguktebof"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:ruler-48-filled" /></template>
<style>
.mguktebof {
  fill: currentColor;
  d: path("M14.022 7.815A4.25 4.25 0 0 1 18.25 4h11.5A4.25 4.25 0 0 1 34 8.25v31.5A4.25 4.25 0 0 1 29.75 44h-11.5A4.25 4.25 0 0 1 14 39.75V8.25q0-.22.022-.435M16.5 10.25v2.5h4.25a1.25 1.25 0 1 0 0-2.5zm0 6.25V19h8.25a1.25 1.25 0 1 0 0-2.5zm0 6.25v2.5h4.25a1.25 1.25 0 1 0 0-2.5zm0 6.25v2.5h8.25a1.25 1.25 0 1 0 0-2.5zm0 6.25v2.5h4.25a1.25 1.25 0 1 0 0-2.5z");
}

</style>
