<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rt77pvbha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:speed-1-2-outline" /></template>
<style>
.rt77pvbha {
  fill: currentColor;
  d: path("M7.73 16.5v-8h-2v-1h3v9zm2.77 0v-1h1v1zm2.77 0h5v-1h-4v-2.384q0-.27.172-.443q.173-.173.442-.173h1.77q.69 0 1.153-.462t.462-1.154V9.115q0-.69-.462-1.153T16.654 7.5h-3.385v1h3.385q.269 0 .442.173t.173.443v1.769q0 .269-.173.442t-.442.173h-1.77q-.69 0-1.152.463t-.463 1.153z");
}

</style>
