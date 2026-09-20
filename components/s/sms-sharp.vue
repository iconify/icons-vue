<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jbcmb0bkn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:sms-sharp" /></template>
<style>
.jbcmb0bkn {
  fill: currentColor;
  d: path("M3 20.077V3h18v14H6.077zm5.54-9.537q.23-.23.23-.54t-.23-.54T8 9.23t-.54.23t-.23.54t.23.54t.54.23t.54-.23m4 0q.23-.23.23-.54t-.23-.54t-.54-.23t-.54.23t-.23.54t.23.54t.54.23t.54-.23m4 0q.23-.23.23-.54t-.23-.54t-.54-.23t-.54.23t-.23.54t.23.54t.54.23t.54-.23");
}

</style>
