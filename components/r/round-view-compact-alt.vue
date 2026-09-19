<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cbjdrccrs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-view-compact-alt" /></template>
<style>
.cbjdrccrs {
  fill: currentColor;
  d: path("M20 4H4c-1.1 0-2 .9-2 2v12c0 1.1.9 2 2 2h16c1.1 0 2-.9 2-2V6c0-1.1-.9-2-2-2m-9 12.5H8c-.28 0-.5-.22-.5-.5v-3c0-.28.22-.5.5-.5h3c.28 0 .5.22.5.5v3c0 .28-.22.5-.5.5m0-5H8c-.28 0-.5-.22-.5-.5V8c0-.28.22-.5.5-.5h3c.28 0 .5.22.5.5v3c0 .28-.22.5-.5.5m5 5h-3c-.28 0-.5-.22-.5-.5v-3c0-.28.22-.5.5-.5h3c.28 0 .5.22.5.5v3c0 .28-.22.5-.5.5m0-5h-3c-.28 0-.5-.22-.5-.5V8c0-.28.22-.5.5-.5h3c.28 0 .5.22.5.5v3c0 .28-.22.5-.5.5");
}

</style>
