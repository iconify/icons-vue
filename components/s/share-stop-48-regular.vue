<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="za5ospb5r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:share-stop-48-regular" /></template>
<style>
.za5ospb5r {
  fill: currentColor;
  d: path("m22.232 24l-5.866-5.866a1.25 1.25 0 0 1 1.768-1.768L24 22.232l5.866-5.866a1.25 1.25 0 0 1 1.768 1.768L25.768 24l5.866 5.866a1.25 1.25 0 0 1-1.768 1.768L24 25.768l-5.866 5.866a1.25 1.25 0 0 1-1.768-1.768zM4 12.75A4.75 4.75 0 0 1 8.75 8h30.5A4.75 4.75 0 0 1 44 12.75v22.5A4.75 4.75 0 0 1 39.25 40H8.75A4.75 4.75 0 0 1 4 35.25zm4.75-2.25a2.25 2.25 0 0 0-2.25 2.25v22.5a2.25 2.25 0 0 0 2.25 2.25h30.5a2.25 2.25 0 0 0 2.25-2.25v-22.5a2.25 2.25 0 0 0-2.25-2.25z");
}

</style>
