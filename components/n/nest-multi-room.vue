<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bo4w__bep"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:nest-multi-room" /></template>
<style>
.bo4w__bep {
  fill: currentColor;
  d: path("m5 9.5l7-5.27l7 5.27zM5 20v-4.25h8.5V20zm9.5 0v-4.25H19V20zM5 14.75V10.5h4.5v4.25zm5.5 0V10.5H19v4.25z");
}

</style>
