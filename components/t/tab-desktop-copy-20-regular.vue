<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="fvoknebtu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:tab-desktop-copy-20-regular" /></template>
<style>
.fvoknebtu {
  fill: currentColor;
  d: path("M7.5 2A2.5 2.5 0 0 0 5 4.5v8A2.5 2.5 0 0 0 7.5 15h8a2.5 2.5 0 0 0 2.5-2.5v-8A2.5 2.5 0 0 0 15.5 2zM17 4.5V5h-6.5a.5.5 0 0 1-.5-.5V3h5.5A1.5 1.5 0 0 1 17 4.5m-8 0A1.5 1.5 0 0 0 10.5 6H17v6.5a1.5 1.5 0 0 1-1.5 1.5h-8A1.5 1.5 0 0 1 6 12.5v-8A1.5 1.5 0 0 1 7.5 3H9zM12.5 18a2.5 2.5 0 0 0 2.45-2h-1.035a1.5 1.5 0 0 1-1.415 1H6a3 3 0 0 1-3-3V7.5a1.5 1.5 0 0 1 1-1.415V5.05A2.5 2.5 0 0 0 2 7.5V14a4 4 0 0 0 4 4z");
}

</style>
