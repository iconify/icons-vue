<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x2g7jji_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-contact-emergency" /></template>
<style>
.x2g7jji_p {
  fill: currentColor;
  d: path("M23.99 3H0v18h23.99zM9 8c1.65 0 3 1.35 3 3s-1.35 3-3 3s-3-1.35-3-3s1.35-3 3-3M2.08 19c1.38-2.39 3.96-4 6.92-4s5.54 1.61 6.92 4zm18.89-9.15l-.75 1.3l-1.47-.85V12h-1.5v-1.7l-1.47.85l-.75-1.3L16.5 9l-1.47-.85l.75-1.3l1.47.85V6h1.5v1.7l1.47-.85l.75 1.3L19.5 9z");
}

</style>
