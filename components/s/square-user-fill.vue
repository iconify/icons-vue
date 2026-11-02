<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hyhh94b5h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-user-fill" /></template>
<style>
.hyhh94b5h {
  fill: currentColor;
  d: path("M19 22H5a3 3 0 0 1-3-3V5a3 3 0 0 1 3-3h14a3 3 0 0 1 3 3v14a3 3 0 0 1-3 3M8.315 8.443a4 4 0 1 0 7.37 3.114a4 4 0 0 0-7.37-3.114M17.882 20c-.251-1.038-.893-1.946-1.722-2.609c-2.323-1.858-5.997-1.858-8.32 0c-.829.663-1.471 1.571-1.722 2.609Z");
}

</style>
