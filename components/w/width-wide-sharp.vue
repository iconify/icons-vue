<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b8adwbbyw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:width-wide-sharp" /></template>
<style>
.b8adwbbyw {
  fill: currentColor;
  d: path("M3 19V5h18v14zm1-1h3V6H4zm13 0h3V6h-3z");
}

</style>
