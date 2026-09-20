<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j9ldb98hx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:side-navigation-outline-sharp" /></template>
<style>
.j9ldb98hx {
  fill: currentColor;
  d: path("M4 20V4h16v16zm8-1h7V5h-7z");
}

</style>
