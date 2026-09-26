<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jlv7qya0l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-align-offset-top-fill" /></template>
<style>
.jlv7qya0l {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M18 2C20.2091 2 22 3.79086 22 6V18C22 20.2091 20.2091 22 18 22H6C3.79086 22 2 20.2091 2 18V6C2 3.79086 3.79086 2 6 2H18ZM14 15C13.4477 15 13 15.4477 13 16C13 16.5523 13.4477 17 14 17H16C16.5523 17 17 16.5523 17 16C17 15.4477 16.5523 15 16 15H14ZM9 11C8.44772 11 8 11.4477 8 12C8 12.5523 8.44772 13 9 13H16C16.5523 13 17 12.5523 17 12C17 11.4477 16.5523 11 16 11H9ZM8 7C7.44772 7 7 7.44772 7 8C7 8.55228 7.44772 9 8 9H13C13.5523 9 14 8.55228 14 8C14 7.44772 13.5523 7 13 7H8Z");
}

</style>
