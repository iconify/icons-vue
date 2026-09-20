<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m9ux19k0s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:mobiledata-arrows-sharp" /></template>
<style>
.m9ux19k0s {
  fill: currentColor;
  d: path("M8.5 9.09h1v8.983l2.089-2.089l.719.708L9 20l-3.308-3.308l.72-.707L8.5 18.073zm7 4.385h-1v-7.56l-2.1 2.1l-.708-.707L15 4l3.308 3.308l-.708.708l-2.1-2.1z");
}

</style>
