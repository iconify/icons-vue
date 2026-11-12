<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tv3j0v99t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-dashed-sparkle-fill-round" /></template>
<style>
.tv3j0v99t {
  fill: currentColor;
  d: path("M5 4a.997.997 0 0 0-1 1v2a1 1 0 0 1-2 0V5a3 3 0 0 1 3-3h2a1 1 0 0 1 0 2Zm8-2a1 1 0 0 1 0 2h-2a1 1 0 0 1 0-2Zm6 0a3 3 0 0 1 3 3v2a1 1 0 0 1-2 0V5a1 1 0 0 0-1-1h-2a1 1 0 0 1 0-2Zm-8 6a1 1 0 0 1 2 0c0 1.452 1.548 3 3 3a1 1 0 0 1 0 2c-.774 0-1.508.422-2.043.957a3.5 3.5 0 0 0-.707.997c-.153.328-.25.683-.25 1.046a1 1 0 0 1-2 0c0-.363-.097-.718-.25-1.046a3.5 3.5 0 0 0-.707-.997a3.5 3.5 0 0 0-.997-.707A2.5 2.5 0 0 0 8 13a1 1 0 0 1 0-2c1.452 0 3-1.548 3-3m-7 5a1 1 0 0 1-2 0v-2a1 1 0 0 1 2 0Zm16 0v-2a1 1 0 0 1 2 0v2a1 1 0 0 1-2 0M4 19a1 1 0 0 0 1 1h2a1 1 0 0 1 0 2H5a3 3 0 0 1-3-3v-2a1 1 0 0 1 2 0Zm15 1a1 1 0 0 0 1-1v-2a1 1 0 0 1 2 0v2a3 3 0 0 1-3 3h-2a1 1 0 0 1 0-2Zm-6 2h-2a1 1 0 0 1 0-2h2a1 1 0 0 1 0 2");
}

</style>
