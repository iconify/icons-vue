<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yyyp8vbtk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:mail-sparkle-corner-fill-round" /></template>
<style>
.yyyp8vbtk {
  fill: currentColor;
  d: path("M7.536 9.121L3.677 5.263A4.98 4.98 0 0 1 7 4h10c1.228 0 2.406.445 3.323 1.263l-3.859 3.858a3 3 0 0 1-2.121.879H9.657a3 3 0 0 1-2.121-.879M16.414 12l5.117-5.117c.31.664.47 1.384.469 2.117v2a1 1 0 0 1-1 1ZM2.469 6.883l3.652 3.653A5 5 0 0 0 9.657 12H12v7a1 1 0 0 1-1 1H7a5 5 0 0 1-5-5V9c0-.733.158-1.453.469-2.117m12.52 10.116c.134-.028.261-.107.375-.177a4.9 4.9 0 0 0 1.458-1.458c.07-.114.149-.241.177-.375l.001-.003a1 1 0 0 1 2 0l.001.003c.028.134.107.261.177.375a4.9 4.9 0 0 0 1.458 1.458c.114.07.241.149.375.177l.003.001a1 1 0 0 1 0 2l-.003.001c-.134.028-.261.107-.375.177a4.9 4.9 0 0 0-1.458 1.458c-.07.114-.149.241-.177.375l-.001.003a1 1 0 0 1-2 0l-.001-.003c-.028-.134-.107-.261-.177-.375a4.9 4.9 0 0 0-1.458-1.458c-.114-.07-.241-.149-.375-.177L14.986 19a1 1 0 0 1 0-2Z");
}

</style>
