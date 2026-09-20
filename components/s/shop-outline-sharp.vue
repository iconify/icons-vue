<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ia16deadi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:shop-outline-sharp" /></template>
<style>
.ia16deadi {
  fill: currentColor;
  d: path("M3 20V7h6V4h6v3h6v13zm1-1h16V8H4zm6-12h4V5h-4zM4 19V8zm6-1.923l5.577-3.577L10 9.923z");
}

</style>
