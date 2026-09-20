<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s16qxqyse"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:work-outline-sharp" /></template>
<style>
.s16qxqyse {
  fill: currentColor;
  d: path("M3 20V7h6V4h6v3h6v13zm1-1h16V8H4zm6-12h4V5h-4zM4 19V8z");
}

</style>
