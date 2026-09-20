<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l1gu1ikhh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:speed-1-5-outline" /></template>
<style>
.l1gu1ikhh {
  fill: currentColor;
  d: path("M7.73 16.5v-8h-2v-1h3v9zm2.77 0v-1h1v1zm2.77 0v-1h3.384q.269 0 .442-.173t.173-.442v-1.77q0-.269-.173-.442t-.442-.173h-3.385v-5h5v1h-4v3h2.385q.69 0 1.153.463t.462 1.153v1.769q0 .69-.462 1.153t-1.16.462z");
}

</style>
