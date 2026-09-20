<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g_5sm9s0l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:stop-screen-share" /></template>
<style>
.g_5sm9s0l {
  fill: currentColor;
  d: path("m21.192 22.608l-3.146-3.146H1.77v-1h15.272l-1-1H4.616q-.691 0-1.153-.463T3 15.846V6.042q0-.327.173-.586q.173-.26.442-.414L1.392 2.808L2.1 2.1l19.8 19.8zM10.077 11.485l-.787-.793q-.201.225-.361.59q-.16.366-.16.834v2h1v-1.804q0-.27.077-.462t.231-.365m10.046 5.788L14.04 11.19l1.037-1.074l-1.808-1.808v1.308h-.804L7.312 4.462h12.073q.69 0 1.152.462T21 6.077v9.77q0 .419-.209.81q-.208.391-.668.616");
}

</style>
