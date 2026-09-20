<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="agkb49b-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:turn-right-outline-sharp" /></template>
<style>
.agkb49b-d {
  fill: currentColor;
  d: path("M7.48 19V9.5h10.605l-2.1-2.1l.707-.708L20 10l-3.308 3.308l-.707-.708l2.1-2.1H8.48V19z");
}

</style>
