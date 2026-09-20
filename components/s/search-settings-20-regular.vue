<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="uuelxrb5h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:search-settings-20-regular" /></template>
<style>
.uuelxrb5h {
  fill: currentColor;
  d: path("M4.07 10.82a2 2 0 0 0 2.91 0l.324-.343q.447.212.835.518l-.126.422a2 2 0 0 0 1.456 2.518l.348.084a4.7 4.7 0 0 1 .011 1.016l-.46.117a2 2 0 0 0-1.431 2.479l.156.556a4.3 4.3 0 0 1-.822.498l-.337-.358a2 2 0 0 0-2.91-.002l-.325.345a4.3 4.3 0 0 1-.835-.519l.126-.422a2 2 0 0 0-1.456-2.519l-.35-.083a4.7 4.7 0 0 1-.01-1.016l.462-.118a2 2 0 0 0 1.43-2.477l-.156-.558q.383-.293.822-.497zM9.5 3a6.5 6.5 0 0 1 4.937 10.73l3.417 3.416a.5.5 0 0 1-.638.765l-.07-.058l-3.417-3.417a6.5 6.5 0 0 1-2.881 1.422q.124-.516.146-1.065a5.5 5.5 0 0 0 2.733-1.773a5.5 5.5 0 1 0-9.722-3.74q-.525.148-1.001.392Q3 9.586 3 9.5A6.5 6.5 0 0 1 9.5 3M5.501 13.573a1 1 0 1 0 0 2.001a1 1 0 0 0 0-2");
}

</style>
