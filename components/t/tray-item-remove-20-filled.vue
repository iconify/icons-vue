<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="h97q0-9na"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:tray-item-remove-20-filled" /></template>
<style>
.h97q0-9na {
  fill: currentColor;
  d: path("M12 2a1 1 0 0 0-1 1v2a1 1 0 0 0 1 1h3a1 1 0 0 0 1-1V3a1 1 0 0 0-1-1zm1.854 5.146a.5.5 0 0 0-.708 0l-2 2a.5.5 0 0 0 .708.708L13 8.707V14.5a.5.5 0 0 0 1 0V8.707l1.146 1.147a.5.5 0 0 0 .708-.708zM5 11a1 1 0 0 0-1 1v2a1 1 0 0 0 1 1h3a1 1 0 0 0 1-1v-2a1 1 0 0 0-1-1zm-2 2.5a.5.5 0 0 0-1 0V15a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2v-1.5a.5.5 0 0 0-1 0V15a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1z");
}

</style>
