<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vh7xp39bg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:speed-0-5" /></template>
<style>
.vh7xp39bg {
  fill: currentColor;
  d: path("M7.75 16.5v-1h1v1zm2.5 0v-1h3.385q.269 0 .442-.173t.173-.442v-1.77q0-.269-.173-.442t-.442-.173H10.25v-5h5v1h-4v3h2.385q.69 0 1.152.463t.463 1.153v1.769q0 .69-.462 1.153t-1.153.462z");
}

</style>
