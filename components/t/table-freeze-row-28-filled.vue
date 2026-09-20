<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="shk5uq8om"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:table-freeze-row-28-filled" /></template>
<style>
.shk5uq8om {
  fill: currentColor;
  d: path("M21.25 4.5a2.25 2.25 0 0 1 2.25 2.25V11h-5v6H25V6.75A3.75 3.75 0 0 0 21.25 3H6.75A3.75 3.75 0 0 0 3 6.75V17h6.5v-6h-5V6.75A2.25 2.25 0 0 1 6.75 4.5zM3 21.25V18.5h6.5V25H6.75A3.75 3.75 0 0 1 3 21.25M17 25h-6v-6.5h6zm4.25 0H18.5v-6.5H25v2.75A3.75 3.75 0 0 1 21.25 25M11 17h6v-6h-6z");
}

</style>
