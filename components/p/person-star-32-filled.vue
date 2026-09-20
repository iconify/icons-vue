<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="g47lm-bph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:person-star-32-filled" /></template>
<style>
.g47lm-bph {
  fill: currentColor;
  d: path("M15 16a7 7 0 1 0 0-14a7 7 0 0 0 0 14m-8.5 2A3.5 3.5 0 0 0 3 21.5v.5c0 2.393 1.523 4.417 3.685 5.793C8.859 29.177 11.802 30 15 30q1.118-.001 2.185-.13A8.98 8.98 0 0 1 14 23c0-1.85.558-3.57 1.516-5zm24 5a7.5 7.5 0 1 1-15 0a7.5 7.5 0 0 1 15 0m-8.212-4.862l-.94 2.828h-2.994c-.731 0-1.03.938-.434 1.361l2.406 1.707l-.929 2.792c-.228.687.555 1.267 1.146.848L23 25.931l2.457 1.743c.591.42 1.374-.16 1.146-.848l-.93-2.792l2.407-1.707c.597-.423.297-1.361-.434-1.361h-2.994l-.94-2.828c-.228-.684-1.196-.684-1.424 0");
}

</style>
