<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y8tng0e6i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:text-heading-bold" /></template>
<style>
.y8tng0e6i {
  fill: currentColor;
  d: path("M19 1.25C19.4142 1.25 19.75 1.58579 19.75 2V22C19.75 22.4142 19.4142 22.75 19 22.75C18.5858 22.75 18.25 22.4142 18.25 22V12.75H5.75V22C5.75 22.4142 5.41421 22.75 5 22.75C4.58579 22.75 4.25 22.4142 4.25 22V2C4.25 1.58579 4.58579 1.25 5 1.25C5.41421 1.25 5.75 1.58579 5.75 2V11.25H18.25V2C18.25 1.58579 18.5858 1.25 19 1.25Z");
}

</style>
