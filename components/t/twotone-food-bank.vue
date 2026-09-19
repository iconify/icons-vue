<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jrztbbczp"/><path class="ipfqzqb6s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-food-bank" /></template>
<style>
.ipfqzqb6s {
  fill: currentColor;
  d: path("m12 5.5l6 4.5v9H6v-9zM12 3L4 9v12h16V9zm-.5 6.5v3H11v-3h-1v3h-.5v-3h-1v3c0 .83.67 1.5 1.5 1.5v4h1v-4c.83 0 1.5-.67 1.5-1.5v-3zm1.5 2v3h1V18h1V9.5c-1.1 0-2 .9-2 2");
}

.jrztbbczp {
  fill: currentColor;
  d: path("m12 5.5l6 4.5v9H6v-9zm-.5 4v3H11v-3h-1v3h-.5v-3h-1v3c0 .83.67 1.5 1.5 1.5v4h1v-4c.83 0 1.5-.67 1.5-1.5v-3zm1.5 2v3h1V18h1V9.5c-1.1 0-2 .9-2 2");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
