<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mv2p8bb7z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:security-camera-fill" /></template>
<style>
.mv2p8bb7z {
  fill: currentColor;
  d: path("M2.789 9.398A3 3 0 0 1 4.91 5.723l11.591-3.106a3 3 0 0 1 3.675 2.122l1.035 3.863a3 3 0 0 1-2.121 3.675L13 13.908V16h5a1 1 0 0 1 2 0v5a1 1 0 0 1-2 0v-3h-6a1 1 0 0 1-1-1v-2.556l-3.501.939a3 3 0 0 1-3.675-2.122ZM16.571 6.74a1 1 0 0 0-1.226-.706a1 1 0 0 0-.706 1.224l.518 1.931a1 1 0 1 0 1.931-.517Zm-5.163 7.595l.702-.188c-.25-.027-.5.04-.702.188");
}

</style>
