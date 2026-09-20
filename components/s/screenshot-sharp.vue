<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t6feptdzo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:screenshot-sharp" /></template>
<style>
.t6feptdzo {
  fill: currentColor;
  d: path("M15.308 15h-1v3.23h-3.231v1h4.23zM8.769 9h1V5.77H13v-1H8.77zM6 22V2h12.077v4.83H19v3.686h-.923V22z");
}

</style>
