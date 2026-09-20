<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zhavzk43w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:variable-insert" /></template>
<style>
.zhavzk43w {
  fill: currentColor;
  d: path("M4 16V8h16v3.192h-5.423V16zm17.677 3l-3.715-3.71v3.21h-1v-4.923h4.923v1h-3.216l3.697 3.735z");
}

</style>
