<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n_fd13q9k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:star-half-24-filled" /></template>
<style>
.n_fd13q9k {
  fill: currentColor;
  d: path("M12 2.35c-.482 0-.964.25-1.212.752L8.43 7.88l-5.273.766c-1.107.16-1.55 1.522-.748 2.303l3.815 3.719l-.9 5.25c-.15.874.544 1.583 1.331 1.582c.208 0 .422-.05.63-.158l4.714-2.479z");
}

</style>
