<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="p579235wp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-list-filter-fill" /></template>
<style>
.p579235wp {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M18 2C20.209 2 22 3.791 22 6V18C22 20.209 20.209 22 18 22H6C3.791 22 2 20.209 2 18V6C2 3.791 3.791 2 6 2H18ZM11 15C10.448 15 10 15.448 10 16C10 16.552 10.448 17 11 17H13C13.552 17 14 16.552 14 16C14 15.448 13.552 15 13 15H11ZM9.5 11C8.948 11 8.5 11.448 8.5 12C8.5 12.552 8.948 13 9.5 13H14.5C15.052 13 15.5 12.552 15.5 12C15.5 11.448 15.052 11 14.5 11H9.5ZM8 7C7.448 7 7 7.448 7 8C7 8.552 7.448 9 8 9H16C16.552 9 17 8.552 17 8C17 7.448 16.552 7 16 7H8Z");
}

</style>
