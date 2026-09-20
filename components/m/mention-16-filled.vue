<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="vcp45904r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:mention-16-filled" /></template>
<style>
.vcp45904r {
  fill: currentColor;
  d: path("M8 1a7 7 0 0 1 7 7l-.014.39c-.136 1.908-1.272 3.172-2.736 3.172c-.864 0-1.612-.44-2.11-1.193c-.583.687-1.422 1.131-2.39 1.131C5.89 11.5 4.5 9.864 4.5 8s1.39-3.5 3.25-3.5c.666 0 1.271.21 1.774.565A.748.748 0 0 1 11 5.248V8c0 1.625.812 2.063 1.25 2.063c.41 0 1.15-.385 1.241-1.772L13.5 8a5.5 5.5 0 1 0-3.677 5.188a.86.86 0 0 1 .893.18c.365.365.28.978-.201 1.164A7 7 0 1 1 8 1m-.25 5C6.85 6 6 6.827 6 8s.85 2 1.75 2S9.5 9.173 9.5 8s-.85-2-1.75-2");
}

</style>
