<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="vflpv1bkl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:tag-edit-32-filled" /></template>
<style>
.vflpv1bkl {
  fill: currentColor;
  d: path("M15.636 3.952A3.25 3.25 0 0 1 17.934 3h7.818a3.25 3.25 0 0 1 3.25 3.25v7.45a4.38 4.38 0 0 0-5.49.594l-8.567 8.64a4.16 4.16 0 0 0-1.072 1.886l-.79 3.051a2.5 2.5 0 0 0-.063.953a3.2 3.2 0 0 1-1.246-.778l-7.818-7.818a3.25 3.25 0 0 1 0-4.596zM23 11a2 2 0 1 0 0-4a2 2 0 0 0 0 4m5.644 8.424l-8.61 8.544a2.8 2.8 0 0 1-1.269.72l-3.02.779a1 1 0 0 1-1.216-1.22l.79-3.051a2.66 2.66 0 0 1 .686-1.206l8.567-8.64a2.88 2.88 0 0 1 4.144.057a2.88 2.88 0 0 1-.072 4.017");
}

</style>
