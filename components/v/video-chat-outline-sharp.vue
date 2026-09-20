<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="on92o0npz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:video-chat-outline-sharp" /></template>
<style>
.on92o0npz {
  fill: currentColor;
  d: path("M7 14h8v-3l2 2V7l-2 2V6H7zm-5 8V2h20v16H6zm3.15-6H20V4H4v13.125zM4 16V4z");
}

</style>
