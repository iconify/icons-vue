<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="adrnk45uc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-add-location" /></template>
<style>
.adrnk45uc {
  fill: currentColor;
  d: path("M13 7c0-.55-.44-1-1-1c-.55 0-1 .44-1 1v2H9c-.55 0-1 .44-1 1c0 .55.44 1 1 1h2v2c0 .55.44 1 1 1c.55 0 1-.44 1-1v-2h2c.55 0 1-.44 1-1c0-.55-.44-1-1-1h-2zm-1-5c4.2 0 8 3.22 8 8.2c0 3.18-2.45 6.92-7.34 11.23c-.38.33-.95.33-1.33 0C6.45 17.12 4 13.38 4 10.2C4 5.22 7.8 2 12 2");
}

</style>
