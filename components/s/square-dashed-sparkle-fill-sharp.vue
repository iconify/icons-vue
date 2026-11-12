<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xg5fbnbyu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-dashed-sparkle-fill-sharp" /></template>
<style>
.xg5fbnbyu {
  fill: currentColor;
  d: path("M4 4v3a1 1 0 0 1-2 0V3a1 1 0 0 1 1-1h4a1 1 0 0 1 0 2Zm9-2a1 1 0 0 1 0 2h-2a1 1 0 0 1 0-2Zm8 0a1 1 0 0 1 1 1v4a1 1 0 0 1-2 0V4h-3a1 1 0 0 1 0-2ZM11 8a1 1 0 0 1 2 0c0 1.452 1.548 3 3 3a1 1 0 0 1 0 2c-.774 0-1.508.422-2.043.957a3.5 3.5 0 0 0-.707.997c-.153.328-.25.683-.25 1.046a1 1 0 0 1-2 0c0-.363-.097-.718-.25-1.046a3.5 3.5 0 0 0-.707-.997a3.5 3.5 0 0 0-.997-.707A2.5 2.5 0 0 0 8 13a1 1 0 0 1 0-2c1.452 0 3-1.548 3-3m-7 5a1 1 0 0 1-2 0v-2a1 1 0 0 1 2 0Zm16 0v-2a1 1 0 0 1 2 0v2a1 1 0 0 1-2 0M4 20h3a1 1 0 0 1 0 2H3a1 1 0 0 1-1-1v-4a1 1 0 0 1 2 0Zm16 0v-3a1 1 0 0 1 2 0v4a1 1 0 0 1-1 1h-4a1 1 0 0 1 0-2Zm-7 2h-2a1 1 0 0 1 0-2h2a1 1 0 0 1 0 2");
}

</style>
