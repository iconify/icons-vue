<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r17vrp05l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:thumbs-up-fill-sharp" /></template>
<style>
.r17vrp05l {
  fill: currentColor;
  d: path("M8 22V8.83A3.01 3.01 0 0 0 10 6V5a3 3 0 1 1 6 0v4h5a1 1 0 0 1 1 1v4q0 .14-.038.275l-2 7A1 1 0 0 1 19 22Zm-2 0H3a1 1 0 0 1-1-1V10a1 1 0 0 1 1-1h3Z");
}

</style>
