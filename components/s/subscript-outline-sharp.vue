<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t08qusbxb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:subscript-outline-sharp" /></template>
<style>
.t08qusbxb {
  fill: currentColor;
  d: path("M19 20v-3h3v-1h-3v-1h4v3h-3v1h3v1zM5.875 18l4.625-7.275L6.2 4h2.65l3.1 5h.1l3.075-5H17.8l-4.325 6.725L18.125 18H15.45l-3.4-5.425h-.1L8.55 18z");
}

</style>
