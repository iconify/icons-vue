<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="izvtx9biz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:stylus-pen-sharp" /></template>
<style>
.izvtx9biz {
  fill: currentColor;
  d: path("m6 16l2.5-9H10V5.5L11.5 2h1L14 5.5V7h1.5l2.5 9zm-2 5l1-3h14l1 3z");
}

</style>
