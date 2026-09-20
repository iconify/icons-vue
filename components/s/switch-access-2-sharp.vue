<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lz707ibet"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:switch-access-2-sharp" /></template>
<style>
.lz707ibet {
  fill: currentColor;
  d: path("M13 20v-4h2v2h2v2zm6 0v-2h2v-2h2v4zM13 8V4h4v2h-2v2zm8 0V6h-2V4h4v4zm-4 8l-1.4-1.4l1.575-1.6H6v-2h11.175L15.6 9.4L17 8l4 4zM1 20V4h10v5H4v6h7v5z");
}

</style>
