<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="twp7rymwc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:vertical-align-center-outline-sharp" /></template>
<style>
.twp7rymwc {
  fill: currentColor;
  d: path("M11 22v-4.2l-1.6 1.6L8 18l4-4l4 4l-1.4 1.4l-1.6-1.6V22zm-7-9v-2h16v2zm8-3L8 6l1.4-1.4L11 6.2V2h2v4.2l1.6-1.6L16 6z");
}

</style>
