<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="khq-hufki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:unarchive-sharp" /></template>
<style>
.khq-hufki {
  fill: currentColor;
  d: path("m12 10l-4 4l1.4 1.4l1.6-1.6V18h2v-4.2l1.6 1.6L16 14zM3 21V5.8L5.3 3h13.4L21 5.8V21zM5.4 6h13.2l-.85-1H6.25z");
}

</style>
