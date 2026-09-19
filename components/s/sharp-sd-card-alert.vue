<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="piufsb68s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-sd-card-alert" /></template>
<style>
.piufsb68s {
  fill: currentColor;
  d: path("M20 2H10L4 8v14h16zm-7 15h-2v-2h2zm0-4h-2V8h2z");
}

</style>
