<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v0f_mt_gg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:play-disabled" /></template>
<style>
.v0f_mt_gg {
  fill: currentColor;
  d: path("M15.258 13.177L9 6.919v-.111L17.154 12zm2.415 6.654l-4.98-4.992L9 17.192v-6.046L4.13 6.277l.709-.708l13.553 13.554z");
}

</style>
