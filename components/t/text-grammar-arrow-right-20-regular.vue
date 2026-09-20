<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="v-6ir3q6o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-grammar-arrow-right-20-regular" /></template>
<style>
.v-6ir3q6o {
  fill: currentColor;
  d: path("M17.5 5a.5.5 0 0 1 0 1h-15a.5.5 0 0 1 0-1zm0 3a.5.5 0 0 1 0 1h-15a.5.5 0 0 1 0-1zm-7.243 3a5.5 5.5 0 0 0-.657 1H2.5a.5.5 0 0 1 0-1zM9 14.5q0 .252.022.5H2.5a.5.5 0 0 1 0-1h6.522a6 6 0 0 0-.022.5m10 0a4.5 4.5 0 1 0-9 0a4.5 4.5 0 0 0 9 0m-4.146 2.354a.5.5 0 0 1-.708-.708L15.293 15H12.5a.5.5 0 0 1 0-1h2.793l-1.147-1.146a.5.5 0 0 1 .708-.708l2 2a.5.5 0 0 1 .146.351v.006a.5.5 0 0 1-.144.348l-.003.003z");
}

</style>
