<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o1u2c-bcj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:splitscreen-vertical-add-sharp" /></template>
<style>
.o1u2c-bcj {
  fill: currentColor;
  d: path("M4 20V4h6.635v16zm9.385 0V4H20v10.427q-.154-.021-.308-.032q-.153-.01-.307-.01q-2.075 0-3.538 1.455t-1.462 3.539q0 .166.015.316t.027.305zM19 22.23V20h-2.23v-1H19v-2.23h1V19h2.23v1H20v2.23z");
}

</style>
