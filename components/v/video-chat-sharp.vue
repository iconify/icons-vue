<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bir74zakd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:video-chat-sharp" /></template>
<style>
.bir74zakd {
  fill: currentColor;
  d: path("M7 14h8v-3l2 2V7l-2 2V6H7zm-5 8V2h20v16H6z");
}

</style>
