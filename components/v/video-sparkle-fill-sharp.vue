<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vjg2jubma"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:video-sparkle-fill-sharp" /></template>
<style>
.vjg2jubma {
  fill: currentColor;
  d: path("M2 18V6a1 1 0 0 1 1-1h12a1 1 0 0 1 1 1v2.382l4.553-2.276A1 1 0 0 1 22 7v10a1 1 0 0 1-1.447.894L16 15.618V18a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1m3.989-7.001L5.986 11a1 1 0 0 0 0 2l.003.001c.134.028.261.107.375.177a4.9 4.9 0 0 1 1.458 1.458c.07.114.149.241.177.375l.001.003a1 1 0 0 0 2 0l.001-.003c.028-.134.107-.261.177-.375a4.9 4.9 0 0 1 1.458-1.458c.114-.07.241-.149.375-.177l.003-.001a1 1 0 0 0 0-2l-.003-.001c-.134-.028-.261-.107-.375-.177a4.9 4.9 0 0 1-1.458-1.458c-.07-.114-.149-.241-.177-.375L10 8.986a1 1 0 0 0-2 0l-.001.003c-.028.134-.107.261-.177.375a4.9 4.9 0 0 1-1.458 1.458c-.114.07-.241.149-.375.177M16 13.382l4 2V8.618l-4 2Z");
}

</style>
