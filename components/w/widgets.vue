<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lcewj0s3w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:widgets" /></template>
<style>
.lcewj0s3w {
  fill: currentColor;
  d: path("m16.304 11.962l-4.227-4.227l4.227-4.227l4.227 4.227zM4.615 10.616v-6h6v6zm8.77 8.769v-6h6v6zm-8.77 0v-6h6v6z");
}

</style>
