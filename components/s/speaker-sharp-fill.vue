<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="thb22ebzm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:speaker-sharp-fill" /></template>
<style>
.thb22ebzm {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5 1L19 1C19.5523 1 20 1.4477 20 2L20 22C20 22.5523 19.5523 23 19 23L5 23C4.4477 23 4 22.5523 4 22L4 2C4 1.4477 4.4477 1 5 1ZM16 15C16 12.7909 14.2091 11 12 11C9.7909 11 8 12.7909 8 15C8 17.2091 9.7909 19 12 19C14.2091 19 16 17.2091 16 15ZM14 15C14 16.1046 13.1046 17 12 17C10.8954 17 10 16.1046 10 15C10 13.8954 10.8954 13 12 13C13.1046 13 14 13.8954 14 15ZM13.5 7C13.5 6.1716 12.8284 5.5 12 5.5C11.1716 5.5 10.5 6.1716 10.5 7C10.5 7.8284 11.1716 8.5 12 8.5C12.8284 8.5 13.5 7.8284 13.5 7Z");
}

</style>
