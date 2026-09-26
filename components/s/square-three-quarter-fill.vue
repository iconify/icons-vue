<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="irrintbde"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-three-quarter-fill" /></template>
<style>
.irrintbde {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2 6C2 3.79086 3.79086 2 6 2H18C20.2091 2 22 3.79086 22 6V18C22 20.2091 20.2091 22 18 22H6C3.79086 22 2 20.2091 2 18V6ZM12 6L15.5 6C16.8807 6 18 7.1193 18 8.5L18 15.5C18 16.8807 16.8807 18 15.5 18L8.5 18C7.1193 18 6 16.8807 6 15.5L6 12C6 11.4477 6.4477 11 7 11L11 11L11 7C11 6.4477 11.4477 6 12 6Z");
}

</style>
