<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bg__msbli"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:timer-10-sharp" /></template>
<style>
.bg__msbli {
  fill: currentColor;
  d: path("M12.827 16.885h4.77v-9.77h-4.77zm-1.23 1.23V5.886h7.23v12.23zm-4 0v-11H5.191v-1.23h3.635v12.23z");
}

</style>
