<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gmdxivbim"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:trip-outline-sharp" /></template>
<style>
.gmdxivbim {
  fill: currentColor;
  d: path("M3 20V7h6V4h6v3h6v13zm7-13h4V5h-4zM7 8H4v11h3zm9 11V8H8v11zm1-11v11h3V8zm-5 5.5");
}

</style>
