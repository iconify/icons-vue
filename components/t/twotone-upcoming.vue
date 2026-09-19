<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r9os634fx"/><path class="rs0df3bcb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-upcoming" /></template>
<style>
.r9os634fx {
  fill: currentColor;
  d: path("M12 17c-2.04 0-3.81-1.24-4.58-3H4v5h16v-5h-3.42c-.77 1.76-2.54 3-4.58 3");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.rs0df3bcb {
  fill: currentColor;
  d: path("m21.16 7.26l-1.41-1.41l-3.56 3.55l1.41 1.41s3.45-3.52 3.56-3.55M11 3h2v5h-2zm9 9h-5c0 1.66-1.34 3-3 3s-3-1.34-3-3H4c-1.1 0-2 .9-2 2v5c0 1.1.9 2 2 2h16c1.1 0 2-.9 2-2v-5c0-1.1-.9-2-2-2m0 7H4v-5h3.42c.77 1.76 2.54 3 4.58 3s3.81-1.24 4.58-3H20zM6.4 10.81L7.81 9.4L4.26 5.84L2.84 7.26c.11.03 3.56 3.55 3.56 3.55");
}

</style>
