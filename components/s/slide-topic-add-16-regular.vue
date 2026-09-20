<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="cn4arccxm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:slide-topic-add-16-regular" /></template>
<style>
.cn4arccxm {
  fill: currentColor;
  d: path("M11.5 7a4.5 4.5 0 1 1 0 9a4.5 4.5 0 0 1 0-9m0 2a.5.5 0 0 0-.5.5V11H9.5a.5.5 0 0 0 0 1H11v1.5a.5.5 0 0 0 1 0V12h1.5a.5.5 0 0 0 0-1H12V9.5a.5.5 0 0 0-.5-.5m0-3c-1.177 0-2.266.37-3.16 1H3.5A1.5 1.5 0 0 0 2 8.5v3l.008.153A1.5 1.5 0 0 0 3.5 13h2.708q.149.524.394 1H3.5a2.5 2.5 0 0 1-2.487-2.244L1 11.5v-3A2.5 2.5 0 0 1 3.5 6zm-5.292 4a5.5 5.5 0 0 0-.185 1H3.5a.5.5 0 0 1 0-1zm1.05-2a5.5 5.5 0 0 0-.656 1H3.5a.5.5 0 0 1 0-1zM13.5 2a1.5 1.5 0 0 1 0 3h-11a1.5 1.5 0 1 1 0-3z");
}

</style>
