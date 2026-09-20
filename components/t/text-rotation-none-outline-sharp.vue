<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ly4_mp06s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:text-rotation-none-outline-sharp" /></template>
<style>
.ly4_mp06s {
  fill: currentColor;
  d: path("M4.5 18.5v-1h13.892l-1.55-1.55l.708-.708L20.308 18l-2.758 2.758l-.708-.708l1.55-1.55zm3.112-4.846l3.907-10.308h1l3.831 10.308h-1.016l-1.026-2.838H9.666l-1.039 2.838zm2.372-3.708h3.993l-1.908-5.28h-.1z");
}

</style>
