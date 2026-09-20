<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mxdib5dgx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:voice-chat-off-sharp" /></template>
<style>
.mxdib5dgx {
  fill: currentColor;
  d: path("M16.808 10.5h.884v-1h-.884zm-2.5-3v4.035L12.442 9.65V5.5h-.884v3.246L5.85 3H21v14h-1.265l-4.543-4.58V7.5zm5.961 14.185L15.573 17H6.077L3 20.077V4.416L1.008 2.423l.707-.707l19.262 19.261zm-7.953-7.954l-.758-.758V14.5h.758zM8.808 12.5h.884v-1.392l-.884-.885zm-2.5-2h.884v-.7l-.3-.3h-.584z");
}

</style>
