<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gtu4cob9w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:play-disabled-outline" /></template>
<style>
.gtu4cob9w {
  fill: currentColor;
  d: path("m15.258 13.177l-.708-.72l.692-.422l-3.257-2.131L9 6.919v-.111L17.154 12zm2.415 6.654l-4.98-4.992L9 17.192v-6.046L4.13 6.277l.709-.708l13.553 13.554zM10 15.35l1.935-1.23L10 12.184zm1.985-5.446");
}

</style>
