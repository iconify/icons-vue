<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="urd-khb9h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:terminal-sharp" /></template>
<style>
.urd-khb9h {
  fill: currentColor;
  d: path("M3 19V5h18v14zm1-1h16V8H4zm3.5-1.711l-.689-.689L9.388 13l-2.6-2.6l.713-.688L10.789 13zm5 .211v-1h5v1z");
}

</style>
