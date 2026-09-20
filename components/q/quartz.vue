<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pzylr5buw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:quartz" /></template>
<style>
.pzylr5buw {
  fill: var(--svg-color--fff, #fff);
  d: path("m3.9 16.95l-.9-.954l.936-.846H9.75l-4.5-4.5V9.3H6.6l4.5 4.603V7.95l.9-.9l.9.9v5.953L17.4 9.3h1.35v1.35l-4.5 4.5h5.85l.9.9l-.9.9h-6.75L12 15.6l-1.35 1.35z");
}

</style>
