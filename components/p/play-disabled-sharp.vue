<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tmcnvjbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:play-disabled-sharp" /></template>
<style>
.tmcnvjbeo {
  fill: currentColor;
  d: path("M16.45 13.6L8 5.15V5l11 7zm3.3 9L13 15.8L8 19v-8.2L1.4 4.2l1.4-1.4l18.4 18.4z");
}

</style>
