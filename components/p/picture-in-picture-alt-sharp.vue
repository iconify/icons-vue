<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jk0i7owuz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:picture-in-picture-alt-sharp" /></template>
<style>
.jk0i7owuz {
  fill: currentColor;
  d: path("M3 19V5h18v14zm8.308-2.039H19V11.27h-7.692zm3.846-2.845");
}

</style>
