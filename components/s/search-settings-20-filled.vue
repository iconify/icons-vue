<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="npyo5cbdo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:search-settings-20-filled" /></template>
<style>
.npyo5cbdo {
  fill: currentColor;
  d: path("M4.07 10.82a2 2 0 0 0 2.91 0l.324-.343q.447.212.835.518l-.126.422a2 2 0 0 0 1.456 2.518l.348.084a4.7 4.7 0 0 1 .011 1.016l-.46.117a2 2 0 0 0-1.431 2.479l.156.556a4.3 4.3 0 0 1-.822.498l-.337-.358a2 2 0 0 0-2.91-.002l-.325.345a4.3 4.3 0 0 1-.835-.519l.126-.422a2 2 0 0 0-1.456-2.519l-.35-.083a4.7 4.7 0 0 1-.01-1.016l.462-.118a2 2 0 0 0 1.43-2.477l-.156-.558q.383-.293.822-.497zM9.5 3a6.5 6.5 0 0 1 5.096 10.535l3.434 3.435a.75.75 0 0 1-.976 1.133l-.084-.073l-3.435-3.434a6.5 6.5 0 0 1-2.688 1.263a5.5 5.5 0 0 0 .144-1.586A5.002 5.002 0 0 0 9.5 4.5a5 5 0 0 0-4.988 4.663c-.534.097-1.04.27-1.508.509Q3 9.586 3 9.5A6.5 6.5 0 0 1 9.5 3M5.501 13.573a1 1 0 1 0 0 2.001a1 1 0 0 0 0-2");
}

</style>
