<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="royq6abgh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:send-to-mobile-outline-sharp" /></template>
<style>
.royq6abgh {
  fill: currentColor;
  d: path("M8.692 11.48v1h4.689l-2.108 2.12l.708.708l3.327-3.327l-3.289-3.289l-.707.708l2.069 2.08zM6 22V2h12.077v4.83H19v3.686h-.923V22zm1-1h10.077V3H7zm0 0V3z");
}

</style>
