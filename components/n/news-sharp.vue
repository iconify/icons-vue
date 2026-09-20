<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fynhpk7ir"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:news-sharp" /></template>
<style>
.fynhpk7ir {
  fill: currentColor;
  d: path("M4 20V4h11.577L20 8.423V20zM15 5v4h4zM7.5 16h9v-1h-9zm0-7H12V8H7.5zm0 3.5h9v-1h-9z");
}

</style>
