<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b87k-nb1k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:table-insert-left-24-regular" /></template>
<style>
.b87k-nb1k {
  fill: currentColor;
  d: path("M4.5 3.75a.75.75 0 0 0-1.5 0v16.5a.75.75 0 0 0 1.5 0zm4 0A.75.75 0 0 1 9.25 3h8.5A3.25 3.25 0 0 1 21 6.25v11.5A3.25 3.25 0 0 1 17.75 21h-8.5a.75.75 0 0 1-.75-.75zM10 10v4h4v-4zm0 5.5v4h4v-4zm5.5 0v4h2.25a1.75 1.75 0 0 0 1.75-1.75V15.5zm0-5.5v4h4v-4zm4-1.5V6.25a1.75 1.75 0 0 0-1.75-1.75H15.5v4zm-9.5-4v4h4v-4z");
}

</style>
