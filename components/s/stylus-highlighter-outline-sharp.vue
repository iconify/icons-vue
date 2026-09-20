<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g201h1q2t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:stylus-highlighter-outline-sharp" /></template>
<style>
.g201h1q2t {
  fill: currentColor;
  d: path("M7.673 15.308V4h1.994l6.64 3.244v8.064zm1-1h6.635v-6.43L9.442 5h-.769zM5 20l.827-2.308h12.346L19 20zm3.673-5.692h6.635z");
}

</style>
