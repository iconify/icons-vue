<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":149};
const content = `<path class="x3kf55g8h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:pipecat" /></template>
<style>
.x3kf55g8h {
  d: path("M220.706.594a9.25 9.25 0 0 1 5.993 8.66V92.53H256v18.506h-47.807V33.83l-19.647 22.393a9.25 9.25 0 0 1-6.956 3.151H74.41a9.25 9.25 0 0 1-6.956-3.15L47.807 33.83v77.207H0V92.53h29.301V9.253A9.253 9.253 0 0 1 45.51 3.151L78.6 40.868h98.798L210.49 3.151A9.25 9.25 0 0 1 220.706.594M86.362 86.362c6.813 0 12.337 5.524 12.337 12.338s-5.524 12.337-12.337 12.337c-6.814 0-12.338-5.524-12.338-12.337c0-6.814 5.524-12.338 12.338-12.338m83.276 0c6.814 0 12.338 5.524 12.338 12.338s-5.524 12.337-12.338 12.337s-12.337-5.524-12.337-12.337c0-6.814 5.524-12.338 12.337-12.338m38.555 43.18H256v18.507h-47.807zM0 129.543h47.807v18.507H0z");
}

</style>
