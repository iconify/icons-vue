<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jdk1rkbnz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:reload-warning-fill" /></template>
<style>
.jdk1rkbnz {
  fill: currentColor;
  d: path("M5.826 7H8a1 1 0 0 1 0 2H4a1 1 0 0 1-1-.986V4a1 1 0 0 1 2 0v.937a9.94 9.94 0 0 1 15.894 2.616a1 1 0 1 1-1.788.894a7.9 7.9 0 0 0-1.489-2.064A7.936 7.936 0 0 0 5.826 7M13 8v5a1 1 0 0 1-2 0V8a1 1 0 0 1 2 0m5.174 9H16a1 1 0 0 1 0-2h4a1 1 0 0 1 1 .986V20a1 1 0 0 1-2 0v-.937a9.94 9.94 0 0 1-15.894-2.616a1 1 0 1 1 1.788-.894A7.947 7.947 0 0 0 18.174 17M12 15h.01a1 1 0 0 1 0 2H12a1 1 0 0 1 0-2");
}

</style>
