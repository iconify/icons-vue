<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nage5tqoc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:tv-with-assistant-outline-rounded" /></template>
<style>
.nage5tqoc {
  fill: currentColor;
  d: path("M11.04 12.04q.23-.23.23-.54t-.23-.54t-.54-.23t-.54.23t-.23.54t.23.54t.54.23t.54-.23m3 0q.23-.23.23-.54t-.23-.54t-.54-.23t-.54.23t-.23.54t.23.54t.54.23t.54-.23m-6 0q.23-.23.23-.54t-.23-.54t-.54-.23t-.54.23t-.23.54t.23.54t.54.23t.54-.23m9 0q.23-.23.23-.54t-.23-.54t-.54-.23t-.54.23t-.23.54t.23.54t.54.23t.54-.23M5.675 18l-.492 1.304q-.031.073-.098.115q-.068.043-.146.043h-.073q-.104 0-.177-.073t-.073-.177V18q-.672 0-1.144-.472T3 16.385v-9.77q0-.67.472-1.143Q3.944 5 4.616 5h14.769q.67 0 1.143.472q.472.472.472 1.144v9.769q0 .67-.472 1.143q-.472.472-1.143.472v1.237q0 .104-.061.164t-.164.06h-.098q-.073 0-.14-.039q-.068-.04-.099-.112L18.369 18zm-1.06-1h14.77q.269 0 .442-.173t.173-.442v-9.77q0-.269-.173-.442T19.385 6H4.615q-.269 0-.442.173T4 6.616v9.769q0 .269.173.442t.443.173M12 11.5");
}

</style>
