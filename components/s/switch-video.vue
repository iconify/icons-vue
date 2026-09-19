<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u6dzh-1fc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:switch-video" /></template>
<style>
.u6dzh-1fc {
  fill: currentColor;
  d: path("M18 9.5V6c0-.55-.45-1-1-1H3c-.55 0-1 .45-1 1v12c0 .55.45 1 1 1h14c.55 0 1-.45 1-1v-3.5l4 4v-13zm-5 6V13H7v2.5L3.5 12L7 8.5V11h6V8.5l3.5 3.5z");
}

</style>
