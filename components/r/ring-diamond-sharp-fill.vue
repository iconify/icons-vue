<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o3facrfhx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:ring-diamond-sharp-fill" /></template>
<style>
.o3facrfhx {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M14.048 1C14.308 1.03 14.616 1.17 14.781 1.38L16.781 3.88C17.005 4.16 17.031 4.61 16.904 4.93L15.311 7.72C18.013 9 20 11.81 20 15C20 19.42 16.418 23 12 23C7.582 23 4 19.42 4 15C4 11.85 6.038 9.02 8.685 7.72L7.132 5C6.929 4.64 6.963 4.2 7.219 3.88L9.252 1.33C9.438 1.15 9.734 1 10 1H14.048ZM12 9C8.686 9 6 11.69 6 15C6 18.31 8.686 21 12 21C15.314 21 18 18.31 18 15C18 11.69 15.314 9 12 9Z");
}

</style>
