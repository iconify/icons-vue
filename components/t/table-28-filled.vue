<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="pds4yjb0s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:table-28-filled" /></template>
<style>
.pds4yjb0s {
  fill: currentColor;
  d: path("M3 6.75A3.75 3.75 0 0 1 6.75 3H9.5v6.5H3zM3 11v6h6.5v-6zm0 7.5v2.75A3.75 3.75 0 0 0 6.75 25H9.5v-6.5zm8 6.5h6v-6.5h-6zm7.5 0h2.75A3.75 3.75 0 0 0 25 21.25V18.5h-6.5zm6.5-8v-6h-6.5v6zm0-7.5V6.75A3.75 3.75 0 0 0 21.25 3H18.5v6.5zM17 3h-6v6.5h6zm0 8v6h-6v-6z");
}

</style>
