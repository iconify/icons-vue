<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eru3ubclo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:settings-cell-outline" /></template>
<style>
.eru3ubclo {
  fill: currentColor;
  d: path("M8 23.77q-.31 0-.54-.23T7.23 23t.23-.54t.54-.23t.54.23t.23.54t-.23.54t-.54.23m4 0q-.31 0-.54-.23t-.23-.54t.23-.54t.54-.23t.54.23t.23.54t-.23.54t-.54.23m4 0q-.31 0-.54-.23t-.23-.54t.23-.54t.54-.23t.54.23t.23.54t-.23.54t-.54.23M8.423 19q-.69 0-1.153-.462t-.462-1.153V2.615q0-.69.462-1.152T8.423 1h7.154q.69 0 1.153.463t.462 1.152v14.77q0 .69-.462 1.152T15.577 19zm0-1h7.154q.27 0 .442-.173q.173-.173.173-.442V16.5H7.808v.885q0 .269.173.442t.442.173m-.615-2.5h8.384v-11H7.808zm0-12h8.384v-.885q0-.269-.173-.442T15.577 2H8.423q-.27 0-.442.173q-.173.173-.173.443zm0 0V2zm0 14.5v-1.5z");
}

</style>
