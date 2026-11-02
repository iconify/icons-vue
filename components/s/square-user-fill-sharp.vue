<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z9cjd2b-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-user-fill-sharp" /></template>
<style>
.z9cjd2b-t {
  fill: currentColor;
  d: path("M21 22H3a1 1 0 0 1-1-1V3a1 1 0 0 1 1-1h18a1 1 0 0 1 1 1v18a1 1 0 0 1-1 1M8.315 8.443a4 4 0 1 0 7.37 3.114a4 4 0 0 0-7.37-3.114M17.882 20c-.251-1.038-.893-1.946-1.722-2.609c-2.323-1.858-5.997-1.858-8.32 0c-.829.663-1.471 1.571-1.722 2.609Z");
}

</style>
