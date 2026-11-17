<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rzole-bef"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:security-camera-fill-round" /></template>
<style>
.rzole-bef {
  fill: currentColor;
  d: path("M3.048 10.363a4 4 0 0 1 2.828-4.899l9.66-2.588a4 4 0 0 1 4.899 2.829l.517 1.932a4 4 0 0 1-2.828 4.899L13 13.908V16h5a1 1 0 0 1 2 0v5a1 1 0 0 1-2 0v-3h-6a1 1 0 0 1-1-1v-2.556l-2.536.68a4 4 0 0 1-4.899-2.829ZM16.571 6.74a1 1 0 0 0-1.226-.706a1 1 0 0 0-.706 1.224l.518 1.931a1 1 0 1 0 1.931-.517Zm-5.163 7.595l.702-.188c-.25-.027-.5.04-.702.188");
}

</style>
