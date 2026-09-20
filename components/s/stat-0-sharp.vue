<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ti33s4bvw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:stat-0-sharp" /></template>
<style>
.ti33s4bvw {
  fill: currentColor;
  d: path("M12 17.577L6.423 12L12 6.423L17.577 12z");
}

</style>
