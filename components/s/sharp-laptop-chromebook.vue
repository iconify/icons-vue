<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rwzgto0ix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-laptop-chromebook" /></template>
<style>
.rwzgto0ix {
  fill: currentColor;
  d: path("M22 18V3H2v15H0v2h24v-2zm-8 0h-4v-1h4zm6-3H4V5h16z");
}

</style>
