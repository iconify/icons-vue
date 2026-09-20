<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k26hz5d2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:send-rounded" /></template>
<style>
.k26hz5d2u {
  fill: currentColor;
  d: path("M5.133 18.02q-.406.163-.77-.066T4 17.288v-3.942L9.846 12L4 10.654V6.712q0-.438.364-.666t.77-.067l12.512 5.269q.49.225.49.756q0 .53-.49.748z");
}

</style>
