<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nr2ay2spy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-keyboard-alt" /></template>
<style>
.nr2ay2spy {
  fill: currentColor;
  d: path("M23 4H1v17h22zM7 12v2H5v-2zm-2-2V8h2v2zm6 2v2H9v-2zm-2-2V8h2v2zm7 6v1H8v-1zm-1-4v2h-2v-2zm-2-2V8h2v2zm4 4v-2h2v2zm2-4h-2V8h2z");
}

</style>
